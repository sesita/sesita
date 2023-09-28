```php

<?php

namespace Sesita;

class About extends Me
{
    public function getCurrentWorkplace(): array
    {
        return [
            'workplace' => [
                'company' => 'Connect',
                'position' => 'Back-end Developer'         
            ]
        ];
    }

    public function getDailyKnowledge(): array
    {
        return [
            PHP::class,
            Javascript::class,
            Laravel::class,
            VueJs::class,
            React::class,
            TailwindCSS::class,
        ];
    }

    public function getFutureGoal(): string
    {
        return 'To contribute to open source.';
    }
}
```
