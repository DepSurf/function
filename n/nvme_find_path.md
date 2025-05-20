# Function: <code>nvme_find_path</code>

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
struct nvme_ns *nvme_find_path(struct nvme_ns_head *head);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvme/host/multipath.c (ffffffff81749c83)
Location: drivers/nvme/host/multipath.c:265
Inline: True
Inline callers:
  - drivers/nvme/host/multipath.c:nvme_ns_head_make_request
Direct callers:
  - drivers/nvme/host/core.c:nvme_pr_command
  - drivers/nvme/host/core.c:nvme_ioctl
```
**Symbols:**

```
ffffffff8174a3c0-ffffffff8174a555: nvme_find_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct nvme_ns *nvme_find_path(struct nvme_ns_head *head);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvme/host/multipath.c (ffffffff8172b863)
Location: drivers/nvme/host/multipath.c:265
Inline: True
Inline callers:
  - drivers/nvme/host/multipath.c:nvme_ns_head_make_request
Direct callers:
  - drivers/nvme/host/core.c:nvme_pr_command
  - drivers/nvme/host/core.c:nvme_ioctl
```
**Symbols:**

```
ffffffff8172bfa0-ffffffff8172c135: nvme_find_path (STB_GLOBAL)
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
