# Dart-List-Map-Set
Dart-List/Map/Set
  List number=[];//ist method of list
  
  number.add(1);//how to add interger in list
  number.add(2);//..........................
  number.add("marry");//how to add string in list
  number[1]=45;//how to update value in list
  print(number);

  
  var list=[1,2,3,"marry","malik"]; //////////////// list...2nd method
 
  print("$list");//simple print
  
  List<String>myinfo=["fname","lname","middle"];/////string type list...third method
  
  
  
  print(myinfo);//simple print
  
  for(String items in myinfo) // how to use  for-in-loop  in list
  {
  
   print(items);         
  
  
}
  
  
  for(int i=0;i<myinfo.length;i++)// how to use simple loop in list
  
  {
    var c=myinfo[i];
    print(c);
  }
  
  
  
  
  
  Set<int>num={1,2,3,4,5,6};//it stores unique value
  
   print(num);//simple print
  
  
  for(int item in num)// how to use for-in-loop in set
  {
    
    print(item);
    
  }
  
  
  for(int i=1;i<=num.length;i++)// how to use simple loop in set
  
  {
   
    print(i);
  }
  
  
  
  
  Map info={"key1":"value1","key2":"value2","key3":"value3","key4":"value4"};//In map key is unique and value may be duplicate for exapme  "key1":"value1" and "key2":"value1"
 
   print(info); //simple print    
  
  {
      for(String key in info.keys)
  {
    
    print("$key : ${info[key]}");
    
  }
    
  }
  
  
  
  
  
  
  
  
  
  
 print("${myinfoo("Marry","Malik",myinfo,phone:032323233,id:534758457485)}");
  
  
  }  //voidddddddddddddddddddddddd   end    
   myinfoo (String name11 ,String name12,List myinfo,{int? phone,int? id} )
                
                  {
                    
                    print(name11);
                  
                     print(name12);
     
       for(String items in myinfo) // how to use  for-in-loop  in list
  {
  
   print(items);         
  
  
}
  if(phone!=null)
  {print(phone);}
                  if(id!=null)
                  {print(id);}
     
                  }

  
