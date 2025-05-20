# Function: <code>virtnet_fail_on_feature</code>

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
In drivers/net/virtio_net.c (ffffffff815f1a60)
Location: drivers/net/virtio_net.c:1686
Inline: True
Direct callers:
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
```
**Symbols:**

```
ffffffff815f1a60-ffffffff815f1acf: virtnet_fail_on_feature.constprop.41 (STB_LOCAL)
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
In drivers/net/virtio_net.c (ffffffff81651370)
Location: drivers/net/virtio_net.c:1688
Inline: True
Direct callers:
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
```
**Symbols:**

```
ffffffff81651370-ffffffff816513df: virtnet_fail_on_feature.constprop.46 (STB_LOCAL)
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
In drivers/net/virtio_net.c (ffffffff81c514ad)
Location: drivers/net/virtio_net.c:3922
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_validate
  - drivers/net/virtio_net.c:virtnet_validate
  - drivers/net/virtio_net.c:virtnet_validate
  - drivers/net/virtio_net.c:virtnet_validate
  - drivers/net/virtio_net.c:virtnet_validate
  - drivers/net/virtio_net.c:virtnet_validate
  - drivers/net/virtio_net.c:virtnet_validate
  - drivers/net/virtio_net.c:virtnet_validate
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
In drivers/net/virtio_net.c (ffffffff81d097b7)
Location: drivers/net/virtio_net.c:4485
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_validate_features
  - drivers/net/virtio_net.c:virtnet_validate_features
  - drivers/net/virtio_net.c:virtnet_validate_features
  - drivers/net/virtio_net.c:virtnet_validate_features
  - drivers/net/virtio_net.c:virtnet_validate_features
  - drivers/net/virtio_net.c:virtnet_validate_features
  - drivers/net/virtio_net.c:virtnet_validate_features
  - drivers/net/virtio_net.c:virtnet_validate_features
  - drivers/net/virtio_net.c:virtnet_validate_features
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
