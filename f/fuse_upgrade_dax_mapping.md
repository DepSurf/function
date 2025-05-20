# Function: <code>fuse_upgrade_dax_mapping</code>

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
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int fuse_upgrade_dax_mapping(struct inode *inode, loff_t pos, loff_t length, unsigned int flags, struct iomap *iomap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dax.c (ffffffff8149d0d0)
Location: fs/fuse/dax.c:498
Inline: False
Direct callers:
  - fs/fuse/dax.c:fuse_iomap_begin
```
**Symbols:**

```
ffffffff8149d0d0-ffffffff8149d1dc: fuse_upgrade_dax_mapping (STB_LOCAL)
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
In fs/fuse/dax.c (ffffffff814a3be9)
Location: fs/fuse/dax.c:498
Inline: True
Inline callers:
  - fs/fuse/dax.c:fuse_iomap_begin
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
In fs/fuse/dax.c (ffffffff814fbc65)
Location: fs/fuse/dax.c:499
Inline: True
Inline callers:
  - fs/fuse/dax.c:fuse_iomap_begin
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
In fs/fuse/dax.c (ffffffff8158c193)
Location: fs/fuse/dax.c:499
Inline: True
Inline callers:
  - fs/fuse/dax.c:fuse_iomap_begin
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
In fs/fuse/dax.c (ffffffff816329e3)
Location: fs/fuse/dax.c:499
Inline: True
Inline callers:
  - fs/fuse/dax.c:fuse_iomap_begin
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
In fs/fuse/dax.c (ffffffff8166a933)
Location: fs/fuse/dax.c:499
Inline: True
Inline callers:
  - fs/fuse/dax.c:fuse_iomap_begin
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
In fs/fuse/dax.c (ffffffff816a4c73)
Location: fs/fuse/dax.c:499
Inline: True
Inline callers:
  - fs/fuse/dax.c:fuse_iomap_begin
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
</ul>
