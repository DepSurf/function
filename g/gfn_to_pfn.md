# Function: <code>gfn_to_pfn</code>

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
In drivers/xen/xenbus/xenbus_client.c (ffffffff814cc463)
Location: arch/x86/include/asm/xen/page.h:200
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff81fa4d3a)
Location: arch/x86/include/asm/xen/page.h:200
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
```
```
In drivers/xen/swiotlb-xen.c (ffffffff814d49c9)
Location: arch/x86/include/asm/xen/page.h:200
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff814ff2dd)
Location: arch/x86/include/asm/xen/page.h:200
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xen_pv_console_init
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
In drivers/xen/xenbus/xenbus_client.c (ffffffff8151d1b5)
Location: arch/x86/include/asm/xen/page.h:200
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff81fd1307)
Location: arch/x86/include/asm/xen/page.h:200
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
```
```
In drivers/xen/swiotlb-xen.c (ffffffff815260f2)
Location: arch/x86/include/asm/xen/page.h:200
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff8154fd82)
Location: arch/x86/include/asm/xen/page.h:200
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init
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
In drivers/xen/xenbus/xenbus_client.c (ffffffff81549705)
Location: arch/x86/include/asm/xen/page.h:200
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff8200ec84)
Location: arch/x86/include/asm/xen/page.h:200
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81552602)
Location: arch/x86/include/asm/xen/page.h:200
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff8157c932)
Location: arch/x86/include/asm/xen/page.h:200
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init
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
In drivers/xen/xenbus/xenbus_client.c (ffffffff8155d5e5)
Location: arch/x86/include/asm/xen/page.h:226
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff820f0747)
Location: arch/x86/include/asm/xen/page.h:226
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81566dd2)
Location: arch/x86/include/asm/xen/page.h:226
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff815909f4)
Location: arch/x86/include/asm/xen/page.h:226
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init
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
In drivers/xen/xenbus/xenbus_client.c (ffffffff815c18f5)
Location: arch/x86/include/asm/xen/page.h:233
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff826f9f51)
Location: arch/x86/include/asm/xen/page.h:233
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
```
```
In drivers/xen/swiotlb-xen.c (ffffffff815caf82)
Location: arch/x86/include/asm/xen/page.h:233
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff815f56d4)
Location: arch/x86/include/asm/xen/page.h:233
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init
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
In drivers/xen/xenbus/xenbus_client.c (ffffffff815f9975)
Location: arch/x86/include/asm/xen/page.h:233
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff827242df)
Location: arch/x86/include/asm/xen/page.h:233
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
```
```
In drivers/xen/swiotlb-xen.c (ffffffff816037df)
Location: arch/x86/include/asm/xen/page.h:233
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff8162e47f)
Location: arch/x86/include/asm/xen/page.h:233
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init
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
In drivers/xen/xenbus/xenbus_client.c (ffffffff81614a35)
Location: arch/x86/include/asm/xen/page.h:260
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff828dc4b8)
Location: arch/x86/include/asm/xen/page.h:260
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
```
```
In drivers/xen/swiotlb-xen.c (ffffffff8161e8d3)
Location: arch/x86/include/asm/xen/page.h:260
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff8164c6bf)
Location: arch/x86/include/asm/xen/page.h:260
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init
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
In drivers/xen/xenbus/xenbus_client.c (ffffffff81648715)
Location: arch/x86/include/asm/xen/page.h:260
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff828f6d93)
Location: arch/x86/include/asm/xen/page.h:260
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81651364)
Location: arch/x86/include/asm/xen/page.h:260
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff816811cf)
Location: arch/x86/include/asm/xen/page.h:260
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init
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
In drivers/xen/xenbus/xenbus_client.c (ffffffff8166abb5)
Location: arch/x86/include/asm/xen/page.h:260
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff828ffdea)
Location: arch/x86/include/asm/xen/page.h:260
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81673744)
Location: arch/x86/include/asm/xen/page.h:260
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff816a387f)
Location: arch/x86/include/asm/xen/page.h:260
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init
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
In drivers/xen/xenbus/xenbus_client.c (ffffffff8171ae05)
Location: arch/x86/include/asm/xen/page.h:259
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff82d171ee)
Location: arch/x86/include/asm/xen/page.h:259
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81723f52)
Location: arch/x86/include/asm/xen/page.h:259
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_sg_for_device
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_sg_for_cpu
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81755cff)
Location: arch/x86/include/asm/xen/page.h:259
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init
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
In drivers/xen/xenbus/xenbus_client.c (ffffffff81737f75)
Location: arch/x86/include/asm/xen/page.h:259
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff83004dce)
Location: arch/x86/include/asm/xen/page.h:259
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
```
```
In drivers/xen/swiotlb-xen.c (0)
Location: arch/x86/include/asm/xen/page.h:259
Inline: True
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81770f6f)
Location: arch/x86/include/asm/xen/page.h:259
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init
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
In drivers/xen/xenbus/xenbus_client.c (ffffffff8171b825)
Location: arch/x86/include/asm/xen/page.h:259
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff8320f828)
Location: arch/x86/include/asm/xen/page.h:259
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
```
```
In drivers/xen/swiotlb-xen.c (ffffffff8172416a)
Location: arch/x86/include/asm/xen/page.h:259
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81754a2f)
Location: arch/x86/include/asm/xen/page.h:259
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init
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
In drivers/xen/grant-table.c (ffffffff81790ec4)
Location: arch/x86/include/asm/xen/page.h:259
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_add_deferred
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff8179a455)
Location: arch/x86/include/asm/xen/page.h:259
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff832f87cf)
Location: arch/x86/include/asm/xen/page.h:259
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
```
```
In drivers/xen/swiotlb-xen.c (ffffffff817a2ff0)
Location: arch/x86/include/asm/xen/page.h:259
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_unmap_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff817d80ef)
Location: arch/x86/include/asm/xen/page.h:259
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init
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
In drivers/xen/grant-table.c (ffffffff818c9506)
Location: arch/x86/include/asm/xen/page.h:251
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_add_deferred
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff818d3f14)
Location: arch/x86/include/asm/xen/page.h:251
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff834b106a)
Location: arch/x86/include/asm/xen/page.h:251
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
```
```
In drivers/xen/swiotlb-xen.c (ffffffff818dd284)
Location: arch/x86/include/asm/xen/page.h:251
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_unmap_page
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff8191658d)
Location: arch/x86/include/asm/xen/page.h:251
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init
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
In drivers/xen/grant-table.c (ffffffff81a1a3ac)
Location: arch/x86/include/asm/xen/page.h:251
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_add_deferred
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff81a26134)
Location: arch/x86/include/asm/xen/page.h:251
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff83eeaf69)
Location: arch/x86/include/asm/xen/page.h:251
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81a30704)
Location: arch/x86/include/asm/xen/page.h:251
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_unmap_page
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81a71ffd)
Location: arch/x86/include/asm/xen/page.h:251
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init
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
In drivers/xen/grant-table.c (ffffffff81a637ce)
Location: arch/x86/include/asm/xen/page.h:251
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_add_deferred
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff81a6f6ec)
Location: arch/x86/include/asm/xen/page.h:251
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff83710979)
Location: arch/x86/include/asm/xen/page.h:251
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81a79f14)
Location: arch/x86/include/asm/xen/page.h:251
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_unmap_page
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81abc8c4)
Location: arch/x86/include/asm/xen/page.h:251
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init
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
In drivers/xen/grant-table.c (ffffffff81ab601d)
Location: arch/x86/include/asm/xen/page.h:251
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_add_deferred
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff81ac17ec)
Location: arch/x86/include/asm/xen/page.h:251
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff839442f9)
Location: arch/x86/include/asm/xen/page.h:251
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81acc3d1)
Location: arch/x86/include/asm/xen/page.h:251
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_unmap_page
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81b0f684)
Location: arch/x86/include/asm/xen/page.h:251
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Collision, Selective Inline ⚠️</summary>

```c
kvm_pfn_t gfn_to_pfn(struct kvm *kvm, gfn_t gfn);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In virt/kvm/kvm_main.c (ffff8000100bc180)
Location: virt/kvm/kvm_main.c:1760
Inline: False
Direct callers:
  - virt/kvm/kvm_main.c:gfn_to_page
```
```
In drivers/xen/xenbus/xenbus_client.c (0)
Location: include/xen/arm/page.h:52
Inline: True
```
```
In drivers/xen/xenbus/xenbus_probe.c (0)
Location: include/xen/arm/page.h:52
Inline: True
```
```
In drivers/tty/hvc/hvc_xen.c (0)
Location: include/xen/arm/page.h:52
Inline: True
```
**Symbols:**

```
ffff8000100bc180-ffff8000100bc278: gfn_to_pfn (STB_GLOBAL)
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
In drivers/xen/xenbus/xenbus_client.c (ffffffff81630a25)
Location: arch/x86/include/asm/xen/page.h:260
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff828e7607)
Location: arch/x86/include/asm/xen/page.h:260
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81639434)
Location: arch/x86/include/asm/xen/page.h:260
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff816692df)
Location: arch/x86/include/asm/xen/page.h:260
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init
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
In drivers/xen/xenbus/xenbus_client.c (ffffffff8165e9f5)
Location: arch/x86/include/asm/xen/page.h:260
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff828fb10d)
Location: arch/x86/include/asm/xen/page.h:260
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81667584)
Location: arch/x86/include/asm/xen/page.h:260
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff816976bf)
Location: arch/x86/include/asm/xen/page.h:260
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init
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
In drivers/xen/xenbus/xenbus_client.c (ffffffff81679535)
Location: arch/x86/include/asm/xen/page.h:260
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff82900e3e)
Location: arch/x86/include/asm/xen/page.h:260
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81681b44)
Location: arch/x86/include/asm/xen/page.h:260
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff816b1fdf)
Location: arch/x86/include/asm/xen/page.h:260
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
