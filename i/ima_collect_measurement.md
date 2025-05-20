# Function: <code>ima_collect_measurement</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ima_collect_measurement(struct integrity_iint_cache *iint, struct file *file, struct evm_ima_xattr_data **xattr_value, int *xattr_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_api.c (ffffffff81398890)
Location: security/integrity/ima/ima_api.c:190
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_appraise.c:ima_update_xattr
```
**Symbols:**

```
ffffffff81398890-ffffffff81398a78: ima_collect_measurement (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ima_collect_measurement(struct integrity_iint_cache *iint, struct file *file, void *buf, loff_t size, enum hash_algo algo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_api.c (ffffffff813d4e60)
Location: security/integrity/ima/ima_api.c:193
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_appraise.c:ima_update_xattr
```
**Symbols:**

```
ffffffff813d4e60-ffffffff813d5020: ima_collect_measurement (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ima_collect_measurement(struct integrity_iint_cache *iint, struct file *file, void *buf, loff_t size, enum hash_algo algo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_api.c (ffffffff813ec8b0)
Location: security/integrity/ima/ima_api.c:193
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_appraise.c:ima_update_xattr
```
**Symbols:**

```
ffffffff813ec8b0-ffffffff813eca70: ima_collect_measurement (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ima_collect_measurement(struct integrity_iint_cache *iint, struct file *file, void *buf, loff_t size, enum hash_algo algo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_api.c (ffffffff813f8ca0)
Location: security/integrity/ima/ima_api.c:194
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_appraise.c:ima_update_xattr
```
**Symbols:**

```
ffffffff813f8ca0-ffffffff813f8e6e: ima_collect_measurement (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ima_collect_measurement(struct integrity_iint_cache *iint, struct file *file, void *buf, loff_t size, enum hash_algo algo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_api.c (ffffffff814210d0)
Location: security/integrity/ima/ima_api.c:194
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_appraise.c:ima_update_xattr
```
**Symbols:**

```
ffffffff814210d0-ffffffff814212e3: ima_collect_measurement (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int ima_collect_measurement(struct integrity_iint_cache *iint, struct file *file, void *buf, loff_t size, enum hash_algo algo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_api.c (0)
Location: security/integrity/ima/ima_api.c:198
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_appraise.c:ima_update_xattr
```
**Symbols:**

```
ffffffff81453b63-ffffffff81453b6f: ima_collect_measurement.cold.4 (STB_LOCAL)
ffffffff81453630-ffffffff81453875: ima_collect_measurement (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int ima_collect_measurement(struct integrity_iint_cache *iint, struct file *file, void *buf, loff_t size, enum hash_algo algo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_api.c (0)
Location: security/integrity/ima/ima_api.c:198
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_appraise.c:ima_update_xattr
```
**Symbols:**

```
ffffffff81470d33-ffffffff81470d3f: ima_collect_measurement.cold.4 (STB_LOCAL)
ffffffff81470810-ffffffff81470a55: ima_collect_measurement (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int ima_collect_measurement(struct integrity_iint_cache *iint, struct file *file, void *buf, loff_t size, enum hash_algo algo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_api.c (0)
Location: security/integrity/ima/ima_api.c:206
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_appraise.c:ima_update_xattr
```
**Symbols:**

```
ffffffff8149e718-ffffffff8149e724: ima_collect_measurement.cold (STB_LOCAL)
ffffffff8149e1e0-ffffffff8149e420: ima_collect_measurement (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int ima_collect_measurement(struct integrity_iint_cache *iint, struct file *file, void *buf, loff_t size, enum hash_algo algo, struct modsig *modsig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_api.c (0)
Location: security/integrity/ima/ima_api.c:206
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_appraise.c:ima_update_xattr
```
**Symbols:**

```
ffffffff814b8bc8-ffffffff814b8bd4: ima_collect_measurement.cold (STB_LOCAL)
ffffffff814b8660-ffffffff814b88cc: ima_collect_measurement (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int ima_collect_measurement(struct integrity_iint_cache *iint, struct file *file, void *buf, loff_t size, enum hash_algo algo, struct modsig *modsig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_api.c (0)
Location: security/integrity/ima/ima_api.c:209
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_appraise.c:ima_update_xattr
```
**Symbols:**

```
ffffffff8151882c-ffffffff81518838: ima_collect_measurement.cold (STB_LOCAL)
ffffffff81518270-ffffffff815184fa: ima_collect_measurement (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int ima_collect_measurement(struct integrity_iint_cache *iint, struct file *file, void *buf, loff_t size, enum hash_algo algo, struct modsig *modsig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_api.c (0)
Location: security/integrity/ima/ima_api.c:209
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_appraise.c:ima_update_xattr
```
**Symbols:**

```
ffffffff81bf1d16-ffffffff81bf1d22: ima_collect_measurement.cold (STB_LOCAL)
ffffffff81535240-ffffffff815354ca: ima_collect_measurement (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int ima_collect_measurement(struct integrity_iint_cache *iint, struct file *file, void *buf, loff_t size, enum hash_algo algo, struct modsig *modsig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_api.c (0)
Location: security/integrity/ima/ima_api.c:211
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_appraise.c:ima_update_xattr
```
**Symbols:**

```
ffffffff81be3d36-ffffffff81be3d42: ima_collect_measurement.cold (STB_LOCAL)
ffffffff8153d860-ffffffff8153daec: ima_collect_measurement (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int ima_collect_measurement(struct integrity_iint_cache *iint, struct file *file, void *buf, loff_t size, enum hash_algo algo, struct modsig *modsig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_api.c (0)
Location: security/integrity/ima/ima_api.c:213
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_appraise.c:ima_update_xattr
```
**Symbols:**

```
ffffffff81cd6f9f-ffffffff81cd6fab: ima_collect_measurement.cold (STB_LOCAL)
ffffffff8159c6f0-ffffffff8159c97c: ima_collect_measurement (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int ima_collect_measurement(struct integrity_iint_cache *iint, struct file *file, void *buf, loff_t size, enum hash_algo algo, struct modsig *modsig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_api.c (0)
Location: security/integrity/ima/ima_api.c:240
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:__ima_inode_hash
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_appraise.c:ima_update_xattr
```
**Symbols:**

```
ffffffff81e8a1c3-ffffffff81e8a1cf: ima_collect_measurement.cold (STB_LOCAL)
ffffffff81641730-ffffffff81641ab7: ima_collect_measurement (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ima_collect_measurement(struct integrity_iint_cache *iint, struct file *file, void *buf, loff_t size, enum hash_algo algo, struct modsig *modsig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_api.c (ffffffff816f9740)
Location: security/integrity/ima/ima_api.c:240
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:__ima_inode_hash
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_appraise.c:ima_update_xattr
```
**Symbols:**

```
ffffffff816f9740-ffffffff816f9b0e: ima_collect_measurement (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ima_collect_measurement(struct integrity_iint_cache *iint, struct file *file, void *buf, loff_t size, enum hash_algo algo, struct modsig *modsig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_api.c (ffffffff817338c0)
Location: security/integrity/ima/ima_api.c:240
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:__ima_inode_hash
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_appraise.c:ima_update_xattr
```
**Symbols:**

```
ffffffff817338c0-ffffffff81733c31: ima_collect_measurement (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ima_collect_measurement(struct integrity_iint_cache *iint, struct file *file, void *buf, loff_t size, enum hash_algo algo, struct modsig *modsig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_api.c (ffffffff817742e0)
Location: security/integrity/ima/ima_api.c:240
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:__ima_inode_hash
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_appraise.c:ima_update_xattr
```
**Symbols:**

```
ffffffff817742e0-ffffffff81774726: ima_collect_measurement (STB_GLOBAL)
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
int ima_collect_measurement(struct integrity_iint_cache *iint, struct file *file, void *buf, loff_t size, enum hash_algo algo, struct modsig *modsig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_api.c (ffff8000105b0988)
Location: security/integrity/ima/ima_api.c:206
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_appraise.c:ima_update_xattr
```
**Symbols:**

```
ffff8000105b0988-ffff8000105b0b7c: ima_collect_measurement (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ima_collect_measurement(struct integrity_iint_cache *iint, struct file *file, void *buf, loff_t size, enum hash_algo algo, struct modsig *modsig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_api.c (c0760000)
Location: security/integrity/ima/ima_api.c:206
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_appraise.c:ima_update_xattr
```
**Symbols:**

```
c0760000-c0760268: ima_collect_measurement (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ima_collect_measurement(struct integrity_iint_cache *iint, struct file *file, void *buf, loff_t size, enum hash_algo algo, struct modsig *modsig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_api.c (c000000000730670)
Location: security/integrity/ima/ima_api.c:206
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_appraise.c:ima_update_xattr
```
**Symbols:**

```
c000000000730670-c000000000730918: ima_collect_measurement (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ima_collect_measurement(struct integrity_iint_cache *iint, struct file *file, void *buf, loff_t size, enum hash_algo algo, struct modsig *modsig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_api.c (ffffffe0003f84e8)
Location: security/integrity/ima/ima_api.c:206
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_appraise.c:ima_update_xattr
```
**Symbols:**

```
ffffffe0003f84e8-ffffffe0003f8698: ima_collect_measurement (STB_GLOBAL)
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
int ima_collect_measurement(struct integrity_iint_cache *iint, struct file *file, void *buf, loff_t size, enum hash_algo algo, struct modsig *modsig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_api.c (0)
Location: security/integrity/ima/ima_api.c:206
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_appraise.c:ima_update_xattr
```
**Symbols:**

```
ffffffff814b11a8-ffffffff814b11b4: ima_collect_measurement.cold (STB_LOCAL)
ffffffff814b0c40-ffffffff814b0eac: ima_collect_measurement (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int ima_collect_measurement(struct integrity_iint_cache *iint, struct file *file, void *buf, loff_t size, enum hash_algo algo, struct modsig *modsig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_api.c (0)
Location: security/integrity/ima/ima_api.c:206
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_appraise.c:ima_update_xattr
```
**Symbols:**

```
ffffffff814a1bc8-ffffffff814a1bd4: ima_collect_measurement.cold (STB_LOCAL)
ffffffff814a1660-ffffffff814a18cc: ima_collect_measurement (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int ima_collect_measurement(struct integrity_iint_cache *iint, struct file *file, void *buf, loff_t size, enum hash_algo algo, struct modsig *modsig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_api.c (0)
Location: security/integrity/ima/ima_api.c:206
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_appraise.c:ima_update_xattr
```
**Symbols:**

```
ffffffff814ad238-ffffffff814ad244: ima_collect_measurement.cold (STB_LOCAL)
ffffffff814accd0-ffffffff814acf3c: ima_collect_measurement (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int ima_collect_measurement(struct integrity_iint_cache *iint, struct file *file, void *buf, loff_t size, enum hash_algo algo, struct modsig *modsig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_api.c (0)
Location: security/integrity/ima/ima_api.c:206
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_appraise.c:ima_update_xattr
```
**Symbols:**

```
ffffffff814c5c88-ffffffff814c5c94: ima_collect_measurement.cold (STB_LOCAL)
ffffffff814c5720-ffffffff814c598c: ima_collect_measurement (STB_GLOBAL)
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
<code>void *buf</code>
</li>
<li>
<b>Param added. </b>
<code>loff_t size</code>
</li>
<li>
<b>Param added. </b>
<code>enum hash_algo algo</code>
</li>
<li>
<b>Param removed. </b>
<code>struct evm_ima_xattr_data **xattr_value</code>
</li>
<li>
<b>Param removed. </b>
<code>int *xattr_len</code>
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
<details>
<summary>Changed between <code>5.3</code> and <code>5.4</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct modsig *modsig</code>
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
