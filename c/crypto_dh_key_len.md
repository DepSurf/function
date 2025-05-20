# Function: <code>crypto_dh_key_len</code>

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
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int crypto_dh_key_len(const struct dh *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/dh_helper.c (ffffffff81405252)
Location: crypto/dh_helper.c:36
Inline: True
Inline callers:
  - crypto/dh_helper.c:crypto_dh_decode_key
  - crypto/dh_helper.c:crypto_dh_encode_key
Direct callers:
  - security/keys/dh.c:__keyctl_dh_compute
```
**Symbols:**

```
ffffffff81405200-ffffffff81405218: crypto_dh_key_len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
unsigned int crypto_dh_key_len(const struct dh *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/dh_helper.c (ffffffff8142db1e)
Location: crypto/dh_helper.c:36
Inline: True
Inline callers:
  - crypto/dh_helper.c:crypto_dh_decode_key
  - crypto/dh_helper.c:crypto_dh_encode_key
Direct callers:
  - security/keys/dh.c:__keyctl_dh_compute
```
**Symbols:**

```
ffffffff8142dad0-ffffffff8142dae8: crypto_dh_key_len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
unsigned int crypto_dh_key_len(const struct dh *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/dh_helper.c (ffffffff814607a9)
Location: crypto/dh_helper.c:36
Inline: True
Inline callers:
  - crypto/dh_helper.c:crypto_dh_decode_key
  - crypto/dh_helper.c:crypto_dh_encode_key
Direct callers:
  - security/keys/dh.c:__keyctl_dh_compute
```
**Symbols:**

```
ffffffff81460750-ffffffff81460768: crypto_dh_key_len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
unsigned int crypto_dh_key_len(const struct dh *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/dh_helper.c (ffffffff8147e2fc)
Location: crypto/dh_helper.c:38
Inline: True
Inline callers:
  - crypto/dh_helper.c:crypto_dh_decode_key
Direct callers:
  - security/keys/dh.c:__keyctl_dh_compute
```
**Symbols:**

```
ffffffff8147e290-ffffffff8147e2ab: crypto_dh_key_len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
unsigned int crypto_dh_key_len(const struct dh *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/dh_helper.c (ffffffff814ac608)
Location: crypto/dh_helper.c:34
Inline: True
Inline callers:
  - crypto/dh_helper.c:crypto_dh_decode_key
Direct callers:
  - security/keys/dh.c:__keyctl_dh_compute
```
**Symbols:**

```
ffffffff814ac590-ffffffff814ac5ab: crypto_dh_key_len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
unsigned int crypto_dh_key_len(const struct dh *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/dh_helper.c (ffffffff814c72b8)
Location: crypto/dh_helper.c:34
Inline: True
Inline callers:
  - crypto/dh_helper.c:crypto_dh_decode_key
Direct callers:
  - security/keys/dh.c:__keyctl_dh_compute
```
**Symbols:**

```
ffffffff814c7240-ffffffff814c725b: crypto_dh_key_len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
unsigned int crypto_dh_key_len(const struct dh *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/dh_helper.c (ffffffff815265a8)
Location: crypto/dh_helper.c:34
Inline: True
Inline callers:
  - crypto/dh_helper.c:crypto_dh_decode_key
Direct callers:
  - security/keys/dh.c:__keyctl_dh_compute
```
**Symbols:**

```
ffffffff81526530-ffffffff8152654b: crypto_dh_key_len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
unsigned int crypto_dh_key_len(const struct dh *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/dh_helper.c (ffffffff81543548)
Location: crypto/dh_helper.c:34
Inline: True
Inline callers:
  - crypto/dh_helper.c:crypto_dh_decode_key
Direct callers:
  - security/keys/dh.c:__keyctl_dh_compute
```
**Symbols:**

```
ffffffff815434d0-ffffffff815434eb: crypto_dh_key_len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
unsigned int crypto_dh_key_len(const struct dh *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/dh_helper.c (ffffffff8154bba8)
Location: crypto/dh_helper.c:34
Inline: True
Inline callers:
  - crypto/dh_helper.c:crypto_dh_decode_key
Direct callers:
  - security/keys/dh.c:__keyctl_dh_compute
```
**Symbols:**

```
ffffffff8154bb30-ffffffff8154bb4b: crypto_dh_key_len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
unsigned int crypto_dh_key_len(const struct dh *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/dh_helper.c (ffffffff815ac388)
Location: crypto/dh_helper.c:34
Inline: True
Inline callers:
  - crypto/dh_helper.c:crypto_dh_decode_key
Direct callers:
  - security/keys/dh.c:__keyctl_dh_compute
```
**Symbols:**

```
ffffffff815ac310-ffffffff815ac32b: crypto_dh_key_len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
unsigned int crypto_dh_key_len(const struct dh *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/dh_helper.c (ffffffff81654781)
Location: crypto/dh_helper.c:34
Inline: True
Inline callers:
  - crypto/dh_helper.c:__crypto_dh_decode_key
Direct callers:
  - security/keys/dh.c:__keyctl_dh_compute
  - crypto/dh.c:dh_safe_prime_set_secret
```
**Symbols:**

```
ffffffff816545c0-ffffffff816545e0: crypto_dh_key_len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
unsigned int crypto_dh_key_len(const struct dh *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/dh_helper.c (ffffffff8170e7d4)
Location: crypto/dh_helper.c:34
Inline: True
Inline callers:
  - crypto/dh_helper.c:__crypto_dh_decode_key
Direct callers:
  - security/keys/dh.c:__keyctl_dh_compute
  - crypto/dh.c:dh_safe_prime_set_secret
```
**Symbols:**

```
ffffffff8170e5b0-ffffffff8170e5d0: crypto_dh_key_len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
unsigned int crypto_dh_key_len(const struct dh *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/dh_helper.c (ffffffff81749139)
Location: crypto/dh_helper.c:34
Inline: True
Inline callers:
  - crypto/dh_helper.c:__crypto_dh_decode_key
Direct callers:
  - security/keys/dh.c:__keyctl_dh_compute
  - crypto/dh.c:dh_safe_prime_set_secret
```
**Symbols:**

```
ffffffff81748f00-ffffffff81748f20: crypto_dh_key_len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
unsigned int crypto_dh_key_len(const struct dh *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/dh_helper.c (ffffffff8178afd9)
Location: crypto/dh_helper.c:34
Inline: True
Inline callers:
  - crypto/dh_helper.c:__crypto_dh_decode_key
Direct callers:
  - security/keys/dh.c:__keyctl_dh_compute
  - crypto/dh.c:dh_safe_prime_set_secret
```
**Symbols:**

```
ffffffff8178ada0-ffffffff8178adc0: crypto_dh_key_len (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
unsigned int crypto_dh_key_len(const struct dh *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/dh_helper.c (ffff8000105c2a08)
Location: crypto/dh_helper.c:34
Inline: True
Inline callers:
  - crypto/dh_helper.c:crypto_dh_decode_key
Direct callers:
  - security/keys/dh.c:__keyctl_dh_compute
```
**Symbols:**

```
ffff8000105c2958-ffff8000105c2994: crypto_dh_key_len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
unsigned int crypto_dh_key_len(const struct dh *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/dh_helper.c (c076fe04)
Location: crypto/dh_helper.c:34
Inline: True
Inline callers:
  - crypto/dh_helper.c:crypto_dh_decode_key
Direct callers:
  - security/keys/dh.c:__keyctl_dh_compute
```
**Symbols:**

```
c076fd54-c076fd8c: crypto_dh_key_len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
unsigned int crypto_dh_key_len(const struct dh *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/dh_helper.c (c00000000074b384)
Location: crypto/dh_helper.c:34
Inline: True
Inline callers:
  - crypto/dh_helper.c:crypto_dh_decode_key
Direct callers:
  - security/keys/dh.c:__keyctl_dh_compute
```
**Symbols:**

```
c00000000074b2e0-c00000000074b310: crypto_dh_key_len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
unsigned int crypto_dh_key_len(const struct dh *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/dh_helper.c (ffffffe0004075b0)
Location: crypto/dh_helper.c:34
Inline: True
Inline callers:
  - crypto/dh_helper.c:crypto_dh_decode_key
Direct callers:
  - security/keys/dh.c:__keyctl_dh_compute
```
**Symbols:**

```
ffffffe0004072e6-ffffffe000407316: crypto_dh_key_len (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
unsigned int crypto_dh_key_len(const struct dh *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/dh_helper.c (ffffffff814bf898)
Location: crypto/dh_helper.c:34
Inline: True
Inline callers:
  - crypto/dh_helper.c:crypto_dh_decode_key
Direct callers:
  - security/keys/dh.c:__keyctl_dh_compute
```
**Symbols:**

```
ffffffff814bf820-ffffffff814bf83b: crypto_dh_key_len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
unsigned int crypto_dh_key_len(const struct dh *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/dh_helper.c (ffffffff814b02b8)
Location: crypto/dh_helper.c:34
Inline: True
Inline callers:
  - crypto/dh_helper.c:crypto_dh_decode_key
Direct callers:
  - security/keys/dh.c:__keyctl_dh_compute
```
**Symbols:**

```
ffffffff814b0240-ffffffff814b025b: crypto_dh_key_len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
unsigned int crypto_dh_key_len(const struct dh *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/dh_helper.c (ffffffff814bb928)
Location: crypto/dh_helper.c:34
Inline: True
Inline callers:
  - crypto/dh_helper.c:crypto_dh_decode_key
Direct callers:
  - security/keys/dh.c:__keyctl_dh_compute
```
**Symbols:**

```
ffffffff814bb8b0-ffffffff814bb8cb: crypto_dh_key_len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
unsigned int crypto_dh_key_len(const struct dh *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/dh_helper.c (ffffffff814d43f8)
Location: crypto/dh_helper.c:34
Inline: True
Inline callers:
  - crypto/dh_helper.c:crypto_dh_decode_key
Direct callers:
  - security/keys/dh.c:__keyctl_dh_compute
```
**Symbols:**

```
ffffffff814d4380-ffffffff814d439b: crypto_dh_key_len (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>unsigned int</code>
</li>
</ul>
</details>
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
