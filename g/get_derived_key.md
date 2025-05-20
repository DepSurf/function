# Function: <code>get_derived_key</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int get_derived_key(u8 *derived_key, enum derived_key_type key_type, const u8 *master_key, size_t master_keylen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/encrypted-keys/encrypted.c (ffffffff813396a0)
Location: security/keys/encrypted-keys/encrypted.c:376
Inline: False
Direct callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:datablob_hmac_verify
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
```
**Symbols:**

```
ffffffff813396a0-ffffffff81339802: get_derived_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int get_derived_key(u8 *derived_key, enum derived_key_type key_type, const u8 *master_key, size_t master_keylen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/encrypted-keys/encrypted.c (ffffffff8136ed90)
Location: security/keys/encrypted-keys/encrypted.c:376
Inline: False
Direct callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
  - security/keys/encrypted-keys/encrypted.c:datablob_hmac_verify
```
**Symbols:**

```
ffffffff8136ed90-ffffffff8136eef2: get_derived_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int get_derived_key(u8 *derived_key, enum derived_key_type key_type, const u8 *master_key, size_t master_keylen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/encrypted-keys/encrypted.c (ffffffff813855c0)
Location: security/keys/encrypted-keys/encrypted.c:376
Inline: False
Direct callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
  - security/keys/encrypted-keys/encrypted.c:datablob_hmac_verify
```
**Symbols:**

```
ffffffff813855c0-ffffffff81385722: get_derived_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int get_derived_key(u8 *derived_key, enum derived_key_type key_type, const u8 *master_key, size_t master_keylen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/encrypted-keys/encrypted.c (ffffffff81399cd0)
Location: security/keys/encrypted-keys/encrypted.c:355
Inline: False
Direct callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
  - security/keys/encrypted-keys/encrypted.c:datablob_hmac_verify
```
**Symbols:**

```
ffffffff81399cd0-ffffffff81399f3d: get_derived_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int get_derived_key(u8 *derived_key, enum derived_key_type key_type, const u8 *master_key, size_t master_keylen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/encrypted-keys/encrypted.c (ffffffff813bf4a0)
Location: security/keys/encrypted-keys/encrypted.c:362
Inline: False
Direct callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
  - security/keys/encrypted-keys/encrypted.c:datablob_hmac_verify
```
**Symbols:**

```
ffffffff813bf4a0-ffffffff813bf5c2: get_derived_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int get_derived_key(u8 *derived_key, enum derived_key_type key_type, const u8 *master_key, size_t master_keylen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/encrypted-keys/encrypted.c (ffffffff813f0280)
Location: security/keys/encrypted-keys/encrypted.c:362
Inline: False
Direct callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
  - security/keys/encrypted-keys/encrypted.c:datablob_hmac_verify
```
**Symbols:**

```
ffffffff813f0280-ffffffff813f03a3: get_derived_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int get_derived_key(u8 *derived_key, enum derived_key_type key_type, const u8 *master_key, size_t master_keylen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/encrypted-keys/encrypted.c (ffffffff8140b560)
Location: security/keys/encrypted-keys/encrypted.c:366
Inline: False
Direct callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
  - security/keys/encrypted-keys/encrypted.c:datablob_hmac_verify
```
**Symbols:**

```
ffffffff8140b560-ffffffff8140b683: get_derived_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int get_derived_key(u8 *derived_key, enum derived_key_type key_type, const u8 *master_key, size_t master_keylen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/encrypted-keys/encrypted.c (ffffffff814382f0)
Location: security/keys/encrypted-keys/encrypted.c:362
Inline: False
Direct callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
  - security/keys/encrypted-keys/encrypted.c:datablob_hmac_verify
```
**Symbols:**

```
ffffffff814382f0-ffffffff814383ef: get_derived_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int get_derived_key(u8 *derived_key, enum derived_key_type key_type, const u8 *master_key, size_t master_keylen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/encrypted-keys/encrypted.c (ffffffff814520b0)
Location: security/keys/encrypted-keys/encrypted.c:362
Inline: False
Direct callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
  - security/keys/encrypted-keys/encrypted.c:datablob_hmac_verify
```
**Symbols:**

```
ffffffff814520b0-ffffffff814521af: get_derived_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int get_derived_key(u8 *derived_key, enum derived_key_type key_type, const u8 *master_key, size_t master_keylen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/encrypted-keys/encrypted.c (ffffffff814a4df0)
Location: security/keys/encrypted-keys/encrypted.c:349
Inline: False
Direct callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_key_decrypt
  - security/keys/encrypted-keys/encrypted.c:datablob_hmac_verify
```
**Symbols:**

```
ffffffff814a4df0-ffffffff814a4eb5: get_derived_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int get_derived_key(u8 *derived_key, enum derived_key_type key_type, const u8 *master_key, size_t master_keylen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/encrypted-keys/encrypted.c (ffffffff814c25f0)
Location: security/keys/encrypted-keys/encrypted.c:349
Inline: False
Direct callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_key_decrypt
  - security/keys/encrypted-keys/encrypted.c:datablob_hmac_verify
```
**Symbols:**

```
ffffffff814c25f0-ffffffff814c26b5: get_derived_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int get_derived_key(u8 *derived_key, enum derived_key_type key_type, const u8 *master_key, size_t master_keylen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/encrypted-keys/encrypted.c (ffffffff814c85a0)
Location: security/keys/encrypted-keys/encrypted.c:349
Inline: False
Direct callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_key_decrypt
  - security/keys/encrypted-keys/encrypted.c:datablob_hmac_verify
```
**Symbols:**

```
ffffffff814c85a0-ffffffff814c865f: get_derived_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int get_derived_key(u8 *derived_key, enum derived_key_type key_type, const u8 *master_key, size_t master_keylen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/encrypted-keys/encrypted.c (ffffffff81521090)
Location: security/keys/encrypted-keys/encrypted.c:349
Inline: False
Direct callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_key_decrypt
  - security/keys/encrypted-keys/encrypted.c:datablob_hmac_verify
```
**Symbols:**

```
ffffffff81521090-ffffffff8152114f: get_derived_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int get_derived_key(u8 *derived_key, enum derived_key_type key_type, const u8 *master_key, size_t master_keylen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/encrypted-keys/encrypted.c (ffffffff815b48b0)
Location: security/keys/encrypted-keys/encrypted.c:355
Inline: False
Direct callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_key_decrypt
  - security/keys/encrypted-keys/encrypted.c:datablob_hmac_verify
```
**Symbols:**

```
ffffffff815b48b0-ffffffff815b497c: get_derived_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int get_derived_key(u8 *derived_key, enum derived_key_type key_type, const u8 *master_key, size_t master_keylen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/encrypted-keys/encrypted.c (ffffffff8165f3b0)
Location: security/keys/encrypted-keys/encrypted.c:355
Inline: False
Direct callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_key_decrypt
  - security/keys/encrypted-keys/encrypted.c:datablob_hmac_verify
```
**Symbols:**

```
ffffffff8165f3b0-ffffffff8165f47c: get_derived_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int get_derived_key(u8 *derived_key, enum derived_key_type key_type, const u8 *master_key, size_t master_keylen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/encrypted-keys/encrypted.c (ffffffff81697d00)
Location: security/keys/encrypted-keys/encrypted.c:355
Inline: False
Direct callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_key_decrypt
  - security/keys/encrypted-keys/encrypted.c:datablob_hmac_verify
```
**Symbols:**

```
ffffffff81697d00-ffffffff81697df1: get_derived_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int get_derived_key(u8 *derived_key, enum derived_key_type key_type, const u8 *master_key, size_t master_keylen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/encrypted-keys/encrypted.c (ffffffff816d4830)
Location: security/keys/encrypted-keys/encrypted.c:355
Inline: False
Direct callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_key_decrypt
  - security/keys/encrypted-keys/encrypted.c:datablob_hmac_verify
```
**Symbols:**

```
ffffffff816d4830-ffffffff816d4921: get_derived_key (STB_LOCAL)
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
int get_derived_key(u8 *derived_key, enum derived_key_type key_type, const u8 *master_key, size_t master_keylen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/encrypted-keys/encrypted.c (ffff80001053d130)
Location: security/keys/encrypted-keys/encrypted.c:362
Inline: False
Direct callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
  - security/keys/encrypted-keys/encrypted.c:datablob_hmac_verify
```
**Symbols:**

```
ffff80001053d130-ffff80001053d214: get_derived_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int get_derived_key(u8 *derived_key, enum derived_key_type key_type, const u8 *master_key, size_t master_keylen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/encrypted-keys/encrypted.c (c06f3228)
Location: security/keys/encrypted-keys/encrypted.c:362
Inline: False
Direct callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
  - security/keys/encrypted-keys/encrypted.c:datablob_hmac_verify
```
**Symbols:**

```
c06f3228-c06f32f0: get_derived_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int get_derived_key(u8 *derived_key, enum derived_key_type key_type, const u8 *master_key, size_t master_keylen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/encrypted-keys/encrypted.c (c00000000068cdf0)
Location: security/keys/encrypted-keys/encrypted.c:362
Inline: False
Direct callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
  - security/keys/encrypted-keys/encrypted.c:datablob_hmac_verify
```
**Symbols:**

```
c00000000068cdf0-c00000000068cf24: get_derived_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int get_derived_key(u8 *derived_key, enum derived_key_type key_type, const u8 *master_key, size_t master_keylen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/encrypted-keys/encrypted.c (ffffffe00039af30)
Location: security/keys/encrypted-keys/encrypted.c:362
Inline: False
Direct callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
  - security/keys/encrypted-keys/encrypted.c:datablob_hmac_verify
```
**Symbols:**

```
ffffffe00039af30-ffffffe00039b002: get_derived_key (STB_LOCAL)
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
int get_derived_key(u8 *derived_key, enum derived_key_type key_type, const u8 *master_key, size_t master_keylen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/encrypted-keys/encrypted.c (ffffffff8144a690)
Location: security/keys/encrypted-keys/encrypted.c:362
Inline: False
Direct callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
  - security/keys/encrypted-keys/encrypted.c:datablob_hmac_verify
```
**Symbols:**

```
ffffffff8144a690-ffffffff8144a78f: get_derived_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int get_derived_key(u8 *derived_key, enum derived_key_type key_type, const u8 *master_key, size_t master_keylen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/encrypted-keys/encrypted.c (ffffffff8143b0e0)
Location: security/keys/encrypted-keys/encrypted.c:362
Inline: False
Direct callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
  - security/keys/encrypted-keys/encrypted.c:datablob_hmac_verify
```
**Symbols:**

```
ffffffff8143b0e0-ffffffff8143b1df: get_derived_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int get_derived_key(u8 *derived_key, enum derived_key_type key_type, const u8 *master_key, size_t master_keylen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/encrypted-keys/encrypted.c (ffffffff81446730)
Location: security/keys/encrypted-keys/encrypted.c:362
Inline: False
Direct callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
  - security/keys/encrypted-keys/encrypted.c:datablob_hmac_verify
```
**Symbols:**

```
ffffffff81446730-ffffffff8144682f: get_derived_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int get_derived_key(u8 *derived_key, enum derived_key_type key_type, const u8 *master_key, size_t master_keylen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/encrypted-keys/encrypted.c (ffffffff8145da60)
Location: security/keys/encrypted-keys/encrypted.c:362
Inline: False
Direct callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
  - security/keys/encrypted-keys/encrypted.c:datablob_hmac_verify
```
**Symbols:**

```
ffffffff8145da60-ffffffff8145db5f: get_derived_key (STB_LOCAL)
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
