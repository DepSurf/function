# Function: <code>itlb_multihit_show_state</code>

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
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff81047b8c)
Location: arch/x86/kernel/cpu/bugs.c:1441
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
ssize_t itlb_multihit_show_state(char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff8104ba40)
Location: arch/x86/kernel/cpu/bugs.c:1558
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:cpu_show_itlb_multihit
```
**Symbols:**

```
ffffffff8104ba40-ffffffff8104bb86: itlb_multihit_show_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ssize_t itlb_multihit_show_state(char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff8104af80)
Location: arch/x86/kernel/cpu/bugs.c:1566
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:cpu_show_itlb_multihit
```
**Symbols:**

```
ffffffff8104af80-ffffffff8104b0c6: itlb_multihit_show_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ssize_t itlb_multihit_show_state(char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff8104c860)
Location: arch/x86/kernel/cpu/bugs.c:1566
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:cpu_show_itlb_multihit
```
**Symbols:**

```
ffffffff8104c860-ffffffff8104c9a6: itlb_multihit_show_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
ssize_t itlb_multihit_show_state(char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (0)
Location: arch/x86/kernel/cpu/bugs.c:1721
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:cpu_show_itlb_multihit
```
**Symbols:**

```
ffffffff81053fc0-ffffffff81054114: itlb_multihit_show_state (STB_LOCAL)
ffffffff81c9ac16-ffffffff81c9ac2b: itlb_multihit_show_state.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
ssize_t itlb_multihit_show_state(char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (0)
Location: arch/x86/kernel/cpu/bugs.c:2223
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:cpu_show_itlb_multihit
```
**Symbols:**

```
ffffffff8105fe70-ffffffff8105ffd0: itlb_multihit_show_state (STB_LOCAL)
ffffffff81e4a0b8-ffffffff81e4a0cd: itlb_multihit_show_state.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
ssize_t itlb_multihit_show_state(char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (0)
Location: arch/x86/kernel/cpu/bugs.c:2274
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:cpu_show_itlb_multihit
```
**Symbols:**

```
ffffffff8106e510-ffffffff8106e5c5: itlb_multihit_show_state (STB_LOCAL)
ffffffff8205296c-ffffffff82052981: itlb_multihit_show_state.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
ssize_t itlb_multihit_show_state(char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (0)
Location: arch/x86/kernel/cpu/bugs.c:2549
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:cpu_show_itlb_multihit
```
**Symbols:**

```
ffffffff8106fd00-ffffffff8106fdb5: itlb_multihit_show_state (STB_LOCAL)
ffffffff820d0e2a-ffffffff820d0e3f: itlb_multihit_show_state.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
ssize_t itlb_multihit_show_state(char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (0)
Location: arch/x86/kernel/cpu/bugs.c:2687
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:cpu_show_itlb_multihit
```
**Symbols:**

```
ffffffff81077170-ffffffff81077225: itlb_multihit_show_state (STB_LOCAL)
ffffffff821ab947-ffffffff821ab95c: itlb_multihit_show_state.cold (STB_LOCAL)
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff81047cfc)
Location: arch/x86/kernel/cpu/bugs.c:1441
Inline: True
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
In arch/x86/kernel/cpu/bugs.c (ffffffff8103700c)
Location: arch/x86/kernel/cpu/bugs.c:1441
Inline: True
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
In arch/x86/kernel/cpu/bugs.c (ffffffff81047b3c)
Location: arch/x86/kernel/cpu/bugs.c:1441
Inline: True
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
In arch/x86/kernel/cpu/bugs.c (ffffffff81048f4c)
Location: arch/x86/kernel/cpu/bugs.c:1441
Inline: True
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
