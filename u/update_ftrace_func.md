# Function: <code>update_ftrace_func</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int update_ftrace_func(long unsigned int ip, void *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ftrace.c (ffffffff8105acc0)
Location: arch/x86/kernel/ftrace.c:228
Inline: False
Direct callers:
  - arch/x86/kernel/ftrace.c:ftrace_update_ftrace_func
  - arch/x86/kernel/ftrace.c:ftrace_update_ftrace_func
  - arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline
  - arch/x86/kernel/ftrace.c:ftrace_enable_ftrace_graph_caller
  - arch/x86/kernel/ftrace.c:ftrace_disable_ftrace_graph_caller
```
**Symbols:**

```
ffffffff8105acc0-ffffffff8105ad8d: update_ftrace_func (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int update_ftrace_func(long unsigned int ip, void *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ftrace.c (ffffffff8105ad50)
Location: arch/x86/kernel/ftrace.c:231
Inline: False
Direct callers:
  - arch/x86/kernel/ftrace.c:ftrace_disable_ftrace_graph_caller
  - arch/x86/kernel/ftrace.c:ftrace_enable_ftrace_graph_caller
  - arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline
  - arch/x86/kernel/ftrace.c:ftrace_update_ftrace_func
  - arch/x86/kernel/ftrace.c:ftrace_update_ftrace_func
```
**Symbols:**

```
ffffffff8105ad50-ffffffff8105ae1d: update_ftrace_func (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int update_ftrace_func(long unsigned int ip, void *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ftrace.c (ffffffff8105db90)
Location: arch/x86/kernel/ftrace.c:231
Inline: False
Direct callers:
  - arch/x86/kernel/ftrace.c:ftrace_disable_ftrace_graph_caller
  - arch/x86/kernel/ftrace.c:ftrace_enable_ftrace_graph_caller
  - arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline
  - arch/x86/kernel/ftrace.c:ftrace_update_ftrace_func
  - arch/x86/kernel/ftrace.c:ftrace_update_ftrace_func
```
**Symbols:**

```
ffffffff8105db90-ffffffff8105dc5d: update_ftrace_func (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int update_ftrace_func(long unsigned int ip, void *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ftrace.c (ffffffff8105d240)
Location: arch/x86/kernel/ftrace.c:231
Inline: False
Direct callers:
  - arch/x86/kernel/ftrace.c:ftrace_disable_ftrace_graph_caller
  - arch/x86/kernel/ftrace.c:ftrace_enable_ftrace_graph_caller
  - arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline
  - arch/x86/kernel/ftrace.c:ftrace_update_ftrace_func
  - arch/x86/kernel/ftrace.c:ftrace_update_ftrace_func
```
**Symbols:**

```
ffffffff8105d240-ffffffff8105d30d: update_ftrace_func (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int update_ftrace_func(long unsigned int ip, void *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ftrace.c (ffffffff81060ee0)
Location: arch/x86/kernel/ftrace.c:232
Inline: False
Direct callers:
  - arch/x86/kernel/ftrace.c:ftrace_disable_ftrace_graph_caller
  - arch/x86/kernel/ftrace.c:ftrace_enable_ftrace_graph_caller
  - arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline
  - arch/x86/kernel/ftrace.c:ftrace_update_ftrace_func
  - arch/x86/kernel/ftrace.c:ftrace_update_ftrace_func
```
**Symbols:**

```
ffffffff81060ee0-ffffffff81060fad: update_ftrace_func (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int update_ftrace_func(long unsigned int ip, void *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ftrace.c (ffffffff81064000)
Location: arch/x86/kernel/ftrace.c:232
Inline: False
Direct callers:
  - arch/x86/kernel/ftrace.c:ftrace_disable_ftrace_graph_caller
  - arch/x86/kernel/ftrace.c:ftrace_enable_ftrace_graph_caller
  - arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline
  - arch/x86/kernel/ftrace.c:ftrace_update_ftrace_func
  - arch/x86/kernel/ftrace.c:ftrace_update_ftrace_func
```
**Symbols:**

```
ffffffff81064000-ffffffff810640cd: update_ftrace_func (STB_LOCAL)
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
In arch/x86/kernel/ftrace.c (ffffffff81069cb0)
Location: arch/x86/kernel/ftrace.c:235
Inline: True
Direct callers:
  - arch/x86/kernel/ftrace.c:ftrace_disable_ftrace_graph_caller
  - arch/x86/kernel/ftrace.c:ftrace_enable_ftrace_graph_caller
  - arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline
  - arch/x86/kernel/ftrace.c:ftrace_update_ftrace_func
  - arch/x86/kernel/ftrace.c:ftrace_update_ftrace_func
```
**Symbols:**

```
ffffffff81069cb0-ffffffff81069d7d: update_ftrace_func.constprop.10 (STB_LOCAL)
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
In arch/x86/kernel/ftrace.c (ffffffff8106d560)
Location: arch/x86/kernel/ftrace.c:247
Inline: True
Direct callers:
  - arch/x86/kernel/ftrace.c:ftrace_disable_ftrace_graph_caller
  - arch/x86/kernel/ftrace.c:ftrace_enable_ftrace_graph_caller
  - arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline
  - arch/x86/kernel/ftrace.c:ftrace_update_ftrace_func
  - arch/x86/kernel/ftrace.c:ftrace_update_ftrace_func
```
**Symbols:**

```
ffffffff8106d560-ffffffff8106d62f: update_ftrace_func.constprop.0 (STB_LOCAL)
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
In arch/x86/kernel/ftrace.c (ffffffff8106eb60)
Location: arch/x86/kernel/ftrace.c:247
Inline: True
Direct callers:
  - arch/x86/kernel/ftrace.c:ftrace_disable_ftrace_graph_caller
  - arch/x86/kernel/ftrace.c:ftrace_enable_ftrace_graph_caller
  - arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline
  - arch/x86/kernel/ftrace.c:ftrace_update_ftrace_func
  - arch/x86/kernel/ftrace.c:ftrace_update_ftrace_func
```
**Symbols:**

```
ffffffff8106eb60-ffffffff8106ec2f: update_ftrace_func.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
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
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8125663b)
Location: kernel/trace/ftrace.c:2770
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_modify_all_code
  - kernel/trace/ftrace.c:ftrace_modify_all_code
  - kernel/trace/ftrace.c:ftrace_modify_all_code
  - kernel/trace/ftrace.c:ftrace_modify_all_code
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
In kernel/trace/ftrace.c (ffffffff8126db3b)
Location: kernel/trace/ftrace.c:2853
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_modify_all_code
  - kernel/trace/ftrace.c:ftrace_modify_all_code
  - kernel/trace/ftrace.c:ftrace_modify_all_code
  - kernel/trace/ftrace.c:ftrace_modify_all_code
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
In kernel/trace/ftrace.c (ffffffff8128802b)
Location: kernel/trace/ftrace.c:2819
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_modify_all_code
  - kernel/trace/ftrace.c:ftrace_modify_all_code
  - kernel/trace/ftrace.c:ftrace_modify_all_code
  - kernel/trace/ftrace.c:ftrace_modify_all_code
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

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/ftrace.c (ffffffff8106db00)
Location: arch/x86/kernel/ftrace.c:247
Inline: True
Direct callers:
  - arch/x86/kernel/ftrace.c:ftrace_disable_ftrace_graph_caller
  - arch/x86/kernel/ftrace.c:ftrace_enable_ftrace_graph_caller
  - arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline
  - arch/x86/kernel/ftrace.c:ftrace_update_ftrace_func
  - arch/x86/kernel/ftrace.c:ftrace_update_ftrace_func
```
**Symbols:**

```
ffffffff8106db00-ffffffff8106dbcf: update_ftrace_func.constprop.0 (STB_LOCAL)
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
In arch/x86/kernel/ftrace.c (ffffffff8105df20)
Location: arch/x86/kernel/ftrace.c:247
Inline: True
Direct callers:
  - arch/x86/kernel/ftrace.c:ftrace_disable_ftrace_graph_caller
  - arch/x86/kernel/ftrace.c:ftrace_enable_ftrace_graph_caller
  - arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline
  - arch/x86/kernel/ftrace.c:ftrace_update_ftrace_func
  - arch/x86/kernel/ftrace.c:ftrace_update_ftrace_func
```
**Symbols:**

```
ffffffff8105df20-ffffffff8105dfef: update_ftrace_func.constprop.0 (STB_LOCAL)
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
In arch/x86/kernel/ftrace.c (ffffffff8106dfb0)
Location: arch/x86/kernel/ftrace.c:247
Inline: True
Direct callers:
  - arch/x86/kernel/ftrace.c:ftrace_disable_ftrace_graph_caller
  - arch/x86/kernel/ftrace.c:ftrace_enable_ftrace_graph_caller
  - arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline
  - arch/x86/kernel/ftrace.c:ftrace_update_ftrace_func
  - arch/x86/kernel/ftrace.c:ftrace_update_ftrace_func
```
**Symbols:**

```
ffffffff8106dfb0-ffffffff8106e07f: update_ftrace_func.constprop.0 (STB_LOCAL)
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
In arch/x86/kernel/ftrace.c (ffffffff81070230)
Location: arch/x86/kernel/ftrace.c:247
Inline: True
Direct callers:
  - arch/x86/kernel/ftrace.c:ftrace_disable_ftrace_graph_caller
  - arch/x86/kernel/ftrace.c:ftrace_enable_ftrace_graph_caller
  - arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline
  - arch/x86/kernel/ftrace.c:ftrace_update_ftrace_func
  - arch/x86/kernel/ftrace.c:ftrace_update_ftrace_func
```
**Symbols:**

```
ffffffff81070230-ffffffff810702ff: update_ftrace_func.constprop.0 (STB_LOCAL)
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
</ul>
