# Function: <code>evtchn_2l_remove</code>

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
void evtchn_2l_remove(evtchn_port_t evtchn, unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_2l.c (ffffffff81736430)
Location: drivers/xen/events/events_2l.c:50
Inline: False
```
**Symbols:**

```
ffffffff81736430-ffffffff81736453: evtchn_2l_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void evtchn_2l_remove(evtchn_port_t evtchn, unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_2l.c (ffffffff81719e70)
Location: drivers/xen/events/events_2l.c:50
Inline: False
```
**Symbols:**

```
ffffffff81719e70-ffffffff81719e93: evtchn_2l_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void evtchn_2l_remove(evtchn_port_t evtchn, unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_2l.c (ffffffff817982b0)
Location: drivers/xen/events/events_2l.c:50
Inline: False
```
**Symbols:**

```
ffffffff817982b0-ffffffff817982f8: evtchn_2l_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void evtchn_2l_remove(evtchn_port_t evtchn, unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_2l.c (ffffffff818d0e20)
Location: drivers/xen/events/events_2l.c:50
Inline: False
```
**Symbols:**

```
ffffffff818d0e20-ffffffff818d0e70: evtchn_2l_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void evtchn_2l_remove(evtchn_port_t evtchn, unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_2l.c (ffffffff81a227a0)
Location: drivers/xen/events/events_2l.c:50
Inline: False
```
**Symbols:**

```
ffffffff81a227a0-ffffffff81a227f0: evtchn_2l_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void evtchn_2l_remove(evtchn_port_t evtchn, unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_2l.c (ffffffff81a6bb30)
Location: drivers/xen/events/events_2l.c:50
Inline: False
```
**Symbols:**

```
ffffffff81a6bb30-ffffffff81a6bb80: evtchn_2l_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void evtchn_2l_remove(evtchn_port_t evtchn, unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_2l.c (ffffffff81abdbd0)
Location: drivers/xen/events/events_2l.c:50
Inline: False
```
**Symbols:**

```
ffffffff81abdbd0-ffffffff81abdc20: evtchn_2l_remove (STB_LOCAL)
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
