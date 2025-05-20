# Function: <code>irq_data_get_effective_affinity_mask</code>

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
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff81056ea5)
Location: include/linux/irq.h:782
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:flat_cpu_mask_to_apicid
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8105c809)
Location: include/linux/irq.h:782
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_cpu_mask_to_apicid
```
```
In kernel/irq/cpuhotplug.c (0)
Location: include/linux/irq.h:782
Inline: True
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
In kernel/irq/manage.c (ffffffff810ef859)
Location: include/linux/irq.h:811
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_do_set_affinity
```
```
In kernel/irq/proc.c (ffffffff810f64f5)
Location: include/linux/irq.h:811
Inline: True
Inline callers:
  - kernel/irq/proc.c:irq_effective_aff_list_proc_show
  - kernel/irq/proc.c:irq_effective_aff_proc_show
```
```
In kernel/irq/cpuhotplug.c (ffffffff810f7233)
Location: include/linux/irq.h:811
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
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
In kernel/irq/manage.c (ffffffff810f77e3)
Location: include/linux/irq.h:813
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_thread_check_affinity
  - kernel/irq/manage.c:irq_do_set_affinity
```
```
In kernel/irq/proc.c (ffffffff810fe815)
Location: include/linux/irq.h:813
Inline: True
Inline callers:
  - kernel/irq/proc.c:irq_effective_aff_list_proc_show
  - kernel/irq/proc.c:irq_effective_aff_proc_show
```
```
In kernel/irq/cpuhotplug.c (ffffffff810ff4df)
Location: include/linux/irq.h:813
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
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
In kernel/irq/manage.c (ffffffff81103072)
Location: include/linux/irq.h:814
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_thread_check_affinity
  - kernel/irq/manage.c:irq_do_set_affinity
```
```
In kernel/irq/proc.c (ffffffff81109fe5)
Location: include/linux/irq.h:814
Inline: True
Inline callers:
  - kernel/irq/proc.c:irq_effective_aff_list_proc_show
  - kernel/irq/proc.c:irq_effective_aff_proc_show
```
```
In kernel/irq/cpuhotplug.c (ffffffff8110acbf)
Location: include/linux/irq.h:814
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
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
In kernel/irq/manage.c (ffffffff8110b706)
Location: include/linux/irq.h:827
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_thread_check_affinity
  - kernel/irq/manage.c:irq_do_set_affinity
```
```
In kernel/irq/proc.c (ffffffff811136d6)
Location: include/linux/irq.h:827
Inline: True
Inline callers:
  - kernel/irq/proc.c:irq_effective_aff_list_proc_show
  - kernel/irq/proc.c:irq_effective_aff_proc_show
```
```
In kernel/irq/cpuhotplug.c (ffffffff8111437f)
Location: include/linux/irq.h:827
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
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
In arch/x86/kernel/apic/vector.c (ffffffff8106906e)
Location: include/linux/irq.h:845
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
```
```
In arch/x86/kernel/apic/msi.c (ffffffff8106c4c0)
Location: include/linux/irq.h:845
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:msi_set_affinity
```
```
In kernel/irq/manage.c (ffffffff81117a06)
Location: include/linux/irq.h:845
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_thread_check_affinity
  - kernel/irq/manage.c:irq_do_set_affinity
```
```
In kernel/irq/proc.c (ffffffff8111f846)
Location: include/linux/irq.h:845
Inline: True
Inline callers:
  - kernel/irq/proc.c:irq_effective_aff_list_proc_show
  - kernel/irq/proc.c:irq_effective_aff_proc_show
```
```
In kernel/irq/cpuhotplug.c (ffffffff811204df)
Location: include/linux/irq.h:845
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
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
In arch/x86/kernel/apic/vector.c (ffffffff8106f7c2)
Location: include/linux/irq.h:875
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:activate_reserved
```
```
In arch/x86/kernel/apic/msi.c (ffffffff81073750)
Location: include/linux/irq.h:875
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:msi_set_affinity
```
```
In kernel/irq/manage.c (ffffffff811234bf)
Location: include/linux/irq.h:875
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_thread_check_affinity
  - kernel/irq/manage.c:irq_set_affinity_locked
  - kernel/irq/manage.c:irq_do_set_affinity
```
```
In kernel/irq/proc.c (ffffffff8112bd86)
Location: include/linux/irq.h:875
Inline: True
Inline callers:
  - kernel/irq/proc.c:irq_effective_aff_list_proc_show
  - kernel/irq/proc.c:irq_effective_aff_proc_show
```
```
In kernel/irq/cpuhotplug.c (ffffffff8112cbfe)
Location: include/linux/irq.h:875
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:hk_should_isolate
  - kernel/irq/cpuhotplug.c:migrate_one_irq
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff81070ce2)
Location: include/linux/irq.h:888
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:activate_reserved
```
```
In arch/x86/kernel/apic/msi.c (ffffffff81074540)
Location: include/linux/irq.h:888
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:msi_set_affinity
```
```
In kernel/irq/manage.c (ffffffff8111f30f)
Location: include/linux/irq.h:888
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_thread_check_affinity
  - kernel/irq/manage.c:irq_set_affinity_locked
  - kernel/irq/manage.c:irq_do_set_affinity
```
```
In kernel/irq/proc.c (ffffffff811277a6)
Location: include/linux/irq.h:888
Inline: True
Inline callers:
  - kernel/irq/proc.c:irq_effective_aff_list_proc_show
  - kernel/irq/proc.c:irq_effective_aff_proc_show
```
```
In kernel/irq/cpuhotplug.c (ffffffff8112862e)
Location: include/linux/irq.h:888
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:hk_should_isolate
  - kernel/irq/cpuhotplug.c:migrate_one_irq
```
```
In drivers/xen/events/events_base.c (ffffffff817340c6)
Location: include/linux/irq.h:888
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/irqdomain.c (ffffffff8103372d)
Location: include/linux/irq.h:890
Inline: True
Inline callers:
  - arch/x86/hyperv/irqdomain.c:hv_irq_compose_msi_msg
```
```
In arch/x86/kernel/apic/vector.c (ffffffff8107157b)
Location: include/linux/irq.h:890
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
```
```
In arch/x86/kernel/apic/msi.c (ffffffff81074ff0)
Location: include/linux/irq.h:890
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:msi_set_affinity
```
```
In kernel/irq/manage.c (ffffffff8111f42f)
Location: include/linux/irq.h:890
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_thread_check_affinity
  - kernel/irq/manage.c:irq_set_affinity_locked
  - kernel/irq/manage.c:irq_do_set_affinity
```
```
In kernel/irq/proc.c (ffffffff81127b36)
Location: include/linux/irq.h:890
Inline: True
Inline callers:
  - kernel/irq/proc.c:irq_effective_aff_list_proc_show
  - kernel/irq/proc.c:irq_effective_aff_proc_show
```
```
In kernel/irq/cpuhotplug.c (ffffffff81128a3f)
Location: include/linux/irq.h:890
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
  - kernel/irq/cpuhotplug.c:migrate_one_irq
```
```
In drivers/xen/events/events_base.c (ffffffff81717bc6)
Location: include/linux/irq.h:890
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
```
```
In drivers/iommu/hyperv-iommu.c (ffffffff817a4784)
Location: include/linux/irq.h:890
Inline: True
Inline callers:
  - drivers/iommu/hyperv-iommu.c:hyperv_root_ir_compose_msi_msg
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/irqdomain.c (ffffffff810388dd)
Location: include/linux/irq.h:892
Inline: True
Inline callers:
  - arch/x86/hyperv/irqdomain.c:hv_irq_compose_msi_msg
```
```
In arch/x86/kernel/apic/vector.c (ffffffff8107d36b)
Location: include/linux/irq.h:892
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
```
```
In arch/x86/kernel/apic/msi.c (ffffffff810824a0)
Location: include/linux/irq.h:892
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:msi_set_affinity
```
```
In kernel/irq/manage.c (ffffffff8113f8bf)
Location: include/linux/irq.h:892
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_thread_check_affinity
  - kernel/irq/manage.c:irq_set_affinity_locked
  - kernel/irq/manage.c:irq_do_set_affinity
```
```
In kernel/irq/proc.c (ffffffff811480a6)
Location: include/linux/irq.h:892
Inline: True
Inline callers:
  - kernel/irq/proc.c:irq_effective_aff_list_proc_show
  - kernel/irq/proc.c:irq_effective_aff_proc_show
```
```
In kernel/irq/cpuhotplug.c (ffffffff8114901f)
Location: include/linux/irq.h:892
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
  - kernel/irq/cpuhotplug.c:migrate_one_irq
```
```
In drivers/xen/events/events_base.c (ffffffff81795401)
Location: include/linux/irq.h:892
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
```
```
In drivers/iommu/hyperv-iommu.c (ffffffff8182df74)
Location: include/linux/irq.h:892
Inline: True
Inline callers:
  - drivers/iommu/hyperv-iommu.c:hyperv_root_ir_compose_msi_msg
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/irqdomain.c (ffffffff8103eb9f)
Location: include/linux/irq.h:896
Inline: True
Inline callers:
  - arch/x86/hyperv/irqdomain.c:hv_irq_compose_msi_msg
```
```
In arch/x86/kernel/apic/vector.c (ffffffff8108ca36)
Location: include/linux/irq.h:896
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
```
```
In arch/x86/kernel/apic/msi.c (ffffffff81092088)
Location: include/linux/irq.h:896
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:msi_set_affinity
```
```
In kernel/irq/manage.c (ffffffff8116322f)
Location: include/linux/irq.h:896
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_thread_check_affinity
  - kernel/irq/manage.c:irq_set_affinity_locked
  - kernel/irq/manage.c:irq_do_set_affinity
```
```
In kernel/irq/proc.c (ffffffff8116c9f5)
Location: include/linux/irq.h:896
Inline: True
Inline callers:
  - kernel/irq/proc.c:irq_effective_aff_list_proc_show
  - kernel/irq/proc.c:irq_effective_aff_proc_show
```
```
In kernel/irq/cpuhotplug.c (ffffffff8116dba2)
Location: include/linux/irq.h:896
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
  - kernel/irq/cpuhotplug.c:irq_needs_fixup
```
```
In drivers/xen/events/events_base.c (ffffffff818ce137)
Location: include/linux/irq.h:896
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
```
```
In drivers/iommu/hyperv-iommu.c (ffffffff8196ef17)
Location: include/linux/irq.h:896
Inline: True
Inline callers:
  - drivers/iommu/hyperv-iommu.c:hyperv_root_ir_compose_msi_msg
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/irqdomain.c (ffffffff81047b8f)
Location: include/linux/irq.h:911
Inline: True
Inline callers:
  - arch/x86/hyperv/irqdomain.c:hv_irq_compose_msi_msg
```
```
In arch/x86/kernel/apic/vector.c (ffffffff810a1036)
Location: include/linux/irq.h:911
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
```
```
In arch/x86/kernel/apic/msi.c (ffffffff810a7078)
Location: include/linux/irq.h:911
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:msi_set_affinity
```
```
In kernel/irq/manage.c (ffffffff81196e54)
Location: include/linux/irq.h:911
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_thread_check_affinity
  - kernel/irq/manage.c:irq_do_set_affinity
```
```
In kernel/irq/proc.c (ffffffff811a1aa5)
Location: include/linux/irq.h:911
Inline: True
Inline callers:
  - kernel/irq/proc.c:irq_effective_aff_list_proc_show
  - kernel/irq/proc.c:irq_effective_aff_proc_show
```
```
In kernel/irq/cpuhotplug.c (ffffffff811a2dd2)
Location: include/linux/irq.h:911
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
  - kernel/irq/cpuhotplug.c:irq_needs_fixup
```
```
In drivers/iommu/hyperv-iommu.c (ffffffff81ad9897)
Location: include/linux/irq.h:911
Inline: True
Inline callers:
  - drivers/iommu/hyperv-iommu.c:hyperv_root_ir_compose_msi_msg
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/irqdomain.c (ffffffff81047e7f)
Location: include/linux/irq.h:924
Inline: True
Inline callers:
  - arch/x86/hyperv/irqdomain.c:hv_irq_compose_msi_msg
```
```
In arch/x86/kernel/apic/vector.c (ffffffff810a4026)
Location: include/linux/irq.h:924
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
```
```
In arch/x86/kernel/apic/msi.c (ffffffff810aa2d8)
Location: include/linux/irq.h:924
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:msi_set_affinity
```
```
In kernel/irq/manage.c (ffffffff811a8912)
Location: include/linux/irq.h:924
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_thread_check_affinity
  - kernel/irq/manage.c:irq_do_set_affinity
```
```
In kernel/irq/proc.c (ffffffff811b3a45)
Location: include/linux/irq.h:924
Inline: True
Inline callers:
  - kernel/irq/proc.c:irq_effective_aff_list_proc_show
  - kernel/irq/proc.c:irq_effective_aff_proc_show
```
```
In kernel/irq/cpuhotplug.c (ffffffff811b4cd2)
Location: include/linux/irq.h:924
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
  - kernel/irq/cpuhotplug.c:irq_needs_fixup
```
```
In drivers/iommu/hyperv-iommu.c (ffffffff81b27a17)
Location: include/linux/irq.h:924
Inline: True
Inline callers:
  - drivers/iommu/hyperv-iommu.c:hyperv_root_ir_compose_msi_msg
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/irqdomain.c (ffffffff8104e5af)
Location: include/linux/irq.h:906
Inline: True
Inline callers:
  - arch/x86/hyperv/irqdomain.c:hv_irq_compose_msi_msg
```
```
In arch/x86/kernel/apic/vector.c (ffffffff810ab056)
Location: include/linux/irq.h:906
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
```
```
In arch/x86/kernel/apic/msi.c (ffffffff810b1368)
Location: include/linux/irq.h:906
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:msi_set_affinity
```
```
In kernel/irq/manage.c (ffffffff811b8472)
Location: include/linux/irq.h:906
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_thread_check_affinity
  - kernel/irq/manage.c:irq_do_set_affinity
```
```
In kernel/irq/proc.c (ffffffff811c38c5)
Location: include/linux/irq.h:906
Inline: True
Inline callers:
  - kernel/irq/proc.c:irq_effective_aff_list_proc_show
  - kernel/irq/proc.c:irq_effective_aff_proc_show
```
```
In kernel/irq/cpuhotplug.c (ffffffff811c4b52)
Location: include/linux/irq.h:906
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
  - kernel/irq/cpuhotplug.c:irq_needs_fixup
```
```
In drivers/iommu/hyperv-iommu.c (ffffffff81b7e8d7)
Location: include/linux/irq.h:906
Inline: True
Inline callers:
  - drivers/iommu/hyperv-iommu.c:hyperv_root_ir_compose_msi_msg
```
</details>
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
In kernel/irq/manage.c (0)
Location: include/linux/irq.h:845
Inline: True
```
```
In kernel/irq/proc.c (0)
Location: include/linux/irq.h:845
Inline: True
```
```
In kernel/irq/cpuhotplug.c (ffff8000101862a8)
Location: include/linux/irq.h:845
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
```
```
In drivers/irqchip/irq-ls-scfg-msi.c (0)
Location: include/linux/irq.h:845
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (c03cbc8c)
Location: include/linux/irq.h:845
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_do_set_affinity
```
```
In kernel/irq/proc.c (c03d4648)
Location: include/linux/irq.h:845
Inline: True
Inline callers:
  - kernel/irq/proc.c:irq_effective_aff_list_proc_show
  - kernel/irq/proc.c:irq_effective_aff_proc_show
```
```
In kernel/irq/cpuhotplug.c (c03d50e4)
Location: include/linux/irq.h:845
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (0)
Location: include/linux/irq.h:860
Inline: True
```
```
In kernel/irq/cpuhotplug.c (0)
Location: include/linux/irq.h:860
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (0)
Location: include/linux/irq.h:860
Inline: True
```
</details>
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
In arch/x86/kernel/apic/vector.c (ffffffff81068b5e)
Location: include/linux/irq.h:845
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
```
```
In arch/x86/kernel/apic/msi.c (ffffffff8106bfb0)
Location: include/linux/irq.h:845
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:msi_set_affinity
```
```
In kernel/irq/manage.c (ffffffff8110ffe6)
Location: include/linux/irq.h:845
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_thread_check_affinity
  - kernel/irq/manage.c:irq_do_set_affinity
```
```
In kernel/irq/proc.c (ffffffff81117e26)
Location: include/linux/irq.h:845
Inline: True
Inline callers:
  - kernel/irq/proc.c:irq_effective_aff_list_proc_show
  - kernel/irq/proc.c:irq_effective_aff_proc_show
```
```
In kernel/irq/cpuhotplug.c (ffffffff81118abf)
Location: include/linux/irq.h:845
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
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
In arch/x86/kernel/apic/vector.c (ffffffff81058ece)
Location: include/linux/irq.h:845
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
```
```
In arch/x86/kernel/apic/msi.c (ffffffff8105c2d0)
Location: include/linux/irq.h:845
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:msi_set_affinity
```
```
In kernel/irq/manage.c (ffffffff81100d16)
Location: include/linux/irq.h:845
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_thread_check_affinity
  - kernel/irq/manage.c:irq_do_set_affinity
```
```
In kernel/irq/proc.c (ffffffff81108e96)
Location: include/linux/irq.h:845
Inline: True
Inline callers:
  - kernel/irq/proc.c:irq_effective_aff_list_proc_show
  - kernel/irq/proc.c:irq_effective_aff_proc_show
```
```
In kernel/irq/cpuhotplug.c (ffffffff81109b2f)
Location: include/linux/irq.h:845
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
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
In arch/x86/kernel/apic/vector.c (ffffffff8106900e)
Location: include/linux/irq.h:845
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
```
```
In arch/x86/kernel/apic/msi.c (ffffffff8106c460)
Location: include/linux/irq.h:845
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:msi_set_affinity
```
```
In kernel/irq/manage.c (ffffffff8110ded6)
Location: include/linux/irq.h:845
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_thread_check_affinity
  - kernel/irq/manage.c:irq_do_set_affinity
```
```
In kernel/irq/proc.c (ffffffff81115d16)
Location: include/linux/irq.h:845
Inline: True
Inline callers:
  - kernel/irq/proc.c:irq_effective_aff_list_proc_show
  - kernel/irq/proc.c:irq_effective_aff_proc_show
```
```
In kernel/irq/cpuhotplug.c (ffffffff811169af)
Location: include/linux/irq.h:845
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
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
In arch/x86/kernel/apic/vector.c (ffffffff8106a712)
Location: include/linux/irq.h:845
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
```
```
In arch/x86/kernel/apic/msi.c (ffffffff8106db60)
Location: include/linux/irq.h:845
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:msi_set_affinity
```
```
In kernel/irq/manage.c (ffffffff8111941f)
Location: include/linux/irq.h:845
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_thread_check_affinity
  - kernel/irq/manage.c:irq_do_set_affinity
```
```
In kernel/irq/proc.c (ffffffff81121346)
Location: include/linux/irq.h:845
Inline: True
Inline callers:
  - kernel/irq/proc.c:irq_effective_aff_list_proc_show
  - kernel/irq/proc.c:irq_effective_aff_proc_show
```
```
In kernel/irq/cpuhotplug.c (ffffffff81121fed)
Location: include/linux/irq.h:845
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
```
</details>
</li>
</ul>

## Differences
