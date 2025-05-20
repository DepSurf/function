# Function: <code>zone_pcp_disable</code>

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
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void zone_pcp_disable(struct zone *zone);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812bfdb0)
Location: mm/page_alloc.c:8795
Inline: False
Direct callers:
  - mm/memory_hotplug.c:offline_pages
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure_hugetlb
```
**Symbols:**

```
ffffffff812bfdb0-ffffffff812bfe18: zone_pcp_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void zone_pcp_disable(struct zone *zone);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812c5530)
Location: mm/page_alloc.c:9024
Inline: False
Direct callers:
  - mm/memory_hotplug.c:offline_pages
  - mm/memory-failure.c:get_hwpoison_page
```
**Symbols:**

```
ffffffff812c5530-ffffffff812c559a: zone_pcp_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void zone_pcp_disable(struct zone *zone);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81309b10)
Location: mm/page_alloc.c:9287
Inline: False
Direct callers:
  - mm/memory_hotplug.c:offline_pages
  - mm/memory-failure.c:get_hwpoison_page
  - mm/memory-failure.c:__page_handle_poison
```
**Symbols:**

```
ffffffff81309b10-ffffffff81309ba6: zone_pcp_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void zone_pcp_disable(struct zone *zone);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff813723c0)
Location: mm/page_alloc.c:9339
Inline: False
Direct callers:
  - mm/memory_hotplug.c:offline_pages
  - mm/memory-failure.c:get_hwpoison_page
  - mm/memory-failure.c:__page_handle_poison
```
**Symbols:**

```
ffffffff813723c0-ffffffff81372466: zone_pcp_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void zone_pcp_disable(struct zone *zone);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff813efbb0)
Location: mm/page_alloc.c:9502
Inline: False
Direct callers:
  - mm/memory_hotplug.c:offline_pages
  - mm/memory-failure.c:get_hwpoison_page
  - mm/memory-failure.c:__page_handle_poison
```
**Symbols:**

```
ffffffff813efbb0-ffffffff813efbf5: zone_pcp_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void zone_pcp_disable(struct zone *zone);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81423730)
Location: mm/page_alloc.c:6409
Inline: False
Direct callers:
  - mm/memory_hotplug.c:offline_pages
  - mm/memory-failure.c:get_hwpoison_page
  - mm/memory-failure.c:__page_handle_poison
```
**Symbols:**

```
ffffffff81423730-ffffffff81423775: zone_pcp_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void zone_pcp_disable(struct zone *zone);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81450660)
Location: mm/page_alloc.c:6551
Inline: False
Direct callers:
  - mm/memory_hotplug.c:offline_pages
  - mm/memory-failure.c:get_hwpoison_page
  - mm/memory-failure.c:__page_handle_poison
```
**Symbols:**

```
ffffffff81450660-ffffffff814506a9: zone_pcp_disable (STB_GLOBAL)
```
</details>
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
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
