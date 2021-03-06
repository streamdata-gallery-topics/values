---
swagger: "2.0"
x-collection-name: aWhere
x-complete: 1
info:
  title: aWhere API Platform
  description: todo-add-description
  version: 1.0.0
host: api.awhere.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v2/agronomics/fields/field1/agronomicvalues/2015-08-01,2015-08-03:
    get:
      summary: Agronomic Values & Accumulations
      description: "####Request\nThis API call gets calculated agronomics and accumulations
        at a field location. \n\nThe URL used here will get the values for a certain
        range of days. This is a very flexible API and so you're encouraged to review
        the [Agronomics Documentation](http://developer.awhere.com/api/reference/agronomics/values).\n\n_Tip:
        Remember to use a field ID that exists in your account. By default, this collection
        uses a default field ID of 'field1'_\n\n\n####Security\nThis API call uses
        the security Access Token that is retrieved with the \"Get a Token\" request.
        If you run that request first, it will save a token to Postman and this API
        will use it automatically. You can also see where the token should normally
        go by clicking the \"Headers\" tab below. The Authorization header holds the
        token, replacing the \"{{aWhereAccessToken}}\" part."
      operationId: V2AgronomicsFieldsField1Agronomicvalues2015080120150803Get
      x-api-path-slug: v2agronomicsfieldsfield1agronomicvalues2015080120150803-get
      responses:
        200:
          description: OK
      tags:
      - Agriculture
      - Agronomic
      - Values
      - '&'
      - Accumulations
---