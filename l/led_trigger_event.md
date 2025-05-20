# Function: <code>led_trigger_event</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void led_trigger_event(struct led_trigger *trig, enum led_brightness brightness);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/leds/led-triggers.c (ffffffff816ce440)
Location: drivers/leds/led-triggers.c:254
Inline: False
Direct callers:
  - drivers/tty/vt/keyboard.c:kbd_propagate_led_state
  - drivers/tty/vt/keyboard.c:kbd_led_trigger_activate
  - drivers/power/power_supply_leds.c:power_supply_update_leds
  - drivers/power/power_supply_leds.c:power_supply_update_leds
  - drivers/power/power_supply_leds.c:power_supply_update_leds
  - drivers/power/power_supply_leds.c:power_supply_update_leds
  - drivers/power/power_supply_leds.c:power_supply_update_leds
  - drivers/power/power_supply_leds.c:power_supply_update_leds
  - drivers/power/power_supply_leds.c:power_supply_update_leds
  - drivers/power/power_supply_leds.c:power_supply_update_leds
  - drivers/power/power_supply_leds.c:power_supply_update_leds
  - drivers/power/power_supply_leds.c:power_supply_update_leds
  - drivers/power/power_supply_leds.c:power_supply_update_leds
  - drivers/power/power_supply_leds.c:power_supply_update_leds
  - drivers/power/power_supply_leds.c:power_supply_update_leds
  - drivers/mmc/core/core.c:mmc_request_done
  - drivers/mmc/core/core.c:mmc_start_request
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu
```
**Symbols:**

```
ffffffff816ce440-ffffffff816ce4ab: led_trigger_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void led_trigger_event(struct led_trigger *trig, enum led_brightness brightness);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/leds/led-triggers.c (ffffffff81731510)
Location: drivers/leds/led-triggers.c:275
Inline: False
Direct callers:
  - drivers/tty/vt/keyboard.c:kbd_propagate_led_state
  - drivers/tty/vt/keyboard.c:kbd_led_trigger_activate
  - drivers/power/power_supply_leds.c:power_supply_update_leds
  - drivers/power/power_supply_leds.c:power_supply_update_leds
  - drivers/power/power_supply_leds.c:power_supply_update_leds
  - drivers/power/power_supply_leds.c:power_supply_update_leds
  - drivers/power/power_supply_leds.c:power_supply_update_leds
  - drivers/power/power_supply_leds.c:power_supply_update_leds
  - drivers/power/power_supply_leds.c:power_supply_update_leds
  - drivers/power/power_supply_leds.c:power_supply_update_leds
  - drivers/power/power_supply_leds.c:power_supply_update_leds
  - drivers/power/power_supply_leds.c:power_supply_update_leds
  - drivers/power/power_supply_leds.c:power_supply_update_leds
  - drivers/power/power_supply_leds.c:power_supply_update_leds
  - drivers/power/power_supply_leds.c:power_supply_update_leds
  - drivers/mmc/core/core.c:mmc_start_request
  - drivers/mmc/core/core.c:mmc_request_done
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu
  - drivers/leds/trigger/ledtrig-panic.c:led_panic_blink
```
**Symbols:**

```
ffffffff81731510-ffffffff8173157b: led_trigger_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void led_trigger_event(struct led_trigger *trig, enum led_brightness brightness);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/leds/led-triggers.c (ffffffff817644b0)
Location: drivers/leds/led-triggers.c:282
Inline: False
Direct callers:
  - drivers/tty/vt/keyboard.c:kbd_propagate_led_state
  - drivers/tty/vt/keyboard.c:kbd_led_trigger_activate
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/mmc/core/core.c:mmc_start_request
  - drivers/mmc/core/core.c:mmc_request_done
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu
  - drivers/leds/trigger/ledtrig-panic.c:led_panic_blink
```
**Symbols:**

```
ffffffff817644b0-ffffffff8176451b: led_trigger_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void led_trigger_event(struct led_trigger *trig, enum led_brightness brightness);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/leds/led-triggers.c (ffffffff81783380)
Location: drivers/leds/led-triggers.c:282
Inline: True
Direct callers:
  - drivers/tty/vt/keyboard.c:kbd_propagate_led_state
  - drivers/tty/vt/keyboard.c:kbd_led_trigger_activate
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/mmc/core/core.c:mmc_request_done
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu
  - drivers/leds/trigger/ledtrig-panic.c:led_panic_blink
  - net/rfkill/core.c:rfkill_any_led_trigger_worker
```
**Symbols:**

```
ffffffff81783380-ffffffff817833ef: led_trigger_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void led_trigger_event(struct led_trigger *trig, enum led_brightness brightness);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/leds/led-triggers.c (ffffffff817f9740)
Location: drivers/leds/led-triggers.c:282
Inline: True
Direct callers:
  - drivers/tty/vt/keyboard.c:kbd_propagate_led_state
  - drivers/tty/vt/keyboard.c:kbd_led_trigger_activate
  - drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed
  - drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed
  - drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed
  - drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed
  - drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/mmc/core/core.c:mmc_start_request
  - drivers/mmc/core/core.c:mmc_request_done
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu
  - drivers/leds/trigger/ledtrig-panic.c:led_panic_blink
  - net/rfkill/core.c:rfkill_any_led_trigger_worker
```
**Symbols:**

```
ffffffff817f9740-ffffffff817f97af: led_trigger_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void led_trigger_event(struct led_trigger *trig, enum led_brightness brightness);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/leds/led-triggers.c (ffffffff81842d50)
Location: drivers/leds/led-triggers.c:282
Inline: True
Direct callers:
  - drivers/tty/vt/keyboard.c:kbd_propagate_led_state
  - drivers/tty/vt/keyboard.c:kbd_led_trigger_activate
  - drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed
  - drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed
  - drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed
  - drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed
  - drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/mmc/core/core.c:mmc_start_request
  - drivers/mmc/core/core.c:mmc_request_done
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu
  - drivers/leds/trigger/ledtrig-panic.c:led_panic_blink
  - net/rfkill/core.c:rfkill_global_led_trigger_worker
  - net/rfkill/core.c:rfkill_global_led_trigger_worker
  - net/rfkill/core.c:rfkill_global_led_trigger_worker
  - net/rfkill/core.c:rfkill_global_led_trigger_worker
```
**Symbols:**

```
ffffffff81842d50-ffffffff81842dbb: led_trigger_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void led_trigger_event(struct led_trigger *trig, enum led_brightness brightness);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/leds/led-triggers.c (ffffffff8186eaf0)
Location: drivers/leds/led-triggers.c:320
Inline: True
Direct callers:
  - drivers/tty/vt/keyboard.c:kbd_propagate_led_state
  - drivers/tty/vt/keyboard.c:kbd_led_trigger_activate
  - drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed
  - drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed
  - drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed
  - drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed
  - drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/mmc/core/core.c:mmc_start_request
  - drivers/mmc/core/core.c:mmc_request_done
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu
  - drivers/leds/trigger/ledtrig-panic.c:led_panic_blink
  - net/rfkill/core.c:rfkill_global_led_trigger_worker
  - net/rfkill/core.c:rfkill_global_led_trigger_worker
  - net/rfkill/core.c:rfkill_global_led_trigger_worker
  - net/rfkill/core.c:rfkill_global_led_trigger_worker
```
**Symbols:**

```
ffffffff8186eaf0-ffffffff8186eb5b: led_trigger_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void led_trigger_event(struct led_trigger *trig, enum led_brightness brightness);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/leds/led-triggers.c (ffffffff818b2da0)
Location: drivers/leds/led-triggers.c:316
Inline: True
Direct callers:
  - drivers/tty/vt/keyboard.c:kbd_propagate_led_state
  - drivers/tty/vt/keyboard.c:kbd_led_trigger_activate
  - drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed
  - drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed
  - drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed
  - drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed
  - drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed
  - drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed
  - drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/mmc/core/core.c:mmc_start_request
  - drivers/mmc/core/core.c:mmc_request_done
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu
  - drivers/leds/trigger/ledtrig-panic.c:led_panic_blink
  - net/rfkill/core.c:rfkill_global_led_trigger_worker
  - net/rfkill/core.c:rfkill_global_led_trigger_worker
  - net/rfkill/core.c:rfkill_global_led_trigger_worker
  - net/rfkill/core.c:rfkill_global_led_trigger_worker
```
**Symbols:**

```
ffffffff818b2da0-ffffffff818b2e0b: led_trigger_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void led_trigger_event(struct led_trigger *trig, enum led_brightness brightness);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/leds/led-triggers.c (ffffffff818e56c0)
Location: drivers/leds/led-triggers.c:317
Inline: True
Direct callers:
  - drivers/tty/vt/keyboard.c:kbd_propagate_led_state
  - drivers/tty/vt/keyboard.c:kbd_led_trigger_activate
  - drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed
  - drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed
  - drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed
  - drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed
  - drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed
  - drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed
  - drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/mmc/core/core.c:mmc_start_request
  - drivers/mmc/core/core.c:mmc_request_done
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu
  - drivers/leds/trigger/ledtrig-panic.c:led_panic_blink
  - net/rfkill/core.c:rfkill_global_led_trigger_worker
  - net/rfkill/core.c:rfkill_global_led_trigger_worker
  - net/rfkill/core.c:rfkill_global_led_trigger_worker
  - net/rfkill/core.c:rfkill_global_led_trigger_worker
```
**Symbols:**

```
ffffffff818e56c0-ffffffff818e572b: led_trigger_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void led_trigger_event(struct led_trigger *trig, enum led_brightness brightness);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/leds/led-triggers.c (ffffffff819b8bd0)
Location: drivers/leds/led-triggers.c:363
Inline: True
Direct callers:
  - drivers/tty/vt/keyboard.c:kbd_start
  - drivers/tty/vt/keyboard.c:kbd_bh
  - drivers/tty/vt/keyboard.c:kbd_led_trigger_activate
  - drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed
  - drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed
  - drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed
  - drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed
  - drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed
  - drivers/power/supply/power_supply_leds.c:power_supply_update_gen_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_gen_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds
  - drivers/mmc/core/core.c:mmc_start_request
  - drivers/mmc/core/core.c:mmc_request_done
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu
  - drivers/leds/trigger/ledtrig-panic.c:led_panic_blink
  - net/rfkill/core.c:rfkill_set_states
  - net/rfkill/core.c:rfkill_set_states
  - net/rfkill/core.c:rfkill_set_sw_state
  - net/rfkill/core.c:rfkill_set_sw_state
  - net/rfkill/core.c:rfkill_set_hw_state
  - net/rfkill/core.c:rfkill_set_hw_state
  - net/rfkill/core.c:rfkill_set_block
  - net/rfkill/core.c:rfkill_set_block
  - net/rfkill/core.c:rfkill_global_led_trigger_worker
  - net/rfkill/core.c:rfkill_global_led_trigger_worker
  - net/rfkill/core.c:rfkill_global_led_trigger_worker
  - net/rfkill/core.c:rfkill_global_led_trigger_worker
  - net/rfkill/core.c:rfkill_led_trigger_activate
  - net/rfkill/core.c:rfkill_led_trigger_activate
```
**Symbols:**

```
ffffffff819b8bd0-ffffffff819b8c3b: led_trigger_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void led_trigger_event(struct led_trigger *trig, enum led_brightness brightness);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/leds/led-triggers.c (ffffffff819bae70)
Location: drivers/leds/led-triggers.c:377
Inline: True
Direct callers:
  - drivers/tty/vt/keyboard.c:kbd_start
  - drivers/tty/vt/keyboard.c:kbd_bh
  - drivers/tty/vt/keyboard.c:kbd_led_trigger_activate
  - drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed
  - drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed
  - drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed
  - drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed
  - drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed
  - drivers/power/supply/power_supply_leds.c:power_supply_update_gen_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_gen_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds
  - drivers/mmc/core/core.c:mmc_start_request
  - drivers/mmc/core/core.c:mmc_request_done
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu
  - drivers/leds/trigger/ledtrig-panic.c:led_panic_blink
  - net/rfkill/core.c:rfkill_set_states
  - net/rfkill/core.c:rfkill_set_states
  - net/rfkill/core.c:rfkill_set_sw_state
  - net/rfkill/core.c:rfkill_set_sw_state
  - net/rfkill/core.c:rfkill_set_hw_state_reason
  - net/rfkill/core.c:rfkill_set_hw_state_reason
  - net/rfkill/core.c:rfkill_set_block
  - net/rfkill/core.c:rfkill_set_block
  - net/rfkill/core.c:rfkill_global_led_trigger_worker
  - net/rfkill/core.c:rfkill_global_led_trigger_worker
  - net/rfkill/core.c:rfkill_global_led_trigger_worker
  - net/rfkill/core.c:rfkill_global_led_trigger_worker
  - net/rfkill/core.c:rfkill_led_trigger_activate
  - net/rfkill/core.c:rfkill_led_trigger_activate
```
**Symbols:**

```
ffffffff819bae70-ffffffff819baee5: led_trigger_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void led_trigger_event(struct led_trigger *trig, enum led_brightness brightness);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/leds/led-triggers.c (ffffffff8199f690)
Location: drivers/leds/led-triggers.c:377
Inline: True
Direct callers:
  - drivers/tty/vt/keyboard.c:kbd_start
  - drivers/tty/vt/keyboard.c:kbd_bh
  - drivers/tty/vt/keyboard.c:kbd_led_trigger_activate
  - drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed
  - drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed
  - drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed
  - drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed
  - drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds
  - drivers/mmc/core/core.c:mmc_start_request
  - drivers/mmc/core/core.c:mmc_request_done
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu
  - drivers/leds/trigger/ledtrig-panic.c:led_panic_blink
  - net/rfkill/core.c:rfkill_set_states
  - net/rfkill/core.c:rfkill_set_states
  - net/rfkill/core.c:rfkill_set_sw_state
  - net/rfkill/core.c:rfkill_set_sw_state
  - net/rfkill/core.c:rfkill_set_hw_state_reason
  - net/rfkill/core.c:rfkill_set_hw_state_reason
  - net/rfkill/core.c:rfkill_set_block
  - net/rfkill/core.c:rfkill_set_block
  - net/rfkill/core.c:rfkill_global_led_trigger_worker
  - net/rfkill/core.c:rfkill_global_led_trigger_worker
  - net/rfkill/core.c:rfkill_global_led_trigger_worker
  - net/rfkill/core.c:rfkill_global_led_trigger_worker
  - net/rfkill/core.c:rfkill_led_trigger_activate
  - net/rfkill/core.c:rfkill_led_trigger_activate
```
**Symbols:**

```
ffffffff8199f690-ffffffff8199f705: led_trigger_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void led_trigger_event(struct led_trigger *trig, enum led_brightness brightness);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/leds/led-triggers.c (ffffffff81a4c330)
Location: drivers/leds/led-triggers.c:377
Inline: True
Direct callers:
  - drivers/tty/vt/keyboard.c:kbd_start
  - drivers/tty/vt/keyboard.c:kbd_bh
  - drivers/tty/vt/keyboard.c:kbd_led_trigger_activate
  - drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed
  - drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed
  - drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed
  - drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed
  - drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds
  - drivers/mmc/core/core.c:mmc_start_request
  - drivers/mmc/core/core.c:mmc_request_done
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu
  - drivers/leds/trigger/ledtrig-panic.c:led_panic_blink
  - net/rfkill/core.c:rfkill_global_led_trigger_worker
  - net/rfkill/core.c:rfkill_global_led_trigger_worker
  - net/rfkill/core.c:rfkill_global_led_trigger_worker
  - net/rfkill/core.c:rfkill_global_led_trigger_worker
  - net/rfkill/core.c:rfkill_led_trigger_activate
  - net/rfkill/core.c:rfkill_led_trigger_activate
```
**Symbols:**

```
ffffffff81a4c330-ffffffff81a4c3a5: led_trigger_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void led_trigger_event(struct led_trigger *trig, enum led_brightness brightness);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/leds/led-triggers.c (ffffffff81bbab80)
Location: drivers/leds/led-triggers.c:380
Inline: True
Direct callers:
  - drivers/tty/vt/keyboard.c:kbd_start
  - drivers/tty/vt/keyboard.c:kbd_bh
  - drivers/tty/vt/keyboard.c:kbd_led_trigger_activate
  - drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed
  - drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed
  - drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed
  - drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed
  - drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds
  - drivers/mmc/core/core.c:mmc_start_request
  - drivers/mmc/core/core.c:mmc_request_done
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu
  - drivers/leds/trigger/ledtrig-panic.c:led_panic_blink
  - net/rfkill/core.c:rfkill_global_led_trigger_worker
  - net/rfkill/core.c:rfkill_global_led_trigger_worker
  - net/rfkill/core.c:rfkill_global_led_trigger_worker
  - net/rfkill/core.c:rfkill_global_led_trigger_worker
  - net/rfkill/core.c:rfkill_led_trigger_activate
  - net/rfkill/core.c:rfkill_led_trigger_activate
```
**Symbols:**

```
ffffffff81bbab80-ffffffff81bbabf1: led_trigger_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void led_trigger_event(struct led_trigger *trig, enum led_brightness brightness);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/leds/led-triggers.c (ffffffff81d60180)
Location: drivers/leds/led-triggers.c:380
Inline: True
Direct callers:
  - drivers/tty/vt/keyboard.c:kbd_start
  - drivers/tty/vt/keyboard.c:kbd_bh
  - drivers/tty/vt/keyboard.c:kbd_led_trigger_activate
  - drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed
  - drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed
  - drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed
  - drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed
  - drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds
  - drivers/mmc/core/core.c:mmc_start_request
  - drivers/mmc/core/core.c:mmc_request_done
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu
  - drivers/leds/trigger/ledtrig-panic.c:led_panic_blink
  - net/rfkill/core.c:rfkill_global_led_trigger_worker
  - net/rfkill/core.c:rfkill_global_led_trigger_worker
  - net/rfkill/core.c:rfkill_global_led_trigger_worker
  - net/rfkill/core.c:rfkill_global_led_trigger_worker
  - net/rfkill/core.c:rfkill_led_trigger_activate
  - net/rfkill/core.c:rfkill_led_trigger_activate
```
**Symbols:**

```
ffffffff81d60180-ffffffff81d601f1: led_trigger_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void led_trigger_event(struct led_trigger *trig, enum led_brightness brightness);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/leds/led-triggers.c (ffffffff81dcb310)
Location: drivers/leds/led-triggers.c:381
Inline: True
Direct callers:
  - drivers/tty/vt/keyboard.c:kbd_start
  - drivers/tty/vt/keyboard.c:kbd_bh
  - drivers/tty/vt/keyboard.c:kbd_led_trigger_activate
  - drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed
  - drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed
  - drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed
  - drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed
  - drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds
  - drivers/mmc/core/core.c:mmc_start_request
  - drivers/mmc/core/core.c:mmc_request_done
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu
  - drivers/leds/trigger/ledtrig-panic.c:led_panic_blink
  - net/rfkill/core.c:rfkill_global_led_trigger_worker
  - net/rfkill/core.c:rfkill_global_led_trigger_worker
  - net/rfkill/core.c:rfkill_global_led_trigger_worker
  - net/rfkill/core.c:rfkill_global_led_trigger_worker
  - net/rfkill/core.c:rfkill_led_trigger_activate
  - net/rfkill/core.c:rfkill_led_trigger_activate
```
**Symbols:**

```
ffffffff81dcb310-ffffffff81dcb381: led_trigger_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void led_trigger_event(struct led_trigger *trig, enum led_brightness brightness);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/leds/led-triggers.c (ffffffff81e83d90)
Location: drivers/leds/led-triggers.c:368
Inline: True
Direct callers:
  - drivers/tty/vt/keyboard.c:kbd_start
  - drivers/tty/vt/keyboard.c:kbd_bh
  - drivers/tty/vt/keyboard.c:kbd_led_trigger_activate
  - drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed
  - drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed
  - drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed
  - drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed
  - drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds
  - drivers/mmc/core/core.c:mmc_start_request
  - drivers/mmc/core/core.c:mmc_request_done
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu
  - drivers/leds/trigger/ledtrig-panic.c:led_panic_blink
  - net/rfkill/core.c:rfkill_global_led_trigger_worker
  - net/rfkill/core.c:rfkill_global_led_trigger_worker
  - net/rfkill/core.c:rfkill_global_led_trigger_worker
  - net/rfkill/core.c:rfkill_global_led_trigger_worker
  - net/rfkill/core.c:rfkill_led_trigger_activate
  - net/rfkill/core.c:rfkill_led_trigger_activate
```
**Symbols:**

```
ffffffff81e83d90-ffffffff81e83e01: led_trigger_event (STB_GLOBAL)
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
void led_trigger_event(struct led_trigger *trig, enum led_brightness brightness);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/leds/led-triggers.c (ffff800010b49fc8)
Location: drivers/leds/led-triggers.c:317
Inline: True
Direct callers:
  - drivers/tty/vt/keyboard.c:kbd_propagate_led_state
  - drivers/tty/vt/keyboard.c:kbd_led_trigger_activate
  - drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed
  - drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed
  - drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed
  - drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed
  - drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/mmc/core/core.c:mmc_start_request
  - drivers/mmc/core/core.c:mmc_request_done
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu
  - drivers/leds/trigger/ledtrig-panic.c:led_panic_blink
  - net/rfkill/core.c:rfkill_global_led_trigger_worker
  - net/rfkill/core.c:rfkill_global_led_trigger_worker
  - net/rfkill/core.c:rfkill_global_led_trigger_worker
  - net/rfkill/core.c:rfkill_global_led_trigger_worker
```
**Symbols:**

```
ffff800010b49fc8-ffff800010b4a09c: led_trigger_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void led_trigger_event(struct led_trigger *trig, enum led_brightness brightness);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/leds/led-triggers.c (c0c33c18)
Location: drivers/leds/led-triggers.c:317
Inline: True
Direct callers:
  - drivers/tty/vt/keyboard.c:kbd_propagate_led_state
  - drivers/tty/vt/keyboard.c:kbd_led_trigger_activate
  - drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed
  - drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed
  - drivers/net/phy/phy_led_triggers.c:phy_led_trigger_no_link
  - drivers/net/phy/phy_led_triggers.c:phy_led_trigger_no_link
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/mmc/core/core.c:mmc_request_done
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu
  - drivers/leds/trigger/ledtrig-panic.c:led_panic_blink
  - net/rfkill/core.c:rfkill_global_led_trigger_worker
  - net/rfkill/core.c:rfkill_global_led_trigger_worker
  - net/rfkill/core.c:rfkill_global_led_trigger_worker
```
**Symbols:**

```
c0c33c18-c0c33ca0: led_trigger_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void led_trigger_event(struct led_trigger *trig, enum led_brightness brightness);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/leds/led-triggers.c (c000000000c3f200)
Location: drivers/leds/led-triggers.c:317
Inline: True
Direct callers:
  - drivers/tty/vt/keyboard.c:kbd_propagate_led_state
  - drivers/tty/vt/keyboard.c:kbd_led_trigger_activate
  - drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed
  - drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed
  - drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed
  - drivers/net/phy/phy_led_triggers.c:phy_led_trigger_no_link
  - drivers/net/phy/phy_led_triggers.c:phy_led_trigger_no_link
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/mmc/core/core.c:mmc_start_request
  - drivers/mmc/core/core.c:mmc_request_done
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu
  - drivers/leds/trigger/ledtrig-panic.c:led_panic_blink
  - net/rfkill/core.c:rfkill_global_led_trigger_worker
  - net/rfkill/core.c:rfkill_global_led_trigger_worker
  - net/rfkill/core.c:rfkill_global_led_trigger_worker
  - net/rfkill/core.c:rfkill_global_led_trigger_worker
```
**Symbols:**

```
c000000000c3f200-c000000000c3f2b4: led_trigger_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void led_trigger_event(struct led_trigger *trig, enum led_brightness brightness);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/leds/led-triggers.c (ffffffe00071d948)
Location: drivers/leds/led-triggers.c:317
Inline: True
Direct callers:
  - drivers/tty/vt/keyboard.c:kbd_propagate_led_state
  - drivers/tty/vt/keyboard.c:kbd_led_trigger_activate
  - drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed
  - drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed
  - drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed
  - drivers/net/phy/phy_led_triggers.c:phy_led_trigger_no_link
  - drivers/net/phy/phy_led_triggers.c:phy_led_trigger_no_link
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/mmc/core/core.c:mmc_start_request
  - drivers/mmc/core/core.c:mmc_request_done
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu
  - drivers/leds/trigger/ledtrig-panic.c:led_panic_blink
  - net/rfkill/core.c:rfkill_global_led_trigger_worker
  - net/rfkill/core.c:rfkill_global_led_trigger_worker
  - net/rfkill/core.c:rfkill_global_led_trigger_worker
  - net/rfkill/core.c:rfkill_global_led_trigger_worker
```
**Symbols:**

```
ffffffe00071d948-ffffffe00071d9bc: led_trigger_event (STB_GLOBAL)
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
void led_trigger_event(struct led_trigger *trig, enum led_brightness brightness);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/leds/led-triggers.c (ffffffff81888850)
Location: drivers/leds/led-triggers.c:317
Inline: True
Direct callers:
  - drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed
  - drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed
  - drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed
  - drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed
  - drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed
  - drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed
  - drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/mmc/core/core.c:mmc_start_request
  - drivers/mmc/core/core.c:mmc_request_done
  - net/rfkill/core.c:rfkill_global_led_trigger_worker
  - net/rfkill/core.c:rfkill_global_led_trigger_worker
  - net/rfkill/core.c:rfkill_global_led_trigger_worker
  - net/rfkill/core.c:rfkill_global_led_trigger_worker
```
**Symbols:**

```
ffffffff81888850-ffffffff818888bb: led_trigger_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void led_trigger_event(struct led_trigger *trig, enum led_brightness brightness);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/leds/led-triggers.c (ffffffff818401d0)
Location: drivers/leds/led-triggers.c:317
Inline: True
Direct callers:
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - net/rfkill/core.c:rfkill_global_led_trigger_worker
  - net/rfkill/core.c:rfkill_global_led_trigger_worker
  - net/rfkill/core.c:rfkill_global_led_trigger_worker
  - net/rfkill/core.c:rfkill_global_led_trigger_worker
```
**Symbols:**

```
ffffffff818401d0-ffffffff8184023b: led_trigger_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void led_trigger_event(struct led_trigger *trig, enum led_brightness brightness);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/leds/led-triggers.c (ffffffff818da520)
Location: drivers/leds/led-triggers.c:317
Inline: True
Direct callers:
  - drivers/tty/vt/keyboard.c:kbd_propagate_led_state
  - drivers/tty/vt/keyboard.c:kbd_led_trigger_activate
  - drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed
  - drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed
  - drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed
  - drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed
  - drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed
  - drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed
  - drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/mmc/core/core.c:mmc_start_request
  - drivers/mmc/core/core.c:mmc_request_done
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu
  - drivers/leds/trigger/ledtrig-panic.c:led_panic_blink
  - net/rfkill/core.c:rfkill_global_led_trigger_worker
  - net/rfkill/core.c:rfkill_global_led_trigger_worker
  - net/rfkill/core.c:rfkill_global_led_trigger_worker
  - net/rfkill/core.c:rfkill_global_led_trigger_worker
```
**Symbols:**

```
ffffffff818da520-ffffffff818da58b: led_trigger_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void led_trigger_event(struct led_trigger *trig, enum led_brightness brightness);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/leds/led-triggers.c (ffffffff818f7040)
Location: drivers/leds/led-triggers.c:317
Inline: True
Direct callers:
  - drivers/tty/vt/keyboard.c:kbd_propagate_led_state
  - drivers/tty/vt/keyboard.c:kbd_led_trigger_activate
  - drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed
  - drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed
  - drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed
  - drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed
  - drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed
  - drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed
  - drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/power/supply/power_supply_leds.c:power_supply_update_leds
  - drivers/mmc/core/core.c:mmc_start_request
  - drivers/mmc/core/core.c:mmc_request_done
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu
  - drivers/leds/trigger/ledtrig-panic.c:led_panic_blink
  - net/rfkill/core.c:rfkill_global_led_trigger_worker
  - net/rfkill/core.c:rfkill_global_led_trigger_worker
  - net/rfkill/core.c:rfkill_global_led_trigger_worker
  - net/rfkill/core.c:rfkill_global_led_trigger_worker
```
**Symbols:**

```
ffffffff818f7040-ffffffff818f70ab: led_trigger_event (STB_GLOBAL)
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
