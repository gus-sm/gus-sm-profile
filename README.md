## Olá =D, bem vindo ao meu GitHub 👋
<div style="display:flex">
   <img src="https://img.shields.io/badge/TypeScript-black?style=flat-square&logo=typescript&logoColor=007ACC"/>
   <img src="https://img.shields.io/badge/-Nodejs-black?style=flat-square&logo=Node.js"/>
   <img src="https://img.shields.io/badge/-MySQL-black?style=flat-square&logo=mysql"/>
   <img src="https://img.shields.io/badge/-Docker-black?style=flat-square&logo=docker"/>
   <img src="https://img.shields.io/badge/Amazon%20AWS-232F3E?style=flat-square&logo=amazon-aws"/>
   <img src="https://img.shields.io/badge/-Git-black?style=flat-square&logo=git"/>
   <img src="https://img.shields.io/badge/-Linux-black?style=flat-square&logo=linux"/>
</div>


  <img src="https://github-readme-stats.vercel.app/api?username=gustavo-sm&show_icons=true&count_private=true&theme=dark" />



##### Caso queira saber mais sobre mim:
<a target="_blank" href="https://linkedin.com/in/gustavo-sm"> Linkedin </a>  
<a target="_blank" href="https://hackerrank.com/gustavosm"> HackerRank (algorithm practice)</a>

```Typescript
const job: Job = new Job('Eng. de software Jr.', 'Itaú Unibanco'),
me: Me = new Me('Gustavo', 23, job);

console.log(me.greetings());

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
   private _age : number;
   private _job : Job;
   
   constructor(name : string, age : number, job : Job) {
      this._name = name;
      this._job = job;
      this._age = age;
   }
   
   public greetings() : string {
      return `Oi :), me chamo ${this._name},\ 
              tenho ${this._age} anos\  
              e trabalho atualmente como ${this._job.role} no ${this._job.company}.`;
   }
}
```
> Oi :), me chamo Gustavo, tenho 23 anos e atualmente trabalho como Eng. de software Jr. no Itaú Unibanco.
