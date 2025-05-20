# Function: <code>amd_init_l3_cache</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_cacheinfo.c (ffffffff8103ee76)
Location: arch/x86/kernel/cpu/intel_cacheinfo.c:568
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_cacheinfo.c:cpuid4_cache_lookup_regs
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_cacheinfo.c (ffffffff8103eca1)
Location: arch/x86/kernel/cpu/intel_cacheinfo.c:568
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_cacheinfo.c:cpuid4_cache_lookup_regs
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
In arch/x86/kernel/cpu/intel_cacheinfo.c (ffffffff8103e631)
Location: arch/x86/kernel/cpu/intel_cacheinfo.c:569
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_cacheinfo.c:cpuid4_cache_lookup_regs
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
In arch/x86/kernel/cpu/intel_cacheinfo.c (ffffffff8103c601)
Location: arch/x86/kernel/cpu/intel_cacheinfo.c:570
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_cacheinfo.c:cpuid4_cache_lookup_regs
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
In arch/x86/kernel/cpu/intel_cacheinfo.c (ffffffff8103f211)
Location: arch/x86/kernel/cpu/intel_cacheinfo.c:571
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_cacheinfo.c:cpuid4_cache_lookup_regs
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
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81040801)
Location: arch/x86/kernel/cpu/cacheinfo.c:573
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff810420e8)
Location: arch/x86/kernel/cpu/cacheinfo.c:574
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
Direct callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
```
**Symbols:**

```
ffffffff81041cc0-ffffffff81041de2: amd_init_l3_cache.isra.7.part.8 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff810444fc)
Location: arch/x86/kernel/cpu/cacheinfo.c:575
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
Direct callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
```
**Symbols:**

```
ffffffff81044150-ffffffff81044274: amd_init_l3_cache.isra.0.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81044c4c)
Location: arch/x86/kernel/cpu/cacheinfo.c:575
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
Direct callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
```
**Symbols:**

```
ffffffff810448a0-ffffffff810449c4: amd_init_l3_cache.isra.0.part.0 (STB_LOCAL)
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
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81048e24)
Location: arch/x86/kernel/cpu/cacheinfo.c:575
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff810482e8)
Location: arch/x86/kernel/cpu/cacheinfo.c:575
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
Direct callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
```
**Symbols:**

```
ffffffff810477b0-ffffffff81047807: amd_init_l3_cache.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81049aa8)
Location: arch/x86/kernel/cpu/cacheinfo.c:575
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
Direct callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
```
**Symbols:**

```
ffffffff81048ef0-ffffffff81049022: amd_init_l3_cache.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff810507c8)
Location: arch/x86/kernel/cpu/cacheinfo.c:575
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
Direct callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
```
**Symbols:**

```
ffffffff8104f890-ffffffff8104f9ea: amd_init_l3_cache.part.0 (STB_LOCAL)
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
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff8105bbe1)
Location: arch/x86/kernel/cpu/cacheinfo.c:575
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
Direct callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
```
**Symbols:**

```
ffffffff8105b070-ffffffff8105b1d8: amd_init_l3_cache.part.0 (STB_LOCAL)
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
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81069b81)
Location: arch/x86/kernel/cpu/cacheinfo.c:588
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
Direct callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
```
**Symbols:**

```
ffffffff810689f0-ffffffff81068b58: amd_init_l3_cache.part.0 (STB_LOCAL)
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
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff8106b4a1)
Location: arch/x86/kernel/cpu/cacheinfo.c:590
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
Direct callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
```
**Symbols:**

```
ffffffff8106a300-ffffffff8106a468: amd_init_l3_cache.part.0 (STB_LOCAL)
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
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81072971)
Location: arch/x86/kernel/cpu/cacheinfo.c:599
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
Direct callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
```
**Symbols:**

```
ffffffff810717d0-ffffffff81071937: amd_init_l3_cache.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81044dcc)
Location: arch/x86/kernel/cpu/cacheinfo.c:575
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
Direct callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
```
**Symbols:**

```
ffffffff81044a20-ffffffff81044b44: amd_init_l3_cache.isra.0.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff810342f1)
Location: arch/x86/kernel/cpu/cacheinfo.c:575
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
Direct callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
```
**Symbols:**

```
ffffffff81033fa0-ffffffff810340c4: amd_init_l3_cache.isra.0.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81044c0c)
Location: arch/x86/kernel/cpu/cacheinfo.c:575
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
Direct callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
```
**Symbols:**

```
ffffffff81044860-ffffffff81044984: amd_init_l3_cache.isra.0.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff8104600c)
Location: arch/x86/kernel/cpu/cacheinfo.c:575
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
Direct callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs
```
**Symbols:**

```
ffffffff81045c60-ffffffff81045d84: amd_init_l3_cache.isra.0.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
