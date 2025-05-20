# Function: <code>param_set_lid_init_state</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int param_set_lid_init_state(const char *val, struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/button.c (ffffffff814fa225)
Location: drivers/acpi/button.c:480
Inline: True
```
**Symbols:**

```
ffffffff814fa225-ffffffff814fa2c0: param_set_lid_init_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int param_set_lid_init_state(const char *val, struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/button.c (ffffffff8151cda5)
Location: drivers/acpi/button.c:559
Inline: True
```
**Symbols:**

```
ffffffff8151cda5-ffffffff8151ce40: param_set_lid_init_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int param_set_lid_init_state(const char *val, struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/button.c (ffffffff8152dc00)
Location: drivers/acpi/button.c:560
Inline: True
```
**Symbols:**

```
ffffffff8152dc00-ffffffff8152dcb6: param_set_lid_init_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int param_set_lid_init_state(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/button.c (ffffffff8158eb80)
Location: drivers/acpi/button.c:576
Inline: True
```
**Symbols:**

```
ffffffff8158eb80-ffffffff8158ec36: param_set_lid_init_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
int param_set_lid_init_state(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/button.c (0)
Location: drivers/acpi/button.c:586
Inline: True
```
**Symbols:**

```
ffffffff815c5eb0-ffffffff815c5f2d: param_set_lid_init_state (STB_LOCAL)
ffffffff815c64a6-ffffffff815c64ee: param_set_lid_init_state.cold.10 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
int param_set_lid_init_state(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/button.c (ffffffff815dfa66)
Location: drivers/acpi/button.c:588
Inline: True
```
**Symbols:**

```
ffffffff815df470-ffffffff815df4ed: param_set_lid_init_state (STB_LOCAL)
ffffffff815dfa66-ffffffff815dfaae: param_set_lid_init_state.cold.9 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int param_set_lid_init_state(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/button.c (ffffffff816115ee)
Location: drivers/acpi/button.c:578
Inline: True
```
**Symbols:**

```
ffffffff81610fd0-ffffffff8161105d: param_set_lid_init_state (STB_LOCAL)
ffffffff816115ee-ffffffff81611636: param_set_lid_init_state.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int param_set_lid_init_state(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/button.c (ffffffff81632a9e)
Location: drivers/acpi/button.c:600
Inline: True
```
**Symbols:**

```
ffffffff81632480-ffffffff8163250d: param_set_lid_init_state (STB_LOCAL)
ffffffff81632a9e-ffffffff81632ae6: param_set_lid_init_state.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int param_set_lid_init_state(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/button.c (0)
Location: drivers/acpi/button.c:593
Inline: False
```
**Symbols:**

```
ffffffff816de960-ffffffff816de987: param_set_lid_init_state (STB_LOCAL)
ffffffff816df573-ffffffff816df597: param_set_lid_init_state.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int param_set_lid_init_state(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/button.c (0)
Location: drivers/acpi/button.c:592
Inline: False
```
**Symbols:**

```
ffffffff816fc9a0-ffffffff816fc9c7: param_set_lid_init_state (STB_LOCAL)
ffffffff81c0280c-ffffffff81c02830: param_set_lid_init_state.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int param_set_lid_init_state(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/button.c (0)
Location: drivers/acpi/button.c:582
Inline: False
```
**Symbols:**

```
ffffffff816de780-ffffffff816de7a7: param_set_lid_init_state (STB_LOCAL)
ffffffff81bf4208-ffffffff81bf422c: param_set_lid_init_state.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int param_set_lid_init_state(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/button.c (ffffffff817568e0)
Location: drivers/acpi/button.c:593
Inline: False
```
**Symbols:**

```
ffffffff817568e0-ffffffff81756941: param_set_lid_init_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int param_set_lid_init_state(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/button.c (ffffffff81889a10)
Location: drivers/acpi/button.c:593
Inline: False
```
**Symbols:**

```
ffffffff81889a10-ffffffff81889a7b: param_set_lid_init_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int param_set_lid_init_state(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/button.c (ffffffff819d0400)
Location: drivers/acpi/button.c:592
Inline: False
```
**Symbols:**

```
ffffffff819d0400-ffffffff819d046f: param_set_lid_init_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int param_set_lid_init_state(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/button.c (ffffffff81a17810)
Location: drivers/acpi/button.c:668
Inline: False
```
**Symbols:**

```
ffffffff81a17810-ffffffff81a1787f: param_set_lid_init_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int param_set_lid_init_state(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/button.c (ffffffff81a62a40)
Location: drivers/acpi/button.c:678
Inline: False
```
**Symbols:**

```
ffffffff81a62a40-ffffffff81a62aaf: param_set_lid_init_state (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int param_set_lid_init_state(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/button.c (ffff8000107a0ab0)
Location: drivers/acpi/button.c:600
Inline: True
```
**Symbols:**

```
ffff8000107a0ab0-ffff8000107a0b80: param_set_lid_init_state (STB_LOCAL)
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
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
int param_set_lid_init_state(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/button.c (ffffffff81602f0e)
Location: drivers/acpi/button.c:600
Inline: True
```
**Symbols:**

```
ffffffff816028f0-ffffffff8160297d: param_set_lid_init_state (STB_LOCAL)
ffffffff81602f0e-ffffffff81602f56: param_set_lid_init_state.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
int param_set_lid_init_state(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/button.c (ffffffff815ee3be)
Location: drivers/acpi/button.c:600
Inline: True
```
**Symbols:**

```
ffffffff815edda0-ffffffff815ede2d: param_set_lid_init_state (STB_LOCAL)
ffffffff815ee3be-ffffffff815ee406: param_set_lid_init_state.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
int param_set_lid_init_state(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/button.c (ffffffff81626d7e)
Location: drivers/acpi/button.c:600
Inline: True
```
**Symbols:**

```
ffffffff81626760-ffffffff816267ed: param_set_lid_init_state (STB_LOCAL)
ffffffff81626d7e-ffffffff81626dc6: param_set_lid_init_state.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
int param_set_lid_init_state(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/button.c (ffffffff81640c2e)
Location: drivers/acpi/button.c:600
Inline: True
```
**Symbols:**

```
ffffffff81640610-ffffffff8164069d: param_set_lid_init_state (STB_LOCAL)
ffffffff81640c2e-ffffffff81640c76: param_set_lid_init_state.cold (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct kernel_param *kp</code> ➡️ <code>const struct kernel_param *kp</code>
</li>
</ul>
</details>
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
