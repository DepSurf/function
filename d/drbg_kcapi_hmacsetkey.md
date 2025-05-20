# Function: <code>drbg_kcapi_hmacsetkey</code>

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
void drbg_kcapi_hmacsetkey(struct drbg_state *drbg, const unsigned char *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/drbg.c (ffffffff813eb970)
Location: crypto/drbg.c:1600
Inline: False
Direct callers:
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_hmac_update
```
**Symbols:**

```
ffffffff813eb970-ffffffff813eb9a8: drbg_kcapi_hmacsetkey (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void drbg_kcapi_hmacsetkey(struct drbg_state *drbg, const unsigned char *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/drbg.c (ffffffff814051b0)
Location: crypto/drbg.c:1607
Inline: False
Direct callers:
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_hmac_update
```
**Symbols:**

```
ffffffff814051b0-ffffffff814051e8: drbg_kcapi_hmacsetkey (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void drbg_kcapi_hmacsetkey(struct drbg_state *drbg, const unsigned char *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/drbg.c (ffffffff81412950)
Location: crypto/drbg.c:1607
Inline: False
Direct callers:
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_hmac_update
```
**Symbols:**

```
ffffffff81412950-ffffffff8141297e: drbg_kcapi_hmacsetkey (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void drbg_kcapi_hmacsetkey(struct drbg_state *drbg, const unsigned char *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/drbg.c (ffffffff8143d0d0)
Location: crypto/drbg.c:1607
Inline: False
Direct callers:
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_hmac_update
```
**Symbols:**

```
ffffffff8143d0d0-ffffffff8143d0fe: drbg_kcapi_hmacsetkey (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void drbg_kcapi_hmacsetkey(struct drbg_state *drbg, const unsigned char *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/drbg.c (ffffffff8146ff10)
Location: crypto/drbg.c:1609
Inline: False
Direct callers:
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_hmac_update
```
**Symbols:**

```
ffffffff8146ff10-ffffffff8146ff3e: drbg_kcapi_hmacsetkey (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void drbg_kcapi_hmacsetkey(struct drbg_state *drbg, const unsigned char *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/drbg.c (ffffffff8148d690)
Location: crypto/drbg.c:1607
Inline: False
Direct callers:
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_hmac_update
```
**Symbols:**

```
ffffffff8148d690-ffffffff8148d6be: drbg_kcapi_hmacsetkey (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void drbg_kcapi_hmacsetkey(struct drbg_state *drbg, const unsigned char *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/drbg.c (ffffffff814bb010)
Location: crypto/drbg.c:1694
Inline: False
Direct callers:
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_hmac_update
```
**Symbols:**

```
ffffffff814bb010-ffffffff814bb03e: drbg_kcapi_hmacsetkey (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void drbg_kcapi_hmacsetkey(struct drbg_state *drbg, const unsigned char *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/drbg.c (ffffffff814d3de0)
Location: crypto/drbg.c:1694
Inline: False
Direct callers:
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_hmac_update
```
**Symbols:**

```
ffffffff814d3de0-ffffffff814d3e0e: drbg_kcapi_hmacsetkey (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/drbg.c (ffffffff81534d16)
Location: crypto/drbg.c:1710
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_hmac_update
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/drbg.c (ffffffff81551c86)
Location: crypto/drbg.c:1710
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_hmac_update
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
In crypto/drbg.c (ffffffff8155a417)
Location: crypto/drbg.c:1711
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_hmac_update
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
In crypto/drbg.c (ffffffff815bb717)
Location: crypto/drbg.c:1711
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_hmac_update
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
In crypto/drbg.c (ffffffff81665040)
Location: crypto/drbg.c:1715
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_hmac_update
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
In crypto/drbg.c (ffffffff8171f3de)
Location: crypto/drbg.c:1715
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_hmac_update
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
In crypto/drbg.c (ffffffff8175acf0)
Location: crypto/drbg.c:1715
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_hmac_update
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
In crypto/drbg.c (ffffffff8179cbf0)
Location: crypto/drbg.c:1699
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_hmac_update
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
void drbg_kcapi_hmacsetkey(struct drbg_state *drbg, const unsigned char *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/drbg.c (ffff8000105d0870)
Location: crypto/drbg.c:1694
Inline: False
Direct callers:
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_hmac_update
```
**Symbols:**

```
ffff8000105d0870-ffff8000105d08bc: drbg_kcapi_hmacsetkey (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void drbg_kcapi_hmacsetkey(struct drbg_state *drbg, const unsigned char *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/drbg.c (c077e6bc)
Location: crypto/drbg.c:1694
Inline: False
Direct callers:
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_hmac_update
```
**Symbols:**

```
c077e6bc-c077e6f8: drbg_kcapi_hmacsetkey (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void drbg_kcapi_hmacsetkey(struct drbg_state *drbg, const unsigned char *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/drbg.c (c00000000075d5e0)
Location: crypto/drbg.c:1694
Inline: False
Direct callers:
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_hmac_update
```
**Symbols:**

```
c00000000075d5e0-c00000000075d63c: drbg_kcapi_hmacsetkey (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void drbg_kcapi_hmacsetkey(struct drbg_state *drbg, const unsigned char *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/drbg.c (ffffffe0004158c0)
Location: crypto/drbg.c:1694
Inline: False
Direct callers:
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_hmac_update
```
**Symbols:**

```
ffffffe0004158c0-ffffffe000415902: drbg_kcapi_hmacsetkey (STB_LOCAL)
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
void drbg_kcapi_hmacsetkey(struct drbg_state *drbg, const unsigned char *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/drbg.c (ffffffff814cc3c0)
Location: crypto/drbg.c:1694
Inline: False
Direct callers:
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_hmac_update
```
**Symbols:**

```
ffffffff814cc3c0-ffffffff814cc3ee: drbg_kcapi_hmacsetkey (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void drbg_kcapi_hmacsetkey(struct drbg_state *drbg, const unsigned char *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/drbg.c (ffffffff814bcde0)
Location: crypto/drbg.c:1694
Inline: False
Direct callers:
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_hmac_update
```
**Symbols:**

```
ffffffff814bcde0-ffffffff814bce0e: drbg_kcapi_hmacsetkey (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void drbg_kcapi_hmacsetkey(struct drbg_state *drbg, const unsigned char *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/drbg.c (ffffffff814c8450)
Location: crypto/drbg.c:1694
Inline: False
Direct callers:
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_hmac_update
```
**Symbols:**

```
ffffffff814c8450-ffffffff814c847e: drbg_kcapi_hmacsetkey (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void drbg_kcapi_hmacsetkey(struct drbg_state *drbg, const unsigned char *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/drbg.c (ffffffff814e0f20)
Location: crypto/drbg.c:1694
Inline: False
Direct callers:
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_hmac_update
```
**Symbols:**

```
ffffffff814e0f20-ffffffff814e0f4e: drbg_kcapi_hmacsetkey (STB_LOCAL)
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
