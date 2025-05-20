# Function: <code>integrity_digsig_verify</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int integrity_digsig_verify(const unsigned int id, const char *sig, int siglen, const char *digest, int digestlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/digsig.c (ffffffff81396680)
Location: security/integrity/digsig.c:36
Inline: False
Direct callers:
  - security/integrity/ima/ima_appraise.c:ima_appraise_measurement
  - security/integrity/evm/evm_main.c:evm_verify_hmac
```
**Symbols:**

```
ffffffff81396680-ffffffff81396786: integrity_digsig_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int integrity_digsig_verify(const unsigned int id, const char *sig, int siglen, const char *digest, int digestlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/digsig.c (ffffffff813d2400)
Location: security/integrity/digsig.c:51
Inline: False
Direct callers:
  - security/integrity/ima/ima_appraise.c:ima_appraise_measurement
  - security/integrity/evm/evm_main.c:evm_verify_hmac
```
**Symbols:**

```
ffffffff813d2400-ffffffff813d2519: integrity_digsig_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int integrity_digsig_verify(const unsigned int id, const char *sig, int siglen, const char *digest, int digestlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/digsig.c (ffffffff813e9b20)
Location: security/integrity/digsig.c:51
Inline: False
Direct callers:
  - security/integrity/ima/ima_appraise.c:ima_appraise_measurement
  - security/integrity/evm/evm_main.c:evm_verify_hmac
```
**Symbols:**

```
ffffffff813e9b20-ffffffff813e9c39: integrity_digsig_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int integrity_digsig_verify(const unsigned int id, const char *sig, int siglen, const char *digest, int digestlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/digsig.c (ffffffff813f5f20)
Location: security/integrity/digsig.c:51
Inline: False
Direct callers:
  - security/integrity/ima/ima_appraise.c:ima_appraise_measurement
  - security/integrity/evm/evm_main.c:evm_verify_hmac
```
**Symbols:**

```
ffffffff813f5f20-ffffffff813f6039: integrity_digsig_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int integrity_digsig_verify(const unsigned int id, const char *sig, int siglen, const char *digest, int digestlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/digsig.c (ffffffff8141e020)
Location: security/integrity/digsig.c:51
Inline: False
Direct callers:
  - security/integrity/ima/ima_appraise.c:ima_appraise_measurement
  - security/integrity/evm/evm_main.c:evm_verify_hmac
```
**Symbols:**

```
ffffffff8141e020-ffffffff8141e139: integrity_digsig_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int integrity_digsig_verify(const unsigned int id, const char *sig, int siglen, const char *digest, int digestlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/digsig.c (0)
Location: security/integrity/digsig.c:52
Inline: False
Direct callers:
  - security/integrity/ima/ima_appraise.c:ima_appraise_measurement
  - security/integrity/evm/evm_main.c:evm_verify_hmac
```
**Symbols:**

```
ffffffff814503c9-ffffffff814503ee: integrity_digsig_verify.cold.1 (STB_LOCAL)
ffffffff814502d0-ffffffff814503c9: integrity_digsig_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int integrity_digsig_verify(const unsigned int id, const char *sig, int siglen, const char *digest, int digestlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/digsig.c (0)
Location: security/integrity/digsig.c:46
Inline: False
Direct callers:
  - security/integrity/ima/ima_appraise.c:ima_appraise_measurement
  - security/integrity/evm/evm_main.c:evm_verify_hmac
```
**Symbols:**

```
ffffffff8146d369-ffffffff8146d38e: integrity_digsig_verify.cold.0 (STB_LOCAL)
ffffffff8146d270-ffffffff8146d369: integrity_digsig_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int integrity_digsig_verify(const unsigned int id, const char *sig, int siglen, const char *digest, int digestlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/digsig.c (0)
Location: security/integrity/digsig.c:42
Inline: False
Direct callers:
  - security/integrity/ima/ima_appraise.c:ima_appraise_measurement
  - security/integrity/ima/ima_appraise.c:ima_appraise_measurement
  - security/integrity/evm/evm_main.c:evm_verify_hmac
```
**Symbols:**

```
ffffffff8149aa53-ffffffff8149aa78: integrity_digsig_verify.cold (STB_LOCAL)
ffffffff8149a970-ffffffff8149aa53: integrity_digsig_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int integrity_digsig_verify(const unsigned int id, const char *sig, int siglen, const char *digest, int digestlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/digsig.c (ffffffff814b4be0)
Location: security/integrity/digsig.c:61
Inline: False
Direct callers:
  - security/integrity/ima/ima_appraise.c:ima_appraise_measurement
  - security/integrity/ima/ima_appraise.c:ima_appraise_measurement
  - security/integrity/evm/evm_main.c:evm_verify_hmac
```
**Symbols:**

```
ffffffff814b4be0-ffffffff814b4c6f: integrity_digsig_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int integrity_digsig_verify(const unsigned int id, const char *sig, int siglen, const char *digest, int digestlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/digsig.c (ffffffff81514130)
Location: security/integrity/digsig.c:59
Inline: False
Direct callers:
  - security/integrity/ima/ima_appraise.c:xattr_verify
  - security/integrity/ima/ima_appraise.c:xattr_verify
  - security/integrity/evm/evm_main.c:evm_verify_hmac
```
**Symbols:**

```
ffffffff81514130-ffffffff815141bf: integrity_digsig_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int integrity_digsig_verify(const unsigned int id, const char *sig, int siglen, const char *digest, int digestlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/digsig.c (ffffffff815312b0)
Location: security/integrity/digsig.c:60
Inline: False
Direct callers:
  - security/integrity/ima/ima_appraise.c:xattr_verify
  - security/integrity/ima/ima_appraise.c:xattr_verify
  - security/integrity/evm/evm_main.c:evm_verify_hmac
```
**Symbols:**

```
ffffffff815312b0-ffffffff8153133f: integrity_digsig_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int integrity_digsig_verify(const unsigned int id, const char *sig, int siglen, const char *digest, int digestlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/digsig.c (ffffffff815396e0)
Location: security/integrity/digsig.c:60
Inline: False
Direct callers:
  - security/integrity/ima/ima_appraise.c:xattr_verify
  - security/integrity/ima/ima_appraise.c:xattr_verify
  - security/integrity/evm/evm_main.c:evm_verify_hmac
```
**Symbols:**

```
ffffffff815396e0-ffffffff8153976f: integrity_digsig_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int integrity_digsig_verify(const unsigned int id, const char *sig, int siglen, const char *digest, int digestlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/digsig.c (ffffffff81598030)
Location: security/integrity/digsig.c:60
Inline: False
Direct callers:
  - security/integrity/ima/ima_appraise.c:xattr_verify
  - security/integrity/ima/ima_appraise.c:xattr_verify
  - security/integrity/evm/evm_main.c:evm_verify_hmac
```
**Symbols:**

```
ffffffff81598030-ffffffff815980bf: integrity_digsig_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int integrity_digsig_verify(const unsigned int id, const char *sig, int siglen, const char *digest, int digestlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/digsig.c (ffffffff8163c850)
Location: security/integrity/digsig.c:61
Inline: False
Direct callers:
  - security/integrity/ima/ima_appraise.c:xattr_verify
  - security/integrity/ima/ima_appraise.c:xattr_verify
  - security/integrity/ima/ima_appraise.c:xattr_verify
  - security/integrity/evm/evm_main.c:evm_verify_hmac
```
**Symbols:**

```
ffffffff8163c850-ffffffff8163c919: integrity_digsig_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int integrity_digsig_verify(const unsigned int id, const char *sig, int siglen, const char *digest, int digestlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/digsig.c (ffffffff816f40d0)
Location: security/integrity/digsig.c:61
Inline: False
Direct callers:
  - security/integrity/ima/ima_appraise.c:xattr_verify
  - security/integrity/ima/ima_appraise.c:xattr_verify
  - security/integrity/ima/ima_appraise.c:xattr_verify
  - security/integrity/evm/evm_main.c:evm_verify_hmac
```
**Symbols:**

```
ffffffff816f40d0-ffffffff816f4199: integrity_digsig_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int integrity_digsig_verify(const unsigned int id, const char *sig, int siglen, const char *digest, int digestlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/digsig.c (ffffffff8172e200)
Location: security/integrity/digsig.c:61
Inline: False
Direct callers:
  - security/integrity/ima/ima_appraise.c:xattr_verify
  - security/integrity/ima/ima_appraise.c:xattr_verify
  - security/integrity/ima/ima_appraise.c:xattr_verify
  - security/integrity/evm/evm_main.c:evm_verify_hmac
```
**Symbols:**

```
ffffffff8172e200-ffffffff8172e2c9: integrity_digsig_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int integrity_digsig_verify(const unsigned int id, const char *sig, int siglen, const char *digest, int digestlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/digsig.c (ffffffff8176eb60)
Location: security/integrity/digsig.c:61
Inline: False
Direct callers:
  - security/integrity/ima/ima_appraise.c:xattr_verify
  - security/integrity/ima/ima_appraise.c:xattr_verify
  - security/integrity/ima/ima_appraise.c:xattr_verify
  - security/integrity/evm/evm_main.c:evm_verify_hmac
```
**Symbols:**

```
ffffffff8176eb60-ffffffff8176ec29: integrity_digsig_verify (STB_GLOBAL)
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
int integrity_digsig_verify(const unsigned int id, const char *sig, int siglen, const char *digest, int digestlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/digsig.c (ffff8000105acd68)
Location: security/integrity/digsig.c:61
Inline: False
Direct callers:
  - security/integrity/ima/ima_appraise.c:ima_appraise_measurement
  - security/integrity/ima/ima_appraise.c:ima_appraise_measurement
  - security/integrity/evm/evm_main.c:evm_verify_hmac
```
**Symbols:**

```
ffff8000105acd68-ffff8000105ace40: integrity_digsig_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int integrity_digsig_verify(const unsigned int id, const char *sig, int siglen, const char *digest, int digestlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/digsig.c (c075c620)
Location: security/integrity/digsig.c:61
Inline: False
Direct callers:
  - security/integrity/ima/ima_appraise.c:ima_appraise_measurement
  - security/integrity/ima/ima_appraise.c:ima_appraise_measurement
  - security/integrity/evm/evm_main.c:evm_verify_hmac
```
**Symbols:**

```
c075c620-c075c6c4: integrity_digsig_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int integrity_digsig_verify(const unsigned int id, const char *sig, int siglen, const char *digest, int digestlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/digsig.c (c00000000072b290)
Location: security/integrity/digsig.c:61
Inline: False
Direct callers:
  - security/integrity/ima/ima_appraise.c:ima_appraise_measurement
  - security/integrity/ima/ima_appraise.c:ima_appraise_measurement
  - security/integrity/evm/evm_main.c:evm_verify_hmac
```
**Symbols:**

```
c00000000072b290-c00000000072b3cc: integrity_digsig_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int integrity_digsig_verify(const unsigned int id, const char *sig, int siglen, const char *digest, int digestlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/digsig.c (ffffffe0003f5398)
Location: security/integrity/digsig.c:61
Inline: False
Direct callers:
  - security/integrity/ima/ima_appraise.c:ima_appraise_measurement
  - security/integrity/ima/ima_appraise.c:ima_appraise_measurement
  - security/integrity/evm/evm_main.c:evm_verify_hmac
```
**Symbols:**

```
ffffffe0003f5398-ffffffe0003f5436: integrity_digsig_verify (STB_GLOBAL)
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
int integrity_digsig_verify(const unsigned int id, const char *sig, int siglen, const char *digest, int digestlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/digsig.c (ffffffff814ad1c0)
Location: security/integrity/digsig.c:61
Inline: False
Direct callers:
  - security/integrity/ima/ima_appraise.c:ima_appraise_measurement
  - security/integrity/ima/ima_appraise.c:ima_appraise_measurement
  - security/integrity/evm/evm_main.c:evm_verify_hmac
```
**Symbols:**

```
ffffffff814ad1c0-ffffffff814ad24f: integrity_digsig_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int integrity_digsig_verify(const unsigned int id, const char *sig, int siglen, const char *digest, int digestlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/digsig.c (ffffffff8149dbe0)
Location: security/integrity/digsig.c:61
Inline: False
Direct callers:
  - security/integrity/ima/ima_appraise.c:ima_appraise_measurement
  - security/integrity/ima/ima_appraise.c:ima_appraise_measurement
  - security/integrity/evm/evm_main.c:evm_verify_hmac
```
**Symbols:**

```
ffffffff8149dbe0-ffffffff8149dc6f: integrity_digsig_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int integrity_digsig_verify(const unsigned int id, const char *sig, int siglen, const char *digest, int digestlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/digsig.c (ffffffff814a9260)
Location: security/integrity/digsig.c:61
Inline: False
Direct callers:
  - security/integrity/ima/ima_appraise.c:ima_appraise_measurement
  - security/integrity/ima/ima_appraise.c:ima_appraise_measurement
  - security/integrity/evm/evm_main.c:evm_verify_hmac
```
**Symbols:**

```
ffffffff814a9260-ffffffff814a92ef: integrity_digsig_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int integrity_digsig_verify(const unsigned int id, const char *sig, int siglen, const char *digest, int digestlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/digsig.c (ffffffff814c1c70)
Location: security/integrity/digsig.c:61
Inline: False
Direct callers:
  - security/integrity/ima/ima_appraise.c:ima_appraise_measurement
  - security/integrity/ima/ima_appraise.c:ima_appraise_measurement
  - security/integrity/evm/evm_main.c:evm_verify_hmac
```
**Symbols:**

```
ffffffff814c1c70-ffffffff814c1cff: integrity_digsig_verify (STB_GLOBAL)
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
