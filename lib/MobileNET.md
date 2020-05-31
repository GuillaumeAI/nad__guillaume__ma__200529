# MobileNET Notes

Classify images in real-time.

![MobileNET Card](https://i.imgur.com/woIuHt6.png)

## Comments

Simple to use and the result is a JSON file that is pretty clear to use.


## OUTPUT: JSON Content of the classification


![](https://i.imgur.com/wu8H0k8.png)

## It can be run locally on Docker using RunwayML

![](https://i.imgur.com/1qI2tOG.png)


## Sample result

```json
 {
        "filename": "animal-animal-photography-big-682375.jpg",
        "results": [
            {
                "className": "timber wolf, grey wolf, gray wolf, Canis lupus",
                "probability": 0.43917644023895264
            },
            {
                "className": "red wolf, maned wolf, Canis rufus, Canis niger",
                "probability": 0.3488337993621826
            },
            {
                "className": "white wolf, Arctic wolf, Canis lupus tundrarum",
                "probability": 0.09634949266910553
            }
        ]
    },
```