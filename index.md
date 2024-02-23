## Sprint DEL-102

### [AV] Change OrderPayment update flow

- Deleting `OrderPayment` will create an amending reverse OrderPayment instead of deleting.

  <img width="400" alt="Deleted payment" src="https://upload.wikimedia.org/wikipedia/commons/thumb/b/b6/Image_created_with_a_mobile_phone.png/1200px-Image_created_with_a_mobile_phone.png">

- Deleted payment shown with reason "Manualy deleted" without action.

https://github.com/khoale38/eleventy-page/assets/61538368/ad9e7c44-9e35-4e27-ad98-1b97f333821b

