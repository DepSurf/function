# Function: <code>trace_event_raw_event_qdisc_create</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void trace_event_raw_event_qdisc_create(void *__data, const struct Qdisc_ops *ops, struct net_device *dev, u32 parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff81a48630)
Location: include/trace/events/qdisc.h:99
Inline: False
```
**Symbols:**

```
ffffffff81a48630-ffffffff81a48790: trace_event_raw_event_qdisc_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void trace_event_raw_event_qdisc_create(void *__data, const struct Qdisc_ops *ops, struct net_device *dev, u32 parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/net-traces.c (0)
Location: include/trace/events/qdisc.h:99
Inline: False
```
**Symbols:**

```
ffffffff81a4d950-ffffffff81a4dc26: trace_event_raw_event_qdisc_create (STB_LOCAL)
ffffffff81c31ddb-ffffffff81c31df3: trace_event_raw_event_qdisc_create.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void trace_event_raw_event_qdisc_create(void *__data, const struct Qdisc_ops *ops, struct net_device *dev, u32 parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/net-traces.c (0)
Location: include/trace/events/qdisc.h:99
Inline: False
```
**Symbols:**

```
ffffffff81a32950-ffffffff81a32c40: trace_event_raw_event_qdisc_create (STB_LOCAL)
ffffffff81c240a4-ffffffff81c240bc: trace_event_raw_event_qdisc_create.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void trace_event_raw_event_qdisc_create(void *__data, const struct Qdisc_ops *ops, struct net_device *dev, u32 parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/net-traces.c (0)
Location: include/trace/events/qdisc.h:127
Inline: False
```
**Symbols:**

```
ffffffff81ae8340-ffffffff81ae8630: trace_event_raw_event_qdisc_create (STB_LOCAL)
ffffffff81d380da-ffffffff81d380f2: trace_event_raw_event_qdisc_create.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void trace_event_raw_event_qdisc_create(void *__data, const struct Qdisc_ops *ops, struct net_device *dev, u32 parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/net-traces.c (0)
Location: include/trace/events/qdisc.h:127
Inline: False
```
**Symbols:**

```
ffffffff81c6b110-ffffffff81c6b409: trace_event_raw_event_qdisc_create (STB_LOCAL)
ffffffff81f04af3-ffffffff81f04b0b: trace_event_raw_event_qdisc_create.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void trace_event_raw_event_qdisc_create(void *__data, const struct Qdisc_ops *ops, struct net_device *dev, u32 parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff81e22b00)
Location: include/trace/events/qdisc.h:127
Inline: False
```
**Symbols:**

```
ffffffff81e22b00-ffffffff81e22e0c: trace_event_raw_event_qdisc_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void trace_event_raw_event_qdisc_create(void *__data, const struct Qdisc_ops *ops, struct net_device *dev, u32 parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff81e98460)
Location: include/trace/events/qdisc.h:127
Inline: False
```
**Symbols:**

```
ffffffff81e98460-ffffffff81e987a9: trace_event_raw_event_qdisc_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void trace_event_raw_event_qdisc_create(void *__data, const struct Qdisc_ops *ops, struct net_device *dev, u32 parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff81f5aad0)
Location: include/trace/events/qdisc.h:127
Inline: False
```
**Symbols:**

```
ffffffff81f5aad0-ffffffff81f5ae26: trace_event_raw_event_qdisc_create (STB_LOCAL)
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
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
