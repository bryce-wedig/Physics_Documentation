# Running Simulations on WashU RIS

Fisrt, a few reference webpages. The official documentation is here, starting with the general FAQ: https://docs.ris.wustl.edu/doc/compute/compute-faq.html. For more advanced documentation, this page is pretty good: https://docs.ris.wustl.edu/doc/compute/compute-recipes.html. 

## Getting an account

In order to get an account, go to this link: https://ris.wustl.edu/services/compute/resources/ and click "Request Service". You'll need to log in with your WUSTL Key. Then, click on the first link, which is "Request a NEW Compute Service". You'll need to fill a form, indicating your PI. If you are affiliated with the Physics department, the Cost Center number to use should be CC0001124.

## Logging in

There are 4 log-in nodes that you can connect to: _client-1_, _client-2_, _client-3_, and _client-4_. You can connect to e.g. _client-1_ using:
````
ssh wustlkey@compute1-client-1.ris.wustl.edu
````
Substitute you own WUSTL Key for `wustlkey`, and substitute `client-1` for other clients like `client-3`. Note that you'll need to use the WashU vpn if you connect from outside the campus: https://it.wustl.edu/items/connect/.


It is recommended to set up an SSH key for authentication. A guide is provided by the RIS here: https://docs.ris.wustl.edu/doc/compute/recipes/ssh-keypair.html#ris-ssh-keypair.

