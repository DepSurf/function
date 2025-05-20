# Function: <code>ima_calc_file_hash</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ima_calc_file_hash(struct file *file, struct ima_digest_data *hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_crypto.c (ffffffff81398190)
Location: security/integrity/ima/ima_crypto.c:439
Inline: False
Direct callers:
  - security/integrity/ima/ima_api.c:ima_collect_measurement
  - security/integrity/ima/ima_template_lib.c:ima_eventdigest_init
```
**Symbols:**

```
ffffffff81398190-ffffffff81398487: ima_calc_file_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ima_calc_file_hash(struct file *file, struct ima_digest_data *hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_crypto.c (ffffffff813d4030)
Location: security/integrity/ima/ima_crypto.c:439
Inline: False
Direct callers:
  - security/integrity/ima/ima_api.c:ima_collect_measurement
  - security/integrity/ima/ima_template_lib.c:ima_eventdigest_init
```
**Symbols:**

```
ffffffff813d4030-ffffffff813d4738: ima_calc_file_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ima_calc_file_hash(struct file *file, struct ima_digest_data *hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_crypto.c (ffffffff813eba80)
Location: security/integrity/ima/ima_crypto.c:439
Inline: False
Direct callers:
  - security/integrity/ima/ima_api.c:ima_collect_measurement
  - security/integrity/ima/ima_template_lib.c:ima_eventdigest_init
```
**Symbols:**

```
ffffffff813eba80-ffffffff813ec18b: ima_calc_file_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ima_calc_file_hash(struct file *file, struct ima_digest_data *hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_crypto.c (ffffffff813f7db0)
Location: security/integrity/ima/ima_crypto.c:439
Inline: False
Direct callers:
  - security/integrity/ima/ima_api.c:ima_collect_measurement
  - security/integrity/ima/ima_template_lib.c:ima_eventdigest_init
```
**Symbols:**

```
ffffffff813f7db0-ffffffff813f8559: ima_calc_file_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ima_calc_file_hash(struct file *file, struct ima_digest_data *hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_crypto.c (ffffffff8141fe60)
Location: security/integrity/ima/ima_crypto.c:417
Inline: False
Direct callers:
  - security/integrity/ima/ima_api.c:ima_collect_measurement
  - security/integrity/ima/ima_template_lib.c:ima_eventdigest_init
```
**Symbols:**

```
ffffffff8141fe60-ffffffff814208cc: ima_calc_file_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int ima_calc_file_hash(struct file *file, struct ima_digest_data *hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_crypto.c (0)
Location: security/integrity/ima/ima_crypto.c:419
Inline: False
Direct callers:
  - security/integrity/ima/ima_api.c:ima_collect_measurement
  - security/integrity/ima/ima_template_lib.c:ima_eventdigest_init
```
**Symbols:**

```
ffffffff8145320e-ffffffff8145324a: ima_calc_file_hash.cold.9 (STB_LOCAL)
ffffffff81452440-ffffffff81452d3f: ima_calc_file_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int ima_calc_file_hash(struct file *file, struct ima_digest_data *hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_crypto.c (0)
Location: security/integrity/ima/ima_crypto.c:405
Inline: False
Direct callers:
  - security/integrity/ima/ima_api.c:ima_collect_measurement
  - security/integrity/ima/ima_template_lib.c:ima_eventdigest_init
```
**Symbols:**

```
ffffffff8147039e-ffffffff81470413: ima_calc_file_hash.cold.10 (STB_LOCAL)
ffffffff8146f6a0-ffffffff8146ff3a: ima_calc_file_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int ima_calc_file_hash(struct file *file, struct ima_digest_data *hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_crypto.c (0)
Location: security/integrity/ima/ima_crypto.c:401
Inline: False
Direct callers:
  - security/integrity/ima/ima_api.c:ima_collect_measurement
  - security/integrity/ima/ima_template_lib.c:ima_eventdigest_init
```
**Symbols:**

```
ffffffff8149ddb1-ffffffff8149ddc2: ima_calc_file_hash.cold (STB_LOCAL)
ffffffff8149d7b0-ffffffff8149d93d: ima_calc_file_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int ima_calc_file_hash(struct file *file, struct ima_digest_data *hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_crypto.c (0)
Location: security/integrity/ima/ima_crypto.c:409
Inline: False
Direct callers:
  - security/integrity/ima/ima_api.c:ima_collect_measurement
  - security/integrity/ima/ima_template_lib.c:ima_eventdigest_init
```
**Symbols:**

```
ffffffff814b8217-ffffffff814b8228: ima_calc_file_hash.cold (STB_LOCAL)
ffffffff814b7bf0-ffffffff814b7d7d: ima_calc_file_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int ima_calc_file_hash(struct file *file, struct ima_digest_data *hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_crypto.c (0)
Location: security/integrity/ima/ima_crypto.c:535
Inline: False
Direct callers:
  - security/integrity/ima/ima_api.c:ima_collect_measurement
  - security/integrity/ima/ima_template_lib.c:ima_eventdigest_init
```
**Symbols:**

```
ffffffff81517dfb-ffffffff81517e0c: ima_calc_file_hash.cold (STB_LOCAL)
ffffffff81517850-ffffffff815179d9: ima_calc_file_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ima_calc_file_hash(struct file *file, struct ima_digest_data *hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_crypto.c (ffffffff81534980)
Location: security/integrity/ima/ima_crypto.c:535
Inline: False
Direct callers:
  - security/integrity/ima/ima_api.c:ima_collect_measurement
  - security/integrity/ima/ima_template_lib.c:ima_eventdigest_init
```
**Symbols:**

```
ffffffff81534980-ffffffff81534ad8: ima_calc_file_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ima_calc_file_hash(struct file *file, struct ima_digest_data *hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_crypto.c (ffffffff8153cd30)
Location: security/integrity/ima/ima_crypto.c:535
Inline: False
Direct callers:
  - security/integrity/ima/ima_api.c:ima_collect_measurement
  - security/integrity/ima/ima_template_lib.c:ima_eventdigest_init
```
**Symbols:**

```
ffffffff8153cd30-ffffffff8153ce8b: ima_calc_file_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ima_calc_file_hash(struct file *file, struct ima_digest_data *hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_crypto.c (ffffffff8159bb90)
Location: security/integrity/ima/ima_crypto.c:535
Inline: False
Direct callers:
  - security/integrity/ima/ima_api.c:ima_collect_measurement
  - security/integrity/ima/ima_template_lib.c:ima_eventdigest_init
```
**Symbols:**

```
ffffffff8159bb90-ffffffff8159bd02: ima_calc_file_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ima_calc_file_hash(struct file *file, struct ima_digest_data *hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_crypto.c (ffffffff81640b00)
Location: security/integrity/ima/ima_crypto.c:536
Inline: False
Direct callers:
  - security/integrity/ima/ima_api.c:ima_collect_measurement
  - security/integrity/ima/ima_template_lib.c:ima_eventdigest_init
```
**Symbols:**

```
ffffffff81640b00-ffffffff81640c83: ima_calc_file_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ima_calc_file_hash(struct file *file, struct ima_digest_data *hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_crypto.c (ffffffff816f8a50)
Location: security/integrity/ima/ima_crypto.c:536
Inline: False
Direct callers:
  - security/integrity/ima/ima_api.c:ima_collect_measurement
  - security/integrity/ima/ima_template_lib.c:ima_eventdigest_init
```
**Symbols:**

```
ffffffff816f8a50-ffffffff816f8bd3: ima_calc_file_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ima_calc_file_hash(struct file *file, struct ima_digest_data *hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_crypto.c (ffffffff81732c50)
Location: security/integrity/ima/ima_crypto.c:536
Inline: False
Direct callers:
  - security/integrity/ima/ima_api.c:ima_collect_measurement
  - security/integrity/ima/ima_template_lib.c:ima_eventdigest_init
```
**Symbols:**

```
ffffffff81732c50-ffffffff81732dd3: ima_calc_file_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ima_calc_file_hash(struct file *file, struct ima_digest_data *hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_crypto.c (ffffffff81773660)
Location: security/integrity/ima/ima_crypto.c:536
Inline: False
Direct callers:
  - security/integrity/ima/ima_api.c:ima_collect_measurement
  - security/integrity/ima/ima_template_lib.c:ima_eventdigest_init
```
**Symbols:**

```
ffffffff81773660-ffffffff817737e3: ima_calc_file_hash (STB_GLOBAL)
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
int ima_calc_file_hash(struct file *file, struct ima_digest_data *hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_crypto.c (ffff8000105aff08)
Location: security/integrity/ima/ima_crypto.c:409
Inline: False
Direct callers:
  - security/integrity/ima/ima_api.c:ima_collect_measurement
  - security/integrity/ima/ima_template_lib.c:ima_eventdigest_init
```
**Symbols:**

```
ffff8000105aff08-ffff8000105b0104: ima_calc_file_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ima_calc_file_hash(struct file *file, struct ima_digest_data *hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_crypto.c (c075f634)
Location: security/integrity/ima/ima_crypto.c:409
Inline: False
Direct callers:
  - security/integrity/ima/ima_api.c:ima_collect_measurement
  - security/integrity/ima/ima_template_lib.c:ima_eventdigest_init
```
**Symbols:**

```
c075f634-c075f84c: ima_calc_file_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ima_calc_file_hash(struct file *file, struct ima_digest_data *hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_crypto.c (c00000000072f8d0)
Location: security/integrity/ima/ima_crypto.c:409
Inline: False
Direct callers:
  - security/integrity/ima/ima_api.c:ima_collect_measurement
  - security/integrity/ima/ima_template_lib.c:ima_eventdigest_init
```
**Symbols:**

```
c00000000072f8d0-c00000000072fb34: ima_calc_file_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ima_calc_file_hash(struct file *file, struct ima_digest_data *hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_crypto.c (ffffffe0003f7c7e)
Location: security/integrity/ima/ima_crypto.c:409
Inline: False
Direct callers:
  - security/integrity/ima/ima_api.c:ima_collect_measurement
  - security/integrity/ima/ima_template_lib.c:ima_eventdigest_init
```
**Symbols:**

```
ffffffe0003f7c7e-ffffffe0003f7e02: ima_calc_file_hash (STB_GLOBAL)
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
int ima_calc_file_hash(struct file *file, struct ima_digest_data *hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_crypto.c (0)
Location: security/integrity/ima/ima_crypto.c:409
Inline: False
Direct callers:
  - security/integrity/ima/ima_api.c:ima_collect_measurement
  - security/integrity/ima/ima_template_lib.c:ima_eventdigest_init
```
**Symbols:**

```
ffffffff814b07f7-ffffffff814b0808: ima_calc_file_hash.cold (STB_LOCAL)
ffffffff814b01d0-ffffffff814b035d: ima_calc_file_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int ima_calc_file_hash(struct file *file, struct ima_digest_data *hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_crypto.c (0)
Location: security/integrity/ima/ima_crypto.c:409
Inline: False
Direct callers:
  - security/integrity/ima/ima_api.c:ima_collect_measurement
  - security/integrity/ima/ima_template_lib.c:ima_eventdigest_init
```
**Symbols:**

```
ffffffff814a1217-ffffffff814a1228: ima_calc_file_hash.cold (STB_LOCAL)
ffffffff814a0bf0-ffffffff814a0d7d: ima_calc_file_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int ima_calc_file_hash(struct file *file, struct ima_digest_data *hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_crypto.c (0)
Location: security/integrity/ima/ima_crypto.c:409
Inline: False
Direct callers:
  - security/integrity/ima/ima_api.c:ima_collect_measurement
  - security/integrity/ima/ima_template_lib.c:ima_eventdigest_init
```
**Symbols:**

```
ffffffff814ac887-ffffffff814ac898: ima_calc_file_hash.cold (STB_LOCAL)
ffffffff814ac260-ffffffff814ac3ed: ima_calc_file_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int ima_calc_file_hash(struct file *file, struct ima_digest_data *hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_crypto.c (0)
Location: security/integrity/ima/ima_crypto.c:409
Inline: False
Direct callers:
  - security/integrity/ima/ima_api.c:ima_collect_measurement
  - security/integrity/ima/ima_template_lib.c:ima_eventdigest_init
```
**Symbols:**

```
ffffffff814c52d7-ffffffff814c52e8: ima_calc_file_hash.cold (STB_LOCAL)
ffffffff814c4cb0-ffffffff814c4e3d: ima_calc_file_hash (STB_GLOBAL)
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
