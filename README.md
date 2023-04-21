# giriconst name="sherlock;
console.log("name");
const greet=(name)=>{
console.log('hello,${name}');
}
greet('bhubali');
greet('kattappa');
global.setTimeout(()=>{
console.log('in the timeout');
},5000);
const int=setinterval(()=>{
    console.log('in the every interval');
},5000);
