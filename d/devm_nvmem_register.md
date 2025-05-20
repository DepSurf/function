# Function: <code>devm_nvmem_register</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct nvmem_device *devm_nvmem_register(struct device *dev, const struct nvmem_config *config);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff81867630)
Location: drivers/nvmem/core.c:578
Inline: False
```
**Symbols:**

```
ffffffff81867630-ffffffff818676c0: devm_nvmem_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct nvmem_device *devm_nvmem_register(struct device *dev, const struct nvmem_config *config);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff818876e0)
Location: drivers/nvmem/core.c:750
Inline: False
Direct callers:
  - drivers/rtc/nvmem.c:rtc_nvmem_register
```
**Symbols:**

```
ffffffff818876e0-ffffffff81887770: devm_nvmem_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct nvmem_device *devm_nvmem_register(struct device *dev, const struct nvmem_config *config);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff818d1760)
Location: drivers/nvmem/core.c:496
Inline: False
Direct callers:
  - drivers/rtc/nvmem.c:rtc_nvmem_register
```
**Symbols:**

```
ffffffff818d1760-ffffffff818d17e6: devm_nvmem_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct nvmem_device *devm_nvmem_register(struct device *dev, const struct nvmem_config *config);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff81903b60)
Location: drivers/nvmem/core.c:493
Inline: False
Direct callers:
  - drivers/rtc/nvmem.c:rtc_nvmem_register
```
**Symbols:**

```
ffffffff81903b60-ffffffff81903be6: devm_nvmem_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct nvmem_device *devm_nvmem_register(struct device *dev, const struct nvmem_config *config);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff819db480)
Location: drivers/nvmem/core.c:733
Inline: False
Direct callers:
  - drivers/rtc/nvmem.c:rtc_nvmem_register
```
**Symbols:**

```
ffffffff819db480-ffffffff819db4f8: devm_nvmem_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct nvmem_device *devm_nvmem_register(struct device *dev, const struct nvmem_config *config);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff819dab00)
Location: drivers/nvmem/core.c:908
Inline: False
Direct callers:
  - drivers/rtc/nvmem.c:devm_rtc_nvmem_register
```
**Symbols:**

```
ffffffff819dab00-ffffffff819dab78: devm_nvmem_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct nvmem_device *devm_nvmem_register(struct device *dev, const struct nvmem_config *config);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff819c06e0)
Location: drivers/nvmem/core.c:911
Inline: False
Direct callers:
  - drivers/rtc/nvmem.c:devm_rtc_nvmem_register
```
**Symbols:**

```
ffffffff819c06e0-ffffffff819c0758: devm_nvmem_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct nvmem_device *devm_nvmem_register(struct device *dev, const struct nvmem_config *config);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff81a6fec0)
Location: drivers/nvmem/core.c:922
Inline: False
Direct callers:
  - drivers/rtc/nvmem.c:devm_rtc_nvmem_register
```
**Symbols:**

```
ffffffff81a6fec0-ffffffff81a6ff3f: devm_nvmem_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct nvmem_device *devm_nvmem_register(struct device *dev, const struct nvmem_config *config);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff81be1300)
Location: drivers/nvmem/core.c:928
Inline: False
Direct callers:
  - drivers/rtc/nvmem.c:devm_rtc_nvmem_register
```
**Symbols:**

```
ffffffff81be1300-ffffffff81be1358: devm_nvmem_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct nvmem_device *devm_nvmem_register(struct device *dev, const struct nvmem_config *config);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff81d8cbe0)
Location: drivers/nvmem/core.c:926
Inline: False
Direct callers:
  - drivers/rtc/nvmem.c:devm_rtc_nvmem_register
```
**Symbols:**

```
ffffffff81d8cbe0-ffffffff81d8cc38: devm_nvmem_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct nvmem_device *devm_nvmem_register(struct device *dev, const struct nvmem_config *config);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff81dfb2d0)
Location: drivers/nvmem/core.c:1076
Inline: False
Direct callers:
  - drivers/rtc/nvmem.c:devm_rtc_nvmem_register
```
**Symbols:**

```
ffffffff81dfb2d0-ffffffff81dfb331: devm_nvmem_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct nvmem_device *devm_nvmem_register(struct device *dev, const struct nvmem_config *config);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff81eb2920)
Location: drivers/nvmem/core.c:1087
Inline: False
Direct callers:
  - drivers/rtc/nvmem.c:devm_rtc_nvmem_register
```
**Symbols:**

```
ffffffff81eb2920-ffffffff81eb2981: devm_nvmem_register (STB_GLOBAL)
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
struct nvmem_device *devm_nvmem_register(struct device *dev, const struct nvmem_config *config);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffff800010ba0178)
Location: drivers/nvmem/core.c:493
Inline: False
Direct callers:
  - drivers/rtc/nvmem.c:rtc_nvmem_register
  - drivers/nvmem/zynqmp_nvmem.c:zynqmp_nvmem_probe
```
**Symbols:**

```
ffff800010ba0178-ffff800010ba0210: devm_nvmem_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct nvmem_device *devm_nvmem_register(struct device *dev, const struct nvmem_config *config);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (c0c81b14)
Location: drivers/nvmem/core.c:493
Inline: False
Direct callers:
  - drivers/rtc/nvmem.c:rtc_nvmem_register
```
**Symbols:**

```
c0c81b14-c0c81ba0: devm_nvmem_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct nvmem_device *devm_nvmem_register(struct device *dev, const struct nvmem_config *config);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (c000000000c73b20)
Location: drivers/nvmem/core.c:493
Inline: False
Direct callers:
  - drivers/rtc/nvmem.c:rtc_nvmem_register
```
**Symbols:**

```
c000000000c73b20-c000000000c73bec: devm_nvmem_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct nvmem_device *devm_nvmem_register(struct device *dev, const struct nvmem_config *config);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffe000738236)
Location: drivers/nvmem/core.c:493
Inline: False
Direct callers:
  - drivers/rtc/nvmem.c:rtc_nvmem_register
```
**Symbols:**

```
ffffffe000738236-ffffffe0007382ba: devm_nvmem_register (STB_GLOBAL)
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
struct nvmem_device *devm_nvmem_register(struct device *dev, const struct nvmem_config *config);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff818a2f90)
Location: drivers/nvmem/core.c:493
Inline: False
Direct callers:
  - drivers/rtc/nvmem.c:rtc_nvmem_register
```
**Symbols:**

```
ffffffff818a2f90-ffffffff818a3016: devm_nvmem_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct nvmem_device *devm_nvmem_register(struct device *dev, const struct nvmem_config *config);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff8185e700)
Location: drivers/nvmem/core.c:493
Inline: False
Direct callers:
  - drivers/rtc/nvmem.c:rtc_nvmem_register
```
**Symbols:**

```
ffffffff8185e700-ffffffff8185e786: devm_nvmem_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct nvmem_device *devm_nvmem_register(struct device *dev, const struct nvmem_config *config);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff818f4580)
Location: drivers/nvmem/core.c:493
Inline: False
Direct callers:
  - drivers/rtc/nvmem.c:rtc_nvmem_register
```
**Symbols:**

```
ffffffff818f4580-ffffffff818f4606: devm_nvmem_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct nvmem_device *devm_nvmem_register(struct device *dev, const struct nvmem_config *config);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff81915620)
Location: drivers/nvmem/core.c:493
Inline: False
Direct callers:
  - drivers/rtc/nvmem.c:rtc_nvmem_register
```
**Symbols:**

```
ffffffff81915620-ffffffff819156a6: devm_nvmem_register (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
