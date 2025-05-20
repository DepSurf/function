# Function: <code>acpi_os_write_port</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_os_write_port(acpi_io_address port, u32 value, u32 width);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff81479acb)
Location: drivers/acpi/osl.c:933
Inline: True
Direct callers:
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_write_port
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_write_port
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_ptc
  - drivers/acpi/apei/apei-base.c:apei_write
```
**Symbols:**

```
ffffffff81479acb-ffffffff81479afb: acpi_os_write_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_os_write_port(acpi_io_address port, u32 value, u32 width);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff814c8090)
Location: drivers/acpi/osl.c:655
Inline: True
Direct callers:
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_write_port
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_write_port
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_ptc
  - drivers/acpi/apei/apei-base.c:apei_write
  - drivers/cpufreq/acpi-cpufreq.c:cpu_freq_write_io
```
**Symbols:**

```
ffffffff814c8090-ffffffff814c80c0: acpi_os_write_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_os_write_port(acpi_io_address port, u32 value, u32 width);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff814e9fa0)
Location: drivers/acpi/osl.c:650
Inline: True
Direct callers:
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_write_port
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_write_port
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_ptc
  - drivers/acpi/processor_perflib.c:acpi_processor_pstate_control
  - drivers/acpi/apei/apei-base.c:apei_write
  - drivers/cpufreq/acpi-cpufreq.c:cpu_freq_write_io
```
**Symbols:**

```
ffffffff814e9fa0-ffffffff814e9fd0: acpi_os_write_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_os_write_port(acpi_io_address port, u32 value, u32 width);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff814f5c70)
Location: drivers/acpi/osl.c:649
Inline: True
Direct callers:
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_write_port
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_write_port
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_ptc
  - drivers/acpi/processor_perflib.c:acpi_processor_pstate_control
  - drivers/acpi/apei/apei-base.c:apei_write
  - drivers/cpufreq/acpi-cpufreq.c:cpu_freq_write_io
```
**Symbols:**

```
ffffffff814f5c70-ffffffff814f5ca6: acpi_os_write_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_os_write_port(acpi_io_address port, u32 value, u32 width);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff815365b0)
Location: drivers/acpi/osl.c:649
Inline: True
Direct callers:
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_write_port
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_write_port
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_ptc
  - drivers/acpi/apei/apei-base.c:apei_write
  - drivers/cpufreq/acpi-cpufreq.c:cpu_freq_write_io
```
**Symbols:**

```
ffffffff815365b0-ffffffff815365e6: acpi_os_write_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_os_write_port(acpi_io_address port, u32 value, u32 width);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff8156c210)
Location: drivers/acpi/osl.c:654
Inline: True
Direct callers:
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_write_port
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_write_port
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_ptc
  - drivers/acpi/apei/apei-base.c:apei_write
  - drivers/cpufreq/acpi-cpufreq.c:cpu_freq_write_io
```
**Symbols:**

```
ffffffff8156c210-ffffffff8156c246: acpi_os_write_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_os_write_port(acpi_io_address port, u32 value, u32 width);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff81583e40)
Location: drivers/acpi/osl.c:657
Inline: True
Direct callers:
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_write_port
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_write_port
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_ptc
  - drivers/acpi/apei/apei-base.c:apei_write
  - drivers/cpufreq/acpi-cpufreq.c:cpu_freq_write_io
```
**Symbols:**

```
ffffffff81583e40-ffffffff81583e76: acpi_os_write_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_os_write_port(acpi_io_address port, u32 value, u32 width);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff815b4a20)
Location: drivers/acpi/osl.c:643
Inline: True
Direct callers:
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_write_port
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_write_port
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_ptc
  - drivers/acpi/apei/apei-base.c:apei_write
  - drivers/cpufreq/acpi-cpufreq.c:cpu_freq_write_io
```
**Symbols:**

```
ffffffff815b4a20-ffffffff815b4a56: acpi_os_write_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_os_write_port(acpi_io_address port, u32 value, u32 width);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff815d5ca0)
Location: drivers/acpi/osl.c:663
Inline: True
Direct callers:
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_write_port
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_write_port
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_ptc
  - drivers/acpi/apei/apei-base.c:apei_write
  - drivers/cpufreq/acpi-cpufreq.c:cpu_freq_write_io
```
**Symbols:**

```
ffffffff815d5ca0-ffffffff815d5cd6: acpi_os_write_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_os_write_port(acpi_io_address port, u32 value, u32 width);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff8167f830)
Location: drivers/acpi/osl.c:663
Inline: True
Direct callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_claim_cst_control
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_write_port
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_write_port
  - drivers/acpi/acpica/hwxface.c:acpi_reset
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_ptc
  - drivers/acpi/processor_perflib.c:acpi_processor_pstate_control
  - drivers/acpi/apei/apei-base.c:apei_write
  - drivers/cpufreq/acpi-cpufreq.c:cpu_freq_write_io
```
**Symbols:**

```
ffffffff8167f830-ffffffff8167f866: acpi_os_write_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_os_write_port(acpi_io_address port, u32 value, u32 width);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff8169e2f0)
Location: drivers/acpi/osl.c:667
Inline: True
Direct callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_claim_cst_control
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_write_port
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_write_port
  - drivers/acpi/acpica/hwxface.c:acpi_reset
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_ptc
  - drivers/acpi/processor_perflib.c:acpi_processor_pstate_control
  - drivers/acpi/apei/apei-base.c:apei_write
  - drivers/cpufreq/acpi-cpufreq.c:cpu_freq_write_io
```
**Symbols:**

```
ffffffff8169e2f0-ffffffff8169e326: acpi_os_write_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_os_write_port(acpi_io_address port, u32 value, u32 width);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff81681030)
Location: drivers/acpi/osl.c:668
Inline: True
Direct callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_claim_cst_control
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_write_port
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_write_port
  - drivers/acpi/acpica/hwxface.c:acpi_reset
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_ptc
  - drivers/acpi/apei/apei-base.c:apei_write
  - drivers/cpufreq/acpi-cpufreq.c:cpu_freq_write_io
```
**Symbols:**

```
ffffffff81681030-ffffffff81681066: acpi_os_write_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_os_write_port(acpi_io_address port, u32 value, u32 width);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff816f6110)
Location: drivers/acpi/osl.c:668
Inline: True
Direct callers:
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_write_port
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_write_port
  - drivers/acpi/acpica/hwxface.c:acpi_reset
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_ptc
  - drivers/acpi/processor_perflib.c:acpi_processor_pstate_control
  - drivers/acpi/apei/apei-base.c:apei_write
  - drivers/cpufreq/acpi-cpufreq.c:cpu_freq_write_io
```
**Symbols:**

```
ffffffff816f6110-ffffffff816f6146: acpi_os_write_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_os_write_port(acpi_io_address port, u32 value, u32 width);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff81822f70)
Location: drivers/acpi/osl.c:669
Inline: True
Direct callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_claim_cst_control
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_write_port
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_write_port
  - drivers/acpi/acpica/hwxface.c:acpi_reset
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_ptc
  - drivers/acpi/processor_perflib.c:acpi_processor_pstate_control
  - drivers/acpi/cppc_acpi.c:cpc_write
  - drivers/acpi/apei/apei-base.c:apei_write
  - drivers/cpufreq/acpi-cpufreq.c:cpu_freq_write_io
```
**Symbols:**

```
ffffffff81822f70-ffffffff81823008: acpi_os_write_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_os_write_port(acpi_io_address port, u32 value, u32 width);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff81954040)
Location: drivers/acpi/osl.c:669
Inline: True
Direct callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_claim_cst_control
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_enable_wakeup_gpe_block
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_enable_runtime_gpe_block
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_clear_gpe_block
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_disable_gpe_block
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_clear_gpe
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_low_set_gpe
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_write_port
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_write_port
  - drivers/acpi/acpica/hwxface.c:acpi_reset
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_ptc
  - drivers/acpi/cppc_acpi.c:cpc_write
  - drivers/acpi/apei/apei-base.c:apei_write
  - drivers/cpufreq/acpi-cpufreq.c:cpu_freq_write_io
```
**Symbols:**

```
ffffffff81954040-ffffffff819540d8: acpi_os_write_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_os_write_port(acpi_io_address port, u32 value, u32 width);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff8199a450)
Location: drivers/acpi/osl.c:669
Inline: True
Direct callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_claim_cst_control
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_enable_wakeup_gpe_block
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_enable_runtime_gpe_block
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_clear_gpe_block
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_disable_gpe_block
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_clear_gpe
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_low_set_gpe
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_write_port
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_write_port
  - drivers/acpi/acpica/hwxface.c:acpi_reset
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_ptc
  - drivers/acpi/cppc_acpi.c:cpc_write
  - drivers/acpi/apei/apei-base.c:apei_write
  - drivers/cpufreq/acpi-cpufreq.c:cpu_freq_write_io
```
**Symbols:**

```
ffffffff8199a450-ffffffff8199a4e8: acpi_os_write_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_os_write_port(acpi_io_address port, u32 value, u32 width);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff819e28d0)
Location: drivers/acpi/osl.c:666
Inline: True
Direct callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_claim_cst_control
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_enable_wakeup_gpe_block
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_enable_runtime_gpe_block
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_clear_gpe_block
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_disable_gpe_block
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_clear_gpe
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_low_set_gpe
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_write_port
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_write_port
  - drivers/acpi/acpica/hwxface.c:acpi_reset
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_ptc
  - drivers/acpi/cppc_acpi.c:cpc_write
  - drivers/acpi/apei/apei-base.c:apei_write
  - drivers/cpufreq/acpi-cpufreq.c:cpu_freq_write_io
```
**Symbols:**

```
ffffffff819e28d0-ffffffff819e2968: acpi_os_write_port (STB_GLOBAL)
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
acpi_status acpi_os_write_port(acpi_io_address port, u32 value, u32 width);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffff800010763560)
Location: drivers/acpi/osl.c:663
Inline: True
Direct callers:
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_write_port
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_write_port
  - drivers/acpi/processor_perflib.c:acpi_processor_pstate_control
  - drivers/acpi/apei/apei-base.c:apei_write
```
**Symbols:**

```
ffff800010763560-ffff800010763600: acpi_os_write_port (STB_GLOBAL)
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
acpi_status acpi_os_write_port(acpi_io_address port, u32 value, u32 width);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff815c9a00)
Location: drivers/acpi/osl.c:663
Inline: True
Direct callers:
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_write_port
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_write_port
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_ptc
  - drivers/acpi/processor_perflib.c:acpi_processor_pstate_control
  - drivers/cpufreq/acpi-cpufreq.c:cpu_freq_write_io
```
**Symbols:**

```
ffffffff815c9a00-ffffffff815c9a36: acpi_os_write_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_os_write_port(acpi_io_address port, u32 value, u32 width);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff815b2a90)
Location: drivers/acpi/osl.c:663
Inline: True
Direct callers:
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_write_port
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_write_port
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_ptc
  - drivers/acpi/processor_perflib.c:acpi_processor_pstate_control
  - drivers/acpi/apei/apei-base.c:apei_write
  - drivers/cpufreq/acpi-cpufreq.c:cpu_freq_write_io
```
**Symbols:**

```
ffffffff815b2a90-ffffffff815b2ac6: acpi_os_write_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_os_write_port(acpi_io_address port, u32 value, u32 width);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff815c9f80)
Location: drivers/acpi/osl.c:663
Inline: True
Direct callers:
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_write_port
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_write_port
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_ptc
  - drivers/acpi/apei/apei-base.c:apei_write
  - drivers/cpufreq/acpi-cpufreq.c:cpu_freq_write_io
```
**Symbols:**

```
ffffffff815c9f80-ffffffff815c9fb6: acpi_os_write_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_os_write_port(acpi_io_address port, u32 value, u32 width);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff815e3de0)
Location: drivers/acpi/osl.c:663
Inline: True
Direct callers:
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_write_port
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_write_port
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_ptc
  - drivers/acpi/apei/apei-base.c:apei_write
  - drivers/cpufreq/acpi-cpufreq.c:cpu_freq_write_io
```
**Symbols:**

```
ffffffff815e3de0-ffffffff815e3e16: acpi_os_write_port (STB_GLOBAL)
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
