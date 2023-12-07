<!-- loio8bb4723002ef4dc19a065b2e30c5498f -->

| loio |
| -----|
| 8bb4723002ef4dc19a065b2e30c5498f |

<div id="loio">

view on: [demo kit nightly build](https://sdk.openui5.org/nightly/#/topic/8bb4723002ef4dc19a065b2e30c5498f) | [demo kit latest release](https://sdk.openui5.org/topic/8bb4723002ef4dc19a065b2e30c5498f)</div>

## Programmatic Access to RTL

Some controls need to provide specific coding for right-to-left mode \(RTL\), for example, because they position or animate elements programmatically, and not via CSS. To read the OpenUI5 RTL configuration, use the following function call:

```js
sap.ui.require(["sap/base/i18n/Localization"], (Localization) => {
    const bRtl = Localization.getRTL();
});
```

