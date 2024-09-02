var names=new Array();
names[0]="hora";
names[1]="sara";
names[2]="paul";
names[3]="maxy";
names[4]="jimmy";
names[5]="alexa";
names[6]="larry";
names[7]="johnsena";
names[8]="jenifer";
for (var i=0;i<names.length;i++){
	if(names[i].charAt(0)==='J'||names[i].charAt(0)==='j'){
	console.log("Goodbye"+ names[i]);
}
else{
	console.log("Hello"+names[i])
}
}
