# Function: <code>rtmsg_ifinfo_newnet</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void rtmsg_ifinfo_newnet(int type, struct net_device *dev, unsigned int change, gfp_t flags, int *new_nsid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81861940)
Location: net/core/rtnetlink.c:3155
Inline: False
```
**Symbols:**

```
ffffffff81861940-ffffffff81861963: rtmsg_ifinfo_newnet (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void rtmsg_ifinfo_newnet(int type, struct net_device *dev, unsigned int change, gfp_t flags, int *new_nsid, int new_ifindex);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff818ad500)
Location: net/core/rtnetlink.c:3313
Inline: False
Direct callers:
  - net/core/dev.c:dev_change_net_namespace
```
**Symbols:**

```
ffffffff818ad500-ffffffff818ad527: rtmsg_ifinfo_newnet (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void rtmsg_ifinfo_newnet(int type, struct net_device *dev, unsigned int change, gfp_t flags, int *new_nsid, int new_ifindex);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff818d1760)
Location: net/core/rtnetlink.c:3456
Inline: False
Direct callers:
  - net/core/dev.c:dev_change_net_namespace
```
**Symbols:**

```
ffffffff818d1760-ffffffff818d1787: rtmsg_ifinfo_newnet (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void rtmsg_ifinfo_newnet(int type, struct net_device *dev, unsigned int change, gfp_t flags, int *new_nsid, int new_ifindex);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff8191e630)
Location: net/core/rtnetlink.c:3517
Inline: False
Direct callers:
  - net/core/dev.c:dev_change_net_namespace
```
**Symbols:**

```
ffffffff8191e630-ffffffff8191e655: rtmsg_ifinfo_newnet (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void rtmsg_ifinfo_newnet(int type, struct net_device *dev, unsigned int change, gfp_t flags, int *new_nsid, int new_ifindex);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81950c60)
Location: net/core/rtnetlink.c:3548
Inline: False
Direct callers:
  - net/core/dev.c:dev_change_net_namespace
```
**Symbols:**

```
ffffffff81950c60-ffffffff81950c85: rtmsg_ifinfo_newnet (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void rtmsg_ifinfo_newnet(int type, struct net_device *dev, unsigned int change, gfp_t flags, int *new_nsid, int new_ifindex);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81a21ac0)
Location: net/core/rtnetlink.c:3751
Inline: False
Direct callers:
  - net/core/dev.c:dev_change_net_namespace
```
**Symbols:**

```
ffffffff81a21ac0-ffffffff81a21b1d: rtmsg_ifinfo_newnet (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void rtmsg_ifinfo_newnet(int type, struct net_device *dev, unsigned int change, gfp_t flags, int *new_nsid, int new_ifindex);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81a21f00)
Location: net/core/rtnetlink.c:3843
Inline: False
Direct callers:
  - net/core/dev.c:dev_change_net_namespace
```
**Symbols:**

```
ffffffff81a21f00-ffffffff81a21f5d: rtmsg_ifinfo_newnet (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void rtmsg_ifinfo_newnet(int type, struct net_device *dev, unsigned int change, gfp_t flags, int *new_nsid, int new_ifindex);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81a09230)
Location: net/core/rtnetlink.c:3841
Inline: False
Direct callers:
  - net/core/dev.c:__dev_change_net_namespace
```
**Symbols:**

```
ffffffff81a09230-ffffffff81a0928d: rtmsg_ifinfo_newnet (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void rtmsg_ifinfo_newnet(int type, struct net_device *dev, unsigned int change, gfp_t flags, int *new_nsid, int new_ifindex);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81abb700)
Location: net/core/rtnetlink.c:3862
Inline: False
Direct callers:
  - net/core/dev.c:__dev_change_net_namespace
```
**Symbols:**

```
ffffffff81abb700-ffffffff81abb75d: rtmsg_ifinfo_newnet (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void rtmsg_ifinfo_newnet(int type, struct net_device *dev, unsigned int change, gfp_t flags, int *new_nsid, int new_ifindex);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81c35fb0)
Location: net/core/rtnetlink.c:3953
Inline: False
Direct callers:
  - net/core/dev.c:__dev_change_net_namespace
```
**Symbols:**

```
ffffffff81c35fb0-ffffffff81c36035: rtmsg_ifinfo_newnet (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void rtmsg_ifinfo_newnet(int type, struct net_device *dev, unsigned int change, gfp_t flags, int *new_nsid, int new_ifindex);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81de9630)
Location: net/core/rtnetlink.c:3999
Inline: False
Direct callers:
  - net/core/dev.c:__dev_change_net_namespace
```
**Symbols:**

```
ffffffff81de9630-ffffffff81de96bc: rtmsg_ifinfo_newnet (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void rtmsg_ifinfo_newnet(int type, struct net_device *dev, unsigned int change, gfp_t flags, int *new_nsid, int new_ifindex);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81e5ae40)
Location: net/core/rtnetlink.c:4088
Inline: False
Direct callers:
  - net/core/dev.c:__dev_change_net_namespace
```
**Symbols:**

```
ffffffff81e5ae40-ffffffff81e5aecc: rtmsg_ifinfo_newnet (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void rtmsg_ifinfo_newnet(int type, struct net_device *dev, unsigned int change, gfp_t flags, int *new_nsid, int new_ifindex);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81f1a200)
Location: net/core/rtnetlink.c:4128
Inline: False
Direct callers:
  - net/core/dev.c:__dev_change_net_namespace
```
**Symbols:**

```
ffffffff81f1a200-ffffffff81f1a28c: rtmsg_ifinfo_newnet (STB_GLOBAL)
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
void rtmsg_ifinfo_newnet(int type, struct net_device *dev, unsigned int change, gfp_t flags, int *new_nsid, int new_ifindex);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffff800010bf2838)
Location: net/core/rtnetlink.c:3548
Inline: False
Direct callers:
  - net/core/dev.c:dev_change_net_namespace
```
**Symbols:**

```
ffff800010bf2838-ffff800010bf28c0: rtmsg_ifinfo_newnet (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void rtmsg_ifinfo_newnet(int type, struct net_device *dev, unsigned int change, gfp_t flags, int *new_nsid, int new_ifindex);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (c0d0b0e0)
Location: net/core/rtnetlink.c:3548
Inline: False
Direct callers:
  - net/core/dev.c:dev_change_net_namespace
```
**Symbols:**

```
c0d0b0e0-c0d0b130: rtmsg_ifinfo_newnet (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void rtmsg_ifinfo_newnet(int type, struct net_device *dev, unsigned int change, gfp_t flags, int *new_nsid, int new_ifindex);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (c000000000cd77c0)
Location: net/core/rtnetlink.c:3548
Inline: False
Direct callers:
  - net/core/dev.c:dev_change_net_namespace
```
**Symbols:**

```
c000000000cd77c0-c000000000cd77f0: rtmsg_ifinfo_newnet (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void rtmsg_ifinfo_newnet(int type, struct net_device *dev, unsigned int change, gfp_t flags, int *new_nsid, int new_ifindex);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffe0007742f2)
Location: net/core/rtnetlink.c:3548
Inline: False
Direct callers:
  - net/core/dev.c:dev_change_net_namespace
```
**Symbols:**

```
ffffffe0007742f2-ffffffe000774352: rtmsg_ifinfo_newnet (STB_GLOBAL)
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
void rtmsg_ifinfo_newnet(int type, struct net_device *dev, unsigned int change, gfp_t flags, int *new_nsid, int new_ifindex);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff818f0c30)
Location: net/core/rtnetlink.c:3548
Inline: False
Direct callers:
  - net/core/dev.c:dev_change_net_namespace
```
**Symbols:**

```
ffffffff818f0c30-ffffffff818f0c55: rtmsg_ifinfo_newnet (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void rtmsg_ifinfo_newnet(int type, struct net_device *dev, unsigned int change, gfp_t flags, int *new_nsid, int new_ifindex);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff818aaa70)
Location: net/core/rtnetlink.c:3548
Inline: False
Direct callers:
  - net/core/dev.c:dev_change_net_namespace
```
**Symbols:**

```
ffffffff818aaa70-ffffffff818aaa95: rtmsg_ifinfo_newnet (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void rtmsg_ifinfo_newnet(int type, struct net_device *dev, unsigned int change, gfp_t flags, int *new_nsid, int new_ifindex);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81941c60)
Location: net/core/rtnetlink.c:3548
Inline: False
Direct callers:
  - net/core/dev.c:dev_change_net_namespace
```
**Symbols:**

```
ffffffff81941c60-ffffffff81941c85: rtmsg_ifinfo_newnet (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void rtmsg_ifinfo_newnet(int type, struct net_device *dev, unsigned int change, gfp_t flags, int *new_nsid, int new_ifindex);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81963560)
Location: net/core/rtnetlink.c:3548
Inline: False
Direct callers:
  - net/core/dev.c:dev_change_net_namespace
```
**Symbols:**

```
ffffffff81963560-ffffffff81963585: rtmsg_ifinfo_newnet (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int new_ifindex</code>
</li>
</ul>
</details>
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
