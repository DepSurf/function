# Function: <code>acpi_dev_present</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool acpi_dev_present(const char *hid, const char *uid, s64 hrv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff814f7610)
Location: drivers/acpi/utils.c:789
Inline: False
```
**Symbols:**

```
ffffffff814f7610-ffffffff814f771e: acpi_dev_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool acpi_dev_present(const char *hid, const char *uid, s64 hrv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff815388b0)
Location: drivers/acpi/utils.c:790
Inline: False
```
**Symbols:**

```
ffffffff815388b0-ffffffff815389be: acpi_dev_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool acpi_dev_present(const char *hid, const char *uid, s64 hrv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff8156e540)
Location: drivers/acpi/utils.c:793
Inline: False
Direct callers:
  - drivers/acpi/ac.c:acpi_ac_init
  - drivers/acpi/ac.c:acpi_ac_init
  - drivers/acpi/battery.c:acpi_battery_init_async
```
**Symbols:**

```
ffffffff8156e540-ffffffff8156e655: acpi_dev_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool acpi_dev_present(const char *hid, const char *uid, s64 hrv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff81586100)
Location: drivers/acpi/utils.c:793
Inline: False
Direct callers:
  - drivers/acpi/ac.c:acpi_ac_init
  - drivers/acpi/ac.c:acpi_ac_init
  - drivers/acpi/battery.c:acpi_battery_init_async
```
**Symbols:**

```
ffffffff81586100-ffffffff81586215: acpi_dev_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool acpi_dev_present(const char *hid, const char *uid, s64 hrv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff815b6eb0)
Location: drivers/acpi/utils.c:777
Inline: False
Direct callers:
  - drivers/acpi/ac.c:acpi_ac_init
  - drivers/acpi/ac.c:acpi_ac_init
  - drivers/acpi/battery.c:acpi_battery_init_async
  - drivers/platform/x86/intel_pmc_core_pltdrv.c:pmc_core_platform_init
```
**Symbols:**

```
ffffffff815b6eb0-ffffffff815b6fc9: acpi_dev_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool acpi_dev_present(const char *hid, const char *uid, s64 hrv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff815d80e0)
Location: drivers/acpi/utils.c:777
Inline: False
Direct callers:
  - drivers/acpi/ac.c:acpi_ac_init
  - drivers/acpi/ac.c:acpi_ac_init
  - drivers/acpi/battery.c:acpi_battery_init_async
  - drivers/platform/x86/intel_pmc_core_pltdrv.c:pmc_core_platform_init
```
**Symbols:**

```
ffffffff815d80e0-ffffffff815d81f9: acpi_dev_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool acpi_dev_present(const char *hid, const char *uid, s64 hrv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff81681ce0)
Location: drivers/acpi/utils.c:834
Inline: False
Direct callers:
  - drivers/acpi/ac.c:acpi_ac_init
  - drivers/acpi/ac.c:acpi_ac_init
  - drivers/acpi/battery.c:acpi_battery_init_async
  - drivers/platform/x86/intel_pmc_core_pltdrv.c:pmc_core_platform_init
```
**Symbols:**

```
ffffffff81681ce0-ffffffff81681df9: acpi_dev_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool acpi_dev_present(const char *hid, const char *uid, s64 hrv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff816a0830)
Location: drivers/acpi/utils.c:830
Inline: False
Direct callers:
  - drivers/acpi/ac.c:acpi_ac_init
  - drivers/acpi/ac.c:acpi_ac_init
  - drivers/acpi/battery.c:acpi_battery_init_async
  - drivers/platform/x86/intel_pmc_core_pltdrv.c:pmc_core_platform_init
```
**Symbols:**

```
ffffffff816a0830-ffffffff816a0949: acpi_dev_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool acpi_dev_present(const char *hid, const char *uid, s64 hrv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff81683170)
Location: drivers/acpi/utils.c:824
Inline: False
Direct callers:
  - drivers/acpi/ac.c:acpi_ac_init
  - drivers/acpi/ac.c:acpi_ac_init
  - drivers/acpi/battery.c:acpi_battery_init_async
  - drivers/platform/x86/intel_pmc_core_pltdrv.c:pmc_core_platform_init
```
**Symbols:**

```
ffffffff81683170-ffffffff81683288: acpi_dev_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool acpi_dev_present(const char *hid, const char *uid, s64 hrv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff816f82c0)
Location: drivers/acpi/utils.c:838
Inline: False
Direct callers:
  - drivers/acpi/ac.c:acpi_ac_init
  - drivers/acpi/ac.c:acpi_ac_init
  - drivers/acpi/battery.c:acpi_battery_init_async
  - drivers/platform/x86/intel/pmc/pltdrv.c:pmc_core_platform_init
```
**Symbols:**

```
ffffffff816f82c0-ffffffff816f83d8: acpi_dev_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool acpi_dev_present(const char *hid, const char *uid, s64 hrv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff81825440)
Location: drivers/acpi/utils.c:838
Inline: False
Direct callers:
  - drivers/acpi/x86/utils.c:acpi_quirk_skip_acpi_ac_and_battery
  - drivers/acpi/x86/utils.c:acpi_quirk_skip_acpi_ac_and_battery
  - drivers/platform/x86/intel/pmc/pltdrv.c:pmc_core_platform_init
```
**Symbols:**

```
ffffffff81825440-ffffffff81825567: acpi_dev_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool acpi_dev_present(const char *hid, const char *uid, s64 hrv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff819567f0)
Location: drivers/acpi/utils.c:900
Inline: False
Direct callers:
  - drivers/acpi/x86/utils.c:acpi_quirk_skip_acpi_ac_and_battery
  - drivers/acpi/x86/utils.c:acpi_quirk_skip_acpi_ac_and_battery
  - drivers/platform/x86/intel/pmc/pltdrv.c:pmc_core_platform_init
```
**Symbols:**

```
ffffffff819567f0-ffffffff819568d2: acpi_dev_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool acpi_dev_present(const char *hid, const char *uid, s64 hrv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff8199cbf0)
Location: drivers/acpi/utils.c:900
Inline: False
Direct callers:
  - drivers/acpi/x86/utils.c:acpi_quirk_skip_acpi_ac_and_battery
  - drivers/acpi/x86/utils.c:acpi_quirk_skip_acpi_ac_and_battery
  - drivers/platform/x86/intel/pmc/pltdrv.c:pmc_core_platform_init
```
**Symbols:**

```
ffffffff8199cbf0-ffffffff8199ccd2: acpi_dev_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool acpi_dev_present(const char *hid, const char *uid, s64 hrv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff819e4c60)
Location: drivers/acpi/utils.c:946
Inline: False
Direct callers:
  - drivers/acpi/x86/utils.c:acpi_quirk_skip_acpi_ac_and_battery
  - drivers/acpi/x86/utils.c:acpi_quirk_skip_acpi_ac_and_battery
  - drivers/gpu/drm/drm_privacy_screen_x86.c:detect_chromeos_privacy_screen
```
**Symbols:**

```
ffffffff819e4c60-ffffffff819e4d42: acpi_dev_present (STB_GLOBAL)
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
bool acpi_dev_present(const char *hid, const char *uid, s64 hrv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffff800010765660)
Location: drivers/acpi/utils.c:777
Inline: False
Direct callers:
  - drivers/acpi/ac.c:acpi_ac_init
  - drivers/acpi/ac.c:acpi_ac_init
  - drivers/acpi/battery.c:acpi_battery_init_async
  - drivers/tty/serial/8250/8250_dw.c:dw8250_probe
```
**Symbols:**

```
ffff800010765660-ffff800010765730: acpi_dev_present (STB_GLOBAL)
```
</details>
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
bool acpi_dev_present(const char *hid, const char *uid, s64 hrv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff815cb410)
Location: drivers/acpi/utils.c:777
Inline: False
Direct callers:
  - drivers/platform/x86/intel_pmc_core_pltdrv.c:pmc_core_platform_init
```
**Symbols:**

```
ffffffff815cb410-ffffffff815cb529: acpi_dev_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool acpi_dev_present(const char *hid, const char *uid, s64 hrv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff815b4460)
Location: drivers/acpi/utils.c:777
Inline: False
Direct callers:
  - drivers/platform/x86/intel_pmc_core_pltdrv.c:pmc_core_platform_init
```
**Symbols:**

```
ffffffff815b4460-ffffffff815b4579: acpi_dev_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool acpi_dev_present(const char *hid, const char *uid, s64 hrv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff815cc3c0)
Location: drivers/acpi/utils.c:777
Inline: False
Direct callers:
  - drivers/acpi/ac.c:acpi_ac_init
  - drivers/acpi/ac.c:acpi_ac_init
  - drivers/acpi/battery.c:acpi_battery_init_async
  - drivers/platform/x86/intel_pmc_core_pltdrv.c:pmc_core_platform_init
```
**Symbols:**

```
ffffffff815cc3c0-ffffffff815cc4d9: acpi_dev_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool acpi_dev_present(const char *hid, const char *uid, s64 hrv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff815e6260)
Location: drivers/acpi/utils.c:777
Inline: False
Direct callers:
  - drivers/acpi/ac.c:acpi_ac_init
  - drivers/acpi/ac.c:acpi_ac_init
  - drivers/acpi/battery.c:acpi_battery_init_async
  - drivers/platform/x86/intel_pmc_core_pltdrv.c:pmc_core_platform_init
```
**Symbols:**

```
ffffffff815e6260-ffffffff815e6379: acpi_dev_present (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
