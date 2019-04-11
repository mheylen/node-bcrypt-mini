Authentication - Identifing who is requesting the information. It's the process of verifying an individuals entity or website is who is claims to be.

authenticate usually is done through username and passwords.

Encode
Encoding tansforms data into another format using pubicly available schemes and is easily reversible.
 - all you need to decode is the algorithm used to encode.

 Basic Auth. Basic Auth doesn't provide confidentiality protection.

 Form-Based Auth. HTML form, enter credentials, info sent to server.
 HTTPS =>

 Hashing: Another way to protect data
 User Password => Hashing Algorthm => End User password is different.

 Hashed passwords become random string of characters.
 not intended to ever be unhashed
 server stores shashed password, not original.
 same input, same algorithm, same hash.

 Hash and Salt
 Best practices:
 If you are hashing passwords, you should also salt.
 User Password + Salt Value = Hash Algorithm => Hash Value

 Encoding - Encoding - Transofrming data, goal is not to keep it secret. Ensures data can be properly consu,ed by another system.

 Encryption: Goal is to keep data secret from others.
 Hash: goal is to protect data and ensure integrity.

