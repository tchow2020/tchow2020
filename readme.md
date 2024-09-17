```ts

  @Controller('users')
  export class UserController {
    constructor(private readonly createUserService: CreateUserService){ }
    @Post()
    function create () {
      return this.createUserService.execute({
        name: 'lgustavo',
        email: 'lgmds2017@outlook.com',
        age: 23
      });
    }
  }

```

## Experiences

[![My Skills](https://skillicons.dev/icons?i=nestjs,ts,html,css,nodejs,mysql,docker,vscode,linux,git,github,jest,postgres,express,vitest)](https://skillicons.dev)

## ⚙️ My GitHub Analytics

![](http://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=tchow2020&theme=github_dark)
![](http://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=tchow2020&theme=github_dark)
![](http://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=tchow2020&theme=github_dark)
![](http://github-profile-summary-cards.vercel.app/api/cards/stats?username=tchow2020&theme=github_dark)
![](http://github-profile-summary-cards.vercel.app/api/cards/productive-time?username=tchow2020&theme=github_dark&utcOffset=-3)

<div align="center">
  <img src="https://profile-counter.glitch.me/tchow2020/count.svg?"  />
</div>
