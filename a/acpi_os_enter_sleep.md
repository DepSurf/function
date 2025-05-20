# Function: <code>acpi_os_enter_sleep</code>

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
acpi_status acpi_os_enter_sleep(u8 sleep_state, u32 reg_a_value, u32 reg_b_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff814f6b40)
Location: drivers/acpi/osl.c:1729
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep
```
**Symbols:**

```
ffffffff814f6b40-ffffffff814f6b7d: acpi_os_enter_sleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
acpi_status acpi_os_enter_sleep(u8 sleep_state, u32 reg_a_value, u32 reg_b_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff81537b90)
Location: drivers/acpi/osl.c:1739
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep
```
**Symbols:**

```
ffffffff81537b90-ffffffff81537bd0: acpi_os_enter_sleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
acpi_status acpi_os_enter_sleep(u8 sleep_state, u32 reg_a_value, u32 reg_b_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff8156d720)
Location: drivers/acpi/osl.c:1814
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep
```
**Symbols:**

```
ffffffff8156d720-ffffffff8156d762: acpi_os_enter_sleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
acpi_status acpi_os_enter_sleep(u8 sleep_state, u32 reg_a_value, u32 reg_b_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff815852e0)
Location: drivers/acpi/osl.c:1820
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep
```
**Symbols:**

```
ffffffff815852e0-ffffffff81585322: acpi_os_enter_sleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
acpi_status acpi_os_enter_sleep(u8 sleep_state, u32 reg_a_value, u32 reg_b_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff815b5f40)
Location: drivers/acpi/osl.c:1806
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep
```
**Symbols:**

```
ffffffff815b5f40-ffffffff815b5f84: acpi_os_enter_sleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
acpi_status acpi_os_enter_sleep(u8 sleep_state, u32 reg_a_value, u32 reg_b_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff815d7170)
Location: drivers/acpi/osl.c:1826
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep
```
**Symbols:**

```
ffffffff815d7170-ffffffff815d71b4: acpi_os_enter_sleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
acpi_status acpi_os_enter_sleep(u8 sleep_state, u32 reg_a_value, u32 reg_b_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff81680eb0)
Location: drivers/acpi/osl.c:1828
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep
```
**Symbols:**

```
ffffffff81680eb0-ffffffff81680ef4: acpi_os_enter_sleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
acpi_status acpi_os_enter_sleep(u8 sleep_state, u32 reg_a_value, u32 reg_b_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff8169f9b0)
Location: drivers/acpi/osl.c:1856
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep
```
**Symbols:**

```
ffffffff8169f9b0-ffffffff8169f9f4: acpi_os_enter_sleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
acpi_status acpi_os_enter_sleep(u8 sleep_state, u32 reg_a_value, u32 reg_b_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff81682650)
Location: drivers/acpi/osl.c:1845
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep
```
**Symbols:**

```
ffffffff81682650-ffffffff81682694: acpi_os_enter_sleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
acpi_status acpi_os_enter_sleep(u8 sleep_state, u32 reg_a_value, u32 reg_b_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff816f77c0)
Location: drivers/acpi/osl.c:1840
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep
```
**Symbols:**

```
ffffffff816f77c0-ffffffff816f7804: acpi_os_enter_sleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
acpi_status acpi_os_enter_sleep(u8 sleep_state, u32 reg_a_value, u32 reg_b_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff81824760)
Location: drivers/acpi/osl.c:1757
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep
```
**Symbols:**

```
ffffffff81824760-ffffffff818247c0: acpi_os_enter_sleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
acpi_status acpi_os_enter_sleep(u8 sleep_state, u32 reg_a_value, u32 reg_b_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff81955c50)
Location: drivers/acpi/osl.c:1757
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep
```
**Symbols:**

```
ffffffff81955c50-ffffffff81955cb0: acpi_os_enter_sleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
acpi_status acpi_os_enter_sleep(u8 sleep_state, u32 reg_a_value, u32 reg_b_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff8199c050)
Location: drivers/acpi/osl.c:1757
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep
```
**Symbols:**

```
ffffffff8199c050-ffffffff8199c0b0: acpi_os_enter_sleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
acpi_status acpi_os_enter_sleep(u8 sleep_state, u32 reg_a_value, u32 reg_b_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff819e45a0)
Location: drivers/acpi/osl.c:1752
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep
```
**Symbols:**

```
ffffffff819e45a0-ffffffff819e4600: acpi_os_enter_sleep (STB_GLOBAL)
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
acpi_status acpi_os_enter_sleep(u8 sleep_state, u32 reg_a_value, u32 reg_b_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffff800010764728)
Location: drivers/acpi/osl.c:1826
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep
```
**Symbols:**

```
ffff800010764728-ffff8000107647d0: acpi_os_enter_sleep (STB_GLOBAL)
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
acpi_status acpi_os_enter_sleep(u8 sleep_state, u32 reg_a_value, u32 reg_b_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff815ca6a0)
Location: drivers/acpi/osl.c:1826
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep
```
**Symbols:**

```
ffffffff815ca6a0-ffffffff815ca6e4: acpi_os_enter_sleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
acpi_status acpi_os_enter_sleep(u8 sleep_state, u32 reg_a_value, u32 reg_b_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff815b3720)
Location: drivers/acpi/osl.c:1826
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep
```
**Symbols:**

```
ffffffff815b3720-ffffffff815b3764: acpi_os_enter_sleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
acpi_status acpi_os_enter_sleep(u8 sleep_state, u32 reg_a_value, u32 reg_b_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff815cb450)
Location: drivers/acpi/osl.c:1826
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep
```
**Symbols:**

```
ffffffff815cb450-ffffffff815cb494: acpi_os_enter_sleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
acpi_status acpi_os_enter_sleep(u8 sleep_state, u32 reg_a_value, u32 reg_b_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff815e52f0)
Location: drivers/acpi/osl.c:1826
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep
```
**Symbols:**

```
ffffffff815e52f0-ffffffff815e5334: acpi_os_enter_sleep (STB_GLOBAL)
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
