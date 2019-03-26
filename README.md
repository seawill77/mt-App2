# MT-web-APP VUE + SSR + Koa2 + MongoDB

>  this project is based on Vue SSR+Koa2 fullstack technologies, to develop a "meituan" (Chinese Grounpon like) website.

Techonlogies: HTML/CSS、sass/less、JavaScript、Vue2.5、Vuex、Nuxt、Koa2、element-ui、Mongodb ect

## Development Process

Koa2 :
koa-generator
npm install -g koa-generator
koa2 -e project
async and await
koa2 media
koa2 router
redis basic
cookie and session
mongoose basic

function pv(ctx) {
	global.console.log('pv')
}

module.exports = function() {
	return async function(ctx, next) {
		px(ctx)
		await next()
	}
}
mongoose
mongodb installation
www.runoob.com/mongodb/mongodb-osx-install.html
mac : brew installation
which mongod
mongod
mongodb visualization RoBo 3T installation
robomongo.org
mongoose functions:
https://mongoose.shujuwajue.com
mongoose functions;
command POST 
curl -d 'name=lilei&age=26' http://localhost:3000/addPerson
redis
redis introduction:
server save read session 
www.runoob.com/redis
redis-server
npm i koa-generic-session koa-redis
redis functions:
const Kos - require('koa')
const session = require('koa-generic-session')
const Redis = require('koa-redis')

const app = new Koa()
app.keys = ['keys', 'keyskeys'] //  session code
app.use(session({
	key: 'mt',
	prefix: 'mtpr',
	store: new Redis() // 
}))
redis


redis-cli
keys *
get <上一步得到的key值>
Nuxt.js introduction:
base vue2 
 vue router/ vuex （included only when using the store option）
vue server renderer (excluded when using mode: 'spa')
vue-meta
install
https://zh.nuxtjs.org
koa2 project：

vue init nuxt-community/koa-template <project>
nrm npm 
Vue SSR 
（2.0.0）
npm install -g npx
npx create-nuxt-app project-name

element-ui

E-mail verification code：
 qq mail smtp service;
import nodeMailer from 'nodemailer'
passport
npm i koa-passport passport-loal
merge koa
import bodyParser from 'koa-bodyparser'
import session from 'koa-generic-session'
import json from 'koa-json'
regist
：encodeURIComponent(username)
this.$axios
：npm i crypto-js

