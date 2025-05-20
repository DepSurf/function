# Function: <code>dd_queued</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
u32 dd_queued(struct deadline_data *dd, enum dd_prio prio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/mq-deadline.c (ffffffff816003a0)
Location: block/mq-deadline.c:951
Inline: False
Direct callers:
  - block/mq-deadline.c:dd_queued_show
  - block/mq-deadline.c:dd_queued_show
  - block/mq-deadline.c:dd_queued_show
```
**Symbols:**

```
ffffffff816003a0-ffffffff816004bf: dd_queued (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/mq-deadline.c (ffffffff816b2abc)
Location: block/mq-deadline.c:253
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_queued_show
  - block/mq-deadline.c:dd_queued_show
  - block/mq-deadline.c:dd_queued_show
  - block/mq-deadline.c:dd_exit_sched
  - block/mq-deadline.c:dd_dispatch_request
  - block/mq-deadline.c:dd_dispatch_request
  - block/mq-deadline.c:dd_dispatch_request
  - block/mq-deadline.c:dd_dispatch_request
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/mq-deadline.c (ffffffff8177205c)
Location: block/mq-deadline.c:267
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_queued_show
  - block/mq-deadline.c:dd_queued_show
  - block/mq-deadline.c:dd_queued_show
  - block/mq-deadline.c:dd_exit_sched
  - block/mq-deadline.c:dd_dispatch_request
  - block/mq-deadline.c:dd_dispatch_request
  - block/mq-deadline.c:dd_dispatch_request
  - block/mq-deadline.c:dd_dispatch_request
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/mq-deadline.c (ffffffff817b132c)
Location: block/mq-deadline.c:290
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_queued_show
  - block/mq-deadline.c:dd_queued_show
  - block/mq-deadline.c:dd_queued_show
  - block/mq-deadline.c:dd_exit_sched
  - block/mq-deadline.c:dd_dispatch_request
  - block/mq-deadline.c:dd_dispatch_request
  - block/mq-deadline.c:dd_dispatch_request
  - block/mq-deadline.c:dd_dispatch_request
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/mq-deadline.c (ffffffff817f513c)
Location: block/mq-deadline.c:290
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_queued_show
  - block/mq-deadline.c:dd_queued_show
  - block/mq-deadline.c:dd_queued_show
  - block/mq-deadline.c:dd_exit_sched
  - block/mq-deadline.c:dd_dispatch_request
  - block/mq-deadline.c:dd_dispatch_request
  - block/mq-deadline.c:dd_dispatch_request
  - block/mq-deadline.c:dd_dispatch_request
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
</ul>
