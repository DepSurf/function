# Function: <code>ima_get_modsig_digest</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ima_get_modsig_digest(const struct modsig *modsig, enum hash_algo *algo, const u8 **digest, u32 *digest_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_modsig.c (ffffffff814bc580)
Location: security/integrity/ima/ima_modsig.c:142
Inline: False
Direct callers:
  - security/integrity/ima/ima_template_lib.c:ima_eventdigest_modsig_init
  - security/integrity/ima/ima_appraise.c:ima_check_blacklist
```
**Symbols:**

```
ffffffff814bc580-ffffffff814bc59e: ima_get_modsig_digest (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ima_get_modsig_digest(const struct modsig *modsig, enum hash_algo *algo, const u8 **digest, u32 *digest_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_modsig.c (ffffffff8151ca80)
Location: security/integrity/ima/ima_modsig.c:142
Inline: False
Direct callers:
  - security/integrity/ima/ima_template_lib.c:ima_eventdigest_modsig_init
  - security/integrity/ima/ima_appraise.c:ima_check_blacklist
```
**Symbols:**

```
ffffffff8151ca80-ffffffff8151ca9e: ima_get_modsig_digest (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ima_get_modsig_digest(const struct modsig *modsig, enum hash_algo *algo, const u8 **digest, u32 *digest_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_modsig.c (ffffffff815398b0)
Location: security/integrity/ima/ima_modsig.c:122
Inline: False
Direct callers:
  - security/integrity/ima/ima_template_lib.c:ima_eventdigest_modsig_init
  - security/integrity/ima/ima_appraise.c:ima_check_blacklist
```
**Symbols:**

```
ffffffff815398b0-ffffffff815398ce: ima_get_modsig_digest (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ima_get_modsig_digest(const struct modsig *modsig, enum hash_algo *algo, const u8 **digest, u32 *digest_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_modsig.c (ffffffff81541fb0)
Location: security/integrity/ima/ima_modsig.c:122
Inline: False
Direct callers:
  - security/integrity/ima/ima_template_lib.c:ima_eventdigest_modsig_init
  - security/integrity/ima/ima_appraise.c:ima_check_blacklist
```
**Symbols:**

```
ffffffff81541fb0-ffffffff81541fce: ima_get_modsig_digest (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ima_get_modsig_digest(const struct modsig *modsig, enum hash_algo *algo, const u8 **digest, u32 *digest_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_modsig.c (ffffffff815a1f10)
Location: security/integrity/ima/ima_modsig.c:122
Inline: False
Direct callers:
  - security/integrity/ima/ima_template_lib.c:ima_eventdigest_modsig_init
  - security/integrity/ima/ima_appraise.c:ima_check_blacklist
```
**Symbols:**

```
ffffffff815a1f10-ffffffff815a1f2e: ima_get_modsig_digest (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ima_get_modsig_digest(const struct modsig *modsig, enum hash_algo *algo, const u8 **digest, u32 *digest_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_modsig.c (ffffffff81648310)
Location: security/integrity/ima/ima_modsig.c:122
Inline: False
Direct callers:
  - security/integrity/ima/ima_template_lib.c:ima_eventdigest_modsig_init
  - security/integrity/ima/ima_appraise.c:ima_check_blacklist
```
**Symbols:**

```
ffffffff81648310-ffffffff8164833a: ima_get_modsig_digest (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ima_get_modsig_digest(const struct modsig *modsig, enum hash_algo *algo, const u8 **digest, u32 *digest_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_modsig.c (ffffffff81700c40)
Location: security/integrity/ima/ima_modsig.c:122
Inline: False
Direct callers:
  - security/integrity/ima/ima_template_lib.c:ima_eventdigest_modsig_init
  - security/integrity/ima/ima_appraise.c:ima_check_blacklist
```
**Symbols:**

```
ffffffff81700c40-ffffffff81700c6a: ima_get_modsig_digest (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ima_get_modsig_digest(const struct modsig *modsig, enum hash_algo *algo, const u8 **digest, u32 *digest_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_modsig.c (ffffffff8173ace0)
Location: security/integrity/ima/ima_modsig.c:125
Inline: False
Direct callers:
  - security/integrity/ima/ima_template_lib.c:ima_eventdigest_modsig_init
  - security/integrity/ima/ima_appraise.c:ima_check_blacklist
```
**Symbols:**

```
ffffffff8173ace0-ffffffff8173ad0a: ima_get_modsig_digest (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ima_get_modsig_digest(const struct modsig *modsig, enum hash_algo *algo, const u8 **digest, u32 *digest_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_modsig.c (ffffffff8177b850)
Location: security/integrity/ima/ima_modsig.c:125
Inline: False
Direct callers:
  - security/integrity/ima/ima_template_lib.c:ima_eventdigest_modsig_init
  - security/integrity/ima/ima_appraise.c:ima_check_blacklist
```
**Symbols:**

```
ffffffff8177b850-ffffffff8177b87a: ima_get_modsig_digest (STB_GLOBAL)
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
int ima_get_modsig_digest(const struct modsig *modsig, enum hash_algo *algo, const u8 **digest, u32 *digest_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_modsig.c (ffff8000105b5050)
Location: security/integrity/ima/ima_modsig.c:142
Inline: False
Direct callers:
  - security/integrity/ima/ima_template_lib.c:ima_eventdigest_modsig_init
  - security/integrity/ima/ima_appraise.c:ima_check_blacklist
```
**Symbols:**

```
ffff8000105b5050-ffff8000105b50a4: ima_get_modsig_digest (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ima_get_modsig_digest(const struct modsig *modsig, enum hash_algo *algo, const u8 **digest, u32 *digest_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_modsig.c (c0764258)
Location: security/integrity/ima/ima_modsig.c:142
Inline: False
Direct callers:
  - security/integrity/ima/ima_template_lib.c:ima_eventdigest_modsig_init
  - security/integrity/ima/ima_appraise.c:ima_check_blacklist
```
**Symbols:**

```
c0764258-c0764290: ima_get_modsig_digest (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ima_get_modsig_digest(const struct modsig *modsig, enum hash_algo *algo, const u8 **digest, u32 *digest_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_modsig.c (c000000000738120)
Location: security/integrity/ima/ima_modsig.c:142
Inline: False
Direct callers:
  - security/integrity/ima/ima_template_lib.c:ima_eventdigest_modsig_init
  - security/integrity/ima/ima_appraise.c:ima_check_blacklist
```
**Symbols:**

```
c000000000738120-c00000000073814c: ima_get_modsig_digest (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ima_get_modsig_digest(const struct modsig *modsig, enum hash_algo *algo, const u8 **digest, u32 *digest_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_modsig.c (ffffffe0003fc062)
Location: security/integrity/ima/ima_modsig.c:142
Inline: False
Direct callers:
  - security/integrity/ima/ima_template_lib.c:ima_eventdigest_modsig_init
  - security/integrity/ima/ima_appraise.c:ima_check_blacklist
```
**Symbols:**

```
ffffffe0003fc062-ffffffe0003fc0a8: ima_get_modsig_digest (STB_GLOBAL)
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
int ima_get_modsig_digest(const struct modsig *modsig, enum hash_algo *algo, const u8 **digest, u32 *digest_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_modsig.c (ffffffff814b4b60)
Location: security/integrity/ima/ima_modsig.c:142
Inline: False
Direct callers:
  - security/integrity/ima/ima_template_lib.c:ima_eventdigest_modsig_init
  - security/integrity/ima/ima_appraise.c:ima_check_blacklist
```
**Symbols:**

```
ffffffff814b4b60-ffffffff814b4b7e: ima_get_modsig_digest (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ima_get_modsig_digest(const struct modsig *modsig, enum hash_algo *algo, const u8 **digest, u32 *digest_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_modsig.c (ffffffff814a5580)
Location: security/integrity/ima/ima_modsig.c:142
Inline: False
Direct callers:
  - security/integrity/ima/ima_template_lib.c:ima_eventdigest_modsig_init
  - security/integrity/ima/ima_appraise.c:ima_check_blacklist
```
**Symbols:**

```
ffffffff814a5580-ffffffff814a559e: ima_get_modsig_digest (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ima_get_modsig_digest(const struct modsig *modsig, enum hash_algo *algo, const u8 **digest, u32 *digest_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_modsig.c (ffffffff814b0bf0)
Location: security/integrity/ima/ima_modsig.c:142
Inline: False
Direct callers:
  - security/integrity/ima/ima_template_lib.c:ima_eventdigest_modsig_init
  - security/integrity/ima/ima_appraise.c:ima_check_blacklist
```
**Symbols:**

```
ffffffff814b0bf0-ffffffff814b0c0e: ima_get_modsig_digest (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ima_get_modsig_digest(const struct modsig *modsig, enum hash_algo *algo, const u8 **digest, u32 *digest_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_modsig.c (ffffffff814c9670)
Location: security/integrity/ima/ima_modsig.c:142
Inline: False
Direct callers:
  - security/integrity/ima/ima_template_lib.c:ima_eventdigest_modsig_init
  - security/integrity/ima/ima_appraise.c:ima_check_blacklist
```
**Symbols:**

```
ffffffff814c9670-ffffffff814c968e: ima_get_modsig_digest (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
