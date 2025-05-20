# Function: <code>d_rehash</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void d_rehash(struct dentry *entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812234d0)
Location: fs/dcache.c:2431
Inline: False
Direct callers:
  - mm/shmem.c:shmem_rename2
  - fs/dcache.c:d_splice_alias
  - fs/libfs.c:simple_fill_super
  - fs/proc/base.c:proc_pid_instantiate
  - fs/proc/base.c:proc_pident_instantiate
  - fs/proc/base.c:proc_map_files_instantiate
  - fs/proc/base.c:proc_task_instantiate
  - fs/proc/generic.c:proc_lookup_de
  - fs/proc/fd.c:proc_fd_instantiate
  - fs/proc/fd.c:proc_fdinfo_instantiate
  - fs/proc/namespaces.c:proc_ns_instantiate
  - fs/proc/self.c:proc_setup_self
  - fs/proc/thread_self.c:proc_setup_thread_self
  - fs/proc/proc_sysctl.c:proc_sys_lookup
  - fs/devpts/inode.c:devpts_mount
  - fs/devpts/inode.c:devpts_pty_new
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/fuse/control.c:fuse_ctl_add_dentry
  - fs/pstore/inode.c:pstore_mkfile
  - fs/efivarfs/super.c:efivarfs_callback
  - security/selinux/selinuxfs.c:sel_make_dir
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_load
```
**Symbols:**

```
ffffffff812234d0-ffffffff8122352b: d_rehash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void d_rehash(struct dentry *entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8124bb00)
Location: fs/dcache.c:2359
Inline: False
Direct callers:
  - mm/shmem.c:shmem_rename2
```
**Symbols:**

```
ffffffff8124bb00-ffffffff8124bb32: d_rehash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void d_rehash(struct dentry *entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8125eae0)
Location: fs/dcache.c:2368
Inline: False
Direct callers:
  - mm/shmem.c:shmem_rename2
```
**Symbols:**

```
ffffffff8125eae0-ffffffff8125eb12: d_rehash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void d_rehash(struct dentry *entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8126c340)
Location: fs/dcache.c:2398
Inline: False
Direct callers:
  - mm/shmem.c:shmem_rename2
```
**Symbols:**

```
ffffffff8126c340-ffffffff8126c372: d_rehash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void d_rehash(struct dentry *entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8128e640)
Location: fs/dcache.c:2410
Inline: False
Direct callers:
  - mm/shmem.c:shmem_rename2
```
**Symbols:**

```
ffffffff8128e640-ffffffff8128e672: d_rehash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void d_rehash(struct dentry *entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812b4ae0)
Location: fs/dcache.c:2424
Inline: False
Direct callers:
  - mm/shmem.c:shmem_rename2
```
**Symbols:**

```
ffffffff812b4ae0-ffffffff812b4b12: d_rehash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void d_rehash(struct dentry *entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812c9c80)
Location: fs/dcache.c:2405
Inline: False
Direct callers:
  - mm/shmem.c:shmem_rename2
```
**Symbols:**

```
ffffffff812c9c80-ffffffff812c9cb2: d_rehash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void d_rehash(struct dentry *entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812e6680)
Location: fs/dcache.c:2475
Inline: False
Direct callers:
  - mm/shmem.c:shmem_rename2
```
**Symbols:**

```
ffffffff812e6680-ffffffff812e66b4: d_rehash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void d_rehash(struct dentry *entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812f81e0)
Location: fs/dcache.c:2475
Inline: False
Direct callers:
  - mm/shmem.c:shmem_rename2
```
**Symbols:**

```
ffffffff812f81e0-ffffffff812f8214: d_rehash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void d_rehash(struct dentry *entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81331020)
Location: fs/dcache.c:2496
Inline: False
Direct callers:
  - mm/shmem.c:shmem_rename2
```
**Symbols:**

```
ffffffff81331020-ffffffff81331054: d_rehash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void d_rehash(struct dentry *entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8133c9b0)
Location: fs/dcache.c:2503
Inline: False
Direct callers:
  - mm/shmem.c:shmem_rename2
```
**Symbols:**

```
ffffffff8133c9b0-ffffffff8133c9e4: d_rehash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void d_rehash(struct dentry *entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81342e30)
Location: fs/dcache.c:2530
Inline: False
Direct callers:
  - mm/shmem.c:shmem_rename2
```
**Symbols:**

```
ffffffff81342e30-ffffffff81342e64: d_rehash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void d_rehash(struct dentry *entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81390790)
Location: fs/dcache.c:2531
Inline: False
Direct callers:
  - mm/shmem.c:shmem_rename2
```
**Symbols:**

```
ffffffff81390790-ffffffff813907c4: d_rehash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void d_rehash(struct dentry *entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81412c00)
Location: fs/dcache.c:2556
Inline: False
Direct callers:
  - mm/shmem.c:shmem_rename2
```
**Symbols:**

```
ffffffff81412c00-ffffffff81412c36: d_rehash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void d_rehash(struct dentry *entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8149def0)
Location: fs/dcache.c:2590
Inline: False
Direct callers:
  - mm/shmem.c:shmem_rename2
```
**Symbols:**

```
ffffffff8149def0-ffffffff8149df26: d_rehash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void d_rehash(struct dentry *entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff814d3210)
Location: fs/dcache.c:2590
Inline: False
Direct callers:
  - mm/shmem.c:shmem_rename2
```
**Symbols:**

```
ffffffff814d3210-ffffffff814d3246: d_rehash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void d_rehash(struct dentry *entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff815059a0)
Location: fs/dcache.c:2414
Inline: False
Direct callers:
  - mm/shmem.c:shmem_rename2
```
**Symbols:**

```
ffffffff815059a0-ffffffff815059d6: d_rehash (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void d_rehash(struct dentry *entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffff8000103a59d0)
Location: fs/dcache.c:2475
Inline: False
Direct callers:
  - mm/shmem.c:shmem_rename2
```
**Symbols:**

```
ffff8000103a59d0-ffff8000103a5a70: d_rehash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void d_rehash(struct dentry *entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (c0588840)
Location: fs/dcache.c:2475
Inline: False
Direct callers:
  - mm/shmem.c:shmem_rename2
```
**Symbols:**

```
c0588840-c0588884: d_rehash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void d_rehash(struct dentry *entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (c0000000004a0610)
Location: fs/dcache.c:2475
Inline: False
Direct callers:
  - mm/shmem.c:shmem_rename2
```
**Symbols:**

```
c0000000004a0610-c0000000004a06c8: d_rehash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void d_rehash(struct dentry *entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffe00026c6f8)
Location: fs/dcache.c:2475
Inline: False
Direct callers:
  - mm/shmem.c:shmem_rename2
```
**Symbols:**

```
ffffffe00026c6f8-ffffffe00026c76e: d_rehash (STB_GLOBAL)
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
void d_rehash(struct dentry *entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812f07c0)
Location: fs/dcache.c:2475
Inline: False
Direct callers:
  - mm/shmem.c:shmem_rename2
```
**Symbols:**

```
ffffffff812f07c0-ffffffff812f07f4: d_rehash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void d_rehash(struct dentry *entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812e13f0)
Location: fs/dcache.c:2475
Inline: False
Direct callers:
  - mm/shmem.c:shmem_rename2
```
**Symbols:**

```
ffffffff812e13f0-ffffffff812e1424: d_rehash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void d_rehash(struct dentry *entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812ee5d0)
Location: fs/dcache.c:2475
Inline: False
Direct callers:
  - mm/shmem.c:shmem_rename2
```
**Symbols:**

```
ffffffff812ee5d0-ffffffff812ee604: d_rehash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void d_rehash(struct dentry *entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812ffff0)
Location: fs/dcache.c:2475
Inline: False
Direct callers:
  - mm/shmem.c:shmem_rename2
```
**Symbols:**

```
ffffffff812ffff0-ffffffff81300022: d_rehash (STB_GLOBAL)
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
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
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
