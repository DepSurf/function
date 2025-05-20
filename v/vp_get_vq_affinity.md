# Function: <code>vp_get_vq_affinity</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
const struct cpumask *vp_get_vq_affinity(struct virtio_device *vdev, int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_common.c (ffffffff81553750)
Location: drivers/virtio/virtio_pci_common.c:448
Inline: False
```
**Symbols:**

```
ffffffff81553750-ffffffff8155378c: vp_get_vq_affinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
const struct cpumask *vp_get_vq_affinity(struct virtio_device *vdev, int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_common.c (ffffffff815b70d0)
Location: drivers/virtio/virtio_pci_common.c:448
Inline: False
```
**Symbols:**

```
ffffffff815b70d0-ffffffff815b710c: vp_get_vq_affinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
const struct cpumask *vp_get_vq_affinity(struct virtio_device *vdev, int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_common.c (ffffffff815ef5d0)
Location: drivers/virtio/virtio_pci_common.c:449
Inline: False
```
**Symbols:**

```
ffffffff815ef5d0-ffffffff815ef60c: vp_get_vq_affinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
const struct cpumask *vp_get_vq_affinity(struct virtio_device *vdev, int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_common.c (ffffffff81609cf0)
Location: drivers/virtio/virtio_pci_common.c:448
Inline: False
```
**Symbols:**

```
ffffffff81609cf0-ffffffff81609d2c: vp_get_vq_affinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
const struct cpumask *vp_get_vq_affinity(struct virtio_device *vdev, int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_common.c (ffffffff8163dad0)
Location: drivers/virtio/virtio_pci_common.c:447
Inline: False
```
**Symbols:**

```
ffffffff8163dad0-ffffffff8163db0c: vp_get_vq_affinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
const struct cpumask *vp_get_vq_affinity(struct virtio_device *vdev, int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_common.c (ffffffff8165ffb0)
Location: drivers/virtio/virtio_pci_common.c:447
Inline: False
```
**Symbols:**

```
ffffffff8165ffb0-ffffffff8165ffec: vp_get_vq_affinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
const struct cpumask *vp_get_vq_affinity(struct virtio_device *vdev, int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_common.c (ffffffff8170f1a0)
Location: drivers/virtio/virtio_pci_common.c:447
Inline: False
```
**Symbols:**

```
ffffffff8170f1a0-ffffffff8170f1dc: vp_get_vq_affinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
const struct cpumask *vp_get_vq_affinity(struct virtio_device *vdev, int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_common.c (ffffffff8172bf70)
Location: drivers/virtio/virtio_pci_common.c:447
Inline: False
```
**Symbols:**

```
ffffffff8172bf70-ffffffff8172bfac: vp_get_vq_affinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
const struct cpumask *vp_get_vq_affinity(struct virtio_device *vdev, int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_common.c (ffffffff8170fcc0)
Location: drivers/virtio/virtio_pci_common.c:447
Inline: False
```
**Symbols:**

```
ffffffff8170fcc0-ffffffff8170fcfc: vp_get_vq_affinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
const struct cpumask *vp_get_vq_affinity(struct virtio_device *vdev, int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_pci_common.c (0)
Location: drivers/virtio/virtio_pci_common.c:447
Inline: False
```
**Symbols:**

```
ffffffff81cf5149-ffffffff81cf515e: vp_get_vq_affinity.cold (STB_LOCAL)
ffffffff8178c670-ffffffff8178c6d1: vp_get_vq_affinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
const struct cpumask *vp_get_vq_affinity(struct virtio_device *vdev, int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_pci_common.c (0)
Location: drivers/virtio/virtio_pci_common.c:446
Inline: False
```
**Symbols:**

```
ffffffff81ebd2b6-ffffffff81ebd2cb: vp_get_vq_affinity.cold (STB_LOCAL)
ffffffff818c4300-ffffffff818c4371: vp_get_vq_affinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
const struct cpumask *vp_get_vq_affinity(struct virtio_device *vdev, int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_pci_common.c (0)
Location: drivers/virtio/virtio_pci_common.c:455
Inline: False
```
**Symbols:**

```
ffffffff820945cd-ffffffff820945e2: vp_get_vq_affinity.cold (STB_LOCAL)
ffffffff81a14a00-ffffffff81a14a71: vp_get_vq_affinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
const struct cpumask *vp_get_vq_affinity(struct virtio_device *vdev, int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_pci_common.c (0)
Location: drivers/virtio/virtio_pci_common.c:455
Inline: False
```
**Symbols:**

```
ffffffff82115342-ffffffff82115357: vp_get_vq_affinity.cold (STB_LOCAL)
ffffffff81a5dab0-ffffffff81a5db21: vp_get_vq_affinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
const struct cpumask *vp_get_vq_affinity(struct virtio_device *vdev, int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_pci_common.c (0)
Location: drivers/virtio/virtio_pci_common.c:458
Inline: False
```
**Symbols:**

```
ffffffff821f2f9d-ffffffff821f2fb2: vp_get_vq_affinity.cold (STB_LOCAL)
ffffffff81aafa60-ffffffff81aafad1: vp_get_vq_affinity (STB_GLOBAL)
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
const struct cpumask *vp_get_vq_affinity(struct virtio_device *vdev, int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_common.c (ffff800010828ec8)
Location: drivers/virtio/virtio_pci_common.c:447
Inline: False
```
**Symbols:**

```
ffff800010828ec8-ffff800010828f28: vp_get_vq_affinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
const struct cpumask *vp_get_vq_affinity(struct virtio_device *vdev, int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_common.c (c0946b4c)
Location: drivers/virtio/virtio_pci_common.c:447
Inline: False
```
**Symbols:**

```
c0946b4c-c0946b98: vp_get_vq_affinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
const struct cpumask *vp_get_vq_affinity(struct virtio_device *vdev, int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_common.c (c0000000008d5610)
Location: drivers/virtio/virtio_pci_common.c:447
Inline: False
```
**Symbols:**

```
c0000000008d5610-c0000000008d5688: vp_get_vq_affinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
const struct cpumask *vp_get_vq_affinity(struct virtio_device *vdev, int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_common.c (ffffffe00051f250)
Location: drivers/virtio/virtio_pci_common.c:447
Inline: False
```
**Symbols:**

```
ffffffe00051f250-ffffffe00051f2ac: vp_get_vq_affinity (STB_GLOBAL)
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
const struct cpumask *vp_get_vq_affinity(struct virtio_device *vdev, int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_common.c (ffffffff81625e20)
Location: drivers/virtio/virtio_pci_common.c:447
Inline: False
```
**Symbols:**

```
ffffffff81625e20-ffffffff81625e5c: vp_get_vq_affinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
const struct cpumask *vp_get_vq_affinity(struct virtio_device *vdev, int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_common.c (ffffffff8161a4a0)
Location: drivers/virtio/virtio_pci_common.c:447
Inline: False
```
**Symbols:**

```
ffffffff8161a4a0-ffffffff8161a4dc: vp_get_vq_affinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
const struct cpumask *vp_get_vq_affinity(struct virtio_device *vdev, int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_common.c (ffffffff81653df0)
Location: drivers/virtio/virtio_pci_common.c:447
Inline: False
```
**Symbols:**

```
ffffffff81653df0-ffffffff81653e2c: vp_get_vq_affinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
const struct cpumask *vp_get_vq_affinity(struct virtio_device *vdev, int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_common.c (ffffffff8166e480)
Location: drivers/virtio/virtio_pci_common.c:447
Inline: False
```
**Symbols:**

```
ffffffff8166e480-ffffffff8166e4bc: vp_get_vq_affinity (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
