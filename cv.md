Resume

Andrey Somov

Phone number 8044-793-49-91, Skype: Soomoff.

About me: Half a year studying js html css and studying Angular right now. Im responsible and easily trained. 
As an intern, I will study faster and in the future I will benefit the company.

Last code example:
module.exports = function getZerosCount(n, k) {
  let obj = {}, result=n, cloneK=k;
  for(let i=2; i<=cloneK; i++){
    while(cloneK%i==0){
      obj[i] ? obj[i]++ : obj[i]=1;
      cloneK/=i;
    }
  }
  for(let key in obj){
    let cloneN = n, res=0;
    while(cloneN){
      res += Math.floor(cloneN/+key);
      cloneN = Math.floor(cloneN/+key) 
    }
    result=Math.min(result, Math.floor(res/obj[key]))
  }
  return result;
}

English level: A2 Pre-Intermediate.