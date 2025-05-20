# Function: <code>async_schedule_domain</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
async_cookie_t async_schedule_domain(async_func_t func, void *data, struct async_domain *domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/async.c (ffffffff810a33c0)
Location: kernel/async.c:225
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_bulk_enable
  - drivers/base/firmware_class.c:dev_cache_fw_image
  - drivers/nvdimm/bus.c:__nd_device_register
  - drivers/scsi/sd.c:sd_probe
```
**Symbols:**

```
ffffffff810a33c0-ffffffff810a33d0: async_schedule_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
async_cookie_t async_schedule_domain(async_func_t func, void *data, struct async_domain *domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/async.c (ffffffff810a6ae0)
Location: kernel/async.c:225
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_bulk_enable
  - drivers/base/firmware_class.c:dev_cache_fw_image
  - drivers/nvdimm/bus.c:__nd_device_register
  - drivers/scsi/scsi_pm.c:scsi_bus_resume_common
  - drivers/scsi/sd.c:sd_probe
```
**Symbols:**

```
ffffffff810a6ae0-ffffffff810a6af0: async_schedule_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
async_cookie_t async_schedule_domain(async_func_t func, void *data, struct async_domain *domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/async.c (ffffffff810ac740)
Location: kernel/async.c:225
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_bulk_enable
  - drivers/base/firmware_class.c:dev_cache_fw_image
  - drivers/nvdimm/bus.c:__nd_device_register
  - drivers/scsi/scsi_pm.c:scsi_bus_resume_common
  - drivers/scsi/sd.c:sd_probe
```
**Symbols:**

```
ffffffff810ac740-ffffffff810ac750: async_schedule_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
async_cookie_t async_schedule_domain(async_func_t func, void *data, struct async_domain *domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/async.c (ffffffff810a9310)
Location: kernel/async.c:225
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_bulk_enable
  - drivers/base/firmware_class.c:dev_cache_fw_image
  - drivers/nvdimm/bus.c:nd_device_register
  - drivers/scsi/scsi_pm.c:scsi_bus_resume_common
  - drivers/scsi/sd.c:sd_probe
```
**Symbols:**

```
ffffffff810a9310-ffffffff810a9320: async_schedule_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
async_cookie_t async_schedule_domain(async_func_t func, void *data, struct async_domain *domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/async.c (ffffffff810afba0)
Location: kernel/async.c:229
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_bulk_enable
  - drivers/base/firmware_class.c:dev_cache_fw_image
  - drivers/nvdimm/bus.c:nd_device_register
  - drivers/scsi/scsi_pm.c:scsi_bus_resume_common
  - drivers/scsi/sd.c:sd_probe
```
**Symbols:**

```
ffffffff810afba0-ffffffff810afbb0: async_schedule_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
async_cookie_t async_schedule_domain(async_func_t func, void *data, struct async_domain *domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/async.c (ffffffff810b6a00)
Location: kernel/async.c:229
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:dev_cache_fw_image
  - drivers/nvdimm/bus.c:nd_device_register
  - drivers/scsi/scsi_pm.c:scsi_bus_resume_common
  - drivers/scsi/sd.c:sd_probe
```
**Symbols:**

```
ffffffff810b6a00-ffffffff810b6a10: async_schedule_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
async_cookie_t async_schedule_domain(async_func_t func, void *data, struct async_domain *domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/async.c (ffffffff810bfaa0)
Location: kernel/async.c:229
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:dev_cache_fw_image
  - drivers/scsi/sd.c:sd_probe
```
**Symbols:**

```
ffffffff810bfaa0-ffffffff810bfab0: async_schedule_domain (STB_GLOBAL)
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
In drivers/regulator/core.c (ffffffff8165a459)
Location: include/linux/async.h:69
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_bulk_enable
```
```
In drivers/base/firmware_loader/main.c (ffffffff816f5059)
Location: include/linux/async.h:69
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:dev_cache_fw_image
```
```
In drivers/nvdimm/bus.c (ffffffff8172cec4)
Location: include/linux/async.h:69
Inline: True
```
```
In drivers/scsi/scsi_pm.c (ffffffff8175970e)
Location: include/linux/async.h:69
Inline: True
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
In drivers/regulator/core.c (ffffffff8167d199)
Location: include/linux/async.h:69
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_bulk_enable
```
```
In drivers/base/firmware_loader/main.c (ffffffff81719459)
Location: include/linux/async.h:69
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:dev_cache_fw_image
```
```
In drivers/nvdimm/bus.c (ffffffff81750ee4)
Location: include/linux/async.h:69
Inline: True
```
```
In drivers/scsi/scsi_pm.c (ffffffff8177d62e)
Location: include/linux/async.h:69
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
In drivers/regulator/core.c (ffffffff8172e546)
Location: include/linux/async.h:69
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_bulk_enable
```
```
In drivers/base/firmware_loader/main.c (ffffffff817d51ab)
Location: include/linux/async.h:69
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:dev_cache_fw_image
```
```
In drivers/nvdimm/bus.c (ffffffff8180f724)
Location: include/linux/async.h:69
Inline: True
```
```
In drivers/scsi/scsi_pm.c (ffffffff81840a9e)
Location: include/linux/async.h:69
Inline: True
Inline callers:
  - drivers/scsi/scsi_pm.c:scsi_bus_resume_common
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
In drivers/regulator/core.c (ffffffff8174b116)
Location: include/linux/async.h:69
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_bulk_enable
```
```
In drivers/base/firmware_loader/main.c (ffffffff817e9a7b)
Location: include/linux/async.h:69
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:dev_cache_fw_image
```
```
In drivers/nvdimm/bus.c (ffffffff8181e664)
Location: include/linux/async.h:69
Inline: True
```
```
In drivers/scsi/scsi_pm.c (ffffffff81850fde)
Location: include/linux/async.h:69
Inline: True
Inline callers:
  - drivers/scsi/scsi_pm.c:scsi_bus_resume_common
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
In init/initramfs.c (ffffffff831ba970)
Location: include/linux/async.h:69
Inline: True
Inline callers:
  - init/initramfs.c:populate_rootfs
```
```
In drivers/regulator/core.c (ffffffff8172e829)
Location: include/linux/async.h:69
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_bulk_enable
```
```
In drivers/base/firmware_loader/main.c (ffffffff817ce26b)
Location: include/linux/async.h:69
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:dev_cache_fw_image
```
```
In drivers/nvdimm/bus.c (ffffffff81801e54)
Location: include/linux/async.h:69
Inline: True
```
```
In drivers/scsi/scsi_pm.c (ffffffff8183406e)
Location: include/linux/async.h:69
Inline: True
Inline callers:
  - drivers/scsi/scsi_pm.c:scsi_bus_resume_common
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
In init/initramfs.c (ffffffff8329ae5c)
Location: include/linux/async.h:69
Inline: True
Inline callers:
  - init/initramfs.c:populate_rootfs
```
```
In drivers/regulator/core.c (ffffffff817ae409)
Location: include/linux/async.h:69
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_bulk_enable
```
```
In drivers/base/firmware_loader/main.c (ffffffff81858b0b)
Location: include/linux/async.h:69
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:dev_cache_fw_image
```
```
In drivers/nvdimm/bus.c (ffffffff8188c354)
Location: include/linux/async.h:69
Inline: True
```
```
In drivers/scsi/scsi_pm.c (ffffffff818c006e)
Location: include/linux/async.h:69
Inline: True
Inline callers:
  - drivers/scsi/scsi_pm.c:scsi_bus_resume_common
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
In init/initramfs.c (ffffffff8344991c)
Location: include/linux/async.h:69
Inline: True
Inline callers:
  - init/initramfs.c:populate_rootfs
```
```
In drivers/regulator/core.c (ffffffff818e93ec)
Location: include/linux/async.h:69
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_bulk_enable
```
```
In drivers/base/firmware_loader/main.c (ffffffff8199f4d9)
Location: include/linux/async.h:69
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:dev_cache_fw_image
```
```
In drivers/nvdimm/bus.c (ffffffff819d5740)
Location: include/linux/async.h:69
Inline: True
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
In init/initramfs.c (ffffffff83e63455)
Location: include/linux/async.h:69
Inline: True
Inline callers:
  - init/initramfs.c:populate_rootfs
```
```
In drivers/regulator/core.c (ffffffff81a3f728)
Location: include/linux/async.h:69
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_bulk_enable
```
```
In drivers/base/firmware_loader/main.c (ffffffff81b10f29)
Location: include/linux/async.h:69
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:dev_cache_fw_image
```
```
In drivers/nvdimm/bus.c (ffffffff81b501f0)
Location: include/linux/async.h:69
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
In init/initramfs.c (ffffffff83683a75)
Location: include/linux/async.h:69
Inline: True
Inline callers:
  - init/initramfs.c:populate_rootfs
```
```
In drivers/regulator/core.c (ffffffff81a892f8)
Location: include/linux/async.h:69
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_bulk_enable
```
```
In drivers/base/firmware_loader/main.c (ffffffff81b5f1b9)
Location: include/linux/async.h:69
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:dev_cache_fw_image
```
```
In drivers/nvdimm/bus.c (ffffffff81ba3670)
Location: include/linux/async.h:69
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
In init/initramfs.c (ffffffff838b2b85)
Location: include/linux/async.h:69
Inline: True
Inline callers:
  - init/initramfs.c:populate_rootfs
```
```
In drivers/regulator/core.c (ffffffff81adb9d8)
Location: include/linux/async.h:69
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_bulk_enable
```
```
In drivers/base/firmware_loader/main.c (ffffffff81bb2b69)
Location: include/linux/async.h:69
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:dev_cache_fw_image
```
```
In drivers/nvdimm/bus.c (ffffffff81bf7860)
Location: include/linux/async.h:69
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
In drivers/regulator/core.c (ffff800010846d88)
Location: include/linux/async.h:69
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_bulk_enable
```
```
In drivers/base/firmware_loader/main.c (ffff80001090c930)
Location: include/linux/async.h:69
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:dev_cache_fw_image
```
```
In drivers/nvdimm/bus.c (ffff800010951194)
Location: include/linux/async.h:69
Inline: True
```
```
In drivers/scsi/scsi_pm.c (ffff800010983800)
Location: include/linux/async.h:69
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
In drivers/regulator/core.c (c0950514)
Location: include/linux/async.h:69
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_bulk_enable
```
```
In drivers/base/firmware_loader/main.c (c09f54bc)
Location: include/linux/async.h:69
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:dev_cache_fw_image
```
```
In drivers/scsi/scsi_pm.c (c0a560b0)
Location: include/linux/async.h:69
Inline: True
```
```
In sound/soc/soc-dapm.c (c0caa0f4)
Location: include/linux/async.h:69
Inline: True
Inline callers:
  - sound/soc/soc-dapm.c:dapm_power_widgets
  - sound/soc/soc-dapm.c:dapm_power_widgets
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (c0000000008e2ee0)
Location: include/linux/async.h:69
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_bulk_enable
```
```
In drivers/base/firmware_loader/main.c (c0000000009abd90)
Location: include/linux/async.h:69
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:dev_cache_fw_image
```
```
In drivers/nvdimm/bus.c (c0000000009fe1ac)
Location: include/linux/async.h:69
Inline: True
```
```
In drivers/scsi/scsi_pm.c (c000000000a40378)
Location: include/linux/async.h:69
Inline: True
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
In drivers/regulator/core.c (ffffffe00052721a)
Location: include/linux/async.h:69
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_bulk_enable
```
```
In drivers/nvdimm/bus.c (ffffffe0005c1100)
Location: include/linux/async.h:69
Inline: True
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
In drivers/regulator/core.c (ffffffff81642a79)
Location: include/linux/async.h:69
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_bulk_enable
```
```
In drivers/base/firmware_loader/main.c (ffffffff816df789)
Location: include/linux/async.h:69
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:dev_cache_fw_image
```
```
In drivers/nvdimm/bus.c (ffffffff817055d4)
Location: include/linux/async.h:69
Inline: True
```
```
In drivers/scsi/scsi_pm.c (ffffffff81731d1e)
Location: include/linux/async.h:69
Inline: True
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
In drivers/regulator/core.c (ffffffff81623079)
Location: include/linux/async.h:69
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_bulk_enable
```
```
In drivers/base/firmware_loader/main.c (ffffffff816b9dc9)
Location: include/linux/async.h:69
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:dev_cache_fw_image
```
```
In drivers/nvdimm/bus.c (ffffffff816d9054)
Location: include/linux/async.h:69
Inline: True
```
```
In drivers/scsi/scsi_pm.c (ffffffff8170b13e)
Location: include/linux/async.h:69
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
In drivers/regulator/core.c (ffffffff81670fd9)
Location: include/linux/async.h:69
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_bulk_enable
```
```
In drivers/base/firmware_loader/main.c (ffffffff8170cea9)
Location: include/linux/async.h:69
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:dev_cache_fw_image
```
```
In drivers/nvdimm/bus.c (ffffffff817443a4)
Location: include/linux/async.h:69
Inline: True
```
```
In drivers/scsi/scsi_pm.c (ffffffff81770aee)
Location: include/linux/async.h:69
Inline: True
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
In drivers/regulator/core.c (ffffffff8168b639)
Location: include/linux/async.h:69
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_bulk_enable
```
```
In drivers/base/firmware_loader/main.c (ffffffff81727457)
Location: include/linux/async.h:69
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:dev_cache_fw_image
```
```
In drivers/nvdimm/bus.c (ffffffff8175f7f4)
Location: include/linux/async.h:69
Inline: True
```
```
In drivers/scsi/scsi_pm.c (ffffffff8178c28e)
Location: include/linux/async.h:69
Inline: True
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
</ul>
