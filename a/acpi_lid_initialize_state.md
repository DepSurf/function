# Function: <code>acpi_lid_initialize_state</code>

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
void acpi_lid_initialize_state(struct acpi_device *device);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/button.c (ffffffff814fa3e9)
Location: drivers/acpi/button.c:297
Inline: False
Direct callers:
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/button.c:acpi_button_resume
```
**Symbols:**

```
ffffffff814fa3e9-ffffffff814fa413: acpi_lid_initialize_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void acpi_lid_initialize_state(struct acpi_device *device);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/button.c (ffffffff8151d13d)
Location: drivers/acpi/button.c:374
Inline: False
Direct callers:
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/button.c:acpi_button_resume
```
**Symbols:**

```
ffffffff8151d13d-ffffffff8151d167: acpi_lid_initialize_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void acpi_lid_initialize_state(struct acpi_device *device);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/button.c (ffffffff8152d950)
Location: drivers/acpi/button.c:374
Inline: False
Direct callers:
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/button.c:acpi_button_resume
```
**Symbols:**

```
ffffffff8152d950-ffffffff8152d97b: acpi_lid_initialize_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void acpi_lid_initialize_state(struct acpi_device *device);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/button.c (ffffffff8158e7c0)
Location: drivers/acpi/button.c:374
Inline: False
Direct callers:
  - drivers/acpi/button.c:acpi_lid_input_open
  - drivers/acpi/button.c:acpi_button_resume
```
**Symbols:**

```
ffffffff8158e7c0-ffffffff8158e7eb: acpi_lid_initialize_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void acpi_lid_initialize_state(struct acpi_device *device);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/button.c (ffffffff815c5b20)
Location: drivers/acpi/button.c:381
Inline: False
Direct callers:
  - drivers/acpi/button.c:acpi_lid_input_open
  - drivers/acpi/button.c:acpi_button_resume
```
**Symbols:**

```
ffffffff815c5b20-ffffffff815c5b4d: acpi_lid_initialize_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void acpi_lid_initialize_state(struct acpi_device *device);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/button.c (ffffffff815df0e0)
Location: drivers/acpi/button.c:383
Inline: False
Direct callers:
  - drivers/acpi/button.c:acpi_lid_input_open
  - drivers/acpi/button.c:acpi_button_resume
```
**Symbols:**

```
ffffffff815df0e0-ffffffff815df10d: acpi_lid_initialize_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void acpi_lid_initialize_state(struct acpi_device *device);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/button.c (ffffffff81610be0)
Location: drivers/acpi/button.c:370
Inline: False
Direct callers:
  - drivers/acpi/button.c:acpi_lid_input_open
  - drivers/acpi/button.c:acpi_button_resume
```
**Symbols:**

```
ffffffff81610be0-ffffffff81610c0d: acpi_lid_initialize_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void acpi_lid_initialize_state(struct acpi_device *device);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/button.c (ffffffff81632090)
Location: drivers/acpi/button.c:392
Inline: False
Direct callers:
  - drivers/acpi/button.c:acpi_lid_input_open
  - drivers/acpi/button.c:acpi_button_resume
```
**Symbols:**

```
ffffffff81632090-ffffffff816320bd: acpi_lid_initialize_state (STB_LOCAL)
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
In drivers/acpi/button.c (ffffffff816df3e3)
Location: drivers/acpi/button.c:384
Inline: True
Inline callers:
  - drivers/acpi/button.c:acpi_lid_input_open
  - drivers/acpi/button.c:acpi_button_resume
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
In drivers/acpi/button.c (ffffffff816fd3e3)
Location: drivers/acpi/button.c:383
Inline: True
Inline callers:
  - drivers/acpi/button.c:acpi_lid_input_open
  - drivers/acpi/button.c:acpi_button_resume
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
In drivers/acpi/button.c (ffffffff816df173)
Location: drivers/acpi/button.c:373
Inline: True
Inline callers:
  - drivers/acpi/button.c:acpi_lid_input_open
  - drivers/acpi/button.c:acpi_button_resume
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
In drivers/acpi/button.c (ffffffff81757333)
Location: drivers/acpi/button.c:384
Inline: True
Inline callers:
  - drivers/acpi/button.c:acpi_lid_input_open
  - drivers/acpi/button.c:acpi_button_resume
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
In drivers/acpi/button.c (ffffffff8188a4dc)
Location: drivers/acpi/button.c:384
Inline: True
Inline callers:
  - drivers/acpi/button.c:acpi_lid_input_open
  - drivers/acpi/button.c:acpi_button_resume
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
In drivers/acpi/button.c (ffffffff819d0f5c)
Location: drivers/acpi/button.c:384
Inline: True
Inline callers:
  - drivers/acpi/button.c:acpi_lid_input_open
  - drivers/acpi/button.c:acpi_button_resume
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
In drivers/acpi/button.c (ffffffff81a1844c)
Location: drivers/acpi/button.c:391
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
In drivers/acpi/button.c (ffffffff81a636bc)
Location: drivers/acpi/button.c:391
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
void acpi_lid_initialize_state(struct acpi_device *device);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/button.c (ffff8000107a0640)
Location: drivers/acpi/button.c:392
Inline: False
Direct callers:
  - drivers/acpi/button.c:acpi_lid_input_open
  - drivers/acpi/button.c:acpi_button_resume
```
**Symbols:**

```
ffff8000107a0640-ffff8000107a069c: acpi_lid_initialize_state (STB_LOCAL)
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
void acpi_lid_initialize_state(struct acpi_device *device);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/button.c (ffffffff81602550)
Location: drivers/acpi/button.c:392
Inline: False
Direct callers:
  - drivers/acpi/button.c:acpi_lid_input_open
  - drivers/acpi/button.c:acpi_button_resume
```
**Symbols:**

```
ffffffff81602550-ffffffff8160257d: acpi_lid_initialize_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void acpi_lid_initialize_state(struct acpi_device *device);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/button.c (ffffffff815eda00)
Location: drivers/acpi/button.c:392
Inline: False
Direct callers:
  - drivers/acpi/button.c:acpi_lid_input_open
  - drivers/acpi/button.c:acpi_button_resume
```
**Symbols:**

```
ffffffff815eda00-ffffffff815eda2d: acpi_lid_initialize_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void acpi_lid_initialize_state(struct acpi_device *device);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/button.c (ffffffff81626370)
Location: drivers/acpi/button.c:392
Inline: False
Direct callers:
  - drivers/acpi/button.c:acpi_lid_input_open
  - drivers/acpi/button.c:acpi_button_resume
```
**Symbols:**

```
ffffffff81626370-ffffffff8162639d: acpi_lid_initialize_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void acpi_lid_initialize_state(struct acpi_device *device);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/button.c (ffffffff81640220)
Location: drivers/acpi/button.c:392
Inline: False
Direct callers:
  - drivers/acpi/button.c:acpi_lid_input_open
  - drivers/acpi/button.c:acpi_button_resume
```
**Symbols:**

```
ffffffff81640220-ffffffff8164024d: acpi_lid_initialize_state (STB_LOCAL)
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
