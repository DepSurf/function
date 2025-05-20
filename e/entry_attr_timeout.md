# Function: <code>entry_attr_timeout</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff81311dcb)
Location: fs/fuse/dir.c:101
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_lookup_name
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff813480bf)
Location: fs/fuse/dir.c:103
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff8135da1b)
Location: fs/fuse/dir.c:95
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff813724c0)
Location: fs/fuse/dir.c:95
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff813971ce)
Location: fs/fuse/dir.c:95
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff813c613a)
Location: fs/fuse/dir.c:95
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
u64 entry_attr_timeout(struct fuse_entry_out *o);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff813deae6)
Location: fs/fuse/dir.c:79
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/dir.c:fuse_dentry_revalidate
Direct callers:
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_readdir
```
**Symbols:**

```
ffffffff813df610-ffffffff813df633: entry_attr_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
u64 entry_attr_timeout(struct fuse_entry_out *o);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff8140a9c6)
Location: fs/fuse/dir.c:79
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
**Symbols:**

```
ffffffff8140b240-ffffffff8140b263: entry_attr_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
u64 entry_attr_timeout(struct fuse_entry_out *o);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff8142457b)
Location: fs/fuse/dir.c:113
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
**Symbols:**

```
ffffffff81423bd0-ffffffff81423bf3: entry_attr_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
u64 entry_attr_timeout(struct fuse_entry_out *o);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff81473ad9)
Location: fs/fuse/dir.c:113
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
**Symbols:**

```
ffffffff81473050-ffffffff814730c9: entry_attr_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
u64 entry_attr_timeout(struct fuse_entry_out *o);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff8148e3cf)
Location: fs/fuse/dir.c:114
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
**Symbols:**

```
ffffffff8148da20-ffffffff8148da99: entry_attr_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
u64 entry_attr_timeout(struct fuse_entry_out *o);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff81493e1f)
Location: fs/fuse/dir.c:114
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
**Symbols:**

```
ffffffff814932c0-ffffffff81493336: entry_attr_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
u64 entry_attr_timeout(struct fuse_entry_out *o);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff814eb27f)
Location: fs/fuse/dir.c:114
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
**Symbols:**

```
ffffffff814ea720-ffffffff814ea796: entry_attr_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
u64 entry_attr_timeout(struct fuse_entry_out *o);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff81579e0c)
Location: fs/fuse/dir.c:117
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
**Symbols:**

```
ffffffff815791a0-ffffffff8157921e: entry_attr_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
u64 entry_attr_timeout(struct fuse_entry_out *o);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff8161f4c8)
Location: fs/fuse/dir.c:123
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
**Symbols:**

```
ffffffff8161e7e0-ffffffff8161e85e: entry_attr_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
u64 entry_attr_timeout(struct fuse_entry_out *o);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff8165799f)
Location: fs/fuse/dir.c:123
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
**Symbols:**

```
ffffffff81656c10-ffffffff81656c8e: entry_attr_timeout (STB_GLOBAL)
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
u64 entry_attr_timeout(struct fuse_entry_out *o);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffff800010507c6c)
Location: fs/fuse/dir.c:113
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/dir.c:fuse_dentry_revalidate
Direct callers:
  - fs/fuse/readdir.c:parse_dirplusfile
  - fs/fuse/readdir.c:parse_dirplusfile
```
**Symbols:**

```
ffff8000105072d0-ffff80001050731c: entry_attr_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
u64 entry_attr_timeout(struct fuse_entry_out *o);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (c06c3264)
Location: fs/fuse/dir.c:113
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/readdir.c:parse_dirplusfile
  - fs/fuse/readdir.c:parse_dirplusfile
```
**Symbols:**

```
c06c3264-c06c32b4: entry_attr_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
u64 entry_attr_timeout(struct fuse_entry_out *o);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (c00000000064d418)
Location: fs/fuse/dir.c:113
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/dir.c:fuse_dentry_revalidate
Direct callers:
  - fs/fuse/readdir.c:parse_dirplusfile
  - fs/fuse/readdir.c:parse_dirplusfile
```
**Symbols:**

```
c00000000064c820-c00000000064c858: entry_attr_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
u64 entry_attr_timeout(struct fuse_entry_out *o);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffe000373aec)
Location: fs/fuse/dir.c:113
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/dir.c:fuse_dentry_revalidate
Direct callers:
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
**Symbols:**

```
ffffffe000373268-ffffffe000373298: entry_attr_timeout (STB_GLOBAL)
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
u64 entry_attr_timeout(struct fuse_entry_out *o);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff8141cb5b)
Location: fs/fuse/dir.c:113
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
**Symbols:**

```
ffffffff8141c1b0-ffffffff8141c1d3: entry_attr_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
u64 entry_attr_timeout(struct fuse_entry_out *o);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff8140d5db)
Location: fs/fuse/dir.c:113
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
**Symbols:**

```
ffffffff8140cc30-ffffffff8140cc53: entry_attr_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
u64 entry_attr_timeout(struct fuse_entry_out *o);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff81418cfb)
Location: fs/fuse/dir.c:113
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
**Symbols:**

```
ffffffff81418350-ffffffff81418373: entry_attr_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
u64 entry_attr_timeout(struct fuse_entry_out *o);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff8142fa6b)
Location: fs/fuse/dir.c:113
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
**Symbols:**

```
ffffffff8142f0d0-ffffffff8142f0f3: entry_attr_timeout (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
