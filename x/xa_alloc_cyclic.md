# Function: <code>xa_alloc_cyclic</code>

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
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8139ec4e)
Location: include/linux/xarray.h:945
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_register
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
In fs/io_uring.c (ffffffff813ee632)
Location: include/linux/xarray.h:945
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_register
```
```
In net/core/devlink.c (ffffffff81af5fab)
Location: include/linux/xarray.h:945
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_alloc_ns
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
In io_uring/io_uring.c (ffffffff816d84d2)
Location: include/linux/xarray.h:946
Inline: True
Inline callers:
  - io_uring/io_uring.c:__io_uring_register
```
```
In net/core/devlink.c (ffffffff81c7611b)
Location: include/linux/xarray.h:946
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_alloc_ns
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
In io_uring/io_uring.c (ffffffff8178c3cf)
Location: include/linux/xarray.h:958
Inline: True
Inline callers:
  - io_uring/io_uring.c:__io_uring_register
```
```
In net/core/devlink.c (ffffffff81e2e88b)
Location: include/linux/xarray.h:958
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_alloc_ns
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
In io_uring/io_uring.c (ffffffff817cd5e3)
Location: include/linux/xarray.h:958
Inline: True
Inline callers:
  - io_uring/io_uring.c:__io_uring_register
```
```
In net/sched/cls_api.c (ffffffff81eb66e0)
Location: include/linux/xarray.h:958
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_exts_init_ex
```
```
In net/devlink/core.c (ffffffff82041f6d)
Location: include/linux/xarray.h:958
Inline: True
Inline callers:
  - net/devlink/core.c:devlink_alloc_ns
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
In fs/libfs.c (ffffffff8152369c)
Location: include/linux/xarray.h:970
Inline: True
Inline callers:
  - fs/libfs.c:simple_offset_add
```
```
In io_uring/register.c (ffffffff8182bbb0)
Location: include/linux/xarray.h:970
Inline: True
Inline callers:
  - io_uring/register.c:__io_uring_register
```
```
In drivers/dpll/dpll_core.c (ffffffff81eb6bd6)
Location: include/linux/xarray.h:970
Inline: True
Inline callers:
  - drivers/dpll/dpll_core.c:dpll_pin_get
  - drivers/dpll/dpll_core.c:dpll_device_get
```
```
In net/core/dev.c (ffffffff81ef6fbb)
Location: include/linux/xarray.h:970
Inline: True
Inline callers:
  - net/core/dev.c:__dev_change_net_namespace
```
```
In net/core/page_pool_user.c (ffffffff81f460cb)
Location: include/linux/xarray.h:970
Inline: True
Inline callers:
  - net/core/page_pool_user.c:page_pool_list
```
```
In net/sched/cls_api.c (ffffffff81f794fe)
Location: include/linux/xarray.h:970
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_exts_init_ex
```
```
In net/devlink/core.c (ffffffff820fea8d)
Location: include/linux/xarray.h:970
Inline: True
Inline callers:
  - net/devlink/core.c:devlink_alloc_ns
  - net/devlink/core.c:devlink_rel_nested_in_add
```
</details>
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
