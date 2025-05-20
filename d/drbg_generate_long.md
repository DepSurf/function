# Function: <code>drbg_generate_long</code>

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
In crypto/drbg.c (ffffffff813ebf3d)
Location: crypto/drbg.c:1363
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_random
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
In crypto/drbg.c (ffffffff8140577d)
Location: crypto/drbg.c:1370
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_random
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
In crypto/drbg.c (ffffffff81412efd)
Location: crypto/drbg.c:1370
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_random
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
In crypto/drbg.c (ffffffff8143d69d)
Location: crypto/drbg.c:1370
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_random
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
In crypto/drbg.c (ffffffff814704c9)
Location: crypto/drbg.c:1372
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_random
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
In crypto/drbg.c (ffffffff8148f5f9)
Location: crypto/drbg.c:1370
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_random
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
In crypto/drbg.c (ffffffff814bcf05)
Location: crypto/drbg.c:1458
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_random
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
In crypto/drbg.c (ffffffff814d5ba5)
Location: crypto/drbg.c:1458
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_random
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int drbg_generate_long(struct drbg_state *drbg, unsigned char *buf, unsigned int buflen, struct drbg_string *addtl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/drbg.c (ffffffff81533570)
Location: crypto/drbg.c:1472
Inline: False
Direct callers:
  - crypto/drbg.c:drbg_kcapi_random
```
**Symbols:**

```
ffffffff81533570-ffffffff8153373d: drbg_generate_long (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int drbg_generate_long(struct drbg_state *drbg, unsigned char *buf, unsigned int buflen, struct drbg_string *addtl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/drbg.c (ffffffff815504c0)
Location: crypto/drbg.c:1472
Inline: False
Direct callers:
  - crypto/drbg.c:drbg_kcapi_random
```
**Symbols:**

```
ffffffff815504c0-ffffffff8155068d: drbg_generate_long (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int drbg_generate_long(struct drbg_state *drbg, unsigned char *buf, unsigned int buflen, struct drbg_string *addtl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/drbg.c (ffffffff81558ca0)
Location: crypto/drbg.c:1473
Inline: False
Direct callers:
  - crypto/drbg.c:drbg_kcapi_random
```
**Symbols:**

```
ffffffff81558ca0-ffffffff81558e6c: drbg_generate_long (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int drbg_generate_long(struct drbg_state *drbg, unsigned char *buf, unsigned int buflen, struct drbg_string *addtl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In crypto/drbg.c (0)
Location: crypto/drbg.c:1473
Inline: False
Direct callers:
  - crypto/drbg.c:drbg_kcapi_random
```
**Symbols:**

```
ffffffff815b9f50-ffffffff815ba12d: drbg_generate_long (STB_LOCAL)
ffffffff81cd77fe-ffffffff81cd7844: drbg_generate_long.cold (STB_LOCAL)
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
In crypto/drbg.c (ffffffff81664a4b)
Location: crypto/drbg.c:1517
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_random
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
In crypto/drbg.c (ffffffff8171edab)
Location: crypto/drbg.c:1517
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_random
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
In crypto/drbg.c (ffffffff8175a6bb)
Location: crypto/drbg.c:1517
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_random
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
In crypto/drbg.c (ffffffff8179c5bb)
Location: crypto/drbg.c:1501
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_random
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
In crypto/drbg.c (ffff8000105d12f0)
Location: crypto/drbg.c:1458
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_random
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
In crypto/drbg.c (c077f360)
Location: crypto/drbg.c:1458
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_random
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
In crypto/drbg.c (c00000000075e720)
Location: crypto/drbg.c:1458
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_random
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
In crypto/drbg.c (ffffffe000416090)
Location: crypto/drbg.c:1458
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_random
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
In crypto/drbg.c (ffffffff814ce185)
Location: crypto/drbg.c:1458
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_random
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
In crypto/drbg.c (ffffffff814beba5)
Location: crypto/drbg.c:1458
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_random
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
In crypto/drbg.c (ffffffff814ca215)
Location: crypto/drbg.c:1458
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_random
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
In crypto/drbg.c (ffffffff814e2ce5)
Location: crypto/drbg.c:1458
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_random
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
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
</ul>
