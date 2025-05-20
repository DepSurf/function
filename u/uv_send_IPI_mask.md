# Function: <code>uv_send_IPI_mask</code>

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
<summary>In <code>5.4</code>: ✅</summary>

```c
void uv_send_IPI_mask(const struct cpumask *mask, int vector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff8106d3e0)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:552
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_all
```
**Symbols:**

```
ffffffff8106d3e0-ffffffff8106d424: uv_send_IPI_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void uv_send_IPI_mask(const struct cpumask *mask, int vector);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff81074a65)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:586
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_all
```
**Symbols:**

```
ffffffff81074a10-ffffffff81074a54: uv_send_IPI_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void uv_send_IPI_mask(const struct cpumask *mask, int vector);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff810753c4)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:743
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_all
```
**Symbols:**

```
ffffffff81075360-ffffffff810753a4: uv_send_IPI_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void uv_send_IPI_mask(const struct cpumask *mask, int vector);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff81075e64)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:739
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_all
```
**Symbols:**

```
ffffffff81075e00-ffffffff81075e44: uv_send_IPI_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void uv_send_IPI_mask(const struct cpumask *mask, int vector);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff81083434)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:739
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_all
```
**Symbols:**

```
ffffffff810833d0-ffffffff81083414: uv_send_IPI_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void uv_send_IPI_mask(const struct cpumask *mask, int vector);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff810932ce)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:745
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_all
```
**Symbols:**

```
ffffffff81093270-ffffffff810932ba: uv_send_IPI_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void uv_send_IPI_mask(const struct cpumask *mask, int vector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff810a8630)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:745
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_all
```
**Symbols:**

```
ffffffff810a8630-ffffffff810a8681: uv_send_IPI_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void uv_send_IPI_mask(const struct cpumask *mask, int vector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff810ab8a0)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:746
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_all
```
**Symbols:**

```
ffffffff810ab8a0-ffffffff810ab8f1: uv_send_IPI_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void uv_send_IPI_mask(const struct cpumask *mask, int vector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff810b2710)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:747
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_all
```
**Symbols:**

```
ffffffff810b2710-ffffffff810b2761: uv_send_IPI_mask (STB_LOCAL)
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
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void uv_send_IPI_mask(const struct cpumask *mask, int vector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff8106eab0)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:552
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_all
```
**Symbols:**

```
ffffffff8106eab0-ffffffff8106eaf4: uv_send_IPI_mask (STB_LOCAL)
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
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
