let data ="10-15";
let finddata=""
for (let i=0;i<data.length;i++){
  if(data[i]==="+"){
finddata= data[i]
  }
    if(data[i]==="-"){
      finddata=data[i]
    }
      if(data[i]==="*"){
        finddata=data[i]
}
}console.log(finddata)