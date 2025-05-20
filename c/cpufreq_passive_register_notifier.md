# Function: <code>cpufreq_passive_register_notifier</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int cpufreq_passive_register_notifier(struct devfreq *devfreq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/devfreq/governor_passive.c (0)
Location: drivers/devfreq/governor_passive.c:252
Inline: False
Direct callers:
  - drivers/devfreq/governor_passive.c:devfreq_passive_event_handler
```
**Symbols:**

```
ffffffff81bd6440-ffffffff81bd65df: cpufreq_passive_register_notifier (STB_LOCAL)
ffffffff81eff8ee-ffffffff81eff961: cpufreq_passive_register_notifier.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int cpufreq_passive_register_notifier(struct devfreq *devfreq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/devfreq/governor_passive.c (ffffffff81d82b80)
Location: drivers/devfreq/governor_passive.c:252
Inline: False
Direct callers:
  - drivers/devfreq/governor_passive.c:devfreq_passive_event_handler
```
**Symbols:**

```
ffffffff81d82b80-ffffffff81d82da0: cpufreq_passive_register_notifier (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int cpufreq_passive_register_notifier(struct devfreq *devfreq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/devfreq/governor_passive.c (ffffffff81df0f60)
Location: drivers/devfreq/governor_passive.c:252
Inline: False
Direct callers:
  - drivers/devfreq/governor_passive.c:devfreq_passive_event_handler
```
**Symbols:**

```
ffffffff81df0f60-ffffffff81df1180: cpufreq_passive_register_notifier (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int cpufreq_passive_register_notifier(struct devfreq *devfreq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/devfreq/governor_passive.c (ffffffff81ea7580)
Location: drivers/devfreq/governor_passive.c:252
Inline: False
Direct callers:
  - drivers/devfreq/governor_passive.c:devfreq_passive_event_handler
```
**Symbols:**

```
ffffffff81ea7580-ffffffff81ea77cf: cpufreq_passive_register_notifier (STB_LOCAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
