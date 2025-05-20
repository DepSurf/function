# Function: <code>TSS_rawhmac</code>

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
In security/keys/trusted.c (ffffffff81336ee0)
Location: security/keys/trusted.c:77
Inline: True
Direct callers:
  - security/keys/trusted.c:key_seal
```
**Symbols:**

```
ffffffff81336ee0-ffffffff8133704c: TSS_rawhmac.constprop.9 (STB_LOCAL)
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
In security/keys/trusted.c (ffffffff8136c4f0)
Location: security/keys/trusted.c:77
Inline: True
Direct callers:
  - security/keys/trusted.c:key_seal
```
**Symbols:**

```
ffffffff8136c4f0-ffffffff8136c655: TSS_rawhmac.constprop.11 (STB_LOCAL)
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
In security/keys/trusted.c (ffffffff81382d10)
Location: security/keys/trusted.c:77
Inline: True
Direct callers:
  - security/keys/trusted.c:key_seal
```
**Symbols:**

```
ffffffff81382d10-ffffffff81382e75: TSS_rawhmac.constprop.11 (STB_LOCAL)
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
In security/keys/trusted.c (ffffffff813973b0)
Location: security/keys/trusted.c:77
Inline: True
Direct callers:
  - security/keys/trusted.c:key_seal
```
**Symbols:**

```
ffffffff813973b0-ffffffff8139751f: TSS_rawhmac.constprop.10 (STB_LOCAL)
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
In security/keys/trusted.c (ffffffff813bcb90)
Location: security/keys/trusted.c:77
Inline: True
Direct callers:
  - security/keys/trusted.c:key_seal
```
**Symbols:**

```
ffffffff813bcb90-ffffffff813bccfe: TSS_rawhmac.constprop.10 (STB_LOCAL)
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
Location: security/keys/trusted.c:77
Inline: True
Direct callers:
  - security/keys/trusted.c:key_seal
```
**Symbols:**

```
ffffffff813ed920-ffffffff813eda92: TSS_rawhmac.constprop.8 (STB_LOCAL)
ffffffff813ef186-ffffffff813ef1a0: TSS_rawhmac.constprop.8.cold.12 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int TSS_rawhmac(unsigned char *digest, const unsigned char *key, unsigned int keylen, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/keys/trusted.c (0)
Location: security/keys/trusted.c:77
Inline: False
Direct callers:
  - security/keys/trusted.c:key_seal
  - security/keys/trusted.c:TSS_checkhmac1
  - security/keys/trusted.c:TSS_authhmac
```
**Symbols:**

```
ffffffff814085a0-ffffffff81408717: TSS_rawhmac (STB_LOCAL)
ffffffff8140a3c2-ffffffff8140a3dc: TSS_rawhmac.cold.9 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int TSS_rawhmac(unsigned char *digest, const unsigned char *key, unsigned int keylen, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/keys/trusted.c (0)
Location: security/keys/trusted.c:75
Inline: False
Direct callers:
  - security/keys/trusted.c:tpm_seal
  - security/keys/trusted.c:TSS_checkhmac1
  - security/keys/trusted.c:TSS_authhmac
```
**Symbols:**

```
ffffffff81435d50-ffffffff81435ed6: TSS_rawhmac (STB_LOCAL)
ffffffff8143762d-ffffffff81437648: TSS_rawhmac.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int TSS_rawhmac(unsigned char *digest, const unsigned char *key, unsigned int keylen, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/keys/trusted.c (0)
Location: security/keys/trusted.c:75
Inline: False
Direct callers:
  - security/keys/trusted.c:tpm_seal
  - security/keys/trusted.c:TSS_checkhmac1
  - security/keys/trusted.c:TSS_authhmac
```
**Symbols:**

```
ffffffff8144faf0-ffffffff8144fc76: TSS_rawhmac (STB_LOCAL)
ffffffff814513db-ffffffff814513f6: TSS_rawhmac.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int TSS_rawhmac(unsigned char *digest, const unsigned char *key, unsigned int keylen, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/keys/trusted-keys/trusted_tpm1.c (0)
Location: security/keys/trusted-keys/trusted_tpm1.c:75
Inline: False
Direct callers:
  - security/keys/trusted-keys/trusted_tpm1.c:osap
  - security/keys/trusted-keys/trusted_tpm1.c:TSS_checkhmac1
  - security/keys/trusted-keys/trusted_tpm1.c:TSS_authhmac
```
**Symbols:**

```
ffffffff814a12a0-ffffffff814a1426: TSS_rawhmac (STB_LOCAL)
ffffffff814a300b-ffffffff814a3026: TSS_rawhmac.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int TSS_rawhmac(unsigned char *digest, const unsigned char *key, unsigned int keylen, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/keys/trusted-keys/trusted_tpm1.c (0)
Location: security/keys/trusted-keys/trusted_tpm1.c:75
Inline: False
Direct callers:
  - security/keys/trusted-keys/trusted_tpm1.c:osap
  - security/keys/trusted-keys/trusted_tpm1.c:TSS_checkhmac1
  - security/keys/trusted-keys/trusted_tpm1.c:TSS_authhmac
```
**Symbols:**

```
ffffffff814bec60-ffffffff814bede6: TSS_rawhmac (STB_LOCAL)
ffffffff81befc5b-ffffffff81befc76: TSS_rawhmac.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int TSS_rawhmac(unsigned char *digest, const unsigned char *key, unsigned int keylen, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/keys/trusted-keys/trusted_tpm1.c (0)
Location: security/keys/trusted-keys/trusted_tpm1.c:68
Inline: False
Direct callers:
  - security/keys/trusted-keys/trusted_tpm1.c:osap
  - security/keys/trusted-keys/trusted_tpm1.c:TSS_checkhmac1
  - security/keys/trusted-keys/trusted_tpm1.c:TSS_authhmac
```
**Symbols:**

```
ffffffff814c4ec0-ffffffff814c5046: TSS_rawhmac (STB_LOCAL)
ffffffff81be1d30-ffffffff81be1d4b: TSS_rawhmac.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int TSS_rawhmac(unsigned char *digest, const unsigned char *key, unsigned int keylen, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/keys/trusted-keys/trusted_tpm1.c (0)
Location: security/keys/trusted-keys/trusted_tpm1.c:68
Inline: False
Direct callers:
  - security/keys/trusted-keys/trusted_tpm1.c:osap
  - security/keys/trusted-keys/trusted_tpm1.c:TSS_checkhmac1
  - security/keys/trusted-keys/trusted_tpm1.c:TSS_authhmac
```
**Symbols:**

```
ffffffff8151d8e0-ffffffff8151da66: TSS_rawhmac (STB_LOCAL)
ffffffff81cd2fa1-ffffffff81cd2fbc: TSS_rawhmac.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int TSS_rawhmac(unsigned char *digest, const unsigned char *key, unsigned int keylen, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/keys/trusted-keys/trusted_tpm1.c (0)
Location: security/keys/trusted-keys/trusted_tpm1.c:68
Inline: False
Direct callers:
  - security/keys/trusted-keys/trusted_tpm1.c:osap
  - security/keys/trusted-keys/trusted_tpm1.c:TSS_checkhmac1
  - security/keys/trusted-keys/trusted_tpm1.c:TSS_authhmac
```
**Symbols:**

```
ffffffff815b0cc0-ffffffff815b0e64: TSS_rawhmac (STB_LOCAL)
ffffffff81e8613c-ffffffff81e86157: TSS_rawhmac.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int TSS_rawhmac(unsigned char *digest, const unsigned char *key, unsigned int keylen, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/trusted-keys/trusted_tpm1.c (ffffffff8165b750)
Location: security/keys/trusted-keys/trusted_tpm1.c:68
Inline: False
Direct callers:
  - security/keys/trusted-keys/trusted_tpm1.c:osap
  - security/keys/trusted-keys/trusted_tpm1.c:TSS_checkhmac1
  - security/keys/trusted-keys/trusted_tpm1.c:TSS_authhmac
```
**Symbols:**

```
ffffffff8165b750-ffffffff8165b90d: TSS_rawhmac (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int TSS_rawhmac(unsigned char *digest, const unsigned char *key, unsigned int keylen, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/trusted-keys/trusted_tpm1.c (ffffffff81694070)
Location: security/keys/trusted-keys/trusted_tpm1.c:68
Inline: False
Direct callers:
  - security/keys/trusted-keys/trusted_tpm1.c:osap
  - security/keys/trusted-keys/trusted_tpm1.c:TSS_checkhmac1
  - security/keys/trusted-keys/trusted_tpm1.c:TSS_authhmac
```
**Symbols:**

```
ffffffff81694070-ffffffff8169422d: TSS_rawhmac (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int TSS_rawhmac(unsigned char *digest, const unsigned char *key, unsigned int keylen, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/trusted-keys/trusted_tpm1.c (ffffffff816d06a0)
Location: security/keys/trusted-keys/trusted_tpm1.c:68
Inline: False
Direct callers:
  - security/keys/trusted-keys/trusted_tpm1.c:osap
  - security/keys/trusted-keys/trusted_tpm1.c:TSS_checkhmac1
  - security/keys/trusted-keys/trusted_tpm1.c:TSS_authhmac
```
**Symbols:**

```
ffffffff816d06a0-ffffffff816d085d: TSS_rawhmac (STB_LOCAL)
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
int TSS_rawhmac(unsigned char *digest, const unsigned char *key, unsigned int keylen, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/trusted.c (ffff80001053a488)
Location: security/keys/trusted.c:75
Inline: False
Direct callers:
  - security/keys/trusted.c:tpm_seal
  - security/keys/trusted.c:TSS_checkhmac1
  - security/keys/trusted.c:TSS_authhmac
```
**Symbols:**

```
ffff80001053a488-ffff80001053a644: TSS_rawhmac (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int TSS_rawhmac(unsigned char *digest, const unsigned char *key, unsigned int keylen, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/trusted.c (c06f0da8)
Location: security/keys/trusted.c:75
Inline: False
Direct callers:
  - security/keys/trusted.c:tpm_seal
  - security/keys/trusted.c:TSS_checkhmac1
  - security/keys/trusted.c:TSS_authhmac
```
**Symbols:**

```
c06f0da8-c06f0ef0: TSS_rawhmac (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int TSS_rawhmac(unsigned char *digest, const unsigned char *key, unsigned int keylen, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/trusted.c (c000000000689d10)
Location: security/keys/trusted.c:75
Inline: False
Direct callers:
  - security/keys/trusted.c:tpm_seal
  - security/keys/trusted.c:TSS_checkhmac1
  - security/keys/trusted.c:TSS_authhmac
```
**Symbols:**

```
c000000000689d10-c000000000689ea4: TSS_rawhmac (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int TSS_rawhmac(unsigned char *digest, const unsigned char *key, unsigned int keylen, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/trusted.c (ffffffe0003986aa)
Location: security/keys/trusted.c:75
Inline: False
Direct callers:
  - security/keys/trusted.c:tpm_seal
  - security/keys/trusted.c:TSS_checkhmac1
  - security/keys/trusted.c:TSS_authhmac
```
**Symbols:**

```
ffffffe0003986aa-ffffffe0003987ae: TSS_rawhmac (STB_LOCAL)
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
int TSS_rawhmac(unsigned char *digest, const unsigned char *key, unsigned int keylen, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/keys/trusted.c (0)
Location: security/keys/trusted.c:75
Inline: False
Direct callers:
  - security/keys/trusted.c:tpm_seal
  - security/keys/trusted.c:TSS_checkhmac1
  - security/keys/trusted.c:TSS_authhmac
```
**Symbols:**

```
ffffffff814480d0-ffffffff81448256: TSS_rawhmac (STB_LOCAL)
ffffffff814499bb-ffffffff814499d6: TSS_rawhmac.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int TSS_rawhmac(unsigned char *digest, const unsigned char *key, unsigned int keylen, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/keys/trusted.c (0)
Location: security/keys/trusted.c:75
Inline: False
Direct callers:
  - security/keys/trusted.c:tpm_seal
  - security/keys/trusted.c:TSS_checkhmac1
  - security/keys/trusted.c:TSS_authhmac
```
**Symbols:**

```
ffffffff81438b20-ffffffff81438ca6: TSS_rawhmac (STB_LOCAL)
ffffffff8143a40b-ffffffff8143a426: TSS_rawhmac.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int TSS_rawhmac(unsigned char *digest, const unsigned char *key, unsigned int keylen, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/keys/trusted.c (0)
Location: security/keys/trusted.c:75
Inline: False
Direct callers:
  - security/keys/trusted.c:tpm_seal
  - security/keys/trusted.c:TSS_checkhmac1
  - security/keys/trusted.c:TSS_authhmac
```
**Symbols:**

```
ffffffff81444170-ffffffff814442f6: TSS_rawhmac (STB_LOCAL)
ffffffff81445a5b-ffffffff81445a76: TSS_rawhmac.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int TSS_rawhmac(unsigned char *digest, const unsigned char *key, unsigned int keylen, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/keys/trusted.c (0)
Location: security/keys/trusted.c:75
Inline: False
Direct callers:
  - security/keys/trusted.c:tpm_seal
  - security/keys/trusted.c:TSS_checkhmac1
  - security/keys/trusted.c:TSS_authhmac
```
**Symbols:**

```
ffffffff8145b4a0-ffffffff8145b626: TSS_rawhmac (STB_LOCAL)
ffffffff8145cd8b-ffffffff8145cda6: TSS_rawhmac.cold (STB_LOCAL)
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
