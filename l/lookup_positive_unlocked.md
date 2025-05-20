# Function: <code>lookup_positive_unlocked</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct dentry *lookup_positive_unlocked(const char *name, struct dentry *base, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff813240b0)
Location: fs/namei.c:2604
Inline: False
Direct callers:
  - fs/quota/dquot.c:dquot_quota_on_mount
  - fs/kernfs/mount.c:kernfs_node_dentry
  - fs/debugfs/inode.c:debugfs_lookup
```
**Symbols:**

```
ffffffff813240b0-ffffffff813240e3: lookup_positive_unlocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct dentry *lookup_positive_unlocked(const char *name, struct dentry *base, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8132f6b0)
Location: fs/namei.c:2602
Inline: False
Direct callers:
  - fs/quota/dquot.c:dquot_quota_on_mount
  - fs/kernfs/mount.c:kernfs_node_dentry
```
**Symbols:**

```
ffffffff8132f6b0-ffffffff8132f6e3: lookup_positive_unlocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct dentry *lookup_positive_unlocked(const char *name, struct dentry *base, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81334d70)
Location: fs/namei.c:2692
Inline: False
Direct callers:
  - fs/quota/dquot.c:dquot_quota_on_mount
  - fs/kernfs/mount.c:kernfs_node_dentry
```
**Symbols:**

```
ffffffff81334d70-ffffffff81334da3: lookup_positive_unlocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct dentry *lookup_positive_unlocked(const char *name, struct dentry *base, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81382780)
Location: fs/namei.c:2758
Inline: False
Direct callers:
  - fs/quota/dquot.c:dquot_quota_on_mount
  - fs/kernfs/mount.c:kernfs_node_dentry
```
**Symbols:**

```
ffffffff81382780-ffffffff813827b3: lookup_positive_unlocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct dentry *lookup_positive_unlocked(const char *name, struct dentry *base, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81401d50)
Location: fs/namei.c:2859
Inline: False
Direct callers:
  - fs/quota/dquot.c:dquot_quota_on_mount
  - fs/kernfs/mount.c:kernfs_node_dentry
  - fs/debugfs/inode.c:debugfs_lookup
```
**Symbols:**

```
ffffffff81401d50-ffffffff81401daa: lookup_positive_unlocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct dentry *lookup_positive_unlocked(const char *name, struct dentry *base, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8148bec0)
Location: fs/namei.c:2838
Inline: False
Direct callers:
  - fs/quota/dquot.c:dquot_quota_on_mount
  - fs/kernfs/mount.c:kernfs_node_dentry
  - fs/debugfs/inode.c:debugfs_lookup
```
**Symbols:**

```
ffffffff8148bec0-ffffffff8148bf1a: lookup_positive_unlocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct dentry *lookup_positive_unlocked(const char *name, struct dentry *base, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff814c09c0)
Location: fs/namei.c:2869
Inline: False
Direct callers:
  - fs/quota/dquot.c:dquot_quota_on_mount
  - fs/kernfs/mount.c:kernfs_node_dentry
  - fs/debugfs/inode.c:debugfs_lookup
```
**Symbols:**

```
ffffffff814c09c0-ffffffff814c0a1a: lookup_positive_unlocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct dentry *lookup_positive_unlocked(const char *name, struct dentry *base, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff814f2ea0)
Location: fs/namei.c:2886
Inline: False
Direct callers:
  - fs/quota/dquot.c:dquot_quota_on_mount
  - fs/kernfs/mount.c:kernfs_node_dentry
  - fs/debugfs/inode.c:debugfs_lookup
```
**Symbols:**

```
ffffffff814f2ea0-ffffffff814f2efa: lookup_positive_unlocked (STB_GLOBAL)
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
