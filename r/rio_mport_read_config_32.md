# Function: <code>rio_mport_read_config_32</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int rio_mport_read_config_32(struct rio_mport *mport, u16 destid, u8 hopcount, u32 offset, u32 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rapidio/rio-access.c (ffffffff8145b130)
Location: drivers/rapidio/rio-access.c:141
Inline: False
Direct callers:
  - drivers/rapidio/rio.c:rio_mport_get_feature
  - drivers/rapidio/rio.c:rio_mport_get_feature
  - drivers/rapidio/rio.c:rio_set_port_lockout
  - drivers/rapidio/rio.c:rio_mport_chk_dev_access
  - drivers/rapidio/rio.c:rio_lock_device
  - drivers/rapidio/rio.c:rio_lock_device
  - drivers/rapidio/rio.c:rio_unlock_device
  - drivers/rapidio/rio.c:rio_route_get_entry
  - drivers/rapidio/rio.c:rio_route_clr_table
  - drivers/rapidio/rio.c:rio_route_clr_table
  - drivers/rapidio/rio.c:rio_mport_get_physefb
  - drivers/rapidio/rio.c:rio_mport_get_physefb
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio-sysfs.c:rio_read_config
```
**Symbols:**

```
ffffffff8145b130-ffffffff8145b1f5: rio_mport_read_config_32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int rio_mport_read_config_32(struct rio_mport *mport, u16 destid, u8 hopcount, u32 offset, u32 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rapidio/rio-access.c (ffffffff814a9230)
Location: drivers/rapidio/rio-access.c:141
Inline: False
Direct callers:
  - drivers/rapidio/rio.c:rio_route_clr_table
  - drivers/rapidio/rio.c:rio_route_clr_table
  - drivers/rapidio/rio.c:rio_route_get_entry
  - drivers/rapidio/rio.c:rio_unlock_device
  - drivers/rapidio/rio.c:rio_lock_device
  - drivers/rapidio/rio.c:rio_lock_device
  - drivers/rapidio/rio.c:rio_mport_get_feature
  - drivers/rapidio/rio.c:rio_mport_get_feature
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_mport_chk_dev_access
  - drivers/rapidio/rio.c:rio_set_port_lockout
  - drivers/rapidio/rio.c:rio_mport_get_physefb
  - drivers/rapidio/rio.c:rio_mport_get_physefb
  - drivers/rapidio/rio-sysfs.c:rio_read_config
```
**Symbols:**

```
ffffffff814a9230-ffffffff814a92fb: rio_mport_read_config_32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int rio_mport_read_config_32(struct rio_mport *mport, u16 destid, u8 hopcount, u32 offset, u32 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rapidio/rio-access.c (ffffffff814cb340)
Location: drivers/rapidio/rio-access.c:141
Inline: False
Direct callers:
  - drivers/rapidio/rio.c:rio_route_clr_table
  - drivers/rapidio/rio.c:rio_route_clr_table
  - drivers/rapidio/rio.c:rio_route_get_entry
  - drivers/rapidio/rio.c:rio_unlock_device
  - drivers/rapidio/rio.c:rio_lock_device
  - drivers/rapidio/rio.c:rio_lock_device
  - drivers/rapidio/rio.c:rio_mport_get_feature
  - drivers/rapidio/rio.c:rio_mport_get_feature
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_mport_chk_dev_access
  - drivers/rapidio/rio.c:rio_set_port_lockout
  - drivers/rapidio/rio.c:rio_mport_get_physefb
  - drivers/rapidio/rio.c:rio_mport_get_physefb
  - drivers/rapidio/rio-sysfs.c:rio_read_config
```
**Symbols:**

```
ffffffff814cb340-ffffffff814cb40b: rio_mport_read_config_32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int rio_mport_read_config_32(struct rio_mport *mport, u16 destid, u8 hopcount, u32 offset, u32 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rapidio/rio-access.c (ffffffff814d7250)
Location: drivers/rapidio/rio-access.c:141
Inline: False
Direct callers:
  - drivers/rapidio/rio.c:rio_route_clr_table
  - drivers/rapidio/rio.c:rio_route_clr_table
  - drivers/rapidio/rio.c:rio_route_get_entry
  - drivers/rapidio/rio.c:rio_unlock_device
  - drivers/rapidio/rio.c:rio_lock_device
  - drivers/rapidio/rio.c:rio_lock_device
  - drivers/rapidio/rio.c:rio_mport_get_feature
  - drivers/rapidio/rio.c:rio_mport_get_feature
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_mport_chk_dev_access
  - drivers/rapidio/rio.c:rio_set_port_lockout
  - drivers/rapidio/rio.c:rio_mport_get_physefb
  - drivers/rapidio/rio.c:rio_mport_get_physefb
  - drivers/rapidio/rio-sysfs.c:rio_read_config
```
**Symbols:**

```
ffffffff814d7250-ffffffff814d7313: rio_mport_read_config_32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int rio_mport_read_config_32(struct rio_mport *mport, u16 destid, u8 hopcount, u32 offset, u32 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rapidio/rio-access.c (ffffffff81517690)
Location: drivers/rapidio/rio-access.c:118
Inline: False
Direct callers:
  - drivers/rapidio/rio.c:rio_route_clr_table
  - drivers/rapidio/rio.c:rio_route_clr_table
  - drivers/rapidio/rio.c:rio_route_get_entry
  - drivers/rapidio/rio.c:rio_unlock_device
  - drivers/rapidio/rio.c:rio_lock_device
  - drivers/rapidio/rio.c:rio_lock_device
  - drivers/rapidio/rio.c:rio_mport_get_feature
  - drivers/rapidio/rio.c:rio_mport_get_feature
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_mport_chk_dev_access
  - drivers/rapidio/rio.c:rio_set_port_lockout
  - drivers/rapidio/rio.c:rio_mport_get_physefb
  - drivers/rapidio/rio.c:rio_mport_get_physefb
  - drivers/rapidio/rio-sysfs.c:rio_read_config
```
**Symbols:**

```
ffffffff81517690-ffffffff81517710: rio_mport_read_config_32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int rio_mport_read_config_32(struct rio_mport *mport, u16 destid, u8 hopcount, u32 offset, u32 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rapidio/rio-access.c (ffffffff8154d270)
Location: drivers/rapidio/rio-access.c:118
Inline: False
Direct callers:
  - drivers/rapidio/rio.c:rio_route_clr_table
  - drivers/rapidio/rio.c:rio_route_clr_table
  - drivers/rapidio/rio.c:rio_route_get_entry
  - drivers/rapidio/rio.c:rio_unlock_device
  - drivers/rapidio/rio.c:rio_lock_device
  - drivers/rapidio/rio.c:rio_lock_device
  - drivers/rapidio/rio.c:rio_mport_get_feature
  - drivers/rapidio/rio.c:rio_mport_get_feature
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_set_port_lockout
  - drivers/rapidio/rio.c:rio_mport_get_physefb
  - drivers/rapidio/rio.c:rio_mport_get_physefb
  - drivers/rapidio/rio-sysfs.c:rio_read_config
```
**Symbols:**

```
ffffffff8154d270-ffffffff8154d2f0: rio_mport_read_config_32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int rio_mport_read_config_32(struct rio_mport *mport, u16 destid, u8 hopcount, u32 offset, u32 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rapidio/rio-access.c (ffffffff815646b0)
Location: drivers/rapidio/rio-access.c:118
Inline: False
Direct callers:
  - drivers/rapidio/rio.c:rio_route_clr_table
  - drivers/rapidio/rio.c:rio_route_clr_table
  - drivers/rapidio/rio.c:rio_route_get_entry
  - drivers/rapidio/rio.c:rio_unlock_device
  - drivers/rapidio/rio.c:rio_lock_device
  - drivers/rapidio/rio.c:rio_lock_device
  - drivers/rapidio/rio.c:rio_mport_get_feature
  - drivers/rapidio/rio.c:rio_mport_get_feature
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_set_port_lockout
  - drivers/rapidio/rio.c:rio_mport_get_physefb
  - drivers/rapidio/rio.c:rio_mport_get_physefb
  - drivers/rapidio/rio-sysfs.c:rio_read_config
```
**Symbols:**

```
ffffffff815646b0-ffffffff81564730: rio_mport_read_config_32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int rio_mport_read_config_32(struct rio_mport *mport, u16 destid, u8 hopcount, u32 offset, u32 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rapidio/rio-access.c (ffffffff81594a40)
Location: drivers/rapidio/rio-access.c:114
Inline: False
Direct callers:
  - drivers/rapidio/rio.c:rio_route_clr_table
  - drivers/rapidio/rio.c:rio_route_clr_table
  - drivers/rapidio/rio.c:rio_route_get_entry
  - drivers/rapidio/rio.c:rio_unlock_device
  - drivers/rapidio/rio.c:rio_lock_device
  - drivers/rapidio/rio.c:rio_lock_device
  - drivers/rapidio/rio.c:rio_mport_get_feature
  - drivers/rapidio/rio.c:rio_mport_get_feature
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_mport_chk_dev_access
  - drivers/rapidio/rio.c:rio_set_port_lockout
  - drivers/rapidio/rio.c:rio_mport_get_physefb
  - drivers/rapidio/rio.c:rio_mport_get_physefb
  - drivers/rapidio/rio-sysfs.c:rio_read_config
```
**Symbols:**

```
ffffffff81594a40-ffffffff81594ac0: rio_mport_read_config_32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int rio_mport_read_config_32(struct rio_mport *mport, u16 destid, u8 hopcount, u32 offset, u32 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rapidio/rio-access.c (ffffffff815b5cc0)
Location: drivers/rapidio/rio-access.c:114
Inline: False
Direct callers:
  - drivers/rapidio/rio.c:rio_route_clr_table
  - drivers/rapidio/rio.c:rio_route_clr_table
  - drivers/rapidio/rio.c:rio_route_get_entry
  - drivers/rapidio/rio.c:rio_unlock_device
  - drivers/rapidio/rio.c:rio_lock_device
  - drivers/rapidio/rio.c:rio_lock_device
  - drivers/rapidio/rio.c:rio_mport_get_feature
  - drivers/rapidio/rio.c:rio_mport_get_feature
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_mport_chk_dev_access
  - drivers/rapidio/rio.c:rio_set_port_lockout
  - drivers/rapidio/rio.c:rio_mport_get_physefb
  - drivers/rapidio/rio.c:rio_mport_get_physefb
  - drivers/rapidio/rio-sysfs.c:rio_read_config
```
**Symbols:**

```
ffffffff815b5cc0-ffffffff815b5d40: rio_mport_read_config_32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int rio_mport_read_config_32(struct rio_mport *mport, u16 destid, u8 hopcount, u32 offset, u32 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rapidio/rio-access.c (ffffffff8165f950)
Location: drivers/rapidio/rio-access.c:116
Inline: False
Direct callers:
  - drivers/rapidio/rio.c:rio_route_clr_table
  - drivers/rapidio/rio.c:rio_route_clr_table
  - drivers/rapidio/rio.c:rio_route_get_entry
  - drivers/rapidio/rio.c:rio_unlock_device
  - drivers/rapidio/rio.c:rio_lock_device
  - drivers/rapidio/rio.c:rio_lock_device
  - drivers/rapidio/rio.c:rio_mport_get_feature
  - drivers/rapidio/rio.c:rio_mport_get_feature
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_chk_dev_route
  - drivers/rapidio/rio.c:rio_set_port_lockout
  - drivers/rapidio/rio.c:rio_mport_get_physefb
  - drivers/rapidio/rio.c:rio_mport_get_physefb
  - drivers/rapidio/rio-sysfs.c:rio_read_config
```
**Symbols:**

```
ffffffff8165f950-ffffffff8165f9d7: rio_mport_read_config_32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int rio_mport_read_config_32(struct rio_mport *mport, u16 destid, u8 hopcount, u32 offset, u32 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rapidio/rio-access.c (ffffffff81680c10)
Location: drivers/rapidio/rio-access.c:116
Inline: False
Direct callers:
  - drivers/rapidio/rio.c:rio_route_clr_table
  - drivers/rapidio/rio.c:rio_route_clr_table
  - drivers/rapidio/rio.c:rio_route_get_entry
  - drivers/rapidio/rio.c:rio_unlock_device
  - drivers/rapidio/rio.c:rio_lock_device
  - drivers/rapidio/rio.c:rio_lock_device
  - drivers/rapidio/rio.c:rio_mport_get_feature
  - drivers/rapidio/rio.c:rio_mport_get_feature
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_chk_dev_route
  - drivers/rapidio/rio.c:rio_set_port_lockout
  - drivers/rapidio/rio.c:rio_mport_get_physefb
  - drivers/rapidio/rio.c:rio_mport_get_physefb
  - drivers/rapidio/rio-sysfs.c:rio_read_config
```
**Symbols:**

```
ffffffff81680c10-ffffffff81680c97: rio_mport_read_config_32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int rio_mport_read_config_32(struct rio_mport *mport, u16 destid, u8 hopcount, u32 offset, u32 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rapidio/rio-access.c (ffffffff81663a80)
Location: drivers/rapidio/rio-access.c:116
Inline: False
Direct callers:
  - drivers/rapidio/rio.c:rio_route_clr_table
  - drivers/rapidio/rio.c:rio_route_clr_table
  - drivers/rapidio/rio.c:rio_route_get_entry
  - drivers/rapidio/rio.c:rio_unlock_device
  - drivers/rapidio/rio.c:rio_lock_device
  - drivers/rapidio/rio.c:rio_lock_device
  - drivers/rapidio/rio.c:rio_mport_get_feature
  - drivers/rapidio/rio.c:rio_mport_get_feature
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_set_port_lockout
  - drivers/rapidio/rio.c:rio_mport_get_physefb
  - drivers/rapidio/rio.c:rio_mport_get_physefb
  - drivers/rapidio/rio-sysfs.c:rio_read_config
```
**Symbols:**

```
ffffffff81663a80-ffffffff81663b00: rio_mport_read_config_32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int rio_mport_read_config_32(struct rio_mport *mport, u16 destid, u8 hopcount, u32 offset, u32 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rapidio/rio-access.c (ffffffff816d6960)
Location: drivers/rapidio/rio-access.c:116
Inline: False
Direct callers:
  - drivers/rapidio/rio.c:rio_route_clr_table
  - drivers/rapidio/rio.c:rio_route_clr_table
  - drivers/rapidio/rio.c:rio_route_get_entry
  - drivers/rapidio/rio.c:rio_unlock_device
  - drivers/rapidio/rio.c:rio_lock_device
  - drivers/rapidio/rio.c:rio_lock_device
  - drivers/rapidio/rio.c:rio_mport_get_feature
  - drivers/rapidio/rio.c:rio_mport_get_feature
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_set_port_lockout
  - drivers/rapidio/rio.c:rio_mport_get_physefb
  - drivers/rapidio/rio.c:rio_mport_get_physefb
  - drivers/rapidio/rio-sysfs.c:rio_read_config
```
**Symbols:**

```
ffffffff816d6960-ffffffff816d69e0: rio_mport_read_config_32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int rio_mport_read_config_32(struct rio_mport *mport, u16 destid, u8 hopcount, u32 offset, u32 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rapidio/rio-access.c (ffffffff818001b0)
Location: drivers/rapidio/rio-access.c:116
Inline: False
Direct callers:
  - drivers/rapidio/rio.c:rio_route_clr_table
  - drivers/rapidio/rio.c:rio_route_clr_table
  - drivers/rapidio/rio.c:rio_route_get_entry
  - drivers/rapidio/rio.c:rio_unlock_device
  - drivers/rapidio/rio.c:rio_lock_device
  - drivers/rapidio/rio.c:rio_lock_device
  - drivers/rapidio/rio.c:rio_mport_get_feature
  - drivers/rapidio/rio.c:rio_mport_get_feature
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_set_port_lockout
  - drivers/rapidio/rio.c:rio_mport_get_physefb
  - drivers/rapidio/rio.c:rio_mport_get_physefb
  - drivers/rapidio/rio-sysfs.c:rio_read_config
```
**Symbols:**

```
ffffffff818001b0-ffffffff81800245: rio_mport_read_config_32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int rio_mport_read_config_32(struct rio_mport *mport, u16 destid, u8 hopcount, u32 offset, u32 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rapidio/rio-access.c (ffffffff8192d5f0)
Location: drivers/rapidio/rio-access.c:116
Inline: False
Direct callers:
  - drivers/rapidio/rio.c:rio_route_clr_table
  - drivers/rapidio/rio.c:rio_route_clr_table
  - drivers/rapidio/rio.c:rio_route_get_entry
  - drivers/rapidio/rio.c:rio_unlock_device
  - drivers/rapidio/rio.c:rio_lock_device
  - drivers/rapidio/rio.c:rio_lock_device
  - drivers/rapidio/rio.c:rio_mport_get_feature
  - drivers/rapidio/rio.c:rio_mport_get_feature
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_set_port_lockout
  - drivers/rapidio/rio.c:rio_mport_get_physefb
  - drivers/rapidio/rio.c:rio_mport_get_physefb
  - drivers/rapidio/rio-sysfs.c:rio_read_config
```
**Symbols:**

```
ffffffff8192d5f0-ffffffff8192d685: rio_mport_read_config_32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int rio_mport_read_config_32(struct rio_mport *mport, u16 destid, u8 hopcount, u32 offset, u32 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rapidio/rio-access.c (ffffffff81971880)
Location: drivers/rapidio/rio-access.c:116
Inline: False
Direct callers:
  - drivers/rapidio/rio.c:rio_route_clr_table
  - drivers/rapidio/rio.c:rio_route_clr_table
  - drivers/rapidio/rio.c:rio_route_get_entry
  - drivers/rapidio/rio.c:rio_unlock_device
  - drivers/rapidio/rio.c:rio_lock_device
  - drivers/rapidio/rio.c:rio_lock_device
  - drivers/rapidio/rio.c:rio_mport_get_feature
  - drivers/rapidio/rio.c:rio_mport_get_feature
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_set_port_lockout
  - drivers/rapidio/rio.c:rio_mport_get_physefb
  - drivers/rapidio/rio.c:rio_mport_get_physefb
  - drivers/rapidio/rio-sysfs.c:rio_read_config
```
**Symbols:**

```
ffffffff81971880-ffffffff81971915: rio_mport_read_config_32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int rio_mport_read_config_32(struct rio_mport *mport, u16 destid, u8 hopcount, u32 offset, u32 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rapidio/rio-access.c (ffffffff819bb8f0)
Location: drivers/rapidio/rio-access.c:116
Inline: False
Direct callers:
  - drivers/rapidio/rio.c:rio_route_clr_table
  - drivers/rapidio/rio.c:rio_route_clr_table
  - drivers/rapidio/rio.c:rio_route_get_entry
  - drivers/rapidio/rio.c:rio_unlock_device
  - drivers/rapidio/rio.c:rio_lock_device
  - drivers/rapidio/rio.c:rio_lock_device
  - drivers/rapidio/rio.c:rio_mport_get_feature
  - drivers/rapidio/rio.c:rio_mport_get_feature
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_set_port_lockout
  - drivers/rapidio/rio.c:rio_mport_get_physefb
  - drivers/rapidio/rio.c:rio_mport_get_physefb
  - drivers/rapidio/rio-sysfs.c:rio_read_config
```
**Symbols:**

```
ffffffff819bb8f0-ffffffff819bb985: rio_mport_read_config_32 (STB_GLOBAL)
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
int rio_mport_read_config_32(struct rio_mport *mport, u16 destid, u8 hopcount, u32 offset, u32 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rapidio/rio-access.c (ffff80001073e230)
Location: drivers/rapidio/rio-access.c:114
Inline: False
Direct callers:
  - drivers/rapidio/rio.c:rio_route_clr_table
  - drivers/rapidio/rio.c:rio_route_clr_table
  - drivers/rapidio/rio.c:rio_route_get_entry
  - drivers/rapidio/rio.c:rio_lock_device
  - drivers/rapidio/rio.c:rio_lock_device
  - drivers/rapidio/rio.c:rio_mport_get_feature
  - drivers/rapidio/rio.c:rio_mport_get_feature
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_mport_chk_dev_access
  - drivers/rapidio/rio.c:rio_mport_chk_dev_access
  - drivers/rapidio/rio.c:rio_set_port_lockout
  - drivers/rapidio/rio.c:rio_mport_get_physefb
  - drivers/rapidio/rio.c:rio_mport_get_physefb
  - drivers/rapidio/rio-sysfs.c:rio_read_config
```
**Symbols:**

```
ffff80001073e230-ffff80001073e2dc: rio_mport_read_config_32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int rio_mport_read_config_32(struct rio_mport *mport, u16 destid, u8 hopcount, u32 offset, u32 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rapidio/rio-access.c (c08c30ec)
Location: drivers/rapidio/rio-access.c:114
Inline: False
Direct callers:
  - drivers/rapidio/rio.c:rio_route_clr_table
  - drivers/rapidio/rio.c:rio_route_clr_table
  - drivers/rapidio/rio.c:rio_route_get_entry
  - drivers/rapidio/rio.c:rio_lock_device
  - drivers/rapidio/rio.c:rio_lock_device
  - drivers/rapidio/rio.c:rio_mport_get_feature
  - drivers/rapidio/rio.c:rio_mport_get_feature
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_mport_chk_dev_access
  - drivers/rapidio/rio.c:rio_set_port_lockout
  - drivers/rapidio/rio.c:rio_mport_get_physefb
  - drivers/rapidio/rio.c:rio_mport_get_physefb
  - drivers/rapidio/rio-sysfs.c:rio_read_config
```
**Symbols:**

```
c08c30ec-c08c3190: rio_mport_read_config_32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int rio_mport_read_config_32(struct rio_mport *mport, u16 destid, u8 hopcount, u32 offset, u32 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rapidio/rio-access.c (c0000000008978f0)
Location: drivers/rapidio/rio-access.c:114
Inline: False
Direct callers:
  - drivers/rapidio/rio.c:rio_route_clr_table
  - drivers/rapidio/rio.c:rio_route_clr_table
  - drivers/rapidio/rio.c:rio_route_get_entry
  - drivers/rapidio/rio.c:rio_lock_device
  - drivers/rapidio/rio.c:rio_lock_device
  - drivers/rapidio/rio.c:rio_mport_get_feature
  - drivers/rapidio/rio.c:rio_mport_get_feature
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_mport_chk_dev_access
  - drivers/rapidio/rio.c:rio_mport_chk_dev_access
  - drivers/rapidio/rio.c:rio_set_port_lockout
  - drivers/rapidio/rio.c:rio_mport_get_physefb
  - drivers/rapidio/rio.c:rio_mport_get_physefb
  - drivers/rapidio/rio-sysfs.c:rio_read_config
```
**Symbols:**

```
c0000000008978f0-c0000000008979b4: rio_mport_read_config_32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int rio_mport_read_config_32(struct rio_mport *mport, u16 destid, u8 hopcount, u32 offset, u32 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rapidio/rio-access.c (ffffffe0004eda7e)
Location: drivers/rapidio/rio-access.c:114
Inline: False
Direct callers:
  - drivers/rapidio/rio.c:rio_route_clr_table
  - drivers/rapidio/rio.c:rio_route_clr_table
  - drivers/rapidio/rio.c:rio_route_get_entry
  - drivers/rapidio/rio.c:rio_lock_device
  - drivers/rapidio/rio.c:rio_lock_device
  - drivers/rapidio/rio.c:rio_mport_get_feature
  - drivers/rapidio/rio.c:rio_mport_get_feature
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_mport_chk_dev_access
  - drivers/rapidio/rio.c:rio_set_port_lockout
  - drivers/rapidio/rio.c:rio_mport_get_physefb
  - drivers/rapidio/rio.c:rio_mport_get_physefb
  - drivers/rapidio/rio-sysfs.c:rio_read_config
```
**Symbols:**

```
ffffffe0004eda7e-ffffffe0004edae8: rio_mport_read_config_32 (STB_GLOBAL)
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
int rio_mport_read_config_32(struct rio_mport *mport, u16 destid, u8 hopcount, u32 offset, u32 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rapidio/rio-access.c (ffffffff815a9f30)
Location: drivers/rapidio/rio-access.c:114
Inline: False
Direct callers:
  - drivers/rapidio/rio.c:rio_route_clr_table
  - drivers/rapidio/rio.c:rio_route_clr_table
  - drivers/rapidio/rio.c:rio_route_get_entry
  - drivers/rapidio/rio.c:rio_unlock_device
  - drivers/rapidio/rio.c:rio_lock_device
  - drivers/rapidio/rio.c:rio_lock_device
  - drivers/rapidio/rio.c:rio_mport_get_feature
  - drivers/rapidio/rio.c:rio_mport_get_feature
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_mport_chk_dev_access
  - drivers/rapidio/rio.c:rio_set_port_lockout
  - drivers/rapidio/rio.c:rio_mport_get_physefb
  - drivers/rapidio/rio.c:rio_mport_get_physefb
  - drivers/rapidio/rio-sysfs.c:rio_read_config
```
**Symbols:**

```
ffffffff815a9f30-ffffffff815a9fb0: rio_mport_read_config_32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int rio_mport_read_config_32(struct rio_mport *mport, u16 destid, u8 hopcount, u32 offset, u32 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rapidio/rio-access.c (ffffffff815990d0)
Location: drivers/rapidio/rio-access.c:114
Inline: False
Direct callers:
  - drivers/rapidio/rio.c:rio_route_clr_table
  - drivers/rapidio/rio.c:rio_route_clr_table
  - drivers/rapidio/rio.c:rio_route_get_entry
  - drivers/rapidio/rio.c:rio_unlock_device
  - drivers/rapidio/rio.c:rio_lock_device
  - drivers/rapidio/rio.c:rio_lock_device
  - drivers/rapidio/rio.c:rio_mport_get_feature
  - drivers/rapidio/rio.c:rio_mport_get_feature
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_mport_chk_dev_access
  - drivers/rapidio/rio.c:rio_set_port_lockout
  - drivers/rapidio/rio.c:rio_mport_get_physefb
  - drivers/rapidio/rio.c:rio_mport_get_physefb
  - drivers/rapidio/rio-sysfs.c:rio_read_config
```
**Symbols:**

```
ffffffff815990d0-ffffffff81599150: rio_mport_read_config_32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int rio_mport_read_config_32(struct rio_mport *mport, u16 destid, u8 hopcount, u32 offset, u32 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rapidio/rio-access.c (ffffffff815aa4c0)
Location: drivers/rapidio/rio-access.c:114
Inline: False
Direct callers:
  - drivers/rapidio/rio.c:rio_route_clr_table
  - drivers/rapidio/rio.c:rio_route_clr_table
  - drivers/rapidio/rio.c:rio_route_get_entry
  - drivers/rapidio/rio.c:rio_unlock_device
  - drivers/rapidio/rio.c:rio_lock_device
  - drivers/rapidio/rio.c:rio_lock_device
  - drivers/rapidio/rio.c:rio_mport_get_feature
  - drivers/rapidio/rio.c:rio_mport_get_feature
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_mport_chk_dev_access
  - drivers/rapidio/rio.c:rio_set_port_lockout
  - drivers/rapidio/rio.c:rio_mport_get_physefb
  - drivers/rapidio/rio.c:rio_mport_get_physefb
  - drivers/rapidio/rio-sysfs.c:rio_read_config
```
**Symbols:**

```
ffffffff815aa4c0-ffffffff815aa540: rio_mport_read_config_32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int rio_mport_read_config_32(struct rio_mport *mport, u16 destid, u8 hopcount, u32 offset, u32 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rapidio/rio-access.c (ffffffff815c3e50)
Location: drivers/rapidio/rio-access.c:114
Inline: False
Direct callers:
  - drivers/rapidio/rio.c:rio_route_clr_table
  - drivers/rapidio/rio.c:rio_route_clr_table
  - drivers/rapidio/rio.c:rio_route_get_entry
  - drivers/rapidio/rio.c:rio_unlock_device
  - drivers/rapidio/rio.c:rio_lock_device
  - drivers/rapidio/rio.c:rio_lock_device
  - drivers/rapidio/rio.c:rio_mport_get_feature
  - drivers/rapidio/rio.c:rio_mport_get_feature
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_mport_chk_dev_access
  - drivers/rapidio/rio.c:rio_set_port_lockout
  - drivers/rapidio/rio.c:rio_mport_get_physefb
  - drivers/rapidio/rio.c:rio_mport_get_physefb
  - drivers/rapidio/rio-sysfs.c:rio_read_config
```
**Symbols:**

```
ffffffff815c3e50-ffffffff815c3ed0: rio_mport_read_config_32 (STB_GLOBAL)
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
