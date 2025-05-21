### aboutMe()
```php
function aboutMe() {
    $name = 'Rio Agung Purnomo';
    $age = null;
    $region = 'South Sumatra, Indonesia';

    function fetchData($url) {
        $ch = curl_init();
        curl_setopt($ch, CURLOPT_URL, $url);
        curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
        $response = curl_exec($ch);
        curl_close($ch);
        return $response;
    }

    $statistics = fetchData('https://github-readme-stats.vercel.app/api?username=riodevnet&show_icons=true](https://github-readme-stats.vercel.app/api?username=riodevnet&show_icons=true&count_private=true&theme=darcula&hide_border=true&hide=issues,contribs&bg_color=00000000');
    $favLang = fetchData('https://github-readme-stats.vercel.app/api/top-langs/?username=riodevnet&langs_count=6&layout=compact](https://github-readme-stats.vercel.app/api/top-langs/?username=riodevnet&layout=compact&hide_border=true&theme=darcula&bg_color=00000000&langs_count=6&hide=jupyter%20notebook,tex,css,php&exclude_repo=Pacman-AI');
    $streak = fetchData('https://github-readme-streak-stats.herokuapp.com/?user=riodevnet&date_format=j%20M%5B%20Y%5D](https://github-readme-streak-stats.herokuapp.com?user=riodevnet&theme=darcula&hide_border=true&background=00000000');
}
```
<p align="center">
  <img height="50%" width="auto" src ="https://github-readme-stats.vercel.app/api?username=riodevnet&show_icons=true&count_private=true&theme=darcula&hide_border=true&hide=issues,contribs&bg_color=00000000">
  <img height="50%" width="auto" src ="https://github-readme-stats.vercel.app/api/top-langs/?username=riodevnet&layout=compact&hide_border=true&theme=darcula&bg_color=00000000&langs_count=6&hide=jupyter%20notebook,tex,css,php&exclude_repo=Pacman-AI">
  <img src ="https://github-readme-streak-stats.herokuapp.com?user=riodevnet&theme=darcula&hide_border=true&background=00000000">

  ```js
$socials = [
  'website'   => 'https://riodev.net',
  'instagram' => 'https://instagr.am/iamrioap',
  'facebook'  => 'https://fb.com/iamrioap',
  'twitter'   => 'https://x/riodevnet',
  'github'    => 'https://github.com/riodevnet',
  'linkedin'  => 'https://linked.com/in/ihsanzz',
  'keybase'   => 'https://keybase.io/riodevnet',
  'discord'   => '#',
  'views'     => 'https://komarev.com/ghpvc/?username=riodevnet&color=brightgreen'
];
```
#### socials.get('views')
![](https://komarev.com/ghpvc/?username=riodevnet&color=brightgreen)
