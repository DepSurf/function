# Function: <code>__dma_has_cap</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma/dmaengine.c (ffffffff814bca71)
Location: include/linux/dmaengine.h:1059
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_issue_pending_all
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_chan_get
  - drivers/dma/dmaengine.c:dmaengine_get
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma/dmaengine.c (ffffffff8150d88f)
Location: include/linux/dmaengine.h:1203
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dmaengine_get
  - drivers/dma/dmaengine.c:find_candidate
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_issue_pending_all
  - drivers/dma/dmaengine.c:dma_chan_get
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma/dmaengine.c (ffffffff815399bf)
Location: include/linux/dmaengine.h:1227
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dmaengine_get
  - drivers/dma/dmaengine.c:find_candidate
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_issue_pending_all
  - drivers/dma/dmaengine.c:dma_chan_get
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma/dmaengine.c (ffffffff8154d20f)
Location: include/linux/dmaengine.h:1238
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dmaengine_get
  - drivers/dma/dmaengine.c:find_candidate
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_issue_pending_all
  - drivers/dma/dmaengine.c:dma_chan_get
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma/dmaengine.c (ffffffff815b079f)
Location: include/linux/dmaengine.h:1227
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dmaengine_get
  - drivers/dma/dmaengine.c:find_candidate
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_issue_pending_all
  - drivers/dma/dmaengine.c:dma_chan_get
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma/dmaengine.c (ffffffff815e8bcf)
Location: include/linux/dmaengine.h:1231
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dmaengine_get
  - drivers/dma/dmaengine.c:find_candidate
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_issue_pending_all
  - drivers/dma/dmaengine.c:dma_chan_get
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma/dmaengine.c (ffffffff8160297f)
Location: include/linux/dmaengine.h:1234
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dmaengine_get
  - drivers/dma/dmaengine.c:find_candidate
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_issue_pending_all
  - drivers/dma/dmaengine.c:dma_chan_get
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
In drivers/dma/dmaengine.c (ffffffff8163518f)
Location: include/linux/dmaengine.h:1222
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dmaengine_get
  - drivers/dma/dmaengine.c:find_candidate
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_issue_pending_all
  - drivers/dma/dmaengine.c:dma_chan_get
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
In drivers/dma/dmaengine.c (ffffffff81656eab)
Location: include/linux/dmaengine.h:1224
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dmaengine_get
  - drivers/dma/dmaengine.c:find_candidate
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_issue_pending_all
  - drivers/dma/dmaengine.c:dma_chan_get
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma/dmaengine.c (ffffffff81708195)
Location: include/linux/dmaengine.h:1354
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dmaengine_put
  - drivers/dma/dmaengine.c:dmaengine_get
  - drivers/dma/dmaengine.c:private_candidate
  - drivers/dma/dmaengine.c:dma_issue_pending_all
  - drivers/dma/dmaengine.c:dma_chan_get
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:min_chan
  - drivers/dma/dmaengine.c:min_chan
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma/dmaengine.c (ffffffff817253b5)
Location: include/linux/dmaengine.h:1399
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dmaengine_put
  - drivers/dma/dmaengine.c:dmaengine_get
  - drivers/dma/dmaengine.c:private_candidate
  - drivers/dma/dmaengine.c:dma_issue_pending_all
  - drivers/dma/dmaengine.c:dma_chan_get
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:min_chan
  - drivers/dma/dmaengine.c:min_chan
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma/dmaengine.c (ffffffff81706655)
Location: include/linux/dmaengine.h:1401
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dmaengine_put
  - drivers/dma/dmaengine.c:dmaengine_get
  - drivers/dma/dmaengine.c:private_candidate
  - drivers/dma/dmaengine.c:dma_issue_pending_all
  - drivers/dma/dmaengine.c:dma_chan_get
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:min_chan
  - drivers/dma/dmaengine.c:min_chan
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma/dmaengine.c (ffffffff81781f15)
Location: include/linux/dmaengine.h:1399
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dmaengine_put
  - drivers/dma/dmaengine.c:dmaengine_get
  - drivers/dma/dmaengine.c:private_candidate
  - drivers/dma/dmaengine.c:dma_issue_pending_all
  - drivers/dma/dmaengine.c:dma_chan_get
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:min_chan
  - drivers/dma/dmaengine.c:min_chan
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma/dmaengine.c (ffffffff818b8905)
Location: include/linux/dmaengine.h:1422
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dmaengine_put
  - drivers/dma/dmaengine.c:dmaengine_get
  - drivers/dma/dmaengine.c:private_candidate
  - drivers/dma/dmaengine.c:dma_issue_pending_all
  - drivers/dma/dmaengine.c:dma_chan_get
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_rebalance
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma/dmaengine.c (ffffffff81a05e45)
Location: include/linux/dmaengine.h:1402
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dmaengine_put
  - drivers/dma/dmaengine.c:dmaengine_get
  - drivers/dma/dmaengine.c:private_candidate
  - drivers/dma/dmaengine.c:dma_issue_pending_all
  - drivers/dma/dmaengine.c:dma_chan_get
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_rebalance
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma/dmaengine.c (ffffffff81a4ed05)
Location: include/linux/dmaengine.h:1403
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dmaengine_put
  - drivers/dma/dmaengine.c:dmaengine_get
  - drivers/dma/dmaengine.c:private_candidate
  - drivers/dma/dmaengine.c:dma_issue_pending_all
  - drivers/dma/dmaengine.c:dma_chan_get
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_rebalance
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma/dmaengine.c (ffffffff81a9a9a5)
Location: include/linux/dmaengine.h:1402
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dmaengine_put
  - drivers/dma/dmaengine.c:dmaengine_get
  - drivers/dma/dmaengine.c:private_candidate
  - drivers/dma/dmaengine.c:dma_issue_pending_all
  - drivers/dma/dmaengine.c:dma_chan_get
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_rebalance
```
</details>
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
In drivers/dma/dmaengine.c (ffff8000107fd170)
Location: include/linux/dmaengine.h:1224
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dmaengine_get
  - drivers/dma/dmaengine.c:find_candidate
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_issue_pending_all
  - drivers/dma/dmaengine.c:dma_chan_get
```
```
In drivers/dma/mv_xor.c (ffff80001080766c)
Location: include/linux/dmaengine.h:1224
Inline: True
Inline callers:
  - drivers/dma/mv_xor.c:mv_xor_channel_add
  - drivers/dma/mv_xor.c:mv_xor_channel_add
  - drivers/dma/mv_xor.c:mv_xor_channel_add
  - drivers/dma/mv_xor.c:mv_xor_channel_add
  - drivers/dma/mv_xor.c:mv_xor_channel_add
  - drivers/dma/mv_xor.c:mv_xor_channel_add
  - drivers/dma/mv_xor.c:mv_xor_channel_add
  - drivers/dma/mv_xor.c:mv_xor_channel_add
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma/dmaengine.c (c091e758)
Location: include/linux/dmaengine.h:1224
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dmaengine_get
  - drivers/dma/dmaengine.c:find_candidate
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_issue_pending_all
  - drivers/dma/dmaengine.c:dma_chan_get
```
```
In drivers/dma/mv_xor.c (c0925800)
Location: include/linux/dmaengine.h:1224
Inline: True
Inline callers:
  - drivers/dma/mv_xor.c:mv_xor_channel_add
  - drivers/dma/mv_xor.c:mv_xor_channel_add
  - drivers/dma/mv_xor.c:mv_xor_channel_add
  - drivers/dma/mv_xor.c:mv_xor_channel_add
  - drivers/dma/mv_xor.c:mv_xor_channel_add
  - drivers/dma/mv_xor.c:mv_xor_channel_add
  - drivers/dma/mv_xor.c:mv_xor_channel_add
  - drivers/dma/mv_xor.c:mv_xor_channel_add
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
In drivers/dma/dmaengine.c (c0000000008c830c)
Location: include/linux/dmaengine.h:1224
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dmaengine_put
  - drivers/dma/dmaengine.c:dmaengine_get
  - drivers/dma/dmaengine.c:find_candidate
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_issue_pending_all
  - drivers/dma/dmaengine.c:dma_chan_get
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
In drivers/dma/dmaengine.c (ffffffe000516e12)
Location: include/linux/dmaengine.h:1224
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dmaengine_get
  - drivers/dma/dmaengine.c:find_candidate
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_issue_pending_all
  - drivers/dma/dmaengine.c:dma_chan_get
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
In drivers/dma/dmaengine.c (ffffffff8161cd4b)
Location: include/linux/dmaengine.h:1224
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dmaengine_get
  - drivers/dma/dmaengine.c:find_candidate
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_issue_pending_all
  - drivers/dma/dmaengine.c:dma_chan_get
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
In drivers/dma/dmaengine.c (ffffffff8161143b)
Location: include/linux/dmaengine.h:1224
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dmaengine_get
  - drivers/dma/dmaengine.c:find_candidate
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_issue_pending_all
  - drivers/dma/dmaengine.c:dma_chan_get
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
In drivers/dma/dmaengine.c (ffffffff8164aceb)
Location: include/linux/dmaengine.h:1224
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dmaengine_get
  - drivers/dma/dmaengine.c:find_candidate
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_issue_pending_all
  - drivers/dma/dmaengine.c:dma_chan_get
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma/dmaengine.c (ffffffff8166528b)
Location: include/linux/dmaengine.h:1224
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dmaengine_get
  - drivers/dma/dmaengine.c:find_candidate
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_issue_pending_all
  - drivers/dma/dmaengine.c:dma_chan_get
```
</details>
</li>
</ul>

## Differences
