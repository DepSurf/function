# Function: <code>memory_bm_clear_bit</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void memory_bm_clear_bit(struct memory_bitmap *bm, long unsigned int pfn);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff810d03d0)
Location: kernel/power/snapshot.c:718
Inline: True
Direct callers:
  - kernel/power/snapshot.c:free_zone_bm_rtree
  - kernel/power/snapshot.c:free_zone_bm_rtree
  - kernel/power/snapshot.c:free_zone_bm_rtree
  - kernel/power/snapshot.c:free_zone_bm_rtree
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_write_next
```
**Symbols:**

```
ffffffff810d03d0-ffffffff810d0421: memory_bm_clear_bit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void memory_bm_clear_bit(struct memory_bitmap *bm, long unsigned int pfn);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff810d4f60)
Location: kernel/power/snapshot.c:788
Inline: True
Direct callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:free_zone_bm_rtree
  - kernel/power/snapshot.c:free_zone_bm_rtree
  - kernel/power/snapshot.c:free_zone_bm_rtree
  - kernel/power/snapshot.c:free_zone_bm_rtree
```
**Symbols:**

```
ffffffff810d4f60-ffffffff810d4fb1: memory_bm_clear_bit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void memory_bm_clear_bit(struct memory_bitmap *bm, long unsigned int pfn);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff810dbb00)
Location: kernel/power/snapshot.c:788
Inline: True
Direct callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:free_zone_bm_rtree
  - kernel/power/snapshot.c:free_zone_bm_rtree
  - kernel/power/snapshot.c:free_zone_bm_rtree
  - kernel/power/snapshot.c:free_zone_bm_rtree
```
**Symbols:**

```
ffffffff810dbb00-ffffffff810dbb51: memory_bm_clear_bit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void memory_bm_clear_bit(struct memory_bitmap *bm, long unsigned int pfn);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff810db060)
Location: kernel/power/snapshot.c:790
Inline: True
Direct callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:free_zone_bm_rtree
  - kernel/power/snapshot.c:free_zone_bm_rtree
  - kernel/power/snapshot.c:free_zone_bm_rtree
  - kernel/power/snapshot.c:free_zone_bm_rtree
```
**Symbols:**

```
ffffffff810db060-ffffffff810db0b1: memory_bm_clear_bit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void memory_bm_clear_bit(struct memory_bitmap *bm, long unsigned int pfn);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff810e30d0)
Location: kernel/power/snapshot.c:792
Inline: True
Direct callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:free_zone_bm_rtree
  - kernel/power/snapshot.c:free_zone_bm_rtree
  - kernel/power/snapshot.c:free_zone_bm_rtree
  - kernel/power/snapshot.c:free_zone_bm_rtree
```
**Symbols:**

```
ffffffff810e30d0-ffffffff810e3121: memory_bm_clear_bit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void memory_bm_clear_bit(struct memory_bitmap *bm, long unsigned int pfn);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff810eb590)
Location: kernel/power/snapshot.c:792
Inline: True
Direct callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:free_zone_bm_rtree
  - kernel/power/snapshot.c:free_zone_bm_rtree
  - kernel/power/snapshot.c:free_zone_bm_rtree
  - kernel/power/snapshot.c:free_zone_bm_rtree
```
**Symbols:**

```
ffffffff810eb590-ffffffff810eb5e1: memory_bm_clear_bit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void memory_bm_clear_bit(struct memory_bitmap *bm, long unsigned int pfn);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff810f6c10)
Location: kernel/power/snapshot.c:792
Inline: True
Direct callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:free_zone_bm_rtree
  - kernel/power/snapshot.c:free_zone_bm_rtree
  - kernel/power/snapshot.c:free_zone_bm_rtree
  - kernel/power/snapshot.c:free_zone_bm_rtree
```
**Symbols:**

```
ffffffff810f6c10-ffffffff810f6c61: memory_bm_clear_bit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void memory_bm_clear_bit(struct memory_bitmap *bm, long unsigned int pfn);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff810ff150)
Location: kernel/power/snapshot.c:790
Inline: True
Direct callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:free_zone_bm_rtree
  - kernel/power/snapshot.c:free_zone_bm_rtree
  - kernel/power/snapshot.c:free_zone_bm_rtree
  - kernel/power/snapshot.c:free_zone_bm_rtree
```
**Symbols:**

```
ffffffff810ff150-ffffffff810ff1a1: memory_bm_clear_bit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void memory_bm_clear_bit(struct memory_bitmap *bm, long unsigned int pfn);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff8110b5b0)
Location: kernel/power/snapshot.c:797
Inline: True
Direct callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:free_zone_bm_rtree
  - kernel/power/snapshot.c:free_zone_bm_rtree
  - kernel/power/snapshot.c:free_zone_bm_rtree
  - kernel/power/snapshot.c:free_zone_bm_rtree
```
**Symbols:**

```
ffffffff8110b5b0-ffffffff8110b601: memory_bm_clear_bit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void memory_bm_clear_bit(struct memory_bitmap *bm, long unsigned int pfn);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff81115f40)
Location: kernel/power/snapshot.c:796
Inline: True
Direct callers:
  - kernel/power/snapshot.c:free_unnecessary_pages
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:memory_bm_create
  - kernel/power/snapshot.c:memory_bm_create
  - kernel/power/snapshot.c:memory_bm_create
  - kernel/power/snapshot.c:memory_bm_create
```
**Symbols:**

```
ffffffff81115f40-ffffffff81115f91: memory_bm_clear_bit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void memory_bm_clear_bit(struct memory_bitmap *bm, long unsigned int pfn);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff811123c0)
Location: kernel/power/snapshot.c:830
Inline: True
Direct callers:
  - kernel/power/snapshot.c:free_unnecessary_pages
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:memory_bm_create
  - kernel/power/snapshot.c:memory_bm_create
  - kernel/power/snapshot.c:memory_bm_create
  - kernel/power/snapshot.c:memory_bm_create
```
**Symbols:**

```
ffffffff811123c0-ffffffff81112411: memory_bm_clear_bit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void memory_bm_clear_bit(struct memory_bitmap *bm, long unsigned int pfn);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff81112cf0)
Location: kernel/power/snapshot.c:830
Inline: True
Direct callers:
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:create_zone_bm_rtree
  - kernel/power/snapshot.c:create_zone_bm_rtree
  - kernel/power/snapshot.c:create_zone_bm_rtree
  - kernel/power/snapshot.c:create_zone_bm_rtree
```
**Symbols:**

```
ffffffff81112cf0-ffffffff81112d41: memory_bm_clear_bit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void memory_bm_clear_bit(struct memory_bitmap *bm, long unsigned int pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff81132cf0)
Location: kernel/power/snapshot.c:830
Inline: False
Direct callers:
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:memory_bm_create
  - kernel/power/snapshot.c:memory_bm_create
  - kernel/power/snapshot.c:memory_bm_create
  - kernel/power/snapshot.c:memory_bm_create
```
**Symbols:**

```
ffffffff81132cf0-ffffffff81132d41: memory_bm_clear_bit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void memory_bm_clear_bit(struct memory_bitmap *bm, long unsigned int pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff81154d50)
Location: kernel/power/snapshot.c:834
Inline: False
Direct callers:
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:memory_bm_create
  - kernel/power/snapshot.c:memory_bm_create
  - kernel/power/snapshot.c:memory_bm_create
  - kernel/power/snapshot.c:memory_bm_create
```
**Symbols:**

```
ffffffff81154d50-ffffffff81154dbe: memory_bm_clear_bit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void memory_bm_clear_bit(struct memory_bitmap *bm, long unsigned int pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff81184bf0)
Location: kernel/power/snapshot.c:834
Inline: False
Direct callers:
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:memory_bm_create
  - kernel/power/snapshot.c:memory_bm_create
  - kernel/power/snapshot.c:memory_bm_create
  - kernel/power/snapshot.c:memory_bm_create
```
**Symbols:**

```
ffffffff81184bf0-ffffffff81184c5e: memory_bm_clear_bit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void memory_bm_clear_bit(struct memory_bitmap *bm, long unsigned int pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff81195950)
Location: kernel/power/snapshot.c:834
Inline: False
Direct callers:
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:memory_bm_create
  - kernel/power/snapshot.c:memory_bm_create
  - kernel/power/snapshot.c:memory_bm_create
  - kernel/power/snapshot.c:memory_bm_create
```
**Symbols:**

```
ffffffff81195950-ffffffff811959be: memory_bm_clear_bit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void memory_bm_clear_bit(struct memory_bitmap *bm, long unsigned int pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff811a4330)
Location: kernel/power/snapshot.c:837
Inline: False
Direct callers:
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:memory_bm_create
  - kernel/power/snapshot.c:memory_bm_create
  - kernel/power/snapshot.c:memory_bm_create
  - kernel/power/snapshot.c:memory_bm_create
```
**Symbols:**

```
ffffffff811a4330-ffffffff811a439e: memory_bm_clear_bit (STB_LOCAL)
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
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void memory_bm_clear_bit(struct memory_bitmap *bm, long unsigned int pfn);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (c03bdc1c)
Location: kernel/power/snapshot.c:797
Inline: True
Direct callers:
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:swsusp_unset_page_forbidden
  - kernel/power/snapshot.c:swsusp_unset_page_free
```
**Symbols:**

```
c03bdc1c-c03bdc90: memory_bm_clear_bit (STB_LOCAL)
```
</details>
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
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void memory_bm_clear_bit(struct memory_bitmap *bm, long unsigned int pfn);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff811037d0)
Location: kernel/power/snapshot.c:796
Inline: True
Direct callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:free_zone_bm_rtree
  - kernel/power/snapshot.c:free_zone_bm_rtree
  - kernel/power/snapshot.c:free_zone_bm_rtree
  - kernel/power/snapshot.c:free_zone_bm_rtree
```
**Symbols:**

```
ffffffff811037d0-ffffffff81103821: memory_bm_clear_bit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void memory_bm_clear_bit(struct memory_bitmap *bm, long unsigned int pfn);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff810f4a70)
Location: kernel/power/snapshot.c:797
Inline: True
Direct callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:free_zone_bm_rtree
  - kernel/power/snapshot.c:free_zone_bm_rtree
  - kernel/power/snapshot.c:free_zone_bm_rtree
  - kernel/power/snapshot.c:free_zone_bm_rtree
```
**Symbols:**

```
ffffffff810f4a70-ffffffff810f4ac1: memory_bm_clear_bit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void memory_bm_clear_bit(struct memory_bitmap *bm, long unsigned int pfn);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff81101a80)
Location: kernel/power/snapshot.c:797
Inline: True
Direct callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:free_zone_bm_rtree
  - kernel/power/snapshot.c:free_zone_bm_rtree
  - kernel/power/snapshot.c:free_zone_bm_rtree
  - kernel/power/snapshot.c:free_zone_bm_rtree
```
**Symbols:**

```
ffffffff81101a80-ffffffff81101ad1: memory_bm_clear_bit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void memory_bm_clear_bit(struct memory_bitmap *bm, long unsigned int pfn);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff8110ce50)
Location: kernel/power/snapshot.c:797
Inline: True
Direct callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:free_zone_bm_rtree
  - kernel/power/snapshot.c:free_zone_bm_rtree
  - kernel/power/snapshot.c:free_zone_bm_rtree
  - kernel/power/snapshot.c:free_zone_bm_rtree
```
**Symbols:**

```
ffffffff8110ce50-ffffffff8110cea1: memory_bm_clear_bit (STB_LOCAL)
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
No changes between <code>amd64</code> and <code>armhf</code> ✅
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
