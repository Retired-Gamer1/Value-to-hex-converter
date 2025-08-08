# Value-to-Hex Converter  
**Version 1 – The Only Surviving Build**  

### A Handy ARM Hex Conversion Tool for Android Modders  

Hex Generator was my passion project—an Android app designed to simplify converting values into ARM machine code (hexadecimal) for both **ARM64-v8a** and **ARMv7a** architectures. It supports a variety of data types and even includes range generation features, making it useful for game modding, reverse engineering, or low-level tinkering.  

Sadly, development hit a dead end when an unfixable bug corrupted the Java source code. This APK is the last surviving build, warts and all. While it’s not perfect, I’ve decided to release it in case others find it helpful.  

---

### 🔧 **Features**  
**Supported Architectures:**  
- ARM64-v8a (AArch64)  
- ARMv7a (AArch32)  

**Data Types:**  
- Primitive types: `bool`, `int`, `float`, `short`, `long`, `double`  
- Range generators for: `int`, `float`, `short`, `long`, `double`  

**Use Cases:**  
- Game value modding (e.g., patching memory values)  
- ARM assembly debugging  
- Quick hex reference for common data types  

---

### ⚠ **Known Issues & Notes**  
- **Double Precision Bug:** Some `double` conversions may produce incorrect hex values. If you encounter this, let me know [@Newbotprexh](https://t.me/retiredgamermods) so I can document it.  
- **Legacy Code:** Since the source is lost, future updates are unlikely unless rewritten from scratch.  
- **No UI Polish:** This was a functional tool first—don’t expect Material Design!  

---

### 💬 **Final Thoughts**  
This project was a learning experience, and while it didn’t reach its full potential, I hope it saves someone time flipping through hex tables. If you find it useful (or spot a bug), I’d love to hear about it!  

**Note to Modders:** Always verify generated hex values with a disassembler—ARM alignment and endianness can sometimes trip up automated tools.  

---  

*(Written by a human who misses Java sometimes.)*  

---  

This version:  
- Feels more personal and conversational.  
- Explains the context (why the source is lost).  
- Adds practical use cases.  
- Keeps the bug notice but softens the tone.  
- Includes a disclaimer about verification (important for hex tools).  
