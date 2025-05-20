# Function: <code>acpi_processor_get_performance_states</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int acpi_processor_get_performance_states(struct acpi_processor *pr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_perflib.c (ffffffff814aebe0)
Location: drivers/acpi/processor_perflib.c:320
Inline: False
Direct callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info
```
**Symbols:**

```
ffffffff814aebe0-ffffffff814aeec9: acpi_processor_get_performance_states (STB_LOCAL)
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
In drivers/acpi/processor_perflib.c (ffffffff814fe6fa)
Location: drivers/acpi/processor_perflib.c:320
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info
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
In drivers/acpi/processor_perflib.c (ffffffff815213ee)
Location: drivers/acpi/processor_perflib.c:318
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info
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
In drivers/acpi/processor_perflib.c (ffffffff81532d3f)
Location: drivers/acpi/processor_perflib.c:316
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info
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
In drivers/acpi/processor_perflib.c (ffffffff81594378)
Location: drivers/acpi/processor_perflib.c:316
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int acpi_processor_get_performance_states(struct acpi_processor *pr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_perflib.c (0)
Location: drivers/acpi/processor_perflib.c:316
Inline: False
Direct callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info
```
**Symbols:**

```
ffffffff815cb750-ffffffff815cbb4e: acpi_processor_get_performance_states (STB_LOCAL)
ffffffff815cc559-ffffffff815cc5d2: acpi_processor_get_performance_states.cold.9 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int acpi_processor_get_performance_states(struct acpi_processor *pr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_perflib.c (0)
Location: drivers/acpi/processor_perflib.c:316
Inline: False
Direct callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info
```
**Symbols:**

```
ffffffff815e4d30-ffffffff815e512e: acpi_processor_get_performance_states (STB_LOCAL)
ffffffff815e5b39-ffffffff815e5bb2: acpi_processor_get_performance_states.cold.10 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int acpi_processor_get_performance_states(struct acpi_processor *pr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_perflib.c (0)
Location: drivers/acpi/processor_perflib.c:303
Inline: False
Direct callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info
```
**Symbols:**

```
ffffffff81616920-ffffffff81616d15: acpi_processor_get_performance_states (STB_LOCAL)
ffffffff8161772f-ffffffff816177aa: acpi_processor_get_performance_states.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int acpi_processor_get_performance_states(struct acpi_processor *pr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_perflib.c (0)
Location: drivers/acpi/processor_perflib.c:289
Inline: False
Direct callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info
```
**Symbols:**

```
ffffffff81637e80-ffffffff81638275: acpi_processor_get_performance_states (STB_LOCAL)
ffffffff81638d47-ffffffff81638dc2: acpi_processor_get_performance_states.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int acpi_processor_get_performance_states(struct acpi_processor *pr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_perflib.c (0)
Location: drivers/acpi/processor_perflib.c:289
Inline: False
Direct callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info
```
**Symbols:**

```
ffffffff816e4dc0-ffffffff816e511d: acpi_processor_get_performance_states (STB_LOCAL)
ffffffff816e5b1c-ffffffff816e5b97: acpi_processor_get_performance_states.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int acpi_processor_get_performance_states(struct acpi_processor *pr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_perflib.c (0)
Location: drivers/acpi/processor_perflib.c:288
Inline: False
Direct callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info
```
**Symbols:**

```
ffffffff81702830-ffffffff81702b8a: acpi_processor_get_performance_states (STB_LOCAL)
ffffffff81c02d8a-ffffffff81c02df8: acpi_processor_get_performance_states.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int acpi_processor_get_performance_states(struct acpi_processor *pr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_perflib.c (0)
Location: drivers/acpi/processor_perflib.c:286
Inline: False
Direct callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info
```
**Symbols:**

```
ffffffff816e4080-ffffffff816e43f0: acpi_processor_get_performance_states (STB_LOCAL)
ffffffff81bf47d1-ffffffff81bf4842: acpi_processor_get_performance_states.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int acpi_processor_get_performance_states(struct acpi_processor *pr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_perflib.c (0)
Location: drivers/acpi/processor_perflib.c:285
Inline: False
Direct callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info
```
**Symbols:**

```
ffffffff8175cd20-ffffffff8175d090: acpi_processor_get_performance_states (STB_LOCAL)
ffffffff81cf18ee-ffffffff81cf195f: acpi_processor_get_performance_states.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int acpi_processor_get_performance_states(struct acpi_processor *pr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_perflib.c (0)
Location: drivers/acpi/processor_perflib.c:285
Inline: False
Direct callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info
```
**Symbols:**

```
ffffffff818908d0-ffffffff81890c5e: acpi_processor_get_performance_states (STB_LOCAL)
ffffffff81eb986d-ffffffff81eb98d4: acpi_processor_get_performance_states.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int acpi_processor_get_performance_states(struct acpi_processor *pr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_perflib.c (ffffffff819d7920)
Location: drivers/acpi/processor_perflib.c:283
Inline: False
Direct callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info
```
**Symbols:**

```
ffffffff819d7920-ffffffff819d7d14: acpi_processor_get_performance_states (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int acpi_processor_get_performance_states(struct acpi_processor *pr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_perflib.c (ffffffff81a1f320)
Location: drivers/acpi/processor_perflib.c:305
Inline: False
Direct callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info
```
**Symbols:**

```
ffffffff81a1f320-ffffffff81a1f714: acpi_processor_get_performance_states (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int acpi_processor_get_performance_states(struct acpi_processor *pr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_perflib.c (ffffffff81a6a640)
Location: drivers/acpi/processor_perflib.c:305
Inline: False
Direct callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info
```
**Symbols:**

```
ffffffff81a6a640-ffffffff81a6aa34: acpi_processor_get_performance_states (STB_LOCAL)
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
In drivers/acpi/processor_perflib.c (ffff8000107a35bc)
Location: drivers/acpi/processor_perflib.c:289
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int acpi_processor_get_performance_states(struct acpi_processor *pr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_perflib.c (0)
Location: drivers/acpi/processor_perflib.c:289
Inline: False
Direct callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info
```
**Symbols:**

```
ffffffff816070b0-ffffffff81607380: acpi_processor_get_performance_states (STB_LOCAL)
ffffffff81607d6c-ffffffff81607de7: acpi_processor_get_performance_states.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int acpi_processor_get_performance_states(struct acpi_processor *pr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_perflib.c (0)
Location: drivers/acpi/processor_perflib.c:289
Inline: False
Direct callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info
```
**Symbols:**

```
ffffffff815f2180-ffffffff815f247a: acpi_processor_get_performance_states (STB_LOCAL)
ffffffff815f2e6c-ffffffff815f2eec: acpi_processor_get_performance_states.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int acpi_processor_get_performance_states(struct acpi_processor *pr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_perflib.c (0)
Location: drivers/acpi/processor_perflib.c:289
Inline: False
Direct callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info
```
**Symbols:**

```
ffffffff8162c160-ffffffff8162c555: acpi_processor_get_performance_states (STB_LOCAL)
ffffffff8162d027-ffffffff8162d0a2: acpi_processor_get_performance_states.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int acpi_processor_get_performance_states(struct acpi_processor *pr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_perflib.c (0)
Location: drivers/acpi/processor_perflib.c:289
Inline: False
Direct callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info
```
**Symbols:**

```
ffffffff81646000-ffffffff816463f5: acpi_processor_get_performance_states (STB_LOCAL)
ffffffff81646ec7-ffffffff81646f42: acpi_processor_get_performance_states.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
