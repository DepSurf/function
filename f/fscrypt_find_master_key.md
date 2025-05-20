# Function: <code>fscrypt_find_master_key</code>

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
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct key *fscrypt_find_master_key(struct super_block *sb, const struct fscrypt_key_specifier *mk_spec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (ffffffff8134c530)
Location: fs/crypto/keyring.c:227
Inline: False
Direct callers:
  - fs/crypto/keyring.c:fscrypt_ioctl_get_key_status
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:fscrypt_verify_key_added
  - fs/crypto/keyring.c:add_master_key
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
```
**Symbols:**

```
ffffffff8134c530-ffffffff8134c599: fscrypt_find_master_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct key *fscrypt_find_master_key(struct super_block *sb, const struct fscrypt_key_specifier *mk_spec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (ffffffff81392460)
Location: fs/crypto/keyring.c:231
Inline: False
Direct callers:
  - fs/crypto/keyring.c:fscrypt_ioctl_get_key_status
  - fs/crypto/keyring.c:fscrypt_verify_key_added
  - fs/crypto/keyring.c:do_add_master_key
  - fs/crypto/keysetup.c:setup_file_encryption_key
```
**Symbols:**

```
ffffffff81392460-ffffffff81392508: fscrypt_find_master_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct key *fscrypt_find_master_key(struct super_block *sb, const struct fscrypt_key_specifier *mk_spec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (ffffffff813a37e0)
Location: fs/crypto/keyring.c:235
Inline: False
Direct callers:
  - fs/crypto/keyring.c:fscrypt_ioctl_get_key_status
  - fs/crypto/keyring.c:fscrypt_verify_key_added
  - fs/crypto/keyring.c:do_add_master_key
  - fs/crypto/keysetup.c:setup_file_encryption_key
```
**Symbols:**

```
ffffffff813a37e0-ffffffff813a3888: fscrypt_find_master_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct key *fscrypt_find_master_key(struct super_block *sb, const struct fscrypt_key_specifier *mk_spec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (ffffffff813aaa20)
Location: fs/crypto/keyring.c:235
Inline: False
Direct callers:
  - fs/crypto/keyring.c:fscrypt_ioctl_get_key_status
  - fs/crypto/keyring.c:fscrypt_verify_key_added
  - fs/crypto/keyring.c:do_add_master_key
  - fs/crypto/keysetup.c:setup_file_encryption_key
```
**Symbols:**

```
ffffffff813aaa20-ffffffff813aaac8: fscrypt_find_master_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct key *fscrypt_find_master_key(struct super_block *sb, const struct fscrypt_key_specifier *mk_spec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (ffffffff813fa2b0)
Location: fs/crypto/keyring.c:235
Inline: False
Direct callers:
  - fs/crypto/keyring.c:fscrypt_ioctl_get_key_status
  - fs/crypto/keyring.c:fscrypt_verify_key_added
  - fs/crypto/keyring.c:do_add_master_key
  - fs/crypto/keysetup.c:setup_file_encryption_key
```
**Symbols:**

```
ffffffff813fa2b0-ffffffff813fa358: fscrypt_find_master_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct key *fscrypt_find_master_key(struct super_block *sb, const struct fscrypt_key_specifier *mk_spec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (ffffffff8146d450)
Location: fs/crypto/keyring.c:235
Inline: False
Direct callers:
  - fs/crypto/keyring.c:fscrypt_ioctl_get_key_status
  - fs/crypto/keyring.c:fscrypt_verify_key_added
  - fs/crypto/keyring.c:do_add_master_key
  - fs/crypto/keysetup.c:setup_file_encryption_key
```
**Symbols:**

```
ffffffff8146d450-ffffffff8146d528: fscrypt_find_master_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct fscrypt_master_key *fscrypt_find_master_key(struct super_block *sb, const struct fscrypt_key_specifier *mk_spec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (ffffffff814febd0)
Location: fs/crypto/keyring.c:274
Inline: False
Direct callers:
  - fs/crypto/keyring.c:fscrypt_ioctl_get_key_status
  - fs/crypto/keyring.c:fscrypt_verify_key_added
  - fs/crypto/keyring.c:add_master_key
  - fs/crypto/keysetup.c:fscrypt_setup_encryption_info
```
**Symbols:**

```
ffffffff814febd0-ffffffff814fecde: fscrypt_find_master_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct fscrypt_master_key *fscrypt_find_master_key(struct super_block *sb, const struct fscrypt_key_specifier *mk_spec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (ffffffff815361e0)
Location: fs/crypto/keyring.c:277
Inline: False
Direct callers:
  - fs/crypto/keyring.c:fscrypt_ioctl_get_key_status
  - fs/crypto/keyring.c:fscrypt_verify_key_added
  - fs/crypto/keyring.c:add_master_key
  - fs/crypto/keysetup.c:setup_file_encryption_key
  - fs/crypto/keysetup.c:setup_file_encryption_key
```
**Symbols:**

```
ffffffff815361e0-ffffffff815362e6: fscrypt_find_master_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct fscrypt_master_key *fscrypt_find_master_key(struct super_block *sb, const struct fscrypt_key_specifier *mk_spec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (ffffffff8156b200)
Location: fs/crypto/keyring.c:284
Inline: False
Direct callers:
  - fs/crypto/keyring.c:fscrypt_ioctl_get_key_status
  - fs/crypto/keyring.c:fscrypt_verify_key_added
  - fs/crypto/keyring.c:add_master_key
  - fs/crypto/keysetup.c:setup_file_encryption_key
  - fs/crypto/keysetup.c:setup_file_encryption_key
```
**Symbols:**

```
ffffffff8156b200-ffffffff8156b306: fscrypt_find_master_key (STB_GLOBAL)
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
struct key *fscrypt_find_master_key(struct super_block *sb, const struct fscrypt_key_specifier *mk_spec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (ffff80001040d3b8)
Location: fs/crypto/keyring.c:227
Inline: False
Direct callers:
  - fs/crypto/keyring.c:fscrypt_ioctl_get_key_status
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:fscrypt_verify_key_added
  - fs/crypto/keyring.c:add_master_key
  - fs/crypto/keyring.c:add_master_key
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
```
**Symbols:**

```
ffff80001040d3b8-ffff80001040d440: fscrypt_find_master_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct key *fscrypt_find_master_key(struct super_block *sb, const struct fscrypt_key_specifier *mk_spec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (c05da060)
Location: fs/crypto/keyring.c:227
Inline: False
Direct callers:
  - fs/crypto/keyring.c:fscrypt_ioctl_get_key_status
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:fscrypt_verify_key_added
  - fs/crypto/keyring.c:add_master_key
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
```
**Symbols:**

```
c05da060-c05da0dc: fscrypt_find_master_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct key *fscrypt_find_master_key(struct super_block *sb, const struct fscrypt_key_specifier *mk_spec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (c00000000051a4f0)
Location: fs/crypto/keyring.c:227
Inline: False
Direct callers:
  - fs/crypto/keyring.c:fscrypt_ioctl_get_key_status
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:fscrypt_verify_key_added
  - fs/crypto/keyring.c:add_master_key
  - fs/crypto/keyring.c:add_master_key
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
```
**Symbols:**

```
c00000000051a4f0-c00000000051a588: fscrypt_find_master_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct key *fscrypt_find_master_key(struct super_block *sb, const struct fscrypt_key_specifier *mk_spec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (ffffffe0002b677a)
Location: fs/crypto/keyring.c:227
Inline: False
Direct callers:
  - fs/crypto/keyring.c:fscrypt_ioctl_get_key_status
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:fscrypt_verify_key_added
  - fs/crypto/keyring.c:add_master_key
  - fs/crypto/keyring.c:add_master_key
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
```
**Symbols:**

```
ffffffe0002b677a-ffffffe0002b67cc: fscrypt_find_master_key (STB_GLOBAL)
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
struct key *fscrypt_find_master_key(struct super_block *sb, const struct fscrypt_key_specifier *mk_spec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (ffffffff81344b10)
Location: fs/crypto/keyring.c:227
Inline: False
Direct callers:
  - fs/crypto/keyring.c:fscrypt_ioctl_get_key_status
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:fscrypt_verify_key_added
  - fs/crypto/keyring.c:add_master_key
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
```
**Symbols:**

```
ffffffff81344b10-ffffffff81344b79: fscrypt_find_master_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct key *fscrypt_find_master_key(struct super_block *sb, const struct fscrypt_key_specifier *mk_spec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (ffffffff813357f0)
Location: fs/crypto/keyring.c:227
Inline: False
Direct callers:
  - fs/crypto/keyring.c:fscrypt_ioctl_get_key_status
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:fscrypt_verify_key_added
  - fs/crypto/keyring.c:add_master_key
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
```
**Symbols:**

```
ffffffff813357f0-ffffffff81335859: fscrypt_find_master_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct key *fscrypt_find_master_key(struct super_block *sb, const struct fscrypt_key_specifier *mk_spec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (ffffffff813425e0)
Location: fs/crypto/keyring.c:227
Inline: False
Direct callers:
  - fs/crypto/keyring.c:fscrypt_ioctl_get_key_status
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:fscrypt_verify_key_added
  - fs/crypto/keyring.c:add_master_key
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
```
**Symbols:**

```
ffffffff813425e0-ffffffff81342649: fscrypt_find_master_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct key *fscrypt_find_master_key(struct super_block *sb, const struct fscrypt_key_specifier *mk_spec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (ffffffff813558e0)
Location: fs/crypto/keyring.c:227
Inline: False
Direct callers:
  - fs/crypto/keyring.c:fscrypt_ioctl_get_key_status
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:fscrypt_verify_key_added
  - fs/crypto/keyring.c:add_master_key
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
```
**Symbols:**

```
ffffffff813558e0-ffffffff81355949: fscrypt_find_master_key (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>struct key *</code> ➡️ <code>struct fscrypt_master_key *</code>
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
