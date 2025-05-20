# Function: <code>spectre_v2_show_state</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
ssize_t spectre_v2_show_state(char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (0)
Location: arch/x86/kernel/cpu/bugs.c:1809
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:cpu_show_spectre_v2
```
**Symbols:**

```
ffffffff81053cc0-ffffffff81053fb9: spectre_v2_show_state (STB_LOCAL)
ffffffff81c9ac01-ffffffff81c9ac16: spectre_v2_show_state.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
ssize_t spectre_v2_show_state(char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (0)
Location: arch/x86/kernel/cpu/bugs.c:2341
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:cpu_show_spectre_v2
```
**Symbols:**

```
ffffffff8105fb00-ffffffff8105fe6c: spectre_v2_show_state (STB_LOCAL)
ffffffff81e4a0a3-ffffffff81e4a0b8: spectre_v2_show_state.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
ssize_t spectre_v2_show_state(char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (0)
Location: arch/x86/kernel/cpu/bugs.c:2392
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:cpu_show_spectre_v2
```
**Symbols:**

```
ffffffff8106e250-ffffffff8106e4f9: spectre_v2_show_state (STB_LOCAL)
ffffffff82052957-ffffffff8205296c: spectre_v2_show_state.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
ssize_t spectre_v2_show_state(char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (0)
Location: arch/x86/kernel/cpu/bugs.c:2668
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:cpu_show_spectre_v2
```
**Symbols:**

```
ffffffff8106fa20-ffffffff8106fcea: spectre_v2_show_state (STB_LOCAL)
ffffffff820d0e0f-ffffffff820d0e2a: spectre_v2_show_state.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
ssize_t spectre_v2_show_state(char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (0)
Location: arch/x86/kernel/cpu/bugs.c:2828
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:cpu_show_spectre_v2
```
**Symbols:**

```
ffffffff81076de0-ffffffff8107715a: spectre_v2_show_state (STB_LOCAL)
ffffffff821ab932-ffffffff821ab947: spectre_v2_show_state.cold (STB_LOCAL)
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
