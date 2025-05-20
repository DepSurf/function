# Function: <code>shmem_radix_tree_replace</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int shmem_radix_tree_replace(struct address_space *mapping, long unsigned int index, void *expected, void *replacement);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811a7d80)
Location: mm/shmem.c:259
Inline: True
Direct callers:
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_add_to_page_cache
```
**Symbols:**

```
ffffffff811a7d80-ffffffff811a7dc3: shmem_radix_tree_replace (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int shmem_radix_tree_replace(struct address_space *mapping, long unsigned int index, void *expected, void *replacement);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811be200)
Location: mm/shmem.c:304
Inline: True
Direct callers:
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_add_to_page_cache
```
**Symbols:**

```
ffffffff811be200-ffffffff811be247: shmem_radix_tree_replace (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int shmem_radix_tree_replace(struct address_space *mapping, long unsigned int index, void *expected, void *replacement);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811cd520)
Location: mm/shmem.c:300
Inline: False
Direct callers:
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_add_to_page_cache
```
**Symbols:**

```
ffffffff811cd520-ffffffff811cd5a6: shmem_radix_tree_replace (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int shmem_radix_tree_replace(struct address_space *mapping, long unsigned int index, void *expected, void *replacement);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811d6440)
Location: mm/shmem.c:316
Inline: False
Direct callers:
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_add_to_page_cache
```
**Symbols:**

```
ffffffff811d6440-ffffffff811d64c6: shmem_radix_tree_replace (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int shmem_radix_tree_replace(struct address_space *mapping, long unsigned int index, void *expected, void *replacement);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811eb960)
Location: mm/shmem.c:330
Inline: False
Direct callers:
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_add_to_page_cache
```
**Symbols:**

```
ffffffff811eb960-ffffffff811eb9e3: shmem_radix_tree_replace (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int shmem_radix_tree_replace(struct address_space *mapping, long unsigned int index, void *expected, void *replacement);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8120d0f0)
Location: mm/shmem.c:330
Inline: False
Direct callers:
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_add_to_page_cache
```
**Symbols:**

```
ffffffff8120d0f0-ffffffff8120d173: shmem_radix_tree_replace (STB_LOCAL)
```
</details>
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
</ul>
