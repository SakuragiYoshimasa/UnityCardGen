# CardImageGen
Tools for card images.

## How to use
### With GUI environment
Please build app with Unity for your build target.

#### Command line argments

```
--master:
	Json filepath to masterInfo for card list.
	It should contain these data.
	{"masterDatas": [masterData]}
	masterData := {
		   card_id: "card_id",
		   image_path: "image path for master image"
	}
--outdir:
	Output target of auto generated images.
	outdir____Card_ID1
		|_Card_ID2
		|_Card_ID3
		...
--gen-per-master:
	How many cards will be generated per master card.
--variation:
	low, high, vhigh
```
