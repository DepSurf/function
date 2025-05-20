# Function: <code>hv_send_ipi_mask_allbutself</code>

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
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
void hv_send_ipi_mask_allbutself(const struct cpumask *mask, int vector);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/hyperv/hv_apic.c (ffffffff8102bbe0)
Location: arch/x86/hyperv/hv_apic.c:203
Inline: True
Direct callers:
  - arch/x86/hyperv/hv_apic.c:hv_send_ipi_allbutself
```
**Symbols:**

```
ffffffff8102bbe0-ffffffff8102bbf7: hv_send_ipi_mask_allbutself.part.6 (STB_LOCAL)
ffffffff8102c000-ffffffff8102c0ae: hv_send_ipi_mask_allbutself (STB_LOCAL)
ffffffff8102c102-ffffffff8102c10e: hv_send_ipi_mask_allbutself.cold.12 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
void hv_send_ipi_mask_allbutself(const struct cpumask *mask, int vector);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/hyperv/hv_apic.c (ffffffff8102cbb0)
Location: arch/x86/hyperv/hv_apic.c:210
Inline: True
Direct callers:
  - arch/x86/hyperv/hv_apic.c:hv_send_ipi_allbutself
```
**Symbols:**

```
ffffffff8102cbb0-ffffffff8102cbc7: hv_send_ipi_mask_allbutself.part.6 (STB_LOCAL)
ffffffff8102d000-ffffffff8102d0ae: hv_send_ipi_mask_allbutself (STB_LOCAL)
ffffffff8102d102-ffffffff8102d10e: hv_send_ipi_mask_allbutself.cold.13 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void hv_send_ipi_mask_allbutself(const struct cpumask *mask, int vector);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/hyperv/hv_apic.c (ffffffff8102e930)
Location: arch/x86/hyperv/hv_apic.c:215
Inline: True
Direct callers:
  - arch/x86/hyperv/hv_apic.c:hv_send_ipi_allbutself
```
**Symbols:**

```
ffffffff8102e930-ffffffff8102e947: hv_send_ipi_mask_allbutself.part.0 (STB_LOCAL)
ffffffff8102ede0-ffffffff8102ee8c: hv_send_ipi_mask_allbutself (STB_LOCAL)
ffffffff8102eee4-ffffffff8102eef0: hv_send_ipi_mask_allbutself.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void hv_send_ipi_mask_allbutself(const struct cpumask *mask, int vector);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/hyperv/hv_apic.c (ffffffff8102f240)
Location: arch/x86/hyperv/hv_apic.c:215
Inline: True
Direct callers:
  - arch/x86/hyperv/hv_apic.c:hv_send_ipi_allbutself
```
**Symbols:**

```
ffffffff8102f240-ffffffff8102f257: hv_send_ipi_mask_allbutself.part.0 (STB_LOCAL)
ffffffff8102f6f0-ffffffff8102f79c: hv_send_ipi_mask_allbutself (STB_LOCAL)
ffffffff8102f844-ffffffff8102f850: hv_send_ipi_mask_allbutself.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void hv_send_ipi_mask_allbutself(const struct cpumask *mask, int vector);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/hyperv/hv_apic.c (ffffffff810317a0)
Location: arch/x86/hyperv/hv_apic.c:225
Inline: True
Direct callers:
  - arch/x86/hyperv/hv_apic.c:hv_send_ipi_allbutself
```
**Symbols:**

```
ffffffff810317a0-ffffffff810317b7: hv_send_ipi_mask_allbutself.part.0 (STB_LOCAL)
ffffffff81031b60-ffffffff81031c0c: hv_send_ipi_mask_allbutself (STB_LOCAL)
ffffffff81031f74-ffffffff81031f80: hv_send_ipi_mask_allbutself.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void hv_send_ipi_mask_allbutself(const struct cpumask *mask, int vector);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/hyperv/hv_apic.c (ffffffff810324a0)
Location: arch/x86/hyperv/hv_apic.c:225
Inline: True
Direct callers:
  - arch/x86/hyperv/hv_apic.c:hv_send_ipi_allbutself
```
**Symbols:**

```
ffffffff810324a0-ffffffff810324b7: hv_send_ipi_mask_allbutself.part.0 (STB_LOCAL)
ffffffff81032840-ffffffff810328ec: hv_send_ipi_mask_allbutself (STB_LOCAL)
ffffffff81bd2f93-ffffffff81bd2f9f: hv_send_ipi_mask_allbutself.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void hv_send_ipi_mask_allbutself(const struct cpumask *mask, int vector);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/hyperv/hv_apic.c (ffffffff810338e0)
Location: arch/x86/hyperv/hv_apic.c:229
Inline: True
Direct callers:
  - arch/x86/hyperv/hv_apic.c:hv_send_ipi_allbutself
```
**Symbols:**

```
ffffffff810338e0-ffffffff810338f7: hv_send_ipi_mask_allbutself.part.0 (STB_LOCAL)
ffffffff81033ca0-ffffffff81033d4c: hv_send_ipi_mask_allbutself (STB_LOCAL)
ffffffff81bc536f-ffffffff81bc537b: hv_send_ipi_mask_allbutself.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void hv_send_ipi_mask_allbutself(const struct cpumask *mask, int vector);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_apic.c (ffffffff81039115)
Location: arch/x86/hyperv/hv_apic.c:255
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:hv_send_ipi_allbutself
  - arch/x86/hyperv/hv_apic.c:hv_send_ipi_allbutself
```
**Symbols:**

```
ffffffff81039090-ffffffff810390c9: hv_send_ipi_mask_allbutself (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void hv_send_ipi_mask_allbutself(const struct cpumask *mask, int vector);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_apic.c (ffffffff8103ff35)
Location: arch/x86/hyperv/hv_apic.c:255
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:hv_send_ipi_allbutself
  - arch/x86/hyperv/hv_apic.c:hv_send_ipi_allbutself
```
**Symbols:**

```
ffffffff8103fea0-ffffffff8103fee3: hv_send_ipi_mask_allbutself (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void hv_send_ipi_mask_allbutself(const struct cpumask *mask, int vector);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_apic.c (ffffffff81048ed5)
Location: arch/x86/hyperv/hv_apic.c:255
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:hv_send_ipi_allbutself
  - arch/x86/hyperv/hv_apic.c:hv_send_ipi_allbutself
```
**Symbols:**

```
ffffffff81048e20-ffffffff81048e63: hv_send_ipi_mask_allbutself (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void hv_send_ipi_mask_allbutself(const struct cpumask *mask, int vector);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_apic.c (ffffffff81049135)
Location: arch/x86/hyperv/hv_apic.c:257
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:hv_send_ipi_allbutself
  - arch/x86/hyperv/hv_apic.c:hv_send_ipi_allbutself
```
**Symbols:**

```
ffffffff81049080-ffffffff810490c3: hv_send_ipi_mask_allbutself (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void hv_send_ipi_mask_allbutself(const struct cpumask *mask, int vector);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_apic.c (ffffffff81050595)
Location: arch/x86/hyperv/hv_apic.c:266
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:hv_send_ipi_allbutself
  - arch/x86/hyperv/hv_apic.c:hv_send_ipi_allbutself
```
**Symbols:**

```
ffffffff810502e0-ffffffff81050323: hv_send_ipi_mask_allbutself (STB_LOCAL)
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
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
void hv_send_ipi_mask_allbutself(const struct cpumask *mask, int vector);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/hyperv/hv_apic.c (ffffffff8102f3a0)
Location: arch/x86/hyperv/hv_apic.c:215
Inline: True
Direct callers:
  - arch/x86/hyperv/hv_apic.c:hv_send_ipi_allbutself
```
**Symbols:**

```
ffffffff8102f3a0-ffffffff8102f3b7: hv_send_ipi_mask_allbutself.part.0 (STB_LOCAL)
ffffffff8102f850-ffffffff8102f8fc: hv_send_ipi_mask_allbutself (STB_LOCAL)
ffffffff8102f9a4-ffffffff8102f9b0: hv_send_ipi_mask_allbutself.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
void hv_send_ipi_mask_allbutself(const struct cpumask *mask, int vector);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/hyperv/hv_apic.c (ffffffff8101ec20)
Location: arch/x86/hyperv/hv_apic.c:215
Inline: True
Direct callers:
  - arch/x86/hyperv/hv_apic.c:hv_send_ipi_allbutself
```
**Symbols:**

```
ffffffff8101ec20-ffffffff8101ec37: hv_send_ipi_mask_allbutself.part.0 (STB_LOCAL)
ffffffff8101f060-ffffffff8101f10c: hv_send_ipi_mask_allbutself (STB_LOCAL)
ffffffff8101f374-ffffffff8101f380: hv_send_ipi_mask_allbutself.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void hv_send_ipi_mask_allbutself(const struct cpumask *mask, int vector);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/hyperv/hv_apic.c (ffffffff8102f200)
Location: arch/x86/hyperv/hv_apic.c:215
Inline: True
Direct callers:
  - arch/x86/hyperv/hv_apic.c:hv_send_ipi_allbutself
```
**Symbols:**

```
ffffffff8102f200-ffffffff8102f217: hv_send_ipi_mask_allbutself.part.0 (STB_LOCAL)
ffffffff8102f6b0-ffffffff8102f75c: hv_send_ipi_mask_allbutself (STB_LOCAL)
ffffffff8102f804-ffffffff8102f810: hv_send_ipi_mask_allbutself.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void hv_send_ipi_mask_allbutself(const struct cpumask *mask, int vector);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/hyperv/hv_apic.c (ffffffff81030040)
Location: arch/x86/hyperv/hv_apic.c:215
Inline: True
Direct callers:
  - arch/x86/hyperv/hv_apic.c:hv_send_ipi_allbutself
```
**Symbols:**

```
ffffffff81030040-ffffffff81030057: hv_send_ipi_mask_allbutself.part.0 (STB_LOCAL)
ffffffff81030500-ffffffff810305ac: hv_send_ipi_mask_allbutself (STB_LOCAL)
ffffffff81030654-ffffffff81030660: hv_send_ipi_mask_allbutself.cold (STB_LOCAL)
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
