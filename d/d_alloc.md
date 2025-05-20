# Function: <code>d_alloc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct dentry *d_alloc(struct dentry *parent, const struct qstr *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812258f0)
Location: fs/dcache.c:1617
Inline: False
Direct callers:
  - mm/shmem.c:shmem_rename2
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_openat
  - fs/dcache.c:d_alloc_name
  - fs/dcache.c:d_add_ci
  - fs/libfs.c:dcache_dir_open
  - fs/proc/base.c:proc_fill_cache
  - fs/fuse/dir.c:fuse_readdir
  - fs/efivarfs/super.c:efivarfs_callback
```
**Symbols:**

```
ffffffff812258f0-ffffffff8122596c: d_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct dentry *d_alloc(struct dentry *parent, const struct qstr *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8124da30)
Location: fs/dcache.c:1644
Inline: False
Direct callers:
  - mm/shmem.c:shmem_rename2
  - fs/namei.c:path_openat
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_name
  - fs/efivarfs/super.c:efivarfs_callback
```
**Symbols:**

```
ffffffff8124da30-ffffffff8124dab4: d_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct dentry *d_alloc(struct dentry *parent, const struct qstr *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81260b10)
Location: fs/dcache.c:1653
Inline: False
Direct callers:
  - mm/shmem.c:shmem_rename2
  - fs/namei.c:path_openat
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_name
  - fs/efivarfs/super.c:efivarfs_callback
```
**Symbols:**

```
ffffffff81260b10-ffffffff81260b94: d_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct dentry *d_alloc(struct dentry *parent, const struct qstr *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8126e2e0)
Location: fs/dcache.c:1683
Inline: False
Direct callers:
  - mm/shmem.c:shmem_rename2
  - fs/namei.c:vfs_tmpfile
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_name
  - fs/efivarfs/super.c:efivarfs_callback
```
**Symbols:**

```
ffffffff8126e2e0-ffffffff8126e364: d_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct dentry *d_alloc(struct dentry *parent, const struct qstr *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81290c00)
Location: fs/dcache.c:1695
Inline: False
Direct callers:
  - mm/shmem.c:shmem_rename2
  - fs/namei.c:vfs_tmpfile
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_name
  - fs/efivarfs/super.c:efivarfs_callback
```
**Symbols:**

```
ffffffff81290c00-ffffffff81290c84: d_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct dentry *d_alloc(struct dentry *parent, const struct qstr *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812b7400)
Location: fs/dcache.c:1697
Inline: False
Direct callers:
  - mm/shmem.c:shmem_rename2
  - fs/namei.c:vfs_tmpfile
  - fs/namei.c:__lookup_hash
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_name
  - fs/efivarfs/super.c:efivarfs_callback
```
**Symbols:**

```
ffffffff812b7400-ffffffff812b7484: d_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct dentry *d_alloc(struct dentry *parent, const struct qstr *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812cc560)
Location: fs/dcache.c:1700
Inline: False
Direct callers:
  - mm/shmem.c:shmem_rename2
  - fs/namei.c:vfs_tmpfile
  - fs/namei.c:__lookup_hash
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_name
  - fs/efivarfs/super.c:efivarfs_callback
```
**Symbols:**

```
ffffffff812cc560-ffffffff812cc5e4: d_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct dentry *d_alloc(struct dentry *parent, const struct qstr *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812e9160)
Location: fs/dcache.c:1766
Inline: False
Direct callers:
  - mm/shmem.c:shmem_rename2
  - fs/namei.c:vfs_tmpfile
  - fs/namei.c:__lookup_hash
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_name
  - fs/efivarfs/super.c:efivarfs_callback
```
**Symbols:**

```
ffffffff812e9160-ffffffff812e91dc: d_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct dentry *d_alloc(struct dentry *parent, const struct qstr *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812fad00)
Location: fs/dcache.c:1766
Inline: False
Direct callers:
  - mm/shmem.c:shmem_rename2
  - fs/namei.c:vfs_tmpfile
  - fs/namei.c:__lookup_hash
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_name
  - fs/efivarfs/super.c:efivarfs_callback
```
**Symbols:**

```
ffffffff812fad00-ffffffff812fad7c: d_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct dentry *d_alloc(struct dentry *parent, const struct qstr *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81331140)
Location: fs/dcache.c:1787
Inline: False
Direct callers:
  - mm/shmem.c:shmem_rename2
  - fs/namei.c:vfs_tmpfile
  - fs/namei.c:__lookup_hash
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_name
  - fs/efivarfs/super.c:efivarfs_alloc_dentry
```
**Symbols:**

```
ffffffff81331140-ffffffff813311bc: d_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct dentry *d_alloc(struct dentry *parent, const struct qstr *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8133cad0)
Location: fs/dcache.c:1794
Inline: False
Direct callers:
  - mm/shmem.c:shmem_rename2
  - fs/namei.c:vfs_tmpfile
  - fs/namei.c:__lookup_hash
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_name
  - fs/efivarfs/super.c:efivarfs_alloc_dentry
```
**Symbols:**

```
ffffffff8133cad0-ffffffff8133cb4c: d_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct dentry *d_alloc(struct dentry *parent, const struct qstr *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81342f50)
Location: fs/dcache.c:1821
Inline: False
Direct callers:
  - mm/shmem.c:shmem_rename2
  - fs/namei.c:vfs_tmpfile
  - fs/namei.c:__lookup_hash
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_name
  - fs/efivarfs/super.c:efivarfs_callback
```
**Symbols:**

```
ffffffff81342f50-ffffffff81342fcc: d_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct dentry *d_alloc(struct dentry *parent, const struct qstr *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff813908b0)
Location: fs/dcache.c:1822
Inline: False
Direct callers:
  - mm/shmem.c:shmem_rename2
  - fs/namei.c:vfs_tmpfile
  - fs/namei.c:__lookup_hash
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_name
  - fs/efivarfs/super.c:efivarfs_callback
```
**Symbols:**

```
ffffffff813908b0-ffffffff8139092c: d_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct dentry *d_alloc(struct dentry *parent, const struct qstr *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81414fef)
Location: fs/dcache.c:1847
Inline: True
Inline callers:
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_name
Direct callers:
  - mm/shmem.c:shmem_rename2
  - fs/namei.c:vfs_tmpfile
  - fs/namei.c:__lookup_hash
  - fs/efivarfs/super.c:efivarfs_callback
```
**Symbols:**

```
ffffffff81411dc0-ffffffff81411e44: d_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct dentry *d_alloc(struct dentry *parent, const struct qstr *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff814a0509)
Location: fs/dcache.c:1847
Inline: True
Inline callers:
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_name
Direct callers:
  - mm/shmem.c:shmem_rename2
  - fs/namei.c:vfs_tmpfile
  - fs/namei.c:__lookup_hash
  - fs/efivarfs/super.c:efivarfs_callback
```
**Symbols:**

```
ffffffff8149cb30-ffffffff8149cbb4: d_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct dentry *d_alloc(struct dentry *parent, const struct qstr *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff814d5811)
Location: fs/dcache.c:1847
Inline: True
Inline callers:
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_name
Direct callers:
  - mm/shmem.c:shmem_rename2
  - fs/namei.c:vfs_tmpfile
  - fs/namei.c:lookup_one_qstr_excl
  - fs/efivarfs/super.c:efivarfs_callback
```
**Symbols:**

```
ffffffff814d1f50-ffffffff814d1fd4: d_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct dentry *d_alloc(struct dentry *parent, const struct qstr *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81504920)
Location: fs/dcache.c:1702
Inline: False
Direct callers:
  - mm/shmem.c:shmem_rename2
  - fs/namei.c:vfs_tmpfile
  - fs/namei.c:lookup_one_qstr_excl
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_name
  - fs/efivarfs/super.c:efivarfs_callback
```
**Symbols:**

```
ffffffff81504920-ffffffff815049a9: d_alloc (STB_GLOBAL)
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
struct dentry *d_alloc(struct dentry *parent, const struct qstr *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffff8000103a9f88)
Location: fs/dcache.c:1766
Inline: False
Direct callers:
  - mm/shmem.c:shmem_rename2
  - fs/namei.c:vfs_tmpfile
  - fs/namei.c:__lookup_hash
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_name
  - fs/efivarfs/super.c:efivarfs_callback
```
**Symbols:**

```
ffff8000103a9f88-ffff8000103aa048: d_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct dentry *d_alloc(struct dentry *parent, const struct qstr *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (c058b000)
Location: fs/dcache.c:1766
Inline: False
Direct callers:
  - mm/shmem.c:shmem_rename2
  - fs/namei.c:vfs_tmpfile
  - fs/namei.c:__lookup_hash
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_name
  - fs/efivarfs/super.c:efivarfs_callback
```
**Symbols:**

```
c058b000-c058b07c: d_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct dentry *d_alloc(struct dentry *parent, const struct qstr *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (c0000000004a4db0)
Location: fs/dcache.c:1766
Inline: False
Direct callers:
  - mm/shmem.c:shmem_rename2
  - fs/namei.c:vfs_tmpfile
  - fs/namei.c:__lookup_hash
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_name
```
**Symbols:**

```
c0000000004a4db0-c0000000004a4e80: d_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct dentry *d_alloc(struct dentry *parent, const struct qstr *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffe00026fd82)
Location: fs/dcache.c:1766
Inline: False
Direct callers:
  - mm/shmem.c:shmem_rename2
  - fs/namei.c:vfs_tmpfile
  - fs/namei.c:__lookup_hash
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_name
```
**Symbols:**

```
ffffffe00026fd82-ffffffe00026fe26: d_alloc (STB_GLOBAL)
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
struct dentry *d_alloc(struct dentry *parent, const struct qstr *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812f32e0)
Location: fs/dcache.c:1766
Inline: False
Direct callers:
  - mm/shmem.c:shmem_rename2
  - fs/namei.c:vfs_tmpfile
  - fs/namei.c:__lookup_hash
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_name
  - fs/efivarfs/super.c:efivarfs_callback
```
**Symbols:**

```
ffffffff812f32e0-ffffffff812f335c: d_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct dentry *d_alloc(struct dentry *parent, const struct qstr *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812e3f10)
Location: fs/dcache.c:1766
Inline: False
Direct callers:
  - mm/shmem.c:shmem_rename2
  - fs/namei.c:vfs_tmpfile
  - fs/namei.c:__lookup_hash
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_name
  - fs/efivarfs/super.c:efivarfs_callback
```
**Symbols:**

```
ffffffff812e3f10-ffffffff812e3f8c: d_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct dentry *d_alloc(struct dentry *parent, const struct qstr *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812f10f0)
Location: fs/dcache.c:1766
Inline: False
Direct callers:
  - mm/shmem.c:shmem_rename2
  - fs/namei.c:vfs_tmpfile
  - fs/namei.c:__lookup_hash
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_name
  - fs/efivarfs/super.c:efivarfs_callback
```
**Symbols:**

```
ffffffff812f10f0-ffffffff812f116c: d_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct dentry *d_alloc(struct dentry *parent, const struct qstr *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff813022b0)
Location: fs/dcache.c:1766
Inline: False
Direct callers:
  - mm/shmem.c:shmem_rename2
  - fs/namei.c:vfs_tmpfile
  - fs/namei.c:__lookup_hash
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_name
  - fs/efivarfs/super.c:efivarfs_callback
```
**Symbols:**

```
ffffffff813022b0-ffffffff8130232a: d_alloc (STB_GLOBAL)
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
