# Function: <code>__node_reclaim</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff811bbfd0)
Location: mm/vmscan.c:3710
Inline: True
Inline callers:
  - mm/vmscan.c:node_reclaim
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
In mm/vmscan.c (ffffffff811cc6a0)
Location: mm/vmscan.c:3721
Inline: True
Inline callers:
  - mm/vmscan.c:node_reclaim
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff811d52c7)
Location: mm/vmscan.c:3824
Inline: True
Inline callers:
  - mm/vmscan.c:node_reclaim
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
In mm/vmscan.c (ffffffff811ea7f7)
Location: mm/vmscan.c:3847
Inline: True
Inline callers:
  - mm/vmscan.c:node_reclaim
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __node_reclaim(struct pglist_data *pgdat, gfp_t gfp_mask, unsigned int order);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff8120bf30)
Location: mm/vmscan.c:3876
Inline: False
Direct callers:
  - mm/vmscan.c:node_reclaim
```
**Symbols:**

```
ffffffff8120bf30-ffffffff8120c0b8: __node_reclaim (STB_LOCAL)
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
In mm/vmscan.c (ffffffff8121ec68)
Location: mm/vmscan.c:4169
Inline: True
Inline callers:
  - mm/vmscan.c:node_reclaim
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
In mm/vmscan.c (ffffffff8122e345)
Location: mm/vmscan.c:4123
Inline: True
Inline callers:
  - mm/vmscan.c:node_reclaim
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
In mm/vmscan.c (ffffffff8123c4d5)
Location: mm/vmscan.c:4209
Inline: True
Inline callers:
  - mm/vmscan.c:node_reclaim
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __node_reclaim(struct pglist_data *pgdat, gfp_t gfp_mask, unsigned int order);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81269420)
Location: mm/vmscan.c:4167
Inline: False
Direct callers:
  - mm/vmscan.c:node_reclaim
```
**Symbols:**

```
ffffffff81269420-ffffffff81269663: __node_reclaim (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __node_reclaim(struct pglist_data *pgdat, gfp_t gfp_mask, unsigned int order);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81273f50)
Location: mm/vmscan.c:4170
Inline: False
Direct callers:
  - mm/vmscan.c:node_reclaim
```
**Symbols:**

```
ffffffff81273f50-ffffffff81274158: __node_reclaim (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __node_reclaim(struct pglist_data *pgdat, gfp_t gfp_mask, unsigned int order);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81278d90)
Location: mm/vmscan.c:4360
Inline: False
Direct callers:
  - mm/vmscan.c:node_reclaim
```
**Symbols:**

```
ffffffff81278d90-ffffffff81278fa6: __node_reclaim (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int __node_reclaim(struct pglist_data *pgdat, gfp_t gfp_mask, unsigned int order);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/vmscan.c (0)
Location: mm/vmscan.c:4549
Inline: False
Direct callers:
  - mm/vmscan.c:node_reclaim
```
**Symbols:**

```
ffffffff812b6b60-ffffffff812b6dcd: __node_reclaim (STB_LOCAL)
ffffffff81cba863-ffffffff81cba87b: __node_reclaim.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int __node_reclaim(struct pglist_data *pgdat, gfp_t gfp_mask, unsigned int order);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/vmscan.c (0)
Location: mm/vmscan.c:4695
Inline: False
Direct callers:
  - mm/vmscan.c:node_reclaim
```
**Symbols:**

```
ffffffff81312a60-ffffffff81312d25: __node_reclaim (STB_LOCAL)
ffffffff81e6c195-ffffffff81e6c1ad: __node_reclaim.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int __node_reclaim(struct pglist_data *pgdat, gfp_t gfp_mask, unsigned int order);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/vmscan.c (0)
Location: mm/vmscan.c:7640
Inline: False
Direct callers:
  - mm/vmscan.c:node_reclaim
```
**Symbols:**

```
ffffffff81385ea0-ffffffff8138616e: __node_reclaim (STB_LOCAL)
ffffffff82062c29-ffffffff82062c41: __node_reclaim.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int __node_reclaim(struct pglist_data *pgdat, gfp_t gfp_mask, unsigned int order);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/vmscan.c (0)
Location: mm/vmscan.c:8004
Inline: False
Direct callers:
  - mm/vmscan.c:node_reclaim
```
**Symbols:**

```
ffffffff813b9170-ffffffff813b943b: __node_reclaim (STB_LOCAL)
ffffffff820e23c2-ffffffff820e23da: __node_reclaim.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int __node_reclaim(struct pglist_data *pgdat, gfp_t gfp_mask, unsigned int order);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/vmscan.c (0)
Location: mm/vmscan.c:7372
Inline: False
Direct callers:
  - mm/vmscan.c:node_reclaim
```
**Symbols:**

```
ffffffff813e2170-ffffffff813e248e: __node_reclaim (STB_LOCAL)
ffffffff821bed6c-ffffffff821bed84: __node_reclaim.cold (STB_LOCAL)
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
In mm/vmscan.c (ffff8000102cd6e4)
Location: mm/vmscan.c:4209
Inline: True
Inline callers:
  - mm/vmscan.c:node_reclaim
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (c00000000038b128)
Location: mm/vmscan.c:4209
Inline: True
Inline callers:
  - mm/vmscan.c:node_reclaim
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81234b25)
Location: mm/vmscan.c:4209
Inline: True
Inline callers:
  - mm/vmscan.c:node_reclaim
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
In mm/vmscan.c (ffffffff81227b95)
Location: mm/vmscan.c:4209
Inline: True
Inline callers:
  - mm/vmscan.c:node_reclaim
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
In mm/vmscan.c (ffffffff812328c5)
Location: mm/vmscan.c:4209
Inline: True
Inline callers:
  - mm/vmscan.c:node_reclaim
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
In mm/vmscan.c (ffffffff81241d85)
Location: mm/vmscan.c:4209
Inline: True
Inline callers:
  - mm/vmscan.c:node_reclaim
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
