# Function: <code>fscrypt_hkdf_expand</code>

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
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int fscrypt_hkdf_expand(struct fscrypt_hkdf *hkdf, u8 context, const u8 *info, unsigned int infolen, u8 *okm, unsigned int okmlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/hkdf.c (0)
Location: fs/crypto/hkdf.c:115
Inline: False
Direct callers:
  - fs/crypto/keyring.c:fscrypt_ioctl_add_key
  - fs/crypto/keysetup.c:fscrypt_setup_v2_file_key
  - fs/crypto/keysetup.c:setup_per_mode_key
```
**Symbols:**

```
ffffffff8134bb73-ffffffff8134bb7f: fscrypt_hkdf_expand.cold (STB_LOCAL)
ffffffff8134b830-ffffffff8134bb22: fscrypt_hkdf_expand (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int fscrypt_hkdf_expand(const struct fscrypt_hkdf *hkdf, u8 context, const u8 *info, unsigned int infolen, u8 *okm, unsigned int okmlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/hkdf.c (0)
Location: fs/crypto/hkdf.c:111
Inline: False
Direct callers:
  - fs/crypto/keyring.c:add_master_key
  - fs/crypto/keysetup.c:fscrypt_setup_v2_file_key
  - fs/crypto/keysetup.c:fscrypt_setup_v2_file_key
  - fs/crypto/keysetup.c:fscrypt_setup_iv_ino_lblk_32_key
  - fs/crypto/keysetup.c:setup_per_mode_enc_key
```
**Symbols:**

```
ffffffff813914b7-ffffffff813914c3: fscrypt_hkdf_expand.cold (STB_LOCAL)
ffffffff81391180-ffffffff81391477: fscrypt_hkdf_expand (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int fscrypt_hkdf_expand(const struct fscrypt_hkdf *hkdf, u8 context, const u8 *info, unsigned int infolen, u8 *okm, unsigned int okmlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/hkdf.c (0)
Location: fs/crypto/hkdf.c:111
Inline: False
Direct callers:
  - fs/crypto/keyring.c:add_master_key
  - fs/crypto/keysetup.c:fscrypt_setup_v2_file_key
  - fs/crypto/keysetup.c:fscrypt_setup_v2_file_key
  - fs/crypto/keysetup.c:fscrypt_setup_iv_ino_lblk_32_key
  - fs/crypto/keysetup.c:setup_per_mode_enc_key
```
**Symbols:**

```
ffffffff81beae06-ffffffff81beae12: fscrypt_hkdf_expand.cold (STB_LOCAL)
ffffffff813a25e0-ffffffff813a28d7: fscrypt_hkdf_expand (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int fscrypt_hkdf_expand(const struct fscrypt_hkdf *hkdf, u8 context, const u8 *info, unsigned int infolen, u8 *okm, unsigned int okmlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/hkdf.c (0)
Location: fs/crypto/hkdf.c:111
Inline: False
Direct callers:
  - fs/crypto/keyring.c:add_master_key
  - fs/crypto/keysetup.c:fscrypt_setup_v2_file_key
  - fs/crypto/keysetup.c:fscrypt_setup_v2_file_key
  - fs/crypto/keysetup.c:fscrypt_setup_v2_file_key
  - fs/crypto/keysetup.c:setup_per_mode_enc_key
```
**Symbols:**

```
ffffffff81bdce53-ffffffff81bdce5f: fscrypt_hkdf_expand.cold (STB_LOCAL)
ffffffff813a9760-ffffffff813a9a61: fscrypt_hkdf_expand (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int fscrypt_hkdf_expand(const struct fscrypt_hkdf *hkdf, u8 context, const u8 *info, unsigned int infolen, u8 *okm, unsigned int okmlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/hkdf.c (0)
Location: fs/crypto/hkdf.c:116
Inline: False
Direct callers:
  - fs/crypto/keyring.c:add_master_key
  - fs/crypto/keysetup.c:fscrypt_setup_v2_file_key
  - fs/crypto/keysetup.c:fscrypt_setup_v2_file_key
  - fs/crypto/keysetup.c:fscrypt_setup_v2_file_key
  - fs/crypto/keysetup.c:setup_per_mode_enc_key
```
**Symbols:**

```
ffffffff81cc640e-ffffffff81cc641a: fscrypt_hkdf_expand.cold (STB_LOCAL)
ffffffff813f8fa0-ffffffff813f92a1: fscrypt_hkdf_expand (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int fscrypt_hkdf_expand(const struct fscrypt_hkdf *hkdf, u8 context, const u8 *info, unsigned int infolen, u8 *okm, unsigned int okmlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/hkdf.c (ffffffff8146bd60)
Location: fs/crypto/hkdf.c:116
Inline: False
Direct callers:
  - fs/crypto/keyring.c:fscrypt_get_test_dummy_key_identifier
  - fs/crypto/keyring.c:add_master_key
  - fs/crypto/keysetup.c:fscrypt_setup_v2_file_key
  - fs/crypto/keysetup.c:fscrypt_setup_v2_file_key
  - fs/crypto/keysetup.c:fscrypt_setup_v2_file_key
  - fs/crypto/keysetup.c:setup_per_mode_enc_key
```
**Symbols:**

```
ffffffff8146bd60-ffffffff8146c0cb: fscrypt_hkdf_expand (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int fscrypt_hkdf_expand(const struct fscrypt_hkdf *hkdf, u8 context, const u8 *info, unsigned int infolen, u8 *okm, unsigned int okmlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/hkdf.c (ffffffff814fd090)
Location: fs/crypto/hkdf.c:116
Inline: False
Direct callers:
  - fs/crypto/keyring.c:fscrypt_get_test_dummy_key_identifier
  - fs/crypto/keyring.c:add_master_key
  - fs/crypto/keysetup.c:fscrypt_setup_v2_file_key
  - fs/crypto/keysetup.c:fscrypt_setup_v2_file_key
  - fs/crypto/keysetup.c:fscrypt_setup_v2_file_key
  - fs/crypto/keysetup.c:setup_per_mode_enc_key
```
**Symbols:**

```
ffffffff814fd090-ffffffff814fd3fb: fscrypt_hkdf_expand (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int fscrypt_hkdf_expand(const struct fscrypt_hkdf *hkdf, u8 context, const u8 *info, unsigned int infolen, u8 *okm, unsigned int okmlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/hkdf.c (ffffffff815345f0)
Location: fs/crypto/hkdf.c:116
Inline: False
Direct callers:
  - fs/crypto/keyring.c:fscrypt_get_test_dummy_key_identifier
  - fs/crypto/keyring.c:add_master_key
  - fs/crypto/keysetup.c:fscrypt_setup_v2_file_key
  - fs/crypto/keysetup.c:fscrypt_setup_v2_file_key
  - fs/crypto/keysetup.c:fscrypt_setup_v2_file_key
  - fs/crypto/keysetup.c:setup_per_mode_enc_key
```
**Symbols:**

```
ffffffff815345f0-ffffffff8153495e: fscrypt_hkdf_expand (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int fscrypt_hkdf_expand(const struct fscrypt_hkdf *hkdf, u8 context, const u8 *info, unsigned int infolen, u8 *okm, unsigned int okmlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/hkdf.c (ffffffff815695b0)
Location: fs/crypto/hkdf.c:116
Inline: False
Direct callers:
  - fs/crypto/keyring.c:fscrypt_get_test_dummy_key_identifier
  - fs/crypto/keyring.c:add_master_key
  - fs/crypto/keysetup.c:fscrypt_setup_v2_file_key
  - fs/crypto/keysetup.c:fscrypt_setup_v2_file_key
  - fs/crypto/keysetup.c:fscrypt_setup_v2_file_key
  - fs/crypto/keysetup.c:setup_per_mode_enc_key
```
**Symbols:**

```
ffffffff815695b0-ffffffff8156991e: fscrypt_hkdf_expand (STB_GLOBAL)
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
int fscrypt_hkdf_expand(struct fscrypt_hkdf *hkdf, u8 context, const u8 *info, unsigned int infolen, u8 *okm, unsigned int okmlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/hkdf.c (ffff80001040c2c8)
Location: fs/crypto/hkdf.c:115
Inline: False
Direct callers:
  - fs/crypto/keyring.c:fscrypt_ioctl_add_key
  - fs/crypto/keysetup.c:fscrypt_setup_v2_file_key
  - fs/crypto/keysetup.c:setup_per_mode_key
```
**Symbols:**

```
ffff80001040c2c8-ffff80001040c510: fscrypt_hkdf_expand (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int fscrypt_hkdf_expand(struct fscrypt_hkdf *hkdf, u8 context, const u8 *info, unsigned int infolen, u8 *okm, unsigned int okmlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/hkdf.c (c05d93d0)
Location: fs/crypto/hkdf.c:115
Inline: False
Direct callers:
  - fs/crypto/keyring.c:fscrypt_ioctl_add_key
  - fs/crypto/keysetup.c:fscrypt_setup_v2_file_key
  - fs/crypto/keysetup.c:setup_per_mode_key
```
**Symbols:**

```
c05d93d0-c05d9638: fscrypt_hkdf_expand (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int fscrypt_hkdf_expand(struct fscrypt_hkdf *hkdf, u8 context, const u8 *info, unsigned int infolen, u8 *okm, unsigned int okmlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/hkdf.c (c000000000519240)
Location: fs/crypto/hkdf.c:115
Inline: False
Direct callers:
  - fs/crypto/keyring.c:fscrypt_ioctl_add_key
  - fs/crypto/keysetup.c:fscrypt_setup_v2_file_key
  - fs/crypto/keysetup.c:setup_per_mode_key
```
**Symbols:**

```
c000000000519240-c000000000519568: fscrypt_hkdf_expand (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int fscrypt_hkdf_expand(struct fscrypt_hkdf *hkdf, u8 context, const u8 *info, unsigned int infolen, u8 *okm, unsigned int okmlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/hkdf.c (ffffffe0002b5bec)
Location: fs/crypto/hkdf.c:115
Inline: False
Direct callers:
  - fs/crypto/keyring.c:fscrypt_ioctl_add_key
  - fs/crypto/keysetup.c:fscrypt_setup_v2_file_key
  - fs/crypto/keysetup.c:setup_per_mode_key
```
**Symbols:**

```
ffffffe0002b5bec-ffffffe0002b5dd0: fscrypt_hkdf_expand (STB_GLOBAL)
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
int fscrypt_hkdf_expand(struct fscrypt_hkdf *hkdf, u8 context, const u8 *info, unsigned int infolen, u8 *okm, unsigned int okmlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/hkdf.c (0)
Location: fs/crypto/hkdf.c:115
Inline: False
Direct callers:
  - fs/crypto/keyring.c:fscrypt_ioctl_add_key
  - fs/crypto/keysetup.c:fscrypt_setup_v2_file_key
  - fs/crypto/keysetup.c:setup_per_mode_key
```
**Symbols:**

```
ffffffff81344153-ffffffff8134415f: fscrypt_hkdf_expand.cold (STB_LOCAL)
ffffffff81343e10-ffffffff81344102: fscrypt_hkdf_expand (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int fscrypt_hkdf_expand(struct fscrypt_hkdf *hkdf, u8 context, const u8 *info, unsigned int infolen, u8 *okm, unsigned int okmlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/hkdf.c (0)
Location: fs/crypto/hkdf.c:115
Inline: False
Direct callers:
  - fs/crypto/keyring.c:fscrypt_ioctl_add_key
  - fs/crypto/keysetup.c:fscrypt_setup_v2_file_key
  - fs/crypto/keysetup.c:setup_per_mode_key
```
**Symbols:**

```
ffffffff81334e33-ffffffff81334e3f: fscrypt_hkdf_expand.cold (STB_LOCAL)
ffffffff81334af0-ffffffff81334de2: fscrypt_hkdf_expand (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int fscrypt_hkdf_expand(struct fscrypt_hkdf *hkdf, u8 context, const u8 *info, unsigned int infolen, u8 *okm, unsigned int okmlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/hkdf.c (0)
Location: fs/crypto/hkdf.c:115
Inline: False
Direct callers:
  - fs/crypto/keyring.c:fscrypt_ioctl_add_key
  - fs/crypto/keysetup.c:fscrypt_setup_v2_file_key
  - fs/crypto/keysetup.c:setup_per_mode_key
```
**Symbols:**

```
ffffffff81341c23-ffffffff81341c2f: fscrypt_hkdf_expand.cold (STB_LOCAL)
ffffffff813418e0-ffffffff81341bd2: fscrypt_hkdf_expand (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int fscrypt_hkdf_expand(struct fscrypt_hkdf *hkdf, u8 context, const u8 *info, unsigned int infolen, u8 *okm, unsigned int okmlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/hkdf.c (0)
Location: fs/crypto/hkdf.c:115
Inline: False
Direct callers:
  - fs/crypto/keyring.c:fscrypt_ioctl_add_key
  - fs/crypto/keysetup.c:fscrypt_setup_v2_file_key
  - fs/crypto/keysetup.c:setup_per_mode_key
```
**Symbols:**

```
ffffffff81354f23-ffffffff81354f2f: fscrypt_hkdf_expand.cold (STB_LOCAL)
ffffffff81354be0-ffffffff81354ed2: fscrypt_hkdf_expand (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct fscrypt_hkdf *hkdf</code> ➡️ <code>const struct fscrypt_hkdf *hkdf</code>
</li>
</ul>
</details>
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
