# Function: <code>__vfp_single_normaliseround</code>

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
<summary>In <code>armhf</code>: ✅</summary>

```c
u32 __vfp_single_normaliseround(int sd, struct vfp_single *vs, u32 fpscr, u32 exceptions);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm/vfp/vfpsingle.c (c0306550)
Location: arch/arm/vfp/vfpsingle.c:70
Inline: False
Direct callers:
  - arch/arm/vfp/vfpsingle.c:vfp_single_fdiv
  - arch/arm/vfp/vfpsingle.c:vfp_single_fadd
  - arch/arm/vfp/vfpsingle.c:vfp_single_fnmul
  - arch/arm/vfp/vfpsingle.c:vfp_single_fmul
  - arch/arm/vfp/vfpsingle.c:vfp_single_fsito
  - arch/arm/vfp/vfpsingle.c:vfp_single_fuito
  - arch/arm/vfp/vfpsingle.c:vfp_single_fsqrt
  - arch/arm/vfp/vfpdouble.c:vfp_double_fcvts
```
**Symbols:**

```
c0306550-c03067c8: __vfp_single_normaliseround (STB_GLOBAL)
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
<b>Arch</b>
<ul>
</ul>
