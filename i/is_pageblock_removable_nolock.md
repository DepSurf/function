# Function: <code>is_pageblock_removable_nolock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
bool is_pageblock_removable_nolock(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81197600)
Location: mm/page_alloc.c:6579
Inline: False
Direct callers:
  - mm/memory_hotplug.c:is_mem_section_removable
```
**Symbols:**

```
ffffffff81197600-ffffffff81197694: is_pageblock_removable_nolock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool is_pageblock_removable_nolock(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811ac510)
Location: mm/page_alloc.c:7110
Inline: False
Direct callers:
  - mm/memory_hotplug.c:is_mem_section_removable
```
**Symbols:**

```
ffffffff811ac510-ffffffff811ac59f: is_pageblock_removable_nolock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool is_pageblock_removable_nolock(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811bcaf0)
Location: mm/page_alloc.c:7162
Inline: False
Direct callers:
  - mm/memory_hotplug.c:is_mem_section_removable
```
**Symbols:**

```
ffffffff811bcaf0-ffffffff811bcb7c: is_pageblock_removable_nolock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool is_pageblock_removable_nolock(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811c4cc0)
Location: mm/page_alloc.c:7492
Inline: False
Direct callers:
  - mm/memory_hotplug.c:is_mem_section_removable
```
**Symbols:**

```
ffffffff811c4cc0-ffffffff811c4d46: is_pageblock_removable_nolock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool is_pageblock_removable_nolock(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811d9aa0)
Location: mm/page_alloc.c:7516
Inline: False
Direct callers:
  - mm/memory_hotplug.c:is_mem_section_removable
```
**Symbols:**

```
ffffffff811d9aa0-ffffffff811d9b1a: is_pageblock_removable_nolock (STB_GLOBAL)
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
In mm/memory_hotplug.c (ffffffff8126c565)
Location: mm/memory_hotplug.c:1253
Inline: True
Inline callers:
  - mm/memory_hotplug.c:is_mem_section_removable
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
In mm/memory_hotplug.c (ffffffff81280dcd)
Location: mm/memory_hotplug.c:1224
Inline: True
Inline callers:
  - mm/memory_hotplug.c:is_mem_section_removable
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
In mm/memory_hotplug.c (ffffffff8129d230)
Location: mm/memory_hotplug.c:1207
Inline: True
Inline callers:
  - mm/memory_hotplug.c:is_mem_section_removable
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
In mm/memory_hotplug.c (ffffffff812aca00)
Location: mm/memory_hotplug.c:1182
Inline: True
Inline callers:
  - mm/memory_hotplug.c:is_mem_section_removable
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
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
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (c00000000042ee70)
Location: mm/memory_hotplug.c:1182
Inline: True
Inline callers:
  - mm/memory_hotplug.c:is_mem_section_removable
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
In mm/memory_hotplug.c (ffffffff812a4fe0)
Location: mm/memory_hotplug.c:1182
Inline: True
Inline callers:
  - mm/memory_hotplug.c:is_mem_section_removable
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
In mm/memory_hotplug.c (ffffffff81296ab0)
Location: mm/memory_hotplug.c:1182
Inline: True
Inline callers:
  - mm/memory_hotplug.c:is_mem_section_removable
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
In mm/memory_hotplug.c (ffffffff812a2df0)
Location: mm/memory_hotplug.c:1182
Inline: True
Inline callers:
  - mm/memory_hotplug.c:is_mem_section_removable
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
In mm/memory_hotplug.c (ffffffff812b307b)
Location: mm/memory_hotplug.c:1182
Inline: True
Inline callers:
  - mm/memory_hotplug.c:is_mem_section_removable
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
</ul>
