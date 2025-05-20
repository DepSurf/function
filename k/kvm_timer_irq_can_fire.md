# Function: <code>kvm_timer_irq_can_fire</code>

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
<summary>In <code>arm64</code>: ✅</summary>

```c
bool kvm_timer_irq_can_fire(struct arch_timer_context *timer_ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In virt/kvm/arm/arch_timer.c (ffff8000100ec120)
Location: virt/kvm/arm/arch_timer.c:143
Inline: False
Direct callers:
  - virt/kvm/arm/arch_timer.c:kvm_timer_vcpu_put
  - virt/kvm/arm/arch_timer.c:kvm_timer_vcpu_put
  - virt/kvm/arm/arch_timer.c:kvm_timer_vcpu_put
  - virt/kvm/arm/arch_timer.c:kvm_timer_vcpu_load
  - virt/kvm/arm/arch_timer.c:kvm_timer_should_fire
  - virt/kvm/arm/arch_timer.c:kvm_timer_earliest_exp
  - virt/kvm/arm/arch_timer.c:kvm_timer_earliest_exp
```
**Symbols:**

```
ffff8000100ec120-ffff8000100ec16c: kvm_timer_irq_can_fire (STB_LOCAL)
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
<b>Arch</b>
<ul>
</ul>
