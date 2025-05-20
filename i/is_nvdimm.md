# Function: <code>is_nvdimm</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
bool is_nvdimm(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff81598f80)
Location: drivers/nvdimm/dimm_devs.c:198
Inline: True
Direct callers:
  - drivers/nvdimm/bus.c:match_dimm
```
**Symbols:**

```
ffffffff81598f80-ffffffff81598f96: is_nvdimm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
bool is_nvdimm(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff815eea60)
Location: drivers/nvdimm/dimm_devs.c:198
Inline: True
Direct callers:
  - drivers/nvdimm/bus.c:match_dimm
```
**Symbols:**

```
ffffffff815eea60-ffffffff815eea76: is_nvdimm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
bool is_nvdimm(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff8161bba0)
Location: drivers/nvdimm/dimm_devs.c:207
Inline: True
Direct callers:
  - drivers/nvdimm/bus.c:match_dimm
```
**Symbols:**

```
ffffffff8161bba0-ffffffff8161bbb6: is_nvdimm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
bool is_nvdimm(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff8162fc90)
Location: drivers/nvdimm/dimm_devs.c:216
Inline: True
Direct callers:
  - drivers/nvdimm/bus.c:match_dimm
```
**Symbols:**

```
ffffffff8162fc90-ffffffff8162fca6: is_nvdimm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
bool is_nvdimm(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff816984a0)
Location: drivers/nvdimm/dimm_devs.c:223
Inline: True
Direct callers:
  - drivers/nvdimm/bus.c:match_dimm
```
**Symbols:**

```
ffffffff816984a0-ffffffff816984b6: is_nvdimm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
bool is_nvdimm(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff816d3915)
Location: drivers/nvdimm/dimm_devs.c:225
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:count_dimms
  - drivers/nvdimm/dimm_devs.c:state_show
  - drivers/nvdimm/dimm_devs.c:flags_show
  - drivers/nvdimm/dimm_devs.c:nvdimm_release
  - drivers/nvdimm/dimm_devs.c:nvdimm_clear_locked
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_locked
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_aliasing
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_init_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_init_nsarea
  - drivers/nvdimm/dimm_devs.c:nvdimm_check_config_data
Direct callers:
  - drivers/nvdimm/bus.c:match_dimm
```
**Symbols:**

```
ffffffff816d4650-ffffffff816d4666: is_nvdimm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
bool is_nvdimm(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff816f5035)
Location: drivers/nvdimm/dimm_devs.c:213
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:count_dimms
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events
  - drivers/nvdimm/dimm_devs.c:security_store
  - drivers/nvdimm/dimm_devs.c:state_show
  - drivers/nvdimm/dimm_devs.c:flags_show
  - drivers/nvdimm/dimm_devs.c:nvdimm_release
  - drivers/nvdimm/dimm_devs.c:nvdimm_clear_locked
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_locked
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_aliasing
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_init_nsarea
  - drivers/nvdimm/dimm_devs.c:nvdimm_check_config_data
Direct callers:
  - drivers/nvdimm/bus.c:match_dimm
```
**Symbols:**

```
ffffffff816f5fb0-ffffffff816f5fc6: is_nvdimm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
bool is_nvdimm(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff8172e8e5)
Location: drivers/nvdimm/dimm_devs.c:210
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:count_dimms
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events
  - drivers/nvdimm/dimm_devs.c:__security_store
  - drivers/nvdimm/dimm_devs.c:state_show
  - drivers/nvdimm/dimm_devs.c:flags_show
  - drivers/nvdimm/dimm_devs.c:nvdimm_release
  - drivers/nvdimm/dimm_devs.c:nvdimm_clear_locked
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_locked
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_aliasing
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_init_nsarea
  - drivers/nvdimm/dimm_devs.c:nvdimm_check_config_data
Direct callers:
  - drivers/nvdimm/bus.c:match_dimm
```
**Symbols:**

```
ffffffff8172f770-ffffffff8172f786: is_nvdimm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool is_nvdimm(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff81752b35)
Location: drivers/nvdimm/dimm_devs.c:210
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:count_dimms
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events
  - drivers/nvdimm/dimm_devs.c:frozen_show
  - drivers/nvdimm/dimm_devs.c:state_show
  - drivers/nvdimm/dimm_devs.c:flags_show
  - drivers/nvdimm/dimm_devs.c:nvdimm_release
  - drivers/nvdimm/dimm_devs.c:nvdimm_clear_locked
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_locked
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_aliasing
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_init_nsarea
  - drivers/nvdimm/dimm_devs.c:nvdimm_check_config_data
Direct callers:
  - drivers/nvdimm/bus.c:match_dimm
```
**Symbols:**

```
ffffffff81753c30-ffffffff81753c46: is_nvdimm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool is_nvdimm(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff81811565)
Location: drivers/nvdimm/dimm_devs.c:461
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:count_dimms
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events
  - drivers/nvdimm/dimm_devs.c:frozen_show
  - drivers/nvdimm/dimm_devs.c:security_show
  - drivers/nvdimm/dimm_devs.c:state_show
  - drivers/nvdimm/dimm_devs.c:flags_show
  - drivers/nvdimm/dimm_devs.c:nvdimm_release
  - drivers/nvdimm/dimm_devs.c:nvdimm_clear_locked
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_locked
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_labeling
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_init_nsarea
  - drivers/nvdimm/dimm_devs.c:validate_dimm
Direct callers:
  - drivers/nvdimm/bus.c:match_dimm
```
**Symbols:**

```
ffffffff81812700-ffffffff81812716: is_nvdimm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool is_nvdimm(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff81820405)
Location: drivers/nvdimm/dimm_devs.c:589
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:count_dimms
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events
  - drivers/nvdimm/dimm_devs.c:nvdimm_firmware_visible
  - drivers/nvdimm/dimm_devs.c:activate_store
  - drivers/nvdimm/dimm_devs.c:activate_show
  - drivers/nvdimm/dimm_devs.c:result_show
  - drivers/nvdimm/dimm_devs.c:frozen_show
  - drivers/nvdimm/dimm_devs.c:security_show
  - drivers/nvdimm/dimm_devs.c:state_show
  - drivers/nvdimm/dimm_devs.c:flags_show
  - drivers/nvdimm/dimm_devs.c:nvdimm_release
  - drivers/nvdimm/dimm_devs.c:nvdimm_clear_locked
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_locked
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_labeling
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_init_nsarea
  - drivers/nvdimm/dimm_devs.c:validate_dimm
Direct callers:
  - drivers/nvdimm/bus.c:match_dimm
```
**Symbols:**

```
ffffffff81821950-ffffffff81821966: is_nvdimm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool is_nvdimm(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff818036e5)
Location: drivers/nvdimm/dimm_devs.c:589
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:count_dimms
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events
  - drivers/nvdimm/dimm_devs.c:nvdimm_firmware_visible
  - drivers/nvdimm/dimm_devs.c:activate_store
  - drivers/nvdimm/dimm_devs.c:activate_show
  - drivers/nvdimm/dimm_devs.c:result_show
  - drivers/nvdimm/dimm_devs.c:frozen_show
  - drivers/nvdimm/dimm_devs.c:security_show
  - drivers/nvdimm/dimm_devs.c:state_show
  - drivers/nvdimm/dimm_devs.c:flags_show
  - drivers/nvdimm/dimm_devs.c:commands_show
  - drivers/nvdimm/dimm_devs.c:nvdimm_release
  - drivers/nvdimm/dimm_devs.c:nvdimm_clear_locked
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_locked
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_labeling
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_init_nsarea
  - drivers/nvdimm/dimm_devs.c:validate_dimm
Direct callers:
  - drivers/nvdimm/bus.c:match_dimm
```
**Symbols:**

```
ffffffff81804c70-ffffffff81804c86: is_nvdimm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool is_nvdimm(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff8188dc65)
Location: drivers/nvdimm/dimm_devs.c:589
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:count_dimms
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events
  - drivers/nvdimm/dimm_devs.c:nvdimm_firmware_visible
  - drivers/nvdimm/dimm_devs.c:activate_store
  - drivers/nvdimm/dimm_devs.c:activate_show
  - drivers/nvdimm/dimm_devs.c:result_show
  - drivers/nvdimm/dimm_devs.c:frozen_show
  - drivers/nvdimm/dimm_devs.c:security_show
  - drivers/nvdimm/dimm_devs.c:state_show
  - drivers/nvdimm/dimm_devs.c:flags_show
  - drivers/nvdimm/dimm_devs.c:commands_show
  - drivers/nvdimm/dimm_devs.c:nvdimm_release
  - drivers/nvdimm/dimm_devs.c:nvdimm_clear_locked
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_locked
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_labeling
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_init_nsarea
  - drivers/nvdimm/dimm_devs.c:validate_dimm
Direct callers:
  - drivers/nvdimm/bus.c:match_dimm
```
**Symbols:**

```
ffffffff8188f3d0-ffffffff8188f3e6: is_nvdimm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
bool is_nvdimm(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff819d71c5)
Location: drivers/nvdimm/dimm_devs.c:568
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:count_dimms
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events
  - drivers/nvdimm/dimm_devs.c:nvdimm_firmware_visible
  - drivers/nvdimm/dimm_devs.c:activate_store
  - drivers/nvdimm/dimm_devs.c:activate_show
  - drivers/nvdimm/dimm_devs.c:result_show
  - drivers/nvdimm/dimm_devs.c:frozen_show
  - drivers/nvdimm/dimm_devs.c:security_show
  - drivers/nvdimm/dimm_devs.c:state_show
  - drivers/nvdimm/dimm_devs.c:flags_show
  - drivers/nvdimm/dimm_devs.c:commands_show
  - drivers/nvdimm/dimm_devs.c:nvdimm_release
  - drivers/nvdimm/dimm_devs.c:nvdimm_clear_locked
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_locked
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_labeling
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_init_nsarea
  - drivers/nvdimm/dimm_devs.c:validate_dimm
Direct callers:
  - drivers/nvdimm/bus.c:match_dimm
```
**Symbols:**

```
ffffffff819d8970-ffffffff819d898c: is_nvdimm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
bool is_nvdimm(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff81b51f05)
Location: drivers/nvdimm/dimm_devs.c:575
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:count_dimms
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events
  - drivers/nvdimm/dimm_devs.c:nvdimm_firmware_visible
  - drivers/nvdimm/dimm_devs.c:activate_store
  - drivers/nvdimm/dimm_devs.c:activate_show
  - drivers/nvdimm/dimm_devs.c:result_show
  - drivers/nvdimm/dimm_devs.c:frozen_show
  - drivers/nvdimm/dimm_devs.c:security_show
  - drivers/nvdimm/dimm_devs.c:state_show
  - drivers/nvdimm/dimm_devs.c:flags_show
  - drivers/nvdimm/dimm_devs.c:nvdimm_release
  - drivers/nvdimm/dimm_devs.c:nvdimm_clear_locked
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_locked
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_labeling
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_init_nsarea
  - drivers/nvdimm/dimm_devs.c:validate_dimm
Direct callers:
  - drivers/nvdimm/bus.c:match_dimm
```
**Symbols:**

```
ffffffff81b538d0-ffffffff81b538ec: is_nvdimm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
bool is_nvdimm(const struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff81ba53e5)
Location: drivers/nvdimm/dimm_devs.c:575
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:count_dimms
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events
  - drivers/nvdimm/dimm_devs.c:nvdimm_firmware_visible
  - drivers/nvdimm/dimm_devs.c:activate_store
  - drivers/nvdimm/dimm_devs.c:activate_show
  - drivers/nvdimm/dimm_devs.c:result_show
  - drivers/nvdimm/dimm_devs.c:frozen_show
  - drivers/nvdimm/dimm_devs.c:security_show
  - drivers/nvdimm/dimm_devs.c:state_show
  - drivers/nvdimm/dimm_devs.c:flags_show
  - drivers/nvdimm/dimm_devs.c:nvdimm_release
  - drivers/nvdimm/dimm_devs.c:nvdimm_clear_locked
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_locked
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_labeling
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_init_nsarea
  - drivers/nvdimm/dimm_devs.c:validate_dimm
Direct callers:
  - drivers/nvdimm/bus.c:match_dimm
```
**Symbols:**

```
ffffffff81ba6dd0-ffffffff81ba6dec: is_nvdimm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
bool is_nvdimm(const struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff81bf9665)
Location: drivers/nvdimm/dimm_devs.c:577
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:count_dimms
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events
  - drivers/nvdimm/dimm_devs.c:nvdimm_firmware_visible
  - drivers/nvdimm/dimm_devs.c:activate_store
  - drivers/nvdimm/dimm_devs.c:activate_show
  - drivers/nvdimm/dimm_devs.c:result_show
  - drivers/nvdimm/dimm_devs.c:frozen_show
  - drivers/nvdimm/dimm_devs.c:security_show
  - drivers/nvdimm/dimm_devs.c:state_show
  - drivers/nvdimm/dimm_devs.c:flags_show
  - drivers/nvdimm/dimm_devs.c:nvdimm_release
  - drivers/nvdimm/dimm_devs.c:nvdimm_clear_locked
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_locked
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_labeling
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_init_nsarea
  - drivers/nvdimm/dimm_devs.c:validate_dimm
Direct callers:
  - drivers/nvdimm/bus.c:match_dimm
```
**Symbols:**

```
ffffffff81bfb080-ffffffff81bfb09c: is_nvdimm (STB_GLOBAL)
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
bool is_nvdimm(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffff800010953204)
Location: drivers/nvdimm/dimm_devs.c:210
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:count_dimms
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events
  - drivers/nvdimm/dimm_devs.c:frozen_show
  - drivers/nvdimm/dimm_devs.c:state_show
  - drivers/nvdimm/dimm_devs.c:flags_show
  - drivers/nvdimm/dimm_devs.c:nvdimm_release
  - drivers/nvdimm/dimm_devs.c:nvdimm_clear_locked
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_locked
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_aliasing
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_init_nsarea
  - drivers/nvdimm/dimm_devs.c:nvdimm_check_config_data
Direct callers:
  - drivers/nvdimm/bus.c:match_dimm
```
**Symbols:**

```
ffff800010954638-ffff800010954670: is_nvdimm (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
bool is_nvdimm(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (c000000000a00290)
Location: drivers/nvdimm/dimm_devs.c:210
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:count_dimms
  - drivers/nvdimm/dimm_devs.c:to_nvdimm
Direct callers:
  - drivers/nvdimm/bus.c:match_dimm
```
**Symbols:**

```
c000000000a01c30-c000000000a01c5c: is_nvdimm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
bool is_nvdimm(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffe0005c2bf4)
Location: drivers/nvdimm/dimm_devs.c:210
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:count_dimms
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events
  - drivers/nvdimm/dimm_devs.c:frozen_show
  - drivers/nvdimm/dimm_devs.c:state_show
  - drivers/nvdimm/dimm_devs.c:flags_show
  - drivers/nvdimm/dimm_devs.c:nvdimm_release
  - drivers/nvdimm/dimm_devs.c:nvdimm_clear_locked
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_locked
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_aliasing
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_init_nsarea
  - drivers/nvdimm/dimm_devs.c:nvdimm_check_config_data
Direct callers:
  - drivers/nvdimm/bus.c:match_dimm
```
**Symbols:**

```
ffffffe0005c3dee-ffffffe0005c3e1e: is_nvdimm (STB_GLOBAL)
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
bool is_nvdimm(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff81707225)
Location: drivers/nvdimm/dimm_devs.c:210
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:count_dimms
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events
  - drivers/nvdimm/dimm_devs.c:frozen_show
  - drivers/nvdimm/dimm_devs.c:state_show
  - drivers/nvdimm/dimm_devs.c:flags_show
  - drivers/nvdimm/dimm_devs.c:nvdimm_release
  - drivers/nvdimm/dimm_devs.c:nvdimm_clear_locked
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_locked
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_aliasing
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_init_nsarea
  - drivers/nvdimm/dimm_devs.c:nvdimm_check_config_data
Direct callers:
  - drivers/nvdimm/bus.c:match_dimm
```
**Symbols:**

```
ffffffff81708320-ffffffff81708336: is_nvdimm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
bool is_nvdimm(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff816daca5)
Location: drivers/nvdimm/dimm_devs.c:210
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:count_dimms
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events
  - drivers/nvdimm/dimm_devs.c:frozen_show
  - drivers/nvdimm/dimm_devs.c:state_show
  - drivers/nvdimm/dimm_devs.c:flags_show
  - drivers/nvdimm/dimm_devs.c:nvdimm_release
  - drivers/nvdimm/dimm_devs.c:nvdimm_clear_locked
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_locked
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_aliasing
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_init_nsarea
  - drivers/nvdimm/dimm_devs.c:nvdimm_check_config_data
Direct callers:
  - drivers/nvdimm/bus.c:match_dimm
```
**Symbols:**

```
ffffffff816dbda0-ffffffff816dbdb6: is_nvdimm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool is_nvdimm(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff81745ff5)
Location: drivers/nvdimm/dimm_devs.c:210
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:count_dimms
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events
  - drivers/nvdimm/dimm_devs.c:frozen_show
  - drivers/nvdimm/dimm_devs.c:state_show
  - drivers/nvdimm/dimm_devs.c:flags_show
  - drivers/nvdimm/dimm_devs.c:nvdimm_release
  - drivers/nvdimm/dimm_devs.c:nvdimm_clear_locked
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_locked
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_aliasing
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_init_nsarea
  - drivers/nvdimm/dimm_devs.c:nvdimm_check_config_data
Direct callers:
  - drivers/nvdimm/bus.c:match_dimm
```
**Symbols:**

```
ffffffff817470f0-ffffffff81747106: is_nvdimm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool is_nvdimm(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff81761435)
Location: drivers/nvdimm/dimm_devs.c:210
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:count_dimms
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events
  - drivers/nvdimm/dimm_devs.c:frozen_show
  - drivers/nvdimm/dimm_devs.c:state_show
  - drivers/nvdimm/dimm_devs.c:flags_show
  - drivers/nvdimm/dimm_devs.c:nvdimm_release
  - drivers/nvdimm/dimm_devs.c:nvdimm_clear_locked
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_locked
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_aliasing
  - drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data
  - drivers/nvdimm/dimm_devs.c:nvdimm_init_nsarea
  - drivers/nvdimm/dimm_devs.c:nvdimm_check_config_data
Direct callers:
  - drivers/nvdimm/bus.c:match_dimm
```
**Symbols:**

```
ffffffff81762530-ffffffff81762546: is_nvdimm (STB_GLOBAL)
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct device *dev</code> ➡️ <code>const struct device *dev</code>
</li>
</ul>
</details>
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
