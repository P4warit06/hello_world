Instruction  Perview 
# 2024 Chain Fusion Hacker House Devcon Bangkok

## Content

-   [Bounties](#bounties)
-   [Tracks](#tracks)
-   [Resources](#resources)
-   [Cycles](#cycles)
-   [How to Submit](#how-to-submit)
-   [Judging](#judging)
-   [Payout](#payout)

# Bounties

Throughout the hacker house, you'll have the opportunity to complete various Bounties that will progressively prepare you for larger challenges, with rewards ranging from $20 to $100 based on complexity. Bounties are designed to be small, well-defined, and time-sensitive, allowing you to apply what you’ve learned and earn as you go. Completing Bounties will also bring you closer to submitting a final project for one of the larger Tracks. Try to complete Bounties as quickly as possible, as there’s only a limited number available to claim.

## Easy Bounties – $25 Each

-   **Ask your mentor for cycles and deploy a canister smart contract on ICP (awarded 100 times)**: Claim a cycles coupon and deploy a simple "Hello World" backend canister on mainnet, including a frontend with specific functionalities:
    -   Modify the `greet` function to update call.
    -   Keep an array of all submitted `name` arguments in the canister and expose them through a `submittedNames` query method
    -   Add a button to display them in the frontend.
-   **Claim gas tokens and deploy a smart contract on [Bitfinity Network](https://bitfinity.network/) (awarded 100 times)**: For this Bounty, you will deploy a Solidity-based "Hello World" smart contract and integrate it with a frontend on the Internet Computer (ICP). Follow the instructions below to complete the Bounty.
    -   Create a Solidity smart contract with a `greet` function that should
        -   Take a string argument `name`.
        -   Return a greeting in the format: `"Hello, <name>"`.
        -   Each time `greet` is called, the contract should:
            -   Store the provided `name` in an array called `submittedNames`.
    -   Implement an endpoint in the smart contract that:
        -   Returns the `submittedNames` array.
        -   This endpoint should be accessible from the frontend to display all previously submitted names.
    -   Build a frontend on ICP to interact with the smart contract, including:
        -   An input field where users can enter the `name` argument and call the `greet` function.
        -   A button to retrieve and display the `submittedNames` array.
        -   Deploy the frontend on ICP, either by:
            -   Using an [asset canister](https://internetcomputer.org/docs/current/developer-docs/web-apps/application-frontends/existing-frontend), or
            -   Deploying via [Juno.build](https://juno.build/docs/guides/manual-deployment).
