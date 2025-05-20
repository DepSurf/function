# Function: <code>imx_gpc_pu_pgc_sw_pxx_req</code>

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
int imx_gpc_pu_pgc_sw_pxx_req(struct generic_pm_domain *genpd, bool on);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/soc/imx/gpcv2.c (ffff8000108180d8)
Location: drivers/soc/imx/gpcv2.c:129
Inline: False
Direct callers:
  - drivers/soc/imx/gpcv2.c:imx_gpc_pu_pgc_sw_pdn_req
  - drivers/soc/imx/gpcv2.c:imx_gpc_pu_pgc_sw_pup_req
```
**Symbols:**

```
ffff8000108180d8-ffff800010818430: imx_gpc_pu_pgc_sw_pxx_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int imx_gpc_pu_pgc_sw_pxx_req(struct generic_pm_domain *genpd, bool on);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/soc/imx/gpcv2.c (c0934d38)
Location: drivers/soc/imx/gpcv2.c:129
Inline: False
Direct callers:
  - drivers/soc/imx/gpcv2.c:imx_gpc_pu_pgc_sw_pdn_req
  - drivers/soc/imx/gpcv2.c:imx_gpc_pu_pgc_sw_pup_req
```
**Symbols:**

```
c0934d38-c0935104: imx_gpc_pu_pgc_sw_pxx_req (STB_LOCAL)
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
