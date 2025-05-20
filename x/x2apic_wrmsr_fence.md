# Function: <code>x2apic_wrmsr_fence</code>

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
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8105980f)
Location: arch/x86/include/asm/apic.h:176
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff81059c3c)
Location: arch/x86/include/asm/apic.h:176
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
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
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff81059a8f)
Location: arch/x86/include/asm/apic.h:183
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff81059f0c)
Location: arch/x86/include/asm/apic.h:183
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI
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
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8105c83f)
Location: arch/x86/include/asm/apic.h:182
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8105cccc)
Location: arch/x86/include/asm/apic.h:182
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI
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
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8105bf4f)
Location: arch/x86/include/asm/apic.h:181
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8105c63c)
Location: arch/x86/include/asm/apic.h:181
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI
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
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8106001f)
Location: arch/x86/include/asm/apic.h:197
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8106036b)
Location: arch/x86/include/asm/apic.h:197
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI
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
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff81062fe5)
Location: arch/x86/include/asm/apic.h:198
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff81063445)
Location: arch/x86/include/asm/apic.h:198
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI
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
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff81068dc5)
Location: arch/x86/include/asm/apic.h:198
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff81069145)
Location: arch/x86/include/asm/apic.h:198
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI
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
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8106c5f5)
Location: arch/x86/include/asm/apic.h:200
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8106c995)
Location: arch/x86/include/asm/apic.h:200
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI
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
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8106de4a)
Location: arch/x86/include/asm/apic.h:205
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_all
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_allbutself
  - arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8106e135)
Location: arch/x86/include/asm/apic.h:205
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI
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
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff810752fa)
Location: arch/x86/include/asm/apic.h:205
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_all
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_allbutself
  - arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff810757b5)
Location: arch/x86/include/asm/apic.h:205
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI
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
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8106cdea)
Location: arch/x86/include/asm/apic.h:205
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_all
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_allbutself
  - arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8106d0d5)
Location: arch/x86/include/asm/apic.h:205
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8105d107)
Location: arch/x86/include/asm/apic.h:205
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_all
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_allbutself
  - arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8105d4d5)
Location: arch/x86/include/asm/apic.h:205
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI
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
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8106d29a)
Location: arch/x86/include/asm/apic.h:205
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_all
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_allbutself
  - arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8106d585)
Location: arch/x86/include/asm/apic.h:205
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI
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
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8106f51a)
Location: arch/x86/include/asm/apic.h:205
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_all
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_allbutself
  - arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8106f805)
Location: arch/x86/include/asm/apic.h:205
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI
```
</details>
</li>
</ul>

## Differences
