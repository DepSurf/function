# Function: <code>acpi_write</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
acpi_status acpi_write(u64 value, struct acpi_generic_address *reg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwxface.c (ffffffff8149b499)
Location: drivers/acpi/acpica/hwxface.c:215
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_wake_prep
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_wake
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target
  - drivers/mailbox/pcc.c:pcc_send_data
```
**Symbols:**

```
ffffffff8149b499-ffffffff8149b540: acpi_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
acpi_status acpi_write(u64 value, struct acpi_generic_address *reg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwxface.c (ffffffff814ea515)
Location: drivers/acpi/acpica/hwxface.c:214
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_wake
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_wake_prep
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq
  - drivers/mailbox/pcc.c:pcc_send_data
```
**Symbols:**

```
ffffffff814ea515-ffffffff814ea5bc: acpi_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
acpi_status acpi_write(u64 value, struct acpi_generic_address *reg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwxface.c (ffffffff8150cd9d)
Location: drivers/acpi/acpica/hwxface.c:214
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_wake
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_wake_prep
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq
  - drivers/mailbox/pcc.c:pcc_send_data
```
**Symbols:**

```
ffffffff8150cd9d-ffffffff8150ce44: acpi_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
acpi_status acpi_write(u64 value, struct acpi_generic_address *reg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwxface.c (ffffffff8151d555)
Location: drivers/acpi/acpica/hwxface.c:214
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_wake
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_wake_prep
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq
  - drivers/mailbox/pcc.c:pcc_send_data
```
**Symbols:**

```
ffffffff8151d555-ffffffff8151d5fb: acpi_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
acpi_status acpi_write(u64 value, struct acpi_generic_address *reg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwxface.c (ffffffff8156e0cf)
Location: drivers/acpi/acpica/hwxface.c:150
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_wake
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_wake_prep
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq
  - drivers/mailbox/pcc.c:pcc_send_data
```
**Symbols:**

```
ffffffff8156e0cf-ffffffff8156e0df: acpi_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
acpi_status acpi_write(u64 value, struct acpi_generic_address *reg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwxface.c (ffffffff815a4dae)
Location: drivers/acpi/acpica/hwxface.c:116
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_wake
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_wake_prep
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq
  - drivers/mailbox/pcc.c:pcc_send_data
```
**Symbols:**

```
ffffffff815a4dae-ffffffff815a4dbe: acpi_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
acpi_status acpi_write(u64 value, struct acpi_generic_address *reg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwxface.c (ffffffff815bd76e)
Location: drivers/acpi/acpica/hwxface.c:116
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_wake
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_wake_prep
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq
  - drivers/mailbox/pcc.c:pcc_send_data
```
**Symbols:**

```
ffffffff815bd76e-ffffffff815bd77e: acpi_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
acpi_status acpi_write(u64 value, struct acpi_generic_address *reg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwxface.c (ffffffff815ef370)
Location: drivers/acpi/acpica/hwxface.c:116
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_wake
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_wake_prep
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq
  - drivers/mailbox/pcc.c:pcc_send_data
```
**Symbols:**

```
ffffffff815ef370-ffffffff815ef380: acpi_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
acpi_status acpi_write(u64 value, struct acpi_generic_address *reg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwxface.c (ffffffff816107fe)
Location: drivers/acpi/acpica/hwxface.c:116
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_wake
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_wake_prep
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq
  - drivers/mailbox/pcc.c:pcc_send_data
```
**Symbols:**

```
ffffffff816107fe-ffffffff8161080e: acpi_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
acpi_status acpi_write(u64 value, struct acpi_generic_address *reg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwxface.c (ffffffff816bcccb)
Location: drivers/acpi/acpica/hwxface.c:116
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_wake
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_wake_prep
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq
  - drivers/mailbox/pcc.c:pcc_send_data
```
**Symbols:**

```
ffffffff816bcccb-ffffffff816bccdb: acpi_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
acpi_status acpi_write(u64 value, struct acpi_generic_address *reg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwxface.c (ffffffff816da86d)
Location: drivers/acpi/acpica/hwxface.c:116
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_wake
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_wake_prep
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq
  - drivers/mailbox/pcc.c:pcc_send_data
```
**Symbols:**

```
ffffffff816da86d-ffffffff816da87d: acpi_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
acpi_status acpi_write(u64 value, struct acpi_generic_address *reg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwxface.c (ffffffff816bc80a)
Location: drivers/acpi/acpica/hwxface.c:116
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_wake
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_wake_prep
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq
  - drivers/mailbox/pcc.c:pcc_send_data
```
**Symbols:**

```
ffffffff816bc80a-ffffffff816bc81a: acpi_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
acpi_status acpi_write(u64 value, struct acpi_generic_address *reg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwxface.c (ffffffff81733a2b)
Location: drivers/acpi/acpica/hwxface.c:116
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_wake
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_wake_prep
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq
  - drivers/mailbox/pcc.c:pcc_send_data
```
**Symbols:**

```
ffffffff81733a2b-ffffffff81733a3b: acpi_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
acpi_status acpi_write(u64 value, struct acpi_generic_address *reg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwxface.c (ffffffff81864976)
Location: drivers/acpi/acpica/hwxface.c:116
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_wake
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_wake_prep
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq
```
**Symbols:**

```
ffffffff81864976-ffffffff8186498e: acpi_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
acpi_status acpi_write(u64 value, struct acpi_generic_address *reg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwxface.c (ffffffff819a28e0)
Location: drivers/acpi/acpica/hwxface.c:116
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_wake
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_wake_prep
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq
```
**Symbols:**

```
ffffffff819a28e0-ffffffff819a28f8: acpi_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
acpi_status acpi_write(u64 value, struct acpi_generic_address *reg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwxface.c (ffffffff819e9590)
Location: drivers/acpi/acpica/hwxface.c:116
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_wake
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_wake_prep
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq
```
**Symbols:**

```
ffffffff819e9590-ffffffff819e95a8: acpi_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
acpi_status acpi_write(u64 value, struct acpi_generic_address *reg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwxface.c (ffffffff81a342e0)
Location: drivers/acpi/acpica/hwxface.c:116
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_wake
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_wake_prep
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq
```
**Symbols:**

```
ffffffff81a342e0-ffffffff81a342f8: acpi_write (STB_GLOBAL)
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
acpi_status acpi_write(u64 value, struct acpi_generic_address *reg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwxface.c (ffff80001078b3e0)
Location: drivers/acpi/acpica/hwxface.c:116
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_wake
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_wake_prep
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep
  - drivers/mailbox/pcc.c:pcc_send_data
```
**Symbols:**

```
ffff80001078b3e0-ffff80001078b414: acpi_write (STB_GLOBAL)
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
acpi_status acpi_write(u64 value, struct acpi_generic_address *reg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwxface.c (ffffffff815f176e)
Location: drivers/acpi/acpica/hwxface.c:116
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_wake
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_wake_prep
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep
  - drivers/mailbox/pcc.c:pcc_send_data
```
**Symbols:**

```
ffffffff815f176e-ffffffff815f177e: acpi_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
acpi_status acpi_write(u64 value, struct acpi_generic_address *reg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwxface.c (ffffffff815dcd15)
Location: drivers/acpi/acpica/hwxface.c:116
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_wake
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_wake_prep
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq
  - drivers/mailbox/pcc.c:pcc_send_data
```
**Symbols:**

```
ffffffff815dcd15-ffffffff815dcd25: acpi_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
acpi_status acpi_write(u64 value, struct acpi_generic_address *reg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwxface.c (ffffffff81604ade)
Location: drivers/acpi/acpica/hwxface.c:116
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_wake
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_wake_prep
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq
  - drivers/mailbox/pcc.c:pcc_send_data
```
**Symbols:**

```
ffffffff81604ade-ffffffff81604aee: acpi_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
acpi_status acpi_write(u64 value, struct acpi_generic_address *reg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwxface.c (ffffffff8161e98e)
Location: drivers/acpi/acpica/hwxface.c:116
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_wake
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_wake_prep
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq
  - drivers/mailbox/pcc.c:pcc_send_data
```
**Symbols:**

```
ffffffff8161e98e-ffffffff8161e99e: acpi_write (STB_GLOBAL)
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
