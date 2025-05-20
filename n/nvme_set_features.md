# Function: <code>nvme_set_features</code>

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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int nvme_set_features(struct nvme_ctrl *dev, unsigned int fid, unsigned int dword11, void *buffer, size_t buflen, u32 *result);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvme/host/core.c (ffffffff81747a44)
Location: drivers/nvme/host/core.c:1180
Inline: True
Inline callers:
  - drivers/nvme/host/core.c:nvme_init_identify
  - drivers/nvme/host/core.c:nvme_init_identify
  - drivers/nvme/host/core.c:nvme_set_queue_count
Direct callers:
  - drivers/nvme/host/pci.c:nvme_suspend
  - drivers/nvme/host/pci.c:nvme_resume
```
**Symbols:**

```
ffffffff81743e70-ffffffff81743e91: nvme_set_features (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int nvme_set_features(struct nvme_ctrl *dev, unsigned int fid, unsigned int dword11, void *buffer, size_t buflen, u32 *result);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvme/host/core.c (ffffffff81729694)
Location: drivers/nvme/host/core.c:1180
Inline: True
Inline callers:
  - drivers/nvme/host/core.c:nvme_init_identify
  - drivers/nvme/host/core.c:nvme_init_identify
  - drivers/nvme/host/core.c:nvme_set_queue_count
Direct callers:
  - drivers/nvme/host/pci.c:nvme_suspend
  - drivers/nvme/host/pci.c:nvme_resume
```
**Symbols:**

```
ffffffff81725b00-ffffffff81725b21: nvme_set_features (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Flavor</b>
<ul>
</ul>
