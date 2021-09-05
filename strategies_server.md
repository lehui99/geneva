The following is a library of strategies for server, the countries they work in, and their average success rates in those countries. See the readme or our paper for an explanation of the strategy DNA format.  


| Strategy 	| China 	| Kazakhstan 	| India 	|
|------------------------------------------------------------------------------------------------------	|-------	|------------	|-------	|
| `[TCP:flags:SA]-tamper{TCP:flags:replace:S}(duplicate(duplicate,tamper{TCP:seq:corrupt}),)-\|` 	|  	|  	|  	|
| `[TCP:flags:SA]-tamper{TCP:window:replace:4}-\|` 	|  	|  	|  	|
| `[TCP:flags:SA]-duplicate(tamper{TCP:ack:corrupt},)-\|` 	|  	|  	|  	|
| `[TCP:flags:SA]-duplicate(tamper{TCP:flags:replace:FS},)-\|` 	|  	|  	|  	|
