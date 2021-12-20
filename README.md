# dependences
{
    "result": {
        "timestamp": "2021-12-20T12:39:07.280",
        "status": 201,
        "id": "f2b211a2-2bce-4e9c-9074-fc5c167597e1",
        "code": "CRDP.00006",
        "message": "Document authorize created (pending)"
    },
    "data": {
        "paymentId": "f2b211a2-2bce-4e9c-9074-fc5c167597e1",
        "amount": 12.11,
        "currency": "RUB",
        "authorize": {
            "authorizationId": null,
            "method": "TDS2",
            "createTime": null,
            "tds": null,
            "tds1": null,
            "tds2": {
                "methodUrl": "https://ds.vendorcert.mirconnect.ru/ma",
                "threeDSMethodNotificationURL": "https://mpi-test.rosbank.ru/ThreeDSServer/methodNotificationUrl.jsp?orderId=BE68239A9FE64080",
                "threeDSServerTransId": "7f9644cc-b044-4bf7-9ee3-179e0e126dd5",
                "threeDSMethodData": "eyJ0aHJlZURTTWV0aG9kTm90aWZpY2F0aW9uVVJMIjoiaHR0cHM6Ly9tcGktdGVzdC5yb3NiYW5rLnJ1L1RocmVlRFNTZXJ2ZXIvbWV0aG9kTm90aWZpY2F0aW9uVXJsLmpzcD9vcmRlcklkPUJFNjgyMzlBOUZFNjQwODAiLCJ0aHJlZURTU2VydmVyVHJhbnNJRCI6IjdmOTY0NGNjLWIwNDQtNGJmNy05ZWUzLTE3OWUwZTEyNmRkNSJ9"
            },
            "areq": null,
            "otp": null
        },
        "state": "CONFIRMED",
        "stateInfo": null,
        "updateDate": "2021-12-20T12:38:26.412"
    }
}
