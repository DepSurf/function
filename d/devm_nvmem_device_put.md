# Function: <code>devm_nvmem_device_put</code>

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
void devm_nvmem_device_put(struct device *dev, struct nvmem_device *nvmem);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff817a5830)
Location: drivers/nvmem/core.c:692
Inline: True
```
**Symbols:**

```
ffffffff817a5830-ffffffff817a5859: devm_nvmem_device_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void devm_nvmem_device_put(struct device *dev, struct nvmem_device *nvmem);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff8181c9a0)
Location: drivers/nvmem/core.c:694
Inline: True
```
**Symbols:**

```
ffffffff8181c9a0-ffffffff8181c9c9: devm_nvmem_device_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void devm_nvmem_device_put(struct device *dev, struct nvmem_device *nvmem);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff81866aa0)
Location: drivers/nvmem/core.c:763
Inline: True
```
**Symbols:**

```
ffffffff81866aa0-ffffffff81866ac9: devm_nvmem_device_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void devm_nvmem_device_put(struct device *dev, struct nvmem_device *nvmem);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff81886900)
Location: drivers/nvmem/core.c:898
Inline: True
```
**Symbols:**

```
ffffffff81886900-ffffffff81886929: devm_nvmem_device_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void devm_nvmem_device_put(struct device *dev, struct nvmem_device *nvmem);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvmem/core.c (ffffffff818d1d9f)
Location: drivers/nvmem/core.c:647
Inline: True
```
**Symbols:**

```
ffffffff818d1d9f-ffffffff818d1db2: devm_nvmem_device_put.cold (STB_LOCAL)
ffffffff818d0de0-ffffffff818d0e09: devm_nvmem_device_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void devm_nvmem_device_put(struct device *dev, struct nvmem_device *nvmem);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff819031e0)
Location: drivers/nvmem/core.c:644
Inline: True
```
**Symbols:**

```
ffffffff819031e0-ffffffff81903209: devm_nvmem_device_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void devm_nvmem_device_put(struct device *dev, struct nvmem_device *nvmem);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff819da130)
Location: drivers/nvmem/core.c:903
Inline: True
```
**Symbols:**

```
ffffffff819da130-ffffffff819da159: devm_nvmem_device_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void devm_nvmem_device_put(struct device *dev, struct nvmem_device *nvmem);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff819d9230)
Location: drivers/nvmem/core.c:1081
Inline: True
```
**Symbols:**

```
ffffffff819d9230-ffffffff819d9259: devm_nvmem_device_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void devm_nvmem_device_put(struct device *dev, struct nvmem_device *nvmem);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff819bf390)
Location: drivers/nvmem/core.c:1084
Inline: True
```
**Symbols:**

```
ffffffff819bf390-ffffffff819bf3b9: devm_nvmem_device_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void devm_nvmem_device_put(struct device *dev, struct nvmem_device *nvmem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff81a6e860)
Location: drivers/nvmem/core.c:1095
Inline: False
```
**Symbols:**

```
ffffffff81a6e860-ffffffff81a6e889: devm_nvmem_device_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void devm_nvmem_device_put(struct device *dev, struct nvmem_device *nvmem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff81bdf7b0)
Location: drivers/nvmem/core.c:1075
Inline: False
```
**Symbols:**

```
ffffffff81bdf7b0-ffffffff81bdf7f5: devm_nvmem_device_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void devm_nvmem_device_put(struct device *dev, struct nvmem_device *nvmem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff81d8aea0)
Location: drivers/nvmem/core.c:1073
Inline: False
```
**Symbols:**

```
ffffffff81d8aea0-ffffffff81d8aee5: devm_nvmem_device_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void devm_nvmem_device_put(struct device *dev, struct nvmem_device *nvmem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff81df9620)
Location: drivers/nvmem/core.c:1223
Inline: False
```
**Symbols:**

```
ffffffff81df9620-ffffffff81df9665: devm_nvmem_device_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void devm_nvmem_device_put(struct device *dev, struct nvmem_device *nvmem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff81eafca0)
Location: drivers/nvmem/core.c:1234
Inline: False
```
**Symbols:**

```
ffffffff81eafca0-ffffffff81eafce5: devm_nvmem_device_put (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void devm_nvmem_device_put(struct device *dev, struct nvmem_device *nvmem);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffff800010b9f3c8)
Location: drivers/nvmem/core.c:644
Inline: True
```
**Symbols:**

```
ffff800010b9f3c8-ffff800010b9f420: devm_nvmem_device_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void devm_nvmem_device_put(struct device *dev, struct nvmem_device *nvmem);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (c0c811bc)
Location: drivers/nvmem/core.c:644
Inline: True
```
**Symbols:**

```
c0c811bc-c0c8120c: devm_nvmem_device_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void devm_nvmem_device_put(struct device *dev, struct nvmem_device *nvmem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (c000000000c72050)
Location: drivers/nvmem/core.c:644
Inline: False
```
**Symbols:**

```
c000000000c72050-c000000000c720a8: devm_nvmem_device_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void devm_nvmem_device_put(struct device *dev, struct nvmem_device *nvmem);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffe000737652)
Location: drivers/nvmem/core.c:644
Inline: True
```
**Symbols:**

```
ffffffe000737652-ffffffe0007376a4: devm_nvmem_device_put (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void devm_nvmem_device_put(struct device *dev, struct nvmem_device *nvmem);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff818a2610)
Location: drivers/nvmem/core.c:644
Inline: True
```
**Symbols:**

```
ffffffff818a2610-ffffffff818a2639: devm_nvmem_device_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void devm_nvmem_device_put(struct device *dev, struct nvmem_device *nvmem);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff8185dd80)
Location: drivers/nvmem/core.c:644
Inline: True
```
**Symbols:**

```
ffffffff8185dd80-ffffffff8185dda9: devm_nvmem_device_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void devm_nvmem_device_put(struct device *dev, struct nvmem_device *nvmem);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff818f3c00)
Location: drivers/nvmem/core.c:644
Inline: True
```
**Symbols:**

```
ffffffff818f3c00-ffffffff818f3c29: devm_nvmem_device_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void devm_nvmem_device_put(struct device *dev, struct nvmem_device *nvmem);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff81914ca0)
Location: drivers/nvmem/core.c:644
Inline: True
```
**Symbols:**

```
ffffffff81914ca0-ffffffff81914cc9: devm_nvmem_device_put (STB_GLOBAL)
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
