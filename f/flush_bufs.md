# Function: <code>flush_bufs</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void flush_bufs(struct virtqueue *vq, bool can_sleep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff8164a340)
Location: drivers/char/virtio_console.c:1770
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:remove_vqs
  - drivers/char/virtio_console.c:in_intr
  - drivers/char/virtio_console.c:out_intr
```
**Symbols:**

```
ffffffff8164a340-ffffffff8164a3a0: flush_bufs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void flush_bufs(struct virtqueue *vq, bool can_sleep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff816682f0)
Location: drivers/char/virtio_console.c:1743
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:remove_vqs
  - drivers/char/virtio_console.c:in_intr
  - drivers/char/virtio_console.c:out_intr
```
**Symbols:**

```
ffffffff816682f0-ffffffff81668350: flush_bufs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void flush_bufs(struct virtqueue *vq, bool can_sleep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff8169dd70)
Location: drivers/char/virtio_console.c:1731
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:remove_vqs
  - drivers/char/virtio_console.c:in_intr
  - drivers/char/virtio_console.c:out_intr
```
**Symbols:**

```
ffffffff8169dd70-ffffffff8169ddd1: flush_bufs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void flush_bufs(struct virtqueue *vq, bool can_sleep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff816c0ae0)
Location: drivers/char/virtio_console.c:1732
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:remove_vqs
  - drivers/char/virtio_console.c:in_intr
  - drivers/char/virtio_console.c:out_intr
```
**Symbols:**

```
ffffffff816c0ae0-ffffffff816c0b41: flush_bufs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff81774d0b)
Location: drivers/char/virtio_console.c:1730
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:remove_vqs
  - drivers/char/virtio_console.c:in_intr
  - drivers/char/virtio_console.c:out_intr
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff8178fa5b)
Location: drivers/char/virtio_console.c:1730
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:remove_vqs
  - drivers/char/virtio_console.c:in_intr
  - drivers/char/virtio_console.c:out_intr
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
In drivers/char/virtio_console.c (ffffffff817725cb)
Location: drivers/char/virtio_console.c:1727
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:remove_vqs
  - drivers/char/virtio_console.c:in_intr
  - drivers/char/virtio_console.c:out_intr
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
In drivers/char/virtio_console.c (ffffffff817f869b)
Location: drivers/char/virtio_console.c:1727
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:remove_vqs
  - drivers/char/virtio_console.c:in_intr
  - drivers/char/virtio_console.c:out_intr
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
In drivers/char/virtio_console.c (ffffffff81936ede)
Location: drivers/char/virtio_console.c:1728
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:remove_vqs
  - drivers/char/virtio_console.c:in_intr
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
In drivers/char/virtio_console.c (ffffffff81a96dae)
Location: drivers/char/virtio_console.c:1724
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:remove_vqs
  - drivers/char/virtio_console.c:in_intr
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
In drivers/char/virtio_console.c (ffffffff81ae25be)
Location: drivers/char/virtio_console.c:1724
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:remove_vqs
  - drivers/char/virtio_console.c:in_intr
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
In drivers/char/virtio_console.c (ffffffff81b359ae)
Location: drivers/char/virtio_console.c:1692
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:remove_vqs
  - drivers/char/virtio_console.c:in_intr
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
void flush_bufs(struct virtqueue *vq, bool can_sleep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (ffff8000108b42c0)
Location: drivers/char/virtio_console.c:1732
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:remove_vqs
  - drivers/char/virtio_console.c:in_intr
  - drivers/char/virtio_console.c:out_intr
```
**Symbols:**

```
ffff8000108b42c0-ffff8000108b4334: flush_bufs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void flush_bufs(struct virtqueue *vq, bool can_sleep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (c09ad760)
Location: drivers/char/virtio_console.c:1732
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:remove_vqs
  - drivers/char/virtio_console.c:in_intr
  - drivers/char/virtio_console.c:out_intr
```
**Symbols:**

```
c09ad760-c09ad7d8: flush_bufs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void flush_bufs(struct virtqueue *vq, bool can_sleep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (c00000000094be00)
Location: drivers/char/virtio_console.c:1732
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:remove_vqs
  - drivers/char/virtio_console.c:in_intr
  - drivers/char/virtio_console.c:out_intr
```
**Symbols:**

```
c00000000094be00-c00000000094be94: flush_bufs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/virtio_console.c (ffffffe000565266)
Location: drivers/char/virtio_console.c:1732
Inline: True
Direct callers:
  - drivers/char/virtio_console.c:virtcons_remove
  - drivers/char/virtio_console.c:in_intr
  - drivers/char/virtio_console.c:out_intr
```
**Symbols:**

```
ffffffe000565266-ffffffe0005652a0: flush_bufs.isra.0 (STB_LOCAL)
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
void flush_bufs(struct virtqueue *vq, bool can_sleep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff81686530)
Location: drivers/char/virtio_console.c:1732
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:remove_vqs
  - drivers/char/virtio_console.c:in_intr
  - drivers/char/virtio_console.c:out_intr
```
**Symbols:**

```
ffffffff81686530-ffffffff81686591: flush_bufs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void flush_bufs(struct virtqueue *vq, bool can_sleep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff816644c0)
Location: drivers/char/virtio_console.c:1732
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:remove_vqs
  - drivers/char/virtio_console.c:in_intr
  - drivers/char/virtio_console.c:out_intr
```
**Symbols:**

```
ffffffff816644c0-ffffffff81664516: flush_bufs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void flush_bufs(struct virtqueue *vq, bool can_sleep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff816b4c10)
Location: drivers/char/virtio_console.c:1732
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:remove_vqs
  - drivers/char/virtio_console.c:in_intr
  - drivers/char/virtio_console.c:out_intr
```
**Symbols:**

```
ffffffff816b4c10-ffffffff816b4c66: flush_bufs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void flush_bufs(struct virtqueue *vq, bool can_sleep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff816cee80)
Location: drivers/char/virtio_console.c:1732
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:remove_vqs
  - drivers/char/virtio_console.c:in_intr
  - drivers/char/virtio_console.c:out_intr
```
**Symbols:**

```
ffffffff816cee80-ffffffff816ceee1: flush_bufs (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
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
