# Konstantin Kokarev
***
### Contacts:

- **E-mail:** woodprop@yandex.ru
- **Discord:** konstantin kokarev (@woodprop)
- **Telegram:** @konstantinkokarev

## About me:
34 y.o., has a lot of technical skills and experience.
Now I want to become a Frontend developer

### Code example:
#### JS:
```javascript
function breakChocolate(n,m) {
  return n * m > 0 ? n * m - 1 : 0;
}
```

#### PHP:
```PHP
function anagrams(string $word, array $words): array {
  $word_arr = str_split($word);
  sort($word_arr);
  $master = array_count_values($word_arr);
  $res = [];
  
  foreach ($words as $w) {
    $arr = str_split($w);
    sort($arr);
    $current = array_count_values($arr);
    if ($current == $master) $res[] = $w;
  }
  
  return $res;
}
```

### Work experience:
- Some backend pet-projects on PHP

### Language:
- **English** Pre-Intermediate
- **Turkish** Elementary