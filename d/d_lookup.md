# Function: <code>d_lookup</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct dentry *d_lookup(const struct dentry *parent, const struct qstr *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81225f10)
Location: fs/dcache.c:2232
Inline: False
Direct callers:
  - fs/namei.c:path_mountpoint
  - fs/dcache.c:d_hash_and_lookup
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_reverse_inval_entry
```
**Symbols:**

```
ffffffff81225f10-ffffffff81225f52: d_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct dentry *d_lookup(const struct dentry *parent, const struct qstr *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8124e560)
Location: fs/dcache.c:2180
Inline: False
Direct callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_mountpoint
  - fs/namei.c:lookup_dcache
  - fs/dcache.c:d_hash_and_lookup
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_reverse_inval_entry
```
**Symbols:**

```
ffffffff8124e560-ffffffff8124e5a9: d_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct dentry *d_lookup(const struct dentry *parent, const struct qstr *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81261640)
Location: fs/dcache.c:2189
Inline: False
Direct callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_mountpoint
  - fs/namei.c:lookup_dcache
  - fs/dcache.c:d_hash_and_lookup
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_reverse_inval_entry
```
**Symbols:**

```
ffffffff81261640-ffffffff81261689: d_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct dentry *d_lookup(const struct dentry *parent, const struct qstr *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8126ee90)
Location: fs/dcache.c:2219
Inline: False
Direct callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_mountpoint
  - fs/namei.c:lookup_dcache
  - fs/dcache.c:d_hash_and_lookup
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_reverse_inval_entry
```
**Symbols:**

```
ffffffff8126ee90-ffffffff8126eed9: d_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct dentry *d_lookup(const struct dentry *parent, const struct qstr *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812917a0)
Location: fs/dcache.c:2231
Inline: False
Direct callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_mountpoint
  - fs/namei.c:lookup_dcache
  - fs/dcache.c:d_hash_and_lookup
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_reverse_inval_entry
```
**Symbols:**

```
ffffffff812917a0-ffffffff812917e9: d_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct dentry *d_lookup(const struct dentry *parent, const struct qstr *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812b7df0)
Location: fs/dcache.c:2255
Inline: False
Direct callers:
  - fs/namei.c:lookup_open
  - fs/namei.c:path_mountpoint
  - fs/namei.c:lookup_dcache
  - fs/dcache.c:d_hash_and_lookup
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_reverse_inval_entry
```
**Symbols:**

```
ffffffff812b7df0-ffffffff812b7e3b: d_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct dentry *d_lookup(const struct dentry *parent, const struct qstr *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812ccf50)
Location: fs/dcache.c:2236
Inline: False
Direct callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_mountpoint
  - fs/namei.c:lookup_dcache
  - fs/dcache.c:d_hash_and_lookup
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/readdir.c:fuse_readdir
```
**Symbols:**

```
ffffffff812ccf50-ffffffff812ccf9b: d_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct dentry *d_lookup(const struct dentry *parent, const struct qstr *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812e9b50)
Location: fs/dcache.c:2308
Inline: False
Direct callers:
  - fs/namei.c:lookup_open
  - fs/namei.c:path_mountpoint
  - fs/namei.c:lookup_dcache
  - fs/dcache.c:d_hash_and_lookup
  - fs/fuse/dir.c:fuse_reverse_inval_entry
```
**Symbols:**

```
ffffffff812e9b50-ffffffff812e9b95: d_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct dentry *d_lookup(const struct dentry *parent, const struct qstr *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812fb6f0)
Location: fs/dcache.c:2308
Inline: False
Direct callers:
  - fs/namei.c:lookup_open
  - fs/namei.c:path_mountpoint
  - fs/namei.c:lookup_dcache
  - fs/dcache.c:d_hash_and_lookup
  - fs/fuse/dir.c:fuse_reverse_inval_entry
```
**Symbols:**

```
ffffffff812fb6f0-ffffffff812fb735: d_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct dentry *d_lookup(const struct dentry *parent, const struct qstr *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff813343b0)
Location: fs/dcache.c:2329
Inline: True
Inline callers:
  - fs/dcache.c:d_hash_and_lookup
Direct callers:
  - fs/namei.c:lookup_dcache
  - fs/fuse/dir.c:fuse_reverse_inval_entry
```
**Symbols:**

```
ffffffff813343b0-ffffffff813343f7: d_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct dentry *d_lookup(const struct dentry *parent, const struct qstr *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8133fd70)
Location: fs/dcache.c:2336
Inline: True
Inline callers:
  - fs/dcache.c:d_hash_and_lookup
Direct callers:
  - fs/namei.c:lookup_dcache
  - fs/fuse/dir.c:fuse_reverse_inval_entry
```
**Symbols:**

```
ffffffff8133fd70-ffffffff8133fdb4: d_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct dentry *d_lookup(const struct dentry *parent, const struct qstr *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81346284)
Location: fs/dcache.c:2363
Inline: True
Inline callers:
  - fs/dcache.c:d_hash_and_lookup
Direct callers:
  - fs/namei.c:lookup_dcache
  - fs/fuse/dir.c:fuse_reverse_inval_entry
```
**Symbols:**

```
ffffffff813461f0-ffffffff81346234: d_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct dentry *d_lookup(const struct dentry *parent, const struct qstr *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81393e84)
Location: fs/dcache.c:2364
Inline: True
Inline callers:
  - fs/dcache.c:d_hash_and_lookup
Direct callers:
  - fs/namei.c:lookup_dcache
  - fs/fuse/dir.c:fuse_reverse_inval_entry
```
**Symbols:**

```
ffffffff81393df0-ffffffff81393e34: d_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct dentry *d_lookup(const struct dentry *parent, const struct qstr *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81415775)
Location: fs/dcache.c:2389
Inline: True
Inline callers:
  - fs/dcache.c:d_hash_and_lookup
Direct callers:
  - fs/namei.c:lookup_dcache
  - fs/fuse/dir.c:fuse_reverse_inval_entry
```
**Symbols:**

```
ffffffff814156e0-ffffffff8141572e: d_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct dentry *d_lookup(const struct dentry *parent, const struct qstr *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff814a0a95)
Location: fs/dcache.c:2423
Inline: True
Inline callers:
  - fs/dcache.c:d_hash_and_lookup
Direct callers:
  - fs/namei.c:lookup_dcache
  - fs/fuse/dir.c:fuse_reverse_inval_entry
```
**Symbols:**

```
ffffffff814a09f0-ffffffff814a0a3e: d_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct dentry *d_lookup(const struct dentry *parent, const struct qstr *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff814d5da5)
Location: fs/dcache.c:2423
Inline: True
Inline callers:
  - fs/dcache.c:d_hash_and_lookup
Direct callers:
  - fs/namei.c:lookup_dcache
  - fs/fuse/dir.c:fuse_reverse_inval_entry
```
**Symbols:**

```
ffffffff814d5d00-ffffffff814d5d4e: d_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct dentry *d_lookup(const struct dentry *parent, const struct qstr *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff815081a5)
Location: fs/dcache.c:2247
Inline: True
Inline callers:
  - fs/dcache.c:d_hash_and_lookup
Direct callers:
  - fs/namei.c:lookup_dcache
  - fs/fuse/dir.c:fuse_reverse_inval_entry
```
**Symbols:**

```
ffffffff81508100-ffffffff8150814e: d_lookup (STB_GLOBAL)
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
struct dentry *d_lookup(const struct dentry *parent, const struct qstr *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffff8000103aab98)
Location: fs/dcache.c:2308
Inline: False
Direct callers:
  - fs/namei.c:lookup_open
  - fs/namei.c:path_mountpoint
  - fs/namei.c:lookup_dcache
  - fs/dcache.c:d_hash_and_lookup
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/readdir.c:parse_dirplusfile
```
**Symbols:**

```
ffff8000103aab98-ffff8000103aac04: d_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct dentry *d_lookup(const struct dentry *parent, const struct qstr *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (c058bb44)
Location: fs/dcache.c:2308
Inline: False
Direct callers:
  - fs/namei.c:lookup_open
  - fs/namei.c:path_mountpoint
  - fs/namei.c:lookup_dcache
  - fs/dcache.c:d_hash_and_lookup
  - fs/proc/proc_sysctl.c:proc_sys_fill_cache
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/readdir.c:parse_dirplusfile
```
**Symbols:**

```
c058bb44-c058bbd8: d_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct dentry *d_lookup(const struct dentry *parent, const struct qstr *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (c0000000004a5d00)
Location: fs/dcache.c:2308
Inline: False
Direct callers:
  - fs/namei.c:lookup_open
  - fs/namei.c:path_mountpoint
  - fs/namei.c:lookup_dcache
  - fs/dcache.c:d_hash_and_lookup
  - fs/proc/proc_sysctl.c:proc_sys_fill_cache
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/readdir.c:parse_dirplusfile
```
**Symbols:**

```
c0000000004a5d00-c0000000004a5d9c: d_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct dentry *d_lookup(const struct dentry *parent, const struct qstr *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffe000270728)
Location: fs/dcache.c:2308
Inline: False
Direct callers:
  - fs/namei.c:lookup_open
  - fs/namei.c:path_mountpoint
  - fs/namei.c:lookup_dcache
  - fs/dcache.c:d_hash_and_lookup
  - fs/proc/proc_sysctl.c:proc_sys_fill_cache
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
**Symbols:**

```
ffffffe000270728-ffffffe000270790: d_lookup (STB_GLOBAL)
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
struct dentry *d_lookup(const struct dentry *parent, const struct qstr *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812f3cd0)
Location: fs/dcache.c:2308
Inline: False
Direct callers:
  - fs/namei.c:lookup_open
  - fs/namei.c:path_mountpoint
  - fs/namei.c:lookup_dcache
  - fs/dcache.c:d_hash_and_lookup
  - fs/fuse/dir.c:fuse_reverse_inval_entry
```
**Symbols:**

```
ffffffff812f3cd0-ffffffff812f3d15: d_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct dentry *d_lookup(const struct dentry *parent, const struct qstr *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812e4900)
Location: fs/dcache.c:2308
Inline: False
Direct callers:
  - fs/namei.c:lookup_open
  - fs/namei.c:path_mountpoint
  - fs/namei.c:lookup_dcache
  - fs/dcache.c:d_hash_and_lookup
  - fs/fuse/dir.c:fuse_reverse_inval_entry
```
**Symbols:**

```
ffffffff812e4900-ffffffff812e4945: d_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct dentry *d_lookup(const struct dentry *parent, const struct qstr *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812f1ae0)
Location: fs/dcache.c:2308
Inline: False
Direct callers:
  - fs/namei.c:lookup_open
  - fs/namei.c:path_mountpoint
  - fs/namei.c:lookup_dcache
  - fs/dcache.c:d_hash_and_lookup
  - fs/fuse/dir.c:fuse_reverse_inval_entry
```
**Symbols:**

```
ffffffff812f1ae0-ffffffff812f1b25: d_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct dentry *d_lookup(const struct dentry *parent, const struct qstr *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81302d00)
Location: fs/dcache.c:2308
Inline: False
Direct callers:
  - fs/namei.c:lookup_open
  - fs/namei.c:path_mountpoint
  - fs/namei.c:lookup_dcache
  - fs/dcache.c:d_hash_and_lookup
  - fs/fuse/dir.c:fuse_reverse_inval_entry
```
**Symbols:**

```
ffffffff81302d00-ffffffff81302d45: d_lookup (STB_GLOBAL)
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
