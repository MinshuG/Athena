# Athena

Athena is a utility which generates the current Fortnite Item Shop into a stylized image and shares it on Twitter.

As seen on [@FNMasterCom](https://twitter.com/FNMasterCom/status/1170487059355713536?s=20)...

<p align="center">
    <img src="https://i.imgur.com/I2vmoEY.png" width="650px" draggable="false">
</p>

## Requirements

- [Python 3.7](https://www.python.org/downloads/)
- [Requests](http://docs.python-requests.org/en/master/user/install/)
- [Colorama](https://pypi.org/project/colorama/)
- [Pillow](https://pillow.readthedocs.io/en/stable/installation.html#basic-installation)
- [python-twitter](https://github.com/bear/python-twitter#installing)

## Usage

Open `configuration_example.json` in your preferred text editor, fill the configurable values. Once finished, save and rename the file to `configuration.json`.

- `language`: Set the shop language. [Available languages: `ar`, `de`, `en`, `es`, `es-419`, `fr`, `it`, `ja`, `ko`, `pl`, `pt-br`, `ru`, `tr`, `zh-CN`, `zh-Hant`]
- `delayStart`: Set to `0` to begin the process immediately
- `supportACreator`: Leave blank to omit the Support-A-Creator tag section of the Tweet
- `twitter`: Set `enabled` to `false` if you wish for `itemshop.png` to not be Tweeted

Edit the images found in `assets/images/` to your liking, avoid changing image dimensions for optimal results.

Install all requirements trough using:
```
pip install -r requirements.txt
```

Now you can start the bot by using:
```
python itemshop.py
```

## Credits

- Item Shop data provided by Not Officer#9999's [API](https://fortnite-api.com/)
- Burbank font property of [Adobe](https://fonts.adobe.com/fonts/burbank)
- Luckiest Guy font property of [Google](https://fonts.google.com/specimen/Luckiest+Guy)
