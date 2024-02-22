## Sprint DEL-102

### [AV] Change OrderPayment update flow

- Deleting `OrderPayment` will create an amending reverse OrderPayment instead of deleting.

  <img width="400" alt="Deleted payment" src="https://upload.wikimedia.org/wikipedia/commons/thumb/b/b6/Image_created_with_a_mobile_phone.png/1200px-Image_created_with_a_mobile_phone.png">

- Deleted payment shown with reason "Manualy deleted" without action.
