# Function: <code>compat_sock_ioctl_trans</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int compat_sock_ioctl_trans(struct file *file, struct socket *sock, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff816fc010)
Location: net/socket.c:3044
Inline: False
Direct callers:
  - net/socket.c:compat_sock_ioctl
```
**Symbols:**

```
ffffffff816fc010-ffffffff816fc8ee: compat_sock_ioctl_trans (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int compat_sock_ioctl_trans(struct file *file, struct socket *sock, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81762a70)
Location: net/socket.c:3046
Inline: False
Direct callers:
  - net/socket.c:compat_sock_ioctl
```
**Symbols:**

```
ffffffff81762a70-ffffffff817633a8: compat_sock_ioctl_trans (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int compat_sock_ioctl_trans(struct file *file, struct socket *sock, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff8178fb60)
Location: net/socket.c:3093
Inline: False
Direct callers:
  - net/socket.c:compat_sock_ioctl
```
**Symbols:**

```
ffffffff8178fb60-ffffffff81790498: compat_sock_ioctl_trans (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff817af841)
Location: net/socket.c:3143
Inline: True
Inline callers:
  - net/socket.c:compat_sock_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81827994)
Location: net/socket.c:3145
Inline: True
Inline callers:
  - net/socket.c:compat_sock_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81871fc1)
Location: net/socket.c:3114
Inline: True
Inline callers:
  - net/socket.c:compat_sock_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81891b2f)
Location: net/socket.c:3179
Inline: True
Inline callers:
  - net/socket.c:compat_sock_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818dbb20)
Location: net/socket.c:3358
Inline: True
Inline callers:
  - net/socket.c:compat_sock_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff8190e700)
Location: net/socket.c:3438
Inline: True
Inline callers:
  - net/socket.c:compat_sock_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int compat_sock_ioctl_trans(struct file *file, struct socket *sock, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819e03d0)
Location: net/socket.c:3384
Inline: False
Direct callers:
  - net/socket.c:compat_sock_ioctl
```
**Symbols:**

```
ffffffff819e03d0-ffffffff819e08a7: compat_sock_ioctl_trans (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int compat_sock_ioctl_trans(struct file *file, struct socket *sock, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819dfd10)
Location: net/socket.c:3378
Inline: False
Direct callers:
  - net/socket.c:compat_sock_ioctl
```
**Symbols:**

```
ffffffff819dfd10-ffffffff819e00f6: compat_sock_ioctl_trans (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int compat_sock_ioctl_trans(struct file *file, struct socket *sock, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819c5990)
Location: net/socket.c:3364
Inline: False
Direct callers:
  - net/socket.c:compat_sock_ioctl
```
**Symbols:**

```
ffffffff819c5990-ffffffff819c5fa7: compat_sock_ioctl_trans (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int compat_sock_ioctl_trans(struct file *file, struct socket *sock, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81a75220)
Location: net/socket.c:3254
Inline: False
Direct callers:
  - net/socket.c:compat_sock_ioctl
```
**Symbols:**

```
ffffffff81a75220-ffffffff81a75517: compat_sock_ioctl_trans (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int compat_sock_ioctl_trans(struct file *file, struct socket *sock, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81be8030)
Location: net/socket.c:3315
Inline: False
Direct callers:
  - net/socket.c:compat_sock_ioctl
```
**Symbols:**

```
ffffffff81be8030-ffffffff81be8336: compat_sock_ioctl_trans (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int compat_sock_ioctl_trans(struct file *file, struct socket *sock, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81d94710)
Location: net/socket.c:3303
Inline: False
Direct callers:
  - net/socket.c:compat_sock_ioctl
```
**Symbols:**

```
ffffffff81d94710-ffffffff81d94a16: compat_sock_ioctl_trans (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int compat_sock_ioctl_trans(struct file *file, struct socket *sock, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81e02d50)
Location: net/socket.c:3341
Inline: False
Direct callers:
  - net/socket.c:compat_sock_ioctl
```
**Symbols:**

```
ffffffff81e02d50-ffffffff81e0305d: compat_sock_ioctl_trans (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int compat_sock_ioctl_trans(struct file *file, struct socket *sock, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81ebf750)
Location: net/socket.c:3411
Inline: False
Direct callers:
  - net/socket.c:compat_sock_ioctl
```
**Symbols:**

```
ffffffff81ebf750-ffffffff81ebfa5d: compat_sock_ioctl_trans (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/socket.c (ffff800010ba6c4c)
Location: net/socket.c:3438
Inline: True
Inline callers:
  - net/socket.c:compat_sock_ioctl
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/socket.c (c000000000c7ac90)
Location: net/socket.c:3438
Inline: True
Inline callers:
  - net/socket.c:compat_sock_ioctl
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818ae700)
Location: net/socket.c:3438
Inline: True
Inline callers:
  - net/socket.c:compat_sock_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81868650)
Location: net/socket.c:3438
Inline: True
Inline callers:
  - net/socket.c:compat_sock_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818ff700)
Location: net/socket.c:3438
Inline: True
Inline callers:
  - net/socket.c:compat_sock_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819206f0)
Location: net/socket.c:3438
Inline: True
Inline callers:
  - net/socket.c:compat_sock_ioctl
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
