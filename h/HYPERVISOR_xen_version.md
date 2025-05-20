# Function: <code>HYPERVISOR_xen_version</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff81f60516)
Location: arch/x86/include/asm/xen/hypercall.h:374
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_banner
  - arch/x86/xen/enlighten.c:xen_banner
```
```
In arch/x86/xen/irq.c (ffffffff810233d1)
Location: arch/x86/include/asm/xen/hypercall.h:374
Inline: True
Inline callers:
  - arch/x86/xen/irq.c:xen_restore_fl
  - arch/x86/xen/irq.c:xen_irq_enable
```
```
In drivers/xen/features.c (ffffffff814c6356)
Location: arch/x86/include/asm/xen/hypercall.h:374
Inline: True
Inline callers:
  - drivers/xen/features.c:xen_setup_features
```
```
In drivers/xen/sys-hypervisor.c (ffffffff814d38b6)
Location: arch/x86/include/asm/xen/hypercall.h:374
Inline: True
Inline callers:
  - drivers/xen/sys-hypervisor.c:features_show
  - drivers/xen/sys-hypervisor.c:pagesize_show
  - drivers/xen/sys-hypervisor.c:minor_show
  - drivers/xen/sys-hypervisor.c:major_show
  - drivers/xen/sys-hypervisor.c:virtual_start_show
  - drivers/xen/sys-hypervisor.c:changeset_show
  - drivers/xen/sys-hypervisor.c:capabilities_show
  - drivers/xen/sys-hypervisor.c:compile_date_show
  - drivers/xen/sys-hypervisor.c:compiled_by_show
  - drivers/xen/sys-hypervisor.c:compiler_show
  - drivers/xen/sys-hypervisor.c:extra_show
  - drivers/xen/sys-hypervisor.c:uuid_show
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff81f88183)
Location: arch/x86/include/asm/xen/hypercall.h:375
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_banner
  - arch/x86/xen/enlighten.c:xen_banner
```
```
In arch/x86/xen/irq.c (ffffffff81022803)
Location: arch/x86/include/asm/xen/hypercall.h:375
Inline: True
Inline callers:
  - arch/x86/xen/irq.c:xen_irq_enable
  - arch/x86/xen/irq.c:xen_restore_fl
```
```
In drivers/xen/features.c (ffffffff81516af6)
Location: arch/x86/include/asm/xen/hypercall.h:375
Inline: True
Inline callers:
  - drivers/xen/features.c:xen_setup_features
```
```
In drivers/xen/sys-hypervisor.c (ffffffff815244e6)
Location: arch/x86/include/asm/xen/hypercall.h:375
Inline: True
Inline callers:
  - drivers/xen/sys-hypervisor.c:features_show
  - drivers/xen/sys-hypervisor.c:pagesize_show
  - drivers/xen/sys-hypervisor.c:virtual_start_show
  - drivers/xen/sys-hypervisor.c:changeset_show
  - drivers/xen/sys-hypervisor.c:capabilities_show
  - drivers/xen/sys-hypervisor.c:compile_date_show
  - drivers/xen/sys-hypervisor.c:compiled_by_show
  - drivers/xen/sys-hypervisor.c:compiler_show
  - drivers/xen/sys-hypervisor.c:uuid_show
  - drivers/xen/sys-hypervisor.c:extra_show
  - drivers/xen/sys-hypervisor.c:minor_show
  - drivers/xen/sys-hypervisor.c:major_show
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff81fc3571)
Location: arch/x86/include/asm/xen/hypercall.h:375
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_banner
  - arch/x86/xen/enlighten.c:xen_banner
```
```
In arch/x86/xen/irq.c (ffffffff81022f53)
Location: arch/x86/include/asm/xen/hypercall.h:375
Inline: True
Inline callers:
  - arch/x86/xen/irq.c:xen_irq_enable
  - arch/x86/xen/irq.c:xen_restore_fl
```
```
In drivers/xen/features.c (ffffffff81542f66)
Location: arch/x86/include/asm/xen/hypercall.h:375
Inline: True
Inline callers:
  - drivers/xen/features.c:xen_setup_features
```
```
In drivers/xen/sys-hypervisor.c (ffffffff815509a6)
Location: arch/x86/include/asm/xen/hypercall.h:375
Inline: True
Inline callers:
  - drivers/xen/sys-hypervisor.c:features_show
  - drivers/xen/sys-hypervisor.c:pagesize_show
  - drivers/xen/sys-hypervisor.c:virtual_start_show
  - drivers/xen/sys-hypervisor.c:changeset_show
  - drivers/xen/sys-hypervisor.c:capabilities_show
  - drivers/xen/sys-hypervisor.c:compile_date_show
  - drivers/xen/sys-hypervisor.c:compiled_by_show
  - drivers/xen/sys-hypervisor.c:compiler_show
  - drivers/xen/sys-hypervisor.c:uuid_show
  - drivers/xen/sys-hypervisor.c:extra_show
  - drivers/xen/sys-hypervisor.c:minor_show
  - drivers/xen/sys-hypervisor.c:major_show
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/irq.c (ffffffff8101ac33)
Location: arch/x86/include/asm/xen/hypercall.h:380
Inline: True
Inline callers:
  - arch/x86/xen/irq.c:xen_irq_enable
  - arch/x86/xen/irq.c:xen_restore_fl
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff820a5752)
Location: arch/x86/include/asm/xen/hypercall.h:380
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_banner
  - arch/x86/xen/enlighten_pv.c:xen_banner
```
```
In drivers/xen/features.c (ffffffff81556e16)
Location: arch/x86/include/asm/xen/hypercall.h:380
Inline: True
Inline callers:
  - drivers/xen/features.c:xen_setup_features
```
```
In drivers/xen/sys-hypervisor.c (ffffffff81565636)
Location: arch/x86/include/asm/xen/hypercall.h:380
Inline: True
Inline callers:
  - drivers/xen/sys-hypervisor.c:buildid_show
  - drivers/xen/sys-hypervisor.c:buildid_show
  - drivers/xen/sys-hypervisor.c:features_show
  - drivers/xen/sys-hypervisor.c:pagesize_show
  - drivers/xen/sys-hypervisor.c:virtual_start_show
  - drivers/xen/sys-hypervisor.c:changeset_show
  - drivers/xen/sys-hypervisor.c:capabilities_show
  - drivers/xen/sys-hypervisor.c:compile_date_show
  - drivers/xen/sys-hypervisor.c:compiled_by_show
  - drivers/xen/sys-hypervisor.c:compiler_show
  - drivers/xen/sys-hypervisor.c:uuid_show
  - drivers/xen/sys-hypervisor.c:extra_show
  - drivers/xen/sys-hypervisor.c:minor_show
  - drivers/xen/sys-hypervisor.c:major_show
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
In arch/x86/xen/irq.c (ffffffff8101b537)
Location: arch/x86/include/asm/xen/hypercall.h:380
Inline: True
Inline callers:
  - arch/x86/xen/irq.c:xen_irq_enable
  - arch/x86/xen/irq.c:xen_restore_fl
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff826abe19)
Location: arch/x86/include/asm/xen/hypercall.h:380
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_banner
  - arch/x86/xen/enlighten_pv.c:xen_banner
```
```
In drivers/xen/features.c (ffffffff815bae26)
Location: arch/x86/include/asm/xen/hypercall.h:380
Inline: True
Inline callers:
  - drivers/xen/features.c:xen_setup_features
```
```
In drivers/xen/sys-hypervisor.c (ffffffff815c97d6)
Location: arch/x86/include/asm/xen/hypercall.h:380
Inline: True
Inline callers:
  - drivers/xen/sys-hypervisor.c:buildid_show
  - drivers/xen/sys-hypervisor.c:buildid_show
  - drivers/xen/sys-hypervisor.c:features_show
  - drivers/xen/sys-hypervisor.c:pagesize_show
  - drivers/xen/sys-hypervisor.c:virtual_start_show
  - drivers/xen/sys-hypervisor.c:changeset_show
  - drivers/xen/sys-hypervisor.c:capabilities_show
  - drivers/xen/sys-hypervisor.c:compile_date_show
  - drivers/xen/sys-hypervisor.c:compiled_by_show
  - drivers/xen/sys-hypervisor.c:compiler_show
  - drivers/xen/sys-hypervisor.c:uuid_show
  - drivers/xen/sys-hypervisor.c:extra_show
  - drivers/xen/sys-hypervisor.c:minor_show
  - drivers/xen/sys-hypervisor.c:major_show
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
In arch/x86/xen/irq.c (ffffffff8101bf27)
Location: arch/x86/include/asm/xen/hypercall.h:380
Inline: True
Inline callers:
  - arch/x86/xen/irq.c:xen_irq_enable
  - arch/x86/xen/irq.c:xen_restore_fl
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff826d4f5e)
Location: arch/x86/include/asm/xen/hypercall.h:380
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_banner
  - arch/x86/xen/enlighten_pv.c:xen_banner
```
```
In drivers/xen/features.c (ffffffff815f34e9)
Location: arch/x86/include/asm/xen/hypercall.h:380
Inline: True
Inline callers:
  - drivers/xen/features.c:xen_setup_features
```
```
In drivers/xen/sys-hypervisor.c (ffffffff81602075)
Location: arch/x86/include/asm/xen/hypercall.h:380
Inline: True
Inline callers:
  - drivers/xen/sys-hypervisor.c:buildid_show
  - drivers/xen/sys-hypervisor.c:buildid_show
  - drivers/xen/sys-hypervisor.c:pagesize_show
  - drivers/xen/sys-hypervisor.c:virtual_start_show
  - drivers/xen/sys-hypervisor.c:changeset_show
  - drivers/xen/sys-hypervisor.c:capabilities_show
  - drivers/xen/sys-hypervisor.c:compile_date_show
  - drivers/xen/sys-hypervisor.c:compiled_by_show
  - drivers/xen/sys-hypervisor.c:compiler_show
  - drivers/xen/sys-hypervisor.c:uuid_show
  - drivers/xen/sys-hypervisor.c:extra_show
  - drivers/xen/sys-hypervisor.c:minor_show
  - drivers/xen/sys-hypervisor.c:major_show
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
In arch/x86/xen/enlighten_pv.c (ffffffff8288af7b)
Location: arch/x86/include/asm/xen/hypercall.h:347
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_banner
  - arch/x86/xen/enlighten_pv.c:xen_banner
```
```
In arch/x86/xen/irq.c (ffffffff81026147)
Location: arch/x86/include/asm/xen/hypercall.h:347
Inline: True
Inline callers:
  - arch/x86/xen/irq.c:xen_irq_enable
  - arch/x86/xen/irq.c:xen_restore_fl
```
```
In drivers/xen/features.c (ffffffff8160e559)
Location: arch/x86/include/asm/xen/hypercall.h:347
Inline: True
Inline callers:
  - drivers/xen/features.c:xen_setup_features
```
```
In drivers/xen/sys-hypervisor.c (ffffffff8161d165)
Location: arch/x86/include/asm/xen/hypercall.h:347
Inline: True
Inline callers:
  - drivers/xen/sys-hypervisor.c:buildid_show
  - drivers/xen/sys-hypervisor.c:buildid_show
  - drivers/xen/sys-hypervisor.c:pagesize_show
  - drivers/xen/sys-hypervisor.c:virtual_start_show
  - drivers/xen/sys-hypervisor.c:changeset_show
  - drivers/xen/sys-hypervisor.c:capabilities_show
  - drivers/xen/sys-hypervisor.c:compile_date_show
  - drivers/xen/sys-hypervisor.c:compiled_by_show
  - drivers/xen/sys-hypervisor.c:compiler_show
  - drivers/xen/sys-hypervisor.c:uuid_show
  - drivers/xen/sys-hypervisor.c:extra_show
  - drivers/xen/sys-hypervisor.c:minor_show
  - drivers/xen/sys-hypervisor.c:major_show
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
In arch/x86/xen/enlighten_pv.c (ffffffff828a2368)
Location: arch/x86/include/asm/xen/hypercall.h:362
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_banner
  - arch/x86/xen/enlighten_pv.c:xen_banner
```
```
In arch/x86/xen/irq.c (ffffffff81027e52)
Location: arch/x86/include/asm/xen/hypercall.h:362
Inline: True
Inline callers:
  - arch/x86/xen/irq.c:xen_irq_enable
  - arch/x86/xen/irq.c:xen_restore_fl
```
```
In drivers/xen/features.c (ffffffff816422d9)
Location: arch/x86/include/asm/xen/hypercall.h:362
Inline: True
Inline callers:
  - drivers/xen/features.c:xen_setup_features
```
```
In drivers/xen/sys-hypervisor.c (ffffffff81650395)
Location: arch/x86/include/asm/xen/hypercall.h:362
Inline: True
Inline callers:
  - drivers/xen/sys-hypervisor.c:buildid_show
  - drivers/xen/sys-hypervisor.c:buildid_show
  - drivers/xen/sys-hypervisor.c:features_show
  - drivers/xen/sys-hypervisor.c:pagesize_show
  - drivers/xen/sys-hypervisor.c:virtual_start_show
  - drivers/xen/sys-hypervisor.c:changeset_show
  - drivers/xen/sys-hypervisor.c:capabilities_show
  - drivers/xen/sys-hypervisor.c:compile_date_show
  - drivers/xen/sys-hypervisor.c:compiled_by_show
  - drivers/xen/sys-hypervisor.c:compiler_show
  - drivers/xen/sys-hypervisor.c:uuid_show
  - drivers/xen/sys-hypervisor.c:extra_show
  - drivers/xen/sys-hypervisor.c:minor_show
  - drivers/xen/sys-hypervisor.c:major_show
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
In arch/x86/xen/enlighten_pv.c (ffffffff828a547b)
Location: arch/x86/include/asm/xen/hypercall.h:362
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_banner
  - arch/x86/xen/enlighten_pv.c:xen_banner
```
```
In arch/x86/xen/irq.c (ffffffff81028762)
Location: arch/x86/include/asm/xen/hypercall.h:362
Inline: True
Inline callers:
  - arch/x86/xen/irq.c:xen_irq_enable
  - arch/x86/xen/irq.c:xen_restore_fl
```
```
In drivers/xen/features.c (ffffffff81664899)
Location: arch/x86/include/asm/xen/hypercall.h:362
Inline: True
Inline callers:
  - drivers/xen/features.c:xen_setup_features
```
```
In drivers/xen/sys-hypervisor.c (ffffffff81672935)
Location: arch/x86/include/asm/xen/hypercall.h:362
Inline: True
Inline callers:
  - drivers/xen/sys-hypervisor.c:buildid_show
  - drivers/xen/sys-hypervisor.c:buildid_show
  - drivers/xen/sys-hypervisor.c:features_show
  - drivers/xen/sys-hypervisor.c:pagesize_show
  - drivers/xen/sys-hypervisor.c:virtual_start_show
  - drivers/xen/sys-hypervisor.c:changeset_show
  - drivers/xen/sys-hypervisor.c:capabilities_show
  - drivers/xen/sys-hypervisor.c:compile_date_show
  - drivers/xen/sys-hypervisor.c:compiled_by_show
  - drivers/xen/sys-hypervisor.c:compiler_show
  - drivers/xen/sys-hypervisor.c:uuid_show
  - drivers/xen/sys-hypervisor.c:extra_show
  - drivers/xen/sys-hypervisor.c:minor_show
  - drivers/xen/sys-hypervisor.c:major_show
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
In arch/x86/xen/enlighten_pv.c (ffffffff82ccb76b)
Location: arch/x86/include/asm/xen/hypercall.h:362
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_banner
  - arch/x86/xen/enlighten_pv.c:xen_banner
```
```
In arch/x86/xen/irq.c (ffffffff8102a6c2)
Location: arch/x86/include/asm/xen/hypercall.h:362
Inline: True
Inline callers:
  - arch/x86/xen/irq.c:xen_irq_enable
  - arch/x86/xen/irq.c:xen_restore_fl
```
```
In drivers/xen/features.c (ffffffff81713e99)
Location: arch/x86/include/asm/xen/hypercall.h:362
Inline: True
Inline callers:
  - drivers/xen/features.c:xen_setup_features
```
```
In drivers/xen/sys-hypervisor.c (ffffffff81723035)
Location: arch/x86/include/asm/xen/hypercall.h:362
Inline: True
Inline callers:
  - drivers/xen/sys-hypervisor.c:buildid_show
  - drivers/xen/sys-hypervisor.c:buildid_show
  - drivers/xen/sys-hypervisor.c:features_show
  - drivers/xen/sys-hypervisor.c:pagesize_show
  - drivers/xen/sys-hypervisor.c:virtual_start_show
  - drivers/xen/sys-hypervisor.c:changeset_show
  - drivers/xen/sys-hypervisor.c:capabilities_show
  - drivers/xen/sys-hypervisor.c:compile_date_show
  - drivers/xen/sys-hypervisor.c:compiled_by_show
  - drivers/xen/sys-hypervisor.c:compiler_show
  - drivers/xen/sys-hypervisor.c:uuid_show
  - drivers/xen/sys-hypervisor.c:extra_show
  - drivers/xen/sys-hypervisor.c:minor_show
  - drivers/xen/sys-hypervisor.c:major_show
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
In arch/x86/xen/enlighten_pv.c (ffffffff82fb757a)
Location: arch/x86/include/asm/xen/hypercall.h:362
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_banner
  - arch/x86/xen/enlighten_pv.c:xen_banner
```
```
In arch/x86/xen/irq.c (ffffffff8102afe2)
Location: arch/x86/include/asm/xen/hypercall.h:362
Inline: True
Inline callers:
  - arch/x86/xen/irq.c:xen_irq_enable
  - arch/x86/xen/irq.c:xen_restore_fl
```
```
In drivers/xen/features.c (ffffffff81730b59)
Location: arch/x86/include/asm/xen/hypercall.h:362
Inline: True
Inline callers:
  - drivers/xen/features.c:xen_setup_features
```
```
In drivers/xen/sys-hypervisor.c (ffffffff8173fc75)
Location: arch/x86/include/asm/xen/hypercall.h:362
Inline: True
Inline callers:
  - drivers/xen/sys-hypervisor.c:buildid_show
  - drivers/xen/sys-hypervisor.c:buildid_show
  - drivers/xen/sys-hypervisor.c:features_show
  - drivers/xen/sys-hypervisor.c:pagesize_show
  - drivers/xen/sys-hypervisor.c:virtual_start_show
  - drivers/xen/sys-hypervisor.c:changeset_show
  - drivers/xen/sys-hypervisor.c:capabilities_show
  - drivers/xen/sys-hypervisor.c:compile_date_show
  - drivers/xen/sys-hypervisor.c:compiled_by_show
  - drivers/xen/sys-hypervisor.c:compiler_show
  - drivers/xen/sys-hypervisor.c:uuid_show
  - drivers/xen/sys-hypervisor.c:extra_show
  - drivers/xen/sys-hypervisor.c:minor_show
  - drivers/xen/sys-hypervisor.c:major_show
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
In arch/x86/xen/enlighten_pv.c (ffffffff831c2275)
Location: arch/x86/include/asm/xen/hypercall.h:362
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_banner
  - arch/x86/xen/enlighten_pv.c:xen_banner
```
```
In arch/x86/xen/irq.c (ffffffff8102bb92)
Location: arch/x86/include/asm/xen/hypercall.h:362
Inline: True
Inline callers:
  - arch/x86/xen/irq.c:xen_irq_enable
```
```
In drivers/xen/features.c (ffffffff817146e9)
Location: arch/x86/include/asm/xen/hypercall.h:362
Inline: True
Inline callers:
  - drivers/xen/features.c:xen_setup_features
```
```
In drivers/xen/sys-hypervisor.c (ffffffff817236c5)
Location: arch/x86/include/asm/xen/hypercall.h:362
Inline: True
Inline callers:
  - drivers/xen/sys-hypervisor.c:buildid_show
  - drivers/xen/sys-hypervisor.c:buildid_show
  - drivers/xen/sys-hypervisor.c:features_show
  - drivers/xen/sys-hypervisor.c:pagesize_show
  - drivers/xen/sys-hypervisor.c:virtual_start_show
  - drivers/xen/sys-hypervisor.c:changeset_show
  - drivers/xen/sys-hypervisor.c:capabilities_show
  - drivers/xen/sys-hypervisor.c:compile_date_show
  - drivers/xen/sys-hypervisor.c:compiled_by_show
  - drivers/xen/sys-hypervisor.c:compiler_show
  - drivers/xen/sys-hypervisor.c:uuid_show
  - drivers/xen/sys-hypervisor.c:extra_show
  - drivers/xen/sys-hypervisor.c:minor_show
  - drivers/xen/sys-hypervisor.c:major_show
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
In arch/x86/xen/enlighten.c (ffffffff81026ea5)
Location: arch/x86/include/asm/xen/hypercall.h:362
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_running_on_version_or_later
  - arch/x86/xen/enlighten.c:xen_banner
  - arch/x86/xen/enlighten.c:xen_banner
```
```
In arch/x86/xen/irq.c (ffffffff81030302)
Location: arch/x86/include/asm/xen/hypercall.h:362
Inline: True
Inline callers:
  - arch/x86/xen/irq.c:xen_irq_enable
```
```
In drivers/xen/features.c (ffffffff81791492)
Location: arch/x86/include/asm/xen/hypercall.h:362
Inline: True
Inline callers:
  - drivers/xen/features.c:xen_setup_features
```
```
In drivers/xen/sys-hypervisor.c (ffffffff817a24d5)
Location: arch/x86/include/asm/xen/hypercall.h:362
Inline: True
Inline callers:
  - drivers/xen/sys-hypervisor.c:buildid_show
  - drivers/xen/sys-hypervisor.c:buildid_show
  - drivers/xen/sys-hypervisor.c:features_show
  - drivers/xen/sys-hypervisor.c:pagesize_show
  - drivers/xen/sys-hypervisor.c:virtual_start_show
  - drivers/xen/sys-hypervisor.c:changeset_show
  - drivers/xen/sys-hypervisor.c:capabilities_show
  - drivers/xen/sys-hypervisor.c:compile_date_show
  - drivers/xen/sys-hypervisor.c:compiled_by_show
  - drivers/xen/sys-hypervisor.c:compiler_show
  - drivers/xen/sys-hypervisor.c:uuid_show
  - drivers/xen/sys-hypervisor.c:extra_show
  - drivers/xen/sys-hypervisor.c:minor_show
  - drivers/xen/sys-hypervisor.c:major_show
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
In arch/x86/xen/enlighten.c (ffffffff8102aff7)
Location: arch/x86/include/asm/xen/hypercall.h:432
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_running_on_version_or_later
  - arch/x86/xen/enlighten.c:xen_banner
  - arch/x86/xen/enlighten.c:xen_banner
```
```
In arch/x86/xen/irq.c (ffffffff81f13590)
Location: arch/x86/include/asm/xen/hypercall.h:432
Inline: True
Inline callers:
  - arch/x86/xen/irq.c:xen_force_evtchn_callback
```
```
In drivers/xen/features.c (ffffffff818c9bb3)
Location: arch/x86/include/asm/xen/hypercall.h:432
Inline: True
Inline callers:
  - drivers/xen/features.c:xen_setup_features
```
```
In drivers/xen/sys-hypervisor.c (ffffffff818dc6d5)
Location: arch/x86/include/asm/xen/hypercall.h:432
Inline: True
Inline callers:
  - drivers/xen/sys-hypervisor.c:buildid_show
  - drivers/xen/sys-hypervisor.c:buildid_show
  - drivers/xen/sys-hypervisor.c:features_show
  - drivers/xen/sys-hypervisor.c:pagesize_show
  - drivers/xen/sys-hypervisor.c:virtual_start_show
  - drivers/xen/sys-hypervisor.c:changeset_show
  - drivers/xen/sys-hypervisor.c:capabilities_show
  - drivers/xen/sys-hypervisor.c:compile_date_show
  - drivers/xen/sys-hypervisor.c:compiled_by_show
  - drivers/xen/sys-hypervisor.c:compiler_show
  - drivers/xen/sys-hypervisor.c:uuid_show
  - drivers/xen/sys-hypervisor.c:extra_show
  - drivers/xen/sys-hypervisor.c:minor_show
  - drivers/xen/sys-hypervisor.c:major_show
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
In arch/x86/xen/enlighten.c (ffffffff81031c97)
Location: arch/x86/include/asm/xen/hypercall.h:432
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_running_on_version_or_later
  - arch/x86/xen/enlighten.c:xen_banner
  - arch/x86/xen/enlighten.c:xen_banner
```
```
In arch/x86/xen/irq.c (ffffffff820ba6b0)
Location: arch/x86/include/asm/xen/hypercall.h:432
Inline: True
Inline callers:
  - arch/x86/xen/irq.c:xen_force_evtchn_callback
```
```
In drivers/xen/features.c (ffffffff81a1aaf3)
Location: arch/x86/include/asm/xen/hypercall.h:432
Inline: True
Inline callers:
  - drivers/xen/features.c:xen_setup_features
```
```
In drivers/xen/sys-hypervisor.c (ffffffff81a2f9c5)
Location: arch/x86/include/asm/xen/hypercall.h:432
Inline: True
Inline callers:
  - drivers/xen/sys-hypervisor.c:buildid_show
  - drivers/xen/sys-hypervisor.c:buildid_show
  - drivers/xen/sys-hypervisor.c:features_show
  - drivers/xen/sys-hypervisor.c:pagesize_show
  - drivers/xen/sys-hypervisor.c:virtual_start_show
  - drivers/xen/sys-hypervisor.c:changeset_show
  - drivers/xen/sys-hypervisor.c:capabilities_show
  - drivers/xen/sys-hypervisor.c:compile_date_show
  - drivers/xen/sys-hypervisor.c:compiled_by_show
  - drivers/xen/sys-hypervisor.c:compiler_show
  - drivers/xen/sys-hypervisor.c:uuid_show
  - drivers/xen/sys-hypervisor.c:extra_show
  - drivers/xen/sys-hypervisor.c:minor_show
  - drivers/xen/sys-hypervisor.c:major_show
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
In arch/x86/xen/enlighten.c (ffffffff81031c97)
Location: arch/x86/include/asm/xen/hypercall.h:432
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_running_on_version_or_later
  - arch/x86/xen/enlighten.c:xen_banner
  - arch/x86/xen/enlighten.c:xen_banner
```
```
In arch/x86/xen/irq.c (ffffffff82139fa0)
Location: arch/x86/include/asm/xen/hypercall.h:432
Inline: True
Inline callers:
  - arch/x86/xen/irq.c:xen_force_evtchn_callback
```
```
In drivers/xen/features.c (ffffffff81a63ca3)
Location: arch/x86/include/asm/xen/hypercall.h:432
Inline: True
Inline callers:
  - drivers/xen/features.c:xen_setup_features
```
```
In drivers/xen/sys-hypervisor.c (ffffffff81a791d5)
Location: arch/x86/include/asm/xen/hypercall.h:432
Inline: True
Inline callers:
  - drivers/xen/sys-hypervisor.c:buildid_show
  - drivers/xen/sys-hypervisor.c:buildid_show
  - drivers/xen/sys-hypervisor.c:features_show
  - drivers/xen/sys-hypervisor.c:pagesize_show
  - drivers/xen/sys-hypervisor.c:virtual_start_show
  - drivers/xen/sys-hypervisor.c:changeset_show
  - drivers/xen/sys-hypervisor.c:capabilities_show
  - drivers/xen/sys-hypervisor.c:compile_date_show
  - drivers/xen/sys-hypervisor.c:compiled_by_show
  - drivers/xen/sys-hypervisor.c:compiler_show
  - drivers/xen/sys-hypervisor.c:uuid_show
  - drivers/xen/sys-hypervisor.c:extra_show
  - drivers/xen/sys-hypervisor.c:minor_show
  - drivers/xen/sys-hypervisor.c:major_show
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
In arch/x86/xen/enlighten.c (ffffffff81037f87)
Location: arch/x86/include/asm/xen/hypercall.h:432
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_running_on_version_or_later
  - arch/x86/xen/enlighten.c:xen_banner
  - arch/x86/xen/enlighten.c:xen_banner
```
```
In arch/x86/xen/irq.c (ffffffff8221bf10)
Location: arch/x86/include/asm/xen/hypercall.h:432
Inline: True
Inline callers:
  - arch/x86/xen/irq.c:xen_force_evtchn_callback
```
```
In drivers/xen/features.c (ffffffff81ab64e3)
Location: arch/x86/include/asm/xen/hypercall.h:432
Inline: True
Inline callers:
  - drivers/xen/features.c:xen_setup_features
```
```
In drivers/xen/sys-hypervisor.c (ffffffff81acb645)
Location: arch/x86/include/asm/xen/hypercall.h:432
Inline: True
Inline callers:
  - drivers/xen/sys-hypervisor.c:buildid_show
  - drivers/xen/sys-hypervisor.c:buildid_show
  - drivers/xen/sys-hypervisor.c:features_show
  - drivers/xen/sys-hypervisor.c:pagesize_show
  - drivers/xen/sys-hypervisor.c:virtual_start_show
  - drivers/xen/sys-hypervisor.c:changeset_show
  - drivers/xen/sys-hypervisor.c:capabilities_show
  - drivers/xen/sys-hypervisor.c:compile_date_show
  - drivers/xen/sys-hypervisor.c:compiled_by_show
  - drivers/xen/sys-hypervisor.c:compiler_show
  - drivers/xen/sys-hypervisor.c:uuid_show
  - drivers/xen/sys-hypervisor.c:extra_show
  - drivers/xen/sys-hypervisor.c:minor_show
  - drivers/xen/sys-hypervisor.c:major_show
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - drivers/xen/features.c:xen_setup_features
  - drivers/xen/sys-hypervisor.c:buildid_show
  - drivers/xen/sys-hypervisor.c:buildid_show
  - drivers/xen/sys-hypervisor.c:features_show
  - drivers/xen/sys-hypervisor.c:pagesize_show
  - drivers/xen/sys-hypervisor.c:virtual_start_show
  - drivers/xen/sys-hypervisor.c:changeset_show
  - drivers/xen/sys-hypervisor.c:capabilities_show
  - drivers/xen/sys-hypervisor.c:compile_date_show
  - drivers/xen/sys-hypervisor.c:compiled_by_show
  - drivers/xen/sys-hypervisor.c:compiler_show
  - drivers/xen/sys-hypervisor.c:uuid_show
  - drivers/xen/sys-hypervisor.c:extra_show
  - drivers/xen/sys-hypervisor.c:minor_show
  - drivers/xen/sys-hypervisor.c:major_show
```
**Symbols:**

```
ffff8000100f0cf0-ffff8000100f0cfc: HYPERVISOR_xen_version (STB_GLOBAL)
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
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_pv.c (ffffffff82893484)
Location: arch/x86/include/asm/xen/hypercall.h:362
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_banner
  - arch/x86/xen/enlighten_pv.c:xen_banner
```
```
In arch/x86/xen/irq.c (ffffffff810288c2)
Location: arch/x86/include/asm/xen/hypercall.h:362
Inline: True
Inline callers:
  - arch/x86/xen/irq.c:xen_irq_enable
  - arch/x86/xen/irq.c:xen_restore_fl
```
```
In drivers/xen/features.c (ffffffff8162a709)
Location: arch/x86/include/asm/xen/hypercall.h:362
Inline: True
Inline callers:
  - drivers/xen/features.c:xen_setup_features
```
```
In drivers/xen/sys-hypervisor.c (ffffffff81638625)
Location: arch/x86/include/asm/xen/hypercall.h:362
Inline: True
Inline callers:
  - drivers/xen/sys-hypervisor.c:buildid_show
  - drivers/xen/sys-hypervisor.c:buildid_show
  - drivers/xen/sys-hypervisor.c:features_show
  - drivers/xen/sys-hypervisor.c:pagesize_show
  - drivers/xen/sys-hypervisor.c:virtual_start_show
  - drivers/xen/sys-hypervisor.c:changeset_show
  - drivers/xen/sys-hypervisor.c:capabilities_show
  - drivers/xen/sys-hypervisor.c:compile_date_show
  - drivers/xen/sys-hypervisor.c:compiled_by_show
  - drivers/xen/sys-hypervisor.c:compiler_show
  - drivers/xen/sys-hypervisor.c:uuid_show
  - drivers/xen/sys-hypervisor.c:extra_show
  - drivers/xen/sys-hypervisor.c:minor_show
  - drivers/xen/sys-hypervisor.c:major_show
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_pv.c (ffffffff828a647b)
Location: arch/x86/include/asm/xen/hypercall.h:362
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_banner
  - arch/x86/xen/enlighten_pv.c:xen_banner
```
```
In arch/x86/xen/irq.c (ffffffff81028722)
Location: arch/x86/include/asm/xen/hypercall.h:362
Inline: True
Inline callers:
  - arch/x86/xen/irq.c:xen_irq_enable
  - arch/x86/xen/irq.c:xen_restore_fl
```
```
In drivers/xen/features.c (ffffffff816586d9)
Location: arch/x86/include/asm/xen/hypercall.h:362
Inline: True
Inline callers:
  - drivers/xen/features.c:xen_setup_features
```
```
In drivers/xen/sys-hypervisor.c (ffffffff81666775)
Location: arch/x86/include/asm/xen/hypercall.h:362
Inline: True
Inline callers:
  - drivers/xen/sys-hypervisor.c:buildid_show
  - drivers/xen/sys-hypervisor.c:buildid_show
  - drivers/xen/sys-hypervisor.c:features_show
  - drivers/xen/sys-hypervisor.c:pagesize_show
  - drivers/xen/sys-hypervisor.c:virtual_start_show
  - drivers/xen/sys-hypervisor.c:changeset_show
  - drivers/xen/sys-hypervisor.c:capabilities_show
  - drivers/xen/sys-hypervisor.c:compile_date_show
  - drivers/xen/sys-hypervisor.c:compiled_by_show
  - drivers/xen/sys-hypervisor.c:compiler_show
  - drivers/xen/sys-hypervisor.c:uuid_show
  - drivers/xen/sys-hypervisor.c:extra_show
  - drivers/xen/sys-hypervisor.c:minor_show
  - drivers/xen/sys-hypervisor.c:major_show
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
In arch/x86/xen/enlighten_pv.c (ffffffff828a644f)
Location: arch/x86/include/asm/xen/hypercall.h:362
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_banner
  - arch/x86/xen/enlighten_pv.c:xen_banner
```
```
In arch/x86/xen/irq.c (ffffffff810293fe)
Location: arch/x86/include/asm/xen/hypercall.h:362
Inline: True
Inline callers:
  - arch/x86/xen/irq.c:xen_irq_enable
  - arch/x86/xen/irq.c:xen_restore_fl
```
```
In drivers/xen/features.c (ffffffff81672cd9)
Location: arch/x86/include/asm/xen/hypercall.h:362
Inline: True
Inline callers:
  - drivers/xen/features.c:xen_setup_features
```
```
In drivers/xen/sys-hypervisor.c (ffffffff81680d25)
Location: arch/x86/include/asm/xen/hypercall.h:362
Inline: True
Inline callers:
  - drivers/xen/sys-hypervisor.c:buildid_show
  - drivers/xen/sys-hypervisor.c:buildid_show
  - drivers/xen/sys-hypervisor.c:features_show
  - drivers/xen/sys-hypervisor.c:pagesize_show
  - drivers/xen/sys-hypervisor.c:virtual_start_show
  - drivers/xen/sys-hypervisor.c:changeset_show
  - drivers/xen/sys-hypervisor.c:capabilities_show
  - drivers/xen/sys-hypervisor.c:compile_date_show
  - drivers/xen/sys-hypervisor.c:compiled_by_show
  - drivers/xen/sys-hypervisor.c:compiler_show
  - drivers/xen/sys-hypervisor.c:uuid_show
  - drivers/xen/sys-hypervisor.c:extra_show
  - drivers/xen/sys-hypervisor.c:minor_show
  - drivers/xen/sys-hypervisor.c:major_show
```
</details>
</li>
</ul>

## Differences
