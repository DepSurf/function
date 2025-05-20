# Function: <code>print_tickdevice</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/time/timer_list.c (ffffffff810f9420)
Location: kernel/time/timer_list.c:206
Inline: True
Direct callers:
  - kernel/time/timer_list.c:timer_list_show_tickdevices_header
  - kernel/time/timer_list.c:timer_list_show
  - kernel/time/timer_list.c:sysrq_timer_list_show
```
**Symbols:**

```
ffffffff810f9420-ffffffff810f96ad: print_tickdevice.isra.4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/time/timer_list.c (ffffffff811006a0)
Location: kernel/time/timer_list.c:206
Inline: True
Direct callers:
  - kernel/time/timer_list.c:sysrq_timer_list_show
  - kernel/time/timer_list.c:timer_list_show
  - kernel/time/timer_list.c:timer_list_show_tickdevices_header
```
**Symbols:**

```
ffffffff811006a0-ffffffff8110092d: print_tickdevice.isra.4 (STB_LOCAL)
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
In kernel/time/timer_list.c (ffffffff81103440)
Location: kernel/time/timer_list.c:206
Inline: True
Direct callers:
  - kernel/time/timer_list.c:sysrq_timer_list_show
  - kernel/time/timer_list.c:timer_list_show
  - kernel/time/timer_list.c:timer_list_show_tickdevices_header
```
**Symbols:**

```
ffffffff81103440-ffffffff811036cd: print_tickdevice.isra.4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void print_tickdevice(struct seq_file *m, struct tick_device *td, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer_list.c (ffffffff81105470)
Location: kernel/time/timer_list.c:200
Inline: False
Direct callers:
  - kernel/time/timer_list.c:sysrq_timer_list_show
  - kernel/time/timer_list.c:timer_list_show
  - kernel/time/timer_list.c:timer_list_show_tickdevices_header
```
**Symbols:**

```
ffffffff81105470-ffffffff81105717: print_tickdevice (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void print_tickdevice(struct seq_file *m, struct tick_device *td, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer_list.c (ffffffff811105d0)
Location: kernel/time/timer_list.c:200
Inline: False
Direct callers:
  - kernel/time/timer_list.c:sysrq_timer_list_show
  - kernel/time/timer_list.c:timer_list_show
  - kernel/time/timer_list.c:timer_list_show_tickdevices_header
```
**Symbols:**

```
ffffffff811105d0-ffffffff81110877: print_tickdevice (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/time/timer_list.c (ffffffff8111bff0)
Location: kernel/time/timer_list.c:198
Inline: True
Direct callers:
  - kernel/time/timer_list.c:sysrq_timer_list_show
  - kernel/time/timer_list.c:timer_list_show
  - kernel/time/timer_list.c:timer_list_show_tickdevices_header
```
**Symbols:**

```
ffffffff8111bff0-ffffffff8111c296: print_tickdevice.isra.4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/time/timer_list.c (ffffffff811277a0)
Location: kernel/time/timer_list.c:193
Inline: True
Direct callers:
  - kernel/time/timer_list.c:sysrq_timer_list_show
  - kernel/time/timer_list.c:timer_list_show
  - kernel/time/timer_list.c:timer_list_show_tickdevices_header
```
**Symbols:**

```
ffffffff811277a0-ffffffff81127a46: print_tickdevice.isra.4 (STB_LOCAL)
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
In kernel/time/timer_list.c (ffffffff811321d0)
Location: kernel/time/timer_list.c:193
Inline: True
Direct callers:
  - kernel/time/timer_list.c:timer_list_show
  - kernel/time/timer_list.c:sysrq_timer_list_show
  - kernel/time/timer_list.c:timer_list_show_tickdevices_header
```
**Symbols:**

```
ffffffff811321d0-ffffffff8113245f: print_tickdevice.isra.0 (STB_LOCAL)
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
In kernel/time/timer_list.c (ffffffff8113e120)
Location: kernel/time/timer_list.c:193
Inline: True
Direct callers:
  - kernel/time/timer_list.c:timer_list_show
  - kernel/time/timer_list.c:sysrq_timer_list_show
  - kernel/time/timer_list.c:timer_list_show_tickdevices_header
```
**Symbols:**

```
ffffffff8113e120-ffffffff8113e3af: print_tickdevice.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void print_tickdevice(struct seq_file *m, struct tick_device *td, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer_list.c (ffffffff8114d2f0)
Location: kernel/time/timer_list.c:193
Inline: False
Direct callers:
  - kernel/time/timer_list.c:timer_list_show
  - kernel/time/timer_list.c:sysrq_timer_list_show
  - kernel/time/timer_list.c:timer_list_show_tickdevices_header
```
**Symbols:**

```
ffffffff8114d2f0-ffffffff8114d580: print_tickdevice (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void print_tickdevice(struct seq_file *m, struct tick_device *td, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer_list.c (ffffffff811494d0)
Location: kernel/time/timer_list.c:178
Inline: False
Direct callers:
  - kernel/time/timer_list.c:timer_list_show
  - kernel/time/timer_list.c:sysrq_timer_list_show
  - kernel/time/timer_list.c:timer_list_show_tickdevices_header
```
**Symbols:**

```
ffffffff811494d0-ffffffff811496c4: print_tickdevice (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void print_tickdevice(struct seq_file *m, struct tick_device *td, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer_list.c (ffffffff8114a9a0)
Location: kernel/time/timer_list.c:178
Inline: False
Direct callers:
  - kernel/time/timer_list.c:timer_list_show
  - kernel/time/timer_list.c:sysrq_timer_list_show
  - kernel/time/timer_list.c:timer_list_show_tickdevices_header
```
**Symbols:**

```
ffffffff8114a9a0-ffffffff8114ab94: print_tickdevice (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void print_tickdevice(struct seq_file *m, struct tick_device *td, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer_list.c (ffffffff8116e6c0)
Location: kernel/time/timer_list.c:178
Inline: False
Direct callers:
  - kernel/time/timer_list.c:timer_list_show
  - kernel/time/timer_list.c:sysrq_timer_list_show
  - kernel/time/timer_list.c:timer_list_show_tickdevices_header
```
**Symbols:**

```
ffffffff8116e6c0-ffffffff8116e8e5: print_tickdevice (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void print_tickdevice(struct seq_file *m, struct tick_device *td, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer_list.c (ffffffff811a2970)
Location: kernel/time/timer_list.c:178
Inline: False
Direct callers:
  - kernel/time/timer_list.c:timer_list_show
  - kernel/time/timer_list.c:sysrq_timer_list_show
  - kernel/time/timer_list.c:timer_list_show_tickdevices_header
```
**Symbols:**

```
ffffffff811a2970-ffffffff811a2bbf: print_tickdevice (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void print_tickdevice(struct seq_file *m, struct tick_device *td, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer_list.c (ffffffff811e1ed0)
Location: kernel/time/timer_list.c:178
Inline: False
Direct callers:
  - kernel/time/timer_list.c:timer_list_show
  - kernel/time/timer_list.c:sysrq_timer_list_show
  - kernel/time/timer_list.c:timer_list_show_tickdevices_header
```
**Symbols:**

```
ffffffff811e1ed0-ffffffff811e211f: print_tickdevice (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void print_tickdevice(struct seq_file *m, struct tick_device *td, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer_list.c (ffffffff811f6430)
Location: kernel/time/timer_list.c:178
Inline: False
Direct callers:
  - kernel/time/timer_list.c:timer_list_show
  - kernel/time/timer_list.c:sysrq_timer_list_show
  - kernel/time/timer_list.c:timer_list_show_tickdevices_header
```
**Symbols:**

```
ffffffff811f6430-ffffffff811f667f: print_tickdevice (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void print_tickdevice(struct seq_file *m, struct tick_device *td, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer_list.c (ffffffff8120c5d0)
Location: kernel/time/timer_list.c:178
Inline: False
Direct callers:
  - kernel/time/timer_list.c:timer_list_show
  - kernel/time/timer_list.c:sysrq_timer_list_show
  - kernel/time/timer_list.c:timer_list_show_tickdevices_header
```
**Symbols:**

```
ffffffff8120c5d0-ffffffff8120c81f: print_tickdevice (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/time/timer_list.c (ffff8000101a7800)
Location: kernel/time/timer_list.c:193
Inline: True
Direct callers:
  - kernel/time/timer_list.c:timer_list_show
  - kernel/time/timer_list.c:sysrq_timer_list_show
  - kernel/time/timer_list.c:timer_list_show_tickdevices_header
```
**Symbols:**

```
ffff8000101a7800-ffff8000101a7ab4: print_tickdevice.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void print_tickdevice(struct seq_file *m, struct tick_device *td, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer_list.c (c03f3154)
Location: kernel/time/timer_list.c:193
Inline: False
Direct callers:
  - kernel/time/timer_list.c:sysrq_timer_list_show
  - kernel/time/timer_list.c:timer_list_show_tickdevices_header
```
**Symbols:**

```
c03f3154-c03f3410: print_tickdevice (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/time/timer_list.c (c00000000020ab00)
Location: kernel/time/timer_list.c:193
Inline: True
Direct callers:
  - kernel/time/timer_list.c:timer_list_show
  - kernel/time/timer_list.c:sysrq_timer_list_show
  - kernel/time/timer_list.c:timer_list_show_tickdevices_header
```
**Symbols:**

```
c00000000020ab00-c00000000020ae18: print_tickdevice.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/time/timer_list.c (ffffffe000133c18)
Location: kernel/time/timer_list.c:193
Inline: True
Direct callers:
  - kernel/time/timer_list.c:timer_list_show
  - kernel/time/timer_list.c:sysrq_timer_list_show
```
**Symbols:**

```
ffffffe000133c18-ffffffe000133f1e: print_tickdevice.isra.0 (STB_LOCAL)
```
</details>
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
In kernel/time/timer_list.c (ffffffff811368d0)
Location: kernel/time/timer_list.c:193
Inline: True
Direct callers:
  - kernel/time/timer_list.c:timer_list_show
  - kernel/time/timer_list.c:sysrq_timer_list_show
  - kernel/time/timer_list.c:timer_list_show_tickdevices_header
```
**Symbols:**

```
ffffffff811368d0-ffffffff81136b5f: print_tickdevice.isra.0 (STB_LOCAL)
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
In kernel/time/timer_list.c (ffffffff81129320)
Location: kernel/time/timer_list.c:193
Inline: True
Direct callers:
  - kernel/time/timer_list.c:timer_list_show
  - kernel/time/timer_list.c:sysrq_timer_list_show
  - kernel/time/timer_list.c:timer_list_show_tickdevices_header
```
**Symbols:**

```
ffffffff81129320-ffffffff811295af: print_tickdevice.isra.0 (STB_LOCAL)
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
In kernel/time/timer_list.c (ffffffff811345f0)
Location: kernel/time/timer_list.c:193
Inline: True
Direct callers:
  - kernel/time/timer_list.c:timer_list_show
  - kernel/time/timer_list.c:sysrq_timer_list_show
  - kernel/time/timer_list.c:timer_list_show_tickdevices_header
```
**Symbols:**

```
ffffffff811345f0-ffffffff8113487f: print_tickdevice.isra.0 (STB_LOCAL)
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
In kernel/time/timer_list.c (ffffffff81141010)
Location: kernel/time/timer_list.c:193
Inline: True
Direct callers:
  - kernel/time/timer_list.c:timer_list_show
  - kernel/time/timer_list.c:sysrq_timer_list_show
  - kernel/time/timer_list.c:timer_list_show_tickdevices_header
```
**Symbols:**

```
ffffffff81141010-ffffffff8114129f: print_tickdevice.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
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
<b>Arch</b>
<ul>
</ul>
