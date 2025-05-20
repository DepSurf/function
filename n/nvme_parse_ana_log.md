# Function: <code>nvme_parse_ana_log</code>

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
int nvme_parse_ana_log(struct nvme_ctrl *ctrl, void *data, int (*cb)(struct nvme_ctrl *, struct nvme_ana_group_desc *, void *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvme/host/multipath.c (ffffffff81749530)
Location: drivers/nvme/host/multipath.c:438
Inline: False
Direct callers:
  - drivers/nvme/host/multipath.c:nvme_mpath_add_disk
  - drivers/nvme/host/multipath.c:nvme_read_ana_log
```
**Symbols:**

```
ffffffff81749530-ffffffff81749696: nvme_parse_ana_log (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int nvme_parse_ana_log(struct nvme_ctrl *ctrl, void *data, int (*cb)(struct nvme_ctrl *, struct nvme_ana_group_desc *, void *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvme/host/multipath.c (ffffffff8172b120)
Location: drivers/nvme/host/multipath.c:438
Inline: False
Direct callers:
  - drivers/nvme/host/multipath.c:nvme_mpath_add_disk
  - drivers/nvme/host/multipath.c:nvme_read_ana_log
```
**Symbols:**

```
ffffffff8172b120-ffffffff8172b286: nvme_parse_ana_log (STB_LOCAL)
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
