# payment_matching
Payment matching between bank statement and checkout data from a company.

At Shopee, bank transfer is a payment method in most countries. When a buyer chooses to place an order using bank transfer, he/she is supposed to make the transfer within 2 days after he/she places the order. After he/she makes the transfer, Shopee will receive a bank statement from the bank and Shopee needs to compare and match the bank statement with the checkout information in order to confirm that this particular order has been paid. This process is called payment matching.
Two criteria need to be met in order to match a bank statement with a checkout :
* Amount match : statement amount equals checkout amount.
* Name match : statement description "matches" checkout buyer name.
A proper match occurs when both the amount and the name matches on both bank statement and checkout list. Based on the two criteria, I have matched the bank statement IDs to the checkout IDs. 
