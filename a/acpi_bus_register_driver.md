# Function: <code>acpi_bus_register_driver</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int acpi_bus_register_driver(struct acpi_driver *driver);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff8147e175)
Location: drivers/acpi/bus.c:705
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_init
  - drivers/acpi/ac.c:acpi_ac_init
  - drivers/acpi/button.c:acpi_button_driver_init
  - drivers/acpi/battery.c:acpi_battery_init_async
  - drivers/acpi/hed.c:acpi_hed_driver_init
  - drivers/xen/xen-acpi-pad.c:xen_acpi_pad_init
  - drivers/char/hpet.c:hpet_init
```
**Symbols:**

```
ffffffff8147e175-ffffffff8147e1b8: acpi_bus_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int acpi_bus_register_driver(struct acpi_driver *driver);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff814cc8ce)
Location: drivers/acpi/bus.c:781
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_init
  - drivers/acpi/ac.c:acpi_ac_init
  - drivers/acpi/button.c:acpi_button_driver_init
  - drivers/acpi/battery.c:acpi_battery_init_async
  - drivers/acpi/hed.c:acpi_hed_driver_init
  - drivers/xen/xen-acpi-pad.c:xen_acpi_pad_init
  - drivers/char/hpet.c:hpet_init
```
**Symbols:**

```
ffffffff814cc8ce-ffffffff814cc911: acpi_bus_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int acpi_bus_register_driver(struct acpi_driver *driver);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff814ee7fc)
Location: drivers/acpi/bus.c:791
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_init
  - drivers/acpi/ac.c:acpi_ac_init
  - drivers/acpi/button.c:acpi_button_driver_init
  - drivers/acpi/battery.c:acpi_battery_init_async
  - drivers/acpi/hed.c:acpi_hed_driver_init
  - drivers/xen/xen-acpi-pad.c:xen_acpi_pad_init
  - drivers/char/hpet.c:hpet_init
```
**Symbols:**

```
ffffffff814ee7fc-ffffffff814ee83f: acpi_bus_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int acpi_bus_register_driver(struct acpi_driver *driver);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff814fb860)
Location: drivers/acpi/bus.c:819
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_init
  - drivers/acpi/button.c:acpi_button_driver_init
  - drivers/acpi/hed.c:acpi_hed_driver_init
  - drivers/xen/xen-acpi-pad.c:xen_acpi_pad_init
  - drivers/char/hpet.c:hpet_init
```
**Symbols:**

```
ffffffff814fb860-ffffffff814fb8a4: acpi_bus_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int acpi_bus_register_driver(struct acpi_driver *driver);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff8153d4f0)
Location: drivers/acpi/bus.c:846
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_init
  - drivers/acpi/button.c:acpi_button_driver_init
  - drivers/acpi/hed.c:acpi_hed_driver_init
  - drivers/xen/xen-acpi-pad.c:xen_acpi_pad_init
  - drivers/char/hpet.c:hpet_init
```
**Symbols:**

```
ffffffff8153d4f0-ffffffff8153d534: acpi_bus_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int acpi_bus_register_driver(struct acpi_driver *driver);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff815732f0)
Location: drivers/acpi/bus.c:878
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_init
  - drivers/acpi/ac.c:acpi_ac_init
  - drivers/acpi/button.c:acpi_button_driver_init
  - drivers/acpi/thermal.c:acpi_thermal_init
  - drivers/acpi/battery.c:acpi_battery_init_async
  - drivers/acpi/hed.c:acpi_hed_driver_init
  - drivers/xen/xen-acpi-pad.c:xen_acpi_pad_init
  - drivers/char/hpet.c:hpet_init
  - drivers/char/tpm/tpm_crb.c:crb_acpi_driver_init
```
**Symbols:**

```
ffffffff815732f0-ffffffff81573331: acpi_bus_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int acpi_bus_register_driver(struct acpi_driver *driver);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff8158aef0)
Location: drivers/acpi/bus.c:847
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_init
  - drivers/acpi/ac.c:acpi_ac_init
  - drivers/acpi/button.c:acpi_button_driver_init
  - drivers/acpi/thermal.c:acpi_thermal_init
  - drivers/acpi/battery.c:acpi_battery_init_async
  - drivers/acpi/hed.c:acpi_hed_driver_init
  - drivers/xen/xen-acpi-pad.c:xen_acpi_pad_init
  - drivers/char/hpet.c:hpet_init
  - drivers/char/tpm/tpm_crb.c:crb_acpi_driver_init
```
**Symbols:**

```
ffffffff8158aef0-ffffffff8158af31: acpi_bus_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int acpi_bus_register_driver(struct acpi_driver *driver);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff815bbd50)
Location: drivers/acpi/bus.c:848
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_init
  - drivers/acpi/ac.c:acpi_ac_init
  - drivers/acpi/button.c:acpi_button_driver_init
  - drivers/acpi/thermal.c:acpi_thermal_init
  - drivers/acpi/battery.c:acpi_battery_init_async
  - drivers/acpi/hed.c:acpi_hed_driver_init
  - drivers/xen/xen-acpi-pad.c:xen_acpi_pad_init
  - drivers/char/hpet.c:hpet_init
  - drivers/char/tpm/tpm_crb.c:crb_acpi_driver_init
```
**Symbols:**

```
ffffffff815bbd50-ffffffff815bbd91: acpi_bus_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int acpi_bus_register_driver(struct acpi_driver *driver);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff815dd010)
Location: drivers/acpi/bus.c:848
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_init
  - drivers/acpi/ac.c:acpi_ac_init
  - drivers/acpi/button.c:acpi_button_driver_init
  - drivers/acpi/thermal.c:acpi_thermal_init
  - drivers/acpi/battery.c:acpi_battery_init_async
  - drivers/acpi/hed.c:acpi_hed_driver_init
  - drivers/xen/xen-acpi-pad.c:xen_acpi_pad_init
  - drivers/char/hpet.c:hpet_init
  - drivers/char/tpm/tpm_crb.c:crb_acpi_driver_init
```
**Symbols:**

```
ffffffff815dd010-ffffffff815dd051: acpi_bus_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int acpi_bus_register_driver(struct acpi_driver *driver);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff81687730)
Location: drivers/acpi/bus.c:848
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_init
  - drivers/acpi/ac.c:acpi_ac_init
  - drivers/acpi/button.c:acpi_button_driver_init
  - drivers/acpi/thermal.c:acpi_thermal_init
  - drivers/acpi/battery.c:acpi_battery_init_async
  - drivers/acpi/hed.c:acpi_hed_driver_init
  - drivers/xen/xen-acpi-pad.c:xen_acpi_pad_init
  - drivers/char/hpet.c:hpet_init
  - drivers/char/tpm/tpm_crb.c:crb_acpi_driver_init
```
**Symbols:**

```
ffffffff81687730-ffffffff81687771: acpi_bus_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int acpi_bus_register_driver(struct acpi_driver *driver);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff816a54a0)
Location: drivers/acpi/bus.c:853
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_init
  - drivers/acpi/ac.c:acpi_ac_init
  - drivers/acpi/button.c:acpi_button_driver_init
  - drivers/acpi/thermal.c:acpi_thermal_init
  - drivers/acpi/battery.c:acpi_battery_init_async
  - drivers/acpi/hed.c:acpi_hed_driver_init
  - drivers/xen/xen-acpi-pad.c:xen_acpi_pad_init
  - drivers/char/hpet.c:hpet_init
  - drivers/char/tpm/tpm_crb.c:crb_acpi_driver_init
```
**Symbols:**

```
ffffffff816a54a0-ffffffff816a54e1: acpi_bus_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int acpi_bus_register_driver(struct acpi_driver *driver);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff81688210)
Location: drivers/acpi/bus.c:932
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_init
  - drivers/acpi/ac.c:acpi_ac_init
  - drivers/acpi/button.c:acpi_button_driver_init
  - drivers/acpi/thermal.c:acpi_thermal_init
  - drivers/acpi/battery.c:acpi_battery_init_async
  - drivers/acpi/hed.c:acpi_hed_driver_init
  - drivers/xen/xen-acpi-pad.c:xen_acpi_pad_init
  - drivers/char/hpet.c:hpet_init
  - drivers/char/tpm/tpm_crb.c:crb_acpi_driver_init
```
**Symbols:**

```
ffffffff81688210-ffffffff81688251: acpi_bus_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int acpi_bus_register_driver(struct acpi_driver *driver);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff816fd660)
Location: drivers/acpi/bus.c:934
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_init
  - drivers/acpi/ac.c:acpi_ac_init
  - drivers/acpi/button.c:acpi_button_driver_init
  - drivers/acpi/thermal.c:acpi_thermal_init
  - drivers/acpi/battery.c:acpi_battery_init_async
  - drivers/acpi/hed.c:acpi_hed_driver_init
  - drivers/xen/xen-acpi-pad.c:xen_acpi_pad_init
  - drivers/char/hpet.c:hpet_init
  - drivers/char/tpm/tpm_crb.c:crb_acpi_driver_init
```
**Symbols:**

```
ffffffff816fd660-ffffffff816fd6a1: acpi_bus_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int acpi_bus_register_driver(struct acpi_driver *driver);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff8182aec0)
Location: drivers/acpi/bus.c:971
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_init
  - drivers/acpi/ac.c:acpi_ac_init
  - drivers/acpi/button.c:acpi_button_driver_init
  - drivers/acpi/thermal.c:acpi_thermal_init
  - drivers/acpi/battery.c:acpi_battery_init_async
  - drivers/acpi/hed.c:acpi_hed_driver_init
  - drivers/xen/xen-acpi-pad.c:xen_acpi_pad_init
  - drivers/char/hpet.c:hpet_init
  - drivers/char/tpm/tpm_crb.c:crb_acpi_driver_init
```
**Symbols:**

```
ffffffff8182aec0-ffffffff8182af0d: acpi_bus_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int acpi_bus_register_driver(struct acpi_driver *driver);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff8195d4b0)
Location: drivers/acpi/bus.c:977
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_init
  - drivers/acpi/ac.c:acpi_ac_init
  - drivers/acpi/button.c:acpi_button_driver_init
  - drivers/acpi/thermal.c:acpi_thermal_init
  - drivers/acpi/battery.c:acpi_battery_init_async
  - drivers/acpi/hed.c:acpi_hed_driver_init
  - drivers/xen/xen-acpi-pad.c:xen_acpi_pad_init
  - drivers/char/hpet.c:hpet_init
  - drivers/char/tpm/tpm_crb.c:crb_acpi_driver_init
```
**Symbols:**

```
ffffffff8195d4b0-ffffffff8195d4fd: acpi_bus_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int acpi_bus_register_driver(struct acpi_driver *driver);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff819a3940)
Location: drivers/acpi/bus.c:950
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_init
  - drivers/acpi/ac.c:acpi_ac_init
  - drivers/acpi/button.c:acpi_button_driver_init
  - drivers/acpi/thermal.c:acpi_thermal_init
  - drivers/acpi/battery.c:acpi_battery_init_async
  - drivers/acpi/hed.c:acpi_hed_driver_init
  - drivers/xen/xen-acpi-pad.c:xen_acpi_pad_init
  - drivers/char/hpet.c:hpet_init
  - drivers/char/tpm/tpm_crb.c:crb_acpi_driver_init
```
**Symbols:**

```
ffffffff819a3940-ffffffff819a398d: acpi_bus_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int acpi_bus_register_driver(struct acpi_driver *driver);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff819ec070)
Location: drivers/acpi/bus.c:1000
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_init
  - drivers/acpi/button.c:acpi_button_driver_init
  - drivers/acpi/thermal.c:acpi_thermal_init
  - drivers/acpi/battery.c:acpi_battery_init_async
  - drivers/acpi/hed.c:acpi_hed_driver_init
  - drivers/xen/xen-acpi-pad.c:xen_acpi_pad_init
  - drivers/char/hpet.c:hpet_init
  - drivers/char/tpm/tpm_crb.c:crb_acpi_driver_init
```
**Symbols:**

```
ffffffff819ec070-ffffffff819ec0bd: acpi_bus_register_driver (STB_GLOBAL)
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
int acpi_bus_register_driver(struct acpi_driver *driver);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffff8000107693b0)
Location: drivers/acpi/bus.c:848
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_init
  - drivers/acpi/ac.c:acpi_ac_init
  - drivers/acpi/button.c:acpi_button_driver_init
  - drivers/acpi/thermal.c:acpi_thermal_init
  - drivers/acpi/battery.c:acpi_battery_init_async
  - drivers/acpi/hed.c:acpi_hed_driver_init
  - drivers/char/tpm/tpm_crb.c:crb_acpi_driver_init
```
**Symbols:**

```
ffff8000107693b0-ffff800010769404: acpi_bus_register_driver (STB_GLOBAL)
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
int acpi_bus_register_driver(struct acpi_driver *driver);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff815cf660)
Location: drivers/acpi/bus.c:848
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_init
  - drivers/acpi/button.c:acpi_button_driver_init
  - drivers/xen/xen-acpi-pad.c:xen_acpi_pad_init
  - drivers/char/hpet.c:hpet_init
  - drivers/char/tpm/tpm_crb.c:crb_acpi_driver_init
```
**Symbols:**

```
ffffffff815cf660-ffffffff815cf6a1: acpi_bus_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int acpi_bus_register_driver(struct acpi_driver *driver);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff815b9220)
Location: drivers/acpi/bus.c:848
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_init
  - drivers/acpi/button.c:acpi_button_driver_init
  - drivers/acpi/nfit/core.c:nfit_init
  - drivers/acpi/hed.c:acpi_hed_driver_init
  - drivers/char/hpet.c:hpet_init
  - drivers/char/tpm/tpm_crb.c:crb_acpi_driver_init
  - drivers/hv/vmbus_drv.c:hv_acpi_init
```
**Symbols:**

```
ffffffff815b9220-ffffffff815b9261: acpi_bus_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int acpi_bus_register_driver(struct acpi_driver *driver);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff815d12f0)
Location: drivers/acpi/bus.c:848
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_init
  - drivers/acpi/ac.c:acpi_ac_init
  - drivers/acpi/button.c:acpi_button_driver_init
  - drivers/acpi/thermal.c:acpi_thermal_init
  - drivers/acpi/battery.c:acpi_battery_init_async
  - drivers/acpi/hed.c:acpi_hed_driver_init
  - drivers/xen/xen-acpi-pad.c:xen_acpi_pad_init
  - drivers/char/hpet.c:hpet_init
  - drivers/char/tpm/tpm_crb.c:crb_acpi_driver_init
```
**Symbols:**

```
ffffffff815d12f0-ffffffff815d1331: acpi_bus_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int acpi_bus_register_driver(struct acpi_driver *driver);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff815eb1b0)
Location: drivers/acpi/bus.c:848
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_init
  - drivers/acpi/ac.c:acpi_ac_init
  - drivers/acpi/button.c:acpi_button_driver_init
  - drivers/acpi/thermal.c:acpi_thermal_init
  - drivers/acpi/battery.c:acpi_battery_init_async
  - drivers/acpi/hed.c:acpi_hed_driver_init
  - drivers/xen/xen-acpi-pad.c:xen_acpi_pad_init
  - drivers/char/hpet.c:hpet_init
  - drivers/char/tpm/tpm_crb.c:crb_acpi_driver_init
```
**Symbols:**

```
ffffffff815eb1b0-ffffffff815eb1f1: acpi_bus_register_driver (STB_GLOBAL)
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
