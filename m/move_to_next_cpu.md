# Function: <code>move_to_next_cpu</code>

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
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_hwlat.c (ffffffff8116d441)
Location: kernel/trace/trace_hwlat.c:269
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
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
In kernel/trace/trace_hwlat.c (ffffffff8117065c)
Location: kernel/trace/trace_hwlat.c:270
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
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
In kernel/trace/trace_hwlat.c (ffffffff8117d849)
Location: kernel/trace/trace_hwlat.c:270
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
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
In kernel/trace/trace_hwlat.c (ffffffff8118c958)
Location: kernel/trace/trace_hwlat.c:270
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
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
In kernel/trace/trace_hwlat.c (ffffffff8119a468)
Location: kernel/trace/trace_hwlat.c:268
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
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
In kernel/trace/trace_hwlat.c (ffffffff811a80d5)
Location: kernel/trace/trace_hwlat.c:268
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
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
In kernel/trace/trace_hwlat.c (ffffffff811b38d5)
Location: kernel/trace/trace_hwlat.c:270
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void move_to_next_cpu();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_hwlat.c (0)
Location: kernel/trace/trace_hwlat.c:283
Inline: False
Direct callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
```
**Symbols:**

```
ffffffff811cbf40-ffffffff811cc038: move_to_next_cpu (STB_LOCAL)
ffffffff811cc56a-ffffffff811cc576: move_to_next_cpu.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void move_to_next_cpu();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_hwlat.c (0)
Location: kernel/trace/trace_hwlat.c:283
Inline: False
Direct callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
```
**Symbols:**

```
ffffffff811c9590-ffffffff811c9688: move_to_next_cpu (STB_LOCAL)
ffffffff81be5bc3-ffffffff81be5bcf: move_to_next_cpu.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void move_to_next_cpu();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_hwlat.c (0)
Location: kernel/trace/trace_hwlat.c:278
Inline: False
Direct callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
```
**Symbols:**

```
ffffffff811ca9a0-ffffffff811caa9d: move_to_next_cpu (STB_LOCAL)
ffffffff81bd7a79-ffffffff81bd7a85: move_to_next_cpu.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void move_to_next_cpu();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_hwlat.c (0)
Location: kernel/trace/trace_hwlat.c:314
Inline: False
Direct callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
```
**Symbols:**

```
ffffffff811f6b20-ffffffff811f6c07: move_to_next_cpu (STB_LOCAL)
ffffffff81cb5e94-ffffffff81cb5ebb: move_to_next_cpu.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void move_to_next_cpu();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_hwlat.c (0)
Location: kernel/trace/trace_hwlat.c:314
Inline: False
Direct callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
```
**Symbols:**

```
ffffffff812305b0-ffffffff812306a1: move_to_next_cpu (STB_LOCAL)
ffffffff81e66eb6-ffffffff81e66edb: move_to_next_cpu.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void move_to_next_cpu();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_hwlat.c (ffffffff8127cbf0)
Location: kernel/trace/trace_hwlat.c:314
Inline: False
Direct callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
```
**Symbols:**

```
ffffffff8127cbf0-ffffffff8127cd21: move_to_next_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void move_to_next_cpu();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_hwlat.c (ffffffff812948d0)
Location: kernel/trace/trace_hwlat.c:314
Inline: False
Direct callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
```
**Symbols:**

```
ffffffff812948d0-ffffffff81294a08: move_to_next_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void move_to_next_cpu();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_hwlat.c (ffffffff812aff30)
Location: kernel/trace/trace_hwlat.c:314
Inline: False
Direct callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
```
**Symbols:**

```
ffffffff812aff30-ffffffff812b0068: move_to_next_cpu (STB_LOCAL)
```
</details>
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
In kernel/trace/trace_hwlat.c (ffff800010231c7c)
Location: kernel/trace/trace_hwlat.c:270
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
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
In kernel/trace/trace_hwlat.c (c046d7a0)
Location: kernel/trace/trace_hwlat.c:270
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
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
In kernel/trace/trace_hwlat.c (c0000000002bc3b0)
Location: kernel/trace/trace_hwlat.c:270
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
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
In kernel/trace/trace_hwlat.c (ffffffe00018939a)
Location: kernel/trace/trace_hwlat.c:270
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
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
In kernel/trace/trace_hwlat.c (ffffffff811abef5)
Location: kernel/trace/trace_hwlat.c:270
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
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
In kernel/trace/trace_hwlat.c (ffffffff8119ede5)
Location: kernel/trace/trace_hwlat.c:270
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
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
In kernel/trace/trace_hwlat.c (ffffffff811a9cc5)
Location: kernel/trace/trace_hwlat.c:270
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
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
In kernel/trace/trace_hwlat.c (ffffffff811b7b05)
Location: kernel/trace/trace_hwlat.c:270
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
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
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
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
