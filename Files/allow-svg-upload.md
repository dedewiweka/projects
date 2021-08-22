## Allow svg upload

### Code Snippet

```php
add_filter('upload_mimes', 'my_mime_types');
function my_mime_types($mimes)  {
    $mimes['svg'] = 'image/svg+xml';
    return $mimes;
}
```
### Explanations

### License

[GNU General Public License v2.0](https://github.com/dedewiweka/snippets/blob/main/LICENSE)

### Support and Contact

For more information and details about my work please visit [My Development Website](https://dede.wiweka.com/development).