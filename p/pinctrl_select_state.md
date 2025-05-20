# Function: <code>pinctrl_select_state</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int pinctrl_select_state(struct pinctrl *p, struct pinctrl_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff8141d520)
Location: drivers/pinctrl/core.c:986
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_select_state
  - drivers/pinctrl/core.c:pinctrl_force_sleep
  - drivers/pinctrl/core.c:pinctrl_force_default
  - drivers/pinctrl/core.c:pinctrl_pm_select_state
  - drivers/pinctrl/core.c:pinctrl_register
  - drivers/pinctrl/core.c:pinctrl_init_done
  - drivers/base/pinctrl.c:pinctrl_bind_pins
  - drivers/base/pinctrl.c:pinctrl_bind_pins
```
**Symbols:**

```
ffffffff8141d520-ffffffff8141d678: pinctrl_select_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int pinctrl_select_state(struct pinctrl *p, struct pinctrl_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff81465bf0)
Location: drivers/pinctrl/core.c:999
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_register
  - drivers/pinctrl/core.c:pinctrl_pm_select_state
  - drivers/pinctrl/core.c:pinctrl_init_done
  - drivers/pinctrl/core.c:pinctrl_force_default
  - drivers/pinctrl/core.c:pinctrl_force_sleep
  - drivers/pinctrl/core.c:pinctrl_select_state
  - drivers/base/pinctrl.c:pinctrl_bind_pins
  - drivers/base/pinctrl.c:pinctrl_bind_pins
```
**Symbols:**

```
ffffffff81465bf0-ffffffff81465d30: pinctrl_select_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int pinctrl_select_state(struct pinctrl *p, struct pinctrl_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff81484ef0)
Location: drivers/pinctrl/core.c:999
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_register
  - drivers/pinctrl/core.c:pinctrl_pm_select_state
  - drivers/pinctrl/core.c:pinctrl_init_done
  - drivers/pinctrl/core.c:pinctrl_force_default
  - drivers/pinctrl/core.c:pinctrl_force_sleep
  - drivers/pinctrl/core.c:pinctrl_select_state
  - drivers/base/pinctrl.c:pinctrl_bind_pins
  - drivers/base/pinctrl.c:pinctrl_bind_pins
```
**Symbols:**

```
ffffffff81484ef0-ffffffff81485030: pinctrl_select_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int pinctrl_select_state(struct pinctrl *p, struct pinctrl_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff8148e6c0)
Location: drivers/pinctrl/core.c:1196
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_pm_select_state
  - drivers/pinctrl/core.c:pinctrl_init_done
  - drivers/pinctrl/core.c:pinctrl_force_default
  - drivers/pinctrl/core.c:pinctrl_force_sleep
  - drivers/pinctrl/core.c:pinctrl_select_state
  - drivers/base/pinctrl.c:pinctrl_bind_pins
  - drivers/base/pinctrl.c:pinctrl_bind_pins
```
**Symbols:**

```
ffffffff8148e6c0-ffffffff8148e7f7: pinctrl_select_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int pinctrl_select_state(struct pinctrl *p, struct pinctrl_state *state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff814ca96a)
Location: drivers/pinctrl/core.c:1271
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:pinctrl_pm_select_state
  - drivers/pinctrl/core.c:pinctrl_init_done
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_commit_state
  - drivers/base/pinctrl.c:pinctrl_bind_pins
  - drivers/base/pinctrl.c:pinctrl_bind_pins
```
**Symbols:**

```
ffffffff814ca930-ffffffff814ca949: pinctrl_select_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int pinctrl_select_state(struct pinctrl *p, struct pinctrl_state *state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff814fb8ca)
Location: drivers/pinctrl/core.c:1271
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:pinctrl_pm_select_state
  - drivers/pinctrl/core.c:pinctrl_init_done
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_commit_state
  - drivers/base/pinctrl.c:pinctrl_bind_pins
  - drivers/base/pinctrl.c:pinctrl_bind_pins
```
**Symbols:**

```
ffffffff814fb890-ffffffff814fb8a9: pinctrl_select_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int pinctrl_select_state(struct pinctrl *p, struct pinctrl_state *state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff8151039a)
Location: drivers/pinctrl/core.c:1299
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:pinctrl_pm_select_state
  - drivers/pinctrl/core.c:pinctrl_init_done
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_commit_state
  - drivers/base/pinctrl.c:pinctrl_bind_pins
  - drivers/base/pinctrl.c:pinctrl_bind_pins
```
**Symbols:**

```
ffffffff81510360-ffffffff81510379: pinctrl_select_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int pinctrl_select_state(struct pinctrl *p, struct pinctrl_state *state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff8153ff3e)
Location: drivers/pinctrl/core.c:1288
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:pinctrl_enable
  - drivers/pinctrl/core.c:pinctrl_pm_select_state
  - drivers/pinctrl/core.c:pinctrl_init_done
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_commit_state
  - drivers/base/pinctrl.c:pinctrl_bind_pins
  - drivers/base/pinctrl.c:pinctrl_bind_pins
```
**Symbols:**

```
ffffffff8153ea20-ffffffff8153ea39: pinctrl_select_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int pinctrl_select_state(struct pinctrl *p, struct pinctrl_state *state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff81560df2)
Location: drivers/pinctrl/core.c:1316
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:pinctrl_enable
  - drivers/pinctrl/core.c:pinctrl_pm_select_state
  - drivers/pinctrl/core.c:pinctrl_init_done
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_commit_state
  - drivers/base/pinctrl.c:pinctrl_bind_pins
  - drivers/base/pinctrl.c:pinctrl_bind_pins
```
**Symbols:**

```
ffffffff8155f8c0-ffffffff8155f8d9: pinctrl_select_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int pinctrl_select_state(struct pinctrl *p, struct pinctrl_state *state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff81603771)
Location: drivers/pinctrl/core.c:1317
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:pinctrl_claim_hogs
  - drivers/pinctrl/core.c:pinctrl_pm_select_idle_state
  - drivers/pinctrl/core.c:pinctrl_pm_select_sleep_state
  - drivers/pinctrl/core.c:pinctrl_pm_select_default_state
  - drivers/pinctrl/core.c:pinctrl_init_done
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_commit_state
  - drivers/base/pinctrl.c:pinctrl_bind_pins
  - drivers/base/pinctrl.c:pinctrl_bind_pins
```
**Symbols:**

```
ffffffff81601bf0-ffffffff81601c09: pinctrl_select_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int pinctrl_select_state(struct pinctrl *p, struct pinctrl_state *state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff81628681)
Location: drivers/pinctrl/core.c:1318
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:pinctrl_claim_hogs
  - drivers/pinctrl/core.c:pinctrl_pm_select_idle_state
  - drivers/pinctrl/core.c:pinctrl_pm_select_sleep_state
  - drivers/pinctrl/core.c:pinctrl_pm_select_default_state
  - drivers/pinctrl/core.c:pinctrl_init_done
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_commit_state
  - drivers/base/pinctrl.c:pinctrl_bind_pins
  - drivers/base/pinctrl.c:pinctrl_bind_pins
  - drivers/i2c/i2c-core-base.c:i2c_gpio_init_generic_recovery
  - drivers/i2c/i2c-core-base.c:i2c_gpio_init_generic_recovery
  - drivers/i2c/i2c-core-base.c:i2c_generic_scl_recovery
  - drivers/i2c/i2c-core-base.c:i2c_generic_scl_recovery
```
**Symbols:**

```
ffffffff81626a50-ffffffff81626a69: pinctrl_select_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int pinctrl_select_state(struct pinctrl *p, struct pinctrl_state *state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff8160c161)
Location: drivers/pinctrl/core.c:1341
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:pinctrl_claim_hogs
  - drivers/pinctrl/core.c:pinctrl_pm_select_idle_state
  - drivers/pinctrl/core.c:pinctrl_pm_select_sleep_state
  - drivers/pinctrl/core.c:pinctrl_pm_select_default_state
  - drivers/pinctrl/core.c:pinctrl_init_done
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_commit_state
  - drivers/base/pinctrl.c:pinctrl_bind_pins
  - drivers/base/pinctrl.c:pinctrl_bind_pins
  - drivers/i2c/i2c-core-base.c:i2c_init_recovery
  - drivers/i2c/i2c-core-base.c:i2c_init_recovery
  - drivers/i2c/i2c-core-base.c:i2c_init_recovery
  - drivers/i2c/i2c-core-base.c:i2c_generic_scl_recovery
  - drivers/i2c/i2c-core-base.c:i2c_generic_scl_recovery
```
**Symbols:**

```
ffffffff8160b330-ffffffff8160b349: pinctrl_select_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int pinctrl_select_state(struct pinctrl *p, struct pinctrl_state *state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff8167ae61)
Location: drivers/pinctrl/core.c:1341
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:pinctrl_claim_hogs
  - drivers/pinctrl/core.c:pinctrl_pm_select_idle_state
  - drivers/pinctrl/core.c:pinctrl_pm_select_sleep_state
  - drivers/pinctrl/core.c:pinctrl_pm_select_default_state
  - drivers/pinctrl/core.c:pinctrl_init_done
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_commit_state
  - drivers/base/pinctrl.c:pinctrl_bind_pins
  - drivers/base/pinctrl.c:pinctrl_bind_pins
  - drivers/i2c/i2c-core-base.c:i2c_init_recovery
  - drivers/i2c/i2c-core-base.c:i2c_init_recovery
  - drivers/i2c/i2c-core-base.c:i2c_init_recovery
  - drivers/i2c/i2c-core-base.c:i2c_generic_scl_recovery
  - drivers/i2c/i2c-core-base.c:i2c_generic_scl_recovery
```
**Symbols:**

```
ffffffff8167a350-ffffffff8167a369: pinctrl_select_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int pinctrl_select_state(struct pinctrl *p, struct pinctrl_state *state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff8179655e)
Location: drivers/pinctrl/core.c:1341
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:pinctrl_claim_hogs
  - drivers/pinctrl/core.c:pinctrl_pm_select_idle_state
  - drivers/pinctrl/core.c:pinctrl_pm_select_sleep_state
  - drivers/pinctrl/core.c:pinctrl_pm_select_default_state
  - drivers/pinctrl/core.c:pinctrl_init_done
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_commit_state
  - drivers/base/pinctrl.c:pinctrl_bind_pins
  - drivers/base/pinctrl.c:pinctrl_bind_pins
  - drivers/i2c/i2c-core-base.c:i2c_init_recovery
  - drivers/i2c/i2c-core-base.c:i2c_init_recovery
  - drivers/i2c/i2c-core-base.c:i2c_init_recovery
  - drivers/i2c/i2c-core-base.c:i2c_generic_scl_recovery
  - drivers/i2c/i2c-core-base.c:i2c_generic_scl_recovery
```
**Symbols:**

```
ffffffff817958e0-ffffffff81795909: pinctrl_select_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int pinctrl_select_state(struct pinctrl *p, struct pinctrl_state *state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff818abca2)
Location: drivers/pinctrl/core.c:1341
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:pinctrl_claim_hogs
  - drivers/pinctrl/core.c:pinctrl_pm_select_idle_state
  - drivers/pinctrl/core.c:pinctrl_pm_select_sleep_state
  - drivers/pinctrl/core.c:pinctrl_pm_select_default_state
  - drivers/pinctrl/core.c:pinctrl_init_done
  - drivers/pinctrl/core.c:pinctrl_commit_state
Direct callers:
  - drivers/base/pinctrl.c:pinctrl_bind_pins
  - drivers/base/pinctrl.c:pinctrl_bind_pins
  - drivers/i2c/i2c-core-base.c:i2c_init_recovery
  - drivers/i2c/i2c-core-base.c:i2c_init_recovery
  - drivers/i2c/i2c-core-base.c:i2c_init_recovery
  - drivers/i2c/i2c-core-base.c:i2c_generic_scl_recovery
  - drivers/i2c/i2c-core-base.c:i2c_generic_scl_recovery
```
**Symbols:**

```
ffffffff818ab1d0-ffffffff818ab1f9: pinctrl_select_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int pinctrl_select_state(struct pinctrl *p, struct pinctrl_state *state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff818eebe2)
Location: drivers/pinctrl/core.c:1345
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:pinctrl_claim_hogs
  - drivers/pinctrl/core.c:pinctrl_pm_select_idle_state
  - drivers/pinctrl/core.c:pinctrl_pm_select_sleep_state
  - drivers/pinctrl/core.c:pinctrl_pm_select_default_state
  - drivers/pinctrl/core.c:pinctrl_init_done
  - drivers/pinctrl/core.c:pinctrl_commit_state
Direct callers:
  - drivers/base/pinctrl.c:pinctrl_bind_pins
  - drivers/base/pinctrl.c:pinctrl_bind_pins
  - drivers/i2c/i2c-core-base.c:i2c_init_recovery
  - drivers/i2c/i2c-core-base.c:i2c_init_recovery
  - drivers/i2c/i2c-core-base.c:i2c_init_recovery
  - drivers/i2c/i2c-core-base.c:i2c_generic_scl_recovery
  - drivers/i2c/i2c-core-base.c:i2c_generic_scl_recovery
```
**Symbols:**

```
ffffffff818ee0d0-ffffffff818ee0f9: pinctrl_select_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int pinctrl_select_state(struct pinctrl *p, struct pinctrl_state *state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff819363a2)
Location: drivers/pinctrl/core.c:1359
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:pinctrl_claim_hogs
  - drivers/pinctrl/core.c:pinctrl_pm_select_idle_state
  - drivers/pinctrl/core.c:pinctrl_pm_select_sleep_state
  - drivers/pinctrl/core.c:pinctrl_pm_select_default_state
  - drivers/pinctrl/core.c:pinctrl_init_done
  - drivers/pinctrl/core.c:pinctrl_commit_state
Direct callers:
  - drivers/base/pinctrl.c:pinctrl_bind_pins
  - drivers/base/pinctrl.c:pinctrl_bind_pins
  - drivers/i2c/i2c-core-base.c:i2c_init_recovery
  - drivers/i2c/i2c-core-base.c:i2c_init_recovery
  - drivers/i2c/i2c-core-base.c:i2c_init_recovery
  - drivers/i2c/i2c-core-base.c:i2c_generic_scl_recovery
  - drivers/i2c/i2c-core-base.c:i2c_generic_scl_recovery
```
**Symbols:**

```
ffffffff81935890-ffffffff819358b9: pinctrl_select_state (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int pinctrl_select_state(struct pinctrl *p, struct pinctrl_state *state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffff80001068d928)
Location: drivers/pinctrl/core.c:1316
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:pinctrl_enable
  - drivers/pinctrl/core.c:pinctrl_pm_select_state
  - drivers/pinctrl/core.c:pinctrl_init_done
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_commit_state
  - drivers/pinctrl/sprd/pinctrl-sprd.c:sprd_pinctrl_shutdown
  - drivers/base/pinctrl.c:pinctrl_bind_pins
  - drivers/base/pinctrl.c:pinctrl_bind_pins
  - drivers/mmc/host/mmci.c:mmci_set_ios
  - drivers/mmc/host/mmci.c:mmci_set_ios
```
**Symbols:**

```
ffff80001068be88-ffff80001068bed8: pinctrl_select_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int pinctrl_select_state(struct pinctrl *p, struct pinctrl_state *state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (c082f980)
Location: drivers/pinctrl/core.c:1316
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:pinctrl_enable
  - drivers/pinctrl/core.c:pinctrl_pm_select_state
  - drivers/pinctrl/core.c:pinctrl_init_done
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_commit_state
  - drivers/base/pinctrl.c:pinctrl_bind_pins
  - drivers/base/pinctrl.c:pinctrl_bind_pins
  - drivers/i2c/busses/i2c-imx.c:i2c_imx_unprepare_recovery
  - drivers/i2c/busses/i2c-imx.c:i2c_imx_prepare_recovery
  - drivers/i2c/busses/i2c-s3c2410.c:s3c24xx_i2c_probe
  - drivers/mmc/host/mmci.c:mmci_set_ios
  - drivers/mmc/host/sdhci-esdhc-imx.c:esdhc_set_uhs_signaling
  - drivers/mmc/host/sdhci-esdhc-imx.c:esdhc_set_uhs_signaling
  - sound/soc/soc-dapm.c:dapm_pinctrl_event
  - sound/soc/soc-ac97.c:snd_soc_ac97_reset
  - sound/soc/soc-ac97.c:snd_soc_ac97_reset
  - sound/soc/soc-ac97.c:snd_soc_ac97_warm_reset
  - sound/soc/soc-ac97.c:snd_soc_ac97_warm_reset
```
**Symbols:**

```
c082e15c-c082e18c: pinctrl_select_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int pinctrl_select_state(struct pinctrl *p, struct pinctrl_state *state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (c0000000008279a8)
Location: drivers/pinctrl/core.c:1316
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:pinctrl_enable
  - drivers/pinctrl/core.c:pinctrl_pm_select_state
  - drivers/pinctrl/core.c:pinctrl_init_done
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_commit_state
  - drivers/base/pinctrl.c:pinctrl_bind_pins
  - drivers/base/pinctrl.c:pinctrl_bind_pins
```
**Symbols:**

```
c000000000824b50-c000000000824b78: pinctrl_select_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int pinctrl_select_state(struct pinctrl *p, struct pinctrl_state *state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffe000499ace)
Location: drivers/pinctrl/core.c:1316
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:pinctrl_enable
  - drivers/pinctrl/core.c:pinctrl_pm_select_state
  - drivers/pinctrl/core.c:pinctrl_init_done
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_commit_state
  - drivers/base/pinctrl.c:pinctrl_bind_pins
  - drivers/base/pinctrl.c:pinctrl_bind_pins
```
**Symbols:**

```
ffffffe00049828a-ffffffe0004982c4: pinctrl_select_state (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int pinctrl_select_state(struct pinctrl *p, struct pinctrl_state *state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff815593e2)
Location: drivers/pinctrl/core.c:1316
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:pinctrl_enable
  - drivers/pinctrl/core.c:pinctrl_pm_select_state
  - drivers/pinctrl/core.c:pinctrl_init_done
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_commit_state
  - drivers/base/pinctrl.c:pinctrl_bind_pins
  - drivers/base/pinctrl.c:pinctrl_bind_pins
```
**Symbols:**

```
ffffffff81557eb0-ffffffff81557ec9: pinctrl_select_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int pinctrl_select_state(struct pinctrl *p, struct pinctrl_state *state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff815498a2)
Location: drivers/pinctrl/core.c:1316
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:pinctrl_enable
  - drivers/pinctrl/core.c:pinctrl_pm_select_state
  - drivers/pinctrl/core.c:pinctrl_init_done
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_commit_state
  - drivers/base/pinctrl.c:pinctrl_bind_pins
  - drivers/base/pinctrl.c:pinctrl_bind_pins
```
**Symbols:**

```
ffffffff81548370-ffffffff81548389: pinctrl_select_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int pinctrl_select_state(struct pinctrl *p, struct pinctrl_state *state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff81555122)
Location: drivers/pinctrl/core.c:1316
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:pinctrl_enable
  - drivers/pinctrl/core.c:pinctrl_pm_select_state
  - drivers/pinctrl/core.c:pinctrl_init_done
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_commit_state
  - drivers/base/pinctrl.c:pinctrl_bind_pins
  - drivers/base/pinctrl.c:pinctrl_bind_pins
```
**Symbols:**

```
ffffffff81553bf0-ffffffff81553c09: pinctrl_select_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int pinctrl_select_state(struct pinctrl *p, struct pinctrl_state *state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff8156efb2)
Location: drivers/pinctrl/core.c:1316
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:pinctrl_enable
  - drivers/pinctrl/core.c:pinctrl_pm_select_state
  - drivers/pinctrl/core.c:pinctrl_init_done
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_commit_state
  - drivers/base/pinctrl.c:pinctrl_bind_pins
  - drivers/base/pinctrl.c:pinctrl_bind_pins
```
**Symbols:**

```
ffffffff8156da80-ffffffff8156da99: pinctrl_select_state (STB_GLOBAL)
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
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
