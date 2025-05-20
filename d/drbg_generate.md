# Function: <code>drbg_generate</code>

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
Location: crypto/drbg.c:1236
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
Location: crypto/drbg.c:1243
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
In crypto/drbg.c (ffffffff81412f02)
Location: crypto/drbg.c:1243
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
In crypto/drbg.c (ffffffff8143d6a2)
Location: crypto/drbg.c:1243
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
In crypto/drbg.c (ffffffff8147057f)
Location: crypto/drbg.c:1245
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
In crypto/drbg.c (ffffffff8148f6af)
Location: crypto/drbg.c:1243
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
In crypto/drbg.c (ffffffff814bcfd0)
Location: crypto/drbg.c:1331
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
In crypto/drbg.c (ffffffff814d5c70)
Location: crypto/drbg.c:1331
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_random
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
In crypto/drbg.c (ffffffff8153364d)
Location: crypto/drbg.c:1345
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_generate_long
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
In crypto/drbg.c (ffffffff8155059d)
Location: crypto/drbg.c:1345
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_generate_long
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
In crypto/drbg.c (ffffffff81558d7a)
Location: crypto/drbg.c:1346
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_generate_long
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
In crypto/drbg.c (ffffffff815ba02d)
Location: crypto/drbg.c:1346
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_generate_long
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int drbg_generate(struct drbg_state *drbg, unsigned char *buf, unsigned int buflen, struct drbg_string *addtl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In crypto/drbg.c (0)
Location: crypto/drbg.c:1383
Inline: False
Direct callers:
  - crypto/drbg.c:drbg_kcapi_random
```
**Symbols:**

```
ffffffff816647f0-ffffffff816649c8: drbg_generate (STB_LOCAL)
ffffffff81e8ab04-ffffffff81e8ab19: drbg_generate.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int drbg_generate(struct drbg_state *drbg, unsigned char *buf, unsigned int buflen, struct drbg_string *addtl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In crypto/drbg.c (0)
Location: crypto/drbg.c:1383
Inline: False
Direct callers:
  - crypto/drbg.c:drbg_kcapi_random
```
**Symbols:**

```
ffffffff8171eb40-ffffffff8171ed18: drbg_generate (STB_LOCAL)
ffffffff8207585b-ffffffff82075870: drbg_generate.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int drbg_generate(struct drbg_state *drbg, unsigned char *buf, unsigned int buflen, struct drbg_string *addtl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In crypto/drbg.c (0)
Location: crypto/drbg.c:1383
Inline: False
Direct callers:
  - crypto/drbg.c:drbg_kcapi_random
```
**Symbols:**

```
ffffffff8175a450-ffffffff8175a628: drbg_generate (STB_LOCAL)
ffffffff820f54c3-ffffffff820f54d8: drbg_generate.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int drbg_generate(struct drbg_state *drbg, unsigned char *buf, unsigned int buflen, struct drbg_string *addtl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In crypto/drbg.c (0)
Location: crypto/drbg.c:1367
Inline: False
Direct callers:
  - crypto/drbg.c:drbg_kcapi_random
```
**Symbols:**

```
ffffffff8179c350-ffffffff8179c528: drbg_generate (STB_LOCAL)
ffffffff821d275a-ffffffff821d276f: drbg_generate.cold (STB_LOCAL)
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
In crypto/drbg.c (ffff8000105d1394)
Location: crypto/drbg.c:1331
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
In crypto/drbg.c (c077f43c)
Location: crypto/drbg.c:1331
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
In crypto/drbg.c (c00000000075e764)
Location: crypto/drbg.c:1331
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
Location: crypto/drbg.c:1331
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
In crypto/drbg.c (ffffffff814ce250)
Location: crypto/drbg.c:1331
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
In crypto/drbg.c (ffffffff814bec70)
Location: crypto/drbg.c:1331
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
In crypto/drbg.c (ffffffff814ca2e0)
Location: crypto/drbg.c:1331
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
In crypto/drbg.c (ffffffff814e2db0)
Location: crypto/drbg.c:1331
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
