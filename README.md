class for movie class Movie{ constructor(title,studio,rating){ this.title=title; this.studio=studio; this.rating=rating; } getname(){ return ["best rated "+this.rating+" movie"]; } set changerating(updater){ this.rating=updater; }

	}
	let m=new Movie("Casiono Royal","Eon Production","PG13");
	m.changerating="PG14";
	console.log(m);
	console.log(m.getname());
  
  class for circle
  class Circle{
constructor(radius,color){
    this.radius=radius;
    this.colour=color;    
}
get calc(){
    console.log("the properties of the circle are below");
    console.log(this.circleradius());
    console.log(this.Circlecircumference());
    console.log(this.Circlearea());
    }
circleradius(){
    return `the radius is ${this.radius}`;

    }    
Circlecircumference(){
    return `the circumference is ${(this.radius*2*Math.PI).toFixed(2)}`;

}
Circlearea(){
    return `the circlearea is ${(Math.pow(this.radius,3)*4*Math.PI/3).toFixed(2)}`;
}

}
var rad1=new Circle(2.0,"blue");
console.log(rad1);
console.log(rad1.calc);
var rad2=new Circle(4,"red");
console.log(rad2);
console.log(rad2.calc);
class for person class Person{ constructor(name,age,address,heigth,weigt){ this.name=name; this.age=age; this.address=address; this.heigth=heigth; this.weigt=weigt;

}
} let p=new Person("jon",25,"1/23, egmore, chennai","6f","60kg"); console.log(p);

class for uber price class Uber{ constructor(price,distance){ this.price=price; this.distance=distance; } get calc(){ console.log("the Uber service"); console.log(this.ubeprice()); } ubeprice(){ return the uber price ${(this.price*this.distance).toFixed(2)}; } } let prc=new Uber(10,10); console.log(prc.calc);
