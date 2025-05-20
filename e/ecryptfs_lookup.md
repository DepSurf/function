# Function: <code>ecryptfs_lookup</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct dentry *ecryptfs_lookup(struct inode *ecryptfs_dir_inode, struct dentry *ecryptfs_dentry, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/inode.c (ffffffff81301c60)
Location: fs/ecryptfs/inode.c:391
Inline: False
```
**Symbols:**

```
ffffffff81301c60-ffffffff81301fb9: ecryptfs_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct dentry *ecryptfs_lookup(struct inode *ecryptfs_dir_inode, struct dentry *ecryptfs_dentry, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/inode.c (ffffffff81335cd0)
Location: fs/ecryptfs/inode.c:386
Inline: False
```
**Symbols:**

```
ffffffff81335cd0-ffffffff81335f8a: ecryptfs_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct dentry *ecryptfs_lookup(struct inode *ecryptfs_dir_inode, struct dentry *ecryptfs_dentry, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/inode.c (ffffffff8134b990)
Location: fs/ecryptfs/inode.c:386
Inline: False
```
**Symbols:**

```
ffffffff8134b990-ffffffff8134bc4a: ecryptfs_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct dentry *ecryptfs_lookup(struct inode *ecryptfs_dir_inode, struct dentry *ecryptfs_dentry, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/inode.c (ffffffff81360520)
Location: fs/ecryptfs/inode.c:386
Inline: False
```
**Symbols:**

```
ffffffff81360520-ffffffff813607e0: ecryptfs_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct dentry *ecryptfs_lookup(struct inode *ecryptfs_dir_inode, struct dentry *ecryptfs_dentry, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/inode.c (ffffffff813851f0)
Location: fs/ecryptfs/inode.c:382
Inline: False
```
**Symbols:**

```
ffffffff813851f0-ffffffff813854ac: ecryptfs_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
struct dentry *ecryptfs_lookup(struct inode *ecryptfs_dir_inode, struct dentry *ecryptfs_dentry, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/inode.c (0)
Location: fs/ecryptfs/inode.c:381
Inline: False
```
**Symbols:**

```
ffffffff813b3fe0-ffffffff813b4219: ecryptfs_lookup (STB_LOCAL)
ffffffff813b52e3-ffffffff813b5343: ecryptfs_lookup.cold.26 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
struct dentry *ecryptfs_lookup(struct inode *ecryptfs_dir_inode, struct dentry *ecryptfs_dentry, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/inode.c (0)
Location: fs/ecryptfs/inode.c:381
Inline: False
```
**Symbols:**

```
ffffffff813cd500-ffffffff813cd739: ecryptfs_lookup (STB_LOCAL)
ffffffff813ce803-ffffffff813ce863: ecryptfs_lookup.cold.27 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct dentry *ecryptfs_lookup(struct inode *ecryptfs_dir_inode, struct dentry *ecryptfs_dentry, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/inode.c (0)
Location: fs/ecryptfs/inode.c:367
Inline: False
```
**Symbols:**

```
ffffffff813f80a0-ffffffff813f82e7: ecryptfs_lookup (STB_LOCAL)
ffffffff813f9353-ffffffff813f93b1: ecryptfs_lookup.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
struct dentry *ecryptfs_lookup(struct inode *ecryptfs_dir_inode, struct dentry *ecryptfs_dentry, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/inode.c (0)
Location: fs/ecryptfs/inode.c:382
Inline: False
```
**Symbols:**

```
ffffffff81411f00-ffffffff81412145: ecryptfs_lookup (STB_LOCAL)
ffffffff8141321f-ffffffff8141327d: ecryptfs_lookup.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
struct dentry *ecryptfs_lookup(struct inode *ecryptfs_dir_inode, struct dentry *ecryptfs_dentry, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/inode.c (0)
Location: fs/ecryptfs/inode.c:382
Inline: False
```
**Symbols:**

```
ffffffff8145ff20-ffffffff81460015: ecryptfs_lookup (STB_LOCAL)
ffffffff8146142f-ffffffff8146144a: ecryptfs_lookup.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
struct dentry *ecryptfs_lookup(struct inode *ecryptfs_dir_inode, struct dentry *ecryptfs_dentry, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/inode.c (0)
Location: fs/ecryptfs/inode.c:382
Inline: False
```
**Symbols:**

```
ffffffff8147bb40-ffffffff8147bc35: ecryptfs_lookup (STB_LOCAL)
ffffffff81bee09c-ffffffff81bee0b7: ecryptfs_lookup.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
struct dentry *ecryptfs_lookup(struct inode *ecryptfs_dir_inode, struct dentry *ecryptfs_dentry, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/inode.c (0)
Location: fs/ecryptfs/inode.c:380
Inline: False
```
**Symbols:**

```
ffffffff81481280-ffffffff814814c6: ecryptfs_lookup (STB_LOCAL)
ffffffff81be00e2-ffffffff81be0140: ecryptfs_lookup.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct dentry *ecryptfs_lookup(struct inode *ecryptfs_dir_inode, struct dentry *ecryptfs_dentry, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/inode.c (0)
Location: fs/ecryptfs/inode.c:380
Inline: False
```
**Symbols:**

```
ffffffff814d8b80-ffffffff814d8dc6: ecryptfs_lookup (STB_LOCAL)
ffffffff81cd082e-ffffffff81cd088c: ecryptfs_lookup.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct dentry *ecryptfs_lookup(struct inode *ecryptfs_dir_inode, struct dentry *ecryptfs_dentry, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/inode.c (0)
Location: fs/ecryptfs/inode.c:380
Inline: False
```
**Symbols:**

```
ffffffff81566400-ffffffff8156664e: ecryptfs_lookup (STB_LOCAL)
ffffffff81e83abd-ffffffff81e83b1a: ecryptfs_lookup.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct dentry *ecryptfs_lookup(struct inode *ecryptfs_dir_inode, struct dentry *ecryptfs_dentry, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/inode.c (ffffffff816098f0)
Location: fs/ecryptfs/inode.c:382
Inline: False
```
**Symbols:**

```
ffffffff816098f0-ffffffff81609ba2: ecryptfs_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct dentry *ecryptfs_lookup(struct inode *ecryptfs_dir_inode, struct dentry *ecryptfs_dentry, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/inode.c (ffffffff816417b0)
Location: fs/ecryptfs/inode.c:382
Inline: False
```
**Symbols:**

```
ffffffff816417b0-ffffffff81641a62: ecryptfs_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct dentry *ecryptfs_lookup(struct inode *ecryptfs_dir_inode, struct dentry *ecryptfs_dentry, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/inode.c (ffffffff8167add0)
Location: fs/ecryptfs/inode.c:390
Inline: False
```
**Symbols:**

```
ffffffff8167add0-ffffffff8167b087: ecryptfs_lookup (STB_LOCAL)
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
struct dentry *ecryptfs_lookup(struct inode *ecryptfs_dir_inode, struct dentry *ecryptfs_dentry, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/inode.c (ffff8000104f32c0)
Location: fs/ecryptfs/inode.c:382
Inline: False
```
**Symbols:**

```
ffff8000104f32c0-ffff8000104f354c: ecryptfs_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct dentry *ecryptfs_lookup(struct inode *ecryptfs_dir_inode, struct dentry *ecryptfs_dentry, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/inode.c (c06b0a0c)
Location: fs/ecryptfs/inode.c:382
Inline: False
```
**Symbols:**

```
c06b0a0c-c06b0cb4: ecryptfs_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct dentry *ecryptfs_lookup(struct inode *ecryptfs_dir_inode, struct dentry *ecryptfs_dentry, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/inode.c (c000000000633330)
Location: fs/ecryptfs/inode.c:382
Inline: False
```
**Symbols:**

```
c000000000633330-c000000000633684: ecryptfs_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct dentry *ecryptfs_lookup(struct inode *ecryptfs_dir_inode, struct dentry *ecryptfs_dentry, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/inode.c (ffffffe000362854)
Location: fs/ecryptfs/inode.c:382
Inline: False
```
**Symbols:**

```
ffffffe000362854-ffffffe000362a8a: ecryptfs_lookup (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
struct dentry *ecryptfs_lookup(struct inode *ecryptfs_dir_inode, struct dentry *ecryptfs_dentry, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/inode.c (0)
Location: fs/ecryptfs/inode.c:382
Inline: False
```
**Symbols:**

```
ffffffff8140a4e0-ffffffff8140a725: ecryptfs_lookup (STB_LOCAL)
ffffffff8140b7ff-ffffffff8140b85d: ecryptfs_lookup.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
struct dentry *ecryptfs_lookup(struct inode *ecryptfs_dir_inode, struct dentry *ecryptfs_dentry, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/inode.c (0)
Location: fs/ecryptfs/inode.c:382
Inline: False
```
**Symbols:**

```
ffffffff813faf60-ffffffff813fb1a5: ecryptfs_lookup (STB_LOCAL)
ffffffff813fc27f-ffffffff813fc2dd: ecryptfs_lookup.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
struct dentry *ecryptfs_lookup(struct inode *ecryptfs_dir_inode, struct dentry *ecryptfs_dentry, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/inode.c (0)
Location: fs/ecryptfs/inode.c:382
Inline: False
```
**Symbols:**

```
ffffffff81407860-ffffffff81407aa5: ecryptfs_lookup (STB_LOCAL)
ffffffff81408b7f-ffffffff81408bdd: ecryptfs_lookup.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
struct dentry *ecryptfs_lookup(struct inode *ecryptfs_dir_inode, struct dentry *ecryptfs_dentry, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/inode.c (0)
Location: fs/ecryptfs/inode.c:382
Inline: False
```
**Symbols:**

```
ffffffff8141d520-ffffffff8141d765: ecryptfs_lookup (STB_LOCAL)
ffffffff8141e83f-ffffffff8141e89d: ecryptfs_lookup.cold (STB_LOCAL)
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
