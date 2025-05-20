# Function: <code>walk_page_mapping</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int walk_page_mapping(struct address_space *mapping, long unsigned int first_index, long unsigned int nr, const struct mm_walk_ops *ops, void *private);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pagewalk.c (ffffffff812a3240)
Location: mm/pagewalk.c:515
Inline: False
Direct callers:
  - mm/mapping_dirty_helpers.c:clean_record_shared_mapping_range
  - mm/mapping_dirty_helpers.c:wp_shared_mapping_range
```
**Symbols:**

```
ffffffff812a3240-ffffffff812a336e: walk_page_mapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int walk_page_mapping(struct address_space *mapping, long unsigned int first_index, long unsigned int nr, const struct mm_walk_ops *ops, void *private);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pagewalk.c (ffffffff812aeb60)
Location: mm/pagewalk.c:515
Inline: False
Direct callers:
  - mm/mapping_dirty_helpers.c:clean_record_shared_mapping_range
  - mm/mapping_dirty_helpers.c:wp_shared_mapping_range
```
**Symbols:**

```
ffffffff812aeb60-ffffffff812aec8e: walk_page_mapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int walk_page_mapping(struct address_space *mapping, long unsigned int first_index, long unsigned int nr, const struct mm_walk_ops *ops, void *private);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pagewalk.c (ffffffff812b3fe0)
Location: mm/pagewalk.c:515
Inline: False
Direct callers:
  - mm/mapping_dirty_helpers.c:clean_record_shared_mapping_range
  - mm/mapping_dirty_helpers.c:wp_shared_mapping_range
```
**Symbols:**

```
ffffffff812b3fe0-ffffffff812b410b: walk_page_mapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int walk_page_mapping(struct address_space *mapping, long unsigned int first_index, long unsigned int nr, const struct mm_walk_ops *ops, void *private);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pagewalk.c (ffffffff812f5bc0)
Location: mm/pagewalk.c:563
Inline: False
Direct callers:
  - mm/mapping_dirty_helpers.c:clean_record_shared_mapping_range
  - mm/mapping_dirty_helpers.c:wp_shared_mapping_range
```
**Symbols:**

```
ffffffff812f5bc0-ffffffff812f5ceb: walk_page_mapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int walk_page_mapping(struct address_space *mapping, long unsigned int first_index, long unsigned int nr, const struct mm_walk_ops *ops, void *private);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pagewalk.c (ffffffff81359ae0)
Location: mm/pagewalk.c:563
Inline: False
Direct callers:
  - mm/mapping_dirty_helpers.c:clean_record_shared_mapping_range
  - mm/mapping_dirty_helpers.c:wp_shared_mapping_range
```
**Symbols:**

```
ffffffff81359ae0-ffffffff81359c1b: walk_page_mapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int walk_page_mapping(struct address_space *mapping, long unsigned int first_index, long unsigned int nr, const struct mm_walk_ops *ops, void *private);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pagewalk.c (ffffffff813d44a0)
Location: mm/pagewalk.c:587
Inline: False
Direct callers:
  - mm/mapping_dirty_helpers.c:clean_record_shared_mapping_range
  - mm/mapping_dirty_helpers.c:wp_shared_mapping_range
```
**Symbols:**

```
ffffffff813d44a0-ffffffff813d45d8: walk_page_mapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int walk_page_mapping(struct address_space *mapping, long unsigned int first_index, long unsigned int nr, const struct mm_walk_ops *ops, void *private);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pagewalk.c (ffffffff81408f40)
Location: mm/pagewalk.c:633
Inline: False
Direct callers:
  - mm/mapping_dirty_helpers.c:clean_record_shared_mapping_range
  - mm/mapping_dirty_helpers.c:wp_shared_mapping_range
```
**Symbols:**

```
ffffffff81408f40-ffffffff8140907b: walk_page_mapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int walk_page_mapping(struct address_space *mapping, long unsigned int first_index, long unsigned int nr, const struct mm_walk_ops *ops, void *private);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pagewalk.c (ffffffff81435660)
Location: mm/pagewalk.c:660
Inline: False
Direct callers:
  - mm/mapping_dirty_helpers.c:clean_record_shared_mapping_range
  - mm/mapping_dirty_helpers.c:wp_shared_mapping_range
```
**Symbols:**

```
ffffffff81435660-ffffffff8143579b: walk_page_mapping (STB_GLOBAL)
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
