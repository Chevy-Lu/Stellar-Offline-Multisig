# Stellar-Offline-Multisig
Standalone Stellar Network Offline Multisig Tool packaged alongside Ian Coleman's BIP39 Mnemonic Code Converter.

Multisig is an added security layer to your wallet, requiring extra signatures for transactions to be validated by the network.

>DISCLAIMER: Use this tool at your own risk. I am not liable for any missuse or loss of any kind you may inquire while using this tool.
This software is licensed under the [MIT LICENSE](https://github.com/Chevy-Lu/Stellar-Transaction-Submitter/blob/main/LICENSE).

## Uses:

- Access to all your keypairs.
- Ability to multisig transactions in an offline environment.

## Benefits:

- Enables the user to be their own multisig service provider.
- Set up multisig with your own keypair, not one by a third party generated in a connected environment.
- A wallet with multisig enabled will keep your funds safe even if your wallet gets compromised.
- This is a satandalone tool, it can run just using an internet browser.

## Screenshots:

![Screenshot from 2024-04-08 08-20-58](https://github.com/Chevy-Lu/Stellar-Offline-Multisig/assets/31299824/5e3b87c8-9759-4e4d-9ff7-e9de50d2a49b)

![Screenshot from 2024-04-08 08-23-15](https://github.com/Chevy-Lu/Stellar-Offline-Multisig/assets/31299824/cdc8b827-1a27-40e6-a9a4-9b47a972de01)


## How to enable multisig in your wallet

WARNING: Make sure you have the secret key to the public key being added as a second signer. Otherwise your account will be locked indefinitely.
You can get keypairs using the [Stellar Offline Multisig Tool](https://github.com/Chevy-Lu/Stellar-Offline-Multisig/releases) in an offline environment or a hardware wallet in air-gapped mode then wipe the device after recording your new seed phrase. Then in an offline computer e.g. [Tails OS](https://tails.net/) input your new seed phrase into the [Stellar Offline Multisig Tool](https://github.com/Chevy-Lu/Stellar-Offline-Multisig/releases) to get your keypairs. Is a good practice enabling multisig to a wallet with little funds until a successful test transaction has been achieved. Do not add a signature from the same seed phrase as the wallet, doing so defeats the purpose of multisig.



### Using StellarX

#

![stellarx-banner](https://github.com/Chevy-Lu/Stellar-Offline-Multisig/assets/31299824/168b8504-1760-4bc2-b097-b7f0c33ae495)

![Screenshot from 2024-04-08 19-49-44](https://github.com/Chevy-Lu/Stellar-Offline-Multisig/assets/31299824/6c867616-67a7-4de0-b50b-6486e466984c)

![Screenshot from 2024-04-08 19-50-49](https://github.com/Chevy-Lu/Stellar-Offline-Multisig/assets/31299824/d4c64193-616a-40a5-813a-326ebb9f30bf)

![Screenshot from 2024-04-08 19-52-40](https://github.com/Chevy-Lu/Stellar-Offline-Multisig/assets/31299824/09d34f85-0466-4cd5-a4ec-cadb0761649f)

![Screenshot from 2024-04-08 19-53-01](https://github.com/Chevy-Lu/Stellar-Offline-Multisig/assets/31299824/4c81e306-8d47-4cf4-8a84-266ca8d242ae)

![Screenshot from 2024-04-08 19-54-08](https://github.com/Chevy-Lu/Stellar-Offline-Multisig/assets/31299824/929614b4-f74f-443d-8be1-61dee0235e78)

### Using Lobstr Wallet

#

![lobstr-wallet-banner](https://github.com/Chevy-Lu/Stellar-Offline-Multisig/assets/31299824/aa9728ef-8b06-4607-98ff-247d18b7be08)

#

![Screenshot from 2024-04-08 01-20-21](https://github.com/Chevy-Lu/Stellar-Offline-Multisig/assets/31299824/5febf202-ab92-45f5-a953-31b5287707da)

![Screenshot from 2024-04-08 01-27-19](https://github.com/Chevy-Lu/Stellar-Offline-Multisig/assets/31299824/c0a4abc3-8206-4309-8afb-982f710a47b0)

![Screenshot from 2024-04-08 03-20-33](https://github.com/Chevy-Lu/Stellar-Offline-Multisig/assets/31299824/0729c26c-4374-424d-bdb8-cc6a7c854a85)

![Screenshot from 2024-04-08 03-21-15](https://github.com/Chevy-Lu/Stellar-Offline-Multisig/assets/31299824/7315d1a3-2468-4c19-9e05-e120850b6761)

![Screenshot from 2024-04-08 03-22-45](https://github.com/Chevy-Lu/Stellar-Offline-Multisig/assets/31299824/591dd18d-03ca-4d40-8467-75f81c3cf6b9)

#

## Signing Transactions 

Now that you have multisig enabled in your wallet every single time you send a transaction you'll be presented with a pre-signed transaction XDR. This is what you need to input into the [Stellar Offline Multisig Tool](https://github.com/Chevy-Lu/Stellar-Offline-Multisig/releases) in order to sign it offline with your extra signature.

This is how a transaction XDR looks like:

![Screenshot from 2024-04-08 19-59-14](https://github.com/Chevy-Lu/Stellar-Offline-Multisig/assets/31299824/da924f6a-f149-4f34-b211-03f94ab08d49)

Copy & Paste it into the "Transaction XDR:" textarea and sign.

![Screenshot from 2024-04-08 20-00-22](https://github.com/Chevy-Lu/Stellar-Offline-Multisig/assets/31299824/ae6869dc-324e-4a09-9f11-29bea1b22fb4)

## Submitting Transactions to the Network
Copy your signed transaction XDR and paste it into the [Stellar Transaction Submitter Tool](https://github.com/Chevy-Lu/Stellar-Transaction-Submitter) and submit. Transaction feedback can take up to six seconds.

![Screenshot from 2024-04-08 20-02-03](https://github.com/Chevy-Lu/Stellar-Offline-Multisig/assets/31299824/f0da531f-884f-416a-bbd8-ab846460ac1f)

