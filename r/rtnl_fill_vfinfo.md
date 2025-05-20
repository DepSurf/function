# Function: <code>rtnl_fill_vfinfo</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int rtnl_fill_vfinfo(struct sk_buff *skb, struct net_device *dev, int vfs_num, struct nlattr *vfinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff8172dba0)
Location: net/core/rtnetlink.c:1074
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
**Symbols:**

```
ffffffff8172dba0-ffffffff8172e043: rtnl_fill_vfinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int rtnl_fill_vfinfo(struct sk_buff *skb, struct net_device *dev, int vfs_num, struct nlattr *vfinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81797450)
Location: net/core/rtnetlink.c:1106
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
**Symbols:**

```
ffffffff81797450-ffffffff8179791b: rtnl_fill_vfinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int rtnl_fill_vfinfo(struct sk_buff *skb, struct net_device *dev, int vfs_num, struct nlattr *vfinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff817c5080)
Location: net/core/rtnetlink.c:1115
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
**Symbols:**

```
ffffffff817c5080-ffffffff817c5693: rtnl_fill_vfinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int rtnl_fill_vfinfo(struct sk_buff *skb, struct net_device *dev, int vfs_num, struct nlattr *vfinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff817e3ac0)
Location: net/core/rtnetlink.c:1114
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
**Symbols:**

```
ffffffff817e3ac0-ffffffff817e404b: rtnl_fill_vfinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int rtnl_fill_vfinfo(struct sk_buff *skb, struct net_device *dev, int vfs_num, struct nlattr *vfinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff8185ea00)
Location: net/core/rtnetlink.c:1089
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_fill_vf
```
**Symbols:**

```
ffffffff8185ea00-ffffffff8185ef94: rtnl_fill_vfinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int rtnl_fill_vfinfo(struct sk_buff *skb, struct net_device *dev, int vfs_num, struct nlattr *vfinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff818aab00)
Location: net/core/rtnetlink.c:1181
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_fill_vf
```
**Symbols:**

```
ffffffff818aab00-ffffffff818ab0fe: rtnl_fill_vfinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int rtnl_fill_vfinfo(struct sk_buff *skb, struct net_device *dev, int vfs_num, struct nlattr *vfinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff818cda70)
Location: net/core/rtnetlink.c:1194
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_fill_vf
```
**Symbols:**

```
ffffffff818cda70-ffffffff818ce06e: rtnl_fill_vfinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int rtnl_fill_vfinfo(struct sk_buff *skb, struct net_device *dev, int vfs_num, struct nlattr *vfinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/rtnetlink.c (0)
Location: net/core/rtnetlink.c:1189
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_fill_vf
```
**Symbols:**

```
ffffffff8191a760-ffffffff8191ae33: rtnl_fill_vfinfo (STB_LOCAL)
ffffffff8191e7be-ffffffff8191e832: rtnl_fill_vfinfo.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int rtnl_fill_vfinfo(struct sk_buff *skb, struct net_device *dev, int vfs_num, struct nlattr *vfinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/rtnetlink.c (0)
Location: net/core/rtnetlink.c:1189
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_fill_vf
```
**Symbols:**

```
ffffffff8194cd80-ffffffff8194d467: rtnl_fill_vfinfo (STB_LOCAL)
ffffffff81950d0a-ffffffff81950d16: rtnl_fill_vfinfo.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int rtnl_fill_vfinfo(struct sk_buff *skb, struct net_device *dev, int vfs_num, struct nlattr *vfinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/rtnetlink.c (0)
Location: net/core/rtnetlink.c:1211
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_fill_vf
```
**Symbols:**

```
ffffffff81a1e9a0-ffffffff81a1f137: rtnl_fill_vfinfo (STB_LOCAL)
ffffffff81a21ba2-ffffffff81a21bae: rtnl_fill_vfinfo.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int rtnl_fill_vfinfo(struct sk_buff *skb, struct net_device *dev, int vfs_num, struct nlattr *vfinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/rtnetlink.c (0)
Location: net/core/rtnetlink.c:1223
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_fill_vf
```
**Symbols:**

```
ffffffff81a1fcc0-ffffffff81a20457: rtnl_fill_vfinfo (STB_LOCAL)
ffffffff81c316df-ffffffff81c316eb: rtnl_fill_vfinfo.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int rtnl_fill_vfinfo(struct sk_buff *skb, struct net_device *dev, int vfs_num, struct nlattr *vfinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/rtnetlink.c (0)
Location: net/core/rtnetlink.c:1225
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_fill_vf
```
**Symbols:**

```
ffffffff81a06d90-ffffffff81a07528: rtnl_fill_vfinfo (STB_LOCAL)
ffffffff81c239e8-ffffffff81c239f4: rtnl_fill_vfinfo.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int rtnl_fill_vfinfo(struct sk_buff *skb, struct net_device *dev, int vfs_num, struct nlattr *vfinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/rtnetlink.c (0)
Location: net/core/rtnetlink.c:1214
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_fill_vf
```
**Symbols:**

```
ffffffff81ab91f0-ffffffff81ab9988: rtnl_fill_vfinfo (STB_LOCAL)
ffffffff81d36e96-ffffffff81d36ea2: rtnl_fill_vfinfo.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int rtnl_fill_vfinfo(struct sk_buff *skb, struct net_device *dev, int vfs_num, struct nlattr *vfinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/rtnetlink.c (0)
Location: net/core/rtnetlink.c:1254
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_fill_vf
```
**Symbols:**

```
ffffffff81c32470-ffffffff81c32d31: rtnl_fill_vfinfo (STB_LOCAL)
ffffffff81f03774-ffffffff81f03780: rtnl_fill_vfinfo.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int rtnl_fill_vfinfo(struct sk_buff *skb, struct net_device *dev, int vfs_num, struct nlattr *vfinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81de5870)
Location: net/core/rtnetlink.c:1265
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_fill_vf
```
**Symbols:**

```
ffffffff81de5870-ffffffff81de613d: rtnl_fill_vfinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int rtnl_fill_vfinfo(struct sk_buff *skb, struct net_device *dev, int vfs_num, struct nlattr *vfinfo, u32 ext_filter_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81e58450)
Location: net/core/rtnetlink.c:1273
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_fill_vf
```
**Symbols:**

```
ffffffff81e58450-ffffffff81e58d23: rtnl_fill_vfinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int rtnl_fill_vfinfo(struct sk_buff *skb, struct net_device *dev, int vfs_num, u32 ext_filter_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81f177a0)
Location: net/core/rtnetlink.c:1281
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_fill_vf
```
**Symbols:**

```
ffffffff81f177a0-ffffffff81f18031: rtnl_fill_vfinfo (STB_LOCAL)
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
int rtnl_fill_vfinfo(struct sk_buff *skb, struct net_device *dev, int vfs_num, struct nlattr *vfinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffff800010beef30)
Location: net/core/rtnetlink.c:1189
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_fill_vf
```
**Symbols:**

```
ffff800010beef30-ffff800010bef47c: rtnl_fill_vfinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int rtnl_fill_vfinfo(struct sk_buff *skb, struct net_device *dev, int vfs_num, struct nlattr *vfinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (c0d074f4)
Location: net/core/rtnetlink.c:1189
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_fill_vf
```
**Symbols:**

```
c0d074f4-c0d07a94: rtnl_fill_vfinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int rtnl_fill_vfinfo(struct sk_buff *skb, struct net_device *dev, int vfs_num, struct nlattr *vfinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (c000000000cd2d50)
Location: net/core/rtnetlink.c:1189
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_fill_vf
```
**Symbols:**

```
c000000000cd2d50-c000000000cd3410: rtnl_fill_vfinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int rtnl_fill_vfinfo(struct sk_buff *skb, struct net_device *dev, int vfs_num, struct nlattr *vfinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffe0007714d8)
Location: net/core/rtnetlink.c:1189
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_fill_vf
```
**Symbols:**

```
ffffffe0007714d8-ffffffe000771946: rtnl_fill_vfinfo (STB_LOCAL)
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
int rtnl_fill_vfinfo(struct sk_buff *skb, struct net_device *dev, int vfs_num, struct nlattr *vfinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/rtnetlink.c (0)
Location: net/core/rtnetlink.c:1189
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_fill_vf
```
**Symbols:**

```
ffffffff818ecd50-ffffffff818ed437: rtnl_fill_vfinfo (STB_LOCAL)
ffffffff818f0cda-ffffffff818f0ce6: rtnl_fill_vfinfo.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int rtnl_fill_vfinfo(struct sk_buff *skb, struct net_device *dev, int vfs_num, struct nlattr *vfinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/rtnetlink.c (0)
Location: net/core/rtnetlink.c:1189
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_fill_vf
```
**Symbols:**

```
ffffffff818a6b90-ffffffff818a7277: rtnl_fill_vfinfo (STB_LOCAL)
ffffffff818aab1a-ffffffff818aab26: rtnl_fill_vfinfo.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int rtnl_fill_vfinfo(struct sk_buff *skb, struct net_device *dev, int vfs_num, struct nlattr *vfinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/rtnetlink.c (0)
Location: net/core/rtnetlink.c:1189
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_fill_vf
```
**Symbols:**

```
ffffffff8193dd80-ffffffff8193e467: rtnl_fill_vfinfo (STB_LOCAL)
ffffffff81941d0a-ffffffff81941d16: rtnl_fill_vfinfo.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int rtnl_fill_vfinfo(struct sk_buff *skb, struct net_device *dev, int vfs_num, struct nlattr *vfinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/rtnetlink.c (0)
Location: net/core/rtnetlink.c:1189
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_fill_vf
```
**Symbols:**

```
ffffffff8195f610-ffffffff8195fcf7: rtnl_fill_vfinfo (STB_LOCAL)
ffffffff8196360a-ffffffff81963616: rtnl_fill_vfinfo.cold (STB_LOCAL)
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>u32 ext_filter_mask</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct nlattr *vfinfo</code>
</li>
<li>
<b>Param reordered. </b>
<code>skb, dev, vfs_num, vfinfo, ext_filter_mask</code> ➡️ <code>skb, dev, vfs_num, ext_filter_mask</code>
</li>
</ul>
</details>
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
