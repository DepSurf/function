# Function: <code>atomic_long_inc_return</code>

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
In mm/backing-dev.c (ffffffff811afa75)
Location: include/asm-generic/atomic-long.h:169
Inline: True
```
```
In mm/workingset.c (ffffffff811b9e40)
Location: include/asm-generic/atomic-long.h:169
Inline: True
Inline callers:
  - mm/workingset.c:workingset_eviction
```
```
In net/unix/garbage.c (ffffffff817c233e)
Location: include/asm-generic/atomic-long.h:169
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_inflight
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
In mm/backing-dev.c (ffffffff811c8f13)
Location: include/asm-generic/atomic-long.h:225
Inline: True
```
```
In mm/workingset.c (ffffffff811d4212)
Location: include/asm-generic/atomic-long.h:225
Inline: True
Inline callers:
  - mm/workingset.c:workingset_eviction
```
```
In net/unix/garbage.c (ffffffff8182f35e)
Location: include/asm-generic/atomic-long.h:225
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_inflight
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
In mm/backing-dev.c (ffffffff811d8ff3)
Location: include/asm-generic/atomic-long.h:225
Inline: True
```
```
In mm/workingset.c (ffffffff811e4252)
Location: include/asm-generic/atomic-long.h:225
Inline: True
Inline callers:
  - mm/workingset.c:workingset_eviction
```
```
In net/unix/garbage.c (ffffffff81860dde)
Location: include/asm-generic/atomic-long.h:225
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_inflight
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
In mm/workingset.c (ffffffff811ee625)
Location: include/asm-generic/atomic-long.h:225
Inline: True
Inline callers:
  - mm/workingset.c:workingset_eviction
```
```
In fs/super.c (ffffffff81253c06)
Location: include/asm-generic/atomic-long.h:225
Inline: True
Inline callers:
  - fs/super.c:super_setup_bdi
```
```
In net/unix/garbage.c (ffffffff8188553e)
Location: include/asm-generic/atomic-long.h:225
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_inflight
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
In mm/workingset.c (ffffffff81204a95)
Location: include/asm-generic/atomic-long.h:226
Inline: True
Inline callers:
  - mm/workingset.c:workingset_eviction
```
```
In fs/super.c (ffffffff81275c86)
Location: include/asm-generic/atomic-long.h:226
Inline: True
Inline callers:
  - fs/super.c:super_setup_bdi
```
```
In net/unix/garbage.c (ffffffff819066ee)
Location: include/asm-generic/atomic-long.h:226
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_inflight
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
In mm/workingset.c (ffffffff81225845)
Location: include/asm-generic/atomic-long.h:243
Inline: True
Inline callers:
  - mm/workingset.c:workingset_eviction
```
```
In fs/super.c (ffffffff8129c1e5)
Location: include/asm-generic/atomic-long.h:243
Inline: True
Inline callers:
  - fs/super.c:super_setup_bdi
```
```
In net/unix/garbage.c (ffffffff8195d6b9)
Location: include/asm-generic/atomic-long.h:243
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_inflight
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
In mm/workingset.c (ffffffff81238dc6)
Location: include/asm-generic/atomic-long.h:243
Inline: True
Inline callers:
  - mm/workingset.c:workingset_eviction
```
```
In fs/super.c (ffffffff812b1325)
Location: include/asm-generic/atomic-long.h:243
Inline: True
Inline callers:
  - fs/super.c:super_setup_bdi
```
```
In net/unix/garbage.c (ffffffff819921f9)
Location: include/asm-generic/atomic-long.h:243
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_inflight
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
In mm/workingset.c (ffffffff81249fca)
Location: include/asm-generic/atomic-long.h:164
Inline: True
Inline callers:
  - mm/workingset.c:workingset_eviction
```
```
In fs/super.c (ffffffff812cddb5)
Location: include/asm-generic/atomic-long.h:164
Inline: True
Inline callers:
  - fs/super.c:super_setup_bdi
```
```
In net/unix/scm.c (ffffffff819fdebb)
Location: include/asm-generic/atomic-long.h:164
Inline: True
Inline callers:
  - net/unix/scm.c:unix_inflight
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
In mm/workingset.c (ffffffff81258419)
Location: include/asm-generic/atomic-long.h:164
Inline: True
Inline callers:
  - mm/workingset.c:workingset_eviction
```
```
In fs/super.c (ffffffff812df7e5)
Location: include/asm-generic/atomic-long.h:164
Inline: True
Inline callers:
  - fs/super.c:super_setup_bdi
```
```
In net/unix/scm.c (ffffffff81a34aab)
Location: include/asm-generic/atomic-long.h:164
Inline: True
Inline callers:
  - net/unix/scm.c:unix_inflight
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
In kernel/events/uprobes.c (ffffffff81246dad)
Location: include/asm-generic/atomic-long.h:165
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/shmem.c (ffffffff8126e8ed)
Location: include/asm-generic/atomic-long.h:165
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/rmap.c (ffffffff812a5981)
Location: include/asm-generic/atomic-long.h:165
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/swapfile.c (ffffffff812bbc5f)
Location: include/asm-generic/atomic-long.h:165
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte
```
```
In mm/migrate.c (ffffffff812e5357)
Location: include/asm-generic/atomic-long.h:165
Inline: True
```
```
In mm/userfaultfd.c (ffffffff81308207)
Location: include/asm-generic/atomic-long.h:165
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic_pte
```
```
In fs/super.c (ffffffff81316595)
Location: include/asm-generic/atomic-long.h:165
Inline: True
Inline callers:
  - fs/super.c:super_setup_bdi
```
```
In net/unix/scm.c (ffffffff81b298eb)
Location: include/asm-generic/atomic-long.h:165
Inline: True
Inline callers:
  - net/unix/scm.c:unix_inflight
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
In kernel/events/uprobes.c (ffffffff8125141a)
Location: include/asm-generic/atomic-long.h:165
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/shmem.c (ffffffff812792e7)
Location: include/asm-generic/atomic-long.h:165
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/rmap.c (ffffffff812b0dfb)
Location: include/asm-generic/atomic-long.h:165
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/swapfile.c (ffffffff812c770f)
Location: include/asm-generic/atomic-long.h:165
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte
```
```
In mm/migrate.c (ffffffff812f0720)
Location: include/asm-generic/atomic-long.h:165
Inline: True
```
```
In mm/userfaultfd.c (ffffffff81313fa9)
Location: include/asm-generic/atomic-long.h:165
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic_pte
```
```
In fs/super.c (ffffffff81321ab5)
Location: include/asm-generic/atomic-long.h:165
Inline: True
Inline callers:
  - fs/super.c:super_setup_bdi
```
```
In net/unix/scm.c (ffffffff81b3821b)
Location: include/asm-generic/atomic-long.h:165
Inline: True
Inline callers:
  - net/unix/scm.c:unix_inflight
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
In kernel/events/uprobes.c (ffffffff81255522)
Location: include/asm-generic/atomic-long.h:165
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/shmem.c (ffffffff8127e2d3)
Location: include/asm-generic/atomic-long.h:165
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/rmap.c (ffffffff812b6448)
Location: include/asm-generic/atomic-long.h:165
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/swapfile.c (ffffffff812ce088)
Location: include/asm-generic/atomic-long.h:165
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte
```
```
In mm/migrate.c (ffffffff812f6ae9)
Location: include/asm-generic/atomic-long.h:165
Inline: True
```
```
In mm/userfaultfd.c (ffffffff8131a168)
Location: include/asm-generic/atomic-long.h:165
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic_pte
```
```
In fs/super.c (ffffffff81327b45)
Location: include/asm-generic/atomic-long.h:165
Inline: True
Inline callers:
  - fs/super.c:super_setup_bdi
```
```
In net/unix/scm.c (ffffffff81b25ebb)
Location: include/asm-generic/atomic-long.h:165
Inline: True
Inline callers:
  - net/unix/scm.c:unix_inflight
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
In kernel/events/uprobes.c (ffffffff81290f63)
Location: include/linux/atomic/atomic-instrumented.h:1342
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/rmap.c (ffffffff812f7e74)
Location: include/linux/atomic/atomic-instrumented.h:1342
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/swapfile.c (ffffffff81313508)
Location: include/linux/atomic/atomic-instrumented.h:1342
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte
```
```
In mm/migrate.c (ffffffff81341145)
Location: include/linux/atomic/atomic-instrumented.h:1342
Inline: True
```
```
In mm/userfaultfd.c (ffffffff81366e6c)
Location: include/linux/atomic/atomic-instrumented.h:1342
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_atomic_install_pte
```
```
In fs/super.c (ffffffff81375115)
Location: include/linux/atomic/atomic-instrumented.h:1342
Inline: True
Inline callers:
  - fs/super.c:super_setup_bdi
```
```
In net/unix/scm.c (ffffffff81bebb0b)
Location: include/linux/atomic/atomic-instrumented.h:1342
Inline: True
Inline callers:
  - net/unix/scm.c:unix_inflight
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
In kernel/events/uprobes.c (ffffffff812e635e)
Location: include/linux/atomic/atomic-instrumented.h:1433
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/rmap.c (ffffffff8135dc19)
Location: include/linux/atomic/atomic-instrumented.h:1433
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/swapfile.c (ffffffff8137e9de)
Location: include/linux/atomic/atomic-instrumented.h:1433
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte
```
```
In mm/migrate_device.c (ffffffff813b7f58)
Location: include/linux/atomic/atomic-instrumented.h:1433
Inline: True
```
```
In mm/userfaultfd.c (ffffffff813e4352)
Location: include/linux/atomic/atomic-instrumented.h:1433
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_atomic_install_pte
```
```
In fs/super.c (ffffffff813f4405)
Location: include/linux/atomic/atomic-instrumented.h:1433
Inline: True
Inline callers:
  - fs/super.c:super_setup_bdi
```
```
In net/unix/scm.c (ffffffff81d83feb)
Location: include/linux/atomic/atomic-instrumented.h:1433
Inline: True
Inline callers:
  - net/unix/scm.c:unix_inflight
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
In fs/super.c (ffffffff8147d4d5)
Location: include/linux/atomic/atomic-instrumented.h:1433
Inline: True
Inline callers:
  - fs/super.c:super_setup_bdi
```
```
In net/unix/scm.c (ffffffff81f5186b)
Location: include/linux/atomic/atomic-instrumented.h:1433
Inline: True
Inline callers:
  - net/unix/scm.c:unix_inflight
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
In fs/super.c (ffffffff814b2295)
Location: include/linux/atomic/atomic-instrumented.h:3578
Inline: True
Inline callers:
  - fs/super.c:super_setup_bdi
```
```
In net/unix/scm.c (ffffffff81fb11eb)
Location: include/linux/atomic/atomic-instrumented.h:3578
Inline: True
Inline callers:
  - net/unix/scm.c:unix_inflight
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
In mm/zswap.c (ffffffff8146f60b)
Location: include/linux/atomic/atomic-instrumented.h:3578
Inline: True
Inline callers:
  - mm/zswap.c:zswap_lru_add
```
```
In fs/super.c (ffffffff814e38f5)
Location: include/linux/atomic/atomic-instrumented.h:3578
Inline: True
Inline callers:
  - fs/super.c:super_setup_bdi
```
```
In net/unix/scm.c (ffffffff8207e8fb)
Location: include/linux/atomic/atomic-instrumented.h:3578
Inline: True
Inline callers:
  - net/unix/scm.c:unix_inflight
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
In kernel/events/core.c (ffff80001029f160)
Location: include/asm-generic/atomic-long.h:164
Inline: True
Inline callers:
  - kernel/events/core.c:perf_output_sample
```
```
In mm/workingset.c (ffff8000102f01f8)
Location: include/asm-generic/atomic-long.h:164
Inline: True
Inline callers:
  - mm/workingset.c:workingset_eviction
```
```
In fs/super.c (ffff8000103863b8)
Location: include/asm-generic/atomic-long.h:164
Inline: True
Inline callers:
  - fs/super.c:super_setup_bdi
```
```
In net/unix/scm.c (ffff800010cf527c)
Location: include/asm-generic/atomic-long.h:164
Inline: True
Inline callers:
  - net/unix/scm.c:unix_inflight
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
In kernel/events/core.c (c04cea78)
Location: include/asm-generic/atomic-long.h:658
Inline: True
Inline callers:
  - kernel/events/core.c:perf_output_sample
```
```
In mm/workingset.c (c0513914)
Location: include/asm-generic/atomic-long.h:658
Inline: True
Inline callers:
  - mm/workingset.c:workingset_eviction
```
```
In fs/super.c (c056f174)
Location: include/asm-generic/atomic-long.h:658
Inline: True
Inline callers:
  - fs/super.c:super_setup_bdi
```
```
In net/unix/scm.c (c0dfbda4)
Location: include/asm-generic/atomic-long.h:658
Inline: True
Inline callers:
  - net/unix/scm.c:unix_inflight
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
In mm/workingset.c (c0000000003b4ba8)
Location: include/asm-generic/atomic-long.h:164
Inline: True
Inline callers:
  - mm/workingset.c:workingset_eviction
```
```
In fs/super.c (c00000000047c7a4)
Location: include/asm-generic/atomic-long.h:164
Inline: True
Inline callers:
  - fs/super.c:super_setup_bdi
```
```
In net/unix/scm.c (c000000000e1b370)
Location: include/asm-generic/atomic-long.h:164
Inline: True
Inline callers:
  - net/unix/scm.c:unix_inflight
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
In kernel/events/core.c (ffffffe0001ce742)
Location: include/asm-generic/atomic-long.h:164
Inline: True
Inline callers:
  - kernel/events/core.c:perf_output_sample
```
```
In mm/workingset.c (ffffffe000203c0c)
Location: include/asm-generic/atomic-long.h:164
Inline: True
Inline callers:
  - mm/workingset.c:workingset_eviction
```
```
In fs/super.c (ffffffe000258ce6)
Location: include/asm-generic/atomic-long.h:164
Inline: True
Inline callers:
  - fs/super.c:super_setup_bdi
```
```
In net/unix/scm.c (ffffffe000840dcc)
Location: include/asm-generic/atomic-long.h:164
Inline: True
Inline callers:
  - net/unix/scm.c:unix_inflight
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
In mm/workingset.c (ffffffff81250a69)
Location: include/asm-generic/atomic-long.h:164
Inline: True
Inline callers:
  - mm/workingset.c:workingset_eviction
```
```
In fs/super.c (ffffffff812d7dc5)
Location: include/asm-generic/atomic-long.h:164
Inline: True
Inline callers:
  - fs/super.c:super_setup_bdi
```
```
In net/unix/scm.c (ffffffff819d413b)
Location: include/asm-generic/atomic-long.h:164
Inline: True
Inline callers:
  - net/unix/scm.c:unix_inflight
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
In mm/workingset.c (ffffffff812439e9)
Location: include/asm-generic/atomic-long.h:164
Inline: True
Inline callers:
  - mm/workingset.c:workingset_eviction
```
```
In fs/super.c (ffffffff812c8a45)
Location: include/asm-generic/atomic-long.h:164
Inline: True
Inline callers:
  - fs/super.c:super_setup_bdi
```
```
In net/unix/scm.c (ffffffff81990efb)
Location: include/asm-generic/atomic-long.h:164
Inline: True
Inline callers:
  - net/unix/scm.c:unix_inflight
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
In mm/workingset.c (ffffffff8124e809)
Location: include/asm-generic/atomic-long.h:164
Inline: True
Inline callers:
  - mm/workingset.c:workingset_eviction
```
```
In fs/super.c (ffffffff812d5bd5)
Location: include/asm-generic/atomic-long.h:164
Inline: True
Inline callers:
  - fs/super.c:super_setup_bdi
```
```
In net/unix/scm.c (ffffffff81a3ebbb)
Location: include/asm-generic/atomic-long.h:164
Inline: True
Inline callers:
  - net/unix/scm.c:unix_inflight
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
In mm/workingset.c (ffffffff8125e179)
Location: include/asm-generic/atomic-long.h:164
Inline: True
Inline callers:
  - mm/workingset.c:workingset_eviction
```
```
In fs/super.c (ffffffff812e6be5)
Location: include/asm-generic/atomic-long.h:164
Inline: True
Inline callers:
  - fs/super.c:super_setup_bdi
```
```
In net/unix/scm.c (ffffffff81a4a67b)
Location: include/asm-generic/atomic-long.h:164
Inline: True
Inline callers:
  - net/unix/scm.c:unix_inflight
```
</details>
</li>
</ul>

## Differences
