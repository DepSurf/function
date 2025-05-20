# Function: <code>try_to_writeback_inodes_sb_nr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
bool try_to_writeback_inodes_sb_nr(struct super_block *sb, long unsigned int nr, enum wb_reason reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff81239cf0)
Location: fs/fs-writeback.c:2268
Inline: False
Direct callers:
  - fs/fs-writeback.c:try_to_writeback_inodes_sb
```
**Symbols:**

```
ffffffff81239cf0-ffffffff81239d46: try_to_writeback_inodes_sb_nr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool try_to_writeback_inodes_sb_nr(struct super_block *sb, long unsigned int nr, enum wb_reason reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff81261cb0)
Location: fs/fs-writeback.c:2347
Inline: False
Direct callers:
  - fs/fs-writeback.c:try_to_writeback_inodes_sb
```
**Symbols:**

```
ffffffff81261cb0-ffffffff81261d06: try_to_writeback_inodes_sb_nr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool try_to_writeback_inodes_sb_nr(struct super_block *sb, long unsigned int nr, enum wb_reason reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff812751b0)
Location: fs/fs-writeback.c:2345
Inline: False
Direct callers:
  - fs/fs-writeback.c:try_to_writeback_inodes_sb
```
**Symbols:**

```
ffffffff812751b0-ffffffff81275206: try_to_writeback_inodes_sb_nr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool try_to_writeback_inodes_sb_nr(struct super_block *sb, long unsigned int nr, enum wb_reason reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff81282700)
Location: fs/fs-writeback.c:2354
Inline: False
Direct callers:
  - fs/fs-writeback.c:try_to_writeback_inodes_sb
```
**Symbols:**

```
ffffffff81282700-ffffffff81282756: try_to_writeback_inodes_sb_nr (STB_GLOBAL)
```
</details>
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
</ul>
