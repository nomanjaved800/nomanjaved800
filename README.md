
## Hi there, I'm Muhammad Noaman 👋
```php
<?php

namespace nomanjaved;

class About extends Me
{
    public function getBio(): string
    {
        return ' I am a software developer specializing in PHP Laravel and JavaScript.
                I develop modern technology web applications with popular frameworks like Laravel, Angular, React, Livewire, Vue.js.
                SaaS,
                Multi-Tenancy,
                E-Commerce,
                RestFull API
                I develop advanced software with software architectures.';
    } 

    public function getMore(): array
    {
        return [
            'work' => [
                'Full Stack Developer - Al-burraq Technologies',
                'Full Stack Engineer - Truetalent.online',
                'PHP Laravel Developer - Baron Tech (Pvt) Limited'
            ]
        ];
    }

    public function getCurrentState(): array 
    {
        return [
            'working_on' => [
                'allcalls.io - Allcalls is a remote opportunity in insurance sales with on-demand client leads. Flexible schedule, daily commissions, performance-based promotions, and management opportunities available.',
                'telaeris.com - Telaeris, Inc. is a US-based software company, specializing in handheld and hands-free safety and physical security solutions to enhance access control and occupancy tracking systems'
            ],
            'learning' => [
                'Advance Programing Techniques',
                'AI',
                'Python'
            ]
        ];
    }

    public function getFutureGoal(): string
    {
        return 'Contribute to open source.';
    }
}
```
