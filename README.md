<h1>Soundness Testnet Guide</h1>

```console
sudo apt update && sudo apt upgrade -y
```

```console
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
```

```console
source $HOME/.cargo/env
```

```console
rustc --version
cargo --version
```

```console
echo 'source $HOME/.cargo/env' >> ~/.bashrc
```

```console
source ~/.bashrc
```

```console
curl -sSL https://raw.githubusercontent.com/soundnesslabs/soundness-layer/main/soundnessup/install | bash
```

```console
source ~/.bashrc
```

```console
soundnessup install
soundnessup update
```

```console
soundness-cli generate-key --name my-key
```
