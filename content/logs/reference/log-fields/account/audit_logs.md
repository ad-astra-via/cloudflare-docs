---
'[ // ]': null
title: Audit logs
---

# Audit logs

The descriptions below detail the fields available for `audit_logs`.

{{<table-wrap>}}

| Field        | Value                                                                                                                                                  | Type          |
| ------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------- |
| ActionResult | Whether the action was successful                                                                                                                      | bool          |
| ActionType   | Type of action taken                                                                                                                                   | string        |
| ActorEmail   | Email of the actor                                                                                                                                     | string        |
| ActorID      | Unique identifier of the actor in Cloudflare's system                                                                                                  | string        |
| ActorIP      | Physical network address of the actor                                                                                                                  | string        |
| ActorType    | Type of user that started the audit trail                                                                                                              | string        |
| ID           | Unique identifier of an audit log                                                                                                                      | string        |
| Interface    | Entry point or interface of the audit log                                                                                                              | string        |
| Metadata     | Additional audit log-specific information. Metadata is organized in key:value pairs. Key and Value formats can vary by ResourceType.                   | object        |
| NewValue     | Contains the new value for the audited item                                                                                                            | object        |
| OldValue     | Contains the old value for the audited item                                                                                                            | object        |
| OwnerID      | The identifier of the user that was acting or was acted on behalf of. If a user did the action themselves, this value will be the same as the ActorID. | string        |
| ResourceID   | Unique identifier of the resource within Cloudflare's system                                                                                           | string        |
| ResourceType | The type of resource that was changed                                                                                                                  | string        |
| When         | When the change happened                                                                                                                               | int or string |

{{</table-wrap>}}
