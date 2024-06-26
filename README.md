```php
<?php

namespace WilliamVieira;

class About extends Me
{
    public function getPersonalInfo(): array
    {
        return [
            'name'     => 'William Vieira',
            'position' => 'Full Stack Developer',
            'location' => 'São Paulo, Brazil 🇧🇷',
            'website'  => 'https://williamvieira.tech/'
        ];
    }
    public function getSkills(): array
    {
        return [
            'languages'  => ['HTML', 'CSS', 'JavaScript', 'TypeScript', 'PHP', 'C#'],
            'frameworks' => ['Angular', 'VueJs', 'React', 'CodeIgniter', 'Laravel', 'WordPress', 'Flutter', 'Ionic', 'MVC'],
            'databases'  => ['MySQL', 'PostgreSQL', 'SQL Server'],
            'versioning' => ['GitHub'],
            'containers' => ['Docker'],
            'cloud' => ['Azure', 'AWS', 'Cloudflare']
        ];
    }
}
```

---

You can reach me via [Portfolio] (https://williamvieira.tech/)
