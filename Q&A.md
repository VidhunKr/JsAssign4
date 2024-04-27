# 1.Write a chained if/else -if statement to fill in the following conditions?
## val<5=>Tiny
## val<10=>Small
## val<15=>Medium
## val<20=>Large
## val<25=>Huge
`var val=9
if (val<5){
   console.log("Tiny");
}else if(val<10){
   console.log("Small");
}else if(val<15){
    console.log("Medium");
}else if(val<20){
   console.log("Large");
}else{
   console.log("Huge");
}`

# 2.Use the switch case and create an application with the following roles?
`admin =>gets full access
 subAdmin =>gets access to create and delete courses
 testPrep =>gets access to create and delete tets
 user =>gets access to consume contents
 let person="subAdmin"
 switch(person){
    case "admin";
    console.log("gets full access");
    break;
    case "subAdmin";
     console.log("gets access to create and delete courses");
      break;
      case "testPrep";
      console.log("gets access to create and delete tets");
        break;
        case "user";
         console.log("gets access to consume contents");
          break;
          default:
           console.log("Invalid option");
 }`
