# Function: <code>acpi_extract_package</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
acpi_status acpi_extract_package(union acpi_object *package, struct acpi_buffer *format, struct acpi_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff8147a774)
Location: drivers/acpi/utils.c:54
Inline: False
Direct callers:
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
```
**Symbols:**

```
ffffffff8147a774-ffffffff8147aa2b: acpi_extract_package (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
acpi_status acpi_extract_package(union acpi_object *package, struct acpi_buffer *format, struct acpi_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff814c8d42)
Location: drivers/acpi/utils.c:55
Inline: False
Direct callers:
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info
```
**Symbols:**

```
ffffffff814c8d42-ffffffff814c8fdc: acpi_extract_package (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
acpi_status acpi_extract_package(union acpi_object *package, struct acpi_buffer *format, struct acpi_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff814eac86)
Location: drivers/acpi/utils.c:55
Inline: False
Direct callers:
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
```
**Symbols:**

```
ffffffff814eac86-ffffffff814eaf20: acpi_extract_package (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
acpi_status acpi_extract_package(union acpi_object *package, struct acpi_buffer *format, struct acpi_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff814f6b80)
Location: drivers/acpi/utils.c:55
Inline: False
Direct callers:
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
```
**Symbols:**

```
ffffffff814f6b80-ffffffff814f6f10: acpi_extract_package (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
acpi_status acpi_extract_package(union acpi_object *package, struct acpi_buffer *format, struct acpi_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff81537bd0)
Location: drivers/acpi/utils.c:55
Inline: False
Direct callers:
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
```
**Symbols:**

```
ffffffff81537bd0-ffffffff81537fba: acpi_extract_package (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
acpi_status acpi_extract_package(union acpi_object *package, struct acpi_buffer *format, struct acpi_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/utils.c (0)
Location: drivers/acpi/utils.c:55
Inline: False
Direct callers:
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_perflib.c:acpi_processor_get_psd
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
```
**Symbols:**

```
ffffffff8156eb00-ffffffff8156eb76: acpi_extract_package.cold.4 (STB_LOCAL)
ffffffff8156d8c0-ffffffff8156dc40: acpi_extract_package (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
acpi_status acpi_extract_package(union acpi_object *package, struct acpi_buffer *format, struct acpi_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/utils.c (0)
Location: drivers/acpi/utils.c:55
Inline: False
Direct callers:
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_perflib.c:acpi_processor_get_psd
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
```
**Symbols:**

```
ffffffff815866c0-ffffffff8158673b: acpi_extract_package.cold.4 (STB_LOCAL)
ffffffff81585480-ffffffff815857ff: acpi_extract_package (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
acpi_status acpi_extract_package(union acpi_object *package, struct acpi_buffer *format, struct acpi_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/utils.c (0)
Location: drivers/acpi/utils.c:42
Inline: False
Direct callers:
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_perflib.c:acpi_processor_get_psd
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
```
**Symbols:**

```
ffffffff815b7328-ffffffff815b73d8: acpi_extract_package.cold (STB_LOCAL)
ffffffff815b6110-ffffffff815b6452: acpi_extract_package (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
acpi_status acpi_extract_package(union acpi_object *package, struct acpi_buffer *format, struct acpi_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/utils.c (0)
Location: drivers/acpi/utils.c:42
Inline: False
Direct callers:
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_perflib.c:acpi_processor_get_psd
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
```
**Symbols:**

```
ffffffff815d8558-ffffffff815d8608: acpi_extract_package.cold (STB_LOCAL)
ffffffff815d7340-ffffffff815d7682: acpi_extract_package (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
acpi_status acpi_extract_package(union acpi_object *package, struct acpi_buffer *format, struct acpi_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/utils.c (0)
Location: drivers/acpi/utils.c:42
Inline: False
Direct callers:
  - drivers/acpi/fan.c:acpi_fan_get_fps
  - drivers/acpi/fan.c:acpi_fan_get_fif
  - drivers/acpi/processor_throttling.c:acpi_processor_get_tsd
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_states
  - drivers/acpi/processor_perflib.c:acpi_processor_get_psd
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states
  - drivers/acpi/cppc_acpi.c:acpi_get_psd
```
**Symbols:**

```
ffffffff816823cb-ffffffff81682478: acpi_extract_package.cold (STB_LOCAL)
ffffffff816810e0-ffffffff816813d0: acpi_extract_package (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
acpi_status acpi_extract_package(union acpi_object *package, struct acpi_buffer *format, struct acpi_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/utils.c (0)
Location: drivers/acpi/utils.c:42
Inline: False
Direct callers:
  - drivers/acpi/fan.c:acpi_fan_get_fps
  - drivers/acpi/fan.c:acpi_fan_get_fif
  - drivers/acpi/processor_throttling.c:acpi_processor_get_tsd
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_states
  - drivers/acpi/processor_perflib.c:acpi_processor_get_psd
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states
  - drivers/acpi/cppc_acpi.c:acpi_get_psd
```
**Symbols:**

```
ffffffff81c009f8-ffffffff81c00aa5: acpi_extract_package.cold (STB_LOCAL)
ffffffff8169fa30-ffffffff8169fd20: acpi_extract_package (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
acpi_status acpi_extract_package(union acpi_object *package, struct acpi_buffer *format, struct acpi_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff816826c0)
Location: drivers/acpi/utils.c:32
Inline: False
Direct callers:
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/fan.c:acpi_fan_get_fps
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_states
  - drivers/acpi/processor_perflib.c:acpi_processor_get_psd
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states
  - drivers/acpi/cppc_acpi.c:acpi_get_psd
```
**Symbols:**

```
ffffffff816826c0-ffffffff81682ad5: acpi_extract_package (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
acpi_status acpi_extract_package(union acpi_object *package, struct acpi_buffer *format, struct acpi_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff816f7830)
Location: drivers/acpi/utils.c:32
Inline: False
Direct callers:
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/fan.c:acpi_fan_get_fps
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_states
  - drivers/acpi/processor_perflib.c:acpi_processor_get_psd
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states
  - drivers/acpi/cppc_acpi.c:acpi_get_psd
```
**Symbols:**

```
ffffffff816f7830-ffffffff816f7c2d: acpi_extract_package (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
acpi_status acpi_extract_package(union acpi_object *package, struct acpi_buffer *format, struct acpi_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff818247e0)
Location: drivers/acpi/utils.c:32
Inline: False
Direct callers:
  - drivers/acpi/fan_core.c:acpi_fan_probe
  - drivers/acpi/fan_core.c:acpi_fan_probe
  - drivers/acpi/processor_throttling.c:acpi_processor_get_tsd
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_states
  - drivers/acpi/processor_perflib.c:acpi_processor_get_psd
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states
  - drivers/acpi/cppc_acpi.c:acpi_get_psd
```
**Symbols:**

```
ffffffff818247e0-ffffffff81824ba9: acpi_extract_package (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
acpi_status acpi_extract_package(union acpi_object *package, struct acpi_buffer *format, struct acpi_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff81956ba0)
Location: drivers/acpi/utils.c:32
Inline: False
Direct callers:
  - drivers/acpi/fan_core.c:acpi_fan_probe
  - drivers/acpi/fan_core.c:acpi_fan_probe
  - drivers/acpi/processor_throttling.c:acpi_processor_get_tsd
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_states
  - drivers/acpi/processor_perflib.c:acpi_processor_get_psd
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states
  - drivers/acpi/cppc_acpi.c:acpi_get_psd
```
**Symbols:**

```
ffffffff81956ba0-ffffffff81956f6f: acpi_extract_package (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
acpi_status acpi_extract_package(union acpi_object *package, struct acpi_buffer *format, struct acpi_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff8199cfa0)
Location: drivers/acpi/utils.c:32
Inline: False
Direct callers:
  - drivers/acpi/fan_core.c:acpi_fan_probe
  - drivers/acpi/fan_core.c:acpi_fan_probe
  - drivers/acpi/processor_throttling.c:acpi_processor_get_tsd
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_states
  - drivers/acpi/processor_perflib.c:acpi_processor_get_psd
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states
  - drivers/acpi/cppc_acpi.c:acpi_get_psd
```
**Symbols:**

```
ffffffff8199cfa0-ffffffff8199d384: acpi_extract_package (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
acpi_status acpi_extract_package(union acpi_object *package, struct acpi_buffer *format, struct acpi_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff819e5010)
Location: drivers/acpi/utils.c:32
Inline: False
Direct callers:
  - drivers/acpi/fan_core.c:acpi_fan_probe
  - drivers/acpi/fan_core.c:acpi_fan_probe
  - drivers/acpi/processor_throttling.c:acpi_processor_get_tsd
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_states
  - drivers/acpi/processor_perflib.c:acpi_processor_get_psd
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states
  - drivers/acpi/cppc_acpi.c:acpi_get_psd
```
**Symbols:**

```
ffffffff819e5010-ffffffff819e53f4: acpi_extract_package (STB_GLOBAL)
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
acpi_status acpi_extract_package(union acpi_object *package, struct acpi_buffer *format, struct acpi_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffff800010764948)
Location: drivers/acpi/utils.c:42
Inline: False
Direct callers:
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/processor_perflib.c:acpi_processor_get_psd
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
```
**Symbols:**

```
ffff800010764948-ffff800010764d08: acpi_extract_package (STB_GLOBAL)
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
acpi_status acpi_extract_package(union acpi_object *package, struct acpi_buffer *format, struct acpi_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/utils.c (0)
Location: drivers/acpi/utils.c:42
Inline: False
Direct callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_perflib.c:acpi_processor_get_psd
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
```
**Symbols:**

```
ffffffff815cb888-ffffffff815cb938: acpi_extract_package.cold (STB_LOCAL)
ffffffff815ca8f0-ffffffff815cabdc: acpi_extract_package (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
acpi_status acpi_extract_package(union acpi_object *package, struct acpi_buffer *format, struct acpi_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/utils.c (0)
Location: drivers/acpi/utils.c:42
Inline: False
Direct callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_perflib.c:acpi_processor_get_psd
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
```
**Symbols:**

```
ffffffff815b48d8-ffffffff815b4988: acpi_extract_package.cold (STB_LOCAL)
ffffffff815b3920-ffffffff815b3c2a: acpi_extract_package (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
acpi_status acpi_extract_package(union acpi_object *package, struct acpi_buffer *format, struct acpi_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/utils.c (0)
Location: drivers/acpi/utils.c:42
Inline: False
Direct callers:
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_perflib.c:acpi_processor_get_psd
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
```
**Symbols:**

```
ffffffff815cc838-ffffffff815cc8e8: acpi_extract_package.cold (STB_LOCAL)
ffffffff815cb620-ffffffff815cb962: acpi_extract_package (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
acpi_status acpi_extract_package(union acpi_object *package, struct acpi_buffer *format, struct acpi_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/utils.c (0)
Location: drivers/acpi/utils.c:42
Inline: False
Direct callers:
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_perflib.c:acpi_processor_get_psd
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
```
**Symbols:**

```
ffffffff815e66d8-ffffffff815e6788: acpi_extract_package.cold (STB_LOCAL)
ffffffff815e54c0-ffffffff815e5802: acpi_extract_package (STB_GLOBAL)
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
