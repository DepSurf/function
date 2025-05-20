# Function: <code>acpi_lid_evaluate_state</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/button.c (ffffffff814fa158)
Location: drivers/acpi/button.c:121
Inline: True
Direct callers:
  - drivers/acpi/button.c:acpi_lid_update_state
  - drivers/acpi/button.c:acpi_lid_open
  - drivers/acpi/button.c:acpi_button_state_seq_show
```
**Symbols:**

```
ffffffff814fa158-ffffffff814fa1b1: acpi_lid_evaluate_state.isra.2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/button.c (ffffffff8151ccdb)
Location: drivers/acpi/button.c:129
Inline: True
Direct callers:
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/button.c:acpi_lid_update_state
  - drivers/acpi/button.c:acpi_lid_open
  - drivers/acpi/button.c:acpi_button_state_seq_show
```
**Symbols:**

```
ffffffff8151ccdb-ffffffff8151cd34: acpi_lid_evaluate_state.isra.2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/button.c (ffffffff8152e069)
Location: drivers/acpi/button.c:129
Inline: True
Inline callers:
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/button.c:acpi_lid_update_state
  - drivers/acpi/button.c:acpi_lid_open
  - drivers/acpi/button.c:acpi_button_state_seq_show
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/button.c (ffffffff8158e836)
Location: drivers/acpi/button.c:129
Inline: True
Inline callers:
  - drivers/acpi/button.c:acpi_lid_input_open
  - drivers/acpi/button.c:acpi_lid_update_state
  - drivers/acpi/button.c:acpi_lid_open
  - drivers/acpi/button.c:acpi_button_state_seq_show
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/button.c (ffffffff815c5bce)
Location: drivers/acpi/button.c:146
Inline: True
Inline callers:
  - drivers/acpi/button.c:acpi_lid_input_open
  - drivers/acpi/button.c:acpi_lid_update_state
  - drivers/acpi/button.c:acpi_lid_open
  - drivers/acpi/button.c:acpi_button_state_seq_show
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/button.c (ffffffff815df18e)
Location: drivers/acpi/button.c:147
Inline: True
Inline callers:
  - drivers/acpi/button.c:acpi_lid_input_open
  - drivers/acpi/button.c:acpi_lid_update_state
  - drivers/acpi/button.c:acpi_lid_open
  - drivers/acpi/button.c:acpi_button_state_seq_show
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/button.c (ffffffff81610d00)
Location: drivers/acpi/button.c:134
Inline: True
Inline callers:
  - drivers/acpi/button.c:acpi_lid_input_open
  - drivers/acpi/button.c:acpi_button_resume
  - drivers/acpi/button.c:acpi_lid_update_state
  - drivers/acpi/button.c:acpi_lid_open
  - drivers/acpi/button.c:acpi_button_state_seq_show
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/button.c (ffffffff816321b0)
Location: drivers/acpi/button.c:156
Inline: True
Inline callers:
  - drivers/acpi/button.c:acpi_lid_input_open
  - drivers/acpi/button.c:acpi_button_resume
  - drivers/acpi/button.c:acpi_lid_update_state
  - drivers/acpi/button.c:acpi_lid_open
  - drivers/acpi/button.c:acpi_button_state_seq_show
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
In drivers/acpi/button.c (ffffffff816df3c0)
Location: drivers/acpi/button.c:172
Inline: True
Inline callers:
  - drivers/acpi/button.c:acpi_lid_input_open
  - drivers/acpi/button.c:acpi_lid_input_open
  - drivers/acpi/button.c:acpi_button_resume
  - drivers/acpi/button.c:acpi_button_resume
  - drivers/acpi/button.c:acpi_button_notify
  - drivers/acpi/button.c:acpi_lid_open
  - drivers/acpi/button.c:acpi_button_state_seq_show
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
In drivers/acpi/button.c (ffffffff816fd3c0)
Location: drivers/acpi/button.c:171
Inline: True
Inline callers:
  - drivers/acpi/button.c:acpi_lid_input_open
  - drivers/acpi/button.c:acpi_lid_input_open
  - drivers/acpi/button.c:acpi_button_resume
  - drivers/acpi/button.c:acpi_button_resume
  - drivers/acpi/button.c:acpi_button_notify
  - drivers/acpi/button.c:acpi_lid_open
  - drivers/acpi/button.c:acpi_button_state_seq_show
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
In drivers/acpi/button.c (ffffffff816df150)
Location: drivers/acpi/button.c:163
Inline: True
Inline callers:
  - drivers/acpi/button.c:acpi_lid_input_open
  - drivers/acpi/button.c:acpi_lid_input_open
  - drivers/acpi/button.c:acpi_button_resume
  - drivers/acpi/button.c:acpi_button_resume
  - drivers/acpi/button.c:acpi_button_notify
  - drivers/acpi/button.c:acpi_lid_open
  - drivers/acpi/button.c:acpi_button_state_seq_show
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
In drivers/acpi/button.c (ffffffff81757310)
Location: drivers/acpi/button.c:174
Inline: True
Inline callers:
  - drivers/acpi/button.c:acpi_lid_input_open
  - drivers/acpi/button.c:acpi_lid_input_open
  - drivers/acpi/button.c:acpi_button_resume
  - drivers/acpi/button.c:acpi_button_resume
  - drivers/acpi/button.c:acpi_button_notify
  - drivers/acpi/button.c:acpi_lid_open
  - drivers/acpi/button.c:acpi_button_state_seq_show
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
In drivers/acpi/button.c (ffffffff8188a4ae)
Location: drivers/acpi/button.c:174
Inline: True
Inline callers:
  - drivers/acpi/button.c:acpi_lid_input_open
  - drivers/acpi/button.c:acpi_lid_input_open
  - drivers/acpi/button.c:acpi_button_resume
  - drivers/acpi/button.c:acpi_button_resume
  - drivers/acpi/button.c:acpi_button_notify
  - drivers/acpi/button.c:acpi_lid_open
  - drivers/acpi/button.c:acpi_button_state_seq_show
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
In drivers/acpi/button.c (ffffffff819d0f2e)
Location: drivers/acpi/button.c:174
Inline: True
Inline callers:
  - drivers/acpi/button.c:acpi_lid_input_open
  - drivers/acpi/button.c:acpi_lid_input_open
  - drivers/acpi/button.c:acpi_button_resume
  - drivers/acpi/button.c:acpi_button_resume
  - drivers/acpi/button.c:acpi_button_notify
  - drivers/acpi/button.c:acpi_lid_open
  - drivers/acpi/button.c:acpi_button_state_seq_show
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
In drivers/acpi/button.c (ffffffff81a1841e)
Location: drivers/acpi/button.c:181
Inline: True
Inline callers:
  - drivers/acpi/button.c:acpi_lid_input_open
  - drivers/acpi/button.c:acpi_lid_input_open
  - drivers/acpi/button.c:acpi_button_resume
  - drivers/acpi/button.c:acpi_button_resume
  - drivers/acpi/button.c:acpi_lid_open
  - drivers/acpi/button.c:acpi_button_state_seq_show
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
In drivers/acpi/button.c (ffffffff81a6368e)
Location: drivers/acpi/button.c:181
Inline: True
Inline callers:
  - drivers/acpi/button.c:acpi_lid_input_open
  - drivers/acpi/button.c:acpi_lid_input_open
  - drivers/acpi/button.c:acpi_button_resume
  - drivers/acpi/button.c:acpi_button_resume
  - drivers/acpi/button.c:acpi_lid_open
  - drivers/acpi/button.c:acpi_button_state_seq_show
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
In drivers/acpi/button.c (ffff8000107a07ac)
Location: drivers/acpi/button.c:156
Inline: True
Inline callers:
  - drivers/acpi/button.c:acpi_lid_input_open
  - drivers/acpi/button.c:acpi_button_resume
  - drivers/acpi/button.c:acpi_lid_update_state
  - drivers/acpi/button.c:acpi_lid_open
  - drivers/acpi/button.c:acpi_button_state_seq_show
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/button.c (ffffffff81602670)
Location: drivers/acpi/button.c:156
Inline: True
Inline callers:
  - drivers/acpi/button.c:acpi_lid_input_open
  - drivers/acpi/button.c:acpi_button_resume
  - drivers/acpi/button.c:acpi_lid_update_state
  - drivers/acpi/button.c:acpi_lid_open
  - drivers/acpi/button.c:acpi_button_state_seq_show
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/button.c (ffffffff815edb20)
Location: drivers/acpi/button.c:156
Inline: True
Inline callers:
  - drivers/acpi/button.c:acpi_lid_input_open
  - drivers/acpi/button.c:acpi_button_resume
  - drivers/acpi/button.c:acpi_lid_update_state
  - drivers/acpi/button.c:acpi_lid_open
  - drivers/acpi/button.c:acpi_button_state_seq_show
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/button.c (ffffffff81626490)
Location: drivers/acpi/button.c:156
Inline: True
Inline callers:
  - drivers/acpi/button.c:acpi_lid_input_open
  - drivers/acpi/button.c:acpi_button_resume
  - drivers/acpi/button.c:acpi_lid_update_state
  - drivers/acpi/button.c:acpi_lid_open
  - drivers/acpi/button.c:acpi_button_state_seq_show
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/button.c (ffffffff81640340)
Location: drivers/acpi/button.c:156
Inline: True
Inline callers:
  - drivers/acpi/button.c:acpi_lid_input_open
  - drivers/acpi/button.c:acpi_button_resume
  - drivers/acpi/button.c:acpi_lid_update_state
  - drivers/acpi/button.c:acpi_lid_open
  - drivers/acpi/button.c:acpi_button_state_seq_show
```
</details>
</li>
</ul>

## Differences
