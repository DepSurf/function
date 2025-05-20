# Function: <code>nvme_configure_apst</code>

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
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvme/host/core.c (ffffffff817477f0)
Location: drivers/nvme/host/core.c:2240
Inline: True
Inline callers:
  - drivers/nvme/host/core.c:nvme_init_identify
  - drivers/nvme/host/core.c:nvme_set_latency_tolerance
Direct callers:
  - drivers/nvme/host/core.c:nvme_init_identify
  - drivers/nvme/host/core.c:nvme_set_latency_tolerance
```
**Symbols:**

```
ffffffff81743f60-ffffffff81744143: nvme_configure_apst.part.0 (STB_LOCAL)
ffffffff817489fc-ffffffff81748a32: nvme_configure_apst.part.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvme/host/core.c (ffffffff81729440)
Location: drivers/nvme/host/core.c:2240
Inline: True
Inline callers:
  - drivers/nvme/host/core.c:nvme_init_identify
  - drivers/nvme/host/core.c:nvme_set_latency_tolerance
Direct callers:
  - drivers/nvme/host/core.c:nvme_init_identify
  - drivers/nvme/host/core.c:nvme_set_latency_tolerance
```
**Symbols:**

```
ffffffff81725bf0-ffffffff81725dd3: nvme_configure_apst.part.0 (STB_LOCAL)
ffffffff8172a61c-ffffffff8172a652: nvme_configure_apst.part.0.cold (STB_LOCAL)
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
