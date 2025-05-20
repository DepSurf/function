# Function: <code>flatten_lpi_states</code>

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
int flatten_lpi_states(struct acpi_processor *pr, struct acpi_lpi_states_array *curr_level, struct acpi_lpi_states_array *prev_level);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_idle.c (ffffffff814fb923)
Location: drivers/acpi/processor_idle.c:1109
Inline: False
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
```
**Symbols:**

```
ffffffff814fb923-ffffffff814fbaeb: flatten_lpi_states (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int flatten_lpi_states(struct acpi_processor *pr, struct acpi_lpi_states_array *curr_level, struct acpi_lpi_states_array *prev_level);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_idle.c (ffffffff8151e5f7)
Location: drivers/acpi/processor_idle.c:1110
Inline: False
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
```
**Symbols:**

```
ffffffff8151e5f7-ffffffff8151e7bf: flatten_lpi_states (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int flatten_lpi_states(struct acpi_processor *pr, struct acpi_lpi_states_array *curr_level, struct acpi_lpi_states_array *prev_level);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_idle.c (ffffffff8152f740)
Location: drivers/acpi/processor_idle.c:1110
Inline: False
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
```
**Symbols:**

```
ffffffff8152f740-ffffffff8152f999: flatten_lpi_states (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int flatten_lpi_states(struct acpi_processor *pr, struct acpi_lpi_states_array *curr_level, struct acpi_lpi_states_array *prev_level);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_idle.c (ffffffff815903d0)
Location: drivers/acpi/processor_idle.c:1119
Inline: False
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
```
**Symbols:**

```
ffffffff815903d0-ffffffff81590629: flatten_lpi_states (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int flatten_lpi_states(struct acpi_processor *pr, struct acpi_lpi_states_array *curr_level, struct acpi_lpi_states_array *prev_level);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_idle.c (0)
Location: drivers/acpi/processor_idle.c:1123
Inline: False
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
```
**Symbols:**

```
ffffffff815c77c0-ffffffff815c79f3: flatten_lpi_states (STB_LOCAL)
ffffffff815c95bf-ffffffff815c95e5: flatten_lpi_states.cold.15 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int flatten_lpi_states(struct acpi_processor *pr, struct acpi_lpi_states_array *curr_level, struct acpi_lpi_states_array *prev_level);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_idle.c (0)
Location: drivers/acpi/processor_idle.c:1124
Inline: False
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
```
**Symbols:**

```
ffffffff815e0d80-ffffffff815e0fb3: flatten_lpi_states (STB_LOCAL)
ffffffff815e2b9f-ffffffff815e2bc5: flatten_lpi_states.cold.15 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int flatten_lpi_states(struct acpi_processor *pr, struct acpi_lpi_states_array *curr_level, struct acpi_lpi_states_array *prev_level);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_idle.c (0)
Location: drivers/acpi/processor_idle.c:1119
Inline: False
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
```
**Symbols:**

```
ffffffff81612910-ffffffff81612b38: flatten_lpi_states (STB_LOCAL)
ffffffff81614732-ffffffff81614758: flatten_lpi_states.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int flatten_lpi_states(struct acpi_processor *pr, struct acpi_lpi_states_array *curr_level, struct acpi_lpi_states_array *prev_level);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_idle.c (0)
Location: drivers/acpi/processor_idle.c:1119
Inline: False
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
```
**Symbols:**

```
ffffffff81633e10-ffffffff81634038: flatten_lpi_states (STB_LOCAL)
ffffffff81635c22-ffffffff81635c48: flatten_lpi_states.cold (STB_LOCAL)
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
In drivers/acpi/processor_idle.c (0)
Location: drivers/acpi/processor_idle.c:979
Inline: True
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
```
**Symbols:**

```
ffffffff816e17b0-ffffffff816e19d2: flatten_lpi_states.isra.0 (STB_LOCAL)
ffffffff816e28b6-ffffffff816e28dc: flatten_lpi_states.isra.0.cold (STB_LOCAL)
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
In drivers/acpi/processor_idle.c (0)
Location: drivers/acpi/processor_idle.c:999
Inline: True
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
```
**Symbols:**

```
ffffffff816ff450-ffffffff816ff672: flatten_lpi_states.isra.0 (STB_LOCAL)
ffffffff81c02ac3-ffffffff81c02ae9: flatten_lpi_states.isra.0.cold (STB_LOCAL)
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
In drivers/acpi/processor_idle.c (0)
Location: drivers/acpi/processor_idle.c:1033
Inline: True
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
```
**Symbols:**

```
ffffffff816e0fe0-ffffffff816e1200: flatten_lpi_states.isra.0 (STB_LOCAL)
ffffffff81bf44da-ffffffff81bf4500: flatten_lpi_states.isra.0.cold (STB_LOCAL)
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
In drivers/acpi/processor_idle.c (0)
Location: drivers/acpi/processor_idle.c:1034
Inline: True
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
```
**Symbols:**

```
ffffffff81759410-ffffffff81759652: flatten_lpi_states.isra.0 (STB_LOCAL)
ffffffff81cf1474-ffffffff81cf149a: flatten_lpi_states.isra.0.cold (STB_LOCAL)
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
In drivers/acpi/processor_idle.c (0)
Location: drivers/acpi/processor_idle.c:1038
Inline: True
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
```
**Symbols:**

```
ffffffff8188cb50-ffffffff8188ccf0: flatten_lpi_states.isra.0 (STB_LOCAL)
ffffffff81eb93ec-ffffffff81eb9412: flatten_lpi_states.isra.0.cold (STB_LOCAL)
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
In drivers/acpi/processor_idle.c (ffffffff819d4410)
Location: drivers/acpi/processor_idle.c:1054
Inline: True
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
```
**Symbols:**

```
ffffffff819d4410-ffffffff819d45b2: flatten_lpi_states.isra.0 (STB_LOCAL)
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
In drivers/acpi/processor_idle.c (0)
Location: drivers/acpi/processor_idle.c:1054
Inline: True
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
```
**Symbols:**

```
ffffffff81a1bbe0-ffffffff81a1be74: flatten_lpi_states.isra.0 (STB_LOCAL)
ffffffff82112f38-ffffffff82112f5d: flatten_lpi_states.isra.0.cold (STB_LOCAL)
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
In drivers/acpi/processor_idle.c (0)
Location: drivers/acpi/processor_idle.c:1054
Inline: True
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
```
**Symbols:**

```
ffffffff81a66ec0-ffffffff81a67154: flatten_lpi_states.isra.0 (STB_LOCAL)
ffffffff821f0c8c-ffffffff821f0cb1: flatten_lpi_states.isra.0.cold (STB_LOCAL)
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
int flatten_lpi_states(struct acpi_processor *pr, struct acpi_lpi_states_array *curr_level, struct acpi_lpi_states_array *prev_level);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_idle.c (ffff8000107a2228)
Location: drivers/acpi/processor_idle.c:1119
Inline: False
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
```
**Symbols:**

```
ffff8000107a2228-ffff8000107a2484: flatten_lpi_states (STB_LOCAL)
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
int flatten_lpi_states(struct acpi_processor *pr, struct acpi_lpi_states_array *curr_level, struct acpi_lpi_states_array *prev_level);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_idle.c (0)
Location: drivers/acpi/processor_idle.c:1119
Inline: False
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
```
**Symbols:**

```
ffffffff81603960-ffffffff81603b88: flatten_lpi_states (STB_LOCAL)
ffffffff81605412-ffffffff81605438: flatten_lpi_states.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int flatten_lpi_states(struct acpi_processor *pr, struct acpi_lpi_states_array *curr_level, struct acpi_lpi_states_array *prev_level);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_idle.c (0)
Location: drivers/acpi/processor_idle.c:1119
Inline: False
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
```
**Symbols:**

```
ffffffff815eea10-ffffffff815eec38: flatten_lpi_states (STB_LOCAL)
ffffffff815f04c2-ffffffff815f04e8: flatten_lpi_states.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int flatten_lpi_states(struct acpi_processor *pr, struct acpi_lpi_states_array *curr_level, struct acpi_lpi_states_array *prev_level);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_idle.c (0)
Location: drivers/acpi/processor_idle.c:1119
Inline: False
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
```
**Symbols:**

```
ffffffff816280f0-ffffffff81628318: flatten_lpi_states (STB_LOCAL)
ffffffff81629f02-ffffffff81629f28: flatten_lpi_states.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int flatten_lpi_states(struct acpi_processor *pr, struct acpi_lpi_states_array *curr_level, struct acpi_lpi_states_array *prev_level);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_idle.c (0)
Location: drivers/acpi/processor_idle.c:1119
Inline: False
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
```
**Symbols:**

```
ffffffff81641fa0-ffffffff816421c8: flatten_lpi_states (STB_LOCAL)
ffffffff81643da2-ffffffff81643dc8: flatten_lpi_states.cold (STB_LOCAL)
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
