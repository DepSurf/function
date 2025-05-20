# Function: <code>virtnet_set_affinity</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void virtnet_set_affinity(struct virtnet_info *vi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/virtio_net.c (ffffffff815f1690)
Location: drivers/net/virtio_net.c:1267
Inline: False
Direct callers:
  - drivers/net/virtio_net.c:virtnet_cpu_callback
  - drivers/net/virtio_net.c:virtnet_set_channels
```
**Symbols:**

```
ffffffff815f1690-ffffffff815f17bc: virtnet_set_affinity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void virtnet_set_affinity(struct virtnet_info *vi);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/virtio_net.c (ffffffff816510b0)
Location: drivers/net/virtio_net.c:1214
Inline: True
Direct callers:
  - drivers/net/virtio_net.c:virtnet_set_channels
  - drivers/net/virtio_net.c:virtnet_cpu_callback
```
**Symbols:**

```
ffffffff816510b0-ffffffff816511e0: virtnet_set_affinity (STB_LOCAL)
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
void virtnet_set_affinity(struct virtnet_info *vi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/virtio_net.c (0)
Location: drivers/net/virtio_net.c:2569
Inline: False
Direct callers:
  - drivers/net/virtio_net.c:virtnet_restore
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_set_channels
  - drivers/net/virtio_net.c:virtnet_cpu_dead
  - drivers/net/virtio_net.c:virtnet_cpu_online
```
**Symbols:**

```
ffffffff81c4cd80-ffffffff81c4cf61: virtnet_set_affinity (STB_LOCAL)
ffffffff8211e6de-ffffffff8211e6f2: virtnet_set_affinity.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void virtnet_set_affinity(struct virtnet_info *vi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/virtio_net.c (0)
Location: drivers/net/virtio_net.c:2823
Inline: False
Direct callers:
  - drivers/net/virtio_net.c:virtnet_set_channels
  - drivers/net/virtio_net.c:virtnet_cpu_dead
  - drivers/net/virtio_net.c:virtnet_cpu_online
```
**Symbols:**

```
ffffffff81d02620-ffffffff81d02814: virtnet_set_affinity (STB_LOCAL)
ffffffff821ffd6e-ffffffff821ffd82: virtnet_set_affinity.cold (STB_LOCAL)
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
