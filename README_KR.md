# things-extension

## 리소스 타입, 리소스 아이디를 바탕으로 한 확장 속성 프로퍼티를 입력받고 보여주는 컴포넌트

```html
<things-extension
  id="ext-properties"
  class="detail-flex"
  resource-type="EventAction"
  resource-id="{{resourceId}}">
</things-extension>
```
# things-prop-extension
## 리소스 타입, 리소스 아이디를 바탕으로 확장속성 타입까지 설정할 수 있는 확장속성 프로퍼티를 입력받고 보여주는  컴포넌트
```html
<things-prop-extension
  id="alarm-params"
  resource-type="EventAction"
  resource-id="[[resourceId]]"
  prop-type="Alarm">
</things-prop-extension>
```

## Dependencies

Element dependencies are managed via [Bower](http://bower.io/). You can
install that via:

    npm install -g bower

Then, go ahead and download the element's dependencies:

    bower install

## Playing With Your Element

If you wish to work on your element in isolation, we recommend that you use
[Polyserve](https://github.com/PolymerLabs/polyserve) to keep your element's
bower dependencies in line. You can install it via:

    npm install -g polymer-cli

And you can run it via:

    polymer serve

Once running, you can preview your element at
`http://localhost:8080/components/things-alarm/`, where `things-alarm` is the name of the directory containing it.
