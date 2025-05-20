# Function: <code>virtqueue_poll</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
bool virtqueue_poll(struct virtqueue *_vq, unsigned int last_used_idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff814bf700)
Location: drivers/virtio/virtio_ring.c:598
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb
  - drivers/net/virtio_net.c:virtnet_busy_poll
```
**Symbols:**

```
ffffffff814bf700-ffffffff814bf719: virtqueue_poll (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
bool virtqueue_poll(struct virtqueue *_vq, unsigned int last_used_idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8150f612)
Location: drivers/virtio/virtio_ring.c:784
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb
Direct callers:
  - drivers/net/virtio_net.c:virtnet_busy_poll
```
**Symbols:**

```
ffffffff8150f5e0-ffffffff8150f5f9: virtqueue_poll (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
bool virtqueue_poll(struct virtqueue *_vq, unsigned int last_used_idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8153b7b2)
Location: drivers/virtio/virtio_ring.c:786
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb
```
**Symbols:**

```
ffffffff8153b780-ffffffff8153b799: virtqueue_poll (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
bool virtqueue_poll(struct virtqueue *_vq, unsigned int last_used_idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8154f102)
Location: drivers/virtio/virtio_ring.c:829
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb
```
**Symbols:**

```
ffffffff8154f0d0-ffffffff8154f0e9: virtqueue_poll (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool virtqueue_poll(struct virtqueue *_vq, unsigned int last_used_idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff815b2870)
Location: drivers/virtio/virtio_ring.c:828
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb
```
**Symbols:**

```
ffffffff815b2870-ffffffff815b28a2: virtqueue_poll (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool virtqueue_poll(struct virtqueue *_vq, unsigned int last_used_idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff815eaca0)
Location: drivers/virtio/virtio_ring.c:827
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb
```
**Symbols:**

```
ffffffff815eaca0-ffffffff815eacd2: virtqueue_poll (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
bool virtqueue_poll(struct virtqueue *_vq, unsigned int last_used_idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff816051c0)
Location: drivers/virtio/virtio_ring.c:1954
Inline: True
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb
```
**Symbols:**

```
ffffffff816051c0-ffffffff81605220: virtqueue_poll (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
bool virtqueue_poll(struct virtqueue *_vq, unsigned int last_used_idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81637c60)
Location: drivers/virtio/virtio_ring.c:1960
Inline: True
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb
```
**Symbols:**

```
ffffffff81637c60-ffffffff81637cc0: virtqueue_poll (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool virtqueue_poll(struct virtqueue *_vq, unsigned int last_used_idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81659a50)
Location: drivers/virtio/virtio_ring.c:1959
Inline: True
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb
```
**Symbols:**

```
ffffffff81659a50-ffffffff81659ab0: virtqueue_poll (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool virtqueue_poll(struct virtqueue *_vq, unsigned int last_used_idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8170a424)
Location: drivers/virtio/virtio_ring.c:1959
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb
```
**Symbols:**

```
ffffffff81709d10-ffffffff81709d7a: virtqueue_poll (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool virtqueue_poll(struct virtqueue *_vq, unsigned int last_used_idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81727954)
Location: drivers/virtio/virtio_ring.c:1959
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb
```
**Symbols:**

```
ffffffff81727270-ffffffff817272da: virtqueue_poll (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool virtqueue_poll(struct virtqueue *_vq, unsigned int last_used_idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8170b934)
Location: drivers/virtio/virtio_ring.c:1961
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb
```
**Symbols:**

```
ffffffff8170ac30-ffffffff8170ac9a: virtqueue_poll (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
bool virtqueue_poll(struct virtqueue *_vq, unsigned int last_used_idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (0)
Location: drivers/virtio/virtio_ring.c:2068
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb
```
**Symbols:**

```
ffffffff81cf44bb-ffffffff81cf44fa: virtqueue_poll.cold (STB_LOCAL)
ffffffff81786350-ffffffff81786401: virtqueue_poll (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool virtqueue_poll(struct virtqueue *_vq, unsigned int last_used_idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (0)
Location: drivers/virtio/virtio_ring.c:2072
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb
```
**Symbols:**

```
ffffffff81ebca01-ffffffff81ebca40: virtqueue_poll.cold (STB_LOCAL)
ffffffff818be160-ffffffff818be233: virtqueue_poll (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
bool virtqueue_poll(struct virtqueue *_vq, unsigned int last_used_idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (0)
Location: drivers/virtio/virtio_ring.c:2358
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb
```
**Symbols:**

```
ffffffff82093e7f-ffffffff82093ebe: virtqueue_poll.cold (STB_LOCAL)
ffffffff81a0d1c0-ffffffff81a0d293: virtqueue_poll (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool virtqueue_poll(struct virtqueue *_vq, unsigned int last_used_idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (0)
Location: drivers/virtio/virtio_ring.c:2389
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb
  - drivers/net/virtio_net.c:virtnet_poll_tx
  - drivers/net/virtio_net.c:virtnet_poll
```
**Symbols:**

```
ffffffff82114b5f-ffffffff82114b9e: virtqueue_poll.cold (STB_LOCAL)
ffffffff81a55e30-ffffffff81a55f03: virtqueue_poll (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool virtqueue_poll(struct virtqueue *_vq, unsigned int last_used_idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (0)
Location: drivers/virtio/virtio_ring.c:2483
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb
  - drivers/net/virtio_net.c:virtnet_poll_tx
  - drivers/net/virtio_net.c:virtnet_poll
```
**Symbols:**

```
ffffffff821f278b-ffffffff821f27ca: virtqueue_poll.cold (STB_LOCAL)
ffffffff81aa6f50-ffffffff81aa7023: virtqueue_poll (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
bool virtqueue_poll(struct virtqueue *_vq, unsigned int last_used_idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffff800010822078)
Location: drivers/virtio/virtio_ring.c:1959
Inline: True
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb
```
**Symbols:**

```
ffff800010822078-ffff80001082210c: virtqueue_poll (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
bool virtqueue_poll(struct virtqueue *_vq, unsigned int last_used_idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (c093f9c0)
Location: drivers/virtio/virtio_ring.c:1959
Inline: True
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb
```
**Symbols:**

```
c093f9c0-c093fa58: virtqueue_poll (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
bool virtqueue_poll(struct virtqueue *_vq, unsigned int last_used_idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (c0000000008cc570)
Location: drivers/virtio/virtio_ring.c:1959
Inline: True
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb
```
**Symbols:**

```
c0000000008cc570-c0000000008cc5ec: virtqueue_poll (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
bool virtqueue_poll(struct virtqueue *_vq, unsigned int last_used_idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffe000518a1a)
Location: drivers/virtio/virtio_ring.c:1959
Inline: True
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb
```
**Symbols:**

```
ffffffe000518a1a-ffffffe000518ab4: virtqueue_poll (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
bool virtqueue_poll(struct virtqueue *_vq, unsigned int last_used_idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8161f8f0)
Location: drivers/virtio/virtio_ring.c:1959
Inline: True
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb
```
**Symbols:**

```
ffffffff8161f8f0-ffffffff8161f950: virtqueue_poll (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
bool virtqueue_poll(struct virtqueue *_vq, unsigned int last_used_idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81613e90)
Location: drivers/virtio/virtio_ring.c:1959
Inline: True
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb
```
**Symbols:**

```
ffffffff81613e90-ffffffff81613ef0: virtqueue_poll (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool virtqueue_poll(struct virtqueue *_vq, unsigned int last_used_idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8164d890)
Location: drivers/virtio/virtio_ring.c:1959
Inline: True
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb
```
**Symbols:**

```
ffffffff8164d890-ffffffff8164d8f0: virtqueue_poll (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool virtqueue_poll(struct virtqueue *_vq, unsigned int last_used_idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81667f20)
Location: drivers/virtio/virtio_ring.c:1959
Inline: True
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb
```
**Symbols:**

```
ffffffff81667f20-ffffffff81667f80: virtqueue_poll (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
