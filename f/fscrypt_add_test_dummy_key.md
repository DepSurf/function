# Function: <code>fscrypt_add_test_dummy_key</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int fscrypt_add_test_dummy_key(struct super_block *sb, struct fscrypt_key_specifier *key_spec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (ffffffff81393000)
Location: fs/crypto/keyring.c:691
Inline: False
Direct callers:
  - fs/crypto/policy.c:fscrypt_set_test_dummy_encryption
```
**Symbols:**

```
ffffffff81393000-ffffffff81393131: fscrypt_add_test_dummy_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int fscrypt_add_test_dummy_key(struct super_block *sb, struct fscrypt_key_specifier *key_spec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (ffffffff813a4360)
Location: fs/crypto/keyring.c:696
Inline: False
Direct callers:
  - fs/crypto/policy.c:fscrypt_set_test_dummy_encryption
```
**Symbols:**

```
ffffffff813a4360-ffffffff813a4491: fscrypt_add_test_dummy_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int fscrypt_add_test_dummy_key(struct super_block *sb, struct fscrypt_key_specifier *key_spec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (ffffffff813ab550)
Location: fs/crypto/keyring.c:696
Inline: False
Direct callers:
  - fs/crypto/policy.c:fscrypt_set_test_dummy_encryption
```
**Symbols:**

```
ffffffff813ab550-ffffffff813ab683: fscrypt_add_test_dummy_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int fscrypt_add_test_dummy_key(struct super_block *sb, struct fscrypt_key_specifier *key_spec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (ffffffff813fade0)
Location: fs/crypto/keyring.c:696
Inline: False
Direct callers:
  - fs/crypto/policy.c:fscrypt_set_test_dummy_encryption
```
**Symbols:**

```
ffffffff813fade0-ffffffff813faf13: fscrypt_add_test_dummy_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int fscrypt_add_test_dummy_key(struct super_block *sb, const struct fscrypt_dummy_policy *dummy_policy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (ffffffff8146db40)
Location: fs/crypto/keyring.c:734
Inline: False
Direct callers:
  - fs/crypto/policy.c:fscrypt_set_test_dummy_encryption
  - fs/ext4/super.c:ext4_check_opt_consistency
```
**Symbols:**

```
ffffffff8146db40-ffffffff8146dc2e: fscrypt_add_test_dummy_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int fscrypt_add_test_dummy_key(struct super_block *sb, const struct fscrypt_dummy_policy *dummy_policy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (ffffffff814ff120)
Location: fs/crypto/keyring.c:790
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_check_opt_consistency
```
**Symbols:**

```
ffffffff814ff120-ffffffff814ff20e: fscrypt_add_test_dummy_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int fscrypt_add_test_dummy_key(struct super_block *sb, struct fscrypt_key_specifier *key_spec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (ffffffff81536d50)
Location: fs/crypto/keyring.c:793
Inline: False
Direct callers:
  - fs/crypto/keysetup.c:setup_file_encryption_key
```
**Symbols:**

```
ffffffff81536d50-ffffffff81536dea: fscrypt_add_test_dummy_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int fscrypt_add_test_dummy_key(struct super_block *sb, struct fscrypt_key_specifier *key_spec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (ffffffff8156be00)
Location: fs/crypto/keyring.c:808
Inline: False
Direct callers:
  - fs/crypto/keysetup.c:setup_file_encryption_key
```
**Symbols:**

```
ffffffff8156be00-ffffffff8156be9a: fscrypt_add_test_dummy_key (STB_GLOBAL)
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct fscrypt_dummy_policy *dummy_policy</code>
</li>
<li>
<b>Param removed. </b>
<code>struct fscrypt_key_specifier *key_spec</code>
</li>
</ul>
</details>
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
<code>struct fscrypt_key_specifier *key_spec</code>
</li>
<li>
<b>Param removed. </b>
<code>const struct fscrypt_dummy_policy *dummy_policy</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
