# eth_wallet
✅ crypto bip39 lib


```from eth_wallet import Wallet
def etherum(seed_phrase):
	wallet = Wallet()
	wallet.from_mnemonic(seed_phrase)
	wallet.from_index(44, harden=True)
	wallet.from_index(60, harden=True)
	wallet.from_index(0, harden=True)
	wallet.from_index(0)
	wallet.from_index(0)
	address = wallet.address()
	priv = wallet.private_key()
	return address
