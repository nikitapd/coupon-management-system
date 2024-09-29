# coupon-management-system
# Coupon API  This is a RESTful API for managing different types of discount coupons for an e-commerce platform. The API supports cart-wise, product-wise, and buy X get Y coupons.

## Implemented Cases

1. **Cart-wise Coupons**: Apply a discount to the entire cart if the total exceeds a specified threshold.
2. **Product-wise Coupons**: Apply a discount to specific products in the cart.
3. **CRUD Operations**: Create, Retrieve, Update, and Delete coupons.

## Unimplemented Cases

1. **BxGy Coupons**: While the structure is in place, logic for applying buy X get Y coupons was not implemented due to time constraints.
2. **Expiration Dates**: Coupons do not currently support expiration dates.

## Limitations

- The current implementation does not support complex coupon logic (e.g., stacking multiple coupons).
- Only basic error handling is implemented.

## Assumptions

- The cart is always passed in a valid format.
- Product IDs are unique and exist in the product database.

## Future Improvements

- Implement BxGy coupon logic.
- Add support for expiration dates.
- Improve error handling and validation.
- Expand unit tests for full coverage.

## API Endpoints

- `POST /coupons`: Create a new coupon.
- `GET /coupons`: Retrieve all coupons.
- `GET /coupons/{id}`: Retrieve a specific coupon.
- `PUT /coupons/{id}`: Update a specific coupon.
- `DELETE /coupons/{id}`: Delete a specific coupon.
