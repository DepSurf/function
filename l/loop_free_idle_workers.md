# Function: <code>loop_free_idle_workers</code>

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
void loop_free_idle_workers(struct timer_list *timer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff8186fad0)
Location: drivers/block/loop.c:2324
Inline: False
```
**Symbols:**

```
ffffffff8186fad0-ffffffff8186fc07: loop_free_idle_workers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void loop_free_idle_workers(struct loop_device *lo, bool delete_all);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff819b68e0)
Location: drivers/block/loop.c:906
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_free_disk
  - drivers/block/loop.c:loop_free_idle_workers_timer
```
**Symbols:**

```
ffffffff819b68e0-ffffffff819b6a54: loop_free_idle_workers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void loop_free_idle_workers(struct loop_device *lo, bool delete_all);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff81b2bb10)
Location: drivers/block/loop.c:906
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_free_disk
  - drivers/block/loop.c:loop_free_idle_workers_timer
```
**Symbols:**

```
ffffffff81b2bb10-ffffffff81b2bc84: loop_free_idle_workers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void loop_free_idle_workers(struct loop_device *lo, bool delete_all);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff81b7be10)
Location: drivers/block/loop.c:906
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_free_disk
  - drivers/block/loop.c:loop_free_idle_workers_timer
```
**Symbols:**

```
ffffffff81b7be10-ffffffff81b7bf84: loop_free_idle_workers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void loop_free_idle_workers(struct loop_device *lo, bool delete_all);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff81bcfe40)
Location: drivers/block/loop.c:902
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_free_disk
  - drivers/block/loop.c:loop_free_idle_workers_timer
```
**Symbols:**

```
ffffffff81bcfe40-ffffffff81bcffb4: loop_free_idle_workers (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct loop_device *lo</code>
</li>
<li>
<b>Param added. </b>
<code>bool delete_all</code>
</li>
<li>
<b>Param removed. </b>
<code>struct timer_list *timer</code>
</li>
</ul>
</details>
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
