# Function: <code>__offline_pages</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memory_hotplug.c (ffffffff8181a1a0)
Location: mm/memory_hotplug.c:1714
Inline: True
Direct callers:
  - mm/memory_hotplug.c:offline_pages
```
**Symbols:**

```
ffffffff8181a1a0-ffffffff8181a91d: __offline_pages.constprop.24 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81893c20)
Location: mm/memory_hotplug.c:1863
Inline: True
Direct callers:
  - mm/memory_hotplug.c:offline_pages
```
**Symbols:**

```
ffffffff81893c20-ffffffff8189450a: __offline_pages.constprop.26 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memory_hotplug.c (ffffffff818c8320)
Location: mm/memory_hotplug.c:1848
Inline: True
Direct callers:
  - mm/memory_hotplug.c:offline_pages
```
**Symbols:**

```
ffffffff818c8320-ffffffff818c8c13: __offline_pages.constprop.27 (STB_LOCAL)
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
In mm/memory_hotplug.c (ffffffff818ff900)
Location: mm/memory_hotplug.c:1615
Inline: True
Direct callers:
  - mm/memory_hotplug.c:offline_pages
```
**Symbols:**

```
ffffffff818ff900-ffffffff8190017f: __offline_pages.constprop.23 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __offline_pages(long unsigned int start_pfn, long unsigned int end_pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81989940)
Location: mm/memory_hotplug.c:1605
Inline: False
Direct callers:
  - mm/memory_hotplug.c:offline_pages
```
**Symbols:**

```
ffffffff81989940-ffffffff8198a11f: __offline_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __offline_pages(long unsigned int start_pfn, long unsigned int end_pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff819e6230)
Location: mm/memory_hotplug.c:1614
Inline: False
Direct callers:
  - mm/memory_hotplug.c:offline_pages
```
**Symbols:**

```
ffffffff819e6230-ffffffff819e6a37: __offline_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __offline_pages(long unsigned int start_pfn, long unsigned int end_pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81a21610)
Location: mm/memory_hotplug.c:1571
Inline: False
Direct callers:
  - mm/memory_hotplug.c:offline_pages
```
**Symbols:**

```
ffffffff81a21610-ffffffff81a21eae: __offline_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __offline_pages(long unsigned int start_pfn, long unsigned int end_pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81a91fb0)
Location: mm/memory_hotplug.c:1525
Inline: False
Direct callers:
  - mm/memory_hotplug.c:offline_pages
```
**Symbols:**

```
ffffffff81a91fb0-ffffffff81a9250e: __offline_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __offline_pages(long unsigned int start_pfn, long unsigned int end_pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81ac9740)
Location: mm/memory_hotplug.c:1500
Inline: False
Direct callers:
  - mm/memory_hotplug.c:offline_pages
```
**Symbols:**

```
ffffffff81ac9740-ffffffff81ac9cb2: __offline_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __offline_pages(long unsigned int start_pfn, long unsigned int end_pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81bc1e70)
Location: mm/memory_hotplug.c:1474
Inline: False
Direct callers:
  - mm/memory_hotplug.c:offline_pages
```
**Symbols:**

```
ffffffff81bc1e70-ffffffff81bc2269: __offline_pages (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
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
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __offline_pages(long unsigned int start_pfn, long unsigned int end_pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (c0000000004305f0)
Location: mm/memory_hotplug.c:1500
Inline: False
Direct callers:
  - mm/memory_hotplug.c:offline_pages
```
**Symbols:**

```
c0000000004305f0-c000000000430db4: __offline_pages (STB_LOCAL)
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
int __offline_pages(long unsigned int start_pfn, long unsigned int end_pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81a685b0)
Location: mm/memory_hotplug.c:1500
Inline: False
Direct callers:
  - mm/memory_hotplug.c:offline_pages
```
**Symbols:**

```
ffffffff81a685b0-ffffffff81a68b22: __offline_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __offline_pages(long unsigned int start_pfn, long unsigned int end_pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81a25070)
Location: mm/memory_hotplug.c:1500
Inline: False
Direct callers:
  - mm/memory_hotplug.c:offline_pages
```
**Symbols:**

```
ffffffff81a25070-ffffffff81a255e2: __offline_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __offline_pages(long unsigned int start_pfn, long unsigned int end_pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81ad49c0)
Location: mm/memory_hotplug.c:1500
Inline: False
Direct callers:
  - mm/memory_hotplug.c:offline_pages
```
**Symbols:**

```
ffffffff81ad49c0-ffffffff81ad4f32: __offline_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __offline_pages(long unsigned int start_pfn, long unsigned int end_pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81ae0ea0)
Location: mm/memory_hotplug.c:1500
Inline: False
Direct callers:
  - mm/memory_hotplug.c:offline_pages
```
**Symbols:**

```
ffffffff81ae0ea0-ffffffff81ae140d: __offline_pages (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
