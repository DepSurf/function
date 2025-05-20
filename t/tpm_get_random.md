# Function: <code>tpm_get_random</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int tpm_get_random(u32 chip_num, u8 *out, size_t max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff81524170)
Location: drivers/char/tpm/tpm-interface.c:1021
Inline: False
Direct callers:
  - security/keys/trusted.c:pcrlock
  - security/keys/trusted.c:tpm_unseal
  - security/keys/trusted.c:key_seal
  - security/keys/trusted.c:key_seal
  - security/keys/trusted.c:trusted_instantiate
```
**Symbols:**

```
ffffffff81524170-ffffffff81524323: tpm_get_random (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int tpm_get_random(u32 chip_num, u8 *out, size_t max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff81577100)
Location: drivers/char/tpm/tpm-interface.c:1049
Inline: False
Direct callers:
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:key_seal
  - security/keys/trusted.c:key_seal
  - security/keys/trusted.c:tpm_unseal
  - security/keys/trusted.c:pcrlock
```
**Symbols:**

```
ffffffff81577100-ffffffff81577298: tpm_get_random (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int tpm_get_random(u32 chip_num, u8 *out, size_t max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff815a36f0)
Location: drivers/char/tpm/tpm-interface.c:1035
Inline: False
Direct callers:
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:key_seal
  - security/keys/trusted.c:key_seal
  - security/keys/trusted.c:tpm_unseal
  - security/keys/trusted.c:pcrlock
```
**Symbols:**

```
ffffffff815a36f0-ffffffff815a388e: tpm_get_random (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int tpm_get_random(u32 chip_num, u8 *out, size_t max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff815b76c0)
Location: drivers/char/tpm/tpm-interface.c:1197
Inline: False
Direct callers:
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:key_seal
  - security/keys/trusted.c:key_seal
  - security/keys/trusted.c:tpm_unseal
  - security/keys/trusted.c:pcrlock
```
**Symbols:**

```
ffffffff815b76c0-ffffffff815b7894: tpm_get_random (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int tpm_get_random(u32 chip_num, u8 *out, size_t max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff8161e2a0)
Location: drivers/char/tpm/tpm-interface.c:1215
Inline: False
Direct callers:
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:key_seal
  - security/keys/trusted.c:key_seal
  - security/keys/trusted.c:tpm_unseal
  - security/keys/trusted.c:pcrlock
```
**Symbols:**

```
ffffffff8161e2a0-ffffffff8161e47f: tpm_get_random (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int tpm_get_random(struct tpm_chip *chip, u8 *out, size_t max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (0)
Location: drivers/char/tpm/tpm-interface.c:1286
Inline: False
Direct callers:
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:key_seal
  - security/keys/trusted.c:key_seal
  - security/keys/trusted.c:tpm_unseal
  - security/keys/trusted.c:pcrlock
  - drivers/char/tpm/tpm-chip.c:tpm_hwrng_read
```
**Symbols:**

```
ffffffff8165891e-ffffffff8165892a: tpm_get_random.cold.7 (STB_LOCAL)
ffffffff81657fb0-ffffffff81658182: tpm_get_random (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int tpm_get_random(struct tpm_chip *chip, u8 *out, size_t max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff81676400)
Location: drivers/char/tpm/tpm-interface.c:615
Inline: False
Direct callers:
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:key_seal
  - security/keys/trusted.c:key_seal
  - security/keys/trusted.c:tpm_unseal
  - security/keys/trusted.c:pcrlock
  - drivers/char/tpm/tpm-chip.c:tpm_hwrng_read
```
**Symbols:**

```
ffffffff81676400-ffffffff81676470: tpm_get_random (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int tpm_get_random(struct tpm_chip *chip, u8 *out, size_t max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff816ac1d0)
Location: drivers/char/tpm/tpm-interface.c:436
Inline: False
Direct callers:
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:tpm_unseal
  - security/keys/trusted.c:tpm_seal
  - security/keys/trusted.c:tpm_seal
  - drivers/char/tpm/tpm-chip.c:tpm_hwrng_read
```
**Symbols:**

```
ffffffff816ac1d0-ffffffff816ac247: tpm_get_random (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int tpm_get_random(struct tpm_chip *chip, u8 *out, size_t max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff816cef30)
Location: drivers/char/tpm/tpm-interface.c:435
Inline: False
Direct callers:
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:tpm_unseal
  - security/keys/trusted.c:tpm_seal
  - security/keys/trusted.c:tpm_seal
  - drivers/char/tpm/tpm-chip.c:tpm_hwrng_read
```
**Symbols:**

```
ffffffff816cef30-ffffffff816cefa7: tpm_get_random (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int tpm_get_random(struct tpm_chip *chip, u8 *out, size_t max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff81783e40)
Location: drivers/char/tpm/tpm-interface.c:441
Inline: False
Direct callers:
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_instantiate
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_unseal
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_seal
  - security/keys/trusted-keys/trusted_tpm1.c:osap
  - drivers/char/tpm/tpm-chip.c:tpm_hwrng_read
```
**Symbols:**

```
ffffffff81783e40-ffffffff81783eb7: tpm_get_random (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int tpm_get_random(struct tpm_chip *chip, u8 *out, size_t max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff8179b390)
Location: drivers/char/tpm/tpm-interface.c:441
Inline: False
Direct callers:
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_instantiate
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_unseal
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_seal
  - security/keys/trusted-keys/trusted_tpm1.c:osap
  - drivers/char/tpm/tpm-chip.c:tpm_hwrng_read
```
**Symbols:**

```
ffffffff8179b390-ffffffff8179b407: tpm_get_random (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int tpm_get_random(struct tpm_chip *chip, u8 *out, size_t max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff8177ded0)
Location: drivers/char/tpm/tpm-interface.c:441
Inline: False
Direct callers:
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_get_random
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_unseal
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_seal
  - security/keys/trusted-keys/trusted_tpm1.c:osap
  - drivers/char/tpm/tpm-chip.c:tpm_hwrng_read
```
**Symbols:**

```
ffffffff8177ded0-ffffffff8177df47: tpm_get_random (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int tpm_get_random(struct tpm_chip *chip, u8 *out, size_t max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff818040c0)
Location: drivers/char/tpm/tpm-interface.c:441
Inline: False
Direct callers:
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_get_random
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_unseal
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_seal
  - security/keys/trusted-keys/trusted_tpm1.c:osap
  - drivers/char/tpm/tpm-chip.c:tpm_hwrng_read
```
**Symbols:**

```
ffffffff818040c0-ffffffff81804137: tpm_get_random (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int tpm_get_random(struct tpm_chip *chip, u8 *out, size_t max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff819439f0)
Location: drivers/char/tpm/tpm-interface.c:441
Inline: False
Direct callers:
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_get_random
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_unseal
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_seal
  - security/keys/trusted-keys/trusted_tpm1.c:osap
  - drivers/char/tpm/tpm-chip.c:tpm_hwrng_read
```
**Symbols:**

```
ffffffff819439f0-ffffffff81943a6f: tpm_get_random (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int tpm_get_random(struct tpm_chip *chip, u8 *out, size_t max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff81aa6510)
Location: drivers/char/tpm/tpm-interface.c:444
Inline: False
Direct callers:
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_get_random
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_unseal
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_seal
  - security/keys/trusted-keys/trusted_tpm1.c:osap
  - drivers/char/tpm/tpm-chip.c:tpm_hwrng_read
```
**Symbols:**

```
ffffffff81aa6510-ffffffff81aa658f: tpm_get_random (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int tpm_get_random(struct tpm_chip *chip, u8 *out, size_t max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff81af1d60)
Location: drivers/char/tpm/tpm-interface.c:454
Inline: False
Direct callers:
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_get_random
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_unseal
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_seal
  - security/keys/trusted-keys/trusted_tpm1.c:osap
  - drivers/char/tpm/tpm-chip.c:tpm_hwrng_read
```
**Symbols:**

```
ffffffff81af1d60-ffffffff81af1ddf: tpm_get_random (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int tpm_get_random(struct tpm_chip *chip, u8 *out, size_t max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff81b452f0)
Location: drivers/char/tpm/tpm-interface.c:454
Inline: False
Direct callers:
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_get_random
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_unseal
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_seal
  - security/keys/trusted-keys/trusted_tpm1.c:osap
  - drivers/char/tpm/tpm-chip.c:tpm_hwrng_read
```
**Symbols:**

```
ffffffff81b452f0-ffffffff81b4536f: tpm_get_random (STB_GLOBAL)
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
int tpm_get_random(struct tpm_chip *chip, u8 *out, size_t max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffff8000108b9530)
Location: drivers/char/tpm/tpm-interface.c:435
Inline: False
Direct callers:
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:tpm_unseal
  - security/keys/trusted.c:tpm_seal
  - security/keys/trusted.c:tpm_seal
  - drivers/char/tpm/tpm-chip.c:tpm_hwrng_read
```
**Symbols:**

```
ffff8000108b9530-ffff8000108b95c4: tpm_get_random (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int tpm_get_random(struct tpm_chip *chip, u8 *out, size_t max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (c09b2980)
Location: drivers/char/tpm/tpm-interface.c:435
Inline: False
Direct callers:
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:tpm_unseal
  - security/keys/trusted.c:tpm_seal
  - security/keys/trusted.c:tpm_seal
  - drivers/char/tpm/tpm-chip.c:tpm_hwrng_read
```
**Symbols:**

```
c09b2980-c09b2a0c: tpm_get_random (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int tpm_get_random(struct tpm_chip *chip, u8 *out, size_t max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (c00000000095a3d0)
Location: drivers/char/tpm/tpm-interface.c:435
Inline: False
Direct callers:
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:tpm_unseal
  - security/keys/trusted.c:tpm_seal
  - security/keys/trusted.c:tpm_seal
  - drivers/char/tpm/tpm-chip.c:tpm_hwrng_read
```
**Symbols:**

```
c00000000095a3d0-c00000000095a4ac: tpm_get_random (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int tpm_get_random(struct tpm_chip *chip, u8 *out, size_t max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffe00056992a)
Location: drivers/char/tpm/tpm-interface.c:435
Inline: False
Direct callers:
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:tpm_unseal
  - security/keys/trusted.c:tpm_seal
  - security/keys/trusted.c:tpm_seal
  - drivers/char/tpm/tpm-chip.c:tpm_hwrng_read
```
**Symbols:**

```
ffffffe00056992a-ffffffe0005699a6: tpm_get_random (STB_GLOBAL)
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
int tpm_get_random(struct tpm_chip *chip, u8 *out, size_t max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff81694980)
Location: drivers/char/tpm/tpm-interface.c:435
Inline: False
Direct callers:
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:tpm_unseal
  - security/keys/trusted.c:tpm_seal
  - security/keys/trusted.c:tpm_seal
  - drivers/char/tpm/tpm-chip.c:tpm_hwrng_read
```
**Symbols:**

```
ffffffff81694980-ffffffff816949f7: tpm_get_random (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int tpm_get_random(struct tpm_chip *chip, u8 *out, size_t max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff81672370)
Location: drivers/char/tpm/tpm-interface.c:435
Inline: False
Direct callers:
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:tpm_unseal
  - security/keys/trusted.c:tpm_seal
  - security/keys/trusted.c:tpm_seal
  - drivers/char/tpm/tpm-chip.c:tpm_hwrng_read
```
**Symbols:**

```
ffffffff81672370-ffffffff816723e7: tpm_get_random (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int tpm_get_random(struct tpm_chip *chip, u8 *out, size_t max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff816c2bf0)
Location: drivers/char/tpm/tpm-interface.c:435
Inline: False
Direct callers:
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:tpm_unseal
  - security/keys/trusted.c:tpm_seal
  - security/keys/trusted.c:tpm_seal
  - drivers/char/tpm/tpm-chip.c:tpm_hwrng_read
```
**Symbols:**

```
ffffffff816c2bf0-ffffffff816c2c67: tpm_get_random (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int tpm_get_random(struct tpm_chip *chip, u8 *out, size_t max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff816dd1c0)
Location: drivers/char/tpm/tpm-interface.c:435
Inline: False
Direct callers:
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:tpm_unseal
  - security/keys/trusted.c:tpm_seal
  - security/keys/trusted.c:tpm_seal
  - drivers/char/tpm/tpm-chip.c:tpm_hwrng_read
```
**Symbols:**

```
ffffffff816dd1c0-ffffffff816dd237: tpm_get_random (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct tpm_chip *chip</code>
</li>
<li>
<b>Param removed. </b>
<code>u32 chip_num</code>
</li>
</ul>
</details>
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
