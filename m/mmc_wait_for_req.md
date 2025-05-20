# Function: <code>mmc_wait_for_req</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void mmc_wait_for_req(struct mmc_host *host, struct mmc_request *mrq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff816bf420)
Location: drivers/mmc/core/core.c:650
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_wait_for_cmd
Direct callers:
  - drivers/mmc/core/mmc_ops.c:mmc_send_cxd_data
  - drivers/mmc/core/mmc_ops.c:mmc_send_bus_test
  - drivers/mmc/core/mmc_ops.c:mmc_send_bus_test
  - drivers/mmc/core/mmc_ops.c:mmc_send_tuning
  - drivers/mmc/core/sd_ops.c:mmc_wait_for_app_cmd
  - drivers/mmc/core/sd_ops.c:mmc_app_send_scr
  - drivers/mmc/core/sd_ops.c:mmc_sd_switch
  - drivers/mmc/core/sd_ops.c:mmc_app_sd_status
  - drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended
  - drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended
```
**Symbols:**

```
ffffffff816bf420-ffffffff816bf447: mmc_wait_for_req (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void mmc_wait_for_req(struct mmc_host *host, struct mmc_request *mrq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81721e93)
Location: drivers/mmc/core/core.c:651
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_wait_for_cmd
Direct callers:
  - drivers/mmc/core/mmc_ops.c:mmc_send_bus_test
  - drivers/mmc/core/mmc_ops.c:mmc_send_bus_test
  - drivers/mmc/core/mmc_ops.c:mmc_send_tuning
  - drivers/mmc/core/mmc_ops.c:mmc_send_cxd_data
  - drivers/mmc/core/sd_ops.c:mmc_app_sd_status
  - drivers/mmc/core/sd_ops.c:mmc_sd_switch
  - drivers/mmc/core/sd_ops.c:mmc_app_send_scr
  - drivers/mmc/core/sd_ops.c:mmc_wait_for_app_cmd
  - drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended
  - drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended
```
**Symbols:**

```
ffffffff81721e20-ffffffff81721e47: mmc_wait_for_req (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void mmc_wait_for_req(struct mmc_host *host, struct mmc_request *mrq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81754d20)
Location: drivers/mmc/core/core.c:724
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_wait_for_cmd
  - drivers/mmc/core/mmc_ops.c:mmc_send_bus_test
  - drivers/mmc/core/mmc_ops.c:mmc_send_bus_test
  - drivers/mmc/core/mmc_ops.c:mmc_send_tuning
  - drivers/mmc/core/mmc_ops.c:mmc_send_cxd_data
  - drivers/mmc/core/sd_ops.c:mmc_app_sd_status
  - drivers/mmc/core/sd_ops.c:mmc_sd_switch
  - drivers/mmc/core/sd_ops.c:mmc_app_send_scr
  - drivers/mmc/core/sd_ops.c:mmc_wait_for_app_cmd
  - drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended
  - drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended
```
**Symbols:**

```
ffffffff81754d20-ffffffff81754dfc: mmc_wait_for_req (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void mmc_wait_for_req(struct mmc_host *host, struct mmc_request *mrq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff817728b0)
Location: drivers/mmc/core/core.c:668
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_wait_for_cmd
  - drivers/mmc/core/mmc_ops.c:mmc_send_bus_test
  - drivers/mmc/core/mmc_ops.c:mmc_send_bus_test
  - drivers/mmc/core/mmc_ops.c:mmc_send_tuning
  - drivers/mmc/core/mmc_ops.c:mmc_send_cxd_data
  - drivers/mmc/core/sd_ops.c:mmc_app_sd_status
  - drivers/mmc/core/sd_ops.c:mmc_sd_switch
  - drivers/mmc/core/sd_ops.c:mmc_app_send_scr
  - drivers/mmc/core/sd_ops.c:mmc_wait_for_app_cmd
  - drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended
  - drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended
```
**Symbols:**

```
ffffffff817728b0-ffffffff8177298c: mmc_wait_for_req (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void mmc_wait_for_req(struct mmc_host *host, struct mmc_request *mrq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff817e8420)
Location: drivers/mmc/core/core.c:822
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_wait_for_cmd
  - drivers/mmc/core/mmc_ops.c:mmc_send_bus_test
  - drivers/mmc/core/mmc_ops.c:mmc_send_bus_test
  - drivers/mmc/core/mmc_ops.c:mmc_send_tuning
  - drivers/mmc/core/mmc_ops.c:mmc_send_cxd_data
  - drivers/mmc/core/sd_ops.c:mmc_app_sd_status
  - drivers/mmc/core/sd_ops.c:mmc_sd_switch
  - drivers/mmc/core/sd_ops.c:mmc_app_send_scr
  - drivers/mmc/core/sd_ops.c:mmc_wait_for_app_cmd
  - drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended
  - drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended
```
**Symbols:**

```
ffffffff817e8420-ffffffff817e84fc: mmc_wait_for_req (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void mmc_wait_for_req(struct mmc_host *host, struct mmc_request *mrq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81831830)
Location: drivers/mmc/core/core.c:621
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_wait_for_cmd
  - drivers/mmc/core/mmc_ops.c:mmc_send_bus_test
  - drivers/mmc/core/mmc_ops.c:mmc_send_bus_test
  - drivers/mmc/core/mmc_ops.c:mmc_send_tuning
  - drivers/mmc/core/mmc_ops.c:mmc_send_cxd_data
  - drivers/mmc/core/sd_ops.c:mmc_app_sd_status
  - drivers/mmc/core/sd_ops.c:mmc_sd_switch
  - drivers/mmc/core/sd_ops.c:mmc_app_send_scr
  - drivers/mmc/core/sd_ops.c:mmc_wait_for_app_cmd
  - drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended
  - drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended
```
**Symbols:**

```
ffffffff81831830-ffffffff818318ee: mmc_wait_for_req (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void mmc_wait_for_req(struct mmc_host *host, struct mmc_request *mrq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff8185d810)
Location: drivers/mmc/core/core.c:621
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_wait_for_cmd
  - drivers/mmc/core/mmc_ops.c:mmc_send_bus_test
  - drivers/mmc/core/mmc_ops.c:mmc_send_bus_test
  - drivers/mmc/core/mmc_ops.c:mmc_send_tuning
  - drivers/mmc/core/mmc_ops.c:mmc_send_cxd_data
  - drivers/mmc/core/sd_ops.c:mmc_app_sd_status
  - drivers/mmc/core/sd_ops.c:mmc_sd_switch
  - drivers/mmc/core/sd_ops.c:mmc_app_send_scr
  - drivers/mmc/core/sd_ops.c:mmc_wait_for_app_cmd
  - drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended
  - drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended
```
**Symbols:**

```
ffffffff8185d810-ffffffff8185d8ce: mmc_wait_for_req (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void mmc_wait_for_req(struct mmc_host *host, struct mmc_request *mrq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff818a1450)
Location: drivers/mmc/core/core.c:619
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_wait_for_cmd
  - drivers/mmc/core/mmc_ops.c:mmc_send_bus_test
  - drivers/mmc/core/mmc_ops.c:mmc_send_bus_test
  - drivers/mmc/core/mmc_ops.c:mmc_send_tuning
  - drivers/mmc/core/mmc_ops.c:mmc_send_cxd_data
  - drivers/mmc/core/sd_ops.c:mmc_app_sd_status
  - drivers/mmc/core/sd_ops.c:mmc_sd_switch
  - drivers/mmc/core/sd_ops.c:mmc_app_send_scr
  - drivers/mmc/core/sd_ops.c:mmc_wait_for_app_cmd
  - drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended
  - drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended
```
**Symbols:**

```
ffffffff818a1450-ffffffff818a151c: mmc_wait_for_req (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void mmc_wait_for_req(struct mmc_host *host, struct mmc_request *mrq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff818d3740)
Location: drivers/mmc/core/core.c:619
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_wait_for_cmd
  - drivers/mmc/core/mmc_ops.c:mmc_send_bus_test
  - drivers/mmc/core/mmc_ops.c:mmc_send_bus_test
  - drivers/mmc/core/mmc_ops.c:mmc_send_tuning
  - drivers/mmc/core/mmc_ops.c:mmc_send_cxd_data
  - drivers/mmc/core/sd_ops.c:mmc_app_sd_status
  - drivers/mmc/core/sd_ops.c:mmc_sd_switch
  - drivers/mmc/core/sd_ops.c:mmc_app_send_scr
  - drivers/mmc/core/sd_ops.c:mmc_wait_for_app_cmd
  - drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended
  - drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended
```
**Symbols:**

```
ffffffff818d3740-ffffffff818d380c: mmc_wait_for_req (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void mmc_wait_for_req(struct mmc_host *host, struct mmc_request *mrq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff819a5e10)
Location: drivers/mmc/core/core.c:602
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_wait_for_cmd
  - drivers/mmc/core/mmc_ops.c:mmc_send_bus_test
  - drivers/mmc/core/mmc_ops.c:mmc_send_bus_test
  - drivers/mmc/core/mmc_ops.c:mmc_send_tuning
  - drivers/mmc/core/mmc_ops.c:mmc_send_cxd_data
  - drivers/mmc/core/sd_ops.c:mmc_app_sd_status
  - drivers/mmc/core/sd_ops.c:mmc_sd_switch
  - drivers/mmc/core/sd_ops.c:mmc_app_send_scr
  - drivers/mmc/core/sd_ops.c:mmc_wait_for_app_cmd
  - drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended
```
**Symbols:**

```
ffffffff819a5e10-ffffffff819a5edc: mmc_wait_for_req (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void mmc_wait_for_req(struct mmc_host *host, struct mmc_request *mrq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff819a8bc0)
Location: drivers/mmc/core/core.c:602
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_wait_for_cmd
  - drivers/mmc/core/mmc_ops.c:mmc_send_bus_test
  - drivers/mmc/core/mmc_ops.c:mmc_send_bus_test
  - drivers/mmc/core/mmc_ops.c:mmc_send_tuning
  - drivers/mmc/core/mmc_ops.c:mmc_send_cxd_data
  - drivers/mmc/core/sd_ops.c:mmc_app_sd_status
  - drivers/mmc/core/sd_ops.c:mmc_sd_switch
  - drivers/mmc/core/sd_ops.c:mmc_app_send_scr
  - drivers/mmc/core/sd_ops.c:mmc_wait_for_app_cmd
  - drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended
```
**Symbols:**

```
ffffffff819a8bc0-ffffffff819a8c8c: mmc_wait_for_req (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void mmc_wait_for_req(struct mmc_host *host, struct mmc_request *mrq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff8198d890)
Location: drivers/mmc/core/core.c:603
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_wait_for_cmd
  - drivers/mmc/core/mmc_ops.c:mmc_send_bus_test
  - drivers/mmc/core/mmc_ops.c:mmc_send_bus_test
  - drivers/mmc/core/mmc_ops.c:mmc_send_tuning
  - drivers/mmc/core/mmc_ops.c:mmc_send_cxd_data
  - drivers/mmc/core/sd_ops.c:mmc_app_sd_status
  - drivers/mmc/core/sd_ops.c:mmc_sd_switch
  - drivers/mmc/core/sd_ops.c:mmc_app_send_scr
  - drivers/mmc/core/sd_ops.c:mmc_wait_for_app_cmd
  - drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended
```
**Symbols:**

```
ffffffff8198d890-ffffffff8198d95c: mmc_wait_for_req (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void mmc_wait_for_req(struct mmc_host *host, struct mmc_request *mrq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/core.c (0)
Location: drivers/mmc/core/core.c:603
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_wait_for_cmd
  - drivers/mmc/core/mmc_ops.c:mmc_send_bus_test
  - drivers/mmc/core/mmc_ops.c:mmc_send_bus_test
  - drivers/mmc/core/mmc_ops.c:mmc_send_tuning
  - drivers/mmc/core/mmc_ops.c:mmc_send_adtc_data
  - drivers/mmc/core/sd_ops.c:mmc_app_sd_status
  - drivers/mmc/core/sd_ops.c:mmc_app_send_scr
  - drivers/mmc/core/sd_ops.c:mmc_wait_for_app_cmd
  - drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended
```
**Symbols:**

```
ffffffff81d2ce21-ffffffff81d2ce4b: mmc_wait_for_req.cold (STB_LOCAL)
ffffffff81a38ee0-ffffffff81a38fd1: mmc_wait_for_req (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void mmc_wait_for_req(struct mmc_host *host, struct mmc_request *mrq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/core.c (0)
Location: drivers/mmc/core/core.c:603
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_wait_for_cmd
  - drivers/mmc/core/mmc_ops.c:mmc_send_bus_test
  - drivers/mmc/core/mmc_ops.c:mmc_send_bus_test
  - drivers/mmc/core/mmc_ops.c:mmc_send_tuning
  - drivers/mmc/core/mmc_ops.c:mmc_send_adtc_data
  - drivers/mmc/core/sd_ops.c:mmc_app_sd_status
  - drivers/mmc/core/sd_ops.c:mmc_app_send_scr
  - drivers/mmc/core/sd_ops.c:mmc_wait_for_app_cmd
  - drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended
```
**Symbols:**

```
ffffffff81ef91ca-ffffffff81ef91f4: mmc_wait_for_req.cold (STB_LOCAL)
ffffffff81ba5f90-ffffffff81ba608d: mmc_wait_for_req (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void mmc_wait_for_req(struct mmc_host *host, struct mmc_request *mrq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/core.c (0)
Location: drivers/mmc/core/core.c:602
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_wait_for_cmd
  - drivers/mmc/core/mmc_ops.c:mmc_send_bus_test
  - drivers/mmc/core/mmc_ops.c:mmc_send_bus_test
  - drivers/mmc/core/mmc_ops.c:mmc_send_tuning
  - drivers/mmc/core/mmc_ops.c:mmc_send_adtc_data
  - drivers/mmc/core/sd_ops.c:mmc_app_sd_status
  - drivers/mmc/core/sd_ops.c:mmc_app_send_scr
  - drivers/mmc/core/sd_ops.c:mmc_wait_for_app_cmd
  - drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended
```
**Symbols:**

```
ffffffff820a94c3-ffffffff820a94ed: mmc_wait_for_req.cold (STB_LOCAL)
ffffffff81d482e0-ffffffff81d483dd: mmc_wait_for_req (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void mmc_wait_for_req(struct mmc_host *host, struct mmc_request *mrq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/core.c (0)
Location: drivers/mmc/core/core.c:602
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_wait_for_cmd
  - drivers/mmc/core/mmc_ops.c:mmc_send_bus_test
  - drivers/mmc/core/mmc_ops.c:mmc_send_bus_test
  - drivers/mmc/core/mmc_ops.c:mmc_send_tuning
  - drivers/mmc/core/mmc_ops.c:mmc_send_adtc_data
  - drivers/mmc/core/sd_ops.c:mmc_app_sd_status
  - drivers/mmc/core/sd_ops.c:mmc_app_send_scr
  - drivers/mmc/core/sd_ops.c:mmc_wait_for_app_cmd
  - drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended
```
**Symbols:**

```
ffffffff8212a8c2-ffffffff8212a8ec: mmc_wait_for_req.cold (STB_LOCAL)
ffffffff81db2be0-ffffffff81db2cdd: mmc_wait_for_req (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void mmc_wait_for_req(struct mmc_host *host, struct mmc_request *mrq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/core.c (0)
Location: drivers/mmc/core/core.c:607
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_wait_for_cmd
  - drivers/mmc/core/mmc_ops.c:mmc_send_bus_test
  - drivers/mmc/core/mmc_ops.c:mmc_send_bus_test
  - drivers/mmc/core/mmc_ops.c:mmc_send_tuning
  - drivers/mmc/core/mmc_ops.c:mmc_send_adtc_data
  - drivers/mmc/core/sd_ops.c:mmc_app_sd_status
  - drivers/mmc/core/sd_ops.c:mmc_app_send_scr
  - drivers/mmc/core/sd_ops.c:mmc_wait_for_app_cmd
  - drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended
```
**Symbols:**

```
ffffffff8220c66a-ffffffff8220c694: mmc_wait_for_req.cold (STB_LOCAL)
ffffffff81e6af70-ffffffff81e6b06d: mmc_wait_for_req (STB_GLOBAL)
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
void mmc_wait_for_req(struct mmc_host *host, struct mmc_request *mrq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffff800010b2cc88)
Location: drivers/mmc/core/core.c:619
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_wait_for_cmd
  - drivers/mmc/core/mmc_ops.c:mmc_send_bus_test
  - drivers/mmc/core/mmc_ops.c:mmc_send_bus_test
  - drivers/mmc/core/mmc_ops.c:mmc_send_tuning
  - drivers/mmc/core/mmc_ops.c:mmc_send_cxd_data
  - drivers/mmc/core/sd_ops.c:mmc_app_sd_status
  - drivers/mmc/core/sd_ops.c:mmc_sd_switch
  - drivers/mmc/core/sd_ops.c:mmc_app_send_scr
  - drivers/mmc/core/sd_ops.c:mmc_wait_for_app_cmd
  - drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended
  - drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended
  - drivers/mmc/core/block.c:mmc_blk_mq_rw_recovery
  - drivers/mmc/core/block.c:mmc_sd_num_wr_blocks
  - drivers/mmc/core/block.c:__mmc_blk_ioctl_cmd
```
**Symbols:**

```
ffff800010b2cc88-ffff800010b2cd8c: mmc_wait_for_req (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void mmc_wait_for_req(struct mmc_host *host, struct mmc_request *mrq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (c0c07fe4)
Location: drivers/mmc/core/core.c:619
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_wait_for_cmd
  - drivers/mmc/core/mmc_ops.c:mmc_send_bus_test
  - drivers/mmc/core/mmc_ops.c:mmc_send_bus_test
  - drivers/mmc/core/mmc_ops.c:mmc_send_tuning
  - drivers/mmc/core/mmc_ops.c:mmc_send_cxd_data
  - drivers/mmc/core/sd_ops.c:mmc_app_sd_status
  - drivers/mmc/core/sd_ops.c:mmc_sd_switch
  - drivers/mmc/core/sd_ops.c:mmc_app_send_scr
  - drivers/mmc/core/sd_ops.c:mmc_wait_for_app_cmd
  - drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended
  - drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended
  - drivers/mmc/core/block.c:mmc_blk_mq_rw_recovery
  - drivers/mmc/core/block.c:mmc_sd_num_wr_blocks
  - drivers/mmc/core/block.c:__mmc_blk_ioctl_cmd
```
**Symbols:**

```
c0c07fe4-c0c080c4: mmc_wait_for_req (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void mmc_wait_for_req(struct mmc_host *host, struct mmc_request *mrq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (c000000000c25ab0)
Location: drivers/mmc/core/core.c:619
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_wait_for_cmd
  - drivers/mmc/core/mmc_ops.c:mmc_send_bus_test
  - drivers/mmc/core/mmc_ops.c:mmc_send_bus_test
  - drivers/mmc/core/mmc_ops.c:mmc_send_tuning
  - drivers/mmc/core/mmc_ops.c:mmc_send_cxd_data
  - drivers/mmc/core/sd_ops.c:mmc_app_sd_status
  - drivers/mmc/core/sd_ops.c:mmc_sd_switch
  - drivers/mmc/core/sd_ops.c:mmc_app_send_scr
  - drivers/mmc/core/sd_ops.c:mmc_wait_for_app_cmd
  - drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended
  - drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended
```
**Symbols:**

```
c000000000c25ab0-c000000000c25bf8: mmc_wait_for_req (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void mmc_wait_for_req(struct mmc_host *host, struct mmc_request *mrq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffe000706cf0)
Location: drivers/mmc/core/core.c:619
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_wait_for_cmd
  - drivers/mmc/core/mmc_ops.c:mmc_send_bus_test
  - drivers/mmc/core/mmc_ops.c:mmc_send_bus_test
  - drivers/mmc/core/mmc_ops.c:mmc_send_tuning
  - drivers/mmc/core/mmc_ops.c:mmc_send_cxd_data
  - drivers/mmc/core/sd_ops.c:mmc_app_sd_status
  - drivers/mmc/core/sd_ops.c:mmc_sd_switch
  - drivers/mmc/core/sd_ops.c:mmc_app_send_scr
  - drivers/mmc/core/sd_ops.c:mmc_wait_for_app_cmd
  - drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended
  - drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended
  - drivers/mmc/core/block.c:mmc_blk_mq_rw_recovery
  - drivers/mmc/core/block.c:mmc_sd_num_wr_blocks
  - drivers/mmc/core/block.c:__mmc_blk_ioctl_cmd
```
**Symbols:**

```
ffffffe000706cf0-ffffffe000706dc6: mmc_wait_for_req (STB_GLOBAL)
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
void mmc_wait_for_req(struct mmc_host *host, struct mmc_request *mrq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81877100)
Location: drivers/mmc/core/core.c:619
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_wait_for_cmd
  - drivers/mmc/core/mmc_ops.c:mmc_send_bus_test
  - drivers/mmc/core/mmc_ops.c:mmc_send_bus_test
  - drivers/mmc/core/mmc_ops.c:mmc_send_tuning
  - drivers/mmc/core/mmc_ops.c:mmc_send_cxd_data
  - drivers/mmc/core/sd_ops.c:mmc_app_sd_status
  - drivers/mmc/core/sd_ops.c:mmc_sd_switch
  - drivers/mmc/core/sd_ops.c:mmc_app_send_scr
  - drivers/mmc/core/sd_ops.c:mmc_wait_for_app_cmd
  - drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended
  - drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended
```
**Symbols:**

```
ffffffff81877100-ffffffff818771cc: mmc_wait_for_req (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void mmc_wait_for_req(struct mmc_host *host, struct mmc_request *mrq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff818c85a0)
Location: drivers/mmc/core/core.c:619
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_wait_for_cmd
  - drivers/mmc/core/mmc_ops.c:mmc_send_bus_test
  - drivers/mmc/core/mmc_ops.c:mmc_send_bus_test
  - drivers/mmc/core/mmc_ops.c:mmc_send_tuning
  - drivers/mmc/core/mmc_ops.c:mmc_send_cxd_data
  - drivers/mmc/core/sd_ops.c:mmc_app_sd_status
  - drivers/mmc/core/sd_ops.c:mmc_sd_switch
  - drivers/mmc/core/sd_ops.c:mmc_app_send_scr
  - drivers/mmc/core/sd_ops.c:mmc_wait_for_app_cmd
  - drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended
  - drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended
```
**Symbols:**

```
ffffffff818c85a0-ffffffff818c866c: mmc_wait_for_req (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void mmc_wait_for_req(struct mmc_host *host, struct mmc_request *mrq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff818e50c0)
Location: drivers/mmc/core/core.c:619
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_wait_for_cmd
  - drivers/mmc/core/mmc_ops.c:mmc_send_bus_test
  - drivers/mmc/core/mmc_ops.c:mmc_send_bus_test
  - drivers/mmc/core/mmc_ops.c:mmc_send_tuning
  - drivers/mmc/core/mmc_ops.c:mmc_send_cxd_data
  - drivers/mmc/core/sd_ops.c:mmc_app_sd_status
  - drivers/mmc/core/sd_ops.c:mmc_sd_switch
  - drivers/mmc/core/sd_ops.c:mmc_app_send_scr
  - drivers/mmc/core/sd_ops.c:mmc_wait_for_app_cmd
  - drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended
  - drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended
```
**Symbols:**

```
ffffffff818e50c0-ffffffff818e518c: mmc_wait_for_req (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
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
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
