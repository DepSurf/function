# Function: <code>trace_event_raw_event_iocost_iocg_activate</code>

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
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void trace_event_raw_event_iocost_iocg_activate(void *__data, struct ioc_gq *iocg, const char *path, struct ioc_now *now, u64 last_period, u64 cur_period, u64 vtime);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff81510bd0)
Location: include/trace/events/iocost.h:14
Inline: False
```
**Symbols:**

```
ffffffff81510bd0-ffffffff81510e3c: trace_event_raw_event_iocost_iocg_activate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void trace_event_raw_event_iocost_iocg_activate(void *__data, struct ioc_gq *iocg, const char *path, struct ioc_now *now, u64 last_period, u64 cur_period, u64 vtime);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff81571850)
Location: include/trace/events/iocost.h:14
Inline: False
```
**Symbols:**

```
ffffffff81571850-ffffffff81571a9d: trace_event_raw_event_iocost_iocg_activate (STB_LOCAL)
```
</details>
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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void trace_event_raw_event_iocost_iocg_activate(void *__data, struct ioc_gq *iocg, const char *path, struct ioc_now *now, u64 last_period, u64 cur_period, u64 vtime);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffff800010613d30)
Location: include/trace/events/iocost.h:14
Inline: False
```
**Symbols:**

```
ffff800010613d30-ffff800010613f5c: trace_event_raw_event_iocost_iocg_activate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void trace_event_raw_event_iocost_iocg_activate(void *__data, struct ioc_gq *iocg, const char *path, struct ioc_now *now, u64 last_period, u64 cur_period, u64 vtime);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (c07bfa9c)
Location: include/trace/events/iocost.h:14
Inline: False
```
**Symbols:**

```
c07bfa9c-c07bfcd8: trace_event_raw_event_iocost_iocg_activate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void trace_event_raw_event_iocost_iocg_activate(void *__data, struct ioc_gq *iocg, const char *path, struct ioc_now *now, u64 last_period, u64 cur_period, u64 vtime);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (c0000000007b30d0)
Location: include/trace/events/iocost.h:14
Inline: False
```
**Symbols:**

```
c0000000007b30d0-c0000000007b33bc: trace_event_raw_event_iocost_iocg_activate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void trace_event_raw_event_iocost_iocg_activate(void *__data, struct ioc_gq *iocg, const char *path, struct ioc_now *now, u64 last_period, u64 cur_period, u64 vtime);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffe00044ba4e)
Location: include/trace/events/iocost.h:14
Inline: False
```
**Symbols:**

```
ffffffe00044ba4e-ffffffe00044bc26: trace_event_raw_event_iocost_iocg_activate (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void trace_event_raw_event_iocost_iocg_activate(void *__data, struct ioc_gq *iocg, const char *path, struct ioc_now *now, u64 last_period, u64 cur_period, u64 vtime);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff815091b0)
Location: include/trace/events/iocost.h:14
Inline: False
```
**Symbols:**

```
ffffffff815091b0-ffffffff8150941c: trace_event_raw_event_iocost_iocg_activate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void trace_event_raw_event_iocost_iocg_activate(void *__data, struct ioc_gq *iocg, const char *path, struct ioc_now *now, u64 last_period, u64 cur_period, u64 vtime);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff814f9660)
Location: include/trace/events/iocost.h:14
Inline: False
```
**Symbols:**

```
ffffffff814f9660-ffffffff814f98cc: trace_event_raw_event_iocost_iocg_activate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void trace_event_raw_event_iocost_iocg_activate(void *__data, struct ioc_gq *iocg, const char *path, struct ioc_now *now, u64 last_period, u64 cur_period, u64 vtime);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff81505240)
Location: include/trace/events/iocost.h:14
Inline: False
```
**Symbols:**

```
ffffffff81505240-ffffffff815054ac: trace_event_raw_event_iocost_iocg_activate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void trace_event_raw_event_iocost_iocg_activate(void *__data, struct ioc_gq *iocg, const char *path, struct ioc_now *now, u64 last_period, u64 cur_period, u64 vtime);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff8151eb80)
Location: include/trace/events/iocost.h:14
Inline: False
```
**Symbols:**

```
ffffffff8151eb80-ffffffff8151edec: trace_event_raw_event_iocost_iocg_activate (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
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
