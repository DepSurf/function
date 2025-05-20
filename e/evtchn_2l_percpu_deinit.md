# Function: <code>evtchn_2l_percpu_deinit</code>

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
int evtchn_2l_percpu_deinit(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_2l.c (ffffffff817360a0)
Location: drivers/xen/events/events_2l.c:357
Inline: False
```
**Symbols:**

```
ffffffff817360a0-ffffffff817360e7: evtchn_2l_percpu_deinit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int evtchn_2l_percpu_deinit(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_2l.c (ffffffff81719b30)
Location: drivers/xen/events/events_2l.c:357
Inline: False
```
**Symbols:**

```
ffffffff81719b30-ffffffff81719b77: evtchn_2l_percpu_deinit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int evtchn_2l_percpu_deinit(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_2l.c (ffffffff81797d50)
Location: drivers/xen/events/events_2l.c:357
Inline: False
```
**Symbols:**

```
ffffffff81797d50-ffffffff81797dc1: evtchn_2l_percpu_deinit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int evtchn_2l_percpu_deinit(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_2l.c (ffffffff818d0f30)
Location: drivers/xen/events/events_2l.c:357
Inline: False
```
**Symbols:**

```
ffffffff818d0f30-ffffffff818d0fab: evtchn_2l_percpu_deinit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int evtchn_2l_percpu_deinit(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_2l.c (ffffffff81a228e0)
Location: drivers/xen/events/events_2l.c:357
Inline: False
```
**Symbols:**

```
ffffffff81a228e0-ffffffff81a2295b: evtchn_2l_percpu_deinit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int evtchn_2l_percpu_deinit(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_2l.c (ffffffff81a6bc70)
Location: drivers/xen/events/events_2l.c:357
Inline: False
```
**Symbols:**

```
ffffffff81a6bc70-ffffffff81a6bceb: evtchn_2l_percpu_deinit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int evtchn_2l_percpu_deinit(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_2l.c (ffffffff81abdd10)
Location: drivers/xen/events/events_2l.c:357
Inline: False
```
**Symbols:**

```
ffffffff81abdd10-ffffffff81abdd8b: evtchn_2l_percpu_deinit (STB_LOCAL)
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
