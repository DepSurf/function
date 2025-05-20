# Function: <code>imx_scu_call_rpc</code>

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
int imx_scu_call_rpc(struct imx_sc_ipc *sc_ipc, void *msg, bool have_resp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/imx/imx-scu.c (ffff800010b61f10)
Location: drivers/firmware/imx/imx-scu.c:179
Inline: False
Direct callers:
  - drivers/pinctrl/freescale/pinctrl-scu.c:imx_pinconf_set_scu
  - drivers/pinctrl/freescale/pinctrl-scu.c:imx_pinconf_get_scu
  - drivers/clk/imx/clk-scu.c:clk_scu_unprepare
  - drivers/clk/imx/clk-scu.c:clk_scu_prepare
  - drivers/clk/imx/clk-scu.c:clk_scu_set_parent
  - drivers/clk/imx/clk-scu.c:clk_scu_get_parent
  - drivers/clk/imx/clk-scu.c:clk_scu_set_rate
  - drivers/clk/imx/clk-scu.c:clk_scu_recalc_rate
  - drivers/soc/imx/soc-imx-scu.c:soc_uid_show
  - drivers/firmware/imx/misc.c:imx_sc_pm_cpu_start
  - drivers/firmware/imx/misc.c:imx_sc_misc_get_control
  - drivers/firmware/imx/misc.c:imx_sc_misc_set_control
  - drivers/firmware/imx/imx-scu-irq.c:imx_scu_irq_group_enable
  - drivers/firmware/imx/imx-scu-irq.c:imx_scu_irq_work_handler
  - drivers/firmware/imx/scu-pd.c:imx_sc_pd_power
  - drivers/firmware/imx/scu-pd.c:imx_sc_pd_power
```
**Symbols:**

```
ffff800010b61f10-ffff800010b6210c: imx_scu_call_rpc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int imx_scu_call_rpc(struct imx_sc_ipc *sc_ipc, void *msg, bool have_resp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/imx/imx-scu.c (c0c40668)
Location: drivers/firmware/imx/imx-scu.c:179
Inline: False
Direct callers:
  - drivers/soc/imx/soc-imx-scu.c:soc_uid_show
  - drivers/firmware/imx/misc.c:imx_sc_pm_cpu_start
  - drivers/firmware/imx/misc.c:imx_sc_misc_get_control
  - drivers/firmware/imx/misc.c:imx_sc_misc_set_control
  - drivers/firmware/imx/imx-scu-irq.c:imx_scu_irq_group_enable
  - drivers/firmware/imx/imx-scu-irq.c:imx_scu_irq_work_handler
  - drivers/firmware/imx/scu-pd.c:imx_sc_pd_power
  - drivers/firmware/imx/scu-pd.c:imx_sc_pd_power
```
**Symbols:**

```
c0c40668-c0c408ac: imx_scu_call_rpc (STB_GLOBAL)
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
