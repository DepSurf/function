# Function: <code>send_cleanup_vector</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void send_cleanup_vector(struct irq_cfg *cfg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff81055950)
Location: arch/x86/kernel/apic/vector.c:551
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_ir_set_affinity
  - drivers/iommu/intel_irq_remapping.c:intel_ir_set_affinity
```
**Symbols:**

```
ffffffff81055950-ffffffff81055967: send_cleanup_vector (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void send_cleanup_vector(struct irq_cfg *cfg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff81055bd0)
Location: arch/x86/kernel/apic/vector.c:553
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_ir_set_affinity
  - drivers/iommu/intel_irq_remapping.c:intel_ir_set_affinity
```
**Symbols:**

```
ffffffff81055bd0-ffffffff81055be7: send_cleanup_vector (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void send_cleanup_vector(struct irq_cfg *cfg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff81058970)
Location: arch/x86/kernel/apic/vector.c:553
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_ir_set_affinity
  - drivers/iommu/intel_irq_remapping.c:intel_ir_set_affinity
```
**Symbols:**

```
ffffffff81058970-ffffffff81058987: send_cleanup_vector (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void send_cleanup_vector(struct irq_cfg *cfg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff81058150)
Location: arch/x86/kernel/apic/vector.c:574
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_ir_set_affinity
  - drivers/iommu/intel_irq_remapping.c:intel_ir_set_affinity
```
**Symbols:**

```
ffffffff81058150-ffffffff81058168: send_cleanup_vector (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void send_cleanup_vector(struct irq_cfg *cfg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff8105c650)
Location: arch/x86/kernel/apic/vector.c:891
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_ir_set_affinity
  - drivers/iommu/intel_irq_remapping.c:intel_ir_set_affinity
```
**Symbols:**

```
ffffffff8105c650-ffffffff8105c668: send_cleanup_vector (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void send_cleanup_vector(struct irq_cfg *cfg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff8105f6b0)
Location: arch/x86/kernel/apic/vector.c:907
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_ir_set_affinity
  - drivers/iommu/intel_irq_remapping.c:intel_ir_set_affinity
```
**Symbols:**

```
ffffffff8105f6b0-ffffffff8105f6c7: send_cleanup_vector (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void send_cleanup_vector(struct irq_cfg *cfg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff81065320)
Location: arch/x86/kernel/apic/vector.c:898
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_ir_set_affinity
  - drivers/iommu/intel_irq_remapping.c:intel_ir_set_affinity
```
**Symbols:**

```
ffffffff81065320-ffffffff81065337: send_cleanup_vector (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void send_cleanup_vector(struct irq_cfg *cfg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff81068a00)
Location: arch/x86/kernel/apic/vector.c:895
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_ir_set_affinity
  - drivers/iommu/intel_irq_remapping.c:intel_ir_set_affinity
  - drivers/iommu/hyperv-iommu.c:hyperv_ir_set_affinity
```
**Symbols:**

```
ffffffff81068a00-ffffffff81068a17: send_cleanup_vector (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void send_cleanup_vector(struct irq_cfg *cfg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff81069370)
Location: arch/x86/kernel/apic/vector.c:906
Inline: False
Direct callers:
  - arch/x86/platform/uv/uv_irq.c:uv_set_irq_affinity
  - drivers/iommu/amd_iommu.c:amd_ir_set_affinity
  - drivers/iommu/intel_irq_remapping.c:intel_ir_set_affinity
  - drivers/iommu/hyperv-iommu.c:hyperv_ir_set_affinity
```
**Symbols:**

```
ffffffff81069370-ffffffff81069387: send_cleanup_vector (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void send_cleanup_vector(struct irq_cfg *cfg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff81070330)
Location: arch/x86/kernel/apic/vector.c:905
Inline: False
Direct callers:
  - arch/x86/platform/uv/uv_irq.c:uv_set_irq_affinity
  - drivers/iommu/amd/iommu.c:amd_ir_set_affinity
  - drivers/iommu/intel/irq_remapping.c:intel_ir_set_affinity
  - drivers/iommu/hyperv-iommu.c:hyperv_ir_set_affinity
```
**Symbols:**

```
ffffffff81070330-ffffffff81070347: send_cleanup_vector (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void send_cleanup_vector(struct irq_cfg *cfg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff81071890)
Location: arch/x86/kernel/apic/vector.c:957
Inline: False
Direct callers:
  - arch/x86/platform/uv/uv_irq.c:uv_set_irq_affinity
  - drivers/iommu/amd/iommu.c:amd_ir_set_affinity
  - drivers/iommu/intel/irq_remapping.c:intel_ir_set_affinity
  - drivers/iommu/hyperv-iommu.c:hyperv_ir_set_affinity
```
**Symbols:**

```
ffffffff81071890-ffffffff810718a7: send_cleanup_vector (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void send_cleanup_vector(struct irq_cfg *cfg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff81072390)
Location: arch/x86/kernel/apic/vector.c:990
Inline: False
Direct callers:
  - arch/x86/platform/uv/uv_irq.c:uv_set_irq_affinity
  - drivers/iommu/amd/iommu.c:amd_ir_set_affinity
  - drivers/iommu/intel/irq_remapping.c:intel_ir_set_affinity
  - drivers/iommu/hyperv-iommu.c:hyperv_root_ir_set_affinity
  - drivers/iommu/hyperv-iommu.c:hyperv_ir_set_affinity
```
**Symbols:**

```
ffffffff81072390-ffffffff810723a7: send_cleanup_vector (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void send_cleanup_vector(struct irq_cfg *cfg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff8107e270)
Location: arch/x86/kernel/apic/vector.c:990
Inline: False
Direct callers:
  - arch/x86/platform/uv/uv_irq.c:uv_set_irq_affinity
  - drivers/iommu/amd/iommu.c:amd_ir_set_affinity
  - drivers/iommu/intel/irq_remapping.c:intel_ir_set_affinity
  - drivers/iommu/hyperv-iommu.c:hyperv_root_ir_set_affinity
  - drivers/iommu/hyperv-iommu.c:hyperv_ir_set_affinity
```
**Symbols:**

```
ffffffff8107e270-ffffffff8107e287: send_cleanup_vector (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void send_cleanup_vector(struct irq_cfg *cfg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff8108d8f0)
Location: arch/x86/kernel/apic/vector.c:990
Inline: False
Direct callers:
  - arch/x86/platform/uv/uv_irq.c:uv_set_irq_affinity
  - drivers/iommu/amd/iommu.c:amd_ir_set_affinity
  - drivers/iommu/intel/irq_remapping.c:intel_ir_set_affinity
  - drivers/iommu/hyperv-iommu.c:hyperv_root_ir_set_affinity
  - drivers/iommu/hyperv-iommu.c:hyperv_ir_set_affinity
```
**Symbols:**

```
ffffffff8108d8f0-ffffffff8108d913: send_cleanup_vector (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void send_cleanup_vector(struct irq_cfg *cfg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff810a2010)
Location: arch/x86/kernel/apic/vector.c:986
Inline: False
Direct callers:
  - arch/x86/platform/uv/uv_irq.c:uv_set_irq_affinity
  - drivers/iommu/amd/iommu.c:amd_ir_set_affinity
  - drivers/iommu/intel/irq_remapping.c:intel_ir_set_affinity
  - drivers/iommu/hyperv-iommu.c:hyperv_root_ir_set_affinity
  - drivers/iommu/hyperv-iommu.c:hyperv_ir_set_affinity
```
**Symbols:**

```
ffffffff810a2010-ffffffff810a2033: send_cleanup_vector (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void send_cleanup_vector(struct irq_cfg *cfg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff810a4ff0)
Location: arch/x86/kernel/apic/vector.c:986
Inline: False
Direct callers:
  - arch/x86/platform/uv/uv_irq.c:uv_set_irq_affinity
  - drivers/iommu/amd/iommu.c:amd_ir_set_affinity
  - drivers/iommu/intel/irq_remapping.c:intel_ir_set_affinity
  - drivers/iommu/hyperv-iommu.c:hyperv_root_ir_set_affinity
  - drivers/iommu/hyperv-iommu.c:hyperv_ir_set_affinity
```
**Symbols:**

```
ffffffff810a4ff0-ffffffff810a5013: send_cleanup_vector (STB_GLOBAL)
```
</details>
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
<summary>In <code>aws</code>: ✅</summary>

```c
void send_cleanup_vector(struct irq_cfg *cfg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff81068e60)
Location: arch/x86/kernel/apic/vector.c:906
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_ir_set_affinity
  - drivers/iommu/intel_irq_remapping.c:intel_ir_set_affinity
  - drivers/iommu/hyperv-iommu.c:hyperv_ir_set_affinity
```
**Symbols:**

```
ffffffff81068e60-ffffffff81068e77: send_cleanup_vector (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void send_cleanup_vector(struct irq_cfg *cfg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff810591d0)
Location: arch/x86/kernel/apic/vector.c:906
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_ir_set_affinity
  - drivers/iommu/intel_irq_remapping.c:intel_ir_set_affinity
  - drivers/iommu/hyperv-iommu.c:hyperv_ir_set_affinity
```
**Symbols:**

```
ffffffff810591d0-ffffffff810591e7: send_cleanup_vector (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void send_cleanup_vector(struct irq_cfg *cfg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff81069310)
Location: arch/x86/kernel/apic/vector.c:906
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_ir_set_affinity
  - drivers/iommu/intel_irq_remapping.c:intel_ir_set_affinity
  - drivers/iommu/hyperv-iommu.c:hyperv_ir_set_affinity
```
**Symbols:**

```
ffffffff81069310-ffffffff81069327: send_cleanup_vector (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void send_cleanup_vector(struct irq_cfg *cfg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff8106aa10)
Location: arch/x86/kernel/apic/vector.c:906
Inline: False
Direct callers:
  - arch/x86/platform/uv/uv_irq.c:uv_set_irq_affinity
  - drivers/iommu/amd_iommu.c:amd_ir_set_affinity
  - drivers/iommu/intel_irq_remapping.c:intel_ir_set_affinity
  - drivers/iommu/hyperv-iommu.c:hyperv_ir_set_affinity
```
**Symbols:**

```
ffffffff8106aa10-ffffffff8106aa27: send_cleanup_vector (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
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
