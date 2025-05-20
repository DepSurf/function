# Function: <code>split_map_pages</code>

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
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void split_map_pages(struct list_head *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff812438e0)
Location: mm/compaction.c:69
Inline: False
Direct callers:
  - mm/compaction.c:compaction_alloc
  - mm/compaction.c:isolate_freepages_range
  - mm/compaction.c:isolate_freepages_range
```
**Symbols:**

```
ffffffff812438e0-ffffffff81243a19: split_map_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void split_map_pages(struct list_head *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff81251da0)
Location: mm/compaction.c:69
Inline: False
Direct callers:
  - mm/compaction.c:compaction_alloc
  - mm/compaction.c:isolate_freepages_range
  - mm/compaction.c:isolate_freepages_range
```
**Symbols:**

```
ffffffff81251da0-ffffffff81251ed9: split_map_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void split_map_pages(struct list_head *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff812807b0)
Location: mm/compaction.c:69
Inline: False
Direct callers:
  - mm/compaction.c:isolate_freepages
  - mm/compaction.c:isolate_freepages_range
  - mm/compaction.c:isolate_freepages_range
```
**Symbols:**

```
ffffffff812807b0-ffffffff812808ef: split_map_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void split_map_pages(struct list_head *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff8128a880)
Location: mm/compaction.c:87
Inline: False
Direct callers:
  - mm/compaction.c:isolate_freepages
  - mm/compaction.c:isolate_freepages_range
  - mm/compaction.c:isolate_freepages_range
```
**Symbols:**

```
ffffffff8128a880-ffffffff8128a9bf: split_map_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void split_map_pages(struct list_head *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff8128fed0)
Location: mm/compaction.c:87
Inline: False
Direct callers:
  - mm/compaction.c:isolate_freepages
  - mm/compaction.c:isolate_freepages_range
  - mm/compaction.c:isolate_freepages_range
```
**Symbols:**

```
ffffffff8128fed0-ffffffff81290013: split_map_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void split_map_pages(struct list_head *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/compaction.c (0)
Location: mm/compaction.c:87
Inline: False
Direct callers:
  - mm/compaction.c:isolate_freepages
  - mm/compaction.c:isolate_freepages_range
  - mm/compaction.c:isolate_freepages_range
```
**Symbols:**

```
ffffffff812cf960-ffffffff812cfab0: split_map_pages (STB_LOCAL)
ffffffff81cbb5b7-ffffffff81cbb5ef: split_map_pages.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void split_map_pages(struct list_head *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/compaction.c (0)
Location: mm/compaction.c:87
Inline: False
Direct callers:
  - mm/compaction.c:isolate_freepages
  - mm/compaction.c:isolate_freepages_range
  - mm/compaction.c:isolate_freepages_range
```
**Symbols:**

```
ffffffff8132e3a0-ffffffff8132e4f7: split_map_pages (STB_LOCAL)
ffffffff81e6d178-ffffffff81e6d1af: split_map_pages.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void split_map_pages(struct list_head *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/compaction.c (0)
Location: mm/compaction.c:85
Inline: False
Direct callers:
  - mm/compaction.c:isolate_freepages
  - mm/compaction.c:isolate_freepages_range
  - mm/compaction.c:isolate_freepages_range
```
**Symbols:**

```
ffffffff813a4b40-ffffffff813a4c97: split_map_pages (STB_LOCAL)
ffffffff820634d0-ffffffff82063507: split_map_pages.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void split_map_pages(struct list_head *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/compaction.c (0)
Location: mm/compaction.c:85
Inline: False
Direct callers:
  - mm/compaction.c:isolate_freepages
  - mm/compaction.c:isolate_freepages_range
  - mm/compaction.c:isolate_freepages_range
```
**Symbols:**

```
ffffffff813d6860-ffffffff813d69bd: split_map_pages (STB_LOCAL)
ffffffff820e2bc4-ffffffff820e2bed: split_map_pages.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void split_map_pages(struct list_head *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/compaction.c (0)
Location: mm/compaction.c:85
Inline: False
Direct callers:
  - mm/compaction.c:isolate_freepages
  - mm/compaction.c:isolate_freepages_range
  - mm/compaction.c:isolate_freepages_range
```
**Symbols:**

```
ffffffff81400540-ffffffff8140069d: split_map_pages (STB_LOCAL)
ffffffff821bf4ec-ffffffff821bf515: split_map_pages.cold (STB_LOCAL)
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
void split_map_pages(struct list_head *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffff8000102e8830)
Location: mm/compaction.c:69
Inline: False
Direct callers:
  - mm/compaction.c:compaction_alloc
  - mm/compaction.c:isolate_freepages_range
  - mm/compaction.c:isolate_freepages_range
```
**Symbols:**

```
ffff8000102e8830-ffff8000102e8998: split_map_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void split_map_pages(struct list_head *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (c050d5cc)
Location: mm/compaction.c:69
Inline: False
Direct callers:
  - mm/compaction.c:compaction_alloc
  - mm/compaction.c:isolate_freepages_range
  - mm/compaction.c:isolate_freepages_range
```
**Symbols:**

```
c050d5cc-c050d70c: split_map_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void split_map_pages(struct list_head *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (c0000000003aba20)
Location: mm/compaction.c:69
Inline: False
Direct callers:
  - mm/compaction.c:compaction_alloc
  - mm/compaction.c:isolate_freepages_range
  - mm/compaction.c:isolate_freepages_range
```
**Symbols:**

```
c0000000003aba20-c0000000003abc20: split_map_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void split_map_pages(struct list_head *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffe0001fe616)
Location: mm/compaction.c:69
Inline: False
Direct callers:
  - mm/compaction.c:compaction_alloc
  - mm/compaction.c:isolate_freepages_range
  - mm/compaction.c:isolate_freepages_range
```
**Symbols:**

```
ffffffe0001fe616-ffffffe0001fe71e: split_map_pages (STB_LOCAL)
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
void split_map_pages(struct list_head *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff8124a3f0)
Location: mm/compaction.c:69
Inline: False
Direct callers:
  - mm/compaction.c:compaction_alloc
  - mm/compaction.c:isolate_freepages_range
  - mm/compaction.c:isolate_freepages_range
```
**Symbols:**

```
ffffffff8124a3f0-ffffffff8124a529: split_map_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void split_map_pages(struct list_head *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff8123d3a0)
Location: mm/compaction.c:69
Inline: False
Direct callers:
  - mm/compaction.c:compaction_alloc
  - mm/compaction.c:isolate_freepages_range
  - mm/compaction.c:isolate_freepages_range
```
**Symbols:**

```
ffffffff8123d3a0-ffffffff8123d4d9: split_map_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void split_map_pages(struct list_head *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff81248190)
Location: mm/compaction.c:69
Inline: False
Direct callers:
  - mm/compaction.c:compaction_alloc
  - mm/compaction.c:isolate_freepages_range
  - mm/compaction.c:isolate_freepages_range
```
**Symbols:**

```
ffffffff81248190-ffffffff812482c9: split_map_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void split_map_pages(struct list_head *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff812579c0)
Location: mm/compaction.c:69
Inline: False
Direct callers:
  - mm/compaction.c:compaction_alloc
  - mm/compaction.c:isolate_freepages_range
  - mm/compaction.c:isolate_freepages_range
```
**Symbols:**

```
ffffffff812579c0-ffffffff81257af9: split_map_pages (STB_LOCAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
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
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
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
