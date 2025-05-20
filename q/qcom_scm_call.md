# Function: <code>qcom_scm_call</code>

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
int qcom_scm_call(struct device *dev, u32 svc_id, u32 cmd_id, const struct qcom_scm_desc *desc, struct arm_smccc_res *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/qcom_scm-64.c (ffff800010b4f7b0)
Location: drivers/firmware/qcom_scm-64.c:75
Inline: False
Direct callers:
  - drivers/firmware/qcom_scm-64.c:__qcom_scm_io_writel
  - drivers/firmware/qcom_scm-64.c:__qcom_scm_io_readl
  - drivers/firmware/qcom_scm-64.c:__qcom_scm_set_dload_mode
  - drivers/firmware/qcom_scm-64.c:__qcom_scm_iommu_secure_ptbl_init
  - drivers/firmware/qcom_scm-64.c:__qcom_scm_iommu_secure_ptbl_size
  - drivers/firmware/qcom_scm-64.c:__qcom_scm_restore_sec_cfg
  - drivers/firmware/qcom_scm-64.c:__qcom_scm_assign_mem
  - drivers/firmware/qcom_scm-64.c:__qcom_scm_set_remote_state
  - drivers/firmware/qcom_scm-64.c:__qcom_scm_pas_mss_reset
  - drivers/firmware/qcom_scm-64.c:__qcom_scm_pas_shutdown
  - drivers/firmware/qcom_scm-64.c:__qcom_scm_pas_auth_and_reset
  - drivers/firmware/qcom_scm-64.c:__qcom_scm_pas_mem_setup
  - drivers/firmware/qcom_scm-64.c:__qcom_scm_pas_init_image
  - drivers/firmware/qcom_scm-64.c:__qcom_scm_pas_supported
  - drivers/firmware/qcom_scm-64.c:__qcom_scm_hdcp_req
  - drivers/firmware/qcom_scm-64.c:__qcom_scm_is_call_available
```
**Symbols:**

```
ffff800010b4f7b0-ffff800010b4fadc: qcom_scm_call (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int qcom_scm_call(struct device *dev, u32 svc_id, u32 cmd_id, const void *cmd_buf, size_t cmd_len, void *resp_buf, size_t resp_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/qcom_scm-32.c (c0c36174)
Location: drivers/firmware/qcom_scm-32.c:162
Inline: False
Direct callers:
  - drivers/firmware/qcom_scm-32.c:__qcom_scm_set_remote_state
  - drivers/firmware/qcom_scm-32.c:__qcom_scm_pas_mss_reset
  - drivers/firmware/qcom_scm-32.c:__qcom_scm_pas_shutdown
  - drivers/firmware/qcom_scm-32.c:__qcom_scm_pas_auth_and_reset
  - drivers/firmware/qcom_scm-32.c:__qcom_scm_pas_mem_setup
  - drivers/firmware/qcom_scm-32.c:__qcom_scm_pas_init_image
  - drivers/firmware/qcom_scm-32.c:__qcom_scm_pas_supported
  - drivers/firmware/qcom_scm-32.c:__qcom_scm_hdcp_req
  - drivers/firmware/qcom_scm-32.c:__qcom_scm_is_call_available
  - drivers/firmware/qcom_scm-32.c:__qcom_scm_set_warm_boot_addr
```
**Symbols:**

```
c0c36174-c0c36570: qcom_scm_call (STB_LOCAL)
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
