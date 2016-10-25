#  DevTools Proxy

## Usage
```
python3 devtools-proxy.py
```

## How it works

```
                 +---+
+----------+     | D |   +--------------+
| CLIENT 1 |<--->| E |   |  +-------+   |
+----------+     | V |<---->| TAB 1 |   |
+----------+     | T |   |  +-------+   |
| CLIENT 2 |<--->| O |   |  +-------+ C |
+----------+     | O |<---->| TAB 2 | H |
+----------+     | L |   |  +-------+ R |
| CLIENT 3 |<--->| S |   |            O |
+----------+     |   |   |            M |
                 | P |   |            E |
                 | R |   |  +-------+   |
+----------+     | O |<---->| TAB M |   |
| CLIENT N |<--->| X |   |  +-------+   |
+----------+     | Y |   +--------------+
                 +---+
```