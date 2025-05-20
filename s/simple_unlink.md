# Function: <code>simple_unlink</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int simple_unlink(struct inode *dir, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff81233c90)
Location: fs/libfs.c:300
Inline: False
Direct callers:
  - fs/libfs.c:simple_rmdir
  - fs/libfs.c:simple_rename
  - fs/pstore/inode.c:pstore_unlink
  - security/inode.c:securityfs_remove
```
**Symbols:**

```
ffffffff81233c90-ffffffff81233cec: simple_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int simple_unlink(struct inode *dir, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff8125c2c0)
Location: fs/libfs.c:328
Inline: False
Direct callers:
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_rmdir
  - fs/pstore/inode.c:pstore_unlink
  - security/inode.c:securityfs_remove
```
**Symbols:**

```
ffffffff8125c2c0-ffffffff8125c31c: simple_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int simple_unlink(struct inode *dir, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff8126f830)
Location: fs/libfs.c:330
Inline: False
Direct callers:
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_rmdir
  - fs/pstore/inode.c:pstore_unlink
  - security/inode.c:securityfs_remove
```
**Symbols:**

```
ffffffff8126f830-ffffffff8126f887: simple_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int simple_unlink(struct inode *dir, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff8127d010)
Location: fs/libfs.c:331
Inline: False
Direct callers:
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_rmdir
  - fs/configfs/inode.c:configfs_drop_dentry
  - fs/pstore/inode.c:pstore_unlink
```
**Symbols:**

```
ffffffff8127d010-ffffffff8127d06b: simple_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int simple_unlink(struct inode *dir, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff8129fab0)
Location: fs/libfs.c:331
Inline: False
Direct callers:
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_rmdir
  - fs/configfs/inode.c:configfs_drop_dentry
  - fs/pstore/inode.c:pstore_unlink
```
**Symbols:**

```
ffffffff8129fab0-ffffffff8129fb0b: simple_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int simple_unlink(struct inode *dir, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff812c64d0)
Location: fs/libfs.c:331
Inline: False
Direct callers:
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_rmdir
  - fs/configfs/inode.c:configfs_drop_dentry
  - fs/pstore/inode.c:pstore_unlink
```
**Symbols:**

```
ffffffff812c64d0-ffffffff812c6527: simple_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int simple_unlink(struct inode *dir, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff812db6d0)
Location: fs/libfs.c:331
Inline: False
Direct callers:
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_rmdir
  - fs/configfs/inode.c:configfs_drop_dentry
  - fs/pstore/inode.c:pstore_unlink
```
**Symbols:**

```
ffffffff812db6d0-ffffffff812db727: simple_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int simple_unlink(struct inode *dir, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff812f9d60)
Location: fs/libfs.c:350
Inline: False
Direct callers:
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_rmdir
  - fs/configfs/inode.c:configfs_drop_dentry
  - fs/pstore/inode.c:pstore_unlink
  - security/inode.c:securityfs_remove
  - security/apparmor/apparmorfs.c:aafs_remove
```
**Symbols:**

```
ffffffff812f9d60-ffffffff812f9db7: simple_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int simple_unlink(struct inode *dir, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff8130b990)
Location: fs/libfs.c:356
Inline: False
Direct callers:
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_rmdir
  - fs/configfs/inode.c:configfs_drop_dentry
  - fs/pstore/inode.c:pstore_unlink
  - security/inode.c:securityfs_remove
  - security/apparmor/apparmorfs.c:aafs_remove
```
**Symbols:**

```
ffffffff8130b990-ffffffff8130b9e7: simple_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int simple_unlink(struct inode *dir, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff81346364)
Location: fs/libfs.c:425
Inline: True
Inline callers:
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_rmdir
Direct callers:
  - fs/configfs/inode.c:configfs_drop_dentry
  - fs/pstore/inode.c:pstore_put_backend_records
  - fs/pstore/inode.c:pstore_unlink
  - security/inode.c:securityfs_remove
  - security/apparmor/apparmorfs.c:aafs_remove
```
**Symbols:**

```
ffffffff81344f60-ffffffff81344fb7: simple_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int simple_unlink(struct inode *dir, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff81352854)
Location: fs/libfs.c:427
Inline: True
Inline callers:
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_rmdir
Direct callers:
  - fs/configfs/inode.c:configfs_drop_dentry
  - fs/pstore/inode.c:pstore_put_backend_records
  - fs/pstore/inode.c:pstore_unlink
  - security/inode.c:securityfs_remove
  - security/apparmor/apparmorfs.c:aafs_remove
```
**Symbols:**

```
ffffffff813512b0-ffffffff81351307: simple_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int simple_unlink(struct inode *dir, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff81359574)
Location: fs/libfs.c:428
Inline: True
Inline callers:
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_rmdir
Direct callers:
  - fs/configfs/inode.c:configfs_drop_dentry
  - fs/pstore/inode.c:pstore_put_backend_records
  - fs/pstore/inode.c:pstore_unlink
  - security/inode.c:securityfs_remove
  - security/apparmor/apparmorfs.c:aafs_remove
```
**Symbols:**

```
ffffffff81357fc0-ffffffff81358017: simple_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int simple_unlink(struct inode *dir, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff813a7a14)
Location: fs/libfs.c:428
Inline: True
Inline callers:
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_rmdir
Direct callers:
  - fs/configfs/inode.c:configfs_drop_dentry
  - fs/pstore/inode.c:pstore_put_backend_records
  - fs/pstore/inode.c:pstore_unlink
  - security/inode.c:securityfs_remove
  - security/apparmor/apparmorfs.c:aafs_remove
```
**Symbols:**

```
ffffffff813a6410-ffffffff813a6467: simple_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int simple_unlink(struct inode *dir, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff8142ca6e)
Location: fs/libfs.c:428
Inline: True
Inline callers:
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_rmdir
Direct callers:
  - fs/configfs/inode.c:configfs_drop_dentry
  - fs/pstore/inode.c:pstore_put_backend_records
  - fs/pstore/inode.c:pstore_unlink
  - security/inode.c:securityfs_remove
  - security/apparmor/apparmorfs.c:aafs_remove
```
**Symbols:**

```
ffffffff8142ab40-ffffffff8142aba5: simple_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int simple_unlink(struct inode *dir, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff814ba1be)
Location: fs/libfs.c:429
Inline: True
Inline callers:
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_rmdir
Direct callers:
  - fs/configfs/inode.c:configfs_drop_dentry
  - fs/pstore/inode.c:pstore_put_backend_records
  - fs/pstore/inode.c:pstore_unlink
  - security/inode.c:securityfs_remove
  - security/apparmor/apparmorfs.c:aafs_remove
```
**Symbols:**

```
ffffffff814b7c30-ffffffff814b7c95: simple_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int simple_unlink(struct inode *dir, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff814ef15e)
Location: fs/libfs.c:424
Inline: True
Inline callers:
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_rmdir
Direct callers:
  - fs/configfs/inode.c:configfs_drop_dentry
  - fs/pstore/inode.c:pstore_put_backend_records
  - fs/pstore/inode.c:pstore_unlink
  - security/inode.c:securityfs_remove
  - security/apparmor/apparmorfs.c:aafs_remove
```
**Symbols:**

```
ffffffff814ece40-ffffffff814ecea5: simple_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int simple_unlink(struct inode *dir, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff815231c9)
Location: fs/libfs.c:681
Inline: True
Inline callers:
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_rmdir
Direct callers:
  - fs/configfs/inode.c:configfs_drop_dentry
  - fs/pstore/inode.c:pstore_put_backend_records
  - fs/pstore/inode.c:pstore_unlink
  - security/inode.c:securityfs_remove
  - security/apparmor/apparmorfs.c:aafs_remove
```
**Symbols:**

```
ffffffff81520ef0-ffffffff81520f46: simple_unlink (STB_GLOBAL)
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
int simple_unlink(struct inode *dir, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffff8000103c0010)
Location: fs/libfs.c:356
Inline: False
Direct callers:
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_rmdir
  - fs/configfs/inode.c:configfs_drop_dentry
  - fs/pstore/inode.c:pstore_unlink
  - security/inode.c:securityfs_remove
  - security/apparmor/apparmorfs.c:aafs_remove
```
**Symbols:**

```
ffff8000103c0010-ffff8000103c0070: simple_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int simple_unlink(struct inode *dir, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (c059d0f0)
Location: fs/libfs.c:356
Inline: False
Direct callers:
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_rmdir
  - fs/configfs/inode.c:configfs_drop_dentry
  - fs/pstore/inode.c:pstore_unlink
  - security/inode.c:securityfs_remove
  - security/apparmor/apparmorfs.c:aafs_remove
```
**Symbols:**

```
c059d0f0-c059d18c: simple_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int simple_unlink(struct inode *dir, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (c0000000004beeb0)
Location: fs/libfs.c:356
Inline: False
Direct callers:
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_rmdir
  - fs/configfs/inode.c:configfs_drop_dentry
  - fs/pstore/inode.c:pstore_unlink
  - security/inode.c:securityfs_remove
  - security/apparmor/apparmorfs.c:aafs_remove
```
**Symbols:**

```
c0000000004beeb0-c0000000004bef44: simple_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int simple_unlink(struct inode *dir, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffe0002807f4)
Location: fs/libfs.c:356
Inline: False
Direct callers:
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_rmdir
  - fs/configfs/inode.c:configfs_drop_dentry
  - fs/pstore/inode.c:pstore_unlink
  - security/inode.c:securityfs_remove
  - security/apparmor/apparmorfs.c:aafs_remove
```
**Symbols:**

```
ffffffe0002807f4-ffffffe000280854: simple_unlink (STB_GLOBAL)
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
int simple_unlink(struct inode *dir, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff81303f70)
Location: fs/libfs.c:356
Inline: False
Direct callers:
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_rmdir
  - fs/configfs/inode.c:configfs_drop_dentry
  - fs/pstore/inode.c:pstore_unlink
  - security/inode.c:securityfs_remove
  - security/apparmor/apparmorfs.c:aafs_remove
```
**Symbols:**

```
ffffffff81303f70-ffffffff81303fc7: simple_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int simple_unlink(struct inode *dir, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff812f4b90)
Location: fs/libfs.c:356
Inline: False
Direct callers:
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_rmdir
  - fs/configfs/inode.c:configfs_drop_dentry
  - fs/pstore/inode.c:pstore_unlink
  - security/inode.c:securityfs_remove
  - security/apparmor/apparmorfs.c:aafs_remove
```
**Symbols:**

```
ffffffff812f4b90-ffffffff812f4be7: simple_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int simple_unlink(struct inode *dir, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff81301d60)
Location: fs/libfs.c:356
Inline: False
Direct callers:
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_rmdir
  - fs/configfs/inode.c:configfs_drop_dentry
  - fs/pstore/inode.c:pstore_unlink
  - security/inode.c:securityfs_remove
  - security/apparmor/apparmorfs.c:aafs_remove
```
**Symbols:**

```
ffffffff81301d60-ffffffff81301db7: simple_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int simple_unlink(struct inode *dir, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff81313130)
Location: fs/libfs.c:356
Inline: False
Direct callers:
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_rmdir
  - fs/configfs/inode.c:configfs_drop_dentry
  - fs/pstore/inode.c:pstore_unlink
  - security/inode.c:securityfs_remove
  - security/apparmor/apparmorfs.c:aafs_remove
```
**Symbols:**

```
ffffffff81313130-ffffffff81313187: simple_unlink (STB_GLOBAL)
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
