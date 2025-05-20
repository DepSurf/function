# Function: <code>fsverity_prepare_setattr</code>

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
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int fsverity_prepare_setattr(struct dentry *dentry, struct iattr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/open.c (ffffffff813508c0)
Location: fs/verity/open.c:319
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_setattr
```
**Symbols:**

```
ffffffff813508c0-ffffffff81350904: fsverity_prepare_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int fsverity_prepare_setattr(struct dentry *dentry, struct iattr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/open.c (ffffffff813972d0)
Location: fs/verity/open.c:320
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_setattr
```
**Symbols:**

```
ffffffff813972d0-ffffffff81397314: fsverity_prepare_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int fsverity_prepare_setattr(struct dentry *dentry, struct iattr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/open.c (ffffffff813a8d40)
Location: fs/verity/open.c:329
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_setattr
```
**Symbols:**

```
ffffffff813a8d40-ffffffff813a8d84: fsverity_prepare_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int fsverity_prepare_setattr(struct dentry *dentry, struct iattr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/open.c (ffffffff813afdb0)
Location: fs/verity/open.c:370
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_setattr
```
**Symbols:**

```
ffffffff813afdb0-ffffffff813afdf4: fsverity_prepare_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int fsverity_prepare_setattr(struct dentry *dentry, struct iattr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/open.c (ffffffff813ff9a0)
Location: fs/verity/open.c:370
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_setattr
```
**Symbols:**

```
ffffffff813ff9a0-ffffffff813ff9e1: fsverity_prepare_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int fsverity_prepare_setattr(struct dentry *dentry, struct iattr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/open.c (ffffffff81473750)
Location: fs/verity/open.c:366
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_setattr
```
**Symbols:**

```
ffffffff81473750-ffffffff814737af: fsverity_prepare_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int fsverity_prepare_setattr(struct dentry *dentry, struct iattr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/open.c (ffffffff81505670)
Location: fs/verity/open.c:366
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_setattr
```
**Symbols:**

```
ffffffff81505670-ffffffff815056cf: fsverity_prepare_setattr (STB_GLOBAL)
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
In fs/ext4/inode.c (ffffffff815bb985)
Location: include/linux/fsverity.h:314
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
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
In fs/ext4/inode.c (ffffffff815f475e)
Location: include/linux/fsverity.h:314
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
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
int fsverity_prepare_setattr(struct dentry *dentry, struct iattr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/open.c (ffff8000104127f8)
Location: fs/verity/open.c:319
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_setattr
```
**Symbols:**

```
ffff8000104127f8-ffff800010412874: fsverity_prepare_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int fsverity_prepare_setattr(struct dentry *dentry, struct iattr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/open.c (c05debb4)
Location: fs/verity/open.c:319
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_setattr
```
**Symbols:**

```
c05debb4-c05dec18: fsverity_prepare_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int fsverity_prepare_setattr(struct dentry *dentry, struct iattr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/open.c (c000000000520350)
Location: fs/verity/open.c:319
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_setattr
```
**Symbols:**

```
c000000000520350-c0000000005203d4: fsverity_prepare_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int fsverity_prepare_setattr(struct dentry *dentry, struct iattr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/open.c (ffffffe0002ba4b0)
Location: fs/verity/open.c:319
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_setattr
```
**Symbols:**

```
ffffffe0002ba4b0-ffffffe0002ba518: fsverity_prepare_setattr (STB_GLOBAL)
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
int fsverity_prepare_setattr(struct dentry *dentry, struct iattr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/open.c (ffffffff81348ea0)
Location: fs/verity/open.c:319
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_setattr
```
**Symbols:**

```
ffffffff81348ea0-ffffffff81348ee4: fsverity_prepare_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int fsverity_prepare_setattr(struct dentry *dentry, struct iattr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/open.c (ffffffff81339b80)
Location: fs/verity/open.c:319
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_setattr
```
**Symbols:**

```
ffffffff81339b80-ffffffff81339bc4: fsverity_prepare_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int fsverity_prepare_setattr(struct dentry *dentry, struct iattr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/open.c (ffffffff81346970)
Location: fs/verity/open.c:319
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_setattr
```
**Symbols:**

```
ffffffff81346970-ffffffff813469b4: fsverity_prepare_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int fsverity_prepare_setattr(struct dentry *dentry, struct iattr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/open.c (ffffffff81359c50)
Location: fs/verity/open.c:319
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_setattr
```
**Symbols:**

```
ffffffff81359c50-ffffffff81359c94: fsverity_prepare_setattr (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
