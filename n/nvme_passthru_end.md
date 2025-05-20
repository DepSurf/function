# Function: <code>nvme_passthru_end</code>

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
void nvme_passthru_end(struct nvme_ctrl *ctrl, u32 effects);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvme/host/core.c (ffffffff81747b70)
Location: drivers/nvme/host/core.c:1356
Inline: True
Direct callers:
  - drivers/nvme/host/core.c:nvme_user_cmd64
  - drivers/nvme/host/core.c:nvme_user_cmd
```
**Symbols:**

```
ffffffff81747b70-ffffffff81747c73: nvme_passthru_end (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void nvme_passthru_end(struct nvme_ctrl *ctrl, u32 effects);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvme/host/core.c (ffffffff817297c0)
Location: drivers/nvme/host/core.c:1356
Inline: True
Direct callers:
  - drivers/nvme/host/core.c:nvme_user_cmd64
  - drivers/nvme/host/core.c:nvme_user_cmd
```
**Symbols:**

```
ffffffff817297c0-ffffffff817298c3: nvme_passthru_end (STB_LOCAL)
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
