# Medical Insurance DApp

## Problem Statement

The challenge at hand is to create a Decentralized Application (DApp) for managing medical insurance claims within the ConsenSys ecosystem. The process involves several key steps:

1. **Patient Interaction:**
   - Patients log in to the system, where they can upload their medical and lab test bills for insurance claims.
   - The system generates notifications to inform the hospital and lab administrators about these submissions.

2. **Hospital Administrator's Role:**
   - Hospital administrators access the system and review the submitted bills.
   - After verification, they approve the bills, and this approval status is securely recorded on the blockchain through a smart contract.

3. **Lab Administrator's Role:**
   - Lab administrators also log in to the system and review the lab test bills.
   - Upon verification, they provide their approval, which is likewise recorded on the blockchain through the smart contract.

4. **Insurance Administrator's Role:**
   - The insurance administrator enters the picture once both the hospital and lab approvals are secured.
   - The insurance administrator verifies these approvals on the blockchain.
   - After confirming all necessary approvals, they calculate the final claim amount.

5. **Smart Contract - HealthCare.sol:**
   - The core logic for managing this DApp resides within the HealthCare.sol smart contract.

6. **Web-based User Interface:**
   - A user-friendly web application, located in the Web-client folder, serves as the interface for users.
   - Users can securely log in with their respective roles (patient, hospital admin, lab admin, insurance admin).
   - This interface facilitates communication with the deployed smart contract, ensuring a seamless user experience.
