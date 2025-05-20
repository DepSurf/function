# Function: <code>hv_map_ioapic_interrupt</code>

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
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int hv_map_ioapic_interrupt(int ioapic_id, bool level, int cpu, int vector, struct hv_interrupt_entry *entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/irqdomain.c (ffffffff810338b0)
Location: arch/x86/hyperv/irqdomain.c:374
Inline: False
Direct callers:
  - drivers/iommu/hyperv-iommu.c:hyperv_root_ir_compose_msi_msg
```
**Symbols:**

```
ffffffff810338b0-ffffffff810338d4: hv_map_ioapic_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int hv_map_ioapic_interrupt(int ioapic_id, bool level, int cpu, int vector, struct hv_interrupt_entry *entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/irqdomain.c (ffffffff81038a50)
Location: arch/x86/hyperv/irqdomain.c:374
Inline: False
Direct callers:
  - drivers/iommu/hyperv-iommu.c:hyperv_root_ir_compose_msi_msg
```
**Symbols:**

```
ffffffff81038a50-ffffffff81038a74: hv_map_ioapic_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int hv_map_ioapic_interrupt(int ioapic_id, bool level, int cpu, int vector, struct hv_interrupt_entry *entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/irqdomain.c (ffffffff8103ed20)
Location: arch/x86/hyperv/irqdomain.c:353
Inline: False
Direct callers:
  - drivers/iommu/hyperv-iommu.c:hyperv_root_ir_compose_msi_msg
```
**Symbols:**

```
ffffffff8103ed20-ffffffff8103ed52: hv_map_ioapic_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int hv_map_ioapic_interrupt(int ioapic_id, bool level, int cpu, int vector, struct hv_interrupt_entry *entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/irqdomain.c (ffffffff81047d20)
Location: arch/x86/hyperv/irqdomain.c:353
Inline: False
Direct callers:
  - drivers/iommu/hyperv-iommu.c:hyperv_root_ir_compose_msi_msg
```
**Symbols:**

```
ffffffff81047d20-ffffffff81047d52: hv_map_ioapic_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int hv_map_ioapic_interrupt(int ioapic_id, bool level, int cpu, int vector, struct hv_interrupt_entry *entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/irqdomain.c (ffffffff81048010)
Location: arch/x86/hyperv/irqdomain.c:353
Inline: False
Direct callers:
  - drivers/iommu/hyperv-iommu.c:hyperv_root_ir_compose_msi_msg
```
**Symbols:**

```
ffffffff81048010-ffffffff81048042: hv_map_ioapic_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int hv_map_ioapic_interrupt(int ioapic_id, bool level, int cpu, int vector, struct hv_interrupt_entry *entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/irqdomain.c (ffffffff8104e500)
Location: arch/x86/hyperv/irqdomain.c:353
Inline: False
Direct callers:
  - drivers/iommu/hyperv-iommu.c:hyperv_root_ir_compose_msi_msg
```
**Symbols:**

```
ffffffff8104e500-ffffffff8104e532: hv_map_ioapic_interrupt (STB_GLOBAL)
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
