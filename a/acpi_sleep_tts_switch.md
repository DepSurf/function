# Function: <code>acpi_sleep_tts_switch</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void acpi_sleep_tts_switch(u32 acpi_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/sleep.c (ffffffff8147b6d4)
Location: drivers/acpi/sleep.c:30
Inline: False
Direct callers:
  - drivers/acpi/sleep.c:tts_notify_reboot
  - drivers/acpi/sleep.c:acpi_pm_end
  - drivers/acpi/sleep.c:acpi_suspend_begin
  - drivers/acpi/sleep.c:acpi_hibernation_begin_old
  - drivers/acpi/sleep.c:acpi_hibernation_begin
```
**Symbols:**

```
ffffffff8147b6d4-ffffffff8147b704: acpi_sleep_tts_switch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void acpi_sleep_tts_switch(u32 acpi_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/sleep.c (ffffffff814c9d56)
Location: drivers/acpi/sleep.c:36
Inline: False
Direct callers:
  - drivers/acpi/sleep.c:acpi_hibernation_begin_old
  - drivers/acpi/sleep.c:acpi_hibernation_begin
  - drivers/acpi/sleep.c:acpi_suspend_begin
  - drivers/acpi/sleep.c:acpi_pm_end
  - drivers/acpi/sleep.c:sleep_notify_reboot
```
**Symbols:**

```
ffffffff814c9d56-ffffffff814c9d86: acpi_sleep_tts_switch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void acpi_sleep_tts_switch(u32 acpi_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/sleep.c (ffffffff814ebc9a)
Location: drivers/acpi/sleep.c:36
Inline: False
Direct callers:
  - drivers/acpi/sleep.c:acpi_hibernation_begin_old
  - drivers/acpi/sleep.c:acpi_hibernation_begin
  - drivers/acpi/sleep.c:acpi_suspend_begin
  - drivers/acpi/sleep.c:acpi_pm_end
  - drivers/acpi/sleep.c:tts_notify_reboot
```
**Symbols:**

```
ffffffff814ebc9a-ffffffff814ebcca: acpi_sleep_tts_switch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void acpi_sleep_tts_switch(u32 acpi_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/sleep.c (ffffffff814f8050)
Location: drivers/acpi/sleep.c:36
Inline: False
Direct callers:
  - drivers/acpi/sleep.c:acpi_hibernation_begin
  - drivers/acpi/sleep.c:acpi_suspend_begin
  - drivers/acpi/sleep.c:acpi_pm_end
  - drivers/acpi/sleep.c:tts_notify_reboot
```
**Symbols:**

```
ffffffff814f8050-ffffffff814f8082: acpi_sleep_tts_switch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void acpi_sleep_tts_switch(u32 acpi_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/sleep.c (ffffffff81539380)
Location: drivers/acpi/sleep.c:36
Inline: False
Direct callers:
  - drivers/acpi/sleep.c:acpi_hibernation_begin
  - drivers/acpi/sleep.c:acpi_suspend_begin
  - drivers/acpi/sleep.c:acpi_pm_end
  - drivers/acpi/sleep.c:tts_notify_reboot
```
**Symbols:**

```
ffffffff81539380-ffffffff815393b2: acpi_sleep_tts_switch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void acpi_sleep_tts_switch(u32 acpi_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/sleep.c (ffffffff8156f190)
Location: drivers/acpi/sleep.c:36
Inline: False
Direct callers:
  - drivers/acpi/sleep.c:acpi_hibernation_begin
  - drivers/acpi/sleep.c:acpi_suspend_begin
  - drivers/acpi/sleep.c:acpi_pm_end
  - drivers/acpi/sleep.c:tts_notify_reboot
```
**Symbols:**

```
ffffffff8156f190-ffffffff8156f1c2: acpi_sleep_tts_switch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void acpi_sleep_tts_switch(u32 acpi_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/sleep.c (ffffffff81586d50)
Location: drivers/acpi/sleep.c:36
Inline: False
Direct callers:
  - drivers/acpi/sleep.c:acpi_hibernation_begin
  - drivers/acpi/sleep.c:acpi_suspend_begin
  - drivers/acpi/sleep.c:acpi_pm_end
  - drivers/acpi/sleep.c:tts_notify_reboot
```
**Symbols:**

```
ffffffff81586d50-ffffffff81586d82: acpi_sleep_tts_switch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void acpi_sleep_tts_switch(u32 acpi_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/sleep.c (0)
Location: drivers/acpi/sleep.c:34
Inline: False
Direct callers:
  - drivers/acpi/sleep.c:acpi_hibernation_begin_old
  - drivers/acpi/sleep.c:acpi_hibernation_begin
  - drivers/acpi/sleep.c:acpi_suspend_begin
  - drivers/acpi/sleep.c:acpi_pm_end
  - drivers/acpi/sleep.c:tts_notify_reboot
```
**Symbols:**

```
ffffffff815b7a00-ffffffff815b7a28: acpi_sleep_tts_switch (STB_LOCAL)
ffffffff815b88e4-ffffffff815b88f5: acpi_sleep_tts_switch.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void acpi_sleep_tts_switch(u32 acpi_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/sleep.c (0)
Location: drivers/acpi/sleep.c:34
Inline: False
Direct callers:
  - drivers/acpi/sleep.c:acpi_hibernation_begin_old
  - drivers/acpi/sleep.c:acpi_hibernation_begin
  - drivers/acpi/sleep.c:acpi_suspend_begin
  - drivers/acpi/sleep.c:acpi_pm_end
  - drivers/acpi/sleep.c:tts_notify_reboot
```
**Symbols:**

```
ffffffff815d8c30-ffffffff815d8c58: acpi_sleep_tts_switch (STB_LOCAL)
ffffffff815d9b22-ffffffff815d9b33: acpi_sleep_tts_switch.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/sleep.c (ffffffff81683a75)
Location: drivers/acpi/sleep.c:34
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_hibernation_begin_old
  - drivers/acpi/sleep.c:acpi_hibernation_begin
  - drivers/acpi/sleep.c:acpi_suspend_begin
  - drivers/acpi/sleep.c:acpi_pm_end
  - drivers/acpi/sleep.c:tts_notify_reboot
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/sleep.c (ffffffff816a1965)
Location: drivers/acpi/sleep.c:34
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_hibernation_begin_old
  - drivers/acpi/sleep.c:acpi_hibernation_begin
  - drivers/acpi/sleep.c:acpi_suspend_begin
  - drivers/acpi/sleep.c:acpi_pm_end
  - drivers/acpi/sleep.c:tts_notify_reboot
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/sleep.c (ffffffff81684925)
Location: drivers/acpi/sleep.c:34
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_hibernation_begin_old
  - drivers/acpi/sleep.c:acpi_hibernation_begin
  - drivers/acpi/sleep.c:acpi_suspend_begin
  - drivers/acpi/sleep.c:acpi_pm_end
  - drivers/acpi/sleep.c:tts_notify_reboot
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/sleep.c (ffffffff816f9bd5)
Location: drivers/acpi/sleep.c:36
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_hibernation_begin_old
  - drivers/acpi/sleep.c:acpi_hibernation_begin
  - drivers/acpi/sleep.c:acpi_suspend_begin
  - drivers/acpi/sleep.c:acpi_pm_end
  - drivers/acpi/sleep.c:tts_notify_reboot
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/sleep.c (ffffffff81eb68e3)
Location: drivers/acpi/sleep.c:36
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_hibernation_begin_old
  - drivers/acpi/sleep.c:acpi_hibernation_begin_old
  - drivers/acpi/sleep.c:acpi_hibernation_begin
  - drivers/acpi/sleep.c:acpi_hibernation_begin
  - drivers/acpi/sleep.c:acpi_suspend_begin
  - drivers/acpi/sleep.c:acpi_suspend_begin
  - drivers/acpi/sleep.c:acpi_pm_end
  - drivers/acpi/sleep.c:acpi_pm_end
  - drivers/acpi/sleep.c:tts_notify_reboot
  - drivers/acpi/sleep.c:tts_notify_reboot
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/sleep.c (ffffffff81958d65)
Location: drivers/acpi/sleep.c:36
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_hibernation_begin_old
  - drivers/acpi/sleep.c:acpi_hibernation_begin_old
  - drivers/acpi/sleep.c:acpi_hibernation_begin
  - drivers/acpi/sleep.c:acpi_hibernation_begin
  - drivers/acpi/sleep.c:acpi_suspend_begin
  - drivers/acpi/sleep.c:acpi_suspend_begin
  - drivers/acpi/sleep.c:acpi_pm_end
  - drivers/acpi/sleep.c:acpi_pm_end
  - drivers/acpi/sleep.c:tts_notify_reboot
  - drivers/acpi/sleep.c:tts_notify_reboot
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/sleep.c (ffffffff8199f1d5)
Location: drivers/acpi/sleep.c:36
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_hibernation_begin_old
  - drivers/acpi/sleep.c:acpi_hibernation_begin_old
  - drivers/acpi/sleep.c:acpi_hibernation_begin
  - drivers/acpi/sleep.c:acpi_hibernation_begin
  - drivers/acpi/sleep.c:acpi_suspend_begin
  - drivers/acpi/sleep.c:acpi_suspend_begin
  - drivers/acpi/sleep.c:acpi_pm_end
  - drivers/acpi/sleep.c:acpi_pm_end
  - drivers/acpi/sleep.c:tts_notify_reboot
  - drivers/acpi/sleep.c:tts_notify_reboot
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/sleep.c (ffffffff819e7875)
Location: drivers/acpi/sleep.c:36
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_hibernation_begin_old
  - drivers/acpi/sleep.c:acpi_hibernation_begin_old
  - drivers/acpi/sleep.c:acpi_hibernation_begin
  - drivers/acpi/sleep.c:acpi_hibernation_begin
  - drivers/acpi/sleep.c:acpi_suspend_begin
  - drivers/acpi/sleep.c:acpi_suspend_begin
  - drivers/acpi/sleep.c:acpi_pm_end
  - drivers/acpi/sleep.c:acpi_pm_end
  - drivers/acpi/sleep.c:tts_notify_reboot
  - drivers/acpi/sleep.c:tts_notify_reboot
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void acpi_sleep_tts_switch(u32 acpi_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/sleep.c (0)
Location: drivers/acpi/sleep.c:34
Inline: False
Direct callers:
  - drivers/acpi/sleep.c:acpi_hibernation_begin
  - drivers/acpi/sleep.c:acpi_pm_end
  - drivers/acpi/sleep.c:tts_notify_reboot
```
**Symbols:**

```
ffffffff815cbf30-ffffffff815cbf58: acpi_sleep_tts_switch (STB_LOCAL)
ffffffff815cc32d-ffffffff815cc33e: acpi_sleep_tts_switch.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void acpi_sleep_tts_switch(u32 acpi_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/sleep.c (0)
Location: drivers/acpi/sleep.c:34
Inline: False
Direct callers:
  - drivers/acpi/sleep.c:acpi_hibernation_begin_old
  - drivers/acpi/sleep.c:acpi_hibernation_begin
  - drivers/acpi/sleep.c:acpi_suspend_begin
  - drivers/acpi/sleep.c:acpi_pm_end
  - drivers/acpi/sleep.c:tts_notify_reboot
```
**Symbols:**

```
ffffffff815b4fb0-ffffffff815b4fd8: acpi_sleep_tts_switch (STB_LOCAL)
ffffffff815b5e82-ffffffff815b5e93: acpi_sleep_tts_switch.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void acpi_sleep_tts_switch(u32 acpi_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/sleep.c (0)
Location: drivers/acpi/sleep.c:34
Inline: False
Direct callers:
  - drivers/acpi/sleep.c:acpi_hibernation_begin_old
  - drivers/acpi/sleep.c:acpi_hibernation_begin
  - drivers/acpi/sleep.c:acpi_suspend_begin
  - drivers/acpi/sleep.c:acpi_pm_end
  - drivers/acpi/sleep.c:tts_notify_reboot
```
**Symbols:**

```
ffffffff815ccf10-ffffffff815ccf38: acpi_sleep_tts_switch (STB_LOCAL)
ffffffff815cde02-ffffffff815cde13: acpi_sleep_tts_switch.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void acpi_sleep_tts_switch(u32 acpi_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/sleep.c (0)
Location: drivers/acpi/sleep.c:34
Inline: False
Direct callers:
  - drivers/acpi/sleep.c:acpi_hibernation_begin_old
  - drivers/acpi/sleep.c:acpi_hibernation_begin
  - drivers/acpi/sleep.c:acpi_suspend_begin
  - drivers/acpi/sleep.c:acpi_pm_end
  - drivers/acpi/sleep.c:tts_notify_reboot
```
**Symbols:**

```
ffffffff815e6db0-ffffffff815e6dd8: acpi_sleep_tts_switch (STB_LOCAL)
ffffffff815e7cc2-ffffffff815e7cd3: acpi_sleep_tts_switch.cold (STB_LOCAL)
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
