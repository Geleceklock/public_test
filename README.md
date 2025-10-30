# demo test content for sensitive scanner - all fake, safe
# 1. Fake private key block (PEM-like)
-----BEGIN RSA PRIVATE KEY-----
MIIEpAIBAAKCAQEA0FakePrivateKeyBlockDataThatIsLongButNotReal==
FakeLineFakeLineFakeLineFakeLineFakeLineFakeLineFakeLine
-----END RSA PRIVATE KEY-----

# 2. Fake AWS Access Key pattern
aws_access_key_id = "AKIAFAKEEXAMPLE00000000"

# 3. Fake AWS Secret-like (40 chars)
aws_secret_access_key = "abcdEFGHijklMNOPqrstUVwxYZ0123456789ABCD"

# 4. Fake JWT token (header.payload.signature)
# Note: these are base64-like strings but not valid keys
auth_token = "eyJhbGciOiJIUzI1NiJ9.eyJzdWIiOiJ1c2VySWQiLCJuYW1lIjoiVGVzdCJ9.SflKxwRJSMeKKF2QT4fwpMeJf36POk6yJV_adQssw5c"

# 5. Fake DB connection string
DATABASE_URL="postgresql://dbuser:FakePass123@db.example.com:5432/mydb"

# 6. Generic API key assignment
API_KEY = "sk_test_FAKEKEY_1234567890abcdef"

# 7. Email and phone (for low/medium risk rules)
contact: security-team@example.com
mobile: 13800138000

# 8. Chinese ID-like pattern (fake)
id_card: 11010519900307823X

# 9. credential in URL style
http://admin:password123@insecure.example.com/dashboard

# 10. comment with a fake credit card-like number (for demonstration only)
# 4111111111111111
