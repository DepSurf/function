# Function: <code>read_file_data_page</code>

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
struct page *read_file_data_page(struct file *filp, long unsigned int index, struct file_ra_state *ra, long unsigned int remaining_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/enable.c (ffffffff81395bf0)
Location: fs/verity/enable.c:21
Inline: False
Direct callers:
  - fs/verity/enable.c:build_merkle_tree_level
```
**Symbols:**

```
ffffffff81395bf0-ffffffff81395d2e: read_file_data_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct page *read_file_data_page(struct file *filp, long unsigned int index, struct file_ra_state *ra, long unsigned int remaining_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/enable.c (ffffffff813a78d0)
Location: fs/verity/enable.c:21
Inline: False
Direct callers:
  - fs/verity/enable.c:build_merkle_tree_level
```
**Symbols:**

```
ffffffff813a78d0-ffffffff813a7a4b: read_file_data_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct page *read_file_data_page(struct file *filp, long unsigned int index, struct file_ra_state *ra, long unsigned int remaining_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/enable.c (ffffffff813ae920)
Location: fs/verity/enable.c:21
Inline: False
Direct callers:
  - fs/verity/enable.c:build_merkle_tree_level
```
**Symbols:**

```
ffffffff813ae920-ffffffff813aeaa5: read_file_data_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct page *read_file_data_page(struct file *filp, long unsigned int index, struct file_ra_state *ra, long unsigned int remaining_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/enable.c (ffffffff813fe4c0)
Location: fs/verity/enable.c:21
Inline: False
Direct callers:
  - fs/verity/enable.c:build_merkle_tree_level
```
**Symbols:**

```
ffffffff813fe4c0-ffffffff813fe642: read_file_data_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct page *read_file_data_page(struct file *file, long unsigned int index, struct file_ra_state *ra, long unsigned int remaining_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/enable.c (ffffffff81471ff0)
Location: fs/verity/enable.c:21
Inline: False
Direct callers:
  - fs/verity/enable.c:build_merkle_tree_level
```
**Symbols:**

```
ffffffff81471ff0-ffffffff8147215c: read_file_data_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/verity/enable.c (ffffffff8150403a)
Location: fs/verity/enable.c:21
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree_level
```
</details>
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct file *file</code>
</li>
<li>
<b>Param removed. </b>
<code>struct file *filp</code>
</li>
</ul>
</details>
</li>
</ul>
