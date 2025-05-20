# Function: <code>virtnet_clean_affinity</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/virtio_net.c (ffffffff815f15f0)
Location: drivers/net/virtio_net.c:1253
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_set_affinity
  - drivers/net/virtio_net.c:virtnet_cpu_callback
  - drivers/net/virtio_net.c:virtnet_del_vqs
Direct callers:
  - drivers/net/virtio_net.c:virtnet_set_affinity
  - drivers/net/virtio_net.c:virtnet_cpu_callback
  - drivers/net/virtio_net.c:virtnet_del_vqs
```
**Symbols:**

```
ffffffff815f15f0-ffffffff815f1682: virtnet_clean_affinity.isra.21.part.22 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/virtio_net.c (ffffffff81650cfc)
Location: drivers/net/virtio_net.c:1200
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_del_vqs
  - drivers/net/virtio_net.c:virtnet_cpu_callback
Direct callers:
  - drivers/net/virtio_net.c:virtnet_del_vqs
  - drivers/net/virtio_net.c:virtnet_cpu_callback
```
**Symbols:**

```
ffffffff81650c50-ffffffff81650ce8: virtnet_clean_affinity.isra.23.part.24 (STB_LOCAL)
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
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/virtio_net.c (ffffffff81c541f8)
Location: drivers/net/virtio_net.c:2555
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:remove_vq_common
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_cpu_down_prep
  - drivers/net/virtio_net.c:virtnet_set_affinity
Direct callers:
  - drivers/net/virtio_net.c:remove_vq_common
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_cpu_down_prep
  - drivers/net/virtio_net.c:virtnet_set_affinity
```
**Symbols:**

```
ffffffff81c4cb50-ffffffff81c4cbee: virtnet_clean_affinity.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/virtio_net.c (ffffffff81d0a99e)
Location: drivers/net/virtio_net.c:2809
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:remove_vq_common
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_cpu_down_prep
  - drivers/net/virtio_net.c:virtnet_set_affinity
Direct callers:
  - drivers/net/virtio_net.c:remove_vq_common
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_cpu_down_prep
  - drivers/net/virtio_net.c:virtnet_set_affinity
```
**Symbols:**

```
ffffffff81d023d0-ffffffff81d0246e: virtnet_clean_affinity.part.0 (STB_LOCAL)
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
