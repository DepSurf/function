# Function: <code>acpi_lid_notify_state</code>

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
int acpi_lid_notify_state(struct acpi_device *device, int state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/button.c (ffffffff814fa33a)
Location: drivers/acpi/button.c:133
Inline: False
Direct callers:
  - drivers/acpi/button.c:acpi_lid_initialize_state
  - drivers/acpi/button.c:acpi_lid_update_state
```
**Symbols:**

```
ffffffff814fa33a-ffffffff814fa3c2: acpi_lid_notify_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int acpi_lid_notify_state(struct acpi_device *device, int state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/button.c (ffffffff8151ceeb)
Location: drivers/acpi/button.c:141
Inline: False
Direct callers:
  - drivers/acpi/button.c:acpi_lid_initialize_state
  - drivers/acpi/button.c:acpi_lid_update_state
```
**Symbols:**

```
ffffffff8151ceeb-ffffffff8151d02d: acpi_lid_notify_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int acpi_lid_notify_state(struct acpi_device *device, int state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/button.c (ffffffff8152d720)
Location: drivers/acpi/button.c:141
Inline: False
Direct callers:
  - drivers/acpi/button.c:acpi_lid_initialize_state
  - drivers/acpi/button.c:acpi_lid_update_state
```
**Symbols:**

```
ffffffff8152d720-ffffffff8152d8d3: acpi_lid_notify_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int acpi_lid_notify_state(struct acpi_device *device, int state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/button.c (ffffffff8158e590)
Location: drivers/acpi/button.c:141
Inline: False
Direct callers:
  - drivers/acpi/button.c:acpi_lid_initialize_state
  - drivers/acpi/button.c:acpi_lid_update_state
```
**Symbols:**

```
ffffffff8158e590-ffffffff8158e743: acpi_lid_notify_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int acpi_lid_notify_state(struct acpi_device *device, int state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/button.c (0)
Location: drivers/acpi/button.c:158
Inline: False
Direct callers:
  - drivers/acpi/button.c:acpi_lid_initialize_state
  - drivers/acpi/button.c:acpi_lid_update_state
```
**Symbols:**

```
ffffffff815c58c0-ffffffff815c5a7f: acpi_lid_notify_state (STB_LOCAL)
ffffffff815c6487-ffffffff815c64a6: acpi_lid_notify_state.cold.9 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int acpi_lid_notify_state(struct acpi_device *device, int state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/button.c (0)
Location: drivers/acpi/button.c:159
Inline: False
Direct callers:
  - drivers/acpi/button.c:acpi_lid_initialize_state
  - drivers/acpi/button.c:acpi_lid_update_state
```
**Symbols:**

```
ffffffff815dee80-ffffffff815df03f: acpi_lid_notify_state (STB_LOCAL)
ffffffff815dfa47-ffffffff815dfa66: acpi_lid_notify_state.cold.8 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int acpi_lid_notify_state(struct acpi_device *device, int state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/button.c (0)
Location: drivers/acpi/button.c:146
Inline: False
Direct callers:
  - drivers/acpi/button.c:acpi_lid_initialize_state
  - drivers/acpi/button.c:acpi_lid_update_state
```
**Symbols:**

```
ffffffff81610980-ffffffff81610b39: acpi_lid_notify_state (STB_LOCAL)
ffffffff816115cf-ffffffff816115ee: acpi_lid_notify_state.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int acpi_lid_notify_state(struct acpi_device *device, int state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/button.c (0)
Location: drivers/acpi/button.c:168
Inline: False
Direct callers:
  - drivers/acpi/button.c:acpi_lid_initialize_state
  - drivers/acpi/button.c:acpi_lid_update_state
```
**Symbols:**

```
ffffffff81631e30-ffffffff81631fe9: acpi_lid_notify_state (STB_LOCAL)
ffffffff81632a7f-ffffffff81632a9e: acpi_lid_notify_state.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/button.c (0)
Location: drivers/acpi/button.c:184
Inline: True
Direct callers:
  - drivers/acpi/button.c:acpi_lid_input_open
  - drivers/acpi/button.c:acpi_lid_input_open
  - drivers/acpi/button.c:acpi_button_resume
  - drivers/acpi/button.c:acpi_button_resume
  - drivers/acpi/button.c:acpi_button_notify
```
**Symbols:**

```
ffffffff816deee0-ffffffff816df06a: acpi_lid_notify_state.isra.0 (STB_LOCAL)
ffffffff816df5c6-ffffffff816df5e5: acpi_lid_notify_state.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/button.c (0)
Location: drivers/acpi/button.c:183
Inline: True
Direct callers:
  - drivers/acpi/button.c:acpi_lid_input_open
  - drivers/acpi/button.c:acpi_lid_input_open
  - drivers/acpi/button.c:acpi_button_resume
  - drivers/acpi/button.c:acpi_button_resume
  - drivers/acpi/button.c:acpi_button_notify
```
**Symbols:**

```
ffffffff816fcf00-ffffffff816fd08a: acpi_lid_notify_state.isra.0 (STB_LOCAL)
ffffffff81c0285f-ffffffff81c0287e: acpi_lid_notify_state.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/button.c (0)
Location: drivers/acpi/button.c:175
Inline: True
Direct callers:
  - drivers/acpi/button.c:acpi_lid_input_open
  - drivers/acpi/button.c:acpi_lid_input_open
  - drivers/acpi/button.c:acpi_button_resume
  - drivers/acpi/button.c:acpi_button_resume
  - drivers/acpi/button.c:acpi_button_notify
```
**Symbols:**

```
ffffffff816decc0-ffffffff816dee38: acpi_lid_notify_state.isra.0 (STB_LOCAL)
ffffffff81bf425d-ffffffff81bf427c: acpi_lid_notify_state.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/button.c (0)
Location: drivers/acpi/button.c:186
Inline: True
Direct callers:
  - drivers/acpi/button.c:acpi_lid_input_open
  - drivers/acpi/button.c:acpi_lid_input_open
  - drivers/acpi/button.c:acpi_button_resume
  - drivers/acpi/button.c:acpi_button_resume
  - drivers/acpi/button.c:acpi_button_notify
```
**Symbols:**

```
ffffffff81756e60-ffffffff81756fe7: acpi_lid_notify_state.isra.0 (STB_LOCAL)
ffffffff81cf1100-ffffffff81cf113b: acpi_lid_notify_state.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/button.c (0)
Location: drivers/acpi/button.c:186
Inline: True
Direct callers:
  - drivers/acpi/button.c:acpi_lid_input_open
  - drivers/acpi/button.c:acpi_lid_input_open
  - drivers/acpi/button.c:acpi_button_resume
  - drivers/acpi/button.c:acpi_button_resume
  - drivers/acpi/button.c:acpi_button_notify
```
**Symbols:**

```
ffffffff81889fa0-ffffffff8188a141: acpi_lid_notify_state.isra.0 (STB_LOCAL)
ffffffff81eb900f-ffffffff81eb904a: acpi_lid_notify_state.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/button.c (0)
Location: drivers/acpi/button.c:186
Inline: True
Direct callers:
  - drivers/acpi/button.c:acpi_lid_input_open
  - drivers/acpi/button.c:acpi_lid_input_open
  - drivers/acpi/button.c:acpi_button_resume
  - drivers/acpi/button.c:acpi_button_resume
  - drivers/acpi/button.c:acpi_button_notify
```
**Symbols:**

```
ffffffff819d09d0-ffffffff819d0b71: acpi_lid_notify_state.isra.0 (STB_LOCAL)
ffffffff820924ec-ffffffff82092508: acpi_lid_notify_state.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/button.c (0)
Location: drivers/acpi/button.c:193
Inline: True
Direct callers:
  - drivers/acpi/button.c:acpi_lid_input_open
  - drivers/acpi/button.c:acpi_lid_input_open
  - drivers/acpi/button.c:acpi_button_resume
  - drivers/acpi/button.c:acpi_button_resume
```
**Symbols:**

```
ffffffff81a18030-ffffffff81a181d0: acpi_lid_notify_state.isra.0 (STB_LOCAL)
ffffffff82112df8-ffffffff82112e14: acpi_lid_notify_state.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/button.c (0)
Location: drivers/acpi/button.c:193
Inline: True
Direct callers:
  - drivers/acpi/button.c:acpi_lid_input_open
  - drivers/acpi/button.c:acpi_lid_input_open
  - drivers/acpi/button.c:acpi_button_resume
  - drivers/acpi/button.c:acpi_button_resume
```
**Symbols:**

```
ffffffff81a632a0-ffffffff81a63440: acpi_lid_notify_state.isra.0 (STB_LOCAL)
ffffffff821f0b4c-ffffffff821f0b68: acpi_lid_notify_state.isra.0.cold (STB_LOCAL)
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
int acpi_lid_notify_state(struct acpi_device *device, int state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/button.c (ffff8000107a03b8)
Location: drivers/acpi/button.c:168
Inline: False
Direct callers:
  - drivers/acpi/button.c:acpi_lid_initialize_state
  - drivers/acpi/button.c:acpi_lid_update_state
```
**Symbols:**

```
ffff8000107a03b8-ffff8000107a058c: acpi_lid_notify_state (STB_LOCAL)
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int acpi_lid_notify_state(struct acpi_device *device, int state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/button.c (0)
Location: drivers/acpi/button.c:168
Inline: False
Direct callers:
  - drivers/acpi/button.c:acpi_lid_initialize_state
  - drivers/acpi/button.c:acpi_lid_update_state
```
**Symbols:**

```
ffffffff816022f0-ffffffff816024a9: acpi_lid_notify_state (STB_LOCAL)
ffffffff81602eef-ffffffff81602f0e: acpi_lid_notify_state.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int acpi_lid_notify_state(struct acpi_device *device, int state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/button.c (0)
Location: drivers/acpi/button.c:168
Inline: False
Direct callers:
  - drivers/acpi/button.c:acpi_lid_initialize_state
  - drivers/acpi/button.c:acpi_lid_update_state
```
**Symbols:**

```
ffffffff815ed7a0-ffffffff815ed959: acpi_lid_notify_state (STB_LOCAL)
ffffffff815ee39f-ffffffff815ee3be: acpi_lid_notify_state.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int acpi_lid_notify_state(struct acpi_device *device, int state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/button.c (0)
Location: drivers/acpi/button.c:168
Inline: False
Direct callers:
  - drivers/acpi/button.c:acpi_lid_initialize_state
  - drivers/acpi/button.c:acpi_lid_update_state
```
**Symbols:**

```
ffffffff81626110-ffffffff816262c9: acpi_lid_notify_state (STB_LOCAL)
ffffffff81626d5f-ffffffff81626d7e: acpi_lid_notify_state.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int acpi_lid_notify_state(struct acpi_device *device, int state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/button.c (0)
Location: drivers/acpi/button.c:168
Inline: False
Direct callers:
  - drivers/acpi/button.c:acpi_lid_initialize_state
  - drivers/acpi/button.c:acpi_lid_update_state
```
**Symbols:**

```
ffffffff8163ffc0-ffffffff81640179: acpi_lid_notify_state (STB_LOCAL)
ffffffff81640c0f-ffffffff81640c2e: acpi_lid_notify_state.cold (STB_LOCAL)
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
