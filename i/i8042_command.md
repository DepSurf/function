# Function: <code>i8042_command</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int i8042_command(unsigned char *param, int command);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/i8042.c (ffffffff816652f0)
Location: drivers/input/serio/i8042.c:311
Inline: False
Direct callers:
  - drivers/input/serio/i8042.c:i8042_dritek_enable
  - drivers/input/serio/i8042.c:i8042_enable_mux_ports
  - drivers/input/serio/i8042.c:i8042_enable_mux_ports
  - drivers/input/serio/i8042.c:i8042_aux_write
  - drivers/input/serio/i8042.c:i8042_aux_write
  - drivers/input/serio/i8042.c:i8042_set_mux_mode
  - drivers/input/serio/i8042.c:i8042_set_mux_mode
  - drivers/input/serio/i8042.c:i8042_set_mux_mode
  - drivers/input/serio/i8042.c:i8042_toggle_aux
  - drivers/input/serio/i8042.c:i8042_toggle_aux
  - drivers/input/serio/i8042.c:i8042_port_close
  - drivers/input/serio/i8042.c:i8042_port_close
  - drivers/input/serio/i8042.c:i8042_controller_selftest
  - drivers/input/serio/i8042.c:i8042_controller_reset
  - drivers/input/serio/i8042.c:i8042_controller_reset
```
**Symbols:**

```
ffffffff816652f0-ffffffff81665360: i8042_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int i8042_command(unsigned char *param, int command);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/i8042.c (ffffffff816c5550)
Location: drivers/input/serio/i8042.c:311
Inline: False
Direct callers:
  - drivers/input/serio/i8042.c:i8042_dritek_enable
  - drivers/input/serio/i8042.c:i8042_controller_reset
  - drivers/input/serio/i8042.c:i8042_controller_reset
  - drivers/input/serio/i8042.c:i8042_controller_selftest
  - drivers/input/serio/i8042.c:i8042_toggle_aux
  - drivers/input/serio/i8042.c:i8042_toggle_aux
  - drivers/input/serio/i8042.c:i8042_set_mux_mode
  - drivers/input/serio/i8042.c:i8042_set_mux_mode
  - drivers/input/serio/i8042.c:i8042_set_mux_mode
  - drivers/input/serio/i8042.c:i8042_enable_mux_ports
  - drivers/input/serio/i8042.c:i8042_enable_mux_ports
  - drivers/input/serio/i8042.c:i8042_port_close
  - drivers/input/serio/i8042.c:i8042_port_close
  - drivers/input/serio/i8042.c:i8042_aux_write
```
**Symbols:**

```
ffffffff816c5550-ffffffff816c55c0: i8042_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int i8042_command(unsigned char *param, int command);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/i8042.c (ffffffff816f3570)
Location: drivers/input/serio/i8042.c:341
Inline: False
Direct callers:
  - drivers/input/serio/i8042.c:i8042_dritek_enable
  - drivers/input/serio/i8042.c:i8042_controller_reset
  - drivers/input/serio/i8042.c:i8042_controller_reset
  - drivers/input/serio/i8042.c:i8042_controller_selftest
  - drivers/input/serio/i8042.c:i8042_toggle_aux
  - drivers/input/serio/i8042.c:i8042_toggle_aux
  - drivers/input/serio/i8042.c:i8042_set_mux_mode
  - drivers/input/serio/i8042.c:i8042_set_mux_mode
  - drivers/input/serio/i8042.c:i8042_set_mux_mode
  - drivers/input/serio/i8042.c:i8042_enable_mux_ports
  - drivers/input/serio/i8042.c:i8042_enable_mux_ports
  - drivers/input/serio/i8042.c:i8042_port_close
  - drivers/input/serio/i8042.c:i8042_port_close
  - drivers/input/serio/i8042.c:i8042_aux_write
```
**Symbols:**

```
ffffffff816f3570-ffffffff816f35e0: i8042_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int i8042_command(unsigned char *param, int command);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/i8042.c (ffffffff81708f10)
Location: drivers/input/serio/i8042.c:343
Inline: False
Direct callers:
  - drivers/input/serio/i8042.c:i8042_controller_resume
  - drivers/input/serio/i8042.c:i8042_controller_resume
  - drivers/input/serio/i8042.c:i8042_dritek_enable
  - drivers/input/serio/i8042.c:i8042_controller_reset
  - drivers/input/serio/i8042.c:i8042_controller_reset
  - drivers/input/serio/i8042.c:i8042_controller_selftest
  - drivers/input/serio/i8042.c:i8042_toggle_aux
  - drivers/input/serio/i8042.c:i8042_toggle_aux
  - drivers/input/serio/i8042.c:i8042_set_mux_mode
  - drivers/input/serio/i8042.c:i8042_set_mux_mode
  - drivers/input/serio/i8042.c:i8042_set_mux_mode
  - drivers/input/serio/i8042.c:i8042_enable_mux_ports
  - drivers/input/serio/i8042.c:i8042_enable_mux_ports
  - drivers/input/serio/i8042.c:i8042_port_close
  - drivers/input/serio/i8042.c:i8042_port_close
  - drivers/input/serio/i8042.c:i8042_aux_write
  - drivers/input/serio/i8042.c:i8042_aux_write
```
**Symbols:**

```
ffffffff81708f10-ffffffff81708f80: i8042_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int i8042_command(unsigned char *param, int command);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/i8042.c (ffffffff8177a0c0)
Location: drivers/input/serio/i8042.c:343
Inline: False
Direct callers:
  - drivers/input/serio/i8042.c:i8042_controller_resume
  - drivers/input/serio/i8042.c:i8042_controller_resume
  - drivers/input/serio/i8042.c:i8042_dritek_enable
  - drivers/input/serio/i8042.c:i8042_controller_reset
  - drivers/input/serio/i8042.c:i8042_controller_reset
  - drivers/input/serio/i8042.c:i8042_controller_selftest
  - drivers/input/serio/i8042.c:i8042_toggle_aux
  - drivers/input/serio/i8042.c:i8042_toggle_aux
  - drivers/input/serio/i8042.c:i8042_set_mux_mode
  - drivers/input/serio/i8042.c:i8042_set_mux_mode
  - drivers/input/serio/i8042.c:i8042_set_mux_mode
  - drivers/input/serio/i8042.c:i8042_enable_mux_ports
  - drivers/input/serio/i8042.c:i8042_enable_mux_ports
  - drivers/input/serio/i8042.c:i8042_port_close
  - drivers/input/serio/i8042.c:i8042_port_close
  - drivers/input/serio/i8042.c:i8042_aux_write
  - drivers/input/serio/i8042.c:i8042_aux_write
```
**Symbols:**

```
ffffffff8177a0c0-ffffffff8177a130: i8042_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int i8042_command(unsigned char *param, int command);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/i8042.c (ffffffff817baa70)
Location: drivers/input/serio/i8042.c:343
Inline: False
Direct callers:
  - drivers/input/serio/i8042.c:i8042_init
  - drivers/input/serio/i8042.c:i8042_init
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_controller_resume
  - drivers/input/serio/i8042.c:i8042_controller_resume
  - drivers/input/serio/i8042.c:i8042_dritek_enable
  - drivers/input/serio/i8042.c:i8042_controller_reset
  - drivers/input/serio/i8042.c:i8042_controller_reset
  - drivers/input/serio/i8042.c:i8042_controller_selftest
  - drivers/input/serio/i8042.c:i8042_toggle_aux
  - drivers/input/serio/i8042.c:i8042_toggle_aux
  - drivers/input/serio/i8042.c:i8042_set_mux_mode
  - drivers/input/serio/i8042.c:i8042_set_mux_mode
  - drivers/input/serio/i8042.c:i8042_set_mux_mode
  - drivers/input/serio/i8042.c:i8042_enable_mux_ports
  - drivers/input/serio/i8042.c:i8042_enable_mux_ports
  - drivers/input/serio/i8042.c:i8042_port_close
  - drivers/input/serio/i8042.c:i8042_port_close
  - drivers/input/serio/i8042.c:i8042_aux_write
```
**Symbols:**

```
ffffffff817baa70-ffffffff817baab8: i8042_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int i8042_command(unsigned char *param, int command);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/i8042.c (ffffffff817e1ee0)
Location: drivers/input/serio/i8042.c:343
Inline: False
Direct callers:
  - drivers/input/serio/i8042.c:i8042_init
  - drivers/input/serio/i8042.c:i8042_init
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_controller_resume
  - drivers/input/serio/i8042.c:i8042_controller_resume
  - drivers/input/serio/i8042.c:i8042_dritek_enable
  - drivers/input/serio/i8042.c:i8042_controller_reset
  - drivers/input/serio/i8042.c:i8042_controller_reset
  - drivers/input/serio/i8042.c:i8042_controller_selftest
  - drivers/input/serio/i8042.c:i8042_toggle_aux
  - drivers/input/serio/i8042.c:i8042_toggle_aux
  - drivers/input/serio/i8042.c:i8042_set_mux_mode
  - drivers/input/serio/i8042.c:i8042_set_mux_mode
  - drivers/input/serio/i8042.c:i8042_set_mux_mode
  - drivers/input/serio/i8042.c:i8042_enable_mux_ports
  - drivers/input/serio/i8042.c:i8042_enable_mux_ports
  - drivers/input/serio/i8042.c:i8042_port_close
  - drivers/input/serio/i8042.c:i8042_port_close
  - drivers/input/serio/i8042.c:i8042_aux_write
```
**Symbols:**

```
ffffffff817e1ee0-ffffffff817e1f28: i8042_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int i8042_command(unsigned char *param, int command);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/i8042.c (ffffffff81822860)
Location: drivers/input/serio/i8042.c:339
Inline: False
Direct callers:
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_controller_resume
  - drivers/input/serio/i8042.c:i8042_controller_resume
  - drivers/input/serio/i8042.c:i8042_dritek_enable
  - drivers/input/serio/i8042.c:i8042_controller_reset
  - drivers/input/serio/i8042.c:i8042_controller_reset
  - drivers/input/serio/i8042.c:i8042_controller_selftest
  - drivers/input/serio/i8042.c:i8042_toggle_aux
  - drivers/input/serio/i8042.c:i8042_toggle_aux
  - drivers/input/serio/i8042.c:i8042_set_mux_mode
  - drivers/input/serio/i8042.c:i8042_set_mux_mode
  - drivers/input/serio/i8042.c:i8042_set_mux_mode
  - drivers/input/serio/i8042.c:i8042_enable_mux_ports
  - drivers/input/serio/i8042.c:i8042_enable_mux_ports
  - drivers/input/serio/i8042.c:i8042_port_close
  - drivers/input/serio/i8042.c:i8042_port_close
  - drivers/input/serio/i8042.c:i8042_aux_write
  - drivers/input/serio/i8042.c:i8042_platform_init
  - drivers/input/serio/i8042.c:i8042_platform_init
```
**Symbols:**

```
ffffffff81822860-ffffffff818228d6: i8042_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int i8042_command(unsigned char *param, int command);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/i8042.c (ffffffff81853cf0)
Location: drivers/input/serio/i8042.c:339
Inline: False
Direct callers:
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_controller_resume
  - drivers/input/serio/i8042.c:i8042_controller_resume
  - drivers/input/serio/i8042.c:i8042_dritek_enable
  - drivers/input/serio/i8042.c:i8042_controller_reset
  - drivers/input/serio/i8042.c:i8042_controller_reset
  - drivers/input/serio/i8042.c:i8042_controller_selftest
  - drivers/input/serio/i8042.c:i8042_toggle_aux
  - drivers/input/serio/i8042.c:i8042_toggle_aux
  - drivers/input/serio/i8042.c:i8042_set_mux_mode
  - drivers/input/serio/i8042.c:i8042_set_mux_mode
  - drivers/input/serio/i8042.c:i8042_set_mux_mode
  - drivers/input/serio/i8042.c:i8042_enable_mux_ports
  - drivers/input/serio/i8042.c:i8042_enable_mux_ports
  - drivers/input/serio/i8042.c:i8042_port_close
  - drivers/input/serio/i8042.c:i8042_port_close
  - drivers/input/serio/i8042.c:i8042_aux_write
  - drivers/input/serio/i8042.c:i8042_platform_init
  - drivers/input/serio/i8042.c:i8042_platform_init
```
**Symbols:**

```
ffffffff81853cf0-ffffffff81853d66: i8042_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int i8042_command(unsigned char *param, int command);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/i8042.c (ffffffff81925f80)
Location: drivers/input/serio/i8042.c:341
Inline: False
Direct callers:
  - drivers/input/serio/i8042.c:i8042_setup_aux
  - drivers/input/serio/i8042.c:i8042_controller_reset
  - drivers/input/serio/i8042.c:i8042_controller_reset
  - drivers/input/serio/i8042.c:i8042_controller_init
  - drivers/input/serio/i8042.c:i8042_controller_init
  - drivers/input/serio/i8042.c:i8042_controller_selftest
  - drivers/input/serio/i8042.c:i8042_check_aux
  - drivers/input/serio/i8042.c:i8042_check_aux
  - drivers/input/serio/i8042.c:i8042_check_aux
  - drivers/input/serio/i8042.c:i8042_toggle_aux
  - drivers/input/serio/i8042.c:i8042_toggle_aux
  - drivers/input/serio/i8042.c:i8042_set_mux_mode
  - drivers/input/serio/i8042.c:i8042_set_mux_mode
  - drivers/input/serio/i8042.c:i8042_set_mux_mode
  - drivers/input/serio/i8042.c:i8042_port_close
  - drivers/input/serio/i8042.c:i8042_port_close
  - drivers/input/serio/i8042.c:i8042_aux_write
  - drivers/input/serio/i8042.c:i8042_platform_init
  - drivers/input/serio/i8042.c:i8042_platform_init
```
**Symbols:**

```
ffffffff81925f80-ffffffff8192601f: i8042_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int i8042_command(unsigned char *param, int command);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/i8042.c (ffffffff8192dae0)
Location: drivers/input/serio/i8042.c:361
Inline: False
Direct callers:
  - drivers/input/serio/i8042.c:i8042_setup_aux
  - drivers/input/serio/i8042.c:i8042_controller_reset
  - drivers/input/serio/i8042.c:i8042_controller_reset
  - drivers/input/serio/i8042.c:i8042_controller_init
  - drivers/input/serio/i8042.c:i8042_controller_init
  - drivers/input/serio/i8042.c:i8042_controller_selftest
  - drivers/input/serio/i8042.c:i8042_check_aux
  - drivers/input/serio/i8042.c:i8042_check_aux
  - drivers/input/serio/i8042.c:i8042_check_aux
  - drivers/input/serio/i8042.c:i8042_toggle_aux
  - drivers/input/serio/i8042.c:i8042_toggle_aux
  - drivers/input/serio/i8042.c:i8042_set_mux_mode
  - drivers/input/serio/i8042.c:i8042_set_mux_mode
  - drivers/input/serio/i8042.c:i8042_set_mux_mode
  - drivers/input/serio/i8042.c:i8042_port_close
  - drivers/input/serio/i8042.c:i8042_port_close
  - drivers/input/serio/i8042.c:i8042_aux_write
  - drivers/input/serio/i8042.c:i8042_platform_init
  - drivers/input/serio/i8042.c:i8042_platform_init
```
**Symbols:**

```
ffffffff8192dae0-ffffffff8192db94: i8042_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int i8042_command(unsigned char *param, int command);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/i8042.c (ffffffff81910ed0)
Location: drivers/input/serio/i8042.c:361
Inline: False
Direct callers:
  - drivers/input/serio/i8042.c:i8042_init
  - drivers/input/serio/i8042.c:i8042_init
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_controller_reset
  - drivers/input/serio/i8042.c:i8042_controller_reset
  - drivers/input/serio/i8042.c:i8042_controller_selftest
  - drivers/input/serio/i8042.c:i8042_check_aux
  - drivers/input/serio/i8042.c:i8042_check_aux
  - drivers/input/serio/i8042.c:i8042_check_aux
  - drivers/input/serio/i8042.c:i8042_toggle_aux
  - drivers/input/serio/i8042.c:i8042_toggle_aux
  - drivers/input/serio/i8042.c:i8042_set_mux_mode
  - drivers/input/serio/i8042.c:i8042_set_mux_mode
  - drivers/input/serio/i8042.c:i8042_set_mux_mode
  - drivers/input/serio/i8042.c:i8042_enable_mux_ports
  - drivers/input/serio/i8042.c:i8042_enable_mux_ports
  - drivers/input/serio/i8042.c:i8042_enable_mux_ports
  - drivers/input/serio/i8042.c:i8042_port_close
  - drivers/input/serio/i8042.c:i8042_port_close
  - drivers/input/serio/i8042.c:i8042_aux_write
```
**Symbols:**

```
ffffffff81910ed0-ffffffff81910f84: i8042_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int i8042_command(unsigned char *param, int command);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/serio/i8042.c (0)
Location: drivers/input/serio/i8042.c:365
Inline: False
Direct callers:
  - drivers/input/serio/i8042.c:i8042_setup_aux
  - drivers/input/serio/i8042.c:i8042_controller_reset
  - drivers/input/serio/i8042.c:i8042_controller_reset
  - drivers/input/serio/i8042.c:i8042_controller_init
  - drivers/input/serio/i8042.c:i8042_controller_init
  - drivers/input/serio/i8042.c:i8042_controller_init
  - drivers/input/serio/i8042.c:i8042_controller_init
  - drivers/input/serio/i8042.c:i8042_controller_selftest
  - drivers/input/serio/i8042.c:i8042_check_aux
  - drivers/input/serio/i8042.c:i8042_check_aux
  - drivers/input/serio/i8042.c:i8042_check_aux
  - drivers/input/serio/i8042.c:i8042_check_aux
  - drivers/input/serio/i8042.c:i8042_check_aux
  - drivers/input/serio/i8042.c:i8042_toggle_aux
  - drivers/input/serio/i8042.c:i8042_toggle_aux
  - drivers/input/serio/i8042.c:i8042_set_mux_mode
  - drivers/input/serio/i8042.c:i8042_set_mux_mode
  - drivers/input/serio/i8042.c:i8042_set_mux_mode
  - drivers/input/serio/i8042.c:i8042_port_close
  - drivers/input/serio/i8042.c:i8042_port_close
  - drivers/input/serio/i8042.c:i8042_aux_write
  - drivers/input/serio/i8042.c:i8042_platform_init
  - drivers/input/serio/i8042.c:i8042_platform_init
```
**Symbols:**

```
ffffffff81d22a79-ffffffff81d22aa1: i8042_command.cold (STB_LOCAL)
ffffffff819b23b0-ffffffff819b247c: i8042_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
int i8042_command(unsigned char *param, int command);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/input/serio/i8042.c (ffffffff81b11c70)
Location: drivers/input/serio/i8042.c:365
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_controller_reset
  - drivers/input/serio/i8042.c:i8042_controller_reset
  - drivers/input/serio/i8042.c:i8042_controller_init
  - drivers/input/serio/i8042.c:i8042_controller_init
  - drivers/input/serio/i8042.c:i8042_controller_selftest
  - drivers/input/serio/i8042.c:i8042_check_aux
  - drivers/input/serio/i8042.c:i8042_check_aux
  - drivers/input/serio/i8042.c:i8042_check_aux
  - drivers/input/serio/i8042.c:i8042_check_aux
  - drivers/input/serio/i8042.c:i8042_toggle_aux
  - drivers/input/serio/i8042.c:i8042_toggle_aux
  - drivers/input/serio/i8042.c:i8042_set_mux_mode
  - drivers/input/serio/i8042.c:i8042_set_mux_mode
  - drivers/input/serio/i8042.c:i8042_set_mux_mode
  - drivers/input/serio/i8042.c:i8042_port_close
  - drivers/input/serio/i8042.c:i8042_port_close
  - drivers/input/serio/i8042.c:i8042_aux_write
Direct callers:
  - drivers/input/serio/i8042.c:i8042_setup_aux
  - drivers/input/serio/i8042.c:i8042_platform_init
  - drivers/input/serio/i8042.c:i8042_platform_init
```
**Symbols:**

```
ffffffff81eee681-ffffffff81eee696: i8042_command.cold (STB_LOCAL)
ffffffff81b11060-ffffffff81b110cf: i8042_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
int i8042_command(unsigned char *param, int command);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/input/serio/i8042.c (ffffffff81ca36ba)
Location: drivers/input/serio/i8042.c:365
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_setup_aux
  - drivers/input/serio/i8042.c:i8042_controller_reset
  - drivers/input/serio/i8042.c:i8042_controller_reset
  - drivers/input/serio/i8042.c:i8042_controller_init
  - drivers/input/serio/i8042.c:i8042_controller_init
  - drivers/input/serio/i8042.c:i8042_controller_selftest
  - drivers/input/serio/i8042.c:i8042_check_aux
  - drivers/input/serio/i8042.c:i8042_check_aux
  - drivers/input/serio/i8042.c:i8042_check_aux
  - drivers/input/serio/i8042.c:i8042_check_aux
  - drivers/input/serio/i8042.c:i8042_toggle_aux
  - drivers/input/serio/i8042.c:i8042_toggle_aux
  - drivers/input/serio/i8042.c:i8042_set_mux_mode
  - drivers/input/serio/i8042.c:i8042_set_mux_mode
  - drivers/input/serio/i8042.c:i8042_set_mux_mode
  - drivers/input/serio/i8042.c:i8042_enable_mux_ports
  - drivers/input/serio/i8042.c:i8042_port_close
  - drivers/input/serio/i8042.c:i8042_port_close
  - drivers/input/serio/i8042.c:i8042_aux_write
Direct callers:
  - drivers/input/serio/i8042.c:i8042_enable_mux_ports
  - drivers/input/serio/i8042.c:i8042_enable_mux_ports
  - drivers/input/serio/i8042.c:i8042_platform_init
  - drivers/input/serio/i8042.c:i8042_platform_init
```
**Symbols:**

```
ffffffff820a62d0-ffffffff820a62e5: i8042_command.cold (STB_LOCAL)
ffffffff81ca1aa0-ffffffff81ca1b0f: i8042_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
int i8042_command(unsigned char *param, int command);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/input/serio/i8042.c (ffffffff81d0ad7a)
Location: drivers/input/serio/i8042.c:365
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_setup_aux
  - drivers/input/serio/i8042.c:i8042_controller_reset
  - drivers/input/serio/i8042.c:i8042_controller_reset
  - drivers/input/serio/i8042.c:i8042_controller_init
  - drivers/input/serio/i8042.c:i8042_controller_init
  - drivers/input/serio/i8042.c:i8042_controller_selftest
  - drivers/input/serio/i8042.c:i8042_check_aux
  - drivers/input/serio/i8042.c:i8042_check_aux
  - drivers/input/serio/i8042.c:i8042_check_aux
  - drivers/input/serio/i8042.c:i8042_check_aux
  - drivers/input/serio/i8042.c:i8042_toggle_aux
  - drivers/input/serio/i8042.c:i8042_toggle_aux
  - drivers/input/serio/i8042.c:i8042_set_mux_mode
  - drivers/input/serio/i8042.c:i8042_set_mux_mode
  - drivers/input/serio/i8042.c:i8042_set_mux_mode
  - drivers/input/serio/i8042.c:i8042_enable_mux_ports
  - drivers/input/serio/i8042.c:i8042_port_close
  - drivers/input/serio/i8042.c:i8042_port_close
  - drivers/input/serio/i8042.c:i8042_aux_write
Direct callers:
  - drivers/input/serio/i8042.c:i8042_enable_mux_ports
  - drivers/input/serio/i8042.c:i8042_enable_mux_ports
  - drivers/input/serio/i8042.c:i8042_platform_init
  - drivers/input/serio/i8042.c:i8042_platform_init
```
**Symbols:**

```
ffffffff821276d7-ffffffff821276ec: i8042_command.cold (STB_LOCAL)
ffffffff81d08ec0-ffffffff81d08f2f: i8042_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int i8042_command(unsigned char *param, int command);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/input/serio/i8042.c (ffffffff81dc0a0a)
Location: drivers/input/serio/i8042.c:365
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_setup_aux
  - drivers/input/serio/i8042.c:i8042_controller_reset
  - drivers/input/serio/i8042.c:i8042_controller_reset
  - drivers/input/serio/i8042.c:i8042_controller_init
  - drivers/input/serio/i8042.c:i8042_controller_init
  - drivers/input/serio/i8042.c:i8042_controller_selftest
  - drivers/input/serio/i8042.c:i8042_check_aux
  - drivers/input/serio/i8042.c:i8042_check_aux
  - drivers/input/serio/i8042.c:i8042_check_aux
  - drivers/input/serio/i8042.c:i8042_check_aux
  - drivers/input/serio/i8042.c:i8042_toggle_aux
  - drivers/input/serio/i8042.c:i8042_toggle_aux
  - drivers/input/serio/i8042.c:i8042_set_mux_mode
  - drivers/input/serio/i8042.c:i8042_set_mux_mode
  - drivers/input/serio/i8042.c:i8042_set_mux_mode
  - drivers/input/serio/i8042.c:i8042_enable_mux_ports
  - drivers/input/serio/i8042.c:i8042_port_close
  - drivers/input/serio/i8042.c:i8042_port_close
  - drivers/input/serio/i8042.c:i8042_aux_write
Direct callers:
  - drivers/input/serio/i8042.c:i8042_enable_mux_ports
  - drivers/input/serio/i8042.c:i8042_enable_mux_ports
  - drivers/input/serio/i8042.c:i8042_platform_init
  - drivers/input/serio/i8042.c:i8042_platform_init
```
**Symbols:**

```
ffffffff82209058-ffffffff8220906d: i8042_command.cold (STB_LOCAL)
ffffffff81dbeb50-ffffffff81dbebbf: i8042_command (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int i8042_command(unsigned char *param, int command);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/i8042.c (c000000000b710c0)
Location: drivers/input/serio/i8042.c:339
Inline: False
Direct callers:
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_controller_resume
  - drivers/input/serio/i8042.c:i8042_controller_resume
  - drivers/input/serio/i8042.c:i8042_controller_reset
  - drivers/input/serio/i8042.c:i8042_controller_reset
  - drivers/input/serio/i8042.c:i8042_controller_selftest
  - drivers/input/serio/i8042.c:i8042_toggle_aux
  - drivers/input/serio/i8042.c:i8042_toggle_aux
  - drivers/input/serio/i8042.c:i8042_set_mux_mode
  - drivers/input/serio/i8042.c:i8042_set_mux_mode
  - drivers/input/serio/i8042.c:i8042_set_mux_mode
  - drivers/input/serio/i8042.c:i8042_enable_mux_ports
  - drivers/input/serio/i8042.c:i8042_enable_mux_ports
  - drivers/input/serio/i8042.c:i8042_port_close
  - drivers/input/serio/i8042.c:i8042_port_close
  - drivers/input/serio/i8042.c:i8042_aux_write
  - drivers/input/serio/i8042.c:i8042_aux_write
```
**Symbols:**

```
c000000000b710c0-c000000000b71184: i8042_command (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int i8042_command(unsigned char *param, int command);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/i8042.c (ffffffff81808e40)
Location: drivers/input/serio/i8042.c:339
Inline: False
Direct callers:
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_pm_restore
  - drivers/input/serio/i8042.c:i8042_pm_restore
  - drivers/input/serio/i8042.c:i8042_dritek_enable
  - drivers/input/serio/i8042.c:i8042_controller_selftest
  - drivers/input/serio/i8042.c:i8042_toggle_aux
  - drivers/input/serio/i8042.c:i8042_toggle_aux
  - drivers/input/serio/i8042.c:i8042_set_mux_mode
  - drivers/input/serio/i8042.c:i8042_set_mux_mode
  - drivers/input/serio/i8042.c:i8042_set_mux_mode
  - drivers/input/serio/i8042.c:i8042_enable_mux_ports
  - drivers/input/serio/i8042.c:i8042_enable_mux_ports
  - drivers/input/serio/i8042.c:i8042_port_close
  - drivers/input/serio/i8042.c:i8042_port_close
  - drivers/input/serio/i8042.c:i8042_aux_write
  - drivers/input/serio/i8042.c:i8042_platform_init
  - drivers/input/serio/i8042.c:i8042_platform_init
```
**Symbols:**

```
ffffffff81808e40-ffffffff81808eb6: i8042_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int i8042_command(unsigned char *param, int command);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/i8042.c (ffffffff817d04b0)
Location: drivers/input/serio/i8042.c:339
Inline: False
Direct callers:
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_controller_resume
  - drivers/input/serio/i8042.c:i8042_controller_resume
  - drivers/input/serio/i8042.c:i8042_dritek_enable
  - drivers/input/serio/i8042.c:i8042_controller_reset
  - drivers/input/serio/i8042.c:i8042_controller_reset
  - drivers/input/serio/i8042.c:i8042_controller_selftest
  - drivers/input/serio/i8042.c:i8042_toggle_aux
  - drivers/input/serio/i8042.c:i8042_toggle_aux
  - drivers/input/serio/i8042.c:i8042_set_mux_mode
  - drivers/input/serio/i8042.c:i8042_set_mux_mode
  - drivers/input/serio/i8042.c:i8042_set_mux_mode
  - drivers/input/serio/i8042.c:i8042_enable_mux_ports
  - drivers/input/serio/i8042.c:i8042_enable_mux_ports
  - drivers/input/serio/i8042.c:i8042_port_close
  - drivers/input/serio/i8042.c:i8042_port_close
  - drivers/input/serio/i8042.c:i8042_aux_write
  - drivers/input/serio/i8042.c:i8042_platform_init
  - drivers/input/serio/i8042.c:i8042_platform_init
```
**Symbols:**

```
ffffffff817d04b0-ffffffff817d0526: i8042_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int i8042_command(unsigned char *param, int command);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/i8042.c (ffffffff81847e80)
Location: drivers/input/serio/i8042.c:339
Inline: False
Direct callers:
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_controller_resume
  - drivers/input/serio/i8042.c:i8042_controller_resume
  - drivers/input/serio/i8042.c:i8042_dritek_enable
  - drivers/input/serio/i8042.c:i8042_controller_reset
  - drivers/input/serio/i8042.c:i8042_controller_reset
  - drivers/input/serio/i8042.c:i8042_controller_selftest
  - drivers/input/serio/i8042.c:i8042_toggle_aux
  - drivers/input/serio/i8042.c:i8042_toggle_aux
  - drivers/input/serio/i8042.c:i8042_set_mux_mode
  - drivers/input/serio/i8042.c:i8042_set_mux_mode
  - drivers/input/serio/i8042.c:i8042_set_mux_mode
  - drivers/input/serio/i8042.c:i8042_enable_mux_ports
  - drivers/input/serio/i8042.c:i8042_enable_mux_ports
  - drivers/input/serio/i8042.c:i8042_port_close
  - drivers/input/serio/i8042.c:i8042_port_close
  - drivers/input/serio/i8042.c:i8042_aux_write
  - drivers/input/serio/i8042.c:i8042_platform_init
  - drivers/input/serio/i8042.c:i8042_platform_init
```
**Symbols:**

```
ffffffff81847e80-ffffffff81847ef6: i8042_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int i8042_command(unsigned char *param, int command);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/i8042.c (ffffffff81863100)
Location: drivers/input/serio/i8042.c:339
Inline: False
Direct callers:
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_controller_resume
  - drivers/input/serio/i8042.c:i8042_controller_resume
  - drivers/input/serio/i8042.c:i8042_dritek_enable
  - drivers/input/serio/i8042.c:i8042_controller_reset
  - drivers/input/serio/i8042.c:i8042_controller_reset
  - drivers/input/serio/i8042.c:i8042_controller_selftest
  - drivers/input/serio/i8042.c:i8042_toggle_aux
  - drivers/input/serio/i8042.c:i8042_toggle_aux
  - drivers/input/serio/i8042.c:i8042_set_mux_mode
  - drivers/input/serio/i8042.c:i8042_set_mux_mode
  - drivers/input/serio/i8042.c:i8042_set_mux_mode
  - drivers/input/serio/i8042.c:i8042_enable_mux_ports
  - drivers/input/serio/i8042.c:i8042_enable_mux_ports
  - drivers/input/serio/i8042.c:i8042_port_close
  - drivers/input/serio/i8042.c:i8042_port_close
  - drivers/input/serio/i8042.c:i8042_aux_write
  - drivers/input/serio/i8042.c:i8042_platform_init
  - drivers/input/serio/i8042.c:i8042_platform_init
```
**Symbols:**

```
ffffffff81863100-ffffffff81863176: i8042_command (STB_GLOBAL)
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
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
