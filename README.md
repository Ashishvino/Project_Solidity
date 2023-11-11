## Project_Solidity

## Introduction

I am embarking on a venture focused on stability, known as Metacrafters, in which I have crafted a token using the solidity language.

## Overview

I have brought into existence my own token, christened "Ash" and abbreviated as "Bur". Its total supply is meticulously tracked. If an individual mints some "Bur" tokens, they will be added to the overall supply. Conversely, if those tokens are burned, they will be subtracted from the total supply (provided there is sufficient balance).

## Configuration

To implement the solidity code, I solely utilized the Online Remix IDE. Subsequently, to publish the same code on GitHub, I created a file named Sur.sol within this repository.

## Program Execution

For code execution, I employed remix.ide.

## Operational Functionality

Here's a step-by-step guide:

Commence by creating a new folder.

If the Remix tool is configured to automatically compile and execute your code, it will do so seamlessly. Alternatively, you can manually select the "Compile and Run" option from the menu.

Upon successful compilation, deploy the contract to acquire the account address for the subsequent steps.

4. A confirmation message will appear, indicating that the deployment process has been completed successfully.

5. Initially, the account balance will be set to zero.

To mint tokens, click the "Mint" button. Next, paste your account address and enter the desired quantity of tokens (900). Click "Transact" to add them to your account.

To verify your balance, click "Balances" and paste your account address. Click "Call" to view your balance.

If you need to check the token supply, there should be an option for that purpose.

To burn tokens from your account, click "Burn", paste your account address, specify the number of tokens you wish to burn (500), and click "Transact" to reduce them from your account.

After burning tokens, reassess your balance by pressing "Call" to obtain an updated balance (e.g., if you burned 500 tokens from a 900 token balance, you should now have 400 tokens remaining).

## AUTHORS

Ashish Burbure

## License

This project is licensed under the [MIT] License - refer to the LICENSE.md file for details
