# Function: <code>nvme_read_ana_log</code>

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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int nvme_read_ana_log(struct nvme_ctrl *ctrl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvme/host/multipath.c (0)
Location: drivers/nvme/host/multipath.c:532
Inline: False
Direct callers:
  - drivers/nvme/host/multipath.c:nvme_mpath_init
  - drivers/nvme/host/multipath.c:nvme_ana_work
```
**Symbols:**

```
ffffffff817499d0-ffffffff81749aad: nvme_read_ana_log (STB_LOCAL)
ffffffff8174aa26-ffffffff8174aa43: nvme_read_ana_log.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int nvme_read_ana_log(struct nvme_ctrl *ctrl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvme/host/multipath.c (0)
Location: drivers/nvme/host/multipath.c:532
Inline: False
Direct callers:
  - drivers/nvme/host/multipath.c:nvme_mpath_init
  - drivers/nvme/host/multipath.c:nvme_ana_work
```
**Symbols:**

```
ffffffff8172b5c0-ffffffff8172b69d: nvme_read_ana_log (STB_LOCAL)
ffffffff8172c606-ffffffff8172c623: nvme_read_ana_log.cold (STB_LOCAL)
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
