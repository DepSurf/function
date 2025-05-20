# Function: <code>ncsi_find_package_and_channel</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void ncsi_find_package_and_channel(struct ncsi_dev_priv *ndp, unsigned char id, struct ncsi_package **np, struct ncsi_channel **nc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-manage.c (ffffffff8188f080)
Location: net/ncsi/ncsi-manage.c:387
Inline: False
Direct callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gpuuid
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gps
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gnpts
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gns
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gcps
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gvi
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_snfc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dgmf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_egmf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dbf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ebf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sma
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dv
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ev
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_svf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gls
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sl
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ae
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dcnt
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ecnt
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_rc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ec
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_cis
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_hncdsc
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_cr
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
```
**Symbols:**

```
ffffffff8188f080-ffffffff8188f11a: ncsi_find_package_and_channel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void ncsi_find_package_and_channel(struct ncsi_dev_priv *ndp, unsigned char id, struct ncsi_package **np, struct ncsi_channel **nc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-manage.c (ffffffff818c3480)
Location: net/ncsi/ncsi-manage.c:407
Inline: False
Direct callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gpuuid
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gps
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gnpts
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gns
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gcps
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gvi
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_snfc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dgmf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_egmf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dbf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ebf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sma
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dv
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ev
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_svf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gls
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sl
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ae
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dcnt
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ecnt
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_rc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ec
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_cis
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_hncdsc
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_cr
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
```
**Symbols:**

```
ffffffff818c3480-ffffffff818c351a: ncsi_find_package_and_channel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void ncsi_find_package_and_channel(struct ncsi_dev_priv *ndp, unsigned char id, struct ncsi_package **np, struct ncsi_channel **nc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-manage.c (ffffffff818e9e10)
Location: net/ncsi/ncsi-manage.c:407
Inline: False
Direct callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gpuuid
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gps
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gnpts
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gns
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gcps
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gvi
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_snfc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dgmf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_egmf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dbf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ebf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sma
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dv
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ev
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_svf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gls
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sl
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ae
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dcnt
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ecnt
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_rc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ec
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_cis
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_hncdsc
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_cr
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
```
**Symbols:**

```
ffffffff818e9e10-ffffffff818e9eaa: ncsi_find_package_and_channel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void ncsi_find_package_and_channel(struct ncsi_dev_priv *ndp, unsigned char id, struct ncsi_package **np, struct ncsi_channel **nc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-manage.c (ffffffff8196f550)
Location: net/ncsi/ncsi-manage.c:432
Inline: False
Direct callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gpuuid
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gps
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gnpts
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gns
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gcps
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gvi
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_snfc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dgmf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_egmf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dbf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ebf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sma
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dv
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ev
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_svf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gls
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sl
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ae
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dcnt
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ecnt
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_rc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ec
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_cis
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_hncdsc
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_cr
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
```
**Symbols:**

```
ffffffff8196f550-ffffffff8196f5ea: ncsi_find_package_and_channel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void ncsi_find_package_and_channel(struct ncsi_dev_priv *ndp, unsigned char id, struct ncsi_package **np, struct ncsi_channel **nc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-manage.c (ffffffff819c8c70)
Location: net/ncsi/ncsi-manage.c:306
Inline: False
Direct callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gpuuid
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gps
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gnpts
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gns
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gcps
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gvi
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_snfc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dgmf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_egmf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dbf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ebf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sma
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dv
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ev
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_svf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gls
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sl
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ae
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dcnt
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ecnt
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_rc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ec
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_cis
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_hncdsc
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_cr
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
```
**Symbols:**

```
ffffffff819c8c70-ffffffff819c8cff: ncsi_find_package_and_channel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void ncsi_find_package_and_channel(struct ncsi_dev_priv *ndp, unsigned char id, struct ncsi_package **np, struct ncsi_channel **nc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-manage.c (ffffffff81a00ba0)
Location: net/ncsi/ncsi-manage.c:329
Inline: False
Direct callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gpuuid
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gps
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gnpts
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gns
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gcps
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gvi
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_snfc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dgmf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_egmf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dbf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ebf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sma
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dv
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ev
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_svf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gls
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sl
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ae
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dcnt
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ecnt
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_rc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ec
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_cis
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_hncdsc
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_cr
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
  - net/ncsi/ncsi-manage.c:ncsi_request_timeout
```
**Symbols:**

```
ffffffff81a00ba0-ffffffff81a00c3a: ncsi_find_package_and_channel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void ncsi_find_package_and_channel(struct ncsi_dev_priv *ndp, unsigned char id, struct ncsi_package **np, struct ncsi_channel **nc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-manage.c (ffffffff81a6fdd0)
Location: net/ncsi/ncsi-manage.c:325
Inline: False
Direct callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gpuuid
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gps
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gnpts
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gns
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gcps
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gvi
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_snfc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dgmf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_egmf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dbf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ebf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sma
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dv
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ev
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_svf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gls
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sl
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ae
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dcnt
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ecnt
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_rc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ec
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_cis
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_hncdsc
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_cr
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
  - net/ncsi/ncsi-manage.c:ncsi_request_timeout
```
**Symbols:**

```
ffffffff81a6fdd0-ffffffff81a6fe57: ncsi_find_package_and_channel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void ncsi_find_package_and_channel(struct ncsi_dev_priv *ndp, unsigned char id, struct ncsi_package **np, struct ncsi_channel **nc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-manage.c (ffffffff81aa6600)
Location: net/ncsi/ncsi-manage.c:324
Inline: False
Direct callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gpuuid
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gps
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gnpts
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gns
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gcps
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gvi
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_snfc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dgmf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_egmf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dbf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ebf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sma
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dv
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ev
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_svf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gls
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sl
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ae
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dcnt
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ecnt
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_rc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ec
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_cis
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_hncdsc
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_cr
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
  - net/ncsi/ncsi-manage.c:ncsi_request_timeout
```
**Symbols:**

```
ffffffff81aa6600-ffffffff81aa6687: ncsi_find_package_and_channel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void ncsi_find_package_and_channel(struct ncsi_dev_priv *ndp, unsigned char id, struct ncsi_package **np, struct ncsi_channel **nc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-manage.c (ffffffff81ba24a0)
Location: net/ncsi/ncsi-manage.c:326
Inline: False
Direct callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gpuuid
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gps
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gnpts
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gns
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gcps
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gvi
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_snfc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dgmf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_egmf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dbf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ebf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sma
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dv
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ev
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_svf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gls
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sl
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ae
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dcnt
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ecnt
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_rc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ec
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_cis
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_hncdsc
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_cr
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
  - net/ncsi/ncsi-manage.c:ncsi_request_timeout
```
**Symbols:**

```
ffffffff81ba24a0-ffffffff81ba252a: ncsi_find_package_and_channel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ncsi_find_package_and_channel(struct ncsi_dev_priv *ndp, unsigned char id, struct ncsi_package **np, struct ncsi_channel **nc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-manage.c (ffffffff81bb1d20)
Location: net/ncsi/ncsi-manage.c:326
Inline: False
Direct callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gpuuid
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gps
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gnpts
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gns
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gcps
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gvi
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_snfc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dgmf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_egmf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dbf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ebf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sma
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dv
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ev
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_svf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gls
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sl
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ae
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dcnt
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ecnt
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_rc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ec
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_cis
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_hncdsc
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_cr
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
  - net/ncsi/ncsi-manage.c:ncsi_request_timeout
```
**Symbols:**

```
ffffffff81bb1d20-ffffffff81bb1daa: ncsi_find_package_and_channel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void ncsi_find_package_and_channel(struct ncsi_dev_priv *ndp, unsigned char id, struct ncsi_package **np, struct ncsi_channel **nc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-manage.c (ffffffff81ba0d40)
Location: net/ncsi/ncsi-manage.c:332
Inline: False
Direct callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gpuuid
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gps
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gnpts
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gns
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gcps
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gvi
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_snfc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dgmf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_egmf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dbf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ebf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sma
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dv
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ev
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_svf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gls
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sl
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ae
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dcnt
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ecnt
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_rc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ec
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_cis
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_hncdsc
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_cr
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
  - net/ncsi/ncsi-manage.c:ncsi_request_timeout
```
**Symbols:**

```
ffffffff81ba0d40-ffffffff81ba0dca: ncsi_find_package_and_channel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void ncsi_find_package_and_channel(struct ncsi_dev_priv *ndp, unsigned char id, struct ncsi_package **np, struct ncsi_channel **nc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-manage.c (ffffffff81c6e640)
Location: net/ncsi/ncsi-manage.c:332
Inline: False
Direct callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gpuuid
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gps
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gnpts
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gns
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gcps
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gvi
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_snfc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dgmf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_egmf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dbf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ebf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sma
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dv
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ev
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_svf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gls
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sl
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ae
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dcnt
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ecnt
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_rc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ec
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_cis
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_hncdsc
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_cr
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
  - net/ncsi/ncsi-manage.c:ncsi_request_timeout
```
**Symbols:**

```
ffffffff81c6e640-ffffffff81c6e6ca: ncsi_find_package_and_channel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void ncsi_find_package_and_channel(struct ncsi_dev_priv *ndp, unsigned char id, struct ncsi_package **np, struct ncsi_channel **nc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-manage.c (ffffffff81e121a0)
Location: net/ncsi/ncsi-manage.c:332
Inline: False
Direct callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gpuuid
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gps
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gnpts
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gns
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gcps
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gvi
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_snfc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dgmf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_egmf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dbf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ebf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sma
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dv
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ev
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_svf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gls
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sl
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ae
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dcnt
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ecnt
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_rc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ec
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_cis
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_hncdsc
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_cr
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
  - net/ncsi/ncsi-manage.c:ncsi_request_timeout
```
**Symbols:**

```
ffffffff81e121a0-ffffffff81e1223e: ncsi_find_package_and_channel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ncsi_find_package_and_channel(struct ncsi_dev_priv *ndp, unsigned char id, struct ncsi_package **np, struct ncsi_channel **nc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-manage.c (ffffffff81fe8be0)
Location: net/ncsi/ncsi-manage.c:332
Inline: False
Direct callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gpuuid
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gps
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gnpts
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gns
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gcps
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gvi
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_snfc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dgmf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_egmf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dbf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ebf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sma
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dv
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ev
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_svf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gls
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sl
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ae
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dcnt
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ecnt
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_rc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ec
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_cis
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_hncdsc
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_cr
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
  - net/ncsi/ncsi-manage.c:ncsi_request_timeout
```
**Symbols:**

```
ffffffff81fe8be0-ffffffff81fe8c7e: ncsi_find_package_and_channel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ncsi_find_package_and_channel(struct ncsi_dev_priv *ndp, unsigned char id, struct ncsi_package **np, struct ncsi_channel **nc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-manage.c (ffffffff82064e60)
Location: net/ncsi/ncsi-manage.c:332
Inline: False
Direct callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gpuuid
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gps
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gnpts
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gns
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gcps
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gvi
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_snfc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dgmf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_egmf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dbf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ebf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sma
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dv
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ev
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_svf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gls
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sl
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ae
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dcnt
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ecnt
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_rc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ec
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_cis
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_hncdsc
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_cr
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
  - net/ncsi/ncsi-manage.c:ncsi_request_timeout
```
**Symbols:**

```
ffffffff82064e60-ffffffff82064efe: ncsi_find_package_and_channel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ncsi_find_package_and_channel(struct ncsi_dev_priv *ndp, unsigned char id, struct ncsi_package **np, struct ncsi_channel **nc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-manage.c (ffffffff82138000)
Location: net/ncsi/ncsi-manage.c:332
Inline: False
Direct callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gpuuid
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gps
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gnpts
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gns
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gcps
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gvi
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_snfc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dgmf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_egmf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dbf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ebf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sma
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dv
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ev
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_svf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gls
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sl
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ae
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dcnt
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ecnt
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_rc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ec
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_cis
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_hncdsc
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_cr
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
  - net/ncsi/ncsi-manage.c:ncsi_request_timeout
```
**Symbols:**

```
ffffffff82138000-ffffffff8213809e: ncsi_find_package_and_channel (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void ncsi_find_package_and_channel(struct ncsi_dev_priv *ndp, unsigned char id, struct ncsi_package **np, struct ncsi_channel **nc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-manage.c (ffff800010d79340)
Location: net/ncsi/ncsi-manage.c:324
Inline: False
Direct callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gpuuid
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gps
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gnpts
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gns
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gcps
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gvi
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_snfc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dgmf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_egmf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dbf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ebf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sma
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dv
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ev
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_svf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gls
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sl
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ae
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dcnt
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ecnt
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_rc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ec
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_cis
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_hncdsc
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_cr
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
  - net/ncsi/ncsi-manage.c:ncsi_request_timeout
```
**Symbols:**

```
ffff800010d79340-ffff800010d79410: ncsi_find_package_and_channel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void ncsi_find_package_and_channel(struct ncsi_dev_priv *ndp, unsigned char id, struct ncsi_package **np, struct ncsi_channel **nc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-manage.c (c0e74e94)
Location: net/ncsi/ncsi-manage.c:324
Inline: False
Direct callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gpuuid
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gps
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gnpts
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gns
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gcps
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gvi
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_snfc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dgmf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_egmf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dbf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ebf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sma
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dv
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ev
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_svf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gls
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sl
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ae
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dcnt
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ecnt
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_rc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ec
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_cis
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_hncdsc
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_cr
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
  - net/ncsi/ncsi-manage.c:ncsi_request_timeout
```
**Symbols:**

```
c0e74e94-c0e74f44: ncsi_find_package_and_channel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void ncsi_find_package_and_channel(struct ncsi_dev_priv *ndp, unsigned char id, struct ncsi_package **np, struct ncsi_channel **nc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-manage.c (c000000000eb8b50)
Location: net/ncsi/ncsi-manage.c:324
Inline: False
Direct callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gpuuid
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gps
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gnpts
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gns
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gcps
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gvi
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_snfc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dgmf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_egmf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dbf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ebf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sma
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dv
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ev
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_svf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gls
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sl
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ae
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dcnt
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ecnt
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_rc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ec
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_cis
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_hncdsc
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_cr
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
  - net/ncsi/ncsi-manage.c:ncsi_request_timeout
```
**Symbols:**

```
c000000000eb8b50-c000000000eb8c18: ncsi_find_package_and_channel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void ncsi_find_package_and_channel(struct ncsi_dev_priv *ndp, unsigned char id, struct ncsi_package **np, struct ncsi_channel **nc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-manage.c (ffffffe0008a837e)
Location: net/ncsi/ncsi-manage.c:324
Inline: False
Direct callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gpuuid
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gps
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gnpts
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gns
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gcps
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gvi
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_snfc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dgmf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_egmf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dbf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ebf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sma
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dv
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ev
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_svf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gls
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sl
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ae
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dcnt
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ecnt
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_rc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ec
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_cis
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_hncdsc
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_cr
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
  - net/ncsi/ncsi-manage.c:ncsi_request_timeout
```
**Symbols:**

```
ffffffe0008a837e-ffffffe0008a841a: ncsi_find_package_and_channel (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void ncsi_find_package_and_channel(struct ncsi_dev_priv *ndp, unsigned char id, struct ncsi_package **np, struct ncsi_channel **nc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-manage.c (ffffffff81a45990)
Location: net/ncsi/ncsi-manage.c:324
Inline: False
Direct callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gpuuid
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gps
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gnpts
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gns
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gcps
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gvi
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_snfc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dgmf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_egmf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dbf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ebf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sma
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dv
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ev
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_svf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gls
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sl
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ae
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dcnt
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ecnt
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_rc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ec
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_cis
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_hncdsc
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_cr
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
  - net/ncsi/ncsi-manage.c:ncsi_request_timeout
```
**Symbols:**

```
ffffffff81a45990-ffffffff81a45a17: ncsi_find_package_and_channel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void ncsi_find_package_and_channel(struct ncsi_dev_priv *ndp, unsigned char id, struct ncsi_package **np, struct ncsi_channel **nc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-manage.c (ffffffff81a02580)
Location: net/ncsi/ncsi-manage.c:324
Inline: False
Direct callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gpuuid
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gps
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gnpts
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gns
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gcps
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gvi
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_snfc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dgmf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_egmf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dbf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ebf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sma
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dv
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ev
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_svf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gls
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sl
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ae
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dcnt
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ecnt
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_rc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ec
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_cis
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_hncdsc
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_cr
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
  - net/ncsi/ncsi-manage.c:ncsi_request_timeout
```
**Symbols:**

```
ffffffff81a02580-ffffffff81a02607: ncsi_find_package_and_channel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void ncsi_find_package_and_channel(struct ncsi_dev_priv *ndp, unsigned char id, struct ncsi_package **np, struct ncsi_channel **nc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-manage.c (ffffffff81ab1840)
Location: net/ncsi/ncsi-manage.c:324
Inline: False
Direct callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gpuuid
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gps
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gnpts
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gns
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gcps
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gvi
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_snfc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dgmf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_egmf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dbf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ebf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sma
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dv
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ev
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_svf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gls
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sl
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ae
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dcnt
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ecnt
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_rc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ec
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_cis
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_hncdsc
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_cr
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
  - net/ncsi/ncsi-manage.c:ncsi_request_timeout
```
**Symbols:**

```
ffffffff81ab1840-ffffffff81ab18c7: ncsi_find_package_and_channel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void ncsi_find_package_and_channel(struct ncsi_dev_priv *ndp, unsigned char id, struct ncsi_package **np, struct ncsi_channel **nc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-manage.c (ffffffff81abdbf0)
Location: net/ncsi/ncsi-manage.c:324
Inline: False
Direct callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gpuuid
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gps
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gnpts
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gns
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gcps
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gvi
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_snfc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dgmf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_egmf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dbf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ebf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sma
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dv
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ev
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_svf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gls
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sl
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ae
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dcnt
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ecnt
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_rc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ec
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_cis
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_hncdsc
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_cr
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
  - net/ncsi/ncsi-manage.c:ncsi_request_timeout
```
**Symbols:**

```
ffffffff81abdbf0-ffffffff81abdc77: ncsi_find_package_and_channel (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
