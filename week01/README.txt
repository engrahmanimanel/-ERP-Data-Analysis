ERP Assignment Synthetic Dataset

This package contains five internally consistent synthetic datasets created for the Week 01 analytics assignment.

Relationships:
customers.customer_id -> invoices.customer_id
invoices.invoice_id -> sales.invoice_id
products.product_id -> sales.product_id
invoices.invoice_id -> payments.invoice_id

Important analysis note:
- sales.revenue is NET sales revenue after line-level discount and before invoice tax.
- invoices.invoice_value includes subtotal + tax.
- payments.amount_paid is the actual amount paid against invoices.

All data is fictional and created for educational purposes.
