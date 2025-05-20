# Function: <code>tpm_pcr_extend</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int tpm_pcr_extend(u32 chip_num, int pcr_idx, const u8 *hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff81523ca0)
Location: drivers/char/tpm/tpm-interface.c:755
Inline: False
Direct callers:
  - security/keys/trusted.c:pcrlock
  - security/integrity/ima/ima_queue.c:ima_add_template_entry
```
**Symbols:**

```
ffffffff81523ca0-ffffffff81523da0: tpm_pcr_extend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int tpm_pcr_extend(u32 chip_num, int pcr_idx, const u8 *hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff81576bd0)
Location: drivers/char/tpm/tpm-interface.c:754
Inline: False
Direct callers:
  - security/keys/trusted.c:pcrlock
  - security/integrity/ima/ima_queue.c:ima_add_template_entry
```
**Symbols:**

```
ffffffff81576bd0-ffffffff81576cce: tpm_pcr_extend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int tpm_pcr_extend(u32 chip_num, int pcr_idx, const u8 *hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff815a3300)
Location: drivers/char/tpm/tpm-interface.c:744
Inline: False
Direct callers:
  - security/keys/trusted.c:pcrlock
  - security/integrity/ima/ima_queue.c:ima_add_template_entry
```
**Symbols:**

```
ffffffff815a3300-ffffffff815a3404: tpm_pcr_extend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int tpm_pcr_extend(u32 chip_num, int pcr_idx, const u8 *hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff815b7340)
Location: drivers/char/tpm/tpm-interface.c:901
Inline: False
Direct callers:
  - security/keys/trusted.c:pcrlock
  - security/integrity/ima/ima_queue.c:ima_add_template_entry
```
**Symbols:**

```
ffffffff815b7340-ffffffff815b748c: tpm_pcr_extend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int tpm_pcr_extend(u32 chip_num, int pcr_idx, const u8 *hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff8161df20)
Location: drivers/char/tpm/tpm-interface.c:919
Inline: False
Direct callers:
  - security/keys/trusted.c:pcrlock
  - security/integrity/ima/ima_queue.c:ima_add_template_entry
```
**Symbols:**

```
ffffffff8161df20-ffffffff8161e06c: tpm_pcr_extend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int tpm_pcr_extend(struct tpm_chip *chip, int pcr_idx, const u8 *hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff81657c30)
Location: drivers/char/tpm/tpm-interface.c:1040
Inline: False
Direct callers:
  - security/keys/trusted.c:pcrlock
  - security/integrity/ima/ima_queue.c:ima_add_template_entry
```
**Symbols:**

```
ffffffff81657c30-ffffffff81657d7e: tpm_pcr_extend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int tpm_pcr_extend(struct tpm_chip *chip, u32 pcr_idx, const u8 *hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff81676250)
Location: drivers/char/tpm/tpm-interface.c:497
Inline: False
Direct callers:
  - security/keys/trusted.c:pcrlock
  - security/integrity/ima/ima_queue.c:ima_add_template_entry
```
**Symbols:**

```
ffffffff81676250-ffffffff8167639e: tpm_pcr_extend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int tpm_pcr_extend(struct tpm_chip *chip, u32 pcr_idx, struct tpm_digest *digests);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff816ac070)
Location: drivers/char/tpm/tpm-interface.c:313
Inline: False
Direct callers:
  - security/keys/trusted.c:pcrlock
  - security/integrity/ima/ima_queue.c:ima_add_template_entry
```
**Symbols:**

```
ffffffff816ac070-ffffffff816ac145: tpm_pcr_extend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int tpm_pcr_extend(struct tpm_chip *chip, u32 pcr_idx, struct tpm_digest *digests);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff816cedf0)
Location: drivers/char/tpm/tpm-interface.c:313
Inline: False
Direct callers:
  - security/keys/trusted.c:pcrlock
  - security/integrity/ima/ima_queue.c:ima_add_template_entry
```
**Symbols:**

```
ffffffff816cedf0-ffffffff816ceeab: tpm_pcr_extend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int tpm_pcr_extend(struct tpm_chip *chip, u32 pcr_idx, struct tpm_digest *digests);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff81783cf0)
Location: drivers/char/tpm/tpm-interface.c:314
Inline: False
Direct callers:
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_update
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_instantiate
  - security/integrity/ima/ima_queue.c:ima_add_template_entry
```
**Symbols:**

```
ffffffff81783cf0-ffffffff81783da8: tpm_pcr_extend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int tpm_pcr_extend(struct tpm_chip *chip, u32 pcr_idx, struct tpm_digest *digests);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff8179b240)
Location: drivers/char/tpm/tpm-interface.c:314
Inline: False
Direct callers:
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_update
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_instantiate
  - security/integrity/ima/ima_queue.c:ima_add_template_entry
```
**Symbols:**

```
ffffffff8179b240-ffffffff8179b2f8: tpm_pcr_extend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int tpm_pcr_extend(struct tpm_chip *chip, u32 pcr_idx, struct tpm_digest *digests);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff8177dd80)
Location: drivers/char/tpm/tpm-interface.c:314
Inline: False
Direct callers:
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_unseal
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_seal
  - security/integrity/ima/ima_queue.c:ima_add_template_entry
```
**Symbols:**

```
ffffffff8177dd80-ffffffff8177de38: tpm_pcr_extend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int tpm_pcr_extend(struct tpm_chip *chip, u32 pcr_idx, struct tpm_digest *digests);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff81803f70)
Location: drivers/char/tpm/tpm-interface.c:314
Inline: False
Direct callers:
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_unseal
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_seal
  - security/integrity/ima/ima_queue.c:ima_add_template_entry
```
**Symbols:**

```
ffffffff81803f70-ffffffff81804028: tpm_pcr_extend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int tpm_pcr_extend(struct tpm_chip *chip, u32 pcr_idx, struct tpm_digest *digests);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff81943890)
Location: drivers/char/tpm/tpm-interface.c:314
Inline: False
Direct callers:
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_unseal
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_seal
  - security/integrity/ima/ima_queue.c:ima_add_template_entry
```
**Symbols:**

```
ffffffff81943890-ffffffff8194394a: tpm_pcr_extend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int tpm_pcr_extend(struct tpm_chip *chip, u32 pcr_idx, struct tpm_digest *digests);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff81aa6380)
Location: drivers/char/tpm/tpm-interface.c:314
Inline: False
Direct callers:
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_unseal
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_seal
  - security/integrity/ima/ima_queue.c:ima_add_template_entry
```
**Symbols:**

```
ffffffff81aa6380-ffffffff81aa643a: tpm_pcr_extend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int tpm_pcr_extend(struct tpm_chip *chip, u32 pcr_idx, struct tpm_digest *digests);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff81af1ba0)
Location: drivers/char/tpm/tpm-interface.c:314
Inline: False
Direct callers:
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_unseal
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_seal
  - security/integrity/ima/ima_queue.c:ima_add_template_entry
```
**Symbols:**

```
ffffffff81af1ba0-ffffffff81af1c5a: tpm_pcr_extend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int tpm_pcr_extend(struct tpm_chip *chip, u32 pcr_idx, struct tpm_digest *digests);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff81b45130)
Location: drivers/char/tpm/tpm-interface.c:314
Inline: False
Direct callers:
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_unseal
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_seal
  - security/integrity/ima/ima_queue.c:ima_add_template_entry
```
**Symbols:**

```
ffffffff81b45130-ffffffff81b451ea: tpm_pcr_extend (STB_GLOBAL)
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
int tpm_pcr_extend(struct tpm_chip *chip, u32 pcr_idx, struct tpm_digest *digests);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffff8000108b93b8)
Location: drivers/char/tpm/tpm-interface.c:313
Inline: False
Direct callers:
  - security/keys/trusted.c:pcrlock
  - security/integrity/ima/ima_queue.c:ima_add_template_entry
```
**Symbols:**

```
ffff8000108b93b8-ffff8000108b9494: tpm_pcr_extend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int tpm_pcr_extend(struct tpm_chip *chip, u32 pcr_idx, struct tpm_digest *digests);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (c09b2824)
Location: drivers/char/tpm/tpm-interface.c:313
Inline: False
Direct callers:
  - security/keys/trusted.c:pcrlock
  - security/integrity/ima/ima_queue.c:ima_add_template_entry
```
**Symbols:**

```
c09b2824-c09b28ec: tpm_pcr_extend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int tpm_pcr_extend(struct tpm_chip *chip, u32 pcr_idx, struct tpm_digest *digests);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (c00000000095a1b0)
Location: drivers/char/tpm/tpm-interface.c:313
Inline: False
Direct callers:
  - security/keys/trusted.c:pcrlock
  - security/integrity/ima/ima_queue.c:ima_add_template_entry
```
**Symbols:**

```
c00000000095a1b0-c00000000095a2d4: tpm_pcr_extend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int tpm_pcr_extend(struct tpm_chip *chip, u32 pcr_idx, struct tpm_digest *digests);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffe0005697da)
Location: drivers/char/tpm/tpm-interface.c:313
Inline: False
Direct callers:
  - security/keys/trusted.c:pcrlock
  - security/integrity/ima/ima_queue.c:ima_add_template_entry
```
**Symbols:**

```
ffffffe0005697da-ffffffe0005698a0: tpm_pcr_extend (STB_GLOBAL)
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
int tpm_pcr_extend(struct tpm_chip *chip, u32 pcr_idx, struct tpm_digest *digests);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff81694840)
Location: drivers/char/tpm/tpm-interface.c:313
Inline: False
Direct callers:
  - security/keys/trusted.c:pcrlock
  - security/integrity/ima/ima_queue.c:ima_add_template_entry
```
**Symbols:**

```
ffffffff81694840-ffffffff816948fb: tpm_pcr_extend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int tpm_pcr_extend(struct tpm_chip *chip, u32 pcr_idx, struct tpm_digest *digests);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff81672230)
Location: drivers/char/tpm/tpm-interface.c:313
Inline: False
Direct callers:
  - security/keys/trusted.c:pcrlock
  - security/integrity/ima/ima_queue.c:ima_add_template_entry
```
**Symbols:**

```
ffffffff81672230-ffffffff816722eb: tpm_pcr_extend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int tpm_pcr_extend(struct tpm_chip *chip, u32 pcr_idx, struct tpm_digest *digests);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff816c2ab0)
Location: drivers/char/tpm/tpm-interface.c:313
Inline: False
Direct callers:
  - security/keys/trusted.c:pcrlock
  - security/integrity/ima/ima_queue.c:ima_add_template_entry
```
**Symbols:**

```
ffffffff816c2ab0-ffffffff816c2b6b: tpm_pcr_extend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int tpm_pcr_extend(struct tpm_chip *chip, u32 pcr_idx, struct tpm_digest *digests);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff816dd080)
Location: drivers/char/tpm/tpm-interface.c:313
Inline: False
Direct callers:
  - security/keys/trusted.c:pcrlock
  - security/integrity/ima/ima_queue.c:ima_add_template_entry
```
**Symbols:**

```
ffffffff816dd080-ffffffff816dd13b: tpm_pcr_extend (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct tpm_chip *chip</code>
</li>
<li>
<b>Param removed. </b>
<code>u32 chip_num</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int pcr_idx</code> ➡️ <code>u32 pcr_idx</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct tpm_digest *digests</code>
</li>
<li>
<b>Param removed. </b>
<code>const u8 *hash</code>
</li>
</ul>
</details>
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
