# Function: <code>ns_mkdir_op</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int ns_mkdir_op(struct inode *dir, struct dentry *dentry, umode_t mode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff813ac7e0)
Location: security/apparmor/apparmorfs.c:1033
Inline: True
```
**Symbols:**

```
ffffffff813ac7e0-ffffffff813acb8b: ns_mkdir_op (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int ns_mkdir_op(struct inode *dir, struct dentry *dentry, umode_t mode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff813c35f0)
Location: security/apparmor/apparmorfs.c:1129
Inline: True
```
**Symbols:**

```
ffffffff813c35f0-ffffffff813c399b: ns_mkdir_op (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int ns_mkdir_op(struct inode *dir, struct dentry *dentry, umode_t mode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff813da4a0)
Location: security/apparmor/apparmorfs.c:1625
Inline: True
```
**Symbols:**

```
ffffffff813da4a0-ffffffff813da793: ns_mkdir_op (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int ns_mkdir_op(struct inode *dir, struct dentry *dentry, umode_t mode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff81401800)
Location: security/apparmor/apparmorfs.c:1689
Inline: True
```
**Symbols:**

```
ffffffff81401800-ffffffff81401b19: ns_mkdir_op (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int ns_mkdir_op(struct inode *dir, struct dentry *dentry, umode_t mode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff814328d0)
Location: security/apparmor/apparmorfs.c:1686
Inline: True
```
**Symbols:**

```
ffffffff814328d0-ffffffff81432bf7: ns_mkdir_op (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int ns_mkdir_op(struct inode *dir, struct dentry *dentry, umode_t mode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff8144f010)
Location: security/apparmor/apparmorfs.c:1684
Inline: True
```
**Symbols:**

```
ffffffff8144f010-ffffffff8144f35d: ns_mkdir_op (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int ns_mkdir_op(struct inode *dir, struct dentry *dentry, umode_t mode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff8147c5f0)
Location: security/apparmor/apparmorfs.c:1689
Inline: True
```
**Symbols:**

```
ffffffff8147c5f0-ffffffff8147c91c: ns_mkdir_op (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int ns_mkdir_op(struct inode *dir, struct dentry *dentry, umode_t mode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff814962c0)
Location: security/apparmor/apparmorfs.c:1657
Inline: True
```
**Symbols:**

```
ffffffff814962c0-ffffffff814965ec: ns_mkdir_op (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ns_mkdir_op(struct inode *dir, struct dentry *dentry, umode_t mode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff814ef1c0)
Location: security/apparmor/apparmorfs.c:1776
Inline: True
```
**Symbols:**

```
ffffffff814ef1c0-ffffffff814ef426: ns_mkdir_op.part.0 (STB_LOCAL)
ffffffff814ef430-ffffffff814ef4e1: ns_mkdir_op (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ns_mkdir_op(struct inode *dir, struct dentry *dentry, umode_t mode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff8150c640)
Location: security/apparmor/apparmorfs.c:1776
Inline: True
```
**Symbols:**

```
ffffffff8150c640-ffffffff8150c8aa: ns_mkdir_op.part.0 (STB_LOCAL)
ffffffff8150c8b0-ffffffff8150c961: ns_mkdir_op (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int ns_mkdir_op(struct user_namespace *mnt_userns, struct inode *dir, struct dentry *dentry, umode_t mode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff81513270)
Location: security/apparmor/apparmorfs.c:1776
Inline: True
```
**Symbols:**

```
ffffffff81513270-ffffffff81513526: ns_mkdir_op (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int ns_mkdir_op(struct user_namespace *mnt_userns, struct inode *dir, struct dentry *dentry, umode_t mode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff81570e70)
Location: security/apparmor/apparmorfs.c:1776
Inline: True
```
**Symbols:**

```
ffffffff81570e70-ffffffff81571126: ns_mkdir_op (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int ns_mkdir_op(struct user_namespace *mnt_userns, struct inode *dir, struct dentry *dentry, umode_t mode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff8160c7b0)
Location: security/apparmor/apparmorfs.c:1796
Inline: True
```
**Symbols:**

```
ffffffff8160c7b0-ffffffff8160ca97: ns_mkdir_op (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int ns_mkdir_op(struct user_namespace *mnt_userns, struct inode *dir, struct dentry *dentry, umode_t mode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff816be0a0)
Location: security/apparmor/apparmorfs.c:1983
Inline: True
```
**Symbols:**

```
ffffffff816be0a0-ffffffff816be38e: ns_mkdir_op (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int ns_mkdir_op(struct mnt_idmap *idmap, struct inode *dir, struct dentry *dentry, umode_t mode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff816f6b50)
Location: security/apparmor/apparmorfs.c:2031
Inline: True
```
**Symbols:**

```
ffffffff816f6b50-ffffffff816f6e32: ns_mkdir_op (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int ns_mkdir_op(struct mnt_idmap *idmap, struct inode *dir, struct dentry *dentry, umode_t mode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff817338c0)
Location: security/apparmor/apparmorfs.c:2029
Inline: True
```
**Symbols:**

```
ffffffff817338c0-ffffffff81733ba5: ns_mkdir_op (STB_LOCAL)
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
int ns_mkdir_op(struct inode *dir, struct dentry *dentry, umode_t mode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffff80001058be18)
Location: security/apparmor/apparmorfs.c:1657
Inline: True
```
**Symbols:**

```
ffff80001058be18-ffff80001058c10c: ns_mkdir_op (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int ns_mkdir_op(struct inode *dir, struct dentry *dentry, umode_t mode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (c073c994)
Location: security/apparmor/apparmorfs.c:1657
Inline: True
```
**Symbols:**

```
c073c994-c073cca4: ns_mkdir_op (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int ns_mkdir_op(struct inode *dir, struct dentry *dentry, umode_t mode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (c0000000006fd690)
Location: security/apparmor/apparmorfs.c:1657
Inline: True
```
**Symbols:**

```
c0000000006fd690-c0000000006fdb58: ns_mkdir_op (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int ns_mkdir_op(struct inode *dir, struct dentry *dentry, umode_t mode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffe0003da39a)
Location: security/apparmor/apparmorfs.c:1657
Inline: True
```
**Symbols:**

```
ffffffe0003da39a-ffffffe0003da642: ns_mkdir_op (STB_LOCAL)
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
int ns_mkdir_op(struct inode *dir, struct dentry *dentry, umode_t mode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff8148e8a0)
Location: security/apparmor/apparmorfs.c:1657
Inline: True
```
**Symbols:**

```
ffffffff8148e8a0-ffffffff8148ebcc: ns_mkdir_op (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int ns_mkdir_op(struct inode *dir, struct dentry *dentry, umode_t mode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff8147f2c0)
Location: security/apparmor/apparmorfs.c:1657
Inline: True
```
**Symbols:**

```
ffffffff8147f2c0-ffffffff8147f5ec: ns_mkdir_op (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int ns_mkdir_op(struct inode *dir, struct dentry *dentry, umode_t mode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff8148a940)
Location: security/apparmor/apparmorfs.c:1657
Inline: True
```
**Symbols:**

```
ffffffff8148a940-ffffffff8148ac6c: ns_mkdir_op (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int ns_mkdir_op(struct inode *dir, struct dentry *dentry, umode_t mode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff814a2640)
Location: security/apparmor/apparmorfs.c:1657
Inline: True
```
**Symbols:**

```
ffffffff814a2640-ffffffff814a298e: ns_mkdir_op (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct user_namespace *mnt_userns</code>
</li>
<li>
<b>Param reordered. </b>
<code>dir, dentry, mode</code> ➡️ <code>mnt_userns, dir, dentry, mode</code>
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct mnt_idmap *idmap</code>
</li>
<li>
<b>Param removed. </b>
<code>struct user_namespace *mnt_userns</code>
</li>
</ul>
</details>
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
