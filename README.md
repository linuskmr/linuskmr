```rust
for (vga, chr) in iter::zip(
	(0xb8000..0xb8fa0).into_iter().step_by(2),
	[0x4c, 0x69, 0x6e, 0x75, 0x73, 0x13] // CP473
) {
	unsafe { (vga as *mut u8).write_volatile(chr); }
}
```

- 👋 Hi, I'm Linus
- 🎓 Studying Computer Science in Germany
- 👨‍💻 Programming in Rust, Python, C++, C, JS/TS, Go, Kotlin, WebAssembly
- 📫 Reach me via linuskmr.dev@gmail.com
- ♥️ Loving human-readable data formats (txt, md, csv) that are still readable in 50 years and don't depend on specific software support


<!--
**linuskmr/linuskmr** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
