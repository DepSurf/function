# Function: <code>x509_fabricate_name</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int x509_fabricate_name(struct x509_parse_context *ctx, size_t hdrlen, unsigned char tag, char **_name, size_t vlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/x509_cert_parser.c (ffffffff813aca40)
Location: crypto/asymmetric_keys/x509_cert_parser.c:292
Inline: False
Direct callers:
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_note_issuer
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_note_subject
```
**Symbols:**

```
ffffffff813aca40-ffffffff813acd63: x509_fabricate_name (STB_LOCAL)
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
In crypto/asymmetric_keys/x509_cert_parser.c (ffffffff813f0c10)
Location: crypto/asymmetric_keys/x509_cert_parser.c:302
Inline: True
Direct callers:
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_note_subject
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_note_issuer
```
**Symbols:**

```
ffffffff813f0c10-ffffffff813f0f22: x509_fabricate_name.constprop.0 (STB_LOCAL)
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
In crypto/asymmetric_keys/x509_cert_parser.c (ffffffff8140a490)
Location: crypto/asymmetric_keys/x509_cert_parser.c:301
Inline: True
Direct callers:
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_note_subject
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_note_issuer
```
**Symbols:**

```
ffffffff8140a490-ffffffff8140a7a2: x509_fabricate_name.constprop.0 (STB_LOCAL)
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
In crypto/asymmetric_keys/x509_cert_parser.c (ffffffff81417ff0)
Location: crypto/asymmetric_keys/x509_cert_parser.c:302
Inline: True
Direct callers:
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_note_subject
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_note_issuer
```
**Symbols:**

```
ffffffff81417ff0-ffffffff814182fa: x509_fabricate_name.constprop.1 (STB_LOCAL)
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
In crypto/asymmetric_keys/x509_cert_parser.c (ffffffff81442ae0)
Location: crypto/asymmetric_keys/x509_cert_parser.c:302
Inline: True
Direct callers:
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_note_subject
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_note_issuer
```
**Symbols:**

```
ffffffff81442ae0-ffffffff81442dea: x509_fabricate_name.constprop.1 (STB_LOCAL)
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
In crypto/asymmetric_keys/x509_cert_parser.c (ffffffff814759d0)
Location: crypto/asymmetric_keys/x509_cert_parser.c:311
Inline: True
Direct callers:
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_note_subject
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_note_issuer
```
**Symbols:**

```
ffffffff814759d0-ffffffff81475ce1: x509_fabricate_name.constprop.1 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In crypto/asymmetric_keys/x509_cert_parser.c (ffffffff81493d50)
Location: crypto/asymmetric_keys/x509_cert_parser.c:308
Inline: True
Direct callers:
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_note_subject
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_note_issuer
```
**Symbols:**

```
ffffffff81493d50-ffffffff81494061: x509_fabricate_name.constprop.1 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In crypto/asymmetric_keys/x509_cert_parser.c (ffffffff814c1650)
Location: crypto/asymmetric_keys/x509_cert_parser.c:328
Inline: True
Direct callers:
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_note_subject
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_note_issuer
```
**Symbols:**

```
ffffffff814c1650-ffffffff814c1952: x509_fabricate_name.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In crypto/asymmetric_keys/x509_cert_parser.c (ffffffff814da480)
Location: crypto/asymmetric_keys/x509_cert_parser.c:328
Inline: True
Direct callers:
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_note_subject
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_note_issuer
```
**Symbols:**

```
ffffffff814da480-ffffffff814da782: x509_fabricate_name.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In crypto/asymmetric_keys/x509_cert_parser.c (ffffffff81539b50)
Location: crypto/asymmetric_keys/x509_cert_parser.c:328
Inline: True
Direct callers:
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_note_subject
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_note_issuer
```
**Symbols:**

```
ffffffff81539b50-ffffffff81539e59: x509_fabricate_name.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In crypto/asymmetric_keys/x509_cert_parser.c (ffffffff81556940)
Location: crypto/asymmetric_keys/x509_cert_parser.c:338
Inline: True
Direct callers:
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_note_subject
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_note_issuer
```
**Symbols:**

```
ffffffff81556940-ffffffff81556c49: x509_fabricate_name.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In crypto/asymmetric_keys/x509_cert_parser.c (ffffffff8155f0c0)
Location: crypto/asymmetric_keys/x509_cert_parser.c:364
Inline: True
Direct callers:
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_note_subject
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_note_issuer
```
**Symbols:**

```
ffffffff8155f0c0-ffffffff8155f3c9: x509_fabricate_name.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In crypto/asymmetric_keys/x509_cert_parser.c (ffffffff815c0450)
Location: crypto/asymmetric_keys/x509_cert_parser.c:364
Inline: True
Direct callers:
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_note_subject
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_note_issuer
```
**Symbols:**

```
ffffffff815c0450-ffffffff815c0759: x509_fabricate_name.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In crypto/asymmetric_keys/x509_cert_parser.c (ffffffff8166a690)
Location: crypto/asymmetric_keys/x509_cert_parser.c:366
Inline: True
Direct callers:
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_note_subject
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_note_issuer
```
**Symbols:**

```
ffffffff8166a690-ffffffff8166a9b5: x509_fabricate_name.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In crypto/asymmetric_keys/x509_cert_parser.c (ffffffff81725100)
Location: crypto/asymmetric_keys/x509_cert_parser.c:366
Inline: True
Direct callers:
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_note_subject
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_note_issuer
```
**Symbols:**

```
ffffffff81725100-ffffffff81725425: x509_fabricate_name.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In crypto/asymmetric_keys/x509_cert_parser.c (ffffffff817613b0)
Location: crypto/asymmetric_keys/x509_cert_parser.c:366
Inline: True
Direct callers:
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_note_subject
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_note_issuer
```
**Symbols:**

```
ffffffff817613b0-ffffffff817616f8: x509_fabricate_name.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In crypto/asymmetric_keys/x509_cert_parser.c (ffffffff817a2d10)
Location: crypto/asymmetric_keys/x509_cert_parser.c:376
Inline: True
Direct callers:
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_note_subject
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_note_issuer
```
**Symbols:**

```
ffffffff817a2d10-ffffffff817a308a: x509_fabricate_name.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In crypto/asymmetric_keys/x509_cert_parser.c (ffff8000105d62e0)
Location: crypto/asymmetric_keys/x509_cert_parser.c:328
Inline: True
Direct callers:
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_note_subject
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_note_issuer
```
**Symbols:**

```
ffff8000105d62e0-ffff8000105d64cc: x509_fabricate_name.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In crypto/asymmetric_keys/x509_cert_parser.c (c0783d40)
Location: crypto/asymmetric_keys/x509_cert_parser.c:328
Inline: True
Direct callers:
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_note_subject
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_note_issuer
```
**Symbols:**

```
c0783d40-c0783efc: x509_fabricate_name.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In crypto/asymmetric_keys/x509_cert_parser.c (c000000000764d40)
Location: crypto/asymmetric_keys/x509_cert_parser.c:328
Inline: True
Direct callers:
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_note_subject
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_note_issuer
```
**Symbols:**

```
c000000000764d40-c00000000076501c: x509_fabricate_name.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In crypto/asymmetric_keys/x509_cert_parser.c (ffffffe00041a658)
Location: crypto/asymmetric_keys/x509_cert_parser.c:328
Inline: True
Direct callers:
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_note_subject
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_note_issuer
```
**Symbols:**

```
ffffffe00041a658-ffffffe00041a7e8: x509_fabricate_name.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In crypto/asymmetric_keys/x509_cert_parser.c (ffffffff814d2a60)
Location: crypto/asymmetric_keys/x509_cert_parser.c:328
Inline: True
Direct callers:
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_note_subject
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_note_issuer
```
**Symbols:**

```
ffffffff814d2a60-ffffffff814d2d62: x509_fabricate_name.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In crypto/asymmetric_keys/x509_cert_parser.c (ffffffff814c3480)
Location: crypto/asymmetric_keys/x509_cert_parser.c:328
Inline: True
Direct callers:
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_note_subject
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_note_issuer
```
**Symbols:**

```
ffffffff814c3480-ffffffff814c3782: x509_fabricate_name.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In crypto/asymmetric_keys/x509_cert_parser.c (ffffffff814ceaf0)
Location: crypto/asymmetric_keys/x509_cert_parser.c:328
Inline: True
Direct callers:
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_note_subject
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_note_issuer
```
**Symbols:**

```
ffffffff814ceaf0-ffffffff814cedf2: x509_fabricate_name.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In crypto/asymmetric_keys/x509_cert_parser.c (ffffffff814e75c0)
Location: crypto/asymmetric_keys/x509_cert_parser.c:328
Inline: True
Direct callers:
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_note_subject
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_note_issuer
```
**Symbols:**

```
ffffffff814e75c0-ffffffff814e78c2: x509_fabricate_name.constprop.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
