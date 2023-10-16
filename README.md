# DR2 Start Workflow

A lambda triggered by our dr2-ingest Step Function once an OPEX package has been created and placed in the Preservica source bucket. This Lambda will start a workflow.

[Link to the infrastructure code](https://github.com/nationalarchives/dr2-terraform-environments)

## Environment Variables

| Name                   | Description                                |
|------------------------|--------------------------------------------|
| PRESERVICA_API_URL     | The Preservica API  url                    |
| PRESERVICA_SECRET_NAME | The secret used to call the Preservica API |
