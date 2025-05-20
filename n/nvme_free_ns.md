# Function: <code>nvme_free_ns</code>

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
void nvme_free_ns(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvme/host/core.c (ffffffff81745f30)
Location: drivers/nvme/host/core.c:451
Inline: False
Direct callers:
  - drivers/nvme/host/core.c:nvme_scan_work
  - drivers/nvme/host/core.c:nvme_validate_ns
  - drivers/nvme/host/core.c:nvme_release
  - drivers/nvme/host/core.c:nvme_open
```
**Symbols:**

```
ffffffff81745f30-ffffffff81745f97: nvme_free_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void nvme_free_ns(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvme/host/core.c (ffffffff81727bc0)
Location: drivers/nvme/host/core.c:451
Inline: False
Direct callers:
  - drivers/nvme/host/core.c:nvme_scan_work
  - drivers/nvme/host/core.c:nvme_validate_ns
  - drivers/nvme/host/core.c:nvme_release
  - drivers/nvme/host/core.c:nvme_open
```
**Symbols:**

```
ffffffff81727bc0-ffffffff81727c18: nvme_free_ns (STB_LOCAL)
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
