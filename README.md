```php
<?php

namespace emirhanwsd;

class About extends Me{

    public function getName(): string{
        return "Emirhan";
    }
    
    public function getSurname(): string{
        return "Akpınar";
    }
    
    public function getAge(): int{
        return 17;
    }
    
    public function getCurrentWorkplace(): string{
        return "Scoutli";
    }
    
    public function getSkills(): array{
        return [
            PHP::class,
            HTML::class,
            CSS::class,
            SASS::class,
            JavaScript::class,
            Laravel::class,
            React::class,
            NextJS::class,
            TailwindCSS::class,
            Bootstrap::class
        ];
    }
    
    public function getFutureGoal(): string{
        return "💸 work for more money and more prestige";
    }
}
```
