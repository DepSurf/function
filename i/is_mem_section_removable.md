# Function: <code>is_mem_section_removable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int is_mem_section_removable(long unsigned int start_pfn, long unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff811f01d0)
Location: mm/memory_hotplug.c:1357
Inline: False
Direct callers:
  - drivers/base/memory.c:show_mem_removable
```
**Symbols:**

```
ffffffff811f01d0-ffffffff811f025d: is_mem_section_removable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool is_mem_section_removable(long unsigned int start_pfn, long unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff8120f4f0)
Location: mm/memory_hotplug.c:1477
Inline: False
Direct callers:
  - drivers/base/memory.c:show_mem_removable
```
**Symbols:**

```
ffffffff8120f4f0-ffffffff8120f57d: is_mem_section_removable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool is_mem_section_removable(long unsigned int start_pfn, long unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff812215f0)
Location: mm/memory_hotplug.c:1469
Inline: False
Direct callers:
  - drivers/base/memory.c:show_mem_removable
```
**Symbols:**

```
ffffffff812215f0-ffffffff8122168d: is_mem_section_removable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool is_mem_section_removable(long unsigned int start_pfn, long unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff8122d210)
Location: mm/memory_hotplug.c:1280
Inline: False
Direct callers:
  - drivers/base/memory.c:show_mem_removable
```
**Symbols:**

```
ffffffff8122d210-ffffffff8122d2a8: is_mem_section_removable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool is_mem_section_removable(long unsigned int start_pfn, long unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81248a90)
Location: mm/memory_hotplug.c:1268
Inline: False
Direct callers:
  - drivers/base/memory.c:show_mem_removable
```
**Symbols:**

```
ffffffff81248a90-ffffffff81248b28: is_mem_section_removable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool is_mem_section_removable(long unsigned int start_pfn, long unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff8126c4b0)
Location: mm/memory_hotplug.c:1277
Inline: False
Direct callers:
  - drivers/base/memory.c:show_mem_removable
```
**Symbols:**

```
ffffffff8126c4b0-ffffffff8126c5b6: is_mem_section_removable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool is_mem_section_removable(long unsigned int start_pfn, long unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81280cd0)
Location: mm/memory_hotplug.c:1248
Inline: False
Direct callers:
  - drivers/base/memory.c:removable_show
```
**Symbols:**

```
ffffffff81280cd0-ffffffff81280e1b: is_mem_section_removable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool is_mem_section_removable(long unsigned int start_pfn, long unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff8129d120)
Location: mm/memory_hotplug.c:1231
Inline: False
Direct callers:
  - drivers/base/memory.c:removable_show
```
**Symbols:**

```
ffffffff8129d120-ffffffff8129d27c: is_mem_section_removable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool is_mem_section_removable(long unsigned int start_pfn, long unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff812ac8f0)
Location: mm/memory_hotplug.c:1206
Inline: False
```
**Symbols:**

```
ffffffff812ac8f0-ffffffff812aca47: is_mem_section_removable (STB_GLOBAL)
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
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool is_mem_section_removable(long unsigned int start_pfn, long unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (c00000000042ed00)
Location: mm/memory_hotplug.c:1206
Inline: False
```
**Symbols:**

```
c00000000042ed00-c00000000042ef38: is_mem_section_removable (STB_GLOBAL)
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
bool is_mem_section_removable(long unsigned int start_pfn, long unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff812a4ed0)
Location: mm/memory_hotplug.c:1206
Inline: False
```
**Symbols:**

```
ffffffff812a4ed0-ffffffff812a5027: is_mem_section_removable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool is_mem_section_removable(long unsigned int start_pfn, long unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff812969a0)
Location: mm/memory_hotplug.c:1206
Inline: False
```
**Symbols:**

```
ffffffff812969a0-ffffffff81296af7: is_mem_section_removable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool is_mem_section_removable(long unsigned int start_pfn, long unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff812a2ce0)
Location: mm/memory_hotplug.c:1206
Inline: False
```
**Symbols:**

```
ffffffff812a2ce0-ffffffff812a2e37: is_mem_section_removable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool is_mem_section_removable(long unsigned int start_pfn, long unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff812b2f70)
Location: mm/memory_hotplug.c:1206
Inline: False
```
**Symbols:**

```
ffffffff812b2f70-ffffffff812b30c2: is_mem_section_removable (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>bool</code>
</li>
</ul>
</details>
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
