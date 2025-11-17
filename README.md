# Educational Cryptografi Algorithms
The algorithms in this library is for educational purposes **only** and is **not** suitable for production use. 

The code is free to use under the **MIT License**

## Contents 
- RSA
    - Encrypt (C++/Python)
    - Decrypt (C++/Python)
    - Key generation (C++)
- AES
    - Encrypt (C++)
    - Decrypt (C++)
    - Key generation (C++)
- Caesar cipher
    - Encrypt (C++/Python)
    - Decrypt (C++/Python)

## How to use

### C++
For the **C++** implementations of the algorithms include their respective **headers files** (.h)

```c++
#include "asymmetric_encryption/RSA/cpp/RSA.h"

#include "symmetric_encryption/AES/AES.h"

#include "symmetric_encryption/caesar_cipher/caesar_cipher.h"
```

Then compile the project

#### RSA
```bash
g++ your-file.cpp asymmetric_encryption/RSA/cpp/RSA.cpp asymmetric_encryption/RSA/cpp/RSA_key_generation.cpp -o output-file
```

#### AES
```bash
g++ your-file.cpp symmetric_encryption/AES/AES.cpp -o output-file
```

#### Caesar cipher
```bash
g++ your-file.cpp symmetric_encryption/caesar_cipher/caesar_cipher.cpp -o output-file
```

### Python
When using the Python implementations include the Python files (.py) directly

```python
from asymmetric_encryption.RSA.python.RSA import *

from symmetric_encryption.caesar_cipher.caesar_cipher import *
```
