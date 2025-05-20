# Function: <code>__traceiter_devlink_health_report</code>

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
int __traceiter_devlink_health_report(void *__data, const struct devlink *devlink, const char *reporter_name, const char *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a56250)
Location: include/trace/events/devlink.h:81
Inline: False
```
**Symbols:**

```
ffffffff81a56250-ffffffff81a562a1: __traceiter_devlink_health_report (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __traceiter_devlink_health_report(void *__data, const struct devlink *devlink, const char *reporter_name, const char *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a39250)
Location: include/trace/events/devlink.h:81
Inline: False
```
**Symbols:**

```
ffffffff81a39250-ffffffff81a3929f: __traceiter_devlink_health_report (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __traceiter_devlink_health_report(void *__data, const struct devlink *devlink, const char *reporter_name, const char *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81aef230)
Location: include/trace/events/devlink.h:81
Inline: False
```
**Symbols:**

```
ffffffff81aef230-ffffffff81aef27f: __traceiter_devlink_health_report (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __traceiter_devlink_health_report(void *__data, const struct devlink *devlink, const char *reporter_name, const char *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81c72250)
Location: include/trace/events/devlink.h:81
Inline: False
```
**Symbols:**

```
ffffffff81c72250-ffffffff81c722ab: __traceiter_devlink_health_report (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __traceiter_devlink_health_report(void *__data, const struct devlink *devlink, const char *reporter_name, const char *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81e2a420)
Location: include/trace/events/devlink.h:81
Inline: False
```
**Symbols:**

```
ffffffff81e2a420-ffffffff81e2a47b: __traceiter_devlink_health_report (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __traceiter_devlink_health_report(void *__data, const struct devlink *devlink, const char *reporter_name, const char *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/devlink/leftover.c (ffffffff8202e120)
Location: include/trace/events/devlink.h:81
Inline: False
```
**Symbols:**

```
ffffffff8202e120-ffffffff8202e17b: __traceiter_devlink_health_report (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __traceiter_devlink_health_report(void *__data, const struct devlink *devlink, const char *reporter_name, const char *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/devlink/core.c (ffffffff820fdba0)
Location: include/trace/events/devlink.h:81
Inline: False
```
**Symbols:**

```
ffffffff820fdba0-ffffffff820fdbfb: __traceiter_devlink_health_report (STB_GLOBAL)
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
