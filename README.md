# 🖥️ SandWM

This project is a basic X11 tiling window manager implemented in Rust. It aims to provide a minimal and efficient way to manage windows in a tiled layout.

## 🌟 Features

- **🪟 Tiling Window Management**: Automatically organizes your windows into a grid layout, maximizing screen real estate and minimizing clutter.
- **🖱️ X11 Support**: Works with the X Window System, commonly used on Unix-like operating systems.
- **🦀 Written in Rust**: Takes advantage of Rust's memory safety and performance.

## 💽 Installation

Ensure you have Rust installed on your system. If not, you can install it using `rustup`:

```bash
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
```

Then, clone this repository and build the project:

```bash
git clone https://github.com/MrSom3body/SandWM.git
cd SandWM
cargo build --release
```

## 🚀 Usage

To start the window manager, add the following line to your `.xinitrc` file:

```bash
/path/of/SandWM
```

Then start X11:

```bash
startx
```

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📜 License

This project is licensed under the MIT License - see the LICENSE.md file for details.
