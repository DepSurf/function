# Function: <code>__send_ipi_mask_ex</code>

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
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_apic.c (ffffffff8102bd61)
Location: arch/x86/hyperv/hv_apic.c:94
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_apic.c (ffffffff8102cd58)
Location: arch/x86/hyperv/hv_apic.c:95
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool __send_ipi_mask_ex(const struct cpumask *mask, int vector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_apic.c (ffffffff8102e980)
Location: arch/x86/hyperv/hv_apic.c:100
Inline: False
Direct callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
```
**Symbols:**

```
ffffffff8102e980-ffffffff8102eb4c: __send_ipi_mask_ex (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool __send_ipi_mask_ex(const struct cpumask *mask, int vector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_apic.c (ffffffff8102f290)
Location: arch/x86/hyperv/hv_apic.c:100
Inline: False
Direct callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
```
**Symbols:**

```
ffffffff8102f290-ffffffff8102f45c: __send_ipi_mask_ex (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/hyperv/hv_apic.c (ffffffff81031e5b)
Location: arch/x86/hyperv/hv_apic.c:100
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_one
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
Direct callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_one
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
```
**Symbols:**

```
ffffffff810317c0-ffffffff81031998: __send_ipi_mask_ex.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/hyperv/hv_apic.c (ffffffff81032b24)
Location: arch/x86/hyperv/hv_apic.c:100
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_one
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
Direct callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_one
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
```
**Symbols:**

```
ffffffff810324c0-ffffffff81032698: __send_ipi_mask_ex.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/hyperv/hv_apic.c (ffffffff81033f84)
Location: arch/x86/hyperv/hv_apic.c:102
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_one
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
Direct callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_one
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
```
**Symbols:**

```
ffffffff81033900-ffffffff81033ae9: __send_ipi_mask_ex.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/hyperv/hv_apic.c (ffffffff810391e5)
Location: arch/x86/hyperv/hv_apic.c:102
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_one
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
Direct callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_one
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
```
**Symbols:**

```
ffffffff81038bc0-ffffffff81038ead: __send_ipi_mask_ex.part.0 (STB_LOCAL)
ffffffff81c97f3f-ffffffff81c97f7b: __send_ipi_mask_ex.part.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/hyperv/hv_apic.c (ffffffff81040092)
Location: arch/x86/hyperv/hv_apic.c:102
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_one
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
Direct callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_one
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
```
**Symbols:**

```
ffffffff8103f950-ffffffff8103fc7d: __send_ipi_mask_ex.part.0 (STB_LOCAL)
ffffffff81e473d1-ffffffff81e47401: __send_ipi_mask_ex.part.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/hyperv/hv_apic.c (ffffffff810492c2)
Location: arch/x86/hyperv/hv_apic.c:102
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_one
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
Direct callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_one
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
```
**Symbols:**

```
ffffffff81048a20-ffffffff81048bb6: __send_ipi_mask_ex.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/hyperv/hv_apic.c (ffffffff81049522)
Location: arch/x86/hyperv/hv_apic.c:107
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_one
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
Direct callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_one
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
```
**Symbols:**

```
ffffffff81048cb0-ffffffff81048e12: __send_ipi_mask_ex.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/hyperv/hv_apic.c (ffffffff81050495)
Location: arch/x86/hyperv/hv_apic.c:107
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_one
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
Direct callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_one
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
```
**Symbols:**

```
ffffffff8104ff70-ffffffff81050081: __send_ipi_mask_ex.part.0 (STB_LOCAL)
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
bool __send_ipi_mask_ex(const struct cpumask *mask, int vector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_apic.c (ffffffff8102f3f0)
Location: arch/x86/hyperv/hv_apic.c:100
Inline: False
Direct callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
```
**Symbols:**

```
ffffffff8102f3f0-ffffffff8102f5bc: __send_ipi_mask_ex (STB_LOCAL)
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
In arch/x86/hyperv/hv_apic.c (ffffffff8101ed9d)
Location: arch/x86/hyperv/hv_apic.c:100
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool __send_ipi_mask_ex(const struct cpumask *mask, int vector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_apic.c (ffffffff8102f250)
Location: arch/x86/hyperv/hv_apic.c:100
Inline: False
Direct callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
```
**Symbols:**

```
ffffffff8102f250-ffffffff8102f41c: __send_ipi_mask_ex (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool __send_ipi_mask_ex(const struct cpumask *mask, int vector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_apic.c (ffffffff81030090)
Location: arch/x86/hyperv/hv_apic.c:100
Inline: False
Direct callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
```
**Symbols:**

```
ffffffff81030090-ffffffff8103025c: __send_ipi_mask_ex (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
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
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
