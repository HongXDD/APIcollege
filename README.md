===== GET USER ====

curl -X POST http://localhost:3000/zcode/users \
  -H "Content-Type: application/json" \
  -d '{
    "name": "Sarakroetth",
    "email":"sarakroetth@gmail.com",
    "password":"12345678",
    "profile_picture":"https://eandrrnqsieuoqnzyiab.supabase.co/storage/v1/object/public/images//photo_2025-05-14_21-27-04.jpg"
}'
