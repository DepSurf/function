# Function: <code>drbg_convert_tfm_core</code>

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
In crypto/drbg.c (ffffffff813ee313)
Location: crypto/drbg.c:1784
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
In crypto/drbg.c (ffffffff81407b53)
Location: crypto/drbg.c:1810
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
In crypto/drbg.c (ffffffff81415256)
Location: crypto/drbg.c:1809
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
In crypto/drbg.c (ffffffff8143fa26)
Location: crypto/drbg.c:1791
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
In crypto/drbg.c (ffffffff814728a8)
Location: crypto/drbg.c:1793
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
In crypto/drbg.c (ffffffff8148fcf8)
Location: crypto/drbg.c:1790
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
In crypto/drbg.c (ffffffff814be5a8)
Location: crypto/drbg.c:1877
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
In crypto/drbg.c (ffffffff814d73f8)
Location: crypto/drbg.c:1877
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_seed
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
In crypto/drbg.c (ffffffff81534a25)
Location: crypto/drbg.c:1893
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_seed
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
In crypto/drbg.c (ffffffff81551975)
Location: crypto/drbg.c:1893
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_seed
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
In crypto/drbg.c (ffffffff81559f9c)
Location: crypto/drbg.c:1894
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
In crypto/drbg.c (ffffffff815bb21c)
Location: crypto/drbg.c:1894
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_seed
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In crypto/drbg.c (ffffffff81663150)
Location: crypto/drbg.c:1898
Inline: True
Direct callers:
  - crypto/drbg.c:drbg_kcapi_seed
```
**Symbols:**

```
ffffffff81663150-ffffffff8166322b: drbg_convert_tfm_core.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In crypto/drbg.c (ffffffff8171d3d0)
Location: crypto/drbg.c:1896
Inline: True
Direct callers:
  - crypto/drbg.c:drbg_kcapi_seed
```
**Symbols:**

```
ffffffff8171d3d0-ffffffff8171d4ab: drbg_convert_tfm_core.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In crypto/drbg.c (ffffffff81758c60)
Location: crypto/drbg.c:1896
Inline: True
Direct callers:
  - crypto/drbg.c:drbg_kcapi_seed
```
**Symbols:**

```
ffffffff81758c60-ffffffff81758d8a: drbg_convert_tfm_core.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In crypto/drbg.c (ffffffff8179ab60)
Location: crypto/drbg.c:1880
Inline: True
Direct callers:
  - crypto/drbg.c:drbg_kcapi_seed
```
**Symbols:**

```
ffffffff8179ab60-ffffffff8179ac8a: drbg_convert_tfm_core.constprop.0 (STB_LOCAL)
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
In crypto/drbg.c (ffff8000105d1950)
Location: crypto/drbg.c:1877
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
In crypto/drbg.c (c078085c)
Location: crypto/drbg.c:1877
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
In crypto/drbg.c (c0000000007601d4)
Location: crypto/drbg.c:1877
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
In crypto/drbg.c (ffffffe00041664a)
Location: crypto/drbg.c:1877
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
In crypto/drbg.c (ffffffff814cf9d8)
Location: crypto/drbg.c:1877
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
In crypto/drbg.c (ffffffff814c03f8)
Location: crypto/drbg.c:1877
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
In crypto/drbg.c (ffffffff814cba68)
Location: crypto/drbg.c:1877
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
In crypto/drbg.c (ffffffff814e4538)
Location: crypto/drbg.c:1877
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_seed
```
</details>
</li>
</ul>

## Differences
