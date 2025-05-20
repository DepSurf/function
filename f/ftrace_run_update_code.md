# Function: <code>ftrace_run_update_code</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void ftrace_run_update_code(int command);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81143af0)
Location: kernel/trace/ftrace.c:2529
Inline: True
Direct callers:
  - kernel/trace/ftrace.c:ftrace_startup_enable
  - kernel/trace/ftrace.c:register_ftrace_function_probe
  - kernel/trace/ftrace.c:ftrace_enable_sysctl
```
**Symbols:**

```
ffffffff81143af0-ffffffff81143b4b: ftrace_run_update_code (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void ftrace_run_update_code(int command);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8114b8f0)
Location: kernel/trace/ftrace.c:2587
Inline: True
Direct callers:
  - kernel/trace/ftrace.c:ftrace_enable_sysctl
  - kernel/trace/ftrace.c:register_ftrace_function_probe
  - kernel/trace/ftrace.c:ftrace_startup_enable
```
**Symbols:**

```
ffffffff8114b8f0-ffffffff8114b94b: ftrace_run_update_code (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void ftrace_run_update_code(int command);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811557e0)
Location: kernel/trace/ftrace.c:2605
Inline: True
Direct callers:
  - kernel/trace/ftrace.c:ftrace_enable_sysctl
  - kernel/trace/ftrace.c:register_ftrace_function_probe
  - kernel/trace/ftrace.c:ftrace_startup_enable
```
**Symbols:**

```
ffffffff811557e0-ffffffff8115583b: ftrace_run_update_code (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void ftrace_run_update_code(int command);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81158070)
Location: kernel/trace/ftrace.c:2690
Inline: True
Direct callers:
  - kernel/trace/ftrace.c:ftrace_enable_sysctl
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
  - kernel/trace/ftrace.c:ftrace_startup_enable
```
**Symbols:**

```
ffffffff81158070-ffffffff811580da: ftrace_run_update_code (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void ftrace_run_update_code(int command);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81164b70)
Location: kernel/trace/ftrace.c:2666
Inline: True
Direct callers:
  - kernel/trace/ftrace.c:ftrace_enable_sysctl
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
  - kernel/trace/ftrace.c:ftrace_startup_enable
```
**Symbols:**

```
ffffffff81164b70-ffffffff81164bda: ftrace_run_update_code (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void ftrace_run_update_code(int command);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81173880)
Location: kernel/trace/ftrace.c:2655
Inline: True
Direct callers:
  - kernel/trace/ftrace.c:ftrace_enable_sysctl
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
  - kernel/trace/ftrace.c:ftrace_startup_enable
```
**Symbols:**

```
ffffffff81173880-ffffffff811738e9: ftrace_run_update_code (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void ftrace_run_update_code(int command);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811814d0)
Location: kernel/trace/ftrace.c:2612
Inline: True
Direct callers:
  - kernel/trace/ftrace.c:ftrace_enable_sysctl
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
  - kernel/trace/ftrace.c:ftrace_startup_enable
```
**Symbols:**

```
ffffffff811814d0-ffffffff81181539: ftrace_run_update_code (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void ftrace_run_update_code(int command);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8118e326)
Location: kernel/trace/ftrace.c:2611
Inline: True
Direct callers:
  - kernel/trace/ftrace.c:ftrace_enable_sysctl
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
  - kernel/trace/ftrace.c:ftrace_startup_enable
```
**Symbols:**

```
ffffffff8118e310-ffffffff8118e33f: ftrace_run_update_code (STB_LOCAL)
ffffffff811922b4-ffffffff81192318: ftrace_run_update_code.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void ftrace_run_update_code(int command);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8119a250)
Location: kernel/trace/ftrace.c:2612
Inline: True
Direct callers:
  - kernel/trace/ftrace.c:ftrace_enable_sysctl
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
  - kernel/trace/ftrace.c:ftrace_startup_enable
```
**Symbols:**

```
ffffffff8119a250-ffffffff8119a2bf: ftrace_run_update_code (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void ftrace_run_update_code(int command);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811afe30)
Location: kernel/trace/ftrace.c:2724
Inline: True
Direct callers:
  - kernel/trace/ftrace.c:ftrace_enable_sysctl
  - kernel/trace/ftrace.c:ftrace_no_pid_open
  - kernel/trace/ftrace.c:ftrace_pid_open
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
```
**Symbols:**

```
ffffffff811afe30-ffffffff811afea3: ftrace_run_update_code (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void ftrace_run_update_code(int command);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811ad7f0)
Location: kernel/trace/ftrace.c:2753
Inline: True
Direct callers:
  - kernel/trace/ftrace.c:ftrace_enable_sysctl
  - kernel/trace/ftrace.c:ftrace_no_pid_open
  - kernel/trace/ftrace.c:ftrace_pid_open
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
```
**Symbols:**

```
ffffffff811ad7f0-ffffffff811ad863: ftrace_run_update_code (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void ftrace_run_update_code(int command);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811ae360)
Location: kernel/trace/ftrace.c:2759
Inline: True
Direct callers:
  - kernel/trace/ftrace.c:ftrace_enable_sysctl
  - kernel/trace/ftrace.c:ftrace_no_pid_open
  - kernel/trace/ftrace.c:ftrace_pid_open
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
```
**Symbols:**

```
ffffffff811ae360-ffffffff811ae3d3: ftrace_run_update_code (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void ftrace_run_update_code(int command);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811d8130)
Location: kernel/trace/ftrace.c:2760
Inline: True
Direct callers:
  - kernel/trace/ftrace.c:ftrace_enable_sysctl
  - kernel/trace/ftrace.c:ftrace_no_pid_open
  - kernel/trace/ftrace.c:ftrace_pid_open
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
```
**Symbols:**

```
ffffffff811d8130-ffffffff811d81a3: ftrace_run_update_code (STB_LOCAL)
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
In kernel/trace/ftrace.c (ffffffff8120da28)
Location: kernel/trace/ftrace.c:2802
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_enable_sysctl
  - kernel/trace/ftrace.c:ftrace_no_pid_open
  - kernel/trace/ftrace.c:ftrace_pid_open
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
  - kernel/trace/ftrace.c:ftrace_startup
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
In kernel/trace/ftrace.c (ffffffff81256a08)
Location: kernel/trace/ftrace.c:2864
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_enable_sysctl
  - kernel/trace/ftrace.c:ftrace_no_pid_open
  - kernel/trace/ftrace.c:ftrace_pid_open
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
  - kernel/trace/ftrace.c:ftrace_startup
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
In kernel/trace/ftrace.c (ffffffff8126df08)
Location: kernel/trace/ftrace.c:2947
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_enable_sysctl
  - kernel/trace/ftrace.c:ftrace_no_pid_open
  - kernel/trace/ftrace.c:ftrace_pid_open
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
  - kernel/trace/ftrace.c:ftrace_startup
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
In kernel/trace/ftrace.c (ffffffff812883f8)
Location: kernel/trace/ftrace.c:2913
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_enable_sysctl
  - kernel/trace/ftrace.c:ftrace_no_pid_open
  - kernel/trace/ftrace.c:ftrace_pid_open
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
  - kernel/trace/ftrace.c:ftrace_startup
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void ftrace_run_update_code(int command);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffff800010212f20)
Location: kernel/trace/ftrace.c:2612
Inline: True
Direct callers:
  - kernel/trace/ftrace.c:ftrace_enable_sysctl
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
  - kernel/trace/ftrace.c:ftrace_startup_enable
```
**Symbols:**

```
ffff800010212f20-ffff800010212f88: ftrace_run_update_code (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void ftrace_run_update_code(int command);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (c0451c20)
Location: kernel/trace/ftrace.c:2612
Inline: True
Direct callers:
  - kernel/trace/ftrace.c:ftrace_enable_sysctl
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
  - kernel/trace/ftrace.c:ftrace_startup_enable
```
**Symbols:**

```
c0451c20-c0451ccc: ftrace_run_update_code (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void ftrace_run_update_code(int command);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (c000000000293060)
Location: kernel/trace/ftrace.c:2612
Inline: True
Direct callers:
  - kernel/trace/ftrace.c:ftrace_enable_sysctl
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
  - kernel/trace/ftrace.c:ftrace_startup_enable
```
**Symbols:**

```
c000000000293060-c000000000293118: ftrace_run_update_code (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void ftrace_run_update_code(int command);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffe00017325a)
Location: kernel/trace/ftrace.c:2612
Inline: True
Direct callers:
  - kernel/trace/ftrace.c:ftrace_enable_sysctl
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
  - kernel/trace/ftrace.c:ftrace_startup_enable
```
**Symbols:**

```
ffffffe00017325a-ffffffe0001732c0: ftrace_run_update_code (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void ftrace_run_update_code(int command);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81192870)
Location: kernel/trace/ftrace.c:2612
Inline: True
Direct callers:
  - kernel/trace/ftrace.c:ftrace_enable_sysctl
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
  - kernel/trace/ftrace.c:ftrace_startup_enable
```
**Symbols:**

```
ffffffff81192870-ffffffff811928df: ftrace_run_update_code (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void ftrace_run_update_code(int command);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81185980)
Location: kernel/trace/ftrace.c:2612
Inline: True
Direct callers:
  - kernel/trace/ftrace.c:ftrace_enable_sysctl
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
  - kernel/trace/ftrace.c:ftrace_startup_enable
```
**Symbols:**

```
ffffffff81185980-ffffffff811859ef: ftrace_run_update_code (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void ftrace_run_update_code(int command);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81190640)
Location: kernel/trace/ftrace.c:2612
Inline: True
Direct callers:
  - kernel/trace/ftrace.c:ftrace_enable_sysctl
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
  - kernel/trace/ftrace.c:ftrace_startup_enable
```
**Symbols:**

```
ffffffff81190640-ffffffff811906af: ftrace_run_update_code (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void ftrace_run_update_code(int command);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8119e1d0)
Location: kernel/trace/ftrace.c:2612
Inline: True
Direct callers:
  - kernel/trace/ftrace.c:ftrace_enable_sysctl
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
  - kernel/trace/ftrace.c:ftrace_startup_enable
```
**Symbols:**

```
ffffffff8119e1d0-ffffffff8119e23f: ftrace_run_update_code (STB_LOCAL)
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
