# Function: <code>evtchn_fifo_percpu_init</code>

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
int evtchn_fifo_percpu_init(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_fifo.c (ffffffff81736890)
Location: drivers/xen/events/events_fifo.c:399
Inline: False
```
**Symbols:**

```
ffffffff81736890-ffffffff817368bf: evtchn_fifo_percpu_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int evtchn_fifo_percpu_init(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_fifo.c (ffffffff8171a2e0)
Location: drivers/xen/events/events_fifo.c:399
Inline: False
```
**Symbols:**

```
ffffffff8171a2e0-ffffffff8171a30b: evtchn_fifo_percpu_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int evtchn_fifo_percpu_init(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_fifo.c (ffffffff81798970)
Location: drivers/xen/events/events_fifo.c:399
Inline: False
```
**Symbols:**

```
ffffffff81798970-ffffffff817989c7: evtchn_fifo_percpu_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int evtchn_fifo_percpu_init(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_fifo.c (ffffffff818d1d30)
Location: drivers/xen/events/events_fifo.c:399
Inline: False
```
**Symbols:**

```
ffffffff818d1d30-ffffffff818d1d90: evtchn_fifo_percpu_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int evtchn_fifo_percpu_init(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_fifo.c (ffffffff81a23a70)
Location: drivers/xen/events/events_fifo.c:399
Inline: False
```
**Symbols:**

```
ffffffff81a23a70-ffffffff81a23ad0: evtchn_fifo_percpu_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int evtchn_fifo_percpu_init(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_fifo.c (ffffffff81a6cf30)
Location: drivers/xen/events/events_fifo.c:399
Inline: False
```
**Symbols:**

```
ffffffff81a6cf30-ffffffff81a6cf90: evtchn_fifo_percpu_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int evtchn_fifo_percpu_init(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_fifo.c (ffffffff81abf000)
Location: drivers/xen/events/events_fifo.c:397
Inline: False
```
**Symbols:**

```
ffffffff81abf000-ffffffff81abf060: evtchn_fifo_percpu_init (STB_LOCAL)
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
