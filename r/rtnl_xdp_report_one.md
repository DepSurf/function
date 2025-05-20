# Function: <code>rtnl_xdp_report_one</code>

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
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int rtnl_xdp_report_one(struct sk_buff *skb, struct net_device *dev, u32 *prog_id, u8 *mode, u8 tgt_mode, u32 attr, u32 (*get_prog_id)(struct net_device *));
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff818ca6b0)
Location: net/core/rtnetlink.c:1392
Inline: True
Direct callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
**Symbols:**

```
ffffffff818ca6b0-ffffffff818ca74e: rtnl_xdp_report_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int rtnl_xdp_report_one(struct sk_buff *skb, struct net_device *dev, u32 *prog_id, u8 *mode, u8 tgt_mode, u32 attr, u32 (*get_prog_id)(struct net_device *));
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff819176e0)
Location: net/core/rtnetlink.c:1390
Inline: True
Direct callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
**Symbols:**

```
ffffffff819176e0-ffffffff81917783: rtnl_xdp_report_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int rtnl_xdp_report_one(struct sk_buff *skb, struct net_device *dev, u32 *prog_id, u8 *mode, u8 tgt_mode, u32 attr, u32 (*get_prog_id)(struct net_device *));
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81949d20)
Location: net/core/rtnetlink.c:1390
Inline: True
Direct callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
**Symbols:**

```
ffffffff81949d20-ffffffff81949dc3: rtnl_xdp_report_one (STB_LOCAL)
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
In net/core/rtnetlink.c (ffffffff81a1c107)
Location: net/core/rtnetlink.c:1428
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_xdp_fill
  - net/core/rtnetlink.c:rtnl_xdp_fill
  - net/core/rtnetlink.c:rtnl_xdp_fill
  - net/core/rtnetlink.c:rtnl_xdp_fill
  - net/core/rtnetlink.c:rtnl_xdp_fill
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
In net/core/rtnetlink.c (ffffffff81a1c157)
Location: net/core/rtnetlink.c:1439
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_xdp_fill
  - net/core/rtnetlink.c:rtnl_xdp_fill
  - net/core/rtnetlink.c:rtnl_xdp_fill
  - net/core/rtnetlink.c:rtnl_xdp_fill
  - net/core/rtnetlink.c:rtnl_xdp_fill
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81a03277)
Location: net/core/rtnetlink.c:1441
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_xdp_fill
  - net/core/rtnetlink.c:rtnl_xdp_fill
  - net/core/rtnetlink.c:rtnl_xdp_fill
  - net/core/rtnetlink.c:rtnl_xdp_fill
  - net/core/rtnetlink.c:rtnl_xdp_fill
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
In net/core/rtnetlink.c (ffffffff81ab4417)
Location: net/core/rtnetlink.c:1430
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_xdp_fill
  - net/core/rtnetlink.c:rtnl_xdp_fill
  - net/core/rtnetlink.c:rtnl_xdp_fill
  - net/core/rtnetlink.c:rtnl_xdp_fill
  - net/core/rtnetlink.c:rtnl_xdp_fill
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
In net/core/rtnetlink.c (ffffffff81c2df68)
Location: net/core/rtnetlink.c:1470
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_xdp_fill
  - net/core/rtnetlink.c:rtnl_xdp_fill
  - net/core/rtnetlink.c:rtnl_xdp_fill
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
In net/core/rtnetlink.c (ffffffff81de1178)
Location: net/core/rtnetlink.c:1481
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_xdp_fill
  - net/core/rtnetlink.c:rtnl_xdp_fill
  - net/core/rtnetlink.c:rtnl_xdp_fill
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
In net/core/rtnetlink.c (ffffffff81e52868)
Location: net/core/rtnetlink.c:1492
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_xdp_fill
  - net/core/rtnetlink.c:rtnl_xdp_fill
  - net/core/rtnetlink.c:rtnl_xdp_fill
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
In net/core/rtnetlink.c (ffffffff81f11948)
Location: net/core/rtnetlink.c:1499
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_xdp_fill
  - net/core/rtnetlink.c:rtnl_xdp_fill
  - net/core/rtnetlink.c:rtnl_xdp_fill
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int rtnl_xdp_report_one(struct sk_buff *skb, struct net_device *dev, u32 *prog_id, u8 *mode, u8 tgt_mode, u32 attr, u32 (*get_prog_id)(struct net_device *));
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffff800010beb8e0)
Location: net/core/rtnetlink.c:1390
Inline: True
Direct callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
**Symbols:**

```
ffff800010beb8e0-ffff800010beb9a8: rtnl_xdp_report_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int rtnl_xdp_report_one(struct sk_buff *skb, struct net_device *dev, u32 *prog_id, u8 *mode, u8 tgt_mode, u32 attr, u32 (*get_prog_id)(struct net_device *));
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (c0d04458)
Location: net/core/rtnetlink.c:1390
Inline: True
Direct callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
**Symbols:**

```
c0d04458-c0d0450c: rtnl_xdp_report_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int rtnl_xdp_report_one(struct sk_buff *skb, struct net_device *dev, u32 *prog_id, u8 *mode, u8 tgt_mode, u32 attr, u32 (*get_prog_id)(struct net_device *));
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (c000000000cceb80)
Location: net/core/rtnetlink.c:1390
Inline: True
Direct callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
**Symbols:**

```
c000000000cceb80-c000000000ccec80: rtnl_xdp_report_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int rtnl_xdp_report_one(struct sk_buff *skb, struct net_device *dev, u32 *prog_id, u8 *mode, u8 tgt_mode, u32 attr, u32 (*get_prog_id)(struct net_device *));
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffe00076f00e)
Location: net/core/rtnetlink.c:1390
Inline: True
Direct callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
**Symbols:**

```
ffffffe00076f00e-ffffffe00076f090: rtnl_xdp_report_one (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int rtnl_xdp_report_one(struct sk_buff *skb, struct net_device *dev, u32 *prog_id, u8 *mode, u8 tgt_mode, u32 attr, u32 (*get_prog_id)(struct net_device *));
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff818e9cf0)
Location: net/core/rtnetlink.c:1390
Inline: True
Direct callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
**Symbols:**

```
ffffffff818e9cf0-ffffffff818e9d93: rtnl_xdp_report_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int rtnl_xdp_report_one(struct sk_buff *skb, struct net_device *dev, u32 *prog_id, u8 *mode, u8 tgt_mode, u32 attr, u32 (*get_prog_id)(struct net_device *));
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff818a3b30)
Location: net/core/rtnetlink.c:1390
Inline: True
Direct callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
**Symbols:**

```
ffffffff818a3b30-ffffffff818a3bd3: rtnl_xdp_report_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int rtnl_xdp_report_one(struct sk_buff *skb, struct net_device *dev, u32 *prog_id, u8 *mode, u8 tgt_mode, u32 attr, u32 (*get_prog_id)(struct net_device *));
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff8193ad20)
Location: net/core/rtnetlink.c:1390
Inline: True
Direct callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
**Symbols:**

```
ffffffff8193ad20-ffffffff8193adc3: rtnl_xdp_report_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int rtnl_xdp_report_one(struct sk_buff *skb, struct net_device *dev, u32 *prog_id, u8 *mode, u8 tgt_mode, u32 attr, u32 (*get_prog_id)(struct net_device *));
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff8195c560)
Location: net/core/rtnetlink.c:1390
Inline: True
Direct callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
**Symbols:**

```
ffffffff8195c560-ffffffff8195c603: rtnl_xdp_report_one (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
