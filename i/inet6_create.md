# Function: <code>inet6_create</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int inet6_create(struct net *net, struct socket *sock, int protocol, int kern);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/af_inet6.c (ffffffff817c3190)
Location: net/ipv6/af_inet6.c:100
Inline: False
```
**Symbols:**

```
ffffffff817c3190-ffffffff817c34f3: inet6_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int inet6_create(struct net *net, struct socket *sock, int protocol, int kern);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/af_inet6.c (ffffffff81830200)
Location: net/ipv6/af_inet6.c:109
Inline: False
```
**Symbols:**

```
ffffffff81830200-ffffffff818305a4: inet6_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int inet6_create(struct net *net, struct socket *sock, int protocol, int kern);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/af_inet6.c (ffffffff81861c80)
Location: net/ipv6/af_inet6.c:110
Inline: False
```
**Symbols:**

```
ffffffff81861c80-ffffffff8186202b: inet6_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int inet6_create(struct net *net, struct socket *sock, int protocol, int kern);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/af_inet6.c (ffffffff81886410)
Location: net/ipv6/af_inet6.c:110
Inline: True
```
**Symbols:**

```
ffffffff81886410-ffffffff81886816: inet6_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int inet6_create(struct net *net, struct socket *sock, int protocol, int kern);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/af_inet6.c (ffffffff81907620)
Location: net/ipv6/af_inet6.c:110
Inline: True
```
**Symbols:**

```
ffffffff81907620-ffffffff81907a0a: inet6_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int inet6_create(struct net *net, struct socket *sock, int protocol, int kern);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/af_inet6.c (ffffffff8195e1d0)
Location: net/ipv6/af_inet6.c:110
Inline: True
```
**Symbols:**

```
ffffffff8195e1d0-ffffffff8195e5b7: inet6_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int inet6_create(struct net *net, struct socket *sock, int protocol, int kern);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/af_inet6.c (ffffffff81992d30)
Location: net/ipv6/af_inet6.c:110
Inline: True
```
**Symbols:**

```
ffffffff81992d30-ffffffff81993124: inet6_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int inet6_create(struct net *net, struct socket *sock, int protocol, int kern);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/af_inet6.c (0)
Location: net/ipv6/af_inet6.c:107
Inline: True
```
**Symbols:**

```
ffffffff819fe7c0-ffffffff819febb2: inet6_create (STB_LOCAL)
ffffffff819ff676-ffffffff819ff691: inet6_create.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int inet6_create(struct net *net, struct socket *sock, int protocol, int kern);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/af_inet6.c (ffffffff81a353b0)
Location: net/ipv6/af_inet6.c:107
Inline: True
```
**Symbols:**

```
ffffffff81a353b0-ffffffff81a357a4: inet6_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int inet6_create(struct net *net, struct socket *sock, int protocol, int kern);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/af_inet6.c (ffffffff81b2a280)
Location: net/ipv6/af_inet6.c:110
Inline: True
```
**Symbols:**

```
ffffffff81b2a280-ffffffff81b2a66b: inet6_create.part.0 (STB_LOCAL)
ffffffff81b2a670-ffffffff81b2a68e: inet6_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int inet6_create(struct net *net, struct socket *sock, int protocol, int kern);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/af_inet6.c (ffffffff81b38be0)
Location: net/ipv6/af_inet6.c:110
Inline: True
```
**Symbols:**

```
ffffffff81b38be0-ffffffff81b38fe1: inet6_create.part.0 (STB_LOCAL)
ffffffff81b38ff0-ffffffff81b3900e: inet6_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int inet6_create(struct net *net, struct socket *sock, int protocol, int kern);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/af_inet6.c (ffffffff81b268d0)
Location: net/ipv6/af_inet6.c:110
Inline: True
```
**Symbols:**

```
ffffffff81b268d0-ffffffff81b26cc9: inet6_create.part.0 (STB_LOCAL)
ffffffff81b26cd0-ffffffff81b26cee: inet6_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int inet6_create(struct net *net, struct socket *sock, int protocol, int kern);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/af_inet6.c (ffffffff81bec3c0)
Location: net/ipv6/af_inet6.c:111
Inline: True
```
**Symbols:**

```
ffffffff81bec3c0-ffffffff81bec908: inet6_create.part.0 (STB_LOCAL)
ffffffff81bec910-ffffffff81bec92e: inet6_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
int inet6_create(struct net *net, struct socket *sock, int protocol, int kern);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/af_inet6.c (ffffffff81d84920)
Location: net/ipv6/af_inet6.c:112
Inline: True
```
**Symbols:**

```
ffffffff81d84920-ffffffff81d84d9e: inet6_create.part.0 (STB_LOCAL)
ffffffff81d84da0-ffffffff81d84dd6: inet6_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
int inet6_create(struct net *net, struct socket *sock, int protocol, int kern);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/af_inet6.c (ffffffff81f52330)
Location: net/ipv6/af_inet6.c:119
Inline: True
```
**Symbols:**

```
ffffffff81f52330-ffffffff81f527b5: inet6_create.part.0 (STB_LOCAL)
ffffffff81f527d0-ffffffff81f52806: inet6_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
int inet6_create(struct net *net, struct socket *sock, int protocol, int kern);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/af_inet6.c (ffffffff81fb1d40)
Location: net/ipv6/af_inet6.c:119
Inline: True
```
**Symbols:**

```
ffffffff81fb1d40-ffffffff81fb21bf: inet6_create.part.0 (STB_LOCAL)
ffffffff81fb21d0-ffffffff81fb2206: inet6_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int inet6_create(struct net *net, struct socket *sock, int protocol, int kern);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/af_inet6.c (ffffffff8207f460)
Location: net/ipv6/af_inet6.c:119
Inline: True
```
**Symbols:**

```
ffffffff8207f460-ffffffff8207f910: inet6_create.part.0 (STB_LOCAL)
ffffffff8207f920-ffffffff8207f956: inet6_create (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int inet6_create(struct net *net, struct socket *sock, int protocol, int kern);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/af_inet6.c (ffff800010cf5e20)
Location: net/ipv6/af_inet6.c:107
Inline: True
```
**Symbols:**

```
ffff800010cf5e20-ffff800010cf61a8: inet6_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int inet6_create(struct net *net, struct socket *sock, int protocol, int kern);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/af_inet6.c (c0dfc95c)
Location: net/ipv6/af_inet6.c:107
Inline: True
```
**Symbols:**

```
c0dfc95c-c0dfccdc: inet6_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int inet6_create(struct net *net, struct socket *sock, int protocol, int kern);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/af_inet6.c (c000000000e1c330)
Location: net/ipv6/af_inet6.c:107
Inline: True
```
**Symbols:**

```
c000000000e1c330-c000000000e1c728: inet6_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int inet6_create(struct net *net, struct socket *sock, int protocol, int kern);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/af_inet6.c (ffffffe0008417c4)
Location: net/ipv6/af_inet6.c:107
Inline: True
```
**Symbols:**

```
ffffffe0008417c4-ffffffe000841a7e: inet6_create (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int inet6_create(struct net *net, struct socket *sock, int protocol, int kern);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/af_inet6.c (ffffffff819d4a40)
Location: net/ipv6/af_inet6.c:107
Inline: True
```
**Symbols:**

```
ffffffff819d4a40-ffffffff819d4e34: inet6_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int inet6_create(struct net *net, struct socket *sock, int protocol, int kern);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/af_inet6.c (ffffffff81991800)
Location: net/ipv6/af_inet6.c:107
Inline: True
```
**Symbols:**

```
ffffffff81991800-ffffffff81991bf4: inet6_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int inet6_create(struct net *net, struct socket *sock, int protocol, int kern);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/af_inet6.c (ffffffff81a3f4c0)
Location: net/ipv6/af_inet6.c:107
Inline: True
```
**Symbols:**

```
ffffffff81a3f4c0-ffffffff81a3f8b4: inet6_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int inet6_create(struct net *net, struct socket *sock, int protocol, int kern);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/af_inet6.c (ffffffff81a4afc0)
Location: net/ipv6/af_inet6.c:107
Inline: True
```
**Symbols:**

```
ffffffff81a4afc0-ffffffff81a4b3db: inet6_create (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
