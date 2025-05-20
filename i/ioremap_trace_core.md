# Function: <code>ioremap_trace_core</code>

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
In arch/x86/mm/mmio-mod.c (ffffffff810744c4)
Location: arch/x86/mm/mmio-mod.c:234
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:mmiotrace_ioremap
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
In arch/x86/mm/mmio-mod.c (ffffffff81075ab8)
Location: arch/x86/mm/mmio-mod.c:234
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:mmiotrace_ioremap
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
In arch/x86/mm/mmio-mod.c (ffffffff81079658)
Location: arch/x86/mm/mmio-mod.c:234
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:mmiotrace_ioremap
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
In arch/x86/mm/mmio-mod.c (ffffffff81077f08)
Location: arch/x86/mm/mmio-mod.c:234
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:mmiotrace_ioremap
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
In arch/x86/mm/mmio-mod.c (ffffffff8107e268)
Location: arch/x86/mm/mmio-mod.c:234
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:mmiotrace_ioremap
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
In arch/x86/mm/mmio-mod.c (ffffffff810812c0)
Location: arch/x86/mm/mmio-mod.c:233
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:mmiotrace_ioremap
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
In arch/x86/mm/mmio-mod.c (ffffffff81087ed0)
Location: arch/x86/mm/mmio-mod.c:233
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:mmiotrace_ioremap
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
In arch/x86/mm/mmio-mod.c (ffffffff8108bb20)
Location: arch/x86/mm/mmio-mod.c:221
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:mmiotrace_ioremap
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
In arch/x86/mm/mmio-mod.c (ffffffff8108c790)
Location: arch/x86/mm/mmio-mod.c:221
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:mmiotrace_ioremap
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void ioremap_trace_core(resource_size_t offset, long unsigned int size, void *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/mmio-mod.c (0)
Location: arch/x86/mm/mmio-mod.c:221
Inline: False
Direct callers:
  - arch/x86/mm/mmio-mod.c:mmiotrace_ioremap
```
**Symbols:**

```
ffffffff81093d80-ffffffff81093ec8: ioremap_trace_core (STB_LOCAL)
ffffffff810942f7-ffffffff81094308: ioremap_trace_core.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void ioremap_trace_core(resource_size_t offset, long unsigned int size, void *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/mmio-mod.c (0)
Location: arch/x86/mm/mmio-mod.c:221
Inline: False
Direct callers:
  - arch/x86/mm/mmio-mod.c:mmiotrace_ioremap
```
**Symbols:**

```
ffffffff810932d0-ffffffff81093418: ioremap_trace_core (STB_LOCAL)
ffffffff81bda0e8-ffffffff81bda0f9: ioremap_trace_core.cold (STB_LOCAL)
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
In arch/x86/mm/mmio-mod.c (ffffffff81093d22)
Location: arch/x86/mm/mmio-mod.c:219
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:mmiotrace_ioremap
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
In arch/x86/mm/mmio-mod.c (ffffffff810a3b02)
Location: arch/x86/mm/mmio-mod.c:219
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:mmiotrace_ioremap
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
In arch/x86/mm/mmio-mod.c (ffffffff810b81e2)
Location: arch/x86/mm/mmio-mod.c:219
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:mmiotrace_ioremap
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
In arch/x86/mm/mmio-mod.c (ffffffff810d3a02)
Location: arch/x86/mm/mmio-mod.c:219
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:mmiotrace_ioremap
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
In arch/x86/mm/mmio-mod.c (ffffffff810d6de2)
Location: arch/x86/mm/mmio-mod.c:219
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:mmiotrace_ioremap
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
In arch/x86/mm/mmio-mod.c (ffffffff810df612)
Location: arch/x86/mm/mmio-mod.c:219
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:mmiotrace_ioremap
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
In arch/x86/mm/mmio-mod.c (ffffffff8108b750)
Location: arch/x86/mm/mmio-mod.c:221
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:mmiotrace_ioremap
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
In arch/x86/mm/mmio-mod.c (ffffffff8107a280)
Location: arch/x86/mm/mmio-mod.c:221
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:mmiotrace_ioremap
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
In arch/x86/mm/mmio-mod.c (ffffffff8108b700)
Location: arch/x86/mm/mmio-mod.c:221
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:mmiotrace_ioremap
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
In arch/x86/mm/mmio-mod.c (ffffffff8108da60)
Location: arch/x86/mm/mmio-mod.c:221
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:mmiotrace_ioremap
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
