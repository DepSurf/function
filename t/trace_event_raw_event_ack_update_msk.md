# Function: <code>trace_event_raw_event_ack_update_msk</code>

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
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void trace_event_raw_event_ack_update_msk(void *__data, u64 data_ack, u64 old_snd_una, u64 new_snd_una, u64 new_wnd_end, u64 msk_wnd_end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff81bab6b0)
Location: include/trace/events/mptcp.h:117
Inline: False
```
**Symbols:**

```
ffffffff81bab6b0-ffffffff81bab796: trace_event_raw_event_ack_update_msk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void trace_event_raw_event_ack_update_msk(void *__data, u64 data_ack, u64 old_snd_una, u64 new_snd_una, u64 new_wnd_end, u64 msk_wnd_end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff81c780a0)
Location: include/trace/events/mptcp.h:122
Inline: False
```
**Symbols:**

```
ffffffff81c780a0-ffffffff81c78186: trace_event_raw_event_ack_update_msk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void trace_event_raw_event_ack_update_msk(void *__data, u64 data_ack, u64 old_snd_una, u64 new_snd_una, u64 new_wnd_end, u64 msk_wnd_end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff81e1c140)
Location: include/trace/events/mptcp.h:128
Inline: False
```
**Symbols:**

```
ffffffff81e1c140-ffffffff81e1c21b: trace_event_raw_event_ack_update_msk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void trace_event_raw_event_ack_update_msk(void *__data, u64 data_ack, u64 old_snd_una, u64 new_snd_una, u64 new_wnd_end, u64 msk_wnd_end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff81ff37c0)
Location: include/trace/events/mptcp.h:128
Inline: False
```
**Symbols:**

```
ffffffff81ff37c0-ffffffff81ff389b: trace_event_raw_event_ack_update_msk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void trace_event_raw_event_ack_update_msk(void *__data, u64 data_ack, u64 old_snd_una, u64 new_snd_una, u64 new_wnd_end, u64 msk_wnd_end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff8206fb30)
Location: include/trace/events/mptcp.h:128
Inline: False
```
**Symbols:**

```
ffffffff8206fb30-ffffffff8206fc0b: trace_event_raw_event_ack_update_msk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void trace_event_raw_event_ack_update_msk(void *__data, u64 data_ack, u64 old_snd_una, u64 new_snd_una, u64 new_wnd_end, u64 msk_wnd_end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff82143c40)
Location: include/trace/events/mptcp.h:128
Inline: False
```
**Symbols:**

```
ffffffff82143c40-ffffffff82143d1b: trace_event_raw_event_ack_update_msk (STB_LOCAL)
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
