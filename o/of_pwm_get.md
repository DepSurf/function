# Function: <code>of_pwm_get</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct pwm_device *of_pwm_get(struct device_node *np, const char *con_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pwm/core.c (ffffffff8142cd19)
Location: drivers/pwm/core.c:570
Inline: True
Inline callers:
  - drivers/pwm/core.c:devm_of_pwm_get
```
**Symbols:**

```
ffffffff8142d120-ffffffff8142d162: of_pwm_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct pwm_device *of_pwm_get(struct device_node *np, const char *con_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pwm/core.c (ffffffff81477eb8)
Location: drivers/pwm/core.c:647
Inline: True
Inline callers:
  - drivers/pwm/core.c:devm_of_pwm_get
```
**Symbols:**

```
ffffffff81478330-ffffffff81478376: of_pwm_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct pwm_device *of_pwm_get(struct device_node *np, const char *con_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pwm/core.c (ffffffff81499218)
Location: drivers/pwm/core.c:649
Inline: True
Inline callers:
  - drivers/pwm/core.c:devm_of_pwm_get
```
**Symbols:**

```
ffffffff81499690-ffffffff814996d6: of_pwm_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct pwm_device *of_pwm_get(struct device_node *np, const char *con_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pwm/core.c (ffffffff814a32e9)
Location: drivers/pwm/core.c:658
Inline: True
Inline callers:
  - drivers/pwm/core.c:devm_of_pwm_get
```
**Symbols:**

```
ffffffff814a2e70-ffffffff814a2ea2: of_pwm_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct pwm_device *of_pwm_get(struct device_node *np, const char *con_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pwm/core.c (ffffffff814e2059)
Location: drivers/pwm/core.c:658
Inline: True
Inline callers:
  - drivers/pwm/core.c:devm_of_pwm_get
```
**Symbols:**

```
ffffffff814e1be0-ffffffff814e1c12: of_pwm_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct pwm_device *of_pwm_get(struct device_node *np, const char *con_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pwm/core.c (ffffffff81511402)
Location: drivers/pwm/core.c:658
Inline: True
Inline callers:
  - drivers/pwm/core.c:devm_of_pwm_get
```
**Symbols:**

```
ffffffff8151197a-ffffffff81511992: of_pwm_get.cold.22 (STB_LOCAL)
ffffffff81511850-ffffffff8151186b: of_pwm_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct pwm_device *of_pwm_get(struct device_node *np, const char *con_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pwm/core.c (ffffffff815269e2)
Location: drivers/pwm/core.c:658
Inline: True
Inline callers:
  - drivers/pwm/core.c:devm_of_pwm_get
  - drivers/pwm/core.c:devm_of_pwm_get
```
**Symbols:**

```
ffffffff8152702a-ffffffff81527042: of_pwm_get.cold.22 (STB_LOCAL)
ffffffff81526f00-ffffffff81526f1b: of_pwm_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct pwm_device *of_pwm_get(struct device *dev, struct device_node *np, const char *con_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pwm/core.c (ffffffff81555a02)
Location: drivers/pwm/core.c:676
Inline: True
Inline callers:
  - drivers/pwm/core.c:devm_of_pwm_get
  - drivers/pwm/core.c:devm_of_pwm_get
```
**Symbols:**

```
ffffffff815560a8-ffffffff815560c0: of_pwm_get.cold (STB_LOCAL)
ffffffff81555f10-ffffffff81555f2b: of_pwm_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct pwm_device *of_pwm_get(struct device *dev, struct device_node *np, const char *con_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pwm/core.c (ffffffff81577042)
Location: drivers/pwm/core.c:677
Inline: True
Inline callers:
  - drivers/pwm/core.c:devm_of_pwm_get
  - drivers/pwm/core.c:devm_of_pwm_get
```
**Symbols:**

```
ffffffff815776bf-ffffffff815776d7: of_pwm_get.cold (STB_LOCAL)
ffffffff81577550-ffffffff8157756b: of_pwm_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct pwm_device *of_pwm_get(struct device *dev, struct device_node *np, const char *con_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pwm/core.c (ffffffff8161b632)
Location: drivers/pwm/core.c:805
Inline: True
Inline callers:
  - drivers/pwm/core.c:devm_of_pwm_get
  - drivers/pwm/core.c:devm_of_pwm_get
```
**Symbols:**

```
ffffffff8161c5b6-ffffffff8161c5ce: of_pwm_get.cold (STB_LOCAL)
ffffffff8161be40-ffffffff8161be5b: of_pwm_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct pwm_device *of_pwm_get(struct device *dev, struct device_node *np, const char *con_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pwm/core.c (ffffffff81641da2)
Location: drivers/pwm/core.c:805
Inline: True
Inline callers:
  - drivers/pwm/core.c:devm_of_pwm_get
  - drivers/pwm/core.c:devm_of_pwm_get
```
**Symbols:**

```
ffffffff81bf6ca3-ffffffff81bf6cbb: of_pwm_get.cold (STB_LOCAL)
ffffffff816425f0-ffffffff8164260b: of_pwm_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct pwm_device *of_pwm_get(struct device *dev, struct device_node *np, const char *con_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pwm/core.c (ffffffff81624c82)
Location: drivers/pwm/core.c:775
Inline: True
Inline callers:
  - drivers/pwm/core.c:devm_of_pwm_get
  - drivers/pwm/core.c:devm_of_pwm_get
```
**Symbols:**

```
ffffffff81be8b07-ffffffff81be8b27: of_pwm_get.cold (STB_LOCAL)
ffffffff81625410-ffffffff81625426: of_pwm_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct pwm_device *of_pwm_get(struct device *dev, struct device_node *np, const char *con_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pwm/core.c (ffffffff81694485)
Location: drivers/pwm/core.c:763
Inline: True
Inline callers:
  - drivers/pwm/core.c:devm_of_pwm_get
  - drivers/pwm/core.c:devm_of_pwm_get
```
**Symbols:**

```
ffffffff81ce2cf8-ffffffff81ce2d18: of_pwm_get.cold (STB_LOCAL)
ffffffff81694c90-ffffffff81694ca6: of_pwm_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct pwm_device *of_pwm_get(struct device *dev, struct device_node *np, const char *con_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pwm/core.c (ffffffff817b57e5)
Location: drivers/pwm/core.c:817
Inline: True
Inline callers:
  - drivers/pwm/core.c:devm_of_pwm_get
  - drivers/pwm/core.c:devm_of_pwm_get
```
**Symbols:**

```
ffffffff81ea97a1-ffffffff81ea97c9: of_pwm_get.part.0 (STB_LOCAL)
ffffffff81ea97c9-ffffffff81ea97e1: of_pwm_get.cold (STB_LOCAL)
ffffffff817b5300-ffffffff817b531c: of_pwm_get (STB_GLOBAL)
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
In drivers/pwm/core.c (0)
Location: drivers/pwm/core.c:746
Inline: True
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
In drivers/pwm/core.c (0)
Location: drivers/pwm/core.c:689
Inline: True
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
In drivers/pwm/core.c (0)
Location: drivers/pwm/core.c:673
Inline: True
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
struct pwm_device *of_pwm_get(struct device *dev, struct device_node *np, const char *con_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/core.c (ffff8000106d8360)
Location: drivers/pwm/core.c:677
Inline: False
Direct callers:
  - drivers/pwm/core.c:devm_fwnode_pwm_get
  - drivers/pwm/core.c:devm_of_pwm_get
  - drivers/pwm/core.c:pwm_get
```
**Symbols:**

```
ffff8000106d8360-ffff8000106d8570: of_pwm_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct pwm_device *of_pwm_get(struct device *dev, struct device_node *np, const char *con_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/core.c (c0875188)
Location: drivers/pwm/core.c:677
Inline: False
Direct callers:
  - drivers/pwm/core.c:devm_fwnode_pwm_get
  - drivers/pwm/core.c:devm_of_pwm_get
  - drivers/pwm/core.c:pwm_get
```
**Symbols:**

```
c0875188-c0875380: of_pwm_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct pwm_device *of_pwm_get(struct device *dev, struct device_node *np, const char *con_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/core.c (c00000000084f580)
Location: drivers/pwm/core.c:677
Inline: False
Direct callers:
  - drivers/pwm/core.c:devm_fwnode_pwm_get
  - drivers/pwm/core.c:devm_of_pwm_get
  - drivers/pwm/core.c:pwm_get
```
**Symbols:**

```
c00000000084f580-c00000000084f844: of_pwm_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct pwm_device *of_pwm_get(struct device *dev, struct device_node *np, const char *con_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/core.c (ffffffe0004b1872)
Location: drivers/pwm/core.c:677
Inline: False
Direct callers:
  - drivers/pwm/core.c:devm_fwnode_pwm_get
  - drivers/pwm/core.c:devm_of_pwm_get
  - drivers/pwm/core.c:pwm_get
```
**Symbols:**

```
ffffffe0004b1872-ffffffe0004b1a18: of_pwm_get (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct pwm_device *of_pwm_get(struct device *dev, struct device_node *np, const char *con_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pwm/core.c (ffffffff8156be52)
Location: drivers/pwm/core.c:677
Inline: True
Inline callers:
  - drivers/pwm/core.c:devm_of_pwm_get
  - drivers/pwm/core.c:devm_of_pwm_get
```
**Symbols:**

```
ffffffff8156c4cf-ffffffff8156c4e7: of_pwm_get.cold (STB_LOCAL)
ffffffff8156c360-ffffffff8156c37b: of_pwm_get (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct pwm_device *of_pwm_get(struct device *dev, struct device_node *np, const char *con_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pwm/core.c (ffffffff8156ad92)
Location: drivers/pwm/core.c:677
Inline: True
Inline callers:
  - drivers/pwm/core.c:devm_of_pwm_get
  - drivers/pwm/core.c:devm_of_pwm_get
```
**Symbols:**

```
ffffffff8156b40f-ffffffff8156b427: of_pwm_get.cold (STB_LOCAL)
ffffffff8156b2a0-ffffffff8156b2bb: of_pwm_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct pwm_device *of_pwm_get(struct device *dev, struct device_node *np, const char *con_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pwm/core.c (ffffffff81585292)
Location: drivers/pwm/core.c:677
Inline: True
Inline callers:
  - drivers/pwm/core.c:devm_of_pwm_get
  - drivers/pwm/core.c:devm_of_pwm_get
```
**Symbols:**

```
ffffffff8158590f-ffffffff81585927: of_pwm_get.cold (STB_LOCAL)
ffffffff815857a0-ffffffff815857bb: of_pwm_get (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
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
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct device *dev</code>
</li>
<li>
<b>Param reordered. </b>
<code>np, con_id</code> ➡️ <code>dev, np, con_id</code>
</li>
</ul>
</details>
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
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
