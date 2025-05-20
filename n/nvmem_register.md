# Function: <code>nvmem_register</code>

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
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct nvmem_device *nvmem_register(const struct nvmem_config *config);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff817a5e40)
Location: drivers/nvmem/core.c:444
Inline: True
Direct callers:
  - drivers/rtc/nvmem.c:rtc_nvmem_register
```
**Symbols:**

```
ffffffff817a5e40-ffffffff817a62b4: nvmem_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct nvmem_device *nvmem_register(const struct nvmem_config *config);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff8181cfd0)
Location: drivers/nvmem/core.c:444
Inline: True
Direct callers:
  - drivers/rtc/nvmem.c:rtc_nvmem_register
```
**Symbols:**

```
ffffffff8181cfd0-ffffffff8181d46d: nvmem_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct nvmem_device *nvmem_register(const struct nvmem_config *config);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvmem/core.c (ffffffff81867675)
Location: drivers/nvmem/core.c:454
Inline: True
Inline callers:
  - drivers/nvmem/core.c:devm_nvmem_register
Direct callers:
  - drivers/nvmem/core.c:devm_nvmem_register
```
**Symbols:**

```
ffffffff81867240-ffffffff8186760f: nvmem_register.part.9 (STB_LOCAL)
ffffffff81867610-ffffffff8186762e: nvmem_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct nvmem_device *nvmem_register(const struct nvmem_config *config);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvmem/core.c (ffffffff81887725)
Location: drivers/nvmem/core.c:603
Inline: True
Inline callers:
  - drivers/nvmem/core.c:devm_nvmem_register
Direct callers:
  - drivers/nvmem/core.c:devm_nvmem_register
```
**Symbols:**

```
ffffffff81887080-ffffffff818876b2: nvmem_register.part.15 (STB_LOCAL)
ffffffff818876c0-ffffffff818876de: nvmem_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct nvmem_device *nvmem_register(const struct nvmem_config *config);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvmem/core.c (ffffffff818d179d)
Location: drivers/nvmem/core.c:356
Inline: True
Inline callers:
  - drivers/nvmem/core.c:devm_nvmem_register
Direct callers:
  - drivers/nvmem/core.c:devm_nvmem_register
```
**Symbols:**

```
ffffffff818d1260-ffffffff818d1740: nvmem_register.part.0 (STB_LOCAL)
ffffffff818d1740-ffffffff818d175e: nvmem_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct nvmem_device *nvmem_register(const struct nvmem_config *config);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvmem/core.c (ffffffff81903b9d)
Location: drivers/nvmem/core.c:353
Inline: True
Inline callers:
  - drivers/nvmem/core.c:devm_nvmem_register
Direct callers:
  - drivers/nvmem/core.c:devm_nvmem_register
```
**Symbols:**

```
ffffffff81903660-ffffffff81903b40: nvmem_register.part.0 (STB_LOCAL)
ffffffff81903b40-ffffffff81903b5e: nvmem_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
struct nvmem_device *nvmem_register(const struct nvmem_config *config);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvmem/core.c (0)
Location: drivers/nvmem/core.c:578
Inline: False
Direct callers:
  - drivers/nvmem/core.c:devm_nvmem_register
```
**Symbols:**

```
ffffffff819db890-ffffffff819db8a6: nvmem_register.cold (STB_LOCAL)
ffffffff819dafb0-ffffffff819db474: nvmem_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
struct nvmem_device *nvmem_register(const struct nvmem_config *config);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvmem/core.c (0)
Location: drivers/nvmem/core.c:739
Inline: False
Direct callers:
  - drivers/nvmem/core.c:devm_nvmem_register
```
**Symbols:**

```
ffffffff81c3022a-ffffffff81c30241: nvmem_register.cold (STB_LOCAL)
ffffffff819da5f0-ffffffff819daaf7: nvmem_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
struct nvmem_device *nvmem_register(const struct nvmem_config *config);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvmem/core.c (0)
Location: drivers/nvmem/core.c:742
Inline: False
Direct callers:
  - drivers/nvmem/core.c:devm_nvmem_register
```
**Symbols:**

```
ffffffff81c22438-ffffffff81c224c6: nvmem_register.cold (STB_LOCAL)
ffffffff819c0020-ffffffff819c06d2: nvmem_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct nvmem_device *nvmem_register(const struct nvmem_config *config);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvmem/core.c (0)
Location: drivers/nvmem/core.c:748
Inline: False
Direct callers:
  - drivers/nvmem/core.c:devm_nvmem_register
```
**Symbols:**

```
ffffffff81d345db-ffffffff81d3475d: nvmem_register.cold (STB_LOCAL)
ffffffff81a6f770-ffffffff81a6febc: nvmem_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct nvmem_device *nvmem_register(const struct nvmem_config *config);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvmem/core.c (0)
Location: drivers/nvmem/core.c:752
Inline: False
Direct callers:
  - drivers/nvmem/core.c:devm_nvmem_register
```
**Symbols:**

```
ffffffff81f009fd-ffffffff81f00b6b: nvmem_register.cold (STB_LOCAL)
ffffffff81be0b60-ffffffff81be12fb: nvmem_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct nvmem_device *nvmem_register(const struct nvmem_config *config);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvmem/core.c (0)
Location: drivers/nvmem/core.c:752
Inline: False
Direct callers:
  - drivers/nvmem/core.c:devm_nvmem_register
```
**Symbols:**

```
ffffffff820aa8e2-ffffffff820aa9c6: nvmem_register.cold (STB_LOCAL)
ffffffff81d8c410-ffffffff81d8cbc3: nvmem_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct nvmem_device *nvmem_register(const struct nvmem_config *config);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvmem/core.c (0)
Location: drivers/nvmem/core.c:879
Inline: False
Direct callers:
  - drivers/nvmem/core.c:devm_nvmem_register
```
**Symbols:**

```
ffffffff8212be1e-ffffffff8212bf02: nvmem_register.cold (STB_LOCAL)
ffffffff81dfaaa0-ffffffff81dfb2b3: nvmem_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct nvmem_device *nvmem_register(const struct nvmem_config *config);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvmem/core.c (0)
Location: drivers/nvmem/core.c:890
Inline: False
Direct callers:
  - drivers/nvmem/core.c:devm_nvmem_register
```
**Symbols:**

```
ffffffff8220db19-ffffffff8220dbfe: nvmem_register.cold (STB_LOCAL)
ffffffff81eb1af0-ffffffff81eb2315: nvmem_register (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct nvmem_device *nvmem_register(const struct nvmem_config *config);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvmem/core.c (ffff800010ba01b8)
Location: drivers/nvmem/core.c:353
Inline: True
Inline callers:
  - drivers/nvmem/core.c:devm_nvmem_register
Direct callers:
  - drivers/nvmem/core.c:devm_nvmem_register
```
**Symbols:**

```
ffff800010b9fae0-ffff800010ba012c: nvmem_register.part.0 (STB_LOCAL)
ffff800010ba0130-ffff800010ba0174: nvmem_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct nvmem_device *nvmem_register(const struct nvmem_config *config);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvmem/core.c (c0c81b50)
Location: drivers/nvmem/core.c:353
Inline: True
Inline callers:
  - drivers/nvmem/core.c:devm_nvmem_register
Direct callers:
  - drivers/mtd/mtdcore.c:add_mtd_device
  - drivers/nvmem/core.c:devm_nvmem_register
```
**Symbols:**

```
c0c81450-c0c81ae4: nvmem_register.part.0 (STB_LOCAL)
c0c81ae4-c0c81b14: nvmem_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct nvmem_device *nvmem_register(const struct nvmem_config *config);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvmem/core.c (c000000000c73b74)
Location: drivers/nvmem/core.c:353
Inline: True
Inline callers:
  - drivers/nvmem/core.c:devm_nvmem_register
Direct callers:
  - drivers/nvmem/core.c:devm_nvmem_register
```
**Symbols:**

```
c000000000c73150-c000000000c73ae8: nvmem_register.part.0 (STB_LOCAL)
c000000000c73af0-c000000000c73b18: nvmem_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct nvmem_device *nvmem_register(const struct nvmem_config *config);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvmem/core.c (ffffffe000738270)
Location: drivers/nvmem/core.c:353
Inline: True
Inline callers:
  - drivers/nvmem/core.c:devm_nvmem_register
Direct callers:
  - drivers/nvmem/core.c:devm_nvmem_register
```
**Symbols:**

```
ffffffe000737bdc-ffffffe000738206: nvmem_register.part.0 (STB_LOCAL)
ffffffe000738206-ffffffe000738236: nvmem_register (STB_GLOBAL)
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
struct nvmem_device *nvmem_register(const struct nvmem_config *config);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvmem/core.c (ffffffff818a2fcd)
Location: drivers/nvmem/core.c:353
Inline: True
Inline callers:
  - drivers/nvmem/core.c:devm_nvmem_register
Direct callers:
  - drivers/nvmem/core.c:devm_nvmem_register
```
**Symbols:**

```
ffffffff818a2a90-ffffffff818a2f70: nvmem_register.part.0 (STB_LOCAL)
ffffffff818a2f70-ffffffff818a2f8e: nvmem_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct nvmem_device *nvmem_register(const struct nvmem_config *config);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvmem/core.c (ffffffff8185e73d)
Location: drivers/nvmem/core.c:353
Inline: True
Inline callers:
  - drivers/nvmem/core.c:devm_nvmem_register
Direct callers:
  - drivers/nvmem/core.c:devm_nvmem_register
```
**Symbols:**

```
ffffffff8185e200-ffffffff8185e6e0: nvmem_register.part.0 (STB_LOCAL)
ffffffff8185e6e0-ffffffff8185e6fe: nvmem_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct nvmem_device *nvmem_register(const struct nvmem_config *config);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvmem/core.c (ffffffff818f45bd)
Location: drivers/nvmem/core.c:353
Inline: True
Inline callers:
  - drivers/nvmem/core.c:devm_nvmem_register
Direct callers:
  - drivers/nvmem/core.c:devm_nvmem_register
```
**Symbols:**

```
ffffffff818f4080-ffffffff818f4560: nvmem_register.part.0 (STB_LOCAL)
ffffffff818f4560-ffffffff818f457e: nvmem_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct nvmem_device *nvmem_register(const struct nvmem_config *config);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvmem/core.c (ffffffff8191565d)
Location: drivers/nvmem/core.c:353
Inline: True
Inline callers:
  - drivers/nvmem/core.c:devm_nvmem_register
Direct callers:
  - drivers/nvmem/core.c:devm_nvmem_register
```
**Symbols:**

```
ffffffff81915120-ffffffff81915600: nvmem_register.part.0 (STB_LOCAL)
ffffffff81915600-ffffffff8191561e: nvmem_register (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
