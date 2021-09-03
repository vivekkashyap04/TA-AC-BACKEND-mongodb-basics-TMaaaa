writeCode

Write code to:-

- create a database named `mountains`
use mountains

- a collection inside that database named `himalayas`
db.createCollection('himalyas');

- insert 1 document into that collection `{name: 'Dhauldhar range', height: '4000 mtrs'}`
db.himalayas.insert({name: 'Dhauldhar range', height: '4000 mtrs'});

- insert multiple document using insertMany command
db.himalayas.insertMany([{name:'triund',height:'3500 mtrs'},{name:'kailash',height:'5000mts'}]);

- find all documents from mountains
db.himalayas.find();
- find a single document using name
db.himalayas.findOne({name:'triund'});