# Function: <code>routing_ioctl</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int routing_ioctl(struct net *net, struct socket *sock, unsigned int cmd, void *argp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff816fba60)
Location: net/socket.c:2972
Inline: False
Direct callers:
  - net/socket.c:compat_sock_ioctl_trans
```
**Symbols:**

```
ffffffff816fba60-ffffffff816fbcb2: routing_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int routing_ioctl(struct net *net, struct socket *sock, unsigned int cmd, void *argp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff817624c0)
Location: net/socket.c:2974
Inline: False
Direct callers:
  - net/socket.c:compat_sock_ioctl_trans
```
**Symbols:**

```
ffffffff817624c0-ffffffff81762712: routing_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int routing_ioctl(struct net *net, struct socket *sock, unsigned int cmd, void *argp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff8178f4f0)
Location: net/socket.c:3021
Inline: False
Direct callers:
  - net/socket.c:compat_sock_ioctl_trans
```
**Symbols:**

```
ffffffff8178f4f0-ffffffff8178f742: routing_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int routing_ioctl(struct net *net, struct socket *sock, unsigned int cmd, void *argp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff817ad470)
Location: net/socket.c:3071
Inline: False
Direct callers:
  - net/socket.c:compat_sock_ioctl
```
**Symbols:**

```
ffffffff817ad470-ffffffff817ad701: routing_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int routing_ioctl(struct net *net, struct socket *sock, unsigned int cmd, void *argp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81825410)
Location: net/socket.c:3073
Inline: False
Direct callers:
  - net/socket.c:compat_sock_ioctl
```
**Symbols:**

```
ffffffff81825410-ffffffff818256ab: routing_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int routing_ioctl(struct net *net, struct socket *sock, unsigned int cmd, void *argp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81871970)
Location: net/socket.c:3041
Inline: False
Direct callers:
  - net/socket.c:compat_sock_ioctl
```
**Symbols:**

```
ffffffff81871970-ffffffff81871bfa: routing_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int routing_ioctl(struct net *net, struct socket *sock, unsigned int cmd, void *argp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff8188fb70)
Location: net/socket.c:3107
Inline: False
Direct callers:
  - net/socket.c:compat_sock_ioctl
```
**Symbols:**

```
ffffffff8188fb70-ffffffff8188fdf4: routing_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int routing_ioctl(struct net *net, struct socket *sock, unsigned int cmd, void *argp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818db7b0)
Location: net/socket.c:3286
Inline: False
Direct callers:
  - net/socket.c:compat_sock_ioctl
```
**Symbols:**

```
ffffffff818db7b0-ffffffff818dba4b: routing_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int routing_ioctl(struct net *net, struct socket *sock, unsigned int cmd, void *argp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff8190e390)
Location: net/socket.c:3366
Inline: False
Direct callers:
  - net/socket.c:compat_sock_ioctl
```
**Symbols:**

```
ffffffff8190e390-ffffffff8190e62b: routing_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int routing_ioctl(struct net *net, struct socket *sock, unsigned int cmd, void *argp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffff800010ba5308)
Location: net/socket.c:3366
Inline: False
Direct callers:
  - net/socket.c:compat_sock_ioctl
```
**Symbols:**

```
ffff800010ba5308-ffff800010ba5d1c: routing_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int routing_ioctl(struct net *net, struct socket *sock, unsigned int cmd, void *argp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (c000000000c79880)
Location: net/socket.c:3366
Inline: False
Direct callers:
  - net/socket.c:compat_sock_ioctl
```
**Symbols:**

```
c000000000c79880-c000000000c7a274: routing_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int routing_ioctl(struct net *net, struct socket *sock, unsigned int cmd, void *argp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818ae390)
Location: net/socket.c:3366
Inline: False
Direct callers:
  - net/socket.c:compat_sock_ioctl
```
**Symbols:**

```
ffffffff818ae390-ffffffff818ae62b: routing_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int routing_ioctl(struct net *net, struct socket *sock, unsigned int cmd, void *argp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818682e0)
Location: net/socket.c:3366
Inline: False
Direct callers:
  - net/socket.c:compat_sock_ioctl
```
**Symbols:**

```
ffffffff818682e0-ffffffff8186857b: routing_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int routing_ioctl(struct net *net, struct socket *sock, unsigned int cmd, void *argp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818ff390)
Location: net/socket.c:3366
Inline: False
Direct callers:
  - net/socket.c:compat_sock_ioctl
```
**Symbols:**

```
ffffffff818ff390-ffffffff818ff62b: routing_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int routing_ioctl(struct net *net, struct socket *sock, unsigned int cmd, void *argp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81920380)
Location: net/socket.c:3366
Inline: False
Direct callers:
  - net/socket.c:compat_sock_ioctl
```
**Symbols:**

```
ffffffff81920380-ffffffff8192061b: routing_ioctl (STB_LOCAL)
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
