# Function: <code>imx_sata_disable</code>

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
<summary>In <code>arm64</code>: ✅</summary>

```c
void imx_sata_disable(struct ahci_host_priv *hpriv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/ahci_imx.c (ffff8000109b6cd8)
Location: drivers/ata/ahci_imx.c:709
Inline: False
Direct callers:
  - drivers/ata/ahci_imx.c:imx_ahci_suspend
  - drivers/ata/ahci_imx.c:ahci_imx_host_stop
  - drivers/ata/ahci_imx.c:imx_ahci_probe
  - drivers/ata/ahci_imx.c:ahci_imx_error_handler
```
**Symbols:**

```
ffff8000109b6cd8-ffff8000109b6ddc: imx_sata_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void imx_sata_disable(struct ahci_host_priv *hpriv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/ahci_imx.c (c0a89838)
Location: drivers/ata/ahci_imx.c:709
Inline: False
Direct callers:
  - drivers/ata/ahci_imx.c:imx_ahci_suspend
  - drivers/ata/ahci_imx.c:ahci_imx_host_stop
  - drivers/ata/ahci_imx.c:imx_ahci_probe
  - drivers/ata/ahci_imx.c:ahci_imx_error_handler
```
**Symbols:**

```
c0a89838-c0a89938: imx_sata_disable (STB_LOCAL)
```
</details>
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
<b>Arch</b>
<ul>
</ul>
