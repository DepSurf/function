# Function: <code>tpm_chip_alloc</code>

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
struct tpm_chip *tpm_chip_alloc(struct device *dev, const struct tpm_class_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-chip.c (ffffffff81578700)
Location: drivers/char/tpm/tpm-chip.c:143
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-chip.c:tpmm_chip_alloc
```
**Symbols:**

```
ffffffff81578700-ffffffff815788bb: tpm_chip_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct tpm_chip *tpm_chip_alloc(struct device *dev, const struct tpm_class_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-chip.c (ffffffff815a4e90)
Location: drivers/char/tpm/tpm-chip.c:144
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-chip.c:tpmm_chip_alloc
```
**Symbols:**

```
ffffffff815a4e90-ffffffff815a504b: tpm_chip_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct tpm_chip *tpm_chip_alloc(struct device *pdev, const struct tpm_class_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-chip.c (ffffffff815b8e20)
Location: drivers/char/tpm/tpm-chip.c:188
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-chip.c:tpmm_chip_alloc
```
**Symbols:**

```
ffffffff815b8e20-ffffffff815b90c6: tpm_chip_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct tpm_chip *tpm_chip_alloc(struct device *pdev, const struct tpm_class_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-chip.c (ffffffff8161f940)
Location: drivers/char/tpm/tpm-chip.c:181
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-chip.c:tpmm_chip_alloc
```
**Symbols:**

```
ffffffff8161f940-ffffffff8161fc0e: tpm_chip_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct tpm_chip *tpm_chip_alloc(struct device *pdev, const struct tpm_class_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-chip.c (ffffffff81659760)
Location: drivers/char/tpm/tpm-chip.c:186
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-chip.c:tpmm_chip_alloc
```
**Symbols:**

```
ffffffff81659760-ffffffff816599fa: tpm_chip_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct tpm_chip *tpm_chip_alloc(struct device *pdev, const struct tpm_class_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-chip.c (ffffffff81675710)
Location: drivers/char/tpm/tpm-chip.c:210
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-chip.c:tpmm_chip_alloc
```
**Symbols:**

```
ffffffff81675710-ffffffff816759aa: tpm_chip_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct tpm_chip *tpm_chip_alloc(struct device *pdev, const struct tpm_class_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm-chip.c (0)
Location: drivers/char/tpm/tpm-chip.c:324
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-chip.c:tpmm_chip_alloc
```
**Symbols:**

```
ffffffff816ab7b1-ffffffff816ab7d0: tpm_chip_alloc.cold (STB_LOCAL)
ffffffff816ab3a0-ffffffff816ab64e: tpm_chip_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
struct tpm_chip *tpm_chip_alloc(struct device *pdev, const struct tpm_class_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm-chip.c (0)
Location: drivers/char/tpm/tpm-chip.c:321
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-chip.c:tpmm_chip_alloc
```
**Symbols:**

```
ffffffff816ce4f5-ffffffff816ce514: tpm_chip_alloc.cold (STB_LOCAL)
ffffffff816ce0e0-ffffffff816ce38e: tpm_chip_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
struct tpm_chip *tpm_chip_alloc(struct device *pdev, const struct tpm_class_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm-chip.c (0)
Location: drivers/char/tpm/tpm-chip.c:321
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-chip.c:tpmm_chip_alloc
```
**Symbols:**

```
ffffffff8178340c-ffffffff8178342b: tpm_chip_alloc.cold (STB_LOCAL)
ffffffff81782ab0-ffffffff81782d2e: tpm_chip_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
struct tpm_chip *tpm_chip_alloc(struct device *pdev, const struct tpm_class_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm-chip.c (0)
Location: drivers/char/tpm/tpm-chip.c:321
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-chip.c:tpmm_chip_alloc
```
**Symbols:**

```
ffffffff81c0a31d-ffffffff81c0a33c: tpm_chip_alloc.cold (STB_LOCAL)
ffffffff8179a100-ffffffff8179a37e: tpm_chip_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
struct tpm_chip *tpm_chip_alloc(struct device *pdev, const struct tpm_class_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm-chip.c (0)
Location: drivers/char/tpm/tpm-chip.c:321
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-chip.c:tpmm_chip_alloc
```
**Symbols:**

```
ffffffff81bfbd18-ffffffff81bfbd37: tpm_chip_alloc.cold (STB_LOCAL)
ffffffff8177cbe0-ffffffff8177ce5e: tpm_chip_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct tpm_chip *tpm_chip_alloc(struct device *pdev, const struct tpm_class_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm-chip.c (0)
Location: drivers/char/tpm/tpm-chip.c:321
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-chip.c:tpmm_chip_alloc
```
**Symbols:**

```
ffffffff81cfc9a2-ffffffff81cfc9c1: tpm_chip_alloc.cold (STB_LOCAL)
ffffffff81802db0-ffffffff8180302e: tpm_chip_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct tpm_chip *tpm_chip_alloc(struct device *pdev, const struct tpm_class_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm-chip.c (0)
Location: drivers/char/tpm/tpm-chip.c:313
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-chip.c:tpmm_chip_alloc
```
**Symbols:**

```
ffffffff81ec51dd-ffffffff81ec51fc: tpm_chip_alloc.cold (STB_LOCAL)
ffffffff81942670-ffffffff81942844: tpm_chip_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct tpm_chip *tpm_chip_alloc(struct device *pdev, const struct tpm_class_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-chip.c (ffffffff81aa4de0)
Location: drivers/char/tpm/tpm-chip.c:313
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-chip.c:tpmm_chip_alloc
```
**Symbols:**

```
ffffffff81aa4de0-ffffffff81aa4fea: tpm_chip_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct tpm_chip *tpm_chip_alloc(struct device *pdev, const struct tpm_class_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-chip.c (ffffffff81af0710)
Location: drivers/char/tpm/tpm-chip.c:312
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-chip.c:tpmm_chip_alloc
```
**Symbols:**

```
ffffffff81af0710-ffffffff81af0912: tpm_chip_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct tpm_chip *tpm_chip_alloc(struct device *pdev, const struct tpm_class_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-chip.c (ffffffff81b43c50)
Location: drivers/char/tpm/tpm-chip.c:317
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-chip.c:tpmm_chip_alloc
```
**Symbols:**

```
ffffffff81b43c50-ffffffff81b43e7e: tpm_chip_alloc (STB_GLOBAL)
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
struct tpm_chip *tpm_chip_alloc(struct device *pdev, const struct tpm_class_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-chip.c (ffff8000108b7f10)
Location: drivers/char/tpm/tpm-chip.c:321
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-chip.c:tpmm_chip_alloc
```
**Symbols:**

```
ffff8000108b7f10-ffff8000108b8194: tpm_chip_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct tpm_chip *tpm_chip_alloc(struct device *pdev, const struct tpm_class_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-chip.c (c09b17b4)
Location: drivers/char/tpm/tpm-chip.c:321
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-chip.c:tpmm_chip_alloc
```
**Symbols:**

```
c09b17b4-c09b1a28: tpm_chip_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct tpm_chip *tpm_chip_alloc(struct device *pdev, const struct tpm_class_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-chip.c (c000000000958ed0)
Location: drivers/char/tpm/tpm-chip.c:321
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-chip.c:tpmm_chip_alloc
```
**Symbols:**

```
c000000000958ed0-c00000000095927c: tpm_chip_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct tpm_chip *tpm_chip_alloc(struct device *pdev, const struct tpm_class_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-chip.c (ffffffe000568bc8)
Location: drivers/char/tpm/tpm-chip.c:321
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-chip.c:tpmm_chip_alloc
```
**Symbols:**

```
ffffffe000568bc8-ffffffe000568e4c: tpm_chip_alloc (STB_GLOBAL)
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
struct tpm_chip *tpm_chip_alloc(struct device *pdev, const struct tpm_class_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm-chip.c (0)
Location: drivers/char/tpm/tpm-chip.c:321
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-chip.c:tpmm_chip_alloc
```
**Symbols:**

```
ffffffff81693f45-ffffffff81693f64: tpm_chip_alloc.cold (STB_LOCAL)
ffffffff81693b30-ffffffff81693dde: tpm_chip_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
struct tpm_chip *tpm_chip_alloc(struct device *pdev, const struct tpm_class_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm-chip.c (0)
Location: drivers/char/tpm/tpm-chip.c:321
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-chip.c:tpmm_chip_alloc
```
**Symbols:**

```
ffffffff81671935-ffffffff81671954: tpm_chip_alloc.cold (STB_LOCAL)
ffffffff81671520-ffffffff816717ce: tpm_chip_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
struct tpm_chip *tpm_chip_alloc(struct device *pdev, const struct tpm_class_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm-chip.c (0)
Location: drivers/char/tpm/tpm-chip.c:321
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-chip.c:tpmm_chip_alloc
```
**Symbols:**

```
ffffffff816c21b5-ffffffff816c21d4: tpm_chip_alloc.cold (STB_LOCAL)
ffffffff816c1da0-ffffffff816c204e: tpm_chip_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
struct tpm_chip *tpm_chip_alloc(struct device *pdev, const struct tpm_class_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm-chip.c (0)
Location: drivers/char/tpm/tpm-chip.c:321
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-chip.c:tpmm_chip_alloc
```
**Symbols:**

```
ffffffff816dc785-ffffffff816dc7a4: tpm_chip_alloc.cold (STB_LOCAL)
ffffffff816dc370-ffffffff816dc61e: tpm_chip_alloc (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct device *pdev</code>
</li>
<li>
<b>Param removed. </b>
<code>struct device *dev</code>
</li>
</ul>
</details>
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
