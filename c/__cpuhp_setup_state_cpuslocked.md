# Function: <code>__cpuhp_setup_state_cpuslocked</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __cpuhp_setup_state_cpuslocked(enum cpuhp_state state, const char *name, bool invoke, int (*startup)(unsigned int), int (*teardown)(unsigned int), bool multi_instance);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff81086200)
Location: kernel/cpu.c:1415
Inline: False
Direct callers:
  - kernel/cpu.c:__cpuhp_setup_state
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
```
**Symbols:**

```
ffffffff81086200-ffffffff810864b3: __cpuhp_setup_state_cpuslocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __cpuhp_setup_state_cpuslocked(enum cpuhp_state state, const char *name, bool invoke, int (*startup)(unsigned int), int (*teardown)(unsigned int), bool multi_instance);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff8108ce70)
Location: kernel/cpu.c:1603
Inline: False
Direct callers:
  - kernel/cpu.c:__cpuhp_setup_state
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
```
**Symbols:**

```
ffffffff8108ce70-ffffffff8108d12b: __cpuhp_setup_state_cpuslocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __cpuhp_setup_state_cpuslocked(enum cpuhp_state state, const char *name, bool invoke, int (*startup)(unsigned int), int (*teardown)(unsigned int), bool multi_instance);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810907e0)
Location: kernel/cpu.c:1685
Inline: False
Direct callers:
  - kernel/cpu.c:__cpuhp_setup_state
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
```
**Symbols:**

```
ffffffff810907e0-ffffffff81090ad2: __cpuhp_setup_state_cpuslocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __cpuhp_setup_state_cpuslocked(enum cpuhp_state state, const char *name, bool invoke, int (*startup)(unsigned int), int (*teardown)(unsigned int), bool multi_instance);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810988a0)
Location: kernel/cpu.c:1707
Inline: False
Direct callers:
  - kernel/cpu.c:__cpuhp_setup_state
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
```
**Symbols:**

```
ffffffff810988a0-ffffffff81098b92: __cpuhp_setup_state_cpuslocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __cpuhp_setup_state_cpuslocked(enum cpuhp_state state, const char *name, bool invoke, int (*startup)(unsigned int), int (*teardown)(unsigned int), bool multi_instance);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff8109ce50)
Location: kernel/cpu.c:1733
Inline: False
Direct callers:
  - kernel/cpu.c:__cpuhp_setup_state
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
```
**Symbols:**

```
ffffffff8109ce50-ffffffff8109d121: __cpuhp_setup_state_cpuslocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __cpuhp_setup_state_cpuslocked(enum cpuhp_state state, const char *name, bool invoke, int (*startup)(unsigned int), int (*teardown)(unsigned int), bool multi_instance);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810a33a0)
Location: kernel/cpu.c:1748
Inline: False
Direct callers:
  - kernel/cpu.c:__cpuhp_setup_state
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
```
**Symbols:**

```
ffffffff810a33a0-ffffffff810a3676: __cpuhp_setup_state_cpuslocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __cpuhp_setup_state_cpuslocked(enum cpuhp_state state, const char *name, bool invoke, int (*startup)(unsigned int), int (*teardown)(unsigned int), bool multi_instance);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810aa410)
Location: kernel/cpu.c:1879
Inline: False
Direct callers:
  - kernel/cpu.c:__cpuhp_setup_state
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
```
**Symbols:**

```
ffffffff810aa410-ffffffff810aa6e6: __cpuhp_setup_state_cpuslocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __cpuhp_setup_state_cpuslocked(enum cpuhp_state state, const char *name, bool invoke, int (*startup)(unsigned int), int (*teardown)(unsigned int), bool multi_instance);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810a5ca0)
Location: kernel/cpu.c:1890
Inline: False
Direct callers:
  - kernel/cpu.c:__cpuhp_setup_state
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
```
**Symbols:**

```
ffffffff810a5ca0-ffffffff810a5f76: __cpuhp_setup_state_cpuslocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __cpuhp_setup_state_cpuslocked(enum cpuhp_state state, const char *name, bool invoke, int (*startup)(unsigned int), int (*teardown)(unsigned int), bool multi_instance);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810a6ae0)
Location: kernel/cpu.c:1993
Inline: False
Direct callers:
  - kernel/cpu.c:__cpuhp_setup_state
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
```
**Symbols:**

```
ffffffff810a6ae0-ffffffff810a6dc3: __cpuhp_setup_state_cpuslocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __cpuhp_setup_state_cpuslocked(enum cpuhp_state state, const char *name, bool invoke, int (*startup)(unsigned int), int (*teardown)(unsigned int), bool multi_instance);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810b8420)
Location: kernel/cpu.c:2024
Inline: False
Direct callers:
  - kernel/cpu.c:__cpuhp_setup_state
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
```
**Symbols:**

```
ffffffff810b8420-ffffffff810b872f: __cpuhp_setup_state_cpuslocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __cpuhp_setup_state_cpuslocked(enum cpuhp_state state, const char *name, bool invoke, int (*startup)(unsigned int), int (*teardown)(unsigned int), bool multi_instance);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810cecb0)
Location: kernel/cpu.c:2046
Inline: False
Direct callers:
  - kernel/cpu.c:__cpuhp_setup_state
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
```
**Symbols:**

```
ffffffff810cecb0-ffffffff810cef9e: __cpuhp_setup_state_cpuslocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __cpuhp_setup_state_cpuslocked(enum cpuhp_state state, const char *name, bool invoke, int (*startup)(unsigned int), int (*teardown)(unsigned int), bool multi_instance);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810ed0d0)
Location: kernel/cpu.c:2070
Inline: False
Direct callers:
  - kernel/cpu.c:__cpuhp_setup_state
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
```
**Symbols:**

```
ffffffff810ed0d0-ffffffff810ed3bf: __cpuhp_setup_state_cpuslocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __cpuhp_setup_state_cpuslocked(enum cpuhp_state state, const char *name, bool invoke, int (*startup)(unsigned int), int (*teardown)(unsigned int), bool multi_instance);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810f8bf0)
Location: kernel/cpu.c:2455
Inline: False
Direct callers:
  - kernel/cpu.c:__cpuhp_setup_state
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
```
**Symbols:**

```
ffffffff810f8bf0-ffffffff810f8f46: __cpuhp_setup_state_cpuslocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __cpuhp_setup_state_cpuslocked(enum cpuhp_state state, const char *name, bool invoke, int (*startup)(unsigned int), int (*teardown)(unsigned int), bool multi_instance);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff81102000)
Location: kernel/cpu.c:2501
Inline: False
Direct callers:
  - kernel/cpu.c:__cpuhp_setup_state
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
```
**Symbols:**

```
ffffffff81102000-ffffffff81102356: __cpuhp_setup_state_cpuslocked (STB_GLOBAL)
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
int __cpuhp_setup_state_cpuslocked(enum cpuhp_state state, const char *name, bool invoke, int (*startup)(unsigned int), int (*teardown)(unsigned int), bool multi_instance);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffff8000100f8b10)
Location: kernel/cpu.c:1748
Inline: False
Direct callers:
  - kernel/cpu.c:__cpuhp_setup_state
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
```
**Symbols:**

```
ffff8000100f8b10-ffff8000100f8df0: __cpuhp_setup_state_cpuslocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __cpuhp_setup_state_cpuslocked(enum cpuhp_state state, const char *name, bool invoke, int (*startup)(unsigned int), int (*teardown)(unsigned int), bool multi_instance);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (c0356d68)
Location: kernel/cpu.c:1748
Inline: False
Direct callers:
  - arch/arm/kernel/hw_breakpoint.c:arch_hw_breakpoint_init
  - kernel/cpu.c:__cpuhp_setup_state
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
```
**Symbols:**

```
c0356d68-c0357054: __cpuhp_setup_state_cpuslocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __cpuhp_setup_state_cpuslocked(enum cpuhp_state state, const char *name, bool invoke, int (*startup)(unsigned int), int (*teardown)(unsigned int), bool multi_instance);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (c00000000013f630)
Location: kernel/cpu.c:1748
Inline: False
Direct callers:
  - kernel/cpu.c:__cpuhp_setup_state
  - kernel/cpu.c:__cpuhp_setup_state
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
```
**Symbols:**

```
c00000000013f630-c00000000013f954: __cpuhp_setup_state_cpuslocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __cpuhp_setup_state_cpuslocked(enum cpuhp_state state, const char *name, bool invoke, int (*startup)(unsigned int), int (*teardown)(unsigned int), bool multi_instance);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffe0000c389e)
Location: kernel/cpu.c:1748
Inline: False
Direct callers:
  - kernel/cpu.c:__cpuhp_setup_state
```
**Symbols:**

```
ffffffe0000c389e-ffffffe0000c3aa4: __cpuhp_setup_state_cpuslocked (STB_GLOBAL)
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
int __cpuhp_setup_state_cpuslocked(enum cpuhp_state state, const char *name, bool invoke, int (*startup)(unsigned int), int (*teardown)(unsigned int), bool multi_instance);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff8109ccc0)
Location: kernel/cpu.c:1748
Inline: False
Direct callers:
  - kernel/cpu.c:__cpuhp_setup_state
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
```
**Symbols:**

```
ffffffff8109ccc0-ffffffff8109cf96: __cpuhp_setup_state_cpuslocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __cpuhp_setup_state_cpuslocked(enum cpuhp_state state, const char *name, bool invoke, int (*startup)(unsigned int), int (*teardown)(unsigned int), bool multi_instance);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff8108b6f0)
Location: kernel/cpu.c:1748
Inline: False
Direct callers:
  - kernel/cpu.c:__cpuhp_setup_state
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
```
**Symbols:**

```
ffffffff8108b6f0-ffffffff8108b9c6: __cpuhp_setup_state_cpuslocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __cpuhp_setup_state_cpuslocked(enum cpuhp_state state, const char *name, bool invoke, int (*startup)(unsigned int), int (*teardown)(unsigned int), bool multi_instance);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff8109cc70)
Location: kernel/cpu.c:1748
Inline: False
Direct callers:
  - kernel/cpu.c:__cpuhp_setup_state
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
```
**Symbols:**

```
ffffffff8109cc70-ffffffff8109cf46: __cpuhp_setup_state_cpuslocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __cpuhp_setup_state_cpuslocked(enum cpuhp_state state, const char *name, bool invoke, int (*startup)(unsigned int), int (*teardown)(unsigned int), bool multi_instance);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810a4a50)
Location: kernel/cpu.c:1748
Inline: False
Direct callers:
  - kernel/cpu.c:__cpuhp_setup_state
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
```
**Symbols:**

```
ffffffff810a4a50-ffffffff810a4d26: __cpuhp_setup_state_cpuslocked (STB_GLOBAL)
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
