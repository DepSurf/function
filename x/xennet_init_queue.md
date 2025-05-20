# Function: <code>xennet_init_queue</code>

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
In drivers/net/xen-netfront.c (ffffffff815fc739)
Location: drivers/net/xen-netfront.c:1603
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:talk_to_netback
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
In drivers/net/xen-netfront.c (ffffffff8165c69f)
Location: drivers/net/xen-netfront.c:1594
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:talk_to_netback
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
In drivers/net/xen-netfront.c (ffffffff8168a4c7)
Location: drivers/net/xen-netfront.c:1601
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_connect
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
In drivers/net/xen-netfront.c (ffffffff8169f78a)
Location: drivers/net/xen-netfront.c:1600
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:talk_to_netback
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
In drivers/net/xen-netfront.c (ffffffff8170a927)
Location: drivers/net/xen-netfront.c:1603
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:talk_to_netback
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
In drivers/net/xen-netfront.c (ffffffff81749413)
Location: drivers/net/xen-netfront.c:1607
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:talk_to_netback
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
In drivers/net/xen-netfront.c (ffffffff8176d163)
Location: drivers/net/xen-netfront.c:1606
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_create_queues
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
In drivers/net/xen-netfront.c (ffffffff817aaf20)
Location: drivers/net/xen-netfront.c:1605
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_create_queues
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
In drivers/net/xen-netfront.c (ffffffff817ce960)
Location: drivers/net/xen-netfront.c:1606
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_create_queues
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int xennet_init_queue(struct netfront_queue *queue);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/xen-netfront.c (0)
Location: drivers/net/xen-netfront.c:1611
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_create_queues
```
**Symbols:**

```
ffffffff81897260-ffffffff818973a6: xennet_init_queue (STB_LOCAL)
ffffffff8189a6c9-ffffffff8189a700: xennet_init_queue.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int xennet_init_queue(struct netfront_queue *queue);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/xen-netfront.c (0)
Location: drivers/net/xen-netfront.c:1843
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_create_queues
```
**Symbols:**

```
ffffffff818a5660-ffffffff818a57a6: xennet_init_queue (STB_LOCAL)
ffffffff81c19c71-ffffffff81c19ca8: xennet_init_queue.cold (STB_LOCAL)
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
In drivers/net/xen-netfront.c (ffffffff81889d46)
Location: drivers/net/xen-netfront.c:1841
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_create_queues
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
In drivers/net/xen-netfront.c (ffffffff8191c866)
Location: drivers/net/xen-netfront.c:2003
Inline: True
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
In drivers/net/xen-netfront.c (ffffffff81a71e25)
Location: drivers/net/xen-netfront.c:2011
Inline: True
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
In drivers/net/xen-netfront.c (ffffffff81c045f5)
Location: drivers/net/xen-netfront.c:2017
Inline: True
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
In drivers/net/xen-netfront.c (ffffffff81c69ced)
Location: drivers/net/xen-netfront.c:2019
Inline: True
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
In drivers/net/xen-netfront.c (ffffffff81d1e69d)
Location: drivers/net/xen-netfront.c:2020
Inline: True
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/xen-netfront.c (ffff800010a07b38)
Location: drivers/net/xen-netfront.c:1606
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_create_queues
```
</details>
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
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/xen-netfront.c (ffffffff81793580)
Location: drivers/net/xen-netfront.c:1640
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_create_queues
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/xen-netfront.c (ffffffff817c37e0)
Location: drivers/net/xen-netfront.c:1606
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_create_queues
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
In drivers/net/xen-netfront.c (ffffffff817ddaa0)
Location: drivers/net/xen-netfront.c:1606
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_create_queues
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
