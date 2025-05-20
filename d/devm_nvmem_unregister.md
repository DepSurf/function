# Function: <code>devm_nvmem_unregister</code>

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
int devm_nvmem_unregister(struct device *dev, struct nvmem_device *nvmem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff818667c0)
Location: drivers/nvmem/core.c:616
Inline: False
```
**Symbols:**

```
ffffffff818667c0-ffffffff818667e1: devm_nvmem_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int devm_nvmem_unregister(struct device *dev, struct nvmem_device *nvmem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff81886640)
Location: drivers/nvmem/core.c:788
Inline: False
```
**Symbols:**

```
ffffffff81886640-ffffffff81886661: devm_nvmem_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int devm_nvmem_unregister(struct device *dev, struct nvmem_device *nvmem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff818d0b70)
Location: drivers/nvmem/core.c:534
Inline: False
```
**Symbols:**

```
ffffffff818d0b70-ffffffff818d0b91: devm_nvmem_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int devm_nvmem_unregister(struct device *dev, struct nvmem_device *nvmem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff81902fd0)
Location: drivers/nvmem/core.c:531
Inline: False
```
**Symbols:**

```
ffffffff81902fd0-ffffffff81902ff1: devm_nvmem_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int devm_nvmem_unregister(struct device *dev, struct nvmem_device *nvmem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff819d9fb0)
Location: drivers/nvmem/core.c:771
Inline: False
```
**Symbols:**

```
ffffffff819d9fb0-ffffffff819d9fd1: devm_nvmem_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int devm_nvmem_unregister(struct device *dev, struct nvmem_device *nvmem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff819d9200)
Location: drivers/nvmem/core.c:946
Inline: False
```
**Symbols:**

```
ffffffff819d9200-ffffffff819d9221: devm_nvmem_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int devm_nvmem_unregister(struct device *dev, struct nvmem_device *nvmem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff819bf360)
Location: drivers/nvmem/core.c:949
Inline: False
```
**Symbols:**

```
ffffffff819bf360-ffffffff819bf381: devm_nvmem_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int devm_nvmem_unregister(struct device *dev, struct nvmem_device *nvmem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff81a6e830)
Location: drivers/nvmem/core.c:960
Inline: False
```
**Symbols:**

```
ffffffff81a6e830-ffffffff81a6e851: devm_nvmem_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void devm_nvmem_unregister(void *nvmem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff81be0090)
Location: drivers/nvmem/core.c:912
Inline: False
Direct callers:
  - drivers/nvmem/core.c:devm_nvmem_register
```
**Symbols:**

```
ffffffff81be0090-ffffffff81be0107: devm_nvmem_unregister (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void devm_nvmem_unregister(void *nvmem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff81d8b8a0)
Location: drivers/nvmem/core.c:910
Inline: False
Direct callers:
  - drivers/nvmem/core.c:devm_nvmem_register
```
**Symbols:**

```
ffffffff81d8b8a0-ffffffff81d8b917: devm_nvmem_unregister (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void devm_nvmem_unregister(void *nvmem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff81df9e00)
Location: drivers/nvmem/core.c:1060
Inline: False
Direct callers:
  - drivers/nvmem/core.c:devm_nvmem_register
```
**Symbols:**

```
ffffffff81df9e00-ffffffff81df9e77: devm_nvmem_unregister (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void devm_nvmem_unregister(void *nvmem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff81eb2860)
Location: drivers/nvmem/core.c:1071
Inline: False
Direct callers:
  - drivers/nvmem/core.c:devm_nvmem_register
```
**Symbols:**

```
ffffffff81eb2860-ffffffff81eb290f: devm_nvmem_unregister (STB_LOCAL)
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
int devm_nvmem_unregister(struct device *dev, struct nvmem_device *nvmem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffff800010b9ed98)
Location: drivers/nvmem/core.c:531
Inline: False
```
**Symbols:**

```
ffff800010b9ed98-ffff800010b9eddc: devm_nvmem_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int devm_nvmem_unregister(struct device *dev, struct nvmem_device *nvmem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (c0c80b44)
Location: drivers/nvmem/core.c:531
Inline: False
```
**Symbols:**

```
c0c80b44-c0c80b74: devm_nvmem_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int devm_nvmem_unregister(struct device *dev, struct nvmem_device *nvmem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (c000000000c72000)
Location: drivers/nvmem/core.c:531
Inline: False
```
**Symbols:**

```
c000000000c72000-c000000000c72048: devm_nvmem_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int devm_nvmem_unregister(struct device *dev, struct nvmem_device *nvmem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffe0007370ac)
Location: drivers/nvmem/core.c:531
Inline: False
```
**Symbols:**

```
ffffffe0007370ac-ffffffe0007370ee: devm_nvmem_unregister (STB_GLOBAL)
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
int devm_nvmem_unregister(struct device *dev, struct nvmem_device *nvmem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff818a2400)
Location: drivers/nvmem/core.c:531
Inline: False
```
**Symbols:**

```
ffffffff818a2400-ffffffff818a2421: devm_nvmem_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int devm_nvmem_unregister(struct device *dev, struct nvmem_device *nvmem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff8185db70)
Location: drivers/nvmem/core.c:531
Inline: False
```
**Symbols:**

```
ffffffff8185db70-ffffffff8185db91: devm_nvmem_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int devm_nvmem_unregister(struct device *dev, struct nvmem_device *nvmem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff818f39f0)
Location: drivers/nvmem/core.c:531
Inline: False
```
**Symbols:**

```
ffffffff818f39f0-ffffffff818f3a11: devm_nvmem_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int devm_nvmem_unregister(struct device *dev, struct nvmem_device *nvmem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff81914a90)
Location: drivers/nvmem/core.c:531
Inline: False
```
**Symbols:**

```
ffffffff81914a90-ffffffff81914ab1: devm_nvmem_unregister (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct device *dev</code>
</li>
<li>
<b>Param reordered. </b>
<code>dev, nvmem</code> ➡️ <code>nvmem</code>
</li>
<li>
<b>Param type changed. </b>
<code>struct nvmem_device *nvmem</code> ➡️ <code>void *nvmem</code>
</li>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>void</code>
</li>
</ul>
</details>
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
