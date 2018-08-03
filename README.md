# sfmc-swagger-ui
Testing Swagger UI in Heroku

# Simple Practices



Schema that defines an array of schemas
```yaml 
    S_attribute:
      type: array
      items:
        allOf:
          - $ref: '#/components/schemas/S_RecipientProps'
```

