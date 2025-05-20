# Function: <code>fscrypt_prepare_inline_crypt_key</code>

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
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int fscrypt_prepare_inline_crypt_key(struct fscrypt_prepared_key *prep_key, const u8 *raw_key, const struct fscrypt_info *ci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/inline_crypt.c (0)
Location: fs/crypto/inline_crypt.c:126
Inline: False
Direct callers:
  - fs/crypto/keysetup.c:fscrypt_setup_v2_file_key
  - fs/crypto/keysetup.c:setup_per_mode_enc_key
```
**Symbols:**

```
ffffffff81beb296-ffffffff81beb328: fscrypt_prepare_inline_crypt_key.cold (STB_LOCAL)
ffffffff813a76f0-ffffffff813a786c: fscrypt_prepare_inline_crypt_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int fscrypt_prepare_inline_crypt_key(struct fscrypt_prepared_key *prep_key, const u8 *raw_key, const struct fscrypt_info *ci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/inline_crypt.c (0)
Location: fs/crypto/inline_crypt.c:126
Inline: False
```
**Symbols:**

```
ffffffff81bdd2ef-ffffffff81bdd37f: fscrypt_prepare_inline_crypt_key.cold (STB_LOCAL)
ffffffff813ae730-ffffffff813ae8bc: fscrypt_prepare_inline_crypt_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int fscrypt_prepare_inline_crypt_key(struct fscrypt_prepared_key *prep_key, const u8 *raw_key, const struct fscrypt_info *ci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/inline_crypt.c (0)
Location: fs/crypto/inline_crypt.c:126
Inline: False
```
**Symbols:**

```
ffffffff81cc6bbc-ffffffff81cc6c4c: fscrypt_prepare_inline_crypt_key.cold (STB_LOCAL)
ffffffff813fe2d0-ffffffff813fe45c: fscrypt_prepare_inline_crypt_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int fscrypt_prepare_inline_crypt_key(struct fscrypt_prepared_key *prep_key, const u8 *raw_key, const struct fscrypt_info *ci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/inline_crypt.c (0)
Location: fs/crypto/inline_crypt.c:158
Inline: False
```
**Symbols:**

```
ffffffff81e790ff-ffffffff81e79191: fscrypt_prepare_inline_crypt_key.cold (STB_LOCAL)
ffffffff81471e00-ffffffff81471f7b: fscrypt_prepare_inline_crypt_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int fscrypt_prepare_inline_crypt_key(struct fscrypt_prepared_key *prep_key, const u8 *raw_key, const struct fscrypt_info *ci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/inline_crypt.c (ffffffff815039c0)
Location: fs/crypto/inline_crypt.c:153
Inline: False
```
**Symbols:**

```
ffffffff815039c0-ffffffff81503b3f: fscrypt_prepare_inline_crypt_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int fscrypt_prepare_inline_crypt_key(struct fscrypt_prepared_key *prep_key, const u8 *raw_key, const struct fscrypt_info *ci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/inline_crypt.c (ffffffff8153b270)
Location: fs/crypto/inline_crypt.c:153
Inline: False
```
**Symbols:**

```
ffffffff8153b270-ffffffff8153b3ee: fscrypt_prepare_inline_crypt_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int fscrypt_prepare_inline_crypt_key(struct fscrypt_prepared_key *prep_key, const u8 *raw_key, const struct fscrypt_inode_info *ci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/inline_crypt.c (0)
Location: fs/crypto/inline_crypt.c:152
Inline: False
```
**Symbols:**

```
ffffffff821c748e-ffffffff821c74ae: fscrypt_prepare_inline_crypt_key.cold (STB_LOCAL)
ffffffff81570500-ffffffff815706c4: fscrypt_prepare_inline_crypt_key (STB_GLOBAL)
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
