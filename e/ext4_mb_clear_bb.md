# Function: <code>ext4_mb_clear_bb</code>

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
void ext4_mb_clear_bb(handle_t *handle, struct inode *inode, ext4_fsblk_t block, long unsigned int count, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/mballoc.c (0)
Location: fs/ext4/mballoc.c:5912
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_free_blocks
```
**Symbols:**

```
ffffffff814f56e0-ffffffff814f5eac: ext4_mb_clear_bb (STB_LOCAL)
ffffffff81e7ed9b-ffffffff81e7eed2: ext4_mb_clear_bb.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void ext4_mb_clear_bb(handle_t *handle, struct inode *inode, ext4_fsblk_t block, long unsigned int count, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/mballoc.c (0)
Location: fs/ext4/mballoc.c:5881
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_free_blocks
```
**Symbols:**

```
ffffffff8158f9d0-ffffffff815901e4: ext4_mb_clear_bb (STB_LOCAL)
ffffffff8206f254-ffffffff8206f38f: ext4_mb_clear_bb.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void ext4_mb_clear_bb(handle_t *handle, struct inode *inode, ext4_fsblk_t block, long unsigned int count, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/mballoc.c (0)
Location: fs/ext4/mballoc.c:6455
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_free_blocks
```
**Symbols:**

```
ffffffff815c6c30-ffffffff815c73b9: ext4_mb_clear_bb (STB_LOCAL)
ffffffff820eeec6-ffffffff820eefc7: ext4_mb_clear_bb.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void ext4_mb_clear_bb(handle_t *handle, struct inode *inode, ext4_fsblk_t block, long unsigned int count, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/mballoc.c (0)
Location: fs/ext4/mballoc.c:6387
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_free_blocks
```
**Symbols:**

```
ffffffff816019a0-ffffffff8160209c: ext4_mb_clear_bb (STB_LOCAL)
ffffffff821cc2b7-ffffffff821cc3af: ext4_mb_clear_bb.cold (STB_LOCAL)
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
