# Integration for GoHighLevel <img src="https://images.leadconnectorhq.com/image/f_webp/q_80/r_1200/u_https://assets.cdn.filesafe.space/knES3eSWYIsc5YSZ3YLl/media/679a9bb431492763982fd8eb.png" style="width:150px">

## Description
The integration allows you to receive data on the webhook and perform basic actions in GoHighLevel (create/update a contact or opportunity)

## Manual for use
1. Set up variable mapping from the data received by your webhook
2. Rename .env_example to .env and insert your API key generated in GoHighLevel.
3. Replace "your_pipeline_id" and "your_stage_id" with the IDs you need for your CRM. You can get the ID using the additional application get_pipeline_id.py by running it <i>python .\get_pipeline_id.py</i> or <i>python3 .\get_pipeline_id.py</i>
4. Run ghl.py via docker, pm2 or other services

## Additional information
Logging is configured for integration, with the capture of data received on the webhook, all actions and errors. For more convenient searching, each new set of data received on the webhook has its own ID
