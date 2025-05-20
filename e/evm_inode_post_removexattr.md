# Function: <code>evm_inode_post_removexattr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void evm_inode_post_removexattr(struct dentry *dentry, const char *xattr_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_main.c (ffffffff8139b180)
Location: security/integrity/evm/evm_main.c:395
Inline: False
Direct callers:
  - fs/xattr.c:vfs_removexattr
```
**Symbols:**

```
ffffffff8139b180-ffffffff8139b1bd: evm_inode_post_removexattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void evm_inode_post_removexattr(struct dentry *dentry, const char *xattr_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_main.c (ffffffff813d7fb0)
Location: security/integrity/evm/evm_main.c:410
Inline: False
Direct callers:
  - fs/xattr.c:__vfs_removexattr_noperm
```
**Symbols:**

```
ffffffff813d7fb0-ffffffff813d800a: evm_inode_post_removexattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void evm_inode_post_removexattr(struct dentry *dentry, const char *xattr_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_main.c (ffffffff813efc60)
Location: security/integrity/evm/evm_main.c:410
Inline: False
```
**Symbols:**

```
ffffffff813efc60-ffffffff813efcba: evm_inode_post_removexattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void evm_inode_post_removexattr(struct dentry *dentry, const char *xattr_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_main.c (ffffffff813fc230)
Location: security/integrity/evm/evm_main.c:412
Inline: False
```
**Symbols:**

```
ffffffff813fc230-ffffffff813fc28e: evm_inode_post_removexattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void evm_inode_post_removexattr(struct dentry *dentry, const char *xattr_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_main.c (ffffffff81424700)
Location: security/integrity/evm/evm_main.c:415
Inline: False
```
**Symbols:**

```
ffffffff81424700-ffffffff8142475e: evm_inode_post_removexattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void evm_inode_post_removexattr(struct dentry *dentry, const char *xattr_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_main.c (ffffffff81456ea0)
Location: security/integrity/evm/evm_main.c:454
Inline: False
```
**Symbols:**

```
ffffffff81456ea0-ffffffff81456ef7: evm_inode_post_removexattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void evm_inode_post_removexattr(struct dentry *dentry, const char *xattr_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_main.c (ffffffff81474340)
Location: security/integrity/evm/evm_main.c:459
Inline: False
```
**Symbols:**

```
ffffffff81474340-ffffffff81474397: evm_inode_post_removexattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void evm_inode_post_removexattr(struct dentry *dentry, const char *xattr_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_main.c (ffffffff814a2070)
Location: security/integrity/evm/evm_main.c:456
Inline: False
```
**Symbols:**

```
ffffffff814a2070-ffffffff814a20c9: evm_inode_post_removexattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void evm_inode_post_removexattr(struct dentry *dentry, const char *xattr_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_main.c (ffffffff814bcd40)
Location: security/integrity/evm/evm_main.c:456
Inline: False
```
**Symbols:**

```
ffffffff814bcd40-ffffffff814bcd99: evm_inode_post_removexattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void evm_inode_post_removexattr(struct dentry *dentry, const char *xattr_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_main.c (ffffffff8151d5f0)
Location: security/integrity/evm/evm_main.c:454
Inline: False
```
**Symbols:**

```
ffffffff8151d5f0-ffffffff8151d649: evm_inode_post_removexattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void evm_inode_post_removexattr(struct dentry *dentry, const char *xattr_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_main.c (ffffffff8153a480)
Location: security/integrity/evm/evm_main.c:463
Inline: False
```
**Symbols:**

```
ffffffff8153a480-ffffffff8153a4d9: evm_inode_post_removexattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void evm_inode_post_removexattr(struct dentry *dentry, const char *xattr_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_main.c (ffffffff81542b40)
Location: security/integrity/evm/evm_main.c:463
Inline: False
```
**Symbols:**

```
ffffffff81542b40-ffffffff81542b99: evm_inode_post_removexattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void evm_inode_post_removexattr(struct dentry *dentry, const char *xattr_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_main.c (ffffffff815a2fa0)
Location: security/integrity/evm/evm_main.c:742
Inline: False
```
**Symbols:**

```
ffffffff815a2fa0-ffffffff815a3011: evm_inode_post_removexattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void evm_inode_post_removexattr(struct dentry *dentry, const char *xattr_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_main.c (ffffffff81649770)
Location: security/integrity/evm/evm_main.c:742
Inline: False
Direct callers:
  - fs/xattr.c:__vfs_removexattr_locked
```
**Symbols:**

```
ffffffff81649770-ffffffff816497fb: evm_inode_post_removexattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void evm_inode_post_removexattr(struct dentry *dentry, const char *xattr_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_main.c (ffffffff81702720)
Location: security/integrity/evm/evm_main.c:766
Inline: False
Direct callers:
  - fs/xattr.c:__vfs_removexattr_locked
  - fs/posix_acl.c:vfs_remove_acl
```
**Symbols:**

```
ffffffff81702720-ffffffff817027ab: evm_inode_post_removexattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void evm_inode_post_removexattr(struct dentry *dentry, const char *xattr_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_main.c (ffffffff8173c690)
Location: security/integrity/evm/evm_main.c:766
Inline: False
Direct callers:
  - fs/xattr.c:__vfs_removexattr_locked
  - fs/posix_acl.c:vfs_remove_acl
```
**Symbols:**

```
ffffffff8173c690-ffffffff8173c71b: evm_inode_post_removexattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void evm_inode_post_removexattr(struct dentry *dentry, const char *xattr_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_main.c (ffffffff8177d460)
Location: security/integrity/evm/evm_main.c:792
Inline: False
Direct callers:
  - fs/xattr.c:__vfs_removexattr_locked
  - fs/posix_acl.c:vfs_remove_acl
```
**Symbols:**

```
ffffffff8177d460-ffffffff8177d4eb: evm_inode_post_removexattr (STB_GLOBAL)
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
void evm_inode_post_removexattr(struct dentry *dentry, const char *xattr_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_main.c (ffff8000105b59a0)
Location: security/integrity/evm/evm_main.c:456
Inline: False
```
**Symbols:**

```
ffff8000105b59a0-ffff8000105b5a20: evm_inode_post_removexattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void evm_inode_post_removexattr(struct dentry *dentry, const char *xattr_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_main.c (c0764ae8)
Location: security/integrity/evm/evm_main.c:456
Inline: False
```
**Symbols:**

```
c0764ae8-c0764b5c: evm_inode_post_removexattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void evm_inode_post_removexattr(struct dentry *dentry, const char *xattr_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_main.c (c000000000739450)
Location: security/integrity/evm/evm_main.c:456
Inline: False
```
**Symbols:**

```
c000000000739450-c0000000007394f0: evm_inode_post_removexattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void evm_inode_post_removexattr(struct dentry *dentry, const char *xattr_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_main.c (ffffffe0003fc7e6)
Location: security/integrity/evm/evm_main.c:456
Inline: False
```
**Symbols:**

```
ffffffe0003fc7e6-ffffffe0003fc860: evm_inode_post_removexattr (STB_GLOBAL)
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
void evm_inode_post_removexattr(struct dentry *dentry, const char *xattr_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_main.c (ffffffff814b5320)
Location: security/integrity/evm/evm_main.c:456
Inline: False
```
**Symbols:**

```
ffffffff814b5320-ffffffff814b5379: evm_inode_post_removexattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void evm_inode_post_removexattr(struct dentry *dentry, const char *xattr_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_main.c (ffffffff814a5d40)
Location: security/integrity/evm/evm_main.c:456
Inline: False
```
**Symbols:**

```
ffffffff814a5d40-ffffffff814a5d99: evm_inode_post_removexattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void evm_inode_post_removexattr(struct dentry *dentry, const char *xattr_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_main.c (ffffffff814b13b0)
Location: security/integrity/evm/evm_main.c:456
Inline: False
```
**Symbols:**

```
ffffffff814b13b0-ffffffff814b1409: evm_inode_post_removexattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void evm_inode_post_removexattr(struct dentry *dentry, const char *xattr_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_main.c (ffffffff814c9e30)
Location: security/integrity/evm/evm_main.c:456
Inline: False
```
**Symbols:**

```
ffffffff814c9e30-ffffffff814c9e89: evm_inode_post_removexattr (STB_GLOBAL)
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
