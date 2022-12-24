## Olá =D, bem vindo ao meu GitHub 👋
![Typescript](https://img.shields.io/badge/TypeScript-black?style=flat-square&logo=typescript&logoColor=007ACC)
![Nodejs](https://img.shields.io/badge/-Nodejs-black?style=flat-square&logo=Node.js)
![React](https://img.shields.io/badge/-React-black?style=flat-square&logo=react)
![MySQL](https://img.shields.io/badge/-MySQL-black?style=flat-square&logo=mysql)
![Docker](https://img.shields.io/badge/-Docker-black?style=flat-square&logo=docker)
![Amazon AWS](https://img.shields.io/badge/Amazon%20AWS-232F3E?style=flat-square&logo=amazon-aws)
![Git](https://img.shields.io/badge/-Git-black?style=flat-square&logo=git)  


<div style="display: flex">
   <img src="https://github-readme-stats.vercel.app/api?username=gustavo-sm&show_icons=true&count_private=true&theme=dark" />
</div>  


##### Caso queira saber mais sobre mim:
[Linkedin](https://linkedin.com/in/gustavo-sm)  
[Hackerrank, (**algorithm practice**)](hackerrank.com/gustavosm)  

```Typescript
class Job {
   private _role : string;
   private _company: string;
   constructor(role: string, company: string){
      this._role = role;
      this._company = company;
   }
   public get role() {
      return this._role;
   }
   public get company() {
      return this._company;
   }
}

class Me {
   private _name : string;
   private _job : Job;
   private _age : number;
   
   constructor(name : string, job : Job, age : number) {
      this._name = name;
      this._job = job;
      this._age = age;
   }
   
   public greetings() : string {
      return `Oi :), me chamo ${this._name},\ 
              tenho ${this._age} anos,\  
              e trabalho atualmente como ${this._job.role} no ${this._job.company}.`;
   }
}


const job = new Job('Eng. de software Jr.', 'Itaú Unibanco'),
me = new Me('Gustavo', job, 23);
```
