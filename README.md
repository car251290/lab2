# lab2
lab2 exercises
//exercises 1
 function arrayRotate(arr) {
   return[arr[1],arr[2],arr[3]];
}
var ex=[1,2,3];
console.log(arrayRotate(["1",""]));
//exercises 2
function reverse3(arrey) {
  var arrey=[1,2,3];
  var arrey2=[9,11,5];
  var arrey3=[0,0,7];
  var reverse3 = arrey.reverse();
  var reverse3 = arrey2.reverse();
  var reverse3 = arrey3.reverse();
console.log(reverse(arrey));

//execercise 3
function return3(arr) {
  if (arr[0] == 2 || arr[0] == 3
    || arr[1] == 2 || arr[1] == 3){
    return true;
  } else {
    return false;
  }
}
console.log(arr);
//exercises 4
function fix23(arr){
  var i;
  var arr
  for(i=0;i <arr.length-1; i++){
  if(arr[i]==2,arr[i+1]==3){
  arr[i+1]=0;
  }
  }
  return arr;
}
console.log(fix23([1,2,3]));
//exercises 5
function maxTriple(arr){
    var firts = arr[0];

    var mid = arr[parseInt(arrey.length / 2)];
    var last = arr[arrey.length - 1];
      var all=[first,mid,last];
      var sorted= all.sort();
      console.log(sorted);
      return sorted[2];
    }
//exercises 6
function swapEnds(arrey){
  if(arr.length<=1){
    return arr;
  } else{
    var temp = arr[0];
    arr[0]=arr[arr.lenght-1];
    arr[arr.length-1]=temp;
    return arr;
  }
console.log(swapEnd(arrey));
//exercises 7
function unlucky1(arr){
  if(arr.length<2){
    return false
  }
  if(arr¨[0]=1,arr[1]==3){
    return true;
  }
  if(arr[arr.length-2]==1,arr[arr.length-1]){
    return true;
  }
  return false;

}
	var lastP = arr.length-1;
	if(lastP >= 2){
	if((arr[0] == 1,arr[1] == 3)
  || (arr[1] == 1,arr[2] == 3));
	return true;
	return (arr[lastP-1] == 1,arr[lastP] == 3);
	}
	if(lastP  == 1)
	return ((arr[0] == 1,arr[1] == 3) || (arr[1] == 1,arr[2] == 3));
	return false;
}
console.log(arr);
//exercises 8
function front11(arr1,arr2){
  if(arr1.length==0||arr2.length==0){
    return[];
  }
  else if(arr1.length>0,arr2.length>0){
    return[arr2[0]];
  }
  else if(arr1.length>0,arr2.length>0){
    return[arr1[0],arr2[0]];
  }


	var maxTriple;
  var arr1
	if(a.length >= 1){

		if(b.length >= 1){
			maxTriple = arr1[2];
			maxTriple[0] = a[0];
			maxTriple[1] = b[0];
		}
		else
		{
			maxTriple = arr1[1];
			maxTriple[0] = a[0];
		}
	}
	if(b.length >= 1){
		maxTriple = arr1[1];
		maxTriple[0] = b[0];
	}
	else{
    maxTriple = arr1[0];
  }
	return maxTriple;
}
  console.log(maxTriple);

//exercises 9
function isEverywhere(arrey,num){
  for(var i=0)
  var i
 for(i = 0; i < arrey.length -1; i++) {
   if(arrey[i]!=num && arrey[i+1]!=num) {
     return false;
   }
  return true;
}
console.log(iseverywhere([1,2,1,4,1]));
//exercises 10
function tenRun(array1) {
  var tenMode = -1;
  }
for(i = 0; i < arrey.length;i++){
 if ( array1[i] % 10 == 0){
   tenMode = arr[i];
 }
 else if(tenMode!= -1){
   arr[i]=tenMode;
 }
   return arr;
//exercises 11
function has22(arrey){
if(arr.length== 1 && arr[0]== 2) {
  return false;
}
if(arr.length>1 && (arr[0]==2 && arr[1] != 2)){
  return false;
}
for(var i=1; i<arr[i+1]!= 2 && arr[i-1]!= 2){
  if(arr[i]==2 && arr[i+1]!=2 && arr[i-1]!=2){
    return false;
  }
}
//exercises 12
function shiftLeft(arry){
  arr.push(arr.shift)
  return arr;


  var i
  var arry
	if(arrey.length >= 2){
		arry = [0];
		for(i = 0; i < arrey.length - 1; i++)
			arry[i] = arry[i+1];
		arrey[arrey.length-1] = arry;
	}
	return arry;
}
//exercises 13
function evenOdd(arrey){
  var i
	var temp;
  var evenIndex = 0;
	for(i = 0; i < arrey.length; i++){
		if(arrey[i] % 2 == 0){
			even.push(arr[i]);
      else{
        odd.push(arr[i]);

      }
      return.evenOdd(i);
//exercises 14
function fizzBuzz(start,end) {
  var arr
  var arr1
  var i
    arr.String =  arr1.String(end - start);
    for(i = start; i < end; i++) {
        if(i % 15 == 0) {
            arr.push("fizzbuzz");
        } else if(i % 3 == 0) {
            arr.push ("fizz");
        } else if(i % 5 == 0) {
            arr.push ("buzz");
        } else {
            arr.push ("",i);
        }
    }

    return arr;
}
  //exercises 15
  function countClumps(arry) {
    var count = 0;
  	var clumps = 0;
  	var isClump = false;
    for(var i = 0; i < arry.length -1; i++){
      if(isClump){
      if(arry[i]!= arry[i+1]) {
        isClump = false;
      }
    } else if(arr[i] == arr[i+1]){
      isClump = true;
      count++;
    }
    return count;
  }
