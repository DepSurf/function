# Function: <code>list_bdev_fs_names</code>

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
<summary>In <code>5.15</code>: ✅</summary>

```c
int list_bdev_fs_names(char *buf, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/filesystems.c (ffffffff832dece9)
Location: fs/filesystems.c:212
Inline: False
Direct callers:
  - init/do_mounts.c:mount_block_root
```
**Symbols:**

```
ffffffff832dece9-ffffffff832ded78: list_bdev_fs_names (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int list_bdev_fs_names(char *buf, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/filesystems.c (ffffffff834947af)
Location: fs/filesystems.c:212
Inline: False
Direct callers:
  - init/do_mounts.c:mount_block_root
```
**Symbols:**

```
ffffffff834947af-ffffffff8349484f: list_bdev_fs_names (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int list_bdev_fs_names(char *buf, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/filesystems.c (ffffffff83ec8f60)
Location: fs/filesystems.c:212
Inline: False
Direct callers:
  - init/do_mounts.c:mount_block_root
```
**Symbols:**

```
ffffffff83ec8f60-ffffffff83ec9014: list_bdev_fs_names (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int list_bdev_fs_names(char *buf, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/filesystems.c (ffffffff836edfd0)
Location: fs/filesystems.c:212
Inline: False
Direct callers:
  - init/do_mounts.c:mount_root_generic
  - init/do_mounts.c:mount_root_generic
```
**Symbols:**

```
ffffffff836edfd0-ffffffff836ee084: list_bdev_fs_names (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int list_bdev_fs_names(char *buf, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/filesystems.c (ffffffff83921030)
Location: fs/filesystems.c:212
Inline: False
Direct callers:
  - init/do_mounts.c:mount_root_generic
  - init/do_mounts.c:mount_root_generic
```
**Symbols:**

```
ffffffff83921030-ffffffff839210e4: list_bdev_fs_names (STB_GLOBAL)
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
