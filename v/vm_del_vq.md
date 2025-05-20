# Function: <code>vm_del_vq</code>

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
In drivers/virtio/virtio_mmio.c (ffffffff814c060b)
Location: drivers/virtio/virtio_mmio.c:321
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_del_vqs
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_mmio.c (ffffffff81510c4e)
Location: drivers/virtio/virtio_mmio.c:315
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_del_vqs
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
In drivers/virtio/virtio_mmio.c (ffffffff8153cdbe)
Location: drivers/virtio/virtio_mmio.c:316
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_del_vqs
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_mmio.c (ffffffff815509db)
Location: drivers/virtio/virtio_mmio.c:316
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_del_vqs
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_mmio.c (ffffffff815b41db)
Location: drivers/virtio/virtio_mmio.c:316
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_del_vqs
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_mmio.c (ffffffff815ec5f6)
Location: drivers/virtio/virtio_mmio.c:316
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_del_vqs
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_mmio.c (ffffffff816071c6)
Location: drivers/virtio/virtio_mmio.c:316
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_del_vqs
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_mmio.c (ffffffff8163aff4)
Location: drivers/virtio/virtio_mmio.c:312
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_del_vqs
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_mmio.c (ffffffff8165d4b4)
Location: drivers/virtio/virtio_mmio.c:312
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_del_vqs
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void vm_del_vq(struct virtqueue *vq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_mmio.c (ffffffff8170c560)
Location: drivers/virtio/virtio_mmio.c:312
Inline: False
Direct callers:
  - drivers/virtio/virtio_mmio.c:vm_find_vqs
```
**Symbols:**

```
ffffffff8170c560-ffffffff8170c616: vm_del_vq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void vm_del_vq(struct virtqueue *vq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_mmio.c (ffffffff81729380)
Location: drivers/virtio/virtio_mmio.c:312
Inline: False
Direct callers:
  - drivers/virtio/virtio_mmio.c:vm_find_vqs
```
**Symbols:**

```
ffffffff81729380-ffffffff81729436: vm_del_vq (STB_LOCAL)
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
In drivers/virtio/virtio_mmio.c (ffffffff8170db84)
Location: drivers/virtio/virtio_mmio.c:312
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_del_vqs
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
In drivers/virtio/virtio_mmio.c (ffffffff8178a404)
Location: drivers/virtio/virtio_mmio.c:312
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_del_vqs
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
In drivers/virtio/virtio_mmio.c (ffffffff818c1c13)
Location: drivers/virtio/virtio_mmio.c:318
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_del_vqs
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
In drivers/virtio/virtio_mmio.c (ffffffff81a11be3)
Location: drivers/virtio/virtio_mmio.c:318
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_del_vqs
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
In drivers/virtio/virtio_mmio.c (ffffffff81a5abb3)
Location: drivers/virtio/virtio_mmio.c:329
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_del_vqs
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
In drivers/virtio/virtio_mmio.c (ffffffff81aac023)
Location: drivers/virtio/virtio_mmio.c:329
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_del_vqs
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_mmio.c (ffff800010826078)
Location: drivers/virtio/virtio_mmio.c:312
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_del_vqs
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_mmio.c (c094413c)
Location: drivers/virtio/virtio_mmio.c:312
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_del_vqs
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_mmio.c (c0000000008d15b8)
Location: drivers/virtio/virtio_mmio.c:312
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_del_vqs
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_mmio.c (ffffffe00051c44a)
Location: drivers/virtio/virtio_mmio.c:312
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_del_vqs
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_mmio.c (ffffffff81623354)
Location: drivers/virtio/virtio_mmio.c:312
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_del_vqs
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_mmio.c (ffffffff816179a4)
Location: drivers/virtio/virtio_mmio.c:312
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_del_vqs
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_mmio.c (ffffffff816512f4)
Location: drivers/virtio/virtio_mmio.c:312
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_del_vqs
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_mmio.c (ffffffff8166b984)
Location: drivers/virtio/virtio_mmio.c:312
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_del_vqs
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
