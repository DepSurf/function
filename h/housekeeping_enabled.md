# Function: <code>housekeeping_enabled</code>

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
bool housekeeping_enabled(enum hk_flags flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/isolation.c (ffffffff810f5b80)
Location: kernel/sched/isolation.c:17
Inline: False
```
**Symbols:**

```
ffffffff810f5b80-ffffffff810f5b94: housekeeping_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool housekeeping_enabled(enum hk_flags flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/isolation.c (ffffffff811018f0)
Location: kernel/sched/isolation.c:17
Inline: False
```
**Symbols:**

```
ffffffff811018f0-ffffffff81101904: housekeeping_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool housekeeping_enabled(enum hk_flags flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/isolation.c (ffffffff8110c180)
Location: kernel/sched/isolation.c:17
Inline: False
Direct callers:
  - kernel/irq/manage.c:irq_do_set_affinity
  - kernel/irq/cpuhotplug.c:hk_should_isolate
```
**Symbols:**

```
ffffffff8110c180-ffffffff8110c194: housekeeping_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool housekeeping_enabled(enum hk_flags flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/isolation.c (ffffffff811093a0)
Location: kernel/sched/isolation.c:17
Inline: False
Direct callers:
  - kernel/irq/manage.c:irq_do_set_affinity
  - kernel/irq/cpuhotplug.c:hk_should_isolate
```
**Symbols:**

```
ffffffff811093a0-ffffffff811093b4: housekeeping_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool housekeeping_enabled(enum hk_flags flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/isolation.c (ffffffff8110b240)
Location: kernel/sched/isolation.c:17
Inline: False
Direct callers:
  - kernel/irq/manage.c:irq_do_set_affinity
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
```
**Symbols:**

```
ffffffff8110b240-ffffffff8110b254: housekeeping_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool housekeeping_enabled(enum hk_flags flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/isolation.c (ffffffff81129aa0)
Location: kernel/sched/isolation.c:17
Inline: False
Direct callers:
  - kernel/irq/manage.c:irq_do_set_affinity
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
```
**Symbols:**

```
ffffffff81129aa0-ffffffff81129ab4: housekeeping_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool housekeeping_enabled(enum hk_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/build_utility.c (0)
Location: kernel/sched/isolation.c:33
Inline: False
Direct callers:
  - kernel/irq/manage.c:irq_do_set_affinity
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
```
**Symbols:**

```
ffffffff81e56910-ffffffff81e56928: housekeeping_enabled.cold (STB_LOCAL)
ffffffff8113c430-ffffffff8113c463: housekeeping_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
bool housekeeping_enabled(enum hk_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/build_utility.c (0)
Location: kernel/sched/isolation.c:33
Inline: False
Direct callers:
  - kernel/irq/manage.c:irq_do_set_affinity
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
```
**Symbols:**

```
ffffffff82057b30-ffffffff82057b48: housekeeping_enabled.cold (STB_LOCAL)
ffffffff81167030-ffffffff81167063: housekeeping_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool housekeeping_enabled(enum hk_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/build_utility.c (0)
Location: kernel/sched/isolation.c:33
Inline: False
Direct callers:
  - kernel/irq/manage.c:irq_do_set_affinity
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
```
**Symbols:**

```
ffffffff820d6356-ffffffff820d636e: housekeeping_enabled.cold (STB_LOCAL)
ffffffff81177500-ffffffff81177533: housekeeping_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool housekeeping_enabled(enum hk_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/build_utility.c (0)
Location: kernel/sched/isolation.c:33
Inline: False
Direct callers:
  - kernel/irq/manage.c:irq_do_set_affinity
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
```
**Symbols:**

```
ffffffff821b151e-ffffffff821b1536: housekeeping_enabled.cold (STB_LOCAL)
ffffffff811852a0-ffffffff811852d3: housekeeping_enabled (STB_GLOBAL)
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
bool housekeeping_enabled(enum hk_flags flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/isolation.c (ffff800010166490)
Location: kernel/sched/isolation.c:17
Inline: False
```
**Symbols:**

```
ffff800010166490-ffff8000101664c4: housekeeping_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool housekeeping_enabled(enum hk_flags flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/isolation.c (c03b28f4)
Location: kernel/sched/isolation.c:17
Inline: False
```
**Symbols:**

```
c03b28f4-c03b2924: housekeeping_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool housekeeping_enabled(enum hk_flags flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/isolation.c (c0000000001bdbc0)
Location: kernel/sched/isolation.c:17
Inline: False
```
**Symbols:**

```
c0000000001bdbc0-c0000000001bdbec: housekeeping_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool housekeeping_enabled(enum hk_flags flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/isolation.c (ffffffe00010877c)
Location: kernel/sched/isolation.c:17
Inline: False
```
**Symbols:**

```
ffffffe00010877c-ffffffe0001087aa: housekeeping_enabled (STB_GLOBAL)
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
bool housekeeping_enabled(enum hk_flags flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/isolation.c (ffffffff810fac00)
Location: kernel/sched/isolation.c:17
Inline: False
```
**Symbols:**

```
ffffffff810fac00-ffffffff810fac14: housekeeping_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool housekeeping_enabled(enum hk_flags flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/isolation.c (ffffffff810eae20)
Location: kernel/sched/isolation.c:17
Inline: False
```
**Symbols:**

```
ffffffff810eae20-ffffffff810eae34: housekeeping_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool housekeeping_enabled(enum hk_flags flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/isolation.c (ffffffff810f7dc0)
Location: kernel/sched/isolation.c:17
Inline: False
```
**Symbols:**

```
ffffffff810f7dc0-ffffffff810f7dd4: housekeeping_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool housekeeping_enabled(enum hk_flags flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/isolation.c (ffffffff81102f00)
Location: kernel/sched/isolation.c:17
Inline: False
```
**Symbols:**

```
ffffffff81102f00-ffffffff81102f14: housekeeping_enabled (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>enum hk_type type</code>
</li>
<li>
<b>Param removed. </b>
<code>enum hk_flags flags</code>
</li>
</ul>
</details>
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
