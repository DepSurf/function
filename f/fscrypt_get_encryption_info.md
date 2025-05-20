# Function: <code>fscrypt_get_encryption_info</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int fscrypt_get_encryption_info(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keyinfo.c (ffffffff8128a8b0)
Location: fs/crypto/keyinfo.c:292
Inline: False
Direct callers:
  - fs/crypto/policy.c:fscrypt_inherit_context
  - fs/crypto/policy.c:fscrypt_inherit_context
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/file.c:ext4_file_open
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:htree_dirblock_to_tree
  - fs/ext4/symlink.c:ext4_encrypted_get_link
```
**Symbols:**

```
ffffffff8128a8b0-ffffffff8128a8e0: fscrypt_get_encryption_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int fscrypt_get_encryption_info(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/keyinfo.c (ffffffff8129f170)
Location: fs/crypto/keyinfo.c:173
Inline: True
Direct callers:
  - fs/crypto/fname.c:fscrypt_setup_filename
  - fs/crypto/policy.c:fscrypt_inherit_context
  - fs/crypto/policy.c:fscrypt_inherit_context
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/file.c:ext4_file_open
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:htree_dirblock_to_tree
  - fs/ext4/symlink.c:ext4_encrypted_get_link
```
**Symbols:**

```
ffffffff8129f170-ffffffff8129f5b3: fscrypt_get_encryption_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int fscrypt_get_encryption_info(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/keyinfo.c (ffffffff812adbb0)
Location: fs/crypto/keyinfo.c:251
Inline: True
Direct callers:
  - fs/crypto/fname.c:fscrypt_setup_filename
  - fs/crypto/policy.c:fscrypt_has_permitted_context
  - fs/crypto/policy.c:fscrypt_has_permitted_context
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/file.c:ext4_file_open
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:htree_dirblock_to_tree
  - fs/ext4/symlink.c:ext4_encrypted_get_link
```
**Symbols:**

```
ffffffff812adbb0-ffffffff812ae104: fscrypt_get_encryption_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int fscrypt_get_encryption_info(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/keyinfo.c (ffffffff812d1080)
Location: fs/crypto/keyinfo.c:242
Inline: True
Direct callers:
  - fs/crypto/fname.c:fscrypt_setup_filename
  - fs/crypto/hooks.c:__fscrypt_prepare_link
  - fs/crypto/hooks.c:fscrypt_file_open
  - fs/crypto/policy.c:fscrypt_has_permitted_context
  - fs/crypto/policy.c:fscrypt_has_permitted_context
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:htree_dirblock_to_tree
  - fs/ext4/symlink.c:ext4_encrypted_get_link
```
**Symbols:**

```
ffffffff812d1080-ffffffff812d15e4: fscrypt_get_encryption_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
int fscrypt_get_encryption_info(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/crypto/keyinfo.c (ffffffff812fbfa0)
Location: fs/crypto/keyinfo.c:288
Inline: True
Direct callers:
  - fs/crypto/fname.c:fscrypt_setup_filename
  - fs/crypto/hooks.c:__fscrypt_encrypt_symlink
  - fs/crypto/hooks.c:__fscrypt_prepare_link
  - fs/crypto/hooks.c:fscrypt_file_open
  - fs/crypto/policy.c:fscrypt_inherit_context
  - fs/crypto/policy.c:fscrypt_inherit_context
  - fs/crypto/policy.c:fscrypt_has_permitted_context
  - fs/crypto/policy.c:fscrypt_has_permitted_context
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/namei.c:htree_dirblock_to_tree
```
**Symbols:**

```
ffffffff812fba70-ffffffff812fbf9d: fscrypt_get_encryption_info.part.7 (STB_LOCAL)
ffffffff812fc020-ffffffff812fc0d7: fscrypt_get_encryption_info.part.7.cold.10 (STB_LOCAL)
ffffffff812fbfa0-ffffffff812fbfdb: fscrypt_get_encryption_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
int fscrypt_get_encryption_info(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/crypto/keyinfo.c (ffffffff813117c0)
Location: fs/crypto/keyinfo.c:504
Inline: True
Direct callers:
  - fs/crypto/fname.c:fscrypt_setup_filename
  - fs/crypto/hooks.c:__fscrypt_encrypt_symlink
  - fs/crypto/hooks.c:__fscrypt_prepare_link
  - fs/crypto/hooks.c:fscrypt_file_open
  - fs/crypto/policy.c:fscrypt_inherit_context
  - fs/crypto/policy.c:fscrypt_inherit_context
  - fs/crypto/policy.c:fscrypt_has_permitted_context
  - fs/crypto/policy.c:fscrypt_has_permitted_context
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/namei.c:htree_dirblock_to_tree
```
**Symbols:**

```
ffffffff81311200-ffffffff813117bd: fscrypt_get_encryption_info.part.11 (STB_LOCAL)
ffffffff813118ab-ffffffff8131194a: fscrypt_get_encryption_info.part.11.cold.18 (STB_LOCAL)
ffffffff813117c0-ffffffff813117fb: fscrypt_get_encryption_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int fscrypt_get_encryption_info(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/crypto/keyinfo.c (ffffffff81338cb0)
Location: fs/crypto/keyinfo.c:502
Inline: True
Direct callers:
  - fs/crypto/fname.c:fscrypt_setup_filename
  - fs/crypto/hooks.c:fscrypt_get_symlink
  - fs/crypto/hooks.c:__fscrypt_encrypt_symlink
  - fs/crypto/hooks.c:__fscrypt_prepare_link
  - fs/crypto/hooks.c:fscrypt_file_open
  - fs/crypto/policy.c:fscrypt_inherit_context
  - fs/crypto/policy.c:fscrypt_inherit_context
  - fs/crypto/policy.c:fscrypt_has_permitted_context
  - fs/crypto/policy.c:fscrypt_has_permitted_context
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/namei.c:htree_dirblock_to_tree
```
**Symbols:**

```
ffffffff81338720-ffffffff81338cac: fscrypt_get_encryption_info.part.0 (STB_LOCAL)
ffffffff81338d9e-ffffffff81338eae: fscrypt_get_encryption_info.part.0.cold (STB_LOCAL)
ffffffff81338cb0-ffffffff81338cef: fscrypt_get_encryption_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int fscrypt_get_encryption_info(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/keysetup.c (0)
Location: fs/crypto/keysetup.c:421
Inline: False
Direct callers:
  - fs/crypto/fname.c:fscrypt_setup_filename
  - fs/crypto/hooks.c:fscrypt_get_symlink
  - fs/crypto/hooks.c:__fscrypt_encrypt_symlink
  - fs/crypto/hooks.c:__fscrypt_prepare_link
  - fs/crypto/hooks.c:fscrypt_file_open
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/namei.c:htree_dirblock_to_tree
```
**Symbols:**

```
ffffffff8134e08f-ffffffff8134e15a: fscrypt_get_encryption_info.cold (STB_LOCAL)
ffffffff8134dac0-ffffffff8134df99: fscrypt_get_encryption_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int fscrypt_get_encryption_info(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/keysetup.c (0)
Location: fs/crypto/keysetup.c:430
Inline: False
Direct callers:
  - fs/crypto/fname.c:fscrypt_setup_filename
  - fs/crypto/hooks.c:fscrypt_get_symlink
  - fs/crypto/hooks.c:__fscrypt_encrypt_symlink
  - fs/crypto/hooks.c:fscrypt_prepare_setflags
  - fs/crypto/policy.c:fscrypt_inherit_context
  - fs/crypto/policy.c:fscrypt_inherit_context
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/namei.c:htree_dirblock_to_tree
```
**Symbols:**

```
ffffffff81393fd6-ffffffff81394012: fscrypt_get_encryption_info.cold (STB_LOCAL)
ffffffff81393a40-ffffffff81393e6e: fscrypt_get_encryption_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int fscrypt_get_encryption_info(struct inode *inode, bool allow_unsupported);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/keysetup.c (0)
Location: fs/crypto/keysetup.c:564
Inline: False
Direct callers:
  - fs/crypto/fname.c:fscrypt_setup_filename
  - fs/crypto/hooks.c:fscrypt_get_symlink
  - fs/crypto/hooks.c:fscrypt_prepare_setflags
  - fs/crypto/hooks.c:__fscrypt_prepare_readdir
  - fs/crypto/policy.c:fscrypt_policy_to_inherit
```
**Symbols:**

```
ffffffff81beafbe-ffffffff81beaff7: fscrypt_get_encryption_info.cold (STB_LOCAL)
ffffffff813a53b0-ffffffff813a54f2: fscrypt_get_encryption_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int fscrypt_get_encryption_info(struct inode *inode, bool allow_unsupported);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/keysetup.c (0)
Location: fs/crypto/keysetup.c:588
Inline: False
Direct callers:
  - fs/crypto/fname.c:fscrypt_setup_filename
  - fs/crypto/hooks.c:fscrypt_get_symlink
  - fs/crypto/hooks.c:fscrypt_prepare_setflags
  - fs/crypto/hooks.c:__fscrypt_prepare_readdir
  - fs/crypto/policy.c:fscrypt_policy_to_inherit
```
**Symbols:**

```
ffffffff81bdd017-ffffffff81bdd050: fscrypt_get_encryption_info.cold (STB_LOCAL)
ffffffff813ac490-ffffffff813ac5d2: fscrypt_get_encryption_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int fscrypt_get_encryption_info(struct inode *inode, bool allow_unsupported);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/keysetup.c (0)
Location: fs/crypto/keysetup.c:621
Inline: False
Direct callers:
  - fs/crypto/fname.c:fscrypt_setup_filename
  - fs/crypto/hooks.c:fscrypt_get_symlink
  - fs/crypto/hooks.c:fscrypt_prepare_setflags
  - fs/crypto/hooks.c:__fscrypt_prepare_readdir
  - fs/crypto/policy.c:fscrypt_policy_to_inherit
```
**Symbols:**

```
ffffffff81cc66f0-ffffffff81cc6729: fscrypt_get_encryption_info.cold (STB_LOCAL)
ffffffff813fbe00-ffffffff813fbf42: fscrypt_get_encryption_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int fscrypt_get_encryption_info(struct inode *inode, bool allow_unsupported);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/keysetup.c (0)
Location: fs/crypto/keysetup.c:608
Inline: False
Direct callers:
  - fs/crypto/fname.c:fscrypt_setup_filename
  - fs/crypto/hooks.c:fscrypt_get_symlink
  - fs/crypto/hooks.c:fscrypt_prepare_setflags
  - fs/crypto/hooks.c:__fscrypt_prepare_readdir
  - fs/crypto/policy.c:fscrypt_policy_to_inherit
  - fs/crypto/policy.c:fscrypt_has_permitted_context
  - fs/crypto/policy.c:fscrypt_has_permitted_context
```
**Symbols:**

```
ffffffff81e78b4e-ffffffff81e78b86: fscrypt_get_encryption_info.cold (STB_LOCAL)
ffffffff8146f1c0-ffffffff8146f349: fscrypt_get_encryption_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int fscrypt_get_encryption_info(struct inode *inode, bool allow_unsupported);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup.c (ffffffff815008c0)
Location: fs/crypto/keysetup.c:617
Inline: False
Direct callers:
  - fs/crypto/fname.c:fscrypt_setup_filename
  - fs/crypto/hooks.c:fscrypt_get_symlink
  - fs/crypto/hooks.c:fscrypt_prepare_setflags
  - fs/crypto/hooks.c:__fscrypt_prepare_readdir
  - fs/crypto/policy.c:fscrypt_policy_to_inherit
  - fs/crypto/policy.c:fscrypt_has_permitted_context
  - fs/crypto/policy.c:fscrypt_has_permitted_context
```
**Symbols:**

```
ffffffff815008c0-ffffffff81500a78: fscrypt_get_encryption_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int fscrypt_get_encryption_info(struct inode *inode, bool allow_unsupported);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup.c (ffffffff81537f50)
Location: fs/crypto/keysetup.c:636
Inline: False
Direct callers:
  - fs/crypto/fname.c:fscrypt_setup_filename
  - fs/crypto/hooks.c:fscrypt_get_symlink
  - fs/crypto/hooks.c:fscrypt_prepare_setflags
  - fs/crypto/hooks.c:__fscrypt_prepare_readdir
  - fs/crypto/policy.c:fscrypt_policy_to_inherit
  - fs/crypto/policy.c:fscrypt_has_permitted_context
  - fs/crypto/policy.c:fscrypt_has_permitted_context
```
**Symbols:**

```
ffffffff81537f50-ffffffff81538108: fscrypt_get_encryption_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int fscrypt_get_encryption_info(struct inode *inode, bool allow_unsupported);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup.c (ffffffff8156d0a0)
Location: fs/crypto/keysetup.c:643
Inline: False
Direct callers:
  - fs/crypto/fname.c:fscrypt_setup_filename
  - fs/crypto/hooks.c:fscrypt_get_symlink
  - fs/crypto/hooks.c:fscrypt_prepare_setflags
  - fs/crypto/hooks.c:__fscrypt_prepare_readdir
  - fs/crypto/policy.c:fscrypt_policy_to_inherit
  - fs/crypto/policy.c:fscrypt_has_permitted_context
  - fs/crypto/policy.c:fscrypt_has_permitted_context
```
**Symbols:**

```
ffffffff8156d0a0-ffffffff8156d258: fscrypt_get_encryption_info (STB_GLOBAL)
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
int fscrypt_get_encryption_info(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup.c (ffff80001040ede0)
Location: fs/crypto/keysetup.c:421
Inline: False
Direct callers:
  - fs/crypto/fname.c:fscrypt_setup_filename
  - fs/crypto/hooks.c:fscrypt_get_symlink
  - fs/crypto/hooks.c:__fscrypt_encrypt_symlink
  - fs/crypto/hooks.c:__fscrypt_prepare_link
  - fs/crypto/hooks.c:fscrypt_file_open
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/namei.c:htree_dirblock_to_tree
```
**Symbols:**

```
ffff80001040ede0-ffff80001040f370: fscrypt_get_encryption_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int fscrypt_get_encryption_info(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup.c (c05db8fc)
Location: fs/crypto/keysetup.c:421
Inline: False
Direct callers:
  - fs/crypto/hooks.c:fscrypt_get_symlink
  - fs/crypto/hooks.c:__fscrypt_encrypt_symlink
  - fs/crypto/hooks.c:__fscrypt_prepare_link
  - fs/crypto/hooks.c:fscrypt_file_open
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/namei.c:htree_dirblock_to_tree
```
**Symbols:**

```
c05db8fc-c05dbecc: fscrypt_get_encryption_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int fscrypt_get_encryption_info(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup.c (c00000000051c4b0)
Location: fs/crypto/keysetup.c:421
Inline: False
Direct callers:
  - fs/crypto/fname.c:fscrypt_setup_filename
  - fs/crypto/hooks.c:fscrypt_get_symlink
  - fs/crypto/hooks.c:__fscrypt_encrypt_symlink
  - fs/crypto/hooks.c:__fscrypt_prepare_link
  - fs/crypto/hooks.c:fscrypt_file_open
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/namei.c:htree_dirblock_to_tree
```
**Symbols:**

```
c00000000051c4b0-c00000000051cbd4: fscrypt_get_encryption_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int fscrypt_get_encryption_info(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup.c (ffffffe0002b7baa)
Location: fs/crypto/keysetup.c:421
Inline: False
Direct callers:
  - fs/crypto/hooks.c:fscrypt_get_symlink
  - fs/crypto/hooks.c:__fscrypt_encrypt_symlink
  - fs/crypto/hooks.c:__fscrypt_prepare_link
  - fs/crypto/hooks.c:fscrypt_file_open
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/namei.c:htree_dirblock_to_tree
```
**Symbols:**

```
ffffffe0002b7baa-ffffffe0002b801a: fscrypt_get_encryption_info (STB_GLOBAL)
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
int fscrypt_get_encryption_info(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/keysetup.c (0)
Location: fs/crypto/keysetup.c:421
Inline: False
Direct callers:
  - fs/crypto/fname.c:fscrypt_setup_filename
  - fs/crypto/hooks.c:fscrypt_get_symlink
  - fs/crypto/hooks.c:__fscrypt_encrypt_symlink
  - fs/crypto/hooks.c:__fscrypt_prepare_link
  - fs/crypto/hooks.c:fscrypt_file_open
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/namei.c:htree_dirblock_to_tree
```
**Symbols:**

```
ffffffff8134666f-ffffffff8134673a: fscrypt_get_encryption_info.cold (STB_LOCAL)
ffffffff813460a0-ffffffff81346579: fscrypt_get_encryption_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int fscrypt_get_encryption_info(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/keysetup.c (0)
Location: fs/crypto/keysetup.c:421
Inline: False
Direct callers:
  - fs/crypto/fname.c:fscrypt_setup_filename
  - fs/crypto/hooks.c:fscrypt_get_symlink
  - fs/crypto/hooks.c:__fscrypt_encrypt_symlink
  - fs/crypto/hooks.c:__fscrypt_prepare_link
  - fs/crypto/hooks.c:fscrypt_file_open
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/namei.c:htree_dirblock_to_tree
```
**Symbols:**

```
ffffffff8133734f-ffffffff8133741a: fscrypt_get_encryption_info.cold (STB_LOCAL)
ffffffff81336d80-ffffffff81337259: fscrypt_get_encryption_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int fscrypt_get_encryption_info(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/keysetup.c (0)
Location: fs/crypto/keysetup.c:421
Inline: False
Direct callers:
  - fs/crypto/fname.c:fscrypt_setup_filename
  - fs/crypto/hooks.c:fscrypt_get_symlink
  - fs/crypto/hooks.c:__fscrypt_encrypt_symlink
  - fs/crypto/hooks.c:__fscrypt_prepare_link
  - fs/crypto/hooks.c:fscrypt_file_open
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/namei.c:htree_dirblock_to_tree
```
**Symbols:**

```
ffffffff8134413f-ffffffff8134420a: fscrypt_get_encryption_info.cold (STB_LOCAL)
ffffffff81343b70-ffffffff81344049: fscrypt_get_encryption_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int fscrypt_get_encryption_info(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/keysetup.c (0)
Location: fs/crypto/keysetup.c:421
Inline: False
Direct callers:
  - fs/crypto/fname.c:fscrypt_setup_filename
  - fs/crypto/hooks.c:fscrypt_get_symlink
  - fs/crypto/hooks.c:__fscrypt_encrypt_symlink
  - fs/crypto/hooks.c:__fscrypt_prepare_link
  - fs/crypto/hooks.c:fscrypt_file_open
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/namei.c:htree_dirblock_to_tree
```
**Symbols:**

```
ffffffff8135741d-ffffffff813574e8: fscrypt_get_encryption_info.cold (STB_LOCAL)
ffffffff81356e50-ffffffff81357327: fscrypt_get_encryption_info (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool allow_unsupported</code>
</li>
</ul>
</details>
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
