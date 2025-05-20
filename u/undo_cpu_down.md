# Function: <code>undo_cpu_down</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cpu.c (ffffffff81083c10)
Location: kernel/cpu.c:366
Inline: True
Direct callers:
  - kernel/cpu.c:cpuhp_thread_fun
  - kernel/cpu.c:cpuhp_down_callbacks
```
**Symbols:**

```
ffffffff81083c10-ffffffff81083c70: undo_cpu_down.isra.7 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cpu.c (ffffffff81088bc0)
Location: kernel/cpu.c:380
Inline: True
Direct callers:
  - kernel/cpu.c:cpuhp_thread_fun
  - kernel/cpu.c:cpuhp_down_callbacks
```
**Symbols:**

```
ffffffff81088bc0-ffffffff81088c4a: undo_cpu_down.isra.9 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cpu.c (ffffffff81085a30)
Location: kernel/cpu.c:320
Inline: True
Direct callers:
  - kernel/cpu.c:cpuhp_thread_fun
  - kernel/cpu.c:cpuhp_down_callbacks
```
**Symbols:**

```
ffffffff81085a30-ffffffff81085aba: undo_cpu_down.isra.10 (STB_LOCAL)
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
In kernel/cpu.c (ffffffff81988bb7)
Location: kernel/cpu.c:826
Inline: True
Inline callers:
  - kernel/cpu.c:_cpu_down
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
In kernel/cpu.c (ffffffff819e55b1)
Location: kernel/cpu.c:911
Inline: True
Inline callers:
  - kernel/cpu.c:_cpu_down
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
In kernel/cpu.c (ffffffff81a207e6)
Location: kernel/cpu.c:930
Inline: True
Inline callers:
  - kernel/cpu.c:_cpu_down
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
In kernel/cpu.c (ffffffff81a90d0b)
Location: kernel/cpu.c:942
Inline: True
Inline callers:
  - kernel/cpu.c:_cpu_down
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
In kernel/cpu.c (ffffffff81ac804d)
Location: kernel/cpu.c:951
Inline: True
Inline callers:
  - kernel/cpu.c:_cpu_down
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff81bc0b15)
Location: kernel/cpu.c:967
Inline: True
Inline callers:
  - kernel/cpu.c:_cpu_down
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
In kernel/cpu.c (ffffffff81c39ba5)
Location: kernel/cpu.c:971
Inline: True
Inline callers:
  - kernel/cpu.c:_cpu_down
```
</details>
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
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffff800010d9be78)
Location: kernel/cpu.c:951
Inline: True
Inline callers:
  - kernel/cpu.c:_cpu_down
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
In kernel/cpu.c (c0e98510)
Location: kernel/cpu.c:951
Inline: True
Inline callers:
  - kernel/cpu.c:_cpu_down
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
In kernel/cpu.c (c0000000001416b0)
Location: kernel/cpu.c:951
Inline: True
Inline callers:
  - kernel/cpu.c:_cpu_down
```
</details>
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
In kernel/cpu.c (ffffffff81a66ebd)
Location: kernel/cpu.c:951
Inline: True
Inline callers:
  - kernel/cpu.c:_cpu_down
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
In kernel/cpu.c (ffffffff81a2397d)
Location: kernel/cpu.c:951
Inline: True
Inline callers:
  - kernel/cpu.c:_cpu_down
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
In kernel/cpu.c (ffffffff81ad32cd)
Location: kernel/cpu.c:951
Inline: True
Inline callers:
  - kernel/cpu.c:_cpu_down
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
In kernel/cpu.c (ffffffff81adf7cd)
Location: kernel/cpu.c:951
Inline: True
Inline callers:
  - kernel/cpu.c:_cpu_down
```
</details>
</li>
</ul>

## Differences
