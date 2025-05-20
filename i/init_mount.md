# Function: <code>init_mount</code>

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
int init_mount(const char *dev_name, const char *dir_name, const char *type_page, long unsigned int flags, void *data_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/init.c (ffffffff82fed917)
Location: fs/init.c:16
Inline: False
Direct callers:
  - init/do_mounts.c:prepare_namespace
  - init/do_mounts.c:mount_block_root
  - drivers/base/devtmpfs.c:devtmpfsd
  - drivers/base/devtmpfs.c:devtmpfs_mount
```
**Symbols:**

```
ffffffff82fed917-ffffffff82fed9a7: init_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int init_mount(const char *dev_name, const char *dir_name, const char *type_page, long unsigned int flags, void *data_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/init.c (ffffffff831f8133)
Location: fs/init.c:16
Inline: False
Direct callers:
  - init/do_mounts.c:prepare_namespace
  - init/do_mounts.c:mount_block_root
  - drivers/base/devtmpfs.c:devtmpfs_setup
  - drivers/base/devtmpfs.c:devtmpfs_mount
```
**Symbols:**

```
ffffffff831f8133-ffffffff831f81c3: init_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int init_mount(const char *dev_name, const char *dir_name, const char *type_page, long unsigned int flags, void *data_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/init.c (ffffffff832df0ac)
Location: fs/init.c:16
Inline: False
Direct callers:
  - init/do_mounts.c:prepare_namespace
  - init/do_mounts.c:do_mount_root
  - drivers/base/devtmpfs.c:devtmpfs_setup
  - drivers/base/devtmpfs.c:devtmpfs_mount
```
**Symbols:**

```
ffffffff832df0ac-ffffffff832df13c: init_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int init_mount(const char *dev_name, const char *dir_name, const char *type_page, long unsigned int flags, void *data_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/init.c (ffffffff83494c18)
Location: fs/init.c:16
Inline: False
Direct callers:
  - init/do_mounts.c:prepare_namespace
  - init/do_mounts.c:do_mount_root
  - drivers/base/devtmpfs.c:devtmpfs_setup
  - drivers/base/devtmpfs.c:devtmpfs_mount
```
**Symbols:**

```
ffffffff83494c18-ffffffff83494cc7: init_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int init_mount(const char *dev_name, const char *dir_name, const char *type_page, long unsigned int flags, void *data_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/init.c (ffffffff83ec9540)
Location: fs/init.c:16
Inline: False
Direct callers:
  - init/do_mounts.c:prepare_namespace
  - init/do_mounts.c:do_mount_root
  - init/do_mounts.c:do_mount_root
  - drivers/base/devtmpfs.c:devtmpfs_setup
  - drivers/base/devtmpfs.c:devtmpfs_mount
```
**Symbols:**

```
ffffffff83ec9540-ffffffff83ec95ec: init_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int init_mount(const char *dev_name, const char *dir_name, const char *type_page, long unsigned int flags, void *data_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/init.c (ffffffff836ee5b0)
Location: fs/init.c:16
Inline: False
Direct callers:
  - init/do_mounts.c:prepare_namespace
  - init/do_mounts.c:do_mount_root
  - init/do_mounts.c:do_mount_root
  - drivers/base/devtmpfs.c:devtmpfs_setup
  - drivers/base/devtmpfs.c:devtmpfs_mount
```
**Symbols:**

```
ffffffff836ee5b0-ffffffff836ee65c: init_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int init_mount(const char *dev_name, const char *dir_name, const char *type_page, long unsigned int flags, void *data_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/init.c (ffffffff83921600)
Location: fs/init.c:16
Inline: False
Direct callers:
  - init/do_mounts.c:prepare_namespace
  - init/do_mounts.c:do_mount_root
  - init/do_mounts.c:do_mount_root
  - drivers/base/devtmpfs.c:devtmpfs_setup
  - drivers/base/devtmpfs.c:devtmpfs_mount
```
**Symbols:**

```
ffffffff83921600-ffffffff839216ac: init_mount (STB_GLOBAL)
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
