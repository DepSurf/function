# Function: <code>kvm_vcpu_get_hsr</code>

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
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In virt/kvm/arm/arm.c (0)
Location: arch/arm64/include/asm/kvm_emulate.h:253
Inline: True
```
```
In virt/kvm/arm/mmu.c (0)
Location: arch/arm64/include/asm/kvm_emulate.h:253
Inline: True
```
```
In virt/kvm/arm/mmio.c (0)
Location: arch/arm64/include/asm/kvm_emulate.h:253
Inline: True
```
```
In arch/arm64/kvm/inject_fault.c (0)
Location: arch/arm64/include/asm/kvm_emulate.h:253
Inline: True
```
```
In arch/arm64/kvm/handle_exit.c (0)
Location: arch/arm64/include/asm/kvm_emulate.h:253
Inline: True
```
```
In arch/arm64/kvm/sys_regs.c (0)
Location: arch/arm64/include/asm/kvm_emulate.h:253
Inline: True
```
```
In virt/kvm/arm/hyp/vgic-v3-sr.c (0)
Location: arch/arm64/include/asm/kvm_emulate.h:253
Inline: True
```
```
In virt/kvm/arm/hyp/aarch32.c (0)
Location: arch/arm64/include/asm/kvm_emulate.h:253
Inline: True
```
```
In arch/arm64/kvm/hyp/vgic-v2-cpuif-proxy.c (0)
Location: arch/arm64/include/asm/kvm_emulate.h:253
Inline: True
```
```
In arch/arm64/kvm/hyp/switch.c (0)
Location: arch/arm64/include/asm/kvm_emulate.h:253
Inline: True
```
</details>
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
