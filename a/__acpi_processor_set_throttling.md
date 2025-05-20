# Function: <code>__acpi_processor_set_throttling</code>

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
int __acpi_processor_set_throttling(struct acpi_processor *pr, int state, bool force, bool direct);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_throttling.c (ffffffff815316a0)
Location: drivers/acpi/processor_throttling.c:1086
Inline: False
Direct callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_ptc
  - drivers/acpi/processor_throttling.c:acpi_processor_reevaluate_tstate
  - drivers/acpi/processor_throttling.c:acpi_processor_tstate_has_changed
```
**Symbols:**

```
ffffffff815316a0-ffffffff815318e0: __acpi_processor_set_throttling (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __acpi_processor_set_throttling(struct acpi_processor *pr, int state, bool force, bool direct);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_throttling.c (ffffffff815926f0)
Location: drivers/acpi/processor_throttling.c:1086
Inline: False
Direct callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_ptc
  - drivers/acpi/processor_throttling.c:acpi_processor_reevaluate_tstate
  - drivers/acpi/processor_throttling.c:acpi_processor_tstate_has_changed
```
**Symbols:**

```
ffffffff815926f0-ffffffff81592971: __acpi_processor_set_throttling (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __acpi_processor_set_throttling(struct acpi_processor *pr, int state, bool force, bool direct);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_throttling.c (ffffffff815c9c50)
Location: drivers/acpi/processor_throttling.c:1087
Inline: False
Direct callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_ptc
  - drivers/acpi/processor_throttling.c:acpi_processor_reevaluate_tstate
  - drivers/acpi/processor_throttling.c:acpi_processor_tstate_has_changed
```
**Symbols:**

```
ffffffff815c9c50-ffffffff815c9ed1: __acpi_processor_set_throttling (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __acpi_processor_set_throttling(struct acpi_processor *pr, int state, bool force, bool direct);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_throttling.c (ffffffff815e3230)
Location: drivers/acpi/processor_throttling.c:1087
Inline: False
Direct callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_ptc
  - drivers/acpi/processor_throttling.c:acpi_processor_reevaluate_tstate
  - drivers/acpi/processor_throttling.c:acpi_processor_tstate_has_changed
```
**Symbols:**

```
ffffffff815e3230-ffffffff815e34b1: __acpi_processor_set_throttling (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __acpi_processor_set_throttling(struct acpi_processor *pr, int state, bool force, bool direct);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_throttling.c (ffffffff81614de0)
Location: drivers/acpi/processor_throttling.c:1074
Inline: False
Direct callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_ptc
  - drivers/acpi/processor_throttling.c:acpi_processor_reevaluate_tstate
  - drivers/acpi/processor_throttling.c:acpi_processor_tstate_has_changed
```
**Symbols:**

```
ffffffff81614de0-ffffffff8161504d: __acpi_processor_set_throttling (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __acpi_processor_set_throttling(struct acpi_processor *pr, int state, bool force, bool direct);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_throttling.c (ffffffff816362d0)
Location: drivers/acpi/processor_throttling.c:1074
Inline: False
Direct callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_ptc
  - drivers/acpi/processor_throttling.c:acpi_processor_reevaluate_tstate
  - drivers/acpi/processor_throttling.c:acpi_processor_tstate_has_changed
```
**Symbols:**

```
ffffffff816362d0-ffffffff8163653d: __acpi_processor_set_throttling (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __acpi_processor_set_throttling(struct acpi_processor *pr, int state, bool force, bool direct);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_throttling.c (ffffffff816e3430)
Location: drivers/acpi/processor_throttling.c:1067
Inline: False
Direct callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_ptc
  - drivers/acpi/processor_throttling.c:acpi_processor_reevaluate_tstate
  - drivers/acpi/processor_throttling.c:acpi_processor_tstate_has_changed
```
**Symbols:**

```
ffffffff816e3430-ffffffff816e3730: __acpi_processor_set_throttling (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __acpi_processor_set_throttling(struct acpi_processor *pr, int state, bool force, bool direct);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_throttling.c (ffffffff81701090)
Location: drivers/acpi/processor_throttling.c:1066
Inline: False
Direct callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_ptc
  - drivers/acpi/processor_throttling.c:acpi_processor_reevaluate_tstate
  - drivers/acpi/processor_throttling.c:acpi_processor_tstate_has_changed
```
**Symbols:**

```
ffffffff81701090-ffffffff81701390: __acpi_processor_set_throttling (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __acpi_processor_set_throttling(struct acpi_processor *pr, int state, bool force, bool direct);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_throttling.c (ffffffff816e2810)
Location: drivers/acpi/processor_throttling.c:1063
Inline: False
Direct callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_ptc
  - drivers/acpi/processor_throttling.c:acpi_processor_reevaluate_tstate
  - drivers/acpi/processor_throttling.c:acpi_processor_tstate_has_changed
```
**Symbols:**

```
ffffffff816e2810-ffffffff816e2b48: __acpi_processor_set_throttling (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int __acpi_processor_set_throttling(struct acpi_processor *pr, int state, bool force, bool direct);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_throttling.c (0)
Location: drivers/acpi/processor_throttling.c:1053
Inline: False
Direct callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_ptc
  - drivers/acpi/processor_throttling.c:acpi_processor_reevaluate_tstate
  - drivers/acpi/processor_throttling.c:acpi_processor_tstate_has_changed
```
**Symbols:**

```
ffffffff8175b450-ffffffff8175b7c3: __acpi_processor_set_throttling (STB_LOCAL)
ffffffff81cf162f-ffffffff81cf166a: __acpi_processor_set_throttling.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int __acpi_processor_set_throttling(struct acpi_processor *pr, int state, bool force, bool direct);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_throttling.c (0)
Location: drivers/acpi/processor_throttling.c:1053
Inline: False
Direct callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_ptc
  - drivers/acpi/processor_throttling.c:acpi_processor_reevaluate_tstate
  - drivers/acpi/processor_throttling.c:acpi_processor_tstate_has_changed
```
**Symbols:**

```
ffffffff8188ed00-ffffffff8188f0ab: __acpi_processor_set_throttling (STB_LOCAL)
ffffffff81eb967d-ffffffff81eb96b8: __acpi_processor_set_throttling.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int __acpi_processor_set_throttling(struct acpi_processor *pr, int state, bool force, bool direct);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_throttling.c (0)
Location: drivers/acpi/processor_throttling.c:1051
Inline: False
Direct callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_ptc
  - drivers/acpi/processor_throttling.c:acpi_processor_reevaluate_tstate
  - drivers/acpi/processor_throttling.c:acpi_processor_tstate_has_changed
```
**Symbols:**

```
ffffffff819d6940-ffffffff819d6cbd: __acpi_processor_set_throttling (STB_LOCAL)
ffffffff82092764-ffffffff8209279d: __acpi_processor_set_throttling.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int __acpi_processor_set_throttling(struct acpi_processor *pr, int state, bool force, bool direct);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_throttling.c (0)
Location: drivers/acpi/processor_throttling.c:1051
Inline: False
Direct callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_ptc
  - drivers/acpi/processor_throttling.c:acpi_processor_reevaluate_tstate
  - drivers/acpi/processor_throttling.c:acpi_processor_tstate_has_changed
```
**Symbols:**

```
ffffffff81a1e300-ffffffff81a1e67d: __acpi_processor_set_throttling (STB_LOCAL)
ffffffff821130ae-ffffffff821130e7: __acpi_processor_set_throttling.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int __acpi_processor_set_throttling(struct acpi_processor *pr, int state, bool force, bool direct);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_throttling.c (0)
Location: drivers/acpi/processor_throttling.c:1051
Inline: False
Direct callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_ptc
  - drivers/acpi/processor_throttling.c:acpi_processor_reevaluate_tstate
  - drivers/acpi/processor_throttling.c:acpi_processor_tstate_has_changed
```
**Symbols:**

```
ffffffff81a69610-ffffffff81a6999f: __acpi_processor_set_throttling (STB_LOCAL)
ffffffff821f0e02-ffffffff821f0e3b: __acpi_processor_set_throttling.cold (STB_LOCAL)
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
int __acpi_processor_set_throttling(struct acpi_processor *pr, int state, bool force, bool direct);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_throttling.c (0)
Location: drivers/acpi/processor_throttling.c:1074
Inline: False
Direct callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_ptc
  - drivers/acpi/processor_throttling.c:acpi_processor_reevaluate_tstate
  - drivers/acpi/processor_throttling.c:acpi_processor_tstate_has_changed
```
**Symbols:**

```
ffffffff81605890-ffffffff81605ab1: __acpi_processor_set_throttling (STB_LOCAL)
ffffffff81606659-ffffffff81606683: __acpi_processor_set_throttling.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int __acpi_processor_set_throttling(struct acpi_processor *pr, int state, bool force, bool direct);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_throttling.c (0)
Location: drivers/acpi/processor_throttling.c:1074
Inline: False
Direct callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_ptc
  - drivers/acpi/processor_throttling.c:acpi_processor_reevaluate_tstate
  - drivers/acpi/processor_throttling.c:acpi_processor_tstate_has_changed
```
**Symbols:**

```
ffffffff815f09e0-ffffffff815f0c01: __acpi_processor_set_throttling (STB_LOCAL)
ffffffff815f1729-ffffffff815f1753: __acpi_processor_set_throttling.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __acpi_processor_set_throttling(struct acpi_processor *pr, int state, bool force, bool direct);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_throttling.c (ffffffff8162a5b0)
Location: drivers/acpi/processor_throttling.c:1074
Inline: False
Direct callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_ptc
  - drivers/acpi/processor_throttling.c:acpi_processor_reevaluate_tstate
  - drivers/acpi/processor_throttling.c:acpi_processor_tstate_has_changed
```
**Symbols:**

```
ffffffff8162a5b0-ffffffff8162a81d: __acpi_processor_set_throttling (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __acpi_processor_set_throttling(struct acpi_processor *pr, int state, bool force, bool direct);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_throttling.c (ffffffff81644450)
Location: drivers/acpi/processor_throttling.c:1074
Inline: False
Direct callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_ptc
  - drivers/acpi/processor_throttling.c:acpi_processor_reevaluate_tstate
  - drivers/acpi/processor_throttling.c:acpi_processor_tstate_has_changed
```
**Symbols:**

```
ffffffff81644450-ffffffff816446bd: __acpi_processor_set_throttling (STB_LOCAL)
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
