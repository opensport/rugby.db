# Welcome to `rugby.db`

Free open public domain rugby database 'n' schema (`rugby.db`)
for use in any (programming) language e.g. uses plain text datasets.

Tournaments include:

- Rugby World Cup 2015 England (Sep/18 - Oct/31; 20 National Teams)


Example:

```
##################################
#  Rugby World Cup 2015 England

Pool A  |  Australia     England    Wales     Fiji     Uruguay
Pool B  |  South Africa  Samoa      Scotland  Japan    United States
Pool C  |  New Zealand   Argentina  Tonga     Georgia  Namibia
Pool D  |  France        Ireland    Italy     Canada   Romania


Matchday 1  |  Fri Sep/18 
Matchday 2  |  Sat Sep/19
Matchday 3  |  Sun Sep/20

...

Pool A:

 (1) Fri Sep/18   England   35-11   Fiji       @ Twickenham Stadium, London
 (7) Sun Sep/20   Wales       v     Uruguay    @ Millennium Stadium, Cardiff
(10) Wed Sep/23   Australia   v     Fiji       @ Millennium Stadium, Cardiff
(16) Sat Sep/26   England     v     Wales      @ Twickenham Stadium, London
(17) Sun Sep/27   Australia   v     Uruguay    @ Villa Park, Birmingham
(21) Thu Oct/1    Wales       v     Fiji       @ Millennium Stadium, Cardiff
(26) Sat Oct/3    England     v     Australia  @ Twickenham Stadium, London
(30) Tue Oct/6    Fiji        v     Uruguay    @ Stadium mk, Milton Keynes

...
```


## Build Your Own `rugby.db` Copy

Use the `sportdb` command line tool to build your own `rugby.db` copy
from the plain text datasets.

### Examples

Build the database for all leagues and seasons (using the included [Datafile](Datafile)):

    $ sportdb build



## License

The `rugby.db` schema, data and scripts are dedicated to the public domain.
Use it as you please with no restrictions whatsoever.

## Questions? Comments?

Send them along to the [Open Sports Database & Friends Forum/Mailing List](http://groups.google.com/group/opensport).
Thanks!
