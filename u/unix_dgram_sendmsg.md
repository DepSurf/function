# Function: <code>unix_dgram_sendmsg</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int unix_dgram_sendmsg(struct socket *sock, struct msghdr *msg, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff817c1830)
Location: net/unix/af_unix.c:1641
Inline: False
```
**Symbols:**

```
ffffffff817c1830-ffffffff817c1f07: unix_dgram_sendmsg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int unix_dgram_sendmsg(struct socket *sock, struct msghdr *msg, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff8182e820)
Location: net/unix/af_unix.c:1626
Inline: False
```
**Symbols:**

```
ffffffff8182e820-ffffffff8182ef1b: unix_dgram_sendmsg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int unix_dgram_sendmsg(struct socket *sock, struct msghdr *msg, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff818602a0)
Location: net/unix/af_unix.c:1631
Inline: False
```
**Symbols:**

```
ffffffff818602a0-ffffffff81860996: unix_dgram_sendmsg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int unix_dgram_sendmsg(struct socket *sock, struct msghdr *msg, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff818849e0)
Location: net/unix/af_unix.c:1638
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_seqpacket_sendmsg
```
**Symbols:**

```
ffffffff818849e0-ffffffff818850f1: unix_dgram_sendmsg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int unix_dgram_sendmsg(struct socket *sock, struct msghdr *msg, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff81905bc0)
Location: net/unix/af_unix.c:1626
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_seqpacket_sendmsg
```
**Symbols:**

```
ffffffff81905bc0-ffffffff819062a2: unix_dgram_sendmsg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int unix_dgram_sendmsg(struct socket *sock, struct msghdr *msg, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff8195c680)
Location: net/unix/af_unix.c:1616
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_seqpacket_sendmsg
```
**Symbols:**

```
ffffffff8195c680-ffffffff8195cd5b: unix_dgram_sendmsg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int unix_dgram_sendmsg(struct socket *sock, struct msghdr *msg, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff819916b0)
Location: net/unix/af_unix.c:1633
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_seqpacket_sendmsg
```
**Symbols:**

```
ffffffff819916b0-ffffffff81991dbb: unix_dgram_sendmsg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int unix_dgram_sendmsg(struct socket *sock, struct msghdr *msg, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff819fc8e0)
Location: net/unix/af_unix.c:1569
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_seqpacket_sendmsg
```
**Symbols:**

```
ffffffff819fc8e0-ffffffff819fcfe1: unix_dgram_sendmsg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int unix_dgram_sendmsg(struct socket *sock, struct msghdr *msg, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff81a33570)
Location: net/unix/af_unix.c:1581
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_seqpacket_sendmsg
```
**Symbols:**

```
ffffffff81a33570-ffffffff81a33c71: unix_dgram_sendmsg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int unix_dgram_sendmsg(struct socket *sock, struct msghdr *msg, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff81b286a0)
Location: net/unix/af_unix.c:1623
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_seqpacket_sendmsg
```
**Symbols:**

```
ffffffff81b286a0-ffffffff81b28ffc: unix_dgram_sendmsg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int unix_dgram_sendmsg(struct socket *sock, struct msghdr *msg, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff81b368d0)
Location: net/unix/af_unix.c:1614
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_seqpacket_sendmsg
```
**Symbols:**

```
ffffffff81b368d0-ffffffff81b3728e: unix_dgram_sendmsg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int unix_dgram_sendmsg(struct socket *sock, struct msghdr *msg, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff81b244b0)
Location: net/unix/af_unix.c:1663
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_seqpacket_sendmsg
```
**Symbols:**

```
ffffffff81b244b0-ffffffff81b24e65: unix_dgram_sendmsg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int unix_dgram_sendmsg(struct socket *sock, struct msghdr *msg, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff81be94f0)
Location: net/unix/af_unix.c:1755
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_seqpacket_sendmsg
```
**Symbols:**

```
ffffffff81be94f0-ffffffff81be9eac: unix_dgram_sendmsg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int unix_dgram_sendmsg(struct socket *sock, struct msghdr *msg, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff81d81fc0)
Location: net/unix/af_unix.c:1840
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_seqpacket_sendmsg
```
**Symbols:**

```
ffffffff81d81fc0-ffffffff81d8299f: unix_dgram_sendmsg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int unix_dgram_sendmsg(struct socket *sock, struct msghdr *msg, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff81f4f510)
Location: net/unix/af_unix.c:1890
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_seqpacket_sendmsg
```
**Symbols:**

```
ffffffff81f4f510-ffffffff81f4ff83: unix_dgram_sendmsg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int unix_dgram_sendmsg(struct socket *sock, struct msghdr *msg, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff81faee00)
Location: net/unix/af_unix.c:1899
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_seqpacket_sendmsg
```
**Symbols:**

```
ffffffff81faee00-ffffffff81faf7df: unix_dgram_sendmsg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int unix_dgram_sendmsg(struct socket *sock, struct msghdr *msg, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff8207c330)
Location: net/unix/af_unix.c:1898
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_seqpacket_sendmsg
```
**Symbols:**

```
ffffffff8207c330-ffffffff8207cdd9: unix_dgram_sendmsg (STB_LOCAL)
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
int unix_dgram_sendmsg(struct socket *sock, struct msghdr *msg, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffff800010cf3588)
Location: net/unix/af_unix.c:1581
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_seqpacket_sendmsg
```
**Symbols:**

```
ffff800010cf3588-ffff800010cf3b84: unix_dgram_sendmsg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int unix_dgram_sendmsg(struct socket *sock, struct msghdr *msg, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (c0dfa7c8)
Location: net/unix/af_unix.c:1581
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_seqpacket_sendmsg
```
**Symbols:**

```
c0dfa7c8-c0dfaed8: unix_dgram_sendmsg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int unix_dgram_sendmsg(struct socket *sock, struct msghdr *msg, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (c000000000e19510)
Location: net/unix/af_unix.c:1581
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_seqpacket_sendmsg
```
**Symbols:**

```
c000000000e19510-c000000000e19ea4: unix_dgram_sendmsg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int unix_dgram_sendmsg(struct socket *sock, struct msghdr *msg, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffe00083fe3c)
Location: net/unix/af_unix.c:1581
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_seqpacket_sendmsg
```
**Symbols:**

```
ffffffe00083fe3c-ffffffe00084052a: unix_dgram_sendmsg (STB_LOCAL)
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
int unix_dgram_sendmsg(struct socket *sock, struct msghdr *msg, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff819d2c00)
Location: net/unix/af_unix.c:1581
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_seqpacket_sendmsg
```
**Symbols:**

```
ffffffff819d2c00-ffffffff819d3301: unix_dgram_sendmsg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int unix_dgram_sendmsg(struct socket *sock, struct msghdr *msg, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff8198f9c0)
Location: net/unix/af_unix.c:1581
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_seqpacket_sendmsg
```
**Symbols:**

```
ffffffff8198f9c0-ffffffff819900c1: unix_dgram_sendmsg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int unix_dgram_sendmsg(struct socket *sock, struct msghdr *msg, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff81a3d680)
Location: net/unix/af_unix.c:1581
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_seqpacket_sendmsg
```
**Symbols:**

```
ffffffff81a3d680-ffffffff81a3dd81: unix_dgram_sendmsg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int unix_dgram_sendmsg(struct socket *sock, struct msghdr *msg, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff81a49130)
Location: net/unix/af_unix.c:1581
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_seqpacket_sendmsg
```
**Symbols:**

```
ffffffff81a49130-ffffffff81a4983a: unix_dgram_sendmsg (STB_LOCAL)
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
