# Function: <code>async_schedule_node_domain</code>

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
<summary>In <code>5.3</code>: ✅</summary>

```c
async_cookie_t async_schedule_node_domain(async_func_t func, void *data, int node, struct async_domain *domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/async.c (ffffffff810c5a20)
Location: kernel/async.c:165
Inline: False
Direct callers:
  - kernel/async.c:async_schedule_node
  - drivers/regulator/core.c:regulator_bulk_enable
  - drivers/base/firmware_loader/main.c:dev_cache_fw_image
```
**Symbols:**

```
ffffffff810c5a20-ffffffff810c5bb9: async_schedule_node_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
async_cookie_t async_schedule_node_domain(async_func_t func, void *data, int node, struct async_domain *domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/async.c (ffffffff810ceb00)
Location: kernel/async.c:165
Inline: False
Direct callers:
  - kernel/async.c:async_schedule_node
  - drivers/regulator/core.c:regulator_bulk_enable
  - drivers/base/firmware_loader/main.c:dev_cache_fw_image
```
**Symbols:**

```
ffffffff810ceb00-ffffffff810cec99: async_schedule_node_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
async_cookie_t async_schedule_node_domain(async_func_t func, void *data, int node, struct async_domain *domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/async.c (ffffffff810d8bb0)
Location: kernel/async.c:165
Inline: False
Direct callers:
  - kernel/async.c:async_schedule_node
  - drivers/regulator/core.c:regulator_bulk_enable
  - drivers/base/firmware_loader/main.c:dev_cache_fw_image
  - drivers/scsi/scsi_pm.c:scsi_bus_resume_common
```
**Symbols:**

```
ffffffff810d8bb0-ffffffff810d8d49: async_schedule_node_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
async_cookie_t async_schedule_node_domain(async_func_t func, void *data, int node, struct async_domain *domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/async.c (ffffffff810d3d50)
Location: kernel/async.c:165
Inline: False
Direct callers:
  - kernel/async.c:async_schedule_node
  - drivers/regulator/core.c:regulator_bulk_enable
  - drivers/base/firmware_loader/main.c:dev_cache_fw_image
  - drivers/scsi/scsi_pm.c:scsi_bus_resume_common
```
**Symbols:**

```
ffffffff810d3d50-ffffffff810d3ee9: async_schedule_node_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
async_cookie_t async_schedule_node_domain(async_func_t func, void *data, int node, struct async_domain *domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/async.c (ffffffff810d59e0)
Location: kernel/async.c:165
Inline: False
Direct callers:
  - init/initramfs.c:populate_rootfs
  - kernel/async.c:async_schedule_node
  - drivers/regulator/core.c:regulator_bulk_enable
  - drivers/base/firmware_loader/main.c:dev_cache_fw_image
  - drivers/scsi/scsi_pm.c:scsi_bus_resume_common
```
**Symbols:**

```
ffffffff810d59e0-ffffffff810d5b79: async_schedule_node_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
async_cookie_t async_schedule_node_domain(async_func_t func, void *data, int node, struct async_domain *domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/async.c (ffffffff810e8c00)
Location: kernel/async.c:165
Inline: False
Direct callers:
  - init/initramfs.c:populate_rootfs
  - kernel/async.c:async_schedule_node
  - drivers/regulator/core.c:regulator_bulk_enable
  - drivers/base/firmware_loader/main.c:dev_cache_fw_image
  - drivers/scsi/scsi_pm.c:scsi_bus_resume_common
```
**Symbols:**

```
ffffffff810e8c00-ffffffff810e8d89: async_schedule_node_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
async_cookie_t async_schedule_node_domain(async_func_t func, void *data, int node, struct async_domain *domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/async.c (ffffffff811036e0)
Location: kernel/async.c:165
Inline: False
Direct callers:
  - init/initramfs.c:populate_rootfs
  - kernel/async.c:async_schedule_node
  - drivers/regulator/core.c:regulator_bulk_enable
  - drivers/base/firmware_loader/main.c:dev_cache_fw_image
```
**Symbols:**

```
ffffffff811036e0-ffffffff81103863: async_schedule_node_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
async_cookie_t async_schedule_node_domain(async_func_t func, void *data, int node, struct async_domain *domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/async.c (ffffffff81128dd0)
Location: kernel/async.c:165
Inline: False
Direct callers:
  - init/initramfs.c:populate_rootfs
  - kernel/async.c:async_schedule_node
  - drivers/regulator/core.c:regulator_bulk_enable
  - drivers/base/firmware_loader/main.c:dev_cache_fw_image
```
**Symbols:**

```
ffffffff81128dd0-ffffffff81128f53: async_schedule_node_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
async_cookie_t async_schedule_node_domain(async_func_t func, void *data, int node, struct async_domain *domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/async.c (ffffffff81136280)
Location: kernel/async.c:165
Inline: False
Direct callers:
  - init/initramfs.c:populate_rootfs
  - kernel/async.c:async_schedule_node
  - drivers/regulator/core.c:regulator_bulk_enable
  - drivers/base/firmware_loader/main.c:dev_cache_fw_image
```
**Symbols:**

```
ffffffff81136280-ffffffff811363fb: async_schedule_node_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
async_cookie_t async_schedule_node_domain(async_func_t func, void *data, int node, struct async_domain *domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/async.c (ffffffff81141430)
Location: kernel/async.c:199
Inline: False
Direct callers:
  - init/initramfs.c:populate_rootfs
  - kernel/async.c:async_schedule_node
  - drivers/regulator/core.c:regulator_bulk_enable
  - drivers/base/firmware_loader/main.c:dev_cache_fw_image
```
**Symbols:**

```
ffffffff81141430-ffffffff81141530: async_schedule_node_domain (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
async_cookie_t async_schedule_node_domain(async_func_t func, void *data, int node, struct async_domain *domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/async.c (ffff80001012ea10)
Location: kernel/async.c:165
Inline: False
Direct callers:
  - kernel/async.c:async_schedule_node
  - drivers/regulator/core.c:regulator_bulk_enable
  - drivers/base/firmware_loader/main.c:dev_cache_fw_image
```
**Symbols:**

```
ffff80001012ea10-ffff80001012ec88: async_schedule_node_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
async_cookie_t async_schedule_node_domain(async_func_t func, void *data, int node, struct async_domain *domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/async.c (c037e488)
Location: kernel/async.c:165
Inline: False
Direct callers:
  - kernel/async.c:async_schedule_node
  - drivers/regulator/core.c:regulator_bulk_enable
  - drivers/base/firmware_loader/main.c:dev_cache_fw_image
  - sound/soc/soc-dapm.c:dapm_power_widgets
  - sound/soc/soc-dapm.c:dapm_power_widgets
```
**Symbols:**

```
c037e488-c037e66c: async_schedule_node_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
async_cookie_t async_schedule_node_domain(async_func_t func, void *data, int node, struct async_domain *domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/async.c (c000000000177af0)
Location: kernel/async.c:165
Inline: False
Direct callers:
  - kernel/async.c:async_schedule_node
  - drivers/regulator/core.c:regulator_bulk_enable
  - drivers/base/firmware_loader/main.c:dev_cache_fw_image
```
**Symbols:**

```
c000000000177af0-c000000000177d60: async_schedule_node_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
async_cookie_t async_schedule_node_domain(async_func_t func, void *data, int node, struct async_domain *domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/async.c (ffffffe0000e2612)
Location: kernel/async.c:165
Inline: False
Direct callers:
  - kernel/async.c:async_schedule_node
  - drivers/regulator/core.c:regulator_bulk_enable
```
**Symbols:**

```
ffffffe0000e2612-ffffffe0000e2796: async_schedule_node_domain (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
async_cookie_t async_schedule_node_domain(async_func_t func, void *data, int node, struct async_domain *domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/async.c (ffffffff810c8e80)
Location: kernel/async.c:165
Inline: False
Direct callers:
  - kernel/async.c:async_schedule_node
  - drivers/regulator/core.c:regulator_bulk_enable
  - drivers/base/firmware_loader/main.c:dev_cache_fw_image
```
**Symbols:**

```
ffffffff810c8e80-ffffffff810c9019: async_schedule_node_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
async_cookie_t async_schedule_node_domain(async_func_t func, void *data, int node, struct async_domain *domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/async.c (ffffffff810b76a0)
Location: kernel/async.c:165
Inline: False
Direct callers:
  - kernel/async.c:async_schedule_node
  - drivers/regulator/core.c:regulator_bulk_enable
  - drivers/base/firmware_loader/main.c:dev_cache_fw_image
```
**Symbols:**

```
ffffffff810b76a0-ffffffff810b7839: async_schedule_node_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
async_cookie_t async_schedule_node_domain(async_func_t func, void *data, int node, struct async_domain *domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/async.c (ffffffff810c83b0)
Location: kernel/async.c:165
Inline: False
Direct callers:
  - kernel/async.c:async_schedule_node
  - drivers/regulator/core.c:regulator_bulk_enable
  - drivers/base/firmware_loader/main.c:dev_cache_fw_image
```
**Symbols:**

```
ffffffff810c83b0-ffffffff810c8549: async_schedule_node_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
async_cookie_t async_schedule_node_domain(async_func_t func, void *data, int node, struct async_domain *domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/async.c (ffffffff810d08e0)
Location: kernel/async.c:165
Inline: False
Direct callers:
  - kernel/async.c:async_schedule_node
  - drivers/regulator/core.c:regulator_bulk_enable
  - drivers/base/firmware_loader/main.c:dev_cache_fw_image
```
**Symbols:**

```
ffffffff810d08e0-ffffffff810d0a79: async_schedule_node_domain (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
