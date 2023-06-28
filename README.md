<h1><img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="25px"> Hi there, I'm Dennis!</h1>

<i>A passionate fullstack software developer from Germany 🇩🇪</i>

## 📖 About Me

```php
<?php

namespace Dennis\Barlowe;

readonly class About extends Me
{
    public const CHARACTERISTICS = [
        'name'              =>  'Dennis Barlowe',
        'nationalities'     =>  ['en_US', 'de_DE'],
        'birthyear'         =>  1994,
        'role'              =>  'Web Developer',
        'gender'            =>  'male',
        'location'          =>  'Aschaffenburg, Germany',
    ];

    public function getPrimarySkillSet(): array
    {
        return [
            'languages' => ['php', 'html', 'twig', 'css', 'scss/sass', 'javascript', 'sql', 'bash'], 
            'frameworks' => ['symfony', 'wordpress'],
            'libraries' => ['react', 'doctrine'],
            'toolset' => ['git', 'composer', 'npm', 'intellij ide', 'atlassian', 'adobe', 'webpack'], 
            'operations' => ['docker', 'jenkins', 'gitlab-ci', 'github-actions'],
            'os' => ['osx', 'ubuntu', 'centos', 'debian', 'windows'],
            'webservers' => ['traefik', 'nginx', 'apache'],
            'databases' => ['mysql', 'mariadb', 'oracle'], 
            'architecture' => ['microservices', 'monolith', 'design patterns', 'api', 'modular', 'unittests', 'message queues', 'SOLID'],
        ];
    }

    public function sayHi(): string
    {
        return 'Thank you for stopping by. Maybe you find some of my work interesting.';
    }

}

$about = new About();
$about->sayHi();

```

## 📫 Connect with me

[<img alt="website" src="https://img.shields.io/badge/-website-4285F4?style=for-the-badge&logo=google-chrome&logoColor=white" />](https://dennzo.com) &nbsp;&nbsp;
[<img alt="discord" src="https://img.shields.io/badge/-discord-7289DA?style=for-the-badge&logo=discord&logoColor=white" />](https://discord.com/users/201773417626730497) &nbsp;&nbsp;
[<img alt="twitter" src="https://img.shields.io/badge/-twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white" />](https://twitter.com/deennzoo)&nbsp;&nbsp;
[<img alt="instagram" src="https://img.shields.io/badge/-instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white" />](https://instagram.com/deennzo)&nbsp;&nbsp;
[<img alt="linkedin" src="https://img.shields.io/badge/-linkedin-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" />](https://linkedin.com/in/dennzo)


<!--

## 🏆 Github Statistics

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=dennzo&layout=compact&theme=dracula)

![trophy](https://github-profile-trophy.vercel.app/?username=dennzo&theme=dracula)

![Dennis's GitHub stats](https://github-readme-stats.vercel.app/api?username=dennzo&show_icons=true&theme=dracula)
-->

