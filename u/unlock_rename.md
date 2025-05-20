# Function: <code>unlock_rename</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void unlock_rename(struct dentry *p1, struct dentry *p2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812166a0)
Location: fs/namei.c:2640
Inline: False
Direct callers:
  - fs/namei.c:SyS_renameat
  - fs/namei.c:SyS_rename
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/debugfs/inode.c:debugfs_rename
  - fs/debugfs/inode.c:debugfs_rename
```
**Symbols:**

```
ffffffff812166a0-ffffffff812166f1: unlock_rename (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void unlock_rename(struct dentry *p1, struct dentry *p2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8123d870)
Location: fs/namei.c:2861
Inline: False
Direct callers:
  - fs/namei.c:SyS_rename
  - fs/namei.c:SyS_renameat
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/debugfs/inode.c:debugfs_rename
  - fs/debugfs/inode.c:debugfs_rename
```
**Symbols:**

```
ffffffff8123d870-ffffffff8123d8bd: unlock_rename (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void unlock_rename(struct dentry *p1, struct dentry *p2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81250610)
Location: fs/namei.c:2825
Inline: False
Direct callers:
  - fs/namei.c:SyS_rename
  - fs/namei.c:SyS_renameat
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/debugfs/inode.c:debugfs_rename
  - fs/debugfs/inode.c:debugfs_rename
```
**Symbols:**

```
ffffffff81250610-ffffffff8125065d: unlock_rename (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void unlock_rename(struct dentry *p1, struct dentry *p2);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8125d990)
Location: fs/namei.c:2870
Inline: True
Direct callers:
  - fs/namei.c:SyS_rename
  - fs/namei.c:SyS_renameat
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/debugfs/inode.c:debugfs_rename
  - fs/debugfs/inode.c:debugfs_rename
```
**Symbols:**

```
ffffffff8125d990-ffffffff8125d9dd: unlock_rename (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void unlock_rename(struct dentry *p1, struct dentry *p2);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8127fd10)
Location: fs/namei.c:2868
Inline: True
Direct callers:
  - fs/namei.c:SyS_rename
  - fs/namei.c:SyS_renameat
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/debugfs/inode.c:debugfs_rename
  - fs/debugfs/inode.c:debugfs_rename
```
**Symbols:**

```
ffffffff8127fd10-ffffffff8127fd5d: unlock_rename (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void unlock_rename(struct dentry *p1, struct dentry *p2);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812a5f90)
Location: fs/namei.c:2869
Inline: True
Direct callers:
  - fs/namei.c:do_renameat2
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/debugfs/inode.c:debugfs_rename
  - fs/debugfs/inode.c:debugfs_rename
```
**Symbols:**

```
ffffffff812a5f90-ffffffff812a5fdd: unlock_rename (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void unlock_rename(struct dentry *p1, struct dentry *p2);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812bb100)
Location: fs/namei.c:2888
Inline: True
Direct callers:
  - fs/namei.c:do_renameat2
  - fs/ecryptfs/inode.c:ecryptfs_rename
```
**Symbols:**

```
ffffffff812bb100-ffffffff812bb14d: unlock_rename (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void unlock_rename(struct dentry *p1, struct dentry *p2);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812d7f10)
Location: fs/namei.c:2886
Inline: True
Direct callers:
  - fs/namei.c:do_renameat2
  - fs/ecryptfs/inode.c:ecryptfs_rename
```
**Symbols:**

```
ffffffff812d7f10-ffffffff812d7f5d: unlock_rename (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void unlock_rename(struct dentry *p1, struct dentry *p2);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812e9a80)
Location: fs/namei.c:2879
Inline: True
Direct callers:
  - fs/namei.c:do_renameat2
  - fs/ecryptfs/inode.c:ecryptfs_rename
```
**Symbols:**

```
ffffffff812e9a80-ffffffff812e9acd: unlock_rename (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void unlock_rename(struct dentry *p1, struct dentry *p2);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81327eeb)
Location: fs/namei.c:2781
Inline: True
Inline callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
Direct callers:
  - fs/ecryptfs/inode.c:ecryptfs_rename
```
**Symbols:**

```
ffffffff813219f0-ffffffff81321a3d: unlock_rename (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void unlock_rename(struct dentry *p1, struct dentry *p2);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81334a16)
Location: fs/namei.c:2779
Inline: True
Inline callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
Direct callers:
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
```
**Symbols:**

```
ffffffff8132cf90-ffffffff8132cfdd: unlock_rename (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void unlock_rename(struct dentry *p1, struct dentry *p2);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8133aba3)
Location: fs/namei.c:2872
Inline: True
Inline callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
Direct callers:
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
```
**Symbols:**

```
ffffffff81332bd0-ffffffff81332c1d: unlock_rename (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void unlock_rename(struct dentry *p1, struct dentry *p2);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8138873d)
Location: fs/namei.c:2941
Inline: True
Inline callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
Direct callers:
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
```
**Symbols:**

```
ffffffff81380360-ffffffff813803ad: unlock_rename (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void unlock_rename(struct dentry *p1, struct dentry *p2);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8140973a)
Location: fs/namei.c:3037
Inline: True
Inline callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
Direct callers:
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/debugfs/inode.c:debugfs_rename
  - fs/debugfs/inode.c:debugfs_rename
  - fs/debugfs/inode.c:debugfs_rename
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
```
**Symbols:**

```
ffffffff814002c0-ffffffff81400317: unlock_rename (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void unlock_rename(struct dentry *p1, struct dentry *p2);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81493dea)
Location: fs/namei.c:3016
Inline: True
Inline callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
Direct callers:
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/debugfs/inode.c:debugfs_rename
  - fs/debugfs/inode.c:debugfs_rename
  - fs/debugfs/inode.c:debugfs_rename
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
```
**Symbols:**

```
ffffffff8148a330-ffffffff8148a387: unlock_rename (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void unlock_rename(struct dentry *p1, struct dentry *p2);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff814c8e58)
Location: fs/namei.c:3093
Inline: True
Inline callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
Direct callers:
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/debugfs/inode.c:debugfs_rename
  - fs/debugfs/inode.c:debugfs_rename
  - fs/debugfs/inode.c:debugfs_rename
  - fs/debugfs/inode.c:debugfs_rename
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
```
**Symbols:**

```
ffffffff814bf890-ffffffff814bf8e7: unlock_rename (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void unlock_rename(struct dentry *p1, struct dentry *p2);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff814fb717)
Location: fs/namei.c:3120
Inline: True
Inline callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
Direct callers:
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/debugfs/inode.c:debugfs_rename
  - fs/debugfs/inode.c:debugfs_rename
  - fs/debugfs/inode.c:debugfs_rename
  - fs/debugfs/inode.c:debugfs_rename
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
```
**Symbols:**

```
ffffffff814f1d80-ffffffff814f1dd7: unlock_rename (STB_GLOBAL)
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
void unlock_rename(struct dentry *p1, struct dentry *p2);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffff800010392fb8)
Location: fs/namei.c:2879
Inline: True
Direct callers:
  - fs/namei.c:do_renameat2
  - fs/ecryptfs/inode.c:ecryptfs_rename
```
**Symbols:**

```
ffff800010392fb8-ffff80001039300c: unlock_rename (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void unlock_rename(struct dentry *p1, struct dentry *p2);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (c057a200)
Location: fs/namei.c:2879
Inline: True
Direct callers:
  - fs/namei.c:do_renameat2
  - fs/ecryptfs/inode.c:ecryptfs_rename
```
**Symbols:**

```
c057a200-c057a24c: unlock_rename (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void unlock_rename(struct dentry *p1, struct dentry *p2);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (c00000000048c4a0)
Location: fs/namei.c:2879
Inline: True
Direct callers:
  - fs/namei.c:do_renameat2
  - fs/ecryptfs/inode.c:ecryptfs_rename
```
**Symbols:**

```
c00000000048c4a0-c00000000048c51c: unlock_rename (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void unlock_rename(struct dentry *p1, struct dentry *p2);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffe00026203c)
Location: fs/namei.c:2879
Inline: True
Direct callers:
  - fs/namei.c:do_renameat2
  - fs/ecryptfs/inode.c:ecryptfs_rename
```
**Symbols:**

```
ffffffe00026203c-ffffffe000262092: unlock_rename (STB_GLOBAL)
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
void unlock_rename(struct dentry *p1, struct dentry *p2);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812e2060)
Location: fs/namei.c:2879
Inline: True
Direct callers:
  - fs/namei.c:do_renameat2
  - fs/ecryptfs/inode.c:ecryptfs_rename
```
**Symbols:**

```
ffffffff812e2060-ffffffff812e20ad: unlock_rename (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void unlock_rename(struct dentry *p1, struct dentry *p2);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812d2ca0)
Location: fs/namei.c:2879
Inline: True
Direct callers:
  - fs/namei.c:do_renameat2
  - fs/ecryptfs/inode.c:ecryptfs_rename
```
**Symbols:**

```
ffffffff812d2ca0-ffffffff812d2ced: unlock_rename (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void unlock_rename(struct dentry *p1, struct dentry *p2);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812dfe70)
Location: fs/namei.c:2879
Inline: True
Direct callers:
  - fs/namei.c:do_renameat2
  - fs/ecryptfs/inode.c:ecryptfs_rename
```
**Symbols:**

```
ffffffff812dfe70-ffffffff812dfebd: unlock_rename (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void unlock_rename(struct dentry *p1, struct dentry *p2);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812f1530)
Location: fs/namei.c:2879
Inline: True
Direct callers:
  - fs/namei.c:do_renameat2
  - fs/ecryptfs/inode.c:ecryptfs_rename
```
**Symbols:**

```
ffffffff812f1530-ffffffff812f157d: unlock_rename (STB_GLOBAL)
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
