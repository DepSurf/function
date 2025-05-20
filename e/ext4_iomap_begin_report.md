# Function: <code>ext4_iomap_begin_report</code>

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
int ext4_iomap_begin_report(struct inode *inode, loff_t offset, loff_t length, unsigned int flags, struct iomap *iomap, struct iomap *srcmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813f9510)
Location: fs/ext4/inode.c:3517
Inline: False
```
**Symbols:**

```
ffffffff813f9510-ffffffff813f96ed: ext4_iomap_begin_report (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ext4_iomap_begin_report(struct inode *inode, loff_t offset, loff_t length, unsigned int flags, struct iomap *iomap, struct iomap *srcmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff8140bb10)
Location: fs/ext4/inode.c:3555
Inline: False
```
**Symbols:**

```
ffffffff8140bb10-ffffffff8140bced: ext4_iomap_begin_report (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ext4_iomap_begin_report(struct inode *inode, loff_t offset, loff_t length, unsigned int flags, struct iomap *iomap, struct iomap *srcmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81411cd0)
Location: fs/ext4/inode.c:3554
Inline: False
```
**Symbols:**

```
ffffffff81411cd0-ffffffff81411eab: ext4_iomap_begin_report (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int ext4_iomap_begin_report(struct inode *inode, loff_t offset, loff_t length, unsigned int flags, struct iomap *iomap, struct iomap *srcmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/inode.c (0)
Location: fs/ext4/inode.c:3477
Inline: False
```
**Symbols:**

```
ffffffff81464b90-ffffffff81464d96: ext4_iomap_begin_report (STB_LOCAL)
ffffffff81ccac07-ffffffff81ccac7b: ext4_iomap_begin_report.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int ext4_iomap_begin_report(struct inode *inode, loff_t offset, loff_t length, unsigned int flags, struct iomap *iomap, struct iomap *srcmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/inode.c (0)
Location: fs/ext4/inode.c:3540
Inline: False
```
**Symbols:**

```
ffffffff814e4270-ffffffff814e44c8: ext4_iomap_begin_report (STB_LOCAL)
ffffffff81e7d9ff-ffffffff81e7dab9: ext4_iomap_begin_report.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int ext4_iomap_begin_report(struct inode *inode, loff_t offset, loff_t length, unsigned int flags, struct iomap *iomap, struct iomap *srcmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/inode.c (0)
Location: fs/ext4/inode.c:3628
Inline: False
```
**Symbols:**

```
ffffffff8157d940-ffffffff8157db98: ext4_iomap_begin_report (STB_LOCAL)
ffffffff8206df69-ffffffff8206e023: ext4_iomap_begin_report.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int ext4_iomap_begin_report(struct inode *inode, loff_t offset, loff_t length, unsigned int flags, struct iomap *iomap, struct iomap *srcmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/inode.c (0)
Location: fs/ext4/inode.c:3411
Inline: False
```
**Symbols:**

```
ffffffff815b4c30-ffffffff815b4e8a: ext4_iomap_begin_report (STB_LOCAL)
ffffffff820edc58-ffffffff820edd02: ext4_iomap_begin_report.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int ext4_iomap_begin_report(struct inode *inode, loff_t offset, loff_t length, unsigned int flags, struct iomap *iomap, struct iomap *srcmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/inode.c (0)
Location: fs/ext4/inode.c:3430
Inline: False
```
**Symbols:**

```
ffffffff815eda90-ffffffff815edc23: ext4_iomap_begin_report (STB_LOCAL)
ffffffff821cadb5-ffffffff821cae5f: ext4_iomap_begin_report.cold (STB_LOCAL)
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
