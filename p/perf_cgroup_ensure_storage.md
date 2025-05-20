# Function: <code>perf_cgroup_ensure_storage</code>

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
int perf_cgroup_ensure_storage(struct perf_event *event, struct cgroup_subsys_state *css);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81234860)
Location: kernel/events/core.c:905
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_alloc
```
**Symbols:**

```
ffffffff81234860-ffffffff8123499e: perf_cgroup_ensure_storage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int perf_cgroup_ensure_storage(struct perf_event *event, struct cgroup_subsys_state *css);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8123e870)
Location: kernel/events/core.c:909
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_alloc
```
**Symbols:**

```
ffffffff8123e870-ffffffff8123e9ae: perf_cgroup_ensure_storage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int perf_cgroup_ensure_storage(struct perf_event *event, struct cgroup_subsys_state *css);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81243bf0)
Location: kernel/events/core.c:907
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_alloc
```
**Symbols:**

```
ffffffff81243bf0-ffffffff81243d35: perf_cgroup_ensure_storage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int perf_cgroup_ensure_storage(struct perf_event *event, struct cgroup_subsys_state *css);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8127e500)
Location: kernel/events/core.c:945
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_alloc
```
**Symbols:**

```
ffffffff8127e500-ffffffff8127e69c: perf_cgroup_ensure_storage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int perf_cgroup_ensure_storage(struct perf_event *event, struct cgroup_subsys_state *css);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812cd370)
Location: kernel/events/core.c:880
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_alloc
```
**Symbols:**

```
ffffffff812cd370-ffffffff812cd510: perf_cgroup_ensure_storage (STB_LOCAL)
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
In kernel/events/core.c (ffffffff81338000)
Location: kernel/events/core.c:884
Inline: True
Direct callers:
  - kernel/events/core.c:perf_event_alloc
```
**Symbols:**

```
ffffffff81338000-ffffffff8133819b: perf_cgroup_ensure_storage.constprop.0 (STB_LOCAL)
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
In kernel/events/core.c (ffffffff81368840)
Location: kernel/events/core.c:884
Inline: True
Direct callers:
  - kernel/events/core.c:perf_event_alloc
```
**Symbols:**

```
ffffffff81368840-ffffffff813689d2: perf_cgroup_ensure_storage.isra.0 (STB_LOCAL)
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
In kernel/events/core.c (ffffffff81391670)
Location: kernel/events/core.c:891
Inline: True
Direct callers:
  - kernel/events/core.c:perf_event_alloc
```
**Symbols:**

```
ffffffff81391670-ffffffff81391802: perf_cgroup_ensure_storage.isra.0 (STB_LOCAL)
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
</ul>
