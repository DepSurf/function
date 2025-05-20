# Function: <code>__traceiter_locks_get_lock_context</code>

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
int __traceiter_locks_get_lock_context(void *__data, struct inode *inode, int type, struct file_lock_context *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff813a9dc0)
Location: include/trace/events/filelock.h:38
Inline: False
```
**Symbols:**

```
ffffffff813a9dc0-ffffffff813a9e11: __traceiter_locks_get_lock_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __traceiter_locks_get_lock_context(void *__data, struct inode *inode, int type, struct file_lock_context *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff813b12e0)
Location: include/trace/events/filelock.h:38
Inline: False
```
**Symbols:**

```
ffffffff813b12e0-ffffffff813b132f: __traceiter_locks_get_lock_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __traceiter_locks_get_lock_context(void *__data, struct inode *inode, int type, struct file_lock_context *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81400fd0)
Location: include/trace/events/filelock.h:38
Inline: False
```
**Symbols:**

```
ffffffff81400fd0-ffffffff8140101f: __traceiter_locks_get_lock_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __traceiter_locks_get_lock_context(void *__data, struct inode *inode, int type, struct file_lock_context *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81475120)
Location: include/trace/events/filelock.h:38
Inline: False
```
**Symbols:**

```
ffffffff81475120-ffffffff8147517b: __traceiter_locks_get_lock_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __traceiter_locks_get_lock_context(void *__data, struct inode *inode, int type, struct file_lock_context *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81507510)
Location: include/trace/events/filelock.h:38
Inline: False
```
**Symbols:**

```
ffffffff81507510-ffffffff8150756b: __traceiter_locks_get_lock_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __traceiter_locks_get_lock_context(void *__data, struct inode *inode, int type, struct file_lock_context *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8153eb00)
Location: include/trace/events/filelock.h:38
Inline: False
```
**Symbols:**

```
ffffffff8153eb00-ffffffff8153eb5b: __traceiter_locks_get_lock_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __traceiter_locks_get_lock_context(void *__data, struct inode *inode, int type, struct file_lock_context *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81573fe0)
Location: include/trace/events/filelock.h:38
Inline: False
```
**Symbols:**

```
ffffffff81573fe0-ffffffff8157403b: __traceiter_locks_get_lock_context (STB_GLOBAL)
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
