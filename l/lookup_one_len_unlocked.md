# Function: <code>lookup_one_len_unlocked</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct dentry *lookup_one_len_unlocked(const char *name, struct dentry *base, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8123f570)
Location: fs/namei.c:2480
Inline: False
Direct callers:
  - fs/quota/dquot.c:dquot_quota_on_mount
  - fs/kernfs/mount.c:kernfs_node_dentry
  - fs/ecryptfs/inode.c:ecryptfs_lookup
```
**Symbols:**

```
ffffffff8123f570-ffffffff8123f676: lookup_one_len_unlocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct dentry *lookup_one_len_unlocked(const char *name, struct dentry *base, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81252340)
Location: fs/namei.c:2469
Inline: False
Direct callers:
  - fs/quota/dquot.c:dquot_quota_on_mount
  - fs/kernfs/mount.c:kernfs_node_dentry
  - fs/ecryptfs/inode.c:ecryptfs_lookup
```
**Symbols:**

```
ffffffff81252340-ffffffff81252446: lookup_one_len_unlocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct dentry *lookup_one_len_unlocked(const char *name, struct dentry *base, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8125e4c0)
Location: fs/namei.c:2514
Inline: False
Direct callers:
  - fs/quota/dquot.c:dquot_quota_on_mount
  - fs/kernfs/mount.c:kernfs_node_dentry
  - fs/ecryptfs/inode.c:ecryptfs_lookup
```
**Symbols:**

```
ffffffff8125e4c0-ffffffff8125e5c9: lookup_one_len_unlocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct dentry *lookup_one_len_unlocked(const char *name, struct dentry *base, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812808a0)
Location: fs/namei.c:2512
Inline: False
Direct callers:
  - fs/quota/dquot.c:dquot_quota_on_mount
  - fs/kernfs/mount.c:kernfs_node_dentry
  - fs/ecryptfs/inode.c:ecryptfs_lookup
```
**Symbols:**

```
ffffffff812808a0-ffffffff812809af: lookup_one_len_unlocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct dentry *lookup_one_len_unlocked(const char *name, struct dentry *base, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812a7ce0)
Location: fs/namei.c:2535
Inline: False
Direct callers:
  - fs/quota/dquot.c:dquot_quota_on_mount
  - fs/kernfs/mount.c:kernfs_node_dentry
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/debugfs/inode.c:debugfs_lookup
```
**Symbols:**

```
ffffffff812a7ce0-ffffffff812a7d4d: lookup_one_len_unlocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct dentry *lookup_one_len_unlocked(const char *name, struct dentry *base, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812bcd80)
Location: fs/namei.c:2559
Inline: False
Direct callers:
  - fs/quota/dquot.c:dquot_quota_on_mount
  - fs/kernfs/mount.c:kernfs_node_dentry
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/debugfs/inode.c:debugfs_lookup
```
**Symbols:**

```
ffffffff812bcd80-ffffffff812bcded: lookup_one_len_unlocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct dentry *lookup_one_len_unlocked(const char *name, struct dentry *base, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812d9890)
Location: fs/namei.c:2557
Inline: False
Direct callers:
  - fs/quota/dquot.c:dquot_quota_on_mount
  - fs/kernfs/mount.c:kernfs_node_dentry
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/debugfs/inode.c:debugfs_lookup
```
**Symbols:**

```
ffffffff812d9890-ffffffff812d98ff: lookup_one_len_unlocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct dentry *lookup_one_len_unlocked(const char *name, struct dentry *base, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812eb3a0)
Location: fs/namei.c:2550
Inline: False
Direct callers:
  - fs/quota/dquot.c:dquot_quota_on_mount
  - fs/kernfs/mount.c:kernfs_node_dentry
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/debugfs/inode.c:debugfs_lookup
```
**Symbols:**

```
ffffffff812eb3a0-ffffffff812eb40f: lookup_one_len_unlocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct dentry *lookup_one_len_unlocked(const char *name, struct dentry *base, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81324010)
Location: fs/namei.c:2578
Inline: False
Direct callers:
  - fs/namei.c:lookup_positive_unlocked
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/exportfs/expfs.c:reconnect_one
```
**Symbols:**

```
ffffffff81324010-ffffffff813240a7: lookup_one_len_unlocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct dentry *lookup_one_len_unlocked(const char *name, struct dentry *base, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8132f610)
Location: fs/namei.c:2576
Inline: False
Direct callers:
  - fs/namei.c:lookup_positive_unlocked
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/exportfs/expfs.c:reconnect_one
```
**Symbols:**

```
ffffffff8132f610-ffffffff8132f6a7: lookup_one_len_unlocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct dentry *lookup_one_len_unlocked(const char *name, struct dentry *base, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81334cd0)
Location: fs/namei.c:2666
Inline: False
Direct callers:
  - fs/namei.c:lookup_positive_unlocked
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/exportfs/expfs.c:reconnect_one
```
**Symbols:**

```
ffffffff81334cd0-ffffffff81334d67: lookup_one_len_unlocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct dentry *lookup_one_len_unlocked(const char *name, struct dentry *base, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff813826d0)
Location: fs/namei.c:2732
Inline: False
Direct callers:
  - fs/namei.c:lookup_positive_unlocked
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/exportfs/expfs.c:reconnect_one
```
**Symbols:**

```
ffffffff813826d0-ffffffff81382776: lookup_one_len_unlocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct dentry *lookup_one_len_unlocked(const char *name, struct dentry *base, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81401db0)
Location: fs/namei.c:2844
Inline: False
Direct callers:
  - fs/ecryptfs/inode.c:ecryptfs_lookup
```
**Symbols:**

```
ffffffff81401db0-ffffffff81401e72: lookup_one_len_unlocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct dentry *lookup_one_len_unlocked(const char *name, struct dentry *base, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8148bf30)
Location: fs/namei.c:2823
Inline: False
Direct callers:
  - fs/ecryptfs/inode.c:ecryptfs_lookup
```
**Symbols:**

```
ffffffff8148bf30-ffffffff8148bff2: lookup_one_len_unlocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct dentry *lookup_one_len_unlocked(const char *name, struct dentry *base, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff814c17d0)
Location: fs/namei.c:2854
Inline: False
Direct callers:
  - fs/ecryptfs/inode.c:ecryptfs_lookup
```
**Symbols:**

```
ffffffff814c17d0-ffffffff814c1892: lookup_one_len_unlocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct dentry *lookup_one_len_unlocked(const char *name, struct dentry *base, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff814f3c90)
Location: fs/namei.c:2871
Inline: False
Direct callers:
  - fs/ecryptfs/inode.c:ecryptfs_lookup
```
**Symbols:**

```
ffffffff814f3c90-ffffffff814f3d52: lookup_one_len_unlocked (STB_GLOBAL)
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
struct dentry *lookup_one_len_unlocked(const char *name, struct dentry *base, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffff800010394b40)
Location: fs/namei.c:2550
Inline: False
Direct callers:
  - fs/quota/dquot.c:dquot_quota_on_mount
  - fs/kernfs/mount.c:kernfs_node_dentry
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/debugfs/inode.c:debugfs_lookup
```
**Symbols:**

```
ffff800010394b40-ffff800010394be0: lookup_one_len_unlocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct dentry *lookup_one_len_unlocked(const char *name, struct dentry *base, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (c057a9a0)
Location: fs/namei.c:2550
Inline: False
Direct callers:
  - fs/quota/dquot.c:dquot_quota_on_mount
  - fs/kernfs/mount.c:kernfs_node_dentry
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/debugfs/inode.c:debugfs_lookup
```
**Symbols:**

```
c057a9a0-c057aa30: lookup_one_len_unlocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct dentry *lookup_one_len_unlocked(const char *name, struct dentry *base, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (c00000000048d900)
Location: fs/namei.c:2550
Inline: False
Direct callers:
  - fs/quota/dquot.c:dquot_quota_on_mount
  - fs/kernfs/mount.c:kernfs_node_dentry
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/exportfs/expfs.c:reconnect_path
  - fs/debugfs/inode.c:debugfs_lookup
```
**Symbols:**

```
c00000000048d900-c00000000048d9a4: lookup_one_len_unlocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct dentry *lookup_one_len_unlocked(const char *name, struct dentry *base, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffe000263570)
Location: fs/namei.c:2550
Inline: False
Direct callers:
  - fs/quota/dquot.c:dquot_quota_on_mount
  - fs/kernfs/mount.c:kernfs_node_dentry
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/debugfs/inode.c:debugfs_lookup
```
**Symbols:**

```
ffffffe000263570-ffffffe0002635d4: lookup_one_len_unlocked (STB_GLOBAL)
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
struct dentry *lookup_one_len_unlocked(const char *name, struct dentry *base, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812e3980)
Location: fs/namei.c:2550
Inline: False
Direct callers:
  - fs/quota/dquot.c:dquot_quota_on_mount
  - fs/kernfs/mount.c:kernfs_node_dentry
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/debugfs/inode.c:debugfs_lookup
```
**Symbols:**

```
ffffffff812e3980-ffffffff812e39ef: lookup_one_len_unlocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct dentry *lookup_one_len_unlocked(const char *name, struct dentry *base, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812d45c0)
Location: fs/namei.c:2550
Inline: False
Direct callers:
  - fs/quota/dquot.c:dquot_quota_on_mount
  - fs/kernfs/mount.c:kernfs_node_dentry
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/debugfs/inode.c:debugfs_lookup
```
**Symbols:**

```
ffffffff812d45c0-ffffffff812d462f: lookup_one_len_unlocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct dentry *lookup_one_len_unlocked(const char *name, struct dentry *base, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812e1790)
Location: fs/namei.c:2550
Inline: False
Direct callers:
  - fs/quota/dquot.c:dquot_quota_on_mount
  - fs/kernfs/mount.c:kernfs_node_dentry
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/debugfs/inode.c:debugfs_lookup
```
**Symbols:**

```
ffffffff812e1790-ffffffff812e17ff: lookup_one_len_unlocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct dentry *lookup_one_len_unlocked(const char *name, struct dentry *base, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812f25e0)
Location: fs/namei.c:2550
Inline: False
Direct callers:
  - fs/quota/dquot.c:dquot_quota_on_mount
  - fs/kernfs/mount.c:kernfs_node_dentry
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/debugfs/inode.c:debugfs_lookup
```
**Symbols:**

```
ffffffff812f25e0-ffffffff812f264f: lookup_one_len_unlocked (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
