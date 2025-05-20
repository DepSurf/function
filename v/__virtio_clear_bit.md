# Function: <code>__virtio_clear_bit</code>

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
In drivers/virtio/virtio_ring.c (ffffffff814bf393)
Location: include/linux/virtio_config.h:126
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:vring_transport_features
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8150f0d3)
Location: include/linux/virtio_config.h:126
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:vring_transport_features
```
```
In drivers/net/virtio_net.c (ffffffff8165465a)
Location: include/linux/virtio_config.h:126
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_probe
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
In drivers/virtio/virtio_ring.c (ffffffff8153b233)
Location: include/linux/virtio_config.h:126
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:vring_transport_features
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8154ea43)
Location: include/linux/virtio_config.h:131
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:vring_transport_features
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81553ec6)
Location: include/linux/virtio_config.h:131
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_validate
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff815b21f3)
Location: include/linux/virtio_config.h:132
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:vring_transport_features
```
```
In drivers/virtio/virtio_balloon.c (ffffffff815b7906)
Location: include/linux/virtio_config.h:132
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_validate
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff815ea63b)
Location: include/linux/virtio_config.h:132
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:vring_transport_features
```
```
In drivers/virtio/virtio_balloon.c (ffffffff815efe25)
Location: include/linux/virtio_config.h:132
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_validate
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81604cad)
Location: include/linux/virtio_config.h:138
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:vring_transport_features
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8160a4dd)
Location: include/linux/virtio_config.h:138
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_validate
  - drivers/virtio/virtio_balloon.c:virtballoon_validate
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff816375b5)
Location: include/linux/virtio_config.h:138
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:vring_transport_features
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8163e2cd)
Location: include/linux/virtio_config.h:138
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_validate
  - drivers/virtio/virtio_balloon.c:virtballoon_validate
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81659315)
Location: include/linux/virtio_config.h:138
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:vring_transport_features
```
```
In drivers/virtio/virtio_balloon.c (ffffffff816607ad)
Location: include/linux/virtio_config.h:138
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_validate
  - drivers/virtio/virtio_balloon.c:virtballoon_validate
```
```
In drivers/remoteproc/remoteproc_virtio.c (ffffffff818f721f)
Location: include/linux/virtio_config.h:138
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81709af5)
Location: include/linux/virtio_config.h:138
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:vring_transport_features
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81710512)
Location: include/linux/virtio_config.h:138
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_validate
  - drivers/virtio/virtio_balloon.c:virtballoon_validate
  - drivers/virtio/virtio_balloon.c:virtballoon_validate
```
```
In drivers/remoteproc/remoteproc_virtio.c (ffffffff819cd2cf)
Location: include/linux/virtio_config.h:138
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81726a65)
Location: include/linux/virtio_config.h:147
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:vring_transport_features
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8172d0f7)
Location: include/linux/virtio_config.h:147
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_validate
  - drivers/virtio/virtio_balloon.c:virtballoon_validate
  - drivers/virtio/virtio_balloon.c:virtballoon_validate
```
```
In drivers/remoteproc/remoteproc_virtio.c (ffffffff819ccb1f)
Location: include/linux/virtio_config.h:147
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8170a6d5)
Location: include/linux/virtio_config.h:147
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:vring_transport_features
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81710557)
Location: include/linux/virtio_config.h:147
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_validate
  - drivers/virtio/virtio_balloon.c:virtballoon_validate
  - drivers/virtio/virtio_balloon.c:virtballoon_validate
```
```
In drivers/remoteproc/remoteproc_virtio.c (ffffffff819b1ccf)
Location: include/linux/virtio_config.h:147
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff817860b5)
Location: include/linux/virtio_config.h:148
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:vring_transport_features
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8178cf31)
Location: include/linux/virtio_config.h:148
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_validate
  - drivers/virtio/virtio_balloon.c:virtballoon_validate
  - drivers/virtio/virtio_balloon.c:virtballoon_validate
```
```
In drivers/remoteproc/remoteproc_virtio.c (ffffffff81a5ffbf)
Location: include/linux/virtio_config.h:148
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_finalize_features
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff818bcf7d)
Location: include/linux/virtio_config.h:154
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:vring_transport_features
```
```
In drivers/virtio/virtio_balloon.c (ffffffff818c5031)
Location: include/linux/virtio_config.h:154
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_validate
  - drivers/virtio/virtio_balloon.c:virtballoon_validate
  - drivers/virtio/virtio_balloon.c:virtballoon_validate
```
```
In drivers/remoteproc/remoteproc_virtio.c (ffffffff81bd042f)
Location: include/linux/virtio_config.h:154
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_finalize_features
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81a0bd4d)
Location: include/linux/virtio_config.h:168
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:vring_transport_features
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81a158d1)
Location: include/linux/virtio_config.h:168
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_validate
  - drivers/virtio/virtio_balloon.c:virtballoon_validate
  - drivers/virtio/virtio_balloon.c:virtballoon_validate
```
```
In drivers/remoteproc/remoteproc_virtio.c (ffffffff81d7b830)
Location: include/linux/virtio_config.h:168
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_finalize_features
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81a54bdd)
Location: include/linux/virtio_config.h:170
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:vring_transport_features
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81a5ec51)
Location: include/linux/virtio_config.h:170
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_validate
  - drivers/virtio/virtio_balloon.c:virtballoon_validate
  - drivers/virtio/virtio_balloon.c:virtballoon_validate
```
```
In drivers/net/virtio_net.c (ffffffff81c51572)
Location: include/linux/virtio_config.h:170
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_validate
  - drivers/net/virtio_net.c:virtnet_validate
```
```
In drivers/remoteproc/remoteproc_virtio.c (ffffffff81de99f0)
Location: include/linux/virtio_config.h:170
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_finalize_features
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81aa590d)
Location: include/linux/virtio_config.h:174
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:vring_transport_features
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81ab13b1)
Location: include/linux/virtio_config.h:174
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_validate
  - drivers/virtio/virtio_balloon.c:virtballoon_validate
  - drivers/virtio/virtio_balloon.c:virtballoon_validate
```
```
In drivers/net/virtio_net.c (ffffffff81d09aa0)
Location: include/linux/virtio_config.h:174
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_validate
  - drivers/net/virtio_net.c:virtnet_validate
```
```
In drivers/remoteproc/remoteproc_virtio.c (ffffffff81e9fc30)
Location: include/linux/virtio_config.h:174
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_finalize_features
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
In drivers/virtio/virtio_ring.c (ffff800010821b80)
Location: include/linux/virtio_config.h:138
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:vring_transport_features
```
```
In drivers/virtio/virtio_balloon.c (ffff800010829800)
Location: include/linux/virtio_config.h:138
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_validate
  - drivers/virtio/virtio_balloon.c:virtballoon_validate
```
```
In drivers/remoteproc/remoteproc_virtio.c (ffff800010b8355c)
Location: include/linux/virtio_config.h:138
Inline: True
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
In drivers/virtio/virtio_ring.c (c093f468)
Location: include/linux/virtio_config.h:138
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:vring_transport_features
```
```
In drivers/virtio/virtio_balloon.c (c09473e0)
Location: include/linux/virtio_config.h:138
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_validate
  - drivers/virtio/virtio_balloon.c:virtballoon_validate
```
```
In drivers/remoteproc/remoteproc_virtio.c (c0c667d8)
Location: include/linux/virtio_config.h:138
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (c0000000008cb4f8)
Location: include/linux/virtio_config.h:138
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:vring_transport_features
```
```
In drivers/virtio/virtio_balloon.c (c0000000008d6268)
Location: include/linux/virtio_config.h:138
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_validate
  - drivers/virtio/virtio_balloon.c:virtballoon_validate
```
```
In drivers/remoteproc/remoteproc_virtio.c (c000000000c602c4)
Location: include/linux/virtio_config.h:138
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_finalize_features
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffe0005185d8)
Location: include/linux/virtio_config.h:138
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:vring_transport_features
```
```
In drivers/virtio/virtio_balloon.c (ffffffe00051fb0e)
Location: include/linux/virtio_config.h:138
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_validate
  - drivers/virtio/virtio_balloon.c:virtballoon_validate
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8161f1b5)
Location: include/linux/virtio_config.h:138
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:vring_transport_features
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8162661d)
Location: include/linux/virtio_config.h:138
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_validate
  - drivers/virtio/virtio_balloon.c:virtballoon_validate
```
```
In drivers/remoteproc/remoteproc_virtio.c (ffffffff8189854f)
Location: include/linux/virtio_config.h:138
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff816137d5)
Location: include/linux/virtio_config.h:138
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:vring_transport_features
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8161ac9d)
Location: include/linux/virtio_config.h:138
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_validate
  - drivers/virtio/virtio_balloon.c:virtballoon_validate
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8164d155)
Location: include/linux/virtio_config.h:138
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:vring_transport_features
```
```
In drivers/virtio/virtio_balloon.c (ffffffff816545ed)
Location: include/linux/virtio_config.h:138
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_validate
  - drivers/virtio/virtio_balloon.c:virtballoon_validate
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
In drivers/virtio/virtio_ring.c (ffffffff816677e5)
Location: include/linux/virtio_config.h:138
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:vring_transport_features
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8166ed4d)
Location: include/linux/virtio_config.h:138
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_validate
  - drivers/virtio/virtio_balloon.c:virtballoon_validate
```
```
In drivers/remoteproc/remoteproc_virtio.c (ffffffff81908caf)
Location: include/linux/virtio_config.h:138
Inline: True
```
</details>
</li>
</ul>

## Differences
