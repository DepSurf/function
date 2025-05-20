# Function: <code>iounmap_trace_core</code>

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
In arch/x86/mm/mmio-mod.c (ffffffff8107463d)
Location: arch/x86/mm/mmio-mod.c:293
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:mmiotrace_iounmap
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
In arch/x86/mm/mmio-mod.c (ffffffff81075c1d)
Location: arch/x86/mm/mmio-mod.c:293
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:mmiotrace_iounmap
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
In arch/x86/mm/mmio-mod.c (ffffffff810797bd)
Location: arch/x86/mm/mmio-mod.c:293
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:mmiotrace_iounmap
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
In arch/x86/mm/mmio-mod.c (ffffffff8107806d)
Location: arch/x86/mm/mmio-mod.c:293
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:mmiotrace_iounmap
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
In arch/x86/mm/mmio-mod.c (ffffffff8107e3cd)
Location: arch/x86/mm/mmio-mod.c:293
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:mmiotrace_iounmap
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
In arch/x86/mm/mmio-mod.c (ffffffff8108141d)
Location: arch/x86/mm/mmio-mod.c:292
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:mmiotrace_iounmap
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
In arch/x86/mm/mmio-mod.c (ffffffff8108802d)
Location: arch/x86/mm/mmio-mod.c:292
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:mmiotrace_iounmap
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
In arch/x86/mm/mmio-mod.c (ffffffff8108bc8d)
Location: arch/x86/mm/mmio-mod.c:280
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:mmiotrace_iounmap
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
In arch/x86/mm/mmio-mod.c (ffffffff8108c8fd)
Location: arch/x86/mm/mmio-mod.c:280
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:mmiotrace_iounmap
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void iounmap_trace_core(volatile void *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mmio-mod.c (ffffffff81093ed0)
Location: arch/x86/mm/mmio-mod.c:280
Inline: False
Direct callers:
  - arch/x86/mm/mmio-mod.c:mmiotrace_iounmap
```
**Symbols:**

```
ffffffff81093ed0-ffffffff81094022: iounmap_trace_core (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void iounmap_trace_core(volatile void *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mmio-mod.c (ffffffff81093420)
Location: arch/x86/mm/mmio-mod.c:280
Inline: False
Direct callers:
  - arch/x86/mm/mmio-mod.c:mmiotrace_iounmap
```
**Symbols:**

```
ffffffff81093420-ffffffff81093572: iounmap_trace_core (STB_LOCAL)
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
In arch/x86/mm/mmio-mod.c (ffffffff81093ebd)
Location: arch/x86/mm/mmio-mod.c:278
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:mmiotrace_iounmap
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
In arch/x86/mm/mmio-mod.c (ffffffff810a3c9d)
Location: arch/x86/mm/mmio-mod.c:278
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:mmiotrace_iounmap
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
In arch/x86/mm/mmio-mod.c (ffffffff810b8399)
Location: arch/x86/mm/mmio-mod.c:278
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:mmiotrace_iounmap
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
In arch/x86/mm/mmio-mod.c (ffffffff810d3be9)
Location: arch/x86/mm/mmio-mod.c:278
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:mmiotrace_iounmap
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
In arch/x86/mm/mmio-mod.c (ffffffff810d6fc9)
Location: arch/x86/mm/mmio-mod.c:278
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:mmiotrace_iounmap
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
In arch/x86/mm/mmio-mod.c (ffffffff810df829)
Location: arch/x86/mm/mmio-mod.c:278
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:mmiotrace_iounmap
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
In arch/x86/mm/mmio-mod.c (ffffffff8108b8bd)
Location: arch/x86/mm/mmio-mod.c:280
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:mmiotrace_iounmap
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
In arch/x86/mm/mmio-mod.c (ffffffff8107a3ed)
Location: arch/x86/mm/mmio-mod.c:280
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:mmiotrace_iounmap
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
In arch/x86/mm/mmio-mod.c (ffffffff8108b86d)
Location: arch/x86/mm/mmio-mod.c:280
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:mmiotrace_iounmap
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
In arch/x86/mm/mmio-mod.c (ffffffff8108dbd0)
Location: arch/x86/mm/mmio-mod.c:280
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:mmiotrace_iounmap
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
