# Function: <code>acpi_s2idle_wakeup</code>

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
bool acpi_s2idle_wakeup();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/sleep.c (ffffffff814f89f0)
Location: drivers/acpi/sleep.c:838
Inline: False
Direct callers:
  - drivers/acpi/device_pm.c:acpi_pm_wakeup_event
```
**Symbols:**

```
ffffffff814f89f0-ffffffff814f8a02: acpi_s2idle_wakeup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool acpi_s2idle_wakeup();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/sleep.c (ffffffff8153a280)
Location: drivers/acpi/sleep.c:1040
Inline: False
Direct callers:
  - drivers/acpi/device_pm.c:acpi_pm_wakeup_event
```
**Symbols:**

```
ffffffff8153a280-ffffffff8153a292: acpi_s2idle_wakeup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool acpi_s2idle_wakeup();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/sleep.c (ffffffff81570010)
Location: drivers/acpi/sleep.c:1072
Inline: False
Direct callers:
  - drivers/acpi/device_pm.c:acpi_pm_wakeup_event
```
**Symbols:**

```
ffffffff81570010-ffffffff81570022: acpi_s2idle_wakeup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool acpi_s2idle_wakeup();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/sleep.c (ffffffff81587bd0)
Location: drivers/acpi/sleep.c:1078
Inline: False
Direct callers:
  - drivers/acpi/device_pm.c:acpi_pm_wakeup_event
```
**Symbols:**

```
ffffffff81587bd0-ffffffff81587be2: acpi_s2idle_wakeup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool acpi_s2idle_wakeup();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/sleep.c (ffffffff815b88a0)
Location: drivers/acpi/sleep.c:1072
Inline: False
Direct callers:
  - drivers/acpi/device_pm.c:acpi_pm_wakeup_event
```
**Symbols:**

```
ffffffff815b88a0-ffffffff815b88b2: acpi_s2idle_wakeup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool acpi_s2idle_wakeup();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/sleep.c (ffffffff815d9b10)
Location: drivers/acpi/sleep.c:1118
Inline: False
Direct callers:
  - drivers/acpi/device_pm.c:acpi_pm_wakeup_event
```
**Symbols:**

```
ffffffff815d9b10-ffffffff815d9b22: acpi_s2idle_wakeup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool acpi_s2idle_wakeup();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/sleep.c (ffffffff81683d60)
Location: drivers/acpi/sleep.c:1116
Inline: False
Direct callers:
  - drivers/acpi/device_pm.c:acpi_pm_wakeup_event
```
**Symbols:**

```
ffffffff81683d60-ffffffff81683d72: acpi_s2idle_wakeup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool acpi_s2idle_wakeup();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/sleep.c (ffffffff816a1c70)
Location: drivers/acpi/sleep.c:835
Inline: False
Direct callers:
  - drivers/acpi/device_pm.c:acpi_pm_wakeup_event
```
**Symbols:**

```
ffffffff816a1c70-ffffffff816a1c82: acpi_s2idle_wakeup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool acpi_s2idle_wakeup();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/sleep.c (ffffffff81684a60)
Location: drivers/acpi/sleep.c:835
Inline: False
Direct callers:
  - drivers/acpi/device_pm.c:acpi_pm_wakeup_event
```
**Symbols:**

```
ffffffff81684a60-ffffffff81684a72: acpi_s2idle_wakeup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
bool acpi_s2idle_wakeup();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/sleep.c (0)
Location: drivers/acpi/sleep.c:836
Inline: False
Direct callers:
  - drivers/acpi/device_pm.c:acpi_pm_wakeup_event
```
**Symbols:**

```
ffffffff81cef1d6-ffffffff81cef1f6: acpi_s2idle_wakeup.cold (STB_LOCAL)
ffffffff816f9d20-ffffffff816f9d38: acpi_s2idle_wakeup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool acpi_s2idle_wakeup();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/sleep.c (0)
Location: drivers/acpi/sleep.c:853
Inline: False
Direct callers:
  - drivers/acpi/device_pm.c:acpi_pm_wakeup_event
```
**Symbols:**

```
ffffffff81eb6b64-ffffffff81eb6b8e: acpi_s2idle_wakeup.cold (STB_LOCAL)
ffffffff81827060-ffffffff81827082: acpi_s2idle_wakeup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
bool acpi_s2idle_wakeup();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/sleep.c (0)
Location: drivers/acpi/sleep.c:860
Inline: False
Direct callers:
  - drivers/acpi/device_pm.c:acpi_pm_wakeup_event
```
**Symbols:**

```
ffffffff820918a7-ffffffff820918d1: acpi_s2idle_wakeup.cold (STB_LOCAL)
ffffffff81958f30-ffffffff81958f52: acpi_s2idle_wakeup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool acpi_s2idle_wakeup();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/sleep.c (0)
Location: drivers/acpi/sleep.c:874
Inline: False
Direct callers:
  - drivers/acpi/device_pm.c:acpi_pm_wakeup_event
```
**Symbols:**

```
ffffffff8211219d-ffffffff821121c7: acpi_s2idle_wakeup.cold (STB_LOCAL)
ffffffff8199f3a0-ffffffff8199f3c2: acpi_s2idle_wakeup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool acpi_s2idle_wakeup();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/sleep.c (0)
Location: drivers/acpi/sleep.c:874
Inline: False
Direct callers:
  - drivers/acpi/device_pm.c:acpi_pm_wakeup_event
```
**Symbols:**

```
ffffffff821efea1-ffffffff821efecb: acpi_s2idle_wakeup.cold (STB_LOCAL)
ffffffff819e7a40-ffffffff819e7a62: acpi_s2idle_wakeup (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (0)
Location: drivers/acpi/internal.h:215
Inline: True
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
bool acpi_s2idle_wakeup();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/sleep.c (ffffffff815cc320)
Location: drivers/acpi/sleep.c:1118
Inline: False
Direct callers:
  - drivers/acpi/device_pm.c:acpi_pm_wakeup_event
```
**Symbols:**

```
ffffffff815cc320-ffffffff815cc32d: acpi_s2idle_wakeup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool acpi_s2idle_wakeup();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/sleep.c (ffffffff815b5e70)
Location: drivers/acpi/sleep.c:1118
Inline: False
Direct callers:
  - drivers/acpi/device_pm.c:acpi_pm_wakeup_event
```
**Symbols:**

```
ffffffff815b5e70-ffffffff815b5e82: acpi_s2idle_wakeup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool acpi_s2idle_wakeup();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/sleep.c (ffffffff815cddf0)
Location: drivers/acpi/sleep.c:1118
Inline: False
Direct callers:
  - drivers/acpi/device_pm.c:acpi_pm_wakeup_event
```
**Symbols:**

```
ffffffff815cddf0-ffffffff815cde02: acpi_s2idle_wakeup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool acpi_s2idle_wakeup();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/sleep.c (ffffffff815e7cb0)
Location: drivers/acpi/sleep.c:1118
Inline: False
Direct callers:
  - drivers/acpi/device_pm.c:acpi_pm_wakeup_event
```
**Symbols:**

```
ffffffff815e7cb0-ffffffff815e7cc2: acpi_s2idle_wakeup (STB_GLOBAL)
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
