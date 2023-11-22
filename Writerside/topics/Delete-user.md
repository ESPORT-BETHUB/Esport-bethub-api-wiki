# Delete user

<note>
    This endpoint is only available for authenticated users.
</note>

This endpoint allows you to smoothly delete own user or another user if you are an admin.

<api-endpoint openapi-path="./../openapi.yaml" endpoint="/api/user/" method="DELETE">
    <request>
        <sample lang="JSON" title="Payload">
        {
            "id": "user_id"
        }
        </sample>
        <sample lang="javascript" title="JavaScript">
        const data = {
            id: "user_id"
        };
        </sample>
    </request>
</api-endpoint>