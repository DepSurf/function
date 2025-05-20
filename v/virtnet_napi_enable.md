# Function: <code>virtnet_napi_enable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void virtnet_napi_enable(struct receive_queue *rq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/virtio_net.c (ffffffff815f1930)
Location: drivers/net/virtio_net.c:696
Inline: True
Direct callers:
  - drivers/net/virtio_net.c:refill_work
  - drivers/net/virtio_net.c:virtnet_open
  - drivers/net/virtio_net.c:virtnet_restore
```
**Symbols:**

```
ffffffff815f1930-ffffffff815f1992: virtnet_napi_enable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void virtnet_napi_enable(struct receive_queue *rq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/virtio_net.c (ffffffff81651240)
Location: drivers/net/virtio_net.c:668
Inline: True
Direct callers:
  - drivers/net/virtio_net.c:virtnet_restore
  - drivers/net/virtio_net.c:virtnet_open
  - drivers/net/virtio_net.c:refill_work
```
**Symbols:**

```
ffffffff81651240-ffffffff816512a1: virtnet_napi_enable (STB_LOCAL)
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
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/virtio_net.c (ffffffff81c4fdae)
Location: drivers/net/virtio_net.c:1815
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_xdp_set
  - drivers/net/virtio_net.c:virtnet_xdp_set
  - drivers/net/virtio_net.c:virtnet_xdp_set
  - drivers/net/virtio_net.c:virtnet_xdp_set
  - drivers/net/virtio_net.c:virtnet_set_ringparam
  - drivers/net/virtio_net.c:virtnet_set_ringparam
  - drivers/net/virtio_net.c:virtnet_open
  - drivers/net/virtio_net.c:virtnet_open
  - drivers/net/virtio_net.c:refill_work
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
In drivers/net/virtio_net.c (ffffffff81d065ac)
Location: drivers/net/virtio_net.c:2036
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_xdp_set
  - drivers/net/virtio_net.c:virtnet_xdp_set
  - drivers/net/virtio_net.c:virtnet_xdp_set
  - drivers/net/virtio_net.c:virtnet_xdp_set
  - drivers/net/virtio_net.c:virtnet_set_ringparam
  - drivers/net/virtio_net.c:virtnet_set_ringparam
  - drivers/net/virtio_net.c:virtnet_open
  - drivers/net/virtio_net.c:virtnet_open
  - drivers/net/virtio_net.c:refill_work
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
</ul>
