Hackerrank SQL (BASIC) Skills Certification Test Solution

I have taken HackerRank test on 31st JAN 2024. Certificate can be viewed  
https://www.hackerrank.com/certificates/7287cfa4f790

2 Questions are asked, as of now 2 questions will be asked from these questions, provided the solution also:

1Q. Country Codes :

  Answer :   
                    
            select customer_id , name ,concat (concat ('+',country_code), phone_number) from customers,country_code
            where customers.country=country_codes.country;
 
2Q. Profitable Stocks :

  Answer : 
              
              SELECT price_tomorrow.stock_code from price_today,price_tomorrow 
               where price_today.stock_code= price_tomorrow.stock_code and
                price_tomorrow.price >price_today.price;
