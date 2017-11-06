# Example with merged sources and global entities

## Input

Two sources of customers, customer system and order system. Orders reference customers from the order system.

## Merge

Merge customers on common property ```company_id```.

## Globals

Enrich merged customers with aggregrated values for order count and the total amount of orders.

## Outputs

Produce a list of VIP customers to the customer system that has an order total greater than 25.
