**URL**: `/topology`

**Method**: `GET`

**Query parameters**:
 - `compact=true|false`: optional, true if the results should be compacted (by default false)

**Description**: returns all [topologies](Topology.md) that the current user has READ permission for.

**Response**: either [`Failed`](../Failed.md) or [`Succeeded`](../Succeeded.md). In case of [`Succeeded`](../Succeeded.md), the `response.topologies` field contains the array of [entity-states](../EntityState.md) of [`topologies`](Topology.md).