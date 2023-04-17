# FEARec
Code for SIGIR 2023 paper, Frequency Enhanced Hybrid Attention Network for Sequential Recommendation

# Usage

Download datasets from [RecSysDatasets](https://github.com/RUCAIBox/RecSysDatasets) or their [Google Drive](https://drive.google.com/drive/folders/1ahiLmzU7cGRPXf5qGMqtAChte2eYp9gI). And put the files in `./dataset/` like the following.

```
$ tree
.
├── Amazon_Beauty
│   ├── Amazon_Beauty.inter
│   └── Amazon_Beauty.item
├── Amazon_Clothing_Shoes_and_Jewelry
│   ├── Amazon_Clothing_Shoes_and_Jewelry.inter
│   └── Amazon_Clothing_Shoes_and_Jewelry.item
├── Amazon_Sports_and_Outdoors
│   ├── Amazon_Sports_and_Outdoors.inter
│   └── Amazon_Sports_and_Outdoors.item
└── ml-1m
    ├── ml-1m.inter
    ├── ml-1m.item
    ├── ml-1m.user
    └── README.md
```

Run `fearec.sh`.



# Credit
This repo is based on [RecBole](https://github.com/RUCAIBox/RecBole).
