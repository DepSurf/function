# Function: <code>vm_del_vqs</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void vm_del_vqs(struct virtio_device *vdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_mmio.c (ffffffff814c05d0)
Location: drivers/virtio/virtio_mmio.c:348
Inline: False
```
**Symbols:**

```
ffffffff814c05d0-ffffffff814c0733: vm_del_vqs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void vm_del_vqs(struct virtio_device *vdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_mmio.c (ffffffff81510c10)
Location: drivers/virtio/virtio_mmio.c:340
Inline: False
```
**Symbols:**

```
ffffffff81510c10-ffffffff81510d4d: vm_del_vqs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void vm_del_vqs(struct virtio_device *vdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_mmio.c (ffffffff8153cd80)
Location: drivers/virtio/virtio_mmio.c:341
Inline: False
```
**Symbols:**

```
ffffffff8153cd80-ffffffff8153cebd: vm_del_vqs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void vm_del_vqs(struct virtio_device *vdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_mmio.c (ffffffff815509a0)
Location: drivers/virtio/virtio_mmio.c:341
Inline: False
```
**Symbols:**

```
ffffffff815509a0-ffffffff81550acb: vm_del_vqs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void vm_del_vqs(struct virtio_device *vdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_mmio.c (ffffffff815b41a0)
Location: drivers/virtio/virtio_mmio.c:341
Inline: False
```
**Symbols:**

```
ffffffff815b41a0-ffffffff815b42cb: vm_del_vqs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void vm_del_vqs(struct virtio_device *vdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_mmio.c (ffffffff815ec580)
Location: drivers/virtio/virtio_mmio.c:341
Inline: False
```
**Symbols:**

```
ffffffff815ec580-ffffffff815ec6ab: vm_del_vqs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void vm_del_vqs(struct virtio_device *vdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_mmio.c (ffffffff81607150)
Location: drivers/virtio/virtio_mmio.c:341
Inline: False
```
**Symbols:**

```
ffffffff81607150-ffffffff8160727b: vm_del_vqs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void vm_del_vqs(struct virtio_device *vdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_mmio.c (0)
Location: drivers/virtio/virtio_mmio.c:337
Inline: False
```
**Symbols:**

```
ffffffff8163af80-ffffffff8163b09c: vm_del_vqs (STB_LOCAL)
ffffffff8163b9d4-ffffffff8163b9e7: vm_del_vqs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void vm_del_vqs(struct virtio_device *vdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_mmio.c (ffffffff8165d440)
Location: drivers/virtio/virtio_mmio.c:337
Inline: False
```
**Symbols:**

```
ffffffff8165d440-ffffffff8165d563: vm_del_vqs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void vm_del_vqs(struct virtio_device *vdev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_mmio.c (ffffffff8170cf7c)
Location: drivers/virtio/virtio_mmio.c:337
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_find_vqs
```
**Symbols:**

```
ffffffff8170c620-ffffffff8170c676: vm_del_vqs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void vm_del_vqs(struct virtio_device *vdev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_mmio.c (ffffffff81729d9c)
Location: drivers/virtio/virtio_mmio.c:337
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_find_vqs
```
**Symbols:**

```
ffffffff81729440-ffffffff81729496: vm_del_vqs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void vm_del_vqs(struct virtio_device *vdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_mmio.c (ffffffff8170db10)
Location: drivers/virtio/virtio_mmio.c:337
Inline: False
Direct callers:
  - drivers/virtio/virtio_mmio.c:vm_find_vqs
```
**Symbols:**

```
ffffffff8170db10-ffffffff8170dc33: vm_del_vqs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void vm_del_vqs(struct virtio_device *vdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_mmio.c (ffffffff8178a390)
Location: drivers/virtio/virtio_mmio.c:337
Inline: False
Direct callers:
  - drivers/virtio/virtio_mmio.c:vm_find_vqs
```
**Symbols:**

```
ffffffff8178a390-ffffffff8178a4b3: vm_del_vqs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void vm_del_vqs(struct virtio_device *vdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_mmio.c (ffffffff818c1ba0)
Location: drivers/virtio/virtio_mmio.c:343
Inline: False
Direct callers:
  - drivers/virtio/virtio_mmio.c:vm_find_vqs
```
**Symbols:**

```
ffffffff818c1ba0-ffffffff818c1cd0: vm_del_vqs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void vm_del_vqs(struct virtio_device *vdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_mmio.c (ffffffff81a11b70)
Location: drivers/virtio/virtio_mmio.c:343
Inline: False
Direct callers:
  - drivers/virtio/virtio_mmio.c:vm_find_vqs
```
**Symbols:**

```
ffffffff81a11b70-ffffffff81a11ca0: vm_del_vqs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void vm_del_vqs(struct virtio_device *vdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_mmio.c (ffffffff81a5ab40)
Location: drivers/virtio/virtio_mmio.c:354
Inline: False
Direct callers:
  - drivers/virtio/virtio_mmio.c:vm_find_vqs
```
**Symbols:**

```
ffffffff81a5ab40-ffffffff81a5ac70: vm_del_vqs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void vm_del_vqs(struct virtio_device *vdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_mmio.c (ffffffff81aabfb0)
Location: drivers/virtio/virtio_mmio.c:354
Inline: False
Direct callers:
  - drivers/virtio/virtio_mmio.c:vm_find_vqs
```
**Symbols:**

```
ffffffff81aabfb0-ffffffff81aac0e0: vm_del_vqs (STB_LOCAL)
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
void vm_del_vqs(struct virtio_device *vdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_mmio.c (ffff800010826020)
Location: drivers/virtio/virtio_mmio.c:337
Inline: False
```
**Symbols:**

```
ffff800010826020-ffff8000108261bc: vm_del_vqs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void vm_del_vqs(struct virtio_device *vdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_mmio.c (c09440b8)
Location: drivers/virtio/virtio_mmio.c:337
Inline: False
```
**Symbols:**

```
c09440b8-c09441e4: vm_del_vqs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void vm_del_vqs(struct virtio_device *vdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_mmio.c (c0000000008d14f0)
Location: drivers/virtio/virtio_mmio.c:337
Inline: False
```
**Symbols:**

```
c0000000008d14f0-c0000000008d171c: vm_del_vqs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void vm_del_vqs(struct virtio_device *vdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_mmio.c (ffffffe00051c40a)
Location: drivers/virtio/virtio_mmio.c:337
Inline: False
```
**Symbols:**

```
ffffffe00051c40a-ffffffe00051c586: vm_del_vqs (STB_LOCAL)
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
void vm_del_vqs(struct virtio_device *vdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_mmio.c (ffffffff816232e0)
Location: drivers/virtio/virtio_mmio.c:337
Inline: False
```
**Symbols:**

```
ffffffff816232e0-ffffffff81623403: vm_del_vqs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void vm_del_vqs(struct virtio_device *vdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_mmio.c (ffffffff81617930)
Location: drivers/virtio/virtio_mmio.c:337
Inline: False
```
**Symbols:**

```
ffffffff81617930-ffffffff81617a53: vm_del_vqs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void vm_del_vqs(struct virtio_device *vdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_mmio.c (ffffffff81651280)
Location: drivers/virtio/virtio_mmio.c:337
Inline: False
```
**Symbols:**

```
ffffffff81651280-ffffffff816513a3: vm_del_vqs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void vm_del_vqs(struct virtio_device *vdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_mmio.c (ffffffff8166b910)
Location: drivers/virtio/virtio_mmio.c:337
Inline: False
```
**Symbols:**

```
ffffffff8166b910-ffffffff8166ba33: vm_del_vqs (STB_LOCAL)
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
