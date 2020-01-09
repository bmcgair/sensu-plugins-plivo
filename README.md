## Sensu-Plugins-plivo

## Functionality

## Files
 * bin/handler-plivosms.rb

## Usage

config goes in /etc/sensu/conf.d/plivosms_handler.json

```
{                                                                                                    
  "plivosms":{                                                                                       
    "id":"MANMU5MGY1MZQ3ZDI3ZT",                                                                     
    "token":"MmQ1OWRlM2UxNGI1MzY1MWNlZmY2NjUxOTlkZTBl",                                              
    "number":"14154729809",                                                                           
    "recipients":{                  
      "15034966362": {                                                                        
        "subscriptions":[ "proxy" ],                                                          
        "checks":["foo"],                                                                     
        "cutoff": 1                                                                           
      }
    }
  }
}

```
## Installation

[Installation and Setup](http://sensu-plugins.io/docs/installation_instructions.html)

## Notes
tagged v.0.0.2
