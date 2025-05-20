# Function: <code>nd_device_unlock</code>

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
In drivers/nvdimm/core.c (ffffffff8172bf8f)
Location: drivers/nvdimm/nd-core.h:240
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:flush_regions_dimms
  - drivers/nvdimm/core.c:flush_namespaces
```
```
In drivers/nvdimm/bus.c (ffffffff8172e1cb)
Location: drivers/nvdimm/nd-core.h:240
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/nvdimm/bus.c:nd_device_notify
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff8172fb72)
Location: drivers/nvdimm/nd-core.h:240
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:security_store
```
```
In drivers/nvdimm/region_devs.c (ffffffff81730f20)
Location: drivers/nvdimm/nd-core.h:240
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:region_badblocks_show
  - drivers/nvdimm/region_devs.c:max_available_extent_show
  - drivers/nvdimm/region_devs.c:available_size_show
  - drivers/nvdimm/region_devs.c:set_cookie_show
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff81736548)
Location: drivers/nvdimm/nd-core.h:240
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
In drivers/nvdimm/btt_devs.c (ffffffff8173b7e1)
Location: drivers/nvdimm/nd-core.h:240
Inline: True
Inline callers:
  - drivers/nvdimm/btt_devs.c:size_show
  - drivers/nvdimm/btt_devs.c:namespace_store
  - drivers/nvdimm/btt_devs.c:uuid_store
  - drivers/nvdimm/btt_devs.c:sector_size_store
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff8173c298)
Location: drivers/nvdimm/nd-core.h:240
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
In drivers/nvdimm/core.c (ffffffff817501df)
Location: drivers/nvdimm/nd-core.h:226
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:flush_regions_dimms
  - drivers/nvdimm/core.c:flush_namespaces
```
```
In drivers/nvdimm/bus.c (ffffffff8175246b)
Location: drivers/nvdimm/nd-core.h:226
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/nvdimm/bus.c:nd_device_notify
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff81752bd2)
Location: drivers/nvdimm/nd-core.h:226
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:security_store
```
```
In drivers/nvdimm/region_devs.c (ffffffff8175500c)
Location: drivers/nvdimm/nd-core.h:226
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:region_badblocks_show
  - drivers/nvdimm/region_devs.c:max_available_extent_show
  - drivers/nvdimm/region_devs.c:available_size_show
  - drivers/nvdimm/region_devs.c:set_cookie_show
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff8175a2d8)
Location: drivers/nvdimm/nd-core.h:226
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
In drivers/nvdimm/btt_devs.c (ffffffff8175f4ad)
Location: drivers/nvdimm/nd-core.h:226
Inline: True
Inline callers:
  - drivers/nvdimm/btt_devs.c:size_show
  - drivers/nvdimm/btt_devs.c:namespace_store
  - drivers/nvdimm/btt_devs.c:uuid_store
  - drivers/nvdimm/btt_devs.c:sector_size_store
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff8175ff48)
Location: drivers/nvdimm/nd-core.h:226
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
In drivers/nvdimm/core.c (ffffffff8180e8cf)
Location: drivers/nvdimm/nd-core.h:238
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:flush_regions_dimms
  - drivers/nvdimm/core.c:flush_namespaces
```
```
In drivers/nvdimm/bus.c (ffffffff81810f16)
Location: drivers/nvdimm/nd-core.h:238
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/nvdimm/bus.c:nvdimm_region_notify
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff81811612)
Location: drivers/nvdimm/nd-core.h:238
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:security_store
```
```
In drivers/nvdimm/region_devs.c (ffffffff81813e2c)
Location: drivers/nvdimm/nd-core.h:238
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:region_badblocks_show
  - drivers/nvdimm/region_devs.c:max_available_extent_show
  - drivers/nvdimm/region_devs.c:available_size_show
  - drivers/nvdimm/region_devs.c:set_cookie_show
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff81819df8)
Location: drivers/nvdimm/nd-core.h:238
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
In drivers/nvdimm/btt_devs.c (ffffffff8181f2ed)
Location: drivers/nvdimm/nd-core.h:238
Inline: True
Inline callers:
  - drivers/nvdimm/btt_devs.c:size_show
  - drivers/nvdimm/btt_devs.c:namespace_store
  - drivers/nvdimm/btt_devs.c:uuid_store
  - drivers/nvdimm/btt_devs.c:sector_size_store
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff8181fa48)
Location: drivers/nvdimm/nd-core.h:238
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
In drivers/nvdimm/core.c (ffffffff8181d43f)
Location: drivers/nvdimm/nd-core.h:239
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:flush_regions_dimms
  - drivers/nvdimm/core.c:flush_namespaces
```
```
In drivers/nvdimm/bus.c (ffffffff8181fe56)
Location: drivers/nvdimm/nd-core.h:239
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/nvdimm/bus.c:nvdimm_region_notify
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff818204b2)
Location: drivers/nvdimm/nd-core.h:239
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:security_store
  - drivers/nvdimm/dimm_devs.c:available_slots_show
```
```
In drivers/nvdimm/region_devs.c (ffffffff8182301c)
Location: drivers/nvdimm/nd-core.h:239
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:region_badblocks_show
  - drivers/nvdimm/region_devs.c:max_available_extent_show
  - drivers/nvdimm/region_devs.c:available_size_show
  - drivers/nvdimm/region_devs.c:set_cookie_show
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff81828f18)
Location: drivers/nvdimm/nd-core.h:239
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
In drivers/nvdimm/btt_devs.c (ffffffff8182e22d)
Location: drivers/nvdimm/nd-core.h:239
Inline: True
Inline callers:
  - drivers/nvdimm/btt_devs.c:size_show
  - drivers/nvdimm/btt_devs.c:namespace_store
  - drivers/nvdimm/btt_devs.c:uuid_store
  - drivers/nvdimm/btt_devs.c:sector_size_store
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff8182e978)
Location: drivers/nvdimm/nd-core.h:239
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
In drivers/nvdimm/core.c (ffffffff818007cf)
Location: drivers/nvdimm/nd-core.h:239
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:flush_regions_dimms
  - drivers/nvdimm/core.c:flush_namespaces
```
```
In drivers/nvdimm/bus.c (ffffffff81803142)
Location: drivers/nvdimm/nd-core.h:239
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/nvdimm/bus.c:nvdimm_region_notify
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff81803792)
Location: drivers/nvdimm/nd-core.h:239
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:security_store
  - drivers/nvdimm/dimm_devs.c:available_slots_show
```
```
In drivers/nvdimm/region_devs.c (ffffffff8180617c)
Location: drivers/nvdimm/nd-core.h:239
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:region_badblocks_show
  - drivers/nvdimm/region_devs.c:max_available_extent_show
  - drivers/nvdimm/region_devs.c:available_size_show
  - drivers/nvdimm/region_devs.c:set_cookie_show
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff8180c138)
Location: drivers/nvdimm/nd-core.h:239
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
In drivers/nvdimm/btt_devs.c (ffffffff818114fd)
Location: drivers/nvdimm/nd-core.h:239
Inline: True
Inline callers:
  - drivers/nvdimm/btt_devs.c:size_show
  - drivers/nvdimm/btt_devs.c:namespace_store
  - drivers/nvdimm/btt_devs.c:uuid_store
  - drivers/nvdimm/btt_devs.c:sector_size_store
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff81811c48)
Location: drivers/nvdimm/nd-core.h:239
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
In drivers/nvdimm/core.c (ffffffff8188abcf)
Location: drivers/nvdimm/nd-core.h:239
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:flush_regions_dimms
  - drivers/nvdimm/core.c:flush_namespaces
```
```
In drivers/nvdimm/bus.c (ffffffff8188d69c)
Location: drivers/nvdimm/nd-core.h:239
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/nvdimm/bus.c:nvdimm_region_notify
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff8188e2d2)
Location: drivers/nvdimm/nd-core.h:239
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:security_store
  - drivers/nvdimm/dimm_devs.c:available_slots_show
```
```
In drivers/nvdimm/region_devs.c (ffffffff8189046c)
Location: drivers/nvdimm/nd-core.h:239
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:region_badblocks_show
  - drivers/nvdimm/region_devs.c:max_available_extent_show
  - drivers/nvdimm/region_devs.c:available_size_show
  - drivers/nvdimm/region_devs.c:set_cookie_show
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff81896758)
Location: drivers/nvdimm/nd-core.h:239
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
In drivers/nvdimm/btt_devs.c (ffffffff8189b8ed)
Location: drivers/nvdimm/nd-core.h:239
Inline: True
Inline callers:
  - drivers/nvdimm/btt_devs.c:size_show
  - drivers/nvdimm/btt_devs.c:namespace_store
  - drivers/nvdimm/btt_devs.c:uuid_store
  - drivers/nvdimm/btt_devs.c:sector_size_store
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff8189c278)
Location: drivers/nvdimm/nd-core.h:239
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
In drivers/nvdimm/core.c (ffff80001095022c)
Location: drivers/nvdimm/nd-core.h:226
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:flush_regions_dimms
  - drivers/nvdimm/core.c:flush_namespaces
```
```
In drivers/nvdimm/bus.c (ffff800010952ac4)
Location: drivers/nvdimm/nd-core.h:226
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/nvdimm/bus.c:nd_device_notify
```
```
In drivers/nvdimm/dimm_devs.c (ffff8000109532f8)
Location: drivers/nvdimm/nd-core.h:226
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:security_store
```
```
In drivers/nvdimm/region_devs.c (ffff8000109560a8)
Location: drivers/nvdimm/nd-core.h:226
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:region_badblocks_show
  - drivers/nvdimm/region_devs.c:max_available_extent_show
  - drivers/nvdimm/region_devs.c:available_size_show
  - drivers/nvdimm/region_devs.c:set_cookie_show
```
```
In drivers/nvdimm/namespace_devs.c (ffff80001095bba4)
Location: drivers/nvdimm/nd-core.h:226
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
In drivers/nvdimm/btt_devs.c (ffff800010960c50)
Location: drivers/nvdimm/nd-core.h:226
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
In drivers/nvdimm/core.c (c0000000009fc744)
Location: drivers/nvdimm/nd-core.h:226
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:flush_regions_dimms
  - drivers/nvdimm/core.c:flush_namespaces
```
```
In drivers/nvdimm/bus.c (c0000000009ffc28)
Location: drivers/nvdimm/nd-core.h:226
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/nvdimm/bus.c:nd_device_notify
```
```
In drivers/nvdimm/dimm_devs.c (c000000000a00770)
Location: drivers/nvdimm/nd-core.h:226
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:security_store
```
```
In drivers/nvdimm/region_devs.c (c000000000a03d50)
Location: drivers/nvdimm/nd-core.h:226
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:region_badblocks_show
  - drivers/nvdimm/region_devs.c:max_available_extent_show
  - drivers/nvdimm/region_devs.c:available_size_show
  - drivers/nvdimm/region_devs.c:set_cookie_show
```
```
In drivers/nvdimm/namespace_devs.c (c000000000a0ca5c)
Location: drivers/nvdimm/nd-core.h:226
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
In drivers/nvdimm/btt_devs.c (c000000000a13fe4)
Location: drivers/nvdimm/nd-core.h:226
Inline: True
Inline callers:
  - drivers/nvdimm/btt_devs.c:size_show
  - drivers/nvdimm/btt_devs.c:namespace_store
  - drivers/nvdimm/btt_devs.c:uuid_store
  - drivers/nvdimm/btt_devs.c:sector_size_store
```
```
In drivers/nvdimm/pfn_devs.c (c000000000a15054)
Location: drivers/nvdimm/nd-core.h:226
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
In drivers/nvdimm/core.c (ffffffe0005c0506)
Location: drivers/nvdimm/nd-core.h:226
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:flush_regions_dimms
  - drivers/nvdimm/core.c:flush_namespaces
```
```
In drivers/nvdimm/bus.c (ffffffe0005c2632)
Location: drivers/nvdimm/nd-core.h:226
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/nvdimm/bus.c:nd_device_notify
```
```
In drivers/nvdimm/dimm_devs.c (ffffffe0005c2cc6)
Location: drivers/nvdimm/nd-core.h:226
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:security_store
```
```
In drivers/nvdimm/region_devs.c (ffffffe0005c54dc)
Location: drivers/nvdimm/nd-core.h:226
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:region_badblocks_show
  - drivers/nvdimm/region_devs.c:max_available_extent_show
  - drivers/nvdimm/region_devs.c:available_size_show
  - drivers/nvdimm/region_devs.c:set_cookie_show
```
```
In drivers/nvdimm/namespace_devs.c (ffffffe0005ca11a)
Location: drivers/nvdimm/nd-core.h:226
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
In drivers/nvdimm/btt_devs.c (ffffffe0005ce606)
Location: drivers/nvdimm/nd-core.h:226
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
In drivers/nvdimm/core.c (ffffffff817048cf)
Location: drivers/nvdimm/nd-core.h:226
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:flush_regions_dimms
  - drivers/nvdimm/core.c:flush_namespaces
```
```
In drivers/nvdimm/bus.c (ffffffff81706b5b)
Location: drivers/nvdimm/nd-core.h:226
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/nvdimm/bus.c:nd_device_notify
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff817072c2)
Location: drivers/nvdimm/nd-core.h:226
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:security_store
```
```
In drivers/nvdimm/region_devs.c (ffffffff817096fc)
Location: drivers/nvdimm/nd-core.h:226
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:region_badblocks_show
  - drivers/nvdimm/region_devs.c:max_available_extent_show
  - drivers/nvdimm/region_devs.c:available_size_show
  - drivers/nvdimm/region_devs.c:set_cookie_show
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff8170e9c8)
Location: drivers/nvdimm/nd-core.h:226
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
In drivers/nvdimm/btt_devs.c (ffffffff81713b9d)
Location: drivers/nvdimm/nd-core.h:226
Inline: True
Inline callers:
  - drivers/nvdimm/btt_devs.c:size_show
  - drivers/nvdimm/btt_devs.c:namespace_store
  - drivers/nvdimm/btt_devs.c:uuid_store
  - drivers/nvdimm/btt_devs.c:sector_size_store
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff81714638)
Location: drivers/nvdimm/nd-core.h:226
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
In drivers/nvdimm/core.c (ffffffff816d834f)
Location: drivers/nvdimm/nd-core.h:226
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:flush_regions_dimms
  - drivers/nvdimm/core.c:flush_namespaces
```
```
In drivers/nvdimm/bus.c (ffffffff816da5db)
Location: drivers/nvdimm/nd-core.h:226
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/nvdimm/bus.c:nd_device_notify
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff816dad42)
Location: drivers/nvdimm/nd-core.h:226
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:security_store
```
```
In drivers/nvdimm/region_devs.c (ffffffff816dd17c)
Location: drivers/nvdimm/nd-core.h:226
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:region_badblocks_show
  - drivers/nvdimm/region_devs.c:max_available_extent_show
  - drivers/nvdimm/region_devs.c:available_size_show
  - drivers/nvdimm/region_devs.c:set_cookie_show
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff816e2448)
Location: drivers/nvdimm/nd-core.h:226
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
In drivers/nvdimm/btt_devs.c (ffffffff816e761d)
Location: drivers/nvdimm/nd-core.h:226
Inline: True
Inline callers:
  - drivers/nvdimm/btt_devs.c:size_show
  - drivers/nvdimm/btt_devs.c:namespace_store
  - drivers/nvdimm/btt_devs.c:uuid_store
  - drivers/nvdimm/btt_devs.c:sector_size_store
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff816e80b8)
Location: drivers/nvdimm/nd-core.h:226
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
In drivers/nvdimm/core.c (ffffffff8174369f)
Location: drivers/nvdimm/nd-core.h:226
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:flush_regions_dimms
  - drivers/nvdimm/core.c:flush_namespaces
```
```
In drivers/nvdimm/bus.c (ffffffff8174592b)
Location: drivers/nvdimm/nd-core.h:226
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/nvdimm/bus.c:nd_device_notify
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff81746092)
Location: drivers/nvdimm/nd-core.h:226
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:security_store
```
```
In drivers/nvdimm/region_devs.c (ffffffff817484cc)
Location: drivers/nvdimm/nd-core.h:226
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:region_badblocks_show
  - drivers/nvdimm/region_devs.c:max_available_extent_show
  - drivers/nvdimm/region_devs.c:available_size_show
  - drivers/nvdimm/region_devs.c:set_cookie_show
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff8174d798)
Location: drivers/nvdimm/nd-core.h:226
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
In drivers/nvdimm/btt_devs.c (ffffffff8175296d)
Location: drivers/nvdimm/nd-core.h:226
Inline: True
Inline callers:
  - drivers/nvdimm/btt_devs.c:size_show
  - drivers/nvdimm/btt_devs.c:namespace_store
  - drivers/nvdimm/btt_devs.c:uuid_store
  - drivers/nvdimm/btt_devs.c:sector_size_store
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff81753408)
Location: drivers/nvdimm/nd-core.h:226
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
In drivers/nvdimm/core.c (ffffffff8175eaef)
Location: drivers/nvdimm/nd-core.h:226
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:flush_regions_dimms
  - drivers/nvdimm/core.c:flush_namespaces
```
```
In drivers/nvdimm/bus.c (ffffffff81760d6b)
Location: drivers/nvdimm/nd-core.h:226
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/nvdimm/bus.c:nd_device_notify
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff817614d2)
Location: drivers/nvdimm/nd-core.h:226
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:security_store
```
```
In drivers/nvdimm/region_devs.c (ffffffff8176394c)
Location: drivers/nvdimm/nd-core.h:226
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:region_badblocks_show
  - drivers/nvdimm/region_devs.c:max_available_extent_show
  - drivers/nvdimm/region_devs.c:available_size_show
  - drivers/nvdimm/region_devs.c:set_cookie_show
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff81768c18)
Location: drivers/nvdimm/nd-core.h:226
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
In drivers/nvdimm/btt_devs.c (ffffffff8176dddd)
Location: drivers/nvdimm/nd-core.h:226
Inline: True
Inline callers:
  - drivers/nvdimm/btt_devs.c:size_show
  - drivers/nvdimm/btt_devs.c:namespace_store
  - drivers/nvdimm/btt_devs.c:uuid_store
  - drivers/nvdimm/btt_devs.c:sector_size_store
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff8176e878)
Location: drivers/nvdimm/nd-core.h:226
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
