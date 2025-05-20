# Function: <code>get_cpu_address_sizes</code>

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
void get_cpu_address_sizes(struct cpuinfo_x86 *c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff81042790)
Location: arch/x86/kernel/cpu/common.c:908
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:early_cpu_init
```
**Symbols:**

```
ffffffff81042790-ffffffff810427f8: get_cpu_address_sizes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void get_cpu_address_sizes(struct cpuinfo_x86 *c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff81043db0)
Location: arch/x86/kernel/cpu/common.c:908
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:early_cpu_init
```
**Symbols:**

```
ffffffff81043db0-ffffffff81043e18: get_cpu_address_sizes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void get_cpu_address_sizes(struct cpuinfo_x86 *c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff81046320)
Location: arch/x86/kernel/cpu/common.c:976
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/kernel/cpu/common.c:identify_cpu
```
**Symbols:**

```
ffffffff81046320-ffffffff81046388: get_cpu_address_sizes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void get_cpu_address_sizes(struct cpuinfo_x86 *c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff81046a80)
Location: arch/x86/kernel/cpu/common.c:976
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:early_cpu_init
```
**Symbols:**

```
ffffffff81046a80-ffffffff81046ae8: get_cpu_address_sizes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void get_cpu_address_sizes(struct cpuinfo_x86 *c);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff8104a92c)
Location: arch/x86/kernel/cpu/common.c:956
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:generic_identify
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
```
**Symbols:**

```
ffffffff8104ae90-ffffffff8104aef6: get_cpu_address_sizes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void get_cpu_address_sizes(struct cpuinfo_x86 *c);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff81049ddc)
Location: arch/x86/kernel/cpu/common.c:974
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:generic_identify
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
```
**Symbols:**

```
ffffffff8104a380-ffffffff8104a3e6: get_cpu_address_sizes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void get_cpu_address_sizes(struct cpuinfo_x86 *c);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff8104b68c)
Location: arch/x86/kernel/cpu/common.c:975
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:generic_identify
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/kernel/cpu/common.c:early_cpu_init
```
**Symbols:**

```
ffffffff8104bbc0-ffffffff8104bc26: get_cpu_address_sizes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void get_cpu_address_sizes(struct cpuinfo_x86 *c);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff810528a9)
Location: arch/x86/kernel/cpu/common.c:978
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:identify_cpu
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/kernel/cpu/common.c:early_cpu_init
```
**Symbols:**

```
ffffffff81052e80-ffffffff81052ee6: get_cpu_address_sizes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void get_cpu_address_sizes(struct cpuinfo_x86 *c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff8105e1d0)
Location: arch/x86/kernel/cpu/common.c:1086
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/kernel/cpu/common.c:identify_cpu
```
**Symbols:**

```
ffffffff8105e1d0-ffffffff8105e277: get_cpu_address_sizes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void get_cpu_address_sizes(struct cpuinfo_x86 *c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff8106c770)
Location: arch/x86/kernel/cpu/common.c:1107
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/kernel/cpu/common.c:identify_cpu
```
**Symbols:**

```
ffffffff8106c770-ffffffff8106c816: get_cpu_address_sizes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void get_cpu_address_sizes(struct cpuinfo_x86 *c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff8106e150)
Location: arch/x86/kernel/cpu/common.c:1099
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/kernel/cpu/common.c:identify_cpu
```
**Symbols:**

```
ffffffff8106e150-ffffffff8106e1f6: get_cpu_address_sizes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void get_cpu_address_sizes(struct cpuinfo_x86 *c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff810753d0)
Location: arch/x86/kernel/cpu/common.c:1096
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/kernel/cpu/common.c:identify_cpu
```
**Symbols:**

```
ffffffff810753d0-ffffffff810754a9: get_cpu_address_sizes (STB_GLOBAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
void get_cpu_address_sizes(struct cpuinfo_x86 *c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff81046c00)
Location: arch/x86/kernel/cpu/common.c:976
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:early_cpu_init
```
**Symbols:**

```
ffffffff81046c00-ffffffff81046c68: get_cpu_address_sizes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void get_cpu_address_sizes(struct cpuinfo_x86 *c);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff81035d84)
Location: arch/x86/kernel/cpu/common.c:976
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:early_cpu_init
```
**Symbols:**

```
ffffffff810362c0-ffffffff810362f5: get_cpu_address_sizes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void get_cpu_address_sizes(struct cpuinfo_x86 *c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff81046a40)
Location: arch/x86/kernel/cpu/common.c:976
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:early_cpu_init
```
**Symbols:**

```
ffffffff81046a40-ffffffff81046aa8: get_cpu_address_sizes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void get_cpu_address_sizes(struct cpuinfo_x86 *c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff81047e40)
Location: arch/x86/kernel/cpu/common.c:976
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:early_cpu_init
```
**Symbols:**

```
ffffffff81047e40-ffffffff81047ea8: get_cpu_address_sizes (STB_GLOBAL)
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
