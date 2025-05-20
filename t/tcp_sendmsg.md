# Function: <code>tcp_sendmsg</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int tcp_sendmsg(struct sock *sk, struct msghdr *msg, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81769610)
Location: net/ipv4/tcp.c:1090
Inline: False
```
**Symbols:**

```
ffffffff81769610-ffffffff8176a127: tcp_sendmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int tcp_sendmsg(struct sock *sk, struct msghdr *msg, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff817d5ff0)
Location: net/ipv4/tcp.c:1080
Inline: False
```
**Symbols:**

```
ffffffff817d5ff0-ffffffff817d6bcc: tcp_sendmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int tcp_sendmsg(struct sock *sk, struct msghdr *msg, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81806000)
Location: net/ipv4/tcp.c:1104
Inline: False
```
**Symbols:**

```
ffffffff81806000-ffffffff81806be5: tcp_sendmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int tcp_sendmsg(struct sock *sk, struct msghdr *msg, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81826480)
Location: net/ipv4/tcp.c:1147
Inline: False
```
**Symbols:**

```
ffffffff81826480-ffffffff818271ee: tcp_sendmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int tcp_sendmsg(struct sock *sk, struct msghdr *msg, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff818a53f0)
Location: net/ipv4/tcp.c:1456
Inline: False
```
**Symbols:**

```
ffffffff818a53f0-ffffffff818a5431: tcp_sendmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int tcp_sendmsg(struct sock *sk, struct msghdr *msg, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff818fb050)
Location: net/ipv4/tcp.c:1442
Inline: False
Direct callers:
  - kernel/bpf/sockmap.c:bpf_tcp_sendmsg
```
**Symbols:**

```
ffffffff818fb050-ffffffff818fb091: tcp_sendmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int tcp_sendmsg(struct sock *sk, struct msghdr *msg, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81928f80)
Location: net/ipv4/tcp.c:1438
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
```
**Symbols:**

```
ffffffff81928f80-ffffffff81928fc1: tcp_sendmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int tcp_sendmsg(struct sock *sk, struct msghdr *msg, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff8198be90)
Location: net/ipv4/tcp.c:1428
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:inet_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv6/af_inet6.c:inet6_sendmsg
```
**Symbols:**

```
ffffffff8198be90-ffffffff8198bed3: tcp_sendmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int tcp_sendmsg(struct sock *sk, struct msghdr *msg, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff819c27e0)
Location: net/ipv4/tcp.c:1429
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:inet_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv6/af_inet6.c:inet6_sendmsg
```
**Symbols:**

```
ffffffff819c27e0-ffffffff819c2823: tcp_sendmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int tcp_sendmsg(struct sock *sk, struct msghdr *msg, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81aadd90)
Location: net/ipv4/tcp.c:1436
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:inet_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv6/af_inet6.c:inet6_sendmsg
```
**Symbols:**

```
ffffffff81aadd90-ffffffff81aaddd3: tcp_sendmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int tcp_sendmsg(struct sock *sk, struct msghdr *msg, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81ab5180)
Location: net/ipv4/tcp.c:1454
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:inet_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv6/af_inet6.c:inet6_sendmsg
```
**Symbols:**

```
ffffffff81ab5180-ffffffff81ab51c3: tcp_sendmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int tcp_sendmsg(struct sock *sk, struct msghdr *msg, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81aa0370)
Location: net/ipv4/tcp.c:1456
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:inet_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv6/af_inet6.c:inet6_sendmsg
```
**Symbols:**

```
ffffffff81aa0370-ffffffff81aa03b3: tcp_sendmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int tcp_sendmsg(struct sock *sk, struct msghdr *msg, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81b5c190)
Location: net/ipv4/tcp.c:1453
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:inet_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv6/af_inet6.c:inet6_sendmsg
```
**Symbols:**

```
ffffffff81b5c190-ffffffff81b5c1d3: tcp_sendmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int tcp_sendmsg(struct sock *sk, struct msghdr *msg, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81ceb300)
Location: net/ipv4/tcp.c:1469
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:inet_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv6/af_inet6.c:inet6_sendmsg
```
**Symbols:**

```
ffffffff81ceb300-ffffffff81ceb34b: tcp_sendmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int tcp_sendmsg(struct sock *sk, struct msghdr *msg, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81eaf050)
Location: net/ipv4/tcp.c:1479
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:inet_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv6/af_inet6.c:inet6_sendmsg
```
**Symbols:**

```
ffffffff81eaf050-ffffffff81eaf09b: tcp_sendmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int tcp_sendmsg(struct sock *sk, struct msghdr *msg, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81f0d380)
Location: net/ipv4/tcp.c:1328
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:inet_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv6/af_inet6.c:inet6_sendmsg
```
**Symbols:**

```
ffffffff81f0d380-ffffffff81f0d3cb: tcp_sendmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int tcp_sendmsg(struct sock *sk, struct msghdr *msg, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81fd1480)
Location: net/ipv4/tcp.c:1336
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:inet_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv6/af_inet6.c:inet6_sendmsg
```
**Symbols:**

```
ffffffff81fd1480-ffffffff81fd14cb: tcp_sendmsg (STB_GLOBAL)
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
int tcp_sendmsg(struct sock *sk, struct msghdr *msg, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffff800010c754c8)
Location: net/ipv4/tcp.c:1429
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
```
**Symbols:**

```
ffff800010c754c8-ffff800010c75528: tcp_sendmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int tcp_sendmsg(struct sock *sk, struct msghdr *msg, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (c0d83c1c)
Location: net/ipv4/tcp.c:1429
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
```
**Symbols:**

```
c0d83c1c-c0d83c68: tcp_sendmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int tcp_sendmsg(struct sock *sk, struct msghdr *msg, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (c000000000d7cb30)
Location: net/ipv4/tcp.c:1429
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
```
**Symbols:**

```
c000000000d7cb30-c000000000d7cbac: tcp_sendmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int tcp_sendmsg(struct sock *sk, struct msghdr *msg, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffe0007d879a)
Location: net/ipv4/tcp.c:1429
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
```
**Symbols:**

```
ffffffe0007d879a-ffffffe0007d87ee: tcp_sendmsg (STB_GLOBAL)
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
int tcp_sendmsg(struct sock *sk, struct msghdr *msg, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81962650)
Location: net/ipv4/tcp.c:1429
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:inet_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv6/af_inet6.c:inet6_sendmsg
```
**Symbols:**

```
ffffffff81962650-ffffffff81962693: tcp_sendmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int tcp_sendmsg(struct sock *sk, struct msghdr *msg, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff8191c140)
Location: net/ipv4/tcp.c:1429
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:inet_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv6/af_inet6.c:inet6_sendmsg
```
**Symbols:**

```
ffffffff8191c140-ffffffff8191c183: tcp_sendmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int tcp_sendmsg(struct sock *sk, struct msghdr *msg, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff819cce20)
Location: net/ipv4/tcp.c:1429
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:inet_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv6/af_inet6.c:inet6_sendmsg
```
**Symbols:**

```
ffffffff819cce20-ffffffff819cce63: tcp_sendmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int tcp_sendmsg(struct sock *sk, struct msghdr *msg, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff819d69b0)
Location: net/ipv4/tcp.c:1429
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:inet_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv6/af_inet6.c:inet6_sendmsg
```
**Symbols:**

```
ffffffff819d69b0-ffffffff819d69f3: tcp_sendmsg (STB_GLOBAL)
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
