# Function: <code>mergeable_rx_buffer_size_show</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
ssize_t mergeable_rx_buffer_size_show(struct netdev_rx_queue *queue, struct rx_queue_attribute *attribute, char *buf);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/virtio_net.c (ffffffff815f18b0)
Location: drivers/net/virtio_net.c:1660
Inline: True
```
**Symbols:**

```
ffffffff815f18b0-ffffffff815f192e: mergeable_rx_buffer_size_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
ssize_t mergeable_rx_buffer_size_show(struct netdev_rx_queue *queue, struct rx_queue_attribute *attribute, char *buf);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/virtio_net.c (ffffffff81651030)
Location: drivers/net/virtio_net.c:1662
Inline: True
```
**Symbols:**

```
ffffffff81651030-ffffffff816510ae: mergeable_rx_buffer_size_show (STB_LOCAL)
```
</details>
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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
ssize_t mergeable_rx_buffer_size_show(struct netdev_rx_queue *queue, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/virtio_net.c (0)
Location: drivers/net/virtio_net.c:3892
Inline: False
```
**Symbols:**

```
ffffffff81c4dec0-ffffffff81c4dfd4: mergeable_rx_buffer_size_show (STB_LOCAL)
ffffffff8211e71c-ffffffff8211e737: mergeable_rx_buffer_size_show.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
ssize_t mergeable_rx_buffer_size_show(struct netdev_rx_queue *queue, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/virtio_net.c (0)
Location: drivers/net/virtio_net.c:4455
Inline: False
```
**Symbols:**

```
ffffffff81d03f30-ffffffff81d0403e: mergeable_rx_buffer_size_show (STB_LOCAL)
ffffffff821ffe27-ffffffff821ffe42: mergeable_rx_buffer_size_show.cold (STB_LOCAL)
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
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
