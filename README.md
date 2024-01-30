# AVA-Mistral-7B

 <img src="https://github.com/mehdihosseinimoghadam/AVA-Mistral-7B/blob/main/AVA.png" height="600" width="940" >

This Repository Contains Documents for Fine-Tuned Mistral 7B Persian Large Language Model(LLM) Called AVA-Mistral 7B

-------------------------------------------------
### Dataset used:

To Be Done

-------------------------------------------------

### Different Versions:

| Model  | Data QA Pairs | BatchSize | GPU/Hour  | link |
| ------ | ------ |------ | ------ | ------ | 
| AVA-Mistral-7B-V1  | 12K | 4 | A100/~2h | |
| AVA-Mistral-7B-V2  | 300K | 4 | A100/~10h | | 
| AVA-Mistral-7B-V3  | 1M | 4 | A100/~18h | |
| AVA-Mistral-7B-V4  | 500K | 4 | A100/~24h | | 

-------------------------------------------------

### Usage:

All models are hosted in HuggingFace, 

-------------------------------------------------

## QA Comparision to other models:

 <img src="https://github.com/mehdihosseinimoghadam/AVA-Mistral-7B/blob/main/AVA2.jpg" height="600" width="940" >


[AVA-V4](https://huggingface.co/MehdiHosseiniMoghadam/AVA-Mistral-7B-V4) vs [AVA-V2](https://huggingface.co/MehdiHosseiniMoghadam/AVA-Mistral-7B-V2) vs [Maral](https://huggingface.co/MaralGPT/Maral-7B-alpha-1) vs  [Llama](https://huggingface.co/hdeldar/llama-2-7b-persian-text-1k)

###Q1: ```
طبق متن زیر ایلان ماسک در کجا به دنیا امده است؟

ایلان ریوْ ماسک (به انگلیسی: Elon Reeve Musk؛ ‎/ˈiːlɒn/‎ EE-lon؛ زادهٔ ۲۸ ژوئن ۱۹۷۱)، سرمایه‌گذار و شخصی نامی در کسب‌وکار است. او بنیان‌گذار، مدیرعامل و مهندس ارشدِ فنی اسپیس‌اکس؛ سرمایه‌گذار فرشته، مدیرعامل، طراح محصولات و مدیرعامل سابق شرکت تسلا؛ بنیان‌گذار شرکت بورینگ؛ یکی از بنیان‌گذاران نیورالینک و اوپن‌ای‌آی و رئیس بنیاد ماسک است. او ثروتمندترین شخص در جهان است؛ دارایی خالص تخمینی او بر اساس شاخص میلیاردرهای بلومبرگ تا نوامبر ۲۰۲۳، ۲۱۹ میلیارد دلار آمریکا و بر اساس فوربز، ۲۴۱ میلیارد دلار است. این دارایی اساساً از سهم مالکیت او در تسلا و اسپیس‌ایکس به‌دست آمده‌است.[۵][۶][۷]

ماسک از ارول ماسک و می ماسک در پرتوریا، آفریقای جنوبی به دنیا آمد. او مدت کوتاهی در دانشگاه پرتوریا به تحصیل پرداخت و در ۱۸ سالگی به کانادا رفت که از طریق مادر کانادایی‌تبارش تابعیت این کشور را به دست آورد.[۸] دو سال بعد به دانشگاه پنسیلوانیا رفت و در آن جا کارشناسی اقتصاد و فیزیک خود را گرفت. او در سال ۱۹۹۵ برای تحصیل در دانشگاه استنفورد به کالیفرنیا نقل مکان کرد اما بعد از دو روز ترک تحصیل کرد و به‌همراه برادرش کیمبال، شرکت نرم‌افزاری راهنمای سفر آنلاین زیپ۲ را تأسیس کرد. این شرکت نوپا در سال ۱۹۹۹ به‌مبلغ ۳۰۷ میلیون دلار توسط کامپک خریداری شد و با ۱۲ میلیون دلاری که به دست آورد، ماسک همان سال مشترکاً بانکداری مستقیم X.com را تأسیس کرد که در سال ۲۰۰۰ با کنفینیتی ادغام شد و باعث تشکیل پی‌پل شد.

```

| Model  | Answer | Rating | 
| ------ | ------ |------ | 
| AVA-Mistral-7B-V2  | 12K | 
| AVA-Mistral-7B-V4  | 300K | 
| Maral  | 1M | 4 |
| Llama  | 500K | 4 | 



 
