# Function: <code>__clockevents_try_unbind</code>

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
In kernel/time/clockevents.c (ffffffff810fbb6e)
Location: kernel/time/clockevents.c:392
Inline: True
Inline callers:
  - kernel/time/clockevents.c:sysfs_unbind_tick_dev
  - kernel/time/clockevents.c:__clockevents_unbind
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
In kernel/time/clockevents.c (ffffffff81102ea1)
Location: kernel/time/clockevents.c:392
Inline: True
Inline callers:
  - kernel/time/clockevents.c:sysfs_unbind_tick_dev
  - kernel/time/clockevents.c:__clockevents_unbind
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/clockevents.c (ffffffff8110a591)
Location: kernel/time/clockevents.c:392
Inline: True
Inline callers:
  - kernel/time/clockevents.c:sysfs_unbind_tick_dev
  - kernel/time/clockevents.c:__clockevents_unbind
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/clockevents.c (ffffffff8110c53e)
Location: kernel/time/clockevents.c:392
Inline: True
Inline callers:
  - kernel/time/clockevents.c:sysfs_unbind_tick_dev
  - kernel/time/clockevents.c:__clockevents_unbind
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/clockevents.c (ffffffff8111778e)
Location: kernel/time/clockevents.c:397
Inline: True
Inline callers:
  - kernel/time/clockevents.c:sysfs_unbind_tick_dev
  - kernel/time/clockevents.c:__clockevents_unbind
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int __clockevents_try_unbind(struct clock_event_device *ced, int cpu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/clockevents.c (ffffffff81124060)
Location: kernel/time/clockevents.c:397
Inline: True
Direct callers:
  - kernel/time/clockevents.c:sysfs_unbind_tick_dev
  - kernel/time/clockevents.c:__clockevents_unbind
```
**Symbols:**

```
ffffffff81124060-ffffffff811240bf: __clockevents_try_unbind (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int __clockevents_try_unbind(struct clock_event_device *ced, int cpu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/clockevents.c (ffffffff8112f760)
Location: kernel/time/clockevents.c:387
Inline: True
Direct callers:
  - kernel/time/clockevents.c:sysfs_unbind_tick_dev
  - kernel/time/clockevents.c:__clockevents_unbind
```
**Symbols:**

```
ffffffff8112f760-ffffffff8112f7bf: __clockevents_try_unbind (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int __clockevents_try_unbind(struct clock_event_device *ced, int cpu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/clockevents.c (ffffffff8113a280)
Location: kernel/time/clockevents.c:387
Inline: True
Direct callers:
  - kernel/time/clockevents.c:sysfs_unbind_tick_dev
  - kernel/time/clockevents.c:__clockevents_unbind
```
**Symbols:**

```
ffffffff8113a280-ffffffff8113a2e0: __clockevents_try_unbind (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int __clockevents_try_unbind(struct clock_event_device *ced, int cpu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/clockevents.c (ffffffff81145ef0)
Location: kernel/time/clockevents.c:387
Inline: True
Direct callers:
  - kernel/time/clockevents.c:sysfs_unbind_tick_dev
  - kernel/time/clockevents.c:__clockevents_unbind
```
**Symbols:**

```
ffffffff81145ef0-ffffffff81145f50: __clockevents_try_unbind (STB_LOCAL)
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
In kernel/time/clockevents.c (ffffffff81155e94)
Location: kernel/time/clockevents.c:387
Inline: True
Inline callers:
  - kernel/time/clockevents.c:sysfs_unbind_tick_dev
  - kernel/time/clockevents.c:sysfs_unbind_tick_dev
  - kernel/time/clockevents.c:__clockevents_unbind
  - kernel/time/clockevents.c:__clockevents_unbind
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
In kernel/time/clockevents.c (ffffffff81152034)
Location: kernel/time/clockevents.c:387
Inline: True
Inline callers:
  - kernel/time/clockevents.c:sysfs_unbind_tick_dev
  - kernel/time/clockevents.c:sysfs_unbind_tick_dev
  - kernel/time/clockevents.c:__clockevents_unbind
  - kernel/time/clockevents.c:__clockevents_unbind
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
In kernel/time/clockevents.c (ffffffff8115352e)
Location: kernel/time/clockevents.c:387
Inline: True
Inline callers:
  - kernel/time/clockevents.c:sysfs_unbind_tick_dev
  - kernel/time/clockevents.c:sysfs_unbind_tick_dev
  - kernel/time/clockevents.c:__clockevents_unbind
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
In kernel/time/clockevents.c (ffffffff81177b80)
Location: kernel/time/clockevents.c:386
Inline: True
Inline callers:
  - kernel/time/clockevents.c:unbind_device_store
  - kernel/time/clockevents.c:unbind_device_store
  - kernel/time/clockevents.c:__clockevents_unbind
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
In kernel/time/clockevents.c (ffffffff811acbc4)
Location: kernel/time/clockevents.c:386
Inline: True
Inline callers:
  - kernel/time/clockevents.c:unbind_device_store
  - kernel/time/clockevents.c:unbind_device_store
  - kernel/time/clockevents.c:__clockevents_unbind
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
In kernel/time/clockevents.c (ffffffff811ed044)
Location: kernel/time/clockevents.c:386
Inline: True
Inline callers:
  - kernel/time/clockevents.c:unbind_device_store
  - kernel/time/clockevents.c:unbind_device_store
  - kernel/time/clockevents.c:__clockevents_unbind
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
In kernel/time/clockevents.c (ffffffff81201764)
Location: kernel/time/clockevents.c:386
Inline: True
Inline callers:
  - kernel/time/clockevents.c:unbind_device_store
  - kernel/time/clockevents.c:unbind_device_store
  - kernel/time/clockevents.c:__clockevents_unbind
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
In kernel/time/clockevents.c (ffffffff81217c04)
Location: kernel/time/clockevents.c:386
Inline: True
Inline callers:
  - kernel/time/clockevents.c:unbind_device_store
  - kernel/time/clockevents.c:unbind_device_store
  - kernel/time/clockevents.c:__clockevents_unbind
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
int __clockevents_try_unbind(struct clock_event_device *ced, int cpu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/clockevents.c (ffff8000101b0488)
Location: kernel/time/clockevents.c:387
Inline: True
Direct callers:
  - kernel/time/clockevents.c:sysfs_unbind_tick_dev
  - kernel/time/clockevents.c:__clockevents_unbind
```
**Symbols:**

```
ffff8000101b0488-ffff8000101b0504: __clockevents_try_unbind (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int __clockevents_try_unbind(struct clock_event_device *ced, int cpu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/clockevents.c (c03fb3e4)
Location: kernel/time/clockevents.c:387
Inline: True
Direct callers:
  - kernel/time/clockevents.c:sysfs_unbind_tick_dev
  - kernel/time/clockevents.c:__clockevents_unbind
```
**Symbols:**

```
c03fb3e4-c03fb450: __clockevents_try_unbind (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int __clockevents_try_unbind(struct clock_event_device *ced, int cpu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/clockevents.c (c000000000215120)
Location: kernel/time/clockevents.c:387
Inline: True
Direct callers:
  - kernel/time/clockevents.c:sysfs_unbind_tick_dev
  - kernel/time/clockevents.c:__clockevents_unbind
```
**Symbols:**

```
c000000000215120-c000000000215194: __clockevents_try_unbind (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int __clockevents_try_unbind(struct clock_event_device *ced, int cpu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/clockevents.c (ffffffe000139476)
Location: kernel/time/clockevents.c:387
Inline: True
Direct callers:
  - kernel/time/clockevents.c:sysfs_unbind_tick_dev
  - kernel/time/clockevents.c:__clockevents_unbind
```
**Symbols:**

```
ffffffe000139476-ffffffe0001394e2: __clockevents_try_unbind (STB_LOCAL)
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
int __clockevents_try_unbind(struct clock_event_device *ced, int cpu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/clockevents.c (ffffffff8113e6a0)
Location: kernel/time/clockevents.c:387
Inline: True
Direct callers:
  - kernel/time/clockevents.c:sysfs_unbind_tick_dev
  - kernel/time/clockevents.c:__clockevents_unbind
```
**Symbols:**

```
ffffffff8113e6a0-ffffffff8113e700: __clockevents_try_unbind (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int __clockevents_try_unbind(struct clock_event_device *ced, int cpu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/clockevents.c (ffffffff811311c0)
Location: kernel/time/clockevents.c:387
Inline: True
Direct callers:
  - kernel/time/clockevents.c:sysfs_unbind_tick_dev
  - kernel/time/clockevents.c:__clockevents_unbind
```
**Symbols:**

```
ffffffff811311c0-ffffffff81131220: __clockevents_try_unbind (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int __clockevents_try_unbind(struct clock_event_device *ced, int cpu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/clockevents.c (ffffffff8113c3c0)
Location: kernel/time/clockevents.c:387
Inline: True
Direct callers:
  - kernel/time/clockevents.c:sysfs_unbind_tick_dev
  - kernel/time/clockevents.c:__clockevents_unbind
```
**Symbols:**

```
ffffffff8113c3c0-ffffffff8113c420: __clockevents_try_unbind (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int __clockevents_try_unbind(struct clock_event_device *ced, int cpu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/clockevents.c (ffffffff81148f30)
Location: kernel/time/clockevents.c:387
Inline: True
Direct callers:
  - kernel/time/clockevents.c:sysfs_unbind_tick_dev
  - kernel/time/clockevents.c:__clockevents_unbind
```
**Symbols:**

```
ffffffff81148f30-ffffffff81148f90: __clockevents_try_unbind (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
