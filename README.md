## Strapdown.js CDN using jsDelivr

[Strapdown.js](http://strapdownjs.com/) was not provided on the CDN. Currently this is solved by [jsDelivr](https://www.jsdelivr.com/).

Original `strapdown.js`. You replace this:

```
<script src="https://strapdownjs.com/v/0.2/strapdown.js"></script>
```

You get the original [Strapdown.js](https://github.com/arturadib/strapdown) v0.2 via jsDelivr:

```
<script src="https://cdn.jsdelivr.net/gh/arturadib/strapdown@gh-pages/v/0.2/strapdown.min.js"></script>
```

There are several more `Strapdown.js` in this project.

___

### 2/

The original `Strapdown.js` v0.2\
It adopts the [Bootstrap 2 theme](https://bootswatch.com/2/).\
The following has been added from the original:

- Cosmo
- Flatly

```
<script src="https://cdn.jsdelivr.net/gh/fu-sen/strapdown.js@master/2/strapdown.min.js"></script>
```

___

### 3/

It can use the [Bootstrap 3 theme](https://bootswatch.com/3/).

It is the [development version](https://github.com/OCG-labs/strapdown/tree/dev) that was included in the [Pull Request](https://github.com/arturadib/strapdown/pull/51).\
I found a bug and fixed it.

```
<script src="https://cdn.jsdelivr.net/gh/fu-sen/strapdown.js@master/3/strapdown.min.js"></script>
```

___

### 4/

It can use the [Bootstrap 4 theme](https://bootswatch.com/).

I wanted to use the Yeti theme for this.\
This was the catalyst for the improvement.

```
<script src="https://cdn.jsdelivr.net/gh/fu-sen/strapdown.js@master/4/strapdown.min.js"></script>
```

___

### 日本語 Japanese

Strapdown.js については次のページで紹介しています。

- [Strapdown.js | ふうせん🎈 FU-SEN](https://balloon.asia/strapdown.js/)
- [md-parser.balloon.net.eu.org](https://md-parser.balloon.net.eu.org/)
