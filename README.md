# 📸 25 كود يعدّلوا صورك في ChatGPT — كلمة واحدة، من غير Prompt

<p align="center">
  <a href="#prompt"><img src="https://img.shields.io/badge/%E2%9A%A1%20GET%20THE%20SETUP-COPY%20%26%20PASTE-F97316?style=for-the-badge" alt="خد الـ Setup على طول" height="44"></a>
  <a href="#fill"><img src="https://img.shields.io/badge/%F0%9F%93%9D%20FILL%20YOUR%20DETAILS-NAME%20%C2%B7%20NICHE%20%C2%B7%20LANGUAGE-2563EB?style=for-the-badge" alt="املا بياناتك" height="44"></a>
</p>

<p align="center"><b>👆 دوس على الزرار البرتقاني وهتروح للـ Setup على طول — املا الخانات والصقه في ChatGPT.</b></p>

كل مرة عايز تعدّل صورة بتكتب Prompt طويل، وفي الآخر وشك بيتغيّر؟
هنا هتعرّف ChatGPT على **25 كود** مرة واحدة، وبعد كده تبعت الصورة وتكتب `/` وكلمة، والتعديل يحصل لوحده.

هنا هتلاقي **الـ Setup اللي بستخدمه بالظبط**، والـ 25 كود مقسّمين حسب الاستخدام، وكل كود معاه شرح بيعمل إيه وامتى تستخدمه.

> 💡 انسخ الـ Setup زي ما هو، وغيّر بس الحاجات اللي بين `[ ]`.

---

## 🔌 الأول: فين تحط الـ Setup؟

الأكواد دي مش موجودة في ChatGPT من نفسها. هي شغالة لأنك بتعرّفه عليها مرة واحدة. عندك 3 طرق:

1. **الأفضل: Project** — اعمل Project جديد في ChatGPT واسمه مثلاً `Photo Codes`، وحط الـ Setup الكامل (الـ 25 كود) في الـ Instructions بتاعة الـ Project. أي Chat جوه الـ Project هيفهم الأكواد.
2. **Custom Instructions** — لو عايز الأكواد تشتغل في كل الـ Chats: حط **النسخة القصيرة** (الـ 5 أكواد اللي في الريل) في الـ Custom Instructions. المساحة هناك محدودة، فالـ 25 كود ممكن ميدخلوش.
3. **أسرع حاجة** — الصق الـ Setup كأول رسالة في أي Chat جديد، وبعدها ابعت صورك في نفس الـ Chat.

📖 شرح الـ Projects والـ Custom Instructions من OpenAI: https://help.openai.com

---

<a id="fill"></a>

## 📝 املا بياناتك الأول (مرة واحدة بس)

نفس الخانات دي مستخدمة في الـ Setup وفي كل الأمثلة تحت، فاملاها مرة واحدة.

| الخانة | تكتب فيها إيه | مثال |
|---|---|---|
| `[YOUR NAME]` | اسمك | Steven |
| `[CONTENT TYPE]` | بتستخدم صورك في إيه | LinkedIn + CV + صفحة متجر زيت زيتون |
| `[AUDIENCE]` | مين هيشوف الصور | أصحاب شركات في مصر والخليج |
| `[LANGUAGE]` | لغة الرد | Egyptian Arabic |
| `[NEW BACKGROUND]` | الخلفية الجديدة لكود `/swapbg` | a bright modern office in Cairo |
| `[FORMAT]` | المقاس لكود `/reframe` و `/extend` | 4:5 Instagram post |

<a id="prompt"></a>

### ⚡ Prompt واحد شامل — الـ Setup الكامل (املا والصق)

املا الخانات، والصق ده في الـ Instructions بتاعة الـ Project (أو كأول رسالة في الـ Chat):

```
Here are my details:
- Name: [YOUR NAME]
- What I use my photos for: [CONTENT TYPE]
- Who sees them: [AUDIENCE]
- Reply language: [LANGUAGE]

PHOTO CODES. When my message starts with a slash code and I attach a photo, edit the photo with that code. Don't ask questions or explain. Return the edited image plus one short line in [LANGUAGE] saying what you changed.

GLOBAL RULES (apply to every code):
- Keep the person's identity 100%: same face shape, eyes, nose, mouth, skin tone, age, hairline and body shape. No beautifying, no slimming, no new features.
- Keep the original framing and aspect ratio unless the code says otherwise.
- Photorealistic result. No illustration style, no added text, no watermarks.
- If I send two or more codes (one per line), apply them in order on the same photo.
- If a code can't be done without changing the face, tell me instead of guessing.

PORTRAITS
/identitylock = retouch: fix exposure, color and small blemishes; face and features unchanged.
/headshot = professional CV/LinkedIn headshot: plain neat background, soft front light, shoulders-up crop; same face, same clothes.
/naturalskin = remove temporary spots and shine only; keep real skin texture, pores and moles.
/hairfix = tidy flyaway and messy hair; same hairstyle and length.
/wrinklefree = remove wrinkles and creases from the clothes only.

LIGHTING
/studioquality = studio lighting: soft key light, gentle fill, sharp detail, clean color.
/goldenhour = warm late-afternoon sunlight with natural shadows.
/softlight = remove harsh shadows and blown-out spots on faces.
/nightfix = brighten a dark or night photo and remove noise without making it look fake.
/colorfix = correct white balance and skin tones (no yellow or blue cast).

OLD PHOTOS
/upscale = increase resolution and clarity; blurry to sharp, every detail true to the original.
/restore = repair scratches, tears, folds, stains and dust on an old photo.
/colorize = add realistic, period-correct color to a black-and-white photo.
/deblur = fix motion blur and focus blur.
/fadefix = bring back faded colors and contrast in an old print.

BACKGROUNDS
/cleanup = remove clutter and distracting objects behind the subject; keep the real place.
/whitebg = pure white background with a soft natural shadow (product or ID style).
/blurbg = blur the background like a portrait lens; subject stays sharp.
/swapbg = replace the background with [NEW BACKGROUND], matching light and perspective.
/removeperson = remove extra people or photobombers from the background.

POSE & FRAMING
/poseonly = change the pose to a natural, confident one; face, clothes and background unchanged.
/posture = straighten slouched posture and shoulders; nothing else changes.
/reframe = crop and recompose to [FORMAT] with the subject well placed.
/extend = extend the image edges to fit [FORMAT] by continuing the real background.
/straighten = fix a tilted horizon or crooked angle.
```

**بيعمل إيه؟** بيعرّف ChatGPT على الـ 25 كود والقواعد اللي بتحافظ على وشك. بعدها كل اللي هتعمله: صورة + `/` + كلمة.

---

### ✂️ النسخة القصيرة للـ Custom Instructions (الـ 5 أكواد بتوع الريل)

لو عايز الأكواد في كل الـ Chats، الصق دي في الـ Custom Instructions (صغيرة عشان تدخل في المساحة):

```
Photo codes: when my message starts with one of these codes and I attach a photo, edit it and return only the image plus one short line in [LANGUAGE].
Always keep the person's face, skin tone, age and body exactly the same. Photorealistic, no text, no watermark. Several codes = apply in order.
/identitylock = retouch exposure, color and small blemishes; face unchanged.
/studioquality = soft studio lighting, sharp detail, clean color.
/upscale = higher resolution, blurry to sharp, true to the original.
/cleanup = remove clutter behind the subject, keep the real place.
/poseonly = new natural pose; face, clothes and background unchanged.
```

---

## 💬 الـ 25 كود خطوة بخطوة

طريقة الاستخدام واحدة لكل الأكواد: **ارفع الصورة واكتب الكود لوحده في الرسالة.**

## 🧑 1. صور شخصية

| الكود | بيعمل إيه | استخدمه امتى |
|---|---|---|
| `/identitylock` | بيظبط الإضاءة والألوان والحبوب الصغيرة، والوش زي ما هو | أي سيلفي محتاجة تتظبط (ده كود الريل) |
| `/headshot` | صورة احترافية بخلفية سادة وإضاءة ناعمة | الـ CV والـ LinkedIn |
| `/naturalskin` | بيشيل الحبوب واللمعة بس، والبشرة تفضل طبيعية | لو بتكره الفلتر البلاستيك |
| `/hairfix` | بيظبط الشعر المنكوش، نفس التسريحة | صور الهوا والبحر |
| `/wrinklefree` | بيكوي الهدوم في الصورة 😄 | قميص متكرمش في صورة مهمة |

```
/identitylock
```
**نصيحة:** قارن الصورة قبل وبعد. لو حسيت إن الوش اتغيّر ولو حاجة بسيطة، اكتبله `keep my face exactly like the original` وابعت تاني.

---

## 💡 2. الإضاءة

| الكود | بيعمل إيه | استخدمه امتى |
|---|---|---|
| `/studioquality` | إضاءة studio وتفاصيل sharp | عايز صورة كأن مصوّر محترف صوّرها |
| `/goldenhour` | نور شمس العصاري الدافي | صور برّه شكلها باهت |
| `/softlight` | بيشيل الضل القاسي على الوش | صور الضهر في الشمس |
| `/nightfix` | بينوّر صور الليل ويشيل الـ noise | صور الأفراح والخروجات بالليل |
| `/colorfix` | بيظبط الألوان ولون البشرة | صورة طالعة صفرا أو زرقا |

```
/studioquality
```

---

## 🖼️ 3. الصور القديمة

| الكود | بيعمل إيه | استخدمه امتى |
|---|---|---|
| `/upscale` | بيكبّر الصورة ويخليها واضحة | صورة قديمة مهزوزة أو صغيرة |
| `/restore` | بيصلّح الخدوش والتنيات والبقع | صور جدو وتيتة في الألبوم |
| `/colorize` | بيلوّن صورة أبيض وأسود بألوان واقعية | صور العيلة القديمة |
| `/deblur` | بيصلّح الصورة اللي اتهزت | لقطة حلوة بس مش فوكس |
| `/fadefix` | بيرجّع الألوان الباهتة | صور مطبوعة من التسعينات |

```
/restore
/colorize
/upscale
```
**نصيحة:** صوّر الصورة القديمة بموبايلك في نور النهار ومن غير فلاش، وبعدين ابعتها.

---

## 🧹 4. الخلفيات

| الكود | بيعمل إيه | استخدمه امتى |
|---|---|---|
| `/cleanup` | بيشيل الكركبة اللي وراك، والمكان يفضل نفسه | الأوضة مش مترتبة |
| `/whitebg` | خلفية بيضا بضل طبيعي | صور المنتجات وصور الـ ID |
| `/blurbg` | بيعمل blur للخلفية زي عدسة البورتريه | الخلفية زحمة |
| `/swapbg` | بيغيّر الخلفية لـ `[NEW BACKGROUND]` | عايز خلفية مكتب أو بحر |
| `/removeperson` | بيشيل الناس اللي ورا | حد دخل في الصورة |

```
/cleanup
```

---

## 🕺 5. الوقفة والكادر

| الكود | بيعمل إيه | استخدمه امتى |
|---|---|---|
| `/poseonly` | بيغيّر وقفتك والوش هو هو (الكود السري في الريل) | الوقفة مش عاجباك |
| `/posture` | بيعدّل الضهر والكتاف بس | صور وانت محني |
| `/reframe` | بيقص الصورة على مقاس `[FORMAT]` | بوست أو ستوري |
| `/extend` | بيكبّر أطراف الصورة عشان تدخل في `[FORMAT]` | صورة ضيقة عايزها ستوري |
| `/straighten` | بيعدّل الصورة المايلة | الأفق مايل |

```
/poseonly
```

---

## 🔗 جمّعهم: وصفات جاهزة

ابعت الصورة واكتب الأكواد تحت بعض، وهو هينفذهم بالترتيب:

| الوصفة | الأكواد |
|---|---|
| صورة منتج للصفحة (زي صور Serenoil في الريل) | `/cleanup` ← `/studioquality` |
| صورة LinkedIn من سيلفي عادية | `/headshot` ← `/colorfix` |
| صورة العيلة القديمة | `/restore` ← `/colorize` ← `/upscale` |
| صورة ستوري من صورة عادية | `/extend` ← `/studioquality` |

```
/cleanup
/studioquality
```

---

## 🇪🇬 تقدر تكتبله بالمصري كمان

الـ Setup ده بالمصري وهيفهمه عادي. املا الخانات اللي بين `[ ]`:

```
أنا [اسمك]، وبستخدم صوري في [بستخدمها في إيه].
لما أبعتلك صورة ومعاها كود بيبدأ بـ / عدّل الصورة على طول من غير أسئلة، وقولّي في سطر واحد غيّرت إيه.
مهم جداً: وشي يفضل زي ما هو بالظبط، نفس الملامح ولون البشرة والسن والجسم.
/identitylock = ظبّط الإضاءة والألوان والحبوب الصغيرة من غير ما الوش يتغيّر
/studioquality = إضاءة studio وتفاصيل واضحة
/upscale = كبّر الصورة وخليها واضحة
/cleanup = شيل الكركبة اللي ورايا
/poseonly = غيّر الوقفة بس، والوش والهدوم زي ما هم
```

---

## ⚠️ نصايح مهمة

- **قارن دايماً قبل وبعد.** الـ AI ممكن يغيّر الوش حاجة بسيطة حتى لو قولتله لأ، وساعتها ابعت تاني.
- **الحساب المجاني** ليه عدد محدود من تعديلات الصور في اليوم، فجمّع الأكواد في رسالة واحدة بدل ما تبعت كل كود لوحده.
- **متعدّلش صور حد من غير إذنه،** ومتستخدمش الأكواد في صور رسمية (بطاقة، باسبور) لو الجهة طالبة صورة من غير تعديل.
- **الصورة الأصلية تفضل معاك.** ChatGPT بيعمل نسخة جديدة، فاحتفظ بالأصل.
- **لو الكود مشتغلش،** اتأكد إنك جوه الـ Project اللي فيه الـ Setup، أو الصق الـ Setup تاني كأول رسالة.

## 🚀 الخلاصة

| قبل | بعد |
|---|---|
| Prompt طويل كل مرة | `/` وكلمة |
| الوش بيتغيّر | قواعد ثابتة بتحافظ على ملامحك |
| جلسة تصوير للـ CV والمنتجات | `/headshot` و `/studioquality` |
| صور العيلة القديمة مكسّرة | `/restore` + `/colorize` |

---
لو استفدت، تابعني عشان فيه Prompts وأتمتة أكتر جاية 🔥

**Steven Ayman — Vida AI**
