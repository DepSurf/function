# Function: <code>security_inode_init_security</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int security_inode_init_security(struct inode *inode, struct inode *dir, const struct qstr *qstr, const initxattrs initxattrs, void *fs_data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8133c800)
Location: security/security.c:366
Inline: True
Direct callers:
  - mm/shmem.c:shmem_tmpfile
  - mm/shmem.c:shmem_mknod
  - mm/shmem.c:shmem_symlink
  - fs/ext4/xattr_security.c:ext4_init_security
```
**Symbols:**

```
ffffffff8133c800-ffffffff8133c988: security_inode_init_security (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int security_inode_init_security(struct inode *inode, struct inode *dir, const struct qstr *qstr, const initxattrs initxattrs, void *fs_data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81371e40)
Location: security/security.c:367
Inline: True
Direct callers:
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_tmpfile
  - mm/shmem.c:shmem_mknod
  - fs/ext4/xattr_security.c:ext4_init_security
```
**Symbols:**

```
ffffffff81371e40-ffffffff81371fb4: security_inode_init_security (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int security_inode_init_security(struct inode *inode, struct inode *dir, const struct qstr *qstr, const initxattrs initxattrs, void *fs_data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81388770)
Location: security/security.c:376
Inline: True
Direct callers:
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_tmpfile
  - mm/shmem.c:shmem_mknod
  - fs/ext4/xattr_security.c:ext4_init_security
```
**Symbols:**

```
ffffffff81388770-ffffffff813888e4: security_inode_init_security (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int security_inode_init_security(struct inode *inode, struct inode *dir, const struct qstr *qstr, const initxattrs initxattrs, void *fs_data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8139d700)
Location: security/security.c:981
Inline: True
Direct callers:
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_tmpfile
  - mm/shmem.c:shmem_mknod
  - fs/ext4/xattr_security.c:ext4_init_security
```
**Symbols:**

```
ffffffff8139d700-ffffffff8139d868: security_inode_init_security (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int security_inode_init_security(struct inode *inode, struct inode *dir, const struct qstr *qstr, const initxattrs initxattrs, void *fs_data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813c2fd0)
Location: security/security.c:930
Inline: True
Direct callers:
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_tmpfile
  - mm/shmem.c:shmem_mknod
  - fs/ext4/xattr_security.c:ext4_init_security
```
**Symbols:**

```
ffffffff813c2fd0-ffffffff813c3149: security_inode_init_security (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int security_inode_init_security(struct inode *inode, struct inode *dir, const struct qstr *qstr, const initxattrs initxattrs, void *fs_data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813f3ba0)
Location: security/security.c:472
Inline: True
Direct callers:
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_tmpfile
  - mm/shmem.c:shmem_mknod
  - fs/ext4/xattr_security.c:ext4_init_security
```
**Symbols:**

```
ffffffff813f3ba0-ffffffff813f3d0d: security_inode_init_security (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int security_inode_init_security(struct inode *inode, struct inode *dir, const struct qstr *qstr, const initxattrs initxattrs, void *fs_data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8140f0e0)
Location: security/security.c:993
Inline: True
Direct callers:
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_tmpfile
  - mm/shmem.c:shmem_mknod
  - fs/ext4/xattr_security.c:ext4_init_security
```
**Symbols:**

```
ffffffff8140f0e0-ffffffff8140f24d: security_inode_init_security (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int security_inode_init_security(struct inode *inode, struct inode *dir, const struct qstr *qstr, const initxattrs initxattrs, void *fs_data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8143c4e0)
Location: security/security.c:1007
Inline: True
Direct callers:
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_tmpfile
  - mm/shmem.c:shmem_mknod
  - fs/ext4/xattr_security.c:ext4_init_security
```
**Symbols:**

```
ffffffff8143c4e0-ffffffff8143c64c: security_inode_init_security (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int security_inode_init_security(struct inode *inode, struct inode *dir, const struct qstr *qstr, const initxattrs initxattrs, void *fs_data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81456060)
Location: security/security.c:1047
Inline: True
Direct callers:
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_tmpfile
  - mm/shmem.c:shmem_mknod
  - fs/ext4/xattr_security.c:ext4_init_security
```
**Symbols:**

```
ffffffff81456060-ffffffff814561c2: security_inode_init_security (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int security_inode_init_security(struct inode *inode, struct inode *dir, const struct qstr *qstr, const initxattrs initxattrs, void *fs_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814a8ac0)
Location: security/security.c:1195
Inline: False
Direct callers:
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_tmpfile
  - mm/shmem.c:shmem_mknod
  - fs/ext4/xattr_security.c:ext4_init_security
```
**Symbols:**

```
ffffffff814a8ac0-ffffffff814a8c16: security_inode_init_security (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int security_inode_init_security(struct inode *inode, struct inode *dir, const struct qstr *qstr, const initxattrs initxattrs, void *fs_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814c6030)
Location: security/security.c:1197
Inline: False
Direct callers:
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_tmpfile
  - mm/shmem.c:shmem_mknod
  - fs/ext4/xattr_security.c:ext4_init_security
```
**Symbols:**

```
ffffffff814c6030-ffffffff814c6186: security_inode_init_security (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int security_inode_init_security(struct inode *inode, struct inode *dir, const struct qstr *qstr, const initxattrs initxattrs, void *fs_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814cc2e0)
Location: security/security.c:1242
Inline: False
Direct callers:
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_tmpfile
  - mm/shmem.c:shmem_mknod
  - fs/ext4/xattr_security.c:ext4_init_security
```
**Symbols:**

```
ffffffff814cc2e0-ffffffff814cc436: security_inode_init_security (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int security_inode_init_security(struct inode *inode, struct inode *dir, const struct qstr *qstr, const initxattrs initxattrs, void *fs_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81525170)
Location: security/security.c:1242
Inline: False
Direct callers:
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_tmpfile
  - mm/shmem.c:shmem_mknod
  - fs/ext4/xattr_security.c:ext4_init_security
```
**Symbols:**

```
ffffffff81525170-ffffffff815252c6: security_inode_init_security (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int security_inode_init_security(struct inode *inode, struct inode *dir, const struct qstr *qstr, const initxattrs initxattrs, void *fs_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff815b90b0)
Location: security/security.c:1262
Inline: False
Direct callers:
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_tmpfile
  - mm/shmem.c:shmem_mknod
  - fs/ext4/xattr_security.c:ext4_init_security
```
**Symbols:**

```
ffffffff815b90b0-ffffffff815b923d: security_inode_init_security (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int security_inode_init_security(struct inode *inode, struct inode *dir, const struct qstr *qstr, const initxattrs initxattrs, void *fs_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81664810)
Location: security/security.c:1260
Inline: False
Direct callers:
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_tmpfile
  - mm/shmem.c:shmem_mknod
  - fs/ext4/xattr_security.c:ext4_init_security
```
**Symbols:**

```
ffffffff81664810-ffffffff8166499d: security_inode_init_security (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int security_inode_init_security(struct inode *inode, struct inode *dir, const struct qstr *qstr, const initxattrs initxattrs, void *fs_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8169ccf0)
Location: security/security.c:1756
Inline: False
Direct callers:
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_tmpfile
  - mm/shmem.c:shmem_mknod
  - fs/ext4/xattr_security.c:ext4_init_security
```
**Symbols:**

```
ffffffff8169ccf0-ffffffff8169ce7f: security_inode_init_security (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int security_inode_init_security(struct inode *inode, struct inode *dir, const struct qstr *qstr, const initxattrs initxattrs, void *fs_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816d9640)
Location: security/security.c:1811
Inline: False
Direct callers:
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_tmpfile
  - mm/shmem.c:shmem_mknod
  - fs/ext4/xattr_security.c:ext4_init_security
```
**Symbols:**

```
ffffffff816d9640-ffffffff816d980e: security_inode_init_security (STB_GLOBAL)
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
int security_inode_init_security(struct inode *inode, struct inode *dir, const struct qstr *qstr, const initxattrs initxattrs, void *fs_data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/security.c (ffff800010541830)
Location: security/security.c:1047
Inline: True
Direct callers:
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_tmpfile
  - mm/shmem.c:shmem_mknod
  - fs/ext4/xattr_security.c:ext4_init_security
```
**Symbols:**

```
ffff800010541830-ffff8000105419c0: security_inode_init_security (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int security_inode_init_security(struct inode *inode, struct inode *dir, const struct qstr *qstr, const initxattrs initxattrs, void *fs_data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/security.c (c06f77f4)
Location: security/security.c:1047
Inline: True
Direct callers:
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_tmpfile
  - mm/shmem.c:shmem_mknod
  - fs/ext4/xattr_security.c:ext4_init_security
```
**Symbols:**

```
c06f77f4-c06f7990: security_inode_init_security (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int security_inode_init_security(struct inode *inode, struct inode *dir, const struct qstr *qstr, const initxattrs initxattrs, void *fs_data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/security.c (c000000000694050)
Location: security/security.c:1047
Inline: True
Direct callers:
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_tmpfile
  - mm/shmem.c:shmem_mknod
  - fs/ext4/xattr_security.c:ext4_init_security
```
**Symbols:**

```
c000000000694050-c00000000069429c: security_inode_init_security (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int security_inode_init_security(struct inode *inode, struct inode *dir, const struct qstr *qstr, const initxattrs initxattrs, void *fs_data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffe00039e4d0)
Location: security/security.c:1047
Inline: True
Direct callers:
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_tmpfile
  - mm/shmem.c:shmem_mknod
  - fs/ext4/xattr_security.c:ext4_init_security
```
**Symbols:**

```
ffffffe00039e4d0-ffffffe00039e5e6: security_inode_init_security (STB_GLOBAL)
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
int security_inode_init_security(struct inode *inode, struct inode *dir, const struct qstr *qstr, const initxattrs initxattrs, void *fs_data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8144e640)
Location: security/security.c:1047
Inline: True
Direct callers:
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_tmpfile
  - mm/shmem.c:shmem_mknod
  - fs/ext4/xattr_security.c:ext4_init_security
```
**Symbols:**

```
ffffffff8144e640-ffffffff8144e7a2: security_inode_init_security (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int security_inode_init_security(struct inode *inode, struct inode *dir, const struct qstr *qstr, const initxattrs initxattrs, void *fs_data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8143f090)
Location: security/security.c:1047
Inline: True
Direct callers:
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_tmpfile
  - mm/shmem.c:shmem_mknod
  - fs/ext4/xattr_security.c:ext4_init_security
```
**Symbols:**

```
ffffffff8143f090-ffffffff8143f1f2: security_inode_init_security (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int security_inode_init_security(struct inode *inode, struct inode *dir, const struct qstr *qstr, const initxattrs initxattrs, void *fs_data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8144a6e0)
Location: security/security.c:1047
Inline: True
Direct callers:
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_tmpfile
  - mm/shmem.c:shmem_mknod
  - fs/ext4/xattr_security.c:ext4_init_security
```
**Symbols:**

```
ffffffff8144a6e0-ffffffff8144a842: security_inode_init_security (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int security_inode_init_security(struct inode *inode, struct inode *dir, const struct qstr *qstr, const initxattrs initxattrs, void *fs_data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81461ab0)
Location: security/security.c:1047
Inline: True
Direct callers:
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_tmpfile
  - mm/shmem.c:shmem_mknod
  - fs/ext4/xattr_security.c:ext4_init_security
```
**Symbols:**

```
ffffffff81461ab0-ffffffff81461c12: security_inode_init_security (STB_GLOBAL)
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
