**URL**: `/permission/{permission-id}`

**Method**: `POST`

**Query parameters**:
 - `dryrun=true|false`: optional, true if kafkakewl should just simulate what would happen (by default false)

**Request Body**: a [permission](Permission.md)

**Description**: creates a new [permission](Permission.md) with the specified id, if the current user is a super-user.

**Response**: either [`Failed`](../Failed.md) or [`Succeeded`](../Succeeded.md). In case of [`Succeeded`](../Succeeded.md), the `response` field is null.