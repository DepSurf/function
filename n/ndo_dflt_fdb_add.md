# Function: <code>ndo_dflt_fdb_add</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ndo_dflt_fdb_add(struct ndmsg *ndm, struct nlattr **tb, struct net_device *dev, const unsigned char *addr, u16 vid, u16 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff8172a950)
Location: net/core/rtnetlink.c:2629
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_fdb_add
```
**Symbols:**

```
ffffffff8172a950-ffffffff8172a9e6: ndo_dflt_fdb_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ndo_dflt_fdb_add(struct ndmsg *ndm, struct nlattr **tb, struct net_device *dev, const unsigned char *addr, u16 vid, u16 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff817943d0)
Location: net/core/rtnetlink.c:2824
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_fdb_add
```
**Symbols:**

```
ffffffff817943d0-ffffffff81794466: ndo_dflt_fdb_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ndo_dflt_fdb_add(struct ndmsg *ndm, struct nlattr **tb, struct net_device *dev, const unsigned char *addr, u16 vid, u16 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff817c1c50)
Location: net/core/rtnetlink.c:2900
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_fdb_add
```
**Symbols:**

```
ffffffff817c1c50-ffffffff817c1ce6: ndo_dflt_fdb_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ndo_dflt_fdb_add(struct ndmsg *ndm, struct nlattr **tb, struct net_device *dev, const unsigned char *addr, u16 vid, u16 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff817e03e0)
Location: net/core/rtnetlink.c:2996
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_fdb_add
```
**Symbols:**

```
ffffffff817e03e0-ffffffff817e0476: ndo_dflt_fdb_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ndo_dflt_fdb_add(struct ndmsg *ndm, struct nlattr **tb, struct net_device *dev, const unsigned char *addr, u16 vid, u16 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff8185ac50)
Location: net/core/rtnetlink.c:3233
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_fdb_add
```
**Symbols:**

```
ffffffff8185ac50-ffffffff8185ace6: ndo_dflt_fdb_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int ndo_dflt_fdb_add(struct ndmsg *ndm, struct nlattr **tb, struct net_device *dev, const unsigned char *addr, u16 vid, u16 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/rtnetlink.c (0)
Location: net/core/rtnetlink.c:3391
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_fdb_add
```
**Symbols:**

```
ffffffff818ad527-ffffffff818ad559: ndo_dflt_fdb_add.cold.41 (STB_LOCAL)
ffffffff818a6520-ffffffff818a6592: ndo_dflt_fdb_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int ndo_dflt_fdb_add(struct ndmsg *ndm, struct nlattr **tb, struct net_device *dev, const unsigned char *addr, u16 vid, u16 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/rtnetlink.c (0)
Location: net/core/rtnetlink.c:3534
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_fdb_add
```
**Symbols:**

```
ffffffff818d1787-ffffffff818d17b9: ndo_dflt_fdb_add.cold.42 (STB_LOCAL)
ffffffff818c9d70-ffffffff818c9de2: ndo_dflt_fdb_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int ndo_dflt_fdb_add(struct ndmsg *ndm, struct nlattr **tb, struct net_device *dev, const unsigned char *addr, u16 vid, u16 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/rtnetlink.c (0)
Location: net/core/rtnetlink.c:3595
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_fdb_add
```
**Symbols:**

```
ffffffff8191e681-ffffffff8191e6b3: ndo_dflt_fdb_add.cold (STB_LOCAL)
ffffffff81916d60-ffffffff81916dd2: ndo_dflt_fdb_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int ndo_dflt_fdb_add(struct ndmsg *ndm, struct nlattr **tb, struct net_device *dev, const unsigned char *addr, u16 vid, u16 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/rtnetlink.c (0)
Location: net/core/rtnetlink.c:3626
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_fdb_add
```
**Symbols:**

```
ffffffff81950c85-ffffffff81950cb7: ndo_dflt_fdb_add.cold (STB_LOCAL)
ffffffff819493a0-ffffffff81949412: ndo_dflt_fdb_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int ndo_dflt_fdb_add(struct ndmsg *ndm, struct nlattr **tb, struct net_device *dev, const unsigned char *addr, u16 vid, u16 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/rtnetlink.c (0)
Location: net/core/rtnetlink.c:3829
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_fdb_add
```
**Symbols:**

```
ffffffff81a21b1d-ffffffff81a21b4f: ndo_dflt_fdb_add.cold (STB_LOCAL)
ffffffff81a19290-ffffffff81a192fd: ndo_dflt_fdb_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int ndo_dflt_fdb_add(struct ndmsg *ndm, struct nlattr **tb, struct net_device *dev, const unsigned char *addr, u16 vid, u16 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/rtnetlink.c (0)
Location: net/core/rtnetlink.c:3921
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_fdb_add
```
**Symbols:**

```
ffffffff81c31642-ffffffff81c31674: ndo_dflt_fdb_add.cold (STB_LOCAL)
ffffffff81a19480-ffffffff81a194ed: ndo_dflt_fdb_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int ndo_dflt_fdb_add(struct ndmsg *ndm, struct nlattr **tb, struct net_device *dev, const unsigned char *addr, u16 vid, u16 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/rtnetlink.c (0)
Location: net/core/rtnetlink.c:3919
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_fdb_add
```
**Symbols:**

```
ffffffff81c2394b-ffffffff81c2397d: ndo_dflt_fdb_add.cold (STB_LOCAL)
ffffffff81a00390-ffffffff81a003fa: ndo_dflt_fdb_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int ndo_dflt_fdb_add(struct ndmsg *ndm, struct nlattr **tb, struct net_device *dev, const unsigned char *addr, u16 vid, u16 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/rtnetlink.c (0)
Location: net/core/rtnetlink.c:3940
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_fdb_add
```
**Symbols:**

```
ffffffff81d36d58-ffffffff81d36d84: ndo_dflt_fdb_add.cold (STB_LOCAL)
ffffffff81ab24e0-ffffffff81ab254a: ndo_dflt_fdb_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int ndo_dflt_fdb_add(struct ndmsg *ndm, struct nlattr **tb, struct net_device *dev, const unsigned char *addr, u16 vid, u16 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/rtnetlink.c (0)
Location: net/core/rtnetlink.c:4031
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_fdb_add
```
**Symbols:**

```
ffffffff81f03674-ffffffff81f03698: ndo_dflt_fdb_add.cold (STB_LOCAL)
ffffffff81c2b530-ffffffff81c2b5ab: ndo_dflt_fdb_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ndo_dflt_fdb_add(struct ndmsg *ndm, struct nlattr **tb, struct net_device *dev, const unsigned char *addr, u16 vid, u16 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81dde0e0)
Location: net/core/rtnetlink.c:4077
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_fdb_add
```
**Symbols:**

```
ffffffff81dde0e0-ffffffff81dde194: ndo_dflt_fdb_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ndo_dflt_fdb_add(struct ndmsg *ndm, struct nlattr **tb, struct net_device *dev, const unsigned char *addr, u16 vid, u16 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81e4f020)
Location: net/core/rtnetlink.c:4166
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_fdb_add
```
**Symbols:**

```
ffffffff81e4f020-ffffffff81e4f0d4: ndo_dflt_fdb_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ndo_dflt_fdb_add(struct ndmsg *ndm, struct nlattr **tb, struct net_device *dev, const unsigned char *addr, u16 vid, u16 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81f0def0)
Location: net/core/rtnetlink.c:4206
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_fdb_add
```
**Symbols:**

```
ffffffff81f0def0-ffffffff81f0dfa4: ndo_dflt_fdb_add (STB_GLOBAL)
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
int ndo_dflt_fdb_add(struct ndmsg *ndm, struct nlattr **tb, struct net_device *dev, const unsigned char *addr, u16 vid, u16 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffff800010beae18)
Location: net/core/rtnetlink.c:3626
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_fdb_add
```
**Symbols:**

```
ffff800010beae18-ffff800010beaef0: ndo_dflt_fdb_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ndo_dflt_fdb_add(struct ndmsg *ndm, struct nlattr **tb, struct net_device *dev, const unsigned char *addr, u16 vid, u16 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (c0d03b94)
Location: net/core/rtnetlink.c:3626
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_fdb_add
```
**Symbols:**

```
c0d03b94-c0d03c54: ndo_dflt_fdb_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ndo_dflt_fdb_add(struct ndmsg *ndm, struct nlattr **tb, struct net_device *dev, const unsigned char *addr, u16 vid, u16 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (c000000000cce110)
Location: net/core/rtnetlink.c:3626
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_fdb_add
```
**Symbols:**

```
c000000000cce110-c000000000cce228: ndo_dflt_fdb_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ndo_dflt_fdb_add(struct ndmsg *ndm, struct nlattr **tb, struct net_device *dev, const unsigned char *addr, u16 vid, u16 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffe00076e86a)
Location: net/core/rtnetlink.c:3626
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_fdb_add
```
**Symbols:**

```
ffffffe00076e86a-ffffffe00076e938: ndo_dflt_fdb_add (STB_GLOBAL)
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
int ndo_dflt_fdb_add(struct ndmsg *ndm, struct nlattr **tb, struct net_device *dev, const unsigned char *addr, u16 vid, u16 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/rtnetlink.c (0)
Location: net/core/rtnetlink.c:3626
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_fdb_add
```
**Symbols:**

```
ffffffff818f0c55-ffffffff818f0c87: ndo_dflt_fdb_add.cold (STB_LOCAL)
ffffffff818e9370-ffffffff818e93e2: ndo_dflt_fdb_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int ndo_dflt_fdb_add(struct ndmsg *ndm, struct nlattr **tb, struct net_device *dev, const unsigned char *addr, u16 vid, u16 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/rtnetlink.c (0)
Location: net/core/rtnetlink.c:3626
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_fdb_add
```
**Symbols:**

```
ffffffff818aaa95-ffffffff818aaac7: ndo_dflt_fdb_add.cold (STB_LOCAL)
ffffffff818a31b0-ffffffff818a3222: ndo_dflt_fdb_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int ndo_dflt_fdb_add(struct ndmsg *ndm, struct nlattr **tb, struct net_device *dev, const unsigned char *addr, u16 vid, u16 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/rtnetlink.c (0)
Location: net/core/rtnetlink.c:3626
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_fdb_add
```
**Symbols:**

```
ffffffff81941c85-ffffffff81941cb7: ndo_dflt_fdb_add.cold (STB_LOCAL)
ffffffff8193a3a0-ffffffff8193a412: ndo_dflt_fdb_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int ndo_dflt_fdb_add(struct ndmsg *ndm, struct nlattr **tb, struct net_device *dev, const unsigned char *addr, u16 vid, u16 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/rtnetlink.c (0)
Location: net/core/rtnetlink.c:3626
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_fdb_add
```
**Symbols:**

```
ffffffff81963585-ffffffff819635b7: ndo_dflt_fdb_add.cold (STB_LOCAL)
ffffffff8195bbd0-ffffffff8195bc42: ndo_dflt_fdb_add (STB_GLOBAL)
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
