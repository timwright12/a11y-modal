# Accessible Modal Dialog

This plugin was converted from a jQuery plugin originally written by [@scottohara](https://github.com/scottaohara/). You can view the original code in [Scott's Accessible Component Library](https://github.com/scottaohara/accessible-components).

It was created to help you implement accessible modal dialogs with minimal work, because everyone is tired of using crappy UI plugins that damage the underlying experience. [Check out the demo](https://timwright12.github.io/a11y-modal/)

## Example HTML You'll Need

```html
<a href="#primary_modal" data-action="modal-open" data-modal-open="primary_modal" data-set-modal-title="Test Title">
  Open Modal with a Link
</a>

<div id="primary_modal" class="a11y-modal no-js-hide-modal">
  <div class="modal">
  
    <div class="modal__intro">
      <h3 id="small_modal_title" data-modal-title class="modal__intro__title">Modal Heading</h3>
      Content
    </div><!--/.modal__intro-->
  
    <div class="modal__content">
      Content
    </div><!--/.modal__content-->
  
    <div class="modal__outro">
      <a href="#x" data-modal-close class="modal__outro__close">
      <span aria-hidden="true">⨉</span>
      </a>
    </div><!--/.modal__outro-->
  
  </div> <!--/.modal-->
</div><!--/.a11y-modal-->
```

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b feature/my-new-feature`
3. Commit your changes: `git commit -m 'Added some great feature!'`
4. Push to the branch: `git push origin feature/my-new-feature`
5. Submit a pull request

## Credits

- [Scott O'Hara](https://github.com/scottaohara/) ( [@scottohara](https://twitter.com/scottohara) )
- [Tim Wright](http://github.com/timwright12) ( [@csskarma](http://twitter.com/csskarma) )

## License

Code and documentation are released under the MIT license.

## Browser support

| Feature       | Chrome | Firefox | Internet Explorer | Safari |
|---------------|--------|---------|-------------------|--------|
| Basic Support | Latest | Latest  | 9+                | 5.1+   |
