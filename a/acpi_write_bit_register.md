# Function: <code>acpi_write_bit_register</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
acpi_status acpi_write_bit_register(u32 register_id, u32 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwxface.c (ffffffff8149b5b0)
Location: drivers/acpi/acpica/hwxface.c:361
Inline: False
Direct callers:
  - drivers/acpi/sleep.c:acpi_suspend_enter
  - drivers/acpi/acpica/evevent.c:acpi_ev_initialize_events
  - drivers/acpi/acpica/evevent.c:acpi_ev_fixed_event_detect
  - drivers/acpi/acpica/evevent.c:acpi_ev_fixed_event_detect
  - drivers/acpi/acpica/evglock.c:acpi_ev_release_global_lock
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake
  - drivers/acpi/processor_idle.c:acpi_processor_resume
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
  - drivers/acpi/processor_idle.c:acpi_idle_enter
```
**Symbols:**

```
ffffffff8149b5b0-ffffffff8149b689: acpi_write_bit_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
acpi_status acpi_write_bit_register(u32 register_id, u32 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwxface.c (ffffffff814ea62c)
Location: drivers/acpi/acpica/hwxface.c:360
Inline: False
Direct callers:
  - drivers/acpi/sleep.c:acpi_restore_bm_rld
  - drivers/acpi/sleep.c:acpi_suspend_enter
  - drivers/acpi/acpica/evevent.c:acpi_ev_fixed_event_detect
  - drivers/acpi/acpica/evevent.c:acpi_ev_fixed_event_detect
  - drivers/acpi/acpica/evevent.c:acpi_ev_initialize_events
  - drivers/acpi/acpica/evglock.c:acpi_ev_release_global_lock
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep
  - drivers/acpi/processor_idle.c:acpi_processor_get_power_info
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
```
**Symbols:**

```
ffffffff814ea62c-ffffffff814ea70c: acpi_write_bit_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
acpi_status acpi_write_bit_register(u32 register_id, u32 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwxface.c (ffffffff8150ceb4)
Location: drivers/acpi/acpica/hwxface.c:360
Inline: False
Direct callers:
  - drivers/acpi/sleep.c:acpi_restore_bm_rld
  - drivers/acpi/sleep.c:acpi_suspend_enter
  - drivers/acpi/acpica/evevent.c:acpi_ev_fixed_event_detect
  - drivers/acpi/acpica/evevent.c:acpi_ev_fixed_event_detect
  - drivers/acpi/acpica/evevent.c:acpi_ev_initialize_events
  - drivers/acpi/acpica/evglock.c:acpi_ev_release_global_lock
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep
  - drivers/acpi/processor_idle.c:acpi_processor_get_power_info
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
```
**Symbols:**

```
ffffffff8150ceb4-ffffffff8150cf94: acpi_write_bit_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
acpi_status acpi_write_bit_register(u32 register_id, u32 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwxface.c (ffffffff8151d66b)
Location: drivers/acpi/acpica/hwxface.c:360
Inline: False
Direct callers:
  - drivers/acpi/sleep.c:acpi_restore_bm_rld
  - drivers/acpi/sleep.c:acpi_suspend_enter
  - drivers/acpi/acpica/evevent.c:acpi_ev_fixed_event_detect
  - drivers/acpi/acpica/evevent.c:acpi_ev_fixed_event_detect
  - drivers/acpi/acpica/evevent.c:acpi_ev_initialize_events
  - drivers/acpi/acpica/evglock.c:acpi_ev_release_global_lock
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep
  - drivers/acpi/processor_idle.c:acpi_processor_get_power_info
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
```
**Symbols:**

```
ffffffff8151d66b-ffffffff8151d74b: acpi_write_bit_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
acpi_status acpi_write_bit_register(u32 register_id, u32 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwxface.c (ffffffff8156e251)
Location: drivers/acpi/acpica/hwxface.c:248
Inline: False
Direct callers:
  - drivers/acpi/sleep.c:acpi_restore_bm_rld
  - drivers/acpi/sleep.c:acpi_suspend_enter
  - drivers/acpi/acpica/evevent.c:acpi_ev_fixed_event_detect
  - drivers/acpi/acpica/evevent.c:acpi_ev_fixed_event_detect
  - drivers/acpi/acpica/evevent.c:acpi_ev_initialize_events
  - drivers/acpi/acpica/evglock.c:acpi_ev_release_global_lock
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep
  - drivers/acpi/processor_idle.c:acpi_processor_get_power_info
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
```
**Symbols:**

```
ffffffff8156e251-ffffffff8156e3ed: acpi_write_bit_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
acpi_status acpi_write_bit_register(u32 register_id, u32 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwxface.c (ffffffff815a4f30)
Location: drivers/acpi/acpica/hwxface.c:214
Inline: False
Direct callers:
  - drivers/acpi/sleep.c:acpi_restore_bm_rld
  - drivers/acpi/sleep.c:acpi_suspend_enter
  - drivers/acpi/acpica/evevent.c:acpi_ev_fixed_event_detect
  - drivers/acpi/acpica/evevent.c:acpi_ev_fixed_event_detect
  - drivers/acpi/acpica/evevent.c:acpi_ev_initialize_events
  - drivers/acpi/acpica/evglock.c:acpi_ev_release_global_lock
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep
  - drivers/acpi/processor_idle.c:acpi_processor_get_power_info
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
```
**Symbols:**

```
ffffffff815a4f30-ffffffff815a50cd: acpi_write_bit_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
acpi_status acpi_write_bit_register(u32 register_id, u32 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwxface.c (ffffffff815bd8eb)
Location: drivers/acpi/acpica/hwxface.c:214
Inline: False
Direct callers:
  - drivers/acpi/sleep.c:acpi_restore_bm_rld
  - drivers/acpi/sleep.c:acpi_suspend_enter
  - drivers/acpi/acpica/evevent.c:acpi_ev_fixed_event_detect
  - drivers/acpi/acpica/evevent.c:acpi_ev_fixed_event_detect
  - drivers/acpi/acpica/evevent.c:acpi_ev_initialize_events
  - drivers/acpi/acpica/evglock.c:acpi_ev_release_global_lock
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep
  - drivers/acpi/processor_idle.c:acpi_processor_get_power_info
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
```
**Symbols:**

```
ffffffff815bd8eb-ffffffff815bda89: acpi_write_bit_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
acpi_status acpi_write_bit_register(u32 register_id, u32 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwxface.c (ffffffff815ef4ed)
Location: drivers/acpi/acpica/hwxface.c:214
Inline: False
Direct callers:
  - drivers/acpi/sleep.c:acpi_restore_bm_rld
  - drivers/acpi/sleep.c:acpi_suspend_enter
  - drivers/acpi/acpica/evevent.c:acpi_ev_fixed_event_detect
  - drivers/acpi/acpica/evevent.c:acpi_ev_fixed_event_detect
  - drivers/acpi/acpica/evevent.c:acpi_ev_initialize_events
  - drivers/acpi/acpica/evglock.c:acpi_ev_release_global_lock
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep
  - drivers/acpi/processor_idle.c:acpi_processor_get_power_info
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
```
**Symbols:**

```
ffffffff815ef4ed-ffffffff815ef68d: acpi_write_bit_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
acpi_status acpi_write_bit_register(u32 register_id, u32 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwxface.c (ffffffff8161097b)
Location: drivers/acpi/acpica/hwxface.c:214
Inline: False
Direct callers:
  - drivers/acpi/sleep.c:acpi_restore_bm_rld
  - drivers/acpi/sleep.c:acpi_suspend_enter
  - drivers/acpi/acpica/evevent.c:acpi_ev_fixed_event_detect
  - drivers/acpi/acpica/evevent.c:acpi_ev_fixed_event_detect
  - drivers/acpi/acpica/evevent.c:acpi_ev_initialize_events
  - drivers/acpi/acpica/evglock.c:acpi_ev_release_global_lock
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep
  - drivers/acpi/processor_idle.c:acpi_processor_get_power_info
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
```
**Symbols:**

```
ffffffff8161097b-ffffffff81610b1b: acpi_write_bit_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
acpi_status acpi_write_bit_register(u32 register_id, u32 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwxface.c (ffffffff816bce48)
Location: drivers/acpi/acpica/hwxface.c:214
Inline: False
Direct callers:
  - drivers/acpi/sleep.c:acpi_restore_bm_rld
  - drivers/acpi/sleep.c:acpi_suspend_enter
  - drivers/acpi/acpica/evevent.c:acpi_ev_fixed_event_detect
  - drivers/acpi/acpica/evevent.c:acpi_ev_fixed_event_detect
  - drivers/acpi/acpica/evevent.c:acpi_ev_initialize_events
  - drivers/acpi/acpica/evglock.c:acpi_ev_release_global_lock
  - drivers/acpi/acpica/evxfevnt.c:acpi_clear_event
  - drivers/acpi/acpica/evxfevnt.c:acpi_disable_event
  - drivers/acpi/acpica/evxfevnt.c:acpi_enable_event
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
  - drivers/acpi/processor_idle.c:acpi_idle_bm_check
  - drivers/acpi/processor_idle.c:acpi_processor_power_verify_c3
```
**Symbols:**

```
ffffffff816bce48-ffffffff816bcfe8: acpi_write_bit_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
acpi_status acpi_write_bit_register(u32 register_id, u32 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwxface.c (ffffffff816da9ea)
Location: drivers/acpi/acpica/hwxface.c:214
Inline: False
Direct callers:
  - drivers/acpi/sleep.c:acpi_restore_bm_rld
  - drivers/acpi/sleep.c:acpi_suspend_enter
  - drivers/acpi/acpica/evevent.c:acpi_ev_fixed_event_detect
  - drivers/acpi/acpica/evevent.c:acpi_ev_fixed_event_detect
  - drivers/acpi/acpica/evevent.c:acpi_ev_initialize_events
  - drivers/acpi/acpica/evglock.c:acpi_ev_release_global_lock
  - drivers/acpi/acpica/evxfevnt.c:acpi_clear_event
  - drivers/acpi/acpica/evxfevnt.c:acpi_disable_event
  - drivers/acpi/acpica/evxfevnt.c:acpi_enable_event
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
  - drivers/acpi/processor_idle.c:acpi_idle_bm_check
  - drivers/acpi/processor_idle.c:acpi_processor_power_verify_c3
```
**Symbols:**

```
ffffffff816da9ea-ffffffff816dab8a: acpi_write_bit_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
acpi_status acpi_write_bit_register(u32 register_id, u32 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwxface.c (ffffffff816bc987)
Location: drivers/acpi/acpica/hwxface.c:214
Inline: False
Direct callers:
  - drivers/acpi/sleep.c:acpi_restore_bm_rld
  - drivers/acpi/sleep.c:acpi_suspend_enter
  - drivers/acpi/acpica/evevent.c:acpi_ev_fixed_event_detect
  - drivers/acpi/acpica/evevent.c:acpi_ev_fixed_event_detect
  - drivers/acpi/acpica/evevent.c:acpi_ev_initialize_events
  - drivers/acpi/acpica/evglock.c:acpi_ev_release_global_lock
  - drivers/acpi/acpica/evxfevnt.c:acpi_clear_event
  - drivers/acpi/acpica/evxfevnt.c:acpi_disable_event
  - drivers/acpi/acpica/evxfevnt.c:acpi_enable_event
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
  - drivers/acpi/processor_idle.c:acpi_processor_power_verify_c3
```
**Symbols:**

```
ffffffff816bc987-ffffffff816bcb27: acpi_write_bit_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
acpi_status acpi_write_bit_register(u32 register_id, u32 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwxface.c (ffffffff81733bc6)
Location: drivers/acpi/acpica/hwxface.c:214
Inline: False
Direct callers:
  - drivers/acpi/sleep.c:acpi_restore_bm_rld
  - drivers/acpi/sleep.c:acpi_suspend_enter
  - drivers/acpi/acpica/evevent.c:acpi_ev_fixed_event_detect
  - drivers/acpi/acpica/evevent.c:acpi_ev_fixed_event_detect
  - drivers/acpi/acpica/evevent.c:acpi_ev_initialize_events
  - drivers/acpi/acpica/evglock.c:acpi_ev_release_global_lock
  - drivers/acpi/acpica/evxfevnt.c:acpi_clear_event
  - drivers/acpi/acpica/evxfevnt.c:acpi_disable_event
  - drivers/acpi/acpica/evxfevnt.c:acpi_enable_event
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
  - drivers/acpi/processor_idle.c:acpi_processor_power_verify_c3
```
**Symbols:**

```
ffffffff81733bc6-ffffffff81733d9a: acpi_write_bit_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
acpi_status acpi_write_bit_register(u32 register_id, u32 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwxface.c (ffffffff81864b38)
Location: drivers/acpi/acpica/hwxface.c:214
Inline: False
Direct callers:
  - drivers/acpi/sleep.c:acpi_restore_bm_rld
  - drivers/acpi/sleep.c:acpi_suspend_enter
  - drivers/acpi/acpica/evevent.c:acpi_ev_fixed_event_detect
  - drivers/acpi/acpica/evevent.c:acpi_ev_fixed_event_detect
  - drivers/acpi/acpica/evevent.c:acpi_ev_initialize_events
  - drivers/acpi/acpica/evglock.c:acpi_ev_release_global_lock
  - drivers/acpi/acpica/evxfevnt.c:acpi_clear_event
  - drivers/acpi/acpica/evxfevnt.c:acpi_disable_event
  - drivers/acpi/acpica/evxfevnt.c:acpi_enable_event
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep
  - drivers/acpi/acpica/hwxfsleep.c:acpi_enter_sleep_state_s4bios
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
  - drivers/acpi/processor_idle.c:acpi_processor_power_verify_c3
```
**Symbols:**

```
ffffffff81864b38-ffffffff81864d24: acpi_write_bit_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
acpi_status acpi_write_bit_register(u32 register_id, u32 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpica/hwxface.c (0)
Location: drivers/acpi/acpica/hwxface.c:214
Inline: False
Direct callers:
  - drivers/acpi/sleep.c:acpi_restore_bm_rld
  - drivers/acpi/sleep.c:acpi_suspend_enter
  - drivers/acpi/acpica/evevent.c:acpi_ev_fixed_event_detect
  - drivers/acpi/acpica/evevent.c:acpi_ev_fixed_event_detect
  - drivers/acpi/acpica/evevent.c:acpi_ev_initialize_events
  - drivers/acpi/acpica/evglock.c:acpi_ev_release_global_lock
  - drivers/acpi/acpica/evxfevnt.c:acpi_clear_event
  - drivers/acpi/acpica/evxfevnt.c:acpi_disable_event
  - drivers/acpi/acpica/evxfevnt.c:acpi_enable_event
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep
  - drivers/acpi/acpica/hwxfsleep.c:acpi_enter_sleep_state_s4bios
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
  - drivers/acpi/processor_idle.c:acpi_processor_power_verify_c3
```
**Symbols:**

```
ffffffff820922c2-ffffffff82092304: acpi_write_bit_register.cold (STB_LOCAL)
ffffffff819a2af0-ffffffff819a2cdd: acpi_write_bit_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
acpi_status acpi_write_bit_register(u32 register_id, u32 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpica/hwxface.c (0)
Location: drivers/acpi/acpica/hwxface.c:214
Inline: False
Direct callers:
  - drivers/acpi/sleep.c:acpi_restore_bm_rld
  - drivers/acpi/sleep.c:acpi_suspend_enter
  - drivers/acpi/acpica/evevent.c:acpi_ev_fixed_event_detect
  - drivers/acpi/acpica/evevent.c:acpi_ev_fixed_event_detect
  - drivers/acpi/acpica/evevent.c:acpi_ev_initialize_events
  - drivers/acpi/acpica/evglock.c:acpi_ev_release_global_lock
  - drivers/acpi/acpica/evxfevnt.c:acpi_clear_event
  - drivers/acpi/acpica/evxfevnt.c:acpi_disable_event
  - drivers/acpi/acpica/evxfevnt.c:acpi_enable_event
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep
  - drivers/acpi/acpica/hwxfsleep.c:acpi_enter_sleep_state_s4bios
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
  - drivers/acpi/processor_idle.c:acpi_processor_power_verify_c3
```
**Symbols:**

```
ffffffff82112bb6-ffffffff82112bfb: acpi_write_bit_register.cold (STB_LOCAL)
ffffffff819e97a0-ffffffff819e998c: acpi_write_bit_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
acpi_status acpi_write_bit_register(u32 register_id, u32 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpica/hwxface.c (0)
Location: drivers/acpi/acpica/hwxface.c:214
Inline: False
Direct callers:
  - drivers/acpi/sleep.c:acpi_restore_bm_rld
  - drivers/acpi/sleep.c:acpi_suspend_enter
  - drivers/acpi/acpica/evevent.c:acpi_ev_fixed_event_detect
  - drivers/acpi/acpica/evevent.c:acpi_ev_fixed_event_detect
  - drivers/acpi/acpica/evevent.c:acpi_ev_initialize_events
  - drivers/acpi/acpica/evglock.c:acpi_ev_release_global_lock
  - drivers/acpi/acpica/evxfevnt.c:acpi_clear_event
  - drivers/acpi/acpica/evxfevnt.c:acpi_disable_event
  - drivers/acpi/acpica/evxfevnt.c:acpi_enable_event
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep
  - drivers/acpi/acpica/hwxfsleep.c:acpi_enter_sleep_state_s4bios
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
  - drivers/acpi/processor_idle.c:acpi_processor_power_verify_c3
```
**Symbols:**

```
ffffffff821f090a-ffffffff821f094f: acpi_write_bit_register.cold (STB_LOCAL)
ffffffff81a344f0-ffffffff81a346dc: acpi_write_bit_register (STB_GLOBAL)
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
acpi_status acpi_write_bit_register(u32 register_id, u32 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwxface.c (ffffffff815f17fe)
Location: drivers/acpi/acpica/hwxface.c:214
Inline: False
Direct callers:
  - drivers/acpi/sleep.c:acpi_restore_bm_rld
  - drivers/acpi/acpica/evevent.c:acpi_ev_fixed_event_detect
  - drivers/acpi/acpica/evevent.c:acpi_ev_fixed_event_detect
  - drivers/acpi/acpica/evevent.c:acpi_ev_initialize_events
  - drivers/acpi/acpica/evglock.c:acpi_ev_release_global_lock
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep
  - drivers/acpi/processor_idle.c:acpi_processor_get_power_info
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
```
**Symbols:**

```
ffffffff815f17fe-ffffffff815f18ce: acpi_write_bit_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
acpi_status acpi_write_bit_register(u32 register_id, u32 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwxface.c (ffffffff815dcda5)
Location: drivers/acpi/acpica/hwxface.c:214
Inline: False
Direct callers:
  - drivers/acpi/sleep.c:acpi_restore_bm_rld
  - drivers/acpi/sleep.c:acpi_suspend_enter
  - drivers/acpi/acpica/evevent.c:acpi_ev_fixed_event_detect
  - drivers/acpi/acpica/evevent.c:acpi_ev_fixed_event_detect
  - drivers/acpi/acpica/evevent.c:acpi_ev_initialize_events
  - drivers/acpi/acpica/evglock.c:acpi_ev_release_global_lock
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep
  - drivers/acpi/processor_idle.c:acpi_processor_get_power_info
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
```
**Symbols:**

```
ffffffff815dcda5-ffffffff815dce75: acpi_write_bit_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
acpi_status acpi_write_bit_register(u32 register_id, u32 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwxface.c (ffffffff81604c5b)
Location: drivers/acpi/acpica/hwxface.c:214
Inline: False
Direct callers:
  - drivers/acpi/sleep.c:acpi_restore_bm_rld
  - drivers/acpi/sleep.c:acpi_suspend_enter
  - drivers/acpi/acpica/evevent.c:acpi_ev_fixed_event_detect
  - drivers/acpi/acpica/evevent.c:acpi_ev_fixed_event_detect
  - drivers/acpi/acpica/evevent.c:acpi_ev_initialize_events
  - drivers/acpi/acpica/evglock.c:acpi_ev_release_global_lock
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep
  - drivers/acpi/processor_idle.c:acpi_processor_get_power_info
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
```
**Symbols:**

```
ffffffff81604c5b-ffffffff81604dfb: acpi_write_bit_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
acpi_status acpi_write_bit_register(u32 register_id, u32 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwxface.c (ffffffff8161eb0b)
Location: drivers/acpi/acpica/hwxface.c:214
Inline: False
Direct callers:
  - drivers/acpi/sleep.c:acpi_restore_bm_rld
  - drivers/acpi/sleep.c:acpi_suspend_enter
  - drivers/acpi/acpica/evevent.c:acpi_ev_fixed_event_detect
  - drivers/acpi/acpica/evevent.c:acpi_ev_fixed_event_detect
  - drivers/acpi/acpica/evevent.c:acpi_ev_initialize_events
  - drivers/acpi/acpica/evglock.c:acpi_ev_release_global_lock
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep
  - drivers/acpi/processor_idle.c:acpi_processor_get_power_info
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
```
**Symbols:**

```
ffffffff8161eb0b-ffffffff8161ecab: acpi_write_bit_register (STB_GLOBAL)
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
