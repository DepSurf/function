# Function: <code>inet_csk_accept</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct sock *inet_csk_accept(struct sock *sk, int flags, int *err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81764e50)
Location: net/ipv4/inet_connection_sock.c:303
Inline: False
```
**Symbols:**

```
ffffffff81764e50-ffffffff81765193: inet_csk_accept (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct sock *inet_csk_accept(struct sock *sk, int flags, int *err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff817d13d0)
Location: net/ipv4/inet_connection_sock.c:298
Inline: False
```
**Symbols:**

```
ffffffff817d13d0-ffffffff817d1713: inet_csk_accept (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct sock *inet_csk_accept(struct sock *sk, int flags, int *err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81801290)
Location: net/ipv4/inet_connection_sock.c:302
Inline: False
```
**Symbols:**

```
ffffffff81801290-ffffffff818015ce: inet_csk_accept (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct sock *inet_csk_accept(struct sock *sk, int flags, int *err, bool kern);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff818217b0)
Location: net/ipv4/inet_connection_sock.c:428
Inline: False
```
**Symbols:**

```
ffffffff818217b0-ffffffff81821af2: inet_csk_accept (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct sock *inet_csk_accept(struct sock *sk, int flags, int *err, bool kern);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff818a0530)
Location: net/ipv4/inet_connection_sock.c:430
Inline: False
```
**Symbols:**

```
ffffffff818a0530-ffffffff818a08a2: inet_csk_accept (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct sock *inet_csk_accept(struct sock *sk, int flags, int *err, bool kern);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff818f5300)
Location: net/ipv4/inet_connection_sock.c:425
Inline: False
```
**Symbols:**

```
ffffffff818f5300-ffffffff818f5674: inet_csk_accept (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct sock *inet_csk_accept(struct sock *sk, int flags, int *err, bool kern);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81922c40)
Location: net/ipv4/inet_connection_sock.c:441
Inline: False
```
**Symbols:**

```
ffffffff81922c40-ffffffff81922fb4: inet_csk_accept (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct sock *inet_csk_accept(struct sock *sk, int flags, int *err, bool kern);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff819855f0)
Location: net/ipv4/inet_connection_sock.c:437
Inline: False
```
**Symbols:**

```
ffffffff819855f0-ffffffff81985956: inet_csk_accept (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct sock *inet_csk_accept(struct sock *sk, int flags, int *err, bool kern);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff819bc380)
Location: net/ipv4/inet_connection_sock.c:437
Inline: False
```
**Symbols:**

```
ffffffff819bc380-ffffffff819bc6e9: inet_csk_accept (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct sock *inet_csk_accept(struct sock *sk, int flags, int *err, bool kern);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81aa6ec0)
Location: net/ipv4/inet_connection_sock.c:463
Inline: False
Direct callers:
  - net/mptcp/protocol.c:mptcp_accept
```
**Symbols:**

```
ffffffff81aa6ec0-ffffffff81aa7163: inet_csk_accept (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct sock *inet_csk_accept(struct sock *sk, int flags, int *err, bool kern);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81ab1550)
Location: net/ipv4/inet_connection_sock.c:463
Inline: False
Direct callers:
  - net/mptcp/protocol.c:mptcp_accept
```
**Symbols:**

```
ffffffff81ab1550-ffffffff81ab17f3: inet_csk_accept (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct sock *inet_csk_accept(struct sock *sk, int flags, int *err, bool kern);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81a9be90)
Location: net/ipv4/inet_connection_sock.c:463
Inline: False
Direct callers:
  - net/mptcp/protocol.c:mptcp_accept
```
**Symbols:**

```
ffffffff81a9be90-ffffffff81a9c250: inet_csk_accept (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct sock *inet_csk_accept(struct sock *sk, int flags, int *err, bool kern);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/inet_connection_sock.c (0)
Location: net/ipv4/inet_connection_sock.c:471
Inline: False
Direct callers:
  - net/mptcp/protocol.c:mptcp_accept
```
**Symbols:**

```
ffffffff81d3a25d-ffffffff81d3a285: inet_csk_accept.cold (STB_LOCAL)
ffffffff81b57730-ffffffff81b57b0d: inet_csk_accept (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct sock *inet_csk_accept(struct sock *sk, int flags, int *err, bool kern);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/inet_connection_sock.c (0)
Location: net/ipv4/inet_connection_sock.c:475
Inline: False
Direct callers:
  - net/mptcp/protocol.c:mptcp_accept
```
**Symbols:**

```
ffffffff81f069e3-ffffffff81f06a0d: inet_csk_accept.cold (STB_LOCAL)
ffffffff81ce5710-ffffffff81ce5b0d: inet_csk_accept (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct sock *inet_csk_accept(struct sock *sk, int flags, int *err, bool kern);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/inet_connection_sock.c (0)
Location: net/ipv4/inet_connection_sock.c:636
Inline: False
Direct callers:
  - net/mptcp/protocol.c:mptcp_accept
```
**Symbols:**

```
ffffffff820ae619-ffffffff820ae643: inet_csk_accept.cold (STB_LOCAL)
ffffffff81ea8910-ffffffff81ea8d10: inet_csk_accept (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct sock *inet_csk_accept(struct sock *sk, int flags, int *err, bool kern);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/inet_connection_sock.c (0)
Location: net/ipv4/inet_connection_sock.c:657
Inline: False
Direct callers:
  - net/mptcp/protocol.c:mptcp_accept
```
**Symbols:**

```
ffffffff8212fadf-ffffffff8212fb09: inet_csk_accept.cold (STB_LOCAL)
ffffffff81f07190-ffffffff81f07585: inet_csk_accept (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct sock *inet_csk_accept(struct sock *sk, int flags, int *err, bool kern);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/inet_connection_sock.c (0)
Location: net/ipv4/inet_connection_sock.c:654
Inline: False
Direct callers:
  - net/mptcp/protocol.c:mptcp_stream_accept
```
**Symbols:**

```
ffffffff82211872-ffffffff8221189c: inet_csk_accept.cold (STB_LOCAL)
ffffffff81fcb4b0-ffffffff81fcb8e1: inet_csk_accept (STB_GLOBAL)
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
struct sock *inet_csk_accept(struct sock *sk, int flags, int *err, bool kern);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffff800010c6dd40)
Location: net/ipv4/inet_connection_sock.c:437
Inline: False
```
**Symbols:**

```
ffff800010c6dd40-ffff800010c6e0ec: inet_csk_accept (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct sock *inet_csk_accept(struct sock *sk, int flags, int *err, bool kern);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (c0d7c95c)
Location: net/ipv4/inet_connection_sock.c:437
Inline: False
```
**Symbols:**

```
c0d7c95c-c0d7ccac: inet_csk_accept (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct sock *inet_csk_accept(struct sock *sk, int flags, int *err, bool kern);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (c000000000d74490)
Location: net/ipv4/inet_connection_sock.c:437
Inline: False
```
**Symbols:**

```
c000000000d74490-c000000000d7490c: inet_csk_accept (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct sock *inet_csk_accept(struct sock *sk, int flags, int *err, bool kern);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffe0007d347a)
Location: net/ipv4/inet_connection_sock.c:437
Inline: False
```
**Symbols:**

```
ffffffe0007d347a-ffffffe0007d3704: inet_csk_accept (STB_GLOBAL)
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
struct sock *inet_csk_accept(struct sock *sk, int flags, int *err, bool kern);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff8195c1f0)
Location: net/ipv4/inet_connection_sock.c:437
Inline: False
```
**Symbols:**

```
ffffffff8195c1f0-ffffffff8195c559: inet_csk_accept (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct sock *inet_csk_accept(struct sock *sk, int flags, int *err, bool kern);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81915ce0)
Location: net/ipv4/inet_connection_sock.c:437
Inline: False
```
**Symbols:**

```
ffffffff81915ce0-ffffffff81916049: inet_csk_accept (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct sock *inet_csk_accept(struct sock *sk, int flags, int *err, bool kern);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff819c69c0)
Location: net/ipv4/inet_connection_sock.c:437
Inline: False
```
**Symbols:**

```
ffffffff819c69c0-ffffffff819c6d29: inet_csk_accept (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct sock *inet_csk_accept(struct sock *sk, int flags, int *err, bool kern);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff819d0510)
Location: net/ipv4/inet_connection_sock.c:437
Inline: False
```
**Symbols:**

```
ffffffff819d0510-ffffffff819d0879: inet_csk_accept (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool kern</code>
</li>
</ul>
</details>
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
