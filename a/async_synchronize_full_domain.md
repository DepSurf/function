# Function: <code>async_synchronize_full_domain</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void async_synchronize_full_domain(struct async_domain *domain);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/async.c (ffffffff810a3180)
Location: kernel/async.c:268
Inline: True
Inline callers:
  - kernel/async.c:async_synchronize_full
Direct callers:
  - drivers/regulator/core.c:regulator_bulk_enable
  - drivers/regulator/core.c:regulator_bulk_enable
  - drivers/scsi/sd.c:sd_remove
  - drivers/scsi/sd.c:sd_remove
```
**Symbols:**

```
ffffffff810a3180-ffffffff810a319a: async_synchronize_full_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void async_synchronize_full_domain(struct async_domain *domain);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/async.c (ffffffff810a68b6)
Location: kernel/async.c:268
Inline: True
Inline callers:
  - kernel/async.c:async_synchronize_full
Direct callers:
  - drivers/regulator/core.c:regulator_bulk_enable
  - drivers/regulator/core.c:regulator_bulk_enable
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/scsi/scsi_pm.c:scsi_bus_resume_common
  - drivers/scsi/sd.c:sd_remove
  - drivers/scsi/sd.c:sd_remove
```
**Symbols:**

```
ffffffff810a6890-ffffffff810a68aa: async_synchronize_full_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void async_synchronize_full_domain(struct async_domain *domain);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/async.c (ffffffff810ac516)
Location: kernel/async.c:268
Inline: True
Inline callers:
  - kernel/async.c:async_synchronize_full
Direct callers:
  - drivers/regulator/core.c:regulator_bulk_enable
  - drivers/regulator/core.c:regulator_bulk_enable
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/scsi/scsi_pm.c:scsi_bus_resume_common
  - drivers/scsi/sd.c:sd_remove
  - drivers/scsi/sd.c:sd_remove
```
**Symbols:**

```
ffffffff810ac4f0-ffffffff810ac50a: async_synchronize_full_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void async_synchronize_full_domain(struct async_domain *domain);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/async.c (ffffffff810a90e6)
Location: kernel/async.c:268
Inline: True
Inline callers:
  - kernel/async.c:async_synchronize_full
Direct callers:
  - drivers/regulator/core.c:regulator_bulk_enable
  - drivers/regulator/core.c:regulator_bulk_enable
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/scsi/scsi_pm.c:scsi_bus_resume_common
  - drivers/scsi/sd.c:sd_remove
  - drivers/scsi/sd.c:sd_remove
```
**Symbols:**

```
ffffffff810a90c0-ffffffff810a90da: async_synchronize_full_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void async_synchronize_full_domain(struct async_domain *domain);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/async.c (ffffffff810af966)
Location: kernel/async.c:272
Inline: True
Inline callers:
  - kernel/async.c:async_synchronize_full
Direct callers:
  - drivers/regulator/core.c:regulator_bulk_enable
  - drivers/regulator/core.c:regulator_bulk_enable
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/scsi/scsi_pm.c:scsi_bus_resume_common
  - drivers/scsi/sd.c:sd_remove
  - drivers/scsi/sd.c:sd_remove
```
**Symbols:**

```
ffffffff810af940-ffffffff810af95a: async_synchronize_full_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void async_synchronize_full_domain(struct async_domain *domain);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/async.c (ffffffff810b67c5)
Location: kernel/async.c:272
Inline: True
Inline callers:
  - kernel/async.c:async_synchronize_full
Direct callers:
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/scsi/scsi_pm.c:scsi_bus_resume_common
  - drivers/scsi/sd.c:sd_remove
  - drivers/scsi/sd.c:sd_remove
```
**Symbols:**

```
ffffffff810b67a0-ffffffff810b67ba: async_synchronize_full_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void async_synchronize_full_domain(struct async_domain *domain);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/async.c (ffffffff810bfc15)
Location: kernel/async.c:272
Inline: True
Inline callers:
  - kernel/async.c:async_synchronize_full
Direct callers:
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/scsi/sd.c:sd_remove
  - drivers/scsi/sd.c:sd_remove
```
**Symbols:**

```
ffffffff810bfbf0-ffffffff810bfc0a: async_synchronize_full_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void async_synchronize_full_domain(struct async_domain *domain);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/async.c (ffffffff810c5d45)
Location: kernel/async.c:273
Inline: True
Inline callers:
  - kernel/async.c:async_synchronize_full
Direct callers:
  - drivers/regulator/core.c:regulator_bulk_enable
  - drivers/regulator/core.c:regulator_bulk_enable
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/scsi/sd.c:sd_remove
```
**Symbols:**

```
ffffffff810c5d20-ffffffff810c5d3a: async_synchronize_full_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void async_synchronize_full_domain(struct async_domain *domain);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/async.c (ffffffff810cee25)
Location: kernel/async.c:273
Inline: True
Inline callers:
  - kernel/async.c:async_synchronize_full
Direct callers:
  - drivers/regulator/core.c:regulator_bulk_enable
  - drivers/regulator/core.c:regulator_bulk_enable
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/scsi/sd.c:sd_remove
```
**Symbols:**

```
ffffffff810cee00-ffffffff810cee1a: async_synchronize_full_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void async_synchronize_full_domain(struct async_domain *domain);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/async.c (ffffffff810d8b25)
Location: kernel/async.c:273
Inline: True
Inline callers:
  - kernel/async.c:async_synchronize_full
Direct callers:
  - drivers/regulator/core.c:regulator_bulk_enable
  - drivers/regulator/core.c:regulator_bulk_enable
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/scsi/scsi_pm.c:scsi_bus_resume_common
  - drivers/scsi/scsi_pm.c:scsi_dev_type_suspend
  - drivers/scsi/sd.c:sd_remove
```
**Symbols:**

```
ffffffff810d8b00-ffffffff810d8b1a: async_synchronize_full_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void async_synchronize_full_domain(struct async_domain *domain);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/async.c (ffffffff810d3cc5)
Location: kernel/async.c:273
Inline: True
Inline callers:
  - kernel/async.c:async_synchronize_full
Direct callers:
  - drivers/regulator/core.c:regulator_bulk_enable
  - drivers/regulator/core.c:regulator_bulk_enable
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/scsi/scsi_pm.c:scsi_bus_resume_common
  - drivers/scsi/scsi_pm.c:scsi_dev_type_suspend
  - drivers/scsi/sd.c:sd_remove
```
**Symbols:**

```
ffffffff810d3ca0-ffffffff810d3cba: async_synchronize_full_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void async_synchronize_full_domain(struct async_domain *domain);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/async.c (ffffffff810d5955)
Location: kernel/async.c:255
Inline: True
Inline callers:
  - kernel/async.c:async_synchronize_full
Direct callers:
  - drivers/regulator/core.c:regulator_bulk_enable
  - drivers/regulator/core.c:regulator_bulk_enable
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/scsi/scsi_pm.c:scsi_bus_resume_common
  - drivers/scsi/scsi_pm.c:scsi_dev_type_suspend
  - drivers/scsi/sd.c:sd_remove
```
**Symbols:**

```
ffffffff810d5930-ffffffff810d594a: async_synchronize_full_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void async_synchronize_full_domain(struct async_domain *domain);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/async.c (ffffffff810e8b75)
Location: kernel/async.c:252
Inline: True
Inline callers:
  - kernel/async.c:async_synchronize_full
Direct callers:
  - drivers/regulator/core.c:regulator_bulk_enable
  - drivers/regulator/core.c:regulator_bulk_enable
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/scsi/scsi_pm.c:scsi_bus_resume_common
  - drivers/scsi/scsi_pm.c:scsi_dev_type_suspend
  - drivers/scsi/sd.c:sd_remove
```
**Symbols:**

```
ffffffff810e8b50-ffffffff810e8b6a: async_synchronize_full_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void async_synchronize_full_domain(struct async_domain *domain);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/async.c (ffffffff81103635)
Location: kernel/async.c:252
Inline: True
Inline callers:
  - kernel/async.c:async_synchronize_full
Direct callers:
  - drivers/regulator/core.c:regulator_bulk_enable
  - drivers/regulator/core.c:regulator_bulk_enable
  - drivers/nvdimm/bus.c:nd_bus_remove
```
**Symbols:**

```
ffffffff81103600-ffffffff81103622: async_synchronize_full_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void async_synchronize_full_domain(struct async_domain *domain);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/async.c (ffffffff81128cf5)
Location: kernel/async.c:252
Inline: True
Inline callers:
  - kernel/async.c:async_synchronize_full
Direct callers:
  - drivers/regulator/core.c:regulator_bulk_enable
  - drivers/regulator/core.c:regulator_bulk_enable
  - drivers/nvdimm/bus.c:nd_bus_remove
```
**Symbols:**

```
ffffffff81128cb0-ffffffff81128cd2: async_synchronize_full_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void async_synchronize_full_domain(struct async_domain *domain);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/async.c (ffffffff811361a5)
Location: kernel/async.c:252
Inline: True
Inline callers:
  - kernel/async.c:async_synchronize_full
Direct callers:
  - drivers/regulator/core.c:regulator_bulk_enable
  - drivers/regulator/core.c:regulator_bulk_enable
  - drivers/nvdimm/bus.c:nd_bus_remove
```
**Symbols:**

```
ffffffff81136160-ffffffff81136182: async_synchronize_full_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void async_synchronize_full_domain(struct async_domain *domain);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/async.c (ffffffff81141355)
Location: kernel/async.c:294
Inline: True
Inline callers:
  - kernel/async.c:async_synchronize_full
Direct callers:
  - drivers/regulator/core.c:regulator_bulk_enable
  - drivers/regulator/core.c:regulator_bulk_enable
  - drivers/nvdimm/bus.c:nd_bus_remove
```
**Symbols:**

```
ffffffff81141310-ffffffff81141332: async_synchronize_full_domain (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void async_synchronize_full_domain(struct async_domain *domain);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/async.c (ffff80001012e7e0)
Location: kernel/async.c:273
Inline: True
Inline callers:
  - kernel/async.c:async_synchronize_full
Direct callers:
  - drivers/regulator/core.c:regulator_bulk_enable
  - drivers/regulator/core.c:regulator_bulk_enable
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/scsi/sd.c:sd_remove
```
**Symbols:**

```
ffff80001012e7a0-ffff80001012e7d0: async_synchronize_full_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void async_synchronize_full_domain(struct async_domain *domain);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/async.c (c037e908)
Location: kernel/async.c:273
Inline: True
Inline callers:
  - kernel/async.c:async_synchronize_full
Direct callers:
  - drivers/regulator/core.c:regulator_bulk_enable
  - drivers/regulator/core.c:regulator_bulk_enable
  - drivers/scsi/sd.c:sd_remove
  - sound/soc/soc-dapm.c:dapm_power_widgets
  - sound/soc/soc-dapm.c:dapm_power_widgets
```
**Symbols:**

```
c037e8cc-c037e8f4: async_synchronize_full_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void async_synchronize_full_domain(struct async_domain *domain);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/async.c (c000000000177a20)
Location: kernel/async.c:273
Inline: True
Inline callers:
  - kernel/async.c:async_synchronize_full
Direct callers:
  - drivers/regulator/core.c:regulator_bulk_enable
  - drivers/regulator/core.c:regulator_bulk_enable
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/scsi/sd.c:sd_remove
```
**Symbols:**

```
c0000000001779f0-c000000000177a0c: async_synchronize_full_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void async_synchronize_full_domain(struct async_domain *domain);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/async.c (ffffffe0000e296e)
Location: kernel/async.c:273
Inline: True
Inline callers:
  - kernel/async.c:async_synchronize_full
Direct callers:
  - drivers/regulator/core.c:regulator_bulk_enable
  - drivers/regulator/core.c:regulator_bulk_enable
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/scsi/sd.c:sd_remove
```
**Symbols:**

```
ffffffe0000e2930-ffffffe0000e295c: async_synchronize_full_domain (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void async_synchronize_full_domain(struct async_domain *domain);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/async.c (ffffffff810c91a5)
Location: kernel/async.c:273
Inline: True
Inline callers:
  - kernel/async.c:async_synchronize_full
Direct callers:
  - drivers/regulator/core.c:regulator_bulk_enable
  - drivers/regulator/core.c:regulator_bulk_enable
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/scsi/sd.c:sd_remove
```
**Symbols:**

```
ffffffff810c9180-ffffffff810c919a: async_synchronize_full_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void async_synchronize_full_domain(struct async_domain *domain);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/async.c (ffffffff810b79c5)
Location: kernel/async.c:273
Inline: True
Inline callers:
  - kernel/async.c:async_synchronize_full
Direct callers:
  - drivers/regulator/core.c:regulator_bulk_enable
  - drivers/regulator/core.c:regulator_bulk_enable
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/scsi/sd.c:sd_remove
```
**Symbols:**

```
ffffffff810b79a0-ffffffff810b79ba: async_synchronize_full_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void async_synchronize_full_domain(struct async_domain *domain);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/async.c (ffffffff810c86d5)
Location: kernel/async.c:273
Inline: True
Inline callers:
  - kernel/async.c:async_synchronize_full
Direct callers:
  - drivers/regulator/core.c:regulator_bulk_enable
  - drivers/regulator/core.c:regulator_bulk_enable
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/scsi/sd.c:sd_remove
```
**Symbols:**

```
ffffffff810c86b0-ffffffff810c86ca: async_synchronize_full_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void async_synchronize_full_domain(struct async_domain *domain);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/async.c (ffffffff810d0c15)
Location: kernel/async.c:273
Inline: True
Inline callers:
  - kernel/async.c:async_synchronize_full
Direct callers:
  - drivers/regulator/core.c:regulator_bulk_enable
  - drivers/regulator/core.c:regulator_bulk_enable
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/scsi/sd.c:sd_remove
```
**Symbols:**

```
ffffffff810d0bf0-ffffffff810d0c0a: async_synchronize_full_domain (STB_GLOBAL)
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
No changes between <code>amd64</code> and <code>armhf</code> ✅
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
