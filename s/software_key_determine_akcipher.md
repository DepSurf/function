# Function: <code>software_key_determine_akcipher</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In crypto/asymmetric_keys/public_key.c (ffffffff81492f90)
Location: crypto/asymmetric_keys/public_key.c:66
Inline: True
Direct callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_query
```
**Symbols:**

```
ffffffff81492f90-ffffffff8149303a: software_key_determine_akcipher.isra.2 (STB_LOCAL)
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
In crypto/asymmetric_keys/public_key.c (ffffffff814c06b0)
Location: crypto/asymmetric_keys/public_key.c:63
Inline: True
Direct callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_query
```
**Symbols:**

```
ffffffff814c06b0-ffffffff814c0769: software_key_determine_akcipher.isra.0 (STB_LOCAL)
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
In crypto/asymmetric_keys/public_key.c (ffffffff814d9500)
Location: crypto/asymmetric_keys/public_key.c:63
Inline: True
Direct callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_query
```
**Symbols:**

```
ffffffff814d9500-ffffffff814d95b9: software_key_determine_akcipher.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int software_key_determine_akcipher(const char *encoding, const char *hash_algo, const struct public_key *pkey, char *alg_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/public_key.c (ffffffff81538d60)
Location: crypto/asymmetric_keys/public_key.c:63
Inline: False
Direct callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_query
```
**Symbols:**

```
ffffffff81538d60-ffffffff81538e1f: software_key_determine_akcipher (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int software_key_determine_akcipher(const char *encoding, const char *hash_algo, const struct public_key *pkey, char *alg_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/public_key.c (ffffffff81555b40)
Location: crypto/asymmetric_keys/public_key.c:65
Inline: False
Direct callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_query
```
**Symbols:**

```
ffffffff81555b40-ffffffff81555bff: software_key_determine_akcipher (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int software_key_determine_akcipher(const char *encoding, const char *hash_algo, const struct public_key *pkey, char *alg_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/public_key.c (ffffffff8155e2b0)
Location: crypto/asymmetric_keys/public_key.c:66
Inline: False
Direct callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_query
```
**Symbols:**

```
ffffffff8155e2b0-ffffffff8155e37e: software_key_determine_akcipher (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int software_key_determine_akcipher(const char *encoding, const char *hash_algo, const struct public_key *pkey, char *alg_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/public_key.c (ffffffff815bf5e0)
Location: crypto/asymmetric_keys/public_key.c:66
Inline: False
Direct callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_query
```
**Symbols:**

```
ffffffff815bf5e0-ffffffff815bf6ae: software_key_determine_akcipher (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int software_key_determine_akcipher(const struct public_key *pkey, const char *encoding, const char *hash_algo, char *alg_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/public_key.c (ffffffff816694a0)
Location: crypto/asymmetric_keys/public_key.c:68
Inline: False
Direct callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_query
```
**Symbols:**

```
ffffffff816694a0-ffffffff81669709: software_key_determine_akcipher (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int software_key_determine_akcipher(const struct public_key *pkey, const char *encoding, const char *hash_algo, char *alg_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/public_key.c (ffffffff81723d90)
Location: crypto/asymmetric_keys/public_key.c:68
Inline: False
Direct callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_query
```
**Symbols:**

```
ffffffff81723d90-ffffffff81723ff9: software_key_determine_akcipher (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int software_key_determine_akcipher(const struct public_key *pkey, const char *encoding, const char *hash_algo, char *alg_name, bool *sig, enum kernel_pkey_operation op);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/public_key.c (ffffffff81760110)
Location: crypto/asymmetric_keys/public_key.c:67
Inline: False
Direct callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_query
```
**Symbols:**

```
ffffffff81760110-ffffffff817603c0: software_key_determine_akcipher (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int software_key_determine_akcipher(const struct public_key *pkey, const char *encoding, const char *hash_algo, char *alg_name, bool *sig, enum kernel_pkey_operation op);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/public_key.c (ffffffff817a1a40)
Location: crypto/asymmetric_keys/public_key.c:67
Inline: False
Direct callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_query
```
**Symbols:**

```
ffffffff817a1a40-ffffffff817a1d1d: software_key_determine_akcipher (STB_LOCAL)
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
In crypto/asymmetric_keys/public_key.c (ffff8000105d56e8)
Location: crypto/asymmetric_keys/public_key.c:63
Inline: True
Direct callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_query
```
**Symbols:**

```
ffff8000105d56e8-ffff8000105d57bc: software_key_determine_akcipher.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int software_key_determine_akcipher(const char *encoding, const char *hash_algo, const struct public_key *pkey, char *alg_name);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/public_key.c (c0782f14)
Location: crypto/asymmetric_keys/public_key.c:63
Inline: True
Direct callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_query
```
**Symbols:**

```
c0782f14-c0782fd8: software_key_determine_akcipher (STB_LOCAL)
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
In crypto/asymmetric_keys/public_key.c (c000000000763b20)
Location: crypto/asymmetric_keys/public_key.c:63
Inline: True
Direct callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_query
```
**Symbols:**

```
c000000000763b20-c000000000763eb8: software_key_determine_akcipher.isra.0 (STB_LOCAL)
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
In crypto/asymmetric_keys/public_key.c (ffffffe0004198a6)
Location: crypto/asymmetric_keys/public_key.c:63
Inline: True
Direct callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_query
```
**Symbols:**

```
ffffffe0004198a6-ffffffe000419962: software_key_determine_akcipher.isra.0 (STB_LOCAL)
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
In crypto/asymmetric_keys/public_key.c (ffffffff814d1ae0)
Location: crypto/asymmetric_keys/public_key.c:63
Inline: True
Direct callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_query
```
**Symbols:**

```
ffffffff814d1ae0-ffffffff814d1b99: software_key_determine_akcipher.isra.0 (STB_LOCAL)
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
In crypto/asymmetric_keys/public_key.c (ffffffff814c2500)
Location: crypto/asymmetric_keys/public_key.c:63
Inline: True
Direct callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_query
```
**Symbols:**

```
ffffffff814c2500-ffffffff814c25b9: software_key_determine_akcipher.isra.0 (STB_LOCAL)
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
In crypto/asymmetric_keys/public_key.c (ffffffff814cdb70)
Location: crypto/asymmetric_keys/public_key.c:63
Inline: True
Direct callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_query
```
**Symbols:**

```
ffffffff814cdb70-ffffffff814cdc29: software_key_determine_akcipher.isra.0 (STB_LOCAL)
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
In crypto/asymmetric_keys/public_key.c (ffffffff814e6640)
Location: crypto/asymmetric_keys/public_key.c:63
Inline: True
Direct callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_query
```
**Symbols:**

```
ffffffff814e6640-ffffffff814e66f9: software_key_determine_akcipher.isra.0 (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param reordered. </b>
<code>encoding, hash_algo, pkey, alg_name</code> ➡️ <code>pkey, encoding, hash_algo, alg_name</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool *sig</code>
</li>
<li>
<b>Param added. </b>
<code>enum kernel_pkey_operation op</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
</ul>
