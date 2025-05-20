# Function: <code>ext4_print_free_blocks</code>

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
In fs/ext4/inode.c (ffffffff8129c634)
Location: fs/ext4/inode.c:1505
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_writepages
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
In fs/ext4/inode.c (ffffffff812c9ff3)
Location: fs/ext4/inode.c:1662
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_writepages
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
In fs/ext4/inode.c (ffffffff812dfcbf)
Location: fs/ext4/inode.c:1691
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_writepages
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
In fs/ext4/inode.c (ffffffff81303c72)
Location: fs/ext4/inode.c:1745
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_writepages
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
In fs/ext4/inode.c (ffffffff8132866d)
Location: fs/ext4/inode.c:1753
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_writepages
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
In fs/ext4/inode.c (ffffffff813566d6)
Location: fs/ext4/inode.c:1756
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_writepages
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
In fs/ext4/inode.c (ffffffff8136e9fc)
Location: fs/ext4/inode.c:1741
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_writepages
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
In fs/ext4/inode.c (ffffffff813974d4)
Location: fs/ext4/inode.c:1757
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_map_and_submit_extent
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
In fs/ext4/inode.c (ffffffff813aff07)
Location: fs/ext4/inode.c:1733
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_map_and_submit_extent
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void ext4_print_free_blocks(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813f54c0)
Location: fs/ext4/inode.c:1584
Inline: False
Direct callers:
  - fs/ext4/inode.c:mpage_map_and_submit_extent
```
**Symbols:**

```
ffffffff813f54c0-ffffffff813f55c4: ext4_print_free_blocks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ext4_print_free_blocks(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81407c60)
Location: fs/ext4/inode.c:1601
Inline: False
Direct callers:
  - fs/ext4/inode.c:mpage_map_and_submit_extent
```
**Symbols:**

```
ffffffff81407c60-ffffffff81407d64: ext4_print_free_blocks (STB_LOCAL)
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
In fs/ext4/inode.c (ffffffff814147ff)
Location: fs/ext4/inode.c:1600
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_map_and_submit_extent
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
In fs/ext4/inode.c (ffffffff81467b92)
Location: fs/ext4/inode.c:1588
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_map_and_submit_extent
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
In fs/ext4/inode.c (ffffffff814e7863)
Location: fs/ext4/inode.c:1610
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_map_and_submit_extent
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
In fs/ext4/inode.c (ffffffff81581bf3)
Location: fs/ext4/inode.c:1630
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_map_and_submit_extent
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
In fs/ext4/inode.c (ffffffff815b87e3)
Location: fs/ext4/inode.c:1589
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_map_and_submit_extent
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
In fs/ext4/inode.c (ffffffff815f1570)
Location: fs/ext4/inode.c:1601
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_map_and_submit_extent
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
In fs/ext4/inode.c (ffff8000104849f0)
Location: fs/ext4/inode.c:1733
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_map_and_submit_extent
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
In fs/ext4/inode.c (c0646284)
Location: fs/ext4/inode.c:1733
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_map_and_submit_extent
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
In fs/ext4/inode.c (c0000000005aa654)
Location: fs/ext4/inode.c:1733
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_writepages
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
In fs/ext4/inode.c (ffffffe00030cd46)
Location: fs/ext4/inode.c:1733
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_map_and_submit_extent
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
In fs/ext4/inode.c (ffffffff813a84e7)
Location: fs/ext4/inode.c:1733
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_map_and_submit_extent
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
In fs/ext4/inode.c (ffffffff81398f77)
Location: fs/ext4/inode.c:1733
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_map_and_submit_extent
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
In fs/ext4/inode.c (ffffffff813a5d47)
Location: fs/ext4/inode.c:1733
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_map_and_submit_extent
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
In fs/ext4/inode.c (ffffffff813ba4c0)
Location: fs/ext4/inode.c:1733
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_map_and_submit_extent
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
