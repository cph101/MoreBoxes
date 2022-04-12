# MoreBoxes
Want more Blooket Boxes? Download this!

## About

This project was created as a joint effort between [cph101](https://github.com/cph101) and [CodingKid101](https://github.com/CodingKid101).

<strong>If this makes no sense to you, don't worry, we're not done yet, and we hope to add some more content in the upcoming months.</strong>

## How to install

1. Download the packaged .crx from [here]()
2. Enable developer mode in the extensions pane in Chrome
3. Drag the extension right in
4. Confirm the permissions message
5. Launch the extension and follow the steps from there


<details>
<summary>## Can I make my own boxes?</summary>

Making your own box is easy - you just need a good understanding of JSON. Example below:

```JSON
{
    "boxName":"Minecraft Box",
    "blooks":[
        {
            "blookName":"Creeper",
            "imgSrc":"https:\/\/res.cloudinary.com\/dfogayqhr\/image\/upload\/v1645525786\/svgviewer-output-7_astjsr.svg",
            "blookRank":"Uncommon"
        }
    ],
    "boxPrice":1
}
```


There are 3 main fields:

`boxName` - The name of the box - String Value

`boxPrice` - The price of the box - can be either **25, 20, or 15**. Numeric Value

`blooks` - An array of the blooks - scroll down to learn more ->

Inside the `blooks` array, there are some more fields:

`blookName` - The name of the blook - String Value

`imgSrc` - The url of the blook image, **it must be a svg** - String Value

`blookRank` - The rank of the blook, determines sell price and rating - String Value


Once you've done, you can upload your JSON to a place like GitHub, make sure you have the direct link, and share it with your friends!
</details>
