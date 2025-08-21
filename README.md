# Helm Charts for KubeSphere

## How to install these charts

Find the repository you want to use under `src/` directory and enter below command:

```shell
helm repo add main https://charts.kubesphere-carryon.top/main
```

## How to contribute

### To an existing Helm repo

Just place your charts under the repo, e.g. 

```shell
src/
├── main/
│   └── example-chart/
│       ├── Chart.yaml
│       ├── values.yaml
│       ├── templates/
│       └── ...
```

### To a new Helm repo

Just create a directory under `src/` for the new repo, and place your charts under it, e.g.

```shell
src/
├── main/
│   └── ...
├── example-repo/
│   └── example-chart/
│       ├── Chart.yaml
│       ├── values.yaml
│       ├── templates/
│       └── ...
```

## 💖 Support this Project  

If you find this project useful, consider buying me a coffee ☕️.  

### 💰 Crypto Donation  

- **BTC Address:** bc1qn3d92gg6v8p78ej680gr7xf7q6d73alu9fga4t
  ![BTC QR Code](./donation/btc.png)  

- **ETH Address:** 0x6433B4d3963361037734fd34dEA7D3683F36D291
  ![ETH QR Code](./donation/eth.png)  

- **SOLANA Address:** 7XY3icFFrm9rcHFDBjMQhnuZ2d7jF4xD4TA8wKU9SZW
  ![SOLANA QR Code](./donation/sol.png)  


