# Function: <code>dma_fence_is_signaled_locked</code>

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
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sw_sync.c (ffffffff8162c53d)
Location: include/linux/dma-fence.h:297
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
```
```
In drivers/dma-buf/sync_debug.c (ffffffff8162c893)
Location: include/linux/dma-fence.h:297
Inline: True
Inline callers:
  - drivers/dma-buf/sync_debug.c:sync_print_fence
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
In drivers/dma-buf/dma-fence.c (ffffffff8163eded)
Location: include/linux/dma-fence.h:299
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_get_status
```
```
In drivers/dma-buf/sw_sync.c (ffffffff81641b0f)
Location: include/linux/dma-fence.h:299
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
```
```
In drivers/dma-buf/sync_debug.c (ffffffff81641ee2)
Location: include/linux/dma-fence.h:299
Inline: True
Inline callers:
  - drivers/dma-buf/sync_debug.c:sync_print_fence
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
In drivers/dma-buf/dma-fence.c (ffffffff816a7bbd)
Location: include/linux/dma-fence.h:302
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_get_status
```
```
In drivers/dma-buf/sw_sync.c (ffffffff816aac33)
Location: include/linux/dma-fence.h:302
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
```
```
In drivers/dma-buf/sync_debug.c (ffffffff816aaef2)
Location: include/linux/dma-fence.h:302
Inline: True
Inline callers:
  - drivers/dma-buf/sync_debug.c:sync_print_fence
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
In drivers/dma-buf/dma-fence.c (ffffffff816e3c9d)
Location: include/linux/dma-fence.h:372
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_get_status
```
```
In drivers/dma-buf/sw_sync.c (ffffffff816e711d)
Location: include/linux/dma-fence.h:372
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
```
```
In drivers/dma-buf/sync_debug.c (ffffffff816e73f1)
Location: include/linux/dma-fence.h:372
Inline: True
Inline callers:
  - drivers/dma-buf/sync_debug.c:sync_print_fence
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
In drivers/dma-buf/dma-fence.c (ffffffff8170713d)
Location: include/linux/dma-fence.h:366
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_get_status
```
```
In drivers/dma-buf/sw_sync.c (ffffffff8170a4ad)
Location: include/linux/dma-fence.h:366
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
```
```
In drivers/dma-buf/sync_debug.c (ffffffff8170a781)
Location: include/linux/dma-fence.h:366
Inline: True
Inline callers:
  - drivers/dma-buf/sync_debug.c:sync_print_fence
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
In drivers/dma-buf/dma-fence.c (ffffffff8174228d)
Location: include/linux/dma-fence.h:366
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_get_status
```
```
In drivers/dma-buf/sw_sync.c (ffffffff81745ce8)
Location: include/linux/dma-fence.h:366
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
```
```
In drivers/dma-buf/sync_debug.c (ffffffff81745ff0)
Location: include/linux/dma-fence.h:366
Inline: True
Inline callers:
  - drivers/dma-buf/sync_debug.c:sync_print_fence
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
In drivers/dma-buf/dma-fence.c (ffffffff8176602c)
Location: include/linux/dma-fence.h:386
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_get_status
```
```
In drivers/dma-buf/sw_sync.c (ffffffff81769e3a)
Location: include/linux/dma-fence.h:386
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
```
```
In drivers/dma-buf/sync_debug.c (ffffffff8176a13f)
Location: include/linux/dma-fence.h:386
Inline: True
Inline callers:
  - drivers/dma-buf/sync_debug.c:sync_print_fence
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
In drivers/dma-buf/dma-fence.c (ffffffff81826d5c)
Location: include/linux/dma-fence.h:386
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_get_status
```
```
In drivers/dma-buf/sw_sync.c (ffffffff8182be44)
Location: include/linux/dma-fence.h:386
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sync_pt_create
```
```
In drivers/dma-buf/sync_debug.c (ffffffff8182c25f)
Location: include/linux/dma-fence.h:386
Inline: True
Inline callers:
  - drivers/dma-buf/sync_debug.c:sync_print_fence
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
In drivers/dma-buf/dma-fence.c (ffffffff8183786c)
Location: include/linux/dma-fence.h:399
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_get_status
```
```
In drivers/dma-buf/sw_sync.c (ffffffff8183cea4)
Location: include/linux/dma-fence.h:399
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sync_pt_create
```
```
In drivers/dma-buf/sync_debug.c (ffffffff8183d2bf)
Location: include/linux/dma-fence.h:399
Inline: True
Inline callers:
  - drivers/dma-buf/sync_debug.c:sync_print_fence
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
In drivers/dma-buf/dma-fence.c (ffffffff8181a7ac)
Location: include/linux/dma-fence.h:402
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_get_status
```
```
In drivers/dma-buf/sw_sync.c (ffffffff8181fe80)
Location: include/linux/dma-fence.h:402
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sync_pt_create
```
```
In drivers/dma-buf/sync_debug.c (ffffffff8182044f)
Location: include/linux/dma-fence.h:402
Inline: True
Inline callers:
  - drivers/dma-buf/sync_debug.c:sync_print_fence
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
In drivers/dma-buf/dma-fence.c (ffffffff818a4c4c)
Location: include/linux/dma-fence.h:402
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_get_status
```
```
In drivers/dma-buf/sw_sync.c (ffffffff818aa540)
Location: include/linux/dma-fence.h:402
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sync_pt_create
```
```
In drivers/dma-buf/sync_debug.c (ffffffff818aab1f)
Location: include/linux/dma-fence.h:402
Inline: True
Inline callers:
  - drivers/dma-buf/sync_debug.c:sync_print_fence
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
In drivers/dma-buf/dma-fence.c (ffffffff819ee87c)
Location: include/linux/dma-fence.h:399
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_get_status
```
```
In drivers/dma-buf/sw_sync.c (ffffffff819f4d33)
Location: include/linux/dma-fence.h:399
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sync_pt_create
```
```
In drivers/dma-buf/sync_debug.c (ffffffff819f5140)
Location: include/linux/dma-fence.h:399
Inline: True
Inline callers:
  - drivers/dma-buf/sync_debug.c:sync_print_fence
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
In drivers/dma-buf/dma-fence.c (ffffffff81b6bf6c)
Location: include/linux/dma-fence.h:399
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_get_status
```
```
In drivers/dma-buf/sw_sync.c (ffffffff81b721e3)
Location: include/linux/dma-fence.h:399
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sync_pt_create
```
```
In drivers/dma-buf/sync_debug.c (ffffffff81b72620)
Location: include/linux/dma-fence.h:399
Inline: True
Inline callers:
  - drivers/dma-buf/sync_debug.c:sync_print_fence
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
In drivers/dma-buf/dma-fence.c (ffffffff81bbf3fc)
Location: include/linux/dma-fence.h:419
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_get_status
```
```
In drivers/dma-buf/sw_sync.c (ffffffff81bc5bf3)
Location: include/linux/dma-fence.h:419
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sync_pt_create
```
```
In drivers/dma-buf/sync_debug.c (ffffffff81bc6020)
Location: include/linux/dma-fence.h:419
Inline: True
Inline callers:
  - drivers/dma-buf/sync_debug.c:sync_print_fence
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
In drivers/dma-buf/dma-fence.c (ffffffff81c13b7c)
Location: include/linux/dma-fence.h:420
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_get_status
```
```
In drivers/dma-buf/sw_sync.c (ffffffff81c1a602)
Location: include/linux/dma-fence.h:420
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sync_pt_create
```
```
In drivers/dma-buf/sync_debug.c (ffffffff81c1ab40)
Location: include/linux/dma-fence.h:420
Inline: True
Inline callers:
  - drivers/dma-buf/sync_debug.c:sync_print_fence
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
In drivers/dma-buf/dma-fence.c (ffff800010966cb0)
Location: include/linux/dma-fence.h:386
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_get_status
```
```
In drivers/dma-buf/sw_sync.c (ffff80001096b864)
Location: include/linux/dma-fence.h:386
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
```
```
In drivers/dma-buf/sync_debug.c (ffff80001096bcbc)
Location: include/linux/dma-fence.h:386
Inline: True
Inline callers:
  - drivers/dma-buf/sync_debug.c:sync_print_fence
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
In drivers/dma-buf/dma-fence.c (c0a3d0bc)
Location: include/linux/dma-fence.h:386
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_get_status
```
```
In drivers/dma-buf/sw_sync.c (c0a41380)
Location: include/linux/dma-fence.h:386
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
```
```
In drivers/dma-buf/sync_debug.c (c0a41814)
Location: include/linux/dma-fence.h:386
Inline: True
Inline callers:
  - drivers/dma-buf/sync_debug.c:sync_print_fence
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
In drivers/dma-buf/dma-fence.c (c000000000a1dca0)
Location: include/linux/dma-fence.h:386
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_get_status
```
```
In drivers/dma-buf/sw_sync.c (c000000000a24094)
Location: include/linux/dma-fence.h:386
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
```
```
In drivers/dma-buf/sync_debug.c (c000000000a246bc)
Location: include/linux/dma-fence.h:386
Inline: True
Inline callers:
  - drivers/dma-buf/sync_debug.c:sync_print_fence
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
In drivers/dma-buf/dma-fence.c (ffffffe0005d2f68)
Location: include/linux/dma-fence.h:386
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_get_status
```
```
In drivers/dma-buf/sw_sync.c (ffffffe0005d68ba)
Location: include/linux/dma-fence.h:386
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
```
```
In drivers/dma-buf/sync_debug.c (ffffffe0005d6b48)
Location: include/linux/dma-fence.h:386
Inline: True
Inline callers:
  - drivers/dma-buf/sync_debug.c:sync_print_fence
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
In drivers/dma-buf/dma-fence.c (ffffffff8171a71c)
Location: include/linux/dma-fence.h:386
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_get_status
```
```
In drivers/dma-buf/sw_sync.c (ffffffff8171e52a)
Location: include/linux/dma-fence.h:386
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
```
```
In drivers/dma-buf/sync_debug.c (ffffffff8171e82f)
Location: include/linux/dma-fence.h:386
Inline: True
Inline callers:
  - drivers/dma-buf/sync_debug.c:sync_print_fence
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
In drivers/dma-buf/dma-fence.c (ffffffff816f3b7c)
Location: include/linux/dma-fence.h:386
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_get_status
```
```
In drivers/dma-buf/sw_sync.c (ffffffff816f797a)
Location: include/linux/dma-fence.h:386
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
```
```
In drivers/dma-buf/sync_debug.c (ffffffff816f7c6f)
Location: include/linux/dma-fence.h:386
Inline: True
Inline callers:
  - drivers/dma-buf/sync_debug.c:sync_print_fence
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
In drivers/dma-buf/dma-fence.c (ffffffff817594ec)
Location: include/linux/dma-fence.h:386
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_get_status
```
```
In drivers/dma-buf/sw_sync.c (ffffffff8175d2fa)
Location: include/linux/dma-fence.h:386
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
```
```
In drivers/dma-buf/sync_debug.c (ffffffff8175d5ff)
Location: include/linux/dma-fence.h:386
Inline: True
Inline callers:
  - drivers/dma-buf/sync_debug.c:sync_print_fence
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
In drivers/dma-buf/dma-fence.c (ffffffff817749ec)
Location: include/linux/dma-fence.h:386
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_get_status
```
```
In drivers/dma-buf/sw_sync.c (ffffffff8177899c)
Location: include/linux/dma-fence.h:386
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
```
```
In drivers/dma-buf/sync_debug.c (ffffffff81778c8f)
Location: include/linux/dma-fence.h:386
Inline: True
Inline callers:
  - drivers/dma-buf/sync_debug.c:sync_print_fence
```
</details>
</li>
</ul>

## Differences
