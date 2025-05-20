# Function: <code>fscrypt_init_hkdf</code>

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
int fscrypt_init_hkdf(struct fscrypt_hkdf *hkdf, const u8 *master_key, unsigned int master_key_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/hkdf.c (0)
Location: fs/crypto/hkdf.c:67
Inline: False
Direct callers:
  - fs/crypto/keyring.c:fscrypt_ioctl_add_key
```
**Symbols:**

```
ffffffff8134bb53-ffffffff8134bb73: fscrypt_init_hkdf.cold (STB_LOCAL)
ffffffff8134b750-ffffffff8134b82d: fscrypt_init_hkdf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int fscrypt_init_hkdf(struct fscrypt_hkdf *hkdf, const u8 *master_key, unsigned int master_key_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/hkdf.c (0)
Location: fs/crypto/hkdf.c:63
Inline: False
Direct callers:
  - fs/crypto/keyring.c:add_master_key
```
**Symbols:**

```
ffffffff81391497-ffffffff813914b7: fscrypt_init_hkdf.cold (STB_LOCAL)
ffffffff81391070-ffffffff81391174: fscrypt_init_hkdf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int fscrypt_init_hkdf(struct fscrypt_hkdf *hkdf, const u8 *master_key, unsigned int master_key_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/hkdf.c (0)
Location: fs/crypto/hkdf.c:63
Inline: False
Direct callers:
  - fs/crypto/keyring.c:add_master_key
```
**Symbols:**

```
ffffffff81beade6-ffffffff81beae06: fscrypt_init_hkdf.cold (STB_LOCAL)
ffffffff813a24d0-ffffffff813a25d4: fscrypt_init_hkdf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int fscrypt_init_hkdf(struct fscrypt_hkdf *hkdf, const u8 *master_key, unsigned int master_key_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/hkdf.c (0)
Location: fs/crypto/hkdf.c:63
Inline: False
Direct callers:
  - fs/crypto/keyring.c:add_master_key
```
**Symbols:**

```
ffffffff81bdce33-ffffffff81bdce53: fscrypt_init_hkdf.cold (STB_LOCAL)
ffffffff813a9650-ffffffff813a9754: fscrypt_init_hkdf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int fscrypt_init_hkdf(struct fscrypt_hkdf *hkdf, const u8 *master_key, unsigned int master_key_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/hkdf.c (0)
Location: fs/crypto/hkdf.c:68
Inline: False
Direct callers:
  - fs/crypto/keyring.c:add_master_key
```
**Symbols:**

```
ffffffff81cc63ee-ffffffff81cc640e: fscrypt_init_hkdf.cold (STB_LOCAL)
ffffffff813f8e90-ffffffff813f8f94: fscrypt_init_hkdf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int fscrypt_init_hkdf(struct fscrypt_hkdf *hkdf, const u8 *master_key, unsigned int master_key_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/hkdf.c (0)
Location: fs/crypto/hkdf.c:68
Inline: False
Direct callers:
  - fs/crypto/keyring.c:fscrypt_get_test_dummy_key_identifier
  - fs/crypto/keyring.c:add_master_key
```
**Symbols:**

```
ffffffff81e78862-ffffffff81e78882: fscrypt_init_hkdf.cold (STB_LOCAL)
ffffffff8146bc40-ffffffff8146bd56: fscrypt_init_hkdf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int fscrypt_init_hkdf(struct fscrypt_hkdf *hkdf, const u8 *master_key, unsigned int master_key_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/hkdf.c (ffffffff814fcf40)
Location: fs/crypto/hkdf.c:68
Inline: False
Direct callers:
  - fs/crypto/keyring.c:fscrypt_get_test_dummy_key_identifier
  - fs/crypto/keyring.c:add_master_key
```
**Symbols:**

```
ffffffff814fcf40-ffffffff814fd07a: fscrypt_init_hkdf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int fscrypt_init_hkdf(struct fscrypt_hkdf *hkdf, const u8 *master_key, unsigned int master_key_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/hkdf.c (ffffffff815344a0)
Location: fs/crypto/hkdf.c:68
Inline: False
Direct callers:
  - fs/crypto/keyring.c:fscrypt_get_test_dummy_key_identifier
  - fs/crypto/keyring.c:add_master_key
```
**Symbols:**

```
ffffffff815344a0-ffffffff815345da: fscrypt_init_hkdf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int fscrypt_init_hkdf(struct fscrypt_hkdf *hkdf, const u8 *master_key, unsigned int master_key_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/hkdf.c (ffffffff81569460)
Location: fs/crypto/hkdf.c:68
Inline: False
Direct callers:
  - fs/crypto/keyring.c:fscrypt_get_test_dummy_key_identifier
  - fs/crypto/keyring.c:add_master_key
```
**Symbols:**

```
ffffffff81569460-ffffffff8156959a: fscrypt_init_hkdf (STB_GLOBAL)
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
int fscrypt_init_hkdf(struct fscrypt_hkdf *hkdf, const u8 *master_key, unsigned int master_key_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/hkdf.c (ffff80001040c198)
Location: fs/crypto/hkdf.c:67
Inline: False
Direct callers:
  - fs/crypto/keyring.c:fscrypt_ioctl_add_key
```
**Symbols:**

```
ffff80001040c198-ffff80001040c2c4: fscrypt_init_hkdf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int fscrypt_init_hkdf(struct fscrypt_hkdf *hkdf, const u8 *master_key, unsigned int master_key_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/hkdf.c (c05d92a0)
Location: fs/crypto/hkdf.c:67
Inline: False
Direct callers:
  - fs/crypto/keyring.c:fscrypt_ioctl_add_key
```
**Symbols:**

```
c05d92a0-c05d93d0: fscrypt_init_hkdf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int fscrypt_init_hkdf(struct fscrypt_hkdf *hkdf, const u8 *master_key, unsigned int master_key_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/hkdf.c (c0000000005190c0)
Location: fs/crypto/hkdf.c:67
Inline: False
Direct callers:
  - fs/crypto/keyring.c:fscrypt_ioctl_add_key
```
**Symbols:**

```
c0000000005190c0-c000000000519240: fscrypt_init_hkdf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int fscrypt_init_hkdf(struct fscrypt_hkdf *hkdf, const u8 *master_key, unsigned int master_key_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/hkdf.c (ffffffe0002b5b02)
Location: fs/crypto/hkdf.c:67
Inline: False
Direct callers:
  - fs/crypto/keyring.c:fscrypt_ioctl_add_key
```
**Symbols:**

```
ffffffe0002b5b02-ffffffe0002b5bec: fscrypt_init_hkdf (STB_GLOBAL)
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
int fscrypt_init_hkdf(struct fscrypt_hkdf *hkdf, const u8 *master_key, unsigned int master_key_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/hkdf.c (0)
Location: fs/crypto/hkdf.c:67
Inline: False
Direct callers:
  - fs/crypto/keyring.c:fscrypt_ioctl_add_key
```
**Symbols:**

```
ffffffff81344133-ffffffff81344153: fscrypt_init_hkdf.cold (STB_LOCAL)
ffffffff81343d30-ffffffff81343e0d: fscrypt_init_hkdf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int fscrypt_init_hkdf(struct fscrypt_hkdf *hkdf, const u8 *master_key, unsigned int master_key_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/hkdf.c (0)
Location: fs/crypto/hkdf.c:67
Inline: False
Direct callers:
  - fs/crypto/keyring.c:fscrypt_ioctl_add_key
```
**Symbols:**

```
ffffffff81334e13-ffffffff81334e33: fscrypt_init_hkdf.cold (STB_LOCAL)
ffffffff81334a10-ffffffff81334aed: fscrypt_init_hkdf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int fscrypt_init_hkdf(struct fscrypt_hkdf *hkdf, const u8 *master_key, unsigned int master_key_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/hkdf.c (0)
Location: fs/crypto/hkdf.c:67
Inline: False
Direct callers:
  - fs/crypto/keyring.c:fscrypt_ioctl_add_key
```
**Symbols:**

```
ffffffff81341c03-ffffffff81341c23: fscrypt_init_hkdf.cold (STB_LOCAL)
ffffffff81341800-ffffffff813418dd: fscrypt_init_hkdf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int fscrypt_init_hkdf(struct fscrypt_hkdf *hkdf, const u8 *master_key, unsigned int master_key_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/hkdf.c (0)
Location: fs/crypto/hkdf.c:67
Inline: False
Direct callers:
  - fs/crypto/keyring.c:fscrypt_ioctl_add_key
```
**Symbols:**

```
ffffffff81354f03-ffffffff81354f23: fscrypt_init_hkdf.cold (STB_LOCAL)
ffffffff81354b00-ffffffff81354bdd: fscrypt_init_hkdf (STB_GLOBAL)
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
