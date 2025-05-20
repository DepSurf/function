# Function: <code>clear_shadow_entry</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void clear_shadow_entry(struct address_space *mapping, long unsigned int index, void *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff811c4700)
Location: mm/truncate.c:27
Inline: False
Direct callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
```
**Symbols:**

```
ffffffff811c4700-ffffffff811c47b4: clear_shadow_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void clear_shadow_entry(struct address_space *mapping, long unsigned int index, void *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff811ccb50)
Location: mm/truncate.c:28
Inline: False
Direct callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
```
**Symbols:**

```
ffffffff811ccb50-ffffffff811ccc04: clear_shadow_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff811e2193)
Location: mm/truncate.c:48
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff8120393b)
Location: mm/truncate.c:48
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff8121620b)
Location: mm/truncate.c:45
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff81225ba7)
Location: mm/truncate.c:46
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
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
In mm/truncate.c (ffffffff812339f7)
Location: mm/truncate.c:46
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
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
In mm/truncate.c (ffffffff8126117f)
Location: mm/truncate.c:46
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
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
In mm/truncate.c (ffffffff8126b57d)
Location: mm/truncate.c:46
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:__invalidate_mapping_pages
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
In mm/truncate.c (ffffffff812706cd)
Location: mm/truncate.c:45
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:__invalidate_mapping_pages
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
In mm/truncate.c (ffffffff812ae355)
Location: mm/truncate.c:45
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:__invalidate_mapping_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void clear_shadow_entry(struct address_space *mapping, long unsigned int index, void *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff81307420)
Location: mm/truncate.c:43
Inline: False
Direct callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pagevec
```
**Symbols:**

```
ffffffff81307420-ffffffff8130751f: clear_shadow_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void clear_shadow_entry(struct address_space *mapping, long unsigned int index, void *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff81371530)
Location: mm/truncate.c:43
Inline: False
Direct callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pagevec
```
**Symbols:**

```
ffffffff81371530-ffffffff8137162f: clear_shadow_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void clear_shadow_entry(struct address_space *mapping, long unsigned int index, void *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff813a3640)
Location: mm/truncate.c:43
Inline: False
Direct callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:mapping_try_invalidate
```
**Symbols:**

```
ffffffff813a3640-ffffffff813a373f: clear_shadow_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void clear_shadow_entry(struct address_space *mapping, long unsigned int index, void *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff813cd1e0)
Location: mm/truncate.c:42
Inline: False
Direct callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:mapping_try_invalidate
```
**Symbols:**

```
ffffffff813cd1e0-ffffffff813cd2df: clear_shadow_entry (STB_LOCAL)
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
In mm/truncate.c (ffff8000102c3f14)
Location: mm/truncate.c:46
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void clear_shadow_entry(struct address_space *mapping, long unsigned int index, void *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (c04ee438)
Location: mm/truncate.c:46
Inline: False
Direct callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
```
**Symbols:**

```
c04ee438-c04ee510: clear_shadow_entry (STB_LOCAL)
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
In mm/truncate.c (c00000000037e450)
Location: mm/truncate.c:46
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
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
In mm/truncate.c (ffffffe0001e4912)
Location: mm/truncate.c:46
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
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
In mm/truncate.c (ffffffff8122c047)
Location: mm/truncate.c:46
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
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
In mm/truncate.c (ffffffff8121f127)
Location: mm/truncate.c:46
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
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
In mm/truncate.c (ffffffff81229de7)
Location: mm/truncate.c:46
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
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
In mm/truncate.c (ffffffff812391dd)
Location: mm/truncate.c:46
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
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
</ul>
