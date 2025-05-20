# Function: <code>calc_buffer_ahash_atfm</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_crypto.c (ffffffff813d4918)
Location: security/integrity/ima/ima_crypto.c:522
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
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
In security/integrity/ima/ima_crypto.c (ffffffff813ec368)
Location: security/integrity/ima/ima_crypto.c:524
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
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
In security/integrity/ima/ima_crypto.c (ffffffff813f8724)
Location: security/integrity/ima/ima_crypto.c:524
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
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
In security/integrity/ima/ima_crypto.c (ffffffff81420aa5)
Location: security/integrity/ima/ima_crypto.c:512
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
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
In security/integrity/ima/ima_crypto.c (ffffffff81452f33)
Location: security/integrity/ima/ima_crypto.c:514
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_crypto.c (ffffffff81470092)
Location: security/integrity/ima/ima_crypto.c:528
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_crypto.c (ffffffff8149da85)
Location: security/integrity/ima/ima_crypto.c:523
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_crypto.c (ffffffff814b7ec5)
Location: security/integrity/ima/ima_crypto.c:531
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int calc_buffer_ahash_atfm(const void *buf, loff_t len, struct ima_digest_data *hash, struct crypto_ahash *tfm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_crypto.c (0)
Location: security/integrity/ima/ima_crypto.c:672
Inline: False
Direct callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
```
**Symbols:**

```
ffffffff81516ed0-ffffffff81517135: calc_buffer_ahash_atfm (STB_LOCAL)
ffffffff81517d4d-ffffffff81517d89: calc_buffer_ahash_atfm.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int calc_buffer_ahash_atfm(const void *buf, loff_t len, struct ima_digest_data *hash, struct crypto_ahash *tfm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_crypto.c (0)
Location: security/integrity/ima/ima_crypto.c:662
Inline: False
Direct callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
```
**Symbols:**

```
ffffffff81534090-ffffffff815342f5: calc_buffer_ahash_atfm (STB_LOCAL)
ffffffff81bf1c51-ffffffff81bf1c8d: calc_buffer_ahash_atfm.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_crypto.c (ffffffff8153d0a4)
Location: security/integrity/ima/ima_crypto.c:662
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_crypto.c (ffffffff8159bf24)
Location: security/integrity/ima/ima_crypto.c:662
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_crypto.c (ffffffff81640ebc)
Location: security/integrity/ima/ima_crypto.c:663
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_crypto.c (ffffffff816f8e2c)
Location: security/integrity/ima/ima_crypto.c:663
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_crypto.c (ffffffff81733027)
Location: security/integrity/ima/ima_crypto.c:663
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_crypto.c (ffffffff81773a37)
Location: security/integrity/ima/ima_crypto.c:663
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_crypto.c (ffff8000105b0294)
Location: security/integrity/ima/ima_crypto.c:531
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_crypto.c (c075f9bc)
Location: security/integrity/ima/ima_crypto.c:531
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_crypto.c (c00000000072fd48)
Location: security/integrity/ima/ima_crypto.c:531
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_crypto.c (ffffffe0003f7f34)
Location: security/integrity/ima/ima_crypto.c:531
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_crypto.c (ffffffff814b04a5)
Location: security/integrity/ima/ima_crypto.c:531
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_crypto.c (ffffffff814a0ec5)
Location: security/integrity/ima/ima_crypto.c:531
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_crypto.c (ffffffff814ac535)
Location: security/integrity/ima/ima_crypto.c:531
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_crypto.c (ffffffff814c4f85)
Location: security/integrity/ima/ima_crypto.c:531
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
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
</ul>
