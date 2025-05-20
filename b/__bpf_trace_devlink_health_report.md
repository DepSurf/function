# Function: <code>__bpf_trace_devlink_health_report</code>

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
void __bpf_trace_devlink_health_report(void *__data, const struct devlink *devlink, const char *reporter_name, const char *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81946650)
Location: include/trace/events/devlink.h:81
Inline: False
```
**Symbols:**

```
ffffffff81946650-ffffffff8194665b: __bpf_trace_devlink_health_report (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __bpf_trace_devlink_health_report(void *__data, const struct devlink *devlink, const char *reporter_name, const char *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff8197b600)
Location: include/trace/events/devlink.h:81
Inline: False
```
**Symbols:**

```
ffffffff8197b600-ffffffff8197b60b: __bpf_trace_devlink_health_report (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __bpf_trace_devlink_health_report(void *__data, const struct devlink *devlink, const char *reporter_name, const char *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a50860)
Location: include/trace/events/devlink.h:81
Inline: False
```
**Symbols:**

```
ffffffff81a50860-ffffffff81a5086b: __bpf_trace_devlink_health_report (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_devlink_health_report(void *__data, const struct devlink *devlink, const char *reporter_name, const char *msg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a56980)
Location: include/trace/events/devlink.h:81
Inline: True
```
**Symbols:**

```
ffffffff81a56980-ffffffff81a5698b: __bpf_trace_devlink_health_report (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_devlink_health_report(void *__data, const struct devlink *devlink, const char *reporter_name, const char *msg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a398e0)
Location: include/trace/events/devlink.h:81
Inline: True
```
**Symbols:**

```
ffffffff81a398e0-ffffffff81a398eb: __bpf_trace_devlink_health_report (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_devlink_health_report(void *__data, const struct devlink *devlink, const char *reporter_name, const char *msg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81aef6e0)
Location: include/trace/events/devlink.h:81
Inline: True
```
**Symbols:**

```
ffffffff81aef6e0-ffffffff81aef6eb: __bpf_trace_devlink_health_report (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_devlink_health_report(void *__data, const struct devlink *devlink, const char *reporter_name, const char *msg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81c72af0)
Location: include/trace/events/devlink.h:81
Inline: True
```
**Symbols:**

```
ffffffff81c72af0-ffffffff81c72b07: __bpf_trace_devlink_health_report (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_devlink_health_report(void *__data, const struct devlink *devlink, const char *reporter_name, const char *msg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81e2b4d0)
Location: include/trace/events/devlink.h:81
Inline: True
```
**Symbols:**

```
ffffffff81e2b4d0-ffffffff81e2b4e7: __bpf_trace_devlink_health_report (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_devlink_health_report(void *__data, const struct devlink *devlink, const char *reporter_name, const char *msg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/devlink/leftover.c (ffffffff8202f470)
Location: include/trace/events/devlink.h:81
Inline: True
```
**Symbols:**

```
ffffffff8202f470-ffffffff8202f487: __bpf_trace_devlink_health_report (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_devlink_health_report(void *__data, const struct devlink *devlink, const char *reporter_name, const char *msg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/devlink/core.c (ffffffff820fe720)
Location: include/trace/events/devlink.h:81
Inline: True
```
**Symbols:**

```
ffffffff820fe720-ffffffff820fe737: __bpf_trace_devlink_health_report (STB_LOCAL)
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
void __bpf_trace_devlink_health_report(void *__data, const struct devlink *devlink, const char *reporter_name, const char *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffff800010c22ed8)
Location: include/trace/events/devlink.h:81
Inline: False
```
**Symbols:**

```
ffff800010c22ed8-ffff800010c22eec: __bpf_trace_devlink_health_report (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __bpf_trace_devlink_health_report(void *__data, const struct devlink *devlink, const char *reporter_name, const char *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (c0d3a25c)
Location: include/trace/events/devlink.h:81
Inline: False
```
**Symbols:**

```
c0d3a25c-c0d3a294: __bpf_trace_devlink_health_report (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __bpf_trace_devlink_health_report(void *__data, const struct devlink *devlink, const char *reporter_name, const char *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (c000000000d15870)
Location: include/trace/events/devlink.h:81
Inline: False
```
**Symbols:**

```
c000000000d15870-c000000000d1589c: __bpf_trace_devlink_health_report (STB_LOCAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void __bpf_trace_devlink_health_report(void *__data, const struct devlink *devlink, const char *reporter_name, const char *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff8191b470)
Location: include/trace/events/devlink.h:81
Inline: False
```
**Symbols:**

```
ffffffff8191b470-ffffffff8191b47b: __bpf_trace_devlink_health_report (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __bpf_trace_devlink_health_report(void *__data, const struct devlink *devlink, const char *reporter_name, const char *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff818d5220)
Location: include/trace/events/devlink.h:81
Inline: False
```
**Symbols:**

```
ffffffff818d5220-ffffffff818d522b: __bpf_trace_devlink_health_report (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __bpf_trace_devlink_health_report(void *__data, const struct devlink *devlink, const char *reporter_name, const char *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff8196c600)
Location: include/trace/events/devlink.h:81
Inline: False
```
**Symbols:**

```
ffffffff8196c600-ffffffff8196c60b: __bpf_trace_devlink_health_report (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __bpf_trace_devlink_health_report(void *__data, const struct devlink *devlink, const char *reporter_name, const char *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff8198ea80)
Location: include/trace/events/devlink.h:81
Inline: False
```
**Symbols:**

```
ffffffff8198ea80-ffffffff8198ea8b: __bpf_trace_devlink_health_report (STB_LOCAL)
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
