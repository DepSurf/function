# Function: <code>mapping_needs_writeback</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool mapping_needs_writeback(struct address_space *mapping);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811c9a00)
Location: mm/filemap.c:606
Inline: False
Direct callers:
  - mm/filemap.c:file_write_and_wait_range
```
**Symbols:**

```
ffffffff811c9a00-ffffffff811c9a2b: mapping_needs_writeback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool mapping_needs_writeback(struct address_space *mapping);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811eab60)
Location: mm/filemap.c:606
Inline: False
Direct callers:
  - mm/filemap.c:file_write_and_wait_range
```
**Symbols:**

```
ffffffff811eab60-ffffffff811eab8b: mapping_needs_writeback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool mapping_needs_writeback(struct address_space *mapping);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811fb6d0)
Location: mm/filemap.c:583
Inline: False
Direct callers:
  - mm/filemap.c:file_write_and_wait_range
```
**Symbols:**

```
ffffffff811fb6d0-ffffffff811fb6fb: mapping_needs_writeback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool mapping_needs_writeback(struct address_space *mapping);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81212d60)
Location: mm/filemap.c:620
Inline: False
Direct callers:
  - mm/filemap.c:file_write_and_wait_range
```
**Symbols:**

```
ffffffff81212d60-ffffffff81212d8b: mapping_needs_writeback (STB_LOCAL)
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
In mm/filemap.c (ffffffff8122684f)
Location: mm/filemap.c:627
Inline: True
Inline callers:
  - mm/filemap.c:file_write_and_wait_range
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff812517df)
Location: mm/filemap.c:627
Inline: True
Inline callers:
  - mm/filemap.c:file_write_and_wait_range
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8125ceff)
Location: mm/filemap.c:628
Inline: True
Inline callers:
  - mm/filemap.c:file_write_and_wait_range
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81261b7c)
Location: mm/filemap.c:619
Inline: True
Inline callers:
  - mm/filemap.c:file_write_and_wait_range
  - mm/filemap.c:filemap_range_needs_writeback
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8129b05f)
Location: mm/filemap.c:637
Inline: True
Inline callers:
  - mm/filemap.c:file_write_and_wait_range
  - mm/filemap.c:filemap_range_needs_writeback
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff812f58d9)
Location: mm/filemap.c:625
Inline: True
Inline callers:
  - mm/filemap.c:file_write_and_wait_range
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
In mm/filemap.c (ffffffff8135f790)
Location: mm/filemap.c:622
Inline: True
Inline callers:
  - mm/filemap.c:file_write_and_wait_range
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81390770)
Location: mm/filemap.c:629
Inline: True
Inline callers:
  - mm/filemap.c:file_write_and_wait_range
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff813ba3f0)
Location: mm/filemap.c:624
Inline: True
Inline callers:
  - mm/filemap.c:file_write_and_wait_range
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffff8000102b3b94)
Location: mm/filemap.c:627
Inline: True
Inline callers:
  - mm/filemap.c:file_write_and_wait_range
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (c04e0e50)
Location: mm/filemap.c:627
Inline: True
Inline callers:
  - mm/filemap.c:file_write_and_wait_range
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (c00000000036a990)
Location: mm/filemap.c:627
Inline: True
Inline callers:
  - mm/filemap.c:file_write_and_wait_range
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffe0001d9106)
Location: mm/filemap.c:627
Inline: True
Inline callers:
  - mm/filemap.c:file_write_and_wait_range
```
</details>
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
In mm/filemap.c (ffffffff8121ee9f)
Location: mm/filemap.c:627
Inline: True
Inline callers:
  - mm/filemap.c:file_write_and_wait_range
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
In mm/filemap.c (ffffffff8121205f)
Location: mm/filemap.c:627
Inline: True
Inline callers:
  - mm/filemap.c:file_write_and_wait_range
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
In mm/filemap.c (ffffffff8121cc3f)
Location: mm/filemap.c:627
Inline: True
Inline callers:
  - mm/filemap.c:file_write_and_wait_range
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
In mm/filemap.c (ffffffff8122bccf)
Location: mm/filemap.c:627
Inline: True
Inline callers:
  - mm/filemap.c:file_write_and_wait_range
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
</ul>
