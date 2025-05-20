# Function: <code>ext4_update_backup_sb</code>

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
<summary>In <code>5.19</code>: ✅</summary>

```c
int ext4_update_backup_sb(struct super_block *sb, handle_t *handle, ext4_group_t grp, ext4_update_sb_callback *func, const void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ioctl.c (ffffffff814ed560)
Location: fs/ext4/ioctl.c:93
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:ext4_update_superblocks_fn
```
**Symbols:**

```
ffffffff814ed560-ffffffff814ed84c: ext4_update_backup_sb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ext4_update_backup_sb(struct super_block *sb, handle_t *handle, ext4_group_t grp, ext4_update_sb_callback *func, const void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ioctl.c (ffffffff815873d0)
Location: fs/ext4/ioctl.c:103
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:ext4_update_superblocks_fn
```
**Symbols:**

```
ffffffff815873d0-ffffffff8158768d: ext4_update_backup_sb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ext4_update_backup_sb(struct super_block *sb, handle_t *handle, ext4_group_t grp, ext4_update_sb_callback *func, const void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ioctl.c (ffffffff815bda90)
Location: fs/ext4/ioctl.c:103
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:ext4_update_superblocks_fn
```
**Symbols:**

```
ffffffff815bda90-ffffffff815bdd4d: ext4_update_backup_sb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ext4_update_backup_sb(struct super_block *sb, handle_t *handle, ext4_group_t grp, ext4_update_sb_callback *func, const void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ioctl.c (ffffffff815f6850)
Location: fs/ext4/ioctl.c:103
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:ext4_update_superblocks_fn
```
**Symbols:**

```
ffffffff815f6850-ffffffff815f6b0d: ext4_update_backup_sb (STB_LOCAL)
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
