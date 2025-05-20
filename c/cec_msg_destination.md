# Function: <code>cec_msg_destination</code>

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
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffffffff818053b7)
Location: include/uapi/linux/cec.h:87
Inline: True
Inline callers:
  - drivers/media/cec/cec-adap.c:cec_feature_abort_reason
  - drivers/media/cec/cec-adap.c:cec_received_msg_ts
  - drivers/media/cec/cec-adap.c:cec_received_msg_ts
  - drivers/media/cec/cec-adap.c:cec_received_msg_ts
  - drivers/media/cec/cec-adap.c:cec_transmit_msg_fh
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffffffff8184705b)
Location: include/uapi/linux/cec.h:87
Inline: True
Inline callers:
  - drivers/media/cec/cec-adap.c:cec_receive_notify
  - drivers/media/cec/cec-adap.c:cec_feature_abort_reason
  - drivers/media/cec/cec-adap.c:cec_received_msg_ts
  - drivers/media/cec/cec-adap.c:cec_received_msg_ts
  - drivers/media/cec/cec-adap.c:cec_transmit_msg_fh
  - drivers/media/cec/cec-adap.c:cec_transmit_msg_fh
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffffffff818789ab)
Location: include/uapi/linux/cec.h:87
Inline: True
Inline callers:
  - drivers/media/cec/cec-adap.c:cec_receive_notify
  - drivers/media/cec/cec-adap.c:cec_feature_abort_reason
  - drivers/media/cec/cec-adap.c:cec_received_msg_ts
  - drivers/media/cec/cec-adap.c:cec_received_msg_ts
  - drivers/media/cec/cec-adap.c:cec_transmit_msg_fh
  - drivers/media/cec/cec-adap.c:cec_transmit_msg_fh
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
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffff800010ac0570)
Location: include/uapi/linux/cec.h:87
Inline: True
Inline callers:
  - drivers/media/cec/cec-adap.c:cec_receive_notify
  - drivers/media/cec/cec-adap.c:cec_feature_abort_reason
  - drivers/media/cec/cec-adap.c:cec_received_msg_ts
  - drivers/media/cec/cec-adap.c:cec_received_msg_ts
  - drivers/media/cec/cec-adap.c:cec_transmit_msg_fh
  - drivers/media/cec/cec-adap.c:cec_transmit_msg_fh
```
```
In drivers/media/cec/cec-pin.c (ffff800010ac5348)
Location: include/uapi/linux/cec.h:87
Inline: True
Inline callers:
  - drivers/media/cec/cec-pin.c:cec_pin_timer
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (c0ba22d8)
Location: include/uapi/linux/cec.h:87
Inline: True
Inline callers:
  - drivers/media/cec/cec-adap.c:cec_receive_notify
  - drivers/media/cec/cec-adap.c:cec_feature_abort_reason
  - drivers/media/cec/cec-adap.c:cec_received_msg_ts
  - drivers/media/cec/cec-adap.c:cec_received_msg_ts
  - drivers/media/cec/cec-adap.c:cec_transmit_msg_fh
  - drivers/media/cec/cec-adap.c:cec_transmit_msg_fh
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (c000000000ba2650)
Location: include/uapi/linux/cec.h:87
Inline: True
Inline callers:
  - drivers/media/cec/cec-adap.c:cec_receive_notify
  - drivers/media/cec/cec-adap.c:cec_feature_abort_reason
  - drivers/media/cec/cec-adap.c:cec_received_msg_ts
  - drivers/media/cec/cec-adap.c:cec_received_msg_ts
  - drivers/media/cec/cec-adap.c:cec_transmit_msg_fh
  - drivers/media/cec/cec-adap.c:cec_transmit_msg_fh
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffffffe0006c1c12)
Location: include/uapi/linux/cec.h:87
Inline: True
Inline callers:
  - drivers/media/cec/cec-adap.c:cec_receive_notify
  - drivers/media/cec/cec-adap.c:cec_feature_abort_reason
  - drivers/media/cec/cec-adap.c:cec_received_msg_ts
  - drivers/media/cec/cec-adap.c:cec_received_msg_ts
  - drivers/media/cec/cec-adap.c:cec_transmit_msg_fh
  - drivers/media/cec/cec-adap.c:cec_transmit_msg_fh
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffffffff81820f1b)
Location: include/uapi/linux/cec.h:87
Inline: True
Inline callers:
  - drivers/media/cec/cec-adap.c:cec_receive_notify
  - drivers/media/cec/cec-adap.c:cec_feature_abort_reason
  - drivers/media/cec/cec-adap.c:cec_received_msg_ts
  - drivers/media/cec/cec-adap.c:cec_received_msg_ts
  - drivers/media/cec/cec-adap.c:cec_transmit_msg_fh
  - drivers/media/cec/cec-adap.c:cec_transmit_msg_fh
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffffffff817e85bb)
Location: include/uapi/linux/cec.h:87
Inline: True
Inline callers:
  - drivers/media/cec/cec-adap.c:cec_receive_notify
  - drivers/media/cec/cec-adap.c:cec_feature_abort_reason
  - drivers/media/cec/cec-adap.c:cec_received_msg_ts
  - drivers/media/cec/cec-adap.c:cec_received_msg_ts
  - drivers/media/cec/cec-adap.c:cec_transmit_msg_fh
  - drivers/media/cec/cec-adap.c:cec_transmit_msg_fh
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffffffff8186de5b)
Location: include/uapi/linux/cec.h:87
Inline: True
Inline callers:
  - drivers/media/cec/cec-adap.c:cec_receive_notify
  - drivers/media/cec/cec-adap.c:cec_feature_abort_reason
  - drivers/media/cec/cec-adap.c:cec_received_msg_ts
  - drivers/media/cec/cec-adap.c:cec_received_msg_ts
  - drivers/media/cec/cec-adap.c:cec_transmit_msg_fh
  - drivers/media/cec/cec-adap.c:cec_transmit_msg_fh
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffffffff81887ddb)
Location: include/uapi/linux/cec.h:87
Inline: True
Inline callers:
  - drivers/media/cec/cec-adap.c:cec_receive_notify
  - drivers/media/cec/cec-adap.c:cec_feature_abort_reason
  - drivers/media/cec/cec-adap.c:cec_received_msg_ts
  - drivers/media/cec/cec-adap.c:cec_received_msg_ts
  - drivers/media/cec/cec-adap.c:cec_transmit_msg_fh
  - drivers/media/cec/cec-adap.c:cec_transmit_msg_fh
```
```
In drivers/media/cec/cec-pin.c (ffffffff8188d094)
Location: include/uapi/linux/cec.h:87
Inline: True
Inline callers:
  - drivers/media/cec/cec-pin.c:cec_pin_timer
```
</details>
</li>
</ul>

## Differences
