# Function: <code>ecryptfs_generate_key_packet_set</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ecryptfs_generate_key_packet_set(char *dest_base, struct ecryptfs_crypt_stat *crypt_stat, struct dentry *ecryptfs_dentry, size_t *len, size_t max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/keystore.c (ffffffff8130a280)
Location: fs/ecryptfs/keystore.c:2390
Inline: False
Direct callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
```
**Symbols:**

```
ffffffff8130a280-ffffffff8130ab6e: ecryptfs_generate_key_packet_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ecryptfs_generate_key_packet_set(char *dest_base, struct ecryptfs_crypt_stat *crypt_stat, struct dentry *ecryptfs_dentry, size_t *len, size_t max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/keystore.c (ffffffff8133e4e0)
Location: fs/ecryptfs/keystore.c:2422
Inline: False
Direct callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
```
**Symbols:**

```
ffffffff8133e4e0-ffffffff8133eda9: ecryptfs_generate_key_packet_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ecryptfs_generate_key_packet_set(char *dest_base, struct ecryptfs_crypt_stat *crypt_stat, struct dentry *ecryptfs_dentry, size_t *len, size_t max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/keystore.c (ffffffff81354270)
Location: fs/ecryptfs/keystore.c:2422
Inline: False
Direct callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
```
**Symbols:**

```
ffffffff81354270-ffffffff81354b39: ecryptfs_generate_key_packet_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ecryptfs_generate_key_packet_set(char *dest_base, struct ecryptfs_crypt_stat *crypt_stat, struct dentry *ecryptfs_dentry, size_t *len, size_t max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/keystore.c (ffffffff81368da0)
Location: fs/ecryptfs/keystore.c:2422
Inline: False
Direct callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
```
**Symbols:**

```
ffffffff81368da0-ffffffff813696b1: ecryptfs_generate_key_packet_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ecryptfs_generate_key_packet_set(char *dest_base, struct ecryptfs_crypt_stat *crypt_stat, struct dentry *ecryptfs_dentry, size_t *len, size_t max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/keystore.c (ffffffff8138d990)
Location: fs/ecryptfs/keystore.c:2412
Inline: False
Direct callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
```
**Symbols:**

```
ffffffff8138d990-ffffffff8138e2a1: ecryptfs_generate_key_packet_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int ecryptfs_generate_key_packet_set(char *dest_base, struct ecryptfs_crypt_stat *crypt_stat, struct dentry *ecryptfs_dentry, size_t *len, size_t max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/keystore.c (0)
Location: fs/ecryptfs/keystore.c:2412
Inline: False
Direct callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
```
**Symbols:**

```
ffffffff813bd304-ffffffff813bd492: ecryptfs_generate_key_packet_set.cold.23 (STB_LOCAL)
ffffffff813bc310-ffffffff813bcaf7: ecryptfs_generate_key_packet_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int ecryptfs_generate_key_packet_set(char *dest_base, struct ecryptfs_crypt_stat *crypt_stat, struct dentry *ecryptfs_dentry, size_t *len, size_t max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/keystore.c (0)
Location: fs/ecryptfs/keystore.c:2412
Inline: False
Direct callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
```
**Symbols:**

```
ffffffff813d6946-ffffffff813d6ad4: ecryptfs_generate_key_packet_set.cold.23 (STB_LOCAL)
ffffffff813d5980-ffffffff813d6167: ecryptfs_generate_key_packet_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int ecryptfs_generate_key_packet_set(char *dest_base, struct ecryptfs_crypt_stat *crypt_stat, struct dentry *ecryptfs_dentry, size_t *len, size_t max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/keystore.c (0)
Location: fs/ecryptfs/keystore.c:2398
Inline: False
Direct callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
```
**Symbols:**

```
ffffffff814012f1-ffffffff814014a2: ecryptfs_generate_key_packet_set.cold (STB_LOCAL)
ffffffff814001c0-ffffffff814009d5: ecryptfs_generate_key_packet_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int ecryptfs_generate_key_packet_set(char *dest_base, struct ecryptfs_crypt_stat *crypt_stat, struct dentry *ecryptfs_dentry, size_t *len, size_t max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/keystore.c (0)
Location: fs/ecryptfs/keystore.c:2398
Inline: False
Direct callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
```
**Symbols:**

```
ffffffff8141b1e1-ffffffff8141b392: ecryptfs_generate_key_packet_set.cold (STB_LOCAL)
ffffffff8141a0b0-ffffffff8141a8c5: ecryptfs_generate_key_packet_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int ecryptfs_generate_key_packet_set(char *dest_base, struct ecryptfs_crypt_stat *crypt_stat, struct dentry *ecryptfs_dentry, size_t *len, size_t max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/keystore.c (0)
Location: fs/ecryptfs/keystore.c:2398
Inline: False
Direct callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_headers_virt
```
**Symbols:**

```
ffffffff81469e0f-ffffffff81469e99: ecryptfs_generate_key_packet_set.cold (STB_LOCAL)
ffffffff81469080-ffffffff81469364: ecryptfs_generate_key_packet_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int ecryptfs_generate_key_packet_set(char *dest_base, struct ecryptfs_crypt_stat *crypt_stat, struct dentry *ecryptfs_dentry, size_t *len, size_t max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/keystore.c (0)
Location: fs/ecryptfs/keystore.c:2398
Inline: False
Direct callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_headers_virt
```
**Symbols:**

```
ffffffff81bef39c-ffffffff81bef426: ecryptfs_generate_key_packet_set.cold (STB_LOCAL)
ffffffff81484500-ffffffff814847e4: ecryptfs_generate_key_packet_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int ecryptfs_generate_key_packet_set(char *dest_base, struct ecryptfs_crypt_stat *crypt_stat, struct dentry *ecryptfs_dentry, size_t *len, size_t max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/keystore.c (0)
Location: fs/ecryptfs/keystore.c:2399
Inline: False
Direct callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
```
**Symbols:**

```
ffffffff81be143e-ffffffff81be14cb: ecryptfs_generate_key_packet_set.cold (STB_LOCAL)
ffffffff81489fb0-ffffffff8148a298: ecryptfs_generate_key_packet_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int ecryptfs_generate_key_packet_set(char *dest_base, struct ecryptfs_crypt_stat *crypt_stat, struct dentry *ecryptfs_dentry, size_t *len, size_t max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/keystore.c (0)
Location: fs/ecryptfs/keystore.c:2399
Inline: False
Direct callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
```
**Symbols:**

```
ffffffff81cd1bd5-ffffffff81cd1c62: ecryptfs_generate_key_packet_set.cold (STB_LOCAL)
ffffffff814e17b0-ffffffff814e1a98: ecryptfs_generate_key_packet_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int ecryptfs_generate_key_packet_set(char *dest_base, struct ecryptfs_crypt_stat *crypt_stat, struct dentry *ecryptfs_dentry, size_t *len, size_t max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/keystore.c (0)
Location: fs/ecryptfs/keystore.c:2399
Inline: False
Direct callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
```
**Symbols:**

```
ffffffff81e84d09-ffffffff81e84da3: ecryptfs_generate_key_packet_set.cold (STB_LOCAL)
ffffffff8156f950-ffffffff8156fc7e: ecryptfs_generate_key_packet_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ecryptfs_generate_key_packet_set(char *dest_base, struct ecryptfs_crypt_stat *crypt_stat, struct dentry *ecryptfs_dentry, size_t *len, size_t max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/keystore.c (ffffffff816147f0)
Location: fs/ecryptfs/keystore.c:2399
Inline: False
Direct callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
```
**Symbols:**

```
ffffffff816147f0-ffffffff81614b5b: ecryptfs_generate_key_packet_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ecryptfs_generate_key_packet_set(char *dest_base, struct ecryptfs_crypt_stat *crypt_stat, struct dentry *ecryptfs_dentry, size_t *len, size_t max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/keystore.c (ffffffff8164c860)
Location: fs/ecryptfs/keystore.c:2399
Inline: False
Direct callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
```
**Symbols:**

```
ffffffff8164c860-ffffffff8164cbd2: ecryptfs_generate_key_packet_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ecryptfs_generate_key_packet_set(char *dest_base, struct ecryptfs_crypt_stat *crypt_stat, struct dentry *ecryptfs_dentry, size_t *len, size_t max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/keystore.c (ffffffff81685d90)
Location: fs/ecryptfs/keystore.c:2399
Inline: False
Direct callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
```
**Symbols:**

```
ffffffff81685d90-ffffffff81686102: ecryptfs_generate_key_packet_set (STB_GLOBAL)
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
int ecryptfs_generate_key_packet_set(char *dest_base, struct ecryptfs_crypt_stat *crypt_stat, struct dentry *ecryptfs_dentry, size_t *len, size_t max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/keystore.c (ffff8000104fbd70)
Location: fs/ecryptfs/keystore.c:2398
Inline: False
Direct callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
```
**Symbols:**

```
ffff8000104fbd70-ffff8000104fc614: ecryptfs_generate_key_packet_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ecryptfs_generate_key_packet_set(char *dest_base, struct ecryptfs_crypt_stat *crypt_stat, struct dentry *ecryptfs_dentry, size_t *len, size_t max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/keystore.c (c06b93dc)
Location: fs/ecryptfs/keystore.c:2398
Inline: False
Direct callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
```
**Symbols:**

```
c06b93dc-c06b9c54: ecryptfs_generate_key_packet_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ecryptfs_generate_key_packet_set(char *dest_base, struct ecryptfs_crypt_stat *crypt_stat, struct dentry *ecryptfs_dentry, size_t *len, size_t max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/keystore.c (c00000000063e9e0)
Location: fs/ecryptfs/keystore.c:2398
Inline: False
Direct callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
```
**Symbols:**

```
c00000000063e9e0-c00000000063f4d4: ecryptfs_generate_key_packet_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ecryptfs_generate_key_packet_set(char *dest_base, struct ecryptfs_crypt_stat *crypt_stat, struct dentry *ecryptfs_dentry, size_t *len, size_t max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/keystore.c (ffffffe00036a38c)
Location: fs/ecryptfs/keystore.c:2398
Inline: False
Direct callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
```
**Symbols:**

```
ffffffe00036a38c-ffffffe00036acfe: ecryptfs_generate_key_packet_set (STB_GLOBAL)
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
int ecryptfs_generate_key_packet_set(char *dest_base, struct ecryptfs_crypt_stat *crypt_stat, struct dentry *ecryptfs_dentry, size_t *len, size_t max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/keystore.c (0)
Location: fs/ecryptfs/keystore.c:2398
Inline: False
Direct callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
```
**Symbols:**

```
ffffffff814137c1-ffffffff81413972: ecryptfs_generate_key_packet_set.cold (STB_LOCAL)
ffffffff81412690-ffffffff81412ea5: ecryptfs_generate_key_packet_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int ecryptfs_generate_key_packet_set(char *dest_base, struct ecryptfs_crypt_stat *crypt_stat, struct dentry *ecryptfs_dentry, size_t *len, size_t max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/keystore.c (0)
Location: fs/ecryptfs/keystore.c:2398
Inline: False
Direct callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
```
**Symbols:**

```
ffffffff81404241-ffffffff814043f2: ecryptfs_generate_key_packet_set.cold (STB_LOCAL)
ffffffff81403110-ffffffff81403925: ecryptfs_generate_key_packet_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int ecryptfs_generate_key_packet_set(char *dest_base, struct ecryptfs_crypt_stat *crypt_stat, struct dentry *ecryptfs_dentry, size_t *len, size_t max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/keystore.c (0)
Location: fs/ecryptfs/keystore.c:2398
Inline: False
Direct callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
```
**Symbols:**

```
ffffffff81410b41-ffffffff81410cf2: ecryptfs_generate_key_packet_set.cold (STB_LOCAL)
ffffffff8140fa10-ffffffff81410225: ecryptfs_generate_key_packet_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int ecryptfs_generate_key_packet_set(char *dest_base, struct ecryptfs_crypt_stat *crypt_stat, struct dentry *ecryptfs_dentry, size_t *len, size_t max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/keystore.c (0)
Location: fs/ecryptfs/keystore.c:2398
Inline: False
Direct callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
```
**Symbols:**

```
ffffffff814267b1-ffffffff81426962: ecryptfs_generate_key_packet_set.cold (STB_LOCAL)
ffffffff81425680-ffffffff81425e95: ecryptfs_generate_key_packet_set (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
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
