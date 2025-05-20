# Function: <code>perf_install_in_context</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void perf_install_in_context(struct perf_event_context *ctx, struct perf_event *event, int cpu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8117dca0)
Location: kernel/events/core.c:2142
Inline: True
Direct callers:
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:perf_event_create_kernel_counter
  - kernel/events/core.c:SYSC_perf_event_open
  - kernel/events/core.c:SYSC_perf_event_open
  - kernel/events/core.c:SYSC_perf_event_open
  - kernel/events/core.c:SYSC_perf_event_open
```
**Symbols:**

```
ffffffff8117dca0-ffffffff8117dd9b: perf_install_in_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void perf_install_in_context(struct perf_event_context *ctx, struct perf_event *event, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8118fba0)
Location: kernel/events/core.c:2290
Inline: False
Direct callers:
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:perf_event_create_kernel_counter
  - kernel/events/core.c:SYSC_perf_event_open
  - kernel/events/core.c:SYSC_perf_event_open
  - kernel/events/core.c:SYSC_perf_event_open
  - kernel/events/core.c:SYSC_perf_event_open
```
**Symbols:**

```
ffffffff8118fba0-ffffffff8118fd11: perf_install_in_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void perf_install_in_context(struct perf_event_context *ctx, struct perf_event *event, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8119fb10)
Location: kernel/events/core.c:2327
Inline: False
Direct callers:
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:perf_event_create_kernel_counter
  - kernel/events/core.c:SYSC_perf_event_open
  - kernel/events/core.c:SYSC_perf_event_open
  - kernel/events/core.c:SYSC_perf_event_open
  - kernel/events/core.c:SYSC_perf_event_open
```
**Symbols:**

```
ffffffff8119fb10-ffffffff8119fc8b: perf_install_in_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void perf_install_in_context(struct perf_event_context *ctx, struct perf_event *event, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811a7770)
Location: kernel/events/core.c:2409
Inline: False
Direct callers:
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:perf_event_create_kernel_counter
  - kernel/events/core.c:SYSC_perf_event_open
  - kernel/events/core.c:SYSC_perf_event_open
  - kernel/events/core.c:SYSC_perf_event_open
  - kernel/events/core.c:SYSC_perf_event_open
```
**Symbols:**

```
ffffffff811a7770-ffffffff811a78a3: perf_install_in_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void perf_install_in_context(struct perf_event_context *ctx, struct perf_event *event, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811baee0)
Location: kernel/events/core.c:2345
Inline: False
Direct callers:
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:perf_event_create_kernel_counter
  - kernel/events/core.c:SYSC_perf_event_open
  - kernel/events/core.c:SYSC_perf_event_open
  - kernel/events/core.c:SYSC_perf_event_open
  - kernel/events/core.c:SYSC_perf_event_open
```
**Symbols:**

```
ffffffff811baee0-ffffffff811bb01b: perf_install_in_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void perf_install_in_context(struct perf_event_context *ctx, struct perf_event *event, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811dacd0)
Location: kernel/events/core.c:2554
Inline: False
Direct callers:
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:perf_event_create_kernel_counter
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
```
**Symbols:**

```
ffffffff811dacd0-ffffffff811dae0e: perf_install_in_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void perf_install_in_context(struct perf_event_context *ctx, struct perf_event *event, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811eaed0)
Location: kernel/events/core.c:2554
Inline: False
Direct callers:
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:perf_event_create_kernel_counter
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
```
**Symbols:**

```
ffffffff811eaed0-ffffffff811eb00e: perf_install_in_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void perf_install_in_context(struct perf_event_context *ctx, struct perf_event *event, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81202e10)
Location: kernel/events/core.c:2570
Inline: False
Direct callers:
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:perf_event_create_kernel_counter
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
```
**Symbols:**

```
ffffffff81202e10-ffffffff81202f72: perf_install_in_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void perf_install_in_context(struct perf_event_context *ctx, struct perf_event *event, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8120fcc0)
Location: kernel/events/core.c:2655
Inline: False
Direct callers:
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
```
**Symbols:**

```
ffffffff8120fcc0-ffffffff8120fe22: perf_install_in_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void perf_install_in_context(struct perf_event_context *ctx, struct perf_event *event, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8123bfd0)
Location: kernel/events/core.c:2804
Inline: False
Direct callers:
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
```
**Symbols:**

```
ffffffff8123bfd0-ffffffff8123c1aa: perf_install_in_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void perf_install_in_context(struct perf_event_context *ctx, struct perf_event *event, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81246270)
Location: kernel/events/core.c:2839
Inline: False
Direct callers:
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
```
**Symbols:**

```
ffffffff81246270-ffffffff81246449: perf_install_in_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void perf_install_in_context(struct perf_event_context *ctx, struct perf_event *event, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8124a390)
Location: kernel/events/core.c:2841
Inline: False
Direct callers:
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
```
**Symbols:**

```
ffffffff8124a390-ffffffff8124a569: perf_install_in_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void perf_install_in_context(struct perf_event_context *ctx, struct perf_event *event, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81283330)
Location: kernel/events/core.c:2880
Inline: False
Direct callers:
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
```
**Symbols:**

```
ffffffff81283330-ffffffff81283517: perf_install_in_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void perf_install_in_context(struct perf_event_context *ctx, struct perf_event *event, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812cfdd0)
Location: kernel/events/core.c:2791
Inline: False
Direct callers:
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
```
**Symbols:**

```
ffffffff812cfdd0-ffffffff812cffde: perf_install_in_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void perf_install_in_context(struct perf_event_context *ctx, struct perf_event *event, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81339910)
Location: kernel/events/core.c:2794
Inline: False
Direct callers:
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
```
**Symbols:**

```
ffffffff81339910-ffffffff81339af8: perf_install_in_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void perf_install_in_context(struct perf_event_context *ctx, struct perf_event *event, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8136a9d0)
Location: kernel/events/core.c:2794
Inline: False
Direct callers:
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
```
**Symbols:**

```
ffffffff8136a9d0-ffffffff8136abb8: perf_install_in_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void perf_install_in_context(struct perf_event_context *ctx, struct perf_event *event, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8138fd50)
Location: kernel/events/core.c:2832
Inline: False
Direct callers:
  - kernel/events/core.c:__perf_pmu_install_event
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
```
**Symbols:**

```
ffffffff8138fd50-ffffffff8138ff38: perf_install_in_context (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void perf_install_in_context(struct perf_event_context *ctx, struct perf_event *event, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffff8000102981a0)
Location: kernel/events/core.c:2655
Inline: False
Direct callers:
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
```
**Symbols:**

```
ffff8000102981a0-ffff800010298388: perf_install_in_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void perf_install_in_context(struct perf_event_context *ctx, struct perf_event *event, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c04c2f60)
Location: kernel/events/core.c:2655
Inline: False
Direct callers:
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
```
**Symbols:**

```
c04c2f60-c04c3168: perf_install_in_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void perf_install_in_context(struct perf_event_context *ctx, struct perf_event *event, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c000000000346870)
Location: kernel/events/core.c:2655
Inline: False
Direct callers:
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
```
**Symbols:**

```
c000000000346870-c000000000346adc: perf_install_in_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void perf_install_in_context(struct perf_event_context *ctx, struct perf_event *event, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffe0001c9532)
Location: kernel/events/core.c:2655
Inline: False
Direct callers:
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
```
**Symbols:**

```
ffffffe0001c9532-ffffffe0001c96be: perf_install_in_context (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void perf_install_in_context(struct perf_event_context *ctx, struct perf_event *event, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812082e0)
Location: kernel/events/core.c:2655
Inline: False
Direct callers:
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
```
**Symbols:**

```
ffffffff812082e0-ffffffff81208442: perf_install_in_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void perf_install_in_context(struct perf_event_context *ctx, struct perf_event *event, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811fa1a0)
Location: kernel/events/core.c:2655
Inline: False
Direct callers:
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
```
**Symbols:**

```
ffffffff811fa1a0-ffffffff811fa2ed: perf_install_in_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void perf_install_in_context(struct perf_event_context *ctx, struct perf_event *event, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812060b0)
Location: kernel/events/core.c:2655
Inline: False
Direct callers:
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
```
**Symbols:**

```
ffffffff812060b0-ffffffff81206212: perf_install_in_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void perf_install_in_context(struct perf_event_context *ctx, struct perf_event *event, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81211ce0)
Location: kernel/events/core.c:2655
Inline: False
Direct callers:
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
```
**Symbols:**

```
ffffffff81211ce0-ffffffff81211e24: perf_install_in_context (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
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
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
