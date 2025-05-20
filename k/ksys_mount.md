# Function: <code>ksys_mount</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ksys_mount(char *dev_name, char *dir_name, char *type, long unsigned int flags, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812c1ae0)
Location: fs/namespace.c:3075
Inline: False
Direct callers:
  - init/do_mounts.c:prepare_namespace
  - init/do_mounts.c:mount_block_root
  - fs/namespace.c:__ia32_sys_mount
  - fs/namespace.c:__x64_sys_mount
  - drivers/base/devtmpfs.c:devtmpfs_mount
```
**Symbols:**

```
ffffffff812c1ae0-ffffffff812c1bb8: ksys_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ksys_mount(char *dev_name, char *dir_name, char *type, long unsigned int flags, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812d6d90)
Location: fs/namespace.c:3047
Inline: False
Direct callers:
  - init/do_mounts.c:prepare_namespace
  - init/do_mounts.c:mount_block_root
  - fs/namespace.c:__ia32_sys_mount
  - fs/namespace.c:__x64_sys_mount
  - drivers/base/devtmpfs.c:devtmpfs_mount
```
**Symbols:**

```
ffffffff812d6d90-ffffffff812d6e5f: ksys_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ksys_mount(const char *dev_name, const char *dir_name, const char *type, long unsigned int flags, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812f51f0)
Location: fs/namespace.c:3306
Inline: False
Direct callers:
  - init/do_mounts.c:prepare_namespace
  - init/do_mounts.c:mount_block_root
  - fs/namespace.c:__ia32_sys_mount
  - fs/namespace.c:__x64_sys_mount
  - drivers/base/devtmpfs.c:devtmpfs_mount
```
**Symbols:**

```
ffffffff812f51f0-ffffffff812f52b6: ksys_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ksys_mount(const char *dev_name, const char *dir_name, const char *type, long unsigned int flags, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81306d70)
Location: fs/namespace.c:3337
Inline: False
Direct callers:
  - init/do_mounts.c:prepare_namespace
  - init/do_mounts.c:mount_block_root
  - fs/namespace.c:__ia32_sys_mount
  - fs/namespace.c:__x64_sys_mount
  - drivers/base/devtmpfs.c:devtmpfs_mount
```
**Symbols:**

```
ffffffff81306d70-ffffffff81306e36: ksys_mount (STB_GLOBAL)
```
</details>
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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int ksys_mount(const char *dev_name, const char *dir_name, const char *type, long unsigned int flags, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffff8000103ba4a8)
Location: fs/namespace.c:3337
Inline: False
Direct callers:
  - init/do_mounts.c:prepare_namespace
  - init/do_mounts.c:mount_block_root
  - fs/namespace.c:__arm64_sys_mount
  - drivers/base/devtmpfs.c:devtmpfs_mount
```
**Symbols:**

```
ffff8000103ba4a8-ffff8000103ba598: ksys_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ksys_mount(const char *dev_name, const char *dir_name, const char *type, long unsigned int flags, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (c0597e80)
Location: fs/namespace.c:3337
Inline: False
Direct callers:
  - init/do_mounts.c:prepare_namespace
  - init/do_mounts.c:mount_block_root
  - fs/namespace.c:__se_sys_mount
  - drivers/base/devtmpfs.c:devtmpfs_mount
```
**Symbols:**

```
c0597e80-c0597f44: ksys_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ksys_mount(const char *dev_name, const char *dir_name, const char *type, long unsigned int flags, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (c0000000004b7c30)
Location: fs/namespace.c:3337
Inline: False
Direct callers:
  - init/do_mounts.c:prepare_namespace
  - init/do_mounts.c:mount_block_root
  - fs/namespace.c:__se_sys_mount
  - drivers/base/devtmpfs.c:devtmpfs_mount
```
**Symbols:**

```
c0000000004b7c30-c0000000004b7d98: ksys_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ksys_mount(const char *dev_name, const char *dir_name, const char *type, long unsigned int flags, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffe00027c600)
Location: fs/namespace.c:3337
Inline: False
Direct callers:
  - init/do_mounts.c:prepare_namespace
  - init/do_mounts.c:mount_block_root
  - fs/namespace.c:__se_sys_mount
  - drivers/base/devtmpfs.c:devtmpfs_mount
```
**Symbols:**

```
ffffffe00027c600-ffffffe00027c6c2: ksys_mount (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int ksys_mount(const char *dev_name, const char *dir_name, const char *type, long unsigned int flags, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812ff350)
Location: fs/namespace.c:3337
Inline: False
Direct callers:
  - init/do_mounts.c:prepare_namespace
  - init/do_mounts.c:mount_block_root
  - fs/namespace.c:__ia32_sys_mount
  - fs/namespace.c:__x64_sys_mount
  - drivers/base/devtmpfs.c:devtmpfs_mount
```
**Symbols:**

```
ffffffff812ff350-ffffffff812ff416: ksys_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ksys_mount(const char *dev_name, const char *dir_name, const char *type, long unsigned int flags, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812eff70)
Location: fs/namespace.c:3337
Inline: False
Direct callers:
  - init/do_mounts.c:prepare_namespace
  - init/do_mounts.c:mount_block_root
  - fs/namespace.c:__ia32_sys_mount
  - fs/namespace.c:__x64_sys_mount
  - drivers/base/devtmpfs.c:devtmpfs_mount
```
**Symbols:**

```
ffffffff812eff70-ffffffff812f0036: ksys_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ksys_mount(const char *dev_name, const char *dir_name, const char *type, long unsigned int flags, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812fd140)
Location: fs/namespace.c:3337
Inline: False
Direct callers:
  - init/do_mounts.c:prepare_namespace
  - init/do_mounts.c:mount_block_root
  - fs/namespace.c:__ia32_sys_mount
  - fs/namespace.c:__x64_sys_mount
  - drivers/base/devtmpfs.c:devtmpfs_mount
```
**Symbols:**

```
ffffffff812fd140-ffffffff812fd206: ksys_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ksys_mount(const char *dev_name, const char *dir_name, const char *type, long unsigned int flags, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8130e4a0)
Location: fs/namespace.c:3337
Inline: False
Direct callers:
  - init/do_mounts.c:prepare_namespace
  - init/do_mounts.c:mount_block_root
  - fs/namespace.c:__ia32_sys_mount
  - fs/namespace.c:__x64_sys_mount
  - drivers/base/devtmpfs.c:devtmpfs_mount
```
**Symbols:**

```
ffffffff8130e4a0-ffffffff8130e566: ksys_mount (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>char *dev_name</code> ➡️ <code>const char *dev_name</code>
</li>
<li>
<b>Param type changed. </b>
<code>char *dir_name</code> ➡️ <code>const char *dir_name</code>
</li>
<li>
<b>Param type changed. </b>
<code>char *type</code> ➡️ <code>const char *type</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
