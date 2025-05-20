# Function: <code>invalidate_complete_page2</code>

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
In mm/truncate.c (ffffffff8119e804)
Location: mm/truncate.c:511
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff811b42e9)
Location: mm/truncate.c:536
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff811c4959)
Location: mm/truncate.c:566
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff811ccfac)
Location: mm/truncate.c:571
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
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
In mm/truncate.c (ffffffff811e1fad)
Location: mm/truncate.c:624
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
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
In mm/truncate.c (ffffffff812039f8)
Location: mm/truncate.c:620
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
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
In mm/truncate.c (ffffffff812162eb)
Location: mm/truncate.c:621
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
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
In mm/truncate.c (ffffffff81225cbf)
Location: mm/truncate.c:624
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
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
In mm/truncate.c (ffffffff81233b1e)
Location: mm/truncate.c:636
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int invalidate_complete_page2(struct address_space *mapping, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff81260d80)
Location: mm/truncate.c:636
Inline: False
Direct callers:
  - mm/truncate.c:invalidate_inode_pages2_range
```
**Symbols:**

```
ffffffff81260d80-ffffffff81260e9e: invalidate_complete_page2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int invalidate_complete_page2(struct address_space *mapping, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff8126b180)
Location: mm/truncate.c:664
Inline: False
Direct callers:
  - mm/truncate.c:invalidate_inode_pages2_range
```
**Symbols:**

```
ffffffff8126b180-ffffffff8126b29b: invalidate_complete_page2 (STB_LOCAL)
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
In mm/truncate.c (ffffffff81270622)
Location: mm/truncate.c:561
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
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
In mm/truncate.c (ffffffff812ae2ad)
Location: mm/truncate.c:562
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
```
</details>
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
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffff8000102c3fc8)
Location: mm/truncate.c:636
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
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
In mm/truncate.c (c04eea78)
Location: mm/truncate.c:636
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
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
In mm/truncate.c (c00000000037e520)
Location: mm/truncate.c:636
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
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
In mm/truncate.c (ffffffe0001e48f4)
Location: mm/truncate.c:636
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
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
In mm/truncate.c (ffffffff8122c16e)
Location: mm/truncate.c:636
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
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
In mm/truncate.c (ffffffff8121f248)
Location: mm/truncate.c:636
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
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
In mm/truncate.c (ffffffff81229f0e)
Location: mm/truncate.c:636
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
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
In mm/truncate.c (ffffffff812392fb)
Location: mm/truncate.c:636
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
