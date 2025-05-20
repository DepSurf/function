# Function: <code>vfp_propagate_nan</code>

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
<summary>In <code>armhf</code>: Collision ⚠️</summary>

```c
u32 vfp_propagate_nan(struct vfp_single *vsd, struct vfp_single *vsn, struct vfp_single *vsm, u32 fpscr);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm/vfp/vfpsingle.c (c0305910)
Location: arch/arm/vfp/vfpsingle.c:215
Inline: False
Direct callers:
  - arch/arm/vfp/vfpsingle.c:vfp_single_fdiv
  - arch/arm/vfp/vfpsingle.c:vfp_single_multiply
  - arch/arm/vfp/vfpsingle.c:vfp_single_add
  - arch/arm/vfp/vfpsingle.c:vfp_single_fsqrt
```
```
In arch/arm/vfp/vfpdouble.c (c0307f10)
Location: arch/arm/vfp/vfpdouble.c:207
Inline: False
Direct callers:
  - arch/arm/vfp/vfpdouble.c:vfp_double_fdiv
  - arch/arm/vfp/vfpdouble.c:vfp_double_multiply
  - arch/arm/vfp/vfpdouble.c:vfp_double_add
  - arch/arm/vfp/vfpdouble.c:vfp_double_fsqrt
```
**Symbols:**

```
c0305910-c0305a68: vfp_propagate_nan (STB_LOCAL)
c0307f10-c0308080: vfp_propagate_nan (STB_LOCAL)
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
