## Thumbnail outside of loop

### Code Snippet

```php
global $post;
$image_arr = wp_get_attachment_image_src(get_post_thumbnail_id($post->ID), 'full');

if(!empty($image_arr)) {
  $image = $image_arr[0];
}
```
### Explanations

### License

[GNU General Public License v2.0](https://github.com/dedewiweka/snippets/blob/main/LICENSE)

### Support and Contact

For more information and details about my work please visit [My Development Website](https://dede.wiweka.com/development).