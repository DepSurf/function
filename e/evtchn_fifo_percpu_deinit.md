# Function: <code>evtchn_fifo_percpu_deinit</code>

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
int evtchn_fifo_percpu_deinit(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_fifo.c (ffffffff81736db0)
Location: drivers/xen/events/events_fifo.c:406
Inline: False
```
**Symbols:**

```
ffffffff81736db0-ffffffff81736dc4: evtchn_fifo_percpu_deinit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int evtchn_fifo_percpu_deinit(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_fifo.c (ffffffff8171a7e0)
Location: drivers/xen/events/events_fifo.c:406
Inline: False
```
**Symbols:**

```
ffffffff8171a7e0-ffffffff8171a7f4: evtchn_fifo_percpu_deinit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int evtchn_fifo_percpu_deinit(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_fifo.c (ffffffff81799030)
Location: drivers/xen/events/events_fifo.c:406
Inline: False
```
**Symbols:**

```
ffffffff81799030-ffffffff81799044: evtchn_fifo_percpu_deinit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int evtchn_fifo_percpu_deinit(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_fifo.c (ffffffff818d22c0)
Location: drivers/xen/events/events_fifo.c:406
Inline: False
```
**Symbols:**

```
ffffffff818d22c0-ffffffff818d22dc: evtchn_fifo_percpu_deinit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int evtchn_fifo_percpu_deinit(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_fifo.c (ffffffff81a23db0)
Location: drivers/xen/events/events_fifo.c:406
Inline: False
```
**Symbols:**

```
ffffffff81a23db0-ffffffff81a23dcc: evtchn_fifo_percpu_deinit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int evtchn_fifo_percpu_deinit(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_fifo.c (ffffffff81a6d2e0)
Location: drivers/xen/events/events_fifo.c:406
Inline: False
```
**Symbols:**

```
ffffffff81a6d2e0-ffffffff81a6d2fc: evtchn_fifo_percpu_deinit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int evtchn_fifo_percpu_deinit(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_fifo.c (ffffffff81abf350)
Location: drivers/xen/events/events_fifo.c:404
Inline: False
```
**Symbols:**

```
ffffffff81abf350-ffffffff81abf36c: evtchn_fifo_percpu_deinit (STB_LOCAL)
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
