# Function: <code>tsk_restore_flags</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff81085ad7)
Location: include/linux/sched.h:2218
Inline: True
Inline callers:
  - kernel/softirq.c:__do_softirq
```
```
In net/core/sock.c (ffffffff81701489)
Location: include/linux/sched.h:2218
Inline: True
```
```
In net/core/dev.c (ffffffff8171ab4f)
Location: include/linux/sched.h:2218
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff818a1cd2)
Location: include/linux/sched.h:2364
Inline: True
Inline callers:
  - kernel/softirq.c:__do_softirq
```
```
In net/core/sock.c (ffffffff81768589)
Location: include/linux/sched.h:2364
Inline: True
```
```
In net/core/dev.c (ffffffff8178305f)
Location: include/linux/sched.h:2364
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff818d7229)
Location: include/linux/sched.h:2456
Inline: True
Inline callers:
  - kernel/softirq.c:__do_softirq
```
```
In net/core/sock.c (ffffffff817955d9)
Location: include/linux/sched.h:2456
Inline: True
```
```
In net/core/dev.c (ffffffff817b08ff)
Location: include/linux/sched.h:2456
Inline: True
```
</details>
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
