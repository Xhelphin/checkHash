# ✅ checkHash

Python package to check if a string is a valid hash.  

## 🚀 Usage

```python
from checkHash import *

# Check if valid MD2 hash
isMD2("1c8f1e6a94aaa7145210bf90bb52871a") # Returns True

# Check if valid MD4 hash
isMD4("94e3cb0fa9aa7a5ee3db74b79e915989") # Returns True

# Check if valid MD5 hash
isMD5("65a8e27d8879283831b664bd8b7f0ad4") # Returns True

# Check if valid MD6 128 hash
isMD6128("229b1e1e0a0725416b8ec8cc0911facf") # Returns True

# Check if valid MD6 256 hash
isMD6256("ce5effce32637e6b8edaacc9284b873c3fd4e66f9779a79df67eb4a82dda8230") # Returns True

# Check if valid MD6 512 hash
isMD6512("1333db8caf3c69ce346f2dacef9805803f9d4c8594e4b20856ce1b0a70ccb0e68028b0b749d4aa25cbe489a2eb51260c0d7bd16d32dd4d7bfbd1f3ae8aa03260") # Returns True

# Check if valid SHA-1 hash
isSHA1("0a0a9f2a6772942557ab5355d76af442f8f65e01") # Returns True

# Check if valid SHA-2 224 hash
isSHA2224("72a23dfa411ba6fde01dbfabf3b00a709c93ebf273dc29e2d8b261ff") # Returns True

# Check if valid SHA-2 256 hash
isSHA2256("dffd6021bb2bd5b0af676290809ec3a53191dd81c7f70a4b28688a362182986f") # Returns True

# Check if valid SHA-2 384 hash
isSHA2384("5485cc9b3365b4305dfb4e8337e0a598a574f8242bf17289e0dd6c20a3cd44a089de16ab4ab308f63e44b1170eb5f515") # Returns True

# Check if valid SHA-2 512 hash
isSHA2512("374d794a95cdcfd8b35993185fef9ba368f160d8daf432d08ba9f1ed1e5abe6cc69291e0fa2fe0006a52570ef18c19def4e617c33ce52ef0a6e5fbe318cb0387") # Returns True

# Check if valid SHA-3 224 hash
isSHA3224("853048fb8b11462b6100385633c0cc8dcdc6e2b8e376c28102bc84f2") # Returns True

# Check if valid SHA-3 256 hash
isSHA3256("1af17a664e3fa8e419b8ba05c2a173169df76162a5a286e0c405b460d478f7ef") # Returns True

# Check if valid SHA-3 384 hash
isSHA3384("aa9ad8a49f31d2ddcabbb7010a1566417cff803fef50eba239558826f872e468c5743e7f026b0a8e5b2d7a1cc465cdbe") # Returns True

# Check if valid SHA-3 512 hash
isSHA3512("38e05c33d7b067127f217d8c856e554fcff09c9320b8a5979ce2ff5d95dd27ba35d1fba50c562dfd1d6cc48bc9c5baa4390894418cc942d968f97bcb659419ed") # Returns True

# Check if valid NTLM hash
isNTLM("A0D6DCCEBBC32FD38E7355AF9926A582") # Returns True

# Check if other valid hash
length = 16
isOtherHash("abcdef1234567890", length) # Returns True

# Check if valid RipeMD-128 hash
isRipeMD128("67f9fe75ca2886dc76ad00f7276bdeba") # Returns True

# Check if valid RipeMD-160 hash
isRipeMD160("527a6a4b9a6da75607546842e0e00105350b1aaf") # Returns True

# Check if valid RipeMD-256 hash
isRipeMD256("567750c6d34dcba7ae038a80016f3ca3260ec25bfdb0b68bbb8e730b00b2447d") # Returns True

# Check if valid RipeMD-320 hash
isRipeMD320("f9832e5bb00576fc56c2221f404eb77addeafe49843c773f0df3fc5a996d5934f3c96e94aeb80e89") # Returns True

# Check if valid CRC16 hash
isCRC16("fa4d") # Returns True

# Check if valid CRC32 hash
isCRC32("ec4ac3d0") # Returns True

# Check if valid Adler32 hash
isAdler32("1f9e046a") # Returns True

# Check if valid Whirlpool hash
isWhirlpool("3d837c9ef7bb291bd1dcfc05d3004af2eeb8c631dd6a6c4ba35159b8889de4b1ec44076ce7a8f7bfa497e4d9dcb7c29337173f78d06791f3c3d9e00cc6017f0b") # Returns True
```

## 📦 Installation

Run the following to install:  

```bash
$ pip install checkHash
```

## 👨‍💻 Developing checkHash

To install checkHash, along with the tools you will need to develop and run tests, run the following in your virtualenv:  

```bash
$ pip install -e .[dev]
```

## 🚦 Development Progress

Stable Development  
