# Function: <code>to_nd_btt</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct nd_btt *to_nd_btt(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/btt_devs.c (ffffffff815a1030)
Location: drivers/nvdimm/btt_devs.c:47
Inline: True
Inline callers:
  - drivers/nvdimm/btt_devs.c:nd_btt_release
  - drivers/nvdimm/btt_devs.c:uuid_store
  - drivers/nvdimm/btt_devs.c:namespace_store
  - drivers/nvdimm/btt_devs.c:namespace_show
  - drivers/nvdimm/btt_devs.c:sector_size_store
  - drivers/nvdimm/btt_devs.c:sector_size_show
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
Direct callers:
  - drivers/nvdimm/region_devs.c:nd_region_notify_driver_action
  - drivers/nvdimm/namespace_devs.c:is_uuid_busy
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/nvdimm/btt_devs.c:nd_btt_release
  - drivers/nvdimm/btt_devs.c:uuid_store
  - drivers/nvdimm/btt_devs.c:namespace_store
  - drivers/nvdimm/btt_devs.c:namespace_show
  - drivers/nvdimm/btt_devs.c:sector_size_store
  - drivers/nvdimm/btt_devs.c:sector_size_show
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
```
**Symbols:**

```
ffffffff815a1030-ffffffff815a104c: to_nd_btt.part.2 (STB_LOCAL)
ffffffff815a1050-ffffffff815a107d: to_nd_btt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct nd_btt *to_nd_btt(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/btt_devs.c (ffffffff815f7c12)
Location: drivers/nvdimm/btt_devs.c:47
Inline: True
Inline callers:
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/btt_devs.c:size_show
  - drivers/nvdimm/btt_devs.c:namespace_store
  - drivers/nvdimm/btt_devs.c:namespace_show
  - drivers/nvdimm/btt_devs.c:uuid_store
  - drivers/nvdimm/btt_devs.c:sector_size_store
  - drivers/nvdimm/btt_devs.c:sector_size_show
  - drivers/nvdimm/btt_devs.c:nd_btt_release
Direct callers:
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:is_uuid_busy
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/btt_devs.c:size_show
  - drivers/nvdimm/btt_devs.c:namespace_store
  - drivers/nvdimm/btt_devs.c:namespace_show
  - drivers/nvdimm/btt_devs.c:uuid_store
  - drivers/nvdimm/btt_devs.c:sector_size_store
  - drivers/nvdimm/btt_devs.c:sector_size_show
  - drivers/nvdimm/btt_devs.c:nd_btt_release
```
**Symbols:**

```
ffffffff815f73f0-ffffffff815f740c: to_nd_btt.part.1 (STB_LOCAL)
ffffffff815f7410-ffffffff815f743a: to_nd_btt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct nd_btt *to_nd_btt(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/btt_devs.c (ffffffff81625e82)
Location: drivers/nvdimm/btt_devs.c:47
Inline: True
Inline callers:
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/btt_devs.c:size_show
  - drivers/nvdimm/btt_devs.c:namespace_store
  - drivers/nvdimm/btt_devs.c:namespace_show
  - drivers/nvdimm/btt_devs.c:uuid_store
  - drivers/nvdimm/btt_devs.c:sector_size_store
  - drivers/nvdimm/btt_devs.c:sector_size_show
  - drivers/nvdimm/btt_devs.c:nd_btt_release
Direct callers:
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:is_uuid_busy
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/btt_devs.c:size_show
  - drivers/nvdimm/btt_devs.c:namespace_store
  - drivers/nvdimm/btt_devs.c:namespace_show
  - drivers/nvdimm/btt_devs.c:uuid_store
  - drivers/nvdimm/btt_devs.c:sector_size_store
  - drivers/nvdimm/btt_devs.c:sector_size_show
  - drivers/nvdimm/btt_devs.c:nd_btt_release
```
**Symbols:**

```
ffffffff81625660-ffffffff8162567c: to_nd_btt.part.1 (STB_LOCAL)
ffffffff81625680-ffffffff816256aa: to_nd_btt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct nd_btt *to_nd_btt(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/btt_devs.c (ffffffff8163afd4)
Location: drivers/nvdimm/btt_devs.c:47
Inline: True
Inline callers:
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/btt_devs.c:size_show
  - drivers/nvdimm/btt_devs.c:namespace_store
  - drivers/nvdimm/btt_devs.c:namespace_show
  - drivers/nvdimm/btt_devs.c:uuid_store
  - drivers/nvdimm/btt_devs.c:sector_size_store
  - drivers/nvdimm/btt_devs.c:sector_size_show
  - drivers/nvdimm/btt_devs.c:nd_btt_release
Direct callers:
  - drivers/nvdimm/bus.c:nd_pmem_forget_poison_check
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:is_uuid_busy
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/btt_devs.c:size_show
  - drivers/nvdimm/btt_devs.c:namespace_store
  - drivers/nvdimm/btt_devs.c:namespace_show
  - drivers/nvdimm/btt_devs.c:uuid_store
  - drivers/nvdimm/btt_devs.c:sector_size_store
  - drivers/nvdimm/btt_devs.c:sector_size_show
  - drivers/nvdimm/btt_devs.c:nd_btt_release
```
**Symbols:**

```
ffffffff8163a6d0-ffffffff8163a6dd: to_nd_btt.part.1 (STB_LOCAL)
ffffffff8163a6e0-ffffffff8163a70b: to_nd_btt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct nd_btt *to_nd_btt(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/btt_devs.c (ffffffff816a3be4)
Location: drivers/nvdimm/btt_devs.c:47
Inline: True
Inline callers:
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/btt_devs.c:size_show
  - drivers/nvdimm/btt_devs.c:namespace_store
  - drivers/nvdimm/btt_devs.c:namespace_show
  - drivers/nvdimm/btt_devs.c:uuid_store
  - drivers/nvdimm/btt_devs.c:sector_size_store
  - drivers/nvdimm/btt_devs.c:sector_size_show
  - drivers/nvdimm/btt_devs.c:nd_btt_release
Direct callers:
  - drivers/nvdimm/bus.c:nd_pmem_forget_poison_check
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:is_uuid_busy
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/btt_devs.c:size_show
  - drivers/nvdimm/btt_devs.c:namespace_store
  - drivers/nvdimm/btt_devs.c:namespace_show
  - drivers/nvdimm/btt_devs.c:uuid_store
  - drivers/nvdimm/btt_devs.c:sector_size_store
  - drivers/nvdimm/btt_devs.c:sector_size_show
  - drivers/nvdimm/btt_devs.c:nd_btt_release
```
**Symbols:**

```
ffffffff816a32d0-ffffffff816a32dd: to_nd_btt.part.1 (STB_LOCAL)
ffffffff816a32e0-ffffffff816a330b: to_nd_btt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct nd_btt *to_nd_btt(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/btt_devs.c (ffffffff816dfcf5)
Location: drivers/nvdimm/btt_devs.c:47
Inline: True
Inline callers:
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/btt_devs.c:size_show
  - drivers/nvdimm/btt_devs.c:namespace_store
  - drivers/nvdimm/btt_devs.c:namespace_show
  - drivers/nvdimm/btt_devs.c:uuid_store
  - drivers/nvdimm/btt_devs.c:sector_size_store
  - drivers/nvdimm/btt_devs.c:sector_size_show
  - drivers/nvdimm/btt_devs.c:nd_btt_release
Direct callers:
  - drivers/nvdimm/bus.c:nd_pmem_forget_poison_check
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:is_uuid_busy
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/btt_devs.c:size_show
  - drivers/nvdimm/btt_devs.c:namespace_store
  - drivers/nvdimm/btt_devs.c:namespace_show
  - drivers/nvdimm/btt_devs.c:uuid_store
  - drivers/nvdimm/btt_devs.c:sector_size_store
  - drivers/nvdimm/btt_devs.c:sector_size_show
  - drivers/nvdimm/btt_devs.c:nd_btt_release
```
**Symbols:**

```
ffffffff816df460-ffffffff816df46d: to_nd_btt.part.1 (STB_LOCAL)
ffffffff816df470-ffffffff816df49a: to_nd_btt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct nd_btt *to_nd_btt(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/btt_devs.c (ffffffff817020b5)
Location: drivers/nvdimm/btt_devs.c:47
Inline: True
Inline callers:
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/btt_devs.c:size_show
  - drivers/nvdimm/btt_devs.c:namespace_store
  - drivers/nvdimm/btt_devs.c:namespace_show
  - drivers/nvdimm/btt_devs.c:uuid_store
  - drivers/nvdimm/btt_devs.c:sector_size_store
  - drivers/nvdimm/btt_devs.c:sector_size_show
  - drivers/nvdimm/btt_devs.c:nd_btt_release
Direct callers:
  - drivers/nvdimm/bus.c:nd_pmem_forget_poison_check
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:is_uuid_busy
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/btt_devs.c:size_show
  - drivers/nvdimm/btt_devs.c:namespace_store
  - drivers/nvdimm/btt_devs.c:namespace_show
  - drivers/nvdimm/btt_devs.c:uuid_store
  - drivers/nvdimm/btt_devs.c:sector_size_store
  - drivers/nvdimm/btt_devs.c:sector_size_show
  - drivers/nvdimm/btt_devs.c:nd_btt_release
```
**Symbols:**

```
ffffffff81701810-ffffffff8170181d: to_nd_btt.part.1 (STB_LOCAL)
ffffffff81701820-ffffffff8170184a: to_nd_btt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct nd_btt *to_nd_btt(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/btt_devs.c (ffffffff8173bf29)
Location: drivers/nvdimm/btt_devs.c:39
Inline: True
Inline callers:
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/btt_devs.c:size_show
  - drivers/nvdimm/btt_devs.c:namespace_store
  - drivers/nvdimm/btt_devs.c:namespace_show
  - drivers/nvdimm/btt_devs.c:uuid_store
  - drivers/nvdimm/btt_devs.c:sector_size_store
  - drivers/nvdimm/btt_devs.c:sector_size_show
  - drivers/nvdimm/btt_devs.c:nd_btt_release
Direct callers:
  - drivers/nvdimm/bus.c:nd_pmem_forget_poison_check
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:is_uuid_busy
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/btt_devs.c:size_show
  - drivers/nvdimm/btt_devs.c:namespace_store
  - drivers/nvdimm/btt_devs.c:namespace_show
  - drivers/nvdimm/btt_devs.c:uuid_store
  - drivers/nvdimm/btt_devs.c:sector_size_store
  - drivers/nvdimm/btt_devs.c:sector_size_show
  - drivers/nvdimm/btt_devs.c:nd_btt_release
```
**Symbols:**

```
ffffffff8173c094-ffffffff8173c0ad: to_nd_btt.part.0 (STB_LOCAL)
ffffffff8173c0ad-ffffffff8173c0bf: to_nd_btt.cold (STB_LOCAL)
ffffffff8173b6e0-ffffffff8173b700: to_nd_btt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct nd_btt *to_nd_btt(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/btt_devs.c (ffffffff8175fc49)
Location: drivers/nvdimm/btt_devs.c:39
Inline: True
Inline callers:
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/btt_devs.c:size_show
  - drivers/nvdimm/btt_devs.c:namespace_store
  - drivers/nvdimm/btt_devs.c:namespace_show
  - drivers/nvdimm/btt_devs.c:uuid_store
  - drivers/nvdimm/btt_devs.c:sector_size_store
  - drivers/nvdimm/btt_devs.c:sector_size_show
  - drivers/nvdimm/btt_devs.c:nd_btt_release
Direct callers:
  - drivers/nvdimm/bus.c:nd_pmem_forget_poison_check
  - drivers/nvdimm/region_devs.c:nd_region_advance_seeds
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:is_uuid_busy
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/btt_devs.c:size_show
  - drivers/nvdimm/btt_devs.c:namespace_store
  - drivers/nvdimm/btt_devs.c:namespace_show
  - drivers/nvdimm/btt_devs.c:uuid_store
  - drivers/nvdimm/btt_devs.c:sector_size_store
  - drivers/nvdimm/btt_devs.c:sector_size_show
  - drivers/nvdimm/btt_devs.c:nd_btt_release
```
**Symbols:**

```
ffffffff8175f390-ffffffff8175f39d: to_nd_btt.part.0 (STB_LOCAL)
ffffffff8175f3a0-ffffffff8175f3ca: to_nd_btt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct nd_btt *to_nd_btt(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/btt_devs.c (ffffffff8181f769)
Location: drivers/nvdimm/btt_devs.c:28
Inline: True
Inline callers:
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/btt_devs.c:size_show
  - drivers/nvdimm/btt_devs.c:size_show
  - drivers/nvdimm/btt_devs.c:namespace_store
  - drivers/nvdimm/btt_devs.c:namespace_store
  - drivers/nvdimm/btt_devs.c:namespace_show
  - drivers/nvdimm/btt_devs.c:namespace_show
  - drivers/nvdimm/btt_devs.c:uuid_store
  - drivers/nvdimm/btt_devs.c:uuid_store
  - drivers/nvdimm/btt_devs.c:sector_size_store
  - drivers/nvdimm/btt_devs.c:sector_size_store
  - drivers/nvdimm/btt_devs.c:sector_size_show
  - drivers/nvdimm/btt_devs.c:sector_size_show
  - drivers/nvdimm/btt_devs.c:nd_btt_release
  - drivers/nvdimm/btt_devs.c:nd_btt_release
Direct callers:
  - drivers/nvdimm/bus.c:nd_pmem_forget_poison_check
  - drivers/nvdimm/region_devs.c:nd_region_advance_seeds
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:is_uuid_busy
  - drivers/nvdimm/claim.c:nd_detach_and_reset
```
**Symbols:**

```
ffffffff8181f200-ffffffff8181f21c: to_nd_btt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct nd_btt *to_nd_btt(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/btt_devs.c (ffffffff8182e6a9)
Location: drivers/nvdimm/btt_devs.c:28
Inline: True
Inline callers:
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/btt_devs.c:size_show
  - drivers/nvdimm/btt_devs.c:size_show
  - drivers/nvdimm/btt_devs.c:namespace_store
  - drivers/nvdimm/btt_devs.c:namespace_store
  - drivers/nvdimm/btt_devs.c:namespace_show
  - drivers/nvdimm/btt_devs.c:namespace_show
  - drivers/nvdimm/btt_devs.c:uuid_store
  - drivers/nvdimm/btt_devs.c:uuid_store
  - drivers/nvdimm/btt_devs.c:sector_size_store
  - drivers/nvdimm/btt_devs.c:sector_size_store
  - drivers/nvdimm/btt_devs.c:sector_size_show
  - drivers/nvdimm/btt_devs.c:sector_size_show
  - drivers/nvdimm/btt_devs.c:nd_btt_release
  - drivers/nvdimm/btt_devs.c:nd_btt_release
Direct callers:
  - drivers/nvdimm/bus.c:nd_pmem_forget_poison_check
  - drivers/nvdimm/region_devs.c:nd_region_advance_seeds
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:is_uuid_busy
  - drivers/nvdimm/claim.c:nd_detach_and_reset
```
**Symbols:**

```
ffffffff8182e140-ffffffff8182e15c: to_nd_btt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct nd_btt *to_nd_btt(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/btt_devs.c (ffffffff81811979)
Location: drivers/nvdimm/btt_devs.c:28
Inline: True
Inline callers:
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/btt_devs.c:size_show
  - drivers/nvdimm/btt_devs.c:size_show
  - drivers/nvdimm/btt_devs.c:namespace_store
  - drivers/nvdimm/btt_devs.c:namespace_store
  - drivers/nvdimm/btt_devs.c:namespace_show
  - drivers/nvdimm/btt_devs.c:namespace_show
  - drivers/nvdimm/btt_devs.c:uuid_store
  - drivers/nvdimm/btt_devs.c:uuid_store
  - drivers/nvdimm/btt_devs.c:sector_size_store
  - drivers/nvdimm/btt_devs.c:sector_size_store
  - drivers/nvdimm/btt_devs.c:sector_size_show
  - drivers/nvdimm/btt_devs.c:sector_size_show
  - drivers/nvdimm/btt_devs.c:nd_btt_release
  - drivers/nvdimm/btt_devs.c:nd_btt_release
Direct callers:
  - drivers/nvdimm/bus.c:nd_pmem_forget_poison_check
  - drivers/nvdimm/region_devs.c:nd_region_advance_seeds
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:is_uuid_busy
  - drivers/nvdimm/claim.c:nd_namespace_store
```
**Symbols:**

```
ffffffff81811410-ffffffff8181142c: to_nd_btt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct nd_btt *to_nd_btt(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/btt_devs.c (ffffffff8189c052)
Location: drivers/nvdimm/btt_devs.c:28
Inline: True
Inline callers:
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/btt_devs.c:size_show
  - drivers/nvdimm/btt_devs.c:namespace_store
  - drivers/nvdimm/btt_devs.c:namespace_show
  - drivers/nvdimm/btt_devs.c:uuid_store
  - drivers/nvdimm/btt_devs.c:sector_size_store
  - drivers/nvdimm/btt_devs.c:sector_size_show
  - drivers/nvdimm/btt_devs.c:nd_btt_release
Direct callers:
  - drivers/nvdimm/bus.c:nd_pmem_forget_poison_check
  - drivers/nvdimm/region_devs.c:nd_region_advance_seeds
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:is_uuid_busy
  - drivers/nvdimm/claim.c:nd_namespace_store
```
**Symbols:**

```
ffffffff8189b7d0-ffffffff8189b7ec: to_nd_btt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct nd_btt *to_nd_btt(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/btt_devs.c (ffffffff819e58ab)
Location: drivers/nvdimm/btt_devs.c:27
Inline: True
Inline callers:
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/btt_devs.c:size_show
  - drivers/nvdimm/btt_devs.c:namespace_store
  - drivers/nvdimm/btt_devs.c:namespace_show
  - drivers/nvdimm/btt_devs.c:uuid_store
  - drivers/nvdimm/btt_devs.c:sector_size_store
  - drivers/nvdimm/btt_devs.c:sector_size_show
  - drivers/nvdimm/btt_devs.c:nd_btt_release
Direct callers:
  - drivers/nvdimm/bus.c:nd_pmem_forget_poison_check
  - drivers/nvdimm/region_devs.c:nd_region_advance_seeds
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:is_uuid_busy
  - drivers/nvdimm/claim.c:nd_namespace_store
```
**Symbols:**

```
ffffffff819e4f50-ffffffff819e4f78: to_nd_btt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct nd_btt *to_nd_btt(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/btt_devs.c (ffffffff81b61757)
Location: drivers/nvdimm/btt_devs.c:27
Inline: True
Inline callers:
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/btt_devs.c:size_show
  - drivers/nvdimm/btt_devs.c:namespace_store
  - drivers/nvdimm/btt_devs.c:namespace_show
  - drivers/nvdimm/btt_devs.c:uuid_store
  - drivers/nvdimm/btt_devs.c:sector_size_store
  - drivers/nvdimm/btt_devs.c:sector_size_show
  - drivers/nvdimm/btt_devs.c:nd_btt_release
Direct callers:
  - drivers/nvdimm/bus.c:nd_pmem_forget_poison_check
  - drivers/nvdimm/region_devs.c:nd_region_advance_seeds
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:is_uuid_busy
  - drivers/nvdimm/claim.c:nd_namespace_store
```
**Symbols:**

```
ffffffff81b60d40-ffffffff81b60d68: to_nd_btt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct nd_btt *to_nd_btt(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/btt_devs.c (ffffffff81bb4d50)
Location: drivers/nvdimm/btt_devs.c:27
Inline: True
Inline callers:
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/btt_devs.c:size_show
  - drivers/nvdimm/btt_devs.c:namespace_store
  - drivers/nvdimm/btt_devs.c:namespace_show
  - drivers/nvdimm/btt_devs.c:uuid_store
  - drivers/nvdimm/btt_devs.c:sector_size_store
  - drivers/nvdimm/btt_devs.c:sector_size_show
  - drivers/nvdimm/btt_devs.c:nd_btt_release
Direct callers:
  - drivers/nvdimm/bus.c:nd_pmem_forget_poison_check
  - drivers/nvdimm/region_devs.c:nd_region_advance_seeds
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:is_uuid_busy
  - drivers/nvdimm/claim.c:nd_namespace_store
```
**Symbols:**

```
ffffffff81bb42c0-ffffffff81bb42e8: to_nd_btt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct nd_btt *to_nd_btt(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/btt_devs.c (ffffffff81c092d0)
Location: drivers/nvdimm/btt_devs.c:27
Inline: True
Inline callers:
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/btt_devs.c:size_show
  - drivers/nvdimm/btt_devs.c:namespace_store
  - drivers/nvdimm/btt_devs.c:namespace_show
  - drivers/nvdimm/btt_devs.c:uuid_store
  - drivers/nvdimm/btt_devs.c:sector_size_store
  - drivers/nvdimm/btt_devs.c:sector_size_show
  - drivers/nvdimm/btt_devs.c:nd_btt_release
Direct callers:
  - drivers/nvdimm/bus.c:nd_pmem_forget_poison_check
  - drivers/nvdimm/region_devs.c:nd_region_advance_seeds
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:is_uuid_busy
  - drivers/nvdimm/claim.c:nd_namespace_store
```
**Symbols:**

```
ffffffff81c08810-ffffffff81c08838: to_nd_btt (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct nd_btt *to_nd_btt(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/btt_devs.c (ffff800010961500)
Location: drivers/nvdimm/btt_devs.c:39
Inline: True
Inline callers:
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/btt_devs.c:size_show
  - drivers/nvdimm/btt_devs.c:namespace_store
  - drivers/nvdimm/btt_devs.c:namespace_show
  - drivers/nvdimm/btt_devs.c:uuid_store
  - drivers/nvdimm/btt_devs.c:sector_size_store
  - drivers/nvdimm/btt_devs.c:sector_size_show
  - drivers/nvdimm/btt_devs.c:nd_btt_release
Direct callers:
  - drivers/nvdimm/bus.c:nd_pmem_forget_poison_check
  - drivers/nvdimm/region_devs.c:nd_region_advance_seeds
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:is_uuid_busy
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/btt_devs.c:size_show
  - drivers/nvdimm/btt_devs.c:namespace_store
  - drivers/nvdimm/btt_devs.c:namespace_show
  - drivers/nvdimm/btt_devs.c:uuid_store
  - drivers/nvdimm/btt_devs.c:sector_size_store
  - drivers/nvdimm/btt_devs.c:sector_size_show
  - drivers/nvdimm/btt_devs.c:nd_btt_release
```
**Symbols:**

```
ffff800010960ae8-ffff800010960b04: to_nd_btt.part.0 (STB_LOCAL)
ffff800010960b08-ffff800010960b58: to_nd_btt (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct nd_btt *to_nd_btt(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/btt_devs.c (c000000000a13e50)
Location: drivers/nvdimm/btt_devs.c:39
Inline: False
Direct callers:
  - drivers/nvdimm/bus.c:nd_pmem_forget_poison_check
  - drivers/nvdimm/region_devs.c:nd_region_advance_seeds
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:is_uuid_busy
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/btt_devs.c:size_show
  - drivers/nvdimm/btt_devs.c:namespace_store
  - drivers/nvdimm/btt_devs.c:namespace_show
  - drivers/nvdimm/btt_devs.c:uuid_store
  - drivers/nvdimm/btt_devs.c:sector_size_store
  - drivers/nvdimm/btt_devs.c:sector_size_show
  - drivers/nvdimm/btt_devs.c:nd_btt_release
```
**Symbols:**

```
c000000000a13e50-c000000000a13e80: to_nd_btt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct nd_btt *to_nd_btt(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/btt_devs.c (ffffffe0005cedb6)
Location: drivers/nvdimm/btt_devs.c:39
Inline: True
Inline callers:
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/btt_devs.c:size_show
  - drivers/nvdimm/btt_devs.c:namespace_store
  - drivers/nvdimm/btt_devs.c:namespace_show
  - drivers/nvdimm/btt_devs.c:uuid_store
  - drivers/nvdimm/btt_devs.c:sector_size_store
  - drivers/nvdimm/btt_devs.c:sector_size_show
  - drivers/nvdimm/btt_devs.c:nd_btt_release
Direct callers:
  - drivers/nvdimm/bus.c:nd_pmem_forget_poison_check
  - drivers/nvdimm/region_devs.c:nd_region_advance_seeds
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:is_uuid_busy
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/btt_devs.c:size_show
  - drivers/nvdimm/btt_devs.c:namespace_store
  - drivers/nvdimm/btt_devs.c:namespace_show
  - drivers/nvdimm/btt_devs.c:uuid_store
  - drivers/nvdimm/btt_devs.c:sector_size_store
  - drivers/nvdimm/btt_devs.c:sector_size_show
  - drivers/nvdimm/btt_devs.c:nd_btt_release
```
**Symbols:**

```
ffffffe0005ce4a0-ffffffe0005ce4bc: to_nd_btt.part.0 (STB_LOCAL)
ffffffe0005ce4bc-ffffffe0005ce500: to_nd_btt (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct nd_btt *to_nd_btt(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/btt_devs.c (ffffffff81714339)
Location: drivers/nvdimm/btt_devs.c:39
Inline: True
Inline callers:
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/btt_devs.c:size_show
  - drivers/nvdimm/btt_devs.c:namespace_store
  - drivers/nvdimm/btt_devs.c:namespace_show
  - drivers/nvdimm/btt_devs.c:uuid_store
  - drivers/nvdimm/btt_devs.c:sector_size_store
  - drivers/nvdimm/btt_devs.c:sector_size_show
  - drivers/nvdimm/btt_devs.c:nd_btt_release
Direct callers:
  - drivers/nvdimm/bus.c:nd_pmem_forget_poison_check
  - drivers/nvdimm/region_devs.c:nd_region_advance_seeds
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:is_uuid_busy
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/btt_devs.c:size_show
  - drivers/nvdimm/btt_devs.c:namespace_store
  - drivers/nvdimm/btt_devs.c:namespace_show
  - drivers/nvdimm/btt_devs.c:uuid_store
  - drivers/nvdimm/btt_devs.c:sector_size_store
  - drivers/nvdimm/btt_devs.c:sector_size_show
  - drivers/nvdimm/btt_devs.c:nd_btt_release
```
**Symbols:**

```
ffffffff81713a80-ffffffff81713a8d: to_nd_btt.part.0 (STB_LOCAL)
ffffffff81713a90-ffffffff81713aba: to_nd_btt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct nd_btt *to_nd_btt(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/btt_devs.c (ffffffff816e7db9)
Location: drivers/nvdimm/btt_devs.c:39
Inline: True
Inline callers:
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/btt_devs.c:size_show
  - drivers/nvdimm/btt_devs.c:namespace_store
  - drivers/nvdimm/btt_devs.c:namespace_show
  - drivers/nvdimm/btt_devs.c:uuid_store
  - drivers/nvdimm/btt_devs.c:sector_size_store
  - drivers/nvdimm/btt_devs.c:sector_size_show
  - drivers/nvdimm/btt_devs.c:nd_btt_release
Direct callers:
  - drivers/nvdimm/bus.c:nd_pmem_forget_poison_check
  - drivers/nvdimm/region_devs.c:nd_region_advance_seeds
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:is_uuid_busy
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/btt_devs.c:size_show
  - drivers/nvdimm/btt_devs.c:namespace_store
  - drivers/nvdimm/btt_devs.c:namespace_show
  - drivers/nvdimm/btt_devs.c:uuid_store
  - drivers/nvdimm/btt_devs.c:sector_size_store
  - drivers/nvdimm/btt_devs.c:sector_size_show
  - drivers/nvdimm/btt_devs.c:nd_btt_release
  - drivers/nvdimm/pmem.c:nd_pmem_remove
  - drivers/nvdimm/btt.c:nvdimm_namespace_attach_btt
```
**Symbols:**

```
ffffffff816e7500-ffffffff816e750d: to_nd_btt.part.0 (STB_LOCAL)
ffffffff816e7510-ffffffff816e753a: to_nd_btt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct nd_btt *to_nd_btt(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/btt_devs.c (ffffffff81753109)
Location: drivers/nvdimm/btt_devs.c:39
Inline: True
Inline callers:
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/btt_devs.c:size_show
  - drivers/nvdimm/btt_devs.c:namespace_store
  - drivers/nvdimm/btt_devs.c:namespace_show
  - drivers/nvdimm/btt_devs.c:uuid_store
  - drivers/nvdimm/btt_devs.c:sector_size_store
  - drivers/nvdimm/btt_devs.c:sector_size_show
  - drivers/nvdimm/btt_devs.c:nd_btt_release
Direct callers:
  - drivers/nvdimm/bus.c:nd_pmem_forget_poison_check
  - drivers/nvdimm/region_devs.c:nd_region_advance_seeds
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:is_uuid_busy
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/btt_devs.c:size_show
  - drivers/nvdimm/btt_devs.c:namespace_store
  - drivers/nvdimm/btt_devs.c:namespace_show
  - drivers/nvdimm/btt_devs.c:uuid_store
  - drivers/nvdimm/btt_devs.c:sector_size_store
  - drivers/nvdimm/btt_devs.c:sector_size_show
  - drivers/nvdimm/btt_devs.c:nd_btt_release
```
**Symbols:**

```
ffffffff81752850-ffffffff8175285d: to_nd_btt.part.0 (STB_LOCAL)
ffffffff81752860-ffffffff8175288a: to_nd_btt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct nd_btt *to_nd_btt(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/btt_devs.c (ffffffff8176e579)
Location: drivers/nvdimm/btt_devs.c:39
Inline: True
Inline callers:
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/btt_devs.c:size_show
  - drivers/nvdimm/btt_devs.c:namespace_store
  - drivers/nvdimm/btt_devs.c:namespace_show
  - drivers/nvdimm/btt_devs.c:uuid_store
  - drivers/nvdimm/btt_devs.c:sector_size_store
  - drivers/nvdimm/btt_devs.c:sector_size_show
  - drivers/nvdimm/btt_devs.c:nd_btt_release
Direct callers:
  - drivers/nvdimm/bus.c:nd_pmem_forget_poison_check
  - drivers/nvdimm/region_devs.c:nd_region_advance_seeds
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:is_uuid_busy
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/btt_devs.c:size_show
  - drivers/nvdimm/btt_devs.c:namespace_store
  - drivers/nvdimm/btt_devs.c:namespace_show
  - drivers/nvdimm/btt_devs.c:uuid_store
  - drivers/nvdimm/btt_devs.c:sector_size_store
  - drivers/nvdimm/btt_devs.c:sector_size_show
  - drivers/nvdimm/btt_devs.c:nd_btt_release
```
**Symbols:**

```
ffffffff8176dcc0-ffffffff8176dccd: to_nd_btt.part.0 (STB_LOCAL)
ffffffff8176dcd0-ffffffff8176dcfa: to_nd_btt (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
