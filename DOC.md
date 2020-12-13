# Небольшая документация по CoreX
По мере разработки увеличивается список компонентов и классов в библиотеке и порой я сам не могу вспомнить что и как. Собственно поэтому и пишу сейчас всё это.

---

# Основное
## Bootstap Grid
То, как надо пользоваться BS Grid можно почитать в интернете. Поверьте, уроков, статей, форумов и видео на YouTube хоть отбавляй.

## Alert - блоки-напоминания
```
<p class="crx-alert"> ... </p>
```
Если нужны вариации:
```
p.crx-alert.crx-alert_danger
```
```
p.crx-alert.crx-alert_warning
```
```
p.crx-alert.crx-alert_success
```
```
p.crx-alert.crx-alert_info
```

## Breadcrumbs - хлебные крошки
```
<ul class="crx-breadcrumbs" crx-breadcrumbs="bottom">
  <li><a>Home</a></li>
  <li><a>Projects</a></li>
  <li><a>Web</a></li>
  <li>Hello</li>
  <li crx-breadcrumbs="current">CoreX</li>
</ul>
```

## Button
```
<button class="crx-button">Обычная кнопка</button>
```
```
<button class="crx-button" crx-button="borderless">Кнопка без контура</button>
```
```
<button class="crx-button crx-button-block">Кнопка-блок</button>
```
```
<button class="crx-button crx-button-block" crx-button="borderless">Кнопка-блок</button>
```

## Card
```
<div class="crx-card" crx-card="centered">

  <a href="https://google.com" class="crx-card-link"></a>

  <img class="crx-card-image" src="image.jpg" alt="">

  <div class="crx-card-body">
    <h2>Title</h2>
    <p>Description</p>
  </div>

</div>
```

## Gallery
```
<ui class="crx-gallery">

  <li><img src="image.jpg" alt="Image description"></li>

  <li><img src="image.jpg" alt="Image description"></li>

  <li><img src="image.jpg" alt="Image description"></li>

  <li><img src="image.jpg" alt="Image description"></li>

</ui>
```

## List
```
<ul class="crx-list">
  <li>
    List item
    <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Reiciendis minima odit magnam reprehenderit quod, praesentium quasi ratione, corporis nihil excepturi blanditiis vero doloribus rerum totam sunt. Cupiditate hic in libero.</p>
  </li>
  <li>List item</li>
  <li>List item</li>
  <li>
    List item
    <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Reiciendis minima odit magnam reprehenderit quod, praesentium quasi ratione, corporis nihil excepturi blanditiis vero doloribus rerum totam sunt. Cupiditate hic in libero.</p>
  </li>
  <li>List item</li>
  <li>List item</li>
  <li>List item</li>
</ul>
```