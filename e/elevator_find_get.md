# Function: <code>elevator_find_get</code>

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
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct elevator_type *elevator_find_get(struct request_queue *q, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff81730510)
Location: block/elevator.c:116
Inline: False
Direct callers:
  - block/elevator.c:elv_iosched_store
  - block/elevator.c:elv_iosched_store
  - block/elevator.c:elevator_init_mq
```
**Symbols:**

```
ffffffff81730510-ffffffff81730584: elevator_find_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct elevator_type *elevator_find_get(struct request_queue *q, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff8176c770)
Location: block/elevator.c:116
Inline: False
Direct callers:
  - block/elevator.c:elv_iosched_store
  - block/elevator.c:elv_iosched_store
  - block/elevator.c:elevator_init_mq
```
**Symbols:**

```
ffffffff8176c770-ffffffff8176c7e4: elevator_find_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct elevator_type *elevator_find_get(struct request_queue *q, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff817ae9a0)
Location: block/elevator.c:116
Inline: False
Direct callers:
  - block/elevator.c:elv_iosched_store
  - block/elevator.c:elv_iosched_store
  - block/elevator.c:elevator_init_mq
```
**Symbols:**

```
ffffffff817ae9a0-ffffffff817aea14: elevator_find_get (STB_LOCAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
