## ⚠️ Bakım & Destek

Bu kütüphane Atlassian ürünleri tarafından yoğun bir şekilde kullanılmaya devam ediyor, ancak şu anda diğer önceliklere odaklanmış durumdayız ve daha fazla özellik geliştirme veya iyileştirme için mevcut bir planımız yok.

Burada GitHub'da olmaya devam edecek ve gerektiğinde kritik güncellemeleri (örn. varsa güvenlik düzeltmeleri) yapmaya devam edeceğiz, ancak sorunları ve çekme isteklerini aktif olarak izlemeyecek veya yanıtlamayacağız.

Bir sonraki duyuruya kadar incelenmeyecekleri veya işleme alınmayacakları için sorun veya çekme isteği oluşturmamanızı öneririz.

> [!Önemli]
>
> **Güncelleme: 3 Nisan 2024**
>
> <a href="https://www.youtube.com/watch?v=uySl2yiUYE4"><img src="https://github.com/alexreardon/files/assets/2182637/bb7740a3-875c-49aa-be54-e7268d836d60" width="300px" /></a>
>
> [📺 Youtube'da izle](https://www.youtube.com/watch?v=uySl2yiUYE4) <br> [🗣️ Tartışma](https://github.com/atlassian/react-beautiful-dnd/issues/2573)

<br>

---

<p align="center">
  <img src="https://user-images.githubusercontent.com/2182637/53611918-54c1ff80-3c24-11e9-9917-66ac3cef513d.png" alt="react beautiful dnd logo" />
</p>
<h1 align="center">react-beautiful-dnd <small><sup>(rbd)</sup></small></h1>

<div align="center">

**Harika** ve **erişilebilir** listeler için sürükle ve bırak [`React`](https://facebook.github.io/react/)

[![CircleCI branch](https://img.shields.io/circleci/project/github/atlassian/react-beautiful-dnd/master.svg)](https://circleci.com/gh/atlassian/react-beautiful-dnd/tree/master)
[![npm](https://img.shields.io/npm/v/react-beautiful-dnd.svg)](https://www.npmjs.com/package/react-beautiful-dnd)

![quote application example](https://user-images.githubusercontent.com/2182637/53614150-efbed780-3c2c-11e9-9204-a5d2e746faca.gif)

[İstersen örnek ile test edebilirsin.](https://react-beautiful-dnd.netlify.com/iframe.html?selectedKind=board&selectedStory=simple)

</div>

## Temel Özellikler

- Öğelerin harika ve [doğal hareketi](/docs/about/animations.md)
- [Erişilebilir](/docs/about/accessibility.md): güçlü klavye ve ekran okuyucu desteği ♿️
- [Son derece performanslı](/docs/support/media.md) 🚀
- Başlaması kolay, temiz ve güçlü api
- Standart tarayıcı etkileşimleriyle son derece iyi çalışır
- [Düzenli tasarım](/docs/guides/preset-styles.md)
- Ek sarmalayıcı dom düğümleri oluşturmaya gerek yok - flexbox ve odak yönetimi dostu!

## Hemen Başla 👩‍🏫

react-beautiful-dnd `kullanmaya mümkün olduğunca çabuk başlamanıza yardımcı olmak için `[egghead.io 🥚](https://egghead.io/courses/beautiful-and-accessible-drag-and-drop-with-react-beautiful-dnd) adresinde ücretsiz bir kurs oluşturduk.

[![course-logo](https://user-images.githubusercontent.com/2182637/43372837-8c72d3f8-93e8-11e8-9d92-a82adde7718f.png)](https://egghead.io/courses/beautiful-and-accessible-drag-and-drop-with-react-beautiful-dnd)

## Şu anda desteklenen özellikler ✅

- Dikey listeler ↕
- Yatay listeler ↔
- Listeler arasında hareket (▤ ↔ ▤)
- [Sanal liste desteği 👾](/docs/patterns/virtual-lists.md) - 60 fps'de 10.000 öğenin kilidini açma
- [Öğeleri birleştirme](/docs/guides/combining.md)
- Fare 🐭, klavye 🎹♿️ ve dokunmatik 👉📱 (mobil, tablet vb.) desteği
- [Çoklu sürükleme desteği](/docs/patterns/multi-drag.md)
- İnanılmaz ekran okuyucu desteği ♿️ - İngilizce ekran okuyucular için kutudan çıkar çıkmaz harika bir deneyim sağlıyoruz 📦. Ayrıca ihtiyaç duyanlar için tam özelleştirme kontrolü ve uluslararasılaştırma desteği sağlıyoruz 💖
- Koşullu sürükleme](/docs/api/draggable.md#optional-props) ve [koşullu bırakma](/docs/api/droppable.md#conditionally-dropping)
- Tek sayfada birden fazla bağımsız liste
- Esnek öğe boyutları - sürüklenebilir öğeler farklı yüksekliklere (dikey listeler) veya genişliklere (yatay listeler) sahip olabilir
- [Sürükleme sırasında öğe ekleme ve kaldırma](/docs/guides/changes-while-dragging.md)
- Anlamsal `<tablo>` yeniden sıralaması ile uyumlu - [tablo kalıbı](/docs/patterns/tables.md)
- Otomatik kaydırma](/docs/guides/auto-scrolling.md) - sürükleme sırasında konteynerleri ve pencereyi gerektiği gibi otomatik olarak kaydırır (klavye ile bile 🔥)
- Özel sürükleme tutamaçları - bir öğenin tamamını sadece bir kısmından sürükleyebilirsiniz
- Sürükleme sırasında sürüklenen öğeyi başka bir öğeye taşıyabilme (klon, portal) - [Reparenting your `<Draggable />`](/docs/guides/reparenting.md)
- [Reparenting your `<Draggable />`](/docs/guides/reparenting.md)
- [Komut dosyası sürükle ve bırak deneyimleri oluşturun 🎮](/docs/sensors/sensor-api.md)
- Uzantıların [istediğiniz herhangi bir girdi türünü 🕹] desteklemesine izin verir (/docs/sensors/sensor-api.md)
- 🌲 [`@atlaskit/tree`](https://atlaskit.atlassian.com/packages/confluence/tree) paketi aracılığıyla ağaç desteği
- Bir `<Droppable />` listesi bir kaydırma konteyneri olabilir (kaydırılabilir bir ebeveyni olmadan) veya bir kaydırma konteynerinin çocuğu olabilir (aynı zamanda kaydırılabilir bir ebeveyni olmayan)
- Bağımsız iç içe listeler - bir liste başka bir listenin alt listesi olabilir, ancak öğeleri üst listeden alt listeye sürükleyemezsiniz
- Sunucu tarafı oluşturma (SSR) uyumlu - bkz [resetServerContext()](/docs/api/reset-server-context.md)
- Varsayılan olarak [iç içe etkileşimli öğeler](/docs/api/draggable.md#interactive-child-elements-within-a-draggable-) ile iyi çalışır.

## Motivation 🤔

`react-beautiful-dnd` exists to create beautiful drag and drop for lists that anyone can use - even people who cannot see. For a good overview of the history and motivations of the project you can take a look at these external resources:

- 📖 [Rethinking drag and drop](https://medium.com/@alexandereardon/rethinking-drag-and-drop-d9f5770b4e6b)
- 🎧 [React podcast: fast, accessible and beautiful drag and drop](https://reactpodcast.simplecast.fm/17)

## Not for everyone ✌️

There are a lot of libraries out there that allow for drag and drop interactions within React. Most notable of these is the amazing [`react-dnd`](https://github.com/react-dnd/react-dnd). It does an incredible job at providing a great set of drag and drop primitives which work especially well with the [wildly inconsistent](https://www.quirksmode.org/blog/archives/2009/09/the_html5_drag.html) html5 drag and drop feature. `react-beautiful-dnd` is a higher level abstraction specifically built for lists (vertical, horizontal, movement between lists, nested lists and so on). Within that subset of functionality `react-beautiful-dnd` offers a powerful, natural and beautiful drag and drop experience. However, it does not provide the breadth of functionality offered by `react-dnd`. So `react-beautiful-dnd` might not be for you depending on what your use case is.

## Documentation 📖

### About 👋

- [Installation](/docs/about/installation.md)
- [Examples and samples](/docs/about/examples.md)
- [Get started](https://egghead.io/courses/beautiful-and-accessible-drag-and-drop-with-react-beautiful-dnd)
- [Design principles](/docs/about/design-principles.md)
- [Animations](/docs/about/animations.md)
- [Accessibility](/docs/about/accessibility.md)
- [Browser support](/docs/about/browser-support.md)

### Sensors 🔉

> The ways in which somebody can start and control a drag

- [Mouse dragging 🐭](/docs/sensors/mouse.md)
- [Touch dragging 👉📱](/docs/sensors/touch.md)
- [Keyboard dragging 🎹♿️](/docs/sensors/keyboard.md)
- [Create your own sensor](/docs/sensors/sensor-api.md) (allows for any input type as well as scripted experiences)

### API 🏋️‍

![diagram](https://user-images.githubusercontent.com/2182637/53607406-c8f3a780-3c12-11e9-979c-7f3b5bd1bfbd.gif)

- [`<DragDropContext />`](/docs/api/drag-drop-context.md) - _Wraps the part of your application you want to have drag and drop enabled for_
- [`<Droppable />`](/docs/api/droppable.md) - _An area that can be dropped into. Contains `<Draggable />`s_
- [`<Draggable />`](/docs/api/draggable.md) - _What can be dragged around_
- [`resetServerContext()`](/docs/api/reset-server-context.md) - _Utility for server side rendering (SSR)_

### Guides 🗺

- [`<DragDropContext />` responders](/docs/guides/responders.md) - _`onDragStart`, `onDragUpdate`, `onDragEnd` and `onBeforeDragStart`_
- [Combining `<Draggable />`s](/docs/guides/combining.md)
- [Common setup issues](/docs/guides/common-setup-issues.md)
- [Using `innerRef`](/docs/guides/using-inner-ref.md)
- [Setup problem detection and error recovery](/docs/guides/setup-problem-detection-and-error-recovery.md)
- [Rules for `draggableId` and `droppableId`s](/docs/guides/identifiers.md)
- [Browser focus retention](/docs/guides/browser-focus.md)
- [Customising or skipping the drop animation](/docs/guides/drop-animation.md)
- [Auto scrolling](/docs/guides/auto-scrolling.md)
- [Controlling the screen reader](/docs/guides/screen-reader.md)
- [Use the html5 `doctype`](/docs/guides/doctype.md)
- [`TypeScript` and `flow`: type information](/docs/guides/types.md)
- [Dragging `<svg>`s](/docs/guides/dragging-svgs.md)
- [Avoiding image flickering](/docs/guides/avoiding-image-flickering.md)
- [Non-visible preset styles](/docs/guides/preset-styles.md)
- [How we detect scroll containers](/docs/guides/how-we-detect-scroll-containers.md)
- [How we use dom events](/docs/guides/how-we-use-dom-events.md) - _Useful if you need to build on top of `react-beautiful-dnd`_
- [Adding `<Draggable />`s during a drag (11.x behaviour)](/docs/guides/changes-while-dragging.md) - _⚠️ Advanced_
- [Setting up Content Security Policy](/docs/guides/content-security-policy.md)

### Patterns 👷‍

- [Virtual lists 👾](/docs/patterns/virtual-lists.md)
- [Multi drag](/docs/patterns/multi-drag.md)
- [Tables](/docs/patterns/tables.md)
- [Reparenting a `<Draggable />`](/docs/guides/reparenting.md) - _Using our cloning API or your own portal_

### Support 👩‍⚕️

- [Engineering health](/docs/support/engineering-health.md)
- [Community and addons](/docs/support/community-and-addons.md)
- [Release notes and changelog](https://github.com/atlassian/react-beautiful-dnd/releases)
- [Upgrading](/docs/support/upgrading.md)
- [Road map](https://github.com/atlassian/react-beautiful-dnd/issues)
- [Media](/docs/support/media.md)

## Read this in other languages 🌎

- [![kr](https://raw.githubusercontent.com/gosquared/flags/master/flags/flags/shiny/24/South-Korea.png) **한글/Korean**](https://github.com/LeeHyungGeun/react-beautiful-dnd-kr)
- [![ru](https://raw.githubusercontent.com/gosquared/flags/master/flags/flags/shiny/24/Russia.png) **На русском/Russian**](https://github.com/vtereshyn/react-beautiful-dnd-ru)
- [![pt](https://raw.githubusercontent.com/gosquared/flags/master/flags/flags/shiny/24/Brazil.png) **Português/Portuguese**](https://github.com/dudestein/react-beautiful-dnd-pt)
- [![gr](https://raw.githubusercontent.com/gosquared/flags/master/flags/flags/shiny/24/Greece.png) **Ελληνικά/Greek**](https://github.com/milvard/react-beautiful-dnd-gr)
- [![ja](https://raw.githubusercontent.com/gosquared/flags/master/flags/flags/shiny/24/Japan.png) **日本語/Japanese**](https://github.com/eltociear/react-beautiful-dnd-ja)

## Creator ✍️

Alex Reardon [@alexandereardon](https://twitter.com/alexandereardon)

> Alex is no longer personally maintaning this project. The other wonderful maintainers are carrying this project forward.

## Maintainers

- [Daniel Del Core](https://twitter.com/danieldelcore)
- Many other [@Atlassian](https://twitter.com/Atlassian)'s!

## Collaborators 🤝

- Bogdan Chadkin [@IAmTrySound](https://twitter.com/IAmTrySound)
