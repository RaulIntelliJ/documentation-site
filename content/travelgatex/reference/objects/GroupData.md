{
  "title": "GroupData",
  "description": "",
  "weight": 1,
  "fields": [
    {
      "typeString": "ID!",
      "name": "id",
      "url": "/travelgatex/reference/scalars/id",
      "description": "",
      "isDeprecated": "",
      "args": null
    },
    {
      "typeString": "ID!",
      "name": "code",
      "url": "/travelgatex/reference/scalars/id",
      "description": "",
      "isDeprecated": "",
      "args": null
    },
    {
      "typeString": "GroupType!",
      "name": "type",
      "url": "/travelgatex/reference/enums/grouptype",
      "description": "",
      "isDeprecated": "",
      "args": null
    },
    {
      "typeString": "String",
      "name": "info",
      "url": "/travelgatex/reference/scalars/string",
      "description": "",
      "isDeprecated": "",
      "args": null
    },
    {
      "typeString": "Group",
      "name": "parent",
      "url": "/travelgatex/reference/objects/group",
      "description": "",
      "isDeprecated": "",
      "args": null
    },
    {
      "typeString": "Member",
      "name": "owner",
      "url": "/travelgatex/reference/objects/member",
      "description": "",
      "isDeprecated": "",
      "args": null
    },
    {
      "typeString": "Boolean!",
      "name": "isEditable",
      "url": "/travelgatex/reference/scalars/boolean",
      "description": "",
      "isDeprecated": "",
      "args": null
    },
    {
      "typeString": "Int",
      "name": "productId",
      "url": "/travelgatex/reference/scalars/int",
      "description": "",
      "isDeprecated": "",
      "args": null
    },
    {
      "typeString": "Int",
      "name": "resourceId",
      "url": "/travelgatex/reference/scalars/int",
      "description": "",
      "isDeprecated": "",
      "args": null
    },
    {
      "typeString": "MemberConnection",
      "name": "members",
      "url": "/travelgatex/reference/objects/memberconnection",
      "description": "",
      "isDeprecated": "",
      "args": [
        {
          "typeString": "[ID!]",
          "name": "codes",
          "url": "/travelgatex/reference/scalars/id",
          "description": "",
          "isDeprecated": ""
        },
        {
          "typeString": "Int",
          "name": "first",
          "url": "/travelgatex/reference/scalars/int",
          "description": "",
          "isDeprecated": ""
        },
        {
          "typeString": "Int",
          "name": "last",
          "url": "/travelgatex/reference/scalars/int",
          "description": "",
          "isDeprecated": ""
        },
        {
          "typeString": "String",
          "name": "before",
          "url": "/travelgatex/reference/scalars/string",
          "description": "",
          "isDeprecated": ""
        },
        {
          "typeString": "String",
          "name": "after",
          "url": "/travelgatex/reference/scalars/string",
          "description": "",
          "isDeprecated": ""
        }
      ]
    },
    {
      "typeString": "APIConnection",
      "name": "apis",
      "url": "/travelgatex/reference/objects/apiconnection",
      "description": "",
      "isDeprecated": "",
      "args": [
        {
          "typeString": "[ID!]",
          "name": "codes",
          "url": "/travelgatex/reference/scalars/id",
          "description": "",
          "isDeprecated": ""
        },
        {
          "typeString": "Int",
          "name": "first",
          "url": "/travelgatex/reference/scalars/int",
          "description": "",
          "isDeprecated": ""
        },
        {
          "typeString": "Int",
          "name": "last",
          "url": "/travelgatex/reference/scalars/int",
          "description": "",
          "isDeprecated": ""
        },
        {
          "typeString": "String",
          "name": "before",
          "url": "/travelgatex/reference/scalars/string",
          "description": "",
          "isDeprecated": ""
        },
        {
          "typeString": "String",
          "name": "after",
          "url": "/travelgatex/reference/scalars/string",
          "description": "",
          "isDeprecated": ""
        }
      ]
    }
  ],
  "requireby": [
    {
      "name": "Group",
      "description": "",
      "url": "/travelgatex/reference/objects/group"
    }
  ],
  "enumValues": null,
  "operator": "type",
  "typename": "GroupData"
}
## GraphQL Schema definition

{{% graphql-schema-type %}}

## Fields

{{% graphql-field %}}

## Require by

{{% graphql-require-by %}}