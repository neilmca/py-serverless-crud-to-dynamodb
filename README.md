To create a todo post

curl --header "Content-Type: application/json" --request POST --data '{"text":"my first note"}' https://kynnc4xgz2.execute-api.eu-west-2.amazonaws.com/dev/todos

Get list of to do items
curl https://kynnc4xgz2.execute-api.eu-west-2.amazonaws.com/dev/todos