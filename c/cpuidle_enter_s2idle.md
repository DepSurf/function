# Function: <code>cpuidle_enter_s2idle</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int cpuidle_enter_s2idle(struct cpuidle_driver *drv, struct cpuidle_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/cpuidle.c (ffffffff817e4020)
Location: drivers/cpuidle/cpuidle.c:165
Inline: False
Direct callers:
  - kernel/sched/idle.c:do_idle
```
**Symbols:**

```
ffffffff817e4020-ffffffff817e40f7: cpuidle_enter_s2idle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int cpuidle_enter_s2idle(struct cpuidle_driver *drv, struct cpuidle_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/cpuidle.c (ffffffff8182d230)
Location: drivers/cpuidle/cpuidle.c:174
Inline: False
Direct callers:
  - kernel/sched/idle.c:do_idle
```
**Symbols:**

```
ffffffff8182d230-ffffffff8182d362: cpuidle_enter_s2idle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int cpuidle_enter_s2idle(struct cpuidle_driver *drv, struct cpuidle_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/cpuidle.c (ffffffff81859210)
Location: drivers/cpuidle/cpuidle.c:174
Inline: False
Direct callers:
  - kernel/sched/idle.c:do_idle
```
**Symbols:**

```
ffffffff81859210-ffffffff81859349: cpuidle_enter_s2idle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int cpuidle_enter_s2idle(struct cpuidle_driver *drv, struct cpuidle_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpuidle/cpuidle.c (0)
Location: drivers/cpuidle/cpuidle.c:174
Inline: False
Direct callers:
  - kernel/sched/idle.c:do_idle
```
**Symbols:**

```
ffffffff8189d387-ffffffff8189d39a: cpuidle_enter_s2idle.cold (STB_LOCAL)
ffffffff8189cb50-ffffffff8189cc8c: cpuidle_enter_s2idle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int cpuidle_enter_s2idle(struct cpuidle_driver *drv, struct cpuidle_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/cpuidle.c (ffffffff818cee70)
Location: drivers/cpuidle/cpuidle.c:174
Inline: False
Direct callers:
  - kernel/sched/idle.c:do_idle
```
**Symbols:**

```
ffffffff818cee70-ffffffff818cefac: cpuidle_enter_s2idle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int cpuidle_enter_s2idle(struct cpuidle_driver *drv, struct cpuidle_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/cpuidle.c (ffffffff819a16f0)
Location: drivers/cpuidle/cpuidle.c:180
Inline: False
Direct callers:
  - kernel/sched/idle.c:cpuidle_idle_call
```
**Symbols:**

```
ffffffff819a16f0-ffffffff819a1786: cpuidle_enter_s2idle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int cpuidle_enter_s2idle(struct cpuidle_driver *drv, struct cpuidle_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/cpuidle.c (ffffffff819a4760)
Location: drivers/cpuidle/cpuidle.c:176
Inline: False
Direct callers:
  - kernel/sched/idle.c:cpuidle_idle_call
```
**Symbols:**

```
ffffffff819a4760-ffffffff819a47f6: cpuidle_enter_s2idle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int cpuidle_enter_s2idle(struct cpuidle_driver *drv, struct cpuidle_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/cpuidle.c (ffffffff819892b0)
Location: drivers/cpuidle/cpuidle.c:176
Inline: False
Direct callers:
  - kernel/sched/idle.c:cpuidle_idle_call
```
**Symbols:**

```
ffffffff819892b0-ffffffff81989416: cpuidle_enter_s2idle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int cpuidle_enter_s2idle(struct cpuidle_driver *drv, struct cpuidle_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/cpuidle.c (ffffffff81a33600)
Location: drivers/cpuidle/cpuidle.c:176
Inline: False
Direct callers:
  - kernel/sched/idle.c:cpuidle_idle_call
```
**Symbols:**

```
ffffffff81a33600-ffffffff81a338cc: cpuidle_enter_s2idle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int cpuidle_enter_s2idle(struct cpuidle_driver *drv, struct cpuidle_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/cpuidle.c (ffffffff81b9fee0)
Location: drivers/cpuidle/cpuidle.c:176
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:cpuidle_idle_call
```
**Symbols:**

```
ffffffff81b9fee0-ffffffff81b9fff8: cpuidle_enter_s2idle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int cpuidle_enter_s2idle(struct cpuidle_driver *drv, struct cpuidle_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/cpuidle.c (ffffffff81d41a00)
Location: drivers/cpuidle/cpuidle.c:178
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:cpuidle_idle_call
```
**Symbols:**

```
ffffffff81d41a00-ffffffff81d41b18: cpuidle_enter_s2idle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int cpuidle_enter_s2idle(struct cpuidle_driver *drv, struct cpuidle_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/cpuidle.c (ffffffff81dac3d0)
Location: drivers/cpuidle/cpuidle.c:187
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:cpuidle_idle_call
```
**Symbols:**

```
ffffffff81dac3d0-ffffffff81dac4e8: cpuidle_enter_s2idle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int cpuidle_enter_s2idle(struct cpuidle_driver *drv, struct cpuidle_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/cpuidle.c (ffffffff81e64470)
Location: drivers/cpuidle/cpuidle.c:187
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:cpuidle_idle_call
```
**Symbols:**

```
ffffffff81e64470-ffffffff81e64588: cpuidle_enter_s2idle (STB_GLOBAL)
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
int cpuidle_enter_s2idle(struct cpuidle_driver *drv, struct cpuidle_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/cpuidle.c (ffff800010b26bc0)
Location: drivers/cpuidle/cpuidle.c:174
Inline: False
Direct callers:
  - kernel/sched/idle.c:do_idle
```
**Symbols:**

```
ffff800010b26bc0-ffff800010b26d24: cpuidle_enter_s2idle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int cpuidle_enter_s2idle(struct cpuidle_driver *drv, struct cpuidle_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/cpuidle.c (c0c01998)
Location: drivers/cpuidle/cpuidle.c:174
Inline: False
Direct callers:
  - kernel/sched/idle.c:do_idle
```
**Symbols:**

```
c0c01998-c0c01ae0: cpuidle_enter_s2idle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int cpuidle_enter_s2idle(struct cpuidle_driver *drv, struct cpuidle_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/cpuidle.c (c000000000c1dc40)
Location: drivers/cpuidle/cpuidle.c:174
Inline: False
Direct callers:
  - kernel/sched/idle.c:do_idle
```
**Symbols:**

```
c000000000c1dc40-c000000000c1de24: cpuidle_enter_s2idle (STB_GLOBAL)
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
Location: include/linux/cpuidle.h:215
Inline: True
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int cpuidle_enter_s2idle(struct cpuidle_driver *drv, struct cpuidle_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/cpuidle.c (ffffffff8183c710)
Location: drivers/cpuidle/cpuidle.c:174
Inline: False
Direct callers:
  - kernel/sched/idle.c:do_idle
```
**Symbols:**

```
ffffffff8183c710-ffffffff8183c847: cpuidle_enter_s2idle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int cpuidle_enter_s2idle(struct cpuidle_driver *drv, struct cpuidle_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/cpuidle.c (ffffffff818c4320)
Location: drivers/cpuidle/cpuidle.c:174
Inline: False
Direct callers:
  - kernel/sched/idle.c:do_idle
```
**Symbols:**

```
ffffffff818c4320-ffffffff818c445c: cpuidle_enter_s2idle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int cpuidle_enter_s2idle(struct cpuidle_driver *drv, struct cpuidle_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/cpuidle.c (ffffffff818e06a0)
Location: drivers/cpuidle/cpuidle.c:174
Inline: False
Direct callers:
  - kernel/sched/idle.c:do_idle
```
**Symbols:**

```
ffffffff818e06a0-ffffffff818e07dc: cpuidle_enter_s2idle (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
<b>Flavor</b>
<ul>
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
