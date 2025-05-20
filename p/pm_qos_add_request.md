# Function: <code>pm_qos_add_request</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void pm_qos_add_request(struct pm_qos_request *req, int pm_qos_class, s32 value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff810cc450)
Location: kernel/power/qos.c:446
Inline: True
Direct callers:
  - kernel/power/qos.c:pm_qos_power_open
```
**Symbols:**

```
ffffffff810cc450-ffffffff810cc54c: pm_qos_add_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void pm_qos_add_request(struct pm_qos_request *req, int pm_qos_class, s32 value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff810d0f60)
Location: kernel/power/qos.c:446
Inline: True
Direct callers:
  - kernel/power/qos.c:pm_qos_power_open
```
**Symbols:**

```
ffffffff810d0f60-ffffffff810d1055: pm_qos_add_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void pm_qos_add_request(struct pm_qos_request *req, int pm_qos_class, s32 value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff810d79d0)
Location: kernel/power/qos.c:446
Inline: True
Direct callers:
  - kernel/power/qos.c:pm_qos_power_open
```
**Symbols:**

```
ffffffff810d79d0-ffffffff810d7ac5: pm_qos_add_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void pm_qos_add_request(struct pm_qos_request *req, int pm_qos_class, s32 value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff810d6a20)
Location: kernel/power/qos.c:446
Inline: True
Direct callers:
  - kernel/power/qos.c:pm_qos_power_open
  - drivers/i2c/busses/i2c-designware-baytrail.c:i2c_dw_probe_lock_support
```
**Symbols:**

```
ffffffff810d6a20-ffffffff810d6b0b: pm_qos_add_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void pm_qos_add_request(struct pm_qos_request *req, int pm_qos_class, s32 value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff810de9b0)
Location: kernel/power/qos.c:446
Inline: True
Direct callers:
  - kernel/power/qos.c:pm_qos_power_open
  - drivers/i2c/busses/i2c-designware-baytrail.c:i2c_dw_probe_lock_support
```
**Symbols:**

```
ffffffff810de9b0-ffffffff810dea99: pm_qos_add_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void pm_qos_add_request(struct pm_qos_request *req, int pm_qos_class, s32 value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff810e6ff0)
Location: kernel/power/qos.c:447
Inline: True
Direct callers:
  - kernel/power/qos.c:pm_qos_power_open
  - drivers/i2c/busses/i2c-designware-baytrail.c:i2c_dw_probe_lock_support
```
**Symbols:**

```
ffffffff810e6ff0-ffffffff810e70dc: pm_qos_add_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void pm_qos_add_request(struct pm_qos_request *req, int pm_qos_class, s32 value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff810f25f0)
Location: kernel/power/qos.c:436
Inline: True
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init
  - kernel/power/qos.c:pm_qos_power_open
```
**Symbols:**

```
ffffffff810f25f0-ffffffff810f26dc: pm_qos_add_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void pm_qos_add_request(struct pm_qos_request *req, int pm_qos_class, s32 value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff810faac0)
Location: kernel/power/qos.c:437
Inline: True
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init
  - kernel/power/qos.c:pm_qos_power_open
```
**Symbols:**

```
ffffffff810faac0-ffffffff810fabaa: pm_qos_add_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void pm_qos_add_request(struct pm_qos_request *req, int pm_qos_class, s32 value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff81106960)
Location: kernel/power/qos.c:389
Inline: True
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init
  - kernel/power/qos.c:pm_qos_power_open
```
**Symbols:**

```
ffffffff81106960-ffffffff81106a4a: pm_qos_add_request (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
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
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void pm_qos_add_request(struct pm_qos_request *req, int pm_qos_class, s32 value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffff80001016d470)
Location: kernel/power/qos.c:389
Inline: True
Direct callers:
  - kernel/power/qos.c:pm_qos_power_open
```
**Symbols:**

```
ffff80001016d470-ffff80001016d59c: pm_qos_add_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void pm_qos_add_request(struct pm_qos_request *req, int pm_qos_class, s32 value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (c03b84c4)
Location: kernel/power/qos.c:389
Inline: True
Direct callers:
  - kernel/power/qos.c:pm_qos_power_open
  - drivers/tty/serial/omap-serial.c:serial_omap_probe
  - drivers/mmc/host/sdhci-esdhc-imx.c:sdhci_esdhc_runtime_resume
  - drivers/mmc/host/sdhci-esdhc-imx.c:sdhci_esdhc_imx_probe
  - sound/core/pcm_native.c:snd_pcm_hw_params
```
**Symbols:**

```
c03b84c4-c03b8600: pm_qos_add_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void pm_qos_add_request(struct pm_qos_request *req, int pm_qos_class, s32 value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (c0000000001c4b70)
Location: kernel/power/qos.c:389
Inline: True
Direct callers:
  - kernel/power/qos.c:pm_qos_power_open
```
**Symbols:**

```
c0000000001c4b70-c0000000001c4d28: pm_qos_add_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void pm_qos_add_request(struct pm_qos_request *req, int pm_qos_class, s32 value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffe00010cce6)
Location: kernel/power/qos.c:389
Inline: True
Direct callers:
  - kernel/power/qos.c:pm_qos_power_open
```
**Symbols:**

```
ffffffe00010cce6-ffffffe00010cdf0: pm_qos_add_request (STB_GLOBAL)
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
void pm_qos_add_request(struct pm_qos_request *req, int pm_qos_class, s32 value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff810ffc70)
Location: kernel/power/qos.c:389
Inline: True
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init
  - kernel/power/qos.c:pm_qos_power_open
```
**Symbols:**

```
ffffffff810ffc70-ffffffff810ffd5a: pm_qos_add_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void pm_qos_add_request(struct pm_qos_request *req, int pm_qos_class, s32 value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff810efe60)
Location: kernel/power/qos.c:389
Inline: True
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init
  - kernel/power/qos.c:pm_qos_power_open
```
**Symbols:**

```
ffffffff810efe60-ffffffff810eff4a: pm_qos_add_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void pm_qos_add_request(struct pm_qos_request *req, int pm_qos_class, s32 value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff810fce30)
Location: kernel/power/qos.c:389
Inline: True
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init
  - kernel/power/qos.c:pm_qos_power_open
```
**Symbols:**

```
ffffffff810fce30-ffffffff810fcf1a: pm_qos_add_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void pm_qos_add_request(struct pm_qos_request *req, int pm_qos_class, s32 value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff81108070)
Location: kernel/power/qos.c:389
Inline: True
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init
  - kernel/power/qos.c:pm_qos_power_open
```
**Symbols:**

```
ffffffff81108070-ffffffff8110816f: pm_qos_add_request (STB_GLOBAL)
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
