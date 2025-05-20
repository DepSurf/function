# Function: <code>is_hash_blacklisted</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int is_hash_blacklisted(const u8 *hash, size_t hash_len, const char *type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In certs/blacklist.c (ffffffff811b56e0)
Location: certs/blacklist.c:113
Inline: False
Direct callers:
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
```
**Symbols:**

```
ffffffff811b56e0-ffffffff811b579f: is_hash_blacklisted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int is_hash_blacklisted(const u8 *hash, size_t hash_len, const char *type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In certs/blacklist.c (ffffffff811c97d0)
Location: certs/blacklist.c:113
Inline: False
Direct callers:
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
```
**Symbols:**

```
ffffffff811c97d0-ffffffff811c988f: is_hash_blacklisted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int is_hash_blacklisted(const u8 *hash, size_t hash_len, const char *type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In certs/blacklist.c (ffffffff811ea920)
Location: certs/blacklist.c:113
Inline: False
Direct callers:
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
```
**Symbols:**

```
ffffffff811ea920-ffffffff811ea9df: is_hash_blacklisted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int is_hash_blacklisted(const u8 *hash, size_t hash_len, const char *type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In certs/blacklist.c (ffffffff811fb490)
Location: certs/blacklist.c:113
Inline: False
Direct callers:
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
```
**Symbols:**

```
ffffffff811fb490-ffffffff811fb54f: is_hash_blacklisted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int is_hash_blacklisted(const u8 *hash, size_t hash_len, const char *type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In certs/blacklist.c (ffffffff81212b80)
Location: certs/blacklist.c:109
Inline: False
Direct callers:
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
```
**Symbols:**

```
ffffffff81212b80-ffffffff81212c47: is_hash_blacklisted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int is_hash_blacklisted(const u8 *hash, size_t hash_len, const char *type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In certs/blacklist.c (ffffffff812203a0)
Location: certs/blacklist.c:109
Inline: False
Direct callers:
  - certs/blacklist.c:is_binary_blacklisted
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
```
**Symbols:**

```
ffffffff812203a0-ffffffff81220467: is_hash_blacklisted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int is_hash_blacklisted(const u8 *hash, size_t hash_len, const char *type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In certs/blacklist.c (ffffffff8124d7c0)
Location: certs/blacklist.c:109
Inline: False
Direct callers:
  - certs/blacklist.c:is_binary_blacklisted
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
```
**Symbols:**

```
ffffffff8124d7c0-ffffffff8124d881: is_hash_blacklisted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int is_hash_blacklisted(const u8 *hash, size_t hash_len, const char *type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In certs/blacklist.c (ffffffff81257c00)
Location: certs/blacklist.c:109
Inline: False
Direct callers:
  - certs/blacklist.c:is_binary_blacklisted
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
```
**Symbols:**

```
ffffffff81257c00-ffffffff81257cc1: is_hash_blacklisted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int is_hash_blacklisted(const u8 *hash, size_t hash_len, const char *type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In certs/blacklist.c (ffffffff8125c120)
Location: certs/blacklist.c:116
Inline: False
Direct callers:
  - certs/blacklist.c:is_binary_blacklisted
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
```
**Symbols:**

```
ffffffff8125c120-ffffffff8125c1e0: is_hash_blacklisted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int is_hash_blacklisted(const u8 *hash, size_t hash_len, const char *type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In certs/blacklist.c (ffffffff81297fd0)
Location: certs/blacklist.c:116
Inline: False
Direct callers:
  - certs/blacklist.c:is_binary_blacklisted
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
```
**Symbols:**

```
ffffffff81297fd0-ffffffff81298090: is_hash_blacklisted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int is_hash_blacklisted(const u8 *hash, size_t hash_len, enum blacklist_hash_type hash_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In certs/blacklist.c (ffffffff812ee5c0)
Location: certs/blacklist.c:221
Inline: False
Direct callers:
  - certs/blacklist.c:is_binary_blacklisted
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
```
**Symbols:**

```
ffffffff812ee5c0-ffffffff812ee636: is_hash_blacklisted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int is_hash_blacklisted(const u8 *hash, size_t hash_len, enum blacklist_hash_type hash_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In certs/blacklist.c (ffffffff81358a70)
Location: certs/blacklist.c:221
Inline: False
Direct callers:
  - certs/blacklist.c:is_binary_blacklisted
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
```
**Symbols:**

```
ffffffff81358a70-ffffffff81358ae6: is_hash_blacklisted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int is_hash_blacklisted(const u8 *hash, size_t hash_len, enum blacklist_hash_type hash_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In certs/blacklist.c (ffffffff8138a3e0)
Location: certs/blacklist.c:224
Inline: False
Direct callers:
  - certs/blacklist.c:is_binary_blacklisted
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
```
**Symbols:**

```
ffffffff8138a3e0-ffffffff8138a456: is_hash_blacklisted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int is_hash_blacklisted(const u8 *hash, size_t hash_len, enum blacklist_hash_type hash_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In certs/blacklist.c (ffffffff813b3f00)
Location: certs/blacklist.c:224
Inline: False
Direct callers:
  - certs/blacklist.c:is_binary_blacklisted
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
```
**Symbols:**

```
ffffffff813b3f00-ffffffff813b3f76: is_hash_blacklisted (STB_GLOBAL)
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
int is_hash_blacklisted(const u8 *hash, size_t hash_len, const char *type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In certs/blacklist.c (ffff8000102ad648)
Location: certs/blacklist.c:109
Inline: False
Direct callers:
  - certs/blacklist.c:is_binary_blacklisted
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
```
**Symbols:**

```
ffff8000102ad648-ffff8000102ad72c: is_hash_blacklisted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int is_hash_blacklisted(const u8 *hash, size_t hash_len, const char *type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In certs/blacklist.c (c04d9fbc)
Location: certs/blacklist.c:109
Inline: False
Direct callers:
  - certs/blacklist.c:is_binary_blacklisted
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
```
**Symbols:**

```
c04d9fbc-c04da084: is_hash_blacklisted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int is_hash_blacklisted(const u8 *hash, size_t hash_len, const char *type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In certs/blacklist.c (c000000000361340)
Location: certs/blacklist.c:109
Inline: False
Direct callers:
  - certs/blacklist.c:is_binary_blacklisted
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
```
**Symbols:**

```
c000000000361340-c000000000361480: is_hash_blacklisted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int is_hash_blacklisted(const u8 *hash, size_t hash_len, const char *type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In certs/blacklist.c (ffffffe0001d3ad6)
Location: certs/blacklist.c:109
Inline: False
Direct callers:
  - certs/blacklist.c:is_binary_blacklisted
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
```
**Symbols:**

```
ffffffe0001d3ad6-ffffffe0001d3bac: is_hash_blacklisted (STB_GLOBAL)
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
int is_hash_blacklisted(const u8 *hash, size_t hash_len, const char *type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In certs/blacklist.c (ffffffff812189f0)
Location: certs/blacklist.c:109
Inline: False
Direct callers:
  - certs/blacklist.c:is_binary_blacklisted
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
```
**Symbols:**

```
ffffffff812189f0-ffffffff81218ab7: is_hash_blacklisted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int is_hash_blacklisted(const u8 *hash, size_t hash_len, const char *type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In certs/blacklist.c (ffffffff8120bc00)
Location: certs/blacklist.c:109
Inline: False
Direct callers:
  - certs/blacklist.c:is_binary_blacklisted
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
```
**Symbols:**

```
ffffffff8120bc00-ffffffff8120bcc7: is_hash_blacklisted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int is_hash_blacklisted(const u8 *hash, size_t hash_len, const char *type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In certs/blacklist.c (ffffffff81216790)
Location: certs/blacklist.c:109
Inline: False
Direct callers:
  - certs/blacklist.c:is_binary_blacklisted
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
```
**Symbols:**

```
ffffffff81216790-ffffffff81216857: is_hash_blacklisted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int is_hash_blacklisted(const u8 *hash, size_t hash_len, const char *type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In certs/blacklist.c (ffffffff81225810)
Location: certs/blacklist.c:109
Inline: False
Direct callers:
  - certs/blacklist.c:is_binary_blacklisted
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
```
**Symbols:**

```
ffffffff81225810-ffffffff812258d7: is_hash_blacklisted (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>enum blacklist_hash_type hash_type</code>
</li>
<li>
<b>Param removed. </b>
<code>const char *type</code>
</li>
</ul>
</details>
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
