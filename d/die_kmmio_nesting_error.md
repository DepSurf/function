# Function: <code>die_kmmio_nesting_error</code>

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
In arch/x86/mm/mmio-mod.c (ffffffff81074226)
Location: arch/x86/mm/mmio-mod.c:120
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:pre
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
In arch/x86/mm/mmio-mod.c (ffffffff81075804)
Location: arch/x86/mm/mmio-mod.c:120
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:pre
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
In arch/x86/mm/mmio-mod.c (ffffffff81079384)
Location: arch/x86/mm/mmio-mod.c:120
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:pre
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
In arch/x86/mm/mmio-mod.c (ffffffff81077c55)
Location: arch/x86/mm/mmio-mod.c:120
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:pre
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
In arch/x86/mm/mmio-mod.c (ffffffff8107dfb5)
Location: arch/x86/mm/mmio-mod.c:120
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:pre
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
In arch/x86/mm/mmio-mod.c (ffffffff81081094)
Location: arch/x86/mm/mmio-mod.c:119
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:pre
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
In arch/x86/mm/mmio-mod.c (ffffffff81087ca4)
Location: arch/x86/mm/mmio-mod.c:119
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:pre
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
In arch/x86/mm/mmio-mod.c (ffffffff8108b886)
Location: arch/x86/mm/mmio-mod.c:107
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:pre
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
In arch/x86/mm/mmio-mod.c (ffffffff8108c4f6)
Location: arch/x86/mm/mmio-mod.c:107
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:pre
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void die_kmmio_nesting_error(struct pt_regs *regs, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mmio-mod.c (ffffffff81093970)
Location: arch/x86/mm/mmio-mod.c:107
Inline: False
Direct callers:
  - arch/x86/mm/mmio-mod.c:pre
```
**Symbols:**

```
ffffffff81093970-ffffffff81093a08: die_kmmio_nesting_error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void die_kmmio_nesting_error(struct pt_regs *regs, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mmio-mod.c (ffffffff81092ec0)
Location: arch/x86/mm/mmio-mod.c:107
Inline: False
Direct callers:
  - arch/x86/mm/mmio-mod.c:pre
```
**Symbols:**

```
ffffffff81092ec0-ffffffff81092f58: die_kmmio_nesting_error (STB_LOCAL)
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
In arch/x86/mm/mmio-mod.c (ffffffff81093a4d)
Location: arch/x86/mm/mmio-mod.c:105
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:pre
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
In arch/x86/mm/mmio-mod.c (ffffffff810a3911)
Location: arch/x86/mm/mmio-mod.c:105
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:pre
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
In arch/x86/mm/mmio-mod.c (ffffffff810b8006)
Location: arch/x86/mm/mmio-mod.c:105
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:pre
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
In arch/x86/mm/mmio-mod.c (ffffffff810d3656)
Location: arch/x86/mm/mmio-mod.c:105
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:pre
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
In arch/x86/mm/mmio-mod.c (ffffffff810d6a35)
Location: arch/x86/mm/mmio-mod.c:105
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:pre
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
In arch/x86/mm/mmio-mod.c (ffffffff810df265)
Location: arch/x86/mm/mmio-mod.c:105
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:pre
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
In arch/x86/mm/mmio-mod.c (ffffffff8108b4b6)
Location: arch/x86/mm/mmio-mod.c:107
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:pre
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
In arch/x86/mm/mmio-mod.c (ffffffff8107a028)
Location: arch/x86/mm/mmio-mod.c:107
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:pre
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
In arch/x86/mm/mmio-mod.c (ffffffff8108b466)
Location: arch/x86/mm/mmio-mod.c:107
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:pre
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
In arch/x86/mm/mmio-mod.c (ffffffff8108d78e)
Location: arch/x86/mm/mmio-mod.c:107
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:pre
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
