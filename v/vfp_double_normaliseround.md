# Function: <code>vfp_double_normaliseround</code>

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
u32 vfp_double_normaliseround(int dd, struct vfp_double *vd, u32 fpscr, u32 exceptions, const char *func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm/vfp/vfpdouble.c (c0308f54)
Location: arch/arm/vfp/vfpdouble.c:70
Inline: False
Direct callers:
  - arch/arm/vfp/vfpsingle.c:vfp_single_fcvtd
  - arch/arm/vfp/vfpdouble.c:vfp_double_fdiv
  - arch/arm/vfp/vfpdouble.c:vfp_double_fsub
  - arch/arm/vfp/vfpdouble.c:vfp_double_fadd
  - arch/arm/vfp/vfpdouble.c:vfp_double_fnmul
  - arch/arm/vfp/vfpdouble.c:vfp_double_fmul
  - arch/arm/vfp/vfpdouble.c:vfp_double_multiply_accumulate
  - arch/arm/vfp/vfpdouble.c:vfp_double_fsito
  - arch/arm/vfp/vfpdouble.c:vfp_double_fuito
  - arch/arm/vfp/vfpdouble.c:vfp_double_fsqrt
```
**Symbols:**

```
c0308f54-c0309360: vfp_double_normaliseround (STB_GLOBAL)
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
