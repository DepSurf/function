# Function: <code>compat_ifr_data_ioctl</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int compat_ifr_data_ioctl(struct net *net, unsigned int cmd, struct compat_ifreq *u_ifreq32);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff816fbcc0)
Location: net/socket.c:2841
Inline: False
Direct callers:
  - net/socket.c:compat_sock_ioctl_trans
```
**Symbols:**

```
ffffffff816fbcc0-ffffffff816fbd7f: compat_ifr_data_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int compat_ifr_data_ioctl(struct net *net, unsigned int cmd, struct compat_ifreq *u_ifreq32);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81762720)
Location: net/socket.c:2843
Inline: False
Direct callers:
  - net/socket.c:compat_sock_ioctl_trans
```
**Symbols:**

```
ffffffff81762720-ffffffff817627df: compat_ifr_data_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int compat_ifr_data_ioctl(struct net *net, unsigned int cmd, struct compat_ifreq *u_ifreq32);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff8178f750)
Location: net/socket.c:2890
Inline: False
Direct callers:
  - net/socket.c:compat_sock_ioctl_trans
```
**Symbols:**

```
ffffffff8178f750-ffffffff8178f80f: compat_ifr_data_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int compat_ifr_data_ioctl(struct net *net, unsigned int cmd, struct compat_ifreq *u_ifreq32);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff817ad710)
Location: net/socket.c:2940
Inline: False
Direct callers:
  - net/socket.c:compat_sock_ioctl
```
**Symbols:**

```
ffffffff817ad710-ffffffff817ad7cf: compat_ifr_data_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int compat_ifr_data_ioctl(struct net *net, unsigned int cmd, struct compat_ifreq *u_ifreq32);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818256b0)
Location: net/socket.c:2942
Inline: False
Direct callers:
  - net/socket.c:compat_sock_ioctl
```
**Symbols:**

```
ffffffff818256b0-ffffffff8182576f: compat_ifr_data_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int compat_ifr_data_ioctl(struct net *net, unsigned int cmd, struct compat_ifreq *u_ifreq32);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff8186f440)
Location: net/socket.c:2961
Inline: False
Direct callers:
  - net/socket.c:compat_sock_ioctl
```
**Symbols:**

```
ffffffff8186f440-ffffffff8186f4d0: compat_ifr_data_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int compat_ifr_data_ioctl(struct net *net, unsigned int cmd, struct compat_ifreq *u_ifreq32);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff8188f9a0)
Location: net/socket.c:2979
Inline: False
Direct callers:
  - net/socket.c:compat_sock_ioctl
```
**Symbols:**

```
ffffffff8188f9a0-ffffffff8188fa30: compat_ifr_data_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int compat_ifr_data_ioctl(struct net *net, unsigned int cmd, struct compat_ifreq *u_ifreq32);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818d9a10)
Location: net/socket.c:3158
Inline: False
Direct callers:
  - net/socket.c:compat_sock_ioctl
```
**Symbols:**

```
ffffffff818d9a10-ffffffff818d9aa0: compat_ifr_data_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int compat_ifr_data_ioctl(struct net *net, unsigned int cmd, struct compat_ifreq *u_ifreq32);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff8190b9f0)
Location: net/socket.c:3238
Inline: False
Direct callers:
  - net/socket.c:compat_sock_ioctl
```
**Symbols:**

```
ffffffff8190b9f0-ffffffff8190ba80: compat_ifr_data_ioctl (STB_LOCAL)
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
In net/socket.c (ffffffff819e0796)
Location: net/socket.c:3272
Inline: True
Inline callers:
  - net/socket.c:compat_sock_ioctl_trans
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
In net/socket.c (ffffffff819dfff5)
Location: net/socket.c:3266
Inline: True
Inline callers:
  - net/socket.c:compat_sock_ioctl_trans
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int compat_ifr_data_ioctl(struct net *net, unsigned int cmd, struct compat_ifreq *u_ifreq32);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819c3800)
Location: net/socket.c:3250
Inline: False
Direct callers:
  - net/socket.c:compat_sock_ioctl_trans
```
**Symbols:**

```
ffffffff819c3800-ffffffff819c389b: compat_ifr_data_ioctl (STB_LOCAL)
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
In net/socket.c (ffffffff81a7543b)
Location: net/socket.c:3224
Inline: True
Inline callers:
  - net/socket.c:compat_sock_ioctl_trans
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
In net/socket.c (ffffffff81be8223)
Location: net/socket.c:3300
Inline: True
Inline callers:
  - net/socket.c:compat_sock_ioctl_trans
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
In net/socket.c (ffffffff81d94903)
Location: net/socket.c:3288
Inline: True
Inline callers:
  - net/socket.c:compat_sock_ioctl_trans
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
In net/socket.c (ffffffff81e02e79)
Location: net/socket.c:3326
Inline: True
Inline callers:
  - net/socket.c:compat_sock_ioctl_trans
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
In net/socket.c (ffffffff81ebf879)
Location: net/socket.c:3396
Inline: True
Inline callers:
  - net/socket.c:compat_sock_ioctl_trans
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
int compat_ifr_data_ioctl(struct net *net, unsigned int cmd, struct compat_ifreq *u_ifreq32);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffff800010ba3fe0)
Location: net/socket.c:3238
Inline: False
Direct callers:
  - net/socket.c:compat_sock_ioctl
```
**Symbols:**

```
ffff800010ba3fe0-ffff800010ba42d0: compat_ifr_data_ioctl (STB_LOCAL)
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
int compat_ifr_data_ioctl(struct net *net, unsigned int cmd, struct compat_ifreq *u_ifreq32);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (c000000000c778c0)
Location: net/socket.c:3238
Inline: False
Direct callers:
  - net/socket.c:compat_sock_ioctl
```
**Symbols:**

```
c000000000c778c0-c000000000c77a00: compat_ifr_data_ioctl (STB_LOCAL)
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
int compat_ifr_data_ioctl(struct net *net, unsigned int cmd, struct compat_ifreq *u_ifreq32);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818ab9f0)
Location: net/socket.c:3238
Inline: False
Direct callers:
  - net/socket.c:compat_sock_ioctl
```
**Symbols:**

```
ffffffff818ab9f0-ffffffff818aba80: compat_ifr_data_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int compat_ifr_data_ioctl(struct net *net, unsigned int cmd, struct compat_ifreq *u_ifreq32);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81865940)
Location: net/socket.c:3238
Inline: False
Direct callers:
  - net/socket.c:compat_sock_ioctl
```
**Symbols:**

```
ffffffff81865940-ffffffff818659d0: compat_ifr_data_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int compat_ifr_data_ioctl(struct net *net, unsigned int cmd, struct compat_ifreq *u_ifreq32);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818fc9f0)
Location: net/socket.c:3238
Inline: False
Direct callers:
  - net/socket.c:compat_sock_ioctl
```
**Symbols:**

```
ffffffff818fc9f0-ffffffff818fca80: compat_ifr_data_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int compat_ifr_data_ioctl(struct net *net, unsigned int cmd, struct compat_ifreq *u_ifreq32);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff8191da60)
Location: net/socket.c:3238
Inline: False
Direct callers:
  - net/socket.c:compat_sock_ioctl
```
**Symbols:**

```
ffffffff8191da60-ffffffff8191daf0: compat_ifr_data_ioctl (STB_LOCAL)
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
