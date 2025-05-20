# Function: <code>rdt_parse_param</code>

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
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int rdt_parse_param(struct fs_context *fc, struct fs_parameter *param);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105a360)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:2054
Inline: False
```
**Symbols:**

```
ffffffff8105a360-ffffffff8105a3e5: rdt_parse_param (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int rdt_parse_param(struct fs_context *fc, struct fs_parameter *param);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105b230)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:2052
Inline: False
```
**Symbols:**

```
ffffffff8105b230-ffffffff8105b2b5: rdt_parse_param (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int rdt_parse_param(struct fs_context *fc, struct fs_parameter *param);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105fa20)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:2151
Inline: False
```
**Symbols:**

```
ffffffff8105fa20-ffffffff8105faa8: rdt_parse_param (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int rdt_parse_param(struct fs_context *fc, struct fs_parameter *param);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105de10)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:2199
Inline: False
```
**Symbols:**

```
ffffffff8105de10-ffffffff8105de98: rdt_parse_param (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int rdt_parse_param(struct fs_context *fc, struct fs_parameter *param);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105e630)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:2199
Inline: False
```
**Symbols:**

```
ffffffff8105e630-ffffffff8105e6b8: rdt_parse_param (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int rdt_parse_param(struct fs_context *fc, struct fs_parameter *param);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81067db0)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:2246
Inline: False
```
**Symbols:**

```
ffffffff81067db0-ffffffff81067e38: rdt_parse_param (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int rdt_parse_param(struct fs_context *fc, struct fs_parameter *param);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81074c10)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:2246
Inline: False
```
**Symbols:**

```
ffffffff81074c10-ffffffff81074cb6: rdt_parse_param (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int rdt_parse_param(struct fs_context *fc, struct fs_parameter *param);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:2286
Inline: False
```
**Symbols:**

```
ffffffff81086de0-ffffffff81086ead: rdt_parse_param (STB_LOCAL)
ffffffff820531fa-ffffffff8205320f: rdt_parse_param.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int rdt_parse_param(struct fs_context *fc, struct fs_parameter *param);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:2572
Inline: False
```
**Symbols:**

```
ffffffff81089890-ffffffff8108995d: rdt_parse_param (STB_LOCAL)
ffffffff820d1807-ffffffff820d181c: rdt_parse_param.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int rdt_parse_param(struct fs_context *fc, struct fs_parameter *param);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:2698
Inline: False
```
**Symbols:**

```
ffffffff8108e520-ffffffff8108e5f7: rdt_parse_param (STB_LOCAL)
ffffffff821ac25e-ffffffff821ac273: rdt_parse_param.cold (STB_LOCAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
int rdt_parse_param(struct fs_context *fc, struct fs_parameter *param);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105adb0)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:2052
Inline: False
```
**Symbols:**

```
ffffffff8105adb0-ffffffff8105ae35: rdt_parse_param (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int rdt_parse_param(struct fs_context *fc, struct fs_parameter *param);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8104ae30)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:2052
Inline: False
```
**Symbols:**

```
ffffffff8104ae30-ffffffff8104aeb5: rdt_parse_param (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int rdt_parse_param(struct fs_context *fc, struct fs_parameter *param);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105b1e0)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:2052
Inline: False
```
**Symbols:**

```
ffffffff8105b1e0-ffffffff8105b265: rdt_parse_param (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int rdt_parse_param(struct fs_context *fc, struct fs_parameter *param);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105c6a0)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:2052
Inline: False
```
**Symbols:**

```
ffffffff8105c6a0-ffffffff8105c725: rdt_parse_param (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
