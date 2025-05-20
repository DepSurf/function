# Function: <code>dev_ethtool</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int dev_ethtool(struct net *net, struct ifreq *ifr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/ethtool.c (ffffffff81720810)
Location: net/core/ethtool.c:1809
Inline: False
Direct callers:
  - net/core/dev_ioctl.c:dev_ioctl
```
**Symbols:**

```
ffffffff81720810-ffffffff81722578: dev_ethtool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int dev_ethtool(struct net *net, struct ifreq *ifr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/ethtool.c (ffffffff8178a010)
Location: net/core/ethtool.c:2427
Inline: False
Direct callers:
  - net/core/dev_ioctl.c:dev_ioctl
```
**Symbols:**

```
ffffffff8178a010-ffffffff8178bfcb: dev_ethtool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int dev_ethtool(struct net *net, struct ifreq *ifr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/ethtool.c (ffffffff817b78f0)
Location: net/core/ethtool.c:2520
Inline: False
Direct callers:
  - net/core/dev_ioctl.c:dev_ioctl
```
**Symbols:**

```
ffffffff817b78f0-ffffffff817b9899: dev_ethtool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int dev_ethtool(struct net *net, struct ifreq *ifr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/ethtool.c (ffffffff817d61b0)
Location: net/core/ethtool.c:2522
Inline: False
Direct callers:
  - net/core/dev_ioctl.c:dev_ioctl
```
**Symbols:**

```
ffffffff817d61b0-ffffffff817d83e6: dev_ethtool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int dev_ethtool(struct net *net, struct ifreq *ifr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/ethtool.c (ffffffff818506f0)
Location: net/core/ethtool.c:2552
Inline: False
Direct callers:
  - net/core/dev_ioctl.c:dev_ioctl
```
**Symbols:**

```
ffffffff818506f0-ffffffff81852aea: dev_ethtool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int dev_ethtool(struct net *net, struct ifreq *ifr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/ethtool.c (ffffffff8189bad0)
Location: net/core/ethtool.c:2590
Inline: False
Direct callers:
  - net/core/dev_ioctl.c:dev_ioctl
```
**Symbols:**

```
ffffffff8189bad0-ffffffff8189e1fa: dev_ethtool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int dev_ethtool(struct net *net, struct ifreq *ifr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/ethtool.c (ffffffff818bdee0)
Location: net/core/ethtool.c:2536
Inline: False
Direct callers:
  - net/core/dev_ioctl.c:dev_ioctl
```
**Symbols:**

```
ffffffff818bdee0-ffffffff818c0a1d: dev_ethtool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int dev_ethtool(struct net *net, struct ifreq *ifr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/ethtool.c (0)
Location: net/core/ethtool.c:2555
Inline: False
Direct callers:
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
```
**Symbols:**

```
ffffffff8190d0fb-ffffffff8190d12b: dev_ethtool.cold (STB_LOCAL)
ffffffff8190a8d0-ffffffff8190d0fb: dev_ethtool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int dev_ethtool(struct net *net, struct ifreq *ifr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/ethtool.c (ffffffff8193cee0)
Location: net/core/ethtool.c:2561
Inline: False
Direct callers:
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
```
**Symbols:**

```
ffffffff8193cee0-ffffffff8193f82d: dev_ethtool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int dev_ethtool(struct net *net, struct ifreq *ifr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/ioctl.c (ffffffff81a84130)
Location: net/ethtool/ioctl.c:2550
Inline: False
Direct callers:
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
```
**Symbols:**

```
ffffffff81a84130-ffffffff81a8550a: dev_ethtool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int dev_ethtool(struct net *net, struct ifreq *ifr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/ioctl.c (ffffffff81a8dc60)
Location: net/ethtool/ioctl.c:2563
Inline: False
Direct callers:
  - net/core/dev_ioctl.c:dev_ioctl
```
**Symbols:**

```
ffffffff81a8dc60-ffffffff81a8ee81: dev_ethtool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int dev_ethtool(struct net *net, struct ifreq *ifr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/ioctl.c (ffffffff81a76b90)
Location: net/ethtool/ioctl.c:2584
Inline: False
Direct callers:
  - net/core/dev_ioctl.c:dev_ioctl
```
**Symbols:**

```
ffffffff81a76b90-ffffffff81a7854a: dev_ethtool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int dev_ethtool(struct net *net, struct ifreq *ifr, void *useraddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/ioctl.c (ffffffff81b30d60)
Location: net/ethtool/ioctl.c:2698
Inline: False
Direct callers:
  - net/core/dev_ioctl.c:dev_ioctl
```
**Symbols:**

```
ffffffff81b30d60-ffffffff81b32615: dev_ethtool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int dev_ethtool(struct net *net, struct ifreq *ifr, void *useraddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/ioctl.c (ffffffff81cbd9f0)
Location: net/ethtool/ioctl.c:3027
Inline: False
Direct callers:
  - net/core/dev_ioctl.c:dev_ioctl
```
**Symbols:**

```
ffffffff81cbd9f0-ffffffff81cbdb6d: dev_ethtool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int dev_ethtool(struct net *net, struct ifreq *ifr, void *useraddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/ioctl.c (ffffffff81e7c0f0)
Location: net/ethtool/ioctl.c:3054
Inline: False
Direct callers:
  - net/core/dev_ioctl.c:dev_ioctl
```
**Symbols:**

```
ffffffff81e7c0f0-ffffffff81e7c26d: dev_ethtool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int dev_ethtool(struct net *net, struct ifreq *ifr, void *useraddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/ioctl.c (ffffffff81ed8480)
Location: net/ethtool/ioctl.c:3066
Inline: False
Direct callers:
  - net/core/dev_ioctl.c:dev_ioctl
```
**Symbols:**

```
ffffffff81ed8480-ffffffff81ed8601: dev_ethtool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int dev_ethtool(struct net *net, struct ifreq *ifr, void *useraddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/ioctl.c (ffffffff81f9c1a0)
Location: net/ethtool/ioctl.c:3115
Inline: False
Direct callers:
  - net/core/dev_ioctl.c:dev_ioctl
```
**Symbols:**

```
ffffffff81f9c1a0-ffffffff81f9c351: dev_ethtool (STB_GLOBAL)
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
int dev_ethtool(struct net *net, struct ifreq *ifr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/ethtool.c (ffff800010bdc768)
Location: net/core/ethtool.c:2561
Inline: False
Direct callers:
  - net/core/dev_ioctl.c:dev_ioctl
```
**Symbols:**

```
ffff800010bdc768-ffff800010bde878: dev_ethtool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int dev_ethtool(struct net *net, struct ifreq *ifr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/ethtool.c (c0cf6e08)
Location: net/core/ethtool.c:2561
Inline: False
Direct callers:
  - net/core/dev_ioctl.c:dev_ioctl
```
**Symbols:**

```
c0cf6e08-c0cf94fc: dev_ethtool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int dev_ethtool(struct net *net, struct ifreq *ifr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/ethtool.c (c000000000cbc780)
Location: net/core/ethtool.c:2561
Inline: False
Direct callers:
  - net/core/dev_ioctl.c:dev_ioctl
```
**Symbols:**

```
c000000000cbc780-c000000000cbf16c: dev_ethtool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int dev_ethtool(struct net *net, struct ifreq *ifr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/ethtool.c (ffffffe000763dc2)
Location: net/core/ethtool.c:2561
Inline: False
Direct callers:
  - net/core/dev_ioctl.c:dev_ioctl
```
**Symbols:**

```
ffffffe000763dc2-ffffffe0007657b2: dev_ethtool (STB_GLOBAL)
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
int dev_ethtool(struct net *net, struct ifreq *ifr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/ethtool.c (ffffffff818dceb0)
Location: net/core/ethtool.c:2561
Inline: False
Direct callers:
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
```
**Symbols:**

```
ffffffff818dceb0-ffffffff818df7fd: dev_ethtool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int dev_ethtool(struct net *net, struct ifreq *ifr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/ethtool.c (ffffffff81896cf0)
Location: net/core/ethtool.c:2561
Inline: False
Direct callers:
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
```
**Symbols:**

```
ffffffff81896cf0-ffffffff8189963d: dev_ethtool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int dev_ethtool(struct net *net, struct ifreq *ifr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/ethtool.c (ffffffff8192dee0)
Location: net/core/ethtool.c:2561
Inline: False
Direct callers:
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
```
**Symbols:**

```
ffffffff8192dee0-ffffffff8193082d: dev_ethtool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int dev_ethtool(struct net *net, struct ifreq *ifr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/ethtool.c (ffffffff8194f5b0)
Location: net/core/ethtool.c:2561
Inline: False
Direct callers:
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
```
**Symbols:**

```
ffffffff8194f5b0-ffffffff81951efd: dev_ethtool (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>void *useraddr</code>
</li>
</ul>
</details>
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
