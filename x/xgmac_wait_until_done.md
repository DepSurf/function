# Function: <code>xgmac_wait_until_done</code>

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
int xgmac_wait_until_done(struct device *dev, struct tgec_mdio_controller *regs, bool is_little_endian);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/ethernet/freescale/xgmac_mdio.c (ffff8000109ed840)
Location: drivers/net/ethernet/freescale/xgmac_mdio.c:102
Inline: False
Direct callers:
  - drivers/net/ethernet/freescale/xgmac_mdio.c:xgmac_mdio_read
  - drivers/net/ethernet/freescale/xgmac_mdio.c:xgmac_mdio_write
```
**Symbols:**

```
ffff8000109ed840-ffff8000109ed8b8: xgmac_wait_until_done (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int xgmac_wait_until_done(struct device *dev, struct tgec_mdio_controller *regs, bool is_little_endian);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/ethernet/freescale/xgmac_mdio.c (c0acf208)
Location: drivers/net/ethernet/freescale/xgmac_mdio.c:102
Inline: False
Direct callers:
  - drivers/net/ethernet/freescale/xgmac_mdio.c:xgmac_mdio_read
  - drivers/net/ethernet/freescale/xgmac_mdio.c:xgmac_mdio_write
```
**Symbols:**

```
c0acf208-c0acf29c: xgmac_wait_until_done (STB_LOCAL)
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
