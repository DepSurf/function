# Function: <code>vfp_single_dump</code>

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
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/arm/vfp/vfpsingle.c (c0305a7c)
Location: arch/arm/vfp/vfpsingle.c:48
Inline: True
Inline callers:
  - arch/arm/vfp/vfpsingle.c:vfp_single_multiply
  - arch/arm/vfp/vfpsingle.c:vfp_single_multiply
  - arch/arm/vfp/vfpsingle.c:vfp_single_multiply
  - arch/arm/vfp/vfpsingle.c:vfp_single_add
  - arch/arm/vfp/vfpsingle.c:vfp_single_add
  - arch/arm/vfp/vfpsingle.c:vfp_single_ftosi
  - arch/arm/vfp/vfpsingle.c:vfp_single_ftoui
  - arch/arm/vfp/vfpsingle.c:vfp_single_fsqrt
  - arch/arm/vfp/vfpsingle.c:vfp_single_fsqrt
  - arch/arm/vfp/vfpsingle.c:__vfp_single_normaliseround
  - arch/arm/vfp/vfpsingle.c:__vfp_single_normaliseround
  - arch/arm/vfp/vfpsingle.c:vfp_single_normalise_denormal
  - arch/arm/vfp/vfpsingle.c:vfp_single_normalise_denormal
Direct callers:
  - arch/arm/vfp/vfpsingle.c:vfp_single_multiply
  - arch/arm/vfp/vfpsingle.c:vfp_single_multiply
  - arch/arm/vfp/vfpsingle.c:vfp_single_multiply
  - arch/arm/vfp/vfpsingle.c:vfp_single_add
  - arch/arm/vfp/vfpsingle.c:vfp_single_add
  - arch/arm/vfp/vfpsingle.c:vfp_single_ftosi
  - arch/arm/vfp/vfpsingle.c:vfp_single_ftoui
  - arch/arm/vfp/vfpsingle.c:vfp_single_fsqrt
  - arch/arm/vfp/vfpsingle.c:vfp_single_fsqrt
  - arch/arm/vfp/vfpsingle.c:__vfp_single_normaliseround
  - arch/arm/vfp/vfpsingle.c:__vfp_single_normaliseround
  - arch/arm/vfp/vfpsingle.c:vfp_single_normalise_denormal
  - arch/arm/vfp/vfpsingle.c:vfp_single_normalise_denormal
  - arch/arm/vfp/vfpsingle.c:vfp_single_normalise_denormal
```
**Symbols:**

```
c0305618-c0305670: vfp_single_dump.part.0 (STB_LOCAL)
```
</details>
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
