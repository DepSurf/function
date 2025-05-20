# Function: <code>register_memory_notifier</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int register_memory_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff81560e40)
Location: drivers/base/memory.c:53
Inline: False
Direct callers:
  - kernel/cpuset.c:cpuset_init_smp
  - mm/mm_init.c:mm_compute_batch_init
  - mm/mmap.c:init_reserve_notifier
  - mm/slub.c:kmem_cache_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/base/node.c:register_node_type
```
**Symbols:**

```
ffffffff81560e40-ffffffff81560e5a: register_memory_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int register_memory_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff815b5580)
Location: drivers/base/memory.c:53
Inline: False
Direct callers:
  - kernel/cpuset.c:cpuset_init_smp
  - mm/mm_init.c:mm_compute_batch_init
  - mm/mmap.c:init_reserve_notifier
  - mm/slub.c:kmem_cache_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/base/node.c:register_node_type
```
**Symbols:**

```
ffffffff815b5580-ffffffff815b559a: register_memory_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int register_memory_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff815e4860)
Location: drivers/base/memory.c:53
Inline: False
Direct callers:
  - kernel/cpuset.c:cpuset_init_smp
  - mm/mm_init.c:mm_compute_batch_init
  - mm/mmap.c:init_reserve_notifier
  - mm/slub.c:kmem_cache_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/base/node.c:register_node_type
```
**Symbols:**

```
ffffffff815e4860-ffffffff815e487a: register_memory_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int register_memory_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff815f9440)
Location: drivers/base/memory.c:53
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_init_smp
  - mm/mm_init.c:mm_compute_batch_init
  - mm/mmap.c:init_reserve_notifier
  - mm/slub.c:kmem_cache_init
  - fs/proc/kcore.c:proc_kcore_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/base/node.c:register_node_type
```
**Symbols:**

```
ffffffff815f9440-ffffffff815f945a: register_memory_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int register_memory_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff81661570)
Location: drivers/base/memory.c:54
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_init_smp
  - mm/mm_init.c:mm_compute_batch_init
  - mm/mmap.c:init_reserve_notifier
  - mm/slub.c:kmem_cache_init
  - fs/proc/kcore.c:proc_kcore_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/base/node.c:register_node_type
```
**Symbols:**

```
ffffffff81661570-ffffffff8166158a: register_memory_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int register_memory_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff8169cd30)
Location: drivers/base/memory.c:54
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_init_smp
  - mm/mm_init.c:mm_compute_batch_init
  - mm/mmap.c:init_reserve_notifier
  - mm/ksm.c:ksm_init
  - mm/slub.c:kmem_cache_init
  - fs/proc/kcore.c:proc_kcore_init
  - drivers/xen/balloon.c:balloon_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/base/node.c:register_node_type
```
**Symbols:**

```
ffffffff8169cd30-ffffffff8169cd4a: register_memory_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int register_memory_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff816bd4e0)
Location: drivers/base/memory.c:54
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_init_smp
  - mm/mm_init.c:mm_compute_batch_init
  - mm/mmap.c:init_reserve_notifier
  - mm/ksm.c:ksm_init
  - mm/slub.c:kmem_cache_init
  - fs/proc/kcore.c:proc_kcore_init
  - drivers/xen/balloon.c:balloon_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/base/node.c:register_node_type
```
**Symbols:**

```
ffffffff816bd4e0-ffffffff816bd4fa: register_memory_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int register_memory_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff816f8320)
Location: drivers/base/memory.c:64
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_init_smp
  - mm/mm_init.c:mm_compute_batch_init
  - mm/mmap.c:init_reserve_notifier
  - mm/ksm.c:ksm_init
  - mm/slub.c:kmem_cache_init
  - fs/proc/kcore.c:proc_kcore_init
  - drivers/xen/balloon.c:balloon_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/base/node.c:register_node_type
```
**Symbols:**

```
ffffffff816f8320-ffffffff816f833a: register_memory_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int register_memory_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff8171c740)
Location: drivers/base/memory.c:64
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_init_smp
  - mm/mm_init.c:mm_compute_batch_init
  - mm/mmap.c:init_reserve_notifier
  - mm/ksm.c:ksm_init
  - mm/slub.c:kmem_cache_init
  - fs/proc/kcore.c:proc_kcore_init
  - drivers/acpi/hmat/hmat.c:hmat_init
  - drivers/xen/balloon.c:balloon_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/base/node.c:register_node_type
```
**Symbols:**

```
ffffffff8171c740-ffffffff8171c75a: register_memory_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int register_memory_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff817d8830)
Location: drivers/base/memory.c:87
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_init_smp
  - mm/mm_init.c:mm_compute_batch_init
  - mm/mmap.c:init_reserve_notifier
  - mm/ksm.c:ksm_init
  - mm/slub.c:kmem_cache_init
  - fs/proc/kcore.c:proc_kcore_init
  - drivers/acpi/numa/hmat.c:hmat_init
  - drivers/xen/balloon.c:balloon_init
  - drivers/iommu/intel/iommu.c:intel_iommu_init
  - drivers/base/node.c:register_node_type
```
**Symbols:**

```
ffffffff817d8830-ffffffff817d884a: register_memory_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int register_memory_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff817ed230)
Location: drivers/base/memory.c:87
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_init_smp
  - mm/mm_init.c:mm_compute_batch_init
  - mm/mmap.c:init_reserve_notifier
  - mm/ksm.c:ksm_init
  - mm/slub.c:kmem_cache_init
  - fs/proc/kcore.c:proc_kcore_init
  - drivers/acpi/numa/hmat.c:hmat_init
  - drivers/xen/balloon.c:balloon_init
  - drivers/iommu/intel/iommu.c:intel_iommu_init
  - drivers/base/node.c:register_node_type
```
**Symbols:**

```
ffffffff817ed230-ffffffff817ed24a: register_memory_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int register_memory_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff817d1a00)
Location: drivers/base/memory.c:87
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_init_smp
  - mm/mm_init.c:mm_compute_batch_init
  - mm/mmap.c:init_reserve_notifier
  - mm/ksm.c:ksm_init
  - mm/slub.c:kmem_cache_init
  - fs/proc/kcore.c:proc_kcore_init
  - drivers/acpi/numa/hmat.c:hmat_init
  - drivers/xen/balloon.c:balloon_init
  - drivers/iommu/intel/iommu.c:intel_iommu_init
  - drivers/base/node.c:register_node_type
```
**Symbols:**

```
ffffffff817d1a00-ffffffff817d1a1a: register_memory_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int register_memory_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff8185c7a0)
Location: drivers/base/memory.c:93
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_init_smp
  - mm/mm_init.c:mm_compute_batch_init
  - mm/mmap.c:init_reserve_notifier
  - mm/ksm.c:ksm_init
  - mm/slub.c:kmem_cache_init
  - mm/migrate.c:migrate_on_reclaim_init
  - fs/proc/kcore.c:proc_kcore_init
  - drivers/acpi/numa/hmat.c:hmat_init
  - drivers/xen/balloon.c:balloon_init
  - drivers/iommu/intel/iommu.c:intel_iommu_init
  - drivers/base/node.c:register_node_type
```
**Symbols:**

```
ffffffff8185c7a0-ffffffff8185c7ba: register_memory_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int register_memory_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff819a3940)
Location: drivers/base/memory.c:93
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_init_smp
  - mm/mm_init.c:mm_compute_batch_init
  - mm/mmap.c:init_reserve_notifier
  - mm/ksm.c:ksm_init
  - mm/slub.c:kmem_cache_init
  - mm/migrate.c:migrate_on_reclaim_init
  - fs/proc/kcore.c:proc_kcore_init
  - drivers/acpi/numa/hmat.c:hmat_init
  - drivers/xen/balloon.c:balloon_init
  - drivers/iommu/intel/iommu.c:intel_iommu_init
  - drivers/base/node.c:node_dev_init
```
**Symbols:**

```
ffffffff819a3940-ffffffff819a3962: register_memory_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int register_memory_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff81b15830)
Location: drivers/base/memory.c:93
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_init_smp
  - mm/mm_init.c:mm_compute_batch_init
  - mm/mmap.c:init_reserve_notifier
  - mm/ksm.c:ksm_init
  - mm/slub.c:kmem_cache_init
  - mm/memory-tiers.c:memory_tier_init
  - fs/proc/kcore.c:proc_kcore_init
  - drivers/acpi/numa/hmat.c:hmat_init
  - drivers/xen/balloon.c:balloon_init
  - drivers/iommu/intel/iommu.c:intel_iommu_init
```
**Symbols:**

```
ffffffff81b15830-ffffffff81b15852: register_memory_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int register_memory_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff81b645a0)
Location: drivers/base/memory.c:93
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_init_smp
  - mm/mm_init.c:mm_compute_batch_init
  - mm/mmap.c:init_reserve_notifier
  - mm/ksm.c:ksm_init
  - mm/slub.c:kmem_cache_init
  - mm/memory-tiers.c:memory_tier_init
  - fs/proc/kcore.c:proc_kcore_init
  - drivers/acpi/numa/hmat.c:hmat_init
  - drivers/xen/balloon.c:balloon_init
  - drivers/iommu/intel/iommu.c:intel_iommu_init
```
**Symbols:**

```
ffffffff81b645a0-ffffffff81b645c2: register_memory_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int register_memory_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff81bb8120)
Location: drivers/base/memory.c:93
Inline: False
Direct callers:
  - kernel/crash_core.c:crash_hotplug_init
  - kernel/cgroup/cpuset.c:cpuset_init_smp
  - mm/mm_init.c:mm_compute_batch_init
  - mm/mmap.c:init_reserve_notifier
  - mm/slub.c:kmem_cache_init
  - mm/ksm.c:ksm_init
  - mm/memory-tiers.c:memory_tier_init
  - fs/proc/kcore.c:proc_kcore_init
  - drivers/acpi/numa/hmat.c:hmat_init
  - drivers/xen/balloon.c:balloon_init
  - drivers/iommu/intel/iommu.c:intel_iommu_init
```
**Symbols:**

```
ffffffff81bb8120-ffffffff81bb8142: register_memory_notifier (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int register_memory_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffff8000109103b8)
Location: drivers/base/memory.c:64
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_init_smp
  - mm/mm_init.c:mm_compute_batch_init
  - mm/mmap.c:init_reserve_notifier
  - mm/slub.c:kmem_cache_init
  - fs/proc/kcore.c:proc_kcore_init
  - drivers/acpi/hmat/hmat.c:hmat_init
  - drivers/xen/balloon.c:balloon_init
  - drivers/base/node.c:register_node_type
```
**Symbols:**

```
ffff8000109103b8-ffff8000109103ec: register_memory_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int register_memory_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (c0000000009b10d0)
Location: drivers/base/memory.c:64
Inline: False
Direct callers:
  - arch/powerpc/platforms/pseries/iommu.c:iommu_init_early_pSeries
  - kernel/cgroup/cpuset.c:cpuset_init_smp
  - mm/mm_init.c:mm_compute_batch_init
  - mm/mmap.c:init_reserve_notifier
  - mm/ksm.c:ksm_init
  - mm/slub.c:kmem_cache_init
  - fs/proc/kcore.c:proc_kcore_init
  - drivers/base/node.c:register_node_type
```
**Symbols:**

```
c0000000009b10d0-c0000000009b1110: register_memory_notifier (STB_GLOBAL)
```
</details>
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
int register_memory_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff816e2a70)
Location: drivers/base/memory.c:64
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_init_smp
  - mm/mm_init.c:mm_compute_batch_init
  - mm/mmap.c:init_reserve_notifier
  - mm/ksm.c:ksm_init
  - mm/slub.c:kmem_cache_init
  - fs/proc/kcore.c:proc_kcore_init
  - drivers/acpi/hmat/hmat.c:hmat_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/base/node.c:register_node_type
```
**Symbols:**

```
ffffffff816e2a70-ffffffff816e2a8a: register_memory_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int register_memory_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff816bd0b0)
Location: drivers/base/memory.c:64
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_init_smp
  - mm/mm_init.c:mm_compute_batch_init
  - mm/mmap.c:init_reserve_notifier
  - mm/ksm.c:ksm_init
  - mm/slub.c:kmem_cache_init
  - fs/proc/kcore.c:proc_kcore_init
  - drivers/acpi/hmat/hmat.c:hmat_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/base/node.c:register_node_type
```
**Symbols:**

```
ffffffff816bd0b0-ffffffff816bd0ca: register_memory_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int register_memory_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff8170fc00)
Location: drivers/base/memory.c:64
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_init_smp
  - mm/mm_init.c:mm_compute_batch_init
  - mm/mmap.c:init_reserve_notifier
  - mm/ksm.c:ksm_init
  - mm/slub.c:kmem_cache_init
  - fs/proc/kcore.c:proc_kcore_init
  - drivers/xen/balloon.c:balloon_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/base/node.c:register_node_type
```
**Symbols:**

```
ffffffff8170fc00-ffffffff8170fc1a: register_memory_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int register_memory_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff8172ad60)
Location: drivers/base/memory.c:64
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_init_smp
  - mm/mm_init.c:mm_compute_batch_init
  - mm/mmap.c:init_reserve_notifier
  - mm/ksm.c:ksm_init
  - mm/slub.c:kmem_cache_init
  - fs/proc/kcore.c:proc_kcore_init
  - drivers/acpi/hmat/hmat.c:hmat_init
  - drivers/xen/balloon.c:balloon_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/base/node.c:register_node_type
```
**Symbols:**

```
ffffffff8172ad60-ffffffff8172ad7a: register_memory_notifier (STB_GLOBAL)
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
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
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
