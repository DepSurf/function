# Function: <code>ip6mr_cache_report</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ip6mr_cache_report(struct mr6_table *mrt, struct sk_buff *pkt, mifi_t mifi, int assert);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffffffff817f84b0)
Location: net/ipv6/ip6mr.c:1129
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:reg_vif_xmit
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ip6_mr_forward
```
**Symbols:**

```
ffffffff817f84b0-ffffffff817f8799: ip6mr_cache_report (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ip6mr_cache_report(struct mr6_table *mrt, struct sk_buff *pkt, mifi_t mifi, int assert);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffffffff81867c90)
Location: net/ipv6/ip6mr.c:1131
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:reg_vif_xmit
```
**Symbols:**

```
ffffffff81867c90-ffffffff81867f7e: ip6mr_cache_report (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ip6mr_cache_report(struct mr6_table *mrt, struct sk_buff *pkt, mifi_t mifi, int assert);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffffffff8189aaf0)
Location: net/ipv6/ip6mr.c:1131
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:reg_vif_xmit
```
**Symbols:**

```
ffffffff8189aaf0-ffffffff8189adde: ip6mr_cache_report (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ip6mr_cache_report(struct mr6_table *mrt, struct sk_buff *pkt, mifi_t mifi, int assert);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffffffff818c1410)
Location: net/ipv6/ip6mr.c:1134
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:reg_vif_xmit
```
**Symbols:**

```
ffffffff818c1410-ffffffff818c1923: ip6mr_cache_report (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ip6mr_cache_report(struct mr6_table *mrt, struct sk_buff *pkt, mifi_t mifi, int assert);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffffffff81944760)
Location: net/ipv6/ip6mr.c:1134
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:reg_vif_xmit
```
**Symbols:**

```
ffffffff81944760-ffffffff81944cab: ip6mr_cache_report (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int ip6mr_cache_report(struct mr_table *mrt, struct sk_buff *pkt, mifi_t mifi, int assert);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/ip6mr.c (0)
Location: net/ipv6/ip6mr.c:1026
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:reg_vif_xmit
```
**Symbols:**

```
ffffffff8199d480-ffffffff8199d9ad: ip6mr_cache_report (STB_LOCAL)
ffffffff819a0c0e-ffffffff819a0c1f: ip6mr_cache_report.cold.55 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int ip6mr_cache_report(struct mr_table *mrt, struct sk_buff *pkt, mifi_t mifi, int assert);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/ip6mr.c (0)
Location: net/ipv6/ip6mr.c:1040
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6mr.c:ip6mr_forward2
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:reg_vif_xmit
```
**Symbols:**

```
ffffffff819d3fe0-ffffffff819d4507: ip6mr_cache_report (STB_LOCAL)
ffffffff819d7821-ffffffff819d7832: ip6mr_cache_report.cold.53 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int ip6mr_cache_report(struct mr_table *mrt, struct sk_buff *pkt, mifi_t mifi, int assert);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/ip6mr.c (0)
Location: net/ipv6/ip6mr.c:1035
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6mr.c:ip6mr_forward2
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:reg_vif_xmit
```
**Symbols:**

```
ffffffff81a42e90-ffffffff81a43387: ip6mr_cache_report (STB_LOCAL)
ffffffff81a468af-ffffffff81a468f7: ip6mr_cache_report.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int ip6mr_cache_report(struct mr_table *mrt, struct sk_buff *pkt, mifi_t mifi, int assert);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/ip6mr.c (0)
Location: net/ipv6/ip6mr.c:1035
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6mr.c:ip6mr_forward2
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:reg_vif_xmit
```
**Symbols:**

```
ffffffff81a799f0-ffffffff81a79ef5: ip6mr_cache_report (STB_LOCAL)
ffffffff81a7d484-ffffffff81a7d495: ip6mr_cache_report.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int ip6mr_cache_report(struct mr_table *mrt, struct sk_buff *pkt, mifi_t mifi, int assert);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/ip6mr.c (0)
Location: net/ipv6/ip6mr.c:1039
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:reg_vif_xmit
```
**Symbols:**

```
ffffffff81b746a0-ffffffff81b749b1: ip6mr_cache_report (STB_LOCAL)
ffffffff81b77e2e-ffffffff81b77e3f: ip6mr_cache_report.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int ip6mr_cache_report(struct mr_table *mrt, struct sk_buff *pkt, mifi_t mifi, int assert);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/ip6mr.c (0)
Location: net/ipv6/ip6mr.c:1039
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:reg_vif_xmit
```
**Symbols:**

```
ffffffff81b83410-ffffffff81b8372c: ip6mr_cache_report (STB_LOCAL)
ffffffff81c32fc7-ffffffff81c32fd8: ip6mr_cache_report.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int ip6mr_cache_report(struct mr_table *mrt, struct sk_buff *pkt, mifi_t mifi, int assert);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/ip6mr.c (0)
Location: net/ipv6/ip6mr.c:1039
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:reg_vif_xmit
```
**Symbols:**

```
ffffffff81b72080-ffffffff81b723a2: ip6mr_cache_report (STB_LOCAL)
ffffffff81c252ca-ffffffff81c252db: ip6mr_cache_report.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int ip6mr_cache_report(struct mr_table *mrt, struct sk_buff *pkt, mifi_t mifi, int assert);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/ip6mr.c (0)
Location: net/ipv6/ip6mr.c:1040
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:reg_vif_xmit
```
**Symbols:**

```
ffffffff81c3c530-ffffffff81c3c87c: ip6mr_cache_report (STB_LOCAL)
ffffffff81d412e6-ffffffff81d412f7: ip6mr_cache_report.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int ip6mr_cache_report(struct mr_table *mrt, struct sk_buff *pkt, mifi_t mifi, int assert);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/ip6mr.c (0)
Location: net/ipv6/ip6mr.c:1034
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:reg_vif_xmit
```
**Symbols:**

```
ffffffff81dda900-ffffffff81ddac76: ip6mr_cache_report (STB_LOCAL)
ffffffff81f0dc1c-ffffffff81f0dc2d: ip6mr_cache_report.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ip6mr_cache_report(const struct mr_table *mrt, struct sk_buff *pkt, mifi_t mifi, int assert);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffffffff81fac630)
Location: net/ipv6/ip6mr.c:1045
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:reg_vif_xmit
```
**Symbols:**

```
ffffffff81fac630-ffffffff81fac97e: ip6mr_cache_report (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ip6mr_cache_report(const struct mr_table *mrt, struct sk_buff *pkt, mifi_t mifi, int assert);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffffffff8200cdd0)
Location: net/ipv6/ip6mr.c:1045
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:reg_vif_xmit
```
**Symbols:**

```
ffffffff8200cdd0-ffffffff8200d137: ip6mr_cache_report (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ip6mr_cache_report(const struct mr_table *mrt, struct sk_buff *pkt, mifi_t mifi, int assert);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffffffff820dbda0)
Location: net/ipv6/ip6mr.c:1045
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:reg_vif_xmit
```
**Symbols:**

```
ffffffff820dbda0-ffffffff820dc107: ip6mr_cache_report (STB_LOCAL)
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
int ip6mr_cache_report(struct mr_table *mrt, struct sk_buff *pkt, mifi_t mifi, int assert);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffff800010d43d20)
Location: net/ipv6/ip6mr.c:1035
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6mr.c:ip6mr_forward2
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:reg_vif_xmit
```
**Symbols:**

```
ffff800010d43d20-ffff800010d44180: ip6mr_cache_report (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ip6mr_cache_report(struct mr_table *mrt, struct sk_buff *pkt, mifi_t mifi, int assert);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (c0e45a90)
Location: net/ipv6/ip6mr.c:1035
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6mr.c:ip6mr_forward2
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:reg_vif_xmit
```
**Symbols:**

```
c0e45a90-c0e45f68: ip6mr_cache_report (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ip6mr_cache_report(struct mr_table *mrt, struct sk_buff *pkt, mifi_t mifi, int assert);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (c000000000e78830)
Location: net/ipv6/ip6mr.c:1035
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6mr.c:ip6mr_forward2
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:reg_vif_xmit
```
**Symbols:**

```
c000000000e78830-c000000000e78db8: ip6mr_cache_report (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ip6mr_cache_report(struct mr_table *mrt, struct sk_buff *pkt, mifi_t mifi, int assert);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffffffe00087e8c6)
Location: net/ipv6/ip6mr.c:1035
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6mr.c:ip6mr_forward2
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:reg_vif_xmit
```
**Symbols:**

```
ffffffe00087e8c6-ffffffe00087ec90: ip6mr_cache_report (STB_LOCAL)
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
int ip6mr_cache_report(struct mr_table *mrt, struct sk_buff *pkt, mifi_t mifi, int assert);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/ip6mr.c (0)
Location: net/ipv6/ip6mr.c:1035
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6mr.c:ip6mr_forward2
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:reg_vif_xmit
```
**Symbols:**

```
ffffffff81a19080-ffffffff81a19585: ip6mr_cache_report (STB_LOCAL)
ffffffff81a1cb14-ffffffff81a1cb25: ip6mr_cache_report.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int ip6mr_cache_report(struct mr_table *mrt, struct sk_buff *pkt, mifi_t mifi, int assert);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/ip6mr.c (0)
Location: net/ipv6/ip6mr.c:1035
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6mr.c:ip6mr_forward2
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:reg_vif_xmit
```
**Symbols:**

```
ffffffff819d5e40-ffffffff819d6345: ip6mr_cache_report (STB_LOCAL)
ffffffff819d98d4-ffffffff819d98e5: ip6mr_cache_report.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int ip6mr_cache_report(struct mr_table *mrt, struct sk_buff *pkt, mifi_t mifi, int assert);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/ip6mr.c (0)
Location: net/ipv6/ip6mr.c:1035
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6mr.c:ip6mr_forward2
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:reg_vif_xmit
```
**Symbols:**

```
ffffffff81a83b00-ffffffff81a84005: ip6mr_cache_report (STB_LOCAL)
ffffffff81a87594-ffffffff81a875a5: ip6mr_cache_report.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int ip6mr_cache_report(struct mr_table *mrt, struct sk_buff *pkt, mifi_t mifi, int assert);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/ip6mr.c (0)
Location: net/ipv6/ip6mr.c:1035
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6_mr_forward
  - net/ipv6/ip6mr.c:ip6mr_forward2
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:reg_vif_xmit
```
**Symbols:**

```
ffffffff81a90420-ffffffff81a90935: ip6mr_cache_report (STB_LOCAL)
ffffffff81a9416c-ffffffff81a9417d: ip6mr_cache_report.cold (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct mr6_table *mrt</code> ➡️ <code>struct mr_table *mrt</code>
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
