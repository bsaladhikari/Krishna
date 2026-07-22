# गोवर्धन गाथा — बाँकी भागहरूको मास्टर प्रोडक्सन प्याकेज

यो प्याकेज पहिले निर्माण भइसकेको भाग १ को दृश्य भाषा, पात्र पहिचान, लोकेसन, प्रप्स, ध्वनि नियम र उत्पादन अनुशासनलाई आधार मानेर भाग २–४ तयार गर्नका लागि हो।

## स्रोतको प्राथमिकता

1. `01_SCRIPT_LOCK/GOVARDHAN_GATHA_SCRIPT_LOCK_BHAAG_2_TO_4.txt`
2. `02_PRODUCTION_PLANNING/CONTINUATION_PRODUCTION_BIBLE.md`
3. `02_PRODUCTION_PLANNING/VOICE_LOCK_AND_AUDITION.md`
4. आगामी स्वीकृत scene/clip architecture र state tracking
5. स्वीकृत Episode 1 references
6. नयाँ, प्रयोगकर्ताले दृश्य रूपमा स्वीकृत गरेका references
7. prompt cards र HTML dashboard

## सक्रिय उत्पादन निर्णय

- भिडियो मोडेल: **Gemini Omni Flash मात्र**
- प्रत्येक भिडियोमा **start frame मात्र** प्रयोग गर्ने; end frame प्रयोग नगर्ने
- प्रत्येक clip/scene कार्डमा आवश्यक सबै references फेरि देखाउने
- प्रत्येक clip का लागि start frame र चार-panel storyboard/reference board उपलब्ध गराउने
- पात्रको आवाज Google Flow custom voice asset का रूपमा एकपटक बनाइने र त्यसपछि `@Voice` बाट बोलाइने
- generated clip भित्र music/background score नराख्ने; music post-production मा थप्ने
- exact Hindi dialogue मात्र; नयाँ dialogue नथप्ने
- dashboard र freelancer निर्देशन नेपाली भाषामा राख्ने

## हालको अवस्था

- भाग २–४ script lock: तयार
- Episode 1 reusable asset audit: प्रारम्भिक mapping तयार
- voice identity specification: तयार; Flow मा base voice audition/approval बाँकी
- नयाँ asset generation: प्रयोगकर्ताको दृश्य स्वीकृति बिना production-approved मानिने छैन
- start frames/storyboards: architecture approval पछि क्रमशः बनाइने

## महत्वपूर्ण नियम

सबै frame एकैचोटि mass-generate नगर्नुहोस्। पहिले scene/clip architecture स्वीकृत गर्नुहोस्, त्यसपछि नयाँ reference assets, त्यसपछि प्रत्येक start frame र storyboard visual review गरेर मात्र भिडियोमा जानुहोस्।
