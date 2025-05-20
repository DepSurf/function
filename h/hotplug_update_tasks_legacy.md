# Function: <code>hotplug_update_tasks_legacy</code>

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
In kernel/cpuset.c (ffffffff8111d2af)
Location: kernel/cpuset.c:2153
Inline: True
Inline callers:
  - kernel/cpuset.c:cpuset_hotplug_workfn
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
In kernel/cpuset.c (ffffffff81124f9a)
Location: kernel/cpuset.c:2174
Inline: True
Inline callers:
  - kernel/cpuset.c:cpuset_hotplug_workfn
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
In kernel/cpuset.c (ffffffff8112e824)
Location: kernel/cpuset.c:2174
Inline: True
Inline callers:
  - kernel/cpuset.c:cpuset_hotplug_workfn
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
In kernel/cgroup/cpuset.c (ffffffff8112ff5d)
Location: kernel/cgroup/cpuset.c:2160
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
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
In kernel/cgroup/cpuset.c (ffffffff8113ca5f)
Location: kernel/cgroup/cpuset.c:2170
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff8114b72f)
Location: kernel/cgroup/cpuset.c:2171
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff8115804a)
Location: kernel/cgroup/cpuset.c:2899
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff81162481)
Location: kernel/cgroup/cpuset.c:2854
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff8116e199)
Location: kernel/cgroup/cpuset.c:2942
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
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
In kernel/cgroup/cpuset.c (0)
Location: kernel/cgroup/cpuset.c:2944
Inline: True
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
```
**Symbols:**

```
ffffffff8117f0e0-ffffffff8117f489: hotplug_update_tasks_legacy.constprop.0 (STB_LOCAL)
ffffffff811831ee-ffffffff81183226: hotplug_update_tasks_legacy.constprop.0.cold (STB_LOCAL)
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
In kernel/cgroup/cpuset.c (0)
Location: kernel/cgroup/cpuset.c:2967
Inline: True
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
```
**Symbols:**

```
ffffffff8117bf70-ffffffff8117c319: hotplug_update_tasks_legacy.constprop.0 (STB_LOCAL)
ffffffff81be4823-ffffffff81be485b: hotplug_update_tasks_legacy.constprop.0.cold (STB_LOCAL)
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
In kernel/cgroup/cpuset.c (ffffffff8117f3f1)
Location: kernel/cgroup/cpuset.c:2967
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
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
In kernel/cgroup/cpuset.c (ffffffff811a75b4)
Location: kernel/cgroup/cpuset.c:3024
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
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
In kernel/cgroup/cpuset.c (ffffffff811d8655)
Location: kernel/cgroup/cpuset.c:3064
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
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
In kernel/cgroup/cpuset.c (ffffffff8121d501)
Location: kernel/cgroup/cpuset.c:3337
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
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
In kernel/cgroup/cpuset.c (ffffffff8122ebe0)
Location: kernel/cgroup/cpuset.c:3526
Inline: True
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
```
**Symbols:**

```
ffffffff8122ebe0-ffffffff8122ef77: hotplug_update_tasks_legacy.constprop.0 (STB_LOCAL)
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
In kernel/cgroup/cpuset.c (ffffffff81247180)
Location: kernel/cgroup/cpuset.c:4357
Inline: True
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
```
**Symbols:**

```
ffffffff81247180-ffffffff8124752e: hotplug_update_tasks_legacy.constprop.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffff8000101e2874)
Location: kernel/cgroup/cpuset.c:2942
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (c0424d38)
Location: kernel/cgroup/cpuset.c:2942
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (c0000000002510e0)
Location: kernel/cgroup/cpuset.c:2942
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
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
In kernel/cgroup/cpuset.c (ffffffe00015935e)
Location: kernel/cgroup/cpuset.c:2942
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff811667b9)
Location: kernel/cgroup/cpuset.c:2942
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff811599f3)
Location: kernel/cgroup/cpuset.c:2942
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff81164589)
Location: kernel/cgroup/cpuset.c:2942
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff81171a2b)
Location: kernel/cgroup/cpuset.c:2942
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
```
</details>
</li>
</ul>

## Differences
