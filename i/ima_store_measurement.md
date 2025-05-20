# Function: <code>ima_store_measurement</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void ima_store_measurement(struct integrity_iint_cache *iint, struct file *file, const unsigned char *filename, struct evm_ima_xattr_data *xattr_value, int xattr_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_api.c (ffffffff81398a80)
Location: security/integrity/ima/ima_api.c:259
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:process_measurement
```
**Symbols:**

```
ffffffff81398a80-ffffffff81398b58: ima_store_measurement (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void ima_store_measurement(struct integrity_iint_cache *iint, struct file *file, const unsigned char *filename, struct evm_ima_xattr_data *xattr_value, int xattr_len, int pcr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_api.c (ffffffff813d5020)
Location: security/integrity/ima/ima_api.c:255
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:process_measurement
```
**Symbols:**

```
ffffffff813d5020-ffffffff813d511e: ima_store_measurement (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void ima_store_measurement(struct integrity_iint_cache *iint, struct file *file, const unsigned char *filename, struct evm_ima_xattr_data *xattr_value, int xattr_len, int pcr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_api.c (ffffffff813eca70)
Location: security/integrity/ima/ima_api.c:255
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:process_measurement
```
**Symbols:**

```
ffffffff813eca70-ffffffff813ecb6e: ima_store_measurement (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void ima_store_measurement(struct integrity_iint_cache *iint, struct file *file, const unsigned char *filename, struct evm_ima_xattr_data *xattr_value, int xattr_len, int pcr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_api.c (ffffffff813f8e70)
Location: security/integrity/ima/ima_api.c:256
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:process_measurement
```
**Symbols:**

```
ffffffff813f8e70-ffffffff813f8f6a: ima_store_measurement (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void ima_store_measurement(struct integrity_iint_cache *iint, struct file *file, const unsigned char *filename, struct evm_ima_xattr_data *xattr_value, int xattr_len, int pcr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_api.c (ffffffff814212f0)
Location: security/integrity/ima/ima_api.c:273
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:process_measurement
```
**Symbols:**

```
ffffffff814212f0-ffffffff814213f8: ima_store_measurement (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void ima_store_measurement(struct integrity_iint_cache *iint, struct file *file, const unsigned char *filename, struct evm_ima_xattr_data *xattr_value, int xattr_len, int pcr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_api.c (ffffffff81453880)
Location: security/integrity/ima/ima_api.c:277
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:process_measurement
```
**Symbols:**

```
ffffffff81453880-ffffffff8145398a: ima_store_measurement (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void ima_store_measurement(struct integrity_iint_cache *iint, struct file *file, const unsigned char *filename, struct evm_ima_xattr_data *xattr_value, int xattr_len, int pcr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_api.c (ffffffff81470a60)
Location: security/integrity/ima/ima_api.c:277
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:process_measurement
```
**Symbols:**

```
ffffffff81470a60-ffffffff81470b6a: ima_store_measurement (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void ima_store_measurement(struct integrity_iint_cache *iint, struct file *file, const unsigned char *filename, struct evm_ima_xattr_data *xattr_value, int xattr_len, int pcr, struct ima_template_desc *template_desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_api.c (ffffffff8149e420)
Location: security/integrity/ima/ima_api.c:285
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:process_measurement
```
**Symbols:**

```
ffffffff8149e420-ffffffff8149e547: ima_store_measurement (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void ima_store_measurement(struct integrity_iint_cache *iint, struct file *file, const unsigned char *filename, struct evm_ima_xattr_data *xattr_value, int xattr_len, const struct modsig *modsig, int pcr, struct ima_template_desc *template_desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_api.c (ffffffff814b88d0)
Location: security/integrity/ima/ima_api.c:293
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:process_measurement
```
**Symbols:**

```
ffffffff814b88d0-ffffffff814b89f4: ima_store_measurement (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void ima_store_measurement(struct integrity_iint_cache *iint, struct file *file, const unsigned char *filename, struct evm_ima_xattr_data *xattr_value, int xattr_len, const struct modsig *modsig, int pcr, struct ima_template_desc *template_desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_api.c (ffffffff81518500)
Location: security/integrity/ima/ima_api.c:296
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:process_measurement
```
**Symbols:**

```
ffffffff81518500-ffffffff8151866b: ima_store_measurement (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ima_store_measurement(struct integrity_iint_cache *iint, struct file *file, const unsigned char *filename, struct evm_ima_xattr_data *xattr_value, int xattr_len, const struct modsig *modsig, int pcr, struct ima_template_desc *template_desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_api.c (ffffffff815354d0)
Location: security/integrity/ima/ima_api.c:296
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:process_measurement
```
**Symbols:**

```
ffffffff815354d0-ffffffff8153563b: ima_store_measurement (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void ima_store_measurement(struct integrity_iint_cache *iint, struct file *file, const unsigned char *filename, struct evm_ima_xattr_data *xattr_value, int xattr_len, const struct modsig *modsig, int pcr, struct ima_template_desc *template_desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_api.c (ffffffff8153daf0)
Location: security/integrity/ima/ima_api.c:298
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:process_measurement
```
**Symbols:**

```
ffffffff8153daf0-ffffffff8153dc5b: ima_store_measurement (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void ima_store_measurement(struct integrity_iint_cache *iint, struct file *file, const unsigned char *filename, struct evm_ima_xattr_data *xattr_value, int xattr_len, const struct modsig *modsig, int pcr, struct ima_template_desc *template_desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_api.c (0)
Location: security/integrity/ima/ima_api.c:300
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:process_measurement
```
**Symbols:**

```
ffffffff81cd6fab-ffffffff81cd7007: ima_store_measurement.cold (STB_LOCAL)
ffffffff8159c980-ffffffff8159cb06: ima_store_measurement (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void ima_store_measurement(struct integrity_iint_cache *iint, struct file *file, const unsigned char *filename, struct evm_ima_xattr_data *xattr_value, int xattr_len, const struct modsig *modsig, int pcr, struct ima_template_desc *template_desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_api.c (0)
Location: security/integrity/ima/ima_api.c:339
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:process_measurement
```
**Symbols:**

```
ffffffff81e8a1cf-ffffffff81e8a21d: ima_store_measurement.cold (STB_LOCAL)
ffffffff81641ac0-ffffffff81641c72: ima_store_measurement (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void ima_store_measurement(struct integrity_iint_cache *iint, struct file *file, const unsigned char *filename, struct evm_ima_xattr_data *xattr_value, int xattr_len, const struct modsig *modsig, int pcr, struct ima_template_desc *template_desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_api.c (0)
Location: security/integrity/ima/ima_api.c:339
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:process_measurement
```
**Symbols:**

```
ffffffff8207535d-ffffffff820753ab: ima_store_measurement.cold (STB_LOCAL)
ffffffff816f9b20-ffffffff816f9cd2: ima_store_measurement (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void ima_store_measurement(struct integrity_iint_cache *iint, struct file *file, const unsigned char *filename, struct evm_ima_xattr_data *xattr_value, int xattr_len, const struct modsig *modsig, int pcr, struct ima_template_desc *template_desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_api.c (0)
Location: security/integrity/ima/ima_api.c:336
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:process_measurement
```
**Symbols:**

```
ffffffff820f4ec9-ffffffff820f4f09: ima_store_measurement.cold (STB_LOCAL)
ffffffff81733c50-ffffffff81733e04: ima_store_measurement (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void ima_store_measurement(struct integrity_iint_cache *iint, struct file *file, const unsigned char *filename, struct evm_ima_xattr_data *xattr_value, int xattr_len, const struct modsig *modsig, int pcr, struct ima_template_desc *template_desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_api.c (0)
Location: security/integrity/ima/ima_api.c:341
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:process_measurement
```
**Symbols:**

```
ffffffff821d2057-ffffffff821d2097: ima_store_measurement.cold (STB_LOCAL)
ffffffff81774740-ffffffff817748f4: ima_store_measurement (STB_GLOBAL)
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
void ima_store_measurement(struct integrity_iint_cache *iint, struct file *file, const unsigned char *filename, struct evm_ima_xattr_data *xattr_value, int xattr_len, const struct modsig *modsig, int pcr, struct ima_template_desc *template_desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_api.c (ffff8000105b0b80)
Location: security/integrity/ima/ima_api.c:293
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:process_measurement
```
**Symbols:**

```
ffff8000105b0b80-ffff8000105b0cd0: ima_store_measurement (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void ima_store_measurement(struct integrity_iint_cache *iint, struct file *file, const unsigned char *filename, struct evm_ima_xattr_data *xattr_value, int xattr_len, const struct modsig *modsig, int pcr, struct ima_template_desc *template_desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_api.c (c0760268)
Location: security/integrity/ima/ima_api.c:293
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:process_measurement
```
**Symbols:**

```
c0760268-c07603b8: ima_store_measurement (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void ima_store_measurement(struct integrity_iint_cache *iint, struct file *file, const unsigned char *filename, struct evm_ima_xattr_data *xattr_value, int xattr_len, const struct modsig *modsig, int pcr, struct ima_template_desc *template_desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_api.c (c000000000730920)
Location: security/integrity/ima/ima_api.c:293
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:process_measurement
```
**Symbols:**

```
c000000000730920-c000000000730af0: ima_store_measurement (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void ima_store_measurement(struct integrity_iint_cache *iint, struct file *file, const unsigned char *filename, struct evm_ima_xattr_data *xattr_value, int xattr_len, const struct modsig *modsig, int pcr, struct ima_template_desc *template_desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_api.c (ffffffe0003f8698)
Location: security/integrity/ima/ima_api.c:293
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:process_measurement
```
**Symbols:**

```
ffffffe0003f8698-ffffffe0003f87b8: ima_store_measurement (STB_GLOBAL)
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
void ima_store_measurement(struct integrity_iint_cache *iint, struct file *file, const unsigned char *filename, struct evm_ima_xattr_data *xattr_value, int xattr_len, const struct modsig *modsig, int pcr, struct ima_template_desc *template_desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_api.c (ffffffff814b0eb0)
Location: security/integrity/ima/ima_api.c:293
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:process_measurement
```
**Symbols:**

```
ffffffff814b0eb0-ffffffff814b0fd4: ima_store_measurement (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void ima_store_measurement(struct integrity_iint_cache *iint, struct file *file, const unsigned char *filename, struct evm_ima_xattr_data *xattr_value, int xattr_len, const struct modsig *modsig, int pcr, struct ima_template_desc *template_desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_api.c (ffffffff814a18d0)
Location: security/integrity/ima/ima_api.c:293
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:process_measurement
```
**Symbols:**

```
ffffffff814a18d0-ffffffff814a19f4: ima_store_measurement (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void ima_store_measurement(struct integrity_iint_cache *iint, struct file *file, const unsigned char *filename, struct evm_ima_xattr_data *xattr_value, int xattr_len, const struct modsig *modsig, int pcr, struct ima_template_desc *template_desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_api.c (ffffffff814acf40)
Location: security/integrity/ima/ima_api.c:293
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:process_measurement
```
**Symbols:**

```
ffffffff814acf40-ffffffff814ad064: ima_store_measurement (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void ima_store_measurement(struct integrity_iint_cache *iint, struct file *file, const unsigned char *filename, struct evm_ima_xattr_data *xattr_value, int xattr_len, const struct modsig *modsig, int pcr, struct ima_template_desc *template_desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_api.c (ffffffff814c5990)
Location: security/integrity/ima/ima_api.c:293
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:process_measurement
```
**Symbols:**

```
ffffffff814c5990-ffffffff814c5ab4: ima_store_measurement (STB_GLOBAL)
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
<code>int pcr</code>
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
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct ima_template_desc *template_desc</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.3</code> and <code>5.4</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct modsig *modsig</code>
</li>
<li>
<b>Param reordered. </b>
<code>iint, file, filename, xattr_value, xattr_len, pcr, template_desc</code> ➡️ <code>iint, file, filename, xattr_value, xattr_len, modsig, pcr, template_desc</code>
</li>
</ul>
</details>
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
