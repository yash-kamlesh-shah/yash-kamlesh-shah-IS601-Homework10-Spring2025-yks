# Homework 10

[Dockerhub_Link](https://hub.docker.com/repository/docker/ykshah1309/event_manager/general)

## closed issues:
1\. The nickname used in cURL requests was not the same as the one shown in the example. This caused confusion when using the API. The issue has been fixed to make sure both match for easier understanding and use.

[Issue#1](https://github.com/yash-kamlesh-shah/yash-kamlesh-shah-IS601-Homework10-Spring2025-yks/issues/1)

2\. verifying an email requires a UUID, which is not very convenient. Allowing email verification directly using the email ID would be more user-friendly since emails are unique, just like UUIDs. This change would improve the user experience.

[Issue#3](https://github.com/yash-kamlesh-shah/yash-kamlesh-shah-IS601-Homework10-Spring2025-yks/issues/3)

3\. When creating a new user, an error occurs if the nicknames are similar. However, nicknames should be allowed to be the same, as two people can share the same nickname.

[Issue#5](https://github.com/yash-kamlesh-shah/yash-kamlesh-shah-IS601-Homework10-Spring2025-yks/issues/5)

4\. The issue is that we need to make sure the URLs are correct. Currently, if an incorrect URL is provided, there’s no validation, which could lead to errors later. To fix this, we should validate the URLs, and if they are wrong, an error should be thrown. This can be done by writing tests to check the URLs and ensure they are properly validated before they are used.

[Issue#7](https://github.com/yash-kamlesh-shah/yash-kamlesh-shah-IS601-Homework10-Spring2025-yks/issues/7)

5\. The test_login_request_valid test is failing because the LoginRequest object expects an email field, but the test fixture does not provide this field. To fix this, you need to update the test fixture to include the required email field in the LoginRequest object, ensuring that the test has all necessary data to pass successfully.

[Issue#9](https://github.com/yash-kamlesh-shah/yash-kamlesh-shah-IS601-Homework10-Spring2025-yks/issues/9)



## Learning from this assignment

This assignment was a great learning, not only in technical skills but also in teamwork. The user lifecycle, identification of bugs, and improvement of functions with a QA-focused approach went deep into my understanding of the codebase. Working with Docker Compose taught me how microservices communicate and how to troubleshoot connectivity using tools like pgAdmin. Writing test cases and improving code coverage underlined the importance of robust testing during development.

It was quite a challenge to balance immediate fixes with long-term design goals, but it was very rewarding. The reutilization of functions and systematic solving of problems increased my confidence in handling complex codebases. This experience pinpointed clear communication between the QA and development teams and cemented the importance of structured and detailed-oriented approaches toward the creation of reliable applications.