# Chapter 1 to 4

The book starts off by introducing the idea behind a design pattern, why they are useful and how they originated. The author discusses how the 1994's [Design Patterns](https://en.wikipedia.org/wiki/Design_Patterns) book has shaped many of the current books and at the time revolutionized the industry. The authors of the book became recognized as the "Gang of Four". The book advocates that some of the main advantages behind using design patterns are: 

1. They provide proven solutions to re-occurring problems that previous developer have run into. 
2. They provide out-of-the-box solutions that are easy to share and re-use. 
3. They provide guardrails that prevent smaller issues that can lead to big problems. 
4. At times can provide a blueprint to decreasing code size by avoiding repetitions. 

The author then goes on to discuss what it takes for something to become a design pattern. 

More specifically he discusses: 

1. **"Pattern"-ity test**: It states:    

    1.1 - The pattern solves a particular problem    
    1.2 - The problem has no obvious solution     
    1.3 - The pattern Is a proven concept    
    1.4 - The pattern describes a relationship   

2. **Proto-Patterns**: A pattern that has not had enough time to be fully scrutinized by others. The pattern might be new or has not have had enough time to pass and meet all of the criteria defined in the "Pattern"-ity test. A pattern that is not known to be "good" or "bad" (more on this later)

3. **Rule of Three**: In addition to the "Pattern"-ity test, a proto-pattern must also pass this rule to be considered a pattern. It states that in order for pattern to be valid it mus be measured against the following rules:   

   3.1 - Fitness of purpose: How is the pattern considered successful?    
   3.2 - Usefulness: Why is the pattern considered successful?    
   3.3 - Applicability: Does it have broader applicability? if yes why?
  
The book then provides a template to structure and write a design pattern. This section of the book focuses on "Good" design patterns while the following chapter discusses "anti-patterns". Let's explore the structure of the former first. 

The pattern should contain:      

1. Name   
2. Description   
3. Context    
4. Problem statement    
5. Solution    
6. Design    
7. Example implementation   
8. Illustrations   
9. Examples   
10. Corerequsites   
11. Relations   
12. known usages 
13. discussion   

I was unable to find some real world example of design patterns that follow this structure but I was able to find some that follow a similar structure: 

1. [Example #1](https://refactoring.guru/design-patterns/singleton)
2. [Example #2](https://sourcemaking.com/design_patterns/singleton) 

Both of these examples focus on the Singleton design pattern. An interesting sidebar I discovered while researching is the idea that JS design patterns can be categorized into three different cases: 

1. **Creational Design Patterns**: These patterns deal with object creation mechanisms, trying to create objects in a manner that's suitable to the situation. 

2. **Structural Design Patterns**: These patterns are concerned with class composition and object structure. They help to form larger structures from individual parts, while keeping those parts independent and interchangeable. 

3. **Behavioral Design Patterns**: These patterns define how objects interact and communicate with each other, focusing on the collaboration between objects.

