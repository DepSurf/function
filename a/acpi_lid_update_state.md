# Function: <code>acpi_lid_update_state</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int acpi_lid_update_state(struct acpi_device *device);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/button.c (ffffffff814fa3c2)
Location: drivers/acpi/button.c:286
Inline: False
Direct callers:
  - drivers/acpi/button.c:acpi_button_notify
  - drivers/acpi/button.c:acpi_lid_initialize_state
```
**Symbols:**

```
ffffffff814fa3c2-ffffffff814fa3e9: acpi_lid_update_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int acpi_lid_update_state(struct acpi_device *device);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/button.c (ffffffff8151d02d)
Location: drivers/acpi/button.c:363
Inline: False
Direct callers:
  - drivers/acpi/button.c:acpi_button_notify
  - drivers/acpi/button.c:acpi_lid_initialize_state
```
**Symbols:**

```
ffffffff8151d02d-ffffffff8151d054: acpi_lid_update_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int acpi_lid_update_state(struct acpi_device *device);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/button.c (ffffffff8152d8e0)
Location: drivers/acpi/button.c:363
Inline: False
Direct callers:
  - drivers/acpi/button.c:acpi_button_notify
  - drivers/acpi/button.c:acpi_lid_initialize_state
```
**Symbols:**

```
ffffffff8152d8e0-ffffffff8152d94f: acpi_lid_update_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int acpi_lid_update_state(struct acpi_device *device);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/button.c (ffffffff8158e750)
Location: drivers/acpi/button.c:363
Inline: False
Direct callers:
  - drivers/acpi/button.c:acpi_button_notify
  - drivers/acpi/button.c:acpi_lid_initialize_state
```
**Symbols:**

```
ffffffff8158e750-ffffffff8158e7bf: acpi_lid_update_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int acpi_lid_update_state(struct acpi_device *device, bool signal_wakeup);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/button.c (ffffffff815c5a80)
Location: drivers/acpi/button.c:366
Inline: False
Direct callers:
  - drivers/acpi/button.c:acpi_button_notify
  - drivers/acpi/button.c:acpi_lid_initialize_state
```
**Symbols:**

```
ffffffff815c5a80-ffffffff815c5b15: acpi_lid_update_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int acpi_lid_update_state(struct acpi_device *device, bool signal_wakeup);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/button.c (ffffffff815df040)
Location: drivers/acpi/button.c:368
Inline: False
Direct callers:
  - drivers/acpi/button.c:acpi_button_notify
  - drivers/acpi/button.c:acpi_lid_initialize_state
```
**Symbols:**

```
ffffffff815df040-ffffffff815df0d5: acpi_lid_update_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int acpi_lid_update_state(struct acpi_device *device, bool signal_wakeup);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/button.c (ffffffff81610b40)
Location: drivers/acpi/button.c:355
Inline: False
Direct callers:
  - drivers/acpi/button.c:acpi_button_notify
  - drivers/acpi/button.c:acpi_lid_initialize_state
```
**Symbols:**

```
ffffffff81610b40-ffffffff81610bd8: acpi_lid_update_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int acpi_lid_update_state(struct acpi_device *device, bool signal_wakeup);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/button.c (ffffffff81631ff0)
Location: drivers/acpi/button.c:377
Inline: False
Direct callers:
  - drivers/acpi/button.c:acpi_button_notify
  - drivers/acpi/button.c:acpi_lid_initialize_state
```
**Symbols:**

```
ffffffff81631ff0-ffffffff81632088: acpi_lid_update_state (STB_LOCAL)
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
In drivers/acpi/button.c (ffffffff816df3f6)
Location: drivers/acpi/button.c:369
Inline: True
Inline callers:
  - drivers/acpi/button.c:acpi_lid_input_open
  - drivers/acpi/button.c:acpi_button_resume
  - drivers/acpi/button.c:acpi_button_notify
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
In drivers/acpi/button.c (ffffffff816fd3fe)
Location: drivers/acpi/button.c:368
Inline: True
Inline callers:
  - drivers/acpi/button.c:acpi_lid_input_open
  - drivers/acpi/button.c:acpi_button_resume
  - drivers/acpi/button.c:acpi_button_notify
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
In drivers/acpi/button.c (ffffffff816df18e)
Location: drivers/acpi/button.c:358
Inline: True
Inline callers:
  - drivers/acpi/button.c:acpi_lid_input_open
  - drivers/acpi/button.c:acpi_button_resume
  - drivers/acpi/button.c:acpi_button_notify
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
In drivers/acpi/button.c (ffffffff8175734e)
Location: drivers/acpi/button.c:369
Inline: True
Inline callers:
  - drivers/acpi/button.c:acpi_lid_input_open
  - drivers/acpi/button.c:acpi_button_resume
  - drivers/acpi/button.c:acpi_button_notify
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
In drivers/acpi/button.c (ffffffff8188a4f6)
Location: drivers/acpi/button.c:369
Inline: True
Inline callers:
  - drivers/acpi/button.c:acpi_lid_input_open
  - drivers/acpi/button.c:acpi_button_resume
  - drivers/acpi/button.c:acpi_button_notify
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
In drivers/acpi/button.c (ffffffff819d0f76)
Location: drivers/acpi/button.c:369
Inline: True
Inline callers:
  - drivers/acpi/button.c:acpi_lid_input_open
  - drivers/acpi/button.c:acpi_button_resume
  - drivers/acpi/button.c:acpi_button_notify
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
In drivers/acpi/button.c (ffffffff81a18492)
Location: drivers/acpi/button.c:376
Inline: True
Inline callers:
  - drivers/acpi/button.c:acpi_lid_input_open
  - drivers/acpi/button.c:acpi_button_resume
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
In drivers/acpi/button.c (ffffffff81a63702)
Location: drivers/acpi/button.c:376
Inline: True
Inline callers:
  - drivers/acpi/button.c:acpi_lid_input_open
  - drivers/acpi/button.c:acpi_button_resume
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
int acpi_lid_update_state(struct acpi_device *device, bool signal_wakeup);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/button.c (ffff8000107a0590)
Location: drivers/acpi/button.c:377
Inline: False
Direct callers:
  - drivers/acpi/button.c:acpi_button_notify
  - drivers/acpi/button.c:acpi_lid_initialize_state
```
**Symbols:**

```
ffff8000107a0590-ffff8000107a063c: acpi_lid_update_state (STB_LOCAL)
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
int acpi_lid_update_state(struct acpi_device *device, bool signal_wakeup);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/button.c (ffffffff816024b0)
Location: drivers/acpi/button.c:377
Inline: False
Direct callers:
  - drivers/acpi/button.c:acpi_button_notify
  - drivers/acpi/button.c:acpi_lid_initialize_state
```
**Symbols:**

```
ffffffff816024b0-ffffffff81602548: acpi_lid_update_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int acpi_lid_update_state(struct acpi_device *device, bool signal_wakeup);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/button.c (ffffffff815ed960)
Location: drivers/acpi/button.c:377
Inline: False
Direct callers:
  - drivers/acpi/button.c:acpi_button_notify
  - drivers/acpi/button.c:acpi_lid_initialize_state
```
**Symbols:**

```
ffffffff815ed960-ffffffff815ed9f8: acpi_lid_update_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int acpi_lid_update_state(struct acpi_device *device, bool signal_wakeup);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/button.c (ffffffff816262d0)
Location: drivers/acpi/button.c:377
Inline: False
Direct callers:
  - drivers/acpi/button.c:acpi_button_notify
  - drivers/acpi/button.c:acpi_lid_initialize_state
```
**Symbols:**

```
ffffffff816262d0-ffffffff81626368: acpi_lid_update_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int acpi_lid_update_state(struct acpi_device *device, bool signal_wakeup);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/button.c (ffffffff81640180)
Location: drivers/acpi/button.c:377
Inline: False
Direct callers:
  - drivers/acpi/button.c:acpi_button_notify
  - drivers/acpi/button.c:acpi_lid_initialize_state
```
**Symbols:**

```
ffffffff81640180-ffffffff81640218: acpi_lid_update_state (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool signal_wakeup</code>
</li>
</ul>
</details>
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
