# Example with merged sources and global entities

## Input

Two sources of customers, crm system and erp system. Erp orders reference customers from the erp system.

## Merge

Merge customers on common property ```company_id```.

## Globals

Enrich merged customers with aggregrated values for order count and the total amount of orders.

## Outputs

Produce a list of VIP customers to the crm system that has an order total greater than 25.
