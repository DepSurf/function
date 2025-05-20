# Function: <code>__traceiter_devlink_hwmsg</code>

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
int __traceiter_devlink_hwmsg(void *__data, const struct devlink *devlink, bool incoming, long unsigned int type, const u8 *buf, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a56180)
Location: include/trace/events/devlink.h:17
Inline: False
```
**Symbols:**

```
ffffffff81a56180-ffffffff81a561ec: __traceiter_devlink_hwmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __traceiter_devlink_hwmsg(void *__data, const struct devlink *devlink, bool incoming, long unsigned int type, const u8 *buf, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a39190)
Location: include/trace/events/devlink.h:17
Inline: False
```
**Symbols:**

```
ffffffff81a39190-ffffffff81a391fa: __traceiter_devlink_hwmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __traceiter_devlink_hwmsg(void *__data, const struct devlink *devlink, bool incoming, long unsigned int type, const u8 *buf, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81aef170)
Location: include/trace/events/devlink.h:17
Inline: False
```
**Symbols:**

```
ffffffff81aef170-ffffffff81aef1da: __traceiter_devlink_hwmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __traceiter_devlink_hwmsg(void *__data, const struct devlink *devlink, bool incoming, long unsigned int type, const u8 *buf, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81c72170)
Location: include/trace/events/devlink.h:17
Inline: False
```
**Symbols:**

```
ffffffff81c72170-ffffffff81c721f0: __traceiter_devlink_hwmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __traceiter_devlink_hwmsg(void *__data, const struct devlink *devlink, bool incoming, long unsigned int type, const u8 *buf, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81e2a320)
Location: include/trace/events/devlink.h:17
Inline: False
```
**Symbols:**

```
ffffffff81e2a320-ffffffff81e2a3a0: __traceiter_devlink_hwmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __traceiter_devlink_hwmsg(void *__data, const struct devlink *devlink, bool incoming, long unsigned int type, const u8 *buf, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/devlink/leftover.c (ffffffff8202dfe0)
Location: include/trace/events/devlink.h:17
Inline: False
```
**Symbols:**

```
ffffffff8202dfe0-ffffffff8202e060: __traceiter_devlink_hwmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __traceiter_devlink_hwmsg(void *__data, const struct devlink *devlink, bool incoming, long unsigned int type, const u8 *buf, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/devlink/core.c (ffffffff820fda60)
Location: include/trace/events/devlink.h:17
Inline: False
```
**Symbols:**

```
ffffffff820fda60-ffffffff820fdae0: __traceiter_devlink_hwmsg (STB_GLOBAL)
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
