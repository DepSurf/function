# Function: <code>iommu_feature</code>

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
In drivers/iommu/amd_iommu.c (ffffffff815323e7)
Location: drivers/iommu/amd_iommu_proto.h:93
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
```
```
In drivers/iommu/amd_iommu_init.c (ffffffff81532972)
Location: drivers/iommu/amd_iommu_proto.h:93
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:enable_iommus_v2
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/amd_iommu_init.c:state_next
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
In drivers/iommu/amd_iommu.c (ffffffff81586ba9)
Location: drivers/iommu/amd_iommu_proto.h:93
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
```
```
In drivers/iommu/amd_iommu_init.c (ffffffff81fd6a00)
Location: drivers/iommu/amd_iommu_proto.h:93
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/amd_iommu_init.c:enable_iommus_v2
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
In drivers/iommu/amd_iommu.c (ffffffff815b4169)
Location: drivers/iommu/amd_iommu_proto.h:88
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
```
```
In drivers/iommu/amd_iommu_init.c (ffffffff815b4416)
Location: drivers/iommu/amd_iommu_proto.h:88
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:enable_iommus_v2
  - drivers/iommu/amd_iommu_init.c:amd_iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:amd_iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:amd_iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:amd_iommu_init_pci
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
In drivers/iommu/amd_iommu.c (ffffffff815c9f04)
Location: drivers/iommu/amd_iommu_proto.h:82
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
```
```
In drivers/iommu/amd_iommu_init.c (ffffffff815ca633)
Location: drivers/iommu/amd_iommu_proto.h:82
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:enable_iommus_v2
  - drivers/iommu/amd_iommu_init.c:amd_iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:amd_iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:amd_iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:amd_iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:amd_iommu_init_pci
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
In drivers/iommu/amd_iommu.c (ffffffff816308d4)
Location: drivers/iommu/amd_iommu_proto.h:82
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
```
```
In drivers/iommu/amd_iommu_init.c (ffffffff81631081)
Location: drivers/iommu/amd_iommu_proto.h:82
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:enable_iommus_v2
  - drivers/iommu/amd_iommu_init.c:amd_iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:amd_iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:amd_iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:amd_iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:amd_iommu_init_pci
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
In drivers/iommu/amd_iommu.c (ffffffff816654f3)
Location: drivers/iommu/amd_iommu_proto.h:82
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:set_dte_entry
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
```
```
In drivers/iommu/amd_iommu_init.c (ffffffff8166c020)
Location: drivers/iommu/amd_iommu_proto.h:82
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:enable_iommus_v2
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_go_to_state
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
In drivers/iommu/amd_iommu.c (ffffffff81683dd3)
Location: drivers/iommu/amd_iommu_proto.h:88
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:set_dte_entry
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
```
```
In drivers/iommu/amd_iommu_init.c (ffffffff8168a4d0)
Location: drivers/iommu/amd_iommu_proto.h:88
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:enable_iommus_v2
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_go_to_state
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
In drivers/iommu/amd_iommu.c (ffffffff816bd285)
Location: drivers/iommu/amd_iommu_proto.h:76
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:set_dte_entry
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
```
```
In drivers/iommu/amd_iommu_init.c (ffffffff828fcd10)
Location: drivers/iommu/amd_iommu_proto.h:76
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/amd_iommu_init.c:enable_iommus_v2
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
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
In drivers/iommu/amd_iommu.c (ffffffff816e0265)
Location: drivers/iommu/amd_iommu_proto.h:76
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:set_dte_entry
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
```
```
In drivers/iommu/amd_iommu_init.c (ffffffff82905cf1)
Location: drivers/iommu/amd_iommu_proto.h:76
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/amd_iommu_init.c:enable_iommus_v2
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
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
In drivers/iommu/amd/iommu.c (ffffffff81798abb)
Location: drivers/iommu/amd/amd_iommu.h:78
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:set_dte_entry
  - drivers/iommu/amd/iommu.c:iommu_flush_all_caches
```
```
In drivers/iommu/amd/init.c (ffffffff8179aff0)
Location: drivers/iommu/amd/amd_iommu.h:78
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:enable_iommus_v2
  - drivers/iommu/amd/init.c:print_iommu_info
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/amd/init.c:iommu_init_pci
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
In drivers/iommu/amd/iommu.c (ffffffff817a7330)
Location: drivers/iommu/amd/amd_iommu.h:87
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:set_dte_entry
  - drivers/iommu/amd/iommu.c:iommu_flush_all_caches
```
```
In drivers/iommu/amd/init.c (ffffffff817a9280)
Location: drivers/iommu/amd/amd_iommu.h:87
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:enable_iommus_v2
  - drivers/iommu/amd/init.c:amd_iommu_init_pci
  - drivers/iommu/amd/init.c:print_iommu_info
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/amd/init.c:init_iommu_perf_ctr
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
In drivers/iommu/amd/iommu.c (ffffffff81788c67)
Location: drivers/iommu/amd/amd_iommu.h:88
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:set_dte_entry
  - drivers/iommu/amd/iommu.c:iommu_flush_all_caches
```
```
In drivers/iommu/amd/init.c (ffffffff8178af7a)
Location: drivers/iommu/amd/amd_iommu.h:88
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:enable_iommus_v2
  - drivers/iommu/amd/init.c:amd_iommu_init_pci
  - drivers/iommu/amd/init.c:amd_iommu_init_pci
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/amd/init.c:iommu_init_pci
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
In drivers/iommu/amd/iommu.c (ffffffff8180f887)
Location: drivers/iommu/amd/amd_iommu.h:89
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:set_dte_entry
  - drivers/iommu/amd/iommu.c:iommu_flush_all_caches
```
```
In drivers/iommu/amd/init.c (ffffffff8181247a)
Location: drivers/iommu/amd/amd_iommu.h:89
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:enable_iommus_v2
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:amd_iommu_init_pci
  - drivers/iommu/amd/init.c:amd_iommu_init_pci
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/amd/init.c:iommu_init_pci
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
In drivers/iommu/amd/iommu.c (ffffffff8194e9a4)
Location: drivers/iommu/amd/amd_iommu.h:88
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:set_dte_entry
  - drivers/iommu/amd/iommu.c:iommu_flush_all_caches
```
```
In drivers/iommu/amd/init.c (ffffffff8195339a)
Location: drivers/iommu/amd/amd_iommu.h:88
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:enable_iommus_v2
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:amd_iommu_init_pci
  - drivers/iommu/amd/init.c:amd_iommu_init_pci
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/amd/init.c:iommu_init_pci
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
In drivers/iommu/amd/iommu.c (ffffffff81ab3270)
Location: drivers/iommu/amd/amd_iommu.h:88
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:set_dte_entry
  - drivers/iommu/amd/iommu.c:iommu_flush_all_caches
```
```
In drivers/iommu/amd/init.c (ffffffff81ab8bea)
Location: drivers/iommu/amd/amd_iommu.h:88
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:enable_iommus_v2
  - drivers/iommu/amd/init.c:amd_iommu_init_pci
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/amd/init.c:iommu_init_pci
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
In drivers/iommu/amd/iommu.c (ffffffff81b00165)
Location: drivers/iommu/amd/amd_iommu.h:89
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:set_dte_entry
  - drivers/iommu/amd/iommu.c:iommu_flush_all_caches
```
```
In drivers/iommu/amd/init.c (ffffffff81b04f5a)
Location: drivers/iommu/amd/amd_iommu.h:89
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:enable_iommus_v2
  - drivers/iommu/amd/init.c:amd_iommu_init_pci
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/amd/init.c:iommu_init_pci
```
</details>
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
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816a5cb5)
Location: drivers/iommu/amd_iommu_proto.h:76
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:set_dte_entry
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
```
```
In drivers/iommu/amd_iommu_init.c (ffffffff828ed4d8)
Location: drivers/iommu/amd_iommu_proto.h:76
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/amd_iommu_init.c:enable_iommus_v2
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
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
In drivers/iommu/amd_iommu.c (ffffffff816836a5)
Location: drivers/iommu/amd_iommu_proto.h:76
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:set_dte_entry
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
```
```
In drivers/iommu/amd_iommu_init.c (ffffffff828e4965)
Location: drivers/iommu/amd_iommu_proto.h:76
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/amd_iommu_init.c:enable_iommus_v2
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
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
In drivers/iommu/amd_iommu.c (ffffffff816d3f25)
Location: drivers/iommu/amd_iommu_proto.h:76
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:set_dte_entry
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
```
```
In drivers/iommu/amd_iommu_init.c (ffffffff82901014)
Location: drivers/iommu/amd_iommu_proto.h:76
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/amd_iommu_init.c:enable_iommus_v2
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
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
In drivers/iommu/amd_iommu.c (ffffffff816ee625)
Location: drivers/iommu/amd_iommu_proto.h:76
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:set_dte_entry
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
```
```
In drivers/iommu/amd_iommu_init.c (ffffffff82906d53)
Location: drivers/iommu/amd_iommu_proto.h:76
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/amd_iommu_init.c:enable_iommus_v2
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
```
</details>
</li>
</ul>

## Differences
