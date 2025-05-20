# Function: <code>wb_domain_writeout_inc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void wb_domain_writeout_inc(struct wb_domain *dom, struct fprop_local_percpu *completions, unsigned int max_prop_frac);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff81198530)
Location: mm/page-writeback.c:534
Inline: False
Direct callers:
  - mm/page-writeback.c:wb_writeout_inc
  - mm/page-writeback.c:wb_writeout_inc
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
```
**Symbols:**

```
ffffffff81198530-ffffffff8119857a: wb_domain_writeout_inc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void wb_domain_writeout_inc(struct wb_domain *dom, struct fprop_local_percpu *completions, unsigned int max_prop_frac);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff811ad480)
Location: mm/page-writeback.c:576
Inline: False
Direct callers:
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:wb_writeout_inc
  - mm/page-writeback.c:wb_writeout_inc
```
**Symbols:**

```
ffffffff811ad480-ffffffff811ad4ca: wb_domain_writeout_inc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void wb_domain_writeout_inc(struct wb_domain *dom, struct fprop_local_percpu *completions, unsigned int max_prop_frac);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff811bd9e0)
Location: mm/page-writeback.c:576
Inline: False
Direct callers:
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:wb_writeout_inc
  - mm/page-writeback.c:wb_writeout_inc
```
**Symbols:**

```
ffffffff811bd9e0-ffffffff811bda2a: wb_domain_writeout_inc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/page-writeback.c (ffffffff811c952d)
Location: mm/page-writeback.c:577
Inline: True
Inline callers:
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:wb_writeout_inc
  - mm/page-writeback.c:wb_writeout_inc
Direct callers:
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:wb_writeout_inc
  - mm/page-writeback.c:wb_writeout_inc
```
**Symbols:**

```
ffffffff811c6220-ffffffff811c624f: wb_domain_writeout_inc.part.28 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/page-writeback.c (ffffffff811de353)
Location: mm/page-writeback.c:577
Inline: True
Inline callers:
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:wb_writeout_inc
  - mm/page-writeback.c:wb_writeout_inc
Direct callers:
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:wb_writeout_inc
  - mm/page-writeback.c:wb_writeout_inc
```
**Symbols:**

```
ffffffff811db030-ffffffff811db05f: wb_domain_writeout_inc.part.28 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/page-writeback.c (ffffffff811ff9ef)
Location: mm/page-writeback.c:577
Inline: True
Inline callers:
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:wb_writeout_inc
  - mm/page-writeback.c:wb_writeout_inc
Direct callers:
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:wb_writeout_inc
  - mm/page-writeback.c:wb_writeout_inc
```
**Symbols:**

```
ffffffff811fc0d0-ffffffff811fc0ff: wb_domain_writeout_inc.part.30 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/page-writeback.c (ffffffff812122bc)
Location: mm/page-writeback.c:576
Inline: True
Inline callers:
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:wb_writeout_inc
  - mm/page-writeback.c:wb_writeout_inc
Direct callers:
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:wb_writeout_inc
  - mm/page-writeback.c:wb_writeout_inc
```
**Symbols:**

```
ffffffff8120e9e0-ffffffff8120ea0f: wb_domain_writeout_inc.part.33 (STB_LOCAL)
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
In mm/page-writeback.c (ffffffff81221bb2)
Location: mm/page-writeback.c:577
Inline: True
Inline callers:
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:wb_writeout_inc
  - mm/page-writeback.c:wb_writeout_inc
  - mm/page-writeback.c:wb_writeout_inc
  - mm/page-writeback.c:wb_writeout_inc
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
In mm/page-writeback.c (ffffffff8122f662)
Location: mm/page-writeback.c:577
Inline: True
Inline callers:
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:wb_writeout_inc
  - mm/page-writeback.c:wb_writeout_inc
  - mm/page-writeback.c:wb_writeout_inc
  - mm/page-writeback.c:wb_writeout_inc
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
In mm/page-writeback.c (ffffffff8125c6d1)
Location: mm/page-writeback.c:571
Inline: True
Inline callers:
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:wb_writeout_inc
  - mm/page-writeback.c:wb_writeout_inc
  - mm/page-writeback.c:wb_writeout_inc
  - mm/page-writeback.c:wb_writeout_inc
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
In mm/page-writeback.c (ffffffff81266aa3)
Location: mm/page-writeback.c:571
Inline: True
Inline callers:
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:wb_writeout_inc
  - mm/page-writeback.c:wb_writeout_inc
  - mm/page-writeback.c:wb_writeout_inc
  - mm/page-writeback.c:wb_writeout_inc
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
In mm/page-writeback.c (ffffffff8126b52f)
Location: mm/page-writeback.c:571
Inline: True
Inline callers:
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:wb_writeout_inc
  - mm/page-writeback.c:wb_writeout_inc
  - mm/page-writeback.c:wb_writeout_inc
  - mm/page-writeback.c:wb_writeout_inc
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
In mm/page-writeback.c (ffffffff812a81eb)
Location: mm/page-writeback.c:565
Inline: True
Inline callers:
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:wb_writeout_inc
  - mm/page-writeback.c:wb_writeout_inc
  - mm/page-writeback.c:wb_writeout_inc
  - mm/page-writeback.c:wb_writeout_inc
```
</details>
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In mm/page-writeback.c (ffff8000102beb10)
Location: mm/page-writeback.c:577
Inline: True
Inline callers:
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:wb_writeout_inc
  - mm/page-writeback.c:wb_writeout_inc
  - mm/page-writeback.c:wb_writeout_inc
  - mm/page-writeback.c:wb_writeout_inc
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
In mm/page-writeback.c (c04ea9d4)
Location: mm/page-writeback.c:577
Inline: True
Inline callers:
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:wb_writeout_inc
  - mm/page-writeback.c:wb_writeout_inc
  - mm/page-writeback.c:wb_writeout_inc
  - mm/page-writeback.c:wb_writeout_inc
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
In mm/page-writeback.c (c00000000037782c)
Location: mm/page-writeback.c:577
Inline: True
Inline callers:
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:wb_writeout_inc
  - mm/page-writeback.c:wb_writeout_inc
  - mm/page-writeback.c:wb_writeout_inc
  - mm/page-writeback.c:wb_writeout_inc
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
In mm/page-writeback.c (ffffffe0001e1192)
Location: mm/page-writeback.c:577
Inline: True
Inline callers:
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:wb_writeout_inc
  - mm/page-writeback.c:wb_writeout_inc
  - mm/page-writeback.c:wb_writeout_inc
  - mm/page-writeback.c:wb_writeout_inc
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
In mm/page-writeback.c (ffffffff81227cb2)
Location: mm/page-writeback.c:577
Inline: True
Inline callers:
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:wb_writeout_inc
  - mm/page-writeback.c:wb_writeout_inc
  - mm/page-writeback.c:wb_writeout_inc
  - mm/page-writeback.c:wb_writeout_inc
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
In mm/page-writeback.c (ffffffff8121adec)
Location: mm/page-writeback.c:577
Inline: True
Inline callers:
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:wb_writeout_inc
  - mm/page-writeback.c:wb_writeout_inc
  - mm/page-writeback.c:wb_writeout_inc
  - mm/page-writeback.c:wb_writeout_inc
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
In mm/page-writeback.c (ffffffff81225a52)
Location: mm/page-writeback.c:577
Inline: True
Inline callers:
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:wb_writeout_inc
  - mm/page-writeback.c:wb_writeout_inc
  - mm/page-writeback.c:wb_writeout_inc
  - mm/page-writeback.c:wb_writeout_inc
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
In mm/page-writeback.c (ffffffff81234d52)
Location: mm/page-writeback.c:577
Inline: True
Inline callers:
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:wb_writeout_inc
  - mm/page-writeback.c:wb_writeout_inc
  - mm/page-writeback.c:wb_writeout_inc
  - mm/page-writeback.c:wb_writeout_inc
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
</ul>
