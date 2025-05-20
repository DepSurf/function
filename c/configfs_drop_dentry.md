# Function: <code>configfs_drop_dentry</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void configfs_drop_dentry(struct configfs_dirent *sd, struct dentry *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/inode.c (ffffffff812de270)
Location: fs/configfs/inode.c:243
Inline: False
Direct callers:
  - fs/configfs/inode.c:configfs_hash_and_remove
  - fs/configfs/symlink.c:configfs_unlink
```
**Symbols:**

```
ffffffff812de270-ffffffff812de2de: configfs_drop_dentry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void configfs_drop_dentry(struct configfs_dirent *sd, struct dentry *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/inode.c (ffffffff81302bb0)
Location: fs/configfs/inode.c:243
Inline: False
Direct callers:
  - fs/configfs/inode.c:configfs_hash_and_remove
  - fs/configfs/symlink.c:configfs_unlink
```
**Symbols:**

```
ffffffff81302bb0-ffffffff81302c1e: configfs_drop_dentry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void configfs_drop_dentry(struct configfs_dirent *sd, struct dentry *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/inode.c (ffffffff81330b00)
Location: fs/configfs/inode.c:243
Inline: False
Direct callers:
  - fs/configfs/inode.c:configfs_hash_and_remove
  - fs/configfs/symlink.c:configfs_unlink
```
**Symbols:**

```
ffffffff81330b00-ffffffff81330b6e: configfs_drop_dentry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void configfs_drop_dentry(struct configfs_dirent *sd, struct dentry *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/inode.c (ffffffff81347ef0)
Location: fs/configfs/inode.c:243
Inline: False
Direct callers:
  - fs/configfs/inode.c:configfs_hash_and_remove
  - fs/configfs/symlink.c:configfs_unlink
```
**Symbols:**

```
ffffffff81347ef0-ffffffff81347f5e: configfs_drop_dentry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void configfs_drop_dentry(struct configfs_dirent *sd, struct dentry *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/inode.c (ffffffff81370370)
Location: fs/configfs/inode.c:229
Inline: False
Direct callers:
  - fs/configfs/inode.c:configfs_hash_and_remove
  - fs/configfs/symlink.c:configfs_unlink
```
**Symbols:**

```
ffffffff81370370-ffffffff813703e3: configfs_drop_dentry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void configfs_drop_dentry(struct configfs_dirent *sd, struct dentry *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/inode.c (ffffffff81388860)
Location: fs/configfs/inode.c:212
Inline: False
Direct callers:
  - fs/configfs/inode.c:configfs_hash_and_remove
  - fs/configfs/symlink.c:configfs_unlink
```
**Symbols:**

```
ffffffff81388860-ffffffff813888d3: configfs_drop_dentry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void configfs_drop_dentry(struct configfs_dirent *sd, struct dentry *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/inode.c (ffffffff813d35a0)
Location: fs/configfs/inode.c:212
Inline: False
Direct callers:
  - fs/configfs/inode.c:configfs_hash_and_remove
  - fs/configfs/symlink.c:configfs_unlink
```
**Symbols:**

```
ffffffff813d35a0-ffffffff813d3613: configfs_drop_dentry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void configfs_drop_dentry(struct configfs_dirent *sd, struct dentry *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/inode.c (ffffffff813e52e0)
Location: fs/configfs/inode.c:212
Inline: False
Direct callers:
  - fs/configfs/inode.c:configfs_hash_and_remove
  - fs/configfs/symlink.c:configfs_unlink
```
**Symbols:**

```
ffffffff813e52e0-ffffffff813e5353: configfs_drop_dentry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void configfs_drop_dentry(struct configfs_dirent *sd, struct dentry *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/inode.c (ffffffff813ebef0)
Location: fs/configfs/inode.c:211
Inline: False
Direct callers:
  - fs/configfs/inode.c:configfs_hash_and_remove
  - fs/configfs/symlink.c:configfs_unlink
```
**Symbols:**

```
ffffffff813ebef0-ffffffff813ebf63: configfs_drop_dentry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void configfs_drop_dentry(struct configfs_dirent *sd, struct dentry *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/inode.c (ffffffff8143dc90)
Location: fs/configfs/inode.c:205
Inline: False
Direct callers:
  - fs/configfs/inode.c:configfs_hash_and_remove
  - fs/configfs/symlink.c:configfs_unlink
```
**Symbols:**

```
ffffffff8143dc90-ffffffff8143dd03: configfs_drop_dentry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void configfs_drop_dentry(struct configfs_dirent *sd, struct dentry *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/inode.c (ffffffff814b9580)
Location: fs/configfs/inode.c:205
Inline: False
Direct callers:
  - fs/configfs/inode.c:configfs_hash_and_remove
  - fs/configfs/symlink.c:configfs_unlink
```
**Symbols:**

```
ffffffff814b9580-ffffffff814b95ff: configfs_drop_dentry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void configfs_drop_dentry(struct configfs_dirent *sd, struct dentry *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/inode.c (ffffffff81550d00)
Location: fs/configfs/inode.c:205
Inline: False
Direct callers:
  - fs/configfs/inode.c:configfs_hash_and_remove
  - fs/configfs/symlink.c:configfs_unlink
```
**Symbols:**

```
ffffffff81550d00-ffffffff81550d7f: configfs_drop_dentry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void configfs_drop_dentry(struct configfs_dirent *sd, struct dentry *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/inode.c (ffffffff815889e0)
Location: fs/configfs/inode.c:205
Inline: False
Direct callers:
  - fs/configfs/inode.c:configfs_hash_and_remove
  - fs/configfs/symlink.c:configfs_unlink
```
**Symbols:**

```
ffffffff815889e0-ffffffff81588a5f: configfs_drop_dentry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void configfs_drop_dentry(struct configfs_dirent *sd, struct dentry *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/inode.c (ffffffff815c15b0)
Location: fs/configfs/inode.c:204
Inline: False
Direct callers:
  - fs/configfs/inode.c:configfs_hash_and_remove
  - fs/configfs/symlink.c:configfs_unlink
```
**Symbols:**

```
ffffffff815c15b0-ffffffff815c162f: configfs_drop_dentry (STB_GLOBAL)
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
void configfs_drop_dentry(struct configfs_dirent *sd, struct dentry *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/inode.c (ffff800010458b18)
Location: fs/configfs/inode.c:212
Inline: False
Direct callers:
  - fs/configfs/inode.c:configfs_hash_and_remove
  - fs/configfs/symlink.c:configfs_unlink
```
**Symbols:**

```
ffff800010458b18-ffff800010458be8: configfs_drop_dentry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void configfs_drop_dentry(struct configfs_dirent *sd, struct dentry *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/inode.c (c061a8b4)
Location: fs/configfs/inode.c:212
Inline: False
Direct callers:
  - fs/configfs/inode.c:configfs_hash_and_remove
  - fs/configfs/dir.c:detach_attrs
  - fs/configfs/symlink.c:configfs_unlink
```
**Symbols:**

```
c061a8b4-c061a950: configfs_drop_dentry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void configfs_drop_dentry(struct configfs_dirent *sd, struct dentry *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/inode.c (c0000000005735d0)
Location: fs/configfs/inode.c:212
Inline: False
Direct callers:
  - fs/configfs/inode.c:configfs_hash_and_remove
  - fs/configfs/symlink.c:configfs_unlink
```
**Symbols:**

```
c0000000005735d0-c0000000005736f0: configfs_drop_dentry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void configfs_drop_dentry(struct configfs_dirent *sd, struct dentry *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/inode.c (ffffffe0002e9b0c)
Location: fs/configfs/inode.c:212
Inline: False
Direct callers:
  - fs/configfs/inode.c:configfs_hash_and_remove
  - fs/configfs/symlink.c:configfs_unlink
```
**Symbols:**

```
ffffffe0002e9b0c-ffffffe0002e9bf4: configfs_drop_dentry (STB_GLOBAL)
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
void configfs_drop_dentry(struct configfs_dirent *sd, struct dentry *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/inode.c (ffffffff81380e40)
Location: fs/configfs/inode.c:212
Inline: False
Direct callers:
  - fs/configfs/inode.c:configfs_hash_and_remove
  - fs/configfs/symlink.c:configfs_unlink
```
**Symbols:**

```
ffffffff81380e40-ffffffff81380eb3: configfs_drop_dentry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void configfs_drop_dentry(struct configfs_dirent *sd, struct dentry *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/inode.c (ffffffff813718d0)
Location: fs/configfs/inode.c:212
Inline: False
Direct callers:
  - fs/configfs/inode.c:configfs_hash_and_remove
  - fs/configfs/symlink.c:configfs_unlink
```
**Symbols:**

```
ffffffff813718d0-ffffffff81371943: configfs_drop_dentry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void configfs_drop_dentry(struct configfs_dirent *sd, struct dentry *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/inode.c (ffffffff8137e910)
Location: fs/configfs/inode.c:212
Inline: False
Direct callers:
  - fs/configfs/inode.c:configfs_hash_and_remove
  - fs/configfs/symlink.c:configfs_unlink
```
**Symbols:**

```
ffffffff8137e910-ffffffff8137e983: configfs_drop_dentry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void configfs_drop_dentry(struct configfs_dirent *sd, struct dentry *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/inode.c (ffffffff81392420)
Location: fs/configfs/inode.c:212
Inline: False
Direct callers:
  - fs/configfs/inode.c:configfs_hash_and_remove
  - fs/configfs/symlink.c:configfs_unlink
```
**Symbols:**

```
ffffffff81392420-ffffffff8139248f: configfs_drop_dentry (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
