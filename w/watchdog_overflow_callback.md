# Function: <code>watchdog_overflow_callback</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void watchdog_overflow_callback(struct perf_event *event, struct perf_sample_data *data, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/watchdog.c (ffffffff8113ae30)
Location: kernel/watchdog.c:311
Inline: True
```
**Symbols:**

```
ffffffff8113ae30-ffffffff8113aefb: watchdog_overflow_callback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void watchdog_overflow_callback(struct perf_event *event, struct perf_sample_data *data, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/watchdog.c (ffffffff81143360)
Location: kernel/watchdog.c:327
Inline: True
```
**Symbols:**

```
ffffffff81143360-ffffffff81143432: watchdog_overflow_callback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void watchdog_overflow_callback(struct perf_event *event, struct perf_sample_data *data, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/watchdog_hld.c (ffffffff8114d5b0)
Location: kernel/watchdog_hld.c:80
Inline: True
```
**Symbols:**

```
ffffffff8114d5b0-ffffffff8114d67f: watchdog_overflow_callback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void watchdog_overflow_callback(struct perf_event *event, struct perf_sample_data *data, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/watchdog_hld.c (ffffffff8114f580)
Location: kernel/watchdog_hld.c:105
Inline: True
```
**Symbols:**

```
ffffffff8114f580-ffffffff8114f690: watchdog_overflow_callback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void watchdog_overflow_callback(struct perf_event *event, struct perf_sample_data *data, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/watchdog_hld.c (ffffffff8115bcb0)
Location: kernel/watchdog_hld.c:110
Inline: True
```
**Symbols:**

```
ffffffff8115bcb0-ffffffff8115bdb9: watchdog_overflow_callback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
void watchdog_overflow_callback(struct perf_event *event, struct perf_sample_data *data, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/watchdog_hld.c (0)
Location: kernel/watchdog_hld.c:110
Inline: True
```
**Symbols:**

```
ffffffff8116a890-ffffffff8116a92f: watchdog_overflow_callback (STB_LOCAL)
ffffffff8116aa8e-ffffffff8116aafe: watchdog_overflow_callback.cold.7 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
void watchdog_overflow_callback(struct perf_event *event, struct perf_sample_data *data, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/watchdog_hld.c (ffffffff81177aa3)
Location: kernel/watchdog_hld.c:110
Inline: True
```
**Symbols:**

```
ffffffff811778a0-ffffffff8117793f: watchdog_overflow_callback (STB_LOCAL)
ffffffff81177a85-ffffffff81177af5: watchdog_overflow_callback.cold.7 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void watchdog_overflow_callback(struct perf_event *event, struct perf_sample_data *data, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/watchdog_hld.c (ffffffff81184909)
Location: kernel/watchdog_hld.c:110
Inline: True
```
**Symbols:**

```
ffffffff81184700-ffffffff8118479e: watchdog_overflow_callback (STB_LOCAL)
ffffffff811848eb-ffffffff8118495b: watchdog_overflow_callback.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void watchdog_overflow_callback(struct perf_event *event, struct perf_sample_data *data, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/watchdog_hld.c (ffffffff81190789)
Location: kernel/watchdog_hld.c:110
Inline: True
```
**Symbols:**

```
ffffffff81190580-ffffffff8119061e: watchdog_overflow_callback (STB_LOCAL)
ffffffff8119076b-ffffffff811907db: watchdog_overflow_callback.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void watchdog_overflow_callback(struct perf_event *event, struct perf_sample_data *data, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/watchdog_hld.c (ffffffff811a5120)
Location: kernel/watchdog_hld.c:110
Inline: True
```
**Symbols:**

```
ffffffff811a5120-ffffffff811a51b2: watchdog_overflow_callback (STB_LOCAL)
ffffffff811a50f0-ffffffff811a5117: watchdog_overflow_callback.part.0 (STB_LOCAL)
ffffffff811a5313-ffffffff811a5386: watchdog_overflow_callback.part.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void watchdog_overflow_callback(struct perf_event *event, struct perf_sample_data *data, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/watchdog_hld.c (ffffffff811a2110)
Location: kernel/watchdog_hld.c:110
Inline: True
```
**Symbols:**

```
ffffffff811a2110-ffffffff811a21a2: watchdog_overflow_callback (STB_LOCAL)
ffffffff811a20e0-ffffffff811a2107: watchdog_overflow_callback.part.0 (STB_LOCAL)
ffffffff81be4ff1-ffffffff81be5064: watchdog_overflow_callback.part.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void watchdog_overflow_callback(struct perf_event *event, struct perf_sample_data *data, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/watchdog_hld.c (ffffffff811a2e58)
Location: kernel/watchdog_hld.c:110
Inline: True
```
**Symbols:**

```
ffffffff811a2dd0-ffffffff811a2e70: watchdog_overflow_callback (STB_LOCAL)
ffffffff81bd6de4-ffffffff81bd6e54: watchdog_overflow_callback.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void watchdog_overflow_callback(struct perf_event *event, struct perf_sample_data *data, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/watchdog_hld.c (ffffffff811cc688)
Location: kernel/watchdog_hld.c:110
Inline: True
```
**Symbols:**

```
ffffffff811cc600-ffffffff811cc6a0: watchdog_overflow_callback (STB_LOCAL)
ffffffff81cb3ef2-ffffffff81cb3f62: watchdog_overflow_callback.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void watchdog_overflow_callback(struct perf_event *event, struct perf_sample_data *data, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/watchdog_hld.c (ffffffff81200583)
Location: kernel/watchdog_hld.c:110
Inline: True
```
**Symbols:**

```
ffffffff812004e0-ffffffff8120059b: watchdog_overflow_callback (STB_LOCAL)
ffffffff81e64da0-ffffffff81e64e10: watchdog_overflow_callback.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void watchdog_overflow_callback(struct perf_event *event, struct perf_sample_data *data, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/watchdog_hld.c (ffffffff81248100)
Location: kernel/watchdog_hld.c:110
Inline: True
```
**Symbols:**

```
ffffffff81248100-ffffffff8124823c: watchdog_overflow_callback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void watchdog_overflow_callback(struct perf_event *event, struct perf_sample_data *data, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/watchdog_perf.c (ffffffff8125f4c0)
Location: kernel/watchdog_perf.c:94
Inline: True
```
**Symbols:**

```
ffffffff8125f4c0-ffffffff8125f53f: watchdog_overflow_callback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void watchdog_overflow_callback(struct perf_event *event, struct perf_sample_data *data, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/watchdog_perf.c (ffffffff812794d0)
Location: kernel/watchdog_perf.c:94
Inline: True
```
**Symbols:**

```
ffffffff812794d0-ffffffff8127954f: watchdog_overflow_callback (STB_LOCAL)
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

```c
void watchdog_overflow_callback(struct perf_event *event, struct perf_sample_data *data, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/watchdog_hld.c (ffffffff81188da9)
Location: kernel/watchdog_hld.c:110
Inline: True
```
**Symbols:**

```
ffffffff81188ba0-ffffffff81188c3e: watchdog_overflow_callback (STB_LOCAL)
ffffffff81188d8b-ffffffff81188dfb: watchdog_overflow_callback.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
void watchdog_overflow_callback(struct perf_event *event, struct perf_sample_data *data, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/watchdog_hld.c (ffffffff8117bee9)
Location: kernel/watchdog_hld.c:110
Inline: True
```
**Symbols:**

```
ffffffff8117bce0-ffffffff8117bd7e: watchdog_overflow_callback (STB_LOCAL)
ffffffff8117becb-ffffffff8117bf3b: watchdog_overflow_callback.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void watchdog_overflow_callback(struct perf_event *event, struct perf_sample_data *data, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/watchdog_hld.c (ffffffff81186b79)
Location: kernel/watchdog_hld.c:110
Inline: True
```
**Symbols:**

```
ffffffff81186970-ffffffff81186a0e: watchdog_overflow_callback (STB_LOCAL)
ffffffff81186b5b-ffffffff81186bcb: watchdog_overflow_callback.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void watchdog_overflow_callback(struct perf_event *event, struct perf_sample_data *data, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/watchdog_hld.c (ffffffff811944c9)
Location: kernel/watchdog_hld.c:110
Inline: True
```
**Symbols:**

```
ffffffff811942c0-ffffffff8119435e: watchdog_overflow_callback (STB_LOCAL)
ffffffff811944ab-ffffffff8119451b: watchdog_overflow_callback.cold (STB_LOCAL)
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
