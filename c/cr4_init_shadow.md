# Function: <code>cr4_init_shadow</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/head64.c (ffffffff81f5935f)
Location: arch/x86/include/asm/tlbflush.h:34
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:x86_64_start_kernel
```
```
In arch/x86/xen/enlighten.c (ffffffff81f60dbc)
Location: arch/x86/include/asm/tlbflush.h:34
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_start_kernel
```
```
In arch/x86/kernel/cpu/common.c (ffffffff810410b3)
Location: arch/x86/include/asm/tlbflush.h:34
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/head64.c (ffffffff81f812ef)
Location: arch/x86/include/asm/tlbflush.h:82
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:x86_64_start_kernel
```
```
In arch/x86/xen/enlighten.c (ffffffff81f88a11)
Location: arch/x86/include/asm/tlbflush.h:82
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_start_kernel
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81040fd4)
Location: arch/x86/include/asm/tlbflush.h:82
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/head64.c (ffffffff81fbd2ef)
Location: arch/x86/include/asm/tlbflush.h:82
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:x86_64_start_kernel
```
```
In arch/x86/xen/enlighten.c (ffffffff81fc3dff)
Location: arch/x86/include/asm/tlbflush.h:82
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_start_kernel
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81040a1e)
Location: arch/x86/include/asm/tlbflush.h:82
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/head64.c (ffffffff8209d2ea)
Location: arch/x86/include/asm/tlbflush.h:87
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:x86_64_start_kernel
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff820a6091)
Location: arch/x86/include/asm/tlbflush.h:87
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8103e9a1)
Location: arch/x86/include/asm/tlbflush.h:87
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/head64.c (ffffffff826a34dc)
Location: arch/x86/include/asm/tlbflush.h:245
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:x86_64_start_kernel
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff826ac75d)
Location: arch/x86/include/asm/tlbflush.h:245
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8104166e)
Location: arch/x86/include/asm/tlbflush.h:245
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/head64.c (ffffffff826cc4b5)
Location: arch/x86/include/asm/tlbflush.h:290
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:x86_64_start_kernel
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff826d589e)
Location: arch/x86/include/asm/tlbflush.h:290
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81042f3e)
Location: arch/x86/include/asm/tlbflush.h:290
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/head64.c (ffffffff828824c0)
Location: arch/x86/include/asm/tlbflush.h:278
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:x86_64_start_kernel
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff8288b944)
Location: arch/x86/include/asm/tlbflush.h:278
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8104451e)
Location: arch/x86/include/asm/tlbflush.h:278
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/head64.c (ffffffff8289944c)
Location: arch/x86/include/asm/tlbflush.h:280
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:x86_64_start_kernel
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff828a2d7d)
Location: arch/x86/include/asm/tlbflush.h:280
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/head64.c (ffffffff8289c44c)
Location: arch/x86/include/asm/tlbflush.h:280
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:x86_64_start_kernel
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff828a5e30)
Location: arch/x86/include/asm/tlbflush.h:280
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/head64.c (ffffffff82cc252a)
Location: arch/x86/include/asm/tlbflush.h:160
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:x86_64_start_kernel
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff82ccc11e)
Location: arch/x86/include/asm/tlbflush.h:160
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/head64.c (ffffffff82fae5c0)
Location: arch/x86/include/asm/tlbflush.h:160
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:x86_64_start_kernel
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff82fb7f5c)
Location: arch/x86/include/asm/tlbflush.h:160
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/head64.c (ffffffff831b85c0)
Location: arch/x86/include/asm/tlbflush.h:163
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:x86_64_start_kernel
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff831c269f)
Location: arch/x86/include/asm/tlbflush.h:163
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/head64.c (ffffffff83298693)
Location: arch/x86/include/asm/tlbflush.h:163
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:x86_64_start_kernel
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff832a308d)
Location: arch/x86/include/asm/tlbflush.h:163
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/head64.c (ffffffff8344671a)
Location: arch/x86/include/asm/tlbflush.h:163
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:x86_64_start_kernel
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff834522b7)
Location: arch/x86/include/asm/tlbflush.h:163
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/head64.c (ffffffff83e5f7ed)
Location: arch/x86/include/asm/tlbflush.h:164
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:x86_64_start_kernel
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff83e6f0ee)
Location: arch/x86/include/asm/tlbflush.h:164
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_pv.c (ffffffff83690038)
Location: arch/x86/include/asm/tlbflush.h:177
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
```
```
In arch/x86/kernel/head64.c (ffffffff83694ad9)
Location: arch/x86/include/asm/tlbflush.h:177
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:x86_64_start_kernel
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_pv.c (ffffffff838bfb88)
Location: arch/x86/include/asm/tlbflush.h:178
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
```
```
In arch/x86/kernel/head64.c (ffffffff838c49c9)
Location: arch/x86/include/asm/tlbflush.h:178
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:x86_64_start_kernel
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
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/head64.c (ffffffff8288a44c)
Location: arch/x86/include/asm/tlbflush.h:280
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:x86_64_start_kernel
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff82893e39)
Location: arch/x86/include/asm/tlbflush.h:280
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/head64.c (ffffffff828883f0)
Location: arch/x86/include/asm/tlbflush.h:280
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:x86_64_start_kernel
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/head64.c (ffffffff8289d44c)
Location: arch/x86/include/asm/tlbflush.h:280
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:x86_64_start_kernel
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff828a6e30)
Location: arch/x86/include/asm/tlbflush.h:280
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/head64.c (ffffffff8289d44c)
Location: arch/x86/include/asm/tlbflush.h:280
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:x86_64_start_kernel
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff828a6e04)
Location: arch/x86/include/asm/tlbflush.h:280
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
```
</details>
</li>
</ul>

## Differences
