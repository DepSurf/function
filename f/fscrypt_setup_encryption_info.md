# Function: <code>fscrypt_setup_encryption_info</code>

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
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int fscrypt_setup_encryption_info(struct inode *inode, const union fscrypt_policy *policy, const u8 *nonce, bool need_dirhash_key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup.c (ffffffff813a4fe0)
Location: fs/crypto/keysetup.c:477
Inline: False
Direct callers:
  - fs/crypto/keysetup.c:fscrypt_prepare_new_inode
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
```
**Symbols:**

```
ffffffff813a4fe0-ffffffff813a52c4: fscrypt_setup_encryption_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int fscrypt_setup_encryption_info(struct inode *inode, const union fscrypt_policy *policy, const u8 *nonce, bool need_dirhash_key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup.c (ffffffff813ac0d0)
Location: fs/crypto/keysetup.c:501
Inline: False
Direct callers:
  - fs/crypto/keysetup.c:fscrypt_prepare_new_inode
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
```
**Symbols:**

```
ffffffff813ac0d0-ffffffff813ac3ac: fscrypt_setup_encryption_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int fscrypt_setup_encryption_info(struct inode *inode, const union fscrypt_policy *policy, const u8 *nonce, bool need_dirhash_key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/keysetup.c (0)
Location: fs/crypto/keysetup.c:534
Inline: False
Direct callers:
  - fs/crypto/keysetup.c:fscrypt_prepare_new_inode
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
```
**Symbols:**

```
ffffffff813fb9f0-ffffffff813fbd17: fscrypt_setup_encryption_info (STB_LOCAL)
ffffffff81cc66dc-ffffffff81cc66f0: fscrypt_setup_encryption_info.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int fscrypt_setup_encryption_info(struct inode *inode, const union fscrypt_policy *policy, const u8 *nonce, bool need_dirhash_key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/keysetup.c (0)
Location: fs/crypto/keysetup.c:521
Inline: False
Direct callers:
  - fs/crypto/keysetup.c:fscrypt_prepare_new_inode
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
```
**Symbols:**

```
ffffffff8146eda0-ffffffff8146f0bf: fscrypt_setup_encryption_info (STB_LOCAL)
ffffffff81e78b3a-ffffffff81e78b4e: fscrypt_setup_encryption_info.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int fscrypt_setup_encryption_info(struct inode *inode, const union fscrypt_policy *policy, const u8 *nonce, bool need_dirhash_key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/keysetup.c (0)
Location: fs/crypto/keysetup.c:534
Inline: False
Direct callers:
  - fs/crypto/keysetup.c:fscrypt_prepare_new_inode
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
```
**Symbols:**

```
ffffffff81500350-ffffffff81500792: fscrypt_setup_encryption_info (STB_LOCAL)
ffffffff8206a6e8-ffffffff8206a6fc: fscrypt_setup_encryption_info.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int fscrypt_setup_encryption_info(struct inode *inode, const union fscrypt_policy *policy, const u8 *nonce, bool need_dirhash_key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/keysetup.c (0)
Location: fs/crypto/keysetup.c:553
Inline: False
Direct callers:
  - fs/crypto/keysetup.c:fscrypt_prepare_new_inode
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
```
**Symbols:**

```
ffffffff81537b70-ffffffff81537e2a: fscrypt_setup_encryption_info (STB_LOCAL)
ffffffff820ea4f6-ffffffff820ea50a: fscrypt_setup_encryption_info.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int fscrypt_setup_encryption_info(struct inode *inode, const union fscrypt_policy *policy, const u8 *nonce, bool need_dirhash_key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/keysetup.c (0)
Location: fs/crypto/keysetup.c:555
Inline: False
Direct callers:
  - fs/crypto/keysetup.c:fscrypt_prepare_new_inode
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
```
**Symbols:**

```
ffffffff8156cc80-ffffffff8156cf7b: fscrypt_setup_encryption_info (STB_LOCAL)
ffffffff821c7074-ffffffff821c7088: fscrypt_setup_encryption_info.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
