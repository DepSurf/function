# Function: <code>nd_device_lock</code>

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
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/core.c (ffffffff8172bf75)
Location: drivers/nvdimm/nd-core.h:235
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:flush_regions_dimms
  - drivers/nvdimm/core.c:flush_namespaces
```
```
In drivers/nvdimm/bus.c (ffffffff8172e139)
Location: drivers/nvdimm/nd-core.h:235
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/nvdimm/bus.c:nd_device_notify
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff8172fb25)
Location: drivers/nvdimm/nd-core.h:235
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:security_store
```
```
In drivers/nvdimm/region_devs.c (ffffffff81730ef6)
Location: drivers/nvdimm/nd-core.h:235
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:region_badblocks_show
  - drivers/nvdimm/region_devs.c:max_available_extent_show
  - drivers/nvdimm/region_devs.c:available_size_show
  - drivers/nvdimm/region_devs.c:set_cookie_show
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff81736539)
Location: drivers/nvdimm/nd-core.h:235
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:mode_show
  - drivers/nvdimm/namespace_devs.c:holder_class_show
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:holder_show
  - drivers/nvdimm/namespace_devs.c:sector_size_store
  - drivers/nvdimm/namespace_devs.c:uuid_store
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
```
```
In drivers/nvdimm/btt_devs.c (ffffffff8173b7b2)
Location: drivers/nvdimm/nd-core.h:235
Inline: True
Inline callers:
  - drivers/nvdimm/btt_devs.c:size_show
  - drivers/nvdimm/btt_devs.c:namespace_store
  - drivers/nvdimm/btt_devs.c:uuid_store
  - drivers/nvdimm/btt_devs.c:sector_size_store
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff8173c248)
Location: drivers/nvdimm/nd-core.h:235
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:size_show
  - drivers/nvdimm/pfn_devs.c:resource_show
  - drivers/nvdimm/pfn_devs.c:namespace_store
  - drivers/nvdimm/pfn_devs.c:uuid_store
  - drivers/nvdimm/pfn_devs.c:align_store
  - drivers/nvdimm/pfn_devs.c:mode_store
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
In drivers/nvdimm/core.c (ffffffff817501c5)
Location: drivers/nvdimm/nd-core.h:221
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:flush_regions_dimms
  - drivers/nvdimm/core.c:flush_namespaces
```
```
In drivers/nvdimm/bus.c (ffffffff817523d9)
Location: drivers/nvdimm/nd-core.h:221
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/nvdimm/bus.c:nd_device_notify
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff81752b85)
Location: drivers/nvdimm/nd-core.h:221
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:security_store
```
```
In drivers/nvdimm/region_devs.c (ffffffff81754fe2)
Location: drivers/nvdimm/nd-core.h:221
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:region_badblocks_show
  - drivers/nvdimm/region_devs.c:max_available_extent_show
  - drivers/nvdimm/region_devs.c:available_size_show
  - drivers/nvdimm/region_devs.c:set_cookie_show
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff8175a2c9)
Location: drivers/nvdimm/nd-core.h:221
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:mode_show
  - drivers/nvdimm/namespace_devs.c:holder_class_show
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:holder_show
  - drivers/nvdimm/namespace_devs.c:sector_size_store
  - drivers/nvdimm/namespace_devs.c:uuid_store
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
```
```
In drivers/nvdimm/btt_devs.c (ffffffff8175f47e)
Location: drivers/nvdimm/nd-core.h:221
Inline: True
Inline callers:
  - drivers/nvdimm/btt_devs.c:size_show
  - drivers/nvdimm/btt_devs.c:namespace_store
  - drivers/nvdimm/btt_devs.c:uuid_store
  - drivers/nvdimm/btt_devs.c:sector_size_store
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff8175fef8)
Location: drivers/nvdimm/nd-core.h:221
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:size_show
  - drivers/nvdimm/pfn_devs.c:resource_show
  - drivers/nvdimm/pfn_devs.c:namespace_store
  - drivers/nvdimm/pfn_devs.c:uuid_store
  - drivers/nvdimm/pfn_devs.c:align_store
  - drivers/nvdimm/pfn_devs.c:mode_store
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
In drivers/nvdimm/core.c (ffffffff8180e8b5)
Location: drivers/nvdimm/nd-core.h:233
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:flush_regions_dimms
  - drivers/nvdimm/core.c:flush_namespaces
```
```
In drivers/nvdimm/bus.c (ffffffff81810d76)
Location: drivers/nvdimm/nd-core.h:233
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/nvdimm/bus.c:nvdimm_region_notify
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff818115c5)
Location: drivers/nvdimm/nd-core.h:233
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:security_store
```
```
In drivers/nvdimm/region_devs.c (ffffffff81813e02)
Location: drivers/nvdimm/nd-core.h:233
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:region_badblocks_show
  - drivers/nvdimm/region_devs.c:max_available_extent_show
  - drivers/nvdimm/region_devs.c:available_size_show
  - drivers/nvdimm/region_devs.c:set_cookie_show
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff81819de9)
Location: drivers/nvdimm/nd-core.h:233
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:mode_show
  - drivers/nvdimm/namespace_devs.c:holder_class_show
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:holder_show
  - drivers/nvdimm/namespace_devs.c:sector_size_store
  - drivers/nvdimm/namespace_devs.c:uuid_store
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
```
```
In drivers/nvdimm/btt_devs.c (ffffffff8181f2be)
Location: drivers/nvdimm/nd-core.h:233
Inline: True
Inline callers:
  - drivers/nvdimm/btt_devs.c:size_show
  - drivers/nvdimm/btt_devs.c:namespace_store
  - drivers/nvdimm/btt_devs.c:uuid_store
  - drivers/nvdimm/btt_devs.c:sector_size_store
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff8181f9f8)
Location: drivers/nvdimm/nd-core.h:233
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:size_show
  - drivers/nvdimm/pfn_devs.c:resource_show
  - drivers/nvdimm/pfn_devs.c:namespace_store
  - drivers/nvdimm/pfn_devs.c:uuid_store
  - drivers/nvdimm/pfn_devs.c:align_store
  - drivers/nvdimm/pfn_devs.c:mode_store
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
In drivers/nvdimm/core.c (ffffffff8181d425)
Location: drivers/nvdimm/nd-core.h:234
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:flush_regions_dimms
  - drivers/nvdimm/core.c:flush_namespaces
```
```
In drivers/nvdimm/bus.c (ffffffff8181fcb6)
Location: drivers/nvdimm/nd-core.h:234
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/nvdimm/bus.c:nvdimm_region_notify
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff81820481)
Location: drivers/nvdimm/nd-core.h:234
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:security_store
  - drivers/nvdimm/dimm_devs.c:available_slots_show
```
```
In drivers/nvdimm/region_devs.c (ffffffff81822ff2)
Location: drivers/nvdimm/nd-core.h:234
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:region_badblocks_show
  - drivers/nvdimm/region_devs.c:max_available_extent_show
  - drivers/nvdimm/region_devs.c:available_size_show
  - drivers/nvdimm/region_devs.c:set_cookie_show
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff81828f09)
Location: drivers/nvdimm/nd-core.h:234
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:mode_show
  - drivers/nvdimm/namespace_devs.c:holder_class_show
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:holder_show
  - drivers/nvdimm/namespace_devs.c:sector_size_store
  - drivers/nvdimm/namespace_devs.c:uuid_store
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
```
```
In drivers/nvdimm/btt_devs.c (ffffffff8182e1fe)
Location: drivers/nvdimm/nd-core.h:234
Inline: True
Inline callers:
  - drivers/nvdimm/btt_devs.c:size_show
  - drivers/nvdimm/btt_devs.c:namespace_store
  - drivers/nvdimm/btt_devs.c:uuid_store
  - drivers/nvdimm/btt_devs.c:sector_size_store
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff8182e928)
Location: drivers/nvdimm/nd-core.h:234
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:size_show
  - drivers/nvdimm/pfn_devs.c:resource_show
  - drivers/nvdimm/pfn_devs.c:namespace_store
  - drivers/nvdimm/pfn_devs.c:uuid_store
  - drivers/nvdimm/pfn_devs.c:align_store
  - drivers/nvdimm/pfn_devs.c:mode_store
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
In drivers/nvdimm/core.c (ffffffff818007b5)
Location: drivers/nvdimm/nd-core.h:234
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:flush_regions_dimms
  - drivers/nvdimm/core.c:flush_namespaces
```
```
In drivers/nvdimm/bus.c (ffffffff81802fa8)
Location: drivers/nvdimm/nd-core.h:234
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/nvdimm/bus.c:nvdimm_region_notify
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff81803761)
Location: drivers/nvdimm/nd-core.h:234
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:security_store
  - drivers/nvdimm/dimm_devs.c:available_slots_show
```
```
In drivers/nvdimm/region_devs.c (ffffffff81806152)
Location: drivers/nvdimm/nd-core.h:234
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:region_badblocks_show
  - drivers/nvdimm/region_devs.c:max_available_extent_show
  - drivers/nvdimm/region_devs.c:available_size_show
  - drivers/nvdimm/region_devs.c:set_cookie_show
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff8180c129)
Location: drivers/nvdimm/nd-core.h:234
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:mode_show
  - drivers/nvdimm/namespace_devs.c:holder_class_show
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:holder_show
  - drivers/nvdimm/namespace_devs.c:sector_size_store
  - drivers/nvdimm/namespace_devs.c:uuid_store
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
```
```
In drivers/nvdimm/btt_devs.c (ffffffff818114ce)
Location: drivers/nvdimm/nd-core.h:234
Inline: True
Inline callers:
  - drivers/nvdimm/btt_devs.c:size_show
  - drivers/nvdimm/btt_devs.c:namespace_store
  - drivers/nvdimm/btt_devs.c:uuid_store
  - drivers/nvdimm/btt_devs.c:sector_size_store
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff81811bf8)
Location: drivers/nvdimm/nd-core.h:234
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:size_show
  - drivers/nvdimm/pfn_devs.c:resource_show
  - drivers/nvdimm/pfn_devs.c:namespace_store
  - drivers/nvdimm/pfn_devs.c:uuid_store
  - drivers/nvdimm/pfn_devs.c:align_store
  - drivers/nvdimm/pfn_devs.c:mode_store
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
In drivers/nvdimm/core.c (ffffffff8188abb5)
Location: drivers/nvdimm/nd-core.h:234
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:flush_regions_dimms
  - drivers/nvdimm/core.c:flush_namespaces
```
```
In drivers/nvdimm/bus.c (ffffffff8188d502)
Location: drivers/nvdimm/nd-core.h:234
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/nvdimm/bus.c:nvdimm_region_notify
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff8188e2a1)
Location: drivers/nvdimm/nd-core.h:234
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:security_store
  - drivers/nvdimm/dimm_devs.c:available_slots_show
```
```
In drivers/nvdimm/region_devs.c (ffffffff81890442)
Location: drivers/nvdimm/nd-core.h:234
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:region_badblocks_show
  - drivers/nvdimm/region_devs.c:max_available_extent_show
  - drivers/nvdimm/region_devs.c:available_size_show
  - drivers/nvdimm/region_devs.c:set_cookie_show
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff81896749)
Location: drivers/nvdimm/nd-core.h:234
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:mode_show
  - drivers/nvdimm/namespace_devs.c:holder_class_show
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:holder_show
  - drivers/nvdimm/namespace_devs.c:sector_size_store
  - drivers/nvdimm/namespace_devs.c:uuid_store
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
```
```
In drivers/nvdimm/btt_devs.c (ffffffff8189b8be)
Location: drivers/nvdimm/nd-core.h:234
Inline: True
Inline callers:
  - drivers/nvdimm/btt_devs.c:size_show
  - drivers/nvdimm/btt_devs.c:namespace_store
  - drivers/nvdimm/btt_devs.c:uuid_store
  - drivers/nvdimm/btt_devs.c:sector_size_store
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff8189c228)
Location: drivers/nvdimm/nd-core.h:234
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:size_show
  - drivers/nvdimm/pfn_devs.c:resource_show
  - drivers/nvdimm/pfn_devs.c:namespace_store
  - drivers/nvdimm/pfn_devs.c:uuid_store
  - drivers/nvdimm/pfn_devs.c:align_store
  - drivers/nvdimm/pfn_devs.c:mode_store
```
</details>
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
In drivers/nvdimm/core.c (ffff800010950224)
Location: drivers/nvdimm/nd-core.h:221
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:flush_regions_dimms
  - drivers/nvdimm/core.c:flush_namespaces
```
```
In drivers/nvdimm/bus.c (ffff800010952a80)
Location: drivers/nvdimm/nd-core.h:221
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/nvdimm/bus.c:nd_device_notify
```
```
In drivers/nvdimm/dimm_devs.c (ffff8000109532c0)
Location: drivers/nvdimm/nd-core.h:221
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:security_store
```
```
In drivers/nvdimm/region_devs.c (ffff800010956080)
Location: drivers/nvdimm/nd-core.h:221
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:region_badblocks_show
  - drivers/nvdimm/region_devs.c:max_available_extent_show
  - drivers/nvdimm/region_devs.c:available_size_show
  - drivers/nvdimm/region_devs.c:set_cookie_show
```
```
In drivers/nvdimm/namespace_devs.c (ffff80001095bb94)
Location: drivers/nvdimm/nd-core.h:221
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:mode_show
  - drivers/nvdimm/namespace_devs.c:holder_class_show
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:holder_show
  - drivers/nvdimm/namespace_devs.c:sector_size_store
  - drivers/nvdimm/namespace_devs.c:uuid_store
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
```
```
In drivers/nvdimm/btt_devs.c (ffff800010960c24)
Location: drivers/nvdimm/nd-core.h:221
Inline: True
Inline callers:
  - drivers/nvdimm/btt_devs.c:size_show
  - drivers/nvdimm/btt_devs.c:namespace_store
  - drivers/nvdimm/btt_devs.c:uuid_store
  - drivers/nvdimm/btt_devs.c:sector_size_store
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
In drivers/nvdimm/core.c (c0000000009fc730)
Location: drivers/nvdimm/nd-core.h:221
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:flush_regions_dimms
  - drivers/nvdimm/core.c:flush_namespaces
```
```
In drivers/nvdimm/bus.c (c0000000009ffb54)
Location: drivers/nvdimm/nd-core.h:221
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/nvdimm/bus.c:nd_device_notify
```
```
In drivers/nvdimm/dimm_devs.c (c000000000a00714)
Location: drivers/nvdimm/nd-core.h:221
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:security_store
```
```
In drivers/nvdimm/region_devs.c (c000000000a03d20)
Location: drivers/nvdimm/nd-core.h:221
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:region_badblocks_show
  - drivers/nvdimm/region_devs.c:max_available_extent_show
  - drivers/nvdimm/region_devs.c:available_size_show
  - drivers/nvdimm/region_devs.c:set_cookie_show
```
```
In drivers/nvdimm/namespace_devs.c (c000000000a0ca4c)
Location: drivers/nvdimm/nd-core.h:221
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:mode_show
  - drivers/nvdimm/namespace_devs.c:holder_class_show
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:holder_show
  - drivers/nvdimm/namespace_devs.c:sector_size_store
  - drivers/nvdimm/namespace_devs.c:uuid_store
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
```
```
In drivers/nvdimm/btt_devs.c (c000000000a13fb0)
Location: drivers/nvdimm/nd-core.h:221
Inline: True
Inline callers:
  - drivers/nvdimm/btt_devs.c:size_show
  - drivers/nvdimm/btt_devs.c:namespace_store
  - drivers/nvdimm/btt_devs.c:uuid_store
  - drivers/nvdimm/btt_devs.c:sector_size_store
```
```
In drivers/nvdimm/pfn_devs.c (c000000000a14ff4)
Location: drivers/nvdimm/nd-core.h:221
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:size_show
  - drivers/nvdimm/pfn_devs.c:resource_show
  - drivers/nvdimm/pfn_devs.c:namespace_store
  - drivers/nvdimm/pfn_devs.c:uuid_store
  - drivers/nvdimm/pfn_devs.c:align_store
  - drivers/nvdimm/pfn_devs.c:mode_store
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
In drivers/nvdimm/core.c (ffffffe0005c04f8)
Location: drivers/nvdimm/nd-core.h:221
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:flush_regions_dimms
  - drivers/nvdimm/core.c:flush_namespaces
```
```
In drivers/nvdimm/bus.c (ffffffe0005c25f2)
Location: drivers/nvdimm/nd-core.h:221
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/nvdimm/bus.c:nd_device_notify
```
```
In drivers/nvdimm/dimm_devs.c (ffffffe0005c2c80)
Location: drivers/nvdimm/nd-core.h:221
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:security_store
```
```
In drivers/nvdimm/region_devs.c (ffffffe0005c54b8)
Location: drivers/nvdimm/nd-core.h:221
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:region_badblocks_show
  - drivers/nvdimm/region_devs.c:max_available_extent_show
  - drivers/nvdimm/region_devs.c:available_size_show
  - drivers/nvdimm/region_devs.c:set_cookie_show
```
```
In drivers/nvdimm/namespace_devs.c (ffffffe0005ca10c)
Location: drivers/nvdimm/nd-core.h:221
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:mode_show
  - drivers/nvdimm/namespace_devs.c:holder_class_show
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:holder_show
  - drivers/nvdimm/namespace_devs.c:sector_size_store
  - drivers/nvdimm/namespace_devs.c:uuid_store
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
```
```
In drivers/nvdimm/btt_devs.c (ffffffe0005ce5dc)
Location: drivers/nvdimm/nd-core.h:221
Inline: True
Inline callers:
  - drivers/nvdimm/btt_devs.c:size_show
  - drivers/nvdimm/btt_devs.c:namespace_store
  - drivers/nvdimm/btt_devs.c:uuid_store
  - drivers/nvdimm/btt_devs.c:sector_size_store
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
In drivers/nvdimm/core.c (ffffffff817048b5)
Location: drivers/nvdimm/nd-core.h:221
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:flush_regions_dimms
  - drivers/nvdimm/core.c:flush_namespaces
```
```
In drivers/nvdimm/bus.c (ffffffff81706ac9)
Location: drivers/nvdimm/nd-core.h:221
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/nvdimm/bus.c:nd_device_notify
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff81707275)
Location: drivers/nvdimm/nd-core.h:221
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:security_store
```
```
In drivers/nvdimm/region_devs.c (ffffffff817096d2)
Location: drivers/nvdimm/nd-core.h:221
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:region_badblocks_show
  - drivers/nvdimm/region_devs.c:max_available_extent_show
  - drivers/nvdimm/region_devs.c:available_size_show
  - drivers/nvdimm/region_devs.c:set_cookie_show
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff8170e9b9)
Location: drivers/nvdimm/nd-core.h:221
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:mode_show
  - drivers/nvdimm/namespace_devs.c:holder_class_show
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:holder_show
  - drivers/nvdimm/namespace_devs.c:sector_size_store
  - drivers/nvdimm/namespace_devs.c:uuid_store
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
```
```
In drivers/nvdimm/btt_devs.c (ffffffff81713b6e)
Location: drivers/nvdimm/nd-core.h:221
Inline: True
Inline callers:
  - drivers/nvdimm/btt_devs.c:size_show
  - drivers/nvdimm/btt_devs.c:namespace_store
  - drivers/nvdimm/btt_devs.c:uuid_store
  - drivers/nvdimm/btt_devs.c:sector_size_store
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff817145e8)
Location: drivers/nvdimm/nd-core.h:221
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:size_show
  - drivers/nvdimm/pfn_devs.c:resource_show
  - drivers/nvdimm/pfn_devs.c:namespace_store
  - drivers/nvdimm/pfn_devs.c:uuid_store
  - drivers/nvdimm/pfn_devs.c:align_store
  - drivers/nvdimm/pfn_devs.c:mode_store
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
In drivers/nvdimm/core.c (ffffffff816d8335)
Location: drivers/nvdimm/nd-core.h:221
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:flush_regions_dimms
  - drivers/nvdimm/core.c:flush_namespaces
```
```
In drivers/nvdimm/bus.c (ffffffff816da549)
Location: drivers/nvdimm/nd-core.h:221
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/nvdimm/bus.c:nd_device_notify
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff816dacf5)
Location: drivers/nvdimm/nd-core.h:221
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:security_store
```
```
In drivers/nvdimm/region_devs.c (ffffffff816dd152)
Location: drivers/nvdimm/nd-core.h:221
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:region_badblocks_show
  - drivers/nvdimm/region_devs.c:max_available_extent_show
  - drivers/nvdimm/region_devs.c:available_size_show
  - drivers/nvdimm/region_devs.c:set_cookie_show
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff816e2439)
Location: drivers/nvdimm/nd-core.h:221
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:mode_show
  - drivers/nvdimm/namespace_devs.c:holder_class_show
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:holder_show
  - drivers/nvdimm/namespace_devs.c:sector_size_store
  - drivers/nvdimm/namespace_devs.c:uuid_store
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
```
```
In drivers/nvdimm/btt_devs.c (ffffffff816e75ee)
Location: drivers/nvdimm/nd-core.h:221
Inline: True
Inline callers:
  - drivers/nvdimm/btt_devs.c:size_show
  - drivers/nvdimm/btt_devs.c:namespace_store
  - drivers/nvdimm/btt_devs.c:uuid_store
  - drivers/nvdimm/btt_devs.c:sector_size_store
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff816e8068)
Location: drivers/nvdimm/nd-core.h:221
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:size_show
  - drivers/nvdimm/pfn_devs.c:resource_show
  - drivers/nvdimm/pfn_devs.c:namespace_store
  - drivers/nvdimm/pfn_devs.c:uuid_store
  - drivers/nvdimm/pfn_devs.c:align_store
  - drivers/nvdimm/pfn_devs.c:mode_store
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
In drivers/nvdimm/core.c (ffffffff81743685)
Location: drivers/nvdimm/nd-core.h:221
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:flush_regions_dimms
  - drivers/nvdimm/core.c:flush_namespaces
```
```
In drivers/nvdimm/bus.c (ffffffff81745899)
Location: drivers/nvdimm/nd-core.h:221
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/nvdimm/bus.c:nd_device_notify
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff81746045)
Location: drivers/nvdimm/nd-core.h:221
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:security_store
```
```
In drivers/nvdimm/region_devs.c (ffffffff817484a2)
Location: drivers/nvdimm/nd-core.h:221
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:region_badblocks_show
  - drivers/nvdimm/region_devs.c:max_available_extent_show
  - drivers/nvdimm/region_devs.c:available_size_show
  - drivers/nvdimm/region_devs.c:set_cookie_show
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff8174d789)
Location: drivers/nvdimm/nd-core.h:221
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:mode_show
  - drivers/nvdimm/namespace_devs.c:holder_class_show
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:holder_show
  - drivers/nvdimm/namespace_devs.c:sector_size_store
  - drivers/nvdimm/namespace_devs.c:uuid_store
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
```
```
In drivers/nvdimm/btt_devs.c (ffffffff8175293e)
Location: drivers/nvdimm/nd-core.h:221
Inline: True
Inline callers:
  - drivers/nvdimm/btt_devs.c:size_show
  - drivers/nvdimm/btt_devs.c:namespace_store
  - drivers/nvdimm/btt_devs.c:uuid_store
  - drivers/nvdimm/btt_devs.c:sector_size_store
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff817533b8)
Location: drivers/nvdimm/nd-core.h:221
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:size_show
  - drivers/nvdimm/pfn_devs.c:resource_show
  - drivers/nvdimm/pfn_devs.c:namespace_store
  - drivers/nvdimm/pfn_devs.c:uuid_store
  - drivers/nvdimm/pfn_devs.c:align_store
  - drivers/nvdimm/pfn_devs.c:mode_store
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
In drivers/nvdimm/core.c (ffffffff8175ead5)
Location: drivers/nvdimm/nd-core.h:221
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:flush_regions_dimms
  - drivers/nvdimm/core.c:flush_namespaces
```
```
In drivers/nvdimm/bus.c (ffffffff81760cd9)
Location: drivers/nvdimm/nd-core.h:221
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/nvdimm/bus.c:nd_device_notify
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff81761485)
Location: drivers/nvdimm/nd-core.h:221
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:security_store
```
```
In drivers/nvdimm/region_devs.c (ffffffff81763922)
Location: drivers/nvdimm/nd-core.h:221
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:region_badblocks_show
  - drivers/nvdimm/region_devs.c:max_available_extent_show
  - drivers/nvdimm/region_devs.c:available_size_show
  - drivers/nvdimm/region_devs.c:set_cookie_show
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff81768c09)
Location: drivers/nvdimm/nd-core.h:221
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:mode_show
  - drivers/nvdimm/namespace_devs.c:holder_class_show
  - drivers/nvdimm/namespace_devs.c:holder_class_store
  - drivers/nvdimm/namespace_devs.c:holder_show
  - drivers/nvdimm/namespace_devs.c:sector_size_store
  - drivers/nvdimm/namespace_devs.c:uuid_store
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
```
```
In drivers/nvdimm/btt_devs.c (ffffffff8176ddae)
Location: drivers/nvdimm/nd-core.h:221
Inline: True
Inline callers:
  - drivers/nvdimm/btt_devs.c:size_show
  - drivers/nvdimm/btt_devs.c:namespace_store
  - drivers/nvdimm/btt_devs.c:uuid_store
  - drivers/nvdimm/btt_devs.c:sector_size_store
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff8176e828)
Location: drivers/nvdimm/nd-core.h:221
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:size_show
  - drivers/nvdimm/pfn_devs.c:resource_show
  - drivers/nvdimm/pfn_devs.c:namespace_store
  - drivers/nvdimm/pfn_devs.c:uuid_store
  - drivers/nvdimm/pfn_devs.c:align_store
  - drivers/nvdimm/pfn_devs.c:mode_store
```
</details>
</li>
</ul>

## Differences
