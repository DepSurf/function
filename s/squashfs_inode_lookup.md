# Function: <code>squashfs_inode_lookup</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/squashfs/export.c (ffffffff8132206a)
Location: fs/squashfs/export.c:52
Inline: True
Inline callers:
  - fs/squashfs/export.c:squashfs_export_iget
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
In fs/squashfs/export.c (ffffffff81337efa)
Location: fs/squashfs/export.c:52
Inline: True
Inline callers:
  - fs/squashfs/export.c:squashfs_export_iget
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
In fs/squashfs/export.c (ffffffff8134cc09)
Location: fs/squashfs/export.c:52
Inline: True
Inline callers:
  - fs/squashfs/export.c:squashfs_export_iget
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
In fs/squashfs/export.c (ffffffff81371289)
Location: fs/squashfs/export.c:52
Inline: True
Inline callers:
  - fs/squashfs/export.c:squashfs_export_iget
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
In fs/squashfs/export.c (ffffffff8139fb4a)
Location: fs/squashfs/export.c:52
Inline: True
Inline callers:
  - fs/squashfs/export.c:squashfs_export_iget
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
In fs/squashfs/export.c (ffffffff813b88da)
Location: fs/squashfs/export.c:52
Inline: True
Inline callers:
  - fs/squashfs/export.c:squashfs_export_iget
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
In fs/squashfs/export.c (ffffffff813e30fb)
Location: fs/squashfs/export.c:39
Inline: True
Inline callers:
  - fs/squashfs/export.c:squashfs_export_iget
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
In fs/squashfs/export.c (ffffffff813fd12b)
Location: fs/squashfs/export.c:39
Inline: True
Inline callers:
  - fs/squashfs/export.c:squashfs_export_iget
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long long int squashfs_inode_lookup(struct super_block *sb, int ino_num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/export.c (ffffffff8144aa60)
Location: fs/squashfs/export.c:39
Inline: False
Direct callers:
  - fs/squashfs/export.c:squashfs_export_iget
```
**Symbols:**

```
ffffffff8144aa60-ffffffff8144ab26: squashfs_inode_lookup (STB_LOCAL)
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
In fs/squashfs/export.c (ffffffff81467100)
Location: fs/squashfs/export.c:39
Inline: True
Inline callers:
  - fs/squashfs/export.c:squashfs_export_iget
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
In fs/squashfs/export.c (ffffffff8146c810)
Location: fs/squashfs/export.c:39
Inline: True
Inline callers:
  - fs/squashfs/export.c:squashfs_export_iget
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
In fs/squashfs/export.c (ffffffff814c30c0)
Location: fs/squashfs/export.c:39
Inline: True
Inline callers:
  - fs/squashfs/export.c:squashfs_export_iget
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
In fs/squashfs/export.c (ffffffff8154dbff)
Location: fs/squashfs/export.c:39
Inline: True
Inline callers:
  - fs/squashfs/export.c:squashfs_export_iget
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
In fs/squashfs/export.c (ffffffff815edc1f)
Location: fs/squashfs/export.c:39
Inline: True
Inline callers:
  - fs/squashfs/export.c:squashfs_export_iget
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
In fs/squashfs/export.c (ffffffff81625bdf)
Location: fs/squashfs/export.c:39
Inline: True
Inline callers:
  - fs/squashfs/export.c:squashfs_export_iget
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
In fs/squashfs/export.c (ffffffff8165ed1f)
Location: fs/squashfs/export.c:39
Inline: True
Inline callers:
  - fs/squashfs/export.c:squashfs_export_iget
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
In fs/squashfs/export.c (ffff8000104db0b0)
Location: fs/squashfs/export.c:39
Inline: True
Inline callers:
  - fs/squashfs/export.c:squashfs_export_iget
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
In fs/squashfs/export.c (c069c7ac)
Location: fs/squashfs/export.c:39
Inline: True
Inline callers:
  - fs/squashfs/export.c:squashfs_export_iget
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
In fs/squashfs/export.c (c000000000615f38)
Location: fs/squashfs/export.c:39
Inline: True
Inline callers:
  - fs/squashfs/export.c:squashfs_export_iget
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
In fs/squashfs/export.c (ffffffe00034fe3c)
Location: fs/squashfs/export.c:39
Inline: True
Inline callers:
  - fs/squashfs/export.c:squashfs_export_iget
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
In fs/squashfs/export.c (ffffffff813f570b)
Location: fs/squashfs/export.c:39
Inline: True
Inline callers:
  - fs/squashfs/export.c:squashfs_export_iget
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
In fs/squashfs/export.c (ffffffff813e618b)
Location: fs/squashfs/export.c:39
Inline: True
Inline callers:
  - fs/squashfs/export.c:squashfs_export_iget
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
In fs/squashfs/export.c (ffffffff813f2a8b)
Location: fs/squashfs/export.c:39
Inline: True
Inline callers:
  - fs/squashfs/export.c:squashfs_export_iget
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
In fs/squashfs/export.c (ffffffff8140867b)
Location: fs/squashfs/export.c:39
Inline: True
Inline callers:
  - fs/squashfs/export.c:squashfs_export_iget
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
