# Function: <code>acpi_os_prepare_sleep</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
acpi_status acpi_os_prepare_sleep(u8 sleep_state, u32 pm1a_control, u32 pm1b_control);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff8147a6e4)
Location: drivers/acpi/osl.c:1880
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep
```
**Symbols:**

```
ffffffff8147a6e4-ffffffff8147a71a: acpi_os_prepare_sleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
acpi_status acpi_os_prepare_sleep(u8 sleep_state, u32 pm1a_control, u32 pm1b_control);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff814c8cb2)
Location: drivers/acpi/osl.c:1685
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep
```
**Symbols:**

```
ffffffff814c8cb2-ffffffff814c8ce8: acpi_os_prepare_sleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
acpi_status acpi_os_prepare_sleep(u8 sleep_state, u32 pm1a_control, u32 pm1b_control);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff814eabf6)
Location: drivers/acpi/osl.c:1680
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep
```
**Symbols:**

```
ffffffff814eabf6-ffffffff814eac2c: acpi_os_prepare_sleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_os_prepare_sleep(u8 sleep_state, u32 pm1a_control, u32 pm1b_control);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff814f6b4e)
Location: drivers/acpi/osl.c:1679
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_enter_sleep
```
**Symbols:**

```
ffffffff814f6ac0-ffffffff814f6af6: acpi_os_prepare_sleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_os_prepare_sleep(u8 sleep_state, u32 pm1a_control, u32 pm1b_control);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff81537b9e)
Location: drivers/acpi/osl.c:1689
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_enter_sleep
```
**Symbols:**

```
ffffffff81537b10-ffffffff81537b49: acpi_os_prepare_sleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_os_prepare_sleep(u8 sleep_state, u32 pm1a_control, u32 pm1b_control);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff8156d731)
Location: drivers/acpi/osl.c:1764
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_enter_sleep
```
**Symbols:**

```
ffffffff8156d6a0-ffffffff8156d6dd: acpi_os_prepare_sleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_os_prepare_sleep(u8 sleep_state, u32 pm1a_control, u32 pm1b_control);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff815852f1)
Location: drivers/acpi/osl.c:1770
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_enter_sleep
```
**Symbols:**

```
ffffffff81585260-ffffffff8158529d: acpi_os_prepare_sleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_os_prepare_sleep(u8 sleep_state, u32 pm1a_control, u32 pm1b_control);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff815b5f51)
Location: drivers/acpi/osl.c:1756
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_enter_sleep
```
**Symbols:**

```
ffffffff815b5eb0-ffffffff815b5eeb: acpi_os_prepare_sleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_os_prepare_sleep(u8 sleep_state, u32 pm1a_control, u32 pm1b_control);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff815d7181)
Location: drivers/acpi/osl.c:1776
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_enter_sleep
```
**Symbols:**

```
ffffffff815d70e0-ffffffff815d711b: acpi_os_prepare_sleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_os_prepare_sleep(u8 sleep_state, u32 pm1a_control, u32 pm1b_control);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff81680ec1)
Location: drivers/acpi/osl.c:1778
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_enter_sleep
```
**Symbols:**

```
ffffffff81680e30-ffffffff81680e6b: acpi_os_prepare_sleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_os_prepare_sleep(u8 sleep_state, u32 pm1a_control, u32 pm1b_control);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff8169f9c1)
Location: drivers/acpi/osl.c:1806
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_enter_sleep
```
**Symbols:**

```
ffffffff8169f930-ffffffff8169f96b: acpi_os_prepare_sleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_os_prepare_sleep(u8 sleep_state, u32 pm1a_control, u32 pm1b_control);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff81682661)
Location: drivers/acpi/osl.c:1795
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_enter_sleep
```
**Symbols:**

```
ffffffff816825d0-ffffffff8168260b: acpi_os_prepare_sleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_os_prepare_sleep(u8 sleep_state, u32 pm1a_control, u32 pm1b_control);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff816f77d1)
Location: drivers/acpi/osl.c:1790
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_enter_sleep
```
**Symbols:**

```
ffffffff816f7740-ffffffff816f777b: acpi_os_prepare_sleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_os_prepare_sleep(u8 sleep_state, u32 pm1a_control, u32 pm1b_control);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff8182477b)
Location: drivers/acpi/osl.c:1707
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_enter_sleep
```
**Symbols:**

```
ffffffff818246b0-ffffffff81824707: acpi_os_prepare_sleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_os_prepare_sleep(u8 sleep_state, u32 pm1a_control, u32 pm1b_control);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff81955c6b)
Location: drivers/acpi/osl.c:1707
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_enter_sleep
```
**Symbols:**

```
ffffffff81955b60-ffffffff81955bb7: acpi_os_prepare_sleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_os_prepare_sleep(u8 sleep_state, u32 pm1a_control, u32 pm1b_control);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff8199c06b)
Location: drivers/acpi/osl.c:1707
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_enter_sleep
```
**Symbols:**

```
ffffffff8199bf60-ffffffff8199bfb7: acpi_os_prepare_sleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_os_prepare_sleep(u8 sleep_state, u32 pm1a_control, u32 pm1b_control);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff819e45bb)
Location: drivers/acpi/osl.c:1700
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_enter_sleep
```
**Symbols:**

```
ffffffff819e44b0-ffffffff819e4507: acpi_os_prepare_sleep (STB_GLOBAL)
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
acpi_status acpi_os_prepare_sleep(u8 sleep_state, u32 pm1a_control, u32 pm1b_control);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffff800010764798)
Location: drivers/acpi/osl.c:1776
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_enter_sleep
```
**Symbols:**

```
ffff8000107645c8-ffff800010764644: acpi_os_prepare_sleep (STB_GLOBAL)
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
acpi_status acpi_os_prepare_sleep(u8 sleep_state, u32 pm1a_control, u32 pm1b_control);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff815ca6b1)
Location: drivers/acpi/osl.c:1776
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_enter_sleep
```
**Symbols:**

```
ffffffff815ca610-ffffffff815ca64b: acpi_os_prepare_sleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_os_prepare_sleep(u8 sleep_state, u32 pm1a_control, u32 pm1b_control);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff815b3731)
Location: drivers/acpi/osl.c:1776
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_enter_sleep
```
**Symbols:**

```
ffffffff815b3690-ffffffff815b36cb: acpi_os_prepare_sleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_os_prepare_sleep(u8 sleep_state, u32 pm1a_control, u32 pm1b_control);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff815cb461)
Location: drivers/acpi/osl.c:1776
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_enter_sleep
```
**Symbols:**

```
ffffffff815cb3c0-ffffffff815cb3fb: acpi_os_prepare_sleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_os_prepare_sleep(u8 sleep_state, u32 pm1a_control, u32 pm1b_control);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff815e5301)
Location: drivers/acpi/osl.c:1776
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_enter_sleep
```
**Symbols:**

```
ffffffff815e5260-ffffffff815e529b: acpi_os_prepare_sleep (STB_GLOBAL)
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
