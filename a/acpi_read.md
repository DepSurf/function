# Function: <code>acpi_read</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_read(u64 *return_value, struct acpi_generic_address *reg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwxface.c (ffffffff8149b6da)
Location: drivers/acpi/acpica/hwxface.c:127
Inline: True
Direct callers:
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target
  - drivers/mailbox/pcc.c:pcc_send_data
```
**Symbols:**

```
ffffffff8149b6da-ffffffff8149b7b6: acpi_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_read(u64 *return_value, struct acpi_generic_address *reg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwxface.c (ffffffff814ea75d)
Location: drivers/acpi/acpica/hwxface.c:126
Inline: True
Direct callers:
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq
  - drivers/mailbox/pcc.c:pcc_send_data
```
**Symbols:**

```
ffffffff814ea75d-ffffffff814ea842: acpi_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_read(u64 *return_value, struct acpi_generic_address *reg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwxface.c (ffffffff8150cfe5)
Location: drivers/acpi/acpica/hwxface.c:126
Inline: True
Direct callers:
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq
  - drivers/mailbox/pcc.c:pcc_send_data
```
**Symbols:**

```
ffffffff8150cfe5-ffffffff8150d0ca: acpi_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
acpi_status acpi_read(u64 *return_value, struct acpi_generic_address *reg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwxface.c (ffffffff8151d471)
Location: drivers/acpi/acpica/hwxface.c:126
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq
  - drivers/mailbox/pcc.c:pcc_send_data
```
**Symbols:**

```
ffffffff8151d471-ffffffff8151d555: acpi_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
acpi_status acpi_read(u64 *return_value, struct acpi_generic_address *reg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwxface.c (ffffffff8156e0df)
Location: drivers/acpi/acpica/hwxface.c:126
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq
  - drivers/mailbox/pcc.c:pcc_send_data
```
**Symbols:**

```
ffffffff8156e0df-ffffffff8156e0ef: acpi_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
acpi_status acpi_read(u64 *return_value, struct acpi_generic_address *reg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwxface.c (ffffffff815a4dbe)
Location: drivers/acpi/acpica/hwxface.c:92
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq
  - drivers/mailbox/pcc.c:pcc_send_data
```
**Symbols:**

```
ffffffff815a4dbe-ffffffff815a4dce: acpi_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
acpi_status acpi_read(u64 *return_value, struct acpi_generic_address *reg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwxface.c (ffffffff815bd77e)
Location: drivers/acpi/acpica/hwxface.c:92
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq
  - drivers/mailbox/pcc.c:pcc_send_data
```
**Symbols:**

```
ffffffff815bd77e-ffffffff815bd78e: acpi_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
acpi_status acpi_read(u64 *return_value, struct acpi_generic_address *reg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwxface.c (ffffffff815ef380)
Location: drivers/acpi/acpica/hwxface.c:92
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq
  - drivers/mailbox/pcc.c:pcc_send_data
```
**Symbols:**

```
ffffffff815ef380-ffffffff815ef390: acpi_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
acpi_status acpi_read(u64 *return_value, struct acpi_generic_address *reg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwxface.c (ffffffff8161080e)
Location: drivers/acpi/acpica/hwxface.c:92
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq
  - drivers/mailbox/pcc.c:pcc_send_data
```
**Symbols:**

```
ffffffff8161080e-ffffffff8161081e: acpi_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
acpi_status acpi_read(u64 *return_value, struct acpi_generic_address *reg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwxface.c (ffffffff816bccdb)
Location: drivers/acpi/acpica/hwxface.c:92
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq
  - drivers/mailbox/pcc.c:pcc_send_data
```
**Symbols:**

```
ffffffff816bccdb-ffffffff816bcceb: acpi_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
acpi_status acpi_read(u64 *return_value, struct acpi_generic_address *reg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwxface.c (ffffffff816da87d)
Location: drivers/acpi/acpica/hwxface.c:92
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq
  - drivers/mailbox/pcc.c:pcc_send_data
```
**Symbols:**

```
ffffffff816da87d-ffffffff816da88d: acpi_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
acpi_status acpi_read(u64 *return_value, struct acpi_generic_address *reg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwxface.c (ffffffff816bc81a)
Location: drivers/acpi/acpica/hwxface.c:92
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq
  - drivers/mailbox/pcc.c:pcc_send_data
```
**Symbols:**

```
ffffffff816bc81a-ffffffff816bc82a: acpi_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
acpi_status acpi_read(u64 *return_value, struct acpi_generic_address *reg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwxface.c (ffffffff81733a3b)
Location: drivers/acpi/acpica/hwxface.c:92
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq
  - drivers/mailbox/pcc.c:pcc_send_data
```
**Symbols:**

```
ffffffff81733a3b-ffffffff81733a4b: acpi_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
acpi_status acpi_read(u64 *return_value, struct acpi_generic_address *reg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwxface.c (ffffffff8186498e)
Location: drivers/acpi/acpica/hwxface.c:92
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq
  - drivers/mailbox/pcc.c:pcc_send_data
```
**Symbols:**

```
ffffffff8186498e-ffffffff818649a6: acpi_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
acpi_status acpi_read(u64 *return_value, struct acpi_generic_address *reg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwxface.c (ffffffff819a2910)
Location: drivers/acpi/acpica/hwxface.c:92
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq
  - drivers/mailbox/pcc.c:pcc_send_data
```
**Symbols:**

```
ffffffff819a2910-ffffffff819a2928: acpi_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
acpi_status acpi_read(u64 *return_value, struct acpi_generic_address *reg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwxface.c (ffffffff819e95c0)
Location: drivers/acpi/acpica/hwxface.c:92
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq
  - drivers/mailbox/pcc.c:pcc_send_data
```
**Symbols:**

```
ffffffff819e95c0-ffffffff819e95d8: acpi_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
acpi_status acpi_read(u64 *return_value, struct acpi_generic_address *reg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwxface.c (ffffffff81a34310)
Location: drivers/acpi/acpica/hwxface.c:92
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq
  - drivers/mailbox/pcc.c:pcc_send_data
```
**Symbols:**

```
ffffffff81a34310-ffffffff81a34328: acpi_read (STB_GLOBAL)
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
acpi_status acpi_read(u64 *return_value, struct acpi_generic_address *reg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwxface.c (ffff80001078b414)
Location: drivers/acpi/acpica/hwxface.c:92
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep
  - drivers/mailbox/pcc.c:pcc_send_data
```
**Symbols:**

```
ffff80001078b414-ffff80001078b448: acpi_read (STB_GLOBAL)
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
acpi_status acpi_read(u64 *return_value, struct acpi_generic_address *reg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwxface.c (ffffffff815f177e)
Location: drivers/acpi/acpica/hwxface.c:92
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep
  - drivers/mailbox/pcc.c:pcc_send_data
```
**Symbols:**

```
ffffffff815f177e-ffffffff815f178e: acpi_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
acpi_status acpi_read(u64 *return_value, struct acpi_generic_address *reg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwxface.c (ffffffff815dcd25)
Location: drivers/acpi/acpica/hwxface.c:92
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq
  - drivers/mailbox/pcc.c:pcc_send_data
```
**Symbols:**

```
ffffffff815dcd25-ffffffff815dcd35: acpi_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
acpi_status acpi_read(u64 *return_value, struct acpi_generic_address *reg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwxface.c (ffffffff81604aee)
Location: drivers/acpi/acpica/hwxface.c:92
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq
  - drivers/mailbox/pcc.c:pcc_send_data
```
**Symbols:**

```
ffffffff81604aee-ffffffff81604afe: acpi_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
acpi_status acpi_read(u64 *return_value, struct acpi_generic_address *reg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwxface.c (ffffffff8161e99e)
Location: drivers/acpi/acpica/hwxface.c:92
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq
  - drivers/mailbox/pcc.c:pcc_send_data
```
**Symbols:**

```
ffffffff8161e99e-ffffffff8161e9ae: acpi_read (STB_GLOBAL)
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
