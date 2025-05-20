# Function: <code>ext4_try_to_trim_range</code>

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
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int ext4_try_to_trim_range(struct super_block *sb, struct ext4_buddy *e4b, ext4_grpblk_t start, ext4_grpblk_t max, ext4_grpblk_t minblocks);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/mballoc.c (0)
Location: fs/ext4/mballoc.c:6298
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_discard_work
```
**Symbols:**

```
ffffffff81474170-ffffffff81474591: ext4_try_to_trim_range (STB_LOCAL)
ffffffff81ccbf07-ffffffff81ccc029: ext4_try_to_trim_range.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ext4_try_to_trim_range(struct super_block *sb, struct ext4_buddy *e4b, ext4_grpblk_t start, ext4_grpblk_t max, ext4_grpblk_t minblocks);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff814f6200)
Location: fs/ext4/mballoc.c:6385
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_discard_work
```
**Symbols:**

```
ffffffff814f6200-ffffffff814f65d4: ext4_try_to_trim_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ext4_try_to_trim_range(struct super_block *sb, struct ext4_buddy *e4b, ext4_grpblk_t start, ext4_grpblk_t max, ext4_grpblk_t minblocks);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff815905d0)
Location: fs/ext4/mballoc.c:6354
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_discard_work
```
**Symbols:**

```
ffffffff815905d0-ffffffff81590926: ext4_try_to_trim_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ext4_try_to_trim_range(struct super_block *sb, struct ext4_buddy *e4b, ext4_grpblk_t start, ext4_grpblk_t max, ext4_grpblk_t minblocks);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff815c7780)
Location: fs/ext4/mballoc.c:6930
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_discard_work
```
**Symbols:**

```
ffffffff815c7780-ffffffff815c7b40: ext4_try_to_trim_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int ext4_try_to_trim_range(struct super_block *sb, struct ext4_buddy *e4b, ext4_grpblk_t start, ext4_grpblk_t max, ext4_grpblk_t minblocks);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/mballoc.c (0)
Location: fs/ext4/mballoc.c:6767
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_discard_work
```
**Symbols:**

```
ffffffff815ff300-ffffffff815ff79b: ext4_try_to_trim_range (STB_LOCAL)
ffffffff821cc198-ffffffff821cc1cc: ext4_try_to_trim_range.cold (STB_LOCAL)
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
