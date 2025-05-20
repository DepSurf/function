# Function: <code>__traceiter_writeback_exec</code>

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
int __traceiter_writeback_exec(void *__data, struct bdi_writeback *wb, struct wb_writeback_work *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff81353570)
Location: include/trace/events/writeback.h:389
Inline: False
```
**Symbols:**

```
ffffffff81353570-ffffffff813535b7: __traceiter_writeback_exec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __traceiter_writeback_exec(void *__data, struct bdi_writeback *wb, struct wb_writeback_work *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff8135a240)
Location: include/trace/events/writeback.h:389
Inline: False
```
**Symbols:**

```
ffffffff8135a240-ffffffff8135a285: __traceiter_writeback_exec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __traceiter_writeback_exec(void *__data, struct bdi_writeback *wb, struct wb_writeback_work *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff813a86e0)
Location: include/trace/events/writeback.h:390
Inline: False
```
**Symbols:**

```
ffffffff813a86e0-ffffffff813a8725: __traceiter_writeback_exec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __traceiter_writeback_exec(void *__data, struct bdi_writeback *wb, struct wb_writeback_work *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff8142d030)
Location: include/trace/events/writeback.h:390
Inline: False
```
**Symbols:**

```
ffffffff8142d030-ffffffff8142d07f: __traceiter_writeback_exec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __traceiter_writeback_exec(void *__data, struct bdi_writeback *wb, struct wb_writeback_work *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff814ba870)
Location: include/trace/events/writeback.h:390
Inline: False
```
**Symbols:**

```
ffffffff814ba870-ffffffff814ba8bf: __traceiter_writeback_exec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __traceiter_writeback_exec(void *__data, struct bdi_writeback *wb, struct wb_writeback_work *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff814ef8b0)
Location: include/trace/events/writeback.h:390
Inline: False
```
**Symbols:**

```
ffffffff814ef8b0-ffffffff814ef8ff: __traceiter_writeback_exec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __traceiter_writeback_exec(void *__data, struct bdi_writeback *wb, struct wb_writeback_work *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff81523fc0)
Location: include/trace/events/writeback.h:390
Inline: False
```
**Symbols:**

```
ffffffff81523fc0-ffffffff8152400f: __traceiter_writeback_exec (STB_GLOBAL)
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
