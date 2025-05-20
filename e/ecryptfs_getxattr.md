# Function: <code>ecryptfs_getxattr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
ssize_t ecryptfs_getxattr(struct dentry *dentry, const char *name, void *value, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/inode.c (ffffffff81303040)
Location: fs/ecryptfs/inode.c:1054
Inline: False
```
**Symbols:**

```
ffffffff81303040-ffffffff81303058: ecryptfs_getxattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
ssize_t ecryptfs_getxattr(struct dentry *dentry, struct inode *inode, const char *name, void *value, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/inode.c (ffffffff81336fc0)
Location: fs/ecryptfs/inode.c:1043
Inline: False
```
**Symbols:**

```
ffffffff81336fc0-ffffffff81336fdf: ecryptfs_getxattr (STB_LOCAL)
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
In fs/ecryptfs/inode.c (ffffffff8134cd86)
Location: fs/ecryptfs/inode.c:1040
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_xattr_get
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
In fs/ecryptfs/inode.c (ffffffff81361906)
Location: fs/ecryptfs/inode.c:1043
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_xattr_get
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
In fs/ecryptfs/inode.c (ffffffff813865d6)
Location: fs/ecryptfs/inode.c:1039
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_xattr_get
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
In fs/ecryptfs/inode.c (ffffffff813b52a5)
Location: fs/ecryptfs/inode.c:1037
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_xattr_get
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/inode.c (ffffffff813ce7c5)
Location: fs/ecryptfs/inode.c:1042
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_xattr_get
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/inode.c (ffffffff813f9315)
Location: fs/ecryptfs/inode.c:1028
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_xattr_get
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/inode.c (ffffffff81413175)
Location: fs/ecryptfs/inode.c:1050
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_xattr_get
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/inode.c (ffffffff814600c5)
Location: fs/ecryptfs/inode.c:1050
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_xattr_get
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/inode.c (ffffffff8147bce5)
Location: fs/ecryptfs/inode.c:1054
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_xattr_get
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/inode.c (ffffffff81481575)
Location: fs/ecryptfs/inode.c:1060
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_xattr_get
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/inode.c (ffffffff814d9335)
Location: fs/ecryptfs/inode.c:1060
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_xattr_get
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/inode.c (ffffffff81566b45)
Location: fs/ecryptfs/inode.c:1060
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_xattr_get
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/inode.c (ffffffff8160a115)
Location: fs/ecryptfs/inode.c:1062
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_xattr_get
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/inode.c (ffffffff81641fd5)
Location: fs/ecryptfs/inode.c:1062
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_xattr_get
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/inode.c (ffffffff8167b5f5)
Location: fs/ecryptfs/inode.c:1081
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_xattr_get
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/inode.c (ffff8000104f4660)
Location: fs/ecryptfs/inode.c:1050
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_xattr_get
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/inode.c (c06b2038)
Location: fs/ecryptfs/inode.c:1050
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_xattr_get
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/inode.c (c000000000634dec)
Location: fs/ecryptfs/inode.c:1050
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_xattr_get
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/inode.c (ffffffe00036393e)
Location: fs/ecryptfs/inode.c:1050
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_xattr_get
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/inode.c (ffffffff8140b755)
Location: fs/ecryptfs/inode.c:1050
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_xattr_get
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/inode.c (ffffffff813fc1d5)
Location: fs/ecryptfs/inode.c:1050
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_xattr_get
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/inode.c (ffffffff81408ad5)
Location: fs/ecryptfs/inode.c:1050
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_xattr_get
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/inode.c (ffffffff8141e795)
Location: fs/ecryptfs/inode.c:1050
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_xattr_get
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
<b>Param added. </b>
<code>struct inode *inode</code>
</li>
<li>
<b>Param reordered. </b>
<code>dentry, name, value, size</code> ➡️ <code>dentry, inode, name, value, size</code>
</li>
</ul>
</details>
</li>
</ul>
