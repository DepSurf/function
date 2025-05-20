# Function: <code>mark_hash_blacklisted</code>

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
int mark_hash_blacklisted(const char *hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In certs/blacklist.c (ffffffff811b5810)
Location: certs/blacklist.c:87
Inline: False
Direct callers:
  - certs/load_uefi.c:uefi_blacklist_binary
  - certs/load_uefi.c:uefi_blacklist_x509_tbs
```
**Symbols:**

```
ffffffff811b5810-ffffffff811b586d: mark_hash_blacklisted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int mark_hash_blacklisted(const char *hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In certs/blacklist.c (ffffffff811c9900)
Location: certs/blacklist.c:87
Inline: False
Direct callers:
  - certs/load_uefi.c:uefi_blacklist_binary
  - certs/load_uefi.c:uefi_blacklist_x509_tbs
```
**Symbols:**

```
ffffffff811c9900-ffffffff811c995d: mark_hash_blacklisted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int mark_hash_blacklisted(const char *hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In certs/blacklist.c (0)
Location: certs/blacklist.c:87
Inline: False
Direct callers:
  - certs/blacklist.c:blacklist_init
  - certs/load_uefi.c:uefi_blacklist_binary
  - certs/load_uefi.c:uefi_blacklist_x509_tbs
```
**Symbols:**

```
ffffffff811eaaa6-ffffffff811eaabf: mark_hash_blacklisted.cold.1 (STB_LOCAL)
ffffffff811eaa60-ffffffff811eaaa6: mark_hash_blacklisted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int mark_hash_blacklisted(const char *hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In certs/blacklist.c (0)
Location: certs/blacklist.c:87
Inline: False
Direct callers:
  - certs/blacklist.c:blacklist_init
  - certs/load_uefi.c:uefi_blacklist_binary
  - certs/load_uefi.c:uefi_blacklist_x509_tbs
```
**Symbols:**

```
ffffffff811fb616-ffffffff811fb62f: mark_hash_blacklisted.cold.1 (STB_LOCAL)
ffffffff811fb5d0-ffffffff811fb616: mark_hash_blacklisted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int mark_hash_blacklisted(const char *hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In certs/blacklist.c (0)
Location: certs/blacklist.c:83
Inline: False
Direct callers:
  - certs/blacklist.c:blacklist_init
```
**Symbols:**

```
ffffffff81212d06-ffffffff81212d1f: mark_hash_blacklisted.cold (STB_LOCAL)
ffffffff81212cc0-ffffffff81212d06: mark_hash_blacklisted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int mark_hash_blacklisted(const char *hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In certs/blacklist.c (0)
Location: certs/blacklist.c:83
Inline: False
Direct callers:
  - certs/blacklist.c:blacklist_init
```
**Symbols:**

```
ffffffff81220556-ffffffff8122056f: mark_hash_blacklisted.cold (STB_LOCAL)
ffffffff81220510-ffffffff81220556: mark_hash_blacklisted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int mark_hash_blacklisted(const char *hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In certs/blacklist.c (0)
Location: certs/blacklist.c:83
Inline: False
Direct callers:
  - certs/blacklist.c:blacklist_init
```
**Symbols:**

```
ffffffff8124d976-ffffffff8124d98f: mark_hash_blacklisted.cold (STB_LOCAL)
ffffffff8124d930-ffffffff8124d976: mark_hash_blacklisted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int mark_hash_blacklisted(const char *hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In certs/blacklist.c (0)
Location: certs/blacklist.c:83
Inline: False
Direct callers:
  - certs/blacklist.c:blacklist_init
```
**Symbols:**

```
ffffffff81be6982-ffffffff81be699b: mark_hash_blacklisted.cold (STB_LOCAL)
ffffffff81257d70-ffffffff81257db6: mark_hash_blacklisted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int mark_hash_blacklisted(const char *hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In certs/blacklist.c (0)
Location: certs/blacklist.c:90
Inline: False
Direct callers:
  - certs/blacklist.c:blacklist_init
```
**Symbols:**

```
ffffffff81bd86e6-ffffffff81bd86ff: mark_hash_blacklisted.cold (STB_LOCAL)
ffffffff8125c280-ffffffff8125c2c6: mark_hash_blacklisted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int mark_hash_blacklisted(const char *hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In certs/blacklist.c (0)
Location: certs/blacklist.c:90
Inline: False
Direct callers:
  - certs/blacklist.c:blacklist_init
```
**Symbols:**

```
ffffffff81cb9d3d-ffffffff81cb9d56: mark_hash_blacklisted.cold (STB_LOCAL)
ffffffff81298130-ffffffff81298176: mark_hash_blacklisted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int mark_hash_blacklisted(const u8 *hash, size_t hash_len, enum blacklist_hash_type hash_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In certs/blacklist.c (0)
Location: certs/blacklist.c:201
Inline: False
Direct callers:
  - security/integrity/platform_certs/keyring_handler.c:uefi_blacklist_binary
  - security/integrity/platform_certs/keyring_handler.c:uefi_blacklist_x509_tbs
```
**Symbols:**

```
ffffffff81e6b330-ffffffff81e6b344: mark_hash_blacklisted.cold (STB_LOCAL)
ffffffff812ee670-ffffffff812ee70e: mark_hash_blacklisted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int mark_hash_blacklisted(const u8 *hash, size_t hash_len, enum blacklist_hash_type hash_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In certs/blacklist.c (ffffffff81358b40)
Location: certs/blacklist.c:201
Inline: False
Direct callers:
  - security/integrity/platform_certs/keyring_handler.c:uefi_blacklist_binary
  - security/integrity/platform_certs/keyring_handler.c:uefi_blacklist_x509_tbs
```
**Symbols:**

```
ffffffff81358b40-ffffffff81358bd4: mark_hash_blacklisted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int mark_hash_blacklisted(const u8 *hash, size_t hash_len, enum blacklist_hash_type hash_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In certs/blacklist.c (ffffffff8138a4b0)
Location: certs/blacklist.c:204
Inline: False
Direct callers:
  - security/integrity/platform_certs/keyring_handler.c:uefi_blacklist_binary
  - security/integrity/platform_certs/keyring_handler.c:uefi_blacklist_x509_tbs
```
**Symbols:**

```
ffffffff8138a4b0-ffffffff8138a4f4: mark_hash_blacklisted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int mark_hash_blacklisted(const u8 *hash, size_t hash_len, enum blacklist_hash_type hash_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In certs/blacklist.c (ffffffff813b3fd0)
Location: certs/blacklist.c:204
Inline: False
Direct callers:
  - security/integrity/platform_certs/keyring_handler.c:uefi_blacklist_binary
  - security/integrity/platform_certs/keyring_handler.c:uefi_blacklist_x509_tbs
```
**Symbols:**

```
ffffffff813b3fd0-ffffffff813b4014: mark_hash_blacklisted (STB_GLOBAL)
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
int mark_hash_blacklisted(const char *hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In certs/blacklist.c (ffff8000102ad820)
Location: certs/blacklist.c:83
Inline: False
Direct callers:
  - certs/blacklist.c:blacklist_init
```
**Symbols:**

```
ffff8000102ad820-ffff8000102ad898: mark_hash_blacklisted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int mark_hash_blacklisted(const char *hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In certs/blacklist.c (c04da150)
Location: certs/blacklist.c:83
Inline: False
Direct callers:
  - certs/blacklist.c:blacklist_init
```
**Symbols:**

```
c04da150-c04da1d4: mark_hash_blacklisted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int mark_hash_blacklisted(const char *hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In certs/blacklist.c (c000000000361590)
Location: certs/blacklist.c:83
Inline: False
Direct callers:
  - certs/blacklist.c:blacklist_init
```
**Symbols:**

```
c000000000361590-c000000000361624: mark_hash_blacklisted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int mark_hash_blacklisted(const char *hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In certs/blacklist.c (ffffffe0001d3c72)
Location: certs/blacklist.c:83
Inline: False
Direct callers:
  - certs/blacklist.c:blacklist_init
```
**Symbols:**

```
ffffffe0001d3c72-ffffffe0001d3cdc: mark_hash_blacklisted (STB_GLOBAL)
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
int mark_hash_blacklisted(const char *hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In certs/blacklist.c (0)
Location: certs/blacklist.c:83
Inline: False
Direct callers:
  - certs/blacklist.c:blacklist_init
```
**Symbols:**

```
ffffffff81218ba6-ffffffff81218bbf: mark_hash_blacklisted.cold (STB_LOCAL)
ffffffff81218b60-ffffffff81218ba6: mark_hash_blacklisted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int mark_hash_blacklisted(const char *hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In certs/blacklist.c (0)
Location: certs/blacklist.c:83
Inline: False
Direct callers:
  - certs/blacklist.c:blacklist_init
```
**Symbols:**

```
ffffffff8120bdb6-ffffffff8120bdcf: mark_hash_blacklisted.cold (STB_LOCAL)
ffffffff8120bd70-ffffffff8120bdb6: mark_hash_blacklisted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int mark_hash_blacklisted(const char *hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In certs/blacklist.c (0)
Location: certs/blacklist.c:83
Inline: False
Direct callers:
  - certs/blacklist.c:blacklist_init
```
**Symbols:**

```
ffffffff81216946-ffffffff8121695f: mark_hash_blacklisted.cold (STB_LOCAL)
ffffffff81216900-ffffffff81216946: mark_hash_blacklisted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int mark_hash_blacklisted(const char *hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In certs/blacklist.c (0)
Location: certs/blacklist.c:83
Inline: False
Direct callers:
  - certs/blacklist.c:blacklist_init
```
**Symbols:**

```
ffffffff812259c6-ffffffff812259df: mark_hash_blacklisted.cold (STB_LOCAL)
ffffffff81225980-ffffffff812259c6: mark_hash_blacklisted (STB_GLOBAL)
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
<code>size_t hash_len</code>
</li>
<li>
<b>Param added. </b>
<code>enum blacklist_hash_type hash_type</code>
</li>
<li>
<b>Param type changed. </b>
<code>const char *hash</code> ➡️ <code>const u8 *hash</code>
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
