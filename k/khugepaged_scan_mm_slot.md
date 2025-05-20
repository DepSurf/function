# Function: <code>khugepaged_scan_mm_slot</code>

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
In mm/huge_memory.c (ffffffff811f485f)
Location: mm/huge_memory.c:2742
Inline: True
Inline callers:
  - mm/huge_memory.c:khugepaged
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
In mm/khugepaged.c (ffffffff8121bbe5)
Location: mm/khugepaged.c:1643
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
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
In mm/khugepaged.c (ffffffff8122cf93)
Location: mm/khugepaged.c:1651
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
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
In mm/khugepaged.c (ffffffff8123972c)
Location: mm/khugepaged.c:1652
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
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
In mm/khugepaged.c (ffffffff812582ec)
Location: mm/khugepaged.c:1658
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
unsigned int khugepaged_scan_mm_slot(unsigned int pages, struct page **hpage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff8127cc50)
Location: mm/khugepaged.c:1654
Inline: False
Direct callers:
  - mm/khugepaged.c:khugepaged
```
**Symbols:**

```
ffffffff8127cc50-ffffffff8127d86c: khugepaged_scan_mm_slot (STB_LOCAL)
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
In mm/khugepaged.c (ffffffff812917e0)
Location: mm/khugepaged.c:1643
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
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
In mm/khugepaged.c (ffffffff812ac726)
Location: mm/khugepaged.c:1649
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
unsigned int khugepaged_scan_mm_slot(unsigned int pages, struct page **hpage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff812be100)
Location: mm/khugepaged.c:1902
Inline: False
Direct callers:
  - mm/khugepaged.c:khugepaged
```
**Symbols:**

```
ffffffff812be100-ffffffff812be792: khugepaged_scan_mm_slot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
unsigned int khugepaged_scan_mm_slot(unsigned int pages, struct page **hpage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff812f3990)
Location: mm/khugepaged.c:2028
Inline: False
Direct callers:
  - mm/khugepaged.c:khugepaged_do_scan
```
**Symbols:**

```
ffffffff812f3990-ffffffff812f3d12: khugepaged_scan_mm_slot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
unsigned int khugepaged_scan_mm_slot(unsigned int pages, struct page **hpage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff812ff190)
Location: mm/khugepaged.c:2065
Inline: False
Direct callers:
  - mm/khugepaged.c:khugepaged_do_scan
```
**Symbols:**

```
ffffffff812ff190-ffffffff812ff610: khugepaged_scan_mm_slot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
unsigned int khugepaged_scan_mm_slot(unsigned int pages, struct page **hpage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff81305e10)
Location: mm/khugepaged.c:2055
Inline: False
Direct callers:
  - mm/khugepaged.c:khugepaged
```
**Symbols:**

```
ffffffff81305e10-ffffffff81306287: khugepaged_scan_mm_slot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
unsigned int khugepaged_scan_mm_slot(unsigned int pages, struct page **hpage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff8134fc70)
Location: mm/khugepaged.c:2077
Inline: False
Direct callers:
  - mm/khugepaged.c:khugepaged
```
**Symbols:**

```
ffffffff8134fc70-ffffffff813500d7: khugepaged_scan_mm_slot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
unsigned int khugepaged_scan_mm_slot(unsigned int pages, struct page **hpage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff813c7e90)
Location: mm/khugepaged.c:2090
Inline: False
Direct callers:
  - mm/khugepaged.c:khugepaged
```
**Symbols:**

```
ffffffff813c7e90-ffffffff813c82d9: khugepaged_scan_mm_slot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/khugepaged.c (0)
Location: mm/khugepaged.c:2248
Inline: True
Direct callers:
  - mm/khugepaged.c:khugepaged
```
**Symbols:**

```
ffffffff8144c070-ffffffff8144c5b3: khugepaged_scan_mm_slot.constprop.0 (STB_LOCAL)
ffffffff82067f1f-ffffffff82067f40: khugepaged_scan_mm_slot.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/khugepaged.c (0)
Location: mm/khugepaged.c:2437
Inline: True
Direct callers:
  - mm/khugepaged.c:khugepaged
```
**Symbols:**

```
ffffffff81481890-ffffffff81481e61: khugepaged_scan_mm_slot.constprop.0 (STB_LOCAL)
ffffffff820e7809-ffffffff820e781d: khugepaged_scan_mm_slot.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/khugepaged.c (0)
Location: mm/khugepaged.c:2325
Inline: True
Direct callers:
  - mm/khugepaged.c:khugepaged
```
**Symbols:**

```
ffffffff814b0ca0-ffffffff814b1202: khugepaged_scan_mm_slot.constprop.0 (STB_LOCAL)
ffffffff821c4502-ffffffff821c4516: khugepaged_scan_mm_slot.constprop.0.cold (STB_LOCAL)
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
In mm/khugepaged.c (ffff80001035fa80)
Location: mm/khugepaged.c:1902
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
unsigned int khugepaged_scan_mm_slot(unsigned int pages, struct page **hpage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (c00000000044a680)
Location: mm/khugepaged.c:1902
Inline: False
Direct callers:
  - mm/khugepaged.c:khugepaged
```
**Symbols:**

```
c00000000044a680-c00000000044b048: khugepaged_scan_mm_slot (STB_LOCAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
unsigned int khugepaged_scan_mm_slot(unsigned int pages, struct page **hpage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff812b66e0)
Location: mm/khugepaged.c:1902
Inline: False
Direct callers:
  - mm/khugepaged.c:khugepaged
```
**Symbols:**

```
ffffffff812b66e0-ffffffff812b6d72: khugepaged_scan_mm_slot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
unsigned int khugepaged_scan_mm_slot(unsigned int pages, struct page **hpage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff812a78b0)
Location: mm/khugepaged.c:1902
Inline: False
Direct callers:
  - mm/khugepaged.c:khugepaged
```
**Symbols:**

```
ffffffff812a78b0-ffffffff812a7f42: khugepaged_scan_mm_slot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
unsigned int khugepaged_scan_mm_slot(unsigned int pages, struct page **hpage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff812b44f0)
Location: mm/khugepaged.c:1902
Inline: False
Direct callers:
  - mm/khugepaged.c:khugepaged
```
**Symbols:**

```
ffffffff812b44f0-ffffffff812b4b82: khugepaged_scan_mm_slot (STB_LOCAL)
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
In mm/khugepaged.c (ffffffff812c4e68)
Location: mm/khugepaged.c:1902
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
<b>Arch</b>
<ul>
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
</ul>
