# Function: <code>lock_rename</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct dentry *lock_rename(struct dentry *p1, struct dentry *p2);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81217d80)
Location: fs/namei.c:2609
Inline: True
Direct callers:
  - fs/namei.c:SyS_renameat
  - fs/namei.c:SyS_rename
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/debugfs/inode.c:debugfs_rename
```
**Symbols:**

```
ffffffff81217d80-ffffffff81217e5a: lock_rename (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct dentry *lock_rename(struct dentry *p1, struct dentry *p2);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8123eec0)
Location: fs/namei.c:2830
Inline: True
Direct callers:
  - fs/namei.c:SyS_rename
  - fs/namei.c:SyS_renameat
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/debugfs/inode.c:debugfs_rename
```
**Symbols:**

```
ffffffff8123eec0-ffffffff8123ef79: lock_rename (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct dentry *lock_rename(struct dentry *p1, struct dentry *p2);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81251c90)
Location: fs/namei.c:2794
Inline: True
Direct callers:
  - fs/namei.c:SyS_rename
  - fs/namei.c:SyS_renameat
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/debugfs/inode.c:debugfs_rename
```
**Symbols:**

```
ffffffff81251c90-ffffffff81251d49: lock_rename (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct dentry *lock_rename(struct dentry *p1, struct dentry *p2);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8125d8d0)
Location: fs/namei.c:2839
Inline: True
Direct callers:
  - fs/namei.c:SyS_rename
  - fs/namei.c:SyS_renameat
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/debugfs/inode.c:debugfs_rename
```
**Symbols:**

```
ffffffff8125d8d0-ffffffff8125d989: lock_rename (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct dentry *lock_rename(struct dentry *p1, struct dentry *p2);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8127fc50)
Location: fs/namei.c:2837
Inline: True
Direct callers:
  - fs/namei.c:SyS_rename
  - fs/namei.c:SyS_renameat
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/debugfs/inode.c:debugfs_rename
```
**Symbols:**

```
ffffffff8127fc50-ffffffff8127fd09: lock_rename (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct dentry *lock_rename(struct dentry *p1, struct dentry *p2);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812a5ed0)
Location: fs/namei.c:2838
Inline: True
Direct callers:
  - fs/namei.c:do_renameat2
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/debugfs/inode.c:debugfs_rename
```
**Symbols:**

```
ffffffff812a5ed0-ffffffff812a5f89: lock_rename (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct dentry *lock_rename(struct dentry *p1, struct dentry *p2);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812bb040)
Location: fs/namei.c:2857
Inline: True
Direct callers:
  - fs/namei.c:do_renameat2
  - fs/ecryptfs/inode.c:ecryptfs_rename
```
**Symbols:**

```
ffffffff812bb040-ffffffff812bb0f9: lock_rename (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct dentry *lock_rename(struct dentry *p1, struct dentry *p2);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812d7e50)
Location: fs/namei.c:2855
Inline: True
Direct callers:
  - fs/namei.c:do_renameat2
  - fs/ecryptfs/inode.c:ecryptfs_rename
```
**Symbols:**

```
ffffffff812d7e50-ffffffff812d7f07: lock_rename (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct dentry *lock_rename(struct dentry *p1, struct dentry *p2);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812e99c0)
Location: fs/namei.c:2848
Inline: True
Direct callers:
  - fs/namei.c:do_renameat2
  - fs/ecryptfs/inode.c:ecryptfs_rename
```
**Symbols:**

```
ffffffff812e99c0-ffffffff812e9a77: lock_rename (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct dentry *lock_rename(struct dentry *p1, struct dentry *p2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81321310)
Location: fs/namei.c:2750
Inline: False
Direct callers:
  - fs/namei.c:do_renameat2
  - fs/ecryptfs/inode.c:ecryptfs_rename
```
**Symbols:**

```
ffffffff81321310-ffffffff813213c7: lock_rename (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct dentry *lock_rename(struct dentry *p1, struct dentry *p2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8132c8b0)
Location: fs/namei.c:2748
Inline: False
Direct callers:
  - fs/namei.c:do_renameat2
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
```
**Symbols:**

```
ffffffff8132c8b0-ffffffff8132c967: lock_rename (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct dentry *lock_rename(struct dentry *p1, struct dentry *p2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81332520)
Location: fs/namei.c:2841
Inline: False
Direct callers:
  - fs/namei.c:do_renameat2
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
```
**Symbols:**

```
ffffffff81332520-ffffffff813325d7: lock_rename (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct dentry *lock_rename(struct dentry *p1, struct dentry *p2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8137fcb0)
Location: fs/namei.c:2910
Inline: False
Direct callers:
  - fs/namei.c:do_renameat2
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
```
**Symbols:**

```
ffffffff8137fcb0-ffffffff8137fd67: lock_rename (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct dentry *lock_rename(struct dentry *p1, struct dentry *p2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff813ffec0)
Location: fs/namei.c:3006
Inline: False
Direct callers:
  - fs/namei.c:do_renameat2
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/debugfs/inode.c:debugfs_rename
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
```
**Symbols:**

```
ffffffff813ffec0-ffffffff813fffb3: lock_rename (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct dentry *lock_rename(struct dentry *p1, struct dentry *p2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81489ef0)
Location: fs/namei.c:2985
Inline: False
Direct callers:
  - fs/namei.c:do_renameat2
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/debugfs/inode.c:debugfs_rename
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
```
**Symbols:**

```
ffffffff81489ef0-ffffffff81489fe3: lock_rename (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct dentry *lock_rename(struct dentry *p1, struct dentry *p2);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff814c8d26)
Location: fs/namei.c:3039
Inline: True
Inline callers:
  - fs/namei.c:do_renameat2
Direct callers:
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/debugfs/inode.c:debugfs_rename
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
```
**Symbols:**

```
ffffffff814bf290-ffffffff814bf2e3: lock_rename (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct dentry *lock_rename(struct dentry *p1, struct dentry *p2);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff814fb5d6)
Location: fs/namei.c:3066
Inline: True
Inline callers:
  - fs/namei.c:do_renameat2
Direct callers:
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/debugfs/inode.c:debugfs_rename
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
```
**Symbols:**

```
ffffffff814f1460-ffffffff814f14b3: lock_rename (STB_GLOBAL)
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
struct dentry *lock_rename(struct dentry *p1, struct dentry *p2);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffff800010392ef0)
Location: fs/namei.c:2848
Inline: True
Direct callers:
  - fs/namei.c:do_renameat2
  - fs/ecryptfs/inode.c:ecryptfs_rename
```
**Symbols:**

```
ffff800010392ef0-ffff800010392fb4: lock_rename (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct dentry *lock_rename(struct dentry *p1, struct dentry *p2);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (c057a158)
Location: fs/namei.c:2848
Inline: True
Direct callers:
  - fs/namei.c:do_renameat2
  - fs/ecryptfs/inode.c:ecryptfs_rename
```
**Symbols:**

```
c057a158-c057a200: lock_rename (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct dentry *lock_rename(struct dentry *p1, struct dentry *p2);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (c00000000048c380)
Location: fs/namei.c:2848
Inline: True
Direct callers:
  - fs/namei.c:do_renameat2
  - fs/ecryptfs/inode.c:ecryptfs_rename
```
**Symbols:**

```
c00000000048c380-c00000000048c498: lock_rename (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct dentry *lock_rename(struct dentry *p1, struct dentry *p2);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffe000261f82)
Location: fs/namei.c:2848
Inline: True
Direct callers:
  - fs/namei.c:do_renameat2
  - fs/ecryptfs/inode.c:ecryptfs_rename
```
**Symbols:**

```
ffffffe000261f82-ffffffe00026203c: lock_rename (STB_GLOBAL)
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
struct dentry *lock_rename(struct dentry *p1, struct dentry *p2);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812e1fa0)
Location: fs/namei.c:2848
Inline: True
Direct callers:
  - fs/namei.c:do_renameat2
  - fs/ecryptfs/inode.c:ecryptfs_rename
```
**Symbols:**

```
ffffffff812e1fa0-ffffffff812e2057: lock_rename (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct dentry *lock_rename(struct dentry *p1, struct dentry *p2);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812d2be0)
Location: fs/namei.c:2848
Inline: True
Direct callers:
  - fs/namei.c:do_renameat2
  - fs/ecryptfs/inode.c:ecryptfs_rename
```
**Symbols:**

```
ffffffff812d2be0-ffffffff812d2c97: lock_rename (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct dentry *lock_rename(struct dentry *p1, struct dentry *p2);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812dfdb0)
Location: fs/namei.c:2848
Inline: True
Direct callers:
  - fs/namei.c:do_renameat2
  - fs/ecryptfs/inode.c:ecryptfs_rename
```
**Symbols:**

```
ffffffff812dfdb0-ffffffff812dfe67: lock_rename (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct dentry *lock_rename(struct dentry *p1, struct dentry *p2);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812f1470)
Location: fs/namei.c:2848
Inline: True
Direct callers:
  - fs/namei.c:do_renameat2
  - fs/ecryptfs/inode.c:ecryptfs_rename
```
**Symbols:**

```
ffffffff812f1470-ffffffff812f1527: lock_rename (STB_GLOBAL)
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
