# Steganography
Steganography is the technique of hiding secret data within an ordinary, non-secret, file or message in order to avoid detection. The secret data is then extracted at its destination. In this project LSB overriding technique is used.

## How To Run :runner:

:one: open terminal in `src` folder.

:two: compile the program with this command:
``` sh
javac *.java 
```

:three: Run the program with this command:
``` sh
java Program
```
## Formats Supported

### Vessel File(File which will Hide other files)
:one: .png

### Secret File
any file can be hidden using this technique but the `size` of secret file must be smaller than `embedding-capacity` of Vessel file.

---
---