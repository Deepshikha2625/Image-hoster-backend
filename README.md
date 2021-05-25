 In this Project helps to understand how the API enpoints can be implemented for different functionalities and observe the results on Swagger - UI.and also gives the concept of how to develop REST API endpoints in the following controllers:

Signup-controller: In this controller, the user will able to sign up for an account.

Authentication-controller: After signing up, the user needs to sign in. This controller authenticates the user based on the credentials provided. After authentication, the user will be given an ‘access token’, which will be required to perform any further operation.

Image-upload-controller: Using the ‘access token’, the user can upload an image through this controller. But the image is not ‘ACTIVE’ until reviewed by the admin.

Admin-controller: The admin needs to review all the images uploaded by users. This controller provides the admin with the details about all the images. Once the admin has reviewed the image, he can update it (if needed) and make it ‘ACTIVE’ through this controller.

Run the application on http://localhost:8080/api/swagger-ui.html and observe the signup-controller.

![Screenshot (180)](https://user-images.githubusercontent.com/72148597/119541979-a9756600-bdac-11eb-99cb-5d0ee5682ff6.png)
