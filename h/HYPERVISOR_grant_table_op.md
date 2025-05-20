# Function: <code>HYPERVISOR_grant_table_op</code>

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
In arch/x86/xen/p2m.c (ffffffff810253ce)
Location: arch/x86/include/asm/xen/hypercall.h:397
Inline: True
```
```
In drivers/xen/grant-table.c (ffffffff814c4a7b)
Location: arch/x86/include/asm/xen/hypercall.h:397
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_max_grant_frames
  - drivers/xen/grant-table.c:gnttab_max_grant_frames
  - drivers/xen/grant-table.c:gnttab_map
  - drivers/xen/grant-table.c:gnttab_setup_auto_xlat_frames
  - drivers/xen/grant-table.c:__gnttab_unmap_refs_async
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff814cb2e5)
Location: arch/x86/include/asm/xen/hypercall.h:397
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_pv
  - drivers/xen/xenbus/xenbus_client.c:__xenbus_map_ring
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
In arch/x86/xen/p2m.c (ffffffff810247be)
Location: arch/x86/include/asm/xen/hypercall.h:398
Inline: True
```
```
In drivers/xen/grant-table.c (ffffffff8151554f)
Location: arch/x86/include/asm/xen/hypercall.h:398
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_map
  - drivers/xen/grant-table.c:__gnttab_unmap_refs_async
  - drivers/xen/grant-table.c:gnttab_setup_auto_xlat_frames
  - drivers/xen/grant-table.c:gnttab_max_grant_frames
  - drivers/xen/grant-table.c:gnttab_max_grant_frames
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff8151becb)
Location: arch/x86/include/asm/xen/hypercall.h:398
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_pv
  - drivers/xen/xenbus/xenbus_client.c:__xenbus_map_ring
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
In arch/x86/xen/p2m.c (ffffffff81024eee)
Location: arch/x86/include/asm/xen/hypercall.h:398
Inline: True
```
```
In drivers/xen/grant-table.c (ffffffff815419df)
Location: arch/x86/include/asm/xen/hypercall.h:398
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_map
  - drivers/xen/grant-table.c:__gnttab_unmap_refs_async
  - drivers/xen/grant-table.c:gnttab_setup_auto_xlat_frames
  - drivers/xen/grant-table.c:gnttab_max_grant_frames
  - drivers/xen/grant-table.c:gnttab_max_grant_frames
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff8154839b)
Location: arch/x86/include/asm/xen/hypercall.h:398
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_pv
  - drivers/xen/xenbus/xenbus_client.c:__xenbus_map_ring
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
In arch/x86/xen/p2m.c (ffffffff8101e0ce)
Location: arch/x86/include/asm/xen/hypercall.h:403
Inline: True
```
```
In drivers/xen/grant-table.c (ffffffff8155582f)
Location: arch/x86/include/asm/xen/hypercall.h:403
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_map
  - drivers/xen/grant-table.c:__gnttab_unmap_refs_async
  - drivers/xen/grant-table.c:gnttab_setup_auto_xlat_frames
  - drivers/xen/grant-table.c:gnttab_max_grant_frames
  - drivers/xen/grant-table.c:gnttab_max_grant_frames
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff8155c283)
Location: arch/x86/include/asm/xen/hypercall.h:403
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_pv
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
In arch/x86/xen/p2m.c (ffffffff8101edee)
Location: arch/x86/include/asm/xen/hypercall.h:403
Inline: True
```
```
In drivers/xen/grant-table.c (ffffffff815ba69d)
Location: arch/x86/include/asm/xen/hypercall.h:403
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_request_version
  - drivers/xen/grant-table.c:gnttab_map
  - drivers/xen/grant-table.c:gnttab_map_frames_v2
  - drivers/xen/grant-table.c:__gnttab_unmap_refs_async
  - drivers/xen/grant-table.c:gnttab_setup_auto_xlat_frames
  - drivers/xen/grant-table.c:gnttab_max_grant_frames
  - drivers/xen/grant-table.c:gnttab_max_grant_frames
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff815c0593)
Location: arch/x86/include/asm/xen/hypercall.h:403
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_pv
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
In arch/x86/xen/p2m.c (ffffffff8101f89e)
Location: arch/x86/include/asm/xen/hypercall.h:403
Inline: True
```
```
In drivers/xen/grant-table.c (ffffffff815f2bb2)
Location: arch/x86/include/asm/xen/hypercall.h:403
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_map
  - drivers/xen/grant-table.c:gnttab_map_frames_v2
  - drivers/xen/grant-table.c:__gnttab_unmap_refs_async
  - drivers/xen/grant-table.c:gnttab_setup_auto_xlat_frames
  - drivers/xen/grant-table.c:gnttab_max_grant_frames
  - drivers/xen/grant-table.c:gnttab_max_grant_frames
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff815f9f4f)
Location: arch/x86/include/asm/xen/hypercall.h:403
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_pv
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
In arch/x86/xen/p2m.c (ffffffff8101f15e)
Location: arch/x86/include/asm/xen/hypercall.h:370
Inline: True
```
```
In drivers/xen/grant-table.c (ffffffff8160d382)
Location: arch/x86/include/asm/xen/hypercall.h:370
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_map
  - drivers/xen/grant-table.c:gnttab_map_frames_v2
  - drivers/xen/grant-table.c:__gnttab_unmap_refs_async
  - drivers/xen/grant-table.c:gnttab_setup_auto_xlat_frames
  - drivers/xen/grant-table.c:gnttab_max_grant_frames
  - drivers/xen/grant-table.c:gnttab_max_grant_frames
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff81614e2f)
Location: arch/x86/include/asm/xen/hypercall.h:370
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_pv
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
In arch/x86/xen/p2m.c (ffffffff81020cc0)
Location: arch/x86/include/asm/xen/hypercall.h:380
Inline: True
```
```
In drivers/xen/grant-table.c (ffffffff81640dbf)
Location: arch/x86/include/asm/xen/hypercall.h:380
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_map
  - drivers/xen/grant-table.c:gnttab_map_frames_v2
  - drivers/xen/grant-table.c:__gnttab_unmap_refs_async
  - drivers/xen/grant-table.c:gnttab_setup_auto_xlat_frames
  - drivers/xen/grant-table.c:gnttab_max_grant_frames
  - drivers/xen/grant-table.c:gnttab_max_grant_frames
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff81648ad8)
Location: arch/x86/include/asm/xen/hypercall.h:380
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_pv
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
In arch/x86/xen/p2m.c (ffffffff81021620)
Location: arch/x86/include/asm/xen/hypercall.h:380
Inline: True
```
```
In drivers/xen/grant-table.c (ffffffff8166377f)
Location: arch/x86/include/asm/xen/hypercall.h:380
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_map
  - drivers/xen/grant-table.c:gnttab_map_frames_v2
  - drivers/xen/grant-table.c:__gnttab_unmap_refs_async
  - drivers/xen/grant-table.c:gnttab_setup_auto_xlat_frames
  - drivers/xen/grant-table.c:gnttab_max_grant_frames
  - drivers/xen/grant-table.c:gnttab_max_grant_frames
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff8166af78)
Location: arch/x86/include/asm/xen/hypercall.h:380
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_pv
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
In arch/x86/xen/p2m.c (ffffffff81023e85)
Location: arch/x86/include/asm/xen/hypercall.h:380
Inline: True
```
```
In drivers/xen/grant-table.c (ffffffff8171301b)
Location: arch/x86/include/asm/xen/hypercall.h:380
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_request_version
  - drivers/xen/grant-table.c:gnttab_map
  - drivers/xen/grant-table.c:gnttab_map_frames_v2
  - drivers/xen/grant-table.c:gnttab_setup_auto_xlat_frames
  - drivers/xen/grant-table.c:gnttab_max_grant_frames
  - drivers/xen/grant-table.c:gnttab_max_grant_frames
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff8171b038)
Location: arch/x86/include/asm/xen/hypercall.h:380
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_pv
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
In arch/x86/xen/p2m.c (ffffffff8102446b)
Location: arch/x86/include/asm/xen/hypercall.h:380
Inline: True
```
```
In drivers/xen/grant-table.c (ffffffff8172fe1b)
Location: arch/x86/include/asm/xen/hypercall.h:380
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_request_version
  - drivers/xen/grant-table.c:gnttab_map
  - drivers/xen/grant-table.c:gnttab_map_frames_v2
  - drivers/xen/grant-table.c:gnttab_setup_auto_xlat_frames
  - drivers/xen/grant-table.c:gnttab_max_grant_frames
  - drivers/xen/grant-table.c:gnttab_max_grant_frames
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff817381a8)
Location: arch/x86/include/asm/xen/hypercall.h:380
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_pv
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
In arch/x86/xen/p2m.c (ffffffff81026b9b)
Location: arch/x86/include/asm/xen/hypercall.h:380
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:clear_foreign_p2m_mapping
  - arch/x86/xen/p2m.c:set_foreign_p2m_mapping
  - arch/x86/xen/p2m.c:set_foreign_p2m_mapping
```
```
In drivers/xen/grant-table.c (ffffffff81713d75)
Location: arch/x86/include/asm/xen/hypercall.h:380
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_request_version
  - drivers/xen/grant-table.c:gnttab_map
  - drivers/xen/grant-table.c:gnttab_map_frames_v2
  - drivers/xen/grant-table.c:gnttab_setup_auto_xlat_frames
  - drivers/xen/grant-table.c:gnttab_max_grant_frames
  - drivers/xen/grant-table.c:gnttab_max_grant_frames
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff8171bbd8)
Location: arch/x86/include/asm/xen/hypercall.h:380
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_pv
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
In arch/x86/xen/p2m.c (ffffffff8102b0bb)
Location: arch/x86/include/asm/xen/hypercall.h:380
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:clear_foreign_p2m_mapping
  - arch/x86/xen/p2m.c:set_foreign_p2m_mapping
  - arch/x86/xen/p2m.c:set_foreign_p2m_mapping
```
```
In drivers/xen/grant-table.c (ffffffff817907a5)
Location: arch/x86/include/asm/xen/hypercall.h:380
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_request_version
  - drivers/xen/grant-table.c:gnttab_map
  - drivers/xen/grant-table.c:gnttab_map_frames_v2
  - drivers/xen/grant-table.c:gnttab_batch_copy
  - drivers/xen/grant-table.c:gnttab_batch_copy
  - drivers/xen/grant-table.c:gnttab_batch_map
  - drivers/xen/grant-table.c:gnttab_batch_map
  - drivers/xen/grant-table.c:gnttab_setup_auto_xlat_frames
  - drivers/xen/grant-table.c:gnttab_max_grant_frames
  - drivers/xen/grant-table.c:gnttab_max_grant_frames
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff8179a84c)
Location: arch/x86/include/asm/xen/hypercall.h:380
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_pv
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
In arch/x86/xen/p2m.c (ffffffff8102f936)
Location: arch/x86/include/asm/xen/hypercall.h:450
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:clear_foreign_p2m_mapping
  - arch/x86/xen/p2m.c:set_foreign_p2m_mapping
  - arch/x86/xen/p2m.c:set_foreign_p2m_mapping
```
```
In drivers/xen/grant-table.c (ffffffff818c7b60)
Location: arch/x86/include/asm/xen/hypercall.h:450
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_map
  - drivers/xen/grant-table.c:gnttab_map_frames_v2
  - drivers/xen/grant-table.c:gnttab_batch_copy
  - drivers/xen/grant-table.c:gnttab_batch_copy
  - drivers/xen/grant-table.c:gnttab_batch_map
  - drivers/xen/grant-table.c:gnttab_batch_map
  - drivers/xen/grant-table.c:gnttab_setup_auto_xlat_frames
  - drivers/xen/grant-table.c:gnttab_max_grant_frames
  - drivers/xen/grant-table.c:gnttab_max_grant_frames
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff818d2c38)
Location: arch/x86/include/asm/xen/hypercall.h:450
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_pv
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring
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
In arch/x86/xen/p2m.c (ffffffff81036cf6)
Location: arch/x86/include/asm/xen/hypercall.h:450
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:clear_foreign_p2m_mapping
  - arch/x86/xen/p2m.c:set_foreign_p2m_mapping
  - arch/x86/xen/p2m.c:set_foreign_p2m_mapping
```
```
In drivers/xen/grant-table.c (ffffffff81a197c3)
Location: arch/x86/include/asm/xen/hypercall.h:450
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_request_version
  - drivers/xen/grant-table.c:gnttab_map
  - drivers/xen/grant-table.c:gnttab_map_frames_v2
  - drivers/xen/grant-table.c:gnttab_batch_copy
  - drivers/xen/grant-table.c:gnttab_batch_copy
  - drivers/xen/grant-table.c:gnttab_batch_map
  - drivers/xen/grant-table.c:gnttab_batch_map
  - drivers/xen/grant-table.c:gnttab_setup_auto_xlat_frames
  - drivers/xen/grant-table.c:gnttab_max_grant_frames
  - drivers/xen/grant-table.c:gnttab_max_grant_frames
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff81a24c97)
Location: arch/x86/include/asm/xen/hypercall.h:450
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_pv
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring
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
In arch/x86/xen/p2m.c (ffffffff81036c66)
Location: arch/x86/include/asm/xen/hypercall.h:450
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:clear_foreign_p2m_mapping
  - arch/x86/xen/p2m.c:set_foreign_p2m_mapping
  - arch/x86/xen/p2m.c:set_foreign_p2m_mapping
```
```
In drivers/xen/grant-table.c (ffffffff81a62843)
Location: arch/x86/include/asm/xen/hypercall.h:450
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_request_version
  - drivers/xen/grant-table.c:gnttab_map
  - drivers/xen/grant-table.c:gnttab_map_frames_v2
  - drivers/xen/grant-table.c:gnttab_batch_copy
  - drivers/xen/grant-table.c:gnttab_batch_copy
  - drivers/xen/grant-table.c:gnttab_batch_map
  - drivers/xen/grant-table.c:gnttab_batch_map
  - drivers/xen/grant-table.c:gnttab_setup_auto_xlat_frames
  - drivers/xen/grant-table.c:gnttab_max_grant_frames
  - drivers/xen/grant-table.c:gnttab_max_grant_frames
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff81a6e208)
Location: arch/x86/include/asm/xen/hypercall.h:450
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_pv
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring
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
In arch/x86/xen/p2m.c (ffffffff8103ce66)
Location: arch/x86/include/asm/xen/hypercall.h:450
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:clear_foreign_p2m_mapping
  - arch/x86/xen/p2m.c:set_foreign_p2m_mapping
  - arch/x86/xen/p2m.c:set_foreign_p2m_mapping
```
```
In drivers/xen/grant-table.c (ffffffff81ab57a3)
Location: arch/x86/include/asm/xen/hypercall.h:450
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_request_version
  - drivers/xen/grant-table.c:gnttab_map
  - drivers/xen/grant-table.c:gnttab_map_frames_v2
  - drivers/xen/grant-table.c:gnttab_batch_copy
  - drivers/xen/grant-table.c:gnttab_batch_copy
  - drivers/xen/grant-table.c:gnttab_batch_map
  - drivers/xen/grant-table.c:gnttab_batch_map
  - drivers/xen/grant-table.c:gnttab_setup_auto_xlat_frames
  - drivers/xen/grant-table.c:gnttab_max_grant_frames
  - drivers/xen/grant-table.c:gnttab_max_grant_frames
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff81ac02a8)
Location: arch/x86/include/asm/xen/hypercall.h:450
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_pv
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring
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
  - arch/arm/xen/mm.c:xen_mm_init
  - arch/arm/xen/mm.c:dma_cache_maint
  - drivers/xen/grant-table.c:gnttab_map
  - drivers/xen/grant-table.c:gnttab_map_frames_v2
  - drivers/xen/grant-table.c:__max_nr_grant_frames
```
**Symbols:**

```
ffff8000100f0d08-ffff8000100f0d14: HYPERVISOR_grant_table_op (STB_GLOBAL)
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
In arch/x86/xen/p2m.c (ffffffff81021780)
Location: arch/x86/include/asm/xen/hypercall.h:380
Inline: True
```
```
In drivers/xen/grant-table.c (ffffffff816295ef)
Location: arch/x86/include/asm/xen/hypercall.h:380
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_map
  - drivers/xen/grant-table.c:gnttab_map_frames_v2
  - drivers/xen/grant-table.c:__gnttab_unmap_refs_async
  - drivers/xen/grant-table.c:gnttab_setup_auto_xlat_frames
  - drivers/xen/grant-table.c:gnttab_max_grant_frames
  - drivers/xen/grant-table.c:gnttab_max_grant_frames
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff81630de8)
Location: arch/x86/include/asm/xen/hypercall.h:380
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_pv
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
In arch/x86/xen/p2m.c (ffffffff810215e0)
Location: arch/x86/include/asm/xen/hypercall.h:380
Inline: True
```
```
In drivers/xen/grant-table.c (ffffffff816575bf)
Location: arch/x86/include/asm/xen/hypercall.h:380
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_map
  - drivers/xen/grant-table.c:gnttab_map_frames_v2
  - drivers/xen/grant-table.c:__gnttab_unmap_refs_async
  - drivers/xen/grant-table.c:gnttab_setup_auto_xlat_frames
  - drivers/xen/grant-table.c:gnttab_max_grant_frames
  - drivers/xen/grant-table.c:gnttab_max_grant_frames
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff8165edb8)
Location: arch/x86/include/asm/xen/hypercall.h:380
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_pv
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
In arch/x86/xen/p2m.c (ffffffff81021830)
Location: arch/x86/include/asm/xen/hypercall.h:380
Inline: True
```
```
In drivers/xen/grant-table.c (ffffffff81671bbf)
Location: arch/x86/include/asm/xen/hypercall.h:380
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_map
  - drivers/xen/grant-table.c:gnttab_map_frames_v2
  - drivers/xen/grant-table.c:__gnttab_unmap_refs_async
  - drivers/xen/grant-table.c:gnttab_setup_auto_xlat_frames
  - drivers/xen/grant-table.c:gnttab_max_grant_frames
  - drivers/xen/grant-table.c:gnttab_max_grant_frames
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff81678339)
Location: arch/x86/include/asm/xen/hypercall.h:380
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_pv
```
</details>
</li>
</ul>

## Differences
