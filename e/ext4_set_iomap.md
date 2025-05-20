# Function: <code>ext4_set_iomap</code>

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
void ext4_set_iomap(struct inode *inode, struct iomap *iomap, struct ext4_map_blocks *map, loff_t offset, loff_t length);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813f58e0)
Location: fs/ext4/inode.c:3308
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_iomap_begin_report
  - fs/ext4/inode.c:ext4_iomap_begin_report
  - fs/ext4/inode.c:ext4_iomap_begin_report
  - fs/ext4/inode.c:ext4_iomap_begin
```
**Symbols:**

```
ffffffff813f58e0-ffffffff813f5a73: ext4_set_iomap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ext4_set_iomap(struct inode *inode, struct iomap *iomap, struct ext4_map_blocks *map, loff_t offset, loff_t length);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff814080f0)
Location: fs/ext4/inode.c:3334
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_iomap_begin_report
  - fs/ext4/inode.c:ext4_iomap_begin_report
  - fs/ext4/inode.c:ext4_iomap_begin_report
  - fs/ext4/inode.c:ext4_iomap_begin
```
**Symbols:**

```
ffffffff814080f0-ffffffff814082dc: ext4_set_iomap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void ext4_set_iomap(struct inode *inode, struct iomap *iomap, struct ext4_map_blocks *map, loff_t offset, loff_t length);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff8140e410)
Location: fs/ext4/inode.c:3333
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_iomap_begin_report
  - fs/ext4/inode.c:ext4_iomap_begin_report
  - fs/ext4/inode.c:ext4_iomap_begin_report
  - fs/ext4/inode.c:ext4_iomap_begin
```
**Symbols:**

```
ffffffff8140e410-ffffffff8140e5e8: ext4_set_iomap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void ext4_set_iomap(struct inode *inode, struct iomap *iomap, struct ext4_map_blocks *map, loff_t offset, loff_t length);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/inode.c (0)
Location: fs/ext4/inode.c:3256
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_iomap_begin_report
  - fs/ext4/inode.c:ext4_iomap_begin_report
  - fs/ext4/inode.c:ext4_iomap_begin_report
  - fs/ext4/inode.c:ext4_iomap_begin
```
**Symbols:**

```
ffffffff81461180-ffffffff81461340: ext4_set_iomap (STB_LOCAL)
ffffffff81cca6ed-ffffffff81cca76a: ext4_set_iomap.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void ext4_set_iomap(struct inode *inode, struct iomap *iomap, struct ext4_map_blocks *map, loff_t offset, loff_t length, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/inode.c (0)
Location: fs/ext4/inode.c:3306
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_iomap_begin_report
  - fs/ext4/inode.c:ext4_iomap_begin_report
  - fs/ext4/inode.c:ext4_iomap_begin
```
**Symbols:**

```
ffffffff814df9b0-ffffffff814dfbde: ext4_set_iomap (STB_LOCAL)
ffffffff81e7d424-ffffffff81e7d4aa: ext4_set_iomap.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void ext4_set_iomap(struct inode *inode, struct iomap *iomap, struct ext4_map_blocks *map, loff_t offset, loff_t length, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/inode.c (0)
Location: fs/ext4/inode.c:3394
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_iomap_begin_report
  - fs/ext4/inode.c:ext4_iomap_begin_report
  - fs/ext4/inode.c:ext4_iomap_begin
```
**Symbols:**

```
ffffffff81578cc0-ffffffff81578eee: ext4_set_iomap (STB_LOCAL)
ffffffff8206d991-ffffffff8206da17: ext4_set_iomap.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void ext4_set_iomap(struct inode *inode, struct iomap *iomap, struct ext4_map_blocks *map, loff_t offset, loff_t length, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/inode.c (0)
Location: fs/ext4/inode.c:3177
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_iomap_begin_report
  - fs/ext4/inode.c:ext4_iomap_begin_report
  - fs/ext4/inode.c:ext4_iomap_begin
```
**Symbols:**

```
ffffffff815b00f0-ffffffff815b031b: ext4_set_iomap (STB_LOCAL)
ffffffff820ed692-ffffffff820ed71a: ext4_set_iomap.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void ext4_set_iomap(struct inode *inode, struct iomap *iomap, struct ext4_map_blocks *map, loff_t offset, loff_t length, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/inode.c (0)
Location: fs/ext4/inode.c:3216
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_iomap_begin_report
  - fs/ext4/inode.c:ext4_iomap_begin
```
**Symbols:**

```
ffffffff815e8ea0-ffffffff815e9107: ext4_set_iomap (STB_LOCAL)
ffffffff821ca7a9-ffffffff821ca832: ext4_set_iomap.cold (STB_LOCAL)
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
<code>unsigned int flags</code>
</li>
</ul>
</details>
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
