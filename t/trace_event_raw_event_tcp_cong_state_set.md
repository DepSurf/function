# Function: <code>trace_event_raw_event_tcp_cong_state_set</code>

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
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void trace_event_raw_event_tcp_cong_state_set(void *__data, struct sock *sk, const u8 ca_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff81c625b0)
Location: include/trace/events/tcp.h:374
Inline: False
```
**Symbols:**

```
ffffffff81c625b0-ffffffff81c626e3: trace_event_raw_event_tcp_cong_state_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void trace_event_raw_event_tcp_cong_state_set(void *__data, struct sock *sk, const u8 ca_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff81e19340)
Location: include/trace/events/tcp.h:374
Inline: False
```
**Symbols:**

```
ffffffff81e19340-ffffffff81e19473: trace_event_raw_event_tcp_cong_state_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void trace_event_raw_event_tcp_cong_state_set(void *__data, struct sock *sk, const u8 ca_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff81e8d480)
Location: include/trace/events/tcp.h:374
Inline: False
```
**Symbols:**

```
ffffffff81e8d480-ffffffff81e8d5bb: trace_event_raw_event_tcp_cong_state_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void trace_event_raw_event_tcp_cong_state_set(void *__data, struct sock *sk, const u8 ca_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff81f4f490)
Location: include/trace/events/tcp.h:374
Inline: False
```
**Symbols:**

```
ffffffff81f4f490-ffffffff81f4f5cb: trace_event_raw_event_tcp_cong_state_set (STB_LOCAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
