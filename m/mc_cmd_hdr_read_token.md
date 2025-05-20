# Function: <code>mc_cmd_hdr_read_token</code>

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
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/bus/fsl-mc/mc-sys.c (ffff800010681520)
Location: include/linux/fsl/mc.h:260
Inline: True
Inline callers:
  - drivers/bus/fsl-mc/mc-sys.c:mc_send_command
  - drivers/bus/fsl-mc/mc-sys.c:mc_send_command
  - drivers/bus/fsl-mc/mc-sys.c:mc_send_command
```
```
In drivers/bus/fsl-mc/dpbp.c (ffff800010681ad4)
Location: include/linux/fsl/mc.h:260
Inline: True
Inline callers:
  - drivers/bus/fsl-mc/dpbp.c:dpbp_open
```
```
In drivers/bus/fsl-mc/dpcon.c (ffff800010681f2c)
Location: include/linux/fsl/mc.h:260
Inline: True
Inline callers:
  - drivers/bus/fsl-mc/dpcon.c:dpcon_open
```
```
In drivers/bus/fsl-mc/dprc.c (ffff800010682464)
Location: include/linux/fsl/mc.h:260
Inline: True
Inline callers:
  - drivers/bus/fsl-mc/dprc.c:dprc_open
```
```
In drivers/bus/fsl-mc/dpmcp.c (ffff800010684dbc)
Location: include/linux/fsl/mc.h:260
Inline: True
Inline callers:
  - drivers/bus/fsl-mc/dpmcp.c:dpmcp_open
```
</details>
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
