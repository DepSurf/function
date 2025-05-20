# Function: <code>tboot_create_trampoline</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tboot.c (ffffffff81f6a2d3)
Location: arch/x86/kernel/tboot.c:162
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
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
In arch/x86/kernel/tboot.c (ffffffff81f92545)
Location: arch/x86/kernel/tboot.c:156
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
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
In arch/x86/kernel/tboot.c (ffffffff81fcd811)
Location: arch/x86/kernel/tboot.c:156
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
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
In arch/x86/kernel/tboot.c (ffffffff820ade52)
Location: arch/x86/kernel/tboot.c:160
Inline: True
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
In arch/x86/kernel/tboot.c (ffffffff826b4341)
Location: arch/x86/kernel/tboot.c:171
Inline: True
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
In arch/x86/kernel/tboot.c (ffffffff826ddb14)
Location: arch/x86/kernel/tboot.c:171
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
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
In arch/x86/kernel/tboot.c (ffffffff82893f5c)
Location: arch/x86/kernel/tboot.c:171
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
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
In arch/x86/kernel/tboot.c (ffffffff828ab712)
Location: arch/x86/kernel/tboot.c:158
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
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
In arch/x86/kernel/tboot.c (ffffffff828ae720)
Location: arch/x86/kernel/tboot.c:158
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void tboot_create_trampoline();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tboot.c (ffffffff81047b8b)
Location: arch/x86/kernel/tboot.c:160
Inline: False
Direct callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
**Symbols:**

```
ffffffff81047b8b-ffffffff81047c34: tboot_create_trampoline (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void tboot_create_trampoline();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tboot.c (ffffffff81bd4e02)
Location: arch/x86/kernel/tboot.c:161
Inline: False
Direct callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
**Symbols:**

```
ffffffff81bd4e02-ffffffff81bd4eab: tboot_create_trampoline (STB_LOCAL)
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
In arch/x86/kernel/tboot.c (ffffffff831c9df0)
Location: arch/x86/kernel/tboot.c:169
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
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
In arch/x86/kernel/tboot.c (ffffffff832ab1f1)
Location: arch/x86/kernel/tboot.c:169
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tboot.c (ffffffff8345b19c)
Location: arch/x86/kernel/tboot.c:168
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tboot.c (ffffffff83e7b4a5)
Location: arch/x86/kernel/tboot.c:167
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tboot.c (ffffffff8369db35)
Location: arch/x86/kernel/tboot.c:167
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tboot.c (ffffffff838cd6f5)
Location: arch/x86/kernel/tboot.c:167
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
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
In arch/x86/kernel/tboot.c (ffffffff8289c73f)
Location: arch/x86/kernel/tboot.c:158
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
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
In arch/x86/kernel/tboot.c (ffffffff82894918)
Location: arch/x86/kernel/tboot.c:158
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
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
In arch/x86/kernel/tboot.c (ffffffff828af702)
Location: arch/x86/kernel/tboot.c:158
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
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
In arch/x86/kernel/tboot.c (ffffffff828af730)
Location: arch/x86/kernel/tboot.c:158
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
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
</ul>
