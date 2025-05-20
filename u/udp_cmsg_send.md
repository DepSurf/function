# Function: <code>udp_cmsg_send</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int udp_cmsg_send(struct sock *sk, struct msghdr *msg, u16 *gso_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff8191a6c0)
Location: net/ipv4/udp.c:874
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
```
**Symbols:**

```
ffffffff8191a6c0-ffffffff8191a755: udp_cmsg_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int udp_cmsg_send(struct sock *sk, struct msghdr *msg, u16 *gso_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81948e70)
Location: net/ipv4/udp.c:951
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
```
**Symbols:**

```
ffffffff81948e70-ffffffff81948f05: udp_cmsg_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int udp_cmsg_send(struct sock *sk, struct msghdr *msg, u16 *gso_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff819ad4d0)
Location: net/ipv4/udp.c:938
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
```
**Symbols:**

```
ffffffff819ad4d0-ffffffff819ad55d: udp_cmsg_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int udp_cmsg_send(struct sock *sk, struct msghdr *msg, u16 *gso_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff819e4180)
Location: net/ipv4/udp.c:941
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
```
**Symbols:**

```
ffffffff819e4180-ffffffff819e420d: udp_cmsg_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int udp_cmsg_send(struct sock *sk, struct msghdr *msg, u16 *gso_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81ad18c0)
Location: net/ipv4/udp.c:947
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
```
**Symbols:**

```
ffffffff81ad18c0-ffffffff81ad1958: udp_cmsg_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int udp_cmsg_send(struct sock *sk, struct msghdr *msg, u16 *gso_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81add8f0)
Location: net/ipv4/udp.c:997
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
```
**Symbols:**

```
ffffffff81add8f0-ffffffff81add988: udp_cmsg_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int udp_cmsg_send(struct sock *sk, struct msghdr *msg, u16 *gso_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81ac89c0)
Location: net/ipv4/udp.c:1016
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
```
**Symbols:**

```
ffffffff81ac89c0-ffffffff81ac8a53: udp_cmsg_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int udp_cmsg_send(struct sock *sk, struct msghdr *msg, u16 *gso_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81b87240)
Location: net/ipv4/udp.c:1017
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
```
**Symbols:**

```
ffffffff81b87240-ffffffff81b872d3: udp_cmsg_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int udp_cmsg_send(struct sock *sk, struct msghdr *msg, u16 *gso_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81d17ee0)
Location: net/ipv4/udp.c:1017
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
```
**Symbols:**

```
ffffffff81d17ee0-ffffffff81d17fa6: udp_cmsg_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int udp_cmsg_send(struct sock *sk, struct msghdr *msg, u16 *gso_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81ede780)
Location: net/ipv4/udp.c:1028
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
```
**Symbols:**

```
ffffffff81ede780-ffffffff81ede846: udp_cmsg_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int udp_cmsg_send(struct sock *sk, struct msghdr *msg, u16 *gso_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81f3dbc0)
Location: net/ipv4/udp.c:1043
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
```
**Symbols:**

```
ffffffff81f3dbc0-ffffffff81f3dc86: udp_cmsg_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int udp_cmsg_send(struct sock *sk, struct msghdr *msg, u16 *gso_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff82003cf0)
Location: net/ipv4/udp.c:1014
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
```
**Symbols:**

```
ffffffff82003cf0-ffffffff82003db6: udp_cmsg_send (STB_GLOBAL)
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
int udp_cmsg_send(struct sock *sk, struct msghdr *msg, u16 *gso_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffff800010c98c58)
Location: net/ipv4/udp.c:941
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
```
**Symbols:**

```
ffff800010c98c58-ffff800010c98d18: udp_cmsg_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int udp_cmsg_send(struct sock *sk, struct msghdr *msg, u16 *gso_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (c0da69b0)
Location: net/ipv4/udp.c:941
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
```
**Symbols:**

```
c0da69b0-c0da6a68: udp_cmsg_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int udp_cmsg_send(struct sock *sk, struct msghdr *msg, u16 *gso_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (c000000000daa370)
Location: net/ipv4/udp.c:941
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
```
**Symbols:**

```
c000000000daa370-c000000000daa448: udp_cmsg_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int udp_cmsg_send(struct sock *sk, struct msghdr *msg, u16 *gso_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffe0007f6c00)
Location: net/ipv4/udp.c:941
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
```
**Symbols:**

```
ffffffe0007f6c00-ffffffe0007f6ca0: udp_cmsg_send (STB_GLOBAL)
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
int udp_cmsg_send(struct sock *sk, struct msghdr *msg, u16 *gso_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81983ff0)
Location: net/ipv4/udp.c:941
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
```
**Symbols:**

```
ffffffff81983ff0-ffffffff8198407d: udp_cmsg_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int udp_cmsg_send(struct sock *sk, struct msghdr *msg, u16 *gso_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff8193dab0)
Location: net/ipv4/udp.c:941
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
```
**Symbols:**

```
ffffffff8193dab0-ffffffff8193db3d: udp_cmsg_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int udp_cmsg_send(struct sock *sk, struct msghdr *msg, u16 *gso_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff819ee7c0)
Location: net/ipv4/udp.c:941
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
```
**Symbols:**

```
ffffffff819ee7c0-ffffffff819ee84d: udp_cmsg_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int udp_cmsg_send(struct sock *sk, struct msghdr *msg, u16 *gso_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff819f8820)
Location: net/ipv4/udp.c:941
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
```
**Symbols:**

```
ffffffff819f8820-ffffffff819f88ad: udp_cmsg_send (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
