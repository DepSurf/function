# Function: <code>simple_recursive_removal</code>

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
void simple_recursive_removal(struct dentry *dentry, void (*callback)(struct dentry *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff81345f20)
Location: fs/libfs.c:265
Inline: False
Direct callers:
  - fs/tracefs/inode.c:tracefs_remove
```
**Symbols:**

```
ffffffff81345f20-ffffffff8134610a: simple_recursive_removal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void simple_recursive_removal(struct dentry *dentry, void (*callback)(struct dentry *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff813523f0)
Location: fs/libfs.c:267
Inline: False
Direct callers:
  - fs/tracefs/inode.c:tracefs_remove
```
**Symbols:**

```
ffffffff813523f0-ffffffff813525c6: simple_recursive_removal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void simple_recursive_removal(struct dentry *dentry, void (*callback)(struct dentry *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff81358d30)
Location: fs/libfs.c:268
Inline: False
Direct callers:
  - fs/tracefs/inode.c:tracefs_remove
```
**Symbols:**

```
ffffffff81358d30-ffffffff81358fe7: simple_recursive_removal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void simple_recursive_removal(struct dentry *dentry, void (*callback)(struct dentry *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff813a7590)
Location: fs/libfs.c:268
Inline: False
Direct callers:
  - fs/tracefs/inode.c:tracefs_remove
```
**Symbols:**

```
ffffffff813a7590-ffffffff813a784e: simple_recursive_removal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void simple_recursive_removal(struct dentry *dentry, void (*callback)(struct dentry *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff8142c140)
Location: fs/libfs.c:268
Inline: False
Direct callers:
  - fs/debugfs/inode.c:debugfs_remove
  - fs/tracefs/inode.c:tracefs_remove
```
**Symbols:**

```
ffffffff8142c140-ffffffff8142c3f3: simple_recursive_removal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void simple_recursive_removal(struct dentry *dentry, void (*callback)(struct dentry *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff814b9850)
Location: fs/libfs.c:269
Inline: False
Direct callers:
  - fs/debugfs/inode.c:debugfs_lookup_and_remove
  - fs/tracefs/inode.c:tracefs_remove
```
**Symbols:**

```
ffffffff814b9850-ffffffff814b9b03: simple_recursive_removal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void simple_recursive_removal(struct dentry *dentry, void (*callback)(struct dentry *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff814ee800)
Location: fs/libfs.c:264
Inline: False
Direct callers:
  - fs/debugfs/inode.c:debugfs_lookup_and_remove
  - fs/tracefs/inode.c:tracefs_remove
```
**Symbols:**

```
ffffffff814ee800-ffffffff814eeaae: simple_recursive_removal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void simple_recursive_removal(struct dentry *dentry, void (*callback)(struct dentry *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff81522810)
Location: fs/libfs.c:520
Inline: False
Direct callers:
  - fs/debugfs/inode.c:debugfs_lookup_and_remove
  - fs/tracefs/inode.c:tracefs_remove
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
```
**Symbols:**

```
ffffffff81522810-ffffffff81522a90: simple_recursive_removal (STB_GLOBAL)
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
