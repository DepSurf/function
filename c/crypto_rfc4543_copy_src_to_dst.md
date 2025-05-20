# Function: <code>crypto_rfc4543_copy_src_to_dst</code>

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
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/gcm.c (ffffffff81438fa9)
Location: crypto/gcm.c:1063
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_crypt
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
In crypto/gcm.c (ffffffff8146b2b9)
Location: crypto/gcm.c:1063
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_crypt
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int crypto_rfc4543_copy_src_to_dst(struct aead_request *req, bool enc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/gcm.c (ffffffff81489530)
Location: crypto/gcm.c:1063
Inline: False
Direct callers:
  - crypto/gcm.c:crypto_rfc4543_crypt
```
**Symbols:**

```
ffffffff81489530-ffffffff81489622: crypto_rfc4543_copy_src_to_dst (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int crypto_rfc4543_copy_src_to_dst(struct aead_request *req, bool enc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/gcm.c (ffffffff814b61f0)
Location: crypto/gcm.c:1030
Inline: False
Direct callers:
  - crypto/gcm.c:crypto_rfc4543_crypt
```
**Symbols:**

```
ffffffff814b61f0-ffffffff814b629b: crypto_rfc4543_copy_src_to_dst (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int crypto_rfc4543_copy_src_to_dst(struct aead_request *req, bool enc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/gcm.c (ffffffff814cf3f0)
Location: crypto/gcm.c:1019
Inline: False
Direct callers:
  - crypto/gcm.c:crypto_rfc4543_crypt
```
**Symbols:**

```
ffffffff814cf3f0-ffffffff814cf49b: crypto_rfc4543_copy_src_to_dst (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int crypto_rfc4543_copy_src_to_dst(struct aead_request *req, bool enc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/gcm.c (ffffffff8152e610)
Location: crypto/gcm.c:974
Inline: False
Direct callers:
  - crypto/gcm.c:crypto_rfc4543_crypt
```
**Symbols:**

```
ffffffff8152e610-ffffffff8152e6bb: crypto_rfc4543_copy_src_to_dst (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int crypto_rfc4543_copy_src_to_dst(struct aead_request *req, bool enc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/gcm.c (ffffffff8154b5b0)
Location: crypto/gcm.c:959
Inline: False
Direct callers:
  - crypto/gcm.c:crypto_rfc4543_crypt
```
**Symbols:**

```
ffffffff8154b5b0-ffffffff8154b65b: crypto_rfc4543_copy_src_to_dst (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int crypto_rfc4543_copy_src_to_dst(struct aead_request *req, bool enc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/gcm.c (ffffffff81553bc0)
Location: crypto/gcm.c:959
Inline: False
Direct callers:
  - crypto/gcm.c:crypto_rfc4543_crypt
```
**Symbols:**

```
ffffffff81553bc0-ffffffff81553c6b: crypto_rfc4543_copy_src_to_dst (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int crypto_rfc4543_copy_src_to_dst(struct aead_request *req, bool enc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/gcm.c (ffffffff815b4bf0)
Location: crypto/gcm.c:959
Inline: False
Direct callers:
  - crypto/gcm.c:crypto_rfc4543_crypt
```
**Symbols:**

```
ffffffff815b4bf0-ffffffff815b4c9b: crypto_rfc4543_copy_src_to_dst (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int crypto_rfc4543_copy_src_to_dst(struct aead_request *req, bool enc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/gcm.c (ffffffff8165db70)
Location: crypto/gcm.c:959
Inline: False
Direct callers:
  - crypto/gcm.c:crypto_rfc4543_crypt
```
**Symbols:**

```
ffffffff8165db70-ffffffff8165dc42: crypto_rfc4543_copy_src_to_dst (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int crypto_rfc4543_copy_src_to_dst(struct aead_request *req, bool enc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/gcm.c (ffffffff81717720)
Location: crypto/gcm.c:959
Inline: False
Direct callers:
  - crypto/gcm.c:crypto_rfc4543_crypt
```
**Symbols:**

```
ffffffff81717720-ffffffff817177f2: crypto_rfc4543_copy_src_to_dst (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int crypto_rfc4543_copy_src_to_dst(struct aead_request *req, bool enc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/gcm.c (ffffffff81753110)
Location: crypto/gcm.c:957
Inline: False
Direct callers:
  - crypto/gcm.c:crypto_rfc4543_crypt
```
**Symbols:**

```
ffffffff81753110-ffffffff817531e2: crypto_rfc4543_copy_src_to_dst (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int crypto_rfc4543_copy_src_to_dst(struct aead_request *req, bool enc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/gcm.c (ffffffff81794fe0)
Location: crypto/gcm.c:955
Inline: False
Direct callers:
  - crypto/gcm.c:crypto_rfc4543_crypt
```
**Symbols:**

```
ffffffff81794fe0-ffffffff817950b2: crypto_rfc4543_copy_src_to_dst (STB_LOCAL)
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
int crypto_rfc4543_copy_src_to_dst(struct aead_request *req, bool enc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/gcm.c (ffff8000105cb3d8)
Location: crypto/gcm.c:1019
Inline: False
Direct callers:
  - crypto/gcm.c:crypto_rfc4543_crypt
```
**Symbols:**

```
ffff8000105cb3d8-ffff8000105cb488: crypto_rfc4543_copy_src_to_dst (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int crypto_rfc4543_copy_src_to_dst(struct aead_request *req, bool enc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/gcm.c (c0778edc)
Location: crypto/gcm.c:1019
Inline: False
Direct callers:
  - crypto/gcm.c:crypto_rfc4543_crypt
```
**Symbols:**

```
c0778edc-c0778f94: crypto_rfc4543_copy_src_to_dst (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int crypto_rfc4543_copy_src_to_dst(struct aead_request *req, bool enc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/gcm.c (c000000000756410)
Location: crypto/gcm.c:1019
Inline: False
Direct callers:
  - crypto/gcm.c:crypto_rfc4543_crypt
```
**Symbols:**

```
c000000000756410-c0000000007564e0: crypto_rfc4543_copy_src_to_dst (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int crypto_rfc4543_copy_src_to_dst(struct aead_request *req, bool enc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/gcm.c (ffffffe00040f77c)
Location: crypto/gcm.c:1019
Inline: False
Direct callers:
  - crypto/gcm.c:crypto_rfc4543_crypt
```
**Symbols:**

```
ffffffe00040f77c-ffffffe00040f7ec: crypto_rfc4543_copy_src_to_dst (STB_LOCAL)
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
int crypto_rfc4543_copy_src_to_dst(struct aead_request *req, bool enc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/gcm.c (ffffffff814c79d0)
Location: crypto/gcm.c:1019
Inline: False
Direct callers:
  - crypto/gcm.c:crypto_rfc4543_crypt
```
**Symbols:**

```
ffffffff814c79d0-ffffffff814c7a7b: crypto_rfc4543_copy_src_to_dst (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int crypto_rfc4543_copy_src_to_dst(struct aead_request *req, bool enc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/gcm.c (ffffffff814b83f0)
Location: crypto/gcm.c:1019
Inline: False
Direct callers:
  - crypto/gcm.c:crypto_rfc4543_crypt
```
**Symbols:**

```
ffffffff814b83f0-ffffffff814b849b: crypto_rfc4543_copy_src_to_dst (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int crypto_rfc4543_copy_src_to_dst(struct aead_request *req, bool enc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/gcm.c (ffffffff814c3a60)
Location: crypto/gcm.c:1019
Inline: False
Direct callers:
  - crypto/gcm.c:crypto_rfc4543_crypt
```
**Symbols:**

```
ffffffff814c3a60-ffffffff814c3b0b: crypto_rfc4543_copy_src_to_dst (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int crypto_rfc4543_copy_src_to_dst(struct aead_request *req, bool enc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/gcm.c (ffffffff814dc530)
Location: crypto/gcm.c:1019
Inline: False
Direct callers:
  - crypto/gcm.c:crypto_rfc4543_crypt
```
**Symbols:**

```
ffffffff814dc530-ffffffff814dc5db: crypto_rfc4543_copy_src_to_dst (STB_LOCAL)
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
