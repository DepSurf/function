# Function: <code>__traceiter_leases_conflict</code>

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
int __traceiter_leases_conflict(void *__data, bool conflict, struct file_lock *lease, struct file_lock *breaker);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff813aa180)
Location: include/trace/events/filelock.h:206
Inline: False
```
**Symbols:**

```
ffffffff813aa180-ffffffff813aa1d2: __traceiter_leases_conflict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __traceiter_leases_conflict(void *__data, bool conflict, struct file_lock *lease, struct file_lock *breaker);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff813b1650)
Location: include/trace/events/filelock.h:206
Inline: False
```
**Symbols:**

```
ffffffff813b1650-ffffffff813b16a0: __traceiter_leases_conflict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __traceiter_leases_conflict(void *__data, bool conflict, struct file_lock *lease, struct file_lock *breaker);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81401340)
Location: include/trace/events/filelock.h:206
Inline: False
```
**Symbols:**

```
ffffffff81401340-ffffffff81401390: __traceiter_leases_conflict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __traceiter_leases_conflict(void *__data, bool conflict, struct file_lock *lease, struct file_lock *breaker);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff814754e0)
Location: include/trace/events/filelock.h:206
Inline: False
```
**Symbols:**

```
ffffffff814754e0-ffffffff8147553c: __traceiter_leases_conflict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __traceiter_leases_conflict(void *__data, bool conflict, struct file_lock *lease, struct file_lock *breaker);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81507980)
Location: include/trace/events/filelock.h:206
Inline: False
```
**Symbols:**

```
ffffffff81507980-ffffffff815079dc: __traceiter_leases_conflict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __traceiter_leases_conflict(void *__data, bool conflict, struct file_lock *lease, struct file_lock *breaker);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8153efd0)
Location: include/trace/events/filelock.h:206
Inline: False
```
**Symbols:**

```
ffffffff8153efd0-ffffffff8153f02c: __traceiter_leases_conflict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __traceiter_leases_conflict(void *__data, bool conflict, struct file_lock *lease, struct file_lock *breaker);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff815744b0)
Location: include/trace/events/filelock.h:206
Inline: False
```
**Symbols:**

```
ffffffff815744b0-ffffffff8157450c: __traceiter_leases_conflict (STB_GLOBAL)
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
