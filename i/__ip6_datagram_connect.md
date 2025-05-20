# Function: <code>__ip6_datagram_connect</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __ip6_datagram_connect(struct sock *sk, struct sockaddr *uaddr, int addr_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/datagram.c (ffffffff817f4040)
Location: net/ipv6/datagram.c:43
Inline: False
Direct callers:
  - net/ipv6/datagram.c:ip6_datagram_connect
```
**Symbols:**

```
ffffffff817f4040-ffffffff817f453d: __ip6_datagram_connect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/datagram.c (ffffffff818637f9)
Location: net/ipv6/datagram.c:142
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_connect
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __ip6_datagram_connect(struct sock *sk, struct sockaddr *uaddr, int addr_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/datagram.c (ffffffff81895de0)
Location: net/ipv6/datagram.c:143
Inline: False
Direct callers:
  - net/ipv6/datagram.c:ip6_datagram_connect
```
**Symbols:**

```
ffffffff81895de0-ffffffff818960d5: __ip6_datagram_connect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __ip6_datagram_connect(struct sock *sk, struct sockaddr *uaddr, int addr_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/datagram.c (ffffffff818bc370)
Location: net/ipv6/datagram.c:143
Inline: False
Direct callers:
  - net/ipv6/datagram.c:ip6_datagram_connect
```
**Symbols:**

```
ffffffff818bc370-ffffffff818bc681: __ip6_datagram_connect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __ip6_datagram_connect(struct sock *sk, struct sockaddr *uaddr, int addr_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/datagram.c (ffffffff8193f450)
Location: net/ipv6/datagram.c:143
Inline: False
Direct callers:
  - net/ipv6/datagram.c:ip6_datagram_connect
```
**Symbols:**

```
ffffffff8193f450-ffffffff8193f7a6: __ip6_datagram_connect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __ip6_datagram_connect(struct sock *sk, struct sockaddr *uaddr, int addr_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/datagram.c (ffffffff81998260)
Location: net/ipv6/datagram.c:136
Inline: False
Direct callers:
  - net/ipv6/datagram.c:ip6_datagram_connect
```
**Symbols:**

```
ffffffff81998260-ffffffff819985d1: __ip6_datagram_connect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __ip6_datagram_connect(struct sock *sk, struct sockaddr *uaddr, int addr_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/datagram.c (ffffffff819cebf0)
Location: net/ipv6/datagram.c:136
Inline: False
Direct callers:
  - net/ipv6/datagram.c:ip6_datagram_connect
```
**Symbols:**

```
ffffffff819cebf0-ffffffff819cef4f: __ip6_datagram_connect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __ip6_datagram_connect(struct sock *sk, struct sockaddr *uaddr, int addr_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/datagram.c (ffffffff81a3d8c0)
Location: net/ipv6/datagram.c:133
Inline: False
Direct callers:
  - net/ipv6/datagram.c:ip6_datagram_connect
```
**Symbols:**

```
ffffffff81a3d8c0-ffffffff81a3dc55: __ip6_datagram_connect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __ip6_datagram_connect(struct sock *sk, struct sockaddr *uaddr, int addr_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/datagram.c (ffffffff81a74530)
Location: net/ipv6/datagram.c:133
Inline: False
Direct callers:
  - net/ipv6/datagram.c:ip6_datagram_connect
```
**Symbols:**

```
ffffffff81a74530-ffffffff81a748c5: __ip6_datagram_connect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __ip6_datagram_connect(struct sock *sk, struct sockaddr *uaddr, int addr_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/datagram.c (ffffffff81b6e740)
Location: net/ipv6/datagram.c:133
Inline: False
Direct callers:
  - net/ipv6/datagram.c:ip6_datagram_connect_v6_only
```
**Symbols:**

```
ffffffff81b6e740-ffffffff81b6eada: __ip6_datagram_connect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __ip6_datagram_connect(struct sock *sk, struct sockaddr *uaddr, int addr_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/datagram.c (ffffffff81b7d200)
Location: net/ipv6/datagram.c:134
Inline: False
Direct callers:
  - net/ipv6/datagram.c:ip6_datagram_connect_v6_only
```
**Symbols:**

```
ffffffff81b7d200-ffffffff81b7d595: __ip6_datagram_connect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __ip6_datagram_connect(struct sock *sk, struct sockaddr *uaddr, int addr_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/datagram.c (ffffffff81b6bde0)
Location: net/ipv6/datagram.c:134
Inline: False
Direct callers:
  - net/ipv6/datagram.c:ip6_datagram_connect_v6_only
```
**Symbols:**

```
ffffffff81b6bde0-ffffffff81b6c179: __ip6_datagram_connect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int __ip6_datagram_connect(struct sock *sk, struct sockaddr *uaddr, int addr_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/datagram.c (0)
Location: net/ipv6/datagram.c:134
Inline: False
Direct callers:
  - net/ipv6/datagram.c:ip6_datagram_connect_v6_only
```
**Symbols:**

```
ffffffff81d40f82-ffffffff81d40fae: __ip6_datagram_connect.cold (STB_LOCAL)
ffffffff81c33c70-ffffffff81c34012: __ip6_datagram_connect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int __ip6_datagram_connect(struct sock *sk, struct sockaddr *uaddr, int addr_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/datagram.c (0)
Location: net/ipv6/datagram.c:134
Inline: False
Direct callers:
  - net/ipv6/datagram.c:ip6_datagram_connect_v6_only
```
**Symbols:**

```
ffffffff81f0d8c6-ffffffff81f0d8f2: __ip6_datagram_connect.cold (STB_LOCAL)
ffffffff81dd1500-ffffffff81dd18f1: __ip6_datagram_connect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int __ip6_datagram_connect(struct sock *sk, struct sockaddr *uaddr, int addr_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/datagram.c (0)
Location: net/ipv6/datagram.c:139
Inline: False
Direct callers:
  - net/ipv6/datagram.c:ip6_datagram_connect_v6_only
```
**Symbols:**

```
ffffffff820b4d45-ffffffff820b4d71: __ip6_datagram_connect.cold (STB_LOCAL)
ffffffff81fa2b20-ffffffff81fa2eff: __ip6_datagram_connect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int __ip6_datagram_connect(struct sock *sk, struct sockaddr *uaddr, int addr_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/datagram.c (0)
Location: net/ipv6/datagram.c:139
Inline: False
Direct callers:
  - net/ipv6/datagram.c:ip6_datagram_connect_v6_only
```
**Symbols:**

```
ffffffff82135cc3-ffffffff82135ce6: __ip6_datagram_connect.cold (STB_LOCAL)
ffffffff820033d0-ffffffff820037b8: __ip6_datagram_connect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int __ip6_datagram_connect(struct sock *sk, struct sockaddr *uaddr, int addr_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/datagram.c (0)
Location: net/ipv6/datagram.c:141
Inline: False
Direct callers:
  - net/ipv6/datagram.c:ip6_datagram_connect_v6_only
```
**Symbols:**

```
ffffffff82217911-ffffffff82217934: __ip6_datagram_connect.cold (STB_LOCAL)
ffffffff820d21a0-ffffffff820d258f: __ip6_datagram_connect (STB_GLOBAL)
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
int __ip6_datagram_connect(struct sock *sk, struct sockaddr *uaddr, int addr_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/datagram.c (ffff800010d3cf50)
Location: net/ipv6/datagram.c:133
Inline: False
Direct callers:
  - net/ipv6/datagram.c:ip6_datagram_connect
```
**Symbols:**

```
ffff800010d3cf50-ffff800010d3d294: __ip6_datagram_connect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __ip6_datagram_connect(struct sock *sk, struct sockaddr *uaddr, int addr_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/datagram.c (c0e401ac)
Location: net/ipv6/datagram.c:133
Inline: False
Direct callers:
  - net/ipv6/datagram.c:ip6_datagram_connect
```
**Symbols:**

```
c0e401ac-c0e40550: __ip6_datagram_connect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __ip6_datagram_connect(struct sock *sk, struct sockaddr *uaddr, int addr_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/datagram.c (c000000000e71010)
Location: net/ipv6/datagram.c:133
Inline: False
Direct callers:
  - net/ipv6/datagram.c:ip6_datagram_connect
```
**Symbols:**

```
c000000000e71010-c000000000e71504: __ip6_datagram_connect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __ip6_datagram_connect(struct sock *sk, struct sockaddr *uaddr, int addr_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/datagram.c (ffffffe00087977c)
Location: net/ipv6/datagram.c:133
Inline: False
Direct callers:
  - net/ipv6/datagram.c:ip6_datagram_connect
```
**Symbols:**

```
ffffffe00087977c-ffffffe000879a90: __ip6_datagram_connect (STB_GLOBAL)
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
int __ip6_datagram_connect(struct sock *sk, struct sockaddr *uaddr, int addr_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/datagram.c (ffffffff81a13bc0)
Location: net/ipv6/datagram.c:133
Inline: False
Direct callers:
  - net/ipv6/datagram.c:ip6_datagram_connect
```
**Symbols:**

```
ffffffff81a13bc0-ffffffff81a13f55: __ip6_datagram_connect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __ip6_datagram_connect(struct sock *sk, struct sockaddr *uaddr, int addr_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/datagram.c (ffffffff819d0980)
Location: net/ipv6/datagram.c:133
Inline: False
Direct callers:
  - net/ipv6/datagram.c:ip6_datagram_connect
```
**Symbols:**

```
ffffffff819d0980-ffffffff819d0d15: __ip6_datagram_connect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __ip6_datagram_connect(struct sock *sk, struct sockaddr *uaddr, int addr_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/datagram.c (ffffffff81a7e640)
Location: net/ipv6/datagram.c:133
Inline: False
Direct callers:
  - net/ipv6/datagram.c:ip6_datagram_connect
```
**Symbols:**

```
ffffffff81a7e640-ffffffff81a7e9d5: __ip6_datagram_connect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __ip6_datagram_connect(struct sock *sk, struct sockaddr *uaddr, int addr_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/datagram.c (ffffffff81a8aee0)
Location: net/ipv6/datagram.c:133
Inline: False
Direct callers:
  - net/ipv6/datagram.c:ip6_datagram_connect
```
**Symbols:**

```
ffffffff81a8aee0-ffffffff81a8b291: __ip6_datagram_connect (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
