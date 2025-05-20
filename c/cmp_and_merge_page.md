# Function: <code>cmp_and_merge_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff811e59be)
Location: mm/ksm.c:1434
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff81204726)
Location: mm/ksm.c:1406
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
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
In mm/ksm.c (ffffffff81216be5)
Location: mm/ksm.c:1435
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
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
In mm/ksm.c (ffffffff812225f8)
Location: mm/ksm.c:1991
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
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
In mm/ksm.c (ffffffff8123d96a)
Location: mm/ksm.c:2002
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
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
In mm/ksm.c (ffffffff81260f3e)
Location: mm/ksm.c:2032
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
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
In mm/ksm.c (ffffffff8127571c)
Location: mm/ksm.c:2030
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void cmp_and_merge_page(struct page *page, struct rmap_item *rmap_item);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff81291090)
Location: mm/ksm.c:2053
Inline: False
Direct callers:
  - mm/ksm.c:ksm_scan_thread
```
**Symbols:**

```
ffffffff81291090-ffffffff81291b58: cmp_and_merge_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void cmp_and_merge_page(struct page *page, struct rmap_item *rmap_item);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff812a0e10)
Location: mm/ksm.c:2035
Inline: False
Direct callers:
  - mm/ksm.c:ksm_scan_thread
```
**Symbols:**

```
ffffffff812a0e10-ffffffff812a18d8: cmp_and_merge_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void cmp_and_merge_page(struct page *page, struct rmap_item *rmap_item);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff812d6010)
Location: mm/ksm.c:2035
Inline: False
Direct callers:
  - mm/ksm.c:ksm_scan_thread
```
**Symbols:**

```
ffffffff812d6010-ffffffff812d6539: cmp_and_merge_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void cmp_and_merge_page(struct page *page, struct rmap_item *rmap_item);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff812e1b10)
Location: mm/ksm.c:2036
Inline: False
Direct callers:
  - mm/ksm.c:ksm_scan_thread
```
**Symbols:**

```
ffffffff812e1b10-ffffffff812e2075: cmp_and_merge_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void cmp_and_merge_page(struct page *page, struct rmap_item *rmap_item);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff812e92b0)
Location: mm/ksm.c:2032
Inline: False
Direct callers:
  - mm/ksm.c:ksm_scan_thread
```
**Symbols:**

```
ffffffff812e92b0-ffffffff812e9805: cmp_and_merge_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void cmp_and_merge_page(struct page *page, struct rmap_item *rmap_item);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/ksm.c (0)
Location: mm/ksm.c:2028
Inline: False
Direct callers:
  - mm/ksm.c:ksm_scan_thread
```
**Symbols:**

```
ffffffff813311e0-ffffffff8133173e: cmp_and_merge_page (STB_LOCAL)
ffffffff81cc0921-ffffffff81cc093b: cmp_and_merge_page.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void cmp_and_merge_page(struct page *page, struct rmap_item *rmap_item);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/ksm.c (0)
Location: mm/ksm.c:2040
Inline: False
Direct callers:
  - mm/ksm.c:ksm_scan_thread
```
**Symbols:**

```
ffffffff813a2020-ffffffff813a27f8: cmp_and_merge_page (STB_LOCAL)
ffffffff81e72daf-ffffffff81e72dc9: cmp_and_merge_page.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void cmp_and_merge_page(struct page *page, struct ksm_rmap_item *rmap_item);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/ksm.c (0)
Location: mm/ksm.c:2056
Inline: False
Direct callers:
  - mm/ksm.c:ksm_scan_thread
```
**Symbols:**

```
ffffffff81421c80-ffffffff8142249a: cmp_and_merge_page (STB_LOCAL)
ffffffff82067309-ffffffff82067323: cmp_and_merge_page.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void cmp_and_merge_page(struct page *page, struct ksm_rmap_item *rmap_item);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/ksm.c (0)
Location: mm/ksm.c:2102
Inline: False
Direct callers:
  - mm/ksm.c:ksm_scan_thread
```
**Symbols:**

```
ffffffff81456960-ffffffff81457201: cmp_and_merge_page (STB_LOCAL)
ffffffff820e6bcb-ffffffff820e6be6: cmp_and_merge_page.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void cmp_and_merge_page(struct page *page, struct ksm_rmap_item *rmap_item);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/ksm.c (0)
Location: mm/ksm.c:2301
Inline: False
Direct callers:
  - mm/ksm.c:ksm_scan_thread
```
**Symbols:**

```
ffffffff81491450-ffffffff81491cf0: cmp_and_merge_page (STB_LOCAL)
ffffffff821c3d0a-ffffffff821c3d27: cmp_and_merge_page.cold (STB_LOCAL)
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
void cmp_and_merge_page(struct page *page, struct rmap_item *rmap_item);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffff800010340740)
Location: mm/ksm.c:2035
Inline: False
Direct callers:
  - mm/ksm.c:ksm_scan_thread
```
**Symbols:**

```
ffff800010340740-ffff800010341160: cmp_and_merge_page (STB_LOCAL)
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
In mm/ksm.c (c0546738)
Location: mm/ksm.c:2035
Inline: True
Inline callers:
  - mm/ksm.c:ksm_do_scan
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void cmp_and_merge_page(struct page *page, struct rmap_item *rmap_item);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (c00000000041dcf0)
Location: mm/ksm.c:2035
Inline: False
Direct callers:
  - mm/ksm.c:ksm_scan_thread
```
**Symbols:**

```
c00000000041dcf0-c00000000041ebd8: cmp_and_merge_page (STB_LOCAL)
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
In mm/ksm.c (ffffffe000235040)
Location: mm/ksm.c:2035
Inline: True
Inline callers:
  - mm/ksm.c:ksm_do_scan
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
void cmp_and_merge_page(struct page *page, struct rmap_item *rmap_item);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff812993f0)
Location: mm/ksm.c:2035
Inline: False
Direct callers:
  - mm/ksm.c:ksm_scan_thread
```
**Symbols:**

```
ffffffff812993f0-ffffffff81299eb8: cmp_and_merge_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void cmp_and_merge_page(struct page *page, struct rmap_item *rmap_item);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff8128afb0)
Location: mm/ksm.c:2035
Inline: False
Direct callers:
  - mm/ksm.c:ksm_scan_thread
```
**Symbols:**

```
ffffffff8128afb0-ffffffff8128ba78: cmp_and_merge_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void cmp_and_merge_page(struct page *page, struct rmap_item *rmap_item);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff81297200)
Location: mm/ksm.c:2035
Inline: False
Direct callers:
  - mm/ksm.c:ksm_scan_thread
```
**Symbols:**

```
ffffffff81297200-ffffffff81297cc8: cmp_and_merge_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void cmp_and_merge_page(struct page *page, struct rmap_item *rmap_item);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff812a6fd0)
Location: mm/ksm.c:2035
Inline: False
Direct callers:
  - mm/ksm.c:ksm_scan_thread
```
**Symbols:**

```
ffffffff812a6fd0-ffffffff812a7a90: cmp_and_merge_page (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<code>struct rmap_item *rmap_item</code> ➡️ <code>struct ksm_rmap_item *rmap_item</code>
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
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
