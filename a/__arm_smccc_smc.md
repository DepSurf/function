# Function: <code>__arm_smccc_smc</code>

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

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - drivers/clk/imx/clk-scu.c:clk_scu_atf_set_cpu_rate
  - drivers/clk/rockchip/clk-ddr.c:rockchip_ddrclk_sip_round_rate
  - drivers/clk/rockchip/clk-ddr.c:rockchip_ddrclk_sip_recalc_rate
  - drivers/clk/rockchip/clk-ddr.c:rockchip_ddrclk_sip_set_rate
  - drivers/char/tpm/tpm_crb.c:crb_send
  - drivers/mfd/altera-sysmgr.c:s10_protected_reg_read
  - drivers/mfd/altera-sysmgr.c:s10_protected_reg_write
  - drivers/edac/altera_edac.c:s10_edac_dberr_handler
  - drivers/edac/altera_edac.c:s10_protected_reg_read
  - drivers/edac/altera_edac.c:s10_protected_reg_write
  - drivers/firmware/arm_sdei.c:sdei_smccc_smc
  - drivers/firmware/qcom_scm-64.c:__qcom_scm_init
  - drivers/firmware/qcom_scm-64.c:qcom_scm_call
  - drivers/firmware/psci/psci.c:__invoke_psci_fn_smc
  - drivers/firmware/meson/meson_sm.c:meson_sm_call
  - drivers/firmware/meson/meson_sm.c:meson_sm_map_shmem
  - drivers/firmware/xilinx/zynqmp.c:do_fw_call_smc
```
**Symbols:**

```
ffff80001009d8a8-ffff80001009d8d4: __arm_smccc_smc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - drivers/clk/rockchip/clk-ddr.c:rockchip_ddrclk_sip_round_rate
  - drivers/clk/rockchip/clk-ddr.c:rockchip_ddrclk_sip_recalc_rate
  - drivers/clk/rockchip/clk-ddr.c:rockchip_ddrclk_sip_set_rate
  - drivers/firmware/psci/psci.c:__invoke_psci_fn_smc
```
**Symbols:**

```
c031a21c-c031a23c: __arm_smccc_smc (STB_GLOBAL)
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
