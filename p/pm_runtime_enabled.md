# Function: <code>pm_runtime_enabled</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/phy/phy-core.c (0)
Location: include/linux/pm_runtime.h:102
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/phy/phy-core.c (0)
Location: include/linux/pm_runtime.h:107
Inline: True
```
```
In drivers/base/power/runtime.c (0)
Location: include/linux/pm_runtime.h:107
Inline: True
```
```
In drivers/base/power/domain.c (ffffffff815b0300)
Location: include/linux/pm_runtime.h:107
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_runtime_suspend
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/phy/phy-core.c (0)
Location: include/linux/pm_runtime.h:106
Inline: True
```
```
In drivers/base/power/runtime.c (0)
Location: include/linux/pm_runtime.h:106
Inline: True
```
```
In drivers/base/power/domain.c (ffffffff815df9a0)
Location: include/linux/pm_runtime.h:106
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_runtime_suspend
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/phy/phy-core.c (0)
Location: include/linux/pm_runtime.h:96
Inline: True
```
```
In drivers/base/power/runtime.c (0)
Location: include/linux/pm_runtime.h:96
Inline: True
```
```
In drivers/base/power/domain.c (ffffffff815f4830)
Location: include/linux/pm_runtime.h:96
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_runtime_suspend
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/phy/phy-core.c (0)
Location: include/linux/pm_runtime.h:96
Inline: True
```
```
In drivers/clk/clk.c (0)
Location: include/linux/pm_runtime.h:96
Inline: True
```
```
In drivers/base/power/runtime.c (0)
Location: include/linux/pm_runtime.h:96
Inline: True
```
```
In drivers/base/power/main.c (0)
Location: include/linux/pm_runtime.h:96
Inline: True
```
```
In drivers/base/power/domain.c (ffffffff8165c7f0)
Location: include/linux/pm_runtime.h:96
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_runtime_suspend
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (0)
Location: include/linux/pm_runtime.h:96
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/phy/phy-core.c (ffffffff814facc4)
Location: include/linux/pm_runtime.h:96
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_create
  - drivers/phy/phy-core.c:phy_pm_runtime_forbid
  - drivers/phy/phy-core.c:phy_pm_runtime_allow
  - drivers/phy/phy-core.c:phy_pm_runtime_put_sync
  - drivers/phy/phy-core.c:phy_pm_runtime_put
  - drivers/phy/phy-core.c:phy_pm_runtime_get_sync
  - drivers/phy/phy-core.c:phy_pm_runtime_get
```
```
In drivers/clk/clk.c (ffffffff815e3acc)
Location: include/linux/pm_runtime.h:96
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_register
```
```
In drivers/base/power/runtime.c (ffffffff81690125)
Location: include/linux/pm_runtime.h:96
Inline: True
```
```
In drivers/base/power/main.c (ffffffff81693d26)
Location: include/linux/pm_runtime.h:96
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
```
```
In drivers/base/power/domain.c (ffffffff81698450)
Location: include/linux/pm_runtime.h:96
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_runtime_suspend
```
```
In drivers/gpu/vga/vga_switcheroo.c (ffffffff8172d4a9)
Location: include/linux/pm_runtime.h:96
Inline: True
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff817dba12)
Location: include/linux/pm_runtime.h:96
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/phy/phy-core.c (ffffffff8150f7e9)
Location: include/linux/pm_runtime.h:96
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_create
  - drivers/phy/phy-core.c:phy_pm_runtime_forbid
  - drivers/phy/phy-core.c:phy_pm_runtime_allow
  - drivers/phy/phy-core.c:phy_pm_runtime_put_sync
  - drivers/phy/phy-core.c:phy_pm_runtime_put
  - drivers/phy/phy-core.c:phy_pm_runtime_get_sync
  - drivers/phy/phy-core.c:phy_pm_runtime_get
```
```
In drivers/clk/clk.c (ffffffff815fdeac)
Location: include/linux/pm_runtime.h:96
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_register
```
```
In drivers/base/power/runtime.c (ffffffff816b0785)
Location: include/linux/pm_runtime.h:96
Inline: True
```
```
In drivers/base/power/main.c (ffffffff816b43a6)
Location: include/linux/pm_runtime.h:96
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
```
```
In drivers/base/power/domain.c (ffffffff816b8d90)
Location: include/linux/pm_runtime.h:96
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_runtime_suspend
```
```
In drivers/gpu/vga/vga_switcheroo.c (ffffffff8174fc49)
Location: include/linux/pm_runtime.h:96
Inline: True
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81802dbb)
Location: include/linux/pm_runtime.h:96
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/phy/phy-core.c (ffffffff8153de1f)
Location: include/linux/pm_runtime.h:95
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_create
  - drivers/phy/phy-core.c:phy_pm_runtime_forbid
  - drivers/phy/phy-core.c:phy_pm_runtime_allow
  - drivers/phy/phy-core.c:phy_pm_runtime_put_sync
  - drivers/phy/phy-core.c:phy_pm_runtime_put
  - drivers/phy/phy-core.c:phy_pm_runtime_get_sync
  - drivers/phy/phy-core.c:phy_pm_runtime_get
```
```
In drivers/clk/clk.c (ffffffff8162faf8)
Location: include/linux/pm_runtime.h:95
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_register
```
```
In drivers/base/power/runtime.c (ffffffff816ea375)
Location: include/linux/pm_runtime.h:95
Inline: True
```
```
In drivers/base/power/main.c (ffffffff816ee270)
Location: include/linux/pm_runtime.h:95
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
```
```
In drivers/base/power/domain.c (ffffffff816f2dbf)
Location: include/linux/pm_runtime.h:95
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_runtime_suspend
```
```
In drivers/gpu/vga/vga_switcheroo.c (ffffffff8178ba29)
Location: include/linux/pm_runtime.h:95
Inline: True
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff818441c3)
Location: include/linux/pm_runtime.h:95
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/phy/phy-core.c (ffffffff8155ec2f)
Location: include/linux/pm_runtime.h:95
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_create
  - drivers/phy/phy-core.c:phy_pm_runtime_forbid
  - drivers/phy/phy-core.c:phy_pm_runtime_allow
  - drivers/phy/phy-core.c:phy_pm_runtime_put_sync
  - drivers/phy/phy-core.c:phy_pm_runtime_put
  - drivers/phy/phy-core.c:phy_pm_runtime_get_sync
  - drivers/phy/phy-core.c:phy_pm_runtime_get
```
```
In drivers/clk/clk.c (ffffffff81651ee3)
Location: include/linux/pm_runtime.h:95
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_register
```
```
In drivers/base/power/runtime.c (ffffffff8170e3d5)
Location: include/linux/pm_runtime.h:95
Inline: True
```
```
In drivers/base/power/main.c (ffffffff81712250)
Location: include/linux/pm_runtime.h:95
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
```
```
In drivers/base/power/domain.c (ffffffff8171728f)
Location: include/linux/pm_runtime.h:95
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_runtime_suspend
```
```
In drivers/gpu/vga/vga_switcheroo.c (ffffffff817af649)
Location: include/linux/pm_runtime.h:95
Inline: True
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81875b39)
Location: include/linux/pm_runtime.h:95
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/phy/phy-core.c (ffffffff816009cf)
Location: include/linux/pm_runtime.h:100
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_create
  - drivers/phy/phy-core.c:phy_pm_runtime_forbid
  - drivers/phy/phy-core.c:phy_pm_runtime_allow
  - drivers/phy/phy-core.c:phy_pm_runtime_put_sync
  - drivers/phy/phy-core.c:phy_pm_runtime_get
```
```
In drivers/clk/clk.c (ffffffff81700fcd)
Location: include/linux/pm_runtime.h:100
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_register
```
```
In drivers/base/power/runtime.c (ffffffff817c9dc6)
Location: include/linux/pm_runtime.h:100
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_remove
```
```
In drivers/base/power/domain.c (ffffffff817d2f7f)
Location: include/linux/pm_runtime.h:100
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_runtime_suspend
```
```
In drivers/gpu/vga/vga_switcheroo.c (ffffffff81875be5)
Location: include/linux/pm_runtime.h:100
Inline: True
Inline callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_show
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_get_client_state
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff8194a483)
Location: include/linux/pm_runtime.h:100
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/phy/phy-core.c (ffffffff816258bf)
Location: include/linux/pm_runtime.h:170
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_create
  - drivers/phy/phy-core.c:phy_pm_runtime_forbid
  - drivers/phy/phy-core.c:phy_pm_runtime_allow
  - drivers/phy/phy-core.c:phy_pm_runtime_put_sync
  - drivers/phy/phy-core.c:phy_pm_runtime_get
```
```
In drivers/clk/clk.c (ffffffff8171e4ed)
Location: include/linux/pm_runtime.h:170
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_register
```
```
In drivers/base/power/runtime.c (ffffffff817de8b6)
Location: include/linux/pm_runtime.h:170
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_remove
```
```
In drivers/base/power/domain.c (ffffffff817e7aaf)
Location: include/linux/pm_runtime.h:170
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_runtime_suspend
```
```
In drivers/gpu/vga/vga_switcheroo.c (ffffffff818844c5)
Location: include/linux/pm_runtime.h:170
Inline: True
Inline callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_show
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_get_client_state
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81950013)
Location: include/linux/pm_runtime.h:170
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/phy/phy-core.c (ffffffff8160937f)
Location: include/linux/pm_runtime.h:170
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_create
  - drivers/phy/phy-core.c:phy_pm_runtime_forbid
  - drivers/phy/phy-core.c:phy_pm_runtime_allow
  - drivers/phy/phy-core.c:phy_pm_runtime_put_sync
  - drivers/phy/phy-core.c:phy_pm_runtime_get
```
```
In drivers/clk/clk.c (ffffffff816ff53d)
Location: include/linux/pm_runtime.h:170
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_register
```
```
In drivers/base/power/runtime.c (ffffffff817c2cb6)
Location: include/linux/pm_runtime.h:170
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_remove
```
```
In drivers/base/power/domain.c (ffffffff817cbb9f)
Location: include/linux/pm_runtime.h:170
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_runtime_suspend
```
```
In drivers/gpu/vga/vga_switcheroo.c (ffffffff81866d45)
Location: include/linux/pm_runtime.h:170
Inline: True
Inline callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_show
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_get_client_state
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81933ec5)
Location: include/linux/pm_runtime.h:170
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/phy/phy-core.c (ffffffff81677fef)
Location: include/linux/pm_runtime.h:173
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_create
  - drivers/phy/phy-core.c:phy_pm_runtime_forbid
  - drivers/phy/phy-core.c:phy_pm_runtime_allow
  - drivers/phy/phy-core.c:phy_pm_runtime_put_sync
  - drivers/phy/phy-core.c:phy_pm_runtime_get
```
```
In drivers/clk/clk.c (ffffffff81779d2d)
Location: include/linux/pm_runtime.h:173
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_register
```
```
In drivers/base/power/runtime.c (ffffffff8184d046)
Location: include/linux/pm_runtime.h:173
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_remove
```
```
In drivers/base/power/domain.c (ffffffff818561cf)
Location: include/linux/pm_runtime.h:173
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_runtime_suspend
```
```
In drivers/gpu/vga/vga_switcheroo.c (ffffffff818f6147)
Location: include/linux/pm_runtime.h:173
Inline: True
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff819d72c5)
Location: include/linux/pm_runtime.h:173
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/phy/phy-core.c (ffffffff8179327b)
Location: include/linux/pm_runtime.h:203
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_create
  - drivers/phy/phy-core.c:phy_power_off
  - drivers/phy/phy-core.c:phy_power_on
  - drivers/phy/phy-core.c:phy_pm_runtime_forbid
  - drivers/phy/phy-core.c:phy_pm_runtime_allow
  - drivers/phy/phy-core.c:phy_pm_runtime_put_sync
  - drivers/phy/phy-core.c:phy_pm_runtime_get
```
```
In drivers/clk/clk.c (ffffffff818b014f)
Location: include/linux/pm_runtime.h:203
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_register
```
```
In drivers/base/power/runtime.c (ffffffff81992416)
Location: include/linux/pm_runtime.h:203
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_remove
```
```
In drivers/base/power/domain.c (ffffffff8199ca38)
Location: include/linux/pm_runtime.h:203
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_runtime_suspend
```
```
In drivers/gpu/vga/vga_switcheroo.c (ffffffff81a46f99)
Location: include/linux/pm_runtime.h:203
Inline: True
Inline callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage2
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_show
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_get_client_state
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81b3a046)
Location: include/linux/pm_runtime.h:203
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/phy/phy-core.c (ffffffff818a7e4b)
Location: include/linux/pm_runtime.h:207
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_create
  - drivers/phy/phy-core.c:phy_power_off
  - drivers/phy/phy-core.c:phy_power_on
  - drivers/phy/phy-core.c:phy_power_on
  - drivers/phy/phy-core.c:phy_pm_runtime_forbid
  - drivers/phy/phy-core.c:phy_pm_runtime_allow
  - drivers/phy/phy-core.c:phy_pm_runtime_get
```
```
In drivers/clk/clk.c (ffffffff819fc5ff)
Location: include/linux/pm_runtime.h:207
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_register
```
```
In drivers/base/power/runtime.c (ffffffff81b02876)
Location: include/linux/pm_runtime.h:207
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_remove
```
```
In drivers/base/power/domain.c (ffffffff81b0dc98)
Location: include/linux/pm_runtime.h:207
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_runtime_suspend
```
```
In drivers/gpu/vga/vga_switcheroo.c (ffffffff81bcdf59)
Location: include/linux/pm_runtime.h:207
Inline: True
Inline callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage2
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_show
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_get_client_state
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81ccf9c6)
Location: include/linux/pm_runtime.h:207
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/phy/phy-core.c (ffffffff818eac5f)
Location: include/linux/pm_runtime.h:207
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_create
  - drivers/phy/phy-core.c:phy_power_off
  - drivers/phy/phy-core.c:phy_power_on
  - drivers/phy/phy-core.c:phy_power_on
  - drivers/phy/phy-core.c:phy_pm_runtime_forbid
  - drivers/phy/phy-core.c:phy_pm_runtime_allow
  - drivers/phy/phy-core.c:phy_pm_runtime_get
```
```
In drivers/clk/clk.c (ffffffff81a4506f)
Location: include/linux/pm_runtime.h:207
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_register
```
```
In drivers/base/power/runtime.c (ffffffff81b50926)
Location: include/linux/pm_runtime.h:207
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_remove
```
```
In drivers/base/power/domain.c (ffffffff81b5bd48)
Location: include/linux/pm_runtime.h:207
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_runtime_suspend
```
```
In drivers/gpu/vga/vga_switcheroo.c (ffffffff81c25b49)
Location: include/linux/pm_runtime.h:207
Inline: True
Inline callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage2
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_show
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_get_client_state
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81d37abf)
Location: include/linux/pm_runtime.h:207
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/phy/phy-core.c (ffffffff8193216e)
Location: include/linux/pm_runtime.h:205
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_create
  - drivers/phy/phy-core.c:phy_power_off
  - drivers/phy/phy-core.c:phy_power_on
  - drivers/phy/phy-core.c:phy_power_on
  - drivers/phy/phy-core.c:phy_pm_runtime_forbid
  - drivers/phy/phy-core.c:phy_pm_runtime_allow
  - drivers/phy/phy-core.c:phy_pm_runtime_get
```
```
In drivers/clk/clk.c (ffffffff81a90bae)
Location: include/linux/pm_runtime.h:205
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_register
```
```
In drivers/pmdomain/core.c (ffffffff81aa3848)
Location: include/linux/pm_runtime.h:205
Inline: True
Inline callers:
  - drivers/pmdomain/core.c:genpd_runtime_resume
  - drivers/pmdomain/core.c:genpd_runtime_suspend
```
```
In drivers/base/power/runtime.c (ffffffff81ba8ea6)
Location: include/linux/pm_runtime.h:205
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_remove
```
```
In drivers/gpu/vga/vga_switcheroo.c (ffffffff81cd82c9)
Location: include/linux/pm_runtime.h:205
Inline: True
Inline callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switchto_stage2
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_show
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_get_client_state
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81dedd3f)
Location: include/linux/pm_runtime.h:205
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
</details>
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
In drivers/phy/phy-core.c (ffff800010686b2c)
Location: include/linux/pm_runtime.h:95
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_create
  - drivers/phy/phy-core.c:phy_pm_runtime_forbid
  - drivers/phy/phy-core.c:phy_pm_runtime_allow
  - drivers/phy/phy-core.c:phy_pm_runtime_put_sync
  - drivers/phy/phy-core.c:phy_pm_runtime_put
  - drivers/phy/phy-core.c:phy_pm_runtime_get_sync
  - drivers/phy/phy-core.c:phy_pm_runtime_get
```
```
In drivers/clk/clk.c (ffff8000107c2a6c)
Location: include/linux/pm_runtime.h:95
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_register
```
```
In drivers/iommu/arm-smmu.c (ffff8000108cfec4)
Location: include/linux/pm_runtime.h:95
Inline: True
Inline callers:
  - drivers/iommu/arm-smmu.c:arm_smmu_device_shutdown
  - drivers/iommu/arm-smmu.c:arm_smmu_device_shutdown
  - drivers/iommu/arm-smmu.c:arm_smmu_remove_device
  - drivers/iommu/arm-smmu.c:arm_smmu_remove_device
  - drivers/iommu/arm-smmu.c:arm_smmu_add_device
  - drivers/iommu/arm-smmu.c:arm_smmu_add_device
  - drivers/iommu/arm-smmu.c:arm_smmu_iova_to_phys_hard
  - drivers/iommu/arm-smmu.c:arm_smmu_iova_to_phys_hard
  - drivers/iommu/arm-smmu.c:arm_smmu_iotlb_sync
  - drivers/iommu/arm-smmu.c:arm_smmu_iotlb_sync
  - drivers/iommu/arm-smmu.c:arm_smmu_flush_iotlb_all
  - drivers/iommu/arm-smmu.c:arm_smmu_flush_iotlb_all
  - drivers/iommu/arm-smmu.c:arm_smmu_unmap
  - drivers/iommu/arm-smmu.c:arm_smmu_unmap
  - drivers/iommu/arm-smmu.c:arm_smmu_map
  - drivers/iommu/arm-smmu.c:arm_smmu_map
  - drivers/iommu/arm-smmu.c:arm_smmu_attach_dev
  - drivers/iommu/arm-smmu.c:arm_smmu_attach_dev
  - drivers/iommu/arm-smmu.c:arm_smmu_domain_free
  - drivers/iommu/arm-smmu.c:arm_smmu_domain_free
```
```
In drivers/base/power/runtime.c (ffff8000108fdf58)
Location: include/linux/pm_runtime.h:95
Inline: True
```
```
In drivers/base/power/main.c (ffff800010902c58)
Location: include/linux/pm_runtime.h:95
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
```
```
In drivers/base/power/domain.c (ffff8000109094e4)
Location: include/linux/pm_runtime.h:95
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_runtime_suspend
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffff800010aba97c)
Location: include/linux/pm_runtime.h:95
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/phy/phy-core.c (c082a88c)
Location: include/linux/pm_runtime.h:95
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_create
  - drivers/phy/phy-core.c:phy_pm_runtime_forbid
  - drivers/phy/phy-core.c:phy_pm_runtime_allow
  - drivers/phy/phy-core.c:phy_pm_runtime_put_sync
  - drivers/phy/phy-core.c:phy_pm_runtime_put
  - drivers/phy/phy-core.c:phy_pm_runtime_get_sync
  - drivers/phy/phy-core.c:phy_pm_runtime_get
```
```
In drivers/clk/clk.c (c08ed6d4)
Location: include/linux/pm_runtime.h:95
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_register
```
```
In drivers/dma/tegra20-apb-dma.c (c092a5d8)
Location: include/linux/pm_runtime.h:95
Inline: True
Inline callers:
  - drivers/dma/tegra20-apb-dma.c:tegra_dma_probe
```
```
In drivers/base/power/runtime.c (c09e8af4)
Location: include/linux/pm_runtime.h:95
Inline: True
```
```
In drivers/base/power/main.c (c09ed080)
Location: include/linux/pm_runtime.h:95
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
```
```
In drivers/base/power/domain.c (c09f3950)
Location: include/linux/pm_runtime.h:95
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_runtime_suspend
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (c0b99ed8)
Location: include/linux/pm_runtime.h:95
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/phy/phy-core.c (c000000000823038)
Location: include/linux/pm_runtime.h:95
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_create
  - drivers/phy/phy-core.c:phy_pm_runtime_forbid
  - drivers/phy/phy-core.c:phy_pm_runtime_allow
  - drivers/phy/phy-core.c:phy_pm_runtime_put_sync
  - drivers/phy/phy-core.c:phy_pm_runtime_put
  - drivers/phy/phy-core.c:phy_pm_runtime_get_sync
  - drivers/phy/phy-core.c:phy_pm_runtime_get
```
```
In drivers/base/power/runtime.c (c00000000099b150)
Location: include/linux/pm_runtime.h:95
Inline: True
```
```
In drivers/base/power/main.c (c0000000009a11e4)
Location: include/linux/pm_runtime.h:95
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
```
```
In drivers/base/power/domain.c (c0000000009a9420)
Location: include/linux/pm_runtime.h:95
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_runtime_suspend
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (c000000000b9de4c)
Location: include/linux/pm_runtime.h:95
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/phy/phy-core.c (ffffffe000497242)
Location: include/linux/pm_runtime.h:95
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_create
  - drivers/phy/phy-core.c:phy_pm_runtime_forbid
  - drivers/phy/phy-core.c:phy_pm_runtime_allow
  - drivers/phy/phy-core.c:phy_pm_runtime_put_sync
  - drivers/phy/phy-core.c:phy_pm_runtime_put
  - drivers/phy/phy-core.c:phy_pm_runtime_get_sync
  - drivers/phy/phy-core.c:phy_pm_runtime_get
```
```
In drivers/clk/clk.c (ffffffe0005104c0)
Location: include/linux/pm_runtime.h:95
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_register
```
```
In drivers/base/power/runtime.c (ffffffe00058c9a8)
Location: include/linux/pm_runtime.h:95
Inline: True
```
```
In drivers/base/power/domain.c (ffffffe00058fd58)
Location: include/linux/pm_runtime.h:95
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_runtime_suspend
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffe0006bf2e0)
Location: include/linux/pm_runtime.h:95
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/phy/phy-core.c (ffffffff8155721f)
Location: include/linux/pm_runtime.h:95
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_create
  - drivers/phy/phy-core.c:phy_pm_runtime_forbid
  - drivers/phy/phy-core.c:phy_pm_runtime_allow
  - drivers/phy/phy-core.c:phy_pm_runtime_put_sync
  - drivers/phy/phy-core.c:phy_pm_runtime_put
  - drivers/phy/phy-core.c:phy_pm_runtime_get_sync
  - drivers/phy/phy-core.c:phy_pm_runtime_get
```
```
In drivers/clk/clk.c (ffffffff81617f43)
Location: include/linux/pm_runtime.h:95
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_register
```
```
In drivers/base/power/runtime.c (ffffffff816d3b25)
Location: include/linux/pm_runtime.h:95
Inline: True
```
```
In drivers/base/power/main.c (ffffffff816d85d0)
Location: include/linux/pm_runtime.h:95
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
```
```
In drivers/base/power/domain.c (ffffffff816dd5bf)
Location: include/linux/pm_runtime.h:95
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_runtime_suspend
```
```
In drivers/gpu/vga/vga_switcheroo.c (ffffffff81774179)
Location: include/linux/pm_runtime.h:95
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/phy/phy-core.c (ffffffff815476df)
Location: include/linux/pm_runtime.h:95
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_create
  - drivers/phy/phy-core.c:phy_pm_runtime_forbid
  - drivers/phy/phy-core.c:phy_pm_runtime_allow
  - drivers/phy/phy-core.c:phy_pm_runtime_put_sync
  - drivers/phy/phy-core.c:phy_pm_runtime_put
  - drivers/phy/phy-core.c:phy_pm_runtime_get_sync
  - drivers/phy/phy-core.c:phy_pm_runtime_get
```
```
In drivers/clk/clk.c (ffffffff8160c473)
Location: include/linux/pm_runtime.h:95
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_register
```
```
In drivers/base/power/runtime.c (ffffffff816aedd5)
Location: include/linux/pm_runtime.h:95
Inline: True
```
```
In drivers/base/power/main.c (ffffffff816b2c30)
Location: include/linux/pm_runtime.h:95
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
```
```
In drivers/base/power/domain.c (ffffffff816b7c2f)
Location: include/linux/pm_runtime.h:95
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_runtime_suspend
```
```
In drivers/gpu/vga/vga_switcheroo.c (ffffffff81753f29)
Location: include/linux/pm_runtime.h:95
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/phy/phy-core.c (ffffffff81552f5f)
Location: include/linux/pm_runtime.h:95
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_create
  - drivers/phy/phy-core.c:phy_pm_runtime_forbid
  - drivers/phy/phy-core.c:phy_pm_runtime_allow
  - drivers/phy/phy-core.c:phy_pm_runtime_put_sync
  - drivers/phy/phy-core.c:phy_pm_runtime_put
  - drivers/phy/phy-core.c:phy_pm_runtime_get_sync
  - drivers/phy/phy-core.c:phy_pm_runtime_get
```
```
In drivers/clk/clk.c (ffffffff81645d23)
Location: include/linux/pm_runtime.h:95
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_register
```
```
In drivers/base/power/runtime.c (ffffffff81702095)
Location: include/linux/pm_runtime.h:95
Inline: True
```
```
In drivers/base/power/main.c (ffffffff81705f10)
Location: include/linux/pm_runtime.h:95
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
```
```
In drivers/base/power/domain.c (ffffffff8170af4f)
Location: include/linux/pm_runtime.h:95
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_runtime_suspend
```
```
In drivers/gpu/vga/vga_switcheroo.c (ffffffff817a44c9)
Location: include/linux/pm_runtime.h:95
Inline: True
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff8186afe9)
Location: include/linux/pm_runtime.h:95
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/phy/phy-core.c (ffffffff8156cdef)
Location: include/linux/pm_runtime.h:95
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_create
  - drivers/phy/phy-core.c:phy_pm_runtime_forbid
  - drivers/phy/phy-core.c:phy_pm_runtime_allow
  - drivers/phy/phy-core.c:phy_pm_runtime_put_sync
  - drivers/phy/phy-core.c:phy_pm_runtime_put
  - drivers/phy/phy-core.c:phy_pm_runtime_get_sync
  - drivers/phy/phy-core.c:phy_pm_runtime_get
```
```
In drivers/clk/clk.c (ffffffff816602b3)
Location: include/linux/pm_runtime.h:95
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_register
```
```
In drivers/base/power/runtime.c (ffffffff8171c8c5)
Location: include/linux/pm_runtime.h:95
Inline: True
```
```
In drivers/base/power/main.c (ffffffff817208db)
Location: include/linux/pm_runtime.h:95
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
```
```
In drivers/base/power/domain.c (ffffffff81725dbf)
Location: include/linux/pm_runtime.h:95
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_runtime_suspend
```
```
In drivers/gpu/vga/vga_switcheroo.c (ffffffff817be349)
Location: include/linux/pm_runtime.h:95
Inline: True
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81884f79)
Location: include/linux/pm_runtime.h:95
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
</details>
</li>
</ul>

## Differences
