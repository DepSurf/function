# Function: <code>sock_do_ioctl</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long int sock_do_ioctl(struct net *net, struct socket *sock, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff816fba10)
Location: net/socket.c:863
Inline: False
Direct callers:
  - net/socket.c:routing_ioctl
  - net/socket.c:sock_ioctl
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:compat_sock_ioctl_trans
```
**Symbols:**

```
ffffffff816fba10-ffffffff816fba5b: sock_do_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long int sock_do_ioctl(struct net *net, struct socket *sock, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81762470)
Location: net/socket.c:860
Inline: False
Direct callers:
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:routing_ioctl
  - net/socket.c:sock_ioctl
```
**Symbols:**

```
ffffffff81762470-ffffffff817624bb: sock_do_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long int sock_do_ioctl(struct net *net, struct socket *sock, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff8178f4a0)
Location: net/socket.c:891
Inline: False
Direct callers:
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:routing_ioctl
  - net/socket.c:sock_ioctl
```
**Symbols:**

```
ffffffff8178f4a0-ffffffff8178f4eb: sock_do_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long int sock_do_ioctl(struct net *net, struct socket *sock, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff817ad420)
Location: net/socket.c:941
Inline: False
Direct callers:
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:routing_ioctl
  - net/socket.c:sock_ioctl
```
**Symbols:**

```
ffffffff817ad420-ffffffff817ad46b: sock_do_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long int sock_do_ioctl(struct net *net, struct socket *sock, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818253b0)
Location: net/socket.c:960
Inline: False
Direct callers:
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:routing_ioctl
  - net/socket.c:sock_ioctl
```
**Symbols:**

```
ffffffff818253b0-ffffffff81825401: sock_do_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long int sock_do_ioctl(struct net *net, struct socket *sock, unsigned int cmd, long unsigned int arg, unsigned int ifreq_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81871810)
Location: net/socket.c:964
Inline: False
Direct callers:
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:routing_ioctl
  - net/socket.c:sock_ioctl
```
**Symbols:**

```
ffffffff81871810-ffffffff81871968: sock_do_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long int sock_do_ioctl(struct net *net, struct socket *sock, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff8188fa30)
Location: net/socket.c:944
Inline: False
Direct callers:
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:routing_ioctl
  - net/socket.c:sock_ioctl
```
**Symbols:**

```
ffffffff8188fa30-ffffffff8188fb61: sock_do_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long int sock_do_ioctl(struct net *net, struct socket *sock, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818d9aa0)
Location: net/socket.c:1032
Inline: False
Direct callers:
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:routing_ioctl
  - net/socket.c:sock_ioctl
```
**Symbols:**

```
ffffffff818d9aa0-ffffffff818d9bd9: sock_do_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int sock_do_ioctl(struct net *net, struct socket *sock, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff8190ba80)
Location: net/socket.c:1032
Inline: False
Direct callers:
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:routing_ioctl
  - net/socket.c:sock_ioctl
```
**Symbols:**

```
ffffffff8190ba80-ffffffff8190bbb9: sock_do_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int sock_do_ioctl(struct net *net, struct socket *sock, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819ddd70)
Location: net/socket.c:1042
Inline: False
Direct callers:
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:sock_ioctl
```
**Symbols:**

```
ffffffff819ddd70-ffffffff819ddea2: sock_do_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int sock_do_ioctl(struct net *net, struct socket *sock, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819dd750)
Location: net/socket.c:1031
Inline: False
Direct callers:
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:compat_ifreq_ioctl
  - net/socket.c:sock_ioctl
```
**Symbols:**

```
ffffffff819dd750-ffffffff819dd882: sock_do_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int sock_do_ioctl(struct net *net, struct socket *sock, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819c38a0)
Location: net/socket.c:1033
Inline: False
Direct callers:
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:sock_ioctl
```
**Symbols:**

```
ffffffff819c38a0-ffffffff819c39d6: sock_do_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
long int sock_do_ioctl(struct net *net, struct socket *sock, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/socket.c (0)
Location: net/socket.c:1112
Inline: False
Direct callers:
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:sock_ioctl
```
**Symbols:**

```
ffffffff81a74b20-ffffffff81a74c16: sock_do_ioctl (STB_LOCAL)
ffffffff81d34a51-ffffffff81d34a66: sock_do_ioctl.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
long int sock_do_ioctl(struct net *net, struct socket *sock, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/socket.c (0)
Location: net/socket.c:1160
Inline: False
Direct callers:
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:sock_ioctl
```
**Symbols:**

```
ffffffff81be63e0-ffffffff81be651b: sock_do_ioctl (STB_LOCAL)
ffffffff81f00ebe-ffffffff81f00ed3: sock_do_ioctl.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
long int sock_do_ioctl(struct net *net, struct socket *sock, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/socket.c (0)
Location: net/socket.c:1165
Inline: False
Direct callers:
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:sock_ioctl
```
**Symbols:**

```
ffffffff81d92800-ffffffff81d9293b: sock_do_ioctl (STB_LOCAL)
ffffffff820aaaaa-ffffffff820aaabf: sock_do_ioctl.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
long int sock_do_ioctl(struct net *net, struct socket *sock, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/socket.c (0)
Location: net/socket.c:1190
Inline: False
Direct callers:
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:sock_ioctl
```
**Symbols:**

```
ffffffff81e00b60-ffffffff81e00ca2: sock_do_ioctl (STB_LOCAL)
ffffffff8212bfe0-ffffffff8212bff5: sock_do_ioctl.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
long int sock_do_ioctl(struct net *net, struct socket *sock, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/socket.c (0)
Location: net/socket.c:1212
Inline: False
Direct callers:
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:sock_ioctl
```
**Symbols:**

```
ffffffff81ebd260-ffffffff81ebd3a2: sock_do_ioctl (STB_LOCAL)
ffffffff8220dc92-ffffffff8220dca7: sock_do_ioctl.cold (STB_LOCAL)
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
long int sock_do_ioctl(struct net *net, struct socket *sock, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffff800010ba4f98)
Location: net/socket.c:1032
Inline: False
Direct callers:
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:routing_ioctl
  - net/socket.c:sock_ioctl
```
**Symbols:**

```
ffff800010ba4f98-ffff800010ba5308: sock_do_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/socket.c (c0cc51b0)
Location: net/socket.c:1032
Inline: True
Inline callers:
  - net/socket.c:sock_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int sock_do_ioctl(struct net *net, struct socket *sock, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (c000000000c751c0)
Location: net/socket.c:1032
Inline: False
Direct callers:
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:routing_ioctl
  - net/socket.c:sock_ioctl
```
**Symbols:**

```
c000000000c751c0-c000000000c75370: sock_do_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffe000738fae)
Location: net/socket.c:1032
Inline: True
Inline callers:
  - net/socket.c:sock_ioctl
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
long int sock_do_ioctl(struct net *net, struct socket *sock, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818aba80)
Location: net/socket.c:1032
Inline: False
Direct callers:
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:routing_ioctl
  - net/socket.c:sock_ioctl
```
**Symbols:**

```
ffffffff818aba80-ffffffff818abbb9: sock_do_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int sock_do_ioctl(struct net *net, struct socket *sock, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818659d0)
Location: net/socket.c:1032
Inline: False
Direct callers:
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:routing_ioctl
  - net/socket.c:sock_ioctl
```
**Symbols:**

```
ffffffff818659d0-ffffffff81865b09: sock_do_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int sock_do_ioctl(struct net *net, struct socket *sock, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818fca80)
Location: net/socket.c:1032
Inline: False
Direct callers:
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:routing_ioctl
  - net/socket.c:sock_ioctl
```
**Symbols:**

```
ffffffff818fca80-ffffffff818fcbb9: sock_do_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int sock_do_ioctl(struct net *net, struct socket *sock, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff8191daf0)
Location: net/socket.c:1032
Inline: False
Direct callers:
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:routing_ioctl
  - net/socket.c:sock_ioctl
```
**Symbols:**

```
ffffffff8191daf0-ffffffff8191dc29: sock_do_ioctl (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int ifreq_size</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>unsigned int ifreq_size</code>
</li>
</ul>
</details>
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
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
