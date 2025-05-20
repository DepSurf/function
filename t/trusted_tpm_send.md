# Function: <code>trusted_tpm_send</code>

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
In security/keys/trusted.c (ffffffff813369d5)
Location: security/keys/trusted.c:358
Inline: True
Inline callers:
  - security/keys/trusted.c:oiap
  - security/keys/trusted.c:tpm_unseal
  - security/keys/trusted.c:key_seal
  - security/keys/trusted.c:key_seal
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
In security/keys/trusted.c (ffffffff8136d3c5)
Location: security/keys/trusted.c:358
Inline: True
Inline callers:
  - security/keys/trusted.c:key_seal
  - security/keys/trusted.c:key_seal
  - security/keys/trusted.c:tpm_unseal
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
In security/keys/trusted.c (ffffffff81383be5)
Location: security/keys/trusted.c:358
Inline: True
Inline callers:
  - security/keys/trusted.c:key_seal
  - security/keys/trusted.c:key_seal
  - security/keys/trusted.c:tpm_unseal
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
In security/keys/trusted.c (ffffffff813982a4)
Location: security/keys/trusted.c:358
Inline: True
Inline callers:
  - security/keys/trusted.c:key_seal
  - security/keys/trusted.c:key_seal
  - security/keys/trusted.c:tpm_unseal
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
In security/keys/trusted.c (ffffffff813bdab4)
Location: security/keys/trusted.c:358
Inline: True
Inline callers:
  - security/keys/trusted.c:key_seal
  - security/keys/trusted.c:key_seal
  - security/keys/trusted.c:tpm_unseal
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
In security/keys/trusted.c (ffffffff813eeb6b)
Location: security/keys/trusted.c:358
Inline: True
Inline callers:
  - security/keys/trusted.c:key_seal
  - security/keys/trusted.c:key_seal
  - security/keys/trusted.c:tpm_unseal
  - security/keys/trusted.c:oiap
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int trusted_tpm_send(unsigned char *cmd, size_t buflen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/trusted.c (ffffffff81409b0a)
Location: security/keys/trusted.c:360
Inline: True
Inline callers:
  - security/keys/trusted.c:key_seal
  - security/keys/trusted.c:key_seal
  - security/keys/trusted.c:tpm_unseal
  - security/keys/trusted.c:oiap
```
**Symbols:**

```
ffffffff81408b80-ffffffff81408ba2: trusted_tpm_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int trusted_tpm_send(unsigned char *cmd, size_t buflen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/trusted.c (ffffffff81436931)
Location: security/keys/trusted.c:364
Inline: True
Inline callers:
  - security/keys/trusted.c:tpm_unseal
  - security/keys/trusted.c:tpm_seal
  - security/keys/trusted.c:tpm_seal
```
**Symbols:**

```
ffffffff814356e0-ffffffff81435715: trusted_tpm_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int trusted_tpm_send(unsigned char *cmd, size_t buflen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/trusted.c (ffffffff814506d1)
Location: security/keys/trusted.c:364
Inline: True
Inline callers:
  - security/keys/trusted.c:tpm_unseal
  - security/keys/trusted.c:tpm_seal
  - security/keys/trusted.c:tpm_seal
```
**Symbols:**

```
ffffffff8144f480-ffffffff8144f4b5: trusted_tpm_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int trusted_tpm_send(unsigned char *cmd, size_t buflen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/trusted-keys/trusted_tpm1.c (ffffffff814a225d)
Location: security/keys/trusted-keys/trusted_tpm1.c:364
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_unseal
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_seal
  - security/keys/trusted-keys/trusted_tpm1.c:oiap
  - security/keys/trusted-keys/trusted_tpm1.c:osap
```
**Symbols:**

```
ffffffff814a0d90-ffffffff814a0dc5: trusted_tpm_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int trusted_tpm_send(unsigned char *cmd, size_t buflen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/trusted-keys/trusted_tpm1.c (ffffffff814bfc19)
Location: security/keys/trusted-keys/trusted_tpm1.c:364
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_unseal
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_seal
  - security/keys/trusted-keys/trusted_tpm1.c:oiap
  - security/keys/trusted-keys/trusted_tpm1.c:osap
```
**Symbols:**

```
ffffffff814be740-ffffffff814be775: trusted_tpm_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int trusted_tpm_send(unsigned char *cmd, size_t buflen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/trusted-keys/trusted_tpm1.c (ffffffff814c5e79)
Location: security/keys/trusted-keys/trusted_tpm1.c:357
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_unseal
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_seal
  - security/keys/trusted-keys/trusted_tpm1.c:oiap
  - security/keys/trusted-keys/trusted_tpm1.c:osap
```
**Symbols:**

```
ffffffff814c4a00-ffffffff814c4a35: trusted_tpm_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int trusted_tpm_send(unsigned char *cmd, size_t buflen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/trusted-keys/trusted_tpm1.c (ffffffff8151e899)
Location: security/keys/trusted-keys/trusted_tpm1.c:357
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_unseal
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_seal
  - security/keys/trusted-keys/trusted_tpm1.c:oiap
  - security/keys/trusted-keys/trusted_tpm1.c:osap
```
**Symbols:**

```
ffffffff8151d3e0-ffffffff8151d415: trusted_tpm_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int trusted_tpm_send(unsigned char *cmd, size_t buflen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/trusted-keys/trusted_tpm1.c (ffffffff815b1e78)
Location: security/keys/trusted-keys/trusted_tpm1.c:357
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_unseal
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_seal
  - security/keys/trusted-keys/trusted_tpm1.c:oiap
  - security/keys/trusted-keys/trusted_tpm1.c:osap
```
**Symbols:**

```
ffffffff815b0750-ffffffff815b0799: trusted_tpm_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int trusted_tpm_send(unsigned char *cmd, size_t buflen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/trusted-keys/trusted_tpm1.c (ffffffff8165c9e0)
Location: security/keys/trusted-keys/trusted_tpm1.c:357
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_unseal
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_seal
  - security/keys/trusted-keys/trusted_tpm1.c:oiap
  - security/keys/trusted-keys/trusted_tpm1.c:osap
```
**Symbols:**

```
ffffffff8165b150-ffffffff8165b199: trusted_tpm_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int trusted_tpm_send(unsigned char *cmd, size_t buflen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/trusted-keys/trusted_tpm1.c (ffffffff81695300)
Location: security/keys/trusted-keys/trusted_tpm1.c:357
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_unseal
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_seal
  - security/keys/trusted-keys/trusted_tpm1.c:oiap
  - security/keys/trusted-keys/trusted_tpm1.c:osap
```
**Symbols:**

```
ffffffff81693a40-ffffffff81693a89: trusted_tpm_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int trusted_tpm_send(unsigned char *cmd, size_t buflen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/trusted-keys/trusted_tpm1.c (ffffffff816d1930)
Location: security/keys/trusted-keys/trusted_tpm1.c:357
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_unseal
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_seal
  - security/keys/trusted-keys/trusted_tpm1.c:oiap
  - security/keys/trusted-keys/trusted_tpm1.c:osap
```
**Symbols:**

```
ffffffff816d0040-ffffffff816d0089: trusted_tpm_send (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int trusted_tpm_send(unsigned char *cmd, size_t buflen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/trusted.c (ffff80001053b8a8)
Location: security/keys/trusted.c:364
Inline: True
Inline callers:
  - security/keys/trusted.c:tpm_unseal
  - security/keys/trusted.c:tpm_seal
  - security/keys/trusted.c:tpm_seal
```
**Symbols:**

```
ffff80001053a298-ffff80001053a2e8: trusted_tpm_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int trusted_tpm_send(unsigned char *cmd, size_t buflen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/trusted.c (c06f1800)
Location: security/keys/trusted.c:364
Inline: True
Inline callers:
  - security/keys/trusted.c:tpm_unseal
  - security/keys/trusted.c:tpm_seal
  - security/keys/trusted.c:tpm_seal
```
**Symbols:**

```
c06f06e0-c06f072c: trusted_tpm_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int trusted_tpm_send(unsigned char *cmd, size_t buflen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/trusted.c (c00000000068aa9c)
Location: security/keys/trusted.c:364
Inline: True
Inline callers:
  - security/keys/trusted.c:tpm_unseal
  - security/keys/trusted.c:tpm_seal
  - security/keys/trusted.c:tpm_seal
```
**Symbols:**

```
c000000000688fd0-c000000000689040: trusted_tpm_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int trusted_tpm_send(unsigned char *cmd, size_t buflen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/trusted.c (ffffffe00039951c)
Location: security/keys/trusted.c:364
Inline: True
Inline callers:
  - security/keys/trusted.c:tpm_unseal
  - security/keys/trusted.c:tpm_seal
  - security/keys/trusted.c:tpm_seal
```
**Symbols:**

```
ffffffe000398508-ffffffe000398550: trusted_tpm_send (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int trusted_tpm_send(unsigned char *cmd, size_t buflen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/trusted.c (ffffffff81448cb1)
Location: security/keys/trusted.c:364
Inline: True
Inline callers:
  - security/keys/trusted.c:tpm_unseal
  - security/keys/trusted.c:tpm_seal
  - security/keys/trusted.c:tpm_seal
```
**Symbols:**

```
ffffffff81447a60-ffffffff81447a95: trusted_tpm_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int trusted_tpm_send(unsigned char *cmd, size_t buflen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/trusted.c (ffffffff81439701)
Location: security/keys/trusted.c:364
Inline: True
Inline callers:
  - security/keys/trusted.c:tpm_unseal
  - security/keys/trusted.c:tpm_seal
  - security/keys/trusted.c:tpm_seal
```
**Symbols:**

```
ffffffff814384b0-ffffffff814384e5: trusted_tpm_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int trusted_tpm_send(unsigned char *cmd, size_t buflen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/trusted.c (ffffffff81444d51)
Location: security/keys/trusted.c:364
Inline: True
Inline callers:
  - security/keys/trusted.c:tpm_unseal
  - security/keys/trusted.c:tpm_seal
  - security/keys/trusted.c:tpm_seal
```
**Symbols:**

```
ffffffff81443b00-ffffffff81443b35: trusted_tpm_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int trusted_tpm_send(unsigned char *cmd, size_t buflen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/trusted.c (ffffffff8145c081)
Location: security/keys/trusted.c:364
Inline: True
Inline callers:
  - security/keys/trusted.c:tpm_unseal
  - security/keys/trusted.c:tpm_seal
  - security/keys/trusted.c:tpm_seal
```
**Symbols:**

```
ffffffff8145ae30-ffffffff8145ae65: trusted_tpm_send (STB_GLOBAL)
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
