# Function: <code>ima_calc_buffer_hash</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ima_calc_buffer_hash(const void *buf, loff_t len, struct ima_digest_data *hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_crypto.c (ffffffff813d47c0)
Location: security/integrity/ima/ima_crypto.c:626
Inline: False
Direct callers:
  - security/integrity/ima/ima_api.c:ima_collect_measurement
```
**Symbols:**

```
ffffffff813d47c0-ffffffff813d4ab5: ima_calc_buffer_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ima_calc_buffer_hash(const void *buf, loff_t len, struct ima_digest_data *hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_crypto.c (ffffffff813ec210)
Location: security/integrity/ima/ima_crypto.c:628
Inline: False
Direct callers:
  - security/integrity/ima/ima_api.c:ima_collect_measurement
```
**Symbols:**

```
ffffffff813ec210-ffffffff813ec505: ima_calc_buffer_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ima_calc_buffer_hash(const void *buf, loff_t len, struct ima_digest_data *hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_crypto.c (ffffffff813f85e0)
Location: security/integrity/ima/ima_crypto.c:628
Inline: False
Direct callers:
  - security/integrity/ima/ima_api.c:ima_collect_measurement
```
**Symbols:**

```
ffffffff813f85e0-ffffffff813f88ee: ima_calc_buffer_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ima_calc_buffer_hash(const void *buf, loff_t len, struct ima_digest_data *hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_crypto.c (ffffffff81420950)
Location: security/integrity/ima/ima_crypto.c:616
Inline: False
Direct callers:
  - security/integrity/ima/ima_api.c:ima_collect_measurement
```
**Symbols:**

```
ffffffff81420950-ffffffff81420d20: ima_calc_buffer_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int ima_calc_buffer_hash(const void *buf, loff_t len, struct ima_digest_data *hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_crypto.c (0)
Location: security/integrity/ima/ima_crypto.c:618
Inline: False
Direct callers:
  - security/integrity/ima/ima_api.c:ima_collect_measurement
```
**Symbols:**

```
ffffffff8145324a-ffffffff81453283: ima_calc_buffer_hash.cold.10 (STB_LOCAL)
ffffffff81452dd0-ffffffff814531d6: ima_calc_buffer_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int ima_calc_buffer_hash(const void *buf, loff_t len, struct ima_digest_data *hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_crypto.c (0)
Location: security/integrity/ima/ima_crypto.c:632
Inline: False
Direct callers:
  - security/integrity/ima/ima_api.c:ima_collect_measurement
```
**Symbols:**

```
ffffffff81470413-ffffffff81470467: ima_calc_buffer_hash.cold.11 (STB_LOCAL)
ffffffff8146ffd0-ffffffff81470366: ima_calc_buffer_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int ima_calc_buffer_hash(const void *buf, loff_t len, struct ima_digest_data *hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_crypto.c (0)
Location: security/integrity/ima/ima_crypto.c:626
Inline: False
Direct callers:
  - security/integrity/ima/ima_api.c:ima_collect_measurement
```
**Symbols:**

```
ffffffff8149ddc2-ffffffff8149ddfb: ima_calc_buffer_hash.cold (STB_LOCAL)
ffffffff8149d9d0-ffffffff8149dd1a: ima_calc_buffer_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int ima_calc_buffer_hash(const void *buf, loff_t len, struct ima_digest_data *hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_crypto.c (0)
Location: security/integrity/ima/ima_crypto.c:634
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:process_buffer_measurement
  - security/integrity/ima/ima_api.c:ima_collect_measurement
```
**Symbols:**

```
ffffffff814b8228-ffffffff814b8261: ima_calc_buffer_hash.cold (STB_LOCAL)
ffffffff814b7e10-ffffffff814b815a: ima_calc_buffer_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ima_calc_buffer_hash(const void *buf, loff_t len, struct ima_digest_data *hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_crypto.c (ffffffff81517b40)
Location: security/integrity/ima/ima_crypto.c:775
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:process_buffer_measurement
  - security/integrity/ima/ima_api.c:ima_collect_measurement
```
**Symbols:**

```
ffffffff81517b40-ffffffff81517bfb: ima_calc_buffer_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ima_calc_buffer_hash(const void *buf, loff_t len, struct ima_digest_data *hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_crypto.c (ffffffff81534c40)
Location: security/integrity/ima/ima_crypto.c:765
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:process_buffer_measurement
  - security/integrity/ima/ima_api.c:ima_collect_measurement
```
**Symbols:**

```
ffffffff81534c40-ffffffff81534d04: ima_calc_buffer_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int ima_calc_buffer_hash(const void *buf, loff_t len, struct ima_digest_data *hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_crypto.c (0)
Location: security/integrity/ima/ima_crypto.c:765
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:process_buffer_measurement
  - security/integrity/ima/ima_main.c:process_buffer_measurement
  - security/integrity/ima/ima_api.c:ima_collect_measurement
```
**Symbols:**

```
ffffffff81be3ce9-ffffffff81be3d22: ima_calc_buffer_hash.cold (STB_LOCAL)
ffffffff8153cff0-ffffffff8153d33e: ima_calc_buffer_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int ima_calc_buffer_hash(const void *buf, loff_t len, struct ima_digest_data *hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_crypto.c (0)
Location: security/integrity/ima/ima_crypto.c:765
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:process_buffer_measurement
  - security/integrity/ima/ima_main.c:process_buffer_measurement
  - security/integrity/ima/ima_api.c:ima_collect_measurement
```
**Symbols:**

```
ffffffff81cd6f52-ffffffff81cd6f8b: ima_calc_buffer_hash.cold (STB_LOCAL)
ffffffff8159be70-ffffffff8159c1be: ima_calc_buffer_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int ima_calc_buffer_hash(const void *buf, loff_t len, struct ima_digest_data *hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_crypto.c (0)
Location: security/integrity/ima/ima_crypto.c:766
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:process_buffer_measurement
  - security/integrity/ima/ima_main.c:process_buffer_measurement
  - security/integrity/ima/ima_api.c:ima_collect_measurement
```
**Symbols:**

```
ffffffff81e8a161-ffffffff81e8a1b0: ima_calc_buffer_hash.cold (STB_LOCAL)
ffffffff81640e00-ffffffff816411c2: ima_calc_buffer_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ima_calc_buffer_hash(const void *buf, loff_t len, struct ima_digest_data *hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_crypto.c (ffffffff816f8d70)
Location: security/integrity/ima/ima_crypto.c:766
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:process_buffer_measurement
  - security/integrity/ima/ima_main.c:process_buffer_measurement
  - security/integrity/ima/ima_api.c:ima_collect_measurement
```
**Symbols:**

```
ffffffff816f8d70-ffffffff816f9170: ima_calc_buffer_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ima_calc_buffer_hash(const void *buf, loff_t len, struct ima_digest_data *hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_crypto.c (ffffffff81732f70)
Location: security/integrity/ima/ima_crypto.c:766
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:process_buffer_measurement
  - security/integrity/ima/ima_main.c:process_buffer_measurement
  - security/integrity/ima/ima_api.c:ima_collect_measurement
```
**Symbols:**

```
ffffffff81732f70-ffffffff817332bd: ima_calc_buffer_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ima_calc_buffer_hash(const void *buf, loff_t len, struct ima_digest_data *hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_crypto.c (ffffffff81773980)
Location: security/integrity/ima/ima_crypto.c:766
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:process_buffer_measurement
  - security/integrity/ima/ima_main.c:process_buffer_measurement
  - security/integrity/ima/ima_api.c:ima_collect_measurement
```
**Symbols:**

```
ffffffff81773980-ffffffff81773cdc: ima_calc_buffer_hash (STB_GLOBAL)
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
int ima_calc_buffer_hash(const void *buf, loff_t len, struct ima_digest_data *hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_crypto.c (ffff8000105b01b8)
Location: security/integrity/ima/ima_crypto.c:634
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:process_buffer_measurement
  - security/integrity/ima/ima_api.c:ima_collect_measurement
```
**Symbols:**

```
ffff8000105b01b8-ffff8000105b04d0: ima_calc_buffer_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ima_calc_buffer_hash(const void *buf, loff_t len, struct ima_digest_data *hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_crypto.c (c075f8d4)
Location: security/integrity/ima/ima_crypto.c:634
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:process_buffer_measurement
  - security/integrity/ima/ima_api.c:ima_collect_measurement
```
**Symbols:**

```
c075f8d4-c075fc20: ima_calc_buffer_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ima_calc_buffer_hash(const void *buf, loff_t len, struct ima_digest_data *hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_crypto.c (c00000000072fc30)
Location: security/integrity/ima/ima_crypto.c:634
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:process_buffer_measurement
  - security/integrity/ima/ima_api.c:ima_collect_measurement
```
**Symbols:**

```
c00000000072fc30-c0000000007300cc: ima_calc_buffer_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ima_calc_buffer_hash(const void *buf, loff_t len, struct ima_digest_data *hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_crypto.c (ffffffe0003f7e88)
Location: security/integrity/ima/ima_crypto.c:634
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:process_buffer_measurement
  - security/integrity/ima/ima_api.c:ima_collect_measurement
```
**Symbols:**

```
ffffffe0003f7e88-ffffffe0003f812e: ima_calc_buffer_hash (STB_GLOBAL)
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
int ima_calc_buffer_hash(const void *buf, loff_t len, struct ima_digest_data *hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_crypto.c (0)
Location: security/integrity/ima/ima_crypto.c:634
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:process_buffer_measurement
  - security/integrity/ima/ima_api.c:ima_collect_measurement
```
**Symbols:**

```
ffffffff814b0808-ffffffff814b0841: ima_calc_buffer_hash.cold (STB_LOCAL)
ffffffff814b03f0-ffffffff814b073a: ima_calc_buffer_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int ima_calc_buffer_hash(const void *buf, loff_t len, struct ima_digest_data *hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_crypto.c (0)
Location: security/integrity/ima/ima_crypto.c:634
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:process_buffer_measurement
  - security/integrity/ima/ima_api.c:ima_collect_measurement
```
**Symbols:**

```
ffffffff814a1228-ffffffff814a1261: ima_calc_buffer_hash.cold (STB_LOCAL)
ffffffff814a0e10-ffffffff814a115a: ima_calc_buffer_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int ima_calc_buffer_hash(const void *buf, loff_t len, struct ima_digest_data *hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_crypto.c (0)
Location: security/integrity/ima/ima_crypto.c:634
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:process_buffer_measurement
  - security/integrity/ima/ima_api.c:ima_collect_measurement
```
**Symbols:**

```
ffffffff814ac898-ffffffff814ac8d1: ima_calc_buffer_hash.cold (STB_LOCAL)
ffffffff814ac480-ffffffff814ac7ca: ima_calc_buffer_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int ima_calc_buffer_hash(const void *buf, loff_t len, struct ima_digest_data *hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_crypto.c (0)
Location: security/integrity/ima/ima_crypto.c:634
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:process_buffer_measurement
  - security/integrity/ima/ima_api.c:ima_collect_measurement
```
**Symbols:**

```
ffffffff814c52e8-ffffffff814c5321: ima_calc_buffer_hash.cold (STB_LOCAL)
ffffffff814c4ed0-ffffffff814c521a: ima_calc_buffer_hash (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
