# Function: <code>relocate_initrd</code>

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
In arch/x86/kernel/setup.c (ffffffff81f665f2)
Location: arch/x86/kernel/setup.c:321
Inline: True
Inline callers:
  - arch/x86/kernel/setup.c:setup_arch
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
In arch/x86/kernel/setup.c (ffffffff81f8e439)
Location: arch/x86/kernel/setup.c:323
Inline: True
Inline callers:
  - arch/x86/kernel/setup.c:setup_arch
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
In arch/x86/kernel/setup.c (ffffffff81fc97d1)
Location: arch/x86/kernel/setup.c:323
Inline: True
Inline callers:
  - arch/x86/kernel/setup.c:setup_arch
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
In arch/x86/kernel/setup.c (ffffffff820a9f59)
Location: arch/x86/kernel/setup.c:327
Inline: True
Inline callers:
  - arch/x86/kernel/setup.c:setup_arch
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
In arch/x86/kernel/setup.c (ffffffff826b0a28)
Location: arch/x86/kernel/setup.c:312
Inline: True
Inline callers:
  - arch/x86/kernel/setup.c:setup_arch
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
In arch/x86/kernel/setup.c (ffffffff826da0c4)
Location: arch/x86/kernel/setup.c:310
Inline: True
Inline callers:
  - arch/x86/kernel/setup.c:setup_arch
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
In arch/x86/kernel/setup.c (ffffffff828904a9)
Location: arch/x86/kernel/setup.c:310
Inline: True
Inline callers:
  - arch/x86/kernel/setup.c:setup_arch
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
In arch/x86/kernel/setup.c (ffffffff828a7c8b)
Location: arch/x86/kernel/setup.c:312
Inline: True
Inline callers:
  - arch/x86/kernel/setup.c:setup_arch
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
In arch/x86/kernel/setup.c (ffffffff828aacf6)
Location: arch/x86/kernel/setup.c:312
Inline: True
Inline callers:
  - arch/x86/kernel/setup.c:setup_arch
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void relocate_initrd();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/setup.c (ffffffff82ccf368)
Location: arch/x86/kernel/setup.c:258
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:reserve_initrd
```
**Symbols:**

```
ffffffff82ccf368-ffffffff82ccf442: relocate_initrd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void relocate_initrd();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/setup.c (ffffffff82fbb22e)
Location: arch/x86/kernel/setup.c:257
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:reserve_initrd
```
**Symbols:**

```
ffffffff82fbb22e-ffffffff82fbb2f2: relocate_initrd (STB_LOCAL)
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
In arch/x86/kernel/setup.c (ffffffff831c6557)
Location: arch/x86/kernel/setup.c:257
Inline: True
Inline callers:
  - arch/x86/kernel/setup.c:setup_arch
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
In arch/x86/kernel/setup.c (ffffffff832a73bd)
Location: arch/x86/kernel/setup.c:259
Inline: True
Inline callers:
  - arch/x86/kernel/setup.c:setup_arch
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
In arch/x86/kernel/setup.c (ffffffff834566bf)
Location: arch/x86/kernel/setup.c:255
Inline: True
Inline callers:
  - arch/x86/kernel/setup.c:setup_arch
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
In arch/x86/kernel/setup.c (ffffffff83e74cb3)
Location: arch/x86/kernel/setup.c:264
Inline: True
Inline callers:
  - arch/x86/kernel/setup.c:setup_arch
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
In arch/x86/kernel/setup.c (ffffffff8369678a)
Location: arch/x86/kernel/setup.c:258
Inline: True
Inline callers:
  - arch/x86/kernel/setup.c:setup_arch
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
In arch/x86/kernel/setup.c (ffffffff838c644c)
Location: arch/x86/kernel/setup.c:255
Inline: True
Inline callers:
  - arch/x86/kernel/setup.c:setup_arch
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
In arch/x86/kernel/setup.c (ffffffff82898d06)
Location: arch/x86/kernel/setup.c:312
Inline: True
Inline callers:
  - arch/x86/kernel/setup.c:setup_arch
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
In arch/x86/kernel/setup.c (ffffffff82891016)
Location: arch/x86/kernel/setup.c:312
Inline: True
Inline callers:
  - arch/x86/kernel/setup.c:setup_arch
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
In arch/x86/kernel/setup.c (ffffffff828abcf6)
Location: arch/x86/kernel/setup.c:312
Inline: True
Inline callers:
  - arch/x86/kernel/setup.c:setup_arch
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
In arch/x86/kernel/setup.c (ffffffff828abd06)
Location: arch/x86/kernel/setup.c:312
Inline: True
Inline callers:
  - arch/x86/kernel/setup.c:setup_arch
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
