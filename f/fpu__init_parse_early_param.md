# Function: <code>fpu__init_parse_early_param</code>

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
In arch/x86/kernel/fpu/init.c (ffffffff81f9156d)
Location: arch/x86/kernel/fpu/init.c:338
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/init.c:fpu__init_system
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
In arch/x86/kernel/fpu/init.c (ffffffff81fcc937)
Location: arch/x86/kernel/fpu/init.c:247
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/init.c:fpu__init_system
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
In arch/x86/kernel/fpu/init.c (ffffffff820ad11c)
Location: arch/x86/kernel/fpu/init.c:250
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/init.c:fpu__init_system
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
In arch/x86/kernel/fpu/init.c (ffffffff826b398b)
Location: arch/x86/kernel/fpu/init.c:250
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/init.c:fpu__init_system
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
In arch/x86/kernel/fpu/init.c (ffffffff826dd199)
Location: arch/x86/kernel/fpu/init.c:250
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/init.c:fpu__init_system
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
In arch/x86/kernel/fpu/init.c (ffffffff828935e1)
Location: arch/x86/kernel/fpu/init.c:250
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/init.c:fpu__init_system
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
In arch/x86/kernel/fpu/init.c (ffffffff828aac57)
Location: arch/x86/kernel/fpu/init.c:243
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/init.c:fpu__init_system
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
In arch/x86/kernel/fpu/init.c (ffffffff828adcc7)
Location: arch/x86/kernel/fpu/init.c:243
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/init.c:fpu__init_system
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void fpu__init_parse_early_param();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/init.c (ffffffff82cd3043)
Location: arch/x86/kernel/fpu/init.c:244
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/init.c:fpu__init_system
```
**Symbols:**

```
ffffffff82cd3043-ffffffff82cd3128: fpu__init_parse_early_param (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
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
In arch/x86/kernel/fpu/init.c (ffffffff8289bce6)
Location: arch/x86/kernel/fpu/init.c:243
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/init.c:fpu__init_system
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
In arch/x86/kernel/fpu/init.c (ffffffff82893f8a)
Location: arch/x86/kernel/fpu/init.c:243
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/init.c:fpu__init_system
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
In arch/x86/kernel/fpu/init.c (ffffffff828aeca9)
Location: arch/x86/kernel/fpu/init.c:243
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/init.c:fpu__init_system
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
In arch/x86/kernel/fpu/init.c (ffffffff828aecd7)
Location: arch/x86/kernel/fpu/init.c:243
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/init.c:fpu__init_system
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
