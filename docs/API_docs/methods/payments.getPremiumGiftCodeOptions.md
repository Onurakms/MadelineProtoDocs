---
title: "payments.getPremiumGiftCodeOptions"
description: "payments.getPremiumGiftCodeOptions parameters, return type and example"
grand_parent: "Telegram RPC API"
parent: "Methods"
image: https://docs.madelineproto.xyz/favicons/android-chrome-256x256.png
redirect_from: /API_docs/methods/payments_getPremiumGiftCodeOptions.html
---
# Method: payments.getPremiumGiftCodeOptions
[Back to methods index](index.html)



### Parameters:

| Name     |    Type       | Required |
|----------|---------------|----------|
|boost\_peer|[Username, chat ID, Update, Message or InputPeer](/API_docs/types/InputPeer.html) | Optional|


### Return type: [Vector\_of\_PremiumGiftCodeOption](/API_docs/types/PremiumGiftCodeOption.html)

### Can bots use this method: **NO**


### MadelineProto Example ([now async for huge speed and parallelism!](https://docs.madelineproto.xyz/docs/ASYNC.html)):


```php
if (!file_exists('madeline.php')) {
    copy('https://phar.madelineproto.xyz/madeline.php', 'madeline.php');
}
include 'madeline.php';

$MadelineProto = new \danog\MadelineProto\API('session.madeline');
$MadelineProto->start();

$Vector_of_PremiumGiftCodeOption = $MadelineProto->payments->getPremiumGiftCodeOptions(boost_peer: $InputPeer, );
```

