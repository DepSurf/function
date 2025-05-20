# Function: <code>map_pages</code>

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
In mm/compaction.c (ffffffff811b5c94)
Location: mm/compaction.c:58
Inline: True
Inline callers:
  - mm/compaction.c:compaction_alloc
  - mm/compaction.c:isolate_freepages_range
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void map_pages(struct list_head *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff811cefc0)
Location: mm/compaction.c:66
Inline: False
Direct callers:
  - mm/compaction.c:compaction_alloc
  - mm/compaction.c:isolate_freepages_range
  - mm/compaction.c:isolate_freepages_range
```
**Symbols:**

```
ffffffff811cefc0-ffffffff811cf0fe: map_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void map_pages(struct list_head *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff811df0f0)
Location: mm/compaction.c:66
Inline: False
Direct callers:
  - mm/compaction.c:compaction_alloc
  - mm/compaction.c:isolate_freepages_range
  - mm/compaction.c:isolate_freepages_range
```
**Symbols:**

```
ffffffff811df0f0-ffffffff811df22e: map_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void map_pages(struct list_head *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff811e8d80)
Location: mm/compaction.c:67
Inline: False
Direct callers:
  - mm/compaction.c:compaction_alloc
  - mm/compaction.c:isolate_freepages_range
  - mm/compaction.c:isolate_freepages_range
```
**Symbols:**

```
ffffffff811e8d80-ffffffff811e8eb6: map_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void map_pages(struct list_head *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff811ff0e0)
Location: mm/compaction.c:68
Inline: False
Direct callers:
  - mm/compaction.c:compaction_alloc
  - mm/compaction.c:isolate_freepages_range
  - mm/compaction.c:isolate_freepages_range
```
**Symbols:**

```
ffffffff811ff0e0-ffffffff811ff216: map_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void map_pages(struct list_head *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff812204f0)
Location: mm/compaction.c:68
Inline: False
Direct callers:
  - mm/compaction.c:compaction_alloc
  - mm/compaction.c:isolate_freepages_range
  - mm/compaction.c:isolate_freepages_range
```
**Symbols:**

```
ffffffff812204f0-ffffffff8122062a: map_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void map_pages(struct list_head *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff81233530)
Location: mm/compaction.c:69
Inline: False
Direct callers:
  - mm/compaction.c:compaction_alloc
  - mm/compaction.c:isolate_freepages_range
  - mm/compaction.c:isolate_freepages_range
```
**Symbols:**

```
ffffffff81233530-ffffffff8123366a: map_pages (STB_LOCAL)
```
</details>
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
</ul>
