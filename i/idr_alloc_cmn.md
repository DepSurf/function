# Function: <code>idr_alloc_cmn</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int idr_alloc_cmn(struct idr *idr, void *ptr, long unsigned int *index, long unsigned int start, long unsigned int end, gfp_t gfp, bool ext);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff81972900)
Location: lib/idr.c:10
Inline: False
Direct callers:
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/events/core.c:perf_pmu_register
  - mm/shmem.c:shmem_get_inode
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - ipc/util.c:ipc_addid
  - block/bsg.c:bsg_register_queue
  - drivers/char/tpm/tpm-chip.c:tpm_chip_alloc
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
  - drivers/block/loop.c:loop_add
  - drivers/block/loop.c:loop_add
  - drivers/scsi/sg.c:sg_add_device
  - drivers/spi/spi.c:spi_register_controller
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/i2c/i2c-core-base.c:i2c_add_numbered_adapter
  - drivers/i2c/i2c-core-base.c:i2c_add_adapter
  - drivers/md/dm.c:dm_create
  - drivers/md/dm.c:dm_create
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:__peernet2id_alloc
  - net/sched/act_api.c:tcf_idr_create
  - net/sched/act_api.c:tcf_idr_create
  - lib/idr.c:idr_alloc_cyclic
  - lib/idr.c:idr_alloc_cyclic
```
**Symbols:**

```
ffffffff81972900-ffffffff819729cf: idr_alloc_cmn (STB_GLOBAL)
```
</details>
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
</ul>
