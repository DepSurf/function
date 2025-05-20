# Function: <code>init_cache_level</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int init_cache_level(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_cacheinfo.c (ffffffff8103fd60)
Location: arch/x86/kernel/cpu/intel_cacheinfo.c:940
Inline: False
```
**Symbols:**

```
ffffffff8103fd60-ffffffff8103fdaa: init_cache_level (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int init_cache_level(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_cacheinfo.c (ffffffff8103fbc0)
Location: arch/x86/kernel/cpu/intel_cacheinfo.c:940
Inline: False
Direct callers:
  - drivers/base/cacheinfo.c:detect_cache_attributes
```
**Symbols:**

```
ffffffff8103fbc0-ffffffff8103fc0a: init_cache_level (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int init_cache_level(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_cacheinfo.c (ffffffff8103f610)
Location: arch/x86/kernel/cpu/intel_cacheinfo.c:962
Inline: False
```
**Symbols:**

```
ffffffff8103f610-ffffffff8103f65a: init_cache_level (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int init_cache_level(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_cacheinfo.c (ffffffff8103d500)
Location: arch/x86/kernel/cpu/intel_cacheinfo.c:963
Inline: True
```
**Symbols:**

```
ffffffff8103d500-ffffffff8103d54a: init_cache_level (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int init_cache_level(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_cacheinfo.c (ffffffff81040080)
Location: arch/x86/kernel/cpu/intel_cacheinfo.c:967
Inline: True
```
**Symbols:**

```
ffffffff81040080-ffffffff810400ca: init_cache_level (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int init_cache_level(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff810418b0)
Location: arch/x86/kernel/cpu/cacheinfo.c:1009
Inline: True
```
**Symbols:**

```
ffffffff810418b0-ffffffff810418fa: init_cache_level (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int init_cache_level(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81042f70)
Location: arch/x86/kernel/cpu/cacheinfo.c:1037
Inline: True
```
**Symbols:**

```
ffffffff81042f70-ffffffff81042fba: init_cache_level (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int init_cache_level(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff810452f0)
Location: arch/x86/kernel/cpu/cacheinfo.c:1037
Inline: False
```
**Symbols:**

```
ffffffff810452f0-ffffffff8104533a: init_cache_level (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int init_cache_level(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81045a40)
Location: arch/x86/kernel/cpu/cacheinfo.c:1037
Inline: False
```
**Symbols:**

```
ffffffff81045a40-ffffffff81045a8a: init_cache_level (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int init_cache_level(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81049860)
Location: arch/x86/kernel/cpu/cacheinfo.c:1037
Inline: True
Direct callers:
  - drivers/base/cacheinfo.c:detect_cache_attributes
```
**Symbols:**

```
ffffffff81049860-ffffffff810498aa: init_cache_level (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int init_cache_level(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81048d00)
Location: arch/x86/kernel/cpu/cacheinfo.c:1037
Inline: True
Direct callers:
  - drivers/base/cacheinfo.c:detect_cache_attributes
```
**Symbols:**

```
ffffffff81048d00-ffffffff81048d4a: init_cache_level (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int init_cache_level(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff8104a5d0)
Location: arch/x86/kernel/cpu/cacheinfo.c:1037
Inline: True
```
**Symbols:**

```
ffffffff8104a5d0-ffffffff8104a61a: init_cache_level (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int init_cache_level(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81051350)
Location: arch/x86/kernel/cpu/cacheinfo.c:988
Inline: True
```
**Symbols:**

```
ffffffff81051350-ffffffff8105138b: init_cache_level (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int init_cache_level(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff8105c900)
Location: arch/x86/kernel/cpu/cacheinfo.c:989
Inline: True
```
**Symbols:**

```
ffffffff8105c900-ffffffff8105c953: init_cache_level (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int init_cache_level(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff8106a910)
Location: arch/x86/kernel/cpu/cacheinfo.c:1002
Inline: True
Direct callers:
  - drivers/base/cacheinfo.c:detect_cache_attributes
```
**Symbols:**

```
ffffffff8106a910-ffffffff8106a963: init_cache_level (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int init_cache_level(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff8106c280)
Location: arch/x86/kernel/cpu/cacheinfo.c:1001
Inline: False
```
**Symbols:**

```
ffffffff8106c280-ffffffff8106c2d3: init_cache_level (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int init_cache_level(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81073510)
Location: arch/x86/kernel/cpu/cacheinfo.c:1003
Inline: False
```
**Symbols:**

```
ffffffff81073510-ffffffff81073521: init_cache_level (STB_GLOBAL)
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
int init_cache_level(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/arm64/kernel/cacheinfo.c (ffff80001009b9a0)
Location: arch/arm64/kernel/cacheinfo.c:101
Inline: True
```
**Symbols:**

```
ffff80001009b9a0-ffff80001009ba04: init_cache_level (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int init_cache_level(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/cacheinfo.c (c09e0a24)
Location: drivers/base/cacheinfo.c:302
Inline: True
```
**Symbols:**

```
c09e0a24-c09e0a40: init_cache_level (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int init_cache_level(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/cacheinfo.c (c00000000098e4e0)
Location: drivers/base/cacheinfo.c:302
Inline: False
```
**Symbols:**

```
c00000000098e4e0-c00000000098e4f0: init_cache_level (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int init_cache_level(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/riscv/kernel/cacheinfo.c (ffffffe0000b7916)
Location: arch/riscv/kernel/cacheinfo.c:99
Inline: True
```
**Symbols:**

```
ffffffe0000b7916-ffffffe0000b7952: init_cache_level (STB_GLOBAL)
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
int init_cache_level(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81045bc0)
Location: arch/x86/kernel/cpu/cacheinfo.c:1037
Inline: False
```
**Symbols:**

```
ffffffff81045bc0-ffffffff81045c0a: init_cache_level (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int init_cache_level(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81034fd0)
Location: arch/x86/kernel/cpu/cacheinfo.c:1037
Inline: False
```
**Symbols:**

```
ffffffff81034fd0-ffffffff8103501a: init_cache_level (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int init_cache_level(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81045a00)
Location: arch/x86/kernel/cpu/cacheinfo.c:1037
Inline: False
```
**Symbols:**

```
ffffffff81045a00-ffffffff81045a4a: init_cache_level (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int init_cache_level(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81046e00)
Location: arch/x86/kernel/cpu/cacheinfo.c:1037
Inline: False
```
**Symbols:**

```
ffffffff81046e00-ffffffff81046e4a: init_cache_level (STB_GLOBAL)
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
