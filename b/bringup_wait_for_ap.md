# Function: <code>bringup_wait_for_ap</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff81084054)
Location: kernel/cpu.c:339
Inline: True
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
In kernel/cpu.c (ffffffff810884ad)
Location: kernel/cpu.c:347
Inline: True
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
In kernel/cpu.c (ffffffff810850b3)
Location: kernel/cpu.c:276
Inline: True
Inline callers:
  - kernel/cpu.c:bringup_cpu
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
In kernel/cpu.c (ffffffff8108bc29)
Location: kernel/cpu.c:416
Inline: True
Inline callers:
  - kernel/cpu.c:bringup_cpu
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
In kernel/cpu.c (ffffffff8108f92d)
Location: kernel/cpu.c:492
Inline: True
Inline callers:
  - kernel/cpu.c:bringup_cpu
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
In kernel/cpu.c (ffffffff81097c2d)
Location: kernel/cpu.c:499
Inline: True
Inline callers:
  - kernel/cpu.c:bringup_cpu
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
In kernel/cpu.c (ffffffff8109c21f)
Location: kernel/cpu.c:509
Inline: True
Inline callers:
  - kernel/cpu.c:bringup_cpu
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
In kernel/cpu.c (ffffffff810a277b)
Location: kernel/cpu.c:519
Inline: True
Inline callers:
  - kernel/cpu.c:bringup_cpu
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int bringup_wait_for_ap(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810a9890)
Location: kernel/cpu.c:520
Inline: False
Direct callers:
  - kernel/cpu.c:bringup_cpu
```
**Symbols:**

```
ffffffff810a9890-ffffffff810a9926: bringup_wait_for_ap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int bringup_wait_for_ap(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810a52c0)
Location: kernel/cpu.c:520
Inline: False
Direct callers:
  - kernel/cpu.c:bringup_cpu
```
**Symbols:**

```
ffffffff810a52c0-ffffffff810a5356: bringup_wait_for_ap (STB_LOCAL)
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
In kernel/cpu.c (ffffffff810a705f)
Location: kernel/cpu.c:547
Inline: True
Inline callers:
  - kernel/cpu.c:bringup_cpu
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
In kernel/cpu.c (ffffffff810b7b4b)
Location: kernel/cpu.c:558
Inline: True
Inline callers:
  - kernel/cpu.c:bringup_cpu
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
In kernel/cpu.c (ffffffff810ce103)
Location: kernel/cpu.c:561
Inline: True
Inline callers:
  - kernel/cpu.c:bringup_cpu
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
In kernel/cpu.c (ffffffff810ec283)
Location: kernel/cpu.c:561
Inline: True
Inline callers:
  - kernel/cpu.c:bringup_cpu
```
</details>
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffff8000100f72b8)
Location: kernel/cpu.c:519
Inline: True
Inline callers:
  - kernel/cpu.c:bringup_cpu
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (c0355744)
Location: kernel/cpu.c:519
Inline: True
Inline callers:
  - kernel/cpu.c:bringup_cpu
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (c00000000013d910)
Location: kernel/cpu.c:519
Inline: True
Inline callers:
  - kernel/cpu.c:bringup_cpu
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffe0000c2e44)
Location: kernel/cpu.c:519
Inline: True
Inline callers:
  - kernel/cpu.c:bringup_cpu
```
</details>
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
In kernel/cpu.c (ffffffff8109c09b)
Location: kernel/cpu.c:519
Inline: True
Inline callers:
  - kernel/cpu.c:bringup_cpu
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
In kernel/cpu.c (ffffffff8108aacb)
Location: kernel/cpu.c:519
Inline: True
Inline callers:
  - kernel/cpu.c:bringup_cpu
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
In kernel/cpu.c (ffffffff8109c04b)
Location: kernel/cpu.c:519
Inline: True
Inline callers:
  - kernel/cpu.c:bringup_cpu
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
In kernel/cpu.c (ffffffff810a3cab)
Location: kernel/cpu.c:519
Inline: True
Inline callers:
  - kernel/cpu.c:bringup_cpu
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
