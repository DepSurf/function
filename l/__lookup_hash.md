# Function: <code>__lookup_hash</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct dentry *__lookup_hash(struct qstr *name, struct dentry *base, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81217d20)
Location: fs/namei.c:1510
Inline: False
Direct callers:
  - fs/namei.c:lookup_one_len
  - fs/namei.c:walk_component
  - fs/namei.c:filename_create
  - fs/namei.c:do_rmdir
  - fs/namei.c:do_unlinkat
  - fs/namei.c:kern_path_locked
  - fs/namei.c:SyS_renameat
  - fs/namei.c:SyS_renameat
  - fs/namei.c:SyS_rename
  - fs/namei.c:SyS_rename
```
**Symbols:**

```
ffffffff81217d20-ffffffff81217d7f: __lookup_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct dentry *__lookup_hash(const struct qstr *name, struct dentry *base, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8123ee20)
Location: fs/namei.c:1519
Inline: True
Direct callers:
  - fs/namei.c:SyS_rename
  - fs/namei.c:SyS_rename
  - fs/namei.c:SyS_renameat
  - fs/namei.c:SyS_renameat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:filename_create
  - fs/namei.c:lookup_one_len
  - fs/namei.c:kern_path_locked
```
**Symbols:**

```
ffffffff8123ee20-ffffffff8123eeb8: __lookup_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct dentry *__lookup_hash(const struct qstr *name, struct dentry *base, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81251bf0)
Location: fs/namei.c:1515
Inline: True
Direct callers:
  - fs/namei.c:SyS_rename
  - fs/namei.c:SyS_rename
  - fs/namei.c:SyS_renameat
  - fs/namei.c:SyS_renameat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:filename_create
  - fs/namei.c:lookup_one_len
  - fs/namei.c:kern_path_locked
```
**Symbols:**

```
ffffffff81251bf0-ffffffff81251c88: __lookup_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct dentry *__lookup_hash(const struct qstr *name, struct dentry *base, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8125dbe0)
Location: fs/namei.c:1522
Inline: True
Direct callers:
  - fs/namei.c:SyS_rename
  - fs/namei.c:SyS_rename
  - fs/namei.c:SyS_renameat
  - fs/namei.c:SyS_renameat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:filename_create
  - fs/namei.c:lookup_one_len
  - fs/namei.c:kern_path_locked
```
**Symbols:**

```
ffffffff8125dbe0-ffffffff8125dc78: __lookup_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct dentry *__lookup_hash(const struct qstr *name, struct dentry *base, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8127ff40)
Location: fs/namei.c:1520
Inline: True
Direct callers:
  - fs/namei.c:SyS_rename
  - fs/namei.c:SyS_rename
  - fs/namei.c:SyS_renameat
  - fs/namei.c:SyS_renameat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:filename_create
  - fs/namei.c:lookup_one_len
  - fs/namei.c:kern_path_locked
```
**Symbols:**

```
ffffffff8127ff40-ffffffff8127ffde: __lookup_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct dentry *__lookup_hash(const struct qstr *name, struct dentry *base, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812a64e0)
Location: fs/namei.c:1487
Inline: False
Direct callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:filename_create
  - fs/namei.c:kern_path_locked
```
**Symbols:**

```
ffffffff812a64e0-ffffffff812a657c: __lookup_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct dentry *__lookup_hash(const struct qstr *name, struct dentry *base, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812bb5b0)
Location: fs/namei.c:1528
Inline: False
Direct callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:filename_create
  - fs/namei.c:kern_path_locked
```
**Symbols:**

```
ffffffff812bb5b0-ffffffff812bb64c: __lookup_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct dentry *__lookup_hash(const struct qstr *name, struct dentry *base, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812d81b0)
Location: fs/namei.c:1526
Inline: False
Direct callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:filename_create
  - fs/namei.c:kern_path_locked
```
**Symbols:**

```
ffffffff812d81b0-ffffffff812d824c: __lookup_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct dentry *__lookup_hash(const struct qstr *name, struct dentry *base, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812e9d20)
Location: fs/namei.c:1521
Inline: False
Direct callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:filename_create
  - fs/namei.c:kern_path_locked
```
**Symbols:**

```
ffffffff812e9d20-ffffffff812e9dbc: __lookup_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct dentry *__lookup_hash(const struct qstr *name, struct dentry *base, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81321d10)
Location: fs/namei.c:1427
Inline: False
Direct callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:filename_create
  - fs/namei.c:kern_path_locked
```
**Symbols:**

```
ffffffff81321d10-ffffffff81321dac: __lookup_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct dentry *__lookup_hash(const struct qstr *name, struct dentry *base, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8132d2d0)
Location: fs/namei.c:1427
Inline: False
Direct callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:filename_create
  - fs/namei.c:kern_path_locked
```
**Symbols:**

```
ffffffff8132d2d0-ffffffff8132d36c: __lookup_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct dentry *__lookup_hash(const struct qstr *name, struct dentry *base, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81332dc0)
Location: fs/namei.c:1512
Inline: False
Direct callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:filename_create
  - fs/namei.c:kern_path_locked
```
**Symbols:**

```
ffffffff81332dc0-ffffffff81332e59: __lookup_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct dentry *__lookup_hash(const struct qstr *name, struct dentry *base, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81380550)
Location: fs/namei.c:1540
Inline: False
Direct callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:filename_create
  - fs/namei.c:kern_path_locked
```
**Symbols:**

```
ffffffff81380550-ffffffff813805e9: __lookup_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct dentry *__lookup_hash(const struct qstr *name, struct dentry *base, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff814005e0)
Location: fs/namei.c:1586
Inline: False
Direct callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:filename_create
  - fs/namei.c:kern_path_locked
```
**Symbols:**

```
ffffffff814005e0-ffffffff81400685: __lookup_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct dentry *__lookup_hash(const struct qstr *name, struct dentry *base, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8148a660)
Location: fs/namei.c:1583
Inline: False
Direct callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:filename_create
  - fs/namei.c:kern_path_locked
```
**Symbols:**

```
ffffffff8148a660-ffffffff8148a705: __lookup_hash (STB_LOCAL)
```
</details>
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
struct dentry *__lookup_hash(const struct qstr *name, struct dentry *base, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffff800010393250)
Location: fs/namei.c:1521
Inline: False
Direct callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:filename_create
  - fs/namei.c:kern_path_locked
```
**Symbols:**

```
ffff800010393250-ffff800010393328: __lookup_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct dentry *__lookup_hash(const struct qstr *name, struct dentry *base, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (c057a31c)
Location: fs/namei.c:1521
Inline: False
Direct callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:filename_create
  - fs/namei.c:kern_path_locked
```
**Symbols:**

```
c057a31c-c057a3b4: __lookup_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct dentry *__lookup_hash(const struct qstr *name, struct dentry *base, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (c00000000048c9b0)
Location: fs/namei.c:1521
Inline: False
Direct callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:filename_create
  - fs/namei.c:kern_path_locked
```
**Symbols:**

```
c00000000048c9b0-c00000000048cad8: __lookup_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct dentry *__lookup_hash(const struct qstr *name, struct dentry *base, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffe0002622c0)
Location: fs/namei.c:1521
Inline: False
Direct callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:filename_create
  - fs/namei.c:kern_path_locked
```
**Symbols:**

```
ffffffe0002622c0-ffffffe00026234c: __lookup_hash (STB_LOCAL)
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
struct dentry *__lookup_hash(const struct qstr *name, struct dentry *base, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812e2300)
Location: fs/namei.c:1521
Inline: False
Direct callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:filename_create
  - fs/namei.c:kern_path_locked
```
**Symbols:**

```
ffffffff812e2300-ffffffff812e239c: __lookup_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct dentry *__lookup_hash(const struct qstr *name, struct dentry *base, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812d2f40)
Location: fs/namei.c:1521
Inline: False
Direct callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:filename_create
  - fs/namei.c:kern_path_locked
```
**Symbols:**

```
ffffffff812d2f40-ffffffff812d2fdc: __lookup_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct dentry *__lookup_hash(const struct qstr *name, struct dentry *base, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812e0110)
Location: fs/namei.c:1521
Inline: False
Direct callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:filename_create
  - fs/namei.c:kern_path_locked
```
**Symbols:**

```
ffffffff812e0110-ffffffff812e01ac: __lookup_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct dentry *__lookup_hash(const struct qstr *name, struct dentry *base, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812f1970)
Location: fs/namei.c:1521
Inline: False
Direct callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:filename_create
  - fs/namei.c:kern_path_locked
```
**Symbols:**

```
ffffffff812f1970-ffffffff812f1a0c: __lookup_hash (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct qstr *name</code> ➡️ <code>const struct qstr *name</code>
</li>
</ul>
</details>
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
