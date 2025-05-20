# Function: <code>init_chdir</code>

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
int init_chdir(const char *filename);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/init.c (ffffffff82feda09)
Location: fs/init.c:44
Inline: False
Direct callers:
  - init/do_mounts.c:mount_block_root
  - drivers/base/devtmpfs.c:devtmpfsd
```
**Symbols:**

```
ffffffff82feda09-ffffffff82feda96: init_chdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int init_chdir(const char *filename);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/init.c (ffffffff831f8226)
Location: fs/init.c:44
Inline: False
Direct callers:
  - init/do_mounts.c:mount_block_root
  - drivers/base/devtmpfs.c:devtmpfs_setup
```
**Symbols:**

```
ffffffff831f8226-ffffffff831f82af: init_chdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int init_chdir(const char *filename);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/init.c (ffffffff832df19f)
Location: fs/init.c:44
Inline: False
Direct callers:
  - init/do_mounts.c:do_mount_root
  - drivers/base/devtmpfs.c:devtmpfs_setup
```
**Symbols:**

```
ffffffff832df19f-ffffffff832df228: init_chdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int init_chdir(const char *filename);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/init.c (ffffffff83494d4f)
Location: fs/init.c:44
Inline: False
Direct callers:
  - init/do_mounts.c:do_mount_root
  - drivers/base/devtmpfs.c:devtmpfs_setup
```
**Symbols:**

```
ffffffff83494d4f-ffffffff83494df6: init_chdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int init_chdir(const char *filename);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/init.c (ffffffff83ec9690)
Location: fs/init.c:44
Inline: False
Direct callers:
  - init/do_mounts.c:do_mount_root
  - drivers/base/devtmpfs.c:devtmpfs_setup
```
**Symbols:**

```
ffffffff83ec9690-ffffffff83ec9744: init_chdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int init_chdir(const char *filename);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/init.c (ffffffff836ee700)
Location: fs/init.c:44
Inline: False
Direct callers:
  - init/do_mounts.c:do_mount_root
  - drivers/base/devtmpfs.c:devtmpfs_setup
```
**Symbols:**

```
ffffffff836ee700-ffffffff836ee7ad: init_chdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int init_chdir(const char *filename);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/init.c (ffffffff83921750)
Location: fs/init.c:44
Inline: False
Direct callers:
  - init/do_mounts.c:do_mount_root
  - drivers/base/devtmpfs.c:devtmpfs_setup
```
**Symbols:**

```
ffffffff83921750-ffffffff839217fd: init_chdir (STB_GLOBAL)
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
