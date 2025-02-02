# ![veld chain](https://raw.githubusercontent.com/veldhub/.github/refs/heads/main/images/symbol_V_letter.png) veld_chain__flair

\***work in progress!\***

This repo contains [chain velds](https://zenodo.org/records/13322913) encapsulating a demo training
and inference setup using [veld_code__flair](https://github.com/veldhub/veld_code__flair) and 
[flair](https://github.com/flairnlp/flair) .

## requirements

- git
- docker compose (note: older docker compose versions require running `docker-compose` instead of 
  `docker compose`)

Clone this repo with all its submodules
```
git clone --recurse-submodules https://github.com/veldhub/veld_chain__demo_flair.git
```

## how to reproduce

The following chain velds were used. Open the respective veld yaml file for more information.

**[./veld_demo_01__infer_ner.yaml](./veld_demo_01__infer_ner.yaml)** 

```
docker compose -f veld_demo_01__infer_ner.yaml up
```

