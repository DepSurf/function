# Function: <code>sock_recvmsg_nosec</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int sock_recvmsg_nosec(struct socket *sock, struct msghdr *msg, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff816fb700)
Location: net/socket.c:710
Inline: True
```
**Symbols:**

```
ffffffff816fb700-ffffffff816fb710: sock_recvmsg_nosec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int sock_recvmsg_nosec(struct socket *sock, struct msghdr *msg, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81762150)
Location: net/socket.c:708
Inline: True
```
**Symbols:**

```
ffffffff81762150-ffffffff81762166: sock_recvmsg_nosec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int sock_recvmsg_nosec(struct socket *sock, struct msghdr *msg, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff8178f160)
Location: net/socket.c:739
Inline: True
```
**Symbols:**

```
ffffffff8178f160-ffffffff8178f176: sock_recvmsg_nosec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int sock_recvmsg_nosec(struct socket *sock, struct msghdr *msg, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff817ae325)
Location: net/socket.c:789
Inline: True
Inline callers:
  - net/socket.c:sock_recvmsg
```
**Symbols:**

```
ffffffff817ad160-ffffffff817ad176: sock_recvmsg_nosec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int sock_recvmsg_nosec(struct socket *sock, struct msghdr *msg, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818263f5)
Location: net/socket.c:808
Inline: True
Inline callers:
  - net/socket.c:sock_recvmsg
```
**Symbols:**

```
ffffffff81825160-ffffffff8182517c: sock_recvmsg_nosec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int sock_recvmsg_nosec(struct socket *sock, struct msghdr *msg, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff8186f160)
Location: net/socket.c:812
Inline: True
```
**Symbols:**

```
ffffffff8186f160-ffffffff8186f17c: sock_recvmsg_nosec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int sock_recvmsg_nosec(struct socket *sock, struct msghdr *msg, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff8188f610)
Location: net/socket.c:792
Inline: True
```
**Symbols:**

```
ffffffff8188f610-ffffffff8188f62c: sock_recvmsg_nosec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int sock_recvmsg_nosec(struct socket *sock, struct msghdr *msg, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818dc15e)
Location: net/socket.c:868
Inline: True
Inline callers:
  - net/socket.c:sock_recvmsg
  - net/socket.c:sock_recvmsg
```
**Symbols:**

```
ffffffff818db110-ffffffff818db14a: sock_recvmsg_nosec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int sock_recvmsg_nosec(struct socket *sock, struct msghdr *msg, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff8190ed3e)
Location: net/socket.c:868
Inline: True
Inline callers:
  - net/socket.c:sock_recvmsg
  - net/socket.c:sock_recvmsg
```
**Symbols:**

```
ffffffff8190d260-ffffffff8190d29a: sock_recvmsg_nosec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819df912)
Location: net/socket.c:883
Inline: True
Inline callers:
  - net/socket.c:____sys_recvmsg
  - net/socket.c:____sys_recvmsg
  - net/socket.c:sock_recvmsg
  - net/socket.c:sock_recvmsg
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819df117)
Location: net/socket.c:883
Inline: True
Inline callers:
  - net/socket.c:____sys_recvmsg
  - net/socket.c:____sys_recvmsg
  - net/socket.c:sock_recvmsg
  - net/socket.c:sock_recvmsg
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819c5027)
Location: net/socket.c:885
Inline: True
Inline callers:
  - net/socket.c:____sys_recvmsg
  - net/socket.c:____sys_recvmsg
  - net/socket.c:sock_recvmsg
  - net/socket.c:sock_recvmsg
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81a74557)
Location: net/socket.c:944
Inline: True
Inline callers:
  - net/socket.c:____sys_recvmsg
  - net/socket.c:____sys_recvmsg
  - net/socket.c:sock_recvmsg
  - net/socket.c:sock_recvmsg
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81be7301)
Location: net/socket.c:992
Inline: True
Inline callers:
  - net/socket.c:____sys_recvmsg
  - net/socket.c:____sys_recvmsg
  - net/socket.c:sock_recvmsg
  - net/socket.c:sock_recvmsg
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81d933b1)
Location: net/socket.c:997
Inline: True
Inline callers:
  - net/socket.c:____sys_recvmsg
  - net/socket.c:____sys_recvmsg
  - net/socket.c:sock_recvmsg
  - net/socket.c:sock_recvmsg
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81e01ee1)
Location: net/socket.c:1021
Inline: True
Inline callers:
  - net/socket.c:____sys_recvmsg
  - net/socket.c:kernel_recvmsg
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81ebe8a1)
Location: net/socket.c:1043
Inline: True
Inline callers:
  - net/socket.c:____sys_recvmsg
  - net/socket.c:kernel_recvmsg
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
int sock_recvmsg_nosec(struct socket *sock, struct msghdr *msg, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/socket.c (ffff800010ba0aa8)
Location: net/socket.c:868
Inline: True
```
**Symbols:**

```
ffff800010ba0aa8-ffff800010ba0acc: sock_recvmsg_nosec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int sock_recvmsg_nosec(struct socket *sock, struct msghdr *msg, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/socket.c (c0cc2f14)
Location: net/socket.c:868
Inline: True
```
**Symbols:**

```
c0cc2f14-c0cc2f38: sock_recvmsg_nosec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int sock_recvmsg_nosec(struct socket *sock, struct msghdr *msg, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/socket.c (c000000000c749a0)
Location: net/socket.c:868
Inline: True
```
**Symbols:**

```
c000000000c749a0-c000000000c749e4: sock_recvmsg_nosec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int sock_recvmsg_nosec(struct socket *sock, struct msghdr *msg, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffe0007388a8)
Location: net/socket.c:868
Inline: True
```
**Symbols:**

```
ffffffe0007388a8-ffffffe0007388c2: sock_recvmsg_nosec (STB_LOCAL)
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
int sock_recvmsg_nosec(struct socket *sock, struct msghdr *msg, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818aed3e)
Location: net/socket.c:868
Inline: True
Inline callers:
  - net/socket.c:sock_recvmsg
  - net/socket.c:sock_recvmsg
```
**Symbols:**

```
ffffffff818ad260-ffffffff818ad29a: sock_recvmsg_nosec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int sock_recvmsg_nosec(struct socket *sock, struct msghdr *msg, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81868c8e)
Location: net/socket.c:868
Inline: True
Inline callers:
  - net/socket.c:sock_recvmsg
  - net/socket.c:sock_recvmsg
```
**Symbols:**

```
ffffffff818671b0-ffffffff818671ea: sock_recvmsg_nosec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int sock_recvmsg_nosec(struct socket *sock, struct msghdr *msg, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818ffd3e)
Location: net/socket.c:868
Inline: True
Inline callers:
  - net/socket.c:sock_recvmsg
  - net/socket.c:sock_recvmsg
```
**Symbols:**

```
ffffffff818fe260-ffffffff818fe29a: sock_recvmsg_nosec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int sock_recvmsg_nosec(struct socket *sock, struct msghdr *msg, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81920d2e)
Location: net/socket.c:868
Inline: True
Inline callers:
  - net/socket.c:sock_recvmsg
  - net/socket.c:sock_recvmsg
```
**Symbols:**

```
ffffffff8191f2f0-ffffffff8191f32a: sock_recvmsg_nosec (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>size_t size</code>
</li>
<li>
<b>Param reordered. </b>
<code>sock, msg, size, flags</code> ➡️ <code>sock, msg, flags</code>
</li>
</ul>
</details>
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
