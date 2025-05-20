# Function: <code>vfp_compare</code>

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
<summary>In <code>armhf</code>: Collision, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/arm/vfp/vfpsingle.c (c030574c)
Location: arch/arm/vfp/vfpsingle.c:403
Inline: True
Direct callers:
  - arch/arm/vfp/vfpsingle.c:vfp_single_fcmpez
  - arch/arm/vfp/vfpsingle.c:vfp_single_fcmpz
  - arch/arm/vfp/vfpsingle.c:vfp_single_fcmpe
  - arch/arm/vfp/vfpsingle.c:vfp_single_fcmp
```
```
In arch/arm/vfp/vfpdouble.c (c0307ce4)
Location: arch/arm/vfp/vfpdouble.c:358
Inline: True
Direct callers:
  - arch/arm/vfp/vfpdouble.c:vfp_double_fcmpez
  - arch/arm/vfp/vfpdouble.c:vfp_double_fcmpz
  - arch/arm/vfp/vfpdouble.c:vfp_double_fcmpe
  - arch/arm/vfp/vfpdouble.c:vfp_double_fcmp
```
**Symbols:**

```
c030574c-c0305888: vfp_compare.constprop.0 (STB_LOCAL)
c0307ce4-c0307e88: vfp_compare.constprop.0 (STB_LOCAL)
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
