# Function: <code>tpm_send</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int tpm_send(u32 chip_num, void *cmd, size_t buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff81523f60)
Location: drivers/char/tpm/tpm-interface.c:845
Inline: False
Direct callers:
  - security/keys/trusted.c:oiap
  - security/keys/trusted.c:tpm_unseal
  - security/keys/trusted.c:key_seal
  - security/keys/trusted.c:key_seal
```
**Symbols:**

```
ffffffff81523f60-ffffffff81523fbd: tpm_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int tpm_send(u32 chip_num, void *cmd, size_t buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff81576ea0)
Location: drivers/char/tpm/tpm-interface.c:873
Inline: False
Direct callers:
  - security/keys/trusted.c:key_seal
  - security/keys/trusted.c:key_seal
  - security/keys/trusted.c:tpm_unseal
```
**Symbols:**

```
ffffffff81576ea0-ffffffff81576ef3: tpm_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int tpm_send(u32 chip_num, void *cmd, size_t buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff815a3480)
Location: drivers/char/tpm/tpm-interface.c:858
Inline: False
Direct callers:
  - security/keys/trusted.c:key_seal
  - security/keys/trusted.c:key_seal
  - security/keys/trusted.c:tpm_unseal
```
**Symbols:**

```
ffffffff815a3480-ffffffff815a34d5: tpm_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int tpm_send(u32 chip_num, void *cmd, size_t buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff815b7500)
Location: drivers/char/tpm/tpm-interface.c:1022
Inline: False
Direct callers:
  - security/keys/trusted.c:key_seal
  - security/keys/trusted.c:key_seal
  - security/keys/trusted.c:tpm_unseal
```
**Symbols:**

```
ffffffff815b7500-ffffffff815b755e: tpm_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int tpm_send(u32 chip_num, void *cmd, size_t buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff8161e0e0)
Location: drivers/char/tpm/tpm-interface.c:1040
Inline: False
Direct callers:
  - security/keys/trusted.c:key_seal
  - security/keys/trusted.c:key_seal
  - security/keys/trusted.c:tpm_unseal
```
**Symbols:**

```
ffffffff8161e0e0-ffffffff8161e13e: tpm_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int tpm_send(struct tpm_chip *chip, void *cmd, size_t buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff81657df0)
Location: drivers/char/tpm/tpm-interface.c:1172
Inline: False
Direct callers:
  - security/keys/trusted.c:key_seal
  - security/keys/trusted.c:key_seal
  - security/keys/trusted.c:tpm_unseal
  - security/keys/trusted.c:oiap
```
**Symbols:**

```
ffffffff81657df0-ffffffff81657e4e: tpm_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int tpm_send(struct tpm_chip *chip, void *cmd, size_t buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff81676d70)
Location: drivers/char/tpm/tpm-interface.c:538
Inline: False
Direct callers:
  - security/keys/trusted.c:key_seal
  - security/keys/trusted.c:key_seal
  - security/keys/trusted.c:tpm_unseal
  - security/keys/trusted.c:oiap
```
**Symbols:**

```
ffffffff81676d70-ffffffff81676dce: tpm_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int tpm_send(struct tpm_chip *chip, void *cmd, size_t buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff816ac780)
Location: drivers/char/tpm/tpm-interface.c:348
Inline: False
Direct callers:
  - security/keys/trusted.c:tpm_unseal
  - security/keys/trusted.c:tpm_seal
  - security/keys/trusted.c:tpm_seal
```
**Symbols:**

```
ffffffff816ac780-ffffffff816ac87d: tpm_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int tpm_send(struct tpm_chip *chip, void *cmd, size_t buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff816cf4e0)
Location: drivers/char/tpm/tpm-interface.c:352
Inline: False
Direct callers:
  - security/keys/trusted.c:tpm_unseal
  - security/keys/trusted.c:tpm_seal
  - security/keys/trusted.c:tpm_seal
```
**Symbols:**

```
ffffffff816cf4e0-ffffffff816cf55f: tpm_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int tpm_send(struct tpm_chip *chip, void *cmd, size_t buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff81784370)
Location: drivers/char/tpm/tpm-interface.c:353
Inline: False
Direct callers:
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_unseal
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_seal
  - security/keys/trusted-keys/trusted_tpm1.c:oiap
  - security/keys/trusted-keys/trusted_tpm1.c:osap
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_unseal_cmd
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_load_cmd
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
```
**Symbols:**

```
ffffffff81784370-ffffffff817843ef: tpm_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int tpm_send(struct tpm_chip *chip, void *cmd, size_t buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff8179b8c0)
Location: drivers/char/tpm/tpm-interface.c:353
Inline: False
Direct callers:
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_unseal
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_seal
  - security/keys/trusted-keys/trusted_tpm1.c:oiap
  - security/keys/trusted-keys/trusted_tpm1.c:osap
```
**Symbols:**

```
ffffffff8179b8c0-ffffffff8179b93f: tpm_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int tpm_send(struct tpm_chip *chip, void *cmd, size_t buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff8177e3f0)
Location: drivers/char/tpm/tpm-interface.c:353
Inline: False
Direct callers:
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_unseal
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_seal
  - security/keys/trusted-keys/trusted_tpm1.c:oiap
  - security/keys/trusted-keys/trusted_tpm1.c:osap
```
**Symbols:**

```
ffffffff8177e3f0-ffffffff8177e46f: tpm_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int tpm_send(struct tpm_chip *chip, void *cmd, size_t buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff818045f0)
Location: drivers/char/tpm/tpm-interface.c:353
Inline: False
Direct callers:
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_unseal
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_seal
  - security/keys/trusted-keys/trusted_tpm1.c:oiap
  - security/keys/trusted-keys/trusted_tpm1.c:osap
```
**Symbols:**

```
ffffffff818045f0-ffffffff8180466f: tpm_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int tpm_send(struct tpm_chip *chip, void *cmd, size_t buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff81943fa0)
Location: drivers/char/tpm/tpm-interface.c:353
Inline: False
Direct callers:
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_unseal
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_seal
  - security/keys/trusted-keys/trusted_tpm1.c:oiap
  - security/keys/trusted-keys/trusted_tpm1.c:osap
```
**Symbols:**

```
ffffffff81943fa0-ffffffff81944037: tpm_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int tpm_send(struct tpm_chip *chip, void *cmd, size_t buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff81aa6c40)
Location: drivers/char/tpm/tpm-interface.c:353
Inline: False
Direct callers:
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_unseal
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_seal
  - security/keys/trusted-keys/trusted_tpm1.c:oiap
  - security/keys/trusted-keys/trusted_tpm1.c:osap
```
**Symbols:**

```
ffffffff81aa6c40-ffffffff81aa6cd7: tpm_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int tpm_send(struct tpm_chip *chip, void *cmd, size_t buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff81af2480)
Location: drivers/char/tpm/tpm-interface.c:353
Inline: False
Direct callers:
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_unseal
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_seal
  - security/keys/trusted-keys/trusted_tpm1.c:oiap
  - security/keys/trusted-keys/trusted_tpm1.c:osap
```
**Symbols:**

```
ffffffff81af2480-ffffffff81af2517: tpm_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int tpm_send(struct tpm_chip *chip, void *cmd, size_t buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff81b45a10)
Location: drivers/char/tpm/tpm-interface.c:353
Inline: False
Direct callers:
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_unseal
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_seal
  - security/keys/trusted-keys/trusted_tpm1.c:oiap
  - security/keys/trusted-keys/trusted_tpm1.c:osap
```
**Symbols:**

```
ffffffff81b45a10-ffffffff81b45aa7: tpm_send (STB_GLOBAL)
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
int tpm_send(struct tpm_chip *chip, void *cmd, size_t buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffff8000108b9ab0)
Location: drivers/char/tpm/tpm-interface.c:352
Inline: False
Direct callers:
  - security/keys/trusted.c:tpm_unseal
  - security/keys/trusted.c:tpm_seal
  - security/keys/trusted.c:tpm_seal
```
**Symbols:**

```
ffff8000108b9ab0-ffff8000108b9b4c: tpm_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int tpm_send(struct tpm_chip *chip, void *cmd, size_t buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (c09b2ecc)
Location: drivers/char/tpm/tpm-interface.c:352
Inline: False
Direct callers:
  - security/keys/trusted.c:tpm_unseal
  - security/keys/trusted.c:tpm_seal
  - security/keys/trusted.c:tpm_seal
```
**Symbols:**

```
c09b2ecc-c09b2f60: tpm_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int tpm_send(struct tpm_chip *chip, void *cmd, size_t buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (c00000000095ab50)
Location: drivers/char/tpm/tpm-interface.c:352
Inline: False
Direct callers:
  - security/keys/trusted.c:tpm_unseal
  - security/keys/trusted.c:tpm_seal
  - security/keys/trusted.c:tpm_seal
```
**Symbols:**

```
c00000000095ab50-c00000000095ac00: tpm_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int tpm_send(struct tpm_chip *chip, void *cmd, size_t buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffe000569f30)
Location: drivers/char/tpm/tpm-interface.c:352
Inline: False
Direct callers:
  - security/keys/trusted.c:tpm_unseal
  - security/keys/trusted.c:tpm_seal
  - security/keys/trusted.c:tpm_seal
```
**Symbols:**

```
ffffffe000569f30-ffffffe000569f94: tpm_send (STB_GLOBAL)
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
int tpm_send(struct tpm_chip *chip, void *cmd, size_t buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff81694f30)
Location: drivers/char/tpm/tpm-interface.c:352
Inline: False
Direct callers:
  - security/keys/trusted.c:tpm_unseal
  - security/keys/trusted.c:tpm_seal
  - security/keys/trusted.c:tpm_seal
```
**Symbols:**

```
ffffffff81694f30-ffffffff81694faf: tpm_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int tpm_send(struct tpm_chip *chip, void *cmd, size_t buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff81672920)
Location: drivers/char/tpm/tpm-interface.c:352
Inline: False
Direct callers:
  - security/keys/trusted.c:tpm_unseal
  - security/keys/trusted.c:tpm_seal
  - security/keys/trusted.c:tpm_seal
```
**Symbols:**

```
ffffffff81672920-ffffffff8167299f: tpm_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int tpm_send(struct tpm_chip *chip, void *cmd, size_t buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff816c31a0)
Location: drivers/char/tpm/tpm-interface.c:352
Inline: False
Direct callers:
  - security/keys/trusted.c:tpm_unseal
  - security/keys/trusted.c:tpm_seal
  - security/keys/trusted.c:tpm_seal
```
**Symbols:**

```
ffffffff816c31a0-ffffffff816c321f: tpm_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int tpm_send(struct tpm_chip *chip, void *cmd, size_t buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff816dd770)
Location: drivers/char/tpm/tpm-interface.c:352
Inline: False
Direct callers:
  - security/keys/trusted.c:tpm_unseal
  - security/keys/trusted.c:tpm_seal
  - security/keys/trusted.c:tpm_seal
```
**Symbols:**

```
ffffffff816dd770-ffffffff816dd7ef: tpm_send (STB_GLOBAL)
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
