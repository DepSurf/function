# Function: <code>setup_file_encryption_key</code>

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
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup.c (ffffffff8134dcf6)
Location: fs/crypto/keysetup.c:294
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int setup_file_encryption_key(struct fscrypt_info *ci, struct key **master_key_ret);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/keysetup.c (0)
Location: fs/crypto/keysetup.c:305
Inline: False
Direct callers:
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
```
**Symbols:**

```
ffffffff813938b0-ffffffff81393a32: setup_file_encryption_key (STB_LOCAL)
ffffffff81393f73-ffffffff81393fd6: setup_file_encryption_key.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int setup_file_encryption_key(struct fscrypt_info *ci, bool need_dirhash_key, struct key **master_key_ret);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/keysetup.c (0)
Location: fs/crypto/keysetup.c:346
Inline: False
Direct callers:
  - fs/crypto/keysetup.c:fscrypt_setup_encryption_info
```
**Symbols:**

```
ffffffff813a4e30-ffffffff813a4fd3: setup_file_encryption_key (STB_LOCAL)
ffffffff81beaf5e-ffffffff81beafbe: setup_file_encryption_key.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int setup_file_encryption_key(struct fscrypt_info *ci, bool need_dirhash_key, struct key **master_key_ret);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/keysetup.c (0)
Location: fs/crypto/keysetup.c:370
Inline: False
Direct callers:
  - fs/crypto/keysetup.c:fscrypt_setup_encryption_info
```
**Symbols:**

```
ffffffff813abf20-ffffffff813ac0c3: setup_file_encryption_key (STB_LOCAL)
ffffffff81bdcfb7-ffffffff81bdd017: setup_file_encryption_key.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int setup_file_encryption_key(struct fscrypt_info *ci, bool need_dirhash_key, struct key **master_key_ret);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/keysetup.c (0)
Location: fs/crypto/keysetup.c:414
Inline: False
Direct callers:
  - fs/crypto/keysetup.c:fscrypt_setup_encryption_info
```
**Symbols:**

```
ffffffff813fb810-ffffffff813fb9e3: setup_file_encryption_key (STB_LOCAL)
ffffffff81cc6671-ffffffff81cc66dc: setup_file_encryption_key.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int setup_file_encryption_key(struct fscrypt_info *ci, bool need_dirhash_key, struct key **master_key_ret);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/keysetup.c (0)
Location: fs/crypto/keysetup.c:415
Inline: False
Direct callers:
  - fs/crypto/keysetup.c:fscrypt_setup_encryption_info
```
**Symbols:**

```
ffffffff8146ec00-ffffffff8146ed9b: setup_file_encryption_key (STB_LOCAL)
ffffffff81e78ada-ffffffff81e78b3a: setup_file_encryption_key.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup.c (ffffffff815004a8)
Location: fs/crypto/keysetup.c:437
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_setup_encryption_info
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int setup_file_encryption_key(struct fscrypt_info *ci, bool need_dirhash_key, struct fscrypt_master_key **mk_ret);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup.c (ffffffff81537920)
Location: fs/crypto/keysetup.c:437
Inline: False
Direct callers:
  - fs/crypto/keysetup.c:fscrypt_setup_encryption_info
```
**Symbols:**

```
ffffffff81537920-ffffffff81537b5c: setup_file_encryption_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int setup_file_encryption_key(struct fscrypt_inode_info *ci, bool need_dirhash_key, struct fscrypt_master_key **mk_ret);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/keysetup.c (0)
Location: fs/crypto/keysetup.c:439
Inline: False
Direct callers:
  - fs/crypto/keysetup.c:fscrypt_setup_encryption_info
```
**Symbols:**

```
ffffffff8156c9f0-ffffffff8156cc62: setup_file_encryption_key (STB_LOCAL)
ffffffff821c7057-ffffffff821c7074: setup_file_encryption_key.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup.c (ffff80001040f038)
Location: fs/crypto/keysetup.c:294
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup.c (c05dbb58)
Location: fs/crypto/keysetup.c:294
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup.c (c00000000051c7e0)
Location: fs/crypto/keysetup.c:294
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup.c (ffffffe0002b7d78)
Location: fs/crypto/keysetup.c:294
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup.c (ffffffff813462d6)
Location: fs/crypto/keysetup.c:294
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup.c (ffffffff81336fb6)
Location: fs/crypto/keysetup.c:294
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup.c (ffffffff81343da6)
Location: fs/crypto/keysetup.c:294
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup.c (ffffffff81357086)
Location: fs/crypto/keysetup.c:294
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool need_dirhash_key</code>
</li>
<li>
<b>Param reordered. </b>
<code>ci, master_key_ret</code> ➡️ <code>ci, need_dirhash_key, master_key_ret</code>
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct fscrypt_info *ci</code> ➡️ <code>struct fscrypt_inode_info *ci</code>
</li>
</ul>
</details>
</li>
</ul>
