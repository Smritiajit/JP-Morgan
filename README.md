# JP Morgan

Input file = morgan.txt
Output file = resultLog.txt

How to run the program-
InputReader - This class is basically for reading the sales data.
Parse - This class is for parsing the input line and extracting the product, quantity, price values according to three kinds of messages.
Storage - This class computes the operation and meant for building and displaying log reports.

#Assumptions 
1)All the product are fruit types.
2)Total price is always mentioned in pence.
3)Message type 1 : Orange at 10p. Quantity is taken to be 1 in this message.
4)Message type 2 :20 sales of Orange at 10p each . Here quantity is 20 Product is Orange and price is 10p each. Hence total is 200p
5)Message type 3 :Add 20p apples. Here Addition is performed on price.
6)Plurals aren't considered here. Eg Apple vs Apples. (only apple is taken in input)
7)If message type 1 appears after message type 3 with price not equal to the updated price(message type 3) then only the quantity of the product is incremented by 1 
and the price remain same as the last updated price.Although this is a limitation but This feature depends on the actual sales project and how the company
wants to process that data because same product of different prices should be dealt accordingly.