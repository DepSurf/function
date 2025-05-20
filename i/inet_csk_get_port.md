# Function: <code>inet_csk_get_port</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int inet_csk_get_port(struct sock *sk, short unsigned int snum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81763b70)
Location: net/ipv4/inet_connection_sock.c:93
Inline: False
```
**Symbols:**

```
ffffffff81763b70-ffffffff817640a7: inet_csk_get_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int inet_csk_get_port(struct sock *sk, short unsigned int snum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff817d0060)
Location: net/ipv4/inet_connection_sock.c:96
Inline: False
```
**Symbols:**

```
ffffffff817d0060-ffffffff817d05eb: inet_csk_get_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int inet_csk_get_port(struct sock *sk, short unsigned int snum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff817ffe80)
Location: net/ipv4/inet_connection_sock.c:97
Inline: False
```
**Symbols:**

```
ffffffff817ffe80-ffffffff8180043a: inet_csk_get_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int inet_csk_get_port(struct sock *sk, short unsigned int snum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81820f70)
Location: net/ipv4/inet_connection_sock.c:283
Inline: False
```
**Symbols:**

```
ffffffff81820f70-ffffffff818214eb: inet_csk_get_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int inet_csk_get_port(struct sock *sk, short unsigned int snum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff8189fd30)
Location: net/ipv4/inet_connection_sock.c:283
Inline: False
```
**Symbols:**

```
ffffffff8189fd30-ffffffff818a02c4: inet_csk_get_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int inet_csk_get_port(struct sock *sk, short unsigned int snum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff818f4510)
Location: net/ipv4/inet_connection_sock.c:278
Inline: False
```
**Symbols:**

```
ffffffff818f4510-ffffffff818f4b1c: inet_csk_get_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int inet_csk_get_port(struct sock *sk, short unsigned int snum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81922290)
Location: net/ipv4/inet_connection_sock.c:290
Inline: False
```
**Symbols:**

```
ffffffff81922290-ffffffff819229b6: inet_csk_get_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int inet_csk_get_port(struct sock *sk, short unsigned int snum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/inet_connection_sock.c (0)
Location: net/ipv4/inet_connection_sock.c:286
Inline: False
```
**Symbols:**

```
ffffffff81985f07-ffffffff81985f25: inet_csk_get_port.cold (STB_LOCAL)
ffffffff81984a10-ffffffff81985110: inet_csk_get_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int inet_csk_get_port(struct sock *sk, short unsigned int snum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff819bb480)
Location: net/ipv4/inet_connection_sock.c:286
Inline: False
```
**Symbols:**

```
ffffffff819bb480-ffffffff819bbb8d: inet_csk_get_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int inet_csk_get_port(struct sock *sk, short unsigned int snum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81aa7300)
Location: net/ipv4/inet_connection_sock.c:354
Inline: False
Direct callers:
  - net/mptcp/protocol.c:mptcp_get_port
```
**Symbols:**

```
ffffffff81aa7300-ffffffff81aa7632: inet_csk_get_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int inet_csk_get_port(struct sock *sk, short unsigned int snum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81ab1990)
Location: net/ipv4/inet_connection_sock.c:354
Inline: False
Direct callers:
  - net/mptcp/protocol.c:mptcp_get_port
```
**Symbols:**

```
ffffffff81ab1990-ffffffff81ab1cc7: inet_csk_get_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int inet_csk_get_port(struct sock *sk, short unsigned int snum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81a9cc00)
Location: net/ipv4/inet_connection_sock.c:354
Inline: False
Direct callers:
  - net/mptcp/protocol.c:mptcp_get_port
```
**Symbols:**

```
ffffffff81a9cc00-ffffffff81a9cf36: inet_csk_get_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int inet_csk_get_port(struct sock *sk, short unsigned int snum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/inet_connection_sock.c (0)
Location: net/ipv4/inet_connection_sock.c:362
Inline: False
Direct callers:
  - net/mptcp/protocol.c:mptcp_get_port
```
**Symbols:**

```
ffffffff81d3a2c1-ffffffff81d3a2dd: inet_csk_get_port.cold (STB_LOCAL)
ffffffff81b58940-ffffffff81b58c8b: inet_csk_get_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int inet_csk_get_port(struct sock *sk, short unsigned int snum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/inet_connection_sock.c (0)
Location: net/ipv4/inet_connection_sock.c:366
Inline: False
Direct callers:
  - net/mptcp/protocol.c:mptcp_get_port
```
**Symbols:**

```
ffffffff81f06a4c-ffffffff81f06a69: inet_csk_get_port.cold (STB_LOCAL)
ffffffff81ce6b40-ffffffff81ce6ec6: inet_csk_get_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int inet_csk_get_port(struct sock *sk, short unsigned int snum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/inet_connection_sock.c (0)
Location: net/ipv4/inet_connection_sock.c:486
Inline: False
Direct callers:
  - net/mptcp/protocol.c:mptcp_get_port
```
**Symbols:**

```
ffffffff820ae682-ffffffff820ae6bf: inet_csk_get_port.cold (STB_LOCAL)
ffffffff81ea9dc0-ffffffff81eaa5ac: inet_csk_get_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int inet_csk_get_port(struct sock *sk, short unsigned int snum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/inet_connection_sock.c (0)
Location: net/ipv4/inet_connection_sock.c:507
Inline: False
Direct callers:
  - net/mptcp/protocol.c:mptcp_get_port
```
**Symbols:**

```
ffffffff8212fb48-ffffffff8212fb7c: inet_csk_get_port.cold (STB_LOCAL)
ffffffff81f08620-ffffffff81f08dab: inet_csk_get_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int inet_csk_get_port(struct sock *sk, short unsigned int snum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/inet_connection_sock.c (0)
Location: net/ipv4/inet_connection_sock.c:505
Inline: False
Direct callers:
  - net/mptcp/protocol.c:mptcp_get_port
```
**Symbols:**

```
ffffffff822118db-ffffffff82211911: inet_csk_get_port.cold (STB_LOCAL)
ffffffff81fcc980-ffffffff81fcd0df: inet_csk_get_port (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int inet_csk_get_port(struct sock *sk, short unsigned int snum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffff800010c6e0f0)
Location: net/ipv4/inet_connection_sock.c:286
Inline: False
```
**Symbols:**

```
ffff800010c6e0f0-ffff800010c6e7e4: inet_csk_get_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int inet_csk_get_port(struct sock *sk, short unsigned int snum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (c0d7ccac)
Location: net/ipv4/inet_connection_sock.c:286
Inline: False
```
**Symbols:**

```
c0d7ccac-c0d7d38c: inet_csk_get_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int inet_csk_get_port(struct sock *sk, short unsigned int snum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (c000000000d73c30)
Location: net/ipv4/inet_connection_sock.c:286
Inline: False
```
**Symbols:**

```
c000000000d73c30-c000000000d74490: inet_csk_get_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int inet_csk_get_port(struct sock *sk, short unsigned int snum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffe0007d2804)
Location: net/ipv4/inet_connection_sock.c:286
Inline: False
```
**Symbols:**

```
ffffffe0007d2804-ffffffe0007d2d26: inet_csk_get_port (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int inet_csk_get_port(struct sock *sk, short unsigned int snum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff8195b2f0)
Location: net/ipv4/inet_connection_sock.c:286
Inline: False
```
**Symbols:**

```
ffffffff8195b2f0-ffffffff8195b9fd: inet_csk_get_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int inet_csk_get_port(struct sock *sk, short unsigned int snum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81914de0)
Location: net/ipv4/inet_connection_sock.c:286
Inline: False
```
**Symbols:**

```
ffffffff81914de0-ffffffff819154ed: inet_csk_get_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int inet_csk_get_port(struct sock *sk, short unsigned int snum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff819c5ac0)
Location: net/ipv4/inet_connection_sock.c:286
Inline: False
```
**Symbols:**

```
ffffffff819c5ac0-ffffffff819c61cd: inet_csk_get_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int inet_csk_get_port(struct sock *sk, short unsigned int snum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff819cf5a0)
Location: net/ipv4/inet_connection_sock.c:286
Inline: False
```
**Symbols:**

```
ffffffff819cf5a0-ffffffff819cfce2: inet_csk_get_port (STB_GLOBAL)
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
