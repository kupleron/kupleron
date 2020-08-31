### Hi there 👋

#### I'm a Full-Stack Developer working in Marrakech, Morocco.

- 🏢 I'm currently working at **Home**
- ⚙️ I use daily: `.php`, `.js`, `.py`, `.html`, `.css`
- 🌱 Learning all about **Open Source**
- 💬 Ping me about **laravel**, **javascript**, **python**, **react**, **development**, **design patterns**
- 📫 Reach me: [twitter.com/kupleron](https://twitter.com/kupleron), [khalid@souh.al](mailto:khalid@souh.al)


```php
<?php

namespace Kupleron;

class About extends Me
{
    public function getCurrentWorkplace()
    {
        return [
            'workplace' => [
                'company' => Null,
                'position' => 'Full Stack Developer'         
            ]
        ];
    }

    public function getDailyKnowledge()
    {
        return [
            Php::class,
            Javascript::class,
            Python::class,
            Laravel::class,
            Vuejs::class,
            React::class,
            ReactNative::class,
            TailwindCss::class,
            Aws::class,
        ];
    }

    public function getFutureGoal()
    {
        return 'To contribute to open source.';
    }
}
```
