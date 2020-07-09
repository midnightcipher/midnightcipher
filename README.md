```php
<?php

namespace AshBaker;

class About extends Me
{
	/* Workplace */ 
    public function getCurrentWorkplace()
    {
        return [
            'workplace' => [
                'company' => 'MEA Mobile',
                'position' => 'Full Stack Developer'         
            ]
        ];
    }

    /* Primary skills/knowledge */
    public function getDailyKnowledge()
    {
        return [
            Php::class,
            Javascript::class,
            Laravel::class,
            Vuejs::class,
            Angular::class,
            ReactNative::class,
            TailwindCss::class,
            Aws::class,
        ];
    }
	
	/* Relevant goal */
    public function getFutureGoal()
    {
        return 'To contribute to open source.';
    }
}
```
