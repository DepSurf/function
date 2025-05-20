# Function: <code>to_vp_device</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_modern.c (0)
Location: drivers/virtio/virtio_pci_common.h:127
Inline: True
```
```
In drivers/virtio/virtio_pci_common.c (0)
Location: drivers/virtio/virtio_pci_common.h:127
Inline: True
```
```
In drivers/virtio/virtio_pci_legacy.c (0)
Location: drivers/virtio/virtio_pci_common.h:127
Inline: True
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
In drivers/virtio/virtio_pci_modern.c (0)
Location: drivers/virtio/virtio_pci_common.h:121
Inline: True
```
```
In drivers/virtio/virtio_pci_common.c (0)
Location: drivers/virtio/virtio_pci_common.h:121
Inline: True
```
```
In drivers/virtio/virtio_pci_legacy.c (0)
Location: drivers/virtio/virtio_pci_common.h:121
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_modern.c (0)
Location: drivers/virtio/virtio_pci_common.h:120
Inline: True
```
```
In drivers/virtio/virtio_pci_common.c (0)
Location: drivers/virtio/virtio_pci_common.h:120
Inline: True
```
```
In drivers/virtio/virtio_pci_legacy.c (0)
Location: drivers/virtio/virtio_pci_common.h:120
Inline: True
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
In drivers/virtio/virtio_pci_modern.c (0)
Location: drivers/virtio/virtio_pci_common.h:121
Inline: True
```
```
In drivers/virtio/virtio_pci_common.c (0)
Location: drivers/virtio/virtio_pci_common.h:121
Inline: True
```
```
In drivers/virtio/virtio_pci_legacy.c (0)
Location: drivers/virtio/virtio_pci_common.h:121
Inline: True
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
In drivers/virtio/virtio_pci_modern.c (0)
Location: drivers/virtio/virtio_pci_common.h:121
Inline: True
```
```
In drivers/virtio/virtio_pci_common.c (0)
Location: drivers/virtio/virtio_pci_common.h:121
Inline: True
```
```
In drivers/virtio/virtio_pci_legacy.c (0)
Location: drivers/virtio/virtio_pci_common.h:121
Inline: True
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
In drivers/virtio/virtio_pci_modern.c (ffffffff815ed424)
Location: drivers/virtio/virtio_pci_common.h:121
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_modern.c:del_vq
  - drivers/virtio/virtio_pci_modern.c:vp_reset
  - drivers/virtio/virtio_pci_modern.c:vp_get_status
  - drivers/virtio/virtio_pci_modern.c:vp_generation
  - drivers/virtio/virtio_pci_modern.c:vp_set
  - drivers/virtio/virtio_pci_modern.c:vp_get
  - drivers/virtio/virtio_pci_modern.c:vp_finalize_features
  - drivers/virtio/virtio_pci_modern.c:vp_finalize_features
  - drivers/virtio/virtio_pci_modern.c:vp_get_features
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff815ee6a5)
Location: drivers/virtio/virtio_pci_common.h:121
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:virtio_pci_release_dev
  - drivers/virtio/virtio_pci_common.c:vp_get_vq_affinity
  - drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity
  - drivers/virtio/virtio_pci_common.c:vp_bus_name
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/virtio/virtio_pci_common.c:vp_setup_vq
  - drivers/virtio/virtio_pci_common.c:vp_synchronize_vectors
```
```
In drivers/virtio/virtio_pci_legacy.c (ffffffff815ef6b4)
Location: drivers/virtio/virtio_pci_common.h:121
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_legacy.c:del_vq
  - drivers/virtio/virtio_pci_legacy.c:vp_reset
  - drivers/virtio/virtio_pci_legacy.c:vp_get_status
  - drivers/virtio/virtio_pci_legacy.c:vp_set
  - drivers/virtio/virtio_pci_legacy.c:vp_get
  - drivers/virtio/virtio_pci_legacy.c:vp_get_features
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
In drivers/virtio/virtio_pci_modern.c (ffffffff81607d04)
Location: drivers/virtio/virtio_pci_common.h:121
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_modern.c:del_vq
  - drivers/virtio/virtio_pci_modern.c:vp_reset
  - drivers/virtio/virtio_pci_modern.c:vp_get_status
  - drivers/virtio/virtio_pci_modern.c:vp_generation
  - drivers/virtio/virtio_pci_modern.c:vp_set
  - drivers/virtio/virtio_pci_modern.c:vp_get
  - drivers/virtio/virtio_pci_modern.c:vp_finalize_features
  - drivers/virtio/virtio_pci_modern.c:vp_finalize_features
  - drivers/virtio/virtio_pci_modern.c:vp_get_features
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff81608da5)
Location: drivers/virtio/virtio_pci_common.h:121
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:virtio_pci_release_dev
  - drivers/virtio/virtio_pci_common.c:vp_get_vq_affinity
  - drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity
  - drivers/virtio/virtio_pci_common.c:vp_bus_name
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/virtio/virtio_pci_common.c:vp_setup_vq
  - drivers/virtio/virtio_pci_common.c:vp_synchronize_vectors
```
```
In drivers/virtio/virtio_pci_legacy.c (ffffffff81609dd4)
Location: drivers/virtio/virtio_pci_common.h:121
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_legacy.c:del_vq
  - drivers/virtio/virtio_pci_legacy.c:vp_reset
  - drivers/virtio/virtio_pci_legacy.c:vp_get_status
  - drivers/virtio/virtio_pci_legacy.c:vp_set
  - drivers/virtio/virtio_pci_legacy.c:vp_get
  - drivers/virtio/virtio_pci_legacy.c:vp_get_features
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
In drivers/virtio/virtio_pci_modern.c (ffffffff8163bb64)
Location: drivers/virtio/virtio_pci_common.h:118
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_modern.c:del_vq
  - drivers/virtio/virtio_pci_modern.c:vp_reset
  - drivers/virtio/virtio_pci_modern.c:vp_get_status
  - drivers/virtio/virtio_pci_modern.c:vp_generation
  - drivers/virtio/virtio_pci_modern.c:vp_set
  - drivers/virtio/virtio_pci_modern.c:vp_get
  - drivers/virtio/virtio_pci_modern.c:vp_finalize_features
  - drivers/virtio/virtio_pci_modern.c:vp_finalize_features
  - drivers/virtio/virtio_pci_modern.c:vp_get_features
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff8163cbf5)
Location: drivers/virtio/virtio_pci_common.h:118
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:virtio_pci_release_dev
  - drivers/virtio/virtio_pci_common.c:vp_get_vq_affinity
  - drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity
  - drivers/virtio/virtio_pci_common.c:vp_bus_name
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/virtio/virtio_pci_common.c:vp_setup_vq
  - drivers/virtio/virtio_pci_common.c:vp_synchronize_vectors
```
```
In drivers/virtio/virtio_pci_legacy.c (ffffffff8163dbb4)
Location: drivers/virtio/virtio_pci_common.h:118
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_legacy.c:del_vq
  - drivers/virtio/virtio_pci_legacy.c:vp_reset
  - drivers/virtio/virtio_pci_legacy.c:vp_get_status
  - drivers/virtio/virtio_pci_legacy.c:vp_set
  - drivers/virtio/virtio_pci_legacy.c:vp_get
  - drivers/virtio/virtio_pci_legacy.c:vp_get_features
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
In drivers/virtio/virtio_pci_modern.c (ffffffff8165e014)
Location: drivers/virtio/virtio_pci_common.h:118
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_modern.c:del_vq
  - drivers/virtio/virtio_pci_modern.c:vp_reset
  - drivers/virtio/virtio_pci_modern.c:vp_get_status
  - drivers/virtio/virtio_pci_modern.c:vp_generation
  - drivers/virtio/virtio_pci_modern.c:vp_set
  - drivers/virtio/virtio_pci_modern.c:vp_get
  - drivers/virtio/virtio_pci_modern.c:vp_finalize_features
  - drivers/virtio/virtio_pci_modern.c:vp_finalize_features
  - drivers/virtio/virtio_pci_modern.c:vp_get_features
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff8165f0d5)
Location: drivers/virtio/virtio_pci_common.h:118
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:virtio_pci_release_dev
  - drivers/virtio/virtio_pci_common.c:vp_get_vq_affinity
  - drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity
  - drivers/virtio/virtio_pci_common.c:vp_bus_name
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/virtio/virtio_pci_common.c:vp_setup_vq
  - drivers/virtio/virtio_pci_common.c:vp_synchronize_vectors
```
```
In drivers/virtio/virtio_pci_legacy.c (ffffffff81660094)
Location: drivers/virtio/virtio_pci_common.h:118
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_legacy.c:del_vq
  - drivers/virtio/virtio_pci_legacy.c:vp_reset
  - drivers/virtio/virtio_pci_legacy.c:vp_get_status
  - drivers/virtio/virtio_pci_legacy.c:vp_set
  - drivers/virtio/virtio_pci_legacy.c:vp_get
  - drivers/virtio/virtio_pci_legacy.c:vp_get_features
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
In drivers/virtio/virtio_pci_modern.c (ffffffff8170d124)
Location: drivers/virtio/virtio_pci_common.h:118
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_modern.c:del_vq
  - drivers/virtio/virtio_pci_modern.c:vp_reset
  - drivers/virtio/virtio_pci_modern.c:vp_get_status
  - drivers/virtio/virtio_pci_modern.c:vp_generation
  - drivers/virtio/virtio_pci_modern.c:vp_set
  - drivers/virtio/virtio_pci_modern.c:vp_get
  - drivers/virtio/virtio_pci_modern.c:vp_finalize_features
  - drivers/virtio/virtio_pci_modern.c:vp_finalize_features
  - drivers/virtio/virtio_pci_modern.c:vp_get_features
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff8170e1a5)
Location: drivers/virtio/virtio_pci_common.h:118
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:virtio_pci_release_dev
  - drivers/virtio/virtio_pci_common.c:vp_get_vq_affinity
  - drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity
  - drivers/virtio/virtio_pci_common.c:vp_bus_name
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_intx
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/virtio/virtio_pci_common.c:vp_setup_vq
  - drivers/virtio/virtio_pci_common.c:vp_request_msix_vectors
  - drivers/virtio/virtio_pci_common.c:vp_synchronize_vectors
```
```
In drivers/virtio/virtio_pci_legacy.c (ffffffff8170f284)
Location: drivers/virtio/virtio_pci_common.h:118
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_legacy.c:del_vq
  - drivers/virtio/virtio_pci_legacy.c:vp_reset
  - drivers/virtio/virtio_pci_legacy.c:vp_get_status
  - drivers/virtio/virtio_pci_legacy.c:vp_set
  - drivers/virtio/virtio_pci_legacy.c:vp_get
  - drivers/virtio/virtio_pci_legacy.c:vp_get_features
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
In drivers/virtio/virtio_pci_modern.c (ffffffff8172a05d)
Location: drivers/virtio/virtio_pci_common.h:118
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_modern.c:vp_get_shm_region
  - drivers/virtio/virtio_pci_modern.c:del_vq
  - drivers/virtio/virtio_pci_modern.c:vp_reset
  - drivers/virtio/virtio_pci_modern.c:vp_get_status
  - drivers/virtio/virtio_pci_modern.c:vp_generation
  - drivers/virtio/virtio_pci_modern.c:vp_set
  - drivers/virtio/virtio_pci_modern.c:vp_get
  - drivers/virtio/virtio_pci_modern.c:vp_finalize_features
  - drivers/virtio/virtio_pci_modern.c:vp_finalize_features
  - drivers/virtio/virtio_pci_modern.c:vp_get_features
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff8172af95)
Location: drivers/virtio/virtio_pci_common.h:118
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:virtio_pci_release_dev
  - drivers/virtio/virtio_pci_common.c:vp_get_vq_affinity
  - drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity
  - drivers/virtio/virtio_pci_common.c:vp_bus_name
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_intx
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/virtio/virtio_pci_common.c:vp_setup_vq
  - drivers/virtio/virtio_pci_common.c:vp_request_msix_vectors
  - drivers/virtio/virtio_pci_common.c:vp_synchronize_vectors
```
```
In drivers/virtio/virtio_pci_legacy.c (ffffffff8172c054)
Location: drivers/virtio/virtio_pci_common.h:118
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_legacy.c:del_vq
  - drivers/virtio/virtio_pci_legacy.c:vp_reset
  - drivers/virtio/virtio_pci_legacy.c:vp_get_status
  - drivers/virtio/virtio_pci_legacy.c:vp_set
  - drivers/virtio/virtio_pci_legacy.c:vp_get
  - drivers/virtio/virtio_pci_legacy.c:vp_get_features
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
In drivers/virtio/virtio_pci_modern.c (ffffffff8170e7b7)
Location: drivers/virtio/virtio_pci_common.h:100
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_modern.c:vp_get_shm_region
  - drivers/virtio/virtio_pci_modern.c:del_vq
  - drivers/virtio/virtio_pci_modern.c:vp_reset
  - drivers/virtio/virtio_pci_modern.c:vp_get_status
  - drivers/virtio/virtio_pci_modern.c:vp_generation
  - drivers/virtio/virtio_pci_modern.c:vp_set
  - drivers/virtio/virtio_pci_modern.c:vp_get
  - drivers/virtio/virtio_pci_modern.c:vp_finalize_features
  - drivers/virtio/virtio_pci_modern.c:vp_finalize_features
  - drivers/virtio/virtio_pci_modern.c:vp_get_features
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff8170ed15)
Location: drivers/virtio/virtio_pci_common.h:100
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:virtio_pci_release_dev
  - drivers/virtio/virtio_pci_common.c:vp_get_vq_affinity
  - drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity
  - drivers/virtio/virtio_pci_common.c:vp_bus_name
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/virtio/virtio_pci_common.c:vp_setup_vq
  - drivers/virtio/virtio_pci_common.c:vp_request_msix_vectors
  - drivers/virtio/virtio_pci_common.c:vp_synchronize_vectors
```
```
In drivers/virtio/virtio_pci_legacy.c (ffffffff8170fda4)
Location: drivers/virtio/virtio_pci_common.h:100
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_legacy.c:del_vq
  - drivers/virtio/virtio_pci_legacy.c:vp_reset
  - drivers/virtio/virtio_pci_legacy.c:vp_get_status
  - drivers/virtio/virtio_pci_legacy.c:vp_set
  - drivers/virtio/virtio_pci_legacy.c:vp_get
  - drivers/virtio/virtio_pci_legacy.c:vp_get_features
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
In drivers/virtio/virtio_pci_modern.c (ffffffff8178b047)
Location: drivers/virtio/virtio_pci_common.h:100
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_modern.c:vp_get_shm_region
  - drivers/virtio/virtio_pci_modern.c:del_vq
  - drivers/virtio/virtio_pci_modern.c:vp_reset
  - drivers/virtio/virtio_pci_modern.c:vp_set_status
  - drivers/virtio/virtio_pci_modern.c:vp_get_status
  - drivers/virtio/virtio_pci_modern.c:vp_generation
  - drivers/virtio/virtio_pci_modern.c:vp_set
  - drivers/virtio/virtio_pci_modern.c:vp_get
  - drivers/virtio/virtio_pci_modern.c:vp_finalize_features
  - drivers/virtio/virtio_pci_modern.c:vp_finalize_features
  - drivers/virtio/virtio_pci_modern.c:vp_get_features
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff8178b645)
Location: drivers/virtio/virtio_pci_common.h:100
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:virtio_pci_release_dev
  - drivers/virtio/virtio_pci_common.c:vp_get_vq_affinity
  - drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity
  - drivers/virtio/virtio_pci_common.c:vp_bus_name
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/virtio/virtio_pci_common.c:vp_setup_vq
  - drivers/virtio/virtio_pci_common.c:vp_request_msix_vectors
  - drivers/virtio/virtio_pci_common.c:vp_synchronize_vectors
```
```
In drivers/virtio/virtio_pci_legacy.c (ffffffff8178c784)
Location: drivers/virtio/virtio_pci_common.h:100
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_legacy.c:del_vq
  - drivers/virtio/virtio_pci_legacy.c:vp_reset
  - drivers/virtio/virtio_pci_legacy.c:vp_set_status
  - drivers/virtio/virtio_pci_legacy.c:vp_get_status
  - drivers/virtio/virtio_pci_legacy.c:vp_set
  - drivers/virtio/virtio_pci_legacy.c:vp_get
  - drivers/virtio/virtio_pci_legacy.c:vp_finalize_features
  - drivers/virtio/virtio_pci_legacy.c:vp_get_features
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
In drivers/virtio/virtio_pci_modern.c (0)
Location: drivers/virtio/virtio_pci_common.h:99
Inline: True
```
```
In drivers/virtio/virtio_pci_common.c (0)
Location: drivers/virtio/virtio_pci_common.h:99
Inline: True
```
```
In drivers/virtio/virtio_pci_legacy.c (0)
Location: drivers/virtio/virtio_pci_common.h:99
Inline: True
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
In drivers/virtio/virtio_pci_modern.c (0)
Location: drivers/virtio/virtio_pci_common.h:99
Inline: True
```
```
In drivers/virtio/virtio_pci_common.c (0)
Location: drivers/virtio/virtio_pci_common.h:99
Inline: True
```
```
In drivers/virtio/virtio_pci_legacy.c (0)
Location: drivers/virtio/virtio_pci_common.h:99
Inline: True
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
In drivers/virtio/virtio_pci_modern.c (0)
Location: drivers/virtio/virtio_pci_common.h:100
Inline: True
```
```
In drivers/virtio/virtio_pci_common.c (0)
Location: drivers/virtio/virtio_pci_common.h:100
Inline: True
```
```
In drivers/virtio/virtio_pci_legacy.c (0)
Location: drivers/virtio/virtio_pci_common.h:100
Inline: True
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
In drivers/virtio/virtio_pci_modern.c (0)
Location: drivers/virtio/virtio_pci_common.h:117
Inline: True
```
```
In drivers/virtio/virtio_pci_common.c (0)
Location: drivers/virtio/virtio_pci_common.h:117
Inline: True
```
```
In drivers/virtio/virtio_pci_legacy.c (0)
Location: drivers/virtio/virtio_pci_common.h:117
Inline: True
```
```
In drivers/virtio/virtio_pci_admin_legacy_io.c (0)
Location: drivers/virtio/virtio_pci_common.h:117
Inline: True
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
In drivers/virtio/virtio_pci_modern.c (ffff800010827470)
Location: drivers/virtio/virtio_pci_common.h:118
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_modern.c:del_vq
  - drivers/virtio/virtio_pci_modern.c:vp_reset
  - drivers/virtio/virtio_pci_modern.c:vp_get_status
  - drivers/virtio/virtio_pci_modern.c:vp_generation
  - drivers/virtio/virtio_pci_modern.c:vp_set
  - drivers/virtio/virtio_pci_modern.c:vp_get
  - drivers/virtio/virtio_pci_modern.c:vp_finalize_features
  - drivers/virtio/virtio_pci_modern.c:vp_finalize_features
  - drivers/virtio/virtio_pci_modern.c:vp_get_features
```
```
In drivers/virtio/virtio_pci_common.c (ffff800010827ef0)
Location: drivers/virtio/virtio_pci_common.h:118
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:virtio_pci_release_dev
  - drivers/virtio/virtio_pci_common.c:vp_get_vq_affinity
  - drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity
  - drivers/virtio/virtio_pci_common.c:vp_bus_name
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/virtio/virtio_pci_common.c:vp_setup_vq
  - drivers/virtio/virtio_pci_common.c:vp_synchronize_vectors
```
```
In drivers/virtio/virtio_pci_legacy.c (ffff800010829028)
Location: drivers/virtio/virtio_pci_common.h:118
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_legacy.c:del_vq
  - drivers/virtio/virtio_pci_legacy.c:vp_reset
  - drivers/virtio/virtio_pci_legacy.c:vp_get_status
  - drivers/virtio/virtio_pci_legacy.c:vp_set
  - drivers/virtio/virtio_pci_legacy.c:vp_get
  - drivers/virtio/virtio_pci_legacy.c:vp_get_features
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
In drivers/virtio/virtio_pci_modern.c (c0944dfc)
Location: drivers/virtio/virtio_pci_common.h:118
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_modern.c:del_vq
  - drivers/virtio/virtio_pci_modern.c:vp_reset
  - drivers/virtio/virtio_pci_modern.c:vp_get_status
  - drivers/virtio/virtio_pci_modern.c:vp_generation
  - drivers/virtio/virtio_pci_modern.c:vp_set
  - drivers/virtio/virtio_pci_modern.c:vp_get
  - drivers/virtio/virtio_pci_modern.c:vp_finalize_features
  - drivers/virtio/virtio_pci_modern.c:vp_finalize_features
  - drivers/virtio/virtio_pci_modern.c:vp_get_features
```
```
In drivers/virtio/virtio_pci_common.c (c0945de0)
Location: drivers/virtio/virtio_pci_common.h:118
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:virtio_pci_release_dev
  - drivers/virtio/virtio_pci_common.c:vp_get_vq_affinity
  - drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity
  - drivers/virtio/virtio_pci_common.c:vp_bus_name
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/virtio/virtio_pci_common.c:vp_setup_vq
  - drivers/virtio/virtio_pci_common.c:vp_synchronize_vectors
```
```
In drivers/virtio/virtio_pci_legacy.c (c0946cac)
Location: drivers/virtio/virtio_pci_common.h:118
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_legacy.c:del_vq
  - drivers/virtio/virtio_pci_legacy.c:vp_reset
  - drivers/virtio/virtio_pci_legacy.c:vp_get_status
  - drivers/virtio/virtio_pci_legacy.c:vp_set
  - drivers/virtio/virtio_pci_legacy.c:vp_get
  - drivers/virtio/virtio_pci_legacy.c:vp_get_features
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
In drivers/virtio/virtio_pci_modern.c (c0000000008d2a2c)
Location: drivers/virtio/virtio_pci_common.h:118
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_modern.c:del_vq
  - drivers/virtio/virtio_pci_modern.c:vp_reset
  - drivers/virtio/virtio_pci_modern.c:vp_set_status
  - drivers/virtio/virtio_pci_modern.c:vp_get_status
  - drivers/virtio/virtio_pci_modern.c:vp_generation
  - drivers/virtio/virtio_pci_modern.c:vp_set
  - drivers/virtio/virtio_pci_modern.c:vp_get
  - drivers/virtio/virtio_pci_modern.c:vp_finalize_features
  - drivers/virtio/virtio_pci_modern.c:vp_finalize_features
  - drivers/virtio/virtio_pci_modern.c:vp_get_features
```
```
In drivers/virtio/virtio_pci_common.c (c0000000008d405c)
Location: drivers/virtio/virtio_pci_common.h:118
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:virtio_pci_release_dev
  - drivers/virtio/virtio_pci_common.c:vp_get_vq_affinity
  - drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity
  - drivers/virtio/virtio_pci_common.c:vp_bus_name
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/virtio/virtio_pci_common.c:vp_setup_vq
  - drivers/virtio/virtio_pci_common.c:vp_synchronize_vectors
```
```
In drivers/virtio/virtio_pci_legacy.c (c0000000008d57ac)
Location: drivers/virtio/virtio_pci_common.h:118
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_legacy.c:del_vq
  - drivers/virtio/virtio_pci_legacy.c:vp_reset
  - drivers/virtio/virtio_pci_legacy.c:vp_set_status
  - drivers/virtio/virtio_pci_legacy.c:vp_get_status
  - drivers/virtio/virtio_pci_legacy.c:vp_set
  - drivers/virtio/virtio_pci_legacy.c:vp_get
  - drivers/virtio/virtio_pci_legacy.c:vp_finalize_features
  - drivers/virtio/virtio_pci_legacy.c:vp_get_features
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
In drivers/virtio/virtio_pci_modern.c (ffffffe00051d53e)
Location: drivers/virtio/virtio_pci_common.h:118
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_modern.c:del_vq
  - drivers/virtio/virtio_pci_modern.c:vp_reset
  - drivers/virtio/virtio_pci_modern.c:vp_get_status
  - drivers/virtio/virtio_pci_modern.c:vp_generation
  - drivers/virtio/virtio_pci_modern.c:vp_set
  - drivers/virtio/virtio_pci_modern.c:vp_get
  - drivers/virtio/virtio_pci_modern.c:vp_finalize_features
  - drivers/virtio/virtio_pci_modern.c:vp_finalize_features
  - drivers/virtio/virtio_pci_modern.c:vp_get_features
```
```
In drivers/virtio/virtio_pci_common.c (ffffffe00051e50a)
Location: drivers/virtio/virtio_pci_common.h:118
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:virtio_pci_release_dev
  - drivers/virtio/virtio_pci_common.c:vp_get_vq_affinity
  - drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity
  - drivers/virtio/virtio_pci_common.c:vp_bus_name
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/virtio/virtio_pci_common.c:vp_setup_vq
  - drivers/virtio/virtio_pci_common.c:vp_synchronize_vectors
```
```
In drivers/virtio/virtio_pci_legacy.c (ffffffe00051f492)
Location: drivers/virtio/virtio_pci_common.h:118
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_legacy.c:del_vq
  - drivers/virtio/virtio_pci_legacy.c:vp_reset
  - drivers/virtio/virtio_pci_legacy.c:vp_get_status
  - drivers/virtio/virtio_pci_legacy.c:vp_set
  - drivers/virtio/virtio_pci_legacy.c:vp_get
  - drivers/virtio/virtio_pci_legacy.c:vp_get_features
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
In drivers/virtio/virtio_pci_modern.c (ffffffff81623eb4)
Location: drivers/virtio/virtio_pci_common.h:118
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_modern.c:del_vq
  - drivers/virtio/virtio_pci_modern.c:vp_reset
  - drivers/virtio/virtio_pci_modern.c:vp_get_status
  - drivers/virtio/virtio_pci_modern.c:vp_generation
  - drivers/virtio/virtio_pci_modern.c:vp_set
  - drivers/virtio/virtio_pci_modern.c:vp_get
  - drivers/virtio/virtio_pci_modern.c:vp_finalize_features
  - drivers/virtio/virtio_pci_modern.c:vp_finalize_features
  - drivers/virtio/virtio_pci_modern.c:vp_get_features
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff81624f45)
Location: drivers/virtio/virtio_pci_common.h:118
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:virtio_pci_release_dev
  - drivers/virtio/virtio_pci_common.c:vp_get_vq_affinity
  - drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity
  - drivers/virtio/virtio_pci_common.c:vp_bus_name
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/virtio/virtio_pci_common.c:vp_setup_vq
  - drivers/virtio/virtio_pci_common.c:vp_synchronize_vectors
```
```
In drivers/virtio/virtio_pci_legacy.c (ffffffff81625f04)
Location: drivers/virtio/virtio_pci_common.h:118
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_legacy.c:del_vq
  - drivers/virtio/virtio_pci_legacy.c:vp_reset
  - drivers/virtio/virtio_pci_legacy.c:vp_get_status
  - drivers/virtio/virtio_pci_legacy.c:vp_set
  - drivers/virtio/virtio_pci_legacy.c:vp_get
  - drivers/virtio/virtio_pci_legacy.c:vp_get_features
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
In drivers/virtio/virtio_pci_modern.c (ffffffff81618504)
Location: drivers/virtio/virtio_pci_common.h:118
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_modern.c:del_vq
  - drivers/virtio/virtio_pci_modern.c:vp_reset
  - drivers/virtio/virtio_pci_modern.c:vp_get_status
  - drivers/virtio/virtio_pci_modern.c:vp_generation
  - drivers/virtio/virtio_pci_modern.c:vp_set
  - drivers/virtio/virtio_pci_modern.c:vp_get
  - drivers/virtio/virtio_pci_modern.c:vp_finalize_features
  - drivers/virtio/virtio_pci_modern.c:vp_finalize_features
  - drivers/virtio/virtio_pci_modern.c:vp_get_features
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff816195c5)
Location: drivers/virtio/virtio_pci_common.h:118
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:virtio_pci_release_dev
  - drivers/virtio/virtio_pci_common.c:vp_get_vq_affinity
  - drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity
  - drivers/virtio/virtio_pci_common.c:vp_bus_name
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/virtio/virtio_pci_common.c:vp_setup_vq
  - drivers/virtio/virtio_pci_common.c:vp_synchronize_vectors
```
```
In drivers/virtio/virtio_pci_legacy.c (ffffffff8161a584)
Location: drivers/virtio/virtio_pci_common.h:118
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_legacy.c:del_vq
  - drivers/virtio/virtio_pci_legacy.c:vp_reset
  - drivers/virtio/virtio_pci_legacy.c:vp_get_status
  - drivers/virtio/virtio_pci_legacy.c:vp_set
  - drivers/virtio/virtio_pci_legacy.c:vp_get
  - drivers/virtio/virtio_pci_legacy.c:vp_get_features
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
In drivers/virtio/virtio_pci_modern.c (ffffffff81651e54)
Location: drivers/virtio/virtio_pci_common.h:118
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_modern.c:del_vq
  - drivers/virtio/virtio_pci_modern.c:vp_reset
  - drivers/virtio/virtio_pci_modern.c:vp_get_status
  - drivers/virtio/virtio_pci_modern.c:vp_generation
  - drivers/virtio/virtio_pci_modern.c:vp_set
  - drivers/virtio/virtio_pci_modern.c:vp_get
  - drivers/virtio/virtio_pci_modern.c:vp_finalize_features
  - drivers/virtio/virtio_pci_modern.c:vp_finalize_features
  - drivers/virtio/virtio_pci_modern.c:vp_get_features
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff81652f15)
Location: drivers/virtio/virtio_pci_common.h:118
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:virtio_pci_release_dev
  - drivers/virtio/virtio_pci_common.c:vp_get_vq_affinity
  - drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity
  - drivers/virtio/virtio_pci_common.c:vp_bus_name
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/virtio/virtio_pci_common.c:vp_setup_vq
  - drivers/virtio/virtio_pci_common.c:vp_synchronize_vectors
```
```
In drivers/virtio/virtio_pci_legacy.c (ffffffff81653ed4)
Location: drivers/virtio/virtio_pci_common.h:118
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_legacy.c:del_vq
  - drivers/virtio/virtio_pci_legacy.c:vp_reset
  - drivers/virtio/virtio_pci_legacy.c:vp_get_status
  - drivers/virtio/virtio_pci_legacy.c:vp_set
  - drivers/virtio/virtio_pci_legacy.c:vp_get
  - drivers/virtio/virtio_pci_legacy.c:vp_get_features
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
In drivers/virtio/virtio_pci_modern.c (ffffffff8166c4e4)
Location: drivers/virtio/virtio_pci_common.h:118
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_modern.c:del_vq
  - drivers/virtio/virtio_pci_modern.c:vp_reset
  - drivers/virtio/virtio_pci_modern.c:vp_get_status
  - drivers/virtio/virtio_pci_modern.c:vp_generation
  - drivers/virtio/virtio_pci_modern.c:vp_set
  - drivers/virtio/virtio_pci_modern.c:vp_get
  - drivers/virtio/virtio_pci_modern.c:vp_finalize_features
  - drivers/virtio/virtio_pci_modern.c:vp_finalize_features
  - drivers/virtio/virtio_pci_modern.c:vp_get_features
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff8166d5a5)
Location: drivers/virtio/virtio_pci_common.h:118
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:virtio_pci_release_dev
  - drivers/virtio/virtio_pci_common.c:vp_get_vq_affinity
  - drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity
  - drivers/virtio/virtio_pci_common.c:vp_bus_name
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/virtio/virtio_pci_common.c:vp_setup_vq
  - drivers/virtio/virtio_pci_common.c:vp_synchronize_vectors
```
```
In drivers/virtio/virtio_pci_legacy.c (ffffffff8166e564)
Location: drivers/virtio/virtio_pci_common.h:118
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_legacy.c:del_vq
  - drivers/virtio/virtio_pci_legacy.c:vp_reset
  - drivers/virtio/virtio_pci_legacy.c:vp_get_status
  - drivers/virtio/virtio_pci_legacy.c:vp_set
  - drivers/virtio/virtio_pci_legacy.c:vp_get
  - drivers/virtio/virtio_pci_legacy.c:vp_get_features
```
</details>
</li>
</ul>

## Differences
