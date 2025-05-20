# Function: <code>nvme_features</code>

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
<summary>In <code>aws</code>: ✅</summary>

```c
int nvme_features(struct nvme_ctrl *dev, u8 op, unsigned int fid, unsigned int dword11, void *buffer, size_t buflen, u32 *result);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvme/host/core.c (ffffffff81743dc0)
Location: drivers/nvme/host/core.c:1161
Inline: False
Direct callers:
  - drivers/nvme/host/core.c:nvme_init_identify
  - drivers/nvme/host/core.c:nvme_init_identify
  - drivers/nvme/host/core.c:nvme_set_queue_count
  - drivers/nvme/host/core.c:nvme_get_features
```
**Symbols:**

```
ffffffff81743dc0-ffffffff81743e62: nvme_features (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int nvme_features(struct nvme_ctrl *dev, u8 op, unsigned int fid, unsigned int dword11, void *buffer, size_t buflen, u32 *result);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvme/host/core.c (ffffffff81725a50)
Location: drivers/nvme/host/core.c:1161
Inline: False
Direct callers:
  - drivers/nvme/host/core.c:nvme_init_identify
  - drivers/nvme/host/core.c:nvme_init_identify
  - drivers/nvme/host/core.c:nvme_set_queue_count
  - drivers/nvme/host/core.c:nvme_get_features
```
**Symbols:**

```
ffffffff81725a50-ffffffff81725af2: nvme_features (STB_LOCAL)
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
