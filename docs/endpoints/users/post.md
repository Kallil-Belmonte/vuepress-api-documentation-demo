# POST

## User

Method responsible for adding a user.

### Endpoint

```sh
POST /user
```

[Send request](https://hopp.sh/r/ikyHoc3Ey7wq '/user')

### Body

Type: `UserToAdd`

| Name        | Type     | Default     | Usage    | Description       |
| ----------- | -------- | ----------- | -------- | ----------------- |
| propertyOne | `string` |             | Required | Description here. |
| propertyTwo | `number` | `undefined` | Optional | Description here. |

### Response

::: details 200: OK

Type: `boolean`

```json
true
```

:::
