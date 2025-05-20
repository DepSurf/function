# Function: <code>refresh_ldt_segments</code>

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
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff8103229e)
Location: arch/x86/kernel/ldt.c:32
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:flush_ldt
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff8103378e)
Location: arch/x86/kernel/ldt.c:32
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:flush_ldt
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff81034a5e)
Location: arch/x86/kernel/ldt.c:32
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:flush_ldt
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff81036910)
Location: arch/x86/kernel/ldt.c:32
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:flush_ldt
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff81037140)
Location: arch/x86/kernel/ldt.c:32
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:flush_ldt
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void refresh_ldt_segments();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff81038500)
Location: arch/x86/kernel/ldt.c:116
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:flush_ldt
```
**Symbols:**

```
ffffffff81038500-ffffffff8103851d: refresh_ldt_segments (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void refresh_ldt_segments();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff81038eb0)
Location: arch/x86/kernel/ldt.c:116
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:flush_ldt
```
**Symbols:**

```
ffffffff81038eb0-ffffffff81038ecd: refresh_ldt_segments (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff8103b4ac)
Location: arch/x86/kernel/ldt.c:116
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:flush_ldt
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff81040f0c)
Location: arch/x86/kernel/ldt.c:116
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:flush_ldt
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void refresh_ldt_segments();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff81047c80)
Location: arch/x86/kernel/ldt.c:116
Inline: False
```
**Symbols:**

```
ffffffff81047c80-ffffffff81047ca3: refresh_ldt_segments (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void refresh_ldt_segments();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff810528b0)
Location: arch/x86/kernel/ldt.c:116
Inline: False
```
**Symbols:**

```
ffffffff810528b0-ffffffff810528d3: refresh_ldt_segments (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void refresh_ldt_segments();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff810538c0)
Location: arch/x86/kernel/ldt.c:116
Inline: False
```
**Symbols:**

```
ffffffff810538c0-ffffffff810538e3: refresh_ldt_segments (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void refresh_ldt_segments();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff8105aae0)
Location: arch/x86/kernel/ldt.c:116
Inline: False
```
**Symbols:**

```
ffffffff8105aae0-ffffffff8105ab03: refresh_ldt_segments (STB_LOCAL)
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
In arch/x86/kernel/ldt.c (ffffffff810372a0)
Location: arch/x86/kernel/ldt.c:32
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:flush_ldt
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
In arch/x86/kernel/ldt.c (ffffffff81026c25)
Location: arch/x86/kernel/ldt.c:32
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:flush_ldt
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
In arch/x86/kernel/ldt.c (ffffffff81037100)
Location: arch/x86/kernel/ldt.c:32
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:flush_ldt
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
In arch/x86/kernel/ldt.c (ffffffff81038100)
Location: arch/x86/kernel/ldt.c:32
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:flush_ldt
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
