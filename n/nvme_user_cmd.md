# Function: <code>nvme_user_cmd</code>

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
int nvme_user_cmd(struct nvme_ctrl *ctrl, struct nvme_ns *ns, struct nvme_passthru_cmd *ucmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvme/host/core.c (ffffffff81747c80)
Location: drivers/nvme/host/core.c:1378
Inline: False
Direct callers:
  - drivers/nvme/host/core.c:nvme_dev_ioctl
  - drivers/nvme/host/core.c:nvme_dev_ioctl
  - drivers/nvme/host/core.c:nvme_ioctl
  - drivers/nvme/host/core.c:nvme_ioctl
```
**Symbols:**

```
ffffffff81747c80-ffffffff81747e23: nvme_user_cmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int nvme_user_cmd(struct nvme_ctrl *ctrl, struct nvme_ns *ns, struct nvme_passthru_cmd *ucmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvme/host/core.c (ffffffff817298d0)
Location: drivers/nvme/host/core.c:1378
Inline: False
Direct callers:
  - drivers/nvme/host/core.c:nvme_dev_ioctl
  - drivers/nvme/host/core.c:nvme_dev_ioctl
  - drivers/nvme/host/core.c:nvme_ioctl
  - drivers/nvme/host/core.c:nvme_ioctl
```
**Symbols:**

```
ffffffff817298d0-ffffffff81729a73: nvme_user_cmd (STB_LOCAL)
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
