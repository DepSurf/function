# Function: <code>domain_exit</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void domain_exit(struct dmar_domain *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff81539100)
Location: drivers/iommu/intel-iommu.c:1912
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:disable_dmar_iommu
  - drivers/iommu/intel-iommu.c:device_notifier
  - drivers/iommu/intel-iommu.c:intel_iommu_domain_free
  - drivers/iommu/intel-iommu.c:intel_iommu_attach_device
  - drivers/iommu/intel-iommu.c:iommu_prepare_identity_map
  - drivers/iommu/intel-iommu.c:init_dmars
```
**Symbols:**

```
ffffffff81539100-ffffffff815391ca: domain_exit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void domain_exit(struct dmar_domain *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff8158dbd0)
Location: drivers/iommu/intel-iommu.c:1952
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_attach_device
  - drivers/iommu/intel-iommu.c:intel_iommu_domain_free
  - drivers/iommu/intel-iommu.c:device_notifier
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:iommu_prepare_identity_map
  - drivers/iommu/intel-iommu.c:disable_dmar_iommu
```
**Symbols:**

```
ffffffff8158dbd0-ffffffff8158dcc8: domain_exit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void domain_exit(struct dmar_domain *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff815bb370)
Location: drivers/iommu/intel-iommu.c:1976
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_attach_device
  - drivers/iommu/intel-iommu.c:intel_iommu_domain_free
  - drivers/iommu/intel-iommu.c:device_notifier
  - drivers/iommu/intel-iommu.c:__get_valid_domain_for_dev
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:iommu_prepare_identity_map
  - drivers/iommu/intel-iommu.c:iommu_prepare_identity_map
```
**Symbols:**

```
ffffffff815bb370-ffffffff815bb46a: domain_exit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void domain_exit(struct dmar_domain *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff815d0fd0)
Location: drivers/iommu/intel-iommu.c:1981
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_attach_device
  - drivers/iommu/intel-iommu.c:intel_iommu_domain_free
  - drivers/iommu/intel-iommu.c:intel_iommu_domain_alloc
  - drivers/iommu/intel-iommu.c:device_notifier
  - drivers/iommu/intel-iommu.c:get_valid_domain_for_dev
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:iommu_prepare_identity_map
  - drivers/iommu/intel-iommu.c:iommu_prepare_identity_map
```
**Symbols:**

```
ffffffff815d0fd0-ffffffff815d10c3: domain_exit (STB_LOCAL)
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
In drivers/iommu/intel-iommu.c (ffffffff81639273)
Location: drivers/iommu/intel-iommu.c:1988
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_attach_device
  - drivers/iommu/intel-iommu.c:intel_iommu_domain_free
  - drivers/iommu/intel-iommu.c:intel_iommu_domain_alloc
  - drivers/iommu/intel-iommu.c:device_notifier
  - drivers/iommu/intel-iommu.c:get_valid_domain_for_dev
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:iommu_prepare_identity_map
  - drivers/iommu/intel-iommu.c:iommu_prepare_identity_map
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_attach_device
  - drivers/iommu/intel-iommu.c:intel_iommu_domain_free
  - drivers/iommu/intel-iommu.c:intel_iommu_domain_alloc
  - drivers/iommu/intel-iommu.c:device_notifier
  - drivers/iommu/intel-iommu.c:get_valid_domain_for_dev
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:iommu_prepare_identity_map
  - drivers/iommu/intel-iommu.c:iommu_prepare_identity_map
```
**Symbols:**

```
ffffffff81637dd0-ffffffff81637e76: domain_exit.part.52 (STB_LOCAL)
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
In drivers/iommu/intel-iommu.c (ffffffff816744d3)
Location: drivers/iommu/intel-iommu.c:2016
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_attach_device
  - drivers/iommu/intel-iommu.c:intel_iommu_domain_free
  - drivers/iommu/intel-iommu.c:device_notifier
  - drivers/iommu/intel-iommu.c:get_valid_domain_for_dev
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:iommu_prepare_identity_map
  - drivers/iommu/intel-iommu.c:iommu_prepare_identity_map
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_attach_device
  - drivers/iommu/intel-iommu.c:intel_iommu_domain_free
  - drivers/iommu/intel-iommu.c:device_notifier
  - drivers/iommu/intel-iommu.c:get_valid_domain_for_dev
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:iommu_prepare_identity_map
  - drivers/iommu/intel-iommu.c:iommu_prepare_identity_map
```
**Symbols:**

```
ffffffff81673130-ffffffff816731d6: domain_exit.part.63 (STB_LOCAL)
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
In drivers/iommu/intel-iommu.c (ffffffff81692b03)
Location: drivers/iommu/intel-iommu.c:1902
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_attach_device
  - drivers/iommu/intel-iommu.c:intel_iommu_domain_free
  - drivers/iommu/intel-iommu.c:device_notifier
  - drivers/iommu/intel-iommu.c:get_valid_domain_for_dev
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:iommu_prepare_identity_map
  - drivers/iommu/intel-iommu.c:iommu_prepare_identity_map
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_attach_device
  - drivers/iommu/intel-iommu.c:intel_iommu_domain_free
  - drivers/iommu/intel-iommu.c:device_notifier
  - drivers/iommu/intel-iommu.c:get_valid_domain_for_dev
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:iommu_prepare_identity_map
  - drivers/iommu/intel-iommu.c:iommu_prepare_identity_map
```
**Symbols:**

```
ffffffff8168fe50-ffffffff8168fef6: domain_exit.part.65 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void domain_exit(struct dmar_domain *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816c7ad0)
Location: drivers/iommu/intel-iommu.c:1893
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_domain_free
  - drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info
  - drivers/iommu/intel-iommu.c:init_dmars
```
**Symbols:**

```
ffffffff816c7ad0-ffffffff816c7b82: domain_exit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void domain_exit(struct dmar_domain *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816eaa80)
Location: drivers/iommu/intel-iommu.c:1904
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_domain_free
  - drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info
  - drivers/iommu/intel-iommu.c:init_dmars
```
**Symbols:**

```
ffffffff816eaa80-ffffffff816eab32: domain_exit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void domain_exit(struct dmar_domain *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff817a2220)
Location: drivers/iommu/intel/iommu.c:1919
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_domain_free
  - drivers/iommu/intel/iommu.c:si_domain_init
```
**Symbols:**

```
ffffffff817a2220-ffffffff817a230b: domain_exit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void domain_exit(struct dmar_domain *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff817b03e0)
Location: drivers/iommu/intel/iommu.c:1976
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_domain_free
  - drivers/iommu/intel/iommu.c:si_domain_init
```
**Symbols:**

```
ffffffff817b03e0-ffffffff817b04cd: domain_exit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void domain_exit(struct dmar_domain *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff817921d0)
Location: drivers/iommu/intel/iommu.c:1982
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_domain_free
  - drivers/iommu/intel/iommu.c:si_domain_init
```
**Symbols:**

```
ffffffff817921d0-ffffffff817922bd: domain_exit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void domain_exit(struct dmar_domain *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (0)
Location: drivers/iommu/intel/iommu.c:1978
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_domain_free
  - drivers/iommu/intel/iommu.c:si_domain_init
```
**Symbols:**

```
ffffffff81819fa0-ffffffff8181a081: domain_exit (STB_LOCAL)
ffffffff81cff6fa-ffffffff81cff719: domain_exit.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void domain_exit(struct dmar_domain *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (0)
Location: drivers/iommu/intel/iommu.c:1871
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_domain_alloc
  - drivers/iommu/intel/iommu.c:si_domain_init
```
**Symbols:**

```
ffffffff8195bbd0-ffffffff8195bcbb: domain_exit (STB_LOCAL)
ffffffff81ec8229-ffffffff81ec8248: domain_exit.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void domain_exit(struct dmar_domain *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (0)
Location: drivers/iommu/intel/iommu.c:1857
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_domain_alloc
  - drivers/iommu/intel/iommu.c:init_dmars
  - drivers/iommu/intel/iommu.c:si_domain_init
```
**Symbols:**

```
ffffffff81ac2160-ffffffff81ac2209: domain_exit (STB_LOCAL)
ffffffff82097764-ffffffff82097783: domain_exit.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void domain_exit(struct dmar_domain *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (0)
Location: drivers/iommu/intel/iommu.c:1825
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_domain_alloc
  - drivers/iommu/intel/iommu.c:init_dmars
  - drivers/iommu/intel/iommu.c:si_domain_init
```
**Symbols:**

```
ffffffff81b0e410-ffffffff81b0e4b9: domain_exit (STB_LOCAL)
ffffffff8211879c-ffffffff821187bb: domain_exit.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void domain_exit(struct dmar_domain *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (0)
Location: drivers/iommu/intel/iommu.c:1774
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_domain_free
  - drivers/iommu/intel/iommu.c:intel_iommu_domain_alloc
  - drivers/iommu/intel/iommu.c:init_dmars
  - drivers/iommu/intel/iommu.c:si_domain_init
```
**Symbols:**

```
ffffffff81b63210-ffffffff81b632b9: domain_exit (STB_LOCAL)
ffffffff821f64e8-ffffffff821f6507: domain_exit.cold (STB_LOCAL)
```
</details>
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
<summary>In <code>aws</code>: ✅</summary>

```c
void domain_exit(struct dmar_domain *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816b0560)
Location: drivers/iommu/intel-iommu.c:1904
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_domain_free
  - drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info
  - drivers/iommu/intel-iommu.c:init_dmars
```
**Symbols:**

```
ffffffff816b0560-ffffffff816b0612: domain_exit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void domain_exit(struct dmar_domain *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff8168deb0)
Location: drivers/iommu/intel-iommu.c:1904
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_domain_free
  - drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info
  - drivers/iommu/intel-iommu.c:init_dmars
```
**Symbols:**

```
ffffffff8168deb0-ffffffff8168df62: domain_exit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void domain_exit(struct dmar_domain *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816de740)
Location: drivers/iommu/intel-iommu.c:1904
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_domain_free
  - drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info
  - drivers/iommu/intel-iommu.c:init_dmars
```
**Symbols:**

```
ffffffff816de740-ffffffff816de7f2: domain_exit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void domain_exit(struct dmar_domain *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816f8e60)
Location: drivers/iommu/intel-iommu.c:1904
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_domain_free
  - drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info
  - drivers/iommu/intel-iommu.c:init_dmars
```
**Symbols:**

```
ffffffff816f8e60-ffffffff816f8f12: domain_exit (STB_LOCAL)
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
