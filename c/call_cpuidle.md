# Function: <code>call_cpuidle</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int call_cpuidle(struct cpuidle_driver *drv, struct cpuidle_device *dev, int next_state);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/idle.c (ffffffff810c3d20)
Location: kernel/sched/idle.c:97
Inline: True
Direct callers:
  - kernel/sched/idle.c:cpu_startup_entry
  - kernel/sched/idle.c:cpu_startup_entry
```
**Symbols:**

```
ffffffff810c3d20-ffffffff810c3d78: call_cpuidle (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int call_cpuidle(struct cpuidle_driver *drv, struct cpuidle_device *dev, int next_state);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/idle.c (ffffffff810c78f0)
Location: kernel/sched/idle.c:98
Inline: True
Direct callers:
  - kernel/sched/idle.c:cpu_startup_entry
  - kernel/sched/idle.c:cpu_startup_entry
```
**Symbols:**

```
ffffffff810c78f0-ffffffff810c7931: call_cpuidle (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int call_cpuidle(struct cpuidle_driver *drv, struct cpuidle_device *dev, int next_state);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/idle.c (ffffffff810cd7b0)
Location: kernel/sched/idle.c:101
Inline: True
Direct callers:
  - kernel/sched/idle.c:do_idle
  - kernel/sched/idle.c:do_idle
```
**Symbols:**

```
ffffffff810cd7b0-ffffffff810cd7ea: call_cpuidle (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int call_cpuidle(struct cpuidle_driver *drv, struct cpuidle_device *dev, int next_state);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/idle.c (ffffffff810ca1d0)
Location: kernel/sched/idle.c:103
Inline: True
Direct callers:
  - kernel/sched/idle.c:do_idle
  - kernel/sched/idle.c:do_idle
```
**Symbols:**

```
ffffffff810ca1d0-ffffffff810ca20a: call_cpuidle (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int call_cpuidle(struct cpuidle_driver *drv, struct cpuidle_device *dev, int next_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/idle.c (ffffffff810d1a20)
Location: kernel/sched/idle.c:103
Inline: False
Direct callers:
  - kernel/sched/idle.c:do_idle
  - kernel/sched/idle.c:do_idle
```
**Symbols:**

```
ffffffff810d1a20-ffffffff810d1a5a: call_cpuidle (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int call_cpuidle(struct cpuidle_driver *drv, struct cpuidle_device *dev, int next_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/idle.c (ffffffff810c4130)
Location: kernel/sched/idle.c:98
Inline: False
Direct callers:
  - kernel/sched/idle.c:do_idle
  - kernel/sched/idle.c:do_idle
```
**Symbols:**

```
ffffffff810c4130-ffffffff810c416a: call_cpuidle (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int call_cpuidle(struct cpuidle_driver *drv, struct cpuidle_device *dev, int next_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/idle.c (ffffffff810cd2f0)
Location: kernel/sched/idle.c:98
Inline: False
Direct callers:
  - kernel/sched/idle.c:do_idle
  - kernel/sched/idle.c:do_idle
```
**Symbols:**

```
ffffffff810cd2f0-ffffffff810cd32a: call_cpuidle (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int call_cpuidle(struct cpuidle_driver *drv, struct cpuidle_device *dev, int next_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/idle.c (ffffffff810d57e0)
Location: kernel/sched/idle.c:99
Inline: False
Direct callers:
  - kernel/sched/idle.c:do_idle
  - kernel/sched/idle.c:do_idle
```
**Symbols:**

```
ffffffff810d57e0-ffffffff810d581a: call_cpuidle (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int call_cpuidle(struct cpuidle_driver *drv, struct cpuidle_device *dev, int next_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/idle.c (ffffffff810dfdf0)
Location: kernel/sched/idle.c:99
Inline: False
Direct callers:
  - kernel/sched/idle.c:do_idle
  - kernel/sched/idle.c:do_idle
```
**Symbols:**

```
ffffffff810dfdf0-ffffffff810dfe2a: call_cpuidle (STB_LOCAL)
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
In kernel/sched/idle.c (ffffffff810e8281)
Location: kernel/sched/idle.c:108
Inline: True
Inline callers:
  - kernel/sched/idle.c:cpuidle_idle_call
  - kernel/sched/idle.c:cpuidle_idle_call
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/idle.c (ffffffff810e5e98)
Location: kernel/sched/idle.c:140
Inline: True
Inline callers:
  - kernel/sched/idle.c:cpuidle_idle_call
  - kernel/sched/idle.c:cpuidle_idle_call
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/idle.c (ffffffff810e7e58)
Location: kernel/sched/idle.c:140
Inline: True
Inline callers:
  - kernel/sched/idle.c:cpuidle_idle_call
  - kernel/sched/idle.c:cpuidle_idle_call
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/idle.c (ffffffff810ff508)
Location: kernel/sched/idle.c:140
Inline: True
Inline callers:
  - kernel/sched/idle.c:cpuidle_idle_call
  - kernel/sched/idle.c:cpuidle_idle_call
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int call_cpuidle(struct cpuidle_driver *drv, struct cpuidle_device *dev, int next_state);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff8112f220)
Location: kernel/sched/idle.c:137
Inline: True
Direct callers:
  - kernel/sched/build_policy.c:cpuidle_idle_call
  - kernel/sched/build_policy.c:cpuidle_idle_call
```
**Symbols:**

```
ffffffff8112f220-ffffffff8112f26e: call_cpuidle (STB_LOCAL)
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
In kernel/sched/build_policy.c (ffffffff8115d92d)
Location: kernel/sched/idle.c:137
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:cpuidle_idle_call
  - kernel/sched/build_policy.c:cpuidle_idle_call
Direct callers:
  - kernel/sched/build_policy.c:cpuidle_idle_call
  - kernel/sched/build_policy.c:cpuidle_idle_call
```
**Symbols:**

```
ffffffff811586c0-ffffffff811586ea: call_cpuidle.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int call_cpuidle(struct cpuidle_driver *drv, struct cpuidle_device *dev, int next_state);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff81168820)
Location: kernel/sched/idle.c:116
Inline: True
Direct callers:
  - kernel/sched/build_policy.c:cpuidle_idle_call
  - kernel/sched/build_policy.c:cpuidle_idle_call
```
**Symbols:**

```
ffffffff81168820-ffffffff81168872: call_cpuidle (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int call_cpuidle(struct cpuidle_driver *drv, struct cpuidle_device *dev, int next_state);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff811758b0)
Location: kernel/sched/idle.c:116
Inline: True
Direct callers:
  - kernel/sched/build_policy.c:cpuidle_idle_call
  - kernel/sched/build_policy.c:cpuidle_idle_call
```
**Symbols:**

```
ffffffff811758b0-ffffffff81175902: call_cpuidle (STB_LOCAL)
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
int call_cpuidle(struct cpuidle_driver *drv, struct cpuidle_device *dev, int next_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/idle.c (ffff80001013fa68)
Location: kernel/sched/idle.c:99
Inline: False
Direct callers:
  - kernel/sched/idle.c:do_idle
  - kernel/sched/idle.c:do_idle
```
**Symbols:**

```
ffff80001013fa68-ffff80001013fadc: call_cpuidle (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int call_cpuidle(struct cpuidle_driver *drv, struct cpuidle_device *dev, int next_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/idle.c (c038f8bc)
Location: kernel/sched/idle.c:99
Inline: False
Direct callers:
  - kernel/sched/idle.c:do_idle
  - kernel/sched/idle.c:do_idle
```
**Symbols:**

```
c038f8bc-c038f904: call_cpuidle (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int call_cpuidle(struct cpuidle_driver *drv, struct cpuidle_device *dev, int next_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/idle.c (c00000000018e8b0)
Location: kernel/sched/idle.c:99
Inline: False
Direct callers:
  - kernel/sched/idle.c:do_idle
  - kernel/sched/idle.c:do_idle
```
**Symbols:**

```
c00000000018e8b0-c00000000018e938: call_cpuidle (STB_LOCAL)
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
In kernel/sched/idle.c (0)
Location: kernel/sched/idle.c:99
Inline: True
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
int call_cpuidle(struct cpuidle_driver *drv, struct cpuidle_device *dev, int next_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/idle.c (ffffffff810d9fe0)
Location: kernel/sched/idle.c:99
Inline: False
Direct callers:
  - kernel/sched/idle.c:do_idle
  - kernel/sched/idle.c:do_idle
```
**Symbols:**

```
ffffffff810d9fe0-ffffffff810da01a: call_cpuidle (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int call_cpuidle(struct cpuidle_driver *drv, struct cpuidle_device *dev, int next_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/idle.c (ffffffff810c8fd0)
Location: kernel/sched/idle.c:99
Inline: False
Direct callers:
  - kernel/sched/idle.c:do_idle
  - kernel/sched/idle.c:do_idle
```
**Symbols:**

```
ffffffff810c8fd0-ffffffff810c9003: call_cpuidle (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int call_cpuidle(struct cpuidle_driver *drv, struct cpuidle_device *dev, int next_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/idle.c (ffffffff810d6320)
Location: kernel/sched/idle.c:99
Inline: False
Direct callers:
  - kernel/sched/idle.c:do_idle
  - kernel/sched/idle.c:do_idle
```
**Symbols:**

```
ffffffff810d6320-ffffffff810d635a: call_cpuidle (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int call_cpuidle(struct cpuidle_driver *drv, struct cpuidle_device *dev, int next_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/idle.c (ffffffff810e1c20)
Location: kernel/sched/idle.c:99
Inline: False
Direct callers:
  - kernel/sched/idle.c:do_idle
  - kernel/sched/idle.c:do_idle
```
**Symbols:**

```
ffffffff810e1c20-ffffffff810e1c5a: call_cpuidle (STB_LOCAL)
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
