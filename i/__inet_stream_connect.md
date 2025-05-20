# Function: <code>__inet_stream_connect</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __inet_stream_connect(struct socket *sock, struct sockaddr *uaddr, int addr_len, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff81793540)
Location: net/ipv4/af_inet.c:564
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/ipv4/af_inet.c:inet_stream_connect
```
**Symbols:**

```
ffffffff81793540-ffffffff81793840: __inet_stream_connect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __inet_stream_connect(struct socket *sock, struct sockaddr *uaddr, int addr_len, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff81800d40)
Location: net/ipv4/af_inet.c:568
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/ipv4/af_inet.c:inet_stream_connect
```
**Symbols:**

```
ffffffff81800d40-ffffffff81801045: __inet_stream_connect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __inet_stream_connect(struct socket *sock, struct sockaddr *uaddr, int addr_len, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff81831c90)
Location: net/ipv4/af_inet.c:572
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/ipv4/af_inet.c:inet_stream_connect
```
**Symbols:**

```
ffffffff81831c90-ffffffff81831f82: __inet_stream_connect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __inet_stream_connect(struct socket *sock, struct sockaddr *uaddr, int addr_len, int flags, int is_sendmsg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff81853210)
Location: net/ipv4/af_inet.c:572
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/ipv4/af_inet.c:inet_stream_connect
```
**Symbols:**

```
ffffffff81853210-ffffffff81853548: __inet_stream_connect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __inet_stream_connect(struct socket *sock, struct sockaddr *uaddr, int addr_len, int flags, int is_sendmsg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff818d3060)
Location: net/ipv4/af_inet.c:573
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/af_inet.c:inet_stream_connect
```
**Symbols:**

```
ffffffff818d3060-ffffffff818d33a7: __inet_stream_connect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __inet_stream_connect(struct socket *sock, struct sockaddr *uaddr, int addr_len, int flags, int is_sendmsg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff81929400)
Location: net/ipv4/af_inet.c:603
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/af_inet.c:inet_stream_connect
```
**Symbols:**

```
ffffffff81929400-ffffffff81929794: __inet_stream_connect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __inet_stream_connect(struct socket *sock, struct sockaddr *uaddr, int addr_len, int flags, int is_sendmsg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff819585b0)
Location: net/ipv4/af_inet.c:603
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/af_inet.c:inet_stream_connect
```
**Symbols:**

```
ffffffff819585b0-ffffffff81958944: __inet_stream_connect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __inet_stream_connect(struct socket *sock, struct sockaddr *uaddr, int addr_len, int flags, int is_sendmsg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff819bd100)
Location: net/ipv4/af_inet.c:603
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/af_inet.c:inet_stream_connect
```
**Symbols:**

```
ffffffff819bd100-ffffffff819bd47c: __inet_stream_connect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __inet_stream_connect(struct socket *sock, struct sockaddr *uaddr, int addr_len, int flags, int is_sendmsg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff819f3d10)
Location: net/ipv4/af_inet.c:603
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/af_inet.c:inet_stream_connect
```
**Symbols:**

```
ffffffff819f3d10-ffffffff819f408c: __inet_stream_connect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __inet_stream_connect(struct socket *sock, struct sockaddr *uaddr, int addr_len, int flags, int is_sendmsg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff81ae3390)
Location: net/ipv4/af_inet.c:606
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/af_inet.c:inet_stream_connect
```
**Symbols:**

```
ffffffff81ae3390-ffffffff81ae35bf: __inet_stream_connect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __inet_stream_connect(struct socket *sock, struct sockaddr *uaddr, int addr_len, int flags, int is_sendmsg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff81af0780)
Location: net/ipv4/af_inet.c:609
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/af_inet.c:inet_stream_connect
```
**Symbols:**

```
ffffffff81af0780-ffffffff81af09be: __inet_stream_connect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __inet_stream_connect(struct socket *sock, struct sockaddr *uaddr, int addr_len, int flags, int is_sendmsg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff81adbdc0)
Location: net/ipv4/af_inet.c:612
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/af_inet.c:inet_stream_connect
```
**Symbols:**

```
ffffffff81adbdc0-ffffffff81adc161: __inet_stream_connect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int __inet_stream_connect(struct socket *sock, struct sockaddr *uaddr, int addr_len, int flags, int is_sendmsg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/af_inet.c (0)
Location: net/ipv4/af_inet.c:612
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/af_inet.c:inet_stream_connect
```
**Symbols:**

```
ffffffff81d3c423-ffffffff81d3c45c: __inet_stream_connect.cold (STB_LOCAL)
ffffffff81b9aff0-ffffffff81b9b388: __inet_stream_connect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int __inet_stream_connect(struct socket *sock, struct sockaddr *uaddr, int addr_len, int flags, int is_sendmsg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/af_inet.c (0)
Location: net/ipv4/af_inet.c:608
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/af_inet.c:inet_stream_connect
```
**Symbols:**

```
ffffffff81f08c55-ffffffff81f08c8f: __inet_stream_connect.cold (STB_LOCAL)
ffffffff81d2ce30-ffffffff81d2d1e3: __inet_stream_connect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int __inet_stream_connect(struct socket *sock, struct sockaddr *uaddr, int addr_len, int flags, int is_sendmsg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/af_inet.c (0)
Location: net/ipv4/af_inet.c:614
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg_fastopen
  - net/ipv4/af_inet.c:inet_stream_connect
  - net/mptcp/protocol.c:mptcp_stream_connect
  - net/mptcp/protocol.c:mptcp_connect
  - net/mptcp/protocol.c:mptcp_sendmsg
```
**Symbols:**

```
ffffffff820b0683-ffffffff820b06a5: __inet_stream_connect.cold (STB_LOCAL)
ffffffff81ef49b0-ffffffff81ef4c14: __inet_stream_connect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int __inet_stream_connect(struct socket *sock, struct sockaddr *uaddr, int addr_len, int flags, int is_sendmsg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/af_inet.c (0)
Location: net/ipv4/af_inet.c:614
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg_fastopen
  - net/ipv4/af_inet.c:inet_stream_connect
  - net/mptcp/protocol.c:mptcp_connect
  - net/mptcp/protocol.c:mptcp_sendmsg
```
**Symbols:**

```
ffffffff821318ed-ffffffff8213190c: __inet_stream_connect.cold (STB_LOCAL)
ffffffff81f54330-ffffffff81f545a4: __inet_stream_connect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int __inet_stream_connect(struct socket *sock, struct sockaddr *uaddr, int addr_len, int flags, int is_sendmsg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/af_inet.c (0)
Location: net/ipv4/af_inet.c:625
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg_fastopen
  - net/ipv4/af_inet.c:inet_stream_connect
  - net/mptcp/protocol.c:mptcp_sendmsg
```
**Symbols:**

```
ffffffff82213260-ffffffff8221327f: __inet_stream_connect.cold (STB_LOCAL)
ffffffff8201a570-ffffffff8201a802: __inet_stream_connect (STB_GLOBAL)
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
int __inet_stream_connect(struct socket *sock, struct sockaddr *uaddr, int addr_len, int flags, int is_sendmsg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffff800010cab218)
Location: net/ipv4/af_inet.c:603
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/af_inet.c:inet_stream_connect
```
**Symbols:**

```
ffff800010cab218-ffff800010cab560: __inet_stream_connect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __inet_stream_connect(struct socket *sock, struct sockaddr *uaddr, int addr_len, int flags, int is_sendmsg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (c0db7c98)
Location: net/ipv4/af_inet.c:603
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/af_inet.c:inet_stream_connect
```
**Symbols:**

```
c0db7c98-c0db8058: __inet_stream_connect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __inet_stream_connect(struct socket *sock, struct sockaddr *uaddr, int addr_len, int flags, int is_sendmsg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (c000000000dbf990)
Location: net/ipv4/af_inet.c:603
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/af_inet.c:inet_stream_connect
```
**Symbols:**

```
c000000000dbf990-c000000000dbfe44: __inet_stream_connect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __inet_stream_connect(struct socket *sock, struct sockaddr *uaddr, int addr_len, int flags, int is_sendmsg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffe000804c18)
Location: net/ipv4/af_inet.c:603
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/af_inet.c:inet_stream_connect
```
**Symbols:**

```
ffffffe000804c18-ffffffe000804ea8: __inet_stream_connect (STB_GLOBAL)
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
int __inet_stream_connect(struct socket *sock, struct sockaddr *uaddr, int addr_len, int flags, int is_sendmsg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff81993ab0)
Location: net/ipv4/af_inet.c:603
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/af_inet.c:inet_stream_connect
```
**Symbols:**

```
ffffffff81993ab0-ffffffff81993e2c: __inet_stream_connect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __inet_stream_connect(struct socket *sock, struct sockaddr *uaddr, int addr_len, int flags, int is_sendmsg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff8194d570)
Location: net/ipv4/af_inet.c:603
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/af_inet.c:inet_stream_connect
```
**Symbols:**

```
ffffffff8194d570-ffffffff8194d8ec: __inet_stream_connect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __inet_stream_connect(struct socket *sock, struct sockaddr *uaddr, int addr_len, int flags, int is_sendmsg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff819fe350)
Location: net/ipv4/af_inet.c:603
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/af_inet.c:inet_stream_connect
```
**Symbols:**

```
ffffffff819fe350-ffffffff819fe6cc: __inet_stream_connect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __inet_stream_connect(struct socket *sock, struct sockaddr *uaddr, int addr_len, int flags, int is_sendmsg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff81a086e0)
Location: net/ipv4/af_inet.c:603
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/af_inet.c:inet_stream_connect
```
**Symbols:**

```
ffffffff81a086e0-ffffffff81a08a5c: __inet_stream_connect (STB_GLOBAL)
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
<code>int is_sendmsg</code>
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
