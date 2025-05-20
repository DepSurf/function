# Function: <code>cec_msg_is_broadcast</code>

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
In drivers/media/cec/cec-adap.c (ffffffff81805676)
Location: include/uapi/linux/cec.h:105
Inline: True
Inline callers:
  - drivers/media/cec/cec-adap.c:cec_received_msg_ts
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
In drivers/media/cec/cec-adap.c (ffffffff81846f5d)
Location: include/uapi/linux/cec.h:105
Inline: True
Inline callers:
  - drivers/media/cec/cec-adap.c:cec_receive_notify
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
In drivers/media/cec/cec-adap.c (ffffffff818788ad)
Location: include/uapi/linux/cec.h:105
Inline: True
Inline callers:
  - drivers/media/cec/cec-adap.c:cec_receive_notify
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
In drivers/media/cec/cec-adap.c (ffff800010ac0478)
Location: include/uapi/linux/cec.h:105
Inline: True
Inline callers:
  - drivers/media/cec/cec-adap.c:cec_receive_notify
```
```
In drivers/media/cec/cec-pin.c (0)
Location: include/uapi/linux/cec.h:105
Inline: True
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
In drivers/media/cec/cec-adap.c (c0ba2130)
Location: include/uapi/linux/cec.h:105
Inline: True
Inline callers:
  - drivers/media/cec/cec-adap.c:cec_receive_notify
  - drivers/media/cec/cec-adap.c:cec_received_msg_ts
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
In drivers/media/cec/cec-adap.c (c000000000ba23d0)
Location: include/uapi/linux/cec.h:105
Inline: True
Inline callers:
  - drivers/media/cec/cec-adap.c:cec_receive_notify
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
In drivers/media/cec/cec-adap.c (ffffffe0006c1b3a)
Location: include/uapi/linux/cec.h:105
Inline: True
Inline callers:
  - drivers/media/cec/cec-adap.c:cec_receive_notify
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
In drivers/media/cec/cec-adap.c (ffffffff81820e1d)
Location: include/uapi/linux/cec.h:105
Inline: True
Inline callers:
  - drivers/media/cec/cec-adap.c:cec_receive_notify
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
In drivers/media/cec/cec-adap.c (ffffffff817e84bd)
Location: include/uapi/linux/cec.h:105
Inline: True
Inline callers:
  - drivers/media/cec/cec-adap.c:cec_receive_notify
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
In drivers/media/cec/cec-adap.c (ffffffff8186dd5d)
Location: include/uapi/linux/cec.h:105
Inline: True
Inline callers:
  - drivers/media/cec/cec-adap.c:cec_receive_notify
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
In drivers/media/cec/cec-adap.c (ffffffff81887cdd)
Location: include/uapi/linux/cec.h:105
Inline: True
Inline callers:
  - drivers/media/cec/cec-adap.c:cec_receive_notify
```
```
In drivers/media/cec/cec-pin.c (0)
Location: include/uapi/linux/cec.h:105
Inline: True
```
</details>
</li>
</ul>

## Differences
