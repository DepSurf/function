# Function: <code>pkcs7_verify</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int pkcs7_verify(struct pkcs7_message *pkcs7, enum key_being_used_for usage);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/pkcs7_verify.c (ffffffff813aeb50)
Location: crypto/asymmetric_keys/pkcs7_verify.c:376
Inline: False
Direct callers:
  - certs/system_keyring.c:system_verify_data
  - crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature
```
**Symbols:**

```
ffffffff813aeb50-ffffffff813af488: pkcs7_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int pkcs7_verify(struct pkcs7_message *pkcs7, enum key_being_used_for usage);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/pkcs7_verify.c (ffffffff813f27f0)
Location: crypto/asymmetric_keys/pkcs7_verify.c:366
Inline: False
Direct callers:
  - certs/system_keyring.c:verify_pkcs7_signature
```
**Symbols:**

```
ffffffff813f27f0-ffffffff813f3013: pkcs7_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int pkcs7_verify(struct pkcs7_message *pkcs7, enum key_being_used_for usage);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/pkcs7_verify.c (ffffffff8140c060)
Location: crypto/asymmetric_keys/pkcs7_verify.c:366
Inline: False
Direct callers:
  - certs/system_keyring.c:verify_pkcs7_signature
```
**Symbols:**

```
ffffffff8140c060-ffffffff8140c883: pkcs7_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int pkcs7_verify(struct pkcs7_message *pkcs7, enum key_being_used_for usage);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/pkcs7_verify.c (ffffffff81419c70)
Location: crypto/asymmetric_keys/pkcs7_verify.c:380
Inline: False
Direct callers:
  - certs/system_keyring.c:verify_pkcs7_signature
```
**Symbols:**

```
ffffffff81419c70-ffffffff8141a539: pkcs7_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int pkcs7_verify(struct pkcs7_message *pkcs7, enum key_being_used_for usage);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/pkcs7_verify.c (ffffffff814447a0)
Location: crypto/asymmetric_keys/pkcs7_verify.c:376
Inline: False
Direct callers:
  - certs/system_keyring.c:verify_pkcs7_signature
```
**Symbols:**

```
ffffffff814447a0-ffffffff81445127: pkcs7_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int pkcs7_verify(struct pkcs7_message *pkcs7, enum key_being_used_for usage);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In crypto/asymmetric_keys/pkcs7_verify.c (0)
Location: crypto/asymmetric_keys/pkcs7_verify.c:376
Inline: False
Direct callers:
  - certs/system_keyring.c:verify_pkcs7_signature
```
**Symbols:**

```
ffffffff81477fa4-ffffffff814780a8: pkcs7_verify.cold.5 (STB_LOCAL)
ffffffff814779c0-ffffffff81477f35: pkcs7_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int pkcs7_verify(struct pkcs7_message *pkcs7, enum key_being_used_for usage);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In crypto/asymmetric_keys/pkcs7_verify.c (0)
Location: crypto/asymmetric_keys/pkcs7_verify.c:376
Inline: False
Direct callers:
  - certs/system_keyring.c:verify_pkcs7_signature
```
**Symbols:**

```
ffffffff81496191-ffffffff814962cf: pkcs7_verify.cold.4 (STB_LOCAL)
ffffffff814958d0-ffffffff81496142: pkcs7_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int pkcs7_verify(struct pkcs7_message *pkcs7, enum key_being_used_for usage);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In crypto/asymmetric_keys/pkcs7_verify.c (0)
Location: crypto/asymmetric_keys/pkcs7_verify.c:371
Inline: False
Direct callers:
  - certs/system_keyring.c:verify_pkcs7_signature
```
**Symbols:**

```
ffffffff814c3c36-ffffffff814c3cf0: pkcs7_verify.cold (STB_LOCAL)
ffffffff814c3970-ffffffff814c3b84: pkcs7_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int pkcs7_verify(struct pkcs7_message *pkcs7, enum key_being_used_for usage);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In crypto/asymmetric_keys/pkcs7_verify.c (0)
Location: crypto/asymmetric_keys/pkcs7_verify.c:404
Inline: False
Direct callers:
  - certs/system_keyring.c:verify_pkcs7_message_sig
```
**Symbols:**

```
ffffffff814dcb16-ffffffff814dcbd0: pkcs7_verify.cold (STB_LOCAL)
ffffffff814dc7b0-ffffffff814dc9c4: pkcs7_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int pkcs7_verify(struct pkcs7_message *pkcs7, enum key_being_used_for usage);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In crypto/asymmetric_keys/pkcs7_verify.c (0)
Location: crypto/asymmetric_keys/pkcs7_verify.c:404
Inline: False
Direct callers:
  - certs/system_keyring.c:verify_pkcs7_message_sig
```
**Symbols:**

```
ffffffff8153c432-ffffffff8153c4b6: pkcs7_verify.cold (STB_LOCAL)
ffffffff8153c1d0-ffffffff8153c2ba: pkcs7_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int pkcs7_verify(struct pkcs7_message *pkcs7, enum key_being_used_for usage);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In crypto/asymmetric_keys/pkcs7_verify.c (0)
Location: crypto/asymmetric_keys/pkcs7_verify.c:404
Inline: False
Direct callers:
  - certs/system_keyring.c:verify_pkcs7_message_sig
```
**Symbols:**

```
ffffffff81bf24a3-ffffffff81bf2527: pkcs7_verify.cold (STB_LOCAL)
ffffffff81558e70-ffffffff81558f5a: pkcs7_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int pkcs7_verify(struct pkcs7_message *pkcs7, enum key_being_used_for usage);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In crypto/asymmetric_keys/pkcs7_verify.c (0)
Location: crypto/asymmetric_keys/pkcs7_verify.c:403
Inline: False
Direct callers:
  - certs/system_keyring.c:verify_pkcs7_message_sig
```
**Symbols:**

```
ffffffff81be4433-ffffffff81be44eb: pkcs7_verify.cold (STB_LOCAL)
ffffffff81561690-ffffffff81561875: pkcs7_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int pkcs7_verify(struct pkcs7_message *pkcs7, enum key_being_used_for usage);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In crypto/asymmetric_keys/pkcs7_verify.c (0)
Location: crypto/asymmetric_keys/pkcs7_verify.c:403
Inline: False
Direct callers:
  - certs/system_keyring.c:verify_pkcs7_message_sig
```
**Symbols:**

```
ffffffff81cd7d32-ffffffff81cd7e72: pkcs7_verify.cold (STB_LOCAL)
ffffffff815c2a80-ffffffff815c2ca5: pkcs7_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int pkcs7_verify(struct pkcs7_message *pkcs7, enum key_being_used_for usage);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In crypto/asymmetric_keys/pkcs7_verify.c (0)
Location: crypto/asymmetric_keys/pkcs7_verify.c:394
Inline: False
Direct callers:
  - certs/system_keyring.c:verify_pkcs7_message_sig
```
**Symbols:**

```
ffffffff81e8afbb-ffffffff81e8b0dd: pkcs7_verify.cold (STB_LOCAL)
ffffffff8166cfa0-ffffffff8166d221: pkcs7_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int pkcs7_verify(struct pkcs7_message *pkcs7, enum key_being_used_for usage);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In crypto/asymmetric_keys/pkcs7_verify.c (0)
Location: crypto/asymmetric_keys/pkcs7_verify.c:394
Inline: False
Direct callers:
  - certs/system_keyring.c:verify_pkcs7_message_sig
```
**Symbols:**

```
ffffffff820759c6-ffffffff82075a6c: pkcs7_verify.cold (STB_LOCAL)
ffffffff81727fc0-ffffffff81728285: pkcs7_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int pkcs7_verify(struct pkcs7_message *pkcs7, enum key_being_used_for usage);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In crypto/asymmetric_keys/pkcs7_verify.c (0)
Location: crypto/asymmetric_keys/pkcs7_verify.c:394
Inline: False
Direct callers:
  - certs/system_keyring.c:verify_pkcs7_message_sig
```
**Symbols:**

```
ffffffff820f5818-ffffffff820f5864: pkcs7_verify.cold (STB_LOCAL)
ffffffff817643f0-ffffffff81764689: pkcs7_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int pkcs7_verify(struct pkcs7_message *pkcs7, enum key_being_used_for usage);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In crypto/asymmetric_keys/pkcs7_verify.c (0)
Location: crypto/asymmetric_keys/pkcs7_verify.c:394
Inline: False
Direct callers:
  - certs/system_keyring.c:verify_pkcs7_message_sig
```
**Symbols:**

```
ffffffff821d2a9b-ffffffff821d2ae7: pkcs7_verify.cold (STB_LOCAL)
ffffffff817a6010-ffffffff817a62a9: pkcs7_verify (STB_GLOBAL)
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
int pkcs7_verify(struct pkcs7_message *pkcs7, enum key_being_used_for usage);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/pkcs7_verify.c (ffff8000105d8d20)
Location: crypto/asymmetric_keys/pkcs7_verify.c:404
Inline: False
Direct callers:
  - certs/system_keyring.c:verify_pkcs7_message_sig
```
**Symbols:**

```
ffff8000105d8d20-ffff8000105d8fd4: pkcs7_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int pkcs7_verify(struct pkcs7_message *pkcs7, enum key_being_used_for usage);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/pkcs7_verify.c (c0786278)
Location: crypto/asymmetric_keys/pkcs7_verify.c:404
Inline: False
Direct callers:
  - certs/system_keyring.c:verify_pkcs7_message_sig
```
**Symbols:**

```
c0786278-c0786540: pkcs7_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int pkcs7_verify(struct pkcs7_message *pkcs7, enum key_being_used_for usage);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/pkcs7_verify.c (c000000000768670)
Location: crypto/asymmetric_keys/pkcs7_verify.c:404
Inline: False
Direct callers:
  - certs/system_keyring.c:verify_pkcs7_message_sig
```
**Symbols:**

```
c000000000768670-c000000000768bb4: pkcs7_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int pkcs7_verify(struct pkcs7_message *pkcs7, enum key_being_used_for usage);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/pkcs7_verify.c (ffffffe00041c8be)
Location: crypto/asymmetric_keys/pkcs7_verify.c:404
Inline: False
Direct callers:
  - certs/system_keyring.c:verify_pkcs7_message_sig
```
**Symbols:**

```
ffffffe00041c8be-ffffffe00041cb2c: pkcs7_verify (STB_GLOBAL)
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
int pkcs7_verify(struct pkcs7_message *pkcs7, enum key_being_used_for usage);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In crypto/asymmetric_keys/pkcs7_verify.c (0)
Location: crypto/asymmetric_keys/pkcs7_verify.c:404
Inline: False
Direct callers:
  - certs/system_keyring.c:verify_pkcs7_message_sig
```
**Symbols:**

```
ffffffff814d50f6-ffffffff814d51b0: pkcs7_verify.cold (STB_LOCAL)
ffffffff814d4d90-ffffffff814d4fa4: pkcs7_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int pkcs7_verify(struct pkcs7_message *pkcs7, enum key_being_used_for usage);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In crypto/asymmetric_keys/pkcs7_verify.c (0)
Location: crypto/asymmetric_keys/pkcs7_verify.c:404
Inline: False
Direct callers:
  - certs/system_keyring.c:verify_pkcs7_message_sig
```
**Symbols:**

```
ffffffff814c5b16-ffffffff814c5bd0: pkcs7_verify.cold (STB_LOCAL)
ffffffff814c57b0-ffffffff814c59c4: pkcs7_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int pkcs7_verify(struct pkcs7_message *pkcs7, enum key_being_used_for usage);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In crypto/asymmetric_keys/pkcs7_verify.c (0)
Location: crypto/asymmetric_keys/pkcs7_verify.c:404
Inline: False
Direct callers:
  - certs/system_keyring.c:verify_pkcs7_message_sig
```
**Symbols:**

```
ffffffff814d1186-ffffffff814d1240: pkcs7_verify.cold (STB_LOCAL)
ffffffff814d0e20-ffffffff814d1034: pkcs7_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int pkcs7_verify(struct pkcs7_message *pkcs7, enum key_being_used_for usage);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In crypto/asymmetric_keys/pkcs7_verify.c (0)
Location: crypto/asymmetric_keys/pkcs7_verify.c:404
Inline: False
Direct callers:
  - certs/system_keyring.c:verify_pkcs7_message_sig
```
**Symbols:**

```
ffffffff814e9c36-ffffffff814e9cf0: pkcs7_verify.cold (STB_LOCAL)
ffffffff814e98d0-ffffffff814e9ae4: pkcs7_verify (STB_GLOBAL)
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
