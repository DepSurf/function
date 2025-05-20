# Function: <code>print_stop_info</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void print_stop_info(const char *log_lvl, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/stop_machine.c (0)
Location: kernel/stop_machine.c:52
Inline: False
Direct callers:
  - lib/dump_stack.c:dump_stack_print_info
```
**Symbols:**

```
ffffffff81be48a5-ffffffff81be48c1: print_stop_info.cold (STB_LOCAL)
ffffffff81182e00-ffffffff81182e26: print_stop_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void print_stop_info(const char *log_lvl, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/stop_machine.c (0)
Location: kernel/stop_machine.c:52
Inline: False
Direct callers:
  - lib/dump_stack.c:dump_stack_print_info
```
**Symbols:**

```
ffffffff81bd6705-ffffffff81bd6722: print_stop_info.cold (STB_LOCAL)
ffffffff81183de0-ffffffff81183e01: print_stop_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void print_stop_info(const char *log_lvl, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/stop_machine.c (0)
Location: kernel/stop_machine.c:52
Inline: False
Direct callers:
  - lib/dump_stack.c:dump_stack_print_info
```
**Symbols:**

```
ffffffff81cb342b-ffffffff81cb3447: print_stop_info.cold (STB_LOCAL)
ffffffff811ac160-ffffffff811ac1b5: print_stop_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void print_stop_info(const char *log_lvl, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/stop_machine.c (0)
Location: kernel/stop_machine.c:52
Inline: False
Direct callers:
  - lib/dump_stack.c:dump_stack_print_info
```
**Symbols:**

```
ffffffff81e6425c-ffffffff81e64278: print_stop_info.cold (STB_LOCAL)
ffffffff811ddb70-ffffffff811ddbd3: print_stop_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void print_stop_info(const char *log_lvl, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff81223600)
Location: kernel/stop_machine.c:52
Inline: False
Direct callers:
  - lib/dump_stack.c:dump_stack_print_info
```
**Symbols:**

```
ffffffff81223600-ffffffff8122368d: print_stop_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void print_stop_info(const char *log_lvl, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff81239ca0)
Location: kernel/stop_machine.c:52
Inline: False
Direct callers:
  - lib/dump_stack.c:dump_stack_print_info
```
**Symbols:**

```
ffffffff81239ca0-ffffffff81239d2d: print_stop_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void print_stop_info(const char *log_lvl, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff81253970)
Location: kernel/stop_machine.c:52
Inline: False
Direct callers:
  - lib/dump_stack.c:dump_stack_print_info
```
**Symbols:**

```
ffffffff81253970-ffffffff812539fd: print_stop_info (STB_GLOBAL)
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
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
