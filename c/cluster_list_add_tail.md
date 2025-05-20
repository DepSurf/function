# Function: <code>cluster_list_add_tail</code>

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
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81205957)
Location: mm/swapfile.c:276
Inline: True
Inline callers:
  - mm/swapfile.c:SyS_swapon
  - mm/swapfile.c:swap_entry_free
  - mm/swapfile.c:swap_entry_free
  - mm/swapfile.c:swap_do_scheduled_discard
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/swapfile.c (ffffffff812110ce)
Location: mm/swapfile.c:325
Inline: True
Inline callers:
  - mm/swapfile.c:SyS_swapon
  - mm/swapfile.c:free_cluster
  - mm/swapfile.c:__free_cluster
Direct callers:
  - mm/swapfile.c:SyS_swapon
  - mm/swapfile.c:free_cluster
  - mm/swapfile.c:__free_cluster
```
**Symbols:**

```
ffffffff8120cf40-ffffffff8120cfa7: cluster_list_add_tail.part.21 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/swapfile.c (ffffffff8122864e)
Location: mm/swapfile.c:337
Inline: True
Inline callers:
  - mm/swapfile.c:SYSC_swapon
  - mm/swapfile.c:free_cluster
  - mm/swapfile.c:__free_cluster
Direct callers:
  - mm/swapfile.c:SYSC_swapon
  - mm/swapfile.c:free_cluster
  - mm/swapfile.c:__free_cluster
```
**Symbols:**

```
ffffffff81226df0-ffffffff81226e57: cluster_list_add_tail.part.26 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/swapfile.c (ffffffff8124df15)
Location: mm/swapfile.c:337
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:free_cluster
  - mm/swapfile.c:__free_cluster
Direct callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:free_cluster
  - mm/swapfile.c:__free_cluster
```
**Symbols:**

```
ffffffff81248df0-ffffffff81248e57: cluster_list_add_tail.part.30 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/swapfile.c (ffffffff812622d0)
Location: mm/swapfile.c:365
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:free_cluster
  - mm/swapfile.c:__free_cluster
Direct callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:free_cluster
  - mm/swapfile.c:__free_cluster
```
**Symbols:**

```
ffffffff8125d490-ffffffff8125d4f7: cluster_list_add_tail.part.30 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/swapfile.c (ffffffff8127d0fa)
Location: mm/swapfile.c:400
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:free_cluster
  - mm/swapfile.c:__free_cluster
Direct callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:free_cluster
  - mm/swapfile.c:__free_cluster
```
**Symbols:**

```
ffffffff81278750-ffffffff812787b5: cluster_list_add_tail.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/swapfile.c (ffffffff8128cbd1)
Location: mm/swapfile.c:400
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:free_cluster
  - mm/swapfile.c:__free_cluster
Direct callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:free_cluster
  - mm/swapfile.c:__free_cluster
```
**Symbols:**

```
ffffffff81288240-ffffffff812882a5: cluster_list_add_tail.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff812ba966)
Location: mm/swapfile.c:399
Inline: True
Inline callers:
  - mm/swapfile.c:setup_swap_map_and_extents
  - mm/swapfile.c:setup_swap_map_and_extents
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:swap_free_cluster
  - mm/swapfile.c:swap_free_cluster
  - mm/swapfile.c:swap_do_scheduled_discard
  - mm/swapfile.c:swap_do_scheduled_discard
  - mm/swapfile.c:swap_cluster_schedule_discard
  - mm/swapfile.c:swap_cluster_schedule_discard
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff812c63f6)
Location: mm/swapfile.c:412
Inline: True
Inline callers:
  - mm/swapfile.c:setup_swap_map_and_extents
  - mm/swapfile.c:setup_swap_map_and_extents
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:swap_free_cluster
  - mm/swapfile.c:swap_free_cluster
  - mm/swapfile.c:swap_do_scheduled_discard
  - mm/swapfile.c:swap_do_scheduled_discard
  - mm/swapfile.c:swap_cluster_schedule_discard
  - mm/swapfile.c:swap_cluster_schedule_discard
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff812ccfc4)
Location: mm/swapfile.c:411
Inline: True
Inline callers:
  - mm/swapfile.c:setup_swap_map_and_extents
  - mm/swapfile.c:setup_swap_map_and_extents
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:put_swap_page
  - mm/swapfile.c:put_swap_page
  - mm/swapfile.c:swap_do_scheduled_discard
  - mm/swapfile.c:swap_do_scheduled_discard
  - mm/swapfile.c:swap_cluster_schedule_discard
  - mm/swapfile.c:swap_cluster_schedule_discard
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8131233a)
Location: mm/swapfile.c:411
Inline: True
Inline callers:
  - mm/swapfile.c:setup_swap_map_and_extents
  - mm/swapfile.c:setup_swap_map_and_extents
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:put_swap_page
  - mm/swapfile.c:put_swap_page
  - mm/swapfile.c:swap_do_scheduled_discard
  - mm/swapfile.c:swap_do_scheduled_discard
  - mm/swapfile.c:swap_cluster_schedule_discard
  - mm/swapfile.c:swap_cluster_schedule_discard
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8137d831)
Location: mm/swapfile.c:413
Inline: True
Inline callers:
  - mm/swapfile.c:setup_swap_map_and_extents
  - mm/swapfile.c:setup_swap_map_and_extents
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:put_swap_page
  - mm/swapfile.c:put_swap_page
  - mm/swapfile.c:swap_do_scheduled_discard
  - mm/swapfile.c:swap_do_scheduled_discard
  - mm/swapfile.c:swap_cluster_schedule_discard
  - mm/swapfile.c:swap_cluster_schedule_discard
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff813fb611)
Location: mm/swapfile.c:417
Inline: True
Inline callers:
  - mm/swapfile.c:setup_swap_map_and_extents
  - mm/swapfile.c:setup_swap_map_and_extents
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:put_swap_folio
  - mm/swapfile.c:put_swap_folio
  - mm/swapfile.c:swap_do_scheduled_discard
  - mm/swapfile.c:swap_do_scheduled_discard
  - mm/swapfile.c:swap_cluster_schedule_discard
  - mm/swapfile.c:swap_cluster_schedule_discard
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8142e57d)
Location: mm/swapfile.c:418
Inline: True
Inline callers:
  - mm/swapfile.c:setup_swap_map_and_extents
  - mm/swapfile.c:setup_swap_map_and_extents
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:swap_free_cluster
  - mm/swapfile.c:swap_free_cluster
  - mm/swapfile.c:swap_do_scheduled_discard
  - mm/swapfile.c:swap_do_scheduled_discard
  - mm/swapfile.c:swap_cluster_schedule_discard
  - mm/swapfile.c:swap_cluster_schedule_discard
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8146803d)
Location: mm/swapfile.c:420
Inline: True
Inline callers:
  - mm/swapfile.c:setup_swap_map_and_extents
  - mm/swapfile.c:setup_swap_map_and_extents
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:swap_free_cluster
  - mm/swapfile.c:swap_free_cluster
  - mm/swapfile.c:swap_do_scheduled_discard
  - mm/swapfile.c:swap_do_scheduled_discard
  - mm/swapfile.c:swap_cluster_schedule_discard
  - mm/swapfile.c:swap_cluster_schedule_discard
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/swapfile.c (ffff800010328344)
Location: mm/swapfile.c:400
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:__free_cluster
Direct callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:__free_cluster
```
**Symbols:**

```
ffff800010323110-ffff8000103231bc: cluster_list_add_tail.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/swapfile.c (c053f72c)
Location: mm/swapfile.c:400
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:__free_cluster
Direct callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:__free_cluster
```
**Symbols:**

```
c053b5fc-c053b674: cluster_list_add_tail.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/swapfile.c (c0000000003ff324)
Location: mm/swapfile.c:400
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:__free_cluster
Direct callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:__free_cluster
```
**Symbols:**

```
c0000000003f93c0-c0000000003f94a0: cluster_list_add_tail.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/swapfile.c (ffffffe000227f6a)
Location: mm/swapfile.c:400
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:__free_cluster
Direct callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:__free_cluster
```
**Symbols:**

```
ffffffe000223c78-ffffffe000223d36: cluster_list_add_tail.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/swapfile.c (ffffffff812851b1)
Location: mm/swapfile.c:400
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:free_cluster
  - mm/swapfile.c:__free_cluster
Direct callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:free_cluster
  - mm/swapfile.c:__free_cluster
```
**Symbols:**

```
ffffffff81280820-ffffffff81280885: cluster_list_add_tail.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/swapfile.c (ffffffff81277021)
Location: mm/swapfile.c:400
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:free_cluster
  - mm/swapfile.c:__free_cluster
Direct callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:free_cluster
  - mm/swapfile.c:__free_cluster
```
**Symbols:**

```
ffffffff81272690-ffffffff812726f5: cluster_list_add_tail.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/swapfile.c (ffffffff81282fc1)
Location: mm/swapfile.c:400
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:free_cluster
  - mm/swapfile.c:__free_cluster
Direct callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:free_cluster
  - mm/swapfile.c:__free_cluster
```
**Symbols:**

```
ffffffff8127e630-ffffffff8127e695: cluster_list_add_tail.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/swapfile.c (ffffffff81292ca6)
Location: mm/swapfile.c:400
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:free_cluster
  - mm/swapfile.c:__free_cluster
Direct callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:free_cluster
  - mm/swapfile.c:__free_cluster
```
**Symbols:**

```
ffffffff8128e560-ffffffff8128e5c1: cluster_list_add_tail.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
