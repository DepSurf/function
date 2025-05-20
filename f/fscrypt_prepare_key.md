# Function: <code>fscrypt_prepare_key</code>

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
int fscrypt_prepare_key(struct fscrypt_prepared_key *prep_key, const u8 *raw_key, const struct fscrypt_info *ci);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup.c (ffffffff813a4d96)
Location: fs/crypto/keysetup.c:123
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_setup_v2_file_key
  - fs/crypto/keysetup.c:fscrypt_setup_v2_file_key
  - fs/crypto/keysetup.c:setup_per_mode_enc_key
  - fs/crypto/keysetup.c:setup_per_mode_enc_key
Direct callers:
  - fs/crypto/keysetup_v1.c:fscrypt_get_direct_key
```
**Symbols:**

```
ffffffff813a4a60-ffffffff813a4aa3: fscrypt_prepare_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int fscrypt_prepare_key(struct fscrypt_prepared_key *prep_key, const u8 *raw_key, const struct fscrypt_info *ci);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/crypto/keysetup.c (ffffffff813ab99e)
Location: fs/crypto/keysetup.c:123
Inline: True
Direct callers:
  - fs/crypto/keysetup.c:fscrypt_setup_v2_file_key
  - fs/crypto/keysetup.c:setup_per_mode_enc_key
  - fs/crypto/keysetup_v1.c:fscrypt_get_direct_key
```
**Symbols:**

```
ffffffff81bdcf2e-ffffffff81bdcf9f: fscrypt_prepare_key.cold (STB_LOCAL)
ffffffff813ab970-ffffffff813aba55: fscrypt_prepare_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int fscrypt_prepare_key(struct fscrypt_prepared_key *prep_key, const u8 *raw_key, const struct fscrypt_info *ci);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/crypto/keysetup.c (ffffffff813fb24d)
Location: fs/crypto/keysetup.c:128
Inline: True
Direct callers:
  - fs/crypto/keysetup.c:fscrypt_setup_v2_file_key
  - fs/crypto/keysetup.c:setup_per_mode_enc_key
  - fs/crypto/keysetup_v1.c:fscrypt_get_direct_key
```
**Symbols:**

```
ffffffff81cc6511-ffffffff81cc659f: fscrypt_prepare_key.cold (STB_LOCAL)
ffffffff813fb210-ffffffff813fb30a: fscrypt_prepare_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
int fscrypt_prepare_key(struct fscrypt_prepared_key *prep_key, const u8 *raw_key, const struct fscrypt_info *ci);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/crypto/keysetup.c (ffffffff8146e57a)
Location: fs/crypto/keysetup.c:129
Inline: True
Direct callers:
  - fs/crypto/keysetup.c:fscrypt_setup_v2_file_key
  - fs/crypto/keysetup.c:setup_per_mode_enc_key
  - fs/crypto/keysetup_v1.c:fscrypt_get_direct_key
```
**Symbols:**

```
ffffffff81e78981-ffffffff81e78a0e: fscrypt_prepare_key.cold (STB_LOCAL)
ffffffff8146e540-ffffffff8146e655: fscrypt_prepare_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
int fscrypt_prepare_key(struct fscrypt_prepared_key *prep_key, const u8 *raw_key, const struct fscrypt_info *ci);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/crypto/keysetup.c (ffffffff814ffbca)
Location: fs/crypto/keysetup.c:150
Inline: True
Direct callers:
  - fs/crypto/keysetup.c:fscrypt_setup_v2_file_key
  - fs/crypto/keysetup.c:setup_per_mode_enc_key
  - fs/crypto/keysetup_v1.c:fscrypt_get_direct_key
```
**Symbols:**

```
ffffffff8206a604-ffffffff8206a620: fscrypt_prepare_key.cold (STB_LOCAL)
ffffffff814ffb90-ffffffff814ffd1a: fscrypt_prepare_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
int fscrypt_prepare_key(struct fscrypt_prepared_key *prep_key, const u8 *raw_key, const struct fscrypt_info *ci);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/crypto/keysetup.c (ffffffff8153719a)
Location: fs/crypto/keysetup.c:150
Inline: True
Direct callers:
  - fs/crypto/keysetup.c:fscrypt_setup_v2_file_key
  - fs/crypto/keysetup.c:setup_per_mode_enc_key
  - fs/crypto/keysetup_v1.c:fscrypt_get_direct_key
```
**Symbols:**

```
ffffffff820ea412-ffffffff820ea42e: fscrypt_prepare_key.cold (STB_LOCAL)
ffffffff81537160-ffffffff815372ea: fscrypt_prepare_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int fscrypt_prepare_key(struct fscrypt_prepared_key *prep_key, const u8 *raw_key, const struct fscrypt_inode_info *ci);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/crypto/keysetup.c (ffffffff8156c26a)
Location: fs/crypto/keysetup.c:150
Inline: True
Direct callers:
  - fs/crypto/keysetup.c:fscrypt_setup_v2_file_key
  - fs/crypto/keysetup.c:setup_per_mode_enc_key
  - fs/crypto/keysetup_v1.c:fscrypt_get_direct_key
```
**Symbols:**

```
ffffffff821c6f73-ffffffff821c6f8f: fscrypt_prepare_key.cold (STB_LOCAL)
ffffffff8156c230-ffffffff8156c3ba: fscrypt_prepare_key (STB_GLOBAL)
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>const struct fscrypt_info *ci</code> ➡️ <code>const struct fscrypt_inode_info *ci</code>
</li>
</ul>
</details>
</li>
</ul>
