# Function: <code>uv_gpa_to_offset</code>

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
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
long unsigned int uv_gpa_to_offset(long unsigned int gpa);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/platform/uv/tlb_uv.c (ffffffff81096297)
Location: arch/x86/include/asm/uv/uv_hub.h:565
Inline: True
```
**Symbols:**

```
ffffffff81096270-ffffffff81096343: uv_gpa_to_offset (STB_LOCAL)
ffffffff81097ea6-ffffffff81097eb7: uv_gpa_to_offset.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
long unsigned int uv_gpa_to_offset(long unsigned int gpa);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/platform/uv/tlb_uv.c (ffffffff8109b8e7)
Location: arch/x86/include/asm/uv/uv_hub.h:511
Inline: True
```
**Symbols:**

```
ffffffff8109b8c0-ffffffff8109b98b: uv_gpa_to_offset (STB_LOCAL)
ffffffff8109d5de-ffffffff8109d5ef: uv_gpa_to_offset.cold (STB_LOCAL)
```
</details>
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
long unsigned int uv_gpa_to_offset(long unsigned int gpa);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/platform/uv/tlb_uv.c (ffffffff81097777)
Location: arch/x86/include/asm/uv/uv_hub.h:565
Inline: True
```
**Symbols:**

```
ffffffff81097750-ffffffff81097823: uv_gpa_to_offset (STB_LOCAL)
ffffffff81099366-ffffffff81099377: uv_gpa_to_offset.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
