# Function: <code>num_node_state</code>

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
In arch/x86/kernel/smpboot.c (ffffffff810519a6)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:smp_announce
  - arch/x86/kernel/smpboot.c:native_cpu_up
```
```
In arch/x86/mm/numa.c (ffffffff81f78e5a)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_init
```
```
In kernel/workqueue.c (ffffffff81f7c2e6)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - kernel/workqueue.c:init_workqueues
```
```
In mm/mempolicy.c (ffffffff81f8c4ea)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - mm/mempolicy.c:numa_policy_init
```
```
In mm/memory_hotplug.c (ffffffff811efb07)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_node
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:try_online_node
```
```
In security/apparmor/lsm.c (ffffffff81f9956c)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - security/apparmor/lsm.c:alloc_buffers
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff816b77dd)
Location: include/linux/nodemask.h:413
Inline: True
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
In arch/x86/kernel/smpboot.c (ffffffff8105208a)
Location: include/linux/nodemask.h:422
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/smpboot.c:smp_announce
```
```
In arch/x86/mm/numa.c (ffffffff81fa1585)
Location: include/linux/nodemask.h:422
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_init
```
```
In kernel/workqueue.c (ffffffff81fa5089)
Location: include/linux/nodemask.h:422
Inline: True
Inline callers:
  - kernel/workqueue.c:init_workqueues
```
```
In mm/mempolicy.c (ffffffff81fb61f2)
Location: include/linux/nodemask.h:422
Inline: True
Inline callers:
  - mm/mempolicy.c:numa_policy_init
```
```
In mm/memory_hotplug.c (ffffffff8120ef52)
Location: include/linux/nodemask.h:422
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_node
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:try_online_node
```
```
In security/apparmor/lsm.c (ffffffff81fc42df)
Location: include/linux/nodemask.h:422
Inline: True
Inline callers:
  - security/apparmor/lsm.c:alloc_buffers
```
```
In drivers/md/dm.c (ffffffff81703b4f)
Location: include/linux/nodemask.h:422
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_create
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff817192b6)
Location: include/linux/nodemask.h:422
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_init
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
In arch/x86/kernel/smpboot.c (ffffffff81054961)
Location: include/linux/nodemask.h:422
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
```
```
In arch/x86/mm/numa.c (ffffffff81fdc354)
Location: include/linux/nodemask.h:422
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:alloc_node_data
```
```
In kernel/workqueue.c (ffffffff81fe09ee)
Location: include/linux/nodemask.h:422
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_init
```
```
In kernel/smp.c (ffffffff81fe5d2a)
Location: include/linux/nodemask.h:422
Inline: True
Inline callers:
  - kernel/smp.c:smp_init
```
```
In mm/mempolicy.c (ffffffff81ff2baf)
Location: include/linux/nodemask.h:422
Inline: True
Inline callers:
  - mm/mempolicy.c:numa_policy_init
```
```
In mm/memory_hotplug.c (ffffffff81221056)
Location: include/linux/nodemask.h:422
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_node
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:try_online_node
```
```
In security/apparmor/lsm.c (ffffffff82000d98)
Location: include/linux/nodemask.h:422
Inline: True
```
```
In drivers/md/dm.c (ffffffff81735a08)
Location: include/linux/nodemask.h:422
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_create
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff8174b8f5)
Location: include/linux/nodemask.h:422
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_init
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
In arch/x86/kernel/smpboot.c (ffffffff810542ab)
Location: include/linux/nodemask.h:418
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
```
```
In arch/x86/mm/numa.c (ffffffff820bd36b)
Location: include/linux/nodemask.h:418
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:alloc_node_data
```
```
In kernel/workqueue.c (ffffffff820c183d)
Location: include/linux/nodemask.h:418
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_init
```
```
In kernel/smp.c (ffffffff820c6646)
Location: include/linux/nodemask.h:418
Inline: True
Inline callers:
  - kernel/smp.c:smp_init
```
```
In mm/mempolicy.c (ffffffff820d5279)
Location: include/linux/nodemask.h:418
Inline: True
Inline callers:
  - mm/mempolicy.c:numa_policy_init
```
```
In mm/memory_hotplug.c (ffffffff8122c91d)
Location: include/linux/nodemask.h:418
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_node
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:try_online_node
```
```
In security/apparmor/lsm.c (ffffffff820e467a)
Location: include/linux/nodemask.h:418
Inline: True
```
```
In drivers/md/dm.c (ffffffff8174ee38)
Location: include/linux/nodemask.h:418
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_create
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff817696d6)
Location: include/linux/nodemask.h:418
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
In arch/x86/kernel/smpboot.c (ffffffff81058046)
Location: include/linux/nodemask.h:428
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
```
```
In arch/x86/mm/numa.c (ffffffff826c41aa)
Location: include/linux/nodemask.h:428
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:alloc_node_data
```
```
In kernel/workqueue.c (ffffffff826c9a2e)
Location: include/linux/nodemask.h:428
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_init
```
```
In kernel/smp.c (ffffffff826cecb2)
Location: include/linux/nodemask.h:428
Inline: True
Inline callers:
  - kernel/smp.c:smp_init
```
```
In mm/mempolicy.c (ffffffff826dde3f)
Location: include/linux/nodemask.h:428
Inline: True
Inline callers:
  - mm/mempolicy.c:numa_policy_init
```
```
In mm/memory_hotplug.c (ffffffff81248151)
Location: include/linux/nodemask.h:428
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_node
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:try_online_node
```
```
In security/apparmor/lsm.c (ffffffff826ed319)
Location: include/linux/nodemask.h:428
Inline: True
```
```
In drivers/md/dm.c (ffffffff817c1058)
Location: include/linux/nodemask.h:428
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_create
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff817df46c)
Location: include/linux/nodemask.h:428
Inline: True
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
In arch/x86/kernel/smpboot.c (ffffffff8105acdb)
Location: include/linux/nodemask.h:428
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
```
```
In arch/x86/mm/numa.c (ffffffff826ee445)
Location: include/linux/nodemask.h:428
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:alloc_node_data
```
```
In kernel/workqueue.c (ffffffff826f3c0d)
Location: include/linux/nodemask.h:428
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_numa_init
```
```
In kernel/smp.c (ffffffff826f93c6)
Location: include/linux/nodemask.h:428
Inline: True
Inline callers:
  - kernel/smp.c:smp_init
```
```
In mm/mempolicy.c (ffffffff82708399)
Location: include/linux/nodemask.h:428
Inline: True
Inline callers:
  - mm/mempolicy.c:numa_policy_init
```
```
In mm/memory_hotplug.c (ffffffff8126ba85)
Location: include/linux/nodemask.h:428
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_node
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:try_online_node
```
```
In security/apparmor/lsm.c (ffffffff82717647)
Location: include/linux/nodemask.h:428
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_init
```
```
In drivers/md/dm.c (ffffffff818096d5)
Location: include/linux/nodemask.h:428
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_create
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff81829430)
Location: include/linux/nodemask.h:428
Inline: True
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
In arch/x86/kernel/smpboot.c (ffffffff8106095b)
Location: include/linux/nodemask.h:428
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
```
```
In arch/x86/mm/numa.c (ffffffff828a5133)
Location: include/linux/nodemask.h:428
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:alloc_node_data
```
```
In kernel/workqueue.c (ffffffff828aa9f5)
Location: include/linux/nodemask.h:428
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_numa_init
```
```
In kernel/smp.c (ffffffff828b02a0)
Location: include/linux/nodemask.h:428
Inline: True
Inline callers:
  - kernel/smp.c:smp_init
```
```
In mm/mempolicy.c (ffffffff828bf76b)
Location: include/linux/nodemask.h:428
Inline: True
Inline callers:
  - mm/mempolicy.c:numa_policy_init
```
```
In mm/memory_hotplug.c (ffffffff81a2204a)
Location: include/linux/nodemask.h:428
Inline: True
Inline callers:
  - mm/memory_hotplug.c:add_memory_resource
```
```
In security/apparmor/lsm.c (ffffffff828cf017)
Location: include/linux/nodemask.h:428
Inline: True
Inline callers:
  - security/apparmor/lsm.c:alloc_buffers
```
```
In drivers/md/dm.c (ffffffff818357e5)
Location: include/linux/nodemask.h:428
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_create
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff81853e60)
Location: include/linux/nodemask.h:428
Inline: True
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
In arch/x86/kernel/smpboot.c (ffffffff810640f8)
Location: include/linux/nodemask.h:428
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:do_boot_cpu
```
```
In arch/x86/mm/numa.c (ffffffff828bd6bf)
Location: include/linux/nodemask.h:428
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:alloc_node_data
```
```
In kernel/workqueue.c (ffffffff828c31ec)
Location: include/linux/nodemask.h:428
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_numa_init
```
```
In kernel/smp.c (ffffffff828c8e16)
Location: include/linux/nodemask.h:428
Inline: True
Inline callers:
  - kernel/smp.c:smp_init
```
```
In mm/page_alloc.c (ffffffff828d6d54)
Location: include/linux/nodemask.h:428
Inline: True
Inline callers:
  - mm/page_alloc.c:page_alloc_init
```
```
In mm/mempolicy.c (ffffffff828d8972)
Location: include/linux/nodemask.h:428
Inline: True
Inline callers:
  - mm/mempolicy.c:numa_policy_init
```
```
In mm/memory_hotplug.c (ffffffff81a91dd9)
Location: include/linux/nodemask.h:428
Inline: True
Inline callers:
  - mm/memory_hotplug.c:add_memory_resource
```
```
In security/apparmor/lsm.c (ffffffff828e8b55)
Location: include/linux/nodemask.h:428
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_init
```
```
In drivers/md/dm.c (ffffffff81876b15)
Location: include/linux/nodemask.h:428
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_get_numa_node
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff818979ea)
Location: include/linux/nodemask.h:428
Inline: True
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
In arch/x86/kernel/smpboot.c (ffffffff81064792)
Location: include/linux/nodemask.h:428
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:do_boot_cpu
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff828bd0f5)
Location: include/linux/nodemask.h:428
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:build_socket_tables
  - arch/x86/kernel/apic/x2apic_uv_x.c:build_socket_tables
```
```
In arch/x86/mm/numa.c (ffffffff828c3b49)
Location: include/linux/nodemask.h:428
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:alloc_node_data
```
```
In kernel/workqueue.c (ffffffff828cb7e9)
Location: include/linux/nodemask.h:428
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_init
```
```
In kernel/smp.c (ffffffff828d1381)
Location: include/linux/nodemask.h:428
Inline: True
Inline callers:
  - kernel/smp.c:smp_init
```
```
In mm/page_alloc.c (ffffffff828df1e5)
Location: include/linux/nodemask.h:428
Inline: True
Inline callers:
  - mm/page_alloc.c:page_alloc_init
```
```
In mm/mempolicy.c (ffffffff828e0e06)
Location: include/linux/nodemask.h:428
Inline: True
Inline callers:
  - mm/mempolicy.c:numa_policy_init
```
```
In mm/memory_hotplug.c (ffffffff812abced)
Location: include/linux/nodemask.h:428
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_node
  - mm/memory_hotplug.c:add_memory_resource
```
```
In security/apparmor/lsm.c (ffffffff828f1641)
Location: include/linux/nodemask.h:428
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_init
```
```
In drivers/md/dm.c (ffffffff818a8915)
Location: include/linux/nodemask.h:428
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_get_numa_node
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff818c9f8b)
Location: include/linux/nodemask.h:428
Inline: True
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
In arch/x86/kernel/smpboot.c (ffffffff81069993)
Location: include/linux/nodemask.h:428
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:announce_cpu
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff82ce1643)
Location: include/linux/nodemask.h:428
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:build_socket_tables
  - arch/x86/kernel/apic/x2apic_uv_x.c:build_socket_tables
```
```
In arch/x86/mm/numa.c (ffffffff82ce6c4e)
Location: include/linux/nodemask.h:428
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:alloc_node_data
```
```
In kernel/workqueue.c (ffffffff82ced78b)
Location: include/linux/nodemask.h:428
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_numa_init
```
```
In kernel/smp.c (ffffffff82cf218d)
Location: include/linux/nodemask.h:428
Inline: True
Inline callers:
  - kernel/smp.c:smp_init
```
```
In mm/page_alloc.c (ffffffff82cfc584)
Location: include/linux/nodemask.h:428
Inline: True
Inline callers:
  - mm/page_alloc.c:page_alloc_init
```
```
In mm/mempolicy.c (ffffffff82cfe501)
Location: include/linux/nodemask.h:428
Inline: True
Inline callers:
  - mm/mempolicy.c:numa_policy_init
```
```
In mm/memory_hotplug.c (ffffffff812e05ed)
Location: include/linux/nodemask.h:428
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_node
  - mm/memory_hotplug.c:add_memory_resource
```
```
In fs/io-wq.c (ffffffff8138a925)
Location: include/linux/nodemask.h:428
Inline: True
Inline callers:
  - fs/io-wq.c:io_wq_manager
```
```
In drivers/md/dm.c (ffffffff8197a135)
Location: include/linux/nodemask.h:428
Inline: True
Inline callers:
  - drivers/md/dm.c:alloc_dev
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff8199b5c2)
Location: include/linux/nodemask.h:428
Inline: True
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
In arch/x86/kernel/smpboot.c (ffffffff8106b663)
Location: include/linux/nodemask.h:429
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:announce_cpu
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff82fce3ea)
Location: include/linux/nodemask.h:429
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:build_socket_tables
  - arch/x86/kernel/apic/x2apic_uv_x.c:build_socket_tables
```
```
In arch/x86/mm/numa.c (ffffffff82fd45cd)
Location: include/linux/nodemask.h:429
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:alloc_node_data
```
```
In kernel/workqueue.c (ffffffff82fd9de5)
Location: include/linux/nodemask.h:429
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_numa_init
```
```
In kernel/smp.c (ffffffff82fdec66)
Location: include/linux/nodemask.h:429
Inline: True
Inline callers:
  - kernel/smp.c:smp_init
```
```
In mm/page_alloc.c (ffffffff82fe8f9f)
Location: include/linux/nodemask.h:429
Inline: True
Inline callers:
  - mm/page_alloc.c:page_alloc_init
```
```
In mm/mempolicy.c (ffffffff82feaef4)
Location: include/linux/nodemask.h:429
Inline: True
Inline callers:
  - mm/mempolicy.c:numa_policy_init
```
```
In mm/memory_hotplug.c (ffffffff812ebdcd)
Location: include/linux/nodemask.h:429
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_node
  - mm/memory_hotplug.c:add_memory_resource
```
```
In drivers/md/dm.c (ffffffff8197e775)
Location: include/linux/nodemask.h:429
Inline: True
Inline callers:
  - drivers/md/dm.c:alloc_dev
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff8199e662)
Location: include/linux/nodemask.h:429
Inline: True
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
In arch/x86/kernel/cpu/sgx/main.c (ffffffff831ceb8c)
Location: include/linux/nodemask.h:429
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_page_cache_init
```
```
In arch/x86/kernel/smpboot.c (ffffffff8106c043)
Location: include/linux/nodemask.h:429
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:announce_cpu
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff831d8e8e)
Location: include/linux/nodemask.h:429
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:build_socket_tables
  - arch/x86/kernel/apic/x2apic_uv_x.c:build_socket_tables
```
```
In arch/x86/mm/numa.c (ffffffff831df14c)
Location: include/linux/nodemask.h:429
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:alloc_node_data
```
```
In kernel/workqueue.c (ffffffff831e479c)
Location: include/linux/nodemask.h:429
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_numa_init
```
```
In kernel/smp.c (ffffffff831e9778)
Location: include/linux/nodemask.h:429
Inline: True
Inline callers:
  - kernel/smp.c:smp_init
```
```
In mm/page_alloc.c (ffffffff831f37d9)
Location: include/linux/nodemask.h:429
Inline: True
Inline callers:
  - mm/page_alloc.c:page_alloc_init
```
```
In mm/memory_hotplug.c (ffffffff812c6745)
Location: include/linux/nodemask.h:429
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_node
  - mm/memory_hotplug.c:add_memory_resource
```
```
In mm/mempolicy.c (ffffffff831f5840)
Location: include/linux/nodemask.h:429
Inline: True
Inline callers:
  - mm/mempolicy.c:numa_policy_init
```
```
In drivers/md/dm.c (ffffffff819625c5)
Location: include/linux/nodemask.h:429
Inline: True
Inline callers:
  - drivers/md/dm.c:alloc_dev
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff819832c9)
Location: include/linux/nodemask.h:429
Inline: True
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
In arch/x86/kernel/cpu/sgx/main.c (ffffffff832b0e32)
Location: include/linux/nodemask.h:429
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_page_cache_init
```
```
In arch/x86/kernel/smpboot.c (ffffffff81076c2b)
Location: include/linux/nodemask.h:429
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:announce_cpu
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff832bc355)
Location: include/linux/nodemask.h:429
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:build_socket_tables
  - arch/x86/kernel/apic/x2apic_uv_x.c:build_socket_tables
```
```
In arch/x86/mm/numa.c (ffffffff832c26a1)
Location: include/linux/nodemask.h:429
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:alloc_node_data
```
```
In kernel/workqueue.c (ffffffff832c8458)
Location: include/linux/nodemask.h:429
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_numa_init
```
```
In kernel/smp.c (ffffffff832cdd7b)
Location: include/linux/nodemask.h:429
Inline: True
Inline callers:
  - kernel/smp.c:smp_init
```
```
In mm/page_alloc.c (ffffffff832d9a15)
Location: include/linux/nodemask.h:429
Inline: True
Inline callers:
  - mm/page_alloc.c:page_alloc_init
```
```
In mm/memory_hotplug.c (ffffffff8130b1ab)
Location: include/linux/nodemask.h:429
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_node
  - mm/memory_hotplug.c:add_memory_resource
```
```
In mm/mempolicy.c (ffffffff832dbee3)
Location: include/linux/nodemask.h:429
Inline: True
Inline callers:
  - mm/mempolicy.c:numa_policy_init
```
```
In drivers/md/dm.c (ffffffff81a09805)
Location: include/linux/nodemask.h:429
Inline: True
Inline callers:
  - drivers/md/dm.c:alloc_dev
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff81a2c8b9)
Location: include/linux/nodemask.h:429
Inline: True
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
In arch/x86/kernel/cpu/sgx/main.c (ffffffff83461fc9)
Location: include/linux/nodemask.h:428
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_page_cache_init
```
```
In arch/x86/kernel/smpboot.c (ffffffff81085ac9)
Location: include/linux/nodemask.h:428
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:announce_cpu
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff8346dc72)
Location: include/linux/nodemask.h:428
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:build_socket_tables
  - arch/x86/kernel/apic/x2apic_uv_x.c:build_socket_tables
```
```
In arch/x86/mm/numa.c (ffffffff81e5189f)
Location: include/linux/nodemask.h:428
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:node_set_online
```
```
In kernel/workqueue.c (ffffffff8347b564)
Location: include/linux/nodemask.h:428
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_numa_init
```
```
In kernel/smp.c (ffffffff83481a29)
Location: include/linux/nodemask.h:428
Inline: True
Inline callers:
  - kernel/smp.c:smp_init
```
```
In kernel/bpf/core.c (ffffffff8126c33e)
Location: include/linux/nodemask.h:428
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_pack_alloc
```
```
In mm/vmalloc.c (ffffffff8136703d)
Location: include/linux/nodemask.h:428
Inline: True
Inline callers:
  - mm/vmalloc.c:__vmalloc_node_range
```
```
In mm/page_alloc.c (ffffffff8348e9dc)
Location: include/linux/nodemask.h:428
Inline: True
Inline callers:
  - mm/page_alloc.c:page_alloc_init
```
```
In mm/memory_hotplug.c (ffffffff81373c38)
Location: include/linux/nodemask.h:428
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_node
  - mm/memory_hotplug.c:add_memory_resource
```
```
In mm/mempolicy.c (ffffffff83491681)
Location: include/linux/nodemask.h:428
Inline: True
Inline callers:
  - mm/mempolicy.c:numa_policy_init
```
```
In drivers/md/dm.c (ffffffff81b71145)
Location: include/linux/nodemask.h:428
Inline: True
Inline callers:
  - drivers/md/dm.c:alloc_dev
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff81b98065)
Location: include/linux/nodemask.h:428
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_init
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
In arch/x86/kernel/cpu/sgx/main.c (ffffffff83e8423d)
Location: include/linux/nodemask.h:436
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_page_cache_init
```
```
In arch/x86/kernel/smpboot.c (ffffffff81098d06)
Location: include/linux/nodemask.h:436
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:announce_cpu
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff83e939c2)
Location: include/linux/nodemask.h:436
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:build_socket_tables
  - arch/x86/kernel/apic/x2apic_uv_x.c:build_socket_tables
```
```
In arch/x86/mm/numa.c (ffffffff83e9e91b)
Location: include/linux/nodemask.h:436
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:init_gi_nodes
  - arch/x86/mm/numa.c:init_cpu_to_node
```
```
In kernel/workqueue.c (ffffffff83ea63e5)
Location: include/linux/nodemask.h:436
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_numa_init
```
```
In kernel/smp.c (ffffffff83eaec7a)
Location: include/linux/nodemask.h:436
Inline: True
Inline callers:
  - kernel/smp.c:smp_init
```
```
In kernel/bpf/core.c (ffffffff812c40af)
Location: include/linux/nodemask.h:436
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_pack_free
  - kernel/bpf/core.c:bpf_prog_pack_free
  - kernel/bpf/core.c:bpf_prog_pack_free
  - kernel/bpf/core.c:bpf_prog_pack_free
  - kernel/bpf/core.c:bpf_prog_pack_alloc
  - kernel/bpf/core.c:bpf_prog_pack_alloc
  - kernel/bpf/core.c:bpf_prog_pack_alloc
  - kernel/bpf/core.c:alloc_new_pack
  - kernel/bpf/core.c:alloc_new_pack
  - kernel/bpf/core.c:alloc_new_pack
  - kernel/bpf/core.c:alloc_new_pack
  - kernel/bpf/core.c:alloc_new_pack
```
```
In mm/vmalloc.c (ffffffff813e2edd)
Location: include/linux/nodemask.h:436
Inline: True
Inline callers:
  - mm/vmalloc.c:__vmalloc_node_range
```
```
In mm/page_alloc.c (ffffffff83ec0c75)
Location: include/linux/nodemask.h:436
Inline: True
Inline callers:
  - mm/page_alloc.c:page_alloc_init
```
```
In mm/memory_hotplug.c (ffffffff813f1385)
Location: include/linux/nodemask.h:436
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_node
  - mm/memory_hotplug.c:add_memory_resource
```
```
In mm/mempolicy.c (ffffffff83ec4a6f)
Location: include/linux/nodemask.h:436
Inline: True
Inline callers:
  - mm/mempolicy.c:numa_policy_init
```
```
In drivers/md/dm.c (ffffffff81d0df55)
Location: include/linux/nodemask.h:436
Inline: True
Inline callers:
  - drivers/md/dm.c:alloc_dev
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff81d39313)
Location: include/linux/nodemask.h:436
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_init
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
In arch/x86/kernel/cpu/sgx/main.c (ffffffff836a778d)
Location: include/linux/nodemask.h:436
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_page_cache_init
```
```
In arch/x86/kernel/smpboot.c (ffffffff8109c01b)
Location: include/linux/nodemask.h:436
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:announce_cpu
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff836b74df)
Location: include/linux/nodemask.h:436
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:build_socket_tables
```
```
In arch/x86/mm/numa.c (ffffffff836c2a7b)
Location: include/linux/nodemask.h:436
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:init_gi_nodes
  - arch/x86/mm/numa.c:alloc_node_data
  - arch/x86/mm/numa.c:init_cpu_to_node
```
```
In kernel/workqueue.c (ffffffff836caba5)
Location: include/linux/nodemask.h:436
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_numa_init
```
```
In kernel/smp.c (ffffffff836d3caa)
Location: include/linux/nodemask.h:436
Inline: True
Inline callers:
  - kernel/smp.c:smp_init
```
```
In kernel/bpf/core.c (ffffffff812eb05f)
Location: include/linux/nodemask.h:436
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_pack_free
  - kernel/bpf/core.c:bpf_prog_pack_free
  - kernel/bpf/core.c:bpf_prog_pack_free
  - kernel/bpf/core.c:bpf_prog_pack_free
  - kernel/bpf/core.c:bpf_prog_pack_alloc
  - kernel/bpf/core.c:bpf_prog_pack_alloc
  - kernel/bpf/core.c:bpf_prog_pack_alloc
  - kernel/bpf/core.c:alloc_new_pack
  - kernel/bpf/core.c:alloc_new_pack
  - kernel/bpf/core.c:alloc_new_pack
  - kernel/bpf/core.c:alloc_new_pack
  - kernel/bpf/core.c:alloc_new_pack
```
```
In mm/mm_init.c (ffffffff836e25cd)
Location: include/linux/nodemask.h:436
Inline: True
Inline callers:
  - mm/mm_init.c:free_area_init
```
```
In mm/vmalloc.c (ffffffff81417b3a)
Location: include/linux/nodemask.h:436
Inline: True
Inline callers:
  - mm/vmalloc.c:__vmalloc_node_range
```
```
In mm/memory_hotplug.c (ffffffff81424ec5)
Location: include/linux/nodemask.h:436
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_node
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:__try_online_node
```
```
In mm/mempolicy.c (ffffffff836e9b8f)
Location: include/linux/nodemask.h:436
Inline: True
Inline callers:
  - mm/mempolicy.c:numa_policy_init
```
```
In drivers/md/dm.c (ffffffff81d77555)
Location: include/linux/nodemask.h:436
Inline: True
Inline callers:
  - drivers/md/dm.c:alloc_dev
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff81da3db3)
Location: include/linux/nodemask.h:436
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_init
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
In arch/x86/kernel/cpu/sgx/main.c (ffffffff838d7ccd)
Location: include/linux/nodemask.h:436
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_page_cache_init
```
```
In arch/x86/kernel/smpboot.c (ffffffff810a361b)
Location: include/linux/nodemask.h:436
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:announce_cpu
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff838e7def)
Location: include/linux/nodemask.h:436
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:build_socket_tables
```
```
In arch/x86/mm/numa.c (ffffffff838f349b)
Location: include/linux/nodemask.h:436
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:init_gi_nodes
  - arch/x86/mm/numa.c:init_cpu_to_node
```
```
In kernel/smp.c (ffffffff83905c8a)
Location: include/linux/nodemask.h:436
Inline: True
Inline callers:
  - kernel/smp.c:smp_init
```
```
In kernel/bpf/core.c (ffffffff81309574)
Location: include/linux/nodemask.h:436
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_pack_free
  - kernel/bpf/core.c:bpf_prog_pack_free
  - kernel/bpf/core.c:bpf_prog_pack_free
  - kernel/bpf/core.c:bpf_prog_pack_free
  - kernel/bpf/core.c:bpf_prog_pack_alloc
  - kernel/bpf/core.c:bpf_prog_pack_alloc
  - kernel/bpf/core.c:bpf_prog_pack_alloc
  - kernel/bpf/core.c:alloc_new_pack
  - kernel/bpf/core.c:alloc_new_pack
  - kernel/bpf/core.c:alloc_new_pack
  - kernel/bpf/core.c:alloc_new_pack
  - kernel/bpf/core.c:alloc_new_pack
```
```
In mm/mm_init.c (ffffffff83914ece)
Location: include/linux/nodemask.h:436
Inline: True
Inline callers:
  - mm/mm_init.c:free_area_init
```
```
In mm/vmalloc.c (ffffffff8144468a)
Location: include/linux/nodemask.h:436
Inline: True
Inline callers:
  - mm/vmalloc.c:__vmalloc_node_range
```
```
In mm/memory_hotplug.c (ffffffff81452105)
Location: include/linux/nodemask.h:436
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_node
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:__try_online_node
```
```
In mm/mempolicy.c (ffffffff8391cf4f)
Location: include/linux/nodemask.h:436
Inline: True
Inline callers:
  - mm/mempolicy.c:numa_policy_init
```
```
In drivers/md/dm.c (ffffffff81e2e785)
Location: include/linux/nodemask.h:436
Inline: True
Inline callers:
  - drivers/md/dm.c:alloc_dev
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff81e5be43)
Location: include/linux/nodemask.h:436
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_init
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
In arch/arm64/mm/numa.c (ffff8000100b2344)
Location: include/linux/nodemask.h:428
Inline: True
Inline callers:
  - arch/arm64/mm/numa.c:node_set_online
```
```
In kernel/workqueue.c (ffff800011442ef4)
Location: include/linux/nodemask.h:428
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_numa_init
```
```
In kernel/smp.c (ffff800011449714)
Location: include/linux/nodemask.h:428
Inline: True
Inline callers:
  - kernel/smp.c:smp_init
```
```
In mm/page_alloc.c (ffff800011457fd8)
Location: include/linux/nodemask.h:428
Inline: True
Inline callers:
  - mm/page_alloc.c:page_alloc_init
```
```
In mm/mempolicy.c (ffff80001145a0c8)
Location: include/linux/nodemask.h:428
Inline: True
Inline callers:
  - mm/mempolicy.c:numa_policy_init
```
```
In mm/memory_hotplug.c (ffff80001034dbd8)
Location: include/linux/nodemask.h:428
Inline: True
```
```
In security/apparmor/lsm.c (ffff80001146b774)
Location: include/linux/nodemask.h:428
Inline: True
Inline callers:
  - security/apparmor/lsm.c:alloc_buffers
```
```
In drivers/md/dm.c (ffff800010afd038)
Location: include/linux/nodemask.h:428
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_get_numa_node
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
In kernel/workqueue.c (0)
Location: include/linux/nodemask.h:477
Inline: True
```
```
In kernel/smp.c (0)
Location: include/linux/nodemask.h:477
Inline: True
```
```
In security/apparmor/lsm.c (0)
Location: include/linux/nodemask.h:477
Inline: True
```
```
In drivers/md/dm.c (0)
Location: include/linux/nodemask.h:477
Inline: True
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
In arch/powerpc/mm/numa.c (c0000000000a3a3c)
Location: include/linux/nodemask.h:428
Inline: True
Inline callers:
  - arch/powerpc/mm/numa.c:node_set_online
```
```
In arch/powerpc/platforms/powernv/memtrace.c (c0000000000e0984)
Location: include/linux/nodemask.h:428
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/memtrace.c:memtrace_init_regions_runtime
```
```
In arch/powerpc/perf/imc-pmu.c (c00000000012d508)
Location: include/linux/nodemask.h:428
Inline: True
Inline callers:
  - arch/powerpc/perf/imc-pmu.c:init_imc_pmu
  - arch/powerpc/perf/imc-pmu.c:init_imc_pmu
```
```
In kernel/workqueue.c (c000000001366e5c)
Location: include/linux/nodemask.h:428
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_init
```
```
In kernel/smp.c (c00000000136ea00)
Location: include/linux/nodemask.h:428
Inline: True
Inline callers:
  - kernel/smp.c:smp_init
```
```
In mm/page_alloc.c (c000000001381770)
Location: include/linux/nodemask.h:428
Inline: True
Inline callers:
  - mm/page_alloc.c:page_alloc_init
```
```
In mm/mempolicy.c (c000000001383e60)
Location: include/linux/nodemask.h:428
Inline: True
Inline callers:
  - mm/mempolicy.c:numa_policy_init
```
```
In mm/memory_hotplug.c (c00000000042d5e4)
Location: include/linux/nodemask.h:428
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_node
  - mm/memory_hotplug.c:add_memory_resource
```
```
In security/apparmor/lsm.c (c00000000139a334)
Location: include/linux/nodemask.h:428
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_init
```
```
In drivers/md/dm.c (c000000000beb3f8)
Location: include/linux/nodemask.h:428
Inline: True
Inline callers:
  - drivers/md/dm.c:alloc_dev
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (0)
Location: include/linux/nodemask.h:477
Inline: True
```
```
In kernel/smp.c (0)
Location: include/linux/nodemask.h:477
Inline: True
```
```
In security/apparmor/lsm.c (0)
Location: include/linux/nodemask.h:477
Inline: True
```
```
In drivers/md/dm.c (0)
Location: include/linux/nodemask.h:477
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
In arch/x86/kernel/smpboot.c (ffffffff81064282)
Location: include/linux/nodemask.h:428
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:do_boot_cpu
```
```
In arch/x86/mm/numa.c (ffffffff828aeb1f)
Location: include/linux/nodemask.h:428
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:alloc_node_data
```
```
In kernel/workqueue.c (ffffffff828b45dc)
Location: include/linux/nodemask.h:428
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_init
```
```
In kernel/smp.c (ffffffff828ba232)
Location: include/linux/nodemask.h:428
Inline: True
Inline callers:
  - kernel/smp.c:smp_init
```
```
In mm/page_alloc.c (ffffffff828c8099)
Location: include/linux/nodemask.h:428
Inline: True
Inline callers:
  - mm/page_alloc.c:page_alloc_init
```
```
In mm/mempolicy.c (ffffffff828c9cba)
Location: include/linux/nodemask.h:428
Inline: True
Inline callers:
  - mm/mempolicy.c:numa_policy_init
```
```
In mm/memory_hotplug.c (ffffffff812a42cd)
Location: include/linux/nodemask.h:428
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_node
  - mm/memory_hotplug.c:add_memory_resource
```
```
In security/apparmor/lsm.c (ffffffff828da4f5)
Location: include/linux/nodemask.h:428
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_init
```
```
In drivers/nvme/host/core.c (ffffffff81746b15)
Location: include/linux/nodemask.h:428
Inline: True
Inline callers:
  - drivers/nvme/host/core.c:nvme_alloc_ns_head
```
```
In drivers/md/dm.c (ffffffff8184e795)
Location: include/linux/nodemask.h:428
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_get_numa_node
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff8186e6ab)
Location: include/linux/nodemask.h:428
Inline: True
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
In arch/x86/kernel/smpboot.c (ffffffff81054582)
Location: include/linux/nodemask.h:428
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:do_boot_cpu
```
```
In arch/x86/mm/numa.c (ffffffff828a6d11)
Location: include/linux/nodemask.h:428
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:alloc_node_data
```
```
In kernel/workqueue.c (ffffffff828ac75d)
Location: include/linux/nodemask.h:428
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_init
```
```
In kernel/smp.c (ffffffff828b28c5)
Location: include/linux/nodemask.h:428
Inline: True
Inline callers:
  - kernel/smp.c:smp_init
```
```
In mm/page_alloc.c (ffffffff828c07be)
Location: include/linux/nodemask.h:428
Inline: True
Inline callers:
  - mm/page_alloc.c:page_alloc_init
```
```
In mm/mempolicy.c (ffffffff828c23df)
Location: include/linux/nodemask.h:428
Inline: True
Inline callers:
  - mm/mempolicy.c:numa_policy_init
```
```
In mm/memory_hotplug.c (ffffffff81295d9d)
Location: include/linux/nodemask.h:428
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_node
  - mm/memory_hotplug.c:add_memory_resource
```
```
In security/apparmor/lsm.c (ffffffff828d2c11)
Location: include/linux/nodemask.h:428
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_init
```
```
In drivers/nvme/host/core.c (ffffffff81728795)
Location: include/linux/nodemask.h:428
Inline: True
Inline callers:
  - drivers/nvme/host/core.c:nvme_alloc_ns_head
```
```
In drivers/md/dm.c (ffffffff81815db5)
Location: include/linux/nodemask.h:428
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_get_numa_node
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff8183666b)
Location: include/linux/nodemask.h:428
Inline: True
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
In arch/x86/kernel/smpboot.c (ffffffff81064732)
Location: include/linux/nodemask.h:428
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:do_boot_cpu
```
```
In arch/x86/mm/numa.c (ffffffff828c1a1e)
Location: include/linux/nodemask.h:428
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:alloc_node_data
```
```
In kernel/workqueue.c (ffffffff828c74db)
Location: include/linux/nodemask.h:428
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_init
```
```
In kernel/smp.c (ffffffff828ccfb5)
Location: include/linux/nodemask.h:428
Inline: True
Inline callers:
  - kernel/smp.c:smp_init
```
```
In mm/page_alloc.c (ffffffff828dae19)
Location: include/linux/nodemask.h:428
Inline: True
Inline callers:
  - mm/page_alloc.c:page_alloc_init
```
```
In mm/mempolicy.c (ffffffff828dca3a)
Location: include/linux/nodemask.h:428
Inline: True
Inline callers:
  - mm/mempolicy.c:numa_policy_init
```
```
In mm/memory_hotplug.c (ffffffff812a20dd)
Location: include/linux/nodemask.h:428
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_node
  - mm/memory_hotplug.c:add_memory_resource
```
```
In security/apparmor/lsm.c (ffffffff828ed269)
Location: include/linux/nodemask.h:428
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_init
```
```
In drivers/md/dm.c (ffffffff8189ddc5)
Location: include/linux/nodemask.h:428
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_get_numa_node
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff818bf43b)
Location: include/linux/nodemask.h:428
Inline: True
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
In arch/x86/kernel/smpboot.c (ffffffff81065cf2)
Location: include/linux/nodemask.h:428
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:do_boot_cpu
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff828be122)
Location: include/linux/nodemask.h:428
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:build_socket_tables
  - arch/x86/kernel/apic/x2apic_uv_x.c:build_socket_tables
```
```
In arch/x86/mm/numa.c (ffffffff828c4b69)
Location: include/linux/nodemask.h:428
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:alloc_node_data
```
```
In kernel/workqueue.c (ffffffff828cc832)
Location: include/linux/nodemask.h:428
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_init
```
```
In kernel/smp.c (ffffffff828d23af)
Location: include/linux/nodemask.h:428
Inline: True
Inline callers:
  - kernel/smp.c:smp_init
```
```
In mm/page_alloc.c (ffffffff828e023a)
Location: include/linux/nodemask.h:428
Inline: True
Inline callers:
  - mm/page_alloc.c:page_alloc_init
```
```
In mm/mempolicy.c (ffffffff828e1e51)
Location: include/linux/nodemask.h:428
Inline: True
Inline callers:
  - mm/mempolicy.c:numa_policy_init
```
```
In mm/memory_hotplug.c (ffffffff812b236d)
Location: include/linux/nodemask.h:428
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_node
  - mm/memory_hotplug.c:add_memory_resource
```
```
In security/apparmor/lsm.c (ffffffff828f268b)
Location: include/linux/nodemask.h:428
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_init
```
```
In drivers/md/dm.c (ffffffff818ba175)
Location: include/linux/nodemask.h:428
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_get_numa_node
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff818db74b)
Location: include/linux/nodemask.h:428
Inline: True
```
</details>
</li>
</ul>

## Differences
