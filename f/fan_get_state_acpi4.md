# Function: <code>fan_get_state_acpi4</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/fan.c (ffffffff814ab702)
Location: drivers/acpi/fan.c:107
Inline: True
Inline callers:
  - drivers/acpi/fan.c:fan_get_cur_state
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/fan.c (ffffffff814faa5f)
Location: drivers/acpi/fan.c:107
Inline: True
Inline callers:
  - drivers/acpi/fan.c:fan_get_cur_state
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/fan.c (ffffffff8151d6d0)
Location: drivers/acpi/fan.c:107
Inline: True
Inline callers:
  - drivers/acpi/fan.c:fan_get_cur_state
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
In drivers/acpi/fan.c (ffffffff8152e680)
Location: drivers/acpi/fan.c:107
Inline: True
Inline callers:
  - drivers/acpi/fan.c:fan_get_cur_state
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
In drivers/acpi/fan.c (ffffffff8158f360)
Location: drivers/acpi/fan.c:107
Inline: True
Inline callers:
  - drivers/acpi/fan.c:fan_get_cur_state
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
In drivers/acpi/fan.c (ffffffff815c66af)
Location: drivers/acpi/fan.c:107
Inline: True
Inline callers:
  - drivers/acpi/fan.c:fan_get_cur_state
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
In drivers/acpi/fan.c (ffffffff815dfc6f)
Location: drivers/acpi/fan.c:107
Inline: True
Inline callers:
  - drivers/acpi/fan.c:fan_get_cur_state
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
In drivers/acpi/fan.c (ffffffff816117f0)
Location: drivers/acpi/fan.c:94
Inline: True
Inline callers:
  - drivers/acpi/fan.c:fan_get_cur_state
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
In drivers/acpi/fan.c (ffffffff81632ca0)
Location: drivers/acpi/fan.c:94
Inline: True
Inline callers:
  - drivers/acpi/fan.c:fan_get_cur_state
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int fan_get_state_acpi4(struct acpi_device *device, long unsigned int *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/fan.c (0)
Location: drivers/acpi/fan.c:99
Inline: False
Direct callers:
  - drivers/acpi/fan.c:fan_get_cur_state
```
**Symbols:**

```
ffffffff816df7b0-ffffffff816df8ff: fan_get_state_acpi4 (STB_LOCAL)
ffffffff816e0103-ffffffff816e0144: fan_get_state_acpi4.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int fan_get_state_acpi4(struct acpi_device *device, long unsigned int *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/fan.c (0)
Location: drivers/acpi/fan.c:100
Inline: False
Direct callers:
  - drivers/acpi/fan.c:fan_get_cur_state
```
**Symbols:**

```
ffffffff816fd740-ffffffff816fd88f: fan_get_state_acpi4 (STB_LOCAL)
ffffffff81c0287e-ffffffff81c028bf: fan_get_state_acpi4.cold (STB_LOCAL)
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
In drivers/acpi/fan.c (ffffffff816df4ff)
Location: drivers/acpi/fan.c:99
Inline: True
Inline callers:
  - drivers/acpi/fan.c:fan_get_cur_state
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
In drivers/acpi/fan.c (ffffffff81757afd)
Location: drivers/acpi/fan.c:99
Inline: True
Inline callers:
  - drivers/acpi/fan.c:fan_get_cur_state
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
In drivers/acpi/fan_core.c (ffffffff8188afdc)
Location: drivers/acpi/fan_core.c:109
Inline: True
Inline callers:
  - drivers/acpi/fan_core.c:fan_get_cur_state
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
In drivers/acpi/fan_core.c (ffffffff819d1c4c)
Location: drivers/acpi/fan_core.c:78
Inline: True
Inline callers:
  - drivers/acpi/fan_core.c:fan_get_cur_state
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
In drivers/acpi/fan_core.c (ffffffff81a1924c)
Location: drivers/acpi/fan_core.c:78
Inline: True
Inline callers:
  - drivers/acpi/fan_core.c:fan_get_cur_state
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
In drivers/acpi/fan_core.c (ffffffff81a6451c)
Location: drivers/acpi/fan_core.c:78
Inline: True
Inline callers:
  - drivers/acpi/fan_core.c:fan_get_cur_state
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
In drivers/acpi/fan.c (ffff8000107a126c)
Location: drivers/acpi/fan.c:94
Inline: True
Inline callers:
  - drivers/acpi/fan.c:fan_get_cur_state
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/fan.c (ffffffff81626f80)
Location: drivers/acpi/fan.c:94
Inline: True
Inline callers:
  - drivers/acpi/fan.c:fan_get_cur_state
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
In drivers/acpi/fan.c (ffffffff81640e30)
Location: drivers/acpi/fan.c:94
Inline: True
Inline callers:
  - drivers/acpi/fan.c:fan_get_cur_state
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
