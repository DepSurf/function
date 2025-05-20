# Function: <code>kexec_walk_resources</code>

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
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/kexec_file.c (ffffffff811443a0)
Location: kernel/kexec_file.c:564
Inline: True
Direct callers:
  - kernel/kexec_file.c:kexec_add_buffer
```
**Symbols:**

```
ffffffff811443a0-ffffffff811443fa: kexec_walk_resources.constprop.6 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/kexec_file.c (ffffffff8114f710)
Location: kernel/kexec_file.c:610
Inline: True
Direct callers:
  - kernel/kexec_file.c:kexec_add_buffer
```
**Symbols:**

```
ffffffff8114f710-ffffffff8114f76a: kexec_walk_resources.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/kexec_file.c (ffffffff8115b3f0)
Location: kernel/kexec_file.c:615
Inline: True
Direct callers:
  - kernel/kexec_file.c:kexec_add_buffer
```
**Symbols:**

```
ffffffff8115b3f0-ffffffff8115b44a: kexec_walk_resources.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/kexec_file.c (ffffffff8116c270)
Location: kernel/kexec_file.c:602
Inline: True
Direct callers:
  - kernel/kexec_file.c:kexec_add_buffer
```
**Symbols:**

```
ffffffff8116c270-ffffffff8116c2ca: kexec_walk_resources.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffffffff8116915f)
Location: kernel/kexec_file.c:608
Inline: True
Inline callers:
  - kernel/kexec_file.c:arch_kexec_locate_mem_hole
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
In kernel/kexec_file.c (ffffffff81169e2f)
Location: kernel/kexec_file.c:608
Inline: True
Inline callers:
  - kernel/kexec_file.c:arch_kexec_locate_mem_hole
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
In kernel/kexec_file.c (ffffffff8118f9bf)
Location: kernel/kexec_file.c:608
Inline: True
Inline callers:
  - kernel/kexec_file.c:arch_kexec_locate_mem_hole
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
In kernel/kexec_file.c (ffffffff811bf121)
Location: kernel/kexec_file.c:580
Inline: True
Inline callers:
  - kernel/kexec_file.c:kexec_locate_mem_hole
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
In kernel/kexec_file.c (ffffffff812013b1)
Location: kernel/kexec_file.c:584
Inline: True
Inline callers:
  - kernel/kexec_file.c:kexec_locate_mem_hole
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
In kernel/kexec_file.c (ffffffff81216781)
Location: kernel/kexec_file.c:587
Inline: True
Inline callers:
  - kernel/kexec_file.c:kexec_locate_mem_hole
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
In kernel/kexec_file.c (ffffffff8122e655)
Location: kernel/kexec_file.c:595
Inline: True
Inline callers:
  - kernel/kexec_file.c:kexec_locate_mem_hole
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
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/kexec_file.c (ffffffff81153a10)
Location: kernel/kexec_file.c:615
Inline: True
Direct callers:
  - kernel/kexec_file.c:kexec_add_buffer
```
**Symbols:**

```
ffffffff81153a10-ffffffff81153a6a: kexec_walk_resources.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/kexec_file.c (ffffffff81146d30)
Location: kernel/kexec_file.c:615
Inline: True
Direct callers:
  - kernel/kexec_file.c:kexec_add_buffer
```
**Symbols:**

```
ffffffff81146d30-ffffffff81146d8a: kexec_walk_resources.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/kexec_file.c (ffffffff811518c0)
Location: kernel/kexec_file.c:615
Inline: True
Direct callers:
  - kernel/kexec_file.c:kexec_add_buffer
```
**Symbols:**

```
ffffffff811518c0-ffffffff8115191a: kexec_walk_resources.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/kexec_file.c (ffffffff8115e6e0)
Location: kernel/kexec_file.c:615
Inline: True
Direct callers:
  - kernel/kexec_file.c:kexec_add_buffer
```
**Symbols:**

```
ffffffff8115e6e0-ffffffff8115e73a: kexec_walk_resources.constprop.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
