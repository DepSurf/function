# Function: <code>vfs_fchmod</code>

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
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int vfs_fchmod(struct file *file, umode_t mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff8131b3be)
Location: fs/open.c:596
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_fchmod
  - fs/open.c:__x64_sys_fchmod
Direct callers:
  - init/initramfs.c:do_name
```
**Symbols:**

```
ffffffff8131b490-ffffffff8131b4e7: vfs_fchmod (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int vfs_fchmod(struct file *file, umode_t mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff813214cd)
Location: fs/open.c:598
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_fchmod
  - fs/open.c:__x64_sys_fchmod
Direct callers:
  - init/initramfs.c:do_name
```
**Symbols:**

```
ffffffff813215a0-ffffffff813215f7: vfs_fchmod (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int vfs_fchmod(struct file *file, umode_t mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff8136e9ad)
Location: fs/open.c:595
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_fchmod
  - fs/open.c:__x64_sys_fchmod
Direct callers:
  - init/initramfs.c:do_name
```
**Symbols:**

```
ffffffff8136ea80-ffffffff8136ead7: vfs_fchmod (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int vfs_fchmod(struct file *file, umode_t mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff813ed1d0)
Location: fs/open.c:619
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_fchmod
  - fs/open.c:__x64_sys_fchmod
Direct callers:
  - init/initramfs.c:do_name
```
**Symbols:**

```
ffffffff813ed2c0-ffffffff813ed30e: vfs_fchmod (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int vfs_fchmod(struct file *file, umode_t mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff81475810)
Location: fs/open.c:619
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_fchmod
  - fs/open.c:__x64_sys_fchmod
Direct callers:
  - init/initramfs.c:do_name
```
**Symbols:**

```
ffffffff81475920-ffffffff8147596e: vfs_fchmod (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int vfs_fchmod(struct file *file, umode_t mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff814aa1a0)
Location: fs/open.c:656
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_fchmod
  - fs/open.c:__x64_sys_fchmod
Direct callers:
  - init/initramfs.c:do_name
```
**Symbols:**

```
ffffffff814aa2b0-ffffffff814aa301: vfs_fchmod (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int vfs_fchmod(struct file *file, umode_t mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff814db280)
Location: fs/open.c:661
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_fchmod
  - fs/open.c:__x64_sys_fchmod
Direct callers:
  - init/initramfs.c:do_name
```
**Symbols:**

```
ffffffff814db750-ffffffff814db7a1: vfs_fchmod (STB_GLOBAL)
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
