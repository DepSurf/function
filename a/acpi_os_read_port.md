# Function: <code>acpi_os_read_port</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_os_read_port(acpi_io_address port, u32 *value, u32 width);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff81479a5e)
Location: drivers/acpi/osl.c:910
Inline: True
Direct callers:
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_read_port
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_read_port
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_ptc
  - drivers/acpi/apei/apei-base.c:apei_read
```
**Symbols:**

```
ffffffff81479a5e-ffffffff81479acb: acpi_os_read_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_os_read_port(acpi_io_address port, u32 *value, u32 width);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff814c8023)
Location: drivers/acpi/osl.c:632
Inline: True
Direct callers:
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_read_port
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_read_port
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_ptc
  - drivers/acpi/apei/apei-base.c:apei_read
  - drivers/cpufreq/acpi-cpufreq.c:cpu_freq_read_io
```
**Symbols:**

```
ffffffff814c8023-ffffffff814c8090: acpi_os_read_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_os_read_port(acpi_io_address port, u32 *value, u32 width);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff814e9f33)
Location: drivers/acpi/osl.c:627
Inline: True
Direct callers:
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_read_port
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_read_port
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_ptc
  - drivers/acpi/apei/apei-base.c:apei_read
  - drivers/cpufreq/acpi-cpufreq.c:cpu_freq_read_io
```
**Symbols:**

```
ffffffff814e9f33-ffffffff814e9fa0: acpi_os_read_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_os_read_port(acpi_io_address port, u32 *value, u32 width);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff814f5c00)
Location: drivers/acpi/osl.c:626
Inline: True
Direct callers:
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_read_port
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_read_port
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_ptc
  - drivers/acpi/apei/apei-base.c:apei_read
  - drivers/cpufreq/acpi-cpufreq.c:cpu_freq_read_io
```
**Symbols:**

```
ffffffff814f5c00-ffffffff814f5c6b: acpi_os_read_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_os_read_port(acpi_io_address port, u32 *value, u32 width);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff81536540)
Location: drivers/acpi/osl.c:626
Inline: True
Direct callers:
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_read_port
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_read_port
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_ptc
  - drivers/acpi/apei/apei-base.c:apei_read
  - drivers/cpufreq/acpi-cpufreq.c:cpu_freq_read_io
```
**Symbols:**

```
ffffffff81536540-ffffffff815365ab: acpi_os_read_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_os_read_port(acpi_io_address port, u32 *value, u32 width);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff8156c1a0)
Location: drivers/acpi/osl.c:631
Inline: True
Direct callers:
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_read_port
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_read_port
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_ptc
  - drivers/acpi/apei/apei-base.c:apei_read
  - drivers/cpufreq/acpi-cpufreq.c:cpu_freq_read_io
```
**Symbols:**

```
ffffffff8156c1a0-ffffffff8156c20b: acpi_os_read_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_os_read_port(acpi_io_address port, u32 *value, u32 width);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff81583dd0)
Location: drivers/acpi/osl.c:634
Inline: True
Direct callers:
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_read_port
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_read_port
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_ptc
  - drivers/acpi/apei/apei-base.c:apei_read
  - drivers/cpufreq/acpi-cpufreq.c:cpu_freq_read_io
```
**Symbols:**

```
ffffffff81583dd0-ffffffff81583e3b: acpi_os_read_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_os_read_port(acpi_io_address port, u32 *value, u32 width);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff815b49b0)
Location: drivers/acpi/osl.c:620
Inline: True
Direct callers:
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_read_port
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_read_port
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_ptc
  - drivers/acpi/apei/apei-base.c:apei_read
  - drivers/cpufreq/acpi-cpufreq.c:cpu_freq_read_io
```
**Symbols:**

```
ffffffff815b49b0-ffffffff815b4a1b: acpi_os_read_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_os_read_port(acpi_io_address port, u32 *value, u32 width);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff815d5c30)
Location: drivers/acpi/osl.c:640
Inline: True
Direct callers:
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_read_port
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_read_port
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_ptc
  - drivers/acpi/apei/apei-base.c:apei_read
  - drivers/cpufreq/acpi-cpufreq.c:cpu_freq_read_io
```
**Symbols:**

```
ffffffff815d5c30-ffffffff815d5c9b: acpi_os_read_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_os_read_port(acpi_io_address port, u32 *value, u32 width);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff8167f7c0)
Location: drivers/acpi/osl.c:640
Inline: True
Direct callers:
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_read_port
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_read_port
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_ptc
  - drivers/acpi/apei/apei-base.c:apei_read
  - drivers/cpufreq/acpi-cpufreq.c:cpu_freq_read_io
```
**Symbols:**

```
ffffffff8167f7c0-ffffffff8167f82b: acpi_os_read_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_os_read_port(acpi_io_address port, u32 *value, u32 width);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff8169e280)
Location: drivers/acpi/osl.c:644
Inline: True
Direct callers:
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_read_port
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_read_port
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_ptc
  - drivers/acpi/apei/apei-base.c:apei_read
  - drivers/cpufreq/acpi-cpufreq.c:cpu_freq_read_io
```
**Symbols:**

```
ffffffff8169e280-ffffffff8169e2eb: acpi_os_read_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_os_read_port(acpi_io_address port, u32 *value, u32 width);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff81680fc0)
Location: drivers/acpi/osl.c:645
Inline: True
Direct callers:
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_read_port
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_read_port
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_ptc
  - drivers/acpi/apei/apei-base.c:apei_read
  - drivers/cpufreq/acpi-cpufreq.c:cpu_freq_read_io
```
**Symbols:**

```
ffffffff81680fc0-ffffffff8168102b: acpi_os_read_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
acpi_status acpi_os_read_port(acpi_io_address port, u32 *value, u32 width);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff816f5f50)
Location: drivers/acpi/osl.c:645
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_read_port
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_read_port
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_ptc
  - drivers/acpi/apei/apei-base.c:apei_read
  - drivers/cpufreq/acpi-cpufreq.c:cpu_freq_read_io
```
**Symbols:**

```
ffffffff816f5f50-ffffffff816f5fbb: acpi_os_read_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_os_read_port(acpi_io_address port, u32 *value, u32 width);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff81822ed0)
Location: drivers/acpi/osl.c:644
Inline: True
Direct callers:
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_gpe_read
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_read_port
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_read_port
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_ptc
  - drivers/acpi/apei/apei-base.c:apei_read
  - drivers/cpufreq/acpi-cpufreq.c:cpu_freq_read_io
```
**Symbols:**

```
ffffffff81822ed0-ffffffff81822f6d: acpi_os_read_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_os_read_port(acpi_io_address port, u32 *value, u32 width);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff81953f90)
Location: drivers/acpi/osl.c:644
Inline: True
Direct callers:
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_gpe_read
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_read_port
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_read_port
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_ptc
  - drivers/acpi/apei/apei-base.c:apei_read
  - drivers/cpufreq/acpi-cpufreq.c:cpu_freq_read_io
```
**Symbols:**

```
ffffffff81953f90-ffffffff8195402d: acpi_os_read_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_os_read_port(acpi_io_address port, u32 *value, u32 width);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff8199a390)
Location: drivers/acpi/osl.c:644
Inline: True
Direct callers:
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_gpe_read
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_read_port
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_read_port
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_ptc
  - drivers/acpi/apei/apei-base.c:apei_read
  - drivers/cpufreq/acpi-cpufreq.c:cpu_freq_read_io
```
**Symbols:**

```
ffffffff8199a390-ffffffff8199a431: acpi_os_read_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_os_read_port(acpi_io_address port, u32 *value, u32 width);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff819e2810)
Location: drivers/acpi/osl.c:641
Inline: True
Direct callers:
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_gpe_read
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_read_port
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_read_port
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_ptc
  - drivers/acpi/apei/apei-base.c:apei_read
  - drivers/cpufreq/acpi-cpufreq.c:cpu_freq_read_io
```
**Symbols:**

```
ffffffff819e2810-ffffffff819e28b1: acpi_os_read_port (STB_GLOBAL)
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
acpi_status acpi_os_read_port(acpi_io_address port, u32 *value, u32 width);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffff8000107634a8)
Location: drivers/acpi/osl.c:640
Inline: True
Direct callers:
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_read_port
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_read_port
  - drivers/acpi/apei/apei-base.c:apei_read
```
**Symbols:**

```
ffff8000107634a8-ffff800010763560: acpi_os_read_port (STB_GLOBAL)
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_os_read_port(acpi_io_address port, u32 *value, u32 width);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff815c9990)
Location: drivers/acpi/osl.c:640
Inline: True
Direct callers:
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_read_port
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_read_port
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_ptc
  - drivers/cpufreq/acpi-cpufreq.c:cpu_freq_read_io
```
**Symbols:**

```
ffffffff815c9990-ffffffff815c99fb: acpi_os_read_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_os_read_port(acpi_io_address port, u32 *value, u32 width);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff815b2a20)
Location: drivers/acpi/osl.c:640
Inline: True
Direct callers:
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_read_port
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_read_port
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_ptc
  - drivers/acpi/apei/apei-base.c:apei_read
  - drivers/cpufreq/acpi-cpufreq.c:cpu_freq_read_io
```
**Symbols:**

```
ffffffff815b2a20-ffffffff815b2a8b: acpi_os_read_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_os_read_port(acpi_io_address port, u32 *value, u32 width);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff815c9f10)
Location: drivers/acpi/osl.c:640
Inline: True
Direct callers:
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_read_port
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_read_port
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_ptc
  - drivers/acpi/apei/apei-base.c:apei_read
  - drivers/cpufreq/acpi-cpufreq.c:cpu_freq_read_io
```
**Symbols:**

```
ffffffff815c9f10-ffffffff815c9f7b: acpi_os_read_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_os_read_port(acpi_io_address port, u32 *value, u32 width);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff815e3d70)
Location: drivers/acpi/osl.c:640
Inline: True
Direct callers:
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_read_port
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_read_port
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_ptc
  - drivers/acpi/apei/apei-base.c:apei_read
  - drivers/cpufreq/acpi-cpufreq.c:cpu_freq_read_io
```
**Symbols:**

```
ffffffff815e3d70-ffffffff815e3ddb: acpi_os_read_port (STB_GLOBAL)
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
