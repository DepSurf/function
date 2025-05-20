# Function: <code>TSS_checkhmac1</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/keys/trusted.c (ffffffff81337220)
Location: security/keys/trusted.c:175
Inline: True
Direct callers:
  - security/keys/trusted.c:key_seal
```
**Symbols:**

```
ffffffff81337220-ffffffff81337487: TSS_checkhmac1.constprop.7 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/keys/trusted.c (ffffffff8136c820)
Location: security/keys/trusted.c:175
Inline: True
Direct callers:
  - security/keys/trusted.c:key_seal
```
**Symbols:**

```
ffffffff8136c820-ffffffff8136ca93: TSS_checkhmac1.constprop.9 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/keys/trusted.c (ffffffff81383040)
Location: security/keys/trusted.c:175
Inline: True
Direct callers:
  - security/keys/trusted.c:key_seal
```
**Symbols:**

```
ffffffff81383040-ffffffff813832b3: TSS_checkhmac1.constprop.9 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/keys/trusted.c (ffffffff81397700)
Location: security/keys/trusted.c:175
Inline: True
Direct callers:
  - security/keys/trusted.c:key_seal
```
**Symbols:**

```
ffffffff81397700-ffffffff81397969: TSS_checkhmac1.constprop.8 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/keys/trusted.c (ffffffff813bcef0)
Location: security/keys/trusted.c:175
Inline: True
Direct callers:
  - security/keys/trusted.c:key_seal
```
**Symbols:**

```
ffffffff813bcef0-ffffffff813bd16a: TSS_checkhmac1.constprop.8 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/keys/trusted.c (0)
Location: security/keys/trusted.c:175
Inline: True
Direct callers:
  - security/keys/trusted.c:key_seal
```
**Symbols:**

```
ffffffff813edc70-ffffffff813edee3: TSS_checkhmac1.constprop.6 (STB_LOCAL)
ffffffff813ef1ba-ffffffff813ef1d4: TSS_checkhmac1.constprop.6.cold.14 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int TSS_checkhmac1(unsigned char *buffer, const uint32_t command, const unsigned char *ononce, const unsigned char *key, unsigned int keylen, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/keys/trusted.c (0)
Location: security/keys/trusted.c:176
Inline: False
Direct callers:
  - security/keys/trusted.c:key_seal
```
**Symbols:**

```
ffffffff8140a3f6-ffffffff8140a410: TSS_checkhmac1.cold.11 (STB_LOCAL)
ffffffff81408900-ffffffff81408b7c: TSS_checkhmac1 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int TSS_checkhmac1(unsigned char *buffer, const uint32_t command, const unsigned char *ononce, const unsigned char *key, unsigned int keylen, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/keys/trusted.c (0)
Location: security/keys/trusted.c:177
Inline: False
Direct callers:
  - security/keys/trusted.c:tpm_seal
```
**Symbols:**

```
ffffffff81437663-ffffffff8143767e: TSS_checkhmac1.cold (STB_LOCAL)
ffffffff814360e0-ffffffff81436378: TSS_checkhmac1 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int TSS_checkhmac1(unsigned char *buffer, const uint32_t command, const unsigned char *ononce, const unsigned char *key, unsigned int keylen, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/keys/trusted.c (0)
Location: security/keys/trusted.c:177
Inline: False
Direct callers:
  - security/keys/trusted.c:tpm_seal
```
**Symbols:**

```
ffffffff81451411-ffffffff8145142c: TSS_checkhmac1.cold (STB_LOCAL)
ffffffff8144fe80-ffffffff81450118: TSS_checkhmac1 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int TSS_checkhmac1(unsigned char *buffer, const uint32_t command, const unsigned char *ononce, const unsigned char *key, unsigned int keylen, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/keys/trusted-keys/trusted_tpm1.c (0)
Location: security/keys/trusted-keys/trusted_tpm1.c:177
Inline: False
Direct callers:
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_seal
```
**Symbols:**

```
ffffffff814a305c-ffffffff814a3077: TSS_checkhmac1.cold (STB_LOCAL)
ffffffff814a1950-ffffffff814a1bd4: TSS_checkhmac1 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int TSS_checkhmac1(unsigned char *buffer, const uint32_t command, const unsigned char *ononce, const unsigned char *key, unsigned int keylen, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/keys/trusted-keys/trusted_tpm1.c (0)
Location: security/keys/trusted-keys/trusted_tpm1.c:177
Inline: False
Direct callers:
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_seal
```
**Symbols:**

```
ffffffff81befcac-ffffffff81befcc7: TSS_checkhmac1.cold (STB_LOCAL)
ffffffff814bf310-ffffffff814bf594: TSS_checkhmac1 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int TSS_checkhmac1(unsigned char *buffer, const uint32_t command, const unsigned char *ononce, const unsigned char *key, unsigned int keylen, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/keys/trusted-keys/trusted_tpm1.c (0)
Location: security/keys/trusted-keys/trusted_tpm1.c:170
Inline: False
Direct callers:
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_seal
```
**Symbols:**

```
ffffffff81be1d81-ffffffff81be1d9c: TSS_checkhmac1.cold (STB_LOCAL)
ffffffff814c5570-ffffffff814c57f4: TSS_checkhmac1 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int TSS_checkhmac1(unsigned char *buffer, const uint32_t command, const unsigned char *ononce, const unsigned char *key, unsigned int keylen, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/keys/trusted-keys/trusted_tpm1.c (0)
Location: security/keys/trusted-keys/trusted_tpm1.c:170
Inline: False
Direct callers:
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_seal
```
**Symbols:**

```
ffffffff81cd2ff2-ffffffff81cd300d: TSS_checkhmac1.cold (STB_LOCAL)
ffffffff8151df90-ffffffff8151e214: TSS_checkhmac1 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int TSS_checkhmac1(unsigned char *buffer, const uint32_t command, const unsigned char *ononce, const unsigned char *key, unsigned int keylen, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/keys/trusted-keys/trusted_tpm1.c (0)
Location: security/keys/trusted-keys/trusted_tpm1.c:170
Inline: False
Direct callers:
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_seal
```
**Symbols:**

```
ffffffff81e8618c-ffffffff81e861a7: TSS_checkhmac1.cold (STB_LOCAL)
ffffffff815b1460-ffffffff815b174b: TSS_checkhmac1 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int TSS_checkhmac1(unsigned char *buffer, const uint32_t command, const unsigned char *ononce, const unsigned char *key, unsigned int keylen, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/trusted-keys/trusted_tpm1.c (ffffffff8165bf60)
Location: security/keys/trusted-keys/trusted_tpm1.c:170
Inline: False
Direct callers:
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_seal
```
**Symbols:**

```
ffffffff8165bf60-ffffffff8165c266: TSS_checkhmac1 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int TSS_checkhmac1(unsigned char *buffer, const uint32_t command, const unsigned char *ononce, const unsigned char *key, unsigned int keylen, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/trusted-keys/trusted_tpm1.c (ffffffff81694880)
Location: security/keys/trusted-keys/trusted_tpm1.c:170
Inline: False
Direct callers:
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_seal
```
**Symbols:**

```
ffffffff81694880-ffffffff81694b86: TSS_checkhmac1 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int TSS_checkhmac1(unsigned char *buffer, const uint32_t command, const unsigned char *ononce, const unsigned char *key, unsigned int keylen, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/trusted-keys/trusted_tpm1.c (ffffffff816d0eb0)
Location: security/keys/trusted-keys/trusted_tpm1.c:170
Inline: False
Direct callers:
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_seal
```
**Symbols:**

```
ffffffff816d0eb0-ffffffff816d11b6: TSS_checkhmac1 (STB_GLOBAL)
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
int TSS_checkhmac1(unsigned char *buffer, const uint32_t command, const unsigned char *ononce, const unsigned char *key, unsigned int keylen, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/trusted.c (ffff80001053a878)
Location: security/keys/trusted.c:177
Inline: False
Direct callers:
  - security/keys/trusted.c:tpm_seal
```
**Symbols:**

```
ffff80001053a878-ffff80001053ab68: TSS_checkhmac1 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int TSS_checkhmac1(unsigned char *buffer, const uint32_t command, const unsigned char *ononce, const unsigned char *key, unsigned int keylen, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/trusted.c (c06f1098)
Location: security/keys/trusted.c:177
Inline: False
Direct callers:
  - security/keys/trusted.c:tpm_seal
```
**Symbols:**

```
c06f1098-c06f12b4: TSS_checkhmac1 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int TSS_checkhmac1(unsigned char *buffer, const uint32_t command, const unsigned char *ononce, const unsigned char *key, unsigned int keylen, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/trusted.c (c00000000068a100)
Location: security/keys/trusted.c:177
Inline: False
Direct callers:
  - security/keys/trusted.c:tpm_seal
```
**Symbols:**

```
c00000000068a100-c00000000068a43c: TSS_checkhmac1 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int TSS_checkhmac1(unsigned char *buffer, const uint32_t command, const unsigned char *ononce, const unsigned char *key, unsigned int keylen, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/trusted.c (ffffffe0003988e2)
Location: security/keys/trusted.c:177
Inline: False
Direct callers:
  - security/keys/trusted.c:tpm_seal
```
**Symbols:**

```
ffffffe0003988e2-ffffffe000398abc: TSS_checkhmac1 (STB_GLOBAL)
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
int TSS_checkhmac1(unsigned char *buffer, const uint32_t command, const unsigned char *ononce, const unsigned char *key, unsigned int keylen, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/keys/trusted.c (0)
Location: security/keys/trusted.c:177
Inline: False
Direct callers:
  - security/keys/trusted.c:tpm_seal
```
**Symbols:**

```
ffffffff814499f1-ffffffff81449a0c: TSS_checkhmac1.cold (STB_LOCAL)
ffffffff81448460-ffffffff814486f8: TSS_checkhmac1 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int TSS_checkhmac1(unsigned char *buffer, const uint32_t command, const unsigned char *ononce, const unsigned char *key, unsigned int keylen, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/keys/trusted.c (0)
Location: security/keys/trusted.c:177
Inline: False
Direct callers:
  - security/keys/trusted.c:tpm_seal
```
**Symbols:**

```
ffffffff8143a441-ffffffff8143a45c: TSS_checkhmac1.cold (STB_LOCAL)
ffffffff81438eb0-ffffffff81439148: TSS_checkhmac1 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int TSS_checkhmac1(unsigned char *buffer, const uint32_t command, const unsigned char *ononce, const unsigned char *key, unsigned int keylen, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/keys/trusted.c (0)
Location: security/keys/trusted.c:177
Inline: False
Direct callers:
  - security/keys/trusted.c:tpm_seal
```
**Symbols:**

```
ffffffff81445a91-ffffffff81445aac: TSS_checkhmac1.cold (STB_LOCAL)
ffffffff81444500-ffffffff81444798: TSS_checkhmac1 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int TSS_checkhmac1(unsigned char *buffer, const uint32_t command, const unsigned char *ononce, const unsigned char *key, unsigned int keylen, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/keys/trusted.c (0)
Location: security/keys/trusted.c:177
Inline: False
Direct callers:
  - security/keys/trusted.c:tpm_seal
```
**Symbols:**

```
ffffffff8145cdc1-ffffffff8145cddc: TSS_checkhmac1.cold (STB_LOCAL)
ffffffff8145b830-ffffffff8145bac8: TSS_checkhmac1 (STB_GLOBAL)
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
