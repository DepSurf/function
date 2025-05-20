# Function: <code>kgdb_io_ready</code>

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
In kernel/debug/debug_core.c (ffffffff8112fdee)
Location: kernel/debug/debug_core.c:395
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_nmicallin
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
In kernel/debug/debug_core.c (ffffffff8113886d)
Location: kernel/debug/debug_core.c:395
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_nmicallin
  - kernel/debug/debug_core.c:kgdb_cpu_enter
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
In kernel/debug/debug_core.c (ffffffff811425fd)
Location: kernel/debug/debug_core.c:395
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_nmicallin
  - kernel/debug/debug_core.c:kgdb_cpu_enter
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
In kernel/debug/debug_core.c (ffffffff81143e22)
Location: kernel/debug/debug_core.c:396
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_nmicallin
  - kernel/debug/debug_core.c:kgdb_cpu_enter
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
In kernel/debug/debug_core.c (ffffffff81150ae2)
Location: kernel/debug/debug_core.c:396
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_nmicallin
  - kernel/debug/debug_core.c:kgdb_cpu_enter
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
In kernel/debug/debug_core.c (ffffffff8115f65d)
Location: kernel/debug/debug_core.c:396
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_nmicallin
  - kernel/debug/debug_core.c:kgdb_cpu_enter
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
In kernel/debug/debug_core.c (ffffffff8116c3cd)
Location: kernel/debug/debug_core.c:453
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_nmicallin
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
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
In kernel/debug/debug_core.c (ffffffff811791ee)
Location: kernel/debug/debug_core.c:453
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_nmicallin
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
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
In kernel/debug/debug_core.c (ffffffff8118503e)
Location: kernel/debug/debug_core.c:453
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_nmicallin
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
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
In kernel/debug/debug_core.c (ffffffff811991b3)
Location: kernel/debug/debug_core.c:494
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_nmicallin
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int kgdb_io_ready(int print_wait);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff81195a4e)
Location: kernel/debug/debug_core.c:510
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
**Symbols:**

```
ffffffff811955f0-ffffffff81195649: kgdb_io_ready (STB_LOCAL)
ffffffff81be4b33-ffffffff81be4b44: kgdb_io_ready.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int kgdb_io_ready(int print_wait);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff811969ee)
Location: kernel/debug/debug_core.c:509
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
**Symbols:**

```
ffffffff811965e0-ffffffff81196639: kgdb_io_ready (STB_LOCAL)
ffffffff81bd69a6-ffffffff81bd69b7: kgdb_io_ready.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int kgdb_io_ready(int print_wait);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff811bfdc8)
Location: kernel/debug/debug_core.c:506
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
**Symbols:**

```
ffffffff811bf620-ffffffff811bf679: kgdb_io_ready (STB_LOCAL)
ffffffff81cb39aa-ffffffff81cb39bb: kgdb_io_ready.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
int kgdb_io_ready(int print_wait);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff811f32c9)
Location: kernel/debug/debug_core.c:507
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
**Symbols:**

```
ffffffff811f2860-ffffffff811f28a4: kgdb_io_ready (STB_LOCAL)
ffffffff81e647c1-ffffffff81e647de: kgdb_io_ready.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int kgdb_io_ready(int print_wait);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff8123a055)
Location: kernel/debug/debug_core.c:495
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
**Symbols:**

```
ffffffff81239630-ffffffff8123968d: kgdb_io_ready (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int kgdb_io_ready(int print_wait);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff81251065)
Location: kernel/debug/debug_core.c:495
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
**Symbols:**

```
ffffffff81250640-ffffffff8125069d: kgdb_io_ready (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int kgdb_io_ready(int print_wait);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff8126aeb5)
Location: kernel/debug/debug_core.c:495
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
**Symbols:**

```
ffffffff8126a490-ffffffff8126a4ed: kgdb_io_ready (STB_LOCAL)
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
In kernel/debug/debug_core.c (ffff8000101fac6c)
Location: kernel/debug/debug_core.c:453
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_nmicallin
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
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
In kernel/debug/debug_core.c (c043ad74)
Location: kernel/debug/debug_core.c:453
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_nmicallin
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
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
In kernel/debug/debug_core.c (c0000000002727b0)
Location: kernel/debug/debug_core.c:453
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_nmicallin
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
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
In kernel/debug/debug_core.c (ffffffff8117d65e)
Location: kernel/debug/debug_core.c:453
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_nmicallin
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
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
In kernel/debug/debug_core.c (ffffffff811707ae)
Location: kernel/debug/debug_core.c:453
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_nmicallin
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
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
In kernel/debug/debug_core.c (ffffffff8117b42e)
Location: kernel/debug/debug_core.c:453
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_nmicallin
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
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
In kernel/debug/debug_core.c (ffffffff81188d4e)
Location: kernel/debug/debug_core.c:453
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_nmicallin
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
