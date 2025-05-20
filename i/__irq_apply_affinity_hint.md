# Function: <code>__irq_apply_affinity_hint</code>

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
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __irq_apply_affinity_hint(unsigned int irq, const struct cpumask *m, bool setaffinity);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff81163af0)
Location: kernel/irq/manage.c:504
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity
  - drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
```
**Symbols:**

```
ffffffff81163af0-ffffffff81163bd0: __irq_apply_affinity_hint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __irq_apply_affinity_hint(unsigned int irq, const struct cpumask *m, bool setaffinity);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff811977d0)
Location: kernel/irq/manage.c:496
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity
  - drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
```
**Symbols:**

```
ffffffff811977d0-ffffffff811978b0: __irq_apply_affinity_hint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __irq_apply_affinity_hint(unsigned int irq, const struct cpumask *m, bool setaffinity);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff811a9490)
Location: kernel/irq/manage.c:499
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity
  - drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
```
**Symbols:**

```
ffffffff811a9490-ffffffff811a9570: __irq_apply_affinity_hint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __irq_apply_affinity_hint(unsigned int irq, const struct cpumask *m, bool setaffinity);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff811b8ff0)
Location: kernel/irq/manage.c:501
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity
  - drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
```
**Symbols:**

```
ffffffff811b8ff0-ffffffff811b90d0: __irq_apply_affinity_hint (STB_GLOBAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
