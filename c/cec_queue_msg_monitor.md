# Function: <code>cec_queue_msg_monitor</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void cec_queue_msg_monitor(struct cec_adapter *adap, const struct cec_msg *msg, bool valid_la);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffffffff81804250)
Location: drivers/media/cec/cec-adap.c:268
Inline: False
Direct callers:
  - drivers/media/cec/cec-adap.c:cec_received_msg_ts
  - drivers/media/cec/cec-adap.c:cec_received_msg_ts
  - drivers/media/cec/cec-adap.c:cec_received_msg_ts
  - drivers/media/cec/cec-adap.c:cec_transmit_done_ts
  - drivers/media/cec/cec-adap.c:cec_transmit_done_ts
  - drivers/media/cec/cec-adap.c:cec_data_cancel
```
**Symbols:**

```
ffffffff81804250-ffffffff818042d1: cec_queue_msg_monitor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void cec_queue_msg_monitor(struct cec_adapter *adap, const struct cec_msg *msg, bool valid_la);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffffffff81845890)
Location: drivers/media/cec/cec-adap.c:281
Inline: False
Direct callers:
  - drivers/media/cec/cec-adap.c:cec_received_msg_ts
  - drivers/media/cec/cec-adap.c:cec_received_msg_ts
  - drivers/media/cec/cec-adap.c:cec_received_msg_ts
  - drivers/media/cec/cec-adap.c:cec_received_msg_ts
  - drivers/media/cec/cec-adap.c:cec_received_msg_ts
  - drivers/media/cec/cec-adap.c:cec_received_msg_ts
  - drivers/media/cec/cec-adap.c:cec_received_msg_ts
  - drivers/media/cec/cec-adap.c:cec_received_msg_ts
  - drivers/media/cec/cec-adap.c:cec_received_msg_ts
  - drivers/media/cec/cec-adap.c:cec_transmit_done_ts
  - drivers/media/cec/cec-adap.c:cec_transmit_done_ts
  - drivers/media/cec/cec-adap.c:cec_data_cancel
```
**Symbols:**

```
ffffffff81845890-ffffffff81845911: cec_queue_msg_monitor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void cec_queue_msg_monitor(struct cec_adapter *adap, const struct cec_msg *msg, bool valid_la);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffffffff81877180)
Location: drivers/media/cec/cec-adap.c:281
Inline: False
Direct callers:
  - drivers/media/cec/cec-adap.c:cec_received_msg_ts
  - drivers/media/cec/cec-adap.c:cec_received_msg_ts
  - drivers/media/cec/cec-adap.c:cec_received_msg_ts
  - drivers/media/cec/cec-adap.c:cec_transmit_done_ts
  - drivers/media/cec/cec-adap.c:cec_transmit_done_ts
  - drivers/media/cec/cec-adap.c:cec_data_cancel
```
**Symbols:**

```
ffffffff81877180-ffffffff81877201: cec_queue_msg_monitor (STB_LOCAL)
```
</details>
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
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void cec_queue_msg_monitor(struct cec_adapter *adap, const struct cec_msg *msg, bool valid_la);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffff800010abeb28)
Location: drivers/media/cec/cec-adap.c:281
Inline: False
Direct callers:
  - drivers/media/cec/cec-adap.c:cec_received_msg_ts
  - drivers/media/cec/cec-adap.c:cec_received_msg_ts
  - drivers/media/cec/cec-adap.c:cec_received_msg_ts
  - drivers/media/cec/cec-adap.c:cec_transmit_done_ts
  - drivers/media/cec/cec-adap.c:cec_transmit_done_ts
  - drivers/media/cec/cec-adap.c:cec_data_cancel
```
**Symbols:**

```
ffff800010abeb28-ffff800010abebcc: cec_queue_msg_monitor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void cec_queue_msg_monitor(struct cec_adapter *adap, const struct cec_msg *msg, bool valid_la);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (c0ba0828)
Location: drivers/media/cec/cec-adap.c:281
Inline: False
Direct callers:
  - drivers/media/cec/cec-adap.c:cec_received_msg_ts
  - drivers/media/cec/cec-adap.c:cec_received_msg_ts
  - drivers/media/cec/cec-adap.c:cec_received_msg_ts
  - drivers/media/cec/cec-adap.c:cec_transmit_done_ts
  - drivers/media/cec/cec-adap.c:cec_transmit_done_ts
  - drivers/media/cec/cec-adap.c:cec_data_cancel
```
**Symbols:**

```
c0ba0828-c0ba08a8: cec_queue_msg_monitor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void cec_queue_msg_monitor(struct cec_adapter *adap, const struct cec_msg *msg, bool valid_la);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (c000000000ba0310)
Location: drivers/media/cec/cec-adap.c:281
Inline: False
Direct callers:
  - drivers/media/cec/cec-adap.c:cec_received_msg_ts
  - drivers/media/cec/cec-adap.c:cec_received_msg_ts
  - drivers/media/cec/cec-adap.c:cec_transmit_done_ts
  - drivers/media/cec/cec-adap.c:cec_transmit_done_ts
  - drivers/media/cec/cec-adap.c:cec_data_cancel
  - drivers/media/cec/cec-adap.c:cec_data_cancel
```
**Symbols:**

```
c000000000ba0310-c000000000ba03e0: cec_queue_msg_monitor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void cec_queue_msg_monitor(struct cec_adapter *adap, const struct cec_msg *msg, bool valid_la);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffffffe0006c0638)
Location: drivers/media/cec/cec-adap.c:281
Inline: False
Direct callers:
  - drivers/media/cec/cec-adap.c:cec_received_msg_ts
  - drivers/media/cec/cec-adap.c:cec_received_msg_ts
  - drivers/media/cec/cec-adap.c:cec_received_msg_ts
  - drivers/media/cec/cec-adap.c:cec_transmit_done_ts
  - drivers/media/cec/cec-adap.c:cec_transmit_done_ts
  - drivers/media/cec/cec-adap.c:cec_data_cancel
```
**Symbols:**

```
ffffffe0006c0638-ffffffe0006c06bc: cec_queue_msg_monitor (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void cec_queue_msg_monitor(struct cec_adapter *adap, const struct cec_msg *msg, bool valid_la);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffffffff8181f6f0)
Location: drivers/media/cec/cec-adap.c:281
Inline: False
Direct callers:
  - drivers/media/cec/cec-adap.c:cec_received_msg_ts
  - drivers/media/cec/cec-adap.c:cec_received_msg_ts
  - drivers/media/cec/cec-adap.c:cec_received_msg_ts
  - drivers/media/cec/cec-adap.c:cec_transmit_done_ts
  - drivers/media/cec/cec-adap.c:cec_transmit_done_ts
  - drivers/media/cec/cec-adap.c:cec_data_cancel
```
**Symbols:**

```
ffffffff8181f6f0-ffffffff8181f771: cec_queue_msg_monitor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void cec_queue_msg_monitor(struct cec_adapter *adap, const struct cec_msg *msg, bool valid_la);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffffffff817e6d90)
Location: drivers/media/cec/cec-adap.c:281
Inline: False
Direct callers:
  - drivers/media/cec/cec-adap.c:cec_received_msg_ts
  - drivers/media/cec/cec-adap.c:cec_received_msg_ts
  - drivers/media/cec/cec-adap.c:cec_received_msg_ts
  - drivers/media/cec/cec-adap.c:cec_transmit_done_ts
  - drivers/media/cec/cec-adap.c:cec_transmit_done_ts
  - drivers/media/cec/cec-adap.c:cec_data_cancel
```
**Symbols:**

```
ffffffff817e6d90-ffffffff817e6e11: cec_queue_msg_monitor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void cec_queue_msg_monitor(struct cec_adapter *adap, const struct cec_msg *msg, bool valid_la);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffffffff8186c630)
Location: drivers/media/cec/cec-adap.c:281
Inline: False
Direct callers:
  - drivers/media/cec/cec-adap.c:cec_received_msg_ts
  - drivers/media/cec/cec-adap.c:cec_received_msg_ts
  - drivers/media/cec/cec-adap.c:cec_received_msg_ts
  - drivers/media/cec/cec-adap.c:cec_transmit_done_ts
  - drivers/media/cec/cec-adap.c:cec_transmit_done_ts
  - drivers/media/cec/cec-adap.c:cec_data_cancel
```
**Symbols:**

```
ffffffff8186c630-ffffffff8186c6b1: cec_queue_msg_monitor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void cec_queue_msg_monitor(struct cec_adapter *adap, const struct cec_msg *msg, bool valid_la);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffffffff818865c0)
Location: drivers/media/cec/cec-adap.c:281
Inline: False
Direct callers:
  - drivers/media/cec/cec-adap.c:cec_received_msg_ts
  - drivers/media/cec/cec-adap.c:cec_received_msg_ts
  - drivers/media/cec/cec-adap.c:cec_received_msg_ts
  - drivers/media/cec/cec-adap.c:cec_transmit_done_ts
  - drivers/media/cec/cec-adap.c:cec_transmit_done_ts
  - drivers/media/cec/cec-adap.c:cec_data_cancel
```
**Symbols:**

```
ffffffff818865c0-ffffffff81886641: cec_queue_msg_monitor (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
