# Function: <code>devfreq_update_target</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int devfreq_update_target(struct devfreq *devfreq, long unsigned int freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff819cf5b0)
Location: drivers/devfreq/devfreq.c:405
Inline: False
Direct callers:
  - drivers/devfreq/devfreq.c:qos_max_notifier_call
  - drivers/devfreq/devfreq.c:qos_min_notifier_call
  - drivers/devfreq/devfreq.c:devfreq_notifier_call
  - drivers/devfreq/devfreq.c:devfreq_monitor
  - drivers/devfreq/governor_passive.c:devfreq_passive_notifier_call
```
**Symbols:**

```
ffffffff819cf5b0-ffffffff819cf656: devfreq_update_target (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int devfreq_update_target(struct devfreq *devfreq, long unsigned int freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff819b46e0)
Location: drivers/devfreq/devfreq.c:406
Inline: False
Direct callers:
  - drivers/devfreq/devfreq.c:qos_max_notifier_call
  - drivers/devfreq/devfreq.c:qos_min_notifier_call
  - drivers/devfreq/devfreq.c:devfreq_notifier_call
  - drivers/devfreq/devfreq.c:devfreq_monitor
  - drivers/devfreq/governor_passive.c:devfreq_passive_notifier_call
```
**Symbols:**

```
ffffffff819b46e0-ffffffff819b4786: devfreq_update_target (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int devfreq_update_target(struct devfreq *devfreq, long unsigned int freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff81a63220)
Location: drivers/devfreq/devfreq.c:406
Inline: False
Direct callers:
  - drivers/devfreq/devfreq.c:qos_max_notifier_call
  - drivers/devfreq/devfreq.c:qos_min_notifier_call
  - drivers/devfreq/devfreq.c:devfreq_notifier_call
  - drivers/devfreq/devfreq.c:devfreq_monitor
  - drivers/devfreq/governor_passive.c:devfreq_passive_notifier_call
```
**Symbols:**

```
ffffffff81a63220-ffffffff81a632c6: devfreq_update_target (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int devfreq_update_target(struct devfreq *devfreq, long unsigned int freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff81bd2110)
Location: drivers/devfreq/devfreq.c:403
Inline: False
Direct callers:
  - drivers/devfreq/devfreq.c:qos_max_notifier_call
  - drivers/devfreq/devfreq.c:qos_min_notifier_call
  - drivers/devfreq/devfreq.c:devfreq_notifier_call
  - drivers/devfreq/devfreq.c:devfreq_monitor
  - drivers/devfreq/governor_passive.c:devfreq_passive_notifier_call
  - drivers/devfreq/governor_passive.c:cpufreq_passive_register_notifier
  - drivers/devfreq/governor_passive.c:cpufreq_passive_notifier_call
```
**Symbols:**

```
ffffffff81bd2110-ffffffff81bd21d1: devfreq_update_target (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int devfreq_update_target(struct devfreq *devfreq, long unsigned int freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff81d7dd50)
Location: drivers/devfreq/devfreq.c:403
Inline: False
Direct callers:
  - drivers/devfreq/devfreq.c:qos_max_notifier_call
  - drivers/devfreq/devfreq.c:qos_min_notifier_call
  - drivers/devfreq/devfreq.c:devfreq_notifier_call
  - drivers/devfreq/devfreq.c:devfreq_monitor
  - drivers/devfreq/governor_passive.c:devfreq_passive_notifier_call
  - drivers/devfreq/governor_passive.c:cpufreq_passive_register_notifier
  - drivers/devfreq/governor_passive.c:cpufreq_passive_notifier_call
```
**Symbols:**

```
ffffffff81d7dd50-ffffffff81d7de11: devfreq_update_target (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int devfreq_update_target(struct devfreq *devfreq, long unsigned int freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff81dec0d0)
Location: drivers/devfreq/devfreq.c:403
Inline: False
Direct callers:
  - drivers/devfreq/devfreq.c:qos_max_notifier_call
  - drivers/devfreq/devfreq.c:qos_min_notifier_call
  - drivers/devfreq/devfreq.c:devfreq_notifier_call
  - drivers/devfreq/devfreq.c:devfreq_monitor
  - drivers/devfreq/governor_passive.c:devfreq_passive_notifier_call
  - drivers/devfreq/governor_passive.c:cpufreq_passive_register_notifier
  - drivers/devfreq/governor_passive.c:cpufreq_passive_notifier_call
```
**Symbols:**

```
ffffffff81dec0d0-ffffffff81dec191: devfreq_update_target (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int devfreq_update_target(struct devfreq *devfreq, long unsigned int freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff81ea24c0)
Location: drivers/devfreq/devfreq.c:403
Inline: False
Direct callers:
  - drivers/devfreq/devfreq.c:qos_max_notifier_call
  - drivers/devfreq/devfreq.c:qos_min_notifier_call
  - drivers/devfreq/devfreq.c:devfreq_notifier_call
  - drivers/devfreq/devfreq.c:devfreq_monitor
  - drivers/devfreq/governor_passive.c:devfreq_passive_notifier_call
  - drivers/devfreq/governor_passive.c:cpufreq_passive_register_notifier
  - drivers/devfreq/governor_passive.c:cpufreq_passive_notifier_call
```
**Symbols:**

```
ffffffff81ea24c0-ffffffff81ea2581: devfreq_update_target (STB_GLOBAL)
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
