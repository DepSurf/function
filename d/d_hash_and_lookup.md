# Function: <code>d_hash_and_lookup</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct dentry *d_hash_and_lookup(struct dentry *dir, struct qstr *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81225f60)
Location: fs/dcache.c:2340
Inline: False
Direct callers:
  - fs/dcache.c:d_add_ci
  - fs/proc/base.c:proc_fill_cache
  - fs/proc/base.c:proc_flush_task
  - fs/proc/base.c:proc_flush_task
  - fs/proc/base.c:proc_flush_task
  - fs/proc/base.c:proc_flush_task
```
**Symbols:**

```
ffffffff81225f60-ffffffff81225fad: d_hash_and_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct dentry *d_hash_and_lookup(struct dentry *dir, struct qstr *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8124e5b0)
Location: fs/dcache.c:2273
Inline: False
Direct callers:
  - fs/namei.c:path_pts
  - fs/proc/base.c:proc_flush_task
  - fs/proc/base.c:proc_flush_task
  - fs/proc/base.c:proc_flush_task
  - fs/proc/base.c:proc_flush_task
  - fs/proc/base.c:proc_fill_cache
```
**Symbols:**

```
ffffffff8124e5b0-ffffffff8124e5fd: d_hash_and_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct dentry *d_hash_and_lookup(struct dentry *dir, struct qstr *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81261690)
Location: fs/dcache.c:2282
Inline: False
Direct callers:
  - fs/namei.c:path_pts
  - fs/proc/base.c:proc_flush_task
  - fs/proc/base.c:proc_flush_task
  - fs/proc/base.c:proc_flush_task
  - fs/proc/base.c:proc_flush_task
  - fs/proc/base.c:proc_fill_cache
```
**Symbols:**

```
ffffffff81261690-ffffffff812616dd: d_hash_and_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct dentry *d_hash_and_lookup(struct dentry *dir, struct qstr *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8126eee0)
Location: fs/dcache.c:2312
Inline: False
Direct callers:
  - fs/namei.c:path_pts
  - fs/proc/base.c:proc_flush_task
  - fs/proc/base.c:proc_flush_task
  - fs/proc/base.c:proc_flush_task
  - fs/proc/base.c:proc_flush_task
  - fs/proc/base.c:proc_fill_cache
```
**Symbols:**

```
ffffffff8126eee0-ffffffff8126ef2d: d_hash_and_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct dentry *d_hash_and_lookup(struct dentry *dir, struct qstr *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812917f0)
Location: fs/dcache.c:2324
Inline: False
Direct callers:
  - fs/namei.c:path_pts
  - fs/proc/base.c:proc_flush_task
  - fs/proc/base.c:proc_flush_task
  - fs/proc/base.c:proc_flush_task
  - fs/proc/base.c:proc_flush_task
  - fs/proc/base.c:proc_fill_cache
```
**Symbols:**

```
ffffffff812917f0-ffffffff81291843: d_hash_and_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct dentry *d_hash_and_lookup(struct dentry *dir, struct qstr *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812b7e40)
Location: fs/dcache.c:2348
Inline: False
Direct callers:
  - fs/namei.c:path_pts
  - fs/proc/base.c:proc_flush_task
  - fs/proc/base.c:proc_flush_task
  - fs/proc/base.c:proc_flush_task
  - fs/proc/base.c:proc_flush_task
  - fs/proc/base.c:proc_fill_cache
  - security/selinux/selinuxfs.c:init_sel_fs
```
**Symbols:**

```
ffffffff812b7e40-ffffffff812b7e93: d_hash_and_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct dentry *d_hash_and_lookup(struct dentry *dir, struct qstr *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812ccfa0)
Location: fs/dcache.c:2329
Inline: False
Direct callers:
  - fs/namei.c:path_pts
  - fs/proc/base.c:proc_flush_task
  - fs/proc/base.c:proc_flush_task
  - fs/proc/base.c:proc_flush_task
  - fs/proc/base.c:proc_flush_task
  - fs/proc/base.c:proc_fill_cache
  - security/selinux/selinuxfs.c:init_sel_fs
```
**Symbols:**

```
ffffffff812ccfa0-ffffffff812ccff3: d_hash_and_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct dentry *d_hash_and_lookup(struct dentry *dir, struct qstr *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812e9ba0)
Location: fs/dcache.c:2401
Inline: False
Direct callers:
  - fs/namei.c:path_pts
  - fs/proc/base.c:proc_flush_task
  - fs/proc/base.c:proc_flush_task
  - fs/proc/base.c:proc_flush_task
  - fs/proc/base.c:proc_flush_task
  - fs/proc/base.c:proc_fill_cache
  - security/selinux/selinuxfs.c:init_sel_fs
```
**Symbols:**

```
ffffffff812e9ba0-ffffffff812e9bf6: d_hash_and_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct dentry *d_hash_and_lookup(struct dentry *dir, struct qstr *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812fb740)
Location: fs/dcache.c:2401
Inline: False
Direct callers:
  - fs/namei.c:path_pts
  - fs/proc/base.c:proc_flush_task
  - fs/proc/base.c:proc_flush_task
  - fs/proc/base.c:proc_flush_task
  - fs/proc/base.c:proc_flush_task
  - fs/proc/base.c:proc_fill_cache
  - security/selinux/selinuxfs.c:init_sel_fs
```
**Symbols:**

```
ffffffff812fb740-ffffffff812fb796: d_hash_and_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct dentry *d_hash_and_lookup(struct dentry *dir, struct qstr *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81334400)
Location: fs/dcache.c:2422
Inline: False
Direct callers:
  - fs/namei.c:path_pts
  - fs/proc/base.c:proc_fill_cache
  - security/selinux/selinuxfs.c:init_sel_fs
```
**Symbols:**

```
ffffffff81334400-ffffffff81334478: d_hash_and_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct dentry *d_hash_and_lookup(struct dentry *dir, struct qstr *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8133fdc0)
Location: fs/dcache.c:2429
Inline: False
Direct callers:
  - fs/namei.c:path_pts
  - fs/proc/base.c:proc_fill_cache
  - security/selinux/selinuxfs.c:init_sel_fs
```
**Symbols:**

```
ffffffff8133fdc0-ffffffff8133fe36: d_hash_and_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct dentry *d_hash_and_lookup(struct dentry *dir, struct qstr *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81346240)
Location: fs/dcache.c:2456
Inline: False
Direct callers:
  - fs/namei.c:path_pts
  - fs/proc/base.c:proc_fill_cache
  - security/selinux/selinuxfs.c:init_sel_fs
```
**Symbols:**

```
ffffffff81346240-ffffffff813462b6: d_hash_and_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct dentry *d_hash_and_lookup(struct dentry *dir, struct qstr *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81393e40)
Location: fs/dcache.c:2457
Inline: False
Direct callers:
  - fs/namei.c:path_pts
  - fs/proc/base.c:proc_fill_cache
  - security/selinux/selinuxfs.c:init_sel_fs
```
**Symbols:**

```
ffffffff81393e40-ffffffff81393eb6: d_hash_and_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct dentry *d_hash_and_lookup(struct dentry *dir, struct qstr *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81415730)
Location: fs/dcache.c:2482
Inline: False
Direct callers:
  - fs/namei.c:path_pts
  - fs/proc/base.c:proc_fill_cache
  - security/selinux/selinuxfs.c:init_sel_fs
```
**Symbols:**

```
ffffffff81415730-ffffffff814157b1: d_hash_and_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct dentry *d_hash_and_lookup(struct dentry *dir, struct qstr *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff814a0a50)
Location: fs/dcache.c:2516
Inline: False
Direct callers:
  - fs/namei.c:path_pts
  - fs/proc/base.c:proc_fill_cache
  - security/selinux/selinuxfs.c:init_sel_fs
```
**Symbols:**

```
ffffffff814a0a50-ffffffff814a0ad1: d_hash_and_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct dentry *d_hash_and_lookup(struct dentry *dir, struct qstr *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff814d5d60)
Location: fs/dcache.c:2516
Inline: False
Direct callers:
  - fs/namei.c:path_pts
  - fs/proc/base.c:proc_fill_cache
  - security/selinux/selinuxfs.c:init_sel_fs
```
**Symbols:**

```
ffffffff814d5d60-ffffffff814d5de1: d_hash_and_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct dentry *d_hash_and_lookup(struct dentry *dir, struct qstr *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81508160)
Location: fs/dcache.c:2340
Inline: False
Direct callers:
  - fs/namei.c:path_pts
  - fs/proc/base.c:proc_fill_cache
  - security/selinux/selinuxfs.c:init_sel_fs
```
**Symbols:**

```
ffffffff81508160-ffffffff815081e1: d_hash_and_lookup (STB_GLOBAL)
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
struct dentry *d_hash_and_lookup(struct dentry *dir, struct qstr *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffff8000103aac08)
Location: fs/dcache.c:2401
Inline: False
Direct callers:
  - fs/namei.c:path_pts
  - fs/proc/base.c:proc_flush_task
  - fs/proc/base.c:proc_flush_task
  - fs/proc/base.c:proc_flush_task
  - fs/proc/base.c:proc_flush_task
  - fs/proc/base.c:proc_fill_cache
  - security/selinux/selinuxfs.c:init_sel_fs
```
**Symbols:**

```
ffff8000103aac08-ffff8000103aac78: d_hash_and_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct dentry *d_hash_and_lookup(struct dentry *dir, struct qstr *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (c058bbd8)
Location: fs/dcache.c:2401
Inline: False
Direct callers:
  - fs/namei.c:path_pts
  - fs/proc/base.c:proc_flush_task
  - fs/proc/base.c:proc_flush_task
  - fs/proc/base.c:proc_flush_task
  - fs/proc/base.c:proc_flush_task
  - fs/proc/base.c:proc_fill_cache
  - security/selinux/selinuxfs.c:init_sel_fs
```
**Symbols:**

```
c058bbd8-c058bc3c: d_hash_and_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct dentry *d_hash_and_lookup(struct dentry *dir, struct qstr *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (c0000000004a5da0)
Location: fs/dcache.c:2401
Inline: False
Direct callers:
  - fs/namei.c:path_pts
  - fs/proc/base.c:proc_flush_task
  - fs/proc/base.c:proc_flush_task
  - fs/proc/base.c:proc_flush_task
  - fs/proc/base.c:proc_flush_task
  - fs/proc/base.c:proc_fill_cache
  - security/selinux/selinuxfs.c:init_sel_fs
```
**Symbols:**

```
c0000000004a5da0-c0000000004a5e58: d_hash_and_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct dentry *d_hash_and_lookup(struct dentry *dir, struct qstr *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffe000270790)
Location: fs/dcache.c:2401
Inline: False
Direct callers:
  - fs/namei.c:path_pts
  - fs/proc/base.c:proc_flush_task
  - fs/proc/base.c:proc_flush_task
  - fs/proc/base.c:proc_flush_task
  - fs/proc/base.c:proc_flush_task
  - fs/proc/base.c:proc_fill_cache
  - security/selinux/selinuxfs.c:init_sel_fs
```
**Symbols:**

```
ffffffe000270790-ffffffe0002707ea: d_hash_and_lookup (STB_GLOBAL)
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
struct dentry *d_hash_and_lookup(struct dentry *dir, struct qstr *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812f3d20)
Location: fs/dcache.c:2401
Inline: False
Direct callers:
  - fs/namei.c:path_pts
  - fs/proc/base.c:proc_flush_task
  - fs/proc/base.c:proc_flush_task
  - fs/proc/base.c:proc_flush_task
  - fs/proc/base.c:proc_flush_task
  - fs/proc/base.c:proc_fill_cache
  - security/selinux/selinuxfs.c:init_sel_fs
```
**Symbols:**

```
ffffffff812f3d20-ffffffff812f3d76: d_hash_and_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct dentry *d_hash_and_lookup(struct dentry *dir, struct qstr *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812e4950)
Location: fs/dcache.c:2401
Inline: False
Direct callers:
  - fs/namei.c:path_pts
  - fs/proc/base.c:proc_flush_task
  - fs/proc/base.c:proc_flush_task
  - fs/proc/base.c:proc_flush_task
  - fs/proc/base.c:proc_flush_task
  - fs/proc/base.c:proc_fill_cache
  - security/selinux/selinuxfs.c:init_sel_fs
```
**Symbols:**

```
ffffffff812e4950-ffffffff812e49a6: d_hash_and_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct dentry *d_hash_and_lookup(struct dentry *dir, struct qstr *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812f1b30)
Location: fs/dcache.c:2401
Inline: False
Direct callers:
  - fs/namei.c:path_pts
  - fs/proc/base.c:proc_flush_task
  - fs/proc/base.c:proc_flush_task
  - fs/proc/base.c:proc_flush_task
  - fs/proc/base.c:proc_flush_task
  - fs/proc/base.c:proc_fill_cache
  - security/selinux/selinuxfs.c:init_sel_fs
```
**Symbols:**

```
ffffffff812f1b30-ffffffff812f1b86: d_hash_and_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct dentry *d_hash_and_lookup(struct dentry *dir, struct qstr *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81302d50)
Location: fs/dcache.c:2401
Inline: False
Direct callers:
  - fs/namei.c:path_pts
  - fs/proc/base.c:proc_flush_task
  - fs/proc/base.c:proc_flush_task
  - fs/proc/base.c:proc_flush_task
  - fs/proc/base.c:proc_flush_task
  - fs/proc/base.c:proc_fill_cache
  - security/selinux/selinuxfs.c:init_sel_fs
```
**Symbols:**

```
ffffffff81302d50-ffffffff81302da6: d_hash_and_lookup (STB_GLOBAL)
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
