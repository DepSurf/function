# Function: <code>__traceiter_rtc_read_alarm</code>

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
int __traceiter_rtc_read_alarm(void *__data, time64_t secs, int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff8193f550)
Location: include/trace/events/rtc.h:52
Inline: False
```
**Symbols:**

```
ffffffff8193f550-ffffffff8193f597: __traceiter_rtc_read_alarm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __traceiter_rtc_read_alarm(void *__data, time64_t secs, int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff81922cf0)
Location: include/trace/events/rtc.h:52
Inline: False
```
**Symbols:**

```
ffffffff81922cf0-ffffffff81922d35: __traceiter_rtc_read_alarm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __traceiter_rtc_read_alarm(void *__data, time64_t secs, int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff819c5ca0)
Location: include/trace/events/rtc.h:52
Inline: False
```
**Symbols:**

```
ffffffff819c5ca0-ffffffff819c5ce5: __traceiter_rtc_read_alarm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __traceiter_rtc_read_alarm(void *__data, time64_t secs, int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff81b264e0)
Location: include/trace/events/rtc.h:52
Inline: False
```
**Symbols:**

```
ffffffff81b264e0-ffffffff81b2652f: __traceiter_rtc_read_alarm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __traceiter_rtc_read_alarm(void *__data, time64_t secs, int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff81cb9ca0)
Location: include/trace/events/rtc.h:52
Inline: False
```
**Symbols:**

```
ffffffff81cb9ca0-ffffffff81cb9cef: __traceiter_rtc_read_alarm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __traceiter_rtc_read_alarm(void *__data, time64_t secs, int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff81d213f0)
Location: include/trace/events/rtc.h:52
Inline: False
```
**Symbols:**

```
ffffffff81d213f0-ffffffff81d2143f: __traceiter_rtc_read_alarm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __traceiter_rtc_read_alarm(void *__data, time64_t secs, int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff81dd7150)
Location: include/trace/events/rtc.h:52
Inline: False
```
**Symbols:**

```
ffffffff81dd7150-ffffffff81dd719f: __traceiter_rtc_read_alarm (STB_GLOBAL)
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
