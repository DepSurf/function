# Function: <code>fscrypt_destroy_hkdf</code>

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
void fscrypt_destroy_hkdf(struct fscrypt_hkdf *hkdf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/hkdf.c (ffffffff8134bb30)
Location: fs/crypto/hkdf.c:178
Inline: False
Direct callers:
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:fscrypt_ioctl_add_key
  - fs/crypto/keyring.c:free_master_key
```
**Symbols:**

```
ffffffff8134bb30-ffffffff8134bb47: fscrypt_destroy_hkdf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void fscrypt_destroy_hkdf(struct fscrypt_hkdf *hkdf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/hkdf.c (ffffffff81391480)
Location: fs/crypto/hkdf.c:174
Inline: False
Direct callers:
  - fs/crypto/keyring.c:fscrypt_add_test_dummy_key
  - fs/crypto/keyring.c:fscrypt_ioctl_add_key
  - fs/crypto/keyring.c:free_master_key
```
**Symbols:**

```
ffffffff81391480-ffffffff81391497: fscrypt_destroy_hkdf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void fscrypt_destroy_hkdf(struct fscrypt_hkdf *hkdf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/hkdf.c (ffffffff813a28e0)
Location: fs/crypto/hkdf.c:174
Inline: False
Direct callers:
  - fs/crypto/keyring.c:fscrypt_add_test_dummy_key
  - fs/crypto/keyring.c:fscrypt_ioctl_add_key
  - fs/crypto/keyring.c:free_master_key
```
**Symbols:**

```
ffffffff813a28e0-ffffffff813a28f7: fscrypt_destroy_hkdf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void fscrypt_destroy_hkdf(struct fscrypt_hkdf *hkdf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/hkdf.c (ffffffff813a9a70)
Location: fs/crypto/hkdf.c:174
Inline: False
Direct callers:
  - fs/crypto/keyring.c:fscrypt_add_test_dummy_key
  - fs/crypto/keyring.c:fscrypt_ioctl_add_key
  - fs/crypto/keyring.c:free_master_key
```
**Symbols:**

```
ffffffff813a9a70-ffffffff813a9a87: fscrypt_destroy_hkdf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void fscrypt_destroy_hkdf(struct fscrypt_hkdf *hkdf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/hkdf.c (ffffffff813f92b0)
Location: fs/crypto/hkdf.c:179
Inline: False
Direct callers:
  - fs/crypto/keyring.c:fscrypt_add_test_dummy_key
  - fs/crypto/keyring.c:fscrypt_ioctl_add_key
  - fs/crypto/keyring.c:free_master_key
```
**Symbols:**

```
ffffffff813f92b0-ffffffff813f92c7: fscrypt_destroy_hkdf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void fscrypt_destroy_hkdf(struct fscrypt_hkdf *hkdf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/hkdf.c (ffffffff8146c0d0)
Location: fs/crypto/hkdf.c:179
Inline: False
Direct callers:
  - fs/crypto/keyring.c:fscrypt_add_test_dummy_key
  - fs/crypto/keyring.c:fscrypt_get_test_dummy_key_identifier
  - fs/crypto/keyring.c:fscrypt_ioctl_add_key
  - fs/crypto/keyring.c:add_new_master_key
  - fs/crypto/keyring.c:fscrypt_key_destroy
```
**Symbols:**

```
ffffffff8146c0d0-ffffffff8146c0ef: fscrypt_destroy_hkdf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void fscrypt_destroy_hkdf(struct fscrypt_hkdf *hkdf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/hkdf.c (ffffffff814fd410)
Location: fs/crypto/hkdf.c:179
Inline: False
Direct callers:
  - fs/crypto/keyring.c:fscrypt_add_test_dummy_key
  - fs/crypto/keyring.c:fscrypt_get_test_dummy_key_identifier
  - fs/crypto/keyring.c:fscrypt_ioctl_add_key
  - fs/crypto/keyring.c:fscrypt_destroy_keyring
```
**Symbols:**

```
ffffffff814fd410-ffffffff814fd42f: fscrypt_destroy_hkdf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void fscrypt_destroy_hkdf(struct fscrypt_hkdf *hkdf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/hkdf.c (ffffffff81534970)
Location: fs/crypto/hkdf.c:179
Inline: False
Direct callers:
  - fs/crypto/keyring.c:fscrypt_add_test_dummy_key
  - fs/crypto/keyring.c:fscrypt_get_test_dummy_key_identifier
  - fs/crypto/keyring.c:fscrypt_ioctl_add_key
  - fs/crypto/keyring.c:fscrypt_destroy_keyring
```
**Symbols:**

```
ffffffff81534970-ffffffff8153498f: fscrypt_destroy_hkdf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void fscrypt_destroy_hkdf(struct fscrypt_hkdf *hkdf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/hkdf.c (ffffffff81569930)
Location: fs/crypto/hkdf.c:179
Inline: False
Direct callers:
  - fs/crypto/keyring.c:fscrypt_add_test_dummy_key
  - fs/crypto/keyring.c:fscrypt_get_test_dummy_key_identifier
  - fs/crypto/keyring.c:fscrypt_ioctl_add_key
  - fs/crypto/keyring.c:fscrypt_destroy_keyring
```
**Symbols:**

```
ffffffff81569930-ffffffff8156994f: fscrypt_destroy_hkdf (STB_GLOBAL)
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
void fscrypt_destroy_hkdf(struct fscrypt_hkdf *hkdf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/hkdf.c (ffff80001040c510)
Location: fs/crypto/hkdf.c:178
Inline: False
Direct callers:
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:fscrypt_ioctl_add_key
  - fs/crypto/keyring.c:free_master_key
```
**Symbols:**

```
ffff80001040c510-ffff80001040c540: fscrypt_destroy_hkdf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void fscrypt_destroy_hkdf(struct fscrypt_hkdf *hkdf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/hkdf.c (c05d9638)
Location: fs/crypto/hkdf.c:178
Inline: False
Direct callers:
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:fscrypt_ioctl_add_key
  - fs/crypto/keyring.c:free_master_key
```
**Symbols:**

```
c05d9638-c05d965c: fscrypt_destroy_hkdf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void fscrypt_destroy_hkdf(struct fscrypt_hkdf *hkdf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/hkdf.c (c000000000519570)
Location: fs/crypto/hkdf.c:178
Inline: False
Direct callers:
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:fscrypt_ioctl_add_key
  - fs/crypto/keyring.c:free_master_key
```
**Symbols:**

```
c000000000519570-c0000000005195ac: fscrypt_destroy_hkdf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void fscrypt_destroy_hkdf(struct fscrypt_hkdf *hkdf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/hkdf.c (ffffffe0002b5dd0)
Location: fs/crypto/hkdf.c:178
Inline: False
Direct callers:
  - fs/crypto/keyring.c:wipe_master_key_secret
```
**Symbols:**

```
ffffffe0002b5dd0-ffffffe0002b5dfe: fscrypt_destroy_hkdf (STB_GLOBAL)
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
void fscrypt_destroy_hkdf(struct fscrypt_hkdf *hkdf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/hkdf.c (ffffffff81344110)
Location: fs/crypto/hkdf.c:178
Inline: False
Direct callers:
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:fscrypt_ioctl_add_key
  - fs/crypto/keyring.c:free_master_key
```
**Symbols:**

```
ffffffff81344110-ffffffff81344127: fscrypt_destroy_hkdf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void fscrypt_destroy_hkdf(struct fscrypt_hkdf *hkdf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/hkdf.c (ffffffff81334df0)
Location: fs/crypto/hkdf.c:178
Inline: False
Direct callers:
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:fscrypt_ioctl_add_key
  - fs/crypto/keyring.c:free_master_key
```
**Symbols:**

```
ffffffff81334df0-ffffffff81334e07: fscrypt_destroy_hkdf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void fscrypt_destroy_hkdf(struct fscrypt_hkdf *hkdf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/hkdf.c (ffffffff81341be0)
Location: fs/crypto/hkdf.c:178
Inline: False
Direct callers:
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:fscrypt_ioctl_add_key
  - fs/crypto/keyring.c:free_master_key
```
**Symbols:**

```
ffffffff81341be0-ffffffff81341bf7: fscrypt_destroy_hkdf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void fscrypt_destroy_hkdf(struct fscrypt_hkdf *hkdf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/hkdf.c (ffffffff81354ee0)
Location: fs/crypto/hkdf.c:178
Inline: False
Direct callers:
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:fscrypt_ioctl_add_key
  - fs/crypto/keyring.c:free_master_key
```
**Symbols:**

```
ffffffff81354ee0-ffffffff81354ef7: fscrypt_destroy_hkdf (STB_GLOBAL)
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
