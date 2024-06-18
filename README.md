# AlignedLayer SP1 Proff Oluşturma ve Gönderme

## Aligned testnet indirme işlemi

```
curl -L https://raw.githubusercontent.com/yetanotherco/aligned_layer/main/batcher/aligned/install_aligned.sh | bash
```
```
source /root/.bashrc
```

## SP1 proff reposunu indirme

```
curl -L https://raw.githubusercontent.com/yetanotherco/aligned_layer/main/batcher/aligned/get_proof_test_files.sh | bash
```

## Proff gönderme 

```
aligned verify-proof-onchain \
  --aligned-verification-data ~/aligned_verification_data/*.json \
  --rpc https://ethereum-holesky-rpc.publicnode.com \
  --chain holesky
```
> İşlemler bitti proffunuzun ss'ini alın ve twitter'da @AlignedLayer'i etiketleyerek paylaşın. 
