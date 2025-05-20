# Function: <code>virtqueue_detach_unused_buf</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void *virtqueue_detach_unused_buf(struct virtqueue *_vq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff814bfd40)
Location: drivers/virtio/virtio_ring.c:676
Inline: True
Direct callers:
  - drivers/char/virtio_console.c:remove_port_data
  - drivers/char/virtio_console.c:remove_port_data
  - drivers/char/virtio_console.c:add_port
  - drivers/net/virtio_net.c:free_unused_bufs
  - drivers/net/virtio_net.c:free_unused_bufs
  - drivers/net/virtio_net.c:free_unused_bufs
```
**Symbols:**

```
ffffffff814bfd40-ffffffff814bfda8: virtqueue_detach_unused_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void *virtqueue_detach_unused_buf(struct virtqueue *_vq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8150fc30)
Location: drivers/virtio/virtio_ring.c:865
Inline: True
Direct callers:
  - drivers/char/virtio_console.c:remove_port_data
  - drivers/char/virtio_console.c:remove_port_data
  - drivers/char/virtio_console.c:add_port
  - drivers/net/virtio_net.c:remove_vq_common
  - drivers/net/virtio_net.c:remove_vq_common
  - drivers/net/virtio_net.c:remove_vq_common
```
**Symbols:**

```
ffffffff8150fc30-ffffffff8150fc9b: virtqueue_detach_unused_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void *virtqueue_detach_unused_buf(struct virtqueue *_vq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8153bd50)
Location: drivers/virtio/virtio_ring.c:868
Inline: True
Direct callers:
  - drivers/char/virtio_console.c:remove_port_data
  - drivers/char/virtio_console.c:remove_port_data
  - drivers/char/virtio_console.c:add_port
```
**Symbols:**

```
ffffffff8153bd50-ffffffff8153bdbb: virtqueue_detach_unused_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void *virtqueue_detach_unused_buf(struct virtqueue *_vq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8154f6c0)
Location: drivers/virtio/virtio_ring.c:911
Inline: True
Direct callers:
  - drivers/char/virtio_console.c:remove_port_data
  - drivers/char/virtio_console.c:remove_port_data
  - drivers/char/virtio_console.c:add_port
```
**Symbols:**

```
ffffffff8154f6c0-ffffffff8154f72d: virtqueue_detach_unused_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void *virtqueue_detach_unused_buf(struct virtqueue *_vq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff815b2fd0)
Location: drivers/virtio/virtio_ring.c:910
Inline: True
Direct callers:
  - drivers/char/virtio_console.c:remove_port_data
  - drivers/char/virtio_console.c:remove_port_data
  - drivers/char/virtio_console.c:add_port
```
**Symbols:**

```
ffffffff815b2fd0-ffffffff815b303d: virtqueue_detach_unused_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void *virtqueue_detach_unused_buf(struct virtqueue *_vq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff815eb4e0)
Location: drivers/virtio/virtio_ring.c:909
Inline: True
Direct callers:
  - drivers/char/virtio_console.c:remove_vqs
```
**Symbols:**

```
ffffffff815eb4e0-ffffffff815eb54d: virtqueue_detach_unused_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void *virtqueue_detach_unused_buf(struct virtqueue *_vq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff816057e0)
Location: drivers/virtio/virtio_ring.c:2013
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:remove_vqs
```
**Symbols:**

```
ffffffff816057e0-ffffffff8160589f: virtqueue_detach_unused_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void *virtqueue_detach_unused_buf(struct virtqueue *_vq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8163a9f0)
Location: drivers/virtio/virtio_ring.c:2019
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:remove_vqs
```
**Symbols:**

```
ffffffff8163a9f0-ffffffff8163aa9b: virtqueue_detach_unused_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void *virtqueue_detach_unused_buf(struct virtqueue *_vq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8165ceb0)
Location: drivers/virtio/virtio_ring.c:2018
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:remove_vqs
```
**Symbols:**

```
ffffffff8165ceb0-ffffffff8165cf5b: virtqueue_detach_unused_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void *virtqueue_detach_unused_buf(struct virtqueue *_vq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8170a950)
Location: drivers/virtio/virtio_ring.c:2021
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:remove_vqs
  - drivers/char/virtio_console.c:remove_vqs
```
**Symbols:**

```
ffffffff8170a950-ffffffff8170a9fb: virtqueue_detach_unused_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *virtqueue_detach_unused_buf(struct virtqueue *_vq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81727450)
Location: drivers/virtio/virtio_ring.c:2021
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:remove_vqs
  - drivers/char/virtio_console.c:remove_vqs
```
**Symbols:**

```
ffffffff81727450-ffffffff817274fb: virtqueue_detach_unused_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void *virtqueue_detach_unused_buf(struct virtqueue *_vq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8170ae90)
Location: drivers/virtio/virtio_ring.c:2023
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:remove_vqs
  - drivers/char/virtio_console.c:remove_vqs
```
**Symbols:**

```
ffffffff8170ae90-ffffffff8170af3b: virtqueue_detach_unused_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void *virtqueue_detach_unused_buf(struct virtqueue *_vq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (0)
Location: drivers/virtio/virtio_ring.c:2133
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:remove_vqs
  - drivers/char/virtio_console.c:remove_vqs
```
**Symbols:**

```
ffffffff81cf48cf-ffffffff81cf48e4: virtqueue_detach_unused_buf.cold (STB_LOCAL)
ffffffff817870e0-ffffffff8178719c: virtqueue_detach_unused_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void *virtqueue_detach_unused_buf(struct virtqueue *_vq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (0)
Location: drivers/virtio/virtio_ring.c:2137
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:remove_vqs
  - drivers/char/virtio_console.c:remove_vqs
```
**Symbols:**

```
ffffffff81ebc8c7-ffffffff81ebc8dc: virtqueue_detach_unused_buf.cold (STB_LOCAL)
ffffffff818bdd80-ffffffff818bde40: virtqueue_detach_unused_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void *virtqueue_detach_unused_buf(struct virtqueue *_vq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (0)
Location: drivers/virtio/virtio_ring.c:2423
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_resize
  - drivers/char/virtio_console.c:remove_vqs
  - drivers/char/virtio_console.c:remove_vqs
```
**Symbols:**

```
ffffffff82093dfb-ffffffff82093e10: virtqueue_detach_unused_buf.cold (STB_LOCAL)
ffffffff81a0cf40-ffffffff81a0d010: virtqueue_detach_unused_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void *virtqueue_detach_unused_buf(struct virtqueue *_vq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (0)
Location: drivers/virtio/virtio_ring.c:2454
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_resize
  - drivers/char/virtio_console.c:remove_vqs
  - drivers/char/virtio_console.c:remove_vqs
  - drivers/net/virtio_net.c:remove_vq_common
  - drivers/net/virtio_net.c:remove_vq_common
  - drivers/net/virtio_net.c:remove_vq_common
```
**Symbols:**

```
ffffffff82114adb-ffffffff82114af0: virtqueue_detach_unused_buf.cold (STB_LOCAL)
ffffffff81a55bc0-ffffffff81a55c86: virtqueue_detach_unused_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void *virtqueue_detach_unused_buf(struct virtqueue *_vq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (0)
Location: drivers/virtio/virtio_ring.c:2548
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_disable_and_recycle
  - drivers/char/virtio_console.c:remove_vqs
  - drivers/char/virtio_console.c:remove_vqs
  - drivers/net/virtio_net.c:remove_vq_common
  - drivers/net/virtio_net.c:remove_vq_common
  - drivers/net/virtio_net.c:remove_vq_common
```
**Symbols:**

```
ffffffff821f26f2-ffffffff821f2707: virtqueue_detach_unused_buf.cold (STB_LOCAL)
ffffffff81aa6c30-ffffffff81aa6cf6: virtqueue_detach_unused_buf (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void *virtqueue_detach_unused_buf(struct virtqueue *_vq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffff800010823040)
Location: drivers/virtio/virtio_ring.c:2018
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:remove_vqs
```
**Symbols:**

```
ffff800010823040-ffff800010823124: virtqueue_detach_unused_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void *virtqueue_detach_unused_buf(struct virtqueue *_vq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (c0940bdc)
Location: drivers/virtio/virtio_ring.c:2018
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:remove_vqs
```
**Symbols:**

```
c0940bdc-c0940cb8: virtqueue_detach_unused_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void *virtqueue_detach_unused_buf(struct virtqueue *_vq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (c0000000008d0970)
Location: drivers/virtio/virtio_ring.c:2018
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:remove_vqs
```
**Symbols:**

```
c0000000008d0970-c0000000008d0af8: virtqueue_detach_unused_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void *virtqueue_detach_unused_buf(struct virtqueue *_vq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffe000519964)
Location: drivers/virtio/virtio_ring.c:2018
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:virtcons_remove
```
**Symbols:**

```
ffffffe000519964-ffffffe000519a0c: virtqueue_detach_unused_buf (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void *virtqueue_detach_unused_buf(struct virtqueue *_vq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81622d50)
Location: drivers/virtio/virtio_ring.c:2018
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:remove_vqs
```
**Symbols:**

```
ffffffff81622d50-ffffffff81622dfb: virtqueue_detach_unused_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void *virtqueue_detach_unused_buf(struct virtqueue *_vq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff816173a0)
Location: drivers/virtio/virtio_ring.c:2018
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:remove_vqs
```
**Symbols:**

```
ffffffff816173a0-ffffffff8161744b: virtqueue_detach_unused_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void *virtqueue_detach_unused_buf(struct virtqueue *_vq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81650cf0)
Location: drivers/virtio/virtio_ring.c:2018
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:remove_vqs
```
**Symbols:**

```
ffffffff81650cf0-ffffffff81650d9b: virtqueue_detach_unused_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void *virtqueue_detach_unused_buf(struct virtqueue *_vq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8166b380)
Location: drivers/virtio/virtio_ring.c:2018
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:remove_vqs
```
**Symbols:**

```
ffffffff8166b380-ffffffff8166b42b: virtqueue_detach_unused_buf (STB_GLOBAL)
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
