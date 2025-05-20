# Function: <code>list_is_first</code>

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
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/compaction.c (0)
Location: include/linux/list.h:245
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/compaction.c (0)
Location: include/linux/list.h:245
Inline: True
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
In mm/compaction.c (ffffffff8127f4d0)
Location: include/linux/list.h:259
Inline: True
Inline callers:
  - mm/compaction.c:move_freelist_tail
```
```
In mm/page_reporting.c (ffffffff8130d132)
Location: include/linux/list.h:259
Inline: True
Inline callers:
  - mm/page_reporting.c:page_reporting_cycle
  - mm/page_reporting.c:page_reporting_cycle
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
In mm/compaction.c (ffffffff81289570)
Location: include/linux/list.h:259
Inline: True
Inline callers:
  - mm/compaction.c:move_freelist_tail
```
```
In mm/page_reporting.c (ffffffff81319082)
Location: include/linux/list.h:259
Inline: True
Inline callers:
  - mm/page_reporting.c:page_reporting_cycle
  - mm/page_reporting.c:page_reporting_cycle
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
In mm/compaction.c (ffffffff8128ebd3)
Location: include/linux/list.h:259
Inline: True
Inline callers:
  - mm/compaction.c:move_freelist_tail
```
```
In mm/page_reporting.c (ffffffff8131f26f)
Location: include/linux/list.h:259
Inline: True
Inline callers:
  - mm/page_reporting.c:page_reporting_cycle
  - mm/page_reporting.c:page_reporting_cycle
```
```
In drivers/base/power/domain.c (ffffffff817c9c7b)
Location: include/linux/list.h:259
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_summary_one
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
In mm/compaction.c (ffffffff812cea93)
Location: include/linux/list.h:259
Inline: True
Inline callers:
  - mm/compaction.c:move_freelist_tail
```
```
In mm/page_reporting.c (ffffffff8136c68a)
Location: include/linux/list.h:259
Inline: True
Inline callers:
  - mm/page_reporting.c:page_reporting_cycle
  - mm/page_reporting.c:page_reporting_cycle
```
```
In drivers/base/power/domain.c (ffffffff8185419b)
Location: include/linux/list.h:259
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_summary_one
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
In mm/compaction.c (ffffffff8132cbd3)
Location: include/linux/list.h:261
Inline: True
Inline callers:
  - mm/compaction.c:move_freelist_tail
```
```
In mm/page_reporting.c (ffffffff813ea886)
Location: include/linux/list.h:261
Inline: True
Inline callers:
  - mm/page_reporting.c:page_reporting_cycle
  - mm/page_reporting.c:page_reporting_cycle
```
```
In drivers/base/power/domain.c (ffffffff8199a75f)
Location: include/linux/list.h:261
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_summary_one
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
In mm/compaction.c (ffffffff813a31b3)
Location: include/linux/list.h:261
Inline: True
Inline callers:
  - mm/compaction.c:move_freelist_tail
```
```
In mm/page_reporting.c (ffffffff81472a26)
Location: include/linux/list.h:261
Inline: True
Inline callers:
  - mm/page_reporting.c:page_reporting_cycle
  - mm/page_reporting.c:page_reporting_cycle
```
```
In drivers/iommu/amd/init.c (ffffffff83ef3500)
Location: include/linux/list.h:261
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:init_iommu_all
```
```
In drivers/base/power/domain.c (ffffffff81b0ba1f)
Location: include/linux/list.h:261
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_summary_one
```
```
In drivers/net/ethernet/microchip/vcap/vcap_api.c (ffffffff81bf8f34)
Location: include/linux/list.h:261
Inline: True
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
In mm/compaction.c (ffffffff813d6763)
Location: include/linux/list.h:261
Inline: True
Inline callers:
  - mm/compaction.c:move_freelist_tail
```
```
In mm/page_reporting.c (ffffffff814a7195)
Location: include/linux/list.h:261
Inline: True
Inline callers:
  - mm/page_reporting.c:page_reporting_cycle
  - mm/page_reporting.c:page_reporting_cycle
```
```
In drivers/iommu/amd/init.c (ffffffff837190a6)
Location: include/linux/list.h:261
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:init_iommu_all
```
```
In drivers/base/power/domain.c (ffffffff81b59a5f)
Location: include/linux/list.h:261
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_summary_one
```
```
In drivers/net/ethernet/microchip/vcap/vcap_api.c (ffffffff81c5cd6c)
Location: include/linux/list.h:261
Inline: True
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
In mm/compaction.c (ffffffff814039b5)
Location: include/linux/list.h:342
Inline: True
Inline callers:
  - mm/compaction.c:fast_isolate_freepages
```
```
In mm/page_reporting.c (ffffffff814d8195)
Location: include/linux/list.h:342
Inline: True
Inline callers:
  - mm/page_reporting.c:page_reporting_cycle
  - mm/page_reporting.c:page_reporting_cycle
```
```
In drivers/pmdomain/core.c (ffffffff81aa141f)
Location: include/linux/list.h:342
Inline: True
Inline callers:
  - drivers/pmdomain/core.c:genpd_summary_one
```
```
In drivers/iommu/amd/init.c (ffffffff8394cba4)
Location: include/linux/list.h:342
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:init_iommu_all
```
```
In drivers/gpu/drm/drm_bridge.c (ffffffff81c80140)
Location: include/linux/list.h:342
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_bridge.c:select_bus_fmt_recursive
```
```
In drivers/net/ethernet/microchip/vcap/vcap_api.c (ffffffff81d1369c)
Location: include/linux/list.h:342
Inline: True
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
In virt/kvm/arm/vgic/vgic-its.c (0)
Location: include/linux/list.h:245
Inline: True
```
```
In mm/compaction.c (0)
Location: include/linux/list.h:245
Inline: True
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
In mm/compaction.c (c050c058)
Location: include/linux/list.h:245
Inline: True
Inline callers:
  - mm/compaction.c:move_freelist_tail
```
```
In drivers/dma/tegra20-apb-dma.c (c092b208)
Location: include/linux/list.h:245
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/compaction.c (0)
Location: include/linux/list.h:245
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/compaction.c (0)
Location: include/linux/list.h:245
Inline: True
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/compaction.c (0)
Location: include/linux/list.h:245
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/compaction.c (0)
Location: include/linux/list.h:245
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/compaction.c (0)
Location: include/linux/list.h:245
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/compaction.c (0)
Location: include/linux/list.h:245
Inline: True
```
</details>
</li>
</ul>

## Differences
