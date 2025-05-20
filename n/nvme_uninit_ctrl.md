# Function: <code>nvme_uninit_ctrl</code>

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
void nvme_uninit_ctrl(struct nvme_ctrl *ctrl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvme/host/core.c (ffffffff81748c28)
Location: drivers/nvme/host/core.c:3979
Inline: True
Inline callers:
  - drivers/nvme/host/core.c:nvme_do_delete_ctrl
Direct callers:
  - drivers/nvme/host/pci.c:nvme_remove
```
**Symbols:**

```
ffffffff81742250-ffffffff8174227f: nvme_uninit_ctrl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void nvme_uninit_ctrl(struct nvme_ctrl *ctrl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvme/host/core.c (ffffffff8172a848)
Location: drivers/nvme/host/core.c:3979
Inline: True
Inline callers:
  - drivers/nvme/host/core.c:nvme_do_delete_ctrl
Direct callers:
  - drivers/nvme/host/pci.c:nvme_remove
```
**Symbols:**

```
ffffffff81723ee0-ffffffff81723f0f: nvme_uninit_ctrl (STB_GLOBAL)
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
