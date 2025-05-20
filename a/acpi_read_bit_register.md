# Function: <code>acpi_read_bit_register</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
acpi_status acpi_read_bit_register(u32 register_id, u32 *return_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwxface.c (ffffffff8149b540)
Location: drivers/acpi/acpica/hwxface.c:300
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwacpi.c:acpi_hw_get_mode
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep
  - drivers/acpi/processor_idle.c:acpi_processor_suspend
  - drivers/acpi/processor_idle.c:acpi_processor_resume
  - drivers/acpi/processor_idle.c:acpi_idle_enter
```
**Symbols:**

```
ffffffff8149b540-ffffffff8149b5b0: acpi_read_bit_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
acpi_status acpi_read_bit_register(u32 register_id, u32 *return_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwxface.c (ffffffff814ea5bc)
Location: drivers/acpi/acpica/hwxface.c:299
Inline: False
Direct callers:
  - drivers/acpi/sleep.c:acpi_restore_bm_rld
  - drivers/acpi/sleep.c:acpi_save_bm_rld
  - drivers/acpi/acpica/hwacpi.c:acpi_hw_get_mode
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep
  - drivers/acpi/processor_idle.c:acpi_idle_enter
```
**Symbols:**

```
ffffffff814ea5bc-ffffffff814ea62c: acpi_read_bit_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
acpi_status acpi_read_bit_register(u32 register_id, u32 *return_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwxface.c (ffffffff8150ce44)
Location: drivers/acpi/acpica/hwxface.c:299
Inline: False
Direct callers:
  - drivers/acpi/sleep.c:acpi_restore_bm_rld
  - drivers/acpi/sleep.c:acpi_save_bm_rld
  - drivers/acpi/acpica/hwacpi.c:acpi_hw_get_mode
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep
  - drivers/acpi/processor_idle.c:acpi_idle_enter
```
**Symbols:**

```
ffffffff8150ce44-ffffffff8150ceb4: acpi_read_bit_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
acpi_status acpi_read_bit_register(u32 register_id, u32 *return_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwxface.c (ffffffff8151d5fb)
Location: drivers/acpi/acpica/hwxface.c:299
Inline: False
Direct callers:
  - drivers/acpi/sleep.c:acpi_restore_bm_rld
  - drivers/acpi/sleep.c:acpi_save_bm_rld
  - drivers/acpi/acpica/hwacpi.c:acpi_hw_get_mode
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep
  - drivers/acpi/processor_idle.c:acpi_idle_enter
```
**Symbols:**

```
ffffffff8151d5fb-ffffffff8151d66b: acpi_read_bit_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
acpi_status acpi_read_bit_register(u32 register_id, u32 *return_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwxface.c (ffffffff8156e0ef)
Location: drivers/acpi/acpica/hwxface.c:187
Inline: False
Direct callers:
  - drivers/acpi/sleep.c:acpi_restore_bm_rld
  - drivers/acpi/sleep.c:acpi_save_bm_rld
  - drivers/acpi/acpica/evxfevnt.c:acpi_get_event_status
  - drivers/acpi/acpica/evxfevnt.c:acpi_get_event_status
  - drivers/acpi/acpica/hwacpi.c:acpi_hw_get_mode
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep
  - drivers/acpi/processor_idle.c:acpi_idle_enter
```
**Symbols:**

```
ffffffff8156e0ef-ffffffff8156e251: acpi_read_bit_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
acpi_status acpi_read_bit_register(u32 register_id, u32 *return_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwxface.c (ffffffff815a4dce)
Location: drivers/acpi/acpica/hwxface.c:153
Inline: False
Direct callers:
  - drivers/acpi/sleep.c:acpi_restore_bm_rld
  - drivers/acpi/sleep.c:acpi_save_bm_rld
  - drivers/acpi/acpica/evxfevnt.c:acpi_get_event_status
  - drivers/acpi/acpica/evxfevnt.c:acpi_get_event_status
  - drivers/acpi/acpica/hwacpi.c:acpi_hw_get_mode
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep
  - drivers/acpi/processor_idle.c:acpi_idle_enter
```
**Symbols:**

```
ffffffff815a4dce-ffffffff815a4f30: acpi_read_bit_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
acpi_status acpi_read_bit_register(u32 register_id, u32 *return_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwxface.c (ffffffff815bd78e)
Location: drivers/acpi/acpica/hwxface.c:153
Inline: False
Direct callers:
  - drivers/acpi/sleep.c:acpi_restore_bm_rld
  - drivers/acpi/sleep.c:acpi_save_bm_rld
  - drivers/acpi/acpica/evxfevnt.c:acpi_get_event_status
  - drivers/acpi/acpica/evxfevnt.c:acpi_get_event_status
  - drivers/acpi/acpica/hwacpi.c:acpi_hw_get_mode
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep
  - drivers/acpi/processor_idle.c:acpi_idle_enter
```
**Symbols:**

```
ffffffff815bd78e-ffffffff815bd8eb: acpi_read_bit_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
acpi_status acpi_read_bit_register(u32 register_id, u32 *return_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwxface.c (ffffffff815ef390)
Location: drivers/acpi/acpica/hwxface.c:153
Inline: False
Direct callers:
  - drivers/acpi/sleep.c:acpi_restore_bm_rld
  - drivers/acpi/sleep.c:acpi_save_bm_rld
  - drivers/acpi/acpica/evxfevnt.c:acpi_get_event_status
  - drivers/acpi/acpica/evxfevnt.c:acpi_get_event_status
  - drivers/acpi/acpica/hwacpi.c:acpi_hw_get_mode
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep
  - drivers/acpi/processor_idle.c:acpi_idle_enter
```
**Symbols:**

```
ffffffff815ef390-ffffffff815ef4ed: acpi_read_bit_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
acpi_status acpi_read_bit_register(u32 register_id, u32 *return_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwxface.c (ffffffff8161081e)
Location: drivers/acpi/acpica/hwxface.c:153
Inline: False
Direct callers:
  - drivers/acpi/sleep.c:acpi_restore_bm_rld
  - drivers/acpi/sleep.c:acpi_save_bm_rld
  - drivers/acpi/acpica/evxfevnt.c:acpi_get_event_status
  - drivers/acpi/acpica/evxfevnt.c:acpi_get_event_status
  - drivers/acpi/acpica/hwacpi.c:acpi_hw_get_mode
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep
  - drivers/acpi/processor_idle.c:acpi_idle_enter
```
**Symbols:**

```
ffffffff8161081e-ffffffff8161097b: acpi_read_bit_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
acpi_status acpi_read_bit_register(u32 register_id, u32 *return_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwxface.c (ffffffff816bcceb)
Location: drivers/acpi/acpica/hwxface.c:153
Inline: False
Direct callers:
  - drivers/acpi/sleep.c:acpi_restore_bm_rld
  - drivers/acpi/sleep.c:acpi_save_bm_rld
  - drivers/acpi/acpica/evxfevnt.c:acpi_get_event_status
  - drivers/acpi/acpica/evxfevnt.c:acpi_get_event_status
  - drivers/acpi/acpica/evxfevnt.c:acpi_disable_event
  - drivers/acpi/acpica/evxfevnt.c:acpi_enable_event
  - drivers/acpi/acpica/hwacpi.c:acpi_hw_get_mode
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep
  - drivers/acpi/processor_idle.c:acpi_idle_bm_check
```
**Symbols:**

```
ffffffff816bcceb-ffffffff816bce48: acpi_read_bit_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
acpi_status acpi_read_bit_register(u32 register_id, u32 *return_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwxface.c (ffffffff816da88d)
Location: drivers/acpi/acpica/hwxface.c:153
Inline: False
Direct callers:
  - drivers/acpi/sleep.c:acpi_restore_bm_rld
  - drivers/acpi/sleep.c:acpi_save_bm_rld
  - drivers/acpi/acpica/evxfevnt.c:acpi_get_event_status
  - drivers/acpi/acpica/evxfevnt.c:acpi_get_event_status
  - drivers/acpi/acpica/evxfevnt.c:acpi_disable_event
  - drivers/acpi/acpica/evxfevnt.c:acpi_enable_event
  - drivers/acpi/acpica/hwacpi.c:acpi_hw_get_mode
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep
  - drivers/acpi/processor_idle.c:acpi_idle_bm_check
```
**Symbols:**

```
ffffffff816da88d-ffffffff816da9ea: acpi_read_bit_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
acpi_status acpi_read_bit_register(u32 register_id, u32 *return_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwxface.c (ffffffff816bc82a)
Location: drivers/acpi/acpica/hwxface.c:153
Inline: False
Direct callers:
  - drivers/acpi/sleep.c:acpi_restore_bm_rld
  - drivers/acpi/sleep.c:acpi_save_bm_rld
  - drivers/acpi/acpica/evxfevnt.c:acpi_get_event_status
  - drivers/acpi/acpica/evxfevnt.c:acpi_get_event_status
  - drivers/acpi/acpica/evxfevnt.c:acpi_disable_event
  - drivers/acpi/acpica/evxfevnt.c:acpi_enable_event
  - drivers/acpi/acpica/hwacpi.c:acpi_hw_get_mode
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
```
**Symbols:**

```
ffffffff816bc82a-ffffffff816bc987: acpi_read_bit_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
acpi_status acpi_read_bit_register(u32 register_id, u32 *return_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwxface.c (ffffffff81733a4b)
Location: drivers/acpi/acpica/hwxface.c:153
Inline: False
Direct callers:
  - drivers/acpi/sleep.c:acpi_restore_bm_rld
  - drivers/acpi/sleep.c:acpi_save_bm_rld
  - drivers/acpi/acpica/evxfevnt.c:acpi_get_event_status
  - drivers/acpi/acpica/evxfevnt.c:acpi_get_event_status
  - drivers/acpi/acpica/evxfevnt.c:acpi_disable_event
  - drivers/acpi/acpica/evxfevnt.c:acpi_enable_event
  - drivers/acpi/acpica/hwacpi.c:acpi_hw_get_mode
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
```
**Symbols:**

```
ffffffff81733a4b-ffffffff81733bc6: acpi_read_bit_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
acpi_status acpi_read_bit_register(u32 register_id, u32 *return_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwxface.c (ffffffff818649a6)
Location: drivers/acpi/acpica/hwxface.c:153
Inline: False
Direct callers:
  - drivers/acpi/sleep.c:acpi_restore_bm_rld
  - drivers/acpi/sleep.c:acpi_save_bm_rld
  - drivers/acpi/acpica/evxfevnt.c:acpi_get_event_status
  - drivers/acpi/acpica/evxfevnt.c:acpi_get_event_status
  - drivers/acpi/acpica/evxfevnt.c:acpi_disable_event
  - drivers/acpi/acpica/evxfevnt.c:acpi_enable_event
  - drivers/acpi/acpica/hwacpi.c:acpi_hw_get_mode
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep
  - drivers/acpi/acpica/hwxfsleep.c:acpi_enter_sleep_state_s4bios
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
```
**Symbols:**

```
ffffffff818649a6-ffffffff81864b38: acpi_read_bit_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
acpi_status acpi_read_bit_register(u32 register_id, u32 *return_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpica/hwxface.c (0)
Location: drivers/acpi/acpica/hwxface.c:153
Inline: False
Direct callers:
  - drivers/acpi/sleep.c:acpi_restore_bm_rld
  - drivers/acpi/sleep.c:acpi_save_bm_rld
  - drivers/acpi/acpica/evxfevnt.c:acpi_get_event_status
  - drivers/acpi/acpica/evxfevnt.c:acpi_get_event_status
  - drivers/acpi/acpica/evxfevnt.c:acpi_disable_event
  - drivers/acpi/acpica/evxfevnt.c:acpi_enable_event
  - drivers/acpi/acpica/hwacpi.c:acpi_hw_get_mode
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep
  - drivers/acpi/acpica/hwxfsleep.c:acpi_enter_sleep_state_s4bios
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
```
**Symbols:**

```
ffffffff820922a1-ffffffff820922c2: acpi_read_bit_register.cold (STB_LOCAL)
ffffffff819a2940-ffffffff819a2ad9: acpi_read_bit_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
acpi_status acpi_read_bit_register(u32 register_id, u32 *return_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpica/hwxface.c (0)
Location: drivers/acpi/acpica/hwxface.c:153
Inline: False
Direct callers:
  - drivers/acpi/sleep.c:acpi_restore_bm_rld
  - drivers/acpi/sleep.c:acpi_save_bm_rld
  - drivers/acpi/acpica/evxfevnt.c:acpi_get_event_status
  - drivers/acpi/acpica/evxfevnt.c:acpi_get_event_status
  - drivers/acpi/acpica/evxfevnt.c:acpi_disable_event
  - drivers/acpi/acpica/evxfevnt.c:acpi_enable_event
  - drivers/acpi/acpica/hwacpi.c:acpi_hw_get_mode
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep
  - drivers/acpi/acpica/hwxfsleep.c:acpi_enter_sleep_state_s4bios
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
```
**Symbols:**

```
ffffffff82112b95-ffffffff82112bb6: acpi_read_bit_register.cold (STB_LOCAL)
ffffffff819e95f0-ffffffff819e9789: acpi_read_bit_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
acpi_status acpi_read_bit_register(u32 register_id, u32 *return_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpica/hwxface.c (0)
Location: drivers/acpi/acpica/hwxface.c:153
Inline: False
Direct callers:
  - drivers/acpi/sleep.c:acpi_restore_bm_rld
  - drivers/acpi/sleep.c:acpi_save_bm_rld
  - drivers/acpi/acpica/evxfevnt.c:acpi_get_event_status
  - drivers/acpi/acpica/evxfevnt.c:acpi_get_event_status
  - drivers/acpi/acpica/evxfevnt.c:acpi_disable_event
  - drivers/acpi/acpica/evxfevnt.c:acpi_enable_event
  - drivers/acpi/acpica/hwacpi.c:acpi_hw_get_mode
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep
  - drivers/acpi/acpica/hwxfsleep.c:acpi_enter_sleep_state_s4bios
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
```
**Symbols:**

```
ffffffff821f08e9-ffffffff821f090a: acpi_read_bit_register.cold (STB_LOCAL)
ffffffff81a34340-ffffffff81a344d9: acpi_read_bit_register (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
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
acpi_status acpi_read_bit_register(u32 register_id, u32 *return_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwxface.c (ffffffff815f178e)
Location: drivers/acpi/acpica/hwxface.c:153
Inline: False
Direct callers:
  - drivers/acpi/sleep.c:acpi_restore_bm_rld
  - drivers/acpi/sleep.c:acpi_save_bm_rld
  - drivers/acpi/acpica/hwacpi.c:acpi_hw_get_mode
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep
  - drivers/acpi/processor_idle.c:acpi_idle_enter
```
**Symbols:**

```
ffffffff815f178e-ffffffff815f17fe: acpi_read_bit_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
acpi_status acpi_read_bit_register(u32 register_id, u32 *return_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwxface.c (ffffffff815dcd35)
Location: drivers/acpi/acpica/hwxface.c:153
Inline: False
Direct callers:
  - drivers/acpi/sleep.c:acpi_restore_bm_rld
  - drivers/acpi/sleep.c:acpi_save_bm_rld
  - drivers/acpi/acpica/hwacpi.c:acpi_hw_get_mode
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep
  - drivers/acpi/processor_idle.c:acpi_idle_enter
```
**Symbols:**

```
ffffffff815dcd35-ffffffff815dcda5: acpi_read_bit_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
acpi_status acpi_read_bit_register(u32 register_id, u32 *return_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwxface.c (ffffffff81604afe)
Location: drivers/acpi/acpica/hwxface.c:153
Inline: False
Direct callers:
  - drivers/acpi/sleep.c:acpi_restore_bm_rld
  - drivers/acpi/sleep.c:acpi_save_bm_rld
  - drivers/acpi/acpica/evxfevnt.c:acpi_get_event_status
  - drivers/acpi/acpica/evxfevnt.c:acpi_get_event_status
  - drivers/acpi/acpica/hwacpi.c:acpi_hw_get_mode
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep
  - drivers/acpi/processor_idle.c:acpi_idle_enter
```
**Symbols:**

```
ffffffff81604afe-ffffffff81604c5b: acpi_read_bit_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
acpi_status acpi_read_bit_register(u32 register_id, u32 *return_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwxface.c (ffffffff8161e9ae)
Location: drivers/acpi/acpica/hwxface.c:153
Inline: False
Direct callers:
  - drivers/acpi/sleep.c:acpi_restore_bm_rld
  - drivers/acpi/sleep.c:acpi_save_bm_rld
  - drivers/acpi/acpica/evxfevnt.c:acpi_get_event_status
  - drivers/acpi/acpica/evxfevnt.c:acpi_get_event_status
  - drivers/acpi/acpica/hwacpi.c:acpi_hw_get_mode
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep
  - drivers/acpi/processor_idle.c:acpi_idle_enter
```
**Symbols:**

```
ffffffff8161e9ae-ffffffff8161eb0b: acpi_read_bit_register (STB_GLOBAL)
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
