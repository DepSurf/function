# Function: <code>to_ndns</code>

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
In drivers/nvdimm/namespace_devs.c (ffffffff8159d53c)
Location: include/linux/nd.h:47
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
```
```
In drivers/nvdimm/claim.c (ffffffff815a0ea7)
Location: include/linux/nd.h:47
Inline: True
Inline callers:
  - drivers/nvdimm/claim.c:nd_namespace_store
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
In drivers/nvdimm/namespace_devs.c (ffffffff815f352e)
Location: include/linux/nd.h:54
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:size_show
```
```
In drivers/nvdimm/claim.c (ffffffff815f725b)
Location: include/linux/nd.h:54
Inline: True
Inline callers:
  - drivers/nvdimm/claim.c:nd_namespace_store
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
In drivers/nvdimm/namespace_devs.c (ffffffff81620dfe)
Location: include/linux/nd.h:54
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:size_show
```
```
In drivers/nvdimm/claim.c (ffffffff816254cb)
Location: include/linux/nd.h:54
Inline: True
Inline callers:
  - drivers/nvdimm/claim.c:nd_namespace_store
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
In drivers/nvdimm/bus.c (ffffffff8162d425)
Location: include/linux/nd.h:65
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_pmem_forget_poison_check
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff816357b4)
Location: include/linux/nd.h:65
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:size_show
```
```
In drivers/nvdimm/claim.c (ffffffff8163a4ba)
Location: include/linux/nd.h:65
Inline: True
Inline callers:
  - drivers/nvdimm/claim.c:nd_namespace_store
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
In drivers/nvdimm/bus.c (ffffffff81695bd5)
Location: include/linux/nd.h:65
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_pmem_forget_poison_check
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff8169e144)
Location: include/linux/nd.h:65
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:size_show
```
```
In drivers/nvdimm/claim.c (ffffffff816a30c0)
Location: include/linux/nd.h:65
Inline: True
Inline callers:
  - drivers/nvdimm/claim.c:nd_namespace_store
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
In drivers/nvdimm/bus.c (ffffffff816d1d08)
Location: include/linux/nd.h:65
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_pmem_forget_poison_check
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff816da50e)
Location: include/linux/nd.h:65
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:force_raw_show
  - drivers/nvdimm/namespace_devs.c:force_raw_store
  - drivers/nvdimm/namespace_devs.c:mode_show
  - drivers/nvdimm/namespace_devs.c:holder_class_show
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:holder_show
  - drivers/nvdimm/namespace_devs.c:sector_size_store
  - drivers/nvdimm/namespace_devs.c:uuid_store
  - drivers/nvdimm/namespace_devs.c:size_show
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/namespace_devs.c:nd_namespace_label_update
  - drivers/nvdimm/namespace_devs.c:nd_namespace_label_update
```
```
In drivers/nvdimm/claim.c (ffffffff816df1bc)
Location: include/linux/nd.h:65
Inline: True
Inline callers:
  - drivers/nvdimm/claim.c:nd_namespace_store
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
In drivers/nvdimm/bus.c (ffffffff816f3398)
Location: include/linux/nd.h:65
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_pmem_forget_poison_check
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff816fc4a8)
Location: include/linux/nd.h:65
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:force_raw_show
  - drivers/nvdimm/namespace_devs.c:force_raw_store
  - drivers/nvdimm/namespace_devs.c:mode_show
  - drivers/nvdimm/namespace_devs.c:holder_class_show
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:holder_show
  - drivers/nvdimm/namespace_devs.c:sector_size_store
  - drivers/nvdimm/namespace_devs.c:uuid_store
  - drivers/nvdimm/namespace_devs.c:size_show
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/namespace_devs.c:nd_namespace_label_update
  - drivers/nvdimm/namespace_devs.c:nd_namespace_label_update
```
```
In drivers/nvdimm/claim.c (ffffffff817015a0)
Location: include/linux/nd.h:65
Inline: True
Inline callers:
  - drivers/nvdimm/claim.c:nd_namespace_store
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
In drivers/nvdimm/bus.c (ffffffff8172c8ed)
Location: include/linux/nd.h:57
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_pmem_forget_poison_check
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff81736568)
Location: include/linux/nd.h:57
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:force_raw_show
  - drivers/nvdimm/namespace_devs.c:force_raw_store
  - drivers/nvdimm/namespace_devs.c:mode_show
  - drivers/nvdimm/namespace_devs.c:holder_class_show
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:holder_show
  - drivers/nvdimm/namespace_devs.c:sector_size_store
  - drivers/nvdimm/namespace_devs.c:uuid_store
  - drivers/nvdimm/namespace_devs.c:size_show
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/namespace_devs.c:nd_namespace_label_update
  - drivers/nvdimm/namespace_devs.c:nd_namespace_label_update
```
```
In drivers/nvdimm/claim.c (ffffffff8173b41e)
Location: include/linux/nd.h:57
Inline: True
Inline callers:
  - drivers/nvdimm/claim.c:nd_namespace_store
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
In drivers/nvdimm/bus.c (ffffffff81750b0d)
Location: include/linux/nd.h:57
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_pmem_forget_poison_check
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff8175a2f8)
Location: include/linux/nd.h:57
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:force_raw_show
  - drivers/nvdimm/namespace_devs.c:force_raw_store
  - drivers/nvdimm/namespace_devs.c:mode_show
  - drivers/nvdimm/namespace_devs.c:holder_class_show
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:holder_show
  - drivers/nvdimm/namespace_devs.c:sector_size_store
  - drivers/nvdimm/namespace_devs.c:uuid_store
  - drivers/nvdimm/namespace_devs.c:size_show
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/namespace_devs.c:nd_namespace_label_update
  - drivers/nvdimm/namespace_devs.c:nd_namespace_label_update
```
```
In drivers/nvdimm/claim.c (ffffffff8175f0ee)
Location: include/linux/nd.h:57
Inline: True
Inline callers:
  - drivers/nvdimm/claim.c:nd_namespace_store
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
In drivers/nvdimm/bus.c (ffffffff8180f37d)
Location: include/linux/nd.h:57
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_pmem_forget_poison_check
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff81819e18)
Location: include/linux/nd.h:57
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:force_raw_show
  - drivers/nvdimm/namespace_devs.c:force_raw_store
  - drivers/nvdimm/namespace_devs.c:mode_show
  - drivers/nvdimm/namespace_devs.c:holder_class_show
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:holder_show
  - drivers/nvdimm/namespace_devs.c:sector_size_store
  - drivers/nvdimm/namespace_devs.c:uuid_store
  - drivers/nvdimm/namespace_devs.c:size_show
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/namespace_devs.c:nd_namespace_label_update
  - drivers/nvdimm/namespace_devs.c:nd_namespace_label_update
```
```
In drivers/nvdimm/claim.c (ffffffff8181eb83)
Location: include/linux/nd.h:57
Inline: True
Inline callers:
  - drivers/nvdimm/claim.c:nd_namespace_store
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
In drivers/nvdimm/bus.c (ffffffff8181e2bd)
Location: include/linux/nd.h:57
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_pmem_forget_poison_check
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff81828f38)
Location: include/linux/nd.h:57
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:force_raw_show
  - drivers/nvdimm/namespace_devs.c:force_raw_store
  - drivers/nvdimm/namespace_devs.c:mode_show
  - drivers/nvdimm/namespace_devs.c:holder_class_show
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:holder_show
  - drivers/nvdimm/namespace_devs.c:sector_size_store
  - drivers/nvdimm/namespace_devs.c:uuid_store
  - drivers/nvdimm/namespace_devs.c:size_show
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/namespace_devs.c:nd_namespace_label_update
  - drivers/nvdimm/namespace_devs.c:nd_namespace_label_update
```
```
In drivers/nvdimm/claim.c (ffffffff8182dac3)
Location: include/linux/nd.h:57
Inline: True
Inline callers:
  - drivers/nvdimm/claim.c:nd_namespace_store
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
In drivers/nvdimm/bus.c (ffffffff818015bc)
Location: include/linux/nd.h:58
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_pmem_forget_poison_check
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff8180c158)
Location: include/linux/nd.h:58
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:force_raw_show
  - drivers/nvdimm/namespace_devs.c:force_raw_store
  - drivers/nvdimm/namespace_devs.c:mode_show
  - drivers/nvdimm/namespace_devs.c:holder_class_show
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:holder_show
  - drivers/nvdimm/namespace_devs.c:sector_size_store
  - drivers/nvdimm/namespace_devs.c:uuid_store
  - drivers/nvdimm/namespace_devs.c:size_show
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/namespace_devs.c:nd_namespace_label_update
  - drivers/nvdimm/namespace_devs.c:nd_namespace_label_update
```
```
In drivers/nvdimm/claim.c (ffffffff81810d0c)
Location: include/linux/nd.h:58
Inline: True
Inline callers:
  - drivers/nvdimm/claim.c:nd_namespace_store
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
In drivers/nvdimm/bus.c (ffffffff8188ba4c)
Location: include/linux/nd.h:58
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_pmem_forget_poison_check
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff81896778)
Location: include/linux/nd.h:58
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:force_raw_show
  - drivers/nvdimm/namespace_devs.c:force_raw_store
  - drivers/nvdimm/namespace_devs.c:mode_show
  - drivers/nvdimm/namespace_devs.c:holder_class_show
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:holder_show
  - drivers/nvdimm/namespace_devs.c:sector_size_store
  - drivers/nvdimm/namespace_devs.c:uuid_store
  - drivers/nvdimm/namespace_devs.c:size_show
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/namespace_devs.c:nd_namespace_label_update
  - drivers/nvdimm/namespace_devs.c:nd_namespace_label_update
```
```
In drivers/nvdimm/claim.c (ffffffff8189b36c)
Location: include/linux/nd.h:58
Inline: True
Inline callers:
  - drivers/nvdimm/claim.c:nd_namespace_store
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
In drivers/nvdimm/bus.c (ffffffff819d4ea8)
Location: include/linux/nd.h:110
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_pmem_forget_poison_check
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff819e0e51)
Location: include/linux/nd.h:110
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:size_show
```
```
In drivers/nvdimm/claim.c (ffffffff819e4af0)
Location: include/linux/nd.h:110
Inline: True
Inline callers:
  - drivers/nvdimm/claim.c:nd_namespace_store
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
In drivers/nvdimm/bus.c (ffffffff81b4f828)
Location: include/linux/nd.h:110
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_pmem_forget_poison_check
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff81b5c90d)
Location: include/linux/nd.h:110
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:size_show
```
```
In drivers/nvdimm/claim.c (ffffffff81b60890)
Location: include/linux/nd.h:110
Inline: True
Inline callers:
  - drivers/nvdimm/claim.c:nd_namespace_store
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
In drivers/nvdimm/bus.c (ffffffff81ba2de8)
Location: include/linux/nd.h:110
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_pmem_forget_poison_check
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff81baff11)
Location: include/linux/nd.h:110
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:size_show
```
```
In drivers/nvdimm/claim.c (ffffffff81bb3e1c)
Location: include/linux/nd.h:110
Inline: True
Inline callers:
  - drivers/nvdimm/claim.c:nd_namespace_store
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
In drivers/nvdimm/bus.c (ffffffff81bf6fa8)
Location: include/linux/nd.h:110
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_pmem_forget_poison_check
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff81c04341)
Location: include/linux/nd.h:110
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:size_show
```
```
In drivers/nvdimm/claim.c (ffffffff81c0836c)
Location: include/linux/nd.h:110
Inline: True
Inline callers:
  - drivers/nvdimm/claim.c:nd_namespace_store
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
In drivers/nvdimm/bus.c (ffff8000109509e4)
Location: include/linux/nd.h:57
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_pmem_forget_poison_check
```
```
In drivers/nvdimm/namespace_devs.c (ffff80001095bac4)
Location: include/linux/nd.h:57
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:force_raw_show
  - drivers/nvdimm/namespace_devs.c:force_raw_store
  - drivers/nvdimm/namespace_devs.c:mode_show
  - drivers/nvdimm/namespace_devs.c:mode_show
  - drivers/nvdimm/namespace_devs.c:holder_class_show
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:holder_show
  - drivers/nvdimm/namespace_devs.c:sector_size_store
  - drivers/nvdimm/namespace_devs.c:uuid_store
  - drivers/nvdimm/namespace_devs.c:size_show
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/namespace_devs.c:nd_namespace_label_update
  - drivers/nvdimm/namespace_devs.c:nd_namespace_label_update
```
```
In drivers/nvdimm/claim.c (ffff8000109608cc)
Location: include/linux/nd.h:57
Inline: True
Inline callers:
  - drivers/nvdimm/claim.c:nd_namespace_store
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (c0000000009fd5f0)
Location: include/linux/nd.h:57
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_pmem_forget_poison_check
```
```
In drivers/nvdimm/namespace_devs.c (c000000000a0cc30)
Location: include/linux/nd.h:57
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:force_raw_show
  - drivers/nvdimm/namespace_devs.c:force_raw_store
  - drivers/nvdimm/namespace_devs.c:mode_show
  - drivers/nvdimm/namespace_devs.c:holder_class_show
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:holder_show
  - drivers/nvdimm/namespace_devs.c:sector_size_store
  - drivers/nvdimm/namespace_devs.c:uuid_store
  - drivers/nvdimm/namespace_devs.c:size_show
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/namespace_devs.c:nd_namespace_label_update
  - drivers/nvdimm/namespace_devs.c:nd_namespace_label_update
```
```
In drivers/nvdimm/claim.c (c000000000a13aa0)
Location: include/linux/nd.h:57
Inline: True
Inline callers:
  - drivers/nvdimm/claim.c:nd_namespace_store
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
In drivers/nvdimm/bus.c (ffffffe0005c0ba6)
Location: include/linux/nd.h:57
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_pmem_forget_poison_check
```
```
In drivers/nvdimm/namespace_devs.c (ffffffe0005ca036)
Location: include/linux/nd.h:57
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:force_raw_show
  - drivers/nvdimm/namespace_devs.c:force_raw_store
  - drivers/nvdimm/namespace_devs.c:mode_show
  - drivers/nvdimm/namespace_devs.c:mode_show
  - drivers/nvdimm/namespace_devs.c:holder_class_show
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:holder_show
  - drivers/nvdimm/namespace_devs.c:sector_size_store
  - drivers/nvdimm/namespace_devs.c:uuid_store
  - drivers/nvdimm/namespace_devs.c:size_show
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/namespace_devs.c:nd_namespace_label_update
  - drivers/nvdimm/namespace_devs.c:nd_namespace_label_update
```
```
In drivers/nvdimm/claim.c (ffffffe0005ce2ca)
Location: include/linux/nd.h:57
Inline: True
Inline callers:
  - drivers/nvdimm/claim.c:nd_namespace_store
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
In drivers/nvdimm/bus.c (ffffffff817051fd)
Location: include/linux/nd.h:57
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_pmem_forget_poison_check
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff8170e9e8)
Location: include/linux/nd.h:57
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:force_raw_show
  - drivers/nvdimm/namespace_devs.c:force_raw_store
  - drivers/nvdimm/namespace_devs.c:mode_show
  - drivers/nvdimm/namespace_devs.c:holder_class_show
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:holder_show
  - drivers/nvdimm/namespace_devs.c:sector_size_store
  - drivers/nvdimm/namespace_devs.c:uuid_store
  - drivers/nvdimm/namespace_devs.c:size_show
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/namespace_devs.c:nd_namespace_label_update
  - drivers/nvdimm/namespace_devs.c:nd_namespace_label_update
```
```
In drivers/nvdimm/claim.c (ffffffff817137de)
Location: include/linux/nd.h:57
Inline: True
Inline callers:
  - drivers/nvdimm/claim.c:nd_namespace_store
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
In drivers/nvdimm/bus.c (ffffffff816d8c7d)
Location: include/linux/nd.h:57
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_pmem_forget_poison_check
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff816e2468)
Location: include/linux/nd.h:57
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:force_raw_show
  - drivers/nvdimm/namespace_devs.c:force_raw_store
  - drivers/nvdimm/namespace_devs.c:mode_show
  - drivers/nvdimm/namespace_devs.c:holder_class_show
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:holder_show
  - drivers/nvdimm/namespace_devs.c:sector_size_store
  - drivers/nvdimm/namespace_devs.c:uuid_store
  - drivers/nvdimm/namespace_devs.c:size_show
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/namespace_devs.c:nd_namespace_label_update
  - drivers/nvdimm/namespace_devs.c:nd_namespace_label_update
```
```
In drivers/nvdimm/claim.c (ffffffff816e725e)
Location: include/linux/nd.h:57
Inline: True
Inline callers:
  - drivers/nvdimm/claim.c:nd_namespace_store
```
```
In drivers/nvdimm/pmem.c (ffffffff816eb617)
Location: include/linux/nd.h:57
Inline: True
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
In drivers/nvdimm/bus.c (ffffffff81743fcd)
Location: include/linux/nd.h:57
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_pmem_forget_poison_check
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff8174d7b8)
Location: include/linux/nd.h:57
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:force_raw_show
  - drivers/nvdimm/namespace_devs.c:force_raw_store
  - drivers/nvdimm/namespace_devs.c:mode_show
  - drivers/nvdimm/namespace_devs.c:holder_class_show
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:holder_show
  - drivers/nvdimm/namespace_devs.c:sector_size_store
  - drivers/nvdimm/namespace_devs.c:uuid_store
  - drivers/nvdimm/namespace_devs.c:size_show
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/namespace_devs.c:nd_namespace_label_update
  - drivers/nvdimm/namespace_devs.c:nd_namespace_label_update
```
```
In drivers/nvdimm/claim.c (ffffffff817525ae)
Location: include/linux/nd.h:57
Inline: True
Inline callers:
  - drivers/nvdimm/claim.c:nd_namespace_store
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
In drivers/nvdimm/bus.c (ffffffff8175f41d)
Location: include/linux/nd.h:57
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_pmem_forget_poison_check
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff81768c38)
Location: include/linux/nd.h:57
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:force_raw_show
  - drivers/nvdimm/namespace_devs.c:force_raw_store
  - drivers/nvdimm/namespace_devs.c:mode_show
  - drivers/nvdimm/namespace_devs.c:holder_class_show
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:holder_show
  - drivers/nvdimm/namespace_devs.c:sector_size_store
  - drivers/nvdimm/namespace_devs.c:uuid_store
  - drivers/nvdimm/namespace_devs.c:size_show
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/namespace_devs.c:nd_namespace_label_update
  - drivers/nvdimm/namespace_devs.c:nd_namespace_label_update
```
```
In drivers/nvdimm/claim.c (ffffffff8176da1e)
Location: include/linux/nd.h:57
Inline: True
Inline callers:
  - drivers/nvdimm/claim.c:nd_namespace_store
```
</details>
</li>
</ul>

## Differences
