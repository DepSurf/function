# Function: <code>drbg_instantiate</code>

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
In crypto/drbg.c (ffffffff813ee3df)
Location: crypto/drbg.c:1448
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_seed
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
In crypto/drbg.c (ffffffff81407c1f)
Location: crypto/drbg.c:1455
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_seed
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
In crypto/drbg.c (ffffffff8141533b)
Location: crypto/drbg.c:1455
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_seed
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
In crypto/drbg.c (ffffffff8143fb0b)
Location: crypto/drbg.c:1455
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_seed
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
In crypto/drbg.c (ffffffff8147292f)
Location: crypto/drbg.c:1457
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_seed
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
In crypto/drbg.c (ffffffff8148fd7f)
Location: crypto/drbg.c:1455
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_seed
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
In crypto/drbg.c (ffffffff814be651)
Location: crypto/drbg.c:1543
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_seed
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
In crypto/drbg.c (ffffffff814d74a1)
Location: crypto/drbg.c:1543
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_seed
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int drbg_instantiate(struct drbg_state *drbg, struct drbg_string *pers, int coreref, bool pr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In crypto/drbg.c (0)
Location: crypto/drbg.c:1557
Inline: False
Direct callers:
  - crypto/drbg.c:drbg_kcapi_seed
```
**Symbols:**

```
ffffffff81534810-ffffffff815349d6: drbg_instantiate (STB_LOCAL)
ffffffff81536b53-ffffffff81536b64: drbg_instantiate.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int drbg_instantiate(struct drbg_state *drbg, struct drbg_string *pers, int coreref, bool pr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In crypto/drbg.c (0)
Location: crypto/drbg.c:1557
Inline: False
Direct callers:
  - crypto/drbg.c:drbg_kcapi_seed
```
**Symbols:**

```
ffffffff81551760-ffffffff81551926: drbg_instantiate (STB_LOCAL)
ffffffff81bf2189-ffffffff81bf219a: drbg_instantiate.cold (STB_LOCAL)
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
In crypto/drbg.c (ffffffff8155a04d)
Location: crypto/drbg.c:1558
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_seed
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
In crypto/drbg.c (ffffffff815bb2d3)
Location: crypto/drbg.c:1558
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_seed
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
In crypto/drbg.c (ffffffff81664c6a)
Location: crypto/drbg.c:1574
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_seed
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
In crypto/drbg.c (ffffffff8171efea)
Location: crypto/drbg.c:1574
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_seed
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
In crypto/drbg.c (ffffffff8175a8fa)
Location: crypto/drbg.c:1574
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_seed
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
In crypto/drbg.c (ffffffff8179c7fa)
Location: crypto/drbg.c:1558
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_seed
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
In crypto/drbg.c (ffff8000105d19fc)
Location: crypto/drbg.c:1543
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_seed
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
In crypto/drbg.c (c0780904)
Location: crypto/drbg.c:1543
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_seed
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
In crypto/drbg.c (c0000000007602ac)
Location: crypto/drbg.c:1543
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_seed
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
In crypto/drbg.c (ffffffe0004166ea)
Location: crypto/drbg.c:1543
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_seed
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
In crypto/drbg.c (ffffffff814cfa81)
Location: crypto/drbg.c:1543
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_seed
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
In crypto/drbg.c (ffffffff814c04a1)
Location: crypto/drbg.c:1543
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_seed
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
In crypto/drbg.c (ffffffff814cbb11)
Location: crypto/drbg.c:1543
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_seed
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
In crypto/drbg.c (ffffffff814e45e1)
Location: crypto/drbg.c:1543
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_seed
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
