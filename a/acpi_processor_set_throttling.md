# Function: <code>acpi_processor_set_throttling</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int acpi_processor_set_throttling(struct acpi_processor *pr, int state, bool force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_throttling.c (ffffffff814adc7f)
Location: drivers/acpi/processor_throttling.c:1074
Inline: False
Direct callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_tstate_has_changed
  - drivers/acpi/processor_throttling.c:acpi_processor_reevaluate_tstate
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_ptc
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_thermal.c:processor_set_cur_state
  - drivers/acpi/processor_thermal.c:processor_set_cur_state
```
**Symbols:**

```
ffffffff814adc7f-ffffffff814adec4: acpi_processor_set_throttling (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int acpi_processor_set_throttling(struct acpi_processor *pr, int state, bool force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_throttling.c (ffffffff814fd653)
Location: drivers/acpi/processor_throttling.c:1083
Inline: False
Direct callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_ptc
  - drivers/acpi/processor_throttling.c:acpi_processor_reevaluate_tstate
  - drivers/acpi/processor_throttling.c:acpi_processor_tstate_has_changed
  - drivers/acpi/processor_thermal.c:processor_set_cur_state
  - drivers/acpi/processor_thermal.c:processor_set_cur_state
```
**Symbols:**

```
ffffffff814fd653-ffffffff814fd890: acpi_processor_set_throttling (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int acpi_processor_set_throttling(struct acpi_processor *pr, int state, bool force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_throttling.c (ffffffff8152034b)
Location: drivers/acpi/processor_throttling.c:1083
Inline: False
Direct callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_ptc
  - drivers/acpi/processor_throttling.c:acpi_processor_reevaluate_tstate
  - drivers/acpi/processor_throttling.c:acpi_processor_tstate_has_changed
  - drivers/acpi/processor_thermal.c:processor_set_cur_state
  - drivers/acpi/processor_thermal.c:processor_set_cur_state
```
**Symbols:**

```
ffffffff8152034b-ffffffff8152058a: acpi_processor_set_throttling (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int acpi_processor_set_throttling(struct acpi_processor *pr, int state, bool force);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_throttling.c (ffffffff8153224f)
Location: drivers/acpi/processor_throttling.c:1189
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_reevaluate_tstate
  - drivers/acpi/processor_throttling.c:acpi_processor_tstate_has_changed
Direct callers:
  - drivers/acpi/processor_thermal.c:processor_set_cur_state
  - drivers/acpi/processor_thermal.c:processor_set_cur_state
```
**Symbols:**

```
ffffffff81531e30-ffffffff81531e45: acpi_processor_set_throttling (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int acpi_processor_set_throttling(struct acpi_processor *pr, int state, bool force);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_throttling.c (ffffffff815938c8)
Location: drivers/acpi/processor_throttling.c:1189
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_reevaluate_tstate
  - drivers/acpi/processor_throttling.c:acpi_processor_tstate_has_changed
Direct callers:
  - drivers/acpi/processor_thermal.c:processor_set_cur_state
  - drivers/acpi/processor_thermal.c:processor_set_cur_state
```
**Symbols:**

```
ffffffff81593190-ffffffff815931a5: acpi_processor_set_throttling (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int acpi_processor_set_throttling(struct acpi_processor *pr, int state, bool force);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_throttling.c (ffffffff815cab2a)
Location: drivers/acpi/processor_throttling.c:1190
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_reevaluate_tstate
  - drivers/acpi/processor_throttling.c:acpi_processor_tstate_has_changed
Direct callers:
  - drivers/acpi/processor_thermal.c:processor_set_cur_state
  - drivers/acpi/processor_thermal.c:processor_set_cur_state
```
**Symbols:**

```
ffffffff815ca580-ffffffff815ca595: acpi_processor_set_throttling (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int acpi_processor_set_throttling(struct acpi_processor *pr, int state, bool force);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_throttling.c (ffffffff815e410a)
Location: drivers/acpi/processor_throttling.c:1190
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_reevaluate_tstate
  - drivers/acpi/processor_throttling.c:acpi_processor_tstate_has_changed
Direct callers:
  - drivers/acpi/processor_thermal.c:processor_set_cur_state
  - drivers/acpi/processor_thermal.c:processor_set_cur_state
```
**Symbols:**

```
ffffffff815e3b60-ffffffff815e3b75: acpi_processor_set_throttling (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int acpi_processor_set_throttling(struct acpi_processor *pr, int state, bool force);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_throttling.c (ffffffff81615c1d)
Location: drivers/acpi/processor_throttling.c:1177
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_reevaluate_tstate
  - drivers/acpi/processor_throttling.c:acpi_processor_tstate_has_changed
Direct callers:
  - drivers/acpi/processor_thermal.c:processor_set_cur_state
  - drivers/acpi/processor_thermal.c:processor_set_cur_state
```
**Symbols:**

```
ffffffff81615730-ffffffff81615745: acpi_processor_set_throttling (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int acpi_processor_set_throttling(struct acpi_processor *pr, int state, bool force);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_throttling.c (ffffffff8163710d)
Location: drivers/acpi/processor_throttling.c:1177
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_reevaluate_tstate
  - drivers/acpi/processor_throttling.c:acpi_processor_tstate_has_changed
Direct callers:
  - drivers/acpi/processor_thermal.c:processor_set_cur_state
  - drivers/acpi/processor_thermal.c:processor_set_cur_state
```
**Symbols:**

```
ffffffff81636c20-ffffffff81636c35: acpi_processor_set_throttling (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int acpi_processor_set_throttling(struct acpi_processor *pr, int state, bool force);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_throttling.c (ffffffff816e3f8e)
Location: drivers/acpi/processor_throttling.c:1170
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_reevaluate_tstate
  - drivers/acpi/processor_throttling.c:acpi_processor_tstate_has_changed
Direct callers:
  - drivers/acpi/processor_thermal.c:processor_set_cur_state
  - drivers/acpi/processor_thermal.c:processor_set_cur_state
```
**Symbols:**

```
ffffffff816e3e40-ffffffff816e3e55: acpi_processor_set_throttling (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int acpi_processor_set_throttling(struct acpi_processor *pr, int state, bool force);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_throttling.c (ffffffff81701bde)
Location: drivers/acpi/processor_throttling.c:1169
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_reevaluate_tstate
  - drivers/acpi/processor_throttling.c:acpi_processor_tstate_has_changed
Direct callers:
  - drivers/acpi/processor_thermal.c:processor_set_cur_state
  - drivers/acpi/processor_thermal.c:processor_set_cur_state
```
**Symbols:**

```
ffffffff81701a90-ffffffff81701aa5: acpi_processor_set_throttling (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int acpi_processor_set_throttling(struct acpi_processor *pr, int state, bool force);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_throttling.c (ffffffff816e3506)
Location: drivers/acpi/processor_throttling.c:1165
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_reevaluate_tstate
  - drivers/acpi/processor_throttling.c:acpi_processor_tstate_has_changed
Direct callers:
  - drivers/acpi/processor_thermal.c:processor_set_cur_state
  - drivers/acpi/processor_thermal.c:processor_set_cur_state
```
**Symbols:**

```
ffffffff816e32e0-ffffffff816e32f5: acpi_processor_set_throttling (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int acpi_processor_set_throttling(struct acpi_processor *pr, int state, bool force);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_throttling.c (ffffffff8175bf7b)
Location: drivers/acpi/processor_throttling.c:1155
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_reevaluate_tstate
  - drivers/acpi/processor_throttling.c:acpi_processor_tstate_has_changed
Direct callers:
  - drivers/acpi/processor_thermal.c:processor_set_cur_state
  - drivers/acpi/processor_thermal.c:processor_set_cur_state
```
**Symbols:**

```
ffffffff8175bd30-ffffffff8175bd45: acpi_processor_set_throttling (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int acpi_processor_set_throttling(struct acpi_processor *pr, int state, bool force);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_throttling.c (ffffffff8188f52e)
Location: drivers/acpi/processor_throttling.c:1155
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_reevaluate_tstate
  - drivers/acpi/processor_throttling.c:acpi_processor_tstate_has_changed
Direct callers:
  - drivers/acpi/processor_thermal.c:processor_set_cur_state
  - drivers/acpi/processor_thermal.c:processor_set_cur_state
```
**Symbols:**

```
ffffffff8188f3a0-ffffffff8188f3c1: acpi_processor_set_throttling (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int acpi_processor_set_throttling(struct acpi_processor *pr, int state, bool force);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_throttling.c (ffffffff819d71ea)
Location: drivers/acpi/processor_throttling.c:1153
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_reevaluate_tstate
  - drivers/acpi/processor_throttling.c:acpi_processor_tstate_has_changed
Direct callers:
  - drivers/acpi/processor_thermal.c:processor_set_cur_state
  - drivers/acpi/processor_thermal.c:processor_set_cur_state
```
**Symbols:**

```
ffffffff819d7050-ffffffff819d7071: acpi_processor_set_throttling (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int acpi_processor_set_throttling(struct acpi_processor *pr, int state, bool force);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_throttling.c (ffffffff81a1ebaa)
Location: drivers/acpi/processor_throttling.c:1153
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_reevaluate_tstate
  - drivers/acpi/processor_throttling.c:acpi_processor_tstate_has_changed
Direct callers:
  - drivers/acpi/processor_thermal.c:processor_set_cur_state
  - drivers/acpi/processor_thermal.c:processor_set_cur_state
```
**Symbols:**

```
ffffffff81a1ea10-ffffffff81a1ea31: acpi_processor_set_throttling (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int acpi_processor_set_throttling(struct acpi_processor *pr, int state, bool force);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_throttling.c (ffffffff81a69eca)
Location: drivers/acpi/processor_throttling.c:1153
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_reevaluate_tstate
  - drivers/acpi/processor_throttling.c:acpi_processor_tstate_has_changed
Direct callers:
  - drivers/acpi/processor_thermal.c:processor_set_cur_state
  - drivers/acpi/processor_thermal.c:processor_set_cur_state
```
**Symbols:**

```
ffffffff81a69d30-ffffffff81a69d51: acpi_processor_set_throttling (STB_GLOBAL)
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int acpi_processor_set_throttling(struct acpi_processor *pr, int state, bool force);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_throttling.c (ffffffff81606575)
Location: drivers/acpi/processor_throttling.c:1177
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_reevaluate_tstate
  - drivers/acpi/processor_throttling.c:acpi_processor_tstate_has_changed
Direct callers:
  - drivers/acpi/processor_thermal.c:processor_set_cur_state
  - drivers/acpi/processor_thermal.c:processor_set_cur_state
```
**Symbols:**

```
ffffffff816060b0-ffffffff816060c5: acpi_processor_set_throttling (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int acpi_processor_set_throttling(struct acpi_processor *pr, int state, bool force);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_throttling.c (ffffffff815f1645)
Location: drivers/acpi/processor_throttling.c:1177
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_reevaluate_tstate
  - drivers/acpi/processor_throttling.c:acpi_processor_tstate_has_changed
Direct callers:
  - drivers/acpi/processor_thermal.c:processor_set_cur_state
  - drivers/acpi/processor_thermal.c:processor_set_cur_state
```
**Symbols:**

```
ffffffff815f1180-ffffffff815f1195: acpi_processor_set_throttling (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int acpi_processor_set_throttling(struct acpi_processor *pr, int state, bool force);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_throttling.c (ffffffff8162b3ed)
Location: drivers/acpi/processor_throttling.c:1177
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_reevaluate_tstate
  - drivers/acpi/processor_throttling.c:acpi_processor_tstate_has_changed
Direct callers:
  - drivers/acpi/processor_thermal.c:processor_set_cur_state
  - drivers/acpi/processor_thermal.c:processor_set_cur_state
```
**Symbols:**

```
ffffffff8162af00-ffffffff8162af15: acpi_processor_set_throttling (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int acpi_processor_set_throttling(struct acpi_processor *pr, int state, bool force);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_throttling.c (ffffffff8164528d)
Location: drivers/acpi/processor_throttling.c:1177
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_reevaluate_tstate
  - drivers/acpi/processor_throttling.c:acpi_processor_tstate_has_changed
Direct callers:
  - drivers/acpi/processor_thermal.c:processor_set_cur_state
  - drivers/acpi/processor_thermal.c:processor_set_cur_state
```
**Symbols:**

```
ffffffff81644da0-ffffffff81644db5: acpi_processor_set_throttling (STB_GLOBAL)
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
