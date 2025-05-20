# Function: <code>cpuidle_enter_freeze</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int cpuidle_enter_freeze(struct cpuidle_driver *drv, struct cpuidle_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/cpuidle.c (ffffffff816bb810)
Location: drivers/cpuidle/cpuidle.c:146
Inline: False
Direct callers:
  - kernel/sched/idle.c:cpu_startup_entry
```
**Symbols:**

```
ffffffff816bb810-ffffffff816bb8d9: cpuidle_enter_freeze (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int cpuidle_enter_freeze(struct cpuidle_driver *drv, struct cpuidle_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/cpuidle.c (ffffffff8171d0c0)
Location: drivers/cpuidle/cpuidle.c:146
Inline: False
Direct callers:
  - kernel/sched/idle.c:cpu_startup_entry
```
**Symbols:**

```
ffffffff8171d0c0-ffffffff8171d19e: cpuidle_enter_freeze (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int cpuidle_enter_freeze(struct cpuidle_driver *drv, struct cpuidle_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/cpuidle.c (ffffffff8174fca0)
Location: drivers/cpuidle/cpuidle.c:163
Inline: False
Direct callers:
  - kernel/sched/idle.c:do_idle
```
**Symbols:**

```
ffffffff8174fca0-ffffffff8174fd7e: cpuidle_enter_freeze (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int cpuidle_enter_freeze(struct cpuidle_driver *drv, struct cpuidle_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/cpuidle.c (ffffffff8176e750)
Location: drivers/cpuidle/cpuidle.c:165
Inline: False
Direct callers:
  - kernel/sched/idle.c:do_idle
```
**Symbols:**

```
ffffffff8176e750-ffffffff8176e821: cpuidle_enter_freeze (STB_GLOBAL)
```
</details>
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
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
</ul>
