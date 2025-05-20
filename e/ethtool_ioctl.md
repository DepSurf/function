# Function: <code>ethtool_ioctl</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff816fc376)
Location: net/socket.c:2671
Inline: True
Inline callers:
  - net/socket.c:compat_sock_ioctl_trans
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81762ca4)
Location: net/socket.c:2673
Inline: True
Inline callers:
  - net/socket.c:compat_sock_ioctl_trans
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff8178fd94)
Location: net/socket.c:2720
Inline: True
Inline callers:
  - net/socket.c:compat_sock_ioctl_trans
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ethtool_ioctl(struct net *net, struct compat_ifreq *ifr32);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff817af3b0)
Location: net/socket.c:2770
Inline: False
Direct callers:
  - net/socket.c:compat_sock_ioctl
```
**Symbols:**

```
ffffffff817af3b0-ffffffff817af78d: ethtool_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ethtool_ioctl(struct net *net, struct compat_ifreq *ifr32);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818274f0)
Location: net/socket.c:2772
Inline: False
Direct callers:
  - net/socket.c:compat_sock_ioctl
```
**Symbols:**

```
ffffffff818274f0-ffffffff818278d3: ethtool_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ethtool_ioctl(struct net *net, struct compat_ifreq *ifr32);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81870b10)
Location: net/socket.c:2818
Inline: False
Direct callers:
  - net/socket.c:compat_sock_ioctl
```
**Symbols:**

```
ffffffff81870b10-ffffffff81870f1d: ethtool_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ethtool_ioctl(struct net *net, struct compat_ifreq *ifr32);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81891630)
Location: net/socket.c:2831
Inline: False
Direct callers:
  - net/socket.c:compat_sock_ioctl
```
**Symbols:**

```
ffffffff81891630-ffffffff81891a70: ethtool_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ethtool_ioctl(struct net *net, struct compat_ifreq *ifr32);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818db1c0)
Location: net/socket.c:3010
Inline: False
Direct callers:
  - net/socket.c:compat_sock_ioctl
```
**Symbols:**

```
ffffffff818db1c0-ffffffff818db61d: ethtool_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ethtool_ioctl(struct net *net, struct compat_ifreq *ifr32);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff8190d310)
Location: net/socket.c:3090
Inline: False
Direct callers:
  - net/socket.c:compat_sock_ioctl
```
**Symbols:**

```
ffffffff8190d310-ffffffff8190d76d: ethtool_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ethtool_ioctl(struct net *net, struct compat_ifreq *ifr32);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819dffc0)
Location: net/socket.c:3124
Inline: False
Direct callers:
  - net/socket.c:compat_sock_ioctl_trans
```
**Symbols:**

```
ffffffff819dffc0-ffffffff819e03c8: ethtool_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ethtool_ioctl(struct net *net, struct compat_ifreq *ifr32);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819df780)
Location: net/socket.c:3118
Inline: False
Direct callers:
  - net/socket.c:compat_sock_ioctl_trans
```
**Symbols:**

```
ffffffff819df780-ffffffff819dfd0e: ethtool_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ethtool_ioctl(struct net *net, struct compat_ifreq *ifr32);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819c5530)
Location: net/socket.c:3102
Inline: False
Direct callers:
  - net/socket.c:compat_sock_ioctl_trans
```
**Symbols:**

```
ffffffff819c5530-ffffffff819c5987: ethtool_ioctl (STB_LOCAL)
```
</details>
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
int ethtool_ioctl(struct net *net, struct compat_ifreq *ifr32);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffff800010ba6200)
Location: net/socket.c:3090
Inline: False
Direct callers:
  - net/socket.c:compat_sock_ioctl
```
**Symbols:**

```
ffff800010ba6200-ffff800010ba6b8c: ethtool_ioctl (STB_LOCAL)
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
int ethtool_ioctl(struct net *net, struct compat_ifreq *ifr32);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (c000000000c7a280)
Location: net/socket.c:3090
Inline: False
Direct callers:
  - net/socket.c:compat_sock_ioctl
```
**Symbols:**

```
c000000000c7a280-c000000000c7ab9c: ethtool_ioctl (STB_LOCAL)
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
int ethtool_ioctl(struct net *net, struct compat_ifreq *ifr32);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818ad310)
Location: net/socket.c:3090
Inline: False
Direct callers:
  - net/socket.c:compat_sock_ioctl
```
**Symbols:**

```
ffffffff818ad310-ffffffff818ad76d: ethtool_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ethtool_ioctl(struct net *net, struct compat_ifreq *ifr32);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81867260)
Location: net/socket.c:3090
Inline: False
Direct callers:
  - net/socket.c:compat_sock_ioctl
```
**Symbols:**

```
ffffffff81867260-ffffffff818676bd: ethtool_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ethtool_ioctl(struct net *net, struct compat_ifreq *ifr32);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818fe310)
Location: net/socket.c:3090
Inline: False
Direct callers:
  - net/socket.c:compat_sock_ioctl
```
**Symbols:**

```
ffffffff818fe310-ffffffff818fe76d: ethtool_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ethtool_ioctl(struct net *net, struct compat_ifreq *ifr32);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff8191f390)
Location: net/socket.c:3090
Inline: False
Direct callers:
  - net/socket.c:compat_sock_ioctl
```
**Symbols:**

```
ffffffff8191f390-ffffffff8191f7ed: ethtool_ioctl (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
