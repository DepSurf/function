# Function: <code>vfat_rename</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int vfat_rename(struct inode *old_dir, struct dentry *old_dentry, struct inode *new_dir, struct dentry *new_dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/namei_vfat.c (ffffffff81300400)
Location: fs/fat/namei_vfat.c:905
Inline: False
```
**Symbols:**

```
ffffffff81300400-ffffffff813008ec: vfat_rename (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int vfat_rename(struct inode *old_dir, struct dentry *old_dentry, struct inode *new_dir, struct dentry *new_dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/namei_vfat.c (ffffffff81334330)
Location: fs/fat/namei_vfat.c:905
Inline: False
```
**Symbols:**

```
ffffffff81334330-ffffffff81334834: vfat_rename (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int vfat_rename(struct inode *old_dir, struct dentry *old_dentry, struct inode *new_dir, struct dentry *new_dentry, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/namei_vfat.c (ffffffff8134a0c0)
Location: fs/fat/namei_vfat.c:916
Inline: False
```
**Symbols:**

```
ffffffff8134a0c0-ffffffff8134a619: vfat_rename (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int vfat_rename(struct inode *old_dir, struct dentry *old_dentry, struct inode *new_dir, struct dentry *new_dentry, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/namei_vfat.c (ffffffff8135ebe0)
Location: fs/fat/namei_vfat.c:916
Inline: False
```
**Symbols:**

```
ffffffff8135ebe0-ffffffff8135f1ab: vfat_rename (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int vfat_rename(struct inode *old_dir, struct dentry *old_dentry, struct inode *new_dir, struct dentry *new_dentry, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/namei_vfat.c (ffffffff813838a0)
Location: fs/fat/namei_vfat.c:905
Inline: False
```
**Symbols:**

```
ffffffff813838a0-ffffffff81383e6b: vfat_rename (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int vfat_rename(struct inode *old_dir, struct dentry *old_dentry, struct inode *new_dir, struct dentry *new_dentry, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/namei_vfat.c (0)
Location: fs/fat/namei_vfat.c:898
Inline: False
```
**Symbols:**

```
ffffffff813b26e0-ffffffff813b2c9c: vfat_rename (STB_LOCAL)
ffffffff813b2e8e-ffffffff813b2eb4: vfat_rename.cold.18 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int vfat_rename(struct inode *old_dir, struct dentry *old_dentry, struct inode *new_dir, struct dentry *new_dentry, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/namei_vfat.c (0)
Location: fs/fat/namei_vfat.c:894
Inline: False
```
**Symbols:**

```
ffffffff813cbdd0-ffffffff813cc36c: vfat_rename (STB_LOCAL)
ffffffff813cc378-ffffffff813cc39e: vfat_rename.cold.18 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int vfat_rename(struct inode *old_dir, struct dentry *old_dentry, struct inode *new_dir, struct dentry *new_dentry, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/namei_vfat.c (0)
Location: fs/fat/namei_vfat.c:895
Inline: False
```
**Symbols:**

```
ffffffff813f65e0-ffffffff813f6b99: vfat_rename (STB_LOCAL)
ffffffff813f6ee7-ffffffff813f6f0d: vfat_rename.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int vfat_rename(struct inode *old_dir, struct dentry *old_dentry, struct inode *new_dir, struct dentry *new_dentry, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/namei_vfat.c (0)
Location: fs/fat/namei_vfat.c:895
Inline: False
```
**Symbols:**

```
ffffffff814104b0-ffffffff81410a69: vfat_rename (STB_LOCAL)
ffffffff81410db7-ffffffff81410ddd: vfat_rename.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int vfat_rename(struct inode *old_dir, struct dentry *old_dentry, struct inode *new_dir, struct dentry *new_dentry, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/namei_vfat.c (0)
Location: fs/fat/namei_vfat.c:895
Inline: False
```
**Symbols:**

```
ffffffff8145e730-ffffffff8145ecf7: vfat_rename (STB_LOCAL)
ffffffff8145ed03-ffffffff8145ed29: vfat_rename.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int vfat_rename(struct inode *old_dir, struct dentry *old_dentry, struct inode *new_dir, struct dentry *new_dentry, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/namei_vfat.c (0)
Location: fs/fat/namei_vfat.c:895
Inline: False
```
**Symbols:**

```
ffffffff8147a400-ffffffff8147a9c7: vfat_rename (STB_LOCAL)
ffffffff81bedf49-ffffffff81bedf6f: vfat_rename.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int vfat_rename(struct user_namespace *mnt_userns, struct inode *old_dir, struct dentry *old_dentry, struct inode *new_dir, struct dentry *new_dentry, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/namei_vfat.c (0)
Location: fs/fat/namei_vfat.c:896
Inline: False
```
**Symbols:**

```
ffffffff8147fe40-ffffffff81480406: vfat_rename (STB_LOCAL)
ffffffff81be0053-ffffffff81be0079: vfat_rename.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int vfat_rename(struct user_namespace *mnt_userns, struct inode *old_dir, struct dentry *old_dentry, struct inode *new_dir, struct dentry *new_dentry, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/namei_vfat.c (0)
Location: fs/fat/namei_vfat.c:896
Inline: False
```
**Symbols:**

```
ffffffff814d76e0-ffffffff814d7ca6: vfat_rename (STB_LOCAL)
ffffffff81cd077b-ffffffff81cd07a1: vfat_rename.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int vfat_rename(struct user_namespace *mnt_userns, struct inode *old_dir, struct dentry *old_dentry, struct inode *new_dir, struct dentry *new_dentry, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/namei_vfat.c (0)
Location: fs/fat/namei_vfat.c:892
Inline: False
```
**Symbols:**

```
ffffffff81564cd0-ffffffff815652d4: vfat_rename (STB_LOCAL)
ffffffff81e839ff-ffffffff81e83a30: vfat_rename.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int vfat_rename(struct inode *old_dir, struct dentry *old_dentry, struct inode *new_dir, struct dentry *new_dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/namei_vfat.c (ffffffff816078d0)
Location: fs/fat/namei_vfat.c:931
Inline: False
Direct callers:
  - fs/fat/namei_vfat.c:vfat_rename2
```
**Symbols:**

```
ffffffff816078d0-ffffffff81607ecc: vfat_rename (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int vfat_rename(struct inode *old_dir, struct dentry *old_dentry, struct inode *new_dir, struct dentry *new_dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/namei_vfat.c (ffffffff8163f760)
Location: fs/fat/namei_vfat.c:931
Inline: False
Direct callers:
  - fs/fat/namei_vfat.c:vfat_rename2
```
**Symbols:**

```
ffffffff8163f760-ffffffff8163fd1d: vfat_rename (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int vfat_rename(struct inode *old_dir, struct dentry *old_dentry, struct inode *new_dir, struct dentry *new_dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/namei_vfat.c (ffffffff81678d10)
Location: fs/fat/namei_vfat.c:931
Inline: False
Direct callers:
  - fs/fat/namei_vfat.c:vfat_rename2
```
**Symbols:**

```
ffffffff81678d10-ffffffff816792cd: vfat_rename (STB_LOCAL)
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
int vfat_rename(struct inode *old_dir, struct dentry *old_dentry, struct inode *new_dir, struct dentry *new_dentry, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/namei_vfat.c (ffff8000104f18e8)
Location: fs/fat/namei_vfat.c:895
Inline: False
```
**Symbols:**

```
ffff8000104f18e8-ffff8000104f1df0: vfat_rename (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int vfat_rename(struct inode *old_dir, struct dentry *old_dentry, struct inode *new_dir, struct dentry *new_dentry, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/namei_vfat.c (c06af384)
Location: fs/fat/namei_vfat.c:895
Inline: False
```
**Symbols:**

```
c06af384-c06af90c: vfat_rename (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int vfat_rename(struct inode *old_dir, struct dentry *old_dentry, struct inode *new_dir, struct dentry *new_dentry, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/namei_vfat.c (c000000000630b70)
Location: fs/fat/namei_vfat.c:895
Inline: False
```
**Symbols:**

```
c000000000630b70-c000000000631258: vfat_rename (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int vfat_rename(struct inode *old_dir, struct dentry *old_dentry, struct inode *new_dir, struct dentry *new_dentry, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/namei_vfat.c (ffffffe00036114a)
Location: fs/fat/namei_vfat.c:895
Inline: False
```
**Symbols:**

```
ffffffe00036114a-ffffffe0003615c4: vfat_rename (STB_LOCAL)
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
int vfat_rename(struct inode *old_dir, struct dentry *old_dentry, struct inode *new_dir, struct dentry *new_dentry, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/namei_vfat.c (0)
Location: fs/fat/namei_vfat.c:895
Inline: False
```
**Symbols:**

```
ffffffff81408a90-ffffffff81409049: vfat_rename (STB_LOCAL)
ffffffff81409397-ffffffff814093bd: vfat_rename.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int vfat_rename(struct inode *old_dir, struct dentry *old_dentry, struct inode *new_dir, struct dentry *new_dentry, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/namei_vfat.c (0)
Location: fs/fat/namei_vfat.c:895
Inline: False
```
**Symbols:**

```
ffffffff813f9510-ffffffff813f9ac9: vfat_rename (STB_LOCAL)
ffffffff813f9e17-ffffffff813f9e3d: vfat_rename.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int vfat_rename(struct inode *old_dir, struct dentry *old_dentry, struct inode *new_dir, struct dentry *new_dentry, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/namei_vfat.c (0)
Location: fs/fat/namei_vfat.c:895
Inline: False
```
**Symbols:**

```
ffffffff81405e10-ffffffff814063c9: vfat_rename (STB_LOCAL)
ffffffff81406717-ffffffff8140673d: vfat_rename.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int vfat_rename(struct inode *old_dir, struct dentry *old_dentry, struct inode *new_dir, struct dentry *new_dentry, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/namei_vfat.c (0)
Location: fs/fat/namei_vfat.c:895
Inline: False
```
**Symbols:**

```
ffffffff8141bad0-ffffffff8141c089: vfat_rename (STB_LOCAL)
ffffffff8141c3d7-ffffffff8141c3fd: vfat_rename.cold (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int flags</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct user_namespace *mnt_userns</code>
</li>
<li>
<b>Param reordered. </b>
<code>old_dir, old_dentry, new_dir, new_dentry, flags</code> ➡️ <code>mnt_userns, old_dir, old_dentry, new_dir, new_dentry, flags</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct user_namespace *mnt_userns</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int flags</code>
</li>
<li>
<b>Param reordered. </b>
<code>mnt_userns, old_dir, old_dentry, new_dir, new_dentry, flags</code> ➡️ <code>old_dir, old_dentry, new_dir, new_dentry</code>
</li>
</ul>
</details>
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
