# Function: <code>derive_essiv_salt</code>

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
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/crypto/keyinfo.c (ffffffff812adf53)
Location: fs/crypto/keyinfo.c:185
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/crypto/keyinfo.c (ffffffff812d1437)
Location: fs/crypto/keyinfo.c:176
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/crypto/keyinfo.c (ffffffff812fbe76)
Location: fs/crypto/keyinfo.c:221
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int derive_essiv_salt(const u8 *key, int keysize, u8 *salt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/keyinfo.c (0)
Location: fs/crypto/keyinfo.c:380
Inline: False
```
**Symbols:**

```
ffffffff81310c50-ffffffff81310d3c: derive_essiv_salt (STB_LOCAL)
ffffffff81311840-ffffffff8131185f: derive_essiv_salt.cold.16 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int derive_essiv_salt(const u8 *key, int keysize, u8 *salt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/keyinfo.c (0)
Location: fs/crypto/keyinfo.c:379
Inline: False
```
**Symbols:**

```
ffffffff813381a0-ffffffff8133827f: derive_essiv_salt (STB_LOCAL)
ffffffff81338d36-ffffffff81338d56: derive_essiv_salt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int derive_essiv_salt(const u8 *key, int keysize, u8 *salt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/keysetup.c (0)
Location: fs/crypto/keysetup.c:114
Inline: False
Direct callers:
  - fs/crypto/keysetup.c:fscrypt_set_derived_key
```
**Symbols:**

```
ffffffff8134d4c0-ffffffff8134d59f: derive_essiv_salt (STB_LOCAL)
ffffffff8134df99-ffffffff8134dfde: derive_essiv_salt.cold (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int derive_essiv_salt(const u8 *key, int keysize, u8 *salt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup.c (ffff80001040e7a0)
Location: fs/crypto/keysetup.c:114
Inline: False
Direct callers:
  - fs/crypto/keysetup.c:fscrypt_set_derived_key
```
**Symbols:**

```
ffff80001040e7a0-ffff80001040e8f8: derive_essiv_salt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int derive_essiv_salt(const u8 *key, int keysize, u8 *salt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup.c (c05db2b0)
Location: fs/crypto/keysetup.c:114
Inline: False
Direct callers:
  - fs/crypto/keysetup.c:fscrypt_set_derived_key
```
**Symbols:**

```
c05db2b0-c05db404: derive_essiv_salt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int derive_essiv_salt(const u8 *key, int keysize, u8 *salt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup.c (c00000000051b9f0)
Location: fs/crypto/keysetup.c:114
Inline: False
Direct callers:
  - fs/crypto/keysetup.c:fscrypt_set_derived_key
```
**Symbols:**

```
c00000000051b9f0-c00000000051bb98: derive_essiv_salt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int derive_essiv_salt(const u8 *key, int keysize, u8 *salt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup.c (ffffffe0002b75b4)
Location: fs/crypto/keysetup.c:114
Inline: False
Direct callers:
  - fs/crypto/keysetup.c:fscrypt_set_derived_key
```
**Symbols:**

```
ffffffe0002b75b4-ffffffe0002b769a: derive_essiv_salt (STB_LOCAL)
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
int derive_essiv_salt(const u8 *key, int keysize, u8 *salt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/keysetup.c (0)
Location: fs/crypto/keysetup.c:114
Inline: False
Direct callers:
  - fs/crypto/keysetup.c:fscrypt_set_derived_key
```
**Symbols:**

```
ffffffff81345aa0-ffffffff81345b7f: derive_essiv_salt (STB_LOCAL)
ffffffff81346579-ffffffff813465be: derive_essiv_salt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int derive_essiv_salt(const u8 *key, int keysize, u8 *salt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/keysetup.c (0)
Location: fs/crypto/keysetup.c:114
Inline: False
Direct callers:
  - fs/crypto/keysetup.c:fscrypt_set_derived_key
```
**Symbols:**

```
ffffffff81336780-ffffffff8133685f: derive_essiv_salt (STB_LOCAL)
ffffffff81337259-ffffffff8133729e: derive_essiv_salt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int derive_essiv_salt(const u8 *key, int keysize, u8 *salt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/keysetup.c (0)
Location: fs/crypto/keysetup.c:114
Inline: False
Direct callers:
  - fs/crypto/keysetup.c:fscrypt_set_derived_key
```
**Symbols:**

```
ffffffff81343570-ffffffff8134364f: derive_essiv_salt (STB_LOCAL)
ffffffff81344049-ffffffff8134408e: derive_essiv_salt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int derive_essiv_salt(const u8 *key, int keysize, u8 *salt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/keysetup.c (0)
Location: fs/crypto/keysetup.c:114
Inline: False
Direct callers:
  - fs/crypto/keysetup.c:fscrypt_set_derived_key
```
**Symbols:**

```
ffffffff81356850-ffffffff8135692f: derive_essiv_salt (STB_LOCAL)
ffffffff81357327-ffffffff8135736c: derive_essiv_salt.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
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
