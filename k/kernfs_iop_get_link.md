# Function: <code>kernfs_iop_get_link</code>

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
const char *kernfs_iop_get_link(struct dentry *dentry, struct inode *inode, struct delayed_call *done);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/symlink.c (ffffffff812b9780)
Location: fs/kernfs/symlink.c:115
Inline: False
```
**Symbols:**

```
ffffffff812b9780-ffffffff812b9952: kernfs_iop_get_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
const char *kernfs_iop_get_link(struct dentry *dentry, struct inode *inode, struct delayed_call *done);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/symlink.c (ffffffff812ceec0)
Location: fs/kernfs/symlink.c:115
Inline: False
```
**Symbols:**

```
ffffffff812ceec0-ffffffff812cf092: kernfs_iop_get_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
const char *kernfs_iop_get_link(struct dentry *dentry, struct inode *inode, struct delayed_call *done);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/symlink.c (ffffffff812dc5a0)
Location: fs/kernfs/symlink.c:115
Inline: True
```
**Symbols:**

```
ffffffff812dc5a0-ffffffff812dc7da: kernfs_iop_get_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
const char *kernfs_iop_get_link(struct dentry *dentry, struct inode *inode, struct delayed_call *done);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/symlink.c (ffffffff81300ed0)
Location: fs/kernfs/symlink.c:115
Inline: True
```
**Symbols:**

```
ffffffff81300ed0-ffffffff813010b6: kernfs_iop_get_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
const char *kernfs_iop_get_link(struct dentry *dentry, struct inode *inode, struct delayed_call *done);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/symlink.c (ffffffff8132ebb0)
Location: fs/kernfs/symlink.c:124
Inline: True
```
**Symbols:**

```
ffffffff8132ebb0-ffffffff8132ed79: kernfs_iop_get_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
const char *kernfs_iop_get_link(struct dentry *dentry, struct inode *inode, struct delayed_call *done);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/symlink.c (ffffffff81345f60)
Location: fs/kernfs/symlink.c:127
Inline: True
```
**Symbols:**

```
ffffffff81345f60-ffffffff8134614d: kernfs_iop_get_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
const char *kernfs_iop_get_link(struct dentry *dentry, struct inode *inode, struct delayed_call *done);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/symlink.c (ffffffff8136e280)
Location: fs/kernfs/symlink.c:126
Inline: True
```
**Symbols:**

```
ffffffff8136e280-ffffffff8136e45a: kernfs_iop_get_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
const char *kernfs_iop_get_link(struct dentry *dentry, struct inode *inode, struct delayed_call *done);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/symlink.c (ffffffff81386430)
Location: fs/kernfs/symlink.c:126
Inline: True
```
**Symbols:**

```
ffffffff81386430-ffffffff8138660a: kernfs_iop_get_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
const char *kernfs_iop_get_link(struct dentry *dentry, struct inode *inode, struct delayed_call *done);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/kernfs/symlink.c (ffffffff813d11a0)
Location: fs/kernfs/symlink.c:126
Inline: True
```
**Symbols:**

```
ffffffff813d11a0-ffffffff813d123c: kernfs_iop_get_link.part.0 (STB_LOCAL)
ffffffff813d1240-ffffffff813d1263: kernfs_iop_get_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
const char *kernfs_iop_get_link(struct dentry *dentry, struct inode *inode, struct delayed_call *done);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/kernfs/symlink.c (ffffffff813e2da0)
Location: fs/kernfs/symlink.c:126
Inline: True
```
**Symbols:**

```
ffffffff813e2da0-ffffffff813e2e3c: kernfs_iop_get_link.part.0 (STB_LOCAL)
ffffffff813e2e40-ffffffff813e2e63: kernfs_iop_get_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
const char *kernfs_iop_get_link(struct dentry *dentry, struct inode *inode, struct delayed_call *done);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/symlink.c (ffffffff813e99c0)
Location: fs/kernfs/symlink.c:126
Inline: True
```
**Symbols:**

```
ffffffff813e99c0-ffffffff813e9a79: kernfs_iop_get_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
const char *kernfs_iop_get_link(struct dentry *dentry, struct inode *inode, struct delayed_call *done);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/symlink.c (ffffffff8143b730)
Location: fs/kernfs/symlink.c:126
Inline: True
```
**Symbols:**

```
ffffffff8143b730-ffffffff8143b7e9: kernfs_iop_get_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
const char *kernfs_iop_get_link(struct dentry *dentry, struct inode *inode, struct delayed_call *done);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/symlink.c (ffffffff814b6a10)
Location: fs/kernfs/symlink.c:126
Inline: True
```
**Symbols:**

```
ffffffff814b6a10-ffffffff814b6ad5: kernfs_iop_get_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
const char *kernfs_iop_get_link(struct dentry *dentry, struct inode *inode, struct delayed_call *done);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/symlink.c (ffffffff8154dd00)
Location: fs/kernfs/symlink.c:126
Inline: True
```
**Symbols:**

```
ffffffff8154dd00-ffffffff8154ddc5: kernfs_iop_get_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
const char *kernfs_iop_get_link(struct dentry *dentry, struct inode *inode, struct delayed_call *done);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/symlink.c (ffffffff815859c0)
Location: fs/kernfs/symlink.c:126
Inline: True
```
**Symbols:**

```
ffffffff815859c0-ffffffff81585a85: kernfs_iop_get_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
const char *kernfs_iop_get_link(struct dentry *dentry, struct inode *inode, struct delayed_call *done);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/symlink.c (ffffffff815be470)
Location: fs/kernfs/symlink.c:126
Inline: True
```
**Symbols:**

```
ffffffff815be470-ffffffff815be568: kernfs_iop_get_link (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
const char *kernfs_iop_get_link(struct dentry *dentry, struct inode *inode, struct delayed_call *done);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/symlink.c (ffff800010455ed8)
Location: fs/kernfs/symlink.c:126
Inline: True
```
**Symbols:**

```
ffff800010455ed8-ffff8000104560b4: kernfs_iop_get_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
const char *kernfs_iop_get_link(struct dentry *dentry, struct inode *inode, struct delayed_call *done);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/symlink.c (c0617fdc)
Location: fs/kernfs/symlink.c:126
Inline: True
```
**Symbols:**

```
c0617fdc-c06181ac: kernfs_iop_get_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
const char *kernfs_iop_get_link(struct dentry *dentry, struct inode *inode, struct delayed_call *done);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/symlink.c (c00000000056faa0)
Location: fs/kernfs/symlink.c:126
Inline: True
```
**Symbols:**

```
c00000000056faa0-c00000000056fd74: kernfs_iop_get_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
const char *kernfs_iop_get_link(struct dentry *dentry, struct inode *inode, struct delayed_call *done);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/symlink.c (ffffffe0002e7838)
Location: fs/kernfs/symlink.c:126
Inline: True
```
**Symbols:**

```
ffffffe0002e7838-ffffffe0002e7a0e: kernfs_iop_get_link (STB_LOCAL)
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
const char *kernfs_iop_get_link(struct dentry *dentry, struct inode *inode, struct delayed_call *done);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/symlink.c (ffffffff8137ea10)
Location: fs/kernfs/symlink.c:126
Inline: True
```
**Symbols:**

```
ffffffff8137ea10-ffffffff8137ebea: kernfs_iop_get_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
const char *kernfs_iop_get_link(struct dentry *dentry, struct inode *inode, struct delayed_call *done);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/symlink.c (ffffffff8136f4a0)
Location: fs/kernfs/symlink.c:126
Inline: True
```
**Symbols:**

```
ffffffff8136f4a0-ffffffff8136f67a: kernfs_iop_get_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
const char *kernfs_iop_get_link(struct dentry *dentry, struct inode *inode, struct delayed_call *done);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/symlink.c (ffffffff8137c4e0)
Location: fs/kernfs/symlink.c:126
Inline: True
```
**Symbols:**

```
ffffffff8137c4e0-ffffffff8137c6ba: kernfs_iop_get_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
const char *kernfs_iop_get_link(struct dentry *dentry, struct inode *inode, struct delayed_call *done);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/symlink.c (ffffffff8138ffc0)
Location: fs/kernfs/symlink.c:126
Inline: True
```
**Symbols:**

```
ffffffff8138ffc0-ffffffff8139019a: kernfs_iop_get_link (STB_LOCAL)
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
