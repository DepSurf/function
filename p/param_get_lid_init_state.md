# Function: <code>param_get_lid_init_state</code>

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
int param_get_lid_init_state(char *buffer, struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/button.c (ffffffff814fa0c5)
Location: drivers/acpi/button.c:498
Inline: False
```
**Symbols:**

```
ffffffff814fa0c5-ffffffff814fa120: param_get_lid_init_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int param_get_lid_init_state(char *buffer, struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/button.c (ffffffff8151cc48)
Location: drivers/acpi/button.c:577
Inline: False
```
**Symbols:**

```
ffffffff8151cc48-ffffffff8151cca3: param_get_lid_init_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int param_get_lid_init_state(char *buffer, struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/button.c (ffffffff8152db80)
Location: drivers/acpi/button.c:578
Inline: True
```
**Symbols:**

```
ffffffff8152db80-ffffffff8152dbf3: param_get_lid_init_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int param_get_lid_init_state(char *buffer, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/button.c (ffffffff8158eb00)
Location: drivers/acpi/button.c:595
Inline: True
```
**Symbols:**

```
ffffffff8158eb00-ffffffff8158eb73: param_get_lid_init_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int param_get_lid_init_state(char *buffer, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/button.c (ffffffff815c5e30)
Location: drivers/acpi/button.c:605
Inline: True
```
**Symbols:**

```
ffffffff815c5e30-ffffffff815c5ea5: param_get_lid_init_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int param_get_lid_init_state(char *buffer, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/button.c (ffffffff815df3f0)
Location: drivers/acpi/button.c:607
Inline: True
```
**Symbols:**

```
ffffffff815df3f0-ffffffff815df465: param_get_lid_init_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int param_get_lid_init_state(char *buffer, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/button.c (ffffffff81610f50)
Location: drivers/acpi/button.c:597
Inline: True
```
**Symbols:**

```
ffffffff81610f50-ffffffff81610fc5: param_get_lid_init_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int param_get_lid_init_state(char *buffer, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/button.c (ffffffff81632400)
Location: drivers/acpi/button.c:619
Inline: True
```
**Symbols:**

```
ffffffff81632400-ffffffff81632475: param_get_lid_init_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int param_get_lid_init_state(char *buf, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/button.c (ffffffff816de8d0)
Location: drivers/acpi/button.c:607
Inline: False
```
**Symbols:**

```
ffffffff816de8d0-ffffffff816de95c: param_get_lid_init_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int param_get_lid_init_state(char *buf, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/button.c (ffffffff816fc910)
Location: drivers/acpi/button.c:606
Inline: False
```
**Symbols:**

```
ffffffff816fc910-ffffffff816fc99c: param_get_lid_init_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int param_get_lid_init_state(char *buf, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/button.c (ffffffff816de6f0)
Location: drivers/acpi/button.c:596
Inline: False
```
**Symbols:**

```
ffffffff816de6f0-ffffffff816de77c: param_get_lid_init_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int param_get_lid_init_state(char *buf, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/button.c (ffffffff81756830)
Location: drivers/acpi/button.c:607
Inline: False
```
**Symbols:**

```
ffffffff81756830-ffffffff817568d9: param_get_lid_init_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int param_get_lid_init_state(char *buf, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/button.c (ffffffff81889950)
Location: drivers/acpi/button.c:607
Inline: False
```
**Symbols:**

```
ffffffff81889950-ffffffff81889a03: param_get_lid_init_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int param_get_lid_init_state(char *buf, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/button.c (ffffffff819d0330)
Location: drivers/acpi/button.c:606
Inline: False
```
**Symbols:**

```
ffffffff819d0330-ffffffff819d03e3: param_get_lid_init_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int param_get_lid_init_state(char *buf, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/button.c (ffffffff81a17740)
Location: drivers/acpi/button.c:682
Inline: False
```
**Symbols:**

```
ffffffff81a17740-ffffffff81a177f3: param_get_lid_init_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int param_get_lid_init_state(char *buf, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/button.c (ffffffff81a62970)
Location: drivers/acpi/button.c:692
Inline: False
```
**Symbols:**

```
ffffffff81a62970-ffffffff81a62a23: param_get_lid_init_state (STB_LOCAL)
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
int param_get_lid_init_state(char *buffer, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/button.c (ffff8000107a09f8)
Location: drivers/acpi/button.c:619
Inline: True
```
**Symbols:**

```
ffff8000107a09f8-ffff8000107a0aac: param_get_lid_init_state (STB_LOCAL)
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int param_get_lid_init_state(char *buffer, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/button.c (ffffffff81602870)
Location: drivers/acpi/button.c:619
Inline: True
```
**Symbols:**

```
ffffffff81602870-ffffffff816028e5: param_get_lid_init_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int param_get_lid_init_state(char *buffer, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/button.c (ffffffff815edd20)
Location: drivers/acpi/button.c:619
Inline: True
```
**Symbols:**

```
ffffffff815edd20-ffffffff815edd95: param_get_lid_init_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int param_get_lid_init_state(char *buffer, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/button.c (ffffffff816266e0)
Location: drivers/acpi/button.c:619
Inline: True
```
**Symbols:**

```
ffffffff816266e0-ffffffff81626755: param_get_lid_init_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int param_get_lid_init_state(char *buffer, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/button.c (ffffffff81640590)
Location: drivers/acpi/button.c:619
Inline: True
```
**Symbols:**

```
ffffffff81640590-ffffffff81640605: param_get_lid_init_state (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>char *buf</code>
</li>
<li>
<b>Param removed. </b>
<code>char *buffer</code>
</li>
</ul>
</details>
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
