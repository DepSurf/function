# Function: <code>ima_calc_boot_aggregate_tfm</code>

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
In security/integrity/ima/ima_crypto.c (ffffffff81f9a052)
Location: security/integrity/ima/ima_crypto.c:534
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate
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
In security/integrity/ima/ima_crypto.c (ffffffff81fc4ddb)
Location: security/integrity/ima/ima_crypto.c:652
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate
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
In security/integrity/ima/ima_crypto.c (ffffffff82001825)
Location: security/integrity/ima/ima_crypto.c:654
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate
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
In security/integrity/ima/ima_crypto.c (ffffffff820e50c3)
Location: security/integrity/ima/ima_crypto.c:654
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate
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
In security/integrity/ima/ima_crypto.c (ffffffff826edcd1)
Location: security/integrity/ima/ima_crypto.c:642
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate
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
In security/integrity/ima/ima_crypto.c (ffffffff82718119)
Location: security/integrity/ima/ima_crypto.c:644
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ima_calc_boot_aggregate_tfm(char *digest, struct crypto_shash *tfm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_crypto.c (ffffffff828d00ae)
Location: security/integrity/ima/ima_crypto.c:658
Inline: False
Direct callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate
```
**Symbols:**

```
ffffffff828d00ae-ffffffff828d0190: ima_calc_boot_aggregate_tfm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ima_calc_boot_aggregate_tfm(char *digest, struct crypto_shash *tfm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_crypto.c (ffffffff828e9e38)
Location: security/integrity/ima/ima_crypto.c:652
Inline: False
Direct callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate
```
**Symbols:**

```
ffffffff828e9e38-ffffffff828e9f32: ima_calc_boot_aggregate_tfm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ima_calc_boot_aggregate_tfm(char *digest, struct crypto_shash *tfm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_crypto.c (ffffffff828f2acf)
Location: security/integrity/ima/ima_crypto.c:660
Inline: False
Direct callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate
```
**Symbols:**

```
ffffffff828f2acf-ffffffff828f2bc9: ima_calc_boot_aggregate_tfm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int ima_calc_boot_aggregate_tfm(char *digest, u16 alg_id, struct crypto_shash *tfm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_crypto.c (0)
Location: security/integrity/ima/ima_crypto.c:809
Inline: False
Direct callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate
```
**Symbols:**

```
ffffffff81516d20-ffffffff81516ec4: ima_calc_boot_aggregate_tfm (STB_LOCAL)
ffffffff81517d2b-ffffffff81517d4d: ima_calc_boot_aggregate_tfm.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int ima_calc_boot_aggregate_tfm(char *digest, u16 alg_id, struct crypto_shash *tfm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_crypto.c (0)
Location: security/integrity/ima/ima_crypto.c:799
Inline: False
Direct callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate
```
**Symbols:**

```
ffffffff81533ee0-ffffffff81534085: ima_calc_boot_aggregate_tfm (STB_LOCAL)
ffffffff81bf1c2f-ffffffff81bf1c51: ima_calc_boot_aggregate_tfm.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int ima_calc_boot_aggregate_tfm(char *digest, u16 alg_id, struct crypto_shash *tfm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_crypto.c (0)
Location: security/integrity/ima/ima_crypto.c:799
Inline: False
Direct callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate
```
**Symbols:**

```
ffffffff8153c510-ffffffff8153c6b5: ima_calc_boot_aggregate_tfm (STB_LOCAL)
ffffffff81be3c5e-ffffffff81be3c80: ima_calc_boot_aggregate_tfm.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int ima_calc_boot_aggregate_tfm(char *digest, u16 alg_id, struct crypto_shash *tfm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_crypto.c (0)
Location: security/integrity/ima/ima_crypto.c:799
Inline: False
Direct callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate
```
**Symbols:**

```
ffffffff8159b1f0-ffffffff8159b395: ima_calc_boot_aggregate_tfm (STB_LOCAL)
ffffffff81cd6ec7-ffffffff81cd6ee9: ima_calc_boot_aggregate_tfm.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int ima_calc_boot_aggregate_tfm(char *digest, u16 alg_id, struct crypto_shash *tfm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_crypto.c (0)
Location: security/integrity/ima/ima_crypto.c:800
Inline: False
Direct callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate
```
**Symbols:**

```
ffffffff81640090-ffffffff8164025d: ima_calc_boot_aggregate_tfm (STB_LOCAL)
ffffffff81e8a0ef-ffffffff81e8a111: ima_calc_boot_aggregate_tfm.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ima_calc_boot_aggregate_tfm(char *digest, u16 alg_id, struct crypto_shash *tfm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_crypto.c (ffffffff816f7ef0)
Location: security/integrity/ima/ima_crypto.c:800
Inline: False
Direct callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate
```
**Symbols:**

```
ffffffff816f7ef0-ffffffff816f80d9: ima_calc_boot_aggregate_tfm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ima_calc_boot_aggregate_tfm(char *digest, u16 alg_id, struct crypto_shash *tfm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_crypto.c (ffffffff81732160)
Location: security/integrity/ima/ima_crypto.c:800
Inline: False
Direct callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate
```
**Symbols:**

```
ffffffff81732160-ffffffff81732349: ima_calc_boot_aggregate_tfm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ima_calc_boot_aggregate_tfm(char *digest, u16 alg_id, struct crypto_shash *tfm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_crypto.c (ffffffff81772a00)
Location: security/integrity/ima/ima_crypto.c:800
Inline: False
Direct callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate
```
**Symbols:**

```
ffffffff81772a00-ffffffff81772be9: ima_calc_boot_aggregate_tfm (STB_LOCAL)
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
int ima_calc_boot_aggregate_tfm(char *digest, struct crypto_shash *tfm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_crypto.c (ffff80001146cf20)
Location: security/integrity/ima/ima_crypto.c:660
Inline: False
Direct callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate
```
**Symbols:**

```
ffff80001146cf20-ffff80001146d044: ima_calc_boot_aggregate_tfm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ima_calc_boot_aggregate_tfm(char *digest, struct crypto_shash *tfm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_crypto.c (c1545c2c)
Location: security/integrity/ima/ima_crypto.c:660
Inline: False
Direct callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate
```
**Symbols:**

```
c1545c2c-c1545d40: ima_calc_boot_aggregate_tfm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ima_calc_boot_aggregate_tfm(char *digest, struct crypto_shash *tfm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_crypto.c (c00000000139bf84)
Location: security/integrity/ima/ima_crypto.c:660
Inline: False
Direct callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate
```
**Symbols:**

```
c00000000139bf84-c00000000139c0dc: ima_calc_boot_aggregate_tfm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ima_calc_boot_aggregate_tfm(char *digest, struct crypto_shash *tfm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_crypto.c (ffffffe0000276de)
Location: security/integrity/ima/ima_crypto.c:660
Inline: False
Direct callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate
```
**Symbols:**

```
ffffffe0000276de-ffffffe0000277b2: ima_calc_boot_aggregate_tfm (STB_LOCAL)
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
int ima_calc_boot_aggregate_tfm(char *digest, struct crypto_shash *tfm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_crypto.c (ffffffff828db983)
Location: security/integrity/ima/ima_crypto.c:660
Inline: False
Direct callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate
```
**Symbols:**

```
ffffffff828db983-ffffffff828dba7d: ima_calc_boot_aggregate_tfm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ima_calc_boot_aggregate_tfm(char *digest, struct crypto_shash *tfm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_crypto.c (ffffffff828d409f)
Location: security/integrity/ima/ima_crypto.c:660
Inline: False
Direct callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate
```
**Symbols:**

```
ffffffff828d409f-ffffffff828d4199: ima_calc_boot_aggregate_tfm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ima_calc_boot_aggregate_tfm(char *digest, struct crypto_shash *tfm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_crypto.c (ffffffff828ee6f7)
Location: security/integrity/ima/ima_crypto.c:660
Inline: False
Direct callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate
```
**Symbols:**

```
ffffffff828ee6f7-ffffffff828ee7f1: ima_calc_boot_aggregate_tfm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ima_calc_boot_aggregate_tfm(char *digest, struct crypto_shash *tfm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_crypto.c (ffffffff828f3b19)
Location: security/integrity/ima/ima_crypto.c:660
Inline: False
Direct callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate
```
**Symbols:**

```
ffffffff828f3b19-ffffffff828f3c13: ima_calc_boot_aggregate_tfm (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>u16 alg_id</code>
</li>
<li>
<b>Param reordered. </b>
<code>digest, tfm</code> ➡️ <code>digest, alg_id, tfm</code>
</li>
</ul>
</details>
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
