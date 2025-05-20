# Function: <code>calc_hash</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/encrypted-keys/encrypted.c (ffffffff8133974b)
Location: security/keys/encrypted-keys/encrypted.c:357
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:get_derived_key
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/encrypted-keys/encrypted.c (ffffffff8136ee3b)
Location: security/keys/encrypted-keys/encrypted.c:357
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:get_derived_key
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/encrypted-keys/encrypted.c (ffffffff8138566b)
Location: security/keys/encrypted-keys/encrypted.c:357
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:get_derived_key
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int calc_hash(struct crypto_shash *tfm, u8 *digest, const u8 *buf, unsigned int buflen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/encrypted-keys/encrypted.c (ffffffff81398cc0)
Location: security/keys/encrypted-keys/encrypted.c:318
Inline: False
Direct callers:
  - security/keys/encrypted-keys/encrypted.c:get_derived_key
```
**Symbols:**

```
ffffffff81398cc0-ffffffff81398d64: calc_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int calc_hash(struct crypto_shash *tfm, u8 *digest, const u8 *buf, unsigned int buflen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/encrypted-keys/encrypted.c (ffffffff813be4d0)
Location: security/keys/encrypted-keys/encrypted.c:325
Inline: False
Direct callers:
  - security/keys/encrypted-keys/encrypted.c:get_derived_key
```
**Symbols:**

```
ffffffff813be4d0-ffffffff813be574: calc_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int calc_hash(struct crypto_shash *tfm, u8 *digest, const u8 *buf, unsigned int buflen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/encrypted-keys/encrypted.c (ffffffff813ef3e0)
Location: security/keys/encrypted-keys/encrypted.c:325
Inline: False
Direct callers:
  - security/keys/encrypted-keys/encrypted.c:get_derived_key
```
**Symbols:**

```
ffffffff813ef3e0-ffffffff813ef484: calc_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int calc_hash(struct crypto_shash *tfm, u8 *digest, const u8 *buf, unsigned int buflen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/encrypted-keys/encrypted.c (ffffffff8140a650)
Location: security/keys/encrypted-keys/encrypted.c:329
Inline: False
Direct callers:
  - security/keys/encrypted-keys/encrypted.c:get_derived_key
```
**Symbols:**

```
ffffffff8140a650-ffffffff8140a6d3: calc_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int calc_hash(struct crypto_shash *tfm, u8 *digest, const u8 *buf, unsigned int buflen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/encrypted-keys/encrypted.c (ffffffff81437870)
Location: security/keys/encrypted-keys/encrypted.c:326
Inline: False
Direct callers:
  - security/keys/encrypted-keys/encrypted.c:get_derived_key
```
**Symbols:**

```
ffffffff81437870-ffffffff814378ed: calc_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int calc_hash(struct crypto_shash *tfm, u8 *digest, const u8 *buf, unsigned int buflen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/keys/encrypted-keys/encrypted.c (0)
Location: security/keys/encrypted-keys/encrypted.c:326
Inline: False
Direct callers:
  - security/keys/encrypted-keys/encrypted.c:get_derived_key
```
**Symbols:**

```
ffffffff81451a40-ffffffff81451acd: calc_hash (STB_LOCAL)
ffffffff81452dfe-ffffffff81452e0a: calc_hash.cold (STB_LOCAL)
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
int calc_hash(struct crypto_shash *tfm, u8 *digest, const u8 *buf, unsigned int buflen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/encrypted-keys/encrypted.c (ffff80001053cfa0)
Location: security/keys/encrypted-keys/encrypted.c:326
Inline: False
Direct callers:
  - security/keys/encrypted-keys/encrypted.c:get_derived_key
```
**Symbols:**

```
ffff80001053cfa0-ffff80001053d068: calc_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int calc_hash(struct crypto_shash *tfm, u8 *digest, const u8 *buf, unsigned int buflen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/encrypted-keys/encrypted.c (c06f2c20)
Location: security/keys/encrypted-keys/encrypted.c:326
Inline: False
Direct callers:
  - security/keys/encrypted-keys/encrypted.c:get_derived_key
```
**Symbols:**

```
c06f2c20-c06f2cd0: calc_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int calc_hash(struct crypto_shash *tfm, u8 *digest, const u8 *buf, unsigned int buflen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/encrypted-keys/encrypted.c (c00000000068c620)
Location: security/keys/encrypted-keys/encrypted.c:326
Inline: False
Direct callers:
  - security/keys/encrypted-keys/encrypted.c:get_derived_key
```
**Symbols:**

```
c00000000068c620-c00000000068c6ec: calc_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int calc_hash(struct crypto_shash *tfm, u8 *digest, const u8 *buf, unsigned int buflen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/encrypted-keys/encrypted.c (ffffffe00039a22e)
Location: security/keys/encrypted-keys/encrypted.c:326
Inline: False
Direct callers:
  - security/keys/encrypted-keys/encrypted.c:get_derived_key
```
**Symbols:**

```
ffffffe00039a22e-ffffffe00039a296: calc_hash (STB_LOCAL)
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
int calc_hash(struct crypto_shash *tfm, u8 *digest, const u8 *buf, unsigned int buflen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/keys/encrypted-keys/encrypted.c (0)
Location: security/keys/encrypted-keys/encrypted.c:326
Inline: False
Direct callers:
  - security/keys/encrypted-keys/encrypted.c:get_derived_key
```
**Symbols:**

```
ffffffff8144a020-ffffffff8144a0ad: calc_hash (STB_LOCAL)
ffffffff8144b3de-ffffffff8144b3ea: calc_hash.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int calc_hash(struct crypto_shash *tfm, u8 *digest, const u8 *buf, unsigned int buflen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/keys/encrypted-keys/encrypted.c (0)
Location: security/keys/encrypted-keys/encrypted.c:326
Inline: False
Direct callers:
  - security/keys/encrypted-keys/encrypted.c:get_derived_key
```
**Symbols:**

```
ffffffff8143aa70-ffffffff8143aafd: calc_hash (STB_LOCAL)
ffffffff8143be2e-ffffffff8143be3a: calc_hash.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int calc_hash(struct crypto_shash *tfm, u8 *digest, const u8 *buf, unsigned int buflen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/keys/encrypted-keys/encrypted.c (0)
Location: security/keys/encrypted-keys/encrypted.c:326
Inline: False
Direct callers:
  - security/keys/encrypted-keys/encrypted.c:get_derived_key
```
**Symbols:**

```
ffffffff814460c0-ffffffff8144614d: calc_hash (STB_LOCAL)
ffffffff8144747e-ffffffff8144748a: calc_hash.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int calc_hash(struct crypto_shash *tfm, u8 *digest, const u8 *buf, unsigned int buflen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/keys/encrypted-keys/encrypted.c (0)
Location: security/keys/encrypted-keys/encrypted.c:326
Inline: False
Direct callers:
  - security/keys/encrypted-keys/encrypted.c:get_derived_key
```
**Symbols:**

```
ffffffff8145d3f0-ffffffff8145d47d: calc_hash (STB_LOCAL)
ffffffff8145e7ae-ffffffff8145e7ba: calc_hash.cold (STB_LOCAL)
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
