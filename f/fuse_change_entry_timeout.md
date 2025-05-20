# Function: <code>fuse_change_entry_timeout</code>

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
In fs/fuse/dir.c (ffffffff81311e31)
Location: fs/fuse/dir.c:89
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_lookup
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
In fs/fuse/dir.c (ffffffff81347ff5)
Location: fs/fuse/dir.c:91
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup
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
In fs/fuse/dir.c (ffffffff8135d941)
Location: fs/fuse/dir.c:83
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup
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
In fs/fuse/dir.c (ffffffff813723aa)
Location: fs/fuse/dir.c:83
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup
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
In fs/fuse/dir.c (ffffffff813970b8)
Location: fs/fuse/dir.c:83
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup
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
In fs/fuse/dir.c (ffffffff813c6310)
Location: fs/fuse/dir.c:83
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void fuse_change_entry_timeout(struct dentry *entry, struct fuse_entry_out *o);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff813de8d0)
Location: fs/fuse/dir.c:68
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/readdir.c:fuse_readdir
```
**Symbols:**

```
ffffffff813de8d0-ffffffff813de90a: fuse_change_entry_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void fuse_change_entry_timeout(struct dentry *entry, struct fuse_entry_out *o);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff8140a4c0)
Location: fs/fuse/dir.c:68
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
**Symbols:**

```
ffffffff8140a4c0-ffffffff8140a4fd: fuse_change_entry_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void fuse_change_entry_timeout(struct dentry *entry, struct fuse_entry_out *o);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff81423b80)
Location: fs/fuse/dir.c:102
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
**Symbols:**

```
ffffffff81423b80-ffffffff81423bc5: fuse_change_entry_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void fuse_change_entry_timeout(struct dentry *entry, struct fuse_entry_out *o);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff81473b49)
Location: fs/fuse/dir.c:102
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
**Symbols:**

```
ffffffff81472fc0-ffffffff81473045: fuse_change_entry_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void fuse_change_entry_timeout(struct dentry *entry, struct fuse_entry_out *o);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff8148e42a)
Location: fs/fuse/dir.c:103
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
**Symbols:**

```
ffffffff8148d990-ffffffff8148da15: fuse_change_entry_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void fuse_change_entry_timeout(struct dentry *entry, struct fuse_entry_out *o);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff81493e7a)
Location: fs/fuse/dir.c:103
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
**Symbols:**

```
ffffffff81493230-ffffffff814932b2: fuse_change_entry_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void fuse_change_entry_timeout(struct dentry *entry, struct fuse_entry_out *o);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff814eb2da)
Location: fs/fuse/dir.c:103
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
**Symbols:**

```
ffffffff814ea690-ffffffff814ea712: fuse_change_entry_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void fuse_change_entry_timeout(struct dentry *entry, struct fuse_entry_out *o);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff81579e6c)
Location: fs/fuse/dir.c:106
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
**Symbols:**

```
ffffffff81579110-ffffffff8157919e: fuse_change_entry_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void fuse_change_entry_timeout(struct dentry *entry, struct fuse_entry_out *o);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff8161f528)
Location: fs/fuse/dir.c:112
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
**Symbols:**

```
ffffffff8161e740-ffffffff8161e7ce: fuse_change_entry_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void fuse_change_entry_timeout(struct dentry *entry, struct fuse_entry_out *o);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff81657a05)
Location: fs/fuse/dir.c:112
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
**Symbols:**

```
ffffffff81656b70-ffffffff81656bfe: fuse_change_entry_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void fuse_change_entry_timeout(struct dentry *entry, struct fuse_entry_out *o);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff816916f5)
Location: fs/fuse/dir.c:112
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
**Symbols:**

```
ffffffff81690850-ffffffff816908de: fuse_change_entry_timeout (STB_GLOBAL)
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
void fuse_change_entry_timeout(struct dentry *entry, struct fuse_entry_out *o);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffff800010507268)
Location: fs/fuse/dir.c:102
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/readdir.c:parse_dirplusfile
  - fs/fuse/readdir.c:parse_dirplusfile
```
**Symbols:**

```
ffff800010507268-ffff8000105072d0: fuse_change_entry_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void fuse_change_entry_timeout(struct dentry *entry, struct fuse_entry_out *o);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (c06c3200)
Location: fs/fuse/dir.c:102
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/readdir.c:parse_dirplusfile
```
**Symbols:**

```
c06c3200-c06c3264: fuse_change_entry_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void fuse_change_entry_timeout(struct dentry *entry, struct fuse_entry_out *o);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (c00000000064c7c0)
Location: fs/fuse/dir.c:102
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/readdir.c:parse_dirplusfile
```
**Symbols:**

```
c00000000064c7c0-c00000000064c81c: fuse_change_entry_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void fuse_change_entry_timeout(struct dentry *entry, struct fuse_entry_out *o);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffe000373226)
Location: fs/fuse/dir.c:102
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
**Symbols:**

```
ffffffe000373226-ffffffe000373268: fuse_change_entry_timeout (STB_GLOBAL)
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
void fuse_change_entry_timeout(struct dentry *entry, struct fuse_entry_out *o);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff8141c160)
Location: fs/fuse/dir.c:102
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
**Symbols:**

```
ffffffff8141c160-ffffffff8141c1a5: fuse_change_entry_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void fuse_change_entry_timeout(struct dentry *entry, struct fuse_entry_out *o);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff8140cbe0)
Location: fs/fuse/dir.c:102
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
**Symbols:**

```
ffffffff8140cbe0-ffffffff8140cc25: fuse_change_entry_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void fuse_change_entry_timeout(struct dentry *entry, struct fuse_entry_out *o);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff81418300)
Location: fs/fuse/dir.c:102
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
**Symbols:**

```
ffffffff81418300-ffffffff81418345: fuse_change_entry_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void fuse_change_entry_timeout(struct dentry *entry, struct fuse_entry_out *o);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff8142f080)
Location: fs/fuse/dir.c:102
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
**Symbols:**

```
ffffffff8142f080-ffffffff8142f0c5: fuse_change_entry_timeout (STB_GLOBAL)
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
