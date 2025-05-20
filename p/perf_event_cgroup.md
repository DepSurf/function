# Function: <code>perf_event_cgroup</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void perf_event_cgroup(struct cgroup *cgrp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81233910)
Location: kernel/events/core.c:7841
Inline: False
Direct callers:
  - kernel/events/core.c:perf_cgroup_css_online
```
**Symbols:**

```
ffffffff81233910-ffffffff81233a37: perf_event_cgroup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void perf_event_cgroup(struct cgroup *cgrp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8123d6e0)
Location: kernel/events/core.c:8023
Inline: False
Direct callers:
  - kernel/events/core.c:perf_cgroup_css_online
```
**Symbols:**

```
ffffffff8123d6e0-ffffffff8123d807: perf_event_cgroup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void perf_event_cgroup(struct cgroup *cgrp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81242150)
Location: kernel/events/core.c:8134
Inline: False
Direct callers:
  - kernel/events/core.c:perf_cgroup_css_online
```
**Symbols:**

```
ffffffff81242150-ffffffff81242273: perf_event_cgroup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void perf_event_cgroup(struct cgroup *cgrp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8127ca60)
Location: kernel/events/core.c:8258
Inline: False
Direct callers:
  - kernel/events/core.c:perf_cgroup_css_online
```
**Symbols:**

```
ffffffff8127ca60-ffffffff8127cb83: perf_event_cgroup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void perf_event_cgroup(struct cgroup *cgrp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812d1280)
Location: kernel/events/core.c:8163
Inline: False
Direct callers:
  - kernel/events/core.c:perf_cgroup_css_online
```
**Symbols:**

```
ffffffff812d1280-ffffffff812d13b8: perf_event_cgroup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void perf_event_cgroup(struct cgroup *cgrp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81338a70)
Location: kernel/events/core.c:8445
Inline: False
Direct callers:
  - kernel/events/core.c:perf_cgroup_css_online
```
**Symbols:**

```
ffffffff81338a70-ffffffff81338ba8: perf_event_cgroup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void perf_event_cgroup(struct cgroup *cgrp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81369b20)
Location: kernel/events/core.c:8473
Inline: False
Direct callers:
  - kernel/events/core.c:perf_cgroup_css_online
```
**Symbols:**

```
ffffffff81369b20-ffffffff81369c58: perf_event_cgroup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void perf_event_cgroup(struct cgroup *cgrp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81392a00)
Location: kernel/events/core.c:8554
Inline: False
Direct callers:
  - kernel/events/core.c:perf_cgroup_css_online
```
**Symbols:**

```
ffffffff81392a00-ffffffff81392b67: perf_event_cgroup (STB_LOCAL)
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
