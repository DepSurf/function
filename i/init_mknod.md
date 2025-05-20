# Function: <code>init_mknod</code>

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
int init_mknod(const char *filename, umode_t mode, unsigned int dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/init.c (ffffffff82fedd4e)
Location: fs/init.c:141
Inline: False
Direct callers:
  - init/do_mounts_initrd.c:initrd_load
  - init/initramfs.c:do_name
```
**Symbols:**

```
ffffffff82fedd4e-ffffffff82fede6c: init_mknod (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int init_mknod(const char *filename, umode_t mode, unsigned int dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/init.c (ffffffff831f855f)
Location: fs/init.c:141
Inline: False
Direct callers:
  - init/do_mounts_initrd.c:initrd_load
  - init/initramfs.c:do_name
```
**Symbols:**

```
ffffffff831f855f-ffffffff831f868a: init_mknod (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int init_mknod(const char *filename, umode_t mode, unsigned int dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/init.c (ffffffff832df4d8)
Location: fs/init.c:141
Inline: False
Direct callers:
  - init/do_mounts_initrd.c:initrd_load
  - init/initramfs.c:do_name
```
**Symbols:**

```
ffffffff832df4d8-ffffffff832df602: init_mknod (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int init_mknod(const char *filename, umode_t mode, unsigned int dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/init.c (ffffffff8349514b)
Location: fs/init.c:141
Inline: False
Direct callers:
  - init/do_mounts_initrd.c:initrd_load
  - init/initramfs.c:do_name
```
**Symbols:**

```
ffffffff8349514b-ffffffff83495295: init_mknod (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int init_mknod(const char *filename, umode_t mode, unsigned int dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/init.c (ffffffff83ec9b50)
Location: fs/init.c:141
Inline: False
Direct callers:
  - init/do_mounts.c:prepare_namespace
  - init/do_mounts.c:mount_root
  - init/do_mounts_initrd.c:initrd_load
  - init/initramfs.c:do_name
```
**Symbols:**

```
ffffffff83ec9b50-ffffffff83ec9ccc: init_mknod (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int init_mknod(const char *filename, umode_t mode, unsigned int dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/init.c (ffffffff836eeb90)
Location: fs/init.c:141
Inline: False
Direct callers:
  - init/do_mounts.c:prepare_namespace
  - init/do_mounts.c:mount_root
  - init/do_mounts_initrd.c:initrd_load
  - init/initramfs.c:do_name
```
**Symbols:**

```
ffffffff836eeb90-ffffffff836eed02: init_mknod (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int init_mknod(const char *filename, umode_t mode, unsigned int dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/init.c (ffffffff83921be0)
Location: fs/init.c:141
Inline: False
Direct callers:
  - init/do_mounts.c:prepare_namespace
  - init/do_mounts.c:mount_root
  - init/do_mounts_initrd.c:initrd_load
  - init/initramfs.c:do_name
```
**Symbols:**

```
ffffffff83921be0-ffffffff83921d51: init_mknod (STB_GLOBAL)
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
