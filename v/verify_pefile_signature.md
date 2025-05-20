# Function: <code>verify_pefile_signature</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int verify_pefile_signature(const void *pebuf, unsigned int pelen, struct key *trusted_keyring, enum key_being_used_for usage, bool *_trusted);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/verify_pefile.c (ffffffff813af9a0)
Location: crypto/asymmetric_keys/verify_pefile.c:420
Inline: False
Direct callers:
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_verify_sig
```
**Symbols:**

```
ffffffff813af9a0-ffffffff813aff94: verify_pefile_signature (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int verify_pefile_signature(const void *pebuf, unsigned int pelen, struct key *trusted_keys, enum key_being_used_for usage);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/verify_pefile.c (ffffffff813f3060)
Location: crypto/asymmetric_keys/verify_pefile.c:419
Inline: False
Direct callers:
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_verify_sig
```
**Symbols:**

```
ffffffff813f3060-ffffffff813f3a3a: verify_pefile_signature (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int verify_pefile_signature(const void *pebuf, unsigned int pelen, struct key *trusted_keys, enum key_being_used_for usage);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/verify_pefile.c (ffffffff8140c8d0)
Location: crypto/asymmetric_keys/verify_pefile.c:419
Inline: False
Direct callers:
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_verify_sig
```
**Symbols:**

```
ffffffff8140c8d0-ffffffff8140d2aa: verify_pefile_signature (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int verify_pefile_signature(const void *pebuf, unsigned int pelen, struct key *trusted_keys, enum key_being_used_for usage);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/verify_pefile.c (ffffffff8141aa20)
Location: crypto/asymmetric_keys/verify_pefile.c:419
Inline: False
Direct callers:
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_verify_sig
```
**Symbols:**

```
ffffffff8141aa20-ffffffff8141af49: verify_pefile_signature (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int verify_pefile_signature(const void *pebuf, unsigned int pelen, struct key *trusted_keys, enum key_being_used_for usage);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/verify_pefile.c (ffffffff81445180)
Location: crypto/asymmetric_keys/verify_pefile.c:419
Inline: False
Direct callers:
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_verify_sig
```
**Symbols:**

```
ffffffff81445180-ffffffff81445b7f: verify_pefile_signature (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int verify_pefile_signature(const void *pebuf, unsigned int pelen, struct key *trusted_keys, enum key_being_used_for usage);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/verify_pefile.c (ffffffff814780b0)
Location: crypto/asymmetric_keys/verify_pefile.c:419
Inline: False
Direct callers:
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_verify_sig
```
**Symbols:**

```
ffffffff814780b0-ffffffff81478aae: verify_pefile_signature (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int verify_pefile_signature(const void *pebuf, unsigned int pelen, struct key *trusted_keys, enum key_being_used_for usage);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/verify_pefile.c (ffffffff814962d0)
Location: crypto/asymmetric_keys/verify_pefile.c:419
Inline: False
Direct callers:
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_verify_sig
```
**Symbols:**

```
ffffffff814962d0-ffffffff81496ce3: verify_pefile_signature (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int verify_pefile_signature(const void *pebuf, unsigned int pelen, struct key *trusted_keys, enum key_being_used_for usage);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/verify_pefile.c (ffffffff814c41c0)
Location: crypto/asymmetric_keys/verify_pefile.c:416
Inline: False
Direct callers:
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_verify_sig
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_verify_sig
```
**Symbols:**

```
ffffffff814c41c0-ffffffff814c46f9: verify_pefile_signature (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int verify_pefile_signature(const void *pebuf, unsigned int pelen, struct key *trusted_keys, enum key_being_used_for usage);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/verify_pefile.c (ffffffff814dd0a0)
Location: crypto/asymmetric_keys/verify_pefile.c:416
Inline: False
Direct callers:
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_verify_sig
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_verify_sig
```
**Symbols:**

```
ffffffff814dd0a0-ffffffff814dd5d9: verify_pefile_signature (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int verify_pefile_signature(const void *pebuf, unsigned int pelen, struct key *trusted_keys, enum key_being_used_for usage);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/verify_pefile.c (ffffffff8153ce70)
Location: crypto/asymmetric_keys/verify_pefile.c:416
Inline: False
Direct callers:
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_verify_sig
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_verify_sig
```
**Symbols:**

```
ffffffff8153ce70-ffffffff8153cf56: verify_pefile_signature (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int verify_pefile_signature(const void *pebuf, unsigned int pelen, struct key *trusted_keys, enum key_being_used_for usage);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/verify_pefile.c (ffffffff815599d0)
Location: crypto/asymmetric_keys/verify_pefile.c:416
Inline: False
Direct callers:
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_verify_sig
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_verify_sig
```
**Symbols:**

```
ffffffff815599d0-ffffffff81559ab6: verify_pefile_signature (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int verify_pefile_signature(const void *pebuf, unsigned int pelen, struct key *trusted_keys, enum key_being_used_for usage);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/verify_pefile.c (ffffffff815622e0)
Location: crypto/asymmetric_keys/verify_pefile.c:416
Inline: False
Direct callers:
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_verify_sig
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_verify_sig
```
**Symbols:**

```
ffffffff815622e0-ffffffff815623c6: verify_pefile_signature (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int verify_pefile_signature(const void *pebuf, unsigned int pelen, struct key *trusted_keys, enum key_being_used_for usage);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/verify_pefile.c (ffffffff815c36e0)
Location: crypto/asymmetric_keys/verify_pefile.c:416
Inline: False
Direct callers:
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_verify_sig
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_verify_sig
```
**Symbols:**

```
ffffffff815c36e0-ffffffff815c37c3: verify_pefile_signature (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int verify_pefile_signature(const void *pebuf, unsigned int pelen, struct key *trusted_keys, enum key_being_used_for usage);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/verify_pefile.c (ffffffff8166dcc0)
Location: crypto/asymmetric_keys/verify_pefile.c:416
Inline: False
Direct callers:
  - kernel/kexec_file.c:kexec_kernel_verify_pe_sig
  - kernel/kexec_file.c:kexec_kernel_verify_pe_sig
```
**Symbols:**

```
ffffffff8166dcc0-ffffffff8166ddb5: verify_pefile_signature (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int verify_pefile_signature(const void *pebuf, unsigned int pelen, struct key *trusted_keys, enum key_being_used_for usage);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/verify_pefile.c (ffffffff81728dc0)
Location: crypto/asymmetric_keys/verify_pefile.c:416
Inline: False
Direct callers:
  - kernel/kexec_file.c:kexec_kernel_verify_pe_sig
  - kernel/kexec_file.c:kexec_kernel_verify_pe_sig
```
**Symbols:**

```
ffffffff81728dc0-ffffffff81728eb5: verify_pefile_signature (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int verify_pefile_signature(const void *pebuf, unsigned int pelen, struct key *trusted_keys, enum key_being_used_for usage);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/verify_pefile.c (ffffffff81765110)
Location: crypto/asymmetric_keys/verify_pefile.c:420
Inline: False
Direct callers:
  - kernel/kexec_file.c:kexec_kernel_verify_pe_sig
  - kernel/kexec_file.c:kexec_kernel_verify_pe_sig
```
**Symbols:**

```
ffffffff81765110-ffffffff81765205: verify_pefile_signature (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int verify_pefile_signature(const void *pebuf, unsigned int pelen, struct key *trusted_keys, enum key_being_used_for usage);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/verify_pefile.c (ffffffff817a6d30)
Location: crypto/asymmetric_keys/verify_pefile.c:420
Inline: False
Direct callers:
  - kernel/kexec_file.c:kexec_kernel_verify_pe_sig
  - kernel/kexec_file.c:kexec_kernel_verify_pe_sig
```
**Symbols:**

```
ffffffff817a6d30-ffffffff817a6e25: verify_pefile_signature (STB_GLOBAL)
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
int verify_pefile_signature(const void *pebuf, unsigned int pelen, struct key *trusted_keys, enum key_being_used_for usage);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/verify_pefile.c (ffff8000105d9620)
Location: crypto/asymmetric_keys/verify_pefile.c:416
Inline: False
```
**Symbols:**

```
ffff8000105d9620-ffff8000105d9b58: verify_pefile_signature (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int verify_pefile_signature(const void *pebuf, unsigned int pelen, struct key *trusted_keys, enum key_being_used_for usage);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/verify_pefile.c (c0786954)
Location: crypto/asymmetric_keys/verify_pefile.c:416
Inline: False
```
**Symbols:**

```
c0786954-c07870a0: verify_pefile_signature (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int verify_pefile_signature(const void *pebuf, unsigned int pelen, struct key *trusted_keys, enum key_being_used_for usage);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/verify_pefile.c (c0000000007696e0)
Location: crypto/asymmetric_keys/verify_pefile.c:416
Inline: False
```
**Symbols:**

```
c0000000007696e0-c000000000769d88: verify_pefile_signature (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int verify_pefile_signature(const void *pebuf, unsigned int pelen, struct key *trusted_keys, enum key_being_used_for usage);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/verify_pefile.c (ffffffe00041ccb0)
Location: crypto/asymmetric_keys/verify_pefile.c:416
Inline: False
```
**Symbols:**

```
ffffffe00041ccb0-ffffffe00041d590: verify_pefile_signature (STB_GLOBAL)
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
int verify_pefile_signature(const void *pebuf, unsigned int pelen, struct key *trusted_keys, enum key_being_used_for usage);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/verify_pefile.c (ffffffff814d5680)
Location: crypto/asymmetric_keys/verify_pefile.c:416
Inline: False
Direct callers:
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_verify_sig
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_verify_sig
```
**Symbols:**

```
ffffffff814d5680-ffffffff814d5bb9: verify_pefile_signature (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int verify_pefile_signature(const void *pebuf, unsigned int pelen, struct key *trusted_keys, enum key_being_used_for usage);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/verify_pefile.c (ffffffff814c60a0)
Location: crypto/asymmetric_keys/verify_pefile.c:416
Inline: False
Direct callers:
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_verify_sig
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_verify_sig
```
**Symbols:**

```
ffffffff814c60a0-ffffffff814c65d9: verify_pefile_signature (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int verify_pefile_signature(const void *pebuf, unsigned int pelen, struct key *trusted_keys, enum key_being_used_for usage);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/verify_pefile.c (ffffffff814d1710)
Location: crypto/asymmetric_keys/verify_pefile.c:416
Inline: False
```
**Symbols:**

```
ffffffff814d1710-ffffffff814d1c49: verify_pefile_signature (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int verify_pefile_signature(const void *pebuf, unsigned int pelen, struct key *trusted_keys, enum key_being_used_for usage);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/verify_pefile.c (ffffffff814ea1c0)
Location: crypto/asymmetric_keys/verify_pefile.c:416
Inline: False
Direct callers:
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_verify_sig
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_verify_sig
```
**Symbols:**

```
ffffffff814ea1c0-ffffffff814ea6f9: verify_pefile_signature (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct key *trusted_keys</code>
</li>
<li>
<b>Param removed. </b>
<code>struct key *trusted_keyring</code>
</li>
<li>
<b>Param removed. </b>
<code>bool *_trusted</code>
</li>
</ul>
</details>
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
