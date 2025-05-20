# Function: <code>pkcs7_digest</code>

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
In crypto/asymmetric_keys/pkcs7_verify.c (ffffffff813aec0d)
Location: crypto/asymmetric_keys/pkcs7_verify.c:25
Inline: True
Inline callers:
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify
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
In crypto/asymmetric_keys/pkcs7_verify.c (ffffffff813f2858)
Location: crypto/asymmetric_keys/pkcs7_verify.c:25
Inline: True
Inline callers:
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify
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
In crypto/asymmetric_keys/pkcs7_verify.c (ffffffff8140c0c8)
Location: crypto/asymmetric_keys/pkcs7_verify.c:25
Inline: True
Inline callers:
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/pkcs7_verify.c (ffffffff81419cd3)
Location: crypto/asymmetric_keys/pkcs7_verify.c:25
Inline: True
Inline callers:
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/pkcs7_verify.c (ffffffff81444806)
Location: crypto/asymmetric_keys/pkcs7_verify.c:25
Inline: True
Inline callers:
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify
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
In crypto/asymmetric_keys/pkcs7_verify.c (0)
Location: crypto/asymmetric_keys/pkcs7_verify.c:25
Inline: True
Direct callers:
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify
```
**Symbols:**

```
ffffffff81477700-ffffffff814779bb: pkcs7_digest.isra.0 (STB_LOCAL)
ffffffff81477f81-ffffffff81477fa4: pkcs7_digest.isra.0.cold.4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/pkcs7_verify.c (ffffffff81495938)
Location: crypto/asymmetric_keys/pkcs7_verify.c:25
Inline: True
Inline callers:
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify
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
In crypto/asymmetric_keys/pkcs7_verify.c (0)
Location: crypto/asymmetric_keys/pkcs7_verify.c:21
Inline: True
Direct callers:
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify
```
**Symbols:**

```
ffffffff814c36a0-ffffffff814c3968: pkcs7_digest.isra.0 (STB_LOCAL)
ffffffff814c3c14-ffffffff814c3c36: pkcs7_digest.isra.0.cold (STB_LOCAL)
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
In crypto/asymmetric_keys/pkcs7_verify.c (0)
Location: crypto/asymmetric_keys/pkcs7_verify.c:22
Inline: True
Direct callers:
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_get_digest
```
**Symbols:**

```
ffffffff814dc4d0-ffffffff814dc7af: pkcs7_digest.isra.0 (STB_LOCAL)
ffffffff814dcaf4-ffffffff814dcb16: pkcs7_digest.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int pkcs7_digest(struct pkcs7_message *pkcs7, struct pkcs7_signed_info *sinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In crypto/asymmetric_keys/pkcs7_verify.c (0)
Location: crypto/asymmetric_keys/pkcs7_verify.c:22
Inline: False
Direct callers:
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify_one
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_get_digest
```
**Symbols:**

```
ffffffff8153bde0-ffffffff8153c0b5: pkcs7_digest (STB_LOCAL)
ffffffff8153c3e4-ffffffff8153c406: pkcs7_digest.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int pkcs7_digest(struct pkcs7_message *pkcs7, struct pkcs7_signed_info *sinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In crypto/asymmetric_keys/pkcs7_verify.c (0)
Location: crypto/asymmetric_keys/pkcs7_verify.c:22
Inline: False
Direct callers:
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify_one
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_get_digest
```
**Symbols:**

```
ffffffff81558a80-ffffffff81558d55: pkcs7_digest (STB_LOCAL)
ffffffff81bf2455-ffffffff81bf2477: pkcs7_digest.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int pkcs7_digest(struct pkcs7_message *pkcs7, struct pkcs7_signed_info *sinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In crypto/asymmetric_keys/pkcs7_verify.c (0)
Location: crypto/asymmetric_keys/pkcs7_verify.c:22
Inline: False
Direct callers:
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_get_digest
```
**Symbols:**

```
ffffffff815613b0-ffffffff81561685: pkcs7_digest (STB_LOCAL)
ffffffff81be4411-ffffffff81be4433: pkcs7_digest.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int pkcs7_digest(struct pkcs7_message *pkcs7, struct pkcs7_signed_info *sinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In crypto/asymmetric_keys/pkcs7_verify.c (0)
Location: crypto/asymmetric_keys/pkcs7_verify.c:22
Inline: False
Direct callers:
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_get_digest
```
**Symbols:**

```
ffffffff815c2810-ffffffff815c2a72: pkcs7_digest (STB_LOCAL)
ffffffff81cd7d10-ffffffff81cd7d32: pkcs7_digest.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int pkcs7_digest(struct pkcs7_message *pkcs7, struct pkcs7_signed_info *sinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In crypto/asymmetric_keys/pkcs7_verify.c (0)
Location: crypto/asymmetric_keys/pkcs7_verify.c:22
Inline: False
Direct callers:
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_get_digest
```
**Symbols:**

```
ffffffff8166cd30-ffffffff8166cf92: pkcs7_digest (STB_LOCAL)
ffffffff81e8af9f-ffffffff81e8afbb: pkcs7_digest.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int pkcs7_digest(struct pkcs7_message *pkcs7, struct pkcs7_signed_info *sinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/pkcs7_verify.c (ffffffff81727d30)
Location: crypto/asymmetric_keys/pkcs7_verify.c:22
Inline: False
Direct callers:
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_get_digest
```
**Symbols:**

```
ffffffff81727d30-ffffffff81727fae: pkcs7_digest (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int pkcs7_digest(struct pkcs7_message *pkcs7, struct pkcs7_signed_info *sinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/pkcs7_verify.c (ffffffff81764180)
Location: crypto/asymmetric_keys/pkcs7_verify.c:22
Inline: False
Direct callers:
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_get_digest
```
**Symbols:**

```
ffffffff81764180-ffffffff817643d4: pkcs7_digest (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int pkcs7_digest(struct pkcs7_message *pkcs7, struct pkcs7_signed_info *sinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/pkcs7_verify.c (ffffffff817a5da0)
Location: crypto/asymmetric_keys/pkcs7_verify.c:22
Inline: False
Direct callers:
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_get_digest
```
**Symbols:**

```
ffffffff817a5da0-ffffffff817a5ff4: pkcs7_digest (STB_LOCAL)
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
In crypto/asymmetric_keys/pkcs7_verify.c (ffff8000105d8ab8)
Location: crypto/asymmetric_keys/pkcs7_verify.c:22
Inline: True
Direct callers:
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_get_digest
```
**Symbols:**

```
ffff8000105d8ab8-ffff8000105d8d20: pkcs7_digest.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int pkcs7_digest(struct pkcs7_message *pkcs7, struct pkcs7_signed_info *sinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/pkcs7_verify.c (c0786018)
Location: crypto/asymmetric_keys/pkcs7_verify.c:22
Inline: False
Direct callers:
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_get_digest
```
**Symbols:**

```
c0786018-c0786278: pkcs7_digest (STB_LOCAL)
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
In crypto/asymmetric_keys/pkcs7_verify.c (c000000000768320)
Location: crypto/asymmetric_keys/pkcs7_verify.c:22
Inline: True
Direct callers:
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_get_digest
```
**Symbols:**

```
c000000000768320-c000000000768664: pkcs7_digest.isra.0 (STB_LOCAL)
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
In crypto/asymmetric_keys/pkcs7_verify.c (ffffffe00041c6ca)
Location: crypto/asymmetric_keys/pkcs7_verify.c:22
Inline: True
Direct callers:
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_get_digest
```
**Symbols:**

```
ffffffe00041c6ca-ffffffe00041c8be: pkcs7_digest.isra.0 (STB_LOCAL)
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
In crypto/asymmetric_keys/pkcs7_verify.c (0)
Location: crypto/asymmetric_keys/pkcs7_verify.c:22
Inline: True
Direct callers:
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_get_digest
```
**Symbols:**

```
ffffffff814d4ab0-ffffffff814d4d8f: pkcs7_digest.isra.0 (STB_LOCAL)
ffffffff814d50d4-ffffffff814d50f6: pkcs7_digest.isra.0.cold (STB_LOCAL)
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
In crypto/asymmetric_keys/pkcs7_verify.c (0)
Location: crypto/asymmetric_keys/pkcs7_verify.c:22
Inline: True
Direct callers:
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_get_digest
```
**Symbols:**

```
ffffffff814c54d0-ffffffff814c57af: pkcs7_digest.isra.0 (STB_LOCAL)
ffffffff814c5af4-ffffffff814c5b16: pkcs7_digest.isra.0.cold (STB_LOCAL)
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
In crypto/asymmetric_keys/pkcs7_verify.c (0)
Location: crypto/asymmetric_keys/pkcs7_verify.c:22
Inline: True
Direct callers:
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_get_digest
```
**Symbols:**

```
ffffffff814d0b40-ffffffff814d0e1f: pkcs7_digest.isra.0 (STB_LOCAL)
ffffffff814d1164-ffffffff814d1186: pkcs7_digest.isra.0.cold (STB_LOCAL)
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
In crypto/asymmetric_keys/pkcs7_verify.c (0)
Location: crypto/asymmetric_keys/pkcs7_verify.c:22
Inline: True
Direct callers:
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_get_digest
```
**Symbols:**

```
ffffffff814e95f0-ffffffff814e98cf: pkcs7_digest.isra.0 (STB_LOCAL)
ffffffff814e9c14-ffffffff814e9c36: pkcs7_digest.isra.0.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
