# Function: <code>cgroup_enter_frozen</code>

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
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void cgroup_enter_frozen();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/freezer.c (ffffffff8115e280)
Location: kernel/cgroup/freezer.c:107
Inline: False
Direct callers:
  - kernel/fork.c:_do_fork
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
```
**Symbols:**

```
ffffffff8115e280-ffffffff8115e2de: cgroup_enter_frozen (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void cgroup_enter_frozen();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/freezer.c (ffffffff81169e70)
Location: kernel/cgroup/freezer.c:107
Inline: False
Direct callers:
  - kernel/fork.c:_do_fork
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
```
**Symbols:**

```
ffffffff81169e70-ffffffff81169ece: cgroup_enter_frozen (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void cgroup_enter_frozen();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/freezer.c (ffffffff8117b9e0)
Location: kernel/cgroup/freezer.c:107
Inline: False
Direct callers:
  - kernel/fork.c:wait_for_vfork_done
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
```
**Symbols:**

```
ffffffff8117b9e0-ffffffff8117ba41: cgroup_enter_frozen (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void cgroup_enter_frozen();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/freezer.c (ffffffff81178830)
Location: kernel/cgroup/freezer.c:107
Inline: False
Direct callers:
  - kernel/fork.c:wait_for_vfork_done
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
```
**Symbols:**

```
ffffffff81178830-ffffffff81178891: cgroup_enter_frozen (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void cgroup_enter_frozen();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/freezer.c (ffffffff811793a0)
Location: kernel/cgroup/freezer.c:107
Inline: False
Direct callers:
  - kernel/fork.c:kernel_clone
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
```
**Symbols:**

```
ffffffff811793a0-ffffffff81179404: cgroup_enter_frozen (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void cgroup_enter_frozen();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/freezer.c (ffffffff811a0cb0)
Location: kernel/cgroup/freezer.c:107
Inline: False
Direct callers:
  - kernel/fork.c:kernel_clone
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
```
**Symbols:**

```
ffffffff811a0cb0-ffffffff811a0d14: cgroup_enter_frozen (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void cgroup_enter_frozen();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/freezer.c (ffffffff811d14b0)
Location: kernel/cgroup/freezer.c:107
Inline: False
Direct callers:
  - kernel/fork.c:kernel_clone
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
```
**Symbols:**

```
ffffffff811d14b0-ffffffff811d1513: cgroup_enter_frozen (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void cgroup_enter_frozen();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/freezer.c (ffffffff81215060)
Location: kernel/cgroup/freezer.c:107
Inline: False
Direct callers:
  - kernel/fork.c:kernel_clone
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
```
**Symbols:**

```
ffffffff81215060-ffffffff812150c3: cgroup_enter_frozen (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void cgroup_enter_frozen();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/freezer.c (ffffffff8122a990)
Location: kernel/cgroup/freezer.c:107
Inline: False
Direct callers:
  - kernel/fork.c:kernel_clone
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
```
**Symbols:**

```
ffffffff8122a990-ffffffff8122a9f3: cgroup_enter_frozen (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void cgroup_enter_frozen();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/freezer.c (ffffffff81242950)
Location: kernel/cgroup/freezer.c:107
Inline: False
Direct callers:
  - kernel/fork.c:kernel_clone
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
```
**Symbols:**

```
ffffffff81242950-ffffffff812429b3: cgroup_enter_frozen (STB_GLOBAL)
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
void cgroup_enter_frozen();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/freezer.c (ffff8000101dd718)
Location: kernel/cgroup/freezer.c:107
Inline: False
Direct callers:
  - kernel/fork.c:_do_fork
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
```
**Symbols:**

```
ffff8000101dd718-ffff8000101dd7e4: cgroup_enter_frozen (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void cgroup_enter_frozen();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/freezer.c (c041f300)
Location: kernel/cgroup/freezer.c:107
Inline: False
Direct callers:
  - kernel/fork.c:_do_fork
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
```
**Symbols:**

```
c041f300-c041f398: cgroup_enter_frozen (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void cgroup_enter_frozen();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/freezer.c (c00000000024b420)
Location: kernel/cgroup/freezer.c:107
Inline: False
Direct callers:
  - kernel/fork.c:_do_fork
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
```
**Symbols:**

```
c00000000024b420-c00000000024b50c: cgroup_enter_frozen (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void cgroup_enter_frozen();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/freezer.c (ffffffe000155074)
Location: kernel/cgroup/freezer.c:107
Inline: False
Direct callers:
  - kernel/fork.c:_do_fork
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
```
**Symbols:**

```
ffffffe000155074-ffffffe000155122: cgroup_enter_frozen (STB_GLOBAL)
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
void cgroup_enter_frozen();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/freezer.c (ffffffff81162490)
Location: kernel/cgroup/freezer.c:107
Inline: False
Direct callers:
  - kernel/fork.c:_do_fork
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
```
**Symbols:**

```
ffffffff81162490-ffffffff811624ee: cgroup_enter_frozen (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void cgroup_enter_frozen();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/freezer.c (ffffffff811556f0)
Location: kernel/cgroup/freezer.c:107
Inline: False
Direct callers:
  - kernel/fork.c:_do_fork
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
```
**Symbols:**

```
ffffffff811556f0-ffffffff81155748: cgroup_enter_frozen (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void cgroup_enter_frozen();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/freezer.c (ffffffff81160260)
Location: kernel/cgroup/freezer.c:107
Inline: False
Direct callers:
  - kernel/fork.c:_do_fork
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
```
**Symbols:**

```
ffffffff81160260-ffffffff811602be: cgroup_enter_frozen (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void cgroup_enter_frozen();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/freezer.c (ffffffff8116d5d0)
Location: kernel/cgroup/freezer.c:107
Inline: False
Direct callers:
  - kernel/fork.c:_do_fork
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
```
**Symbols:**

```
ffffffff8116d5d0-ffffffff8116d625: cgroup_enter_frozen (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
