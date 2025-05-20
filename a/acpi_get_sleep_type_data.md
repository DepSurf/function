# Function: <code>acpi_get_sleep_type_data</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_get_sleep_type_data(u8 sleep_state, u8 *sleep_type_a, u8 *sleep_type_b);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwxface.c (ffffffff8149b7b6)
Location: drivers/acpi/acpica/hwxface.c:482
Inline: True
Direct callers:
  - drivers/acpi/sleep.c:acpi_sleep_state_supported
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_wake_prep
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake_prep
```
**Symbols:**

```
ffffffff8149b7b6-ffffffff8149b94a: acpi_get_sleep_type_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_get_sleep_type_data(u8 sleep_state, u8 *sleep_type_a, u8 *sleep_type_b);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwxface.c (ffffffff814ea842)
Location: drivers/acpi/acpica/hwxface.c:481
Inline: True
Direct callers:
  - drivers/acpi/sleep.c:acpi_sleep_state_supported
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_wake_prep
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake_prep
```
**Symbols:**

```
ffffffff814ea842-ffffffff814ea9de: acpi_get_sleep_type_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_get_sleep_type_data(u8 sleep_state, u8 *sleep_type_a, u8 *sleep_type_b);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwxface.c (ffffffff8150d0ca)
Location: drivers/acpi/acpica/hwxface.c:481
Inline: True
Direct callers:
  - drivers/acpi/sleep.c:acpi_sleep_state_supported
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_wake_prep
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake_prep
```
**Symbols:**

```
ffffffff8150d0ca-ffffffff8150d266: acpi_get_sleep_type_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_get_sleep_type_data(u8 sleep_state, u8 *sleep_type_a, u8 *sleep_type_b);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwxface.c (ffffffff8151d79d)
Location: drivers/acpi/acpica/hwxface.c:481
Inline: True
Direct callers:
  - drivers/acpi/sleep.c:acpi_sleep_state_supported
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_wake_prep
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake_prep
```
**Symbols:**

```
ffffffff8151d79d-ffffffff8151d939: acpi_get_sleep_type_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_get_sleep_type_data(u8 sleep_state, u8 *sleep_type_a, u8 *sleep_type_b);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwxface.c (ffffffff8156e4a7)
Location: drivers/acpi/acpica/hwxface.c:369
Inline: True
Direct callers:
  - drivers/acpi/sleep.c:acpi_sleep_state_supported
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_wake_prep
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake_prep
  - drivers/acpi/acpica/dbcmds.c:acpi_db_do_one_sleep_state
```
**Symbols:**

```
ffffffff8156e4a7-ffffffff8156e6bc: acpi_get_sleep_type_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
acpi_status acpi_get_sleep_type_data(u8 sleep_state, u8 *sleep_type_a, u8 *sleep_type_b);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwxface.c (ffffffff815a5187)
Location: drivers/acpi/acpica/hwxface.c:335
Inline: False
Direct callers:
  - drivers/acpi/sleep.c:acpi_sleep_state_supported
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_wake_prep
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake_prep
  - drivers/acpi/acpica/dbcmds.c:acpi_db_do_one_sleep_state
```
**Symbols:**

```
ffffffff815a5187-ffffffff815a539c: acpi_get_sleep_type_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
acpi_status acpi_get_sleep_type_data(u8 sleep_state, u8 *sleep_type_a, u8 *sleep_type_b);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwxface.c (ffffffff815bdb43)
Location: drivers/acpi/acpica/hwxface.c:335
Inline: False
Direct callers:
  - drivers/acpi/sleep.c:acpi_sleep_state_supported
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_wake_prep
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake_prep
  - drivers/acpi/acpica/dbcmds.c:acpi_db_do_one_sleep_state
```
**Symbols:**

```
ffffffff815bdb43-ffffffff815bdd58: acpi_get_sleep_type_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
acpi_status acpi_get_sleep_type_data(u8 sleep_state, u8 *sleep_type_a, u8 *sleep_type_b);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwxface.c (ffffffff815ef747)
Location: drivers/acpi/acpica/hwxface.c:335
Inline: False
Direct callers:
  - drivers/acpi/sleep.c:acpi_sleep_state_supported
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_wake_prep
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake_prep
  - drivers/acpi/acpica/dbcmds.c:acpi_db_do_one_sleep_state
```
**Symbols:**

```
ffffffff815ef747-ffffffff815ef961: acpi_get_sleep_type_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
acpi_status acpi_get_sleep_type_data(u8 sleep_state, u8 *sleep_type_a, u8 *sleep_type_b);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwxface.c (ffffffff81610bd5)
Location: drivers/acpi/acpica/hwxface.c:335
Inline: False
Direct callers:
  - drivers/acpi/sleep.c:acpi_sleep_state_supported
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_wake_prep
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake_prep
  - drivers/acpi/acpica/dbcmds.c:acpi_db_do_one_sleep_state
```
**Symbols:**

```
ffffffff81610bd5-ffffffff81610def: acpi_get_sleep_type_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
acpi_status acpi_get_sleep_type_data(u8 sleep_state, u8 *sleep_type_a, u8 *sleep_type_b);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwxface.c (ffffffff816bcfe8)
Location: drivers/acpi/acpica/hwxface.c:335
Inline: False
Direct callers:
  - drivers/acpi/sleep.c:acpi_sleep_state_supported
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_wake_prep
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake_prep
  - drivers/acpi/acpica/dbcmds.c:acpi_db_do_one_sleep_state
```
**Symbols:**

```
ffffffff816bcfe8-ffffffff816bd202: acpi_get_sleep_type_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
acpi_status acpi_get_sleep_type_data(u8 sleep_state, u8 *sleep_type_a, u8 *sleep_type_b);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwxface.c (ffffffff816dab8a)
Location: drivers/acpi/acpica/hwxface.c:335
Inline: False
Direct callers:
  - drivers/acpi/sleep.c:acpi_sleep_state_supported
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_wake_prep
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake_prep
  - drivers/acpi/acpica/dbcmds.c:acpi_db_do_one_sleep_state
```
**Symbols:**

```
ffffffff816dab8a-ffffffff816dada4: acpi_get_sleep_type_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
acpi_status acpi_get_sleep_type_data(u8 sleep_state, u8 *sleep_type_a, u8 *sleep_type_b);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwxface.c (ffffffff816bcb27)
Location: drivers/acpi/acpica/hwxface.c:335
Inline: False
Direct callers:
  - drivers/acpi/sleep.c:acpi_sleep_state_supported
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_wake_prep
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake_prep
  - drivers/acpi/acpica/dbcmds.c:acpi_db_do_one_sleep_state
```
**Symbols:**

```
ffffffff816bcb27-ffffffff816bcd40: acpi_get_sleep_type_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
acpi_status acpi_get_sleep_type_data(u8 sleep_state, u8 *sleep_type_a, u8 *sleep_type_b);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwxface.c (ffffffff81733d9a)
Location: drivers/acpi/acpica/hwxface.c:335
Inline: False
Direct callers:
  - drivers/acpi/sleep.c:acpi_sleep_state_supported
  - drivers/acpi/acpica/dbcmds.c:acpi_db_do_one_sleep_state
```
**Symbols:**

```
ffffffff81733d9a-ffffffff81733fcc: acpi_get_sleep_type_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
acpi_status acpi_get_sleep_type_data(u8 sleep_state, u8 *sleep_type_a, u8 *sleep_type_b);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwxface.c (ffffffff81864d24)
Location: drivers/acpi/acpica/hwxface.c:335
Inline: False
Direct callers:
  - drivers/acpi/sleep.c:acpi_sleep_state_supported
  - drivers/acpi/acpica/hwxfsleep.c:acpi_enter_sleep_state_prep
  - drivers/acpi/acpica/hwxfsleep.c:acpi_enter_sleep_state_prep
  - drivers/acpi/acpica/dbcmds.c:acpi_db_do_one_sleep_state
```
**Symbols:**

```
ffffffff81864d24-ffffffff81864f6b: acpi_get_sleep_type_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
acpi_status acpi_get_sleep_type_data(u8 sleep_state, u8 *sleep_type_a, u8 *sleep_type_b);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwxface.c (ffffffff819a2cf0)
Location: drivers/acpi/acpica/hwxface.c:335
Inline: False
Direct callers:
  - drivers/acpi/sleep.c:acpi_sleep_state_supported
  - drivers/acpi/acpica/hwxfsleep.c:acpi_enter_sleep_state_prep
  - drivers/acpi/acpica/hwxfsleep.c:acpi_enter_sleep_state_prep
  - drivers/acpi/acpica/dbcmds.c:acpi_db_do_one_sleep_state
```
**Symbols:**

```
ffffffff819a2cf0-ffffffff819a2f90: acpi_get_sleep_type_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
acpi_status acpi_get_sleep_type_data(u8 sleep_state, u8 *sleep_type_a, u8 *sleep_type_b);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwxface.c (ffffffff819e99a0)
Location: drivers/acpi/acpica/hwxface.c:335
Inline: False
Direct callers:
  - drivers/acpi/sleep.c:acpi_sleep_state_supported
  - drivers/acpi/acpica/hwxfsleep.c:acpi_enter_sleep_state_prep
  - drivers/acpi/acpica/hwxfsleep.c:acpi_enter_sleep_state_prep
  - drivers/acpi/acpica/dbcmds.c:acpi_db_do_one_sleep_state
```
**Symbols:**

```
ffffffff819e99a0-ffffffff819e9c40: acpi_get_sleep_type_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
acpi_status acpi_get_sleep_type_data(u8 sleep_state, u8 *sleep_type_a, u8 *sleep_type_b);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwxface.c (ffffffff81a346f0)
Location: drivers/acpi/acpica/hwxface.c:335
Inline: False
Direct callers:
  - drivers/acpi/sleep.c:acpi_sleep_state_supported
  - drivers/acpi/acpica/hwxfsleep.c:acpi_enter_sleep_state_prep
  - drivers/acpi/acpica/hwxfsleep.c:acpi_enter_sleep_state_prep
  - drivers/acpi/acpica/dbcmds.c:acpi_db_do_one_sleep_state
```
**Symbols:**

```
ffffffff81a346f0-ffffffff81a349b5: acpi_get_sleep_type_data (STB_GLOBAL)
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
acpi_status acpi_get_sleep_type_data(u8 sleep_state, u8 *sleep_type_a, u8 *sleep_type_b);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwxface.c (ffff80001078b4b0)
Location: drivers/acpi/acpica/hwxface.c:335
Inline: True
Direct callers:
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_wake_prep
```
**Symbols:**

```
ffff80001078b4b0-ffff80001078b660: acpi_get_sleep_type_data (STB_GLOBAL)
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
acpi_status acpi_get_sleep_type_data(u8 sleep_state, u8 *sleep_type_a, u8 *sleep_type_b);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwxface.c (ffffffff815f1920)
Location: drivers/acpi/acpica/hwxface.c:335
Inline: True
Direct callers:
  - drivers/acpi/sleep.c:acpi_sleep_state_supported
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_wake_prep
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake_prep
```
**Symbols:**

```
ffffffff815f1920-ffffffff815f1abd: acpi_get_sleep_type_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_get_sleep_type_data(u8 sleep_state, u8 *sleep_type_a, u8 *sleep_type_b);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwxface.c (ffffffff815dcec7)
Location: drivers/acpi/acpica/hwxface.c:335
Inline: True
Direct callers:
  - drivers/acpi/sleep.c:acpi_sleep_state_supported
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_wake_prep
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake_prep
```
**Symbols:**

```
ffffffff815dcec7-ffffffff815dd05f: acpi_get_sleep_type_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
acpi_status acpi_get_sleep_type_data(u8 sleep_state, u8 *sleep_type_a, u8 *sleep_type_b);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwxface.c (ffffffff81604eb5)
Location: drivers/acpi/acpica/hwxface.c:335
Inline: False
Direct callers:
  - drivers/acpi/sleep.c:acpi_sleep_state_supported
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_wake_prep
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake_prep
  - drivers/acpi/acpica/dbcmds.c:acpi_db_do_one_sleep_state
```
**Symbols:**

```
ffffffff81604eb5-ffffffff816050cf: acpi_get_sleep_type_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
acpi_status acpi_get_sleep_type_data(u8 sleep_state, u8 *sleep_type_a, u8 *sleep_type_b);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwxface.c (ffffffff8161ed65)
Location: drivers/acpi/acpica/hwxface.c:335
Inline: False
Direct callers:
  - drivers/acpi/sleep.c:acpi_sleep_state_supported
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_wake_prep
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_wake_prep
  - drivers/acpi/acpica/dbcmds.c:acpi_db_do_one_sleep_state
```
**Symbols:**

```
ffffffff8161ed65-ffffffff8161ef7f: acpi_get_sleep_type_data (STB_GLOBAL)
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
