# Function: <code>try_fill_recv</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
bool try_fill_recv(struct virtnet_info *vi, struct receive_queue *rq, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/virtio_net.c (ffffffff815f29f0)
Location: drivers/net/virtio_net.c:661
Inline: False
Direct callers:
  - drivers/net/virtio_net.c:virtnet_receive
  - drivers/net/virtio_net.c:refill_work
  - drivers/net/virtio_net.c:virtnet_open
  - drivers/net/virtio_net.c:virtnet_restore
  - drivers/net/virtio_net.c:virtnet_probe
```
**Symbols:**

```
ffffffff815f29f0-ffffffff815f2ffe: try_fill_recv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool try_fill_recv(struct virtnet_info *vi, struct receive_queue *rq, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/virtio_net.c (ffffffff81652680)
Location: drivers/net/virtio_net.c:633
Inline: False
Direct callers:
  - drivers/net/virtio_net.c:virtnet_restore
  - drivers/net/virtio_net.c:virtnet_open
  - drivers/net/virtio_net.c:virtnet_receive
  - drivers/net/virtio_net.c:refill_work
```
**Symbols:**

```
ffffffff81652680-ffffffff81652d1b: try_fill_recv (STB_LOCAL)
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
bool try_fill_recv(struct virtnet_info *vi, struct receive_queue *rq, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/virtio_net.c (0)
Location: drivers/net/virtio_net.c:1778
Inline: False
Direct callers:
  - drivers/net/virtio_net.c:virtnet_set_ringparam
  - drivers/net/virtio_net.c:virtnet_open
  - drivers/net/virtio_net.c:refill_work
```
**Symbols:**

```
ffffffff81c52520-ffffffff81c529d7: try_fill_recv (STB_LOCAL)
ffffffff8211e9bf-ffffffff8211ea0f: try_fill_recv.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool try_fill_recv(struct virtnet_info *vi, struct receive_queue *rq, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/virtio_net.c (0)
Location: drivers/net/virtio_net.c:1998
Inline: False
Direct callers:
  - drivers/net/virtio_net.c:virtnet_set_ringparam
  - drivers/net/virtio_net.c:virtnet_open
  - drivers/net/virtio_net.c:refill_work
```
**Symbols:**

```
ffffffff81d08950-ffffffff81d08d9a: try_fill_recv (STB_LOCAL)
ffffffff82200134-ffffffff822001ae: try_fill_recv.cold (STB_LOCAL)
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
