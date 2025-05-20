# Function: <code>sch_frag_dst_get_mtu</code>

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
unsigned int sch_frag_dst_get_mtu(const struct dst_entry *dst);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_frag.c (ffffffff81a6f330)
Location: net/sched/sch_frag.c:72
Inline: False
```
**Symbols:**

```
ffffffff81a6f330-ffffffff81a6f344: sch_frag_dst_get_mtu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
unsigned int sch_frag_dst_get_mtu(const struct dst_entry *dst);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_frag.c (ffffffff81a57c00)
Location: net/sched/sch_frag.c:72
Inline: False
```
**Symbols:**

```
ffffffff81a57c00-ffffffff81a57c14: sch_frag_dst_get_mtu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
unsigned int sch_frag_dst_get_mtu(const struct dst_entry *dst);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_frag.c (ffffffff81b10ba0)
Location: net/sched/sch_frag.c:73
Inline: False
```
**Symbols:**

```
ffffffff81b10ba0-ffffffff81b10bb4: sch_frag_dst_get_mtu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
unsigned int sch_frag_dst_get_mtu(const struct dst_entry *dst);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_frag.c (ffffffff81c97c60)
Location: net/sched/sch_frag.c:74
Inline: False
```
**Symbols:**

```
ffffffff81c97c60-ffffffff81c97c7a: sch_frag_dst_get_mtu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
unsigned int sch_frag_dst_get_mtu(const struct dst_entry *dst);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_frag.c (ffffffff81e53b80)
Location: net/sched/sch_frag.c:74
Inline: False
```
**Symbols:**

```
ffffffff81e53b80-ffffffff81e53b9a: sch_frag_dst_get_mtu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
unsigned int sch_frag_dst_get_mtu(const struct dst_entry *dst);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_frag.c (ffffffff81eaf3f0)
Location: net/sched/sch_frag.c:74
Inline: False
```
**Symbols:**

```
ffffffff81eaf3f0-ffffffff81eaf40a: sch_frag_dst_get_mtu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
unsigned int sch_frag_dst_get_mtu(const struct dst_entry *dst);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_frag.c (ffffffff81f71e70)
Location: net/sched/sch_frag.c:74
Inline: False
```
**Symbols:**

```
ffffffff81f71e70-ffffffff81f71e87: sch_frag_dst_get_mtu (STB_LOCAL)
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
