# ZK-SNARK-Designer
Based on the project rubric you provided, here's an outline of the tasks you need to complete:

1. **Write a correct circuit.circom implementation**:
   - Develop a correct implementation of the circuit in the circuit.circom file. This file defines the constraints and operations for your zero-knowledge proof (ZKP) circuit.

2. **Compile the circuit to generate circuit intermediaries**:
   - Use a suitable compiler (such as circom or snarkjs) to compile the circuit.circom file and generate the necessary circuit intermediaries, including the constraint system and the proving and verifying keys.

3. **Generate a proof using inputs A=0 B=1**:
   - With the compiled circuit and intermediaries, generate a proof using specific inputs. In this case, ensure that you generate a proof using A=0 and B=1 as inputs to the circuit.

4. **Deploy a solidity verifier to Sepolia or Mumbai Testnet**:
   - Develop a solidity verifier smart contract that verifies proofs generated by the circuit. Deploy this verifier contract to either the Sepolia or Mumbai Testnet using tools like Hardhat or Truffle.

5. **Call the verifyProof() method on the verifier contract and assert output is true**:
   - After deploying the verifier contract, write a script (using Hardhat, Truffle, or similar tools) to interact with the deployed contract.
   - Within your script, call the verifyProof() method on the deployed verifier contract, passing in the generated proof and the corresponding inputs.
   - Assert that the output of the verifyProof() method is true, indicating that the proof is valid and the inputs satisfy the constraints defined by the circuit.

Ensure that your circuit implementation and proof generation process are accurate and adhere to the requirements specified in the project rubric. Additionally, conduct thorough testing to verify the correctness and reliability of your implementation before deployment.
