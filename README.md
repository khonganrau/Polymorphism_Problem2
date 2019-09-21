# **Polymorphism- _Problem2: Animals_**
## **Problem 02**
### _**Animals**_
> _**NOTE:**_ Creating a public _**StartUp**_ class with the namespace _**Animals**_.  

Create a class _**Animal**_, which holds two fields:
* name : string
* favouriteFood : string

Animal has one virtual method ExplainSelf(): string.  
You should add two new classes - _**Cat**_ and _**Dog**_. _**Override**_ the _**Explainself()**_ method by adding concrete animal soud on a new line.

## **Examples of Output**
|**Output**|
-----------|
I am Pesho and my favourite food is Whiskas | 
MEEOW |
I am Gosho and my favourite food is Meat |
 DJAAF |

## **Solution**
1. Create new folder with name _**Models**_ to contains the sub-class.
   ![Imgur](https://i.imgur.com/95JFurz.png)  

2. Create a class _**Animal**_ with holds two fields name and favouriteFood. This is a base class.
   ![Imgur](https://i.imgur.com/Xz1g4if.png)  

3. In this base class contain one virtual method _**ExplainSelf()**_.  
   ![Imgur](https://i.imgur.com/XVSaVKa.png)  

4. Adding two classes _**Cat**_ and _**Dog**_ into the _**Models**_ folder. Within both of the classes contain _**Override**_ the _**ExplainSelf()**_ method by adding concrete animal sound on a new line. Within the _**ExpainDelf**_ method, we using _**StringBuider**_ to expand the number of characters in the string (to add the sound of animal), and using _**StringBuider.Append(valueToAppend)**_ and _**AppendLine**_ - to append the passed value to the end of the current _**StringBuilder**_ objects.
      
   ![Imgur](https://i.imgur.com/3HKCHFj.png)  

   ![Imgur](https://i.imgur.com/VPbM0on.png)  

   ![Imgur](https://i.imgur.com/rpCpAhX.png)  


5. In the _**Program.cs**_, we adding using _**Models**_ folders on th refferences scape.
   ![Imgur](https://i.imgur.com/3ltGoMa.png)  
   
6. In the main program, we create a new cat and dog by calling the sub-class in _**Models**_ folders.
   ![Imgur](https://i.imgur.com/YeyOlaL.png)  

7. Finally, we called _**ExplainSelf()**_ method in _**Cat**_ class and _**Dog**_ class.
   ![Imgur](https://i.imgur.com/DxHlfWI.png)