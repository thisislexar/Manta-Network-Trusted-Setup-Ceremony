<h1 align="center">Manta Network Trusted Setup Ceremony

## Daha öncesinde kurduğumuz Manta Network Trusted Setup için contribution sağlıyoruz. Sorularınız olursa: [LossNode Chat](https://t.me/LossNode)

## For questions: [LossNode](https://t.me/LossNodeChat)
 

![image](https://user-images.githubusercontent.com/101462877/204377926-3106d30a-b1e5-49cb-9aa7-876a54fa8936.png)

## Sistem gereksinimleri:
 CPU     | RAM      | SSD     |
 ------------- | ------------- | -------- |
 2          | 4         | 5-10 bile yeter  |

## Manta Network Links:
- [Website](https://www.manta.network/)
- [Telegram](https://t.me/Manta_Turkey)
- [Twitter](https://twitter.com/MantaNetworkTR)
- [Discord](https://discord.gg/mantanetwork)

# [Orijinal Doküman](https://mantanetwork.medium.com/the-manta-network-trusted-setup-is-now-open-for-contributions-f43e9c8f9f76)'a da göz atın.

# Sırasıyla kodları giriyoruz.

```
sudo apt update && sudo apt upgrade -y
```

```
sudo apt install screen -y 
```

```
sudo apt install pkg-config build-essential libssl-dev curl jq -y
```

```
curl https://sh.rustup.rs/ -sSf | sh -s -- -y
```

```
source $HOME/.cargo/env
```

```
git clone https://github.com/Manta-Network/manta-rs.git
```

```
screen -S manta
```

```
cd manta-rs
```

```
cargo run --release --all-features --bin groth16_phase2_client contribute
```

![Screenshot_12](https://user-images.githubusercontent.com/101462877/204378504-2391086e-a7b2-4954-a559-098f5f953f56.png)

# Yukarıdaki gibi bir şey göreceksiniz, daha öncesinde kurduğunuz Trusted Setup'tan aldığımız 12 mnemonic kelimeyi giriyoruz.

![image](https://user-images.githubusercontent.com/101462877/204592944-848a9668-4a72-47a7-a783-1b51747519e6.png)

# Bu kısımda bana 280 kişi verdi, onların sırası bitince ben contribution yapacağım. Screen'den CTRL + A + D yaparak çıkabilirsiniz. Bir süre sonra `screen -r manta` komutuyla screen içine yeniden girip sıra size geldiğinde contribution'ınızı tweet atın.


# Sıranız geldikten sonra bir süre bekleyin, aşağıdaki görseldeki gibi bir görüntü oluşacak. Mavi kısmı kopyalayıp tweet atın. Ayrıca mavi kısımda gördüğünüz hash'i Gleam Formunda submitleyin.

![image](https://user-images.githubusercontent.com/101462877/204501387-13aa0ed7-edb3-4206-80a7-ea15476378be.png)



# Son olarak bu [Gleam formu](https://gleam.io/hCQmJ/manta-network-trusted-setup-campaign)nu doldurmamız gerekiyormuş sanırım, doldurmayı unutmayın.
 
 ![image](https://user-images.githubusercontent.com/101462877/204495220-4487eee9-1fb9-482c-b75d-af996a894afc.png)

