---
title: Cheese Club
layout: page
---

<div id='product-component-1631411958591'></div>
<script type="text/javascript">
/*<![CDATA[*/
(function () {
  var scriptURL = 'https://sdks.shopifycdn.com/buy-button/latest/buy-button-storefront.min.js';
  if (window.ShopifyBuy) {
    if (window.ShopifyBuy.UI) {
      ShopifyBuyInit();
    } else {
      loadScript();
    }
  } else {
    loadScript();
  }
  function loadScript() {
    var script = document.createElement('script');
    script.async = true;
    script.src = scriptURL;
    (document.getElementsByTagName('head')[0] || document.getElementsByTagName('body')[0]).appendChild(script);
    script.onload = ShopifyBuyInit;
  }
  function ShopifyBuyInit() {
    var client = ShopifyBuy.buildClient({
      domain: 'linh-food.myshopify.com',
      storefrontAccessToken: 'f5b203bf0ff8b44dd5e95561787d747f',
    });
    ShopifyBuy.UI.onReady(client).then(function (ui) {
      ui.createComponent('product', {
        id: '6955115184318',
        node: document.getElementById('product-component-1631411958591'),
        moneyFormat: '%24%7B%7Bamount%7D%7D',
        options: {
  "product": {
    "styles": {
      "product": {
        "@media (min-width: 601px)": {
          "max-width": "calc(25% - 20px)",
          "margin-left": "20px",
          "margin-bottom": "50px"
        }
      }
    },
    "text": {
      "button": "Add to cart"
    }
  },
  "productSet": {
    "styles": {
      "products": {
        "@media (min-width: 601px)": {
          "margin-left": "-20px"
        }
      }
    }
  },
  "modalProduct": {
    "contents": {
      "img": false,
      "imgWithCarousel": true,
      "button": false,
      "buttonWithQuantity": true
    },
    "styles": {
      "product": {
        "@media (min-width: 601px)": {
          "max-width": "100%",
          "margin-left": "0px",
          "margin-bottom": "0px"
        }
      }
    },
    "text": {
      "button": "Add to cart"
    }
  },
  "option": {},
  "cart": {
    "text": {
      "total": "Subtotal",
      "button": "Checkout"
    }
  },
  "toggle": {}
},
      });
    });
  }
})();
/*]]>*/
</script>

## Why should I buy a cheese box?

These cheese boxes will contain things that you cannot get at the grocery store, farmer’s market or even at your local cheese shop.  It contains my connections with distributors and producers.  It contains my experience and guidance.  It contains cheeses that are freshly cut hours before you get your hands on them.

I was a cheesemonger for almost 9 years and even I get overwhelmed by the selection at most cheese counters.  What’s good?  What’s been sitting around for 3 weeks?  Are they selling me that just because they have too much of it?  How am I supposed to remember all of the information my cheesemonger is giving me?  Why do all these stores sell the same cheese?  Do I have to buy a whole jar of this jam just for this one cheese board?  Can someone just please tell me what to buy?!!?

This club is for cheese adventurists.  These cheeses are ones that have stories to tell and complex flavors to impart.  This is not a box of everyday cheeses.  It contains more special things to appreciate on their own.

## What is in the cheese box?

It’s a surprise!  You will not know ahead of time what types of cheeses or accompaniments are in the box.  It will be up to me to decide.

The box will include:
Three types of cheese, roughly about one pound, enough for a cheese course for four people.
Two accompaniments
Info sheet that gives you fun facts, production details, plating and pairing suggestions
A link for those who want to join in (or watch recording later of) an online cheese chat with me and sometimes special guests.

## How much does it cost?

$40 per box

## How do I get my cheese box?

Pickup is at Forage Kitchen, 478 25th Street, Oakland.
Delivery will be available locally to addresses in Berkeley, Piedmont, Oakland, and Emeryville (+$5)
