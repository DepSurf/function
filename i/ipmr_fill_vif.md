# Function: <code>ipmr_fill_vif</code>

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
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff8186ab7f)
Location: net/ipv4/ipmr.c:2673
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff818eb307)
Location: net/ipv4/ipmr.c:2838
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81941abf)
Location: net/ipv4/ipmr.c:2667
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff8197153f)
Location: net/ipv4/ipmr.c:2708
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff819dacc3)
Location: net/ipv4/ipmr.c:2771
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81a11b78)
Location: net/ipv4/ipmr.c:2772
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool ipmr_fill_vif(struct mr_table *mrt, u32 vifid, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81b02ef0)
Location: net/ipv4/ipmr.c:2740
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
```
**Symbols:**

```
ffffffff81b02ef0-ffffffff81b03168: ipmr_fill_vif (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool ipmr_fill_vif(struct mr_table *mrt, u32 vifid, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81b10040)
Location: net/ipv4/ipmr.c:2749
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
```
**Symbols:**

```
ffffffff81b10040-ffffffff81b102b8: ipmr_fill_vif (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool ipmr_fill_vif(struct mr_table *mrt, u32 vifid, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81afdc50)
Location: net/ipv4/ipmr.c:2749
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
```
**Symbols:**

```
ffffffff81afdc50-ffffffff81afdec6: ipmr_fill_vif (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool ipmr_fill_vif(struct mr_table *mrt, u32 vifid, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81bbee90)
Location: net/ipv4/ipmr.c:2751
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
```
**Symbols:**

```
ffffffff81bbee90-ffffffff81bbf154: ipmr_fill_vif (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool ipmr_fill_vif(struct mr_table *mrt, u32 vifid, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81d53c10)
Location: net/ipv4/ipmr.c:2745
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
```
**Symbols:**

```
ffffffff81d53c10-ffffffff81d53ec5: ipmr_fill_vif (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool ipmr_fill_vif(struct mr_table *mrt, u32 vifid, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81f1ddf0)
Location: net/ipv4/ipmr.c:2752
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
```
**Symbols:**

```
ffffffff81f1ddf0-ffffffff81f1e08b: ipmr_fill_vif (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool ipmr_fill_vif(struct mr_table *mrt, u32 vifid, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81f7d8e0)
Location: net/ipv4/ipmr.c:2767
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
```
**Symbols:**

```
ffffffff81f7d8e0-ffffffff81f7db7b: ipmr_fill_vif (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool ipmr_fill_vif(struct mr_table *mrt, u32 vifid, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff82044120)
Location: net/ipv4/ipmr.c:2765
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
```
**Symbols:**

```
ffffffff82044120-ffffffff820443bb: ipmr_fill_vif (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffff800010cca1f0)
Location: net/ipv4/ipmr.c:2772
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (c0dd61c8)
Location: net/ipv4/ipmr.c:2772
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (c000000000de96f8)
Location: net/ipv4/ipmr.c:2772
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffe00081f52c)
Location: net/ipv4/ipmr.c:2772
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff819b14cb)
Location: net/ipv4/ipmr.c:2772
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff8196dafb)
Location: net/ipv4/ipmr.c:2772
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81a1bd6b)
Location: net/ipv4/ipmr.c:2772
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81a26c88)
Location: net/ipv4/ipmr.c:2772
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
