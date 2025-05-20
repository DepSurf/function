# Function: <code>pkcs7_free_message</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pkcs7_free_message(struct pkcs7_message *pkcs7);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In crypto/asymmetric_keys/pkcs7_parser.c (ffffffff813adfa0)
Location: crypto/asymmetric_keys/pkcs7_parser.c:58
Inline: True
Inline callers:
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message
Direct callers:
  - certs/system_keyring.c:system_verify_data
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message
  - crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature
```
**Symbols:**

```
ffffffff813adfa0-ffffffff813ae00f: pkcs7_free_message.part.0 (STB_LOCAL)
ffffffff813ae010-ffffffff813ae026: pkcs7_free_message (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pkcs7_free_message(struct pkcs7_message *pkcs7);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In crypto/asymmetric_keys/pkcs7_parser.c (ffffffff813f1df2)
Location: crypto/asymmetric_keys/pkcs7_parser.c:56
Inline: True
Inline callers:
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message
Direct callers:
  - certs/system_keyring.c:verify_pkcs7_signature
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message
```
**Symbols:**

```
ffffffff813f1bd0-ffffffff813f1c51: pkcs7_free_message.part.0 (STB_LOCAL)
ffffffff813f1c60-ffffffff813f1c76: pkcs7_free_message (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pkcs7_free_message(struct pkcs7_message *pkcs7);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In crypto/asymmetric_keys/pkcs7_parser.c (ffffffff8140b662)
Location: crypto/asymmetric_keys/pkcs7_parser.c:56
Inline: True
Inline callers:
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message
Direct callers:
  - certs/system_keyring.c:verify_pkcs7_signature
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message
```
**Symbols:**

```
ffffffff8140b440-ffffffff8140b4c1: pkcs7_free_message.part.0 (STB_LOCAL)
ffffffff8140b4d0-ffffffff8140b4e6: pkcs7_free_message (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pkcs7_free_message(struct pkcs7_message *pkcs7);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In crypto/asymmetric_keys/pkcs7_parser.c (ffffffff814191fc)
Location: crypto/asymmetric_keys/pkcs7_parser.c:56
Inline: True
Inline callers:
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message
Direct callers:
  - certs/system_keyring.c:verify_pkcs7_signature
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message
```
**Symbols:**

```
ffffffff81419030-ffffffff814190b1: pkcs7_free_message.part.1 (STB_LOCAL)
ffffffff814190c0-ffffffff814190d7: pkcs7_free_message (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pkcs7_free_message(struct pkcs7_message *pkcs7);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In crypto/asymmetric_keys/pkcs7_parser.c (ffffffff81443d2c)
Location: crypto/asymmetric_keys/pkcs7_parser.c:61
Inline: True
Inline callers:
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message
Direct callers:
  - certs/system_keyring.c:verify_pkcs7_signature
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message
```
**Symbols:**

```
ffffffff81443b60-ffffffff81443be1: pkcs7_free_message.part.1 (STB_LOCAL)
ffffffff81443bf0-ffffffff81443c07: pkcs7_free_message (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void pkcs7_free_message(struct pkcs7_message *pkcs7);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/pkcs7_parser.c (ffffffff81476a90)
Location: crypto/asymmetric_keys/pkcs7_parser.c:61
Inline: True
Direct callers:
  - certs/system_keyring.c:verify_pkcs7_signature
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message
```
**Symbols:**

```
ffffffff81476a90-ffffffff81476b17: pkcs7_free_message (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void pkcs7_free_message(struct pkcs7_message *pkcs7);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/pkcs7_parser.c (ffffffff81494c30)
Location: crypto/asymmetric_keys/pkcs7_parser.c:61
Inline: True
Direct callers:
  - certs/system_keyring.c:verify_pkcs7_signature
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message
```
**Symbols:**

```
ffffffff81494c30-ffffffff81494cb7: pkcs7_free_message (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pkcs7_free_message(struct pkcs7_message *pkcs7);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In crypto/asymmetric_keys/pkcs7_parser.c (ffffffff814c2847)
Location: crypto/asymmetric_keys/pkcs7_parser.c:57
Inline: True
Inline callers:
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message
Direct callers:
  - certs/system_keyring.c:verify_pkcs7_signature
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message
```
**Symbols:**

```
ffffffff814c2620-ffffffff814c26aa: pkcs7_free_message.part.0 (STB_LOCAL)
ffffffff814c26b0-ffffffff814c26c6: pkcs7_free_message (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pkcs7_free_message(struct pkcs7_message *pkcs7);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In crypto/asymmetric_keys/pkcs7_parser.c (ffffffff814db677)
Location: crypto/asymmetric_keys/pkcs7_parser.c:57
Inline: True
Inline callers:
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message
Direct callers:
  - certs/system_keyring.c:verify_pkcs7_signature
  - security/integrity/ima/ima_modsig.c:ima_free_modsig
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message
```
**Symbols:**

```
ffffffff814db450-ffffffff814db4da: pkcs7_free_message.part.0 (STB_LOCAL)
ffffffff814db4e0-ffffffff814db4f6: pkcs7_free_message (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pkcs7_free_message(struct pkcs7_message *pkcs7);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In crypto/asymmetric_keys/pkcs7_parser.c (ffffffff8153af67)
Location: crypto/asymmetric_keys/pkcs7_parser.c:57
Inline: True
Inline callers:
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message
Direct callers:
  - certs/system_keyring.c:verify_pkcs7_signature
  - security/integrity/ima/ima_modsig.c:ima_free_modsig
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message
```
**Symbols:**

```
ffffffff8153ad40-ffffffff8153adca: pkcs7_free_message.part.0 (STB_LOCAL)
ffffffff8153add0-ffffffff8153ade6: pkcs7_free_message (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pkcs7_free_message(struct pkcs7_message *pkcs7);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In crypto/asymmetric_keys/pkcs7_parser.c (ffffffff81557d77)
Location: crypto/asymmetric_keys/pkcs7_parser.c:57
Inline: True
Inline callers:
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message
Direct callers:
  - certs/system_keyring.c:verify_pkcs7_signature
  - security/integrity/ima/ima_modsig.c:ima_free_modsig
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message
```
**Symbols:**

```
ffffffff81557b50-ffffffff81557bda: pkcs7_free_message.part.0 (STB_LOCAL)
ffffffff81557be0-ffffffff81557bf6: pkcs7_free_message (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pkcs7_free_message(struct pkcs7_message *pkcs7);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In crypto/asymmetric_keys/pkcs7_parser.c (ffffffff815606c7)
Location: crypto/asymmetric_keys/pkcs7_parser.c:57
Inline: True
Inline callers:
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message
Direct callers:
  - certs/system_keyring.c:verify_pkcs7_signature
  - security/integrity/ima/ima_modsig.c:ima_free_modsig
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message
```
**Symbols:**

```
ffffffff815604a0-ffffffff8156052a: pkcs7_free_message.part.0 (STB_LOCAL)
ffffffff81560530-ffffffff81560546: pkcs7_free_message (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pkcs7_free_message(struct pkcs7_message *pkcs7);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In crypto/asymmetric_keys/pkcs7_parser.c (ffffffff815c1a77)
Location: crypto/asymmetric_keys/pkcs7_parser.c:57
Inline: True
Inline callers:
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message
Direct callers:
  - certs/system_keyring.c:verify_pkcs7_signature
  - security/integrity/ima/ima_modsig.c:ima_free_modsig
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message
```
**Symbols:**

```
ffffffff815c1850-ffffffff815c18da: pkcs7_free_message.part.0 (STB_LOCAL)
ffffffff815c18e0-ffffffff815c18f6: pkcs7_free_message (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pkcs7_free_message(struct pkcs7_message *pkcs7);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In crypto/asymmetric_keys/pkcs7_parser.c (ffffffff8166be98)
Location: crypto/asymmetric_keys/pkcs7_parser.c:57
Inline: True
Inline callers:
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message
Direct callers:
  - certs/system_keyring.c:verify_pkcs7_signature
  - security/integrity/ima/ima_modsig.c:ima_free_modsig
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message
```
**Symbols:**

```
ffffffff8166bc70-ffffffff8166bcf9: pkcs7_free_message.part.0 (STB_LOCAL)
ffffffff8166bd00-ffffffff8166bd22: pkcs7_free_message (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pkcs7_free_message(struct pkcs7_message *pkcs7);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In crypto/asymmetric_keys/pkcs7_parser.c (ffffffff81726b23)
Location: crypto/asymmetric_keys/pkcs7_parser.c:57
Inline: True
Inline callers:
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message
Direct callers:
  - certs/system_keyring.c:verify_pkcs7_signature
  - security/integrity/ima/ima_modsig.c:ima_free_modsig
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message
```
**Symbols:**

```
ffffffff817268e0-ffffffff81726969: pkcs7_free_message.part.0 (STB_LOCAL)
ffffffff81726980-ffffffff817269a2: pkcs7_free_message (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pkcs7_free_message(struct pkcs7_message *pkcs7);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In crypto/asymmetric_keys/pkcs7_parser.c (ffffffff81762f23)
Location: crypto/asymmetric_keys/pkcs7_parser.c:57
Inline: True
Inline callers:
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message
Direct callers:
  - certs/system_keyring.c:verify_pkcs7_signature
  - security/integrity/ima/ima_modsig.c:ima_free_modsig
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message
```
**Symbols:**

```
ffffffff81762ce0-ffffffff81762d69: pkcs7_free_message.part.0 (STB_LOCAL)
ffffffff81762d80-ffffffff81762da2: pkcs7_free_message (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pkcs7_free_message(struct pkcs7_message *pkcs7);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In crypto/asymmetric_keys/pkcs7_parser.c (ffffffff817a4acf)
Location: crypto/asymmetric_keys/pkcs7_parser.c:57
Inline: True
Inline callers:
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message
Direct callers:
  - certs/system_keyring.c:verify_pkcs7_signature
  - security/integrity/ima/ima_modsig.c:ima_free_modsig
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message
```
**Symbols:**

```
ffffffff817a47d0-ffffffff817a4859: pkcs7_free_message.part.0 (STB_LOCAL)
ffffffff817a4870-ffffffff817a4892: pkcs7_free_message (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pkcs7_free_message(struct pkcs7_message *pkcs7);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In crypto/asymmetric_keys/pkcs7_parser.c (ffff8000105d7980)
Location: crypto/asymmetric_keys/pkcs7_parser.c:57
Inline: True
Inline callers:
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message
Direct callers:
  - certs/system_keyring.c:verify_pkcs7_signature
  - security/integrity/ima/ima_modsig.c:ima_free_modsig
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message
```
**Symbols:**

```
ffff8000105d7760-ffff8000105d77f4: pkcs7_free_message.part.0 (STB_LOCAL)
ffff8000105d77f8-ffff8000105d7828: pkcs7_free_message (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pkcs7_free_message(struct pkcs7_message *pkcs7);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In crypto/asymmetric_keys/pkcs7_parser.c (c0784fd8)
Location: crypto/asymmetric_keys/pkcs7_parser.c:57
Inline: True
Inline callers:
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message
Direct callers:
  - certs/system_keyring.c:verify_pkcs7_signature
  - security/integrity/ima/ima_modsig.c:ima_free_modsig
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message
```
**Symbols:**

```
c0784dac-c0784e48: pkcs7_free_message.part.0 (STB_LOCAL)
c0784e48-c0784e6c: pkcs7_free_message (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pkcs7_free_message(struct pkcs7_message *pkcs7);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In crypto/asymmetric_keys/pkcs7_parser.c (c000000000766dc4)
Location: crypto/asymmetric_keys/pkcs7_parser.c:57
Inline: True
Inline callers:
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message
Direct callers:
  - certs/system_keyring.c:verify_pkcs7_signature
  - security/integrity/ima/ima_modsig.c:ima_free_modsig
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message
```
**Symbols:**

```
c000000000766ae0-c000000000766bd0: pkcs7_free_message.part.0 (STB_LOCAL)
c000000000766bd0-c000000000766bec: pkcs7_free_message (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pkcs7_free_message(struct pkcs7_message *pkcs7);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In crypto/asymmetric_keys/pkcs7_parser.c (ffffffe00041b778)
Location: crypto/asymmetric_keys/pkcs7_parser.c:57
Inline: True
Inline callers:
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message
Direct callers:
  - certs/system_keyring.c:verify_pkcs7_signature
  - security/integrity/ima/ima_modsig.c:ima_free_modsig
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message
```
**Symbols:**

```
ffffffe00041b5a2-ffffffe00041b624: pkcs7_free_message.part.0 (STB_LOCAL)
ffffffe00041b624-ffffffe00041b650: pkcs7_free_message (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pkcs7_free_message(struct pkcs7_message *pkcs7);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In crypto/asymmetric_keys/pkcs7_parser.c (ffffffff814d3c57)
Location: crypto/asymmetric_keys/pkcs7_parser.c:57
Inline: True
Inline callers:
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message
Direct callers:
  - certs/system_keyring.c:verify_pkcs7_signature
  - security/integrity/ima/ima_modsig.c:ima_free_modsig
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message
```
**Symbols:**

```
ffffffff814d3a30-ffffffff814d3aba: pkcs7_free_message.part.0 (STB_LOCAL)
ffffffff814d3ac0-ffffffff814d3ad6: pkcs7_free_message (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pkcs7_free_message(struct pkcs7_message *pkcs7);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In crypto/asymmetric_keys/pkcs7_parser.c (ffffffff814c4677)
Location: crypto/asymmetric_keys/pkcs7_parser.c:57
Inline: True
Inline callers:
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message
Direct callers:
  - certs/system_keyring.c:verify_pkcs7_signature
  - security/integrity/ima/ima_modsig.c:ima_free_modsig
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message
```
**Symbols:**

```
ffffffff814c4450-ffffffff814c44da: pkcs7_free_message.part.0 (STB_LOCAL)
ffffffff814c44e0-ffffffff814c44f6: pkcs7_free_message (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pkcs7_free_message(struct pkcs7_message *pkcs7);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In crypto/asymmetric_keys/pkcs7_parser.c (ffffffff814cfce7)
Location: crypto/asymmetric_keys/pkcs7_parser.c:57
Inline: True
Inline callers:
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message
Direct callers:
  - certs/system_keyring.c:verify_pkcs7_signature
  - security/integrity/ima/ima_modsig.c:ima_free_modsig
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message
```
**Symbols:**

```
ffffffff814cfac0-ffffffff814cfb4a: pkcs7_free_message.part.0 (STB_LOCAL)
ffffffff814cfb50-ffffffff814cfb66: pkcs7_free_message (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pkcs7_free_message(struct pkcs7_message *pkcs7);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In crypto/asymmetric_keys/pkcs7_parser.c (ffffffff814e87b7)
Location: crypto/asymmetric_keys/pkcs7_parser.c:57
Inline: True
Inline callers:
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message
Direct callers:
  - certs/system_keyring.c:verify_pkcs7_signature
  - security/integrity/ima/ima_modsig.c:ima_free_modsig
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message
```
**Symbols:**

```
ffffffff814e8590-ffffffff814e861a: pkcs7_free_message.part.0 (STB_LOCAL)
ffffffff814e8620-ffffffff814e8636: pkcs7_free_message (STB_GLOBAL)
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
