# Function: <code>fscrypt_destroy_prepared_key</code>

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
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void fscrypt_destroy_prepared_key(struct fscrypt_prepared_key *prep_key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup.c (ffffffff813a47c3)
Location: fs/crypto/keysetup.c:145
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:put_crypt_info
Direct callers:
  - fs/crypto/keyring.c:free_master_key
  - fs/crypto/keyring.c:free_master_key
  - fs/crypto/keyring.c:free_master_key
  - fs/crypto/keysetup_v1.c:fscrypt_get_direct_key
  - fs/crypto/keysetup_v1.c:find_or_insert_direct_key
  - fs/crypto/keysetup_v1.c:fscrypt_put_direct_key
```
**Symbols:**

```
ffffffff813a4ab0-ffffffff813a4ad8: fscrypt_destroy_prepared_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void fscrypt_destroy_prepared_key(struct fscrypt_prepared_key *prep_key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup.c (ffffffff813ab903)
Location: fs/crypto/keysetup.c:145
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:put_crypt_info
Direct callers:
  - fs/crypto/keyring.c:free_master_key
  - fs/crypto/keyring.c:free_master_key
  - fs/crypto/keyring.c:free_master_key
  - fs/crypto/keysetup_v1.c:fscrypt_get_direct_key
  - fs/crypto/keysetup_v1.c:find_or_insert_direct_key
  - fs/crypto/keysetup_v1.c:fscrypt_put_direct_key
```
**Symbols:**

```
ffffffff813abc40-ffffffff813abc68: fscrypt_destroy_prepared_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void fscrypt_destroy_prepared_key(struct fscrypt_prepared_key *prep_key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup.c (ffffffff813fb19f)
Location: fs/crypto/keysetup.c:150
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:put_crypt_info
Direct callers:
  - fs/crypto/keyring.c:free_master_key
  - fs/crypto/keyring.c:free_master_key
  - fs/crypto/keyring.c:free_master_key
  - fs/crypto/keysetup_v1.c:fscrypt_get_direct_key
  - fs/crypto/keysetup_v1.c:find_or_insert_direct_key
  - fs/crypto/keysetup_v1.c:fscrypt_put_direct_key
```
**Symbols:**

```
ffffffff813fb510-ffffffff813fb538: fscrypt_destroy_prepared_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void fscrypt_destroy_prepared_key(struct fscrypt_prepared_key *prep_key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup.c (ffffffff8146e4c6)
Location: fs/crypto/keysetup.c:151
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:put_crypt_info
Direct callers:
  - fs/crypto/keyring.c:add_new_master_key
  - fs/crypto/keyring.c:add_new_master_key
  - fs/crypto/keyring.c:add_new_master_key
  - fs/crypto/keyring.c:fscrypt_key_destroy
  - fs/crypto/keyring.c:fscrypt_key_destroy
  - fs/crypto/keyring.c:fscrypt_key_destroy
  - fs/crypto/keysetup_v1.c:fscrypt_get_direct_key
  - fs/crypto/keysetup_v1.c:find_or_insert_direct_key
  - fs/crypto/keysetup_v1.c:fscrypt_put_direct_key
```
**Symbols:**

```
ffffffff8146e8a0-ffffffff8146e8cf: fscrypt_destroy_prepared_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void fscrypt_destroy_prepared_key(struct super_block *sb, struct fscrypt_prepared_key *prep_key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup.c (ffffffff814ffb08)
Location: fs/crypto/keysetup.c:172
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:put_crypt_info
Direct callers:
  - fs/crypto/keysetup_v1.c:fscrypt_get_direct_key
  - fs/crypto/keysetup_v1.c:find_or_insert_direct_key
  - fs/crypto/keysetup_v1.c:fscrypt_put_direct_key
```
**Symbols:**

```
ffffffff814fff80-ffffffff814fffc5: fscrypt_destroy_prepared_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void fscrypt_destroy_prepared_key(struct super_block *sb, struct fscrypt_prepared_key *prep_key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup.c (ffffffff815370d8)
Location: fs/crypto/keysetup.c:172
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:put_crypt_info
Direct callers:
  - fs/crypto/keysetup_v1.c:fscrypt_get_direct_key
  - fs/crypto/keysetup_v1.c:find_or_insert_direct_key
  - fs/crypto/keysetup_v1.c:fscrypt_put_direct_key
```
**Symbols:**

```
ffffffff81537550-ffffffff81537595: fscrypt_destroy_prepared_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void fscrypt_destroy_prepared_key(struct super_block *sb, struct fscrypt_prepared_key *prep_key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup.c (ffffffff8156c1a8)
Location: fs/crypto/keysetup.c:172
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:put_crypt_info
Direct callers:
  - fs/crypto/keysetup_v1.c:fscrypt_get_direct_key
  - fs/crypto/keysetup_v1.c:find_or_insert_direct_key
  - fs/crypto/keysetup_v1.c:fscrypt_put_direct_key
```
**Symbols:**

```
ffffffff8156c620-ffffffff8156c665: fscrypt_destroy_prepared_key (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct super_block *sb</code>
</li>
<li>
<b>Param reordered. </b>
<code>prep_key</code> ➡️ <code>sb, prep_key</code>
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
