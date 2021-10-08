<h1 align="center">Whatopen</h1>

Whatopen is a tool for identify which uses your port.

Usage
---

`curl -sL https://raw.githubusercontent.com/hsbmaulana/whatopen/1.0.0/bin/run | sh -s -- <option>`

Option
---

- `-h` : Usage.
- `-c ...` : Connection type, note that to define `-c` must be before `-b`.
    - tcp *(default)*
    - udp
- `-b ...` : List by specific.
    - all
    - port=...
    - name=...

Author
---

- Hasby Maulana ([@hsbmaulana](https://linkedin.com/in/hsbmaulana))
