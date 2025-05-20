# Function: <code>request_firmware</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int request_firmware(const struct firmware **firmware_p, const char *name, struct device *device);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_class.c (ffffffff8155fe40)
Location: drivers/base/firmware_class.c:1203
Inline: False
```
**Symbols:**

```
ffffffff8155fe40-ffffffff8155fe83: request_firmware (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int request_firmware(const struct firmware **firmware_p, const char *name, struct device *device);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_class.c (ffffffff815b4460)
Location: drivers/base/firmware_class.c:1221
Inline: False
```
**Symbols:**

```
ffffffff815b4460-ffffffff815b44a9: request_firmware (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int request_firmware(const struct firmware **firmware_p, const char *name, struct device *device);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_class.c (ffffffff815e3700)
Location: drivers/base/firmware_class.c:1256
Inline: False
Direct callers:
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
```
**Symbols:**

```
ffffffff815e3700-ffffffff815e3749: request_firmware (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int request_firmware(const struct firmware **firmware_p, const char *name, struct device *device);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_class.c (ffffffff815f83e0)
Location: drivers/base/firmware_class.c:1256
Inline: False
Direct callers:
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
```
**Symbols:**

```
ffffffff815f83e0-ffffffff815f8429: request_firmware (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int request_firmware(const struct firmware **firmware_p, const char *name, struct device *device);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_class.c (ffffffff816603e0)
Location: drivers/base/firmware_class.c:1263
Inline: False
Direct callers:
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
```
**Symbols:**

```
ffffffff816603e0-ffffffff81660429: request_firmware (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int request_firmware(const struct firmware **firmware_p, const char *name, struct device *device);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff8169ad70)
Location: drivers/base/firmware_loader/main.c:620
Inline: False
Direct callers:
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
```
**Symbols:**

```
ffffffff8169ad70-ffffffff8169adb9: request_firmware (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int request_firmware(const struct firmware **firmware_p, const char *name, struct device *device);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff816bb5f0)
Location: drivers/base/firmware_loader/main.c:629
Inline: False
Direct callers:
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
```
**Symbols:**

```
ffffffff816bb5f0-ffffffff816bb639: request_firmware (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int request_firmware(const struct firmware **firmware_p, const char *name, struct device *device);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff816f5ce0)
Location: drivers/base/firmware_loader/main.c:819
Inline: False
Direct callers:
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
```
**Symbols:**

```
ffffffff816f5ce0-ffffffff816f5d2d: request_firmware (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int request_firmware(const struct firmware **firmware_p, const char *name, struct device *device);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff8171a0e0)
Location: drivers/base/firmware_loader/main.c:819
Inline: False
Direct callers:
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
  - drivers/remoteproc/remoteproc_core.c:rproc_boot
  - drivers/remoteproc/remoteproc_core.c:rproc_trigger_recovery
```
**Symbols:**

```
ffffffff8171a0e0-ffffffff8171a12d: request_firmware (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int request_firmware(const struct firmware **firmware_p, const char *name, struct device *device);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff817d6268)
Location: drivers/base/firmware_loader/main.c:826
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:cache_firmware
Direct callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_fw_update
  - drivers/remoteproc/remoteproc_core.c:rproc_boot
  - drivers/remoteproc/remoteproc_core.c:rproc_trigger_recovery
```
**Symbols:**

```
ffffffff817d5fe0-ffffffff817d602d: request_firmware (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int request_firmware(const struct firmware **firmware_p, const char *name, struct device *device);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff817ead48)
Location: drivers/base/firmware_loader/main.c:868
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:cache_firmware
Direct callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_fw_update
  - drivers/remoteproc/remoteproc_core.c:rproc_boot
  - drivers/remoteproc/remoteproc_core.c:rproc_trigger_recovery
  - net/core/devlink.c:devlink_compat_flash_update
  - net/core/devlink.c:devlink_nl_cmd_flash_update
```
**Symbols:**

```
ffffffff817eaa20-ffffffff817eaa70: request_firmware (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int request_firmware(const struct firmware **firmware_p, const char *name, struct device *device);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff817cf1b0)
Location: drivers/base/firmware_loader/main.c:872
Inline: True
Direct callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_fw_update
  - drivers/remoteproc/remoteproc_core.c:rproc_boot
  - drivers/remoteproc/remoteproc_core.c:rproc_trigger_recovery
  - net/core/devlink.c:devlink_compat_flash_update
  - net/core/devlink.c:devlink_nl_cmd_flash_update
```
**Symbols:**

```
ffffffff817cf1b0-ffffffff817cf200: request_firmware (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int request_firmware(const struct firmware **firmware_p, const char *name, struct device *device);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff818599c0)
Location: drivers/base/firmware_loader/main.c:871
Inline: True
Direct callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_fw_update
  - drivers/remoteproc/remoteproc_core.c:rproc_boot
  - drivers/remoteproc/remoteproc_core.c:rproc_trigger_recovery
  - net/core/devlink.c:devlink_compat_flash_update
  - net/core/devlink.c:devlink_nl_cmd_flash_update
```
**Symbols:**

```
ffffffff818599c0-ffffffff81859a10: request_firmware (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int request_firmware(const struct firmware **firmware_p, const char *name, struct device *device);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff819a0590)
Location: drivers/base/firmware_loader/main.c:896
Inline: True
Direct callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_fw_update
  - drivers/remoteproc/remoteproc_core.c:rproc_boot
  - drivers/remoteproc/remoteproc_core.c:rproc_trigger_recovery
  - net/core/devlink.c:devlink_compat_flash_update
  - net/core/devlink.c:devlink_nl_cmd_flash_update
```
**Symbols:**

```
ffffffff819a0590-ffffffff819a05ee: request_firmware (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int request_firmware(const struct firmware **firmware_p, const char *name, struct device *device);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff81b12130)
Location: drivers/base/firmware_loader/main.c:896
Inline: True
Direct callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_fw_update
  - drivers/remoteproc/remoteproc_core.c:rproc_boot
  - drivers/remoteproc/remoteproc_core.c:rproc_trigger_recovery
  - net/core/devlink.c:devlink_compat_flash_update
  - net/core/devlink.c:devlink_nl_cmd_flash_update
```
**Symbols:**

```
ffffffff81b12130-ffffffff81b1218e: request_firmware (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int request_firmware(const struct firmware **firmware_p, const char *name, struct device *device);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff81b60420)
Location: drivers/base/firmware_loader/main.c:951
Inline: True
Direct callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_fw_update
  - drivers/remoteproc/remoteproc_core.c:rproc_boot
  - drivers/remoteproc/remoteproc_core.c:rproc_trigger_recovery
  - net/devlink/dev.c:devlink_compat_flash_update
  - net/devlink/dev.c:devlink_nl_cmd_flash_update
```
**Symbols:**

```
ffffffff81b60420-ffffffff81b6047e: request_firmware (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int request_firmware(const struct firmware **firmware_p, const char *name, struct device *device);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff81bb3e60)
Location: drivers/base/firmware_loader/main.c:952
Inline: True
Direct callers:
  - drivers/gpu/drm/drm_edid_load.c:drm_edid_load_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_fw_update
  - drivers/remoteproc/remoteproc_core.c:rproc_boot
  - drivers/remoteproc/remoteproc_core.c:rproc_trigger_recovery
  - net/devlink/dev.c:devlink_compat_flash_update
  - net/devlink/dev.c:devlink_nl_flash_update_doit
```
**Symbols:**

```
ffffffff81bb3e60-ffffffff81bb3ebe: request_firmware (STB_GLOBAL)
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
int request_firmware(const struct firmware **firmware_p, const char *name, struct device *device);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffff80001090d890)
Location: drivers/base/firmware_loader/main.c:819
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_boot
  - drivers/remoteproc/remoteproc_core.c:rproc_trigger_recovery
  - drivers/memory/brcmstb_dpfe.c:brcmstb_dpfe_download_firmware
```
**Symbols:**

```
ffff80001090d890-ffff80001090d8f8: request_firmware (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int request_firmware(const struct firmware **firmware_p, const char *name, struct device *device);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (c09f68a4)
Location: drivers/base/firmware_loader/main.c:819
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_boot
  - drivers/remoteproc/remoteproc_core.c:rproc_trigger_recovery
```
**Symbols:**

```
c09f68a4-c09f6908: request_firmware (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int request_firmware(const struct firmware **firmware_p, const char *name, struct device *device);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (c0000000009adeb0)
Location: drivers/base/firmware_loader/main.c:819
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_boot
  - drivers/remoteproc/remoteproc_core.c:rproc_trigger_recovery
```
**Symbols:**

```
c0000000009adeb0-c0000000009adf2c: request_firmware (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int request_firmware(const struct firmware **firmware_p, const char *name, struct device *device);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffe000592332)
Location: drivers/base/firmware_loader/main.c:819
Inline: False
```
**Symbols:**

```
ffffffe000592332-ffffffe00059238a: request_firmware (STB_GLOBAL)
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
int request_firmware(const struct firmware **firmware_p, const char *name, struct device *device);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff816e0410)
Location: drivers/base/firmware_loader/main.c:819
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_boot
  - drivers/remoteproc/remoteproc_core.c:rproc_trigger_recovery
```
**Symbols:**

```
ffffffff816e0410-ffffffff816e045d: request_firmware (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int request_firmware(const struct firmware **firmware_p, const char *name, struct device *device);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff816baa50)
Location: drivers/base/firmware_loader/main.c:819
Inline: False
```
**Symbols:**

```
ffffffff816baa50-ffffffff816baa9d: request_firmware (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int request_firmware(const struct firmware **firmware_p, const char *name, struct device *device);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff8170db20)
Location: drivers/base/firmware_loader/main.c:819
Inline: False
Direct callers:
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
```
**Symbols:**

```
ffffffff8170db20-ffffffff8170db6d: request_firmware (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int request_firmware(const struct firmware **firmware_p, const char *name, struct device *device);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff81728750)
Location: drivers/base/firmware_loader/main.c:819
Inline: False
Direct callers:
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
  - drivers/remoteproc/remoteproc_core.c:rproc_boot
  - drivers/remoteproc/remoteproc_core.c:rproc_trigger_recovery
```
**Symbols:**

```
ffffffff81728750-ffffffff8172879d: request_firmware (STB_GLOBAL)
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
