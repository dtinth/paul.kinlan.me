---
slug: webmention-app
date: 2019-06-20T12:33:04.370Z
title: 'Webmention.app'
link: 'https://remysharp.com/2019/06/18/send-outgoing-webmentions'
tags: [links, webmention, zeit, hugo]
---
[Webmentions](https://www.w3.org/TR/webmention/) யோசனையை நான் விரும்புகிறேன், ஆனால் அதை எனது தளத்தில் செயல்படுத்த எனக்கு நேரம் கிடைக்கவில்லை. ஒரு உயர் மட்ட வலை குறிப்புகள், வலையில் உள்ள பிற உள்ளடக்கங்களுக்கு கருத்து தெரிவிக்க, விரும்புவதற்கும் பதிலளிப்பதற்கும் உங்களை அனுமதிக்கின்றன, மேலும் டிஸ்கஸ் போன்ற கருவிகளுடன் மையப்படுத்தப்படாமல் அந்த உள்ளடக்கத்திற்கு இது தெரியும் (இது எனது தளத்திலிருந்து அகற்ற ஆர்வமாக உள்ளேன்).

வலை குறிப்புகள் அனுப்புநர் மற்றும் பெறுநர் என இரண்டு கூறுகளாக பிரிக்கப்படுகின்றன. ரிசீவர் என்பது நான் ஒரு இடுகையை எழுதுகிறேன், மேலும் அவர்கள் தங்கள் தளத்தில் ஏதேனும் இருக்கலாம், அது அவர்களின் வலைப்பதிவிற்கு உள்வரும் இணைப்புகள் அல்லது எதிர்வினைகளைக் காட்டுகிறது; அனுப்புநர், நான் தான். நான் உருவாக்கிய அல்லது அவர்கள் உருவாக்கிய சில உள்ளடக்கங்களுக்கு எதிர்வினையாற்றிய தொலை தளத்தை நான் அனுமதிக்க வேண்டும்.

மிகவும் அற்புதமான [Remy Sharp](https://remysharp.com) [webmention.app](https://webmention.app/) ஒரு பகுதியை தீர்க்க [webmention.app](https://webmention.app/) ஐ உருவாக்கியது: [webmention.app](https://webmention.app/) அனுப்புதல். சி.எல்.ஐ ஸ்கிரிப்டை அழைப்பதன் மூலம், நான் இணைத்துள்ள சாத்தியமான பெறுநர்களுக்கு &#39;பிங்ஸ்&#39; அனுப்ப ரெமியின் கருவி எளிதாக்குகிறது.

ஹ்யூகோ மற்றும் நிலையான-பில்டர் கருவியைப் பயன்படுத்தி [relatively trivial for me to add in support for webmention app](https://github.com/PaulKinlan/paul.kinlan.me/commit/541cf5db0b48b1eb75bedfa326406f887e57e1a9) பயன்படுத்தி எனது வலைப்பதிவை ஹோஸ்ட் செய்கிறேன், எனவே இது [relatively trivial for me to add in support for webmention app](https://github.com/PaulKinlan/paul.kinlan.me/commit/541cf5db0b48b1eb75bedfa326406f887e57e1a9) . நான் `npm i webmention` , பின்னர் எனது `build.sh` கோப்பிலிருந்து கருவியின் CLI பதிப்பை அழைக்கிறேன் - இது மிகவும் எளிது.

இப்போது நான் ஒரு இடுகையை உருவாக்கும்போது, எல்லா புதிய URL களுக்கும் விரைவான பிங் அனுப்ப வேண்டும், அவற்றின் தளத்தைப் பற்றி நான் சில உள்ளடக்கங்களை உருவாக்கியுள்ளேன்.

