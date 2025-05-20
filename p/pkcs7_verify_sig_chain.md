# Function: <code>pkcs7_verify_sig_chain</code>

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
In crypto/asymmetric_keys/pkcs7_verify.c (ffffffff813aed96)
Location: crypto/asymmetric_keys/pkcs7_verify.c:176
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
In crypto/asymmetric_keys/pkcs7_verify.c (ffffffff813f2a53)
Location: crypto/asymmetric_keys/pkcs7_verify.c:175
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
In crypto/asymmetric_keys/pkcs7_verify.c (ffffffff8140c2c3)
Location: crypto/asymmetric_keys/pkcs7_verify.c:175
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
In crypto/asymmetric_keys/pkcs7_verify.c (ffffffff81419f30)
Location: crypto/asymmetric_keys/pkcs7_verify.c:175
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
In crypto/asymmetric_keys/pkcs7_verify.c (ffffffff81444aaf)
Location: crypto/asymmetric_keys/pkcs7_verify.c:172
Inline: True
Inline callers:
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/pkcs7_verify.c (ffffffff81477aca)
Location: crypto/asymmetric_keys/pkcs7_verify.c:172
Inline: True
Inline callers:
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify
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
In crypto/asymmetric_keys/pkcs7_verify.c (ffffffff81495b15)
Location: crypto/asymmetric_keys/pkcs7_verify.c:172
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
Location: crypto/asymmetric_keys/pkcs7_verify.c:167
Inline: True
Direct callers:
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify
```
**Symbols:**

```
ffffffff814c3320-ffffffff814c3694: pkcs7_verify_sig_chain.isra.0 (STB_LOCAL)
ffffffff814c3bd0-ffffffff814c3c14: pkcs7_verify_sig_chain.isra.0.cold (STB_LOCAL)
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
Location: crypto/asymmetric_keys/pkcs7_verify.c:200
Inline: True
Direct callers:
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify
```
**Symbols:**

```
ffffffff814dc150-ffffffff814dc4c4: pkcs7_verify_sig_chain.isra.0 (STB_LOCAL)
ffffffff814dcab0-ffffffff814dcaf4: pkcs7_verify_sig_chain.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int pkcs7_verify_sig_chain(struct pkcs7_message *pkcs7, struct pkcs7_signed_info *sinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In crypto/asymmetric_keys/pkcs7_verify.c (0)
Location: crypto/asymmetric_keys/pkcs7_verify.c:200
Inline: False
Direct callers:
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify_one
```
**Symbols:**

```
ffffffff8153ba60-ffffffff8153bdd4: pkcs7_verify_sig_chain (STB_LOCAL)
ffffffff8153c3a0-ffffffff8153c3e4: pkcs7_verify_sig_chain.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int pkcs7_verify_sig_chain(struct pkcs7_message *pkcs7, struct pkcs7_signed_info *sinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In crypto/asymmetric_keys/pkcs7_verify.c (0)
Location: crypto/asymmetric_keys/pkcs7_verify.c:200
Inline: False
Direct callers:
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify_one
```
**Symbols:**

```
ffffffff81558700-ffffffff81558a74: pkcs7_verify_sig_chain (STB_LOCAL)
ffffffff81bf2411-ffffffff81bf2455: pkcs7_verify_sig_chain.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int pkcs7_verify_sig_chain(struct pkcs7_message *pkcs7, struct pkcs7_signed_info *sinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In crypto/asymmetric_keys/pkcs7_verify.c (0)
Location: crypto/asymmetric_keys/pkcs7_verify.c:199
Inline: False
Direct callers:
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify
```
**Symbols:**

```
ffffffff81561030-ffffffff815613a4: pkcs7_verify_sig_chain (STB_LOCAL)
ffffffff81be43cd-ffffffff81be4411: pkcs7_verify_sig_chain.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int pkcs7_verify_sig_chain(struct pkcs7_message *pkcs7, struct pkcs7_signed_info *sinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In crypto/asymmetric_keys/pkcs7_verify.c (0)
Location: crypto/asymmetric_keys/pkcs7_verify.c:199
Inline: False
Direct callers:
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify
```
**Symbols:**

```
ffffffff815c2450-ffffffff815c2802: pkcs7_verify_sig_chain (STB_LOCAL)
ffffffff81cd7c63-ffffffff81cd7d10: pkcs7_verify_sig_chain.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int pkcs7_verify_sig_chain(struct pkcs7_message *pkcs7, struct pkcs7_signed_info *sinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In crypto/asymmetric_keys/pkcs7_verify.c (0)
Location: crypto/asymmetric_keys/pkcs7_verify.c:193
Inline: False
Direct callers:
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify
```
**Symbols:**

```
ffffffff8166c990-ffffffff8166cd28: pkcs7_verify_sig_chain (STB_LOCAL)
ffffffff81e8af0b-ffffffff81e8af9f: pkcs7_verify_sig_chain.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int pkcs7_verify_sig_chain(struct pkcs7_message *pkcs7, struct pkcs7_signed_info *sinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In crypto/asymmetric_keys/pkcs7_verify.c (0)
Location: crypto/asymmetric_keys/pkcs7_verify.c:193
Inline: False
Direct callers:
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify
```
**Symbols:**

```
ffffffff81727940-ffffffff81727d1a: pkcs7_verify_sig_chain (STB_LOCAL)
ffffffff82075976-ffffffff820759c6: pkcs7_verify_sig_chain.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int pkcs7_verify_sig_chain(struct pkcs7_message *pkcs7, struct pkcs7_signed_info *sinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In crypto/asymmetric_keys/pkcs7_verify.c (0)
Location: crypto/asymmetric_keys/pkcs7_verify.c:193
Inline: False
Direct callers:
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify
```
**Symbols:**

```
ffffffff81763d90-ffffffff8176416a: pkcs7_verify_sig_chain (STB_LOCAL)
ffffffff820f57c8-ffffffff820f5818: pkcs7_verify_sig_chain.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int pkcs7_verify_sig_chain(struct pkcs7_message *pkcs7, struct pkcs7_signed_info *sinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In crypto/asymmetric_keys/pkcs7_verify.c (0)
Location: crypto/asymmetric_keys/pkcs7_verify.c:193
Inline: False
Direct callers:
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify
```
**Symbols:**

```
ffffffff817a59b0-ffffffff817a5d8a: pkcs7_verify_sig_chain (STB_LOCAL)
ffffffff821d2a4b-ffffffff821d2a9b: pkcs7_verify_sig_chain.cold (STB_LOCAL)
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
In crypto/asymmetric_keys/pkcs7_verify.c (ffff8000105d8700)
Location: crypto/asymmetric_keys/pkcs7_verify.c:200
Inline: True
Direct callers:
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify
```
**Symbols:**

```
ffff8000105d8700-ffff8000105d8ab4: pkcs7_verify_sig_chain.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int pkcs7_verify_sig_chain(struct pkcs7_message *pkcs7, struct pkcs7_signed_info *sinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/pkcs7_verify.c (c0785bac)
Location: crypto/asymmetric_keys/pkcs7_verify.c:200
Inline: False
Direct callers:
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify
```
**Symbols:**

```
c0785bac-c0786018: pkcs7_verify_sig_chain (STB_LOCAL)
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
In crypto/asymmetric_keys/pkcs7_verify.c (c000000000767e10)
Location: crypto/asymmetric_keys/pkcs7_verify.c:200
Inline: True
Direct callers:
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify
```
**Symbols:**

```
c000000000767e10-c000000000768318: pkcs7_verify_sig_chain.isra.0 (STB_LOCAL)
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
In crypto/asymmetric_keys/pkcs7_verify.c (ffffffe00041c2e4)
Location: crypto/asymmetric_keys/pkcs7_verify.c:200
Inline: True
Direct callers:
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify
```
**Symbols:**

```
ffffffe00041c2e4-ffffffe00041c6ca: pkcs7_verify_sig_chain.isra.0 (STB_LOCAL)
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
Location: crypto/asymmetric_keys/pkcs7_verify.c:200
Inline: True
Direct callers:
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify
```
**Symbols:**

```
ffffffff814d4730-ffffffff814d4aa4: pkcs7_verify_sig_chain.isra.0 (STB_LOCAL)
ffffffff814d5090-ffffffff814d50d4: pkcs7_verify_sig_chain.isra.0.cold (STB_LOCAL)
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
Location: crypto/asymmetric_keys/pkcs7_verify.c:200
Inline: True
Direct callers:
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify
```
**Symbols:**

```
ffffffff814c5150-ffffffff814c54c4: pkcs7_verify_sig_chain.isra.0 (STB_LOCAL)
ffffffff814c5ab0-ffffffff814c5af4: pkcs7_verify_sig_chain.isra.0.cold (STB_LOCAL)
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
Location: crypto/asymmetric_keys/pkcs7_verify.c:200
Inline: True
Direct callers:
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify
```
**Symbols:**

```
ffffffff814d07c0-ffffffff814d0b34: pkcs7_verify_sig_chain.isra.0 (STB_LOCAL)
ffffffff814d1120-ffffffff814d1164: pkcs7_verify_sig_chain.isra.0.cold (STB_LOCAL)
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
Location: crypto/asymmetric_keys/pkcs7_verify.c:200
Inline: True
Direct callers:
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify
```
**Symbols:**

```
ffffffff814e9280-ffffffff814e95e8: pkcs7_verify_sig_chain.isra.0 (STB_LOCAL)
ffffffff814e9bd0-ffffffff814e9c14: pkcs7_verify_sig_chain.isra.0.cold (STB_LOCAL)
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
