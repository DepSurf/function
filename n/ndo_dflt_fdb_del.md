# Function: <code>ndo_dflt_fdb_del</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ndo_dflt_fdb_del(struct ndmsg *ndm, struct nlattr **tb, struct net_device *dev, const unsigned char *addr, u16 vid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff8172a9f0)
Location: net/core/rtnetlink.c:2760
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_fdb_del
```
**Symbols:**

```
ffffffff8172a9f0-ffffffff8172aa4e: ndo_dflt_fdb_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ndo_dflt_fdb_del(struct ndmsg *ndm, struct nlattr **tb, struct net_device *dev, const unsigned char *addr, u16 vid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81794470)
Location: net/core/rtnetlink.c:2956
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_fdb_del
```
**Symbols:**

```
ffffffff81794470-ffffffff817944ce: ndo_dflt_fdb_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ndo_dflt_fdb_del(struct ndmsg *ndm, struct nlattr **tb, struct net_device *dev, const unsigned char *addr, u16 vid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff817c1cf0)
Location: net/core/rtnetlink.c:3032
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_fdb_del
```
**Symbols:**

```
ffffffff817c1cf0-ffffffff817c1d4e: ndo_dflt_fdb_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ndo_dflt_fdb_del(struct ndmsg *ndm, struct nlattr **tb, struct net_device *dev, const unsigned char *addr, u16 vid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff817e0480)
Location: net/core/rtnetlink.c:3129
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_fdb_del
```
**Symbols:**

```
ffffffff817e0480-ffffffff817e04de: ndo_dflt_fdb_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ndo_dflt_fdb_del(struct ndmsg *ndm, struct nlattr **tb, struct net_device *dev, const unsigned char *addr, u16 vid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff8185acf0)
Location: net/core/rtnetlink.c:3366
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_fdb_del
```
**Symbols:**

```
ffffffff8185acf0-ffffffff8185ad4e: ndo_dflt_fdb_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int ndo_dflt_fdb_del(struct ndmsg *ndm, struct nlattr **tb, struct net_device *dev, const unsigned char *addr, u16 vid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/rtnetlink.c (0)
Location: net/core/rtnetlink.c:3524
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_fdb_del
```
**Symbols:**

```
ffffffff818ad559-ffffffff818ad572: ndo_dflt_fdb_del.cold.42 (STB_LOCAL)
ffffffff818a65a0-ffffffff818a65ec: ndo_dflt_fdb_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int ndo_dflt_fdb_del(struct ndmsg *ndm, struct nlattr **tb, struct net_device *dev, const unsigned char *addr, u16 vid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/rtnetlink.c (0)
Location: net/core/rtnetlink.c:3672
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_fdb_del
```
**Symbols:**

```
ffffffff818d17b9-ffffffff818d17d2: ndo_dflt_fdb_del.cold.43 (STB_LOCAL)
ffffffff818c9df0-ffffffff818c9e3c: ndo_dflt_fdb_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int ndo_dflt_fdb_del(struct ndmsg *ndm, struct nlattr **tb, struct net_device *dev, const unsigned char *addr, u16 vid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/rtnetlink.c (0)
Location: net/core/rtnetlink.c:3735
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_fdb_del
```
**Symbols:**

```
ffffffff8191e6b3-ffffffff8191e6cc: ndo_dflt_fdb_del.cold (STB_LOCAL)
ffffffff81916de0-ffffffff81916e2c: ndo_dflt_fdb_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int ndo_dflt_fdb_del(struct ndmsg *ndm, struct nlattr **tb, struct net_device *dev, const unsigned char *addr, u16 vid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/rtnetlink.c (0)
Location: net/core/rtnetlink.c:3766
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_fdb_del
```
**Symbols:**

```
ffffffff81950cb7-ffffffff81950cd0: ndo_dflt_fdb_del.cold (STB_LOCAL)
ffffffff81949420-ffffffff8194946c: ndo_dflt_fdb_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int ndo_dflt_fdb_del(struct ndmsg *ndm, struct nlattr **tb, struct net_device *dev, const unsigned char *addr, u16 vid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/rtnetlink.c (0)
Location: net/core/rtnetlink.c:3969
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_fdb_del
```
**Symbols:**

```
ffffffff81a21b4f-ffffffff81a21b68: ndo_dflt_fdb_del.cold (STB_LOCAL)
ffffffff81a19300-ffffffff81a19344: ndo_dflt_fdb_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int ndo_dflt_fdb_del(struct ndmsg *ndm, struct nlattr **tb, struct net_device *dev, const unsigned char *addr, u16 vid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/rtnetlink.c (0)
Location: net/core/rtnetlink.c:4061
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_fdb_del
```
**Symbols:**

```
ffffffff81c31674-ffffffff81c3168d: ndo_dflt_fdb_del.cold (STB_LOCAL)
ffffffff81a194f0-ffffffff81a19534: ndo_dflt_fdb_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int ndo_dflt_fdb_del(struct ndmsg *ndm, struct nlattr **tb, struct net_device *dev, const unsigned char *addr, u16 vid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/rtnetlink.c (0)
Location: net/core/rtnetlink.c:4059
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_fdb_del
```
**Symbols:**

```
ffffffff81c2397d-ffffffff81c23996: ndo_dflt_fdb_del.cold (STB_LOCAL)
ffffffff81a00400-ffffffff81a00444: ndo_dflt_fdb_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int ndo_dflt_fdb_del(struct ndmsg *ndm, struct nlattr **tb, struct net_device *dev, const unsigned char *addr, u16 vid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/rtnetlink.c (0)
Location: net/core/rtnetlink.c:4080
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_fdb_del
```
**Symbols:**

```
ffffffff81d36d84-ffffffff81d36d9a: ndo_dflt_fdb_del.cold (STB_LOCAL)
ffffffff81ab2550-ffffffff81ab2594: ndo_dflt_fdb_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int ndo_dflt_fdb_del(struct ndmsg *ndm, struct nlattr **tb, struct net_device *dev, const unsigned char *addr, u16 vid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/rtnetlink.c (0)
Location: net/core/rtnetlink.c:4171
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_fdb_del
```
**Symbols:**

```
ffffffff81f03698-ffffffff81f036ae: ndo_dflt_fdb_del.cold (STB_LOCAL)
ffffffff81c2b5b0-ffffffff81c2b60b: ndo_dflt_fdb_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ndo_dflt_fdb_del(struct ndmsg *ndm, struct nlattr **tb, struct net_device *dev, const unsigned char *addr, u16 vid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81dde1b0)
Location: net/core/rtnetlink.c:4222
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_fdb_del
```
**Symbols:**

```
ffffffff81dde1b0-ffffffff81dde226: ndo_dflt_fdb_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ndo_dflt_fdb_del(struct ndmsg *ndm, struct nlattr **tb, struct net_device *dev, const unsigned char *addr, u16 vid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81e4f0f0)
Location: net/core/rtnetlink.c:4311
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_fdb_del
```
**Symbols:**

```
ffffffff81e4f0f0-ffffffff81e4f166: ndo_dflt_fdb_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ndo_dflt_fdb_del(struct ndmsg *ndm, struct nlattr **tb, struct net_device *dev, const unsigned char *addr, u16 vid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81f0dfc0)
Location: net/core/rtnetlink.c:4351
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_fdb_del
```
**Symbols:**

```
ffffffff81f0dfc0-ffffffff81f0e036: ndo_dflt_fdb_del (STB_GLOBAL)
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
int ndo_dflt_fdb_del(struct ndmsg *ndm, struct nlattr **tb, struct net_device *dev, const unsigned char *addr, u16 vid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffff800010beaef0)
Location: net/core/rtnetlink.c:3766
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_fdb_del
```
**Symbols:**

```
ffff800010beaef0-ffff800010beaf94: ndo_dflt_fdb_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ndo_dflt_fdb_del(struct ndmsg *ndm, struct nlattr **tb, struct net_device *dev, const unsigned char *addr, u16 vid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (c0d03c54)
Location: net/core/rtnetlink.c:3766
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_fdb_del
```
**Symbols:**

```
c0d03c54-c0d03ccc: ndo_dflt_fdb_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ndo_dflt_fdb_del(struct ndmsg *ndm, struct nlattr **tb, struct net_device *dev, const unsigned char *addr, u16 vid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (c000000000cce230)
Location: net/core/rtnetlink.c:3766
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_fdb_del
```
**Symbols:**

```
c000000000cce230-c000000000cce2e4: ndo_dflt_fdb_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ndo_dflt_fdb_del(struct ndmsg *ndm, struct nlattr **tb, struct net_device *dev, const unsigned char *addr, u16 vid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffe00076e938)
Location: net/core/rtnetlink.c:3766
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_fdb_del
```
**Symbols:**

```
ffffffe00076e938-ffffffe00076e9d4: ndo_dflt_fdb_del (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int ndo_dflt_fdb_del(struct ndmsg *ndm, struct nlattr **tb, struct net_device *dev, const unsigned char *addr, u16 vid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/rtnetlink.c (0)
Location: net/core/rtnetlink.c:3766
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_fdb_del
```
**Symbols:**

```
ffffffff818f0c87-ffffffff818f0ca0: ndo_dflt_fdb_del.cold (STB_LOCAL)
ffffffff818e93f0-ffffffff818e943c: ndo_dflt_fdb_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int ndo_dflt_fdb_del(struct ndmsg *ndm, struct nlattr **tb, struct net_device *dev, const unsigned char *addr, u16 vid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/rtnetlink.c (0)
Location: net/core/rtnetlink.c:3766
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_fdb_del
```
**Symbols:**

```
ffffffff818aaac7-ffffffff818aaae0: ndo_dflt_fdb_del.cold (STB_LOCAL)
ffffffff818a3230-ffffffff818a327c: ndo_dflt_fdb_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int ndo_dflt_fdb_del(struct ndmsg *ndm, struct nlattr **tb, struct net_device *dev, const unsigned char *addr, u16 vid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/rtnetlink.c (0)
Location: net/core/rtnetlink.c:3766
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_fdb_del
```
**Symbols:**

```
ffffffff81941cb7-ffffffff81941cd0: ndo_dflt_fdb_del.cold (STB_LOCAL)
ffffffff8193a420-ffffffff8193a46c: ndo_dflt_fdb_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int ndo_dflt_fdb_del(struct ndmsg *ndm, struct nlattr **tb, struct net_device *dev, const unsigned char *addr, u16 vid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/rtnetlink.c (0)
Location: net/core/rtnetlink.c:3766
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_fdb_del
```
**Symbols:**

```
ffffffff819635b7-ffffffff819635d0: ndo_dflt_fdb_del.cold (STB_LOCAL)
ffffffff8195bc50-ffffffff8195bc9c: ndo_dflt_fdb_del (STB_GLOBAL)
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
