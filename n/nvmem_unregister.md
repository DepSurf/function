# Function: <code>nvmem_unregister</code>

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
<summary>In <code>4.13</code>: ✅</summary>

```c
int nvmem_unregister(struct nvmem_device *nvmem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff817a5430)
Location: drivers/nvmem/core.c:527
Inline: False
Direct callers:
  - drivers/rtc/nvmem.c:rtc_nvmem_unregister
```
**Symbols:**

```
ffffffff817a5430-ffffffff817a54fc: nvmem_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int nvmem_unregister(struct nvmem_device *nvmem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff8181c5a0)
Location: drivers/nvmem/core.c:529
Inline: False
Direct callers:
  - drivers/rtc/nvmem.c:rtc_nvmem_unregister
```
**Symbols:**

```
ffffffff8181c5a0-ffffffff8181c66c: nvmem_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int nvmem_unregister(struct nvmem_device *nvmem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff818666f0)
Location: drivers/nvmem/core.c:542
Inline: False
Direct callers:
  - drivers/rtc/nvmem.c:rtc_nvmem_unregister
```
**Symbols:**

```
ffffffff818666f0-ffffffff818667b8: nvmem_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void nvmem_unregister(struct nvmem_device *nvmem);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff81886f75)
Location: drivers/nvmem/core.c:728
Inline: True
Inline callers:
  - drivers/nvmem/core.c:devm_nvmem_release
```
**Symbols:**

```
ffffffff81886f40-ffffffff81886f6b: nvmem_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void nvmem_unregister(struct nvmem_device *nvmem);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff818d17f5)
Location: drivers/nvmem/core.c:474
Inline: True
Inline callers:
  - drivers/nvmem/core.c:devm_nvmem_release
```
**Symbols:**

```
ffffffff818d1230-ffffffff818d125a: nvmem_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void nvmem_unregister(struct nvmem_device *nvmem);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff81903bf5)
Location: drivers/nvmem/core.c:471
Inline: True
Inline callers:
  - drivers/nvmem/core.c:devm_nvmem_release
```
**Symbols:**

```
ffffffff81903630-ffffffff8190365a: nvmem_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void nvmem_unregister(struct nvmem_device *nvmem);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff819daa25)
Location: drivers/nvmem/core.c:711
Inline: True
Inline callers:
  - drivers/nvmem/core.c:devm_nvmem_release
```
**Symbols:**

```
ffffffff819da9d0-ffffffff819daa11: nvmem_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void nvmem_unregister(struct nvmem_device *nvmem);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff819d98b5)
Location: drivers/nvmem/core.c:886
Inline: True
Inline callers:
  - drivers/nvmem/core.c:devm_nvmem_release
```
**Symbols:**

```
ffffffff819d9860-ffffffff819d98a1: nvmem_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void nvmem_unregister(struct nvmem_device *nvmem);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff819bfb55)
Location: drivers/nvmem/core.c:889
Inline: True
Inline callers:
  - drivers/nvmem/core.c:devm_nvmem_release
```
**Symbols:**

```
ffffffff819bfb00-ffffffff819bfb41: nvmem_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void nvmem_unregister(struct nvmem_device *nvmem);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff81a6f1a5)
Location: drivers/nvmem/core.c:900
Inline: True
Inline callers:
  - drivers/nvmem/core.c:devm_nvmem_release
```
**Symbols:**

```
ffffffff81a6f150-ffffffff81a6f191: nvmem_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void nvmem_unregister(struct nvmem_device *nvmem);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff81be0095)
Location: drivers/nvmem/core.c:905
Inline: True
Inline callers:
  - drivers/nvmem/core.c:devm_nvmem_unregister
  - drivers/nvmem/core.c:devm_nvmem_unregister
```
**Symbols:**

```
ffffffff81be0010-ffffffff81be0087: nvmem_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void nvmem_unregister(struct nvmem_device *nvmem);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff81d8b8a5)
Location: drivers/nvmem/core.c:903
Inline: True
Inline callers:
  - drivers/nvmem/core.c:devm_nvmem_unregister
  - drivers/nvmem/core.c:devm_nvmem_unregister
```
**Symbols:**

```
ffffffff81d8b810-ffffffff81d8b887: nvmem_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void nvmem_unregister(struct nvmem_device *nvmem);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff81df9e05)
Location: drivers/nvmem/core.c:1053
Inline: True
Inline callers:
  - drivers/nvmem/core.c:devm_nvmem_unregister
  - drivers/nvmem/core.c:devm_nvmem_unregister
```
**Symbols:**

```
ffffffff81df9d70-ffffffff81df9de7: nvmem_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void nvmem_unregister(struct nvmem_device *nvmem);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff81eb2865)
Location: drivers/nvmem/core.c:1064
Inline: True
Inline callers:
  - drivers/nvmem/core.c:devm_nvmem_unregister
  - drivers/nvmem/core.c:devm_nvmem_unregister
```
**Symbols:**

```
ffffffff81eb27a0-ffffffff81eb284f: nvmem_unregister (STB_GLOBAL)
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
void nvmem_unregister(struct nvmem_device *nvmem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffff800010b9ed28)
Location: drivers/nvmem/core.c:471
Inline: False
Direct callers:
  - drivers/nvmem/core.c:devm_nvmem_release
```
**Symbols:**

```
ffff800010b9ed28-ffff800010b9ed68: nvmem_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void nvmem_unregister(struct nvmem_device *nvmem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (c0c80af0)
Location: drivers/nvmem/core.c:471
Inline: False
Direct callers:
  - drivers/mtd/mtdcore.c:del_mtd_device
  - drivers/nvmem/core.c:devm_nvmem_release
```
**Symbols:**

```
c0c80af0-c0c80b24: nvmem_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void nvmem_unregister(struct nvmem_device *nvmem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (c000000000c71fa0)
Location: drivers/nvmem/core.c:471
Inline: False
Direct callers:
  - drivers/nvmem/core.c:devm_nvmem_release
```
**Symbols:**

```
c000000000c71fa0-c000000000c71fe0: nvmem_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void nvmem_unregister(struct nvmem_device *nvmem);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffe00073707c)
Location: drivers/nvmem/core.c:471
Inline: True
Inline callers:
  - drivers/nvmem/core.c:devm_nvmem_release
```
**Symbols:**

```
ffffffe000737022-ffffffe000737066: nvmem_unregister (STB_GLOBAL)
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
void nvmem_unregister(struct nvmem_device *nvmem);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff818a3025)
Location: drivers/nvmem/core.c:471
Inline: True
Inline callers:
  - drivers/nvmem/core.c:devm_nvmem_release
```
**Symbols:**

```
ffffffff818a2a60-ffffffff818a2a8a: nvmem_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void nvmem_unregister(struct nvmem_device *nvmem);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff8185e795)
Location: drivers/nvmem/core.c:471
Inline: True
Inline callers:
  - drivers/nvmem/core.c:devm_nvmem_release
```
**Symbols:**

```
ffffffff8185e1d0-ffffffff8185e1fa: nvmem_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void nvmem_unregister(struct nvmem_device *nvmem);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff818f4615)
Location: drivers/nvmem/core.c:471
Inline: True
Inline callers:
  - drivers/nvmem/core.c:devm_nvmem_release
```
**Symbols:**

```
ffffffff818f4050-ffffffff818f407a: nvmem_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void nvmem_unregister(struct nvmem_device *nvmem);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff819156b5)
Location: drivers/nvmem/core.c:471
Inline: True
Inline callers:
  - drivers/nvmem/core.c:devm_nvmem_release
```
**Symbols:**

```
ffffffff819150f0-ffffffff8191511a: nvmem_unregister (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>void</code>
</li>
</ul>
</details>
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
