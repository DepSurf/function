# Function: <code>PageKmemcg</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811a8e4d)
Location: include/linux/page-flags.h:660
Inline: True
Inline callers:
  - mm/page_alloc.c:free_hot_cold_page
  - mm/page_alloc.c:__free_pages_ok
```
```
In mm/memcontrol.c (ffffffff812215c9)
Location: include/linux/page-flags.h:660
Inline: True
Inline callers:
  - mm/memcontrol.c:uncharge_list
  - mm/memcontrol.c:memcg_kmem_uncharge
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
In mm/page_alloc.c (ffffffff811b93ea)
Location: include/linux/page-flags.h:676
Inline: True
Inline callers:
  - mm/page_alloc.c:free_hot_cold_page
  - mm/page_alloc.c:__free_pages_ok
```
```
In mm/memcontrol.c (ffffffff81233d39)
Location: include/linux/page-flags.h:676
Inline: True
Inline callers:
  - mm/memcontrol.c:uncharge_list
  - mm/memcontrol.c:memcg_kmem_uncharge
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
In mm/page_alloc.c (ffffffff811c1464)
Location: include/linux/page-flags.h:679
Inline: True
Inline callers:
  - mm/page_alloc.c:free_hot_cold_page
  - mm/page_alloc.c:__free_pages_ok
```
```
In mm/memcontrol.c (ffffffff8123f602)
Location: include/linux/page-flags.h:679
Inline: True
Inline callers:
  - mm/memcontrol.c:uncharge_list
  - mm/memcontrol.c:memcg_kmem_uncharge
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
In mm/page_alloc.c (ffffffff811d44f0)
Location: include/linux/page-flags.h:680
Inline: True
Inline callers:
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcp_prepare
```
```
In mm/memcontrol.c (ffffffff8125f309)
Location: include/linux/page-flags.h:680
Inline: True
Inline callers:
  - mm/memcontrol.c:uncharge_page
  - mm/memcontrol.c:memcg_kmem_uncharge
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
In mm/page_alloc.c (ffffffff811f5e00)
Location: include/linux/page-flags.h:695
Inline: True
Inline callers:
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcp_prepare
```
```
In mm/memcontrol.c (ffffffff812837c9)
Location: include/linux/page-flags.h:695
Inline: True
Inline callers:
  - mm/memcontrol.c:uncharge_page
  - mm/memcontrol.c:memcg_kmem_uncharge
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
In mm/page_alloc.c (ffffffff81207a9c)
Location: include/linux/page-flags.h:718
Inline: True
Inline callers:
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcp_prepare
```
```
In mm/memcontrol.c (ffffffff81297339)
Location: include/linux/page-flags.h:718
Inline: True
Inline callers:
  - mm/memcontrol.c:uncharge_page
  - mm/memcontrol.c:memcg_kmem_uncharge
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
In mm/page_alloc.c (ffffffff8126dc49)
Location: include/linux/page-flags.h:755
Inline: True
Inline callers:
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcp_prepare
```
```
In mm/memcontrol.c (ffffffff812b2e67)
Location: include/linux/page-flags.h:755
Inline: True
Inline callers:
  - mm/memcontrol.c:uncharge_page
  - mm/memcontrol.c:__memcg_kmem_uncharge
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
In mm/page_alloc.c (ffffffff8127ca69)
Location: include/linux/page-flags.h:771
Inline: True
Inline callers:
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcp_prepare
```
```
In mm/memcontrol.c (ffffffff812c4937)
Location: include/linux/page-flags.h:771
Inline: True
Inline callers:
  - mm/memcontrol.c:uncharge_page
  - mm/memcontrol.c:__memcg_kmem_uncharge
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
In mm/page_alloc.c (ffffffff812aee06)
Location: include/linux/page-flags.h:797
Inline: True
Inline callers:
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcp_prepare
```
```
In mm/memcontrol.c (ffffffff812f99be)
Location: include/linux/page-flags.h:797
Inline: True
Inline callers:
  - mm/memcontrol.c:uncharge_page
  - mm/memcontrol.c:__memcg_kmem_uncharge_page
```
</details>
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
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffff800010314588)
Location: include/linux/page-flags.h:771
Inline: True
Inline callers:
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcp_prepare
```
```
In mm/memcontrol.c (ffff80001036754c)
Location: include/linux/page-flags.h:771
Inline: True
Inline callers:
  - mm/memcontrol.c:uncharge_page
  - mm/memcontrol.c:__memcg_kmem_uncharge
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
In mm/page_alloc.c (c052e8ac)
Location: include/linux/page-flags.h:771
Inline: True
Inline callers:
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcp_prepare
```
```
In mm/memcontrol.c (c0558cc8)
Location: include/linux/page-flags.h:771
Inline: True
Inline callers:
  - mm/memcontrol.c:uncharge_page
  - mm/memcontrol.c:__memcg_kmem_uncharge
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
In mm/page_alloc.c (c0000000003e5be0)
Location: include/linux/page-flags.h:771
Inline: True
Inline callers:
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcp_prepare
```
```
In mm/memcontrol.c (c000000000454b58)
Location: include/linux/page-flags.h:771
Inline: True
Inline callers:
  - mm/memcontrol.c:uncharge_page
  - mm/memcontrol.c:__memcg_kmem_uncharge
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
In mm/page_alloc.c (ffffffe00021af6c)
Location: include/linux/page-flags.h:771
Inline: True
Inline callers:
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcp_prepare
```
```
In mm/memcontrol.c (ffffffe00024571e)
Location: include/linux/page-flags.h:771
Inline: True
Inline callers:
  - mm/memcontrol.c:uncharge_page
  - mm/memcontrol.c:__memcg_kmem_uncharge
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
In mm/page_alloc.c (ffffffff812750b9)
Location: include/linux/page-flags.h:771
Inline: True
Inline callers:
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcp_prepare
```
```
In mm/memcontrol.c (ffffffff812bcf17)
Location: include/linux/page-flags.h:771
Inline: True
Inline callers:
  - mm/memcontrol.c:uncharge_page
  - mm/memcontrol.c:__memcg_kmem_uncharge
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
In mm/page_alloc.c (ffffffff81267029)
Location: include/linux/page-flags.h:771
Inline: True
Inline callers:
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcp_prepare
```
```
In mm/memcontrol.c (ffffffff812ae057)
Location: include/linux/page-flags.h:771
Inline: True
Inline callers:
  - mm/memcontrol.c:uncharge_page
  - mm/memcontrol.c:__memcg_kmem_uncharge
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
In mm/page_alloc.c (ffffffff81272e59)
Location: include/linux/page-flags.h:771
Inline: True
Inline callers:
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcp_prepare
```
```
In mm/memcontrol.c (ffffffff812bad27)
Location: include/linux/page-flags.h:771
Inline: True
Inline callers:
  - mm/memcontrol.c:uncharge_page
  - mm/memcontrol.c:__memcg_kmem_uncharge
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
In mm/page_alloc.c (ffffffff81282919)
Location: include/linux/page-flags.h:771
Inline: True
Inline callers:
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcp_prepare
```
```
In mm/memcontrol.c (ffffffff812cb477)
Location: include/linux/page-flags.h:771
Inline: True
Inline callers:
  - mm/memcontrol.c:uncharge_page
  - mm/memcontrol.c:__memcg_kmem_uncharge
```
</details>
</li>
</ul>

## Differences
