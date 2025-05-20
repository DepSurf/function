# Function: <code>device_flush_dte</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int device_flush_dte(struct iommu_dev_data *dev_data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff8152fb30)
Location: drivers/iommu/amd_iommu.c:1013
Inline: True
Direct callers:
  - drivers/iommu/amd_iommu.c:__detach_device
  - drivers/iommu/amd_iommu.c:amd_iommu_attach_device
```
**Symbols:**

```
ffffffff8152fb30-ffffffff8152fc10: device_flush_dte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int device_flush_dte(struct iommu_dev_data *dev_data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff81583370)
Location: drivers/iommu/amd_iommu.c:1109
Inline: True
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_attach_device
  - drivers/iommu/amd_iommu.c:__detach_device
```
**Symbols:**

```
ffffffff81583370-ffffffff81583449: device_flush_dte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int device_flush_dte(struct iommu_dev_data *dev_data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff815b0680)
Location: drivers/iommu/amd_iommu.c:1198
Inline: True
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_attach_device
  - drivers/iommu/amd_iommu.c:__detach_device
```
**Symbols:**

```
ffffffff815b0680-ffffffff815b0754: device_flush_dte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int device_flush_dte(struct iommu_dev_data *dev_data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff815c6380)
Location: drivers/iommu/amd_iommu.c:1257
Inline: True
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_attach_device
  - drivers/iommu/amd_iommu.c:__detach_device
```
**Symbols:**

```
ffffffff815c6380-ffffffff815c6479: device_flush_dte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int device_flush_dte(struct iommu_dev_data *dev_data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff8162ce50)
Location: drivers/iommu/amd_iommu.c:1198
Inline: True
Direct callers:
  - drivers/iommu/amd_iommu.c:__detach_device
  - drivers/iommu/amd_iommu.c:attach_device
```
**Symbols:**

```
ffffffff8162ce50-ffffffff8162cf49: device_flush_dte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int device_flush_dte(struct iommu_dev_data *dev_data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff81667c10)
Location: drivers/iommu/amd_iommu.c:1204
Inline: True
Direct callers:
  - drivers/iommu/amd_iommu.c:__detach_device
  - drivers/iommu/amd_iommu.c:attach_device
```
**Symbols:**

```
ffffffff81667c10-ffffffff81667cf4: device_flush_dte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int device_flush_dte(struct iommu_dev_data *dev_data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff81685d30)
Location: drivers/iommu/amd_iommu.c:1219
Inline: True
Direct callers:
  - drivers/iommu/amd_iommu.c:attach_device
  - drivers/iommu/amd_iommu.c:do_detach
```
**Symbols:**

```
ffffffff81685d30-ffffffff81685e14: device_flush_dte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int device_flush_dte(struct iommu_dev_data *dev_data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816bd490)
Location: drivers/iommu/amd_iommu.c:1218
Inline: True
Direct callers:
  - drivers/iommu/amd_iommu.c:attach_device
  - drivers/iommu/amd_iommu.c:do_detach
```
**Symbols:**

```
ffffffff816bd490-ffffffff816bd574: device_flush_dte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int device_flush_dte(struct iommu_dev_data *dev_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816e0470)
Location: drivers/iommu/amd_iommu.c:1232
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:update_domain
  - drivers/iommu/amd_iommu.c:attach_device
  - drivers/iommu/amd_iommu.c:do_detach
```
**Symbols:**

```
ffffffff816e0470-ffffffff816e0575: device_flush_dte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81796940)
Location: drivers/iommu/amd/iommu.c:1176
Inline: True
Direct callers:
  - drivers/iommu/amd/iommu.c:update_domain
  - drivers/iommu/amd/iommu.c:do_detach
  - drivers/iommu/amd/iommu.c:do_attach
  - drivers/iommu/amd/iommu.c:increase_address_space
```
**Symbols:**

```
ffffffff81796940-ffffffff817969d4: device_flush_dte.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff817a5060)
Location: drivers/iommu/amd/iommu.c:1266
Inline: True
Direct callers:
  - drivers/iommu/amd/iommu.c:update_domain
  - drivers/iommu/amd/iommu.c:do_detach
  - drivers/iommu/amd/iommu.c:do_attach
  - drivers/iommu/amd/iommu.c:increase_address_space
```
**Symbols:**

```
ffffffff817a5060-ffffffff817a50f4: device_flush_dte.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81787360)
Location: drivers/iommu/amd/iommu.c:1198
Inline: True
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_update
  - drivers/iommu/amd/iommu.c:attach_device
  - drivers/iommu/amd/iommu.c:do_detach
```
**Symbols:**

```
ffffffff81787360-ffffffff817873f4: device_flush_dte.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/iommu.c (0)
Location: drivers/iommu/amd/iommu.c:1210
Inline: True
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_update
  - drivers/iommu/amd/iommu.c:attach_device
  - drivers/iommu/amd/iommu.c:do_detach
```
**Symbols:**

```
ffffffff8180e630-ffffffff8180e6d1: device_flush_dte.isra.0 (STB_LOCAL)
ffffffff81cfe073-ffffffff81cfe088: device_flush_dte.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/iommu.c (0)
Location: drivers/iommu/amd/iommu.c:1232
Inline: True
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_update
  - drivers/iommu/amd/iommu.c:attach_device
  - drivers/iommu/amd/iommu.c:do_detach
```
**Symbols:**

```
ffffffff8194f830-ffffffff8194f8fb: device_flush_dte.isra.0 (STB_LOCAL)
ffffffff81ec6a01-ffffffff81ec6a16: device_flush_dte.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/iommu.c (0)
Location: drivers/iommu/amd/iommu.c:1306
Inline: True
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_update
  - drivers/iommu/amd/iommu.c:attach_device
  - drivers/iommu/amd/iommu.c:do_detach
```
**Symbols:**

```
ffffffff81ab5930-ffffffff81ab5ac0: device_flush_dte.isra.0 (STB_LOCAL)
ffffffff82096eec-ffffffff82096f01: device_flush_dte.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/iommu.c (0)
Location: drivers/iommu/amd/iommu.c:1326
Inline: True
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_update
  - drivers/iommu/amd/iommu.c:attach_device
  - drivers/iommu/amd/iommu.c:do_detach
```
**Symbols:**

```
ffffffff81b01300-ffffffff81b013da: device_flush_dte.isra.0 (STB_LOCAL)
ffffffff82117d8a-ffffffff82117d9f: device_flush_dte.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81b55080)
Location: drivers/iommu/amd/iommu.c:1416
Inline: True
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_set_dirty_tracking
  - drivers/iommu/amd/iommu.c:amd_iommu_attach_device
  - drivers/iommu/amd/iommu.c:protection_domain_alloc
  - drivers/iommu/amd/iommu.c:do_detach
```
**Symbols:**

```
ffffffff81b55080-ffffffff81b551ec: device_flush_dte.isra.0 (STB_LOCAL)
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
int device_flush_dte(struct iommu_dev_data *dev_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816a5ec0)
Location: drivers/iommu/amd_iommu.c:1232
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:update_domain
  - drivers/iommu/amd_iommu.c:attach_device
  - drivers/iommu/amd_iommu.c:do_detach
```
**Symbols:**

```
ffffffff816a5ec0-ffffffff816a5fc5: device_flush_dte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int device_flush_dte(struct iommu_dev_data *dev_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816838b0)
Location: drivers/iommu/amd_iommu.c:1232
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:update_domain
  - drivers/iommu/amd_iommu.c:attach_device
  - drivers/iommu/amd_iommu.c:do_detach
```
**Symbols:**

```
ffffffff816838b0-ffffffff816839b5: device_flush_dte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int device_flush_dte(struct iommu_dev_data *dev_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816d4130)
Location: drivers/iommu/amd_iommu.c:1232
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:update_domain
  - drivers/iommu/amd_iommu.c:attach_device
  - drivers/iommu/amd_iommu.c:do_detach
```
**Symbols:**

```
ffffffff816d4130-ffffffff816d4235: device_flush_dte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int device_flush_dte(struct iommu_dev_data *dev_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816ee830)
Location: drivers/iommu/amd_iommu.c:1232
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:update_domain
  - drivers/iommu/amd_iommu.c:attach_device
  - drivers/iommu/amd_iommu.c:do_detach
```
**Symbols:**

```
ffffffff816ee830-ffffffff816ee935: device_flush_dte (STB_LOCAL)
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
