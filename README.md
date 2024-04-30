# Vendor Management System

The Vendor Management System is a Django-based application designed to manage vendor profiles, track purchase orders, and calculate vendor performance metrics. It utilizes Django REST Framework for API development, ensuring efficient and effective management of vendor data.

## Features

- **Vendor Profile Management**: Handle vendor information including names, contact details, and addresses.
- **Purchase Order Tracking**: Track purchase orders with detailed attributes including items, quantity, and status.
- **Vendor Performance Evaluation**: Calculate performance metrics such as on-time delivery rate, quality rating, and fulfillment rate.


## API Endpoints
POST /api/vendors/: Create a new vendor.
GET /api/vendors/: List all vendors.
GET /api/vendors/{vendor_id}/: Retrieve a specific vendor's details.
PUT /api/vendors/{vendor_id}/: Update a vendor's details.
DELETE /api/vendors/{vendor_id}/: Delete a vendor.
POST /api/purchase_orders/: Create a purchase order.
GET /api/purchase_orders/: List all purchase orders.
GET /api/purchase_orders/{po_id}/: Retrieve details of a specific purchase order.
PUT /api/purchase_orders/{po_id}/: Update a purchase order.
DELETE /api/purchase_orders/{po_id}/: Delete a purchase order.

