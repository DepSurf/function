# Function: <code>mem_cgroup_put</code>

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
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff81205dec)
Location: include/linux/memcontrol.h:407
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
```
```
In fs/buffer.c (ffffffff812ebecf)
Location: include/linux/memcontrol.h:407
Inline: True
Inline callers:
  - fs/buffer.c:alloc_page_buffers
```
```
In fs/notify/group.c (ffffffff812f9c54)
Location: include/linux/memcontrol.h:407
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_put_group
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
In mm/oom_kill.c (ffffffff8121c354)
Location: include/linux/memcontrol.h:408
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
```
```
In mm/slab_common.c (ffffffff81240dca)
Location: include/linux/memcontrol.h:408
Inline: True
```
```
In fs/buffer.c (ffffffff8130d605)
Location: include/linux/memcontrol.h:408
Inline: True
Inline callers:
  - fs/buffer.c:alloc_page_buffers
```
```
In fs/notify/group.c (ffffffff8131a304)
Location: include/linux/memcontrol.h:408
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_put_group
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
In mm/oom_kill.c (ffffffff81229d24)
Location: include/linux/memcontrol.h:442
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
```
```
In mm/slab_common.c (ffffffff8124f31e)
Location: include/linux/memcontrol.h:442
Inline: True
Inline callers:
  - mm/slab_common.c:destroy_memcg_params
```
```
In fs/buffer.c (ffffffff813205d5)
Location: include/linux/memcontrol.h:442
Inline: True
Inline callers:
  - fs/buffer.c:alloc_page_buffers
```
```
In fs/notify/group.c (ffffffff8132d124)
Location: include/linux/memcontrol.h:442
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_put_group
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
In mm/oom_kill.c (ffffffff81256b94)
Location: include/linux/memcontrol.h:419
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
```
```
In mm/slab_common.c (ffffffff8127d2fe)
Location: include/linux/memcontrol.h:419
Inline: True
Inline callers:
  - mm/slab_common.c:destroy_memcg_params
```
```
In fs/buffer.c (ffffffff81359a32)
Location: include/linux/memcontrol.h:419
Inline: True
Inline callers:
  - fs/buffer.c:alloc_page_buffers
```
```
In fs/notify/group.c (ffffffff81366e97)
Location: include/linux/memcontrol.h:419
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_final_destroy_group
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
In kernel/bpf/syscall.c (ffffffff811fb612)
Location: include/linux/memcontrol.h:739
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_map_free_deferred
```
```
In mm/oom_kill.c (ffffffff812617a4)
Location: include/linux/memcontrol.h:739
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
```
```
In mm/memcontrol.c (ffffffff81304324)
Location: include/linux/memcontrol.h:739
Inline: True
Inline callers:
  - mm/memcontrol.c:obj_cgroup_release
```
```
In fs/buffer.c (ffffffff81367b1b)
Location: include/linux/memcontrol.h:739
Inline: True
Inline callers:
  - fs/buffer.c:alloc_page_buffers
```
```
In fs/notify/group.c (ffffffff813741e7)
Location: include/linux/memcontrol.h:739
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_final_destroy_group
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
In kernel/bpf/syscall.c (ffffffff811fc332)
Location: include/linux/memcontrol.h:818
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_map_free_deferred
```
```
In mm/oom_kill.c (ffffffff81265fd4)
Location: include/linux/memcontrol.h:818
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
```
```
In mm/memcontrol.c (ffffffff8130c0a5)
Location: include/linux/memcontrol.h:818
Inline: True
Inline callers:
  - mm/memcontrol.c:obj_cgroup_release
```
```
In fs/notify/group.c (ffffffff8137ab80)
Location: include/linux/memcontrol.h:818
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_put_group
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
In kernel/bpf/syscall.c (ffffffff8122dc62)
Location: include/linux/memcontrol.h:814
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_map_free_deferred
```
```
In mm/oom_kill.c (ffffffff812a27f4)
Location: include/linux/memcontrol.h:814
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
```
```
In fs/notify/group.c (ffffffff813c7860)
Location: include/linux/memcontrol.h:814
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_put_group
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
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8107e875)
Location: include/linux/memcontrol.h:815
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_alloc_backing
```
```
In kernel/bpf/syscall.c (ffffffff8126ff2d)
Location: include/linux/memcontrol.h:815
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_map_free_deferred
```
```
In mm/oom_kill.c (ffffffff812fa475)
Location: include/linux/memcontrol.h:815
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
```
```
In mm/memcontrol.c (ffffffff813d5c2c)
Location: include/linux/memcontrol.h:815
Inline: True
Inline callers:
  - mm/memcontrol.c:obj_cgroup_may_zswap
```
```
In fs/notify/group.c (ffffffff8144ec49)
Location: include/linux/memcontrol.h:815
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_put_group
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
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8108feb5)
Location: include/linux/memcontrol.h:797
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_alloc_backing
```
```
In kernel/bpf/syscall.c (ffffffff812c91d8)
Location: include/linux/memcontrol.h:797
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_map_alloc_percpu
  - kernel/bpf/syscall.c:bpf_map_kzalloc
  - kernel/bpf/syscall.c:bpf_map_kmalloc_node
```
```
In kernel/bpf/memalloc.c (ffffffff8131bdf6)
Location: include/linux/memcontrol.h:797
Inline: True
Inline callers:
  - kernel/bpf/memalloc.c:alloc_bulk
```
```
In mm/oom_kill.c (ffffffff81364be5)
Location: include/linux/memcontrol.h:797
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
```
```
In mm/vmscan.c (ffffffff8138239a)
Location: include/linux/memcontrol.h:797
Inline: True
Inline callers:
  - mm/vmscan.c:run_cmd
  - mm/vmscan.c:lru_gen_del_mm
```
```
In mm/memcontrol.c (ffffffff8145b613)
Location: include/linux/memcontrol.h:797
Inline: True
Inline callers:
  - mm/memcontrol.c:obj_cgroup_may_zswap
```
```
In fs/notify/group.c (ffffffff814dd3e9)
Location: include/linux/memcontrol.h:797
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_put_group
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
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81092dcb)
Location: include/linux/memcontrol.h:815
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_alloc_backing
```
```
In kernel/bpf/syscall.c (ffffffff812f08f8)
Location: include/linux/memcontrol.h:815
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_map_alloc_percpu
  - kernel/bpf/syscall.c:bpf_map_kvcalloc
  - kernel/bpf/syscall.c:bpf_map_kzalloc
  - kernel/bpf/syscall.c:bpf_map_kmalloc_node
```
```
In kernel/bpf/memalloc.c (ffffffff8134c4a1)
Location: include/linux/memcontrol.h:815
Inline: True
Inline callers:
  - kernel/bpf/memalloc.c:bpf_mem_cache_alloc_flags
  - kernel/bpf/memalloc.c:alloc_bulk
```
```
In mm/oom_kill.c (ffffffff813970a5)
Location: include/linux/memcontrol.h:815
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
```
```
In mm/vmscan.c (ffffffff813b3f19)
Location: include/linux/memcontrol.h:815
Inline: True
Inline callers:
  - mm/vmscan.c:run_cmd
  - mm/vmscan.c:shrink_many
  - mm/vmscan.c:shrink_many
  - mm/vmscan.c:lru_gen_del_mm
```
```
In mm/memcontrol.c (ffffffff81491283)
Location: include/linux/memcontrol.h:815
Inline: True
Inline callers:
  - mm/memcontrol.c:obj_cgroup_may_zswap
```
```
In fs/notify/group.c (ffffffff81513c49)
Location: include/linux/memcontrol.h:815
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_put_group
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
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8109a20b)
Location: include/linux/memcontrol.h:835
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_alloc_backing
```
```
In kernel/bpf/syscall.c (ffffffff8130f6d8)
Location: include/linux/memcontrol.h:835
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_map_alloc_percpu
  - kernel/bpf/syscall.c:bpf_map_kvcalloc
  - kernel/bpf/syscall.c:bpf_map_kzalloc
  - kernel/bpf/syscall.c:bpf_map_kmalloc_node
```
```
In kernel/bpf/memalloc.c (ffffffff81373a2f)
Location: include/linux/memcontrol.h:835
Inline: True
Inline callers:
  - kernel/bpf/memalloc.c:bpf_mem_cache_alloc_flags
  - kernel/bpf/memalloc.c:alloc_bulk
```
```
In mm/oom_kill.c (ffffffff813c0e19)
Location: include/linux/memcontrol.h:835
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
```
```
In mm/vmscan.c (ffffffff813dd599)
Location: include/linux/memcontrol.h:835
Inline: True
Inline callers:
  - mm/vmscan.c:run_cmd
  - mm/vmscan.c:shrink_many
  - mm/vmscan.c:shrink_many
  - mm/vmscan.c:lru_gen_del_mm
```
```
In mm/workingset.c (ffffffff8140c2ad)
Location: include/linux/memcontrol.h:835
Inline: True
Inline callers:
  - mm/workingset.c:workingset_test_recent
```
```
In mm/zswap.c (ffffffff81470a53)
Location: include/linux/memcontrol.h:835
Inline: True
Inline callers:
  - mm/zswap.c:zswap_store
  - mm/zswap.c:zswap_store
  - mm/zswap.c:zswap_store
  - mm/zswap.c:zswap_store
  - mm/zswap.c:shrink_worker
```
```
In mm/hugetlb.c (ffffffff8147891c)
Location: include/linux/memcontrol.h:835
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_hugetlb_folio
  - mm/hugetlb.c:alloc_hugetlb_folio
  - mm/hugetlb.c:alloc_hugetlb_folio
  - mm/hugetlb.c:alloc_hugetlb_folio
```
```
In mm/memcontrol.c (ffffffff814c0bf3)
Location: include/linux/memcontrol.h:835
Inline: True
Inline callers:
  - mm/memcontrol.c:obj_cgroup_may_zswap
```
```
In fs/notify/group.c (ffffffff81548119)
Location: include/linux/memcontrol.h:835
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_put_group
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
In mm/oom_kill.c (ffff8000102b7bc4)
Location: include/linux/memcontrol.h:442
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
```
```
In mm/slab_common.c (ffff8000102e6a94)
Location: include/linux/memcontrol.h:442
Inline: True
Inline callers:
  - mm/slab_common.c:destroy_memcg_params
```
```
In fs/buffer.c (ffff8000103d9248)
Location: include/linux/memcontrol.h:442
Inline: True
Inline callers:
  - fs/buffer.c:alloc_page_buffers
```
```
In fs/notify/group.c (ffff8000103e8f0c)
Location: include/linux/memcontrol.h:442
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_put_group
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
In mm/oom_kill.c (c04e47ec)
Location: include/linux/memcontrol.h:442
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
```
```
In mm/slab_common.c (c050a568)
Location: include/linux/memcontrol.h:442
Inline: True
Inline callers:
  - mm/slab_common.c:destroy_memcg_params
```
```
In fs/buffer.c (c05b1fb0)
Location: include/linux/memcontrol.h:442
Inline: True
Inline callers:
  - fs/buffer.c:alloc_page_buffers
```
```
In fs/notify/group.c (c05c0628)
Location: include/linux/memcontrol.h:442
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_put_group
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
In mm/oom_kill.c (c00000000036f9f8)
Location: include/linux/memcontrol.h:442
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
```
```
In mm/slab_common.c (c0000000003a7728)
Location: include/linux/memcontrol.h:442
Inline: True
Inline callers:
  - mm/slab_common.c:destroy_memcg_params
```
```
In fs/buffer.c (c0000000004dd250)
Location: include/linux/memcontrol.h:442
Inline: True
Inline callers:
  - fs/buffer.c:alloc_page_buffers
```
```
In fs/notify/group.c (c0000000004efa60)
Location: include/linux/memcontrol.h:442
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_put_group
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
In mm/oom_kill.c (ffffffe0001dbe26)
Location: include/linux/memcontrol.h:442
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
```
```
In mm/slab_common.c (ffffffe0001fc16a)
Location: include/linux/memcontrol.h:442
Inline: True
Inline callers:
  - mm/slab_common.c:destroy_memcg_params
```
```
In fs/buffer.c (ffffffe000291da6)
Location: include/linux/memcontrol.h:442
Inline: True
Inline callers:
  - fs/buffer.c:alloc_page_buffers
```
```
In fs/notify/group.c (ffffffe00029d9b6)
Location: include/linux/memcontrol.h:442
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_final_destroy_group
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
In mm/oom_kill.c (ffffffff81222374)
Location: include/linux/memcontrol.h:442
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
```
```
In mm/slab_common.c (ffffffff8124796e)
Location: include/linux/memcontrol.h:442
Inline: True
Inline callers:
  - mm/slab_common.c:destroy_memcg_params
```
```
In fs/buffer.c (ffffffff81318bb5)
Location: include/linux/memcontrol.h:442
Inline: True
Inline callers:
  - fs/buffer.c:alloc_page_buffers
```
```
In fs/notify/group.c (ffffffff81325704)
Location: include/linux/memcontrol.h:442
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_put_group
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
In mm/oom_kill.c (ffffffff81215524)
Location: include/linux/memcontrol.h:442
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
```
```
In mm/slab_common.c (ffffffff8123a91e)
Location: include/linux/memcontrol.h:442
Inline: True
Inline callers:
  - mm/slab_common.c:destroy_memcg_params
```
```
In fs/buffer.c (ffffffff813097a5)
Location: include/linux/memcontrol.h:442
Inline: True
Inline callers:
  - fs/buffer.c:alloc_page_buffers
```
```
In fs/notify/group.c (ffffffff813162a4)
Location: include/linux/memcontrol.h:442
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_put_group
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
In mm/oom_kill.c (ffffffff81220114)
Location: include/linux/memcontrol.h:442
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
```
```
In mm/slab_common.c (ffffffff8124570e)
Location: include/linux/memcontrol.h:442
Inline: True
Inline callers:
  - mm/slab_common.c:destroy_memcg_params
```
```
In fs/buffer.c (ffffffff81316685)
Location: include/linux/memcontrol.h:442
Inline: True
Inline callers:
  - fs/buffer.c:alloc_page_buffers
```
```
In fs/notify/group.c (ffffffff813231d4)
Location: include/linux/memcontrol.h:442
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_put_group
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
In mm/oom_kill.c (ffffffff8122f222)
Location: include/linux/memcontrol.h:442
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
```
```
In mm/slab_common.c (ffffffff8125511e)
Location: include/linux/memcontrol.h:442
Inline: True
Inline callers:
  - mm/slab_common.c:destroy_memcg_params
```
```
In fs/buffer.c (ffffffff81328475)
Location: include/linux/memcontrol.h:442
Inline: True
Inline callers:
  - fs/buffer.c:alloc_page_buffers
```
```
In fs/notify/group.c (ffffffff81334f14)
Location: include/linux/memcontrol.h:442
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_put_group
```
</details>
</li>
</ul>

## Differences
