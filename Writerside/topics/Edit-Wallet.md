# Edit Wallet

## Overview

Add or remove funds from a user's wallet.

<note>
    This endpoint requires authentication.
</note>

This endpoint allows you to edit the user's wallet.

<api-endpoint openapi-path="./../openapi.yaml" endpoint="/api/wallet" method="PUT">
    <request>
        <sample lang="JSON" title="Payload">
        {
            "amount": 100,
        }
        </sample>
        <sample lang="javascript" title="JavaScript">
        const data = {
            amount: 100,
        };
        </sample>
    </request>
</api-endpoint>
