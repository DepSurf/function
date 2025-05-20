# Function: <code>pcie_do_write_cmd</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void pcie_do_write_cmd(struct controller *ctrl, u16 cmd, u16 mask, bool wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff814503b0)
Location: drivers/pci/hotplug/pciehp_hpc.c:181
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_set_attention_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_green_led_on
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_green_led_off
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_green_led_blink
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_off_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_enable_notification
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_release_ctrl
```
**Symbols:**

```
ffffffff814503b0-ffffffff814504ab: pcie_do_write_cmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void pcie_do_write_cmd(struct controller *ctrl, u16 cmd, u16 mask, bool wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff8149cb80)
Location: drivers/pci/hotplug/pciehp_hpc.c:181
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_release_ctrl
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_enable_notification
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_off_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_green_led_blink
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_green_led_off
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_green_led_on
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_set_attention_status
```
**Symbols:**

```
ffffffff8149cb80-ffffffff8149cc7a: pcie_do_write_cmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void pcie_do_write_cmd(struct controller *ctrl, u16 cmd, u16 mask, bool wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff814be700)
Location: drivers/pci/hotplug/pciehp_hpc.c:181
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_release_ctrl
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_enable_notification
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_off_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_green_led_blink
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_green_led_off
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_green_led_on
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_set_attention_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_set_raw_indicator_status
```
**Symbols:**

```
ffffffff814be700-ffffffff814be7fa: pcie_do_write_cmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void pcie_do_write_cmd(struct controller *ctrl, u16 cmd, u16 mask, bool wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff814c8ee0)
Location: drivers/pci/hotplug/pciehp_hpc.c:181
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_release_ctrl
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_enable_notification
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_off_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_green_led_blink
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_green_led_off
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_green_led_on
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_set_attention_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_set_raw_indicator_status
```
**Symbols:**

```
ffffffff814c8ee0-ffffffff814c8fdc: pcie_do_write_cmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void pcie_do_write_cmd(struct controller *ctrl, u16 cmd, u16 mask, bool wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff815094a0)
Location: drivers/pci/hotplug/pciehp_hpc.c:178
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_release_ctrl
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_enable_notification
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_off_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_green_led_blink
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_green_led_off
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_green_led_on
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_set_attention_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_set_raw_indicator_status
```
**Symbols:**

```
ffffffff815094a0-ffffffff8150959c: pcie_do_write_cmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void pcie_do_write_cmd(struct controller *ctrl, u16 cmd, u16 mask, bool wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff8153a390)
Location: drivers/pci/hotplug/pciehp_hpc.c:160
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_shutdown_notification
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_enable_notification
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_off_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_green_led_blink
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_green_led_off
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_green_led_on
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_set_attention_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_set_raw_indicator_status
```
**Symbols:**

```
ffffffff8153a390-ffffffff8153a4b8: pcie_do_write_cmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void pcie_do_write_cmd(struct controller *ctrl, u16 cmd, u16 mask, bool wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff815516b0)
Location: drivers/pci/hotplug/pciehp_hpc.c:135
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_disable_interrupt
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_enable_interrupt
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_green_led_blink
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_green_led_on
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_set_raw_indicator_status
```
**Symbols:**

```
ffffffff815516b0-ffffffff815517d5: pcie_do_write_cmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void pcie_do_write_cmd(struct controller *ctrl, u16 cmd, u16 mask, bool wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (0)
Location: drivers/pci/hotplug/pciehp_hpc.c:137
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_disable_interrupt
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_enable_interrupt
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_green_led_blink
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_green_led_on
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_set_raw_indicator_status
```
**Symbols:**

```
ffffffff81581630-ffffffff8158173b: pcie_do_write_cmd (STB_LOCAL)
ffffffff81582d4c-ffffffff81582d73: pcie_do_write_cmd.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void pcie_do_write_cmd(struct controller *ctrl, u16 cmd, u16 mask, bool wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (0)
Location: drivers/pci/hotplug/pciehp_hpc.c:137
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_disable_interrupt
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_enable_interrupt
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_set_indicators
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_set_raw_indicator_status
```
**Symbols:**

```
ffffffff815a3130-ffffffff815a323b: pcie_do_write_cmd (STB_LOCAL)
ffffffff815a472c-ffffffff815a4753: pcie_do_write_cmd.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void pcie_do_write_cmd(struct controller *ctrl, u16 cmd, u16 mask, bool wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (0)
Location: drivers/pci/hotplug/pciehp_hpc.c:154
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_disable_interrupt
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_enable_interrupt
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_set_indicators
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_set_raw_indicator_status
```
**Symbols:**

```
ffffffff8164bcc0-ffffffff8164bdcb: pcie_do_write_cmd (STB_LOCAL)
ffffffff8164d38f-ffffffff8164d3b6: pcie_do_write_cmd.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void pcie_do_write_cmd(struct controller *ctrl, u16 cmd, u16 mask, bool wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (0)
Location: drivers/pci/hotplug/pciehp_hpc.c:154
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_disable_interrupt
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_enable_interrupt
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_set_indicators
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_set_raw_indicator_status
```
**Symbols:**

```
ffffffff81670010-ffffffff8167011b: pcie_do_write_cmd (STB_LOCAL)
ffffffff81bfc181-ffffffff81bfc1a8: pcie_do_write_cmd.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void pcie_do_write_cmd(struct controller *ctrl, u16 cmd, u16 mask, bool wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (0)
Location: drivers/pci/hotplug/pciehp_hpc.c:154
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_disable_interrupt
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_enable_interrupt
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_set_indicators
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_set_raw_indicator_status
```
**Symbols:**

```
ffffffff81652510-ffffffff8165261b: pcie_do_write_cmd (STB_LOCAL)
ffffffff81bedff9-ffffffff81bee020: pcie_do_write_cmd.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void pcie_do_write_cmd(struct controller *ctrl, u16 cmd, u16 mask, bool wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (0)
Location: drivers/pci/hotplug/pciehp_hpc.c:154
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_disable_interrupt
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_enable_interrupt
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_set_indicators
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_set_raw_indicator_status
```
**Symbols:**

```
ffffffff816c4260-ffffffff816c436b: pcie_do_write_cmd (STB_LOCAL)
ffffffff81ce8de8-ffffffff81ce8e0f: pcie_do_write_cmd.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void pcie_do_write_cmd(struct controller *ctrl, u16 cmd, u16 mask, bool wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (0)
Location: drivers/pci/hotplug/pciehp_hpc.c:156
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_disable_interrupt
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_enable_interrupt
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_set_indicators
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_set_raw_indicator_status
```
**Symbols:**

```
ffffffff817e9ea0-ffffffff817e9fbe: pcie_do_write_cmd (STB_LOCAL)
ffffffff81eafe92-ffffffff81eafeb8: pcie_do_write_cmd.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void pcie_do_write_cmd(struct controller *ctrl, u16 cmd, u16 mask, bool wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff8190ff00)
Location: drivers/pci/hotplug/pciehp_hpc.c:156
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_disable_interrupt
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_enable_interrupt
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_set_indicators
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_set_raw_indicator_status
```
**Symbols:**

```
ffffffff8190ff00-ffffffff81910042: pcie_do_write_cmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void pcie_do_write_cmd(struct controller *ctrl, u16 cmd, u16 mask, bool wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff81953620)
Location: drivers/pci/hotplug/pciehp_hpc.c:156
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_disable_interrupt
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_enable_interrupt
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_set_indicators
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_set_raw_indicator_status
```
**Symbols:**

```
ffffffff81953620-ffffffff81953762: pcie_do_write_cmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void pcie_do_write_cmd(struct controller *ctrl, u16 cmd, u16 mask, bool wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff8199cab0)
Location: drivers/pci/hotplug/pciehp_hpc.c:157
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_disable_interrupt
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_enable_interrupt
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_set_indicators
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_set_raw_indicator_status
```
**Symbols:**

```
ffffffff8199cab0-ffffffff8199cbf2: pcie_do_write_cmd (STB_LOCAL)
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
void pcie_do_write_cmd(struct controller *ctrl, u16 cmd, u16 mask, bool wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffff80001070ba78)
Location: drivers/pci/hotplug/pciehp_hpc.c:137
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_disable_interrupt
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_enable_interrupt
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_set_indicators
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_set_raw_indicator_status
```
**Symbols:**

```
ffff80001070ba78-ffff80001070bbcc: pcie_do_write_cmd (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void pcie_do_write_cmd(struct controller *ctrl, u16 cmd, u16 mask, bool wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffe0004d859a)
Location: drivers/pci/hotplug/pciehp_hpc.c:137
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_disable_interrupt
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_enable_interrupt
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_set_indicators
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_set_raw_indicator_status
```
**Symbols:**

```
ffffffe0004d859a-ffffffe0004d86c6: pcie_do_write_cmd (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void pcie_do_write_cmd(struct controller *ctrl, u16 cmd, u16 mask, bool wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (0)
Location: drivers/pci/hotplug/pciehp_hpc.c:137
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_disable_interrupt
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_enable_interrupt
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_set_indicators
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_set_raw_indicator_status
```
**Symbols:**

```
ffffffff81596940-ffffffff81596a4b: pcie_do_write_cmd (STB_LOCAL)
ffffffff81597f3c-ffffffff81597f63: pcie_do_write_cmd.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void pcie_do_write_cmd(struct controller *ctrl, u16 cmd, u16 mask, bool wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (0)
Location: drivers/pci/hotplug/pciehp_hpc.c:137
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_disable_interrupt
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_enable_interrupt
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_set_indicators
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_set_raw_indicator_status
```
**Symbols:**

```
ffffffff81585ad0-ffffffff81585bdb: pcie_do_write_cmd (STB_LOCAL)
ffffffff815870cc-ffffffff815870f3: pcie_do_write_cmd.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void pcie_do_write_cmd(struct controller *ctrl, u16 cmd, u16 mask, bool wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (0)
Location: drivers/pci/hotplug/pciehp_hpc.c:137
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_disable_interrupt
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_enable_interrupt
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_set_indicators
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_set_raw_indicator_status
```
**Symbols:**

```
ffffffff81596e80-ffffffff81596f8b: pcie_do_write_cmd (STB_LOCAL)
ffffffff8159847c-ffffffff815984a3: pcie_do_write_cmd.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void pcie_do_write_cmd(struct controller *ctrl, u16 cmd, u16 mask, bool wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (0)
Location: drivers/pci/hotplug/pciehp_hpc.c:137
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_disable_interrupt
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_enable_interrupt
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_set_indicators
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_set_raw_indicator_status
```
**Symbols:**

```
ffffffff815b12c0-ffffffff815b13cb: pcie_do_write_cmd (STB_LOCAL)
ffffffff815b28c0-ffffffff815b28e7: pcie_do_write_cmd.cold (STB_LOCAL)
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
