# NeuralShare
make AI models accessible for free from any device, regardless of its hardware resources

**Feb 1, 2023: the development of the node application is well advanced and is almost ready. It will be simple to use and will also allow you to choose the maximum response per hour you want to send. Also, even if it's listening, the app won't send any response if the nodes aren't at least a reasonable number. Join Discord for updates: [**https://discord.gg/77cMV3M42V**](https://discord.gg/77cMV3M42V)**

![](https://user-images.githubusercontent.com/114559605/215350290-eed2157c-ba6a-4560-ad07-6ec37933273b.jpg)

[**NeuralShare.network**](http://neuralshare.network)

[**Twitter**](https://twitter.com/neuralshare)

[**Discord**](https://discord.gg/77cMV3M42V)


## In short
the client sends a transaction to a predetermined Stellar address on the Test Network with a text memo containing the prompt . The servers will be perpetually listening on that specific Stellar address waiting for new transactions. Whenever there is a new transaction, the server that sees it first sends the response to the "sender" Stellar address using its apikey, this way anyone could use to communicate with gpt-3 just by sending a Stellar transaction.. Theoretically , each time a different server will take charge of the transaction, given that the more servers or "nodes" there are, the less likely it will be that the same node will take charge of it several times in a row. Also, the more nodes there are, the lower the expense (in terms of text tokens if you are using gpt-3) will be for each node. in fact, each node should listen on that chosen address and should then use its own apikey to send the response. Of course, if there was only one node doing all this, poor thing, he would soon be covered in debt. But if so many others were added, the cost for each one would be lower the more the number of nodes increases. This could theoretically allow, thanks to those who decide to run a node, to be able to use gpt-3 completely free for the client, while the nodes will have an expense which, if the number of nodes were high, would be very small.
**`GAU3XW7Z5OYR7BFANSB7HGVGJRZJ5NSJ3ERWJ5HRVZRCHFSRTQ32YPEM`** ,  which is the Stellar address corresponding to the [`neuralshare` keybase account](https://keybase.io/neuralshare), could be used as the Stellar address for this purpose.
**This would also allow all those devices with few CPU and GPU resources to use all those AI models that require high resources instantly and for free, and wherever they are (you will only need an internet connection, even a low one).**

**we are developing a very light node application and a client application (which will also be web). Stay updated on the channels you find at the top of this README, to make this possible WE NEED YOU, all the necessary informations to participate will soon be available, it will ALWAYS be completely free and accessible to all)**




## Problems with this method:
1) **(solved)** Anyone could send a transaction to that address, even for other purposes. How could a node only filter transactions that were sent for the purpose of communicating with gpt? This is the first problem.

2) **(partially solved)** How do you know what is the number of nodes that are actually running? Anyone could, on their own, create their own system to listen for new transactions on that address and send the reply, but you would never know. Unless you create and use a standard "node app" that adds up all the ones they're using, for example. Even in this case, however, someone could decide not to use the standard app but to do it all by themselves. So you could not know for sure how many nodes there are in reality and this is a problem for calculating the costs for each node.

please share your ideas and thoughs on [**DISCORD**](https://discord.gg/77cMV3M42V)

