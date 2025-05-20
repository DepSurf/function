# Function: <code>param_set_event_clearing</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int param_set_event_clearing(const char *val, struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff81483185)
Location: drivers/acpi/ec.c:1613
Inline: True
```
**Symbols:**

```
ffffffff81483185-ffffffff8148321f: param_set_event_clearing (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int param_set_event_clearing(const char *val, struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff814d1cde)
Location: drivers/acpi/ec.c:1622
Inline: True
```
**Symbols:**

```
ffffffff814d1cde-ffffffff814d1d82: param_set_event_clearing (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int param_set_event_clearing(const char *val, struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff814f3fcb)
Location: drivers/acpi/ec.c:1913
Inline: True
```
**Symbols:**

```
ffffffff814f3fcb-ffffffff814f406f: param_set_event_clearing (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int param_set_event_clearing(const char *val, struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff81501f20)
Location: drivers/acpi/ec.c:1936
Inline: True
```
**Symbols:**

```
ffffffff81501f20-ffffffff81501fdf: param_set_event_clearing (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int param_set_event_clearing(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff815441b0)
Location: drivers/acpi/ec.c:1959
Inline: True
```
**Symbols:**

```
ffffffff815441b0-ffffffff8154426f: param_set_event_clearing (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
int param_set_event_clearing(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/ec.c (0)
Location: drivers/acpi/ec.c:1971
Inline: True
```
**Symbols:**

```
ffffffff8157a230-ffffffff8157a2ad: param_set_event_clearing (STB_LOCAL)
ffffffff8157c3a2-ffffffff8157c3f3: param_set_event_clearing.cold.27 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
int param_set_event_clearing(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/ec.c (ffffffff81594082)
Location: drivers/acpi/ec.c:1983
Inline: True
```
**Symbols:**

```
ffffffff815920d0-ffffffff8159214d: param_set_event_clearing (STB_LOCAL)
ffffffff81594082-ffffffff815940d3: param_set_event_clearing.cold.26 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int param_set_event_clearing(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/ec.c (ffffffff815c50d2)
Location: drivers/acpi/ec.c:1986
Inline: True
```
**Symbols:**

```
ffffffff815c2fc0-ffffffff815c304d: param_set_event_clearing (STB_LOCAL)
ffffffff815c50d2-ffffffff815c5123: param_set_event_clearing.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int param_set_event_clearing(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/ec.c (ffffffff815e6300)
Location: drivers/acpi/ec.c:1986
Inline: True
```
**Symbols:**

```
ffffffff815e42f0-ffffffff815e437d: param_set_event_clearing (STB_LOCAL)
ffffffff815e6300-ffffffff815e6351: param_set_event_clearing.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int param_set_event_clearing(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/ec.c (0)
Location: drivers/acpi/ec.c:2038
Inline: False
```
**Symbols:**

```
ffffffff8168f110-ffffffff8168f19f: param_set_event_clearing (STB_LOCAL)
ffffffff81691937-ffffffff81691988: param_set_event_clearing.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int param_set_event_clearing(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/ec.c (0)
Location: drivers/acpi/ec.c:2021
Inline: False
```
**Symbols:**

```
ffffffff816acde0-ffffffff816ace6f: param_set_event_clearing (STB_LOCAL)
ffffffff81c01578-ffffffff81c015c9: param_set_event_clearing.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int param_set_event_clearing(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/ec.c (0)
Location: drivers/acpi/ec.c:2056
Inline: False
```
**Symbols:**

```
ffffffff8168f410-ffffffff8168f486: param_set_event_clearing (STB_LOCAL)
ffffffff81bf2e0e-ffffffff81bf2e62: param_set_event_clearing.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int param_set_event_clearing(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/ec.c (0)
Location: drivers/acpi/ec.c:2085
Inline: False
```
**Symbols:**

```
ffffffff81704d00-ffffffff81704d76: param_set_event_clearing (STB_LOCAL)
ffffffff81cef81e-ffffffff81cef872: param_set_event_clearing.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int param_set_event_clearing(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/ec.c (0)
Location: drivers/acpi/ec.c:2068
Inline: False
```
**Symbols:**

```
ffffffff81832f20-ffffffff81832f93: param_set_event_clearing (STB_LOCAL)
ffffffff81eb7386-ffffffff81eb73d1: param_set_event_clearing.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int param_set_event_clearing(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff819668e0)
Location: drivers/acpi/ec.c:2106
Inline: False
```
**Symbols:**

```
ffffffff819668e0-ffffffff81966991: param_set_event_clearing (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int param_set_event_clearing(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff819ace70)
Location: drivers/acpi/ec.c:2125
Inline: False
```
**Symbols:**

```
ffffffff819ace70-ffffffff819acf21: param_set_event_clearing (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int param_set_event_clearing(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff819f7290)
Location: drivers/acpi/ec.c:2146
Inline: False
```
**Symbols:**

```
ffffffff819f7290-ffffffff819f7341: param_set_event_clearing (STB_LOCAL)
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
int param_set_event_clearing(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffff8000107705a8)
Location: drivers/acpi/ec.c:1986
Inline: True
```
**Symbols:**

```
ffff8000107705a8-ffff800010770678: param_set_event_clearing (STB_LOCAL)
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
int param_set_event_clearing(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/ec.c (ffffffff815d81c0)
Location: drivers/acpi/ec.c:1986
Inline: True
```
**Symbols:**

```
ffffffff815d61e0-ffffffff815d626d: param_set_event_clearing (STB_LOCAL)
ffffffff815d81c0-ffffffff815d8211: param_set_event_clearing.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
int param_set_event_clearing(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/ec.c (ffffffff815c1db0)
Location: drivers/acpi/ec.c:1986
Inline: True
```
**Symbols:**

```
ffffffff815bfda0-ffffffff815bfe2d: param_set_event_clearing (STB_LOCAL)
ffffffff815c1db0-ffffffff815c1e01: param_set_event_clearing.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
int param_set_event_clearing(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/ec.c (ffffffff815da5e0)
Location: drivers/acpi/ec.c:1986
Inline: True
```
**Symbols:**

```
ffffffff815d85d0-ffffffff815d865d: param_set_event_clearing (STB_LOCAL)
ffffffff815da5e0-ffffffff815da631: param_set_event_clearing.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
int param_set_event_clearing(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/ec.c (ffffffff815f44a0)
Location: drivers/acpi/ec.c:1986
Inline: True
```
**Symbols:**

```
ffffffff815f2490-ffffffff815f251d: param_set_event_clearing (STB_LOCAL)
ffffffff815f44a0-ffffffff815f44f1: param_set_event_clearing.cold (STB_LOCAL)
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
