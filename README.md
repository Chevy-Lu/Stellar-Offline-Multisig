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

#

### Using Lobstr Wallet

#

![lobstr-wallet-banner](https://github.com/Chevy-Lu/Stellar-Offline-Multisig/assets/31299824/aa9728ef-8b06-4607-98ff-247d18b7be08)

#

![Screenshot from 2024-04-08 01-20-21](https://github.com/Chevy-Lu/Stellar-Offline-Multisig/assets/31299824/5febf202-ab92-45f5-a953-31b5287707da)

![Screenshot from 2024-04-08 01-27-19](https://github.com/Chevy-Lu/Stellar-Offline-Multisig/assets/31299824/c0a4abc3-8206-4309-8afb-982f710a47b0)

![Screenshot from 2024-04-08 03-18-54](https://github.com/Chevy-Lu/Stellar-Offline-Multisig/assets/31299824/c7d1d9a5-54a2-42d9-9ec4-58775de405eb)

![Screenshot from 2024-04-08 03-20-33](https://github.com/Chevy-Lu/Stellar-Offline-Multisig/assets/31299824/0729c26c-4374-424d-bdb8-cc6a7c854a85)

![Screenshot from 2024-04-08 03-21-15](https://github.com/Chevy-Lu/Stellar-Offline-Multisig/assets/31299824/7315d1a3-2468-4c19-9e05-e120850b6761)

![Screenshot from 2024-04-08 03-22-45](https://github.com/Chevy-Lu/Stellar-Offline-Multisig/assets/31299824/091fb05e-49db-4102-8e65-320e306b52ea)

#

Now that multisig is enabled in your wallet let's make a test transaction to make sure it is working properly. (may need to log-out and back in after enabling multisig)

#

![Screenshot from 2024-04-08 05-04-17](https://github.com/Chevy-Lu/Stellar-Offline-Multisig/assets/31299824/ff93e573-7846-4684-a999-01d57b61fca8)

![Screenshot from 2024-04-08 05-05-08](https://github.com/Chevy-Lu/Stellar-Offline-Multisig/assets/31299824/cefb075c-e67a-4bc2-9437-2c8571f0b5cc)

![Screenshot from 2024-04-08 05-05-40](https://github.com/Chevy-Lu/Stellar-Offline-Multisig/assets/31299824/d2ebe5f3-f7c0-4cda-87de-de01f183306e)

#

Let's paste the copied XDR into the [Stellar Offline Multisig Tool](https://github.com/Chevy-Lu/Stellar-Offline-Multisig/releases) and input the keypair. REMINDER: this step needs to be done offline for security reasons.

#

![Screenshot from 2024-04-08 05-12-57](https://github.com/Chevy-Lu/Stellar-Offline-Multisig/assets/31299824/97817bd4-4a41-4b9e-9016-bbd812f7b762)

![Screenshot from 2024-04-08 05-14-44](https://github.com/Chevy-Lu/Stellar-Offline-Multisig/assets/31299824/5f4e24e7-8cc6-4372-95be-166905ae48e6)

#

Lastly let's submit it to the network using the [Stellar Transaction Submitter](https://github.com/Chevy-Lu/Stellar-Transaction-Submitter). Copy the signed XDR into a USB Flash Drive and transfer it to an online computer. Then paste the signed transaction XDR into [Stellar Transaction Submitter](https://github.com/Chevy-Lu/Stellar-Transaction-Submitter) and submit it to the network.

#
![Screenshot from 2024-04-08 05-18-55](https://github.com/Chevy-Lu/Stellar-Offline-Multisig/assets/31299824/b3f71400-9012-4d32-b520-d6a9fc78562f)
#
It could take up to six seconds to received feedback from the network.
#
![Screenshot from 2024-04-08 05-20-35](https://github.com/Chevy-Lu/Stellar-Offline-Multisig/assets/31299824/665423b0-519b-4be8-8d9f-3ccb0da9e300)

#

### Using StellarX

#

![stellarx-banner](https://github.com/Chevy-Lu/Stellar-Offline-Multisig/assets/31299824/168b8504-1760-4bc2-b097-b7f0c33ae495)

In progress...

#

### Using StellarTerm
TBA

#



