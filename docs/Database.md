# Expert Finance Database

## Tables

### users
- id
- full_name
- email
- password
- role

### accounts
- id
- name
- type
- balance

### incomes
- id
- customer_name
- service_name
- amount
- received_amount
- remaining_amount
- date
- account_id
- user_id
- note
- status

### recurring_incomes
- id
- customer_name
- service_name
- amount
- payment_day
- active

### expenses
- id
- category
- amount
- date
- account_id
- user_id
- note

### receivables
- id
- customer_name
- amount
- paid
- remaining
- due_date

### payables
- id
- supplier_name
- amount
- paid
- remaining
- due_date

### transfers
- id
- from_account
- to_account
- amount
- date

### history
- id
- action
- user
- date
