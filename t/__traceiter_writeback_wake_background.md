# Function: <code>__traceiter_writeback_wake_background</code>

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
int __traceiter_writeback_wake_background(void *__data, struct bdi_writeback *wb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff813536f0)
Location: include/trace/events/writeback.h:427
Inline: False
```
**Symbols:**

```
ffffffff813536f0-ffffffff8135372d: __traceiter_writeback_wake_background (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __traceiter_writeback_wake_background(void *__data, struct bdi_writeback *wb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff8135a3c0)
Location: include/trace/events/writeback.h:427
Inline: False
```
**Symbols:**

```
ffffffff8135a3c0-ffffffff8135a3fb: __traceiter_writeback_wake_background (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __traceiter_writeback_wake_background(void *__data, struct bdi_writeback *wb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff813a8860)
Location: include/trace/events/writeback.h:428
Inline: False
```
**Symbols:**

```
ffffffff813a8860-ffffffff813a889b: __traceiter_writeback_wake_background (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __traceiter_writeback_wake_background(void *__data, struct bdi_writeback *wb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff8142d1c0)
Location: include/trace/events/writeback.h:428
Inline: False
```
**Symbols:**

```
ffffffff8142d1c0-ffffffff8142d203: __traceiter_writeback_wake_background (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __traceiter_writeback_wake_background(void *__data, struct bdi_writeback *wb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff814baa50)
Location: include/trace/events/writeback.h:428
Inline: False
```
**Symbols:**

```
ffffffff814baa50-ffffffff814baa93: __traceiter_writeback_wake_background (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __traceiter_writeback_wake_background(void *__data, struct bdi_writeback *wb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff814efab0)
Location: include/trace/events/writeback.h:428
Inline: False
```
**Symbols:**

```
ffffffff814efab0-ffffffff814efaf3: __traceiter_writeback_wake_background (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __traceiter_writeback_wake_background(void *__data, struct bdi_writeback *wb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff815241c0)
Location: include/trace/events/writeback.h:428
Inline: False
```
**Symbols:**

```
ffffffff815241c0-ffffffff81524203: __traceiter_writeback_wake_background (STB_GLOBAL)
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
