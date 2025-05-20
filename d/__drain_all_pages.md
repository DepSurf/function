# Function: <code>__drain_all_pages</code>

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
void __drain_all_pages(struct zone *zone, bool force_all_cpus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812b9cd0)
Location: mm/page_alloc.c:3042
Inline: False
Direct callers:
  - mm/page_alloc.c:zone_pcp_disable
  - mm/page_alloc.c:alloc_contig_range
```
**Symbols:**

```
ffffffff812b9cd0-ffffffff812b9e7f: __drain_all_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __drain_all_pages(struct zone *zone, bool force_all_cpus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812bed40)
Location: mm/page_alloc.c:3091
Inline: False
Direct callers:
  - mm/page_alloc.c:zone_pcp_disable
  - mm/page_alloc.c:alloc_contig_range
```
**Symbols:**

```
ffffffff812bed40-ffffffff812beeff: __drain_all_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __drain_all_pages(struct zone *zone, bool force_all_cpus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81301870)
Location: mm/page_alloc.c:3167
Inline: False
Direct callers:
  - mm/page_alloc.c:zone_pcp_disable
  - mm/page_alloc.c:alloc_contig_range
```
**Symbols:**

```
ffffffff81301870-ffffffff81301ad3: __drain_all_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __drain_all_pages(struct zone *zone, bool force_all_cpus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff813688e0)
Location: mm/page_alloc.c:3189
Inline: False
Direct callers:
  - mm/page_alloc.c:zone_pcp_disable
  - mm/page_alloc.c:alloc_contig_range
```
**Symbols:**

```
ffffffff813688e0-ffffffff81368b4f: __drain_all_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __drain_all_pages(struct zone *zone, bool force_all_cpus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff813e5ce0)
Location: mm/page_alloc.c:3231
Inline: False
Direct callers:
  - mm/page_alloc.c:zone_pcp_disable
  - mm/page_alloc.c:alloc_contig_range
```
**Symbols:**

```
ffffffff813e5ce0-ffffffff813e5eb1: __drain_all_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __drain_all_pages(struct zone *zone, bool force_all_cpus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8141aa10)
Location: mm/page_alloc.c:2265
Inline: False
Direct callers:
  - mm/page_alloc.c:zone_pcp_disable
  - mm/page_alloc.c:alloc_contig_range
```
**Symbols:**

```
ffffffff8141aa10-ffffffff8141abe1: __drain_all_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __drain_all_pages(struct zone *zone, bool force_all_cpus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81447c10)
Location: mm/page_alloc.c:2263
Inline: False
Direct callers:
  - mm/page_alloc.c:zone_pcp_disable
  - mm/page_alloc.c:alloc_contig_range
```
**Symbols:**

```
ffffffff81447c10-ffffffff81447de1: __drain_all_pages (STB_LOCAL)
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
