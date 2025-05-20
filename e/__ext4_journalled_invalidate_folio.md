# Function: <code>__ext4_journalled_invalidate_folio</code>

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
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int __ext4_journalled_invalidate_folio(struct folio *folio, size_t offset, size_t length);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/inode.c (0)
Location: fs/ext4/inode.c:3248
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_wait_for_tail_page_commit
  - fs/ext4/inode.c:ext4_journalled_invalidate_folio
```
**Symbols:**

```
ffffffff814e0ae0-ffffffff814e0bf5: __ext4_journalled_invalidate_folio (STB_LOCAL)
ffffffff81e7d697-ffffffff81e7d6b1: __ext4_journalled_invalidate_folio.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int __ext4_journalled_invalidate_folio(struct folio *folio, size_t offset, size_t length);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/inode.c (0)
Location: fs/ext4/inode.c:3336
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_wait_for_tail_page_commit
  - fs/ext4/inode.c:ext4_journalled_invalidate_folio
```
**Symbols:**

```
ffffffff8157a0e0-ffffffff8157a1c8: __ext4_journalled_invalidate_folio (STB_LOCAL)
ffffffff8206dcb6-ffffffff8206dcd0: __ext4_journalled_invalidate_folio.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int __ext4_journalled_invalidate_folio(struct folio *folio, size_t offset, size_t length);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/inode.c (0)
Location: fs/ext4/inode.c:3118
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_wait_for_tail_page_commit
  - fs/ext4/inode.c:ext4_journalled_invalidate_folio
```
**Symbols:**

```
ffffffff815b1c80-ffffffff815b1d5a: __ext4_journalled_invalidate_folio (STB_LOCAL)
ffffffff820ed9dd-ffffffff820ed9f8: __ext4_journalled_invalidate_folio.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int __ext4_journalled_invalidate_folio(struct folio *folio, size_t offset, size_t length);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/inode.c (0)
Location: fs/ext4/inode.c:3157
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_wait_for_tail_page_commit
  - fs/ext4/inode.c:ext4_journalled_invalidate_folio
```
**Symbols:**

```
ffffffff815eaaa0-ffffffff815eab81: __ext4_journalled_invalidate_folio (STB_LOCAL)
ffffffff821cab10-ffffffff821cab28: __ext4_journalled_invalidate_folio.cold (STB_LOCAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
