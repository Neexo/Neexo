```php
<?php

namespace MatheusAugusto;

class About extends Me
{
    public function getCurrentWorkplace()
    {
        return [
            'workplace' => [
                'company' => 'Processor',
                'position' => 'Infrastructure and Support Analyst N1'         
            ]
        ];
    }

    public function getDailyKnowledge()
    {
        return [
            html::class,
            javascript::class,
            php::class,
            python::class,
            css::class,
        ];
    }

    public function getFutureGoal()
    {
        return 'To contribute to open source.';
    }
}
```

---
⭐️ From [ashbakernz](https://github.com/ashbakernz)
