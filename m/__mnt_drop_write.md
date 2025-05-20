# Function: <code>__mnt_drop_write</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void __mnt_drop_write(struct vfsmount *mnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8122b580)
Location: fs/namespace.c:460
Inline: True
Inline callers:
  - fs/namespace.c:mnt_drop_write_file
  - fs/namespace.c:__mnt_drop_write_file
Direct callers:
  - fs/open.c:do_dentry_open
  - fs/file_table.c:__fput
  - fs/inode.c:touch_atime
```
**Symbols:**

```
ffffffff8122b580-ffffffff8122b593: __mnt_drop_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void __mnt_drop_write(struct vfsmount *mnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81253fed)
Location: fs/namespace.c:460
Inline: True
Inline callers:
  - fs/namespace.c:mnt_drop_write_file
  - fs/namespace.c:__mnt_drop_write_file
Direct callers:
  - fs/open.c:do_dentry_open
  - fs/file_table.c:__fput
  - fs/inode.c:touch_atime
```
**Symbols:**

```
ffffffff81253cf0-ffffffff81253d03: __mnt_drop_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void __mnt_drop_write(struct vfsmount *mnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8126732d)
Location: fs/namespace.c:459
Inline: True
Inline callers:
  - fs/namespace.c:mnt_drop_write_file
  - fs/namespace.c:__mnt_drop_write_file
Direct callers:
  - fs/open.c:do_dentry_open
  - fs/file_table.c:__fput
  - fs/inode.c:touch_atime
```
**Symbols:**

```
ffffffff81266f40-ffffffff81266f53: __mnt_drop_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void __mnt_drop_write(struct vfsmount *mnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81274b8d)
Location: fs/namespace.c:460
Inline: True
Inline callers:
  - fs/namespace.c:mnt_drop_write_file
  - fs/namespace.c:__mnt_drop_write_file
Direct callers:
  - fs/open.c:do_dentry_open
  - fs/file_table.c:__fput
  - fs/inode.c:touch_atime
```
**Symbols:**

```
ffffffff81274790-ffffffff812747a3: __mnt_drop_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void __mnt_drop_write(struct vfsmount *mnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812974bd)
Location: fs/namespace.c:514
Inline: True
Inline callers:
  - fs/namespace.c:mnt_drop_write_file
  - fs/namespace.c:mnt_drop_write_file_path
  - fs/namespace.c:__mnt_drop_write_file
Direct callers:
  - fs/open.c:do_dentry_open
  - fs/file_table.c:__fput
  - fs/inode.c:touch_atime
```
**Symbols:**

```
ffffffff81297090-ffffffff812970a3: __mnt_drop_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void __mnt_drop_write(struct vfsmount *mnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812bd6aa)
Location: fs/namespace.c:514
Inline: True
Inline callers:
  - fs/namespace.c:mnt_drop_write_file
  - fs/namespace.c:mnt_drop_write
Direct callers:
  - fs/open.c:do_dentry_open
  - fs/file_table.c:__fput
  - fs/inode.c:touch_atime
```
**Symbols:**

```
ffffffff812bd2d0-ffffffff812bd2e3: __mnt_drop_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void __mnt_drop_write(struct vfsmount *mnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812d299a)
Location: fs/namespace.c:431
Inline: True
Inline callers:
  - fs/namespace.c:mnt_drop_write_file
  - fs/namespace.c:mnt_drop_write
Direct callers:
  - fs/open.c:do_dentry_open
  - fs/file_table.c:__fput
  - fs/inode.c:touch_atime
```
**Symbols:**

```
ffffffff812d25f0-ffffffff812d2603: __mnt_drop_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void __mnt_drop_write(struct vfsmount *mnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812efb6a)
Location: fs/namespace.c:428
Inline: True
Inline callers:
  - fs/namespace.c:mnt_drop_write_file
  - fs/namespace.c:mnt_drop_write
Direct callers:
  - kernel/acct.c:acct_on
  - fs/open.c:do_dentry_open
  - fs/file_table.c:__fput
  - fs/inode.c:touch_atime
```
**Symbols:**

```
ffffffff812ef640-ffffffff812ef653: __mnt_drop_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void __mnt_drop_write(struct vfsmount *mnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8130163a)
Location: fs/namespace.c:428
Inline: True
Inline callers:
  - fs/namespace.c:mnt_drop_write_file
  - fs/namespace.c:mnt_drop_write
Direct callers:
  - kernel/acct.c:acct_on
  - fs/open.c:do_dentry_open
  - fs/file_table.c:__fput
  - fs/inode.c:touch_atime
```
**Symbols:**

```
ffffffff81301110-ffffffff81301123: __mnt_drop_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void __mnt_drop_write(struct vfsmount *mnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8133a71a)
Location: fs/namespace.c:428
Inline: True
Inline callers:
  - fs/namespace.c:mnt_drop_write_file
  - fs/namespace.c:mnt_drop_write
Direct callers:
  - kernel/acct.c:acct_on
  - fs/open.c:do_dentry_open
  - fs/file_table.c:__fput
  - fs/inode.c:touch_atime
```
**Symbols:**

```
ffffffff8133a380-ffffffff8133a393: __mnt_drop_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void __mnt_drop_write(struct vfsmount *mnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81346a69)
Location: fs/namespace.c:428
Inline: True
Inline callers:
  - fs/namespace.c:mnt_drop_write_file
  - fs/namespace.c:mnt_drop_write
Direct callers:
  - kernel/acct.c:acct_on
  - fs/open.c:do_dentry_open
  - fs/file_table.c:__fput
  - fs/inode.c:touch_atime
```
**Symbols:**

```
ffffffff81346070-ffffffff81346083: __mnt_drop_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void __mnt_drop_write(struct vfsmount *mnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8134cd4f)
Location: fs/namespace.c:435
Inline: True
Inline callers:
  - fs/namespace.c:mnt_drop_write_file
  - fs/namespace.c:mnt_drop_write
Direct callers:
  - kernel/acct.c:acct_on
  - fs/open.c:do_dentry_open
  - fs/file_table.c:__fput
  - fs/inode.c:touch_atime
```
**Symbols:**

```
ffffffff8134fc40-ffffffff8134fc53: __mnt_drop_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void __mnt_drop_write(struct vfsmount *mnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8139acbf)
Location: fs/namespace.c:436
Inline: True
Inline callers:
  - fs/namespace.c:mnt_drop_write_file
  - fs/namespace.c:mnt_drop_write
Direct callers:
  - kernel/acct.c:acct_on
  - fs/open.c:do_dentry_open
  - fs/file_table.c:__fput
  - fs/inode.c:touch_atime
```
**Symbols:**

```
ffffffff8139a250-ffffffff8139a263: __mnt_drop_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void __mnt_drop_write(struct vfsmount *mnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8141e729)
Location: fs/namespace.c:453
Inline: True
Inline callers:
  - fs/namespace.c:mnt_drop_write_file
  - fs/namespace.c:mnt_drop_write
Direct callers:
  - kernel/acct.c:acct_on
  - fs/open.c:do_dentry_open
  - fs/file_table.c:__fput
  - fs/inode.c:touch_atime
```
**Symbols:**

```
ffffffff81421070-ffffffff814210a9: __mnt_drop_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void __mnt_drop_write(struct vfsmount *mnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff814aae39)
Location: fs/namespace.c:568
Inline: True
Inline callers:
  - fs/namespace.c:mnt_drop_write_file
  - fs/namespace.c:mnt_drop_write
Direct callers:
  - kernel/acct.c:acct_on
  - fs/open.c:do_dentry_open
  - fs/file_table.c:__fput
  - fs/inode.c:touch_atime
```
**Symbols:**

```
ffffffff814ad6c0-ffffffff814ad6f9: __mnt_drop_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void __mnt_drop_write(struct vfsmount *mnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff814dfcef)
Location: fs/namespace.c:463
Inline: True
Inline callers:
  - fs/namespace.c:mnt_drop_write_file
  - fs/namespace.c:mnt_drop_write
Direct callers:
  - kernel/acct.c:acct_on
  - fs/open.c:do_dentry_open
  - fs/file_table.c:__fput
  - fs/inode.c:touch_atime
```
**Symbols:**

```
ffffffff814e24a0-ffffffff814e24d9: __mnt_drop_write (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void __mnt_drop_write(struct vfsmount *mnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffff8000103b4a7c)
Location: fs/namespace.c:428
Inline: True
Inline callers:
  - fs/namespace.c:mnt_drop_write_file
  - fs/namespace.c:mnt_drop_write
Direct callers:
  - kernel/acct.c:__arm64_sys_acct
  - fs/open.c:do_dentry_open
  - fs/file_table.c:__fput
  - fs/inode.c:touch_atime
```
**Symbols:**

```
ffff8000103b49a0-ffff8000103b49e8: __mnt_drop_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void __mnt_drop_write(struct vfsmount *mnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (c0592c20)
Location: fs/namespace.c:428
Inline: True
Inline callers:
  - fs/namespace.c:mnt_drop_write_file
  - fs/namespace.c:mnt_drop_write
Direct callers:
  - kernel/acct.c:__se_sys_acct
  - fs/open.c:do_dentry_open
  - fs/file_table.c:__fput
  - fs/inode.c:touch_atime
```
**Symbols:**

```
c0592528-c0592564: __mnt_drop_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void __mnt_drop_write(struct vfsmount *mnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (c0000000004b0ea4)
Location: fs/namespace.c:428
Inline: True
Inline callers:
  - fs/namespace.c:mnt_drop_write_file
  - fs/namespace.c:mnt_drop_write
Direct callers:
  - kernel/acct.c:__se_sys_acct
  - fs/open.c:do_dentry_open
  - fs/file_table.c:__fput
  - fs/inode.c:touch_atime
```
**Symbols:**

```
c0000000004b0da0-c0000000004b0dfc: __mnt_drop_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void __mnt_drop_write(struct vfsmount *mnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffe000277588)
Location: fs/namespace.c:428
Inline: True
Inline callers:
  - fs/namespace.c:mnt_drop_write_file
  - fs/namespace.c:mnt_drop_write
Direct callers:
  - kernel/acct.c:__se_sys_acct
  - fs/open.c:do_dentry_open
  - fs/file_table.c:__fput
  - fs/inode.c:touch_atime
```
**Symbols:**

```
ffffffe00027707e-ffffffe0002770c8: __mnt_drop_write (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void __mnt_drop_write(struct vfsmount *mnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812f9c1a)
Location: fs/namespace.c:428
Inline: True
Inline callers:
  - fs/namespace.c:mnt_drop_write_file
  - fs/namespace.c:mnt_drop_write
Direct callers:
  - kernel/acct.c:acct_on
  - fs/open.c:do_dentry_open
  - fs/file_table.c:__fput
  - fs/inode.c:touch_atime
```
**Symbols:**

```
ffffffff812f96f0-ffffffff812f9703: __mnt_drop_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void __mnt_drop_write(struct vfsmount *mnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812ea83a)
Location: fs/namespace.c:428
Inline: True
Inline callers:
  - fs/namespace.c:mnt_drop_write_file
  - fs/namespace.c:mnt_drop_write
Direct callers:
  - kernel/acct.c:acct_on
  - fs/open.c:do_dentry_open
  - fs/file_table.c:__fput
  - fs/inode.c:touch_atime
```
**Symbols:**

```
ffffffff812ea310-ffffffff812ea323: __mnt_drop_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void __mnt_drop_write(struct vfsmount *mnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812f7a0a)
Location: fs/namespace.c:428
Inline: True
Inline callers:
  - fs/namespace.c:mnt_drop_write_file
  - fs/namespace.c:mnt_drop_write
Direct callers:
  - kernel/acct.c:acct_on
  - fs/open.c:do_dentry_open
  - fs/file_table.c:__fput
  - fs/inode.c:touch_atime
```
**Symbols:**

```
ffffffff812f74e0-ffffffff812f74f3: __mnt_drop_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void __mnt_drop_write(struct vfsmount *mnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81308d3a)
Location: fs/namespace.c:428
Inline: True
Inline callers:
  - fs/namespace.c:mnt_drop_write_file
  - fs/namespace.c:mnt_drop_write
Direct callers:
  - kernel/acct.c:acct_on
  - fs/open.c:do_dentry_open
  - fs/file_table.c:__fput
  - fs/inode.c:touch_atime
```
**Symbols:**

```
ffffffff81308af0-ffffffff81308b19: __mnt_drop_write (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
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
