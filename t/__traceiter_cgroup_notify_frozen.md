# Function: <code>__traceiter_cgroup_notify_frozen</code>

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
int __traceiter_cgroup_notify_frozen(void *__data, struct cgroup *cgrp, const char *path, int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8116abd0)
Location: include/trace/events/cgroup.h:200
Inline: False
```
**Symbols:**

```
ffffffff8116abd0-ffffffff8116ac21: __traceiter_cgroup_notify_frozen (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __traceiter_cgroup_notify_frozen(void *__data, struct cgroup *cgrp, const char *path, int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8116b820)
Location: include/trace/events/cgroup.h:200
Inline: False
```
**Symbols:**

```
ffffffff8116b820-ffffffff8116b86f: __traceiter_cgroup_notify_frozen (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __traceiter_cgroup_notify_frozen(void *__data, struct cgroup *cgrp, const char *path, int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81191420)
Location: include/trace/events/cgroup.h:200
Inline: False
```
**Symbols:**

```
ffffffff81191420-ffffffff8119146f: __traceiter_cgroup_notify_frozen (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __traceiter_cgroup_notify_frozen(void *__data, struct cgroup *cgrp, const char *path, int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811c0b80)
Location: include/trace/events/cgroup.h:200
Inline: False
```
**Symbols:**

```
ffffffff811c0b80-ffffffff811c0bdb: __traceiter_cgroup_notify_frozen (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __traceiter_cgroup_notify_frozen(void *__data, struct cgroup *cgrp, const char *path, int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81203060)
Location: include/trace/events/cgroup.h:200
Inline: False
```
**Symbols:**

```
ffffffff81203060-ffffffff812030bb: __traceiter_cgroup_notify_frozen (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __traceiter_cgroup_notify_frozen(void *__data, struct cgroup *cgrp, const char *path, int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff812184a0)
Location: include/trace/events/cgroup.h:200
Inline: False
```
**Symbols:**

```
ffffffff812184a0-ffffffff812184fb: __traceiter_cgroup_notify_frozen (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __traceiter_cgroup_notify_frozen(void *__data, struct cgroup *cgrp, const char *path, int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81230060)
Location: include/trace/events/cgroup.h:200
Inline: False
```
**Symbols:**

```
ffffffff81230060-ffffffff812300bb: __traceiter_cgroup_notify_frozen (STB_GLOBAL)
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
