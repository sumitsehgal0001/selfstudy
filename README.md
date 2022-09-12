# selfstudy



**################################################## Concepts ###################################################**
1. Node s1 = new Node();
    Node s2 = new Node();
    one=second; // means pointing to same memory in heap
    Node s3 = new Node();
    s2=s3; // now s2 pointing to s3 memory space but s1 is still pointing to its memory space it will not point to s2 & s3 space.
2. passing null in permitive using ternary operator, will give nullpointer
     int data=0;
         data=orignalNode.arb !=null ?orignalNode.arb.data :null;
3. In a programme we have to take 3 inputs from user using  Scanner sc= new Scanner(System.in);  int a= sc.nextInt(); then if we pass multiple inputs in console sperated by space then it will skip 2nd and 3rd input ask step .
![image](https://user-images.githubusercontent.com/41359231/189638251-fe4614f8-edfd-4911-976d-a5326a49da66.png)

         

**################################################## Linked list ################################################**
ll/LL = linked list
SLL = Singly linked list
**Doubly linked list= DLL**
 1. Doubly LL can be circular
 
**Circular linked list= CLL**
1. Avoid head pointer, all we can do with tail only

**Approaches to solve questions**

1. slow & fast variables approach
2. map appraoch
3. mid in ll by slow and fast method

**Questions**
1. reverse SLL :- iterative & recursive approach.
2. find middle node/value in  SLL :- 
   -> Basic approach = find length then middle index then value or node
   -> sow & fast approach = move fast by 2, slow by 1 when fast ==null then slow is the answer
   
3. 0,1,2 = 

	-> Basic count all three and alter/insert in same array/ll
	-> make 3 ll for 0,1,2 and merge all
	-> three pointer (low, mid, high approach) - if ll is doubly
	
4. merge two sorted ll (merging ll is different from adding 3 ll into another or 4rth ll)
5. check pallindrom in sll
6. clone a ll
7. merge sort in ll


          
