# Function: <code>__traceiter_hyperv_send_ipi_mask</code>

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
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __traceiter_hyperv_send_ipi_mask(void *__data, const struct cpumask *cpus, int vector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/mmu.c (ffffffff81030e90)
Location: arch/x86/include/asm/trace/hyperv.h:59
Inline: False
```
**Symbols:**

```
ffffffff81030e90-ffffffff81030ed7: __traceiter_hyperv_send_ipi_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __traceiter_hyperv_send_ipi_mask(void *__data, const struct cpumask *cpus, int vector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/mmu.c (ffffffff810319f0)
Location: arch/x86/include/asm/trace/hyperv.h:59
Inline: False
```
**Symbols:**

```
ffffffff810319f0-ffffffff81031a35: __traceiter_hyperv_send_ipi_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __traceiter_hyperv_send_ipi_mask(void *__data, const struct cpumask *cpus, int vector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/mmu.c (ffffffff81036b70)
Location: arch/x86/include/asm/trace/hyperv.h:59
Inline: False
```
**Symbols:**

```
ffffffff81036b70-ffffffff81036bb5: __traceiter_hyperv_send_ipi_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __traceiter_hyperv_send_ipi_mask(void *__data, const struct cpumask *cpus, int vector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/mmu.c (ffffffff8103cbf0)
Location: arch/x86/include/asm/trace/hyperv.h:59
Inline: False
```
**Symbols:**

```
ffffffff8103cbf0-ffffffff8103cc3f: __traceiter_hyperv_send_ipi_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __traceiter_hyperv_send_ipi_mask(void *__data, const struct cpumask *cpus, int vector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/mmu.c (ffffffff81045890)
Location: arch/x86/include/asm/trace/hyperv.h:59
Inline: False
```
**Symbols:**

```
ffffffff81045890-ffffffff810458df: __traceiter_hyperv_send_ipi_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __traceiter_hyperv_send_ipi_mask(void *__data, const struct cpumask *cpus, int vector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/mmu.c (ffffffff81045a00)
Location: arch/x86/include/asm/trace/hyperv.h:59
Inline: False
```
**Symbols:**

```
ffffffff81045a00-ffffffff81045a4f: __traceiter_hyperv_send_ipi_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __traceiter_hyperv_send_ipi_mask(void *__data, const struct cpumask *cpus, int vector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/mmu.c (ffffffff8104c0d0)
Location: arch/x86/include/asm/trace/hyperv.h:59
Inline: False
```
**Symbols:**

```
ffffffff8104c0d0-ffffffff8104c11f: __traceiter_hyperv_send_ipi_mask (STB_GLOBAL)
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
<b>Regular</b>
<ul>
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
