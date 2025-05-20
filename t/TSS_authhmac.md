# Function: <code>TSS_authhmac</code>

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
In security/keys/trusted.c (ffffffff81337050)
Location: security/keys/trusted.c:124
Inline: True
Direct callers:
  - security/keys/trusted.c:tpm_unseal
  - security/keys/trusted.c:tpm_unseal
  - security/keys/trusted.c:key_seal
  - security/keys/trusted.c:key_seal
```
**Symbols:**

```
ffffffff81337050-ffffffff81337219: TSS_authhmac.constprop.8 (STB_LOCAL)
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
In security/keys/trusted.c (ffffffff8136c660)
Location: security/keys/trusted.c:124
Inline: True
Direct callers:
  - security/keys/trusted.c:key_seal
  - security/keys/trusted.c:key_seal
  - security/keys/trusted.c:tpm_unseal
  - security/keys/trusted.c:tpm_unseal
```
**Symbols:**

```
ffffffff8136c660-ffffffff8136c81e: TSS_authhmac.constprop.10 (STB_LOCAL)
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
In security/keys/trusted.c (ffffffff81382e80)
Location: security/keys/trusted.c:124
Inline: True
Direct callers:
  - security/keys/trusted.c:key_seal
  - security/keys/trusted.c:key_seal
  - security/keys/trusted.c:tpm_unseal
  - security/keys/trusted.c:tpm_unseal
```
**Symbols:**

```
ffffffff81382e80-ffffffff8138303e: TSS_authhmac.constprop.10 (STB_LOCAL)
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
In security/keys/trusted.c (ffffffff81397520)
Location: security/keys/trusted.c:124
Inline: True
Direct callers:
  - security/keys/trusted.c:key_seal
  - security/keys/trusted.c:key_seal
  - security/keys/trusted.c:tpm_unseal
  - security/keys/trusted.c:tpm_unseal
```
**Symbols:**

```
ffffffff81397520-ffffffff813976f6: TSS_authhmac.constprop.9 (STB_LOCAL)
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
In security/keys/trusted.c (ffffffff813bcd00)
Location: security/keys/trusted.c:124
Inline: True
Direct callers:
  - security/keys/trusted.c:key_seal
  - security/keys/trusted.c:key_seal
  - security/keys/trusted.c:tpm_unseal
  - security/keys/trusted.c:tpm_unseal
```
**Symbols:**

```
ffffffff813bcd00-ffffffff813bcee7: TSS_authhmac.constprop.9 (STB_LOCAL)
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
Location: security/keys/trusted.c:124
Inline: True
Direct callers:
  - security/keys/trusted.c:key_seal
  - security/keys/trusted.c:key_seal
  - security/keys/trusted.c:tpm_unseal
  - security/keys/trusted.c:tpm_unseal
```
**Symbols:**

```
ffffffff813edaa0-ffffffff813edc67: TSS_authhmac.constprop.7 (STB_LOCAL)
ffffffff813ef1a0-ffffffff813ef1ba: TSS_authhmac.constprop.7.cold.13 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int TSS_authhmac(unsigned char *digest, const unsigned char *key, unsigned int keylen, unsigned char *h1, unsigned char *h2, unsigned char h3, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/keys/trusted.c (0)
Location: security/keys/trusted.c:124
Inline: False
Direct callers:
  - security/keys/trusted.c:key_seal
  - security/keys/trusted.c:key_seal
  - security/keys/trusted.c:tpm_unseal
  - security/keys/trusted.c:tpm_unseal
```
**Symbols:**

```
ffffffff8140a3dc-ffffffff8140a3f6: TSS_authhmac.cold.10 (STB_LOCAL)
ffffffff81408720-ffffffff814088fc: TSS_authhmac (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int TSS_authhmac(unsigned char *digest, const unsigned char *key, unsigned int keylen, unsigned char *h1, unsigned char *h2, unsigned int h3, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/keys/trusted.c (0)
Location: security/keys/trusted.c:122
Inline: False
Direct callers:
  - security/keys/trusted.c:tpm_unseal
  - security/keys/trusted.c:tpm_unseal
  - security/keys/trusted.c:tpm_seal
  - security/keys/trusted.c:tpm_seal
```
**Symbols:**

```
ffffffff81437648-ffffffff81437663: TSS_authhmac.cold (STB_LOCAL)
ffffffff81435ee0-ffffffff814360e0: TSS_authhmac (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int TSS_authhmac(unsigned char *digest, const unsigned char *key, unsigned int keylen, unsigned char *h1, unsigned char *h2, unsigned int h3, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/keys/trusted.c (0)
Location: security/keys/trusted.c:122
Inline: False
Direct callers:
  - security/keys/trusted.c:tpm_unseal
  - security/keys/trusted.c:tpm_unseal
  - security/keys/trusted.c:tpm_seal
  - security/keys/trusted.c:tpm_seal
```
**Symbols:**

```
ffffffff814513f6-ffffffff81451411: TSS_authhmac.cold (STB_LOCAL)
ffffffff8144fc80-ffffffff8144fe80: TSS_authhmac (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int TSS_authhmac(unsigned char *digest, const unsigned char *key, unsigned int keylen, unsigned char *h1, unsigned char *h2, unsigned int h3, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/keys/trusted-keys/trusted_tpm1.c (0)
Location: security/keys/trusted-keys/trusted_tpm1.c:122
Inline: False
Direct callers:
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_unseal
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_unseal
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_seal
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_seal
```
**Symbols:**

```
ffffffff814a3026-ffffffff814a3041: TSS_authhmac.cold (STB_LOCAL)
ffffffff814a1430-ffffffff814a1630: TSS_authhmac (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int TSS_authhmac(unsigned char *digest, const unsigned char *key, unsigned int keylen, unsigned char *h1, unsigned char *h2, unsigned int h3, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/keys/trusted-keys/trusted_tpm1.c (0)
Location: security/keys/trusted-keys/trusted_tpm1.c:122
Inline: False
Direct callers:
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_unseal
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_unseal
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_seal
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_seal
```
**Symbols:**

```
ffffffff81befc76-ffffffff81befc91: TSS_authhmac.cold (STB_LOCAL)
ffffffff814bedf0-ffffffff814beff0: TSS_authhmac (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int TSS_authhmac(unsigned char *digest, const unsigned char *key, unsigned int keylen, unsigned char *h1, unsigned char *h2, unsigned int h3, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/keys/trusted-keys/trusted_tpm1.c (0)
Location: security/keys/trusted-keys/trusted_tpm1.c:115
Inline: False
Direct callers:
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_unseal
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_unseal
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_seal
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_seal
```
**Symbols:**

```
ffffffff81be1d4b-ffffffff81be1d66: TSS_authhmac.cold (STB_LOCAL)
ffffffff814c5050-ffffffff814c5250: TSS_authhmac (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int TSS_authhmac(unsigned char *digest, const unsigned char *key, unsigned int keylen, unsigned char *h1, unsigned char *h2, unsigned int h3, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/keys/trusted-keys/trusted_tpm1.c (0)
Location: security/keys/trusted-keys/trusted_tpm1.c:115
Inline: False
Direct callers:
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_unseal
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_unseal
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_seal
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_seal
```
**Symbols:**

```
ffffffff81cd2fbc-ffffffff81cd2fd7: TSS_authhmac.cold (STB_LOCAL)
ffffffff8151da70-ffffffff8151dc70: TSS_authhmac (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int TSS_authhmac(unsigned char *digest, const unsigned char *key, unsigned int keylen, unsigned char *h1, unsigned char *h2, unsigned int h3, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/keys/trusted-keys/trusted_tpm1.c (0)
Location: security/keys/trusted-keys/trusted_tpm1.c:115
Inline: False
Direct callers:
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_unseal
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_unseal
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_seal
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_seal
```
**Symbols:**

```
ffffffff81e86157-ffffffff81e86171: TSS_authhmac.cold (STB_LOCAL)
ffffffff815b0e70-ffffffff815b10c1: TSS_authhmac (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int TSS_authhmac(unsigned char *digest, const unsigned char *key, unsigned int keylen, unsigned char *h1, unsigned char *h2, unsigned int h3, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/trusted-keys/trusted_tpm1.c (ffffffff8165b920)
Location: security/keys/trusted-keys/trusted_tpm1.c:115
Inline: False
Direct callers:
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_unseal
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_unseal
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_seal
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_seal
```
**Symbols:**

```
ffffffff8165b920-ffffffff8165bb93: TSS_authhmac (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int TSS_authhmac(unsigned char *digest, const unsigned char *key, unsigned int keylen, unsigned char *h1, unsigned char *h2, unsigned int h3, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/trusted-keys/trusted_tpm1.c (ffffffff81694240)
Location: security/keys/trusted-keys/trusted_tpm1.c:115
Inline: False
Direct callers:
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_unseal
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_unseal
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_seal
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_seal
```
**Symbols:**

```
ffffffff81694240-ffffffff816944b3: TSS_authhmac (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int TSS_authhmac(unsigned char *digest, const unsigned char *key, unsigned int keylen, unsigned char *h1, unsigned char *h2, unsigned int h3, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/trusted-keys/trusted_tpm1.c (ffffffff816d0870)
Location: security/keys/trusted-keys/trusted_tpm1.c:115
Inline: False
Direct callers:
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_unseal
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_unseal
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_seal
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_seal
```
**Symbols:**

```
ffffffff816d0870-ffffffff816d0ae3: TSS_authhmac (STB_GLOBAL)
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
int TSS_authhmac(unsigned char *digest, const unsigned char *key, unsigned int keylen, unsigned char *h1, unsigned char *h2, unsigned int h3, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/trusted.c (ffff80001053a648)
Location: security/keys/trusted.c:122
Inline: False
Direct callers:
  - security/keys/trusted.c:tpm_unseal
  - security/keys/trusted.c:tpm_unseal
  - security/keys/trusted.c:tpm_seal
  - security/keys/trusted.c:tpm_seal
```
**Symbols:**

```
ffff80001053a648-ffff80001053a874: TSS_authhmac (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int TSS_authhmac(unsigned char *digest, const unsigned char *key, unsigned int keylen, unsigned char *h1, unsigned char *h2, unsigned int h3, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/trusted.c (c06f0ef0)
Location: security/keys/trusted.c:122
Inline: False
Direct callers:
  - security/keys/trusted.c:tpm_unseal
  - security/keys/trusted.c:tpm_unseal
  - security/keys/trusted.c:tpm_seal
  - security/keys/trusted.c:tpm_seal
```
**Symbols:**

```
c06f0ef0-c06f1098: TSS_authhmac (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int TSS_authhmac(unsigned char *digest, const unsigned char *key, unsigned int keylen, unsigned char *h1, unsigned char *h2, unsigned int h3, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/trusted.c (c000000000689eb0)
Location: security/keys/trusted.c:122
Inline: False
Direct callers:
  - security/keys/trusted.c:tpm_unseal
  - security/keys/trusted.c:tpm_unseal
  - security/keys/trusted.c:tpm_seal
  - security/keys/trusted.c:tpm_seal
```
**Symbols:**

```
c000000000689eb0-c00000000068a0f8: TSS_authhmac (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int TSS_authhmac(unsigned char *digest, const unsigned char *key, unsigned int keylen, unsigned char *h1, unsigned char *h2, unsigned int h3, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/trusted.c (ffffffe0003987ae)
Location: security/keys/trusted.c:122
Inline: False
Direct callers:
  - security/keys/trusted.c:tpm_unseal
  - security/keys/trusted.c:tpm_unseal
  - security/keys/trusted.c:tpm_seal
  - security/keys/trusted.c:tpm_seal
```
**Symbols:**

```
ffffffe0003987ae-ffffffe0003988e2: TSS_authhmac (STB_GLOBAL)
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
int TSS_authhmac(unsigned char *digest, const unsigned char *key, unsigned int keylen, unsigned char *h1, unsigned char *h2, unsigned int h3, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/keys/trusted.c (0)
Location: security/keys/trusted.c:122
Inline: False
Direct callers:
  - security/keys/trusted.c:tpm_unseal
  - security/keys/trusted.c:tpm_unseal
  - security/keys/trusted.c:tpm_seal
  - security/keys/trusted.c:tpm_seal
```
**Symbols:**

```
ffffffff814499d6-ffffffff814499f1: TSS_authhmac.cold (STB_LOCAL)
ffffffff81448260-ffffffff81448460: TSS_authhmac (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int TSS_authhmac(unsigned char *digest, const unsigned char *key, unsigned int keylen, unsigned char *h1, unsigned char *h2, unsigned int h3, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/keys/trusted.c (0)
Location: security/keys/trusted.c:122
Inline: False
Direct callers:
  - security/keys/trusted.c:tpm_unseal
  - security/keys/trusted.c:tpm_unseal
  - security/keys/trusted.c:tpm_seal
  - security/keys/trusted.c:tpm_seal
```
**Symbols:**

```
ffffffff8143a426-ffffffff8143a441: TSS_authhmac.cold (STB_LOCAL)
ffffffff81438cb0-ffffffff81438eb0: TSS_authhmac (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int TSS_authhmac(unsigned char *digest, const unsigned char *key, unsigned int keylen, unsigned char *h1, unsigned char *h2, unsigned int h3, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/keys/trusted.c (0)
Location: security/keys/trusted.c:122
Inline: False
Direct callers:
  - security/keys/trusted.c:tpm_unseal
  - security/keys/trusted.c:tpm_unseal
  - security/keys/trusted.c:tpm_seal
  - security/keys/trusted.c:tpm_seal
```
**Symbols:**

```
ffffffff81445a76-ffffffff81445a91: TSS_authhmac.cold (STB_LOCAL)
ffffffff81444300-ffffffff81444500: TSS_authhmac (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int TSS_authhmac(unsigned char *digest, const unsigned char *key, unsigned int keylen, unsigned char *h1, unsigned char *h2, unsigned int h3, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/keys/trusted.c (0)
Location: security/keys/trusted.c:122
Inline: False
Direct callers:
  - security/keys/trusted.c:tpm_unseal
  - security/keys/trusted.c:tpm_unseal
  - security/keys/trusted.c:tpm_seal
  - security/keys/trusted.c:tpm_seal
```
**Symbols:**

```
ffffffff8145cda6-ffffffff8145cdc1: TSS_authhmac.cold (STB_LOCAL)
ffffffff8145b630-ffffffff8145b830: TSS_authhmac (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>unsigned char h3</code> ➡️ <code>unsigned int h3</code>
</li>
</ul>
</details>
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
