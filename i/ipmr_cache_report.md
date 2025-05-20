# Function: <code>ipmr_cache_report</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ipmr_cache_report(struct mr_table *mrt, struct sk_buff *pkt, vifi_t vifi, int assert);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff817a72d0)
Location: net/ipv4/ipmr.c:943
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:reg_vif_xmit
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:ip_mr_forward
```
**Symbols:**

```
ffffffff817a72d0-ffffffff817a75d3: ipmr_cache_report (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ipmr_cache_report(struct mr_table *mrt, struct sk_buff *pkt, vifi_t vifi, int assert);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81814fc0)
Location: net/ipv4/ipmr.c:949
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:reg_vif_xmit
```
**Symbols:**

```
ffffffff81814fc0-ffffffff818152ac: ipmr_cache_report (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ipmr_cache_report(struct mr_table *mrt, struct sk_buff *pkt, vifi_t vifi, int assert);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81846780)
Location: net/ipv4/ipmr.c:954
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:reg_vif_xmit
```
**Symbols:**

```
ffffffff81846780-ffffffff81846a6c: ipmr_cache_report (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ipmr_cache_report(struct mr_table *mrt, struct sk_buff *pkt, vifi_t vifi, int assert);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff818694a0)
Location: net/ipv4/ipmr.c:1003
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:reg_vif_xmit
```
**Symbols:**

```
ffffffff818694a0-ffffffff818699a7: ipmr_cache_report (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ipmr_cache_report(struct mr_table *mrt, struct sk_buff *pkt, vifi_t vifi, int assert);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff818e9af0)
Location: net/ipv4/ipmr.c:1129
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:reg_vif_xmit
```
**Symbols:**

```
ffffffff818e9af0-ffffffff818ea038: ipmr_cache_report (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int ipmr_cache_report(struct mr_table *mrt, struct sk_buff *pkt, vifi_t vifi, int assert);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/ipmr.c (0)
Location: net/ipv4/ipmr.c:1044
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:reg_vif_xmit
```
**Symbols:**

```
ffffffff819401a0-ffffffff819406d5: ipmr_cache_report (STB_LOCAL)
ffffffff81944079-ffffffff8194408a: ipmr_cache_report.cold.68 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int ipmr_cache_report(struct mr_table *mrt, struct sk_buff *pkt, vifi_t vifi, int assert);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/ipmr.c (0)
Location: net/ipv4/ipmr.c:1047
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:reg_vif_xmit
```
**Symbols:**

```
ffffffff81970020-ffffffff8197055f: ipmr_cache_report (STB_LOCAL)
ffffffff819741c9-ffffffff819741da: ipmr_cache_report.cold.69 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int ipmr_cache_report(struct mr_table *mrt, struct sk_buff *pkt, vifi_t vifi, int assert);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/ipmr.c (0)
Location: net/ipv4/ipmr.c:1039
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:reg_vif_xmit
```
**Symbols:**

```
ffffffff819d98e0-ffffffff819d9deb: ipmr_cache_report (STB_LOCAL)
ffffffff819ddc78-ffffffff819ddcc6: ipmr_cache_report.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int ipmr_cache_report(struct mr_table *mrt, struct sk_buff *pkt, vifi_t vifi, int assert);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/ipmr.c (0)
Location: net/ipv4/ipmr.c:1039
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:reg_vif_xmit
```
**Symbols:**

```
ffffffff81a10740-ffffffff81a10c51: ipmr_cache_report (STB_LOCAL)
ffffffff81a14db5-ffffffff81a14dc6: ipmr_cache_report.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int ipmr_cache_report(struct mr_table *mrt, struct sk_buff *pkt, vifi_t vifi, int assert);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/ipmr.c (0)
Location: net/ipv4/ipmr.c:1007
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:reg_vif_xmit
```
**Symbols:**

```
ffffffff81b02180-ffffffff81b0249d: ipmr_cache_report (STB_LOCAL)
ffffffff81b05d37-ffffffff81b05d48: ipmr_cache_report.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int ipmr_cache_report(struct mr_table *mrt, struct sk_buff *pkt, vifi_t vifi, int assert);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/ipmr.c (0)
Location: net/ipv4/ipmr.c:1010
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:reg_vif_xmit
```
**Symbols:**

```
ffffffff81b10520-ffffffff81b1085c: ipmr_cache_report (STB_LOCAL)
ffffffff81c32a35-ffffffff81c32a46: ipmr_cache_report.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int ipmr_cache_report(struct mr_table *mrt, struct sk_buff *pkt, vifi_t vifi, int assert);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/ipmr.c (0)
Location: net/ipv4/ipmr.c:1010
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:reg_vif_xmit
```
**Symbols:**

```
ffffffff81afe130-ffffffff81afe46e: ipmr_cache_report (STB_LOCAL)
ffffffff81c24d2e-ffffffff81c24d3f: ipmr_cache_report.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int ipmr_cache_report(struct mr_table *mrt, struct sk_buff *pkt, vifi_t vifi, int assert);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/ipmr.c (0)
Location: net/ipv4/ipmr.c:1012
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:reg_vif_xmit
```
**Symbols:**

```
ffffffff81bbf3c0-ffffffff81bbf728: ipmr_cache_report (STB_LOCAL)
ffffffff81d3ea25-ffffffff81d3ea36: ipmr_cache_report.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int ipmr_cache_report(struct mr_table *mrt, struct sk_buff *pkt, vifi_t vifi, int assert);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/ipmr.c (0)
Location: net/ipv4/ipmr.c:1006
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:reg_vif_xmit
```
**Symbols:**

```
ffffffff81d54150-ffffffff81d544c9: ipmr_cache_report (STB_LOCAL)
ffffffff81f0b350-ffffffff81f0b361: ipmr_cache_report.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ipmr_cache_report(const struct mr_table *mrt, struct sk_buff *pkt, vifi_t vifi, int assert);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81f1e330)
Location: net/ipv4/ipmr.c:1018
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:reg_vif_xmit
```
**Symbols:**

```
ffffffff81f1e330-ffffffff81f1e6a2: ipmr_cache_report (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ipmr_cache_report(const struct mr_table *mrt, struct sk_buff *pkt, vifi_t vifi, int assert);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81f7de20)
Location: net/ipv4/ipmr.c:1018
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:reg_vif_xmit
```
**Symbols:**

```
ffffffff81f7de20-ffffffff81f7e1a1: ipmr_cache_report (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ipmr_cache_report(const struct mr_table *mrt, struct sk_buff *pkt, vifi_t vifi, int assert);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff82044660)
Location: net/ipv4/ipmr.c:1018
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:reg_vif_xmit
```
**Symbols:**

```
ffffffff82044660-ffffffff820449b3: ipmr_cache_report (STB_LOCAL)
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
int ipmr_cache_report(struct mr_table *mrt, struct sk_buff *pkt, vifi_t vifi, int assert);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffff800010ccb3c0)
Location: net/ipv4/ipmr.c:1039
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:reg_vif_xmit
```
**Symbols:**

```
ffff800010ccb3c0-ffff800010ccb820: ipmr_cache_report (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ipmr_cache_report(struct mr_table *mrt, struct sk_buff *pkt, vifi_t vifi, int assert);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (c0dd58b0)
Location: net/ipv4/ipmr.c:1039
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:reg_vif_xmit
```
**Symbols:**

```
c0dd58b0-c0dd5d60: ipmr_cache_report (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ipmr_cache_report(struct mr_table *mrt, struct sk_buff *pkt, vifi_t vifi, int assert);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (c000000000de8020)
Location: net/ipv4/ipmr.c:1039
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:reg_vif_xmit
```
**Symbols:**

```
c000000000de8020-c000000000de8584: ipmr_cache_report (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ipmr_cache_report(struct mr_table *mrt, struct sk_buff *pkt, vifi_t vifi, int assert);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffe00081e70a)
Location: net/ipv4/ipmr.c:1039
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:reg_vif_xmit
```
**Symbols:**

```
ffffffe00081e70a-ffffffe00081eabe: ipmr_cache_report (STB_LOCAL)
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
int ipmr_cache_report(struct mr_table *mrt, struct sk_buff *pkt, vifi_t vifi, int assert);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/ipmr.c (0)
Location: net/ipv4/ipmr.c:1039
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:reg_vif_xmit
```
**Symbols:**

```
ffffffff819b0150-ffffffff819b0661: ipmr_cache_report (STB_LOCAL)
ffffffff819b4448-ffffffff819b4459: ipmr_cache_report.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int ipmr_cache_report(struct mr_table *mrt, struct sk_buff *pkt, vifi_t vifi, int assert);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/ipmr.c (0)
Location: net/ipv4/ipmr.c:1039
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:reg_vif_xmit
```
**Symbols:**

```
ffffffff8196c780-ffffffff8196cc91: ipmr_cache_report (STB_LOCAL)
ffffffff81970a78-ffffffff81970a89: ipmr_cache_report.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int ipmr_cache_report(struct mr_table *mrt, struct sk_buff *pkt, vifi_t vifi, int assert);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/ipmr.c (0)
Location: net/ipv4/ipmr.c:1039
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:reg_vif_xmit
```
**Symbols:**

```
ffffffff81a1a9f0-ffffffff81a1af01: ipmr_cache_report (STB_LOCAL)
ffffffff81a1ece8-ffffffff81a1ecf9: ipmr_cache_report.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int ipmr_cache_report(struct mr_table *mrt, struct sk_buff *pkt, vifi_t vifi, int assert);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/ipmr.c (0)
Location: net/ipv4/ipmr.c:1039
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ip_mr_forward
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:reg_vif_xmit
```
**Symbols:**

```
ffffffff81a25850-ffffffff81a25d71: ipmr_cache_report (STB_LOCAL)
ffffffff81a2a1aa-ffffffff81a2a1bb: ipmr_cache_report.cold (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct mr_table *mrt</code> ➡️ <code>const struct mr_table *mrt</code>
</li>
</ul>
</details>
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
