# Function: <code>cpu_idle_poll</code>

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
In kernel/sched/idle.c (ffffffff810c3e19)
Location: kernel/sched/idle.c:55
Inline: True
Inline callers:
  - kernel/sched/idle.c:cpu_startup_entry
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
In kernel/sched/idle.c (ffffffff810c7b18)
Location: kernel/sched/idle.c:56
Inline: True
Inline callers:
  - kernel/sched/idle.c:cpu_startup_entry
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int cpu_idle_poll();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/idle.c (ffffffff818d3d80)
Location: kernel/sched/idle.c:59
Inline: False
Direct callers:
  - kernel/sched/idle.c:do_idle
```
**Symbols:**

```
ffffffff818d3d80-ffffffff818d3e8a: cpu_idle_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int cpu_idle_poll();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/idle.c (ffffffff8190aee0)
Location: kernel/sched/idle.c:61
Inline: False
Direct callers:
  - kernel/sched/idle.c:do_idle
```
**Symbols:**

```
ffffffff8190aee0-ffffffff8190b00f: cpu_idle_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int cpu_idle_poll();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/idle.c (ffffffff81995250)
Location: kernel/sched/idle.c:61
Inline: False
Direct callers:
  - kernel/sched/idle.c:do_idle
```
**Symbols:**

```
ffffffff81995250-ffffffff8199538e: cpu_idle_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int cpu_idle_poll();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/idle.c (ffffffff819f17b0)
Location: kernel/sched/idle.c:54
Inline: False
Direct callers:
  - kernel/sched/idle.c:do_idle
```
**Symbols:**

```
ffffffff819f17b0-ffffffff819f18c9: cpu_idle_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int cpu_idle_poll();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/idle.c (ffffffff81a2cc50)
Location: kernel/sched/idle.c:54
Inline: False
Direct callers:
  - kernel/sched/idle.c:do_idle
```
**Symbols:**

```
ffffffff81a2cc50-ffffffff81a2cdd8: cpu_idle_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int cpu_idle_poll();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/idle.c (ffffffff81a9cdc0)
Location: kernel/sched/idle.c:55
Inline: False
Direct callers:
  - kernel/sched/idle.c:do_idle
```
**Symbols:**

```
ffffffff81a9cdc0-ffffffff81a9cf37: cpu_idle_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int cpu_idle_poll();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/idle.c (ffffffff81ad4610)
Location: kernel/sched/idle.c:55
Inline: False
Direct callers:
  - kernel/sched/idle.c:do_idle
```
**Symbols:**

```
ffffffff81ad4610-ffffffff81ad4787: cpu_idle_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/idle.c (ffffffff81bcc680)
Location: kernel/sched/idle.c:55
Inline: True
Direct callers:
  - kernel/sched/idle.c:do_idle
```
**Symbols:**

```
ffffffff81bcc680-ffffffff81bcc7f9: cpu_idle_poll.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/idle.c (ffffffff81c45230)
Location: kernel/sched/idle.c:55
Inline: True
Direct callers:
  - kernel/sched/idle.c:do_idle
```
**Symbols:**

```
ffffffff81c45230-ffffffff81c452f6: cpu_idle_poll.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/idle.c (ffffffff81c384b0)
Location: kernel/sched/idle.c:55
Inline: True
Direct callers:
  - kernel/sched/idle.c:do_idle
```
**Symbols:**

```
ffffffff81c384b0-ffffffff81c38576: cpu_idle_poll.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/idle.c (ffffffff81d56d60)
Location: kernel/sched/idle.c:55
Inline: True
Direct callers:
  - kernel/sched/idle.c:do_idle
```
**Symbols:**

```
ffffffff81d56d60-ffffffff81d56e20: cpu_idle_poll.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff81f29020)
Location: kernel/sched/idle.c:52
Inline: True
Direct callers:
  - kernel/sched/build_policy.c:do_idle
```
**Symbols:**

```
ffffffff81f29020-ffffffff81f2911f: cpu_idle_poll.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff820d4d20)
Location: kernel/sched/idle.c:52
Inline: True
Direct callers:
  - kernel/sched/build_policy.c:do_idle
```
**Symbols:**

```
ffffffff820d4d20-ffffffff820d4e21: cpu_idle_poll.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff821431b0)
Location: kernel/sched/idle.c:52
Inline: True
Direct callers:
  - kernel/sched/build_policy.c:do_idle
```
**Symbols:**

```
ffffffff821431b0-ffffffff821432b8: cpu_idle_poll.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff822258c0)
Location: kernel/sched/idle.c:52
Inline: True
Direct callers:
  - kernel/sched/build_policy.c:do_idle
```
**Symbols:**

```
ffffffff822258c0-ffffffff822259c8: cpu_idle_poll.isra.0 (STB_LOCAL)
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
int cpu_idle_poll();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/idle.c (ffff800010da7160)
Location: kernel/sched/idle.c:55
Inline: False
Direct callers:
  - kernel/sched/idle.c:do_idle
```
**Symbols:**

```
ffff800010da7160-ffff800010da7368: cpu_idle_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int cpu_idle_poll();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/idle.c (c0e9ed78)
Location: kernel/sched/idle.c:55
Inline: False
Direct callers:
  - kernel/sched/idle.c:do_idle
```
**Symbols:**

```
c0e9ed78-c0e9efe8: cpu_idle_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int cpu_idle_poll();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/idle.c (c000000000ee9a10)
Location: kernel/sched/idle.c:55
Inline: False
Direct callers:
  - kernel/sched/idle.c:do_idle
```
**Symbols:**

```
c000000000ee9a10-c000000000ee9cb0: cpu_idle_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int cpu_idle_poll();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/idle.c (ffffffe0008c91e8)
Location: kernel/sched/idle.c:55
Inline: False
Direct callers:
  - kernel/sched/idle.c:do_idle
```
**Symbols:**

```
ffffffe0008c91e8-ffffffe0008c9386: cpu_idle_poll (STB_LOCAL)
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
int cpu_idle_poll();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/idle.c (ffffffff81a73480)
Location: kernel/sched/idle.c:55
Inline: False
Direct callers:
  - kernel/sched/idle.c:do_idle
```
**Symbols:**

```
ffffffff81a73480-ffffffff81a735f7: cpu_idle_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int cpu_idle_poll();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/idle.c (ffffffff81a2f810)
Location: kernel/sched/idle.c:55
Inline: False
Direct callers:
  - kernel/sched/idle.c:do_idle
```
**Symbols:**

```
ffffffff81a2f810-ffffffff81a2f981: cpu_idle_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int cpu_idle_poll();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/idle.c (ffffffff81adf890)
Location: kernel/sched/idle.c:55
Inline: False
Direct callers:
  - kernel/sched/idle.c:do_idle
```
**Symbols:**

```
ffffffff81adf890-ffffffff81adfa07: cpu_idle_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int cpu_idle_poll();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/idle.c (ffffffff81aec060)
Location: kernel/sched/idle.c:55
Inline: False
Direct callers:
  - kernel/sched/idle.c:do_idle
```
**Symbols:**

```
ffffffff81aec060-ffffffff81aec209: cpu_idle_poll (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
