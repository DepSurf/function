# Function: <code>kvm_pmc_to_vcpu</code>

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
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In virt/kvm/arm/pmu.c (ffff8000100ef1d4)
Location: virt/kvm/arm/pmu.c:32
Inline: True
Inline callers:
  - virt/kvm/arm/pmu.c:kvm_pmu_set_counter_event_type
  - virt/kvm/arm/pmu.c:kvm_pmu_create_perf_event
  - virt/kvm/arm/pmu.c:kvm_pmu_software_increment
  - virt/kvm/arm/pmu.c:kvm_pmu_perf_overflow
  - virt/kvm/arm/pmu.c:kvm_pmu_stop_counter
  - virt/kvm/arm/pmu.c:kvm_pmu_stop_counter
  - virt/kvm/arm/pmu.c:kvm_pmu_release_perf_event
  - virt/kvm/arm/pmu.c:kvm_pmu_get_counter_value
  - virt/kvm/arm/pmu.c:kvm_pmu_get_pair_counter_value
  - virt/kvm/arm/pmu.c:kvm_pmu_get_pair_counter_value
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
