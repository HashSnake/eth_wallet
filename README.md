# eth_wallet
✅ crypto bip39 lib


```Python
from eth_wallet import Wallet

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


print(etherum("series exact trouble tissue confirm require about pave soap point crisp beach"))

> 0x86c67bcf7FcAE7C714A972c8CC721027D87E138F
