# Function: <code>thermal_cooling_device_register</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct thermal_cooling_device *thermal_cooling_device_register(char *type, void *devdata, const struct thermal_cooling_device_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81687840)
Location: drivers/thermal/thermal_core.c:1526
Inline: False
Direct callers:
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/processor_driver.c:__acpi_processor_start
  - drivers/power/power_supply_core.c:__power_supply_register
```
**Symbols:**

```
ffffffff81687840-ffffffff8168785b: thermal_cooling_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct thermal_cooling_device *thermal_cooling_device_register(char *type, void *devdata, const struct thermal_cooling_device_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff816e82e0)
Location: drivers/thermal/thermal_core.c:1532
Inline: False
Direct callers:
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/processor_driver.c:__acpi_processor_start
  - drivers/power/power_supply_core.c:__power_supply_register
```
**Symbols:**

```
ffffffff816e82e0-ffffffff816e82fb: thermal_cooling_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct thermal_cooling_device *thermal_cooling_device_register(char *type, void *devdata, const struct thermal_cooling_device_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81716c50)
Location: drivers/thermal/thermal_core.c:983
Inline: False
Direct callers:
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/processor_driver.c:__acpi_processor_start
  - drivers/power/supply/power_supply_core.c:__power_supply_register
```
**Symbols:**

```
ffffffff81716c50-ffffffff81716c6b: thermal_cooling_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct thermal_cooling_device *thermal_cooling_device_register(char *type, void *devdata, const struct thermal_cooling_device_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff8172ef90)
Location: drivers/thermal/thermal_core.c:1021
Inline: False
Direct callers:
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/processor_driver.c:__acpi_processor_start
  - drivers/power/supply/power_supply_core.c:__power_supply_register
```
**Symbols:**

```
ffffffff8172ef90-ffffffff8172efab: thermal_cooling_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct thermal_cooling_device *thermal_cooling_device_register(char *type, void *devdata, const struct thermal_cooling_device_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff817a05e0)
Location: drivers/thermal/thermal_core.c:1017
Inline: False
Direct callers:
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/processor_driver.c:__acpi_processor_start
  - drivers/power/supply/power_supply_core.c:__power_supply_register
```
**Symbols:**

```
ffffffff817a05e0-ffffffff817a05fb: thermal_cooling_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct thermal_cooling_device *thermal_cooling_device_register(char *type, void *devdata, const struct thermal_cooling_device_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff817e7bc0)
Location: drivers/thermal/thermal_core.c:1014
Inline: False
Direct callers:
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/processor_driver.c:__acpi_processor_start
```
**Symbols:**

```
ffffffff817e7bc0-ffffffff817e7bdb: thermal_cooling_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct thermal_cooling_device *thermal_cooling_device_register(char *type, void *devdata, const struct thermal_cooling_device_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81813460)
Location: drivers/thermal/thermal_core.c:1018
Inline: False
Direct callers:
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/processor_driver.c:__acpi_processor_start
```
**Symbols:**

```
ffffffff81813460-ffffffff8181347b: thermal_cooling_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct thermal_cooling_device *thermal_cooling_device_register(const char *type, void *devdata, const struct thermal_cooling_device_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81855580)
Location: drivers/thermal/thermal_core.c:1024
Inline: False
Direct callers:
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/processor_driver.c:__acpi_processor_start
```
**Symbols:**

```
ffffffff81855580-ffffffff8185559b: thermal_cooling_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct thermal_cooling_device *thermal_cooling_device_register(const char *type, void *devdata, const struct thermal_cooling_device_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81886fe0)
Location: drivers/thermal/thermal_core.c:1024
Inline: False
Direct callers:
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/processor_driver.c:__acpi_processor_start
```
**Symbols:**

```
ffffffff81886fe0-ffffffff81886ffb: thermal_cooling_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct thermal_cooling_device *thermal_cooling_device_register(const char *type, void *devdata, const struct thermal_cooling_device_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff819567d0)
Location: drivers/thermal/thermal_core.c:1012
Inline: False
Direct callers:
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/processor_driver.c:acpi_pss_perf_init
  - drivers/power/supply/power_supply_core.c:__power_supply_register
```
**Symbols:**

```
ffffffff819567d0-ffffffff819567eb: thermal_cooling_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct thermal_cooling_device *thermal_cooling_device_register(const char *type, void *devdata, const struct thermal_cooling_device_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff8195a910)
Location: drivers/thermal/thermal_core.c:1080
Inline: False
Direct callers:
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/processor_driver.c:acpi_pss_perf_init
  - drivers/power/supply/power_supply_core.c:__power_supply_register
```
**Symbols:**

```
ffffffff8195a910-ffffffff8195a92b: thermal_cooling_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct thermal_cooling_device *thermal_cooling_device_register(const char *type, void *devdata, const struct thermal_cooling_device_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff8193f750)
Location: drivers/thermal/thermal_core.c:1020
Inline: False
Direct callers:
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/processor_driver.c:__acpi_processor_start
  - drivers/power/supply/power_supply_core.c:__power_supply_register
```
**Symbols:**

```
ffffffff8193f750-ffffffff8193f78e: thermal_cooling_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct thermal_cooling_device *thermal_cooling_device_register(const char *type, void *devdata, const struct thermal_cooling_device_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff819e4040)
Location: drivers/thermal/thermal_core.c:972
Inline: False
Direct callers:
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/processor_driver.c:__acpi_processor_start
  - drivers/power/supply/power_supply_core.c:__power_supply_register
```
**Symbols:**

```
ffffffff819e4040-ffffffff819e407e: thermal_cooling_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct thermal_cooling_device *thermal_cooling_device_register(const char *type, void *devdata, const struct thermal_cooling_device_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81b491e0)
Location: drivers/thermal/thermal_core.c:975
Inline: False
Direct callers:
  - drivers/acpi/fan_core.c:acpi_fan_probe
  - drivers/acpi/processor_driver.c:__acpi_processor_start
  - drivers/power/supply/power_supply_core.c:__power_supply_register
```
**Symbols:**

```
ffffffff81b491e0-ffffffff81b4924e: thermal_cooling_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct thermal_cooling_device *thermal_cooling_device_register(const char *type, void *devdata, const struct thermal_cooling_device_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81ce0820)
Location: drivers/thermal/thermal_core.c:975
Inline: False
Direct callers:
  - drivers/acpi/fan_core.c:acpi_fan_probe
  - drivers/acpi/processor_thermal.c:acpi_processor_thermal_init
```
**Symbols:**

```
ffffffff81ce0820-ffffffff81ce088e: thermal_cooling_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct thermal_cooling_device *thermal_cooling_device_register(const char *type, void *devdata, const struct thermal_cooling_device_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81d48930)
Location: drivers/thermal/thermal_core.c:926
Inline: False
Direct callers:
  - drivers/acpi/fan_core.c:acpi_fan_probe
  - drivers/acpi/processor_thermal.c:acpi_processor_thermal_init
```
**Symbols:**

```
ffffffff81d48930-ffffffff81d489a2: thermal_cooling_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct thermal_cooling_device *thermal_cooling_device_register(const char *type, void *devdata, const struct thermal_cooling_device_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81dfebc0)
Location: drivers/thermal/thermal_core.c:995
Inline: False
Direct callers:
  - drivers/acpi/fan_core.c:acpi_fan_probe
  - drivers/acpi/processor_thermal.c:acpi_processor_thermal_init
```
**Symbols:**

```
ffffffff81dfebc0-ffffffff81dfec32: thermal_cooling_device_register (STB_GLOBAL)
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
struct thermal_cooling_device *thermal_cooling_device_register(const char *type, void *devdata, const struct thermal_cooling_device_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffff800010ad5278)
Location: drivers/thermal/thermal_core.c:1024
Inline: False
Direct callers:
  - drivers/acpi/fan.c:acpi_fan_probe
```
**Symbols:**

```
ffff800010ad5278-ffff800010ad52c0: thermal_cooling_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct thermal_cooling_device *thermal_cooling_device_register(const char *type, void *devdata, const struct thermal_cooling_device_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (c0bb503c)
Location: drivers/thermal/thermal_core.c:1024
Inline: False
```
**Symbols:**

```
c0bb503c-c0bb506c: thermal_cooling_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct thermal_cooling_device *thermal_cooling_device_register(const char *type, void *devdata, const struct thermal_cooling_device_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (c000000000bbb030)
Location: drivers/thermal/thermal_core.c:1024
Inline: False
```
**Symbols:**

```
c000000000bbb030-c000000000bbb05c: thermal_cooling_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct thermal_cooling_device *thermal_cooling_device_register(const char *type, void *devdata, const struct thermal_cooling_device_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffe0006d03e2)
Location: drivers/thermal/thermal_core.c:1024
Inline: False
```
**Symbols:**

```
ffffffe0006d03e2-ffffffe0006d041e: thermal_cooling_device_register (STB_GLOBAL)
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
struct thermal_cooling_device *thermal_cooling_device_register(const char *type, void *devdata, const struct thermal_cooling_device_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff8182ce60)
Location: drivers/thermal/thermal_core.c:1024
Inline: False
Direct callers:
  - drivers/acpi/processor_driver.c:__acpi_processor_start
```
**Symbols:**

```
ffffffff8182ce60-ffffffff8182ce7b: thermal_cooling_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct thermal_cooling_device *thermal_cooling_device_register(const char *type, void *devdata, const struct thermal_cooling_device_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff817f44f0)
Location: drivers/thermal/thermal_core.c:1024
Inline: False
Direct callers:
  - drivers/acpi/processor_driver.c:__acpi_processor_start
```
**Symbols:**

```
ffffffff817f44f0-ffffffff817f450b: thermal_cooling_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct thermal_cooling_device *thermal_cooling_device_register(const char *type, void *devdata, const struct thermal_cooling_device_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff8187c490)
Location: drivers/thermal/thermal_core.c:1024
Inline: False
Direct callers:
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/processor_driver.c:__acpi_processor_start
```
**Symbols:**

```
ffffffff8187c490-ffffffff8187c4ab: thermal_cooling_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct thermal_cooling_device *thermal_cooling_device_register(const char *type, void *devdata, const struct thermal_cooling_device_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81897ec0)
Location: drivers/thermal/thermal_core.c:1024
Inline: False
Direct callers:
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/processor_driver.c:__acpi_processor_start
```
**Symbols:**

```
ffffffff81897ec0-ffffffff81897edb: thermal_cooling_device_register (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>char *type</code> ➡️ <code>const char *type</code>
</li>
</ul>
</details>
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
