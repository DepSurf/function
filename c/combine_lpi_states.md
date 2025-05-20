# Function: <code>combine_lpi_states</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_idle.c (ffffffff814fb9a9)
Location: drivers/acpi/processor_idle.c:1074
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:flatten_lpi_states
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
In drivers/acpi/processor_idle.c (ffffffff8151e67d)
Location: drivers/acpi/processor_idle.c:1075
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:flatten_lpi_states
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
In drivers/acpi/processor_idle.c (ffffffff8152f7b8)
Location: drivers/acpi/processor_idle.c:1075
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:flatten_lpi_states
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
In drivers/acpi/processor_idle.c (ffffffff81590448)
Location: drivers/acpi/processor_idle.c:1084
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:flatten_lpi_states
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
In drivers/acpi/processor_idle.c (ffffffff815c7870)
Location: drivers/acpi/processor_idle.c:1088
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:flatten_lpi_states
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
In drivers/acpi/processor_idle.c (ffffffff815e0e30)
Location: drivers/acpi/processor_idle.c:1089
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:flatten_lpi_states
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
In drivers/acpi/processor_idle.c (ffffffff816129c1)
Location: drivers/acpi/processor_idle.c:1084
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:flatten_lpi_states
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
In drivers/acpi/processor_idle.c (ffffffff81633ec1)
Location: drivers/acpi/processor_idle.c:1084
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:flatten_lpi_states
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
In drivers/acpi/processor_idle.c (ffffffff816e185d)
Location: drivers/acpi/processor_idle.c:944
Inline: True
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
In drivers/acpi/processor_idle.c (ffffffff816ff4fd)
Location: drivers/acpi/processor_idle.c:964
Inline: True
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
In drivers/acpi/processor_idle.c (ffffffff816e108d)
Location: drivers/acpi/processor_idle.c:998
Inline: True
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
In drivers/acpi/processor_idle.c (ffffffff817594c9)
Location: drivers/acpi/processor_idle.c:999
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool combine_lpi_states(struct acpi_lpi_state *local, struct acpi_lpi_state *parent, struct acpi_lpi_state *result);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_idle.c (ffffffff8188bfa0)
Location: drivers/acpi/processor_idle.c:1003
Inline: False
```
**Symbols:**

```
ffffffff8188bfa0-ffffffff8188c067: combine_lpi_states (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool combine_lpi_states(struct acpi_lpi_state *local, struct acpi_lpi_state *parent, struct acpi_lpi_state *result);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_idle.c (ffffffff819d3760)
Location: drivers/acpi/processor_idle.c:1019
Inline: False
```
**Symbols:**

```
ffffffff819d3760-ffffffff819d3827: combine_lpi_states (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool combine_lpi_states(struct acpi_lpi_state *local, struct acpi_lpi_state *parent, struct acpi_lpi_state *result);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_idle.c (ffffffff81a1ae80)
Location: drivers/acpi/processor_idle.c:1019
Inline: False
```
**Symbols:**

```
ffffffff81a1ae80-ffffffff81a1b0c9: combine_lpi_states (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool combine_lpi_states(struct acpi_lpi_state *local, struct acpi_lpi_state *parent, struct acpi_lpi_state *result);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_idle.c (ffffffff81a66180)
Location: drivers/acpi/processor_idle.c:1019
Inline: False
```
**Symbols:**

```
ffffffff81a66180-ffffffff81a663c9: combine_lpi_states (STB_LOCAL)
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
In drivers/acpi/processor_idle.c (ffff8000107a22f0)
Location: drivers/acpi/processor_idle.c:1084
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:flatten_lpi_states
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
In drivers/acpi/processor_idle.c (ffffffff81603a11)
Location: drivers/acpi/processor_idle.c:1084
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:flatten_lpi_states
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
In drivers/acpi/processor_idle.c (ffffffff815eeac1)
Location: drivers/acpi/processor_idle.c:1084
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:flatten_lpi_states
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
In drivers/acpi/processor_idle.c (ffffffff816281a1)
Location: drivers/acpi/processor_idle.c:1084
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:flatten_lpi_states
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
In drivers/acpi/processor_idle.c (ffffffff81642051)
Location: drivers/acpi/processor_idle.c:1084
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:flatten_lpi_states
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
