# Function: <code>scan_get_next_rmap_item</code>

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
In mm/ksm.c (ffffffff811e5a40)
Location: mm/ksm.c:1554
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
In mm/ksm.c (ffffffff81204755)
Location: mm/ksm.c:1526
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
In mm/ksm.c (ffffffff81216849)
Location: mm/ksm.c:1572
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
In mm/ksm.c (ffffffff81222265)
Location: mm/ksm.c:2138
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
In mm/ksm.c (ffffffff8123d5a0)
Location: mm/ksm.c:2152
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
In mm/ksm.c (ffffffff81260bfa)
Location: mm/ksm.c:2210
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
In mm/ksm.c (ffffffff812753dd)
Location: mm/ksm.c:2208
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
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
In mm/ksm.c (ffffffff81291c10)
Location: mm/ksm.c:2234
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
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
In mm/ksm.c (ffffffff812a1990)
Location: mm/ksm.c:2216
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct rmap_item *scan_get_next_rmap_item(struct page **page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff812d57d0)
Location: mm/ksm.c:2224
Inline: False
Direct callers:
  - mm/ksm.c:ksm_scan_thread
```
**Symbols:**

```
ffffffff812d57d0-ffffffff812d5c71: scan_get_next_rmap_item (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct rmap_item *scan_get_next_rmap_item(struct page **page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff812e1250)
Location: mm/ksm.c:2225
Inline: False
Direct callers:
  - mm/ksm.c:ksm_scan_thread
```
**Symbols:**

```
ffffffff812e1250-ffffffff812e1761: scan_get_next_rmap_item (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct rmap_item *scan_get_next_rmap_item(struct page **page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff812e8950)
Location: mm/ksm.c:2221
Inline: False
Direct callers:
  - mm/ksm.c:ksm_scan_thread
```
**Symbols:**

```
ffffffff812e8950-ffffffff812e8f04: scan_get_next_rmap_item (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct rmap_item *scan_get_next_rmap_item(struct page **page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff81330880)
Location: mm/ksm.c:2217
Inline: False
Direct callers:
  - mm/ksm.c:ksm_scan_thread
```
**Symbols:**

```
ffffffff81330880-ffffffff81330e2b: scan_get_next_rmap_item (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct rmap_item *scan_get_next_rmap_item(struct page **page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff813a14a0)
Location: mm/ksm.c:2229
Inline: False
Direct callers:
  - mm/ksm.c:ksm_scan_thread
```
**Symbols:**

```
ffffffff813a14a0-ffffffff813a1b4d: scan_get_next_rmap_item (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct ksm_rmap_item *scan_get_next_rmap_item(struct page **page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff814205c0)
Location: mm/ksm.c:2246
Inline: False
Direct callers:
  - mm/ksm.c:ksm_scan_thread
```
**Symbols:**

```
ffffffff814205c0-ffffffff81420c7d: scan_get_next_rmap_item (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct ksm_rmap_item *scan_get_next_rmap_item(struct page **page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff81455260)
Location: mm/ksm.c:2295
Inline: False
Direct callers:
  - mm/ksm.c:ksm_scan_thread
```
**Symbols:**

```
ffffffff81455260-ffffffff81455a60: scan_get_next_rmap_item (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct ksm_rmap_item *scan_get_next_rmap_item(struct page **page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/ksm.c (0)
Location: mm/ksm.c:2562
Inline: False
Direct callers:
  - mm/ksm.c:ksm_scan_thread
```
**Symbols:**

```
ffffffff8148f150-ffffffff8148fac6: scan_get_next_rmap_item (STB_LOCAL)
ffffffff821c3cc8-ffffffff821c3cea: scan_get_next_rmap_item.cold (STB_LOCAL)
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
In mm/ksm.c (ffff80001034121c)
Location: mm/ksm.c:2216
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
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
In mm/ksm.c (c05463ac)
Location: mm/ksm.c:2216
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
struct rmap_item *scan_get_next_rmap_item(struct page **page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (c00000000041c770)
Location: mm/ksm.c:2216
Inline: False
Direct callers:
  - mm/ksm.c:ksm_scan_thread
```
**Symbols:**

```
c00000000041c770-c00000000041cf78: scan_get_next_rmap_item (STB_LOCAL)
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
In mm/ksm.c (ffffffe000234cd0)
Location: mm/ksm.c:2216
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff81299f70)
Location: mm/ksm.c:2216
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
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
In mm/ksm.c (ffffffff8128bb30)
Location: mm/ksm.c:2216
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
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
In mm/ksm.c (ffffffff81297d80)
Location: mm/ksm.c:2216
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
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
In mm/ksm.c (ffffffff812a7b3b)
Location: mm/ksm.c:2216
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>struct rmap_item *</code> ➡️ <code>struct ksm_rmap_item *</code>
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
</ul>
