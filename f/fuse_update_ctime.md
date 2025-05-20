# Function: <code>fuse_update_ctime</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff813125f8)
Location: fs/fuse/dir.c:635
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_removexattr
  - fs/fuse/dir.c:fuse_setxattr
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff81346ac7)
Location: fs/fuse/dir.c:639
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_removexattr
  - fs/fuse/dir.c:fuse_setxattr
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_unlink
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

```c
void fuse_update_ctime(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fuse/dir.c (ffffffff8135c877)
Location: fs/fuse/dir.c:652
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_unlink
Direct callers:
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/xattr.c:fuse_removexattr
  - fs/fuse/xattr.c:fuse_setxattr
```
**Symbols:**

```
ffffffff8135c100-ffffffff8135c12d: fuse_update_ctime.part.23 (STB_LOCAL)
ffffffff8135df90-ffffffff8135dfa7: fuse_update_ctime (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void fuse_update_ctime(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fuse/dir.c (ffffffff8137124a)
Location: fs/fuse/dir.c:652
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_unlink
Direct callers:
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/xattr.c:fuse_removexattr
  - fs/fuse/xattr.c:fuse_setxattr
```
**Symbols:**

```
ffffffff81370a90-ffffffff81370ac1: fuse_update_ctime.part.23 (STB_LOCAL)
ffffffff81372a70-ffffffff81372a88: fuse_update_ctime (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void fuse_update_ctime(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fuse/dir.c (ffffffff81395f4a)
Location: fs/fuse/dir.c:652
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_unlink
Direct callers:
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/xattr.c:fuse_removexattr
  - fs/fuse/xattr.c:fuse_setxattr
```
**Symbols:**

```
ffffffff81395790-ffffffff813957c1: fuse_update_ctime.part.25 (STB_LOCAL)
ffffffff81397780-ffffffff81397798: fuse_update_ctime (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
void fuse_update_ctime(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fuse/dir.c (ffffffff813c5845)
Location: fs/fuse/dir.c:653
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_unlink
Direct callers:
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/xattr.c:fuse_removexattr
  - fs/fuse/xattr.c:fuse_setxattr
```
**Symbols:**

```
ffffffff813c49a0-ffffffff813c49cd: fuse_update_ctime.part.27 (STB_LOCAL)
ffffffff813c69e0-ffffffff813c69f7: fuse_update_ctime (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
void fuse_update_ctime(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fuse/dir.c (ffffffff813df2a1)
Location: fs/fuse/dir.c:650
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_unlink
Direct callers:
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/xattr.c:fuse_removexattr
  - fs/fuse/xattr.c:fuse_setxattr
```
**Symbols:**

```
ffffffff813ddf30-ffffffff813ddf5d: fuse_update_ctime.part.23 (STB_LOCAL)
ffffffff813dfba0-ffffffff813dfbb7: fuse_update_ctime (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void fuse_update_ctime(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fuse/dir.c (ffffffff8140aed5)
Location: fs/fuse/dir.c:637
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_unlink
Direct callers:
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/xattr.c:fuse_removexattr
  - fs/fuse/xattr.c:fuse_setxattr
```
**Symbols:**

```
ffffffff81409ff0-ffffffff8140a021: fuse_update_ctime.part.0 (STB_LOCAL)
ffffffff8140b7a0-ffffffff8140b7b7: fuse_update_ctime (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void fuse_update_ctime(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fuse/dir.c (ffffffff81424aaf)
Location: fs/fuse/dir.c:693
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_unlink
Direct callers:
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/xattr.c:fuse_removexattr
  - fs/fuse/xattr.c:fuse_setxattr
```
**Symbols:**

```
ffffffff81423530-ffffffff81423561: fuse_update_ctime.part.0 (STB_LOCAL)
ffffffff81425250-ffffffff81425267: fuse_update_ctime (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void fuse_update_ctime(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff81474120)
Location: fs/fuse/dir.c:693
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_unlink
Direct callers:
  - fs/fuse/xattr.c:fuse_removexattr
  - fs/fuse/xattr.c:fuse_setxattr
```
**Symbols:**

```
ffffffff81474960-ffffffff8147499a: fuse_update_ctime (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void fuse_update_ctime(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff8148ea73)
Location: fs/fuse/dir.c:784
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_unlink
Direct callers:
  - fs/fuse/xattr.c:fuse_removexattr
  - fs/fuse/xattr.c:fuse_setxattr
```
**Symbols:**

```
ffffffff8148f340-ffffffff8148f37a: fuse_update_ctime (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void fuse_update_ctime(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff814944a3)
Location: fs/fuse/dir.c:801
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_unlink
Direct callers:
  - fs/fuse/xattr.c:fuse_removexattr
  - fs/fuse/xattr.c:fuse_setxattr
```
**Symbols:**

```
ffffffff81494d60-ffffffff81494d9a: fuse_update_ctime (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void fuse_update_ctime(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff814ec1c3)
Location: fs/fuse/dir.c:748
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_unlink
Direct callers:
  - fs/fuse/xattr.c:fuse_removexattr
  - fs/fuse/xattr.c:fuse_setxattr
```
**Symbols:**

```
ffffffff814ec7e0-ffffffff814ec822: fuse_update_ctime (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void fuse_update_ctime(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff8157b38c)
Location: fs/fuse/dir.c:854
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_entry_unlinked
Direct callers:
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/xattr.c:fuse_removexattr
  - fs/fuse/xattr.c:fuse_setxattr
```
**Symbols:**

```
ffffffff8157b1a0-ffffffff8157b220: fuse_update_ctime (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void fuse_update_ctime(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff81620b7c)
Location: fs/fuse/dir.c:877
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_entry_unlinked
Direct callers:
  - fs/fuse/xattr.c:fuse_removexattr
  - fs/fuse/xattr.c:fuse_setxattr
```
**Symbols:**

```
ffffffff81620de0-ffffffff81620e5b: fuse_update_ctime (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void fuse_update_ctime(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff81658fc7)
Location: fs/fuse/dir.c:943
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_entry_unlinked
Direct callers:
  - fs/fuse/xattr.c:fuse_removexattr
  - fs/fuse/xattr.c:fuse_setxattr
```
**Symbols:**

```
ffffffff81659230-ffffffff816592ab: fuse_update_ctime (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void fuse_update_ctime(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff81692d14)
Location: fs/fuse/dir.c:940
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_entry_unlinked
Direct callers:
  - fs/fuse/xattr.c:fuse_removexattr
  - fs/fuse/xattr.c:fuse_setxattr
```
**Symbols:**

```
ffffffff81692f80-ffffffff81692ff0: fuse_update_ctime (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void fuse_update_ctime(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fuse/dir.c (ffff800010508178)
Location: fs/fuse/dir.c:693
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_unlink
Direct callers:
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/xattr.c:fuse_removexattr
  - fs/fuse/xattr.c:fuse_setxattr
```
**Symbols:**

```
ffff8000105066f8-ffff800010506734: fuse_update_ctime.part.0 (STB_LOCAL)
ffff800010508940-ffff800010508980: fuse_update_ctime (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
void fuse_update_ctime(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fuse/dir.c (c06c41b0)
Location: fs/fuse/dir.c:693
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_unlink
Direct callers:
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/xattr.c:fuse_removexattr
  - fs/fuse/xattr.c:fuse_setxattr
```
**Symbols:**

```
c06c2770-c06c27ec: fuse_update_ctime.part.0 (STB_LOCAL)
c06c48d8-c06c4900: fuse_update_ctime (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
void fuse_update_ctime(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fuse/dir.c (c00000000064da00)
Location: fs/fuse/dir.c:693
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_unlink
Direct callers:
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/xattr.c:fuse_removexattr
  - fs/fuse/xattr.c:fuse_setxattr
```
**Symbols:**

```
c00000000064be30-c00000000064be88: fuse_update_ctime.part.0 (STB_LOCAL)
c00000000064e370-c00000000064e390: fuse_update_ctime (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void fuse_update_ctime(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fuse/dir.c (ffffffe000373eea)
Location: fs/fuse/dir.c:693
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_unlink
Direct callers:
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_unlink
```
**Symbols:**

```
ffffffe000372bb6-ffffffe000372bf0: fuse_update_ctime.part.0 (STB_LOCAL)
ffffffe000374518-ffffffe000374554: fuse_update_ctime (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
void fuse_update_ctime(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fuse/dir.c (ffffffff8141d08f)
Location: fs/fuse/dir.c:693
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_unlink
Direct callers:
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/xattr.c:fuse_removexattr
  - fs/fuse/xattr.c:fuse_setxattr
```
**Symbols:**

```
ffffffff8141bb10-ffffffff8141bb41: fuse_update_ctime.part.0 (STB_LOCAL)
ffffffff8141d830-ffffffff8141d847: fuse_update_ctime (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
void fuse_update_ctime(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fuse/dir.c (ffffffff8140db0f)
Location: fs/fuse/dir.c:693
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_unlink
Direct callers:
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/xattr.c:fuse_removexattr
  - fs/fuse/xattr.c:fuse_setxattr
```
**Symbols:**

```
ffffffff8140c590-ffffffff8140c5c1: fuse_update_ctime.part.0 (STB_LOCAL)
ffffffff8140e2b0-ffffffff8140e2c7: fuse_update_ctime (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void fuse_update_ctime(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fuse/dir.c (ffffffff8141922f)
Location: fs/fuse/dir.c:693
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_unlink
Direct callers:
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/xattr.c:fuse_removexattr
  - fs/fuse/xattr.c:fuse_setxattr
```
**Symbols:**

```
ffffffff81417cb0-ffffffff81417ce1: fuse_update_ctime.part.0 (STB_LOCAL)
ffffffff814199d0-ffffffff814199e7: fuse_update_ctime (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void fuse_update_ctime(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fuse/dir.c (ffffffff8142ff9d)
Location: fs/fuse/dir.c:693
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_unlink
Direct callers:
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/xattr.c:fuse_removexattr
  - fs/fuse/xattr.c:fuse_setxattr
```
**Symbols:**

```
ffffffff8142ebb0-ffffffff8142ebe1: fuse_update_ctime.part.0 (STB_LOCAL)
ffffffff81430740-ffffffff81430757: fuse_update_ctime (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
