1. docker build -t greeter:v1 lessons /02-docker-baasic/homewrk/greeter /app
2. docker run -t greeter -p 9000:8000 greeter:v1
3.   -e GREETING=Shalom
 4. {"message": "Shalom, Rivka!"}
 5. ישתנו השורות מapp.py ומטה כי כך  זה עובד שמהשורה שהשתנתה רץ כצות כל השורות
