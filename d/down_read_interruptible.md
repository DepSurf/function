# Function: <code>down_read_interruptible</code>

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
int down_read_interruptible(struct rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff81c43d60)
Location: kernel/locking/rwsem.c:1359
Inline: False
Direct callers:
  - kernel/events/core.c:__do_sys_perf_event_open
```
**Symbols:**

```
ffffffff81c43d60-ffffffff81c43dfc: down_read_interruptible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int down_read_interruptible(struct rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff81c35bb0)
Location: kernel/locking/rwsem.c:1359
Inline: False
Direct callers:
  - kernel/events/core.c:__do_sys_perf_event_open
```
**Symbols:**

```
ffffffff81c35bb0-ffffffff81c35c4c: down_read_interruptible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int down_read_interruptible(struct rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff81d543b0)
Location: kernel/locking/rwsem.c:1476
Inline: False
Direct callers:
  - kernel/events/core.c:__do_sys_perf_event_open
```
**Symbols:**

```
ffffffff81d543b0-ffffffff81d5444c: down_read_interruptible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int down_read_interruptible(struct rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff81f25580)
Location: kernel/locking/rwsem.c:1505
Inline: False
Direct callers:
  - kernel/events/core.c:__do_sys_perf_event_open
```
**Symbols:**

```
ffffffff81f25580-ffffffff81f2561e: down_read_interruptible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int down_read_interruptible(struct rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff820d0f30)
Location: kernel/locking/rwsem.c:1526
Inline: False
Direct callers:
  - kernel/events/core.c:__do_sys_perf_event_open
```
**Symbols:**

```
ffffffff820d0f30-ffffffff820d0ffc: down_read_interruptible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int down_read_interruptible(struct rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff821551f0)
Location: kernel/locking/rwsem.c:1526
Inline: False
Direct callers:
  - kernel/events/core.c:__do_sys_perf_event_open
```
**Symbols:**

```
ffffffff821551f0-ffffffff821552c2: down_read_interruptible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int down_read_interruptible(struct rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff82238030)
Location: kernel/locking/rwsem.c:1532
Inline: False
Direct callers:
  - kernel/events/core.c:__do_sys_perf_event_open
```
**Symbols:**

```
ffffffff82238030-ffffffff82238102: down_read_interruptible (STB_GLOBAL)
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
