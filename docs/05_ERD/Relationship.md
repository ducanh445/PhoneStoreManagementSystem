\# Relationship Overview



```mermaid

graph TD



Brand --> Product

Category --> Product

Product --> ProductVariant

ProductVariant --> IMEI



Store --> Employee

Employee --> User



Supplier --> PurchaseOrder

PurchaseOrder --> PurchaseOrderDetail



Customer --> Invoice

Invoice --> InvoiceDetail

InvoiceDetail --> IMEI

```

