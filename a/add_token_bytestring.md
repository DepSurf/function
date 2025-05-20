# Function: <code>add_token_bytestring</code>

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
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/sed-opal.c (ffffffff8145c170)
Location: block/sed-opal.c:567
Inline: True
Inline callers:
  - block/sed-opal.c:get_msid_cpin_pin
  - block/sed-opal.c:get_msid_cpin_pin
  - block/sed-opal.c:get_lsp_lifecycle
  - block/sed-opal.c:get_lsp_lifecycle
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:erase_locking_range
  - block/sed-opal.c:erase_locking_range
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:revert_tper
  - block/sed-opal.c:revert_tper
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_generic_opal_session
  - block/sed-opal.c:start_generic_opal_session
  - block/sed-opal.c:start_generic_opal_session
  - block/sed-opal.c:start_generic_opal_session
  - block/sed-opal.c:start_generic_opal_session
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:get_active_key
  - block/sed-opal.c:get_active_key
  - block/sed-opal.c:gen_key
  - block/sed-opal.c:gen_key
Direct callers:
  - block/sed-opal.c:get_msid_cpin_pin
  - block/sed-opal.c:get_msid_cpin_pin
  - block/sed-opal.c:get_lsp_lifecycle
  - block/sed-opal.c:get_lsp_lifecycle
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:erase_locking_range
  - block/sed-opal.c:erase_locking_range
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:revert_tper
  - block/sed-opal.c:revert_tper
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_generic_opal_session
  - block/sed-opal.c:start_generic_opal_session
  - block/sed-opal.c:start_generic_opal_session
  - block/sed-opal.c:start_generic_opal_session
  - block/sed-opal.c:start_generic_opal_session
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:get_active_key
  - block/sed-opal.c:get_active_key
  - block/sed-opal.c:gen_key
  - block/sed-opal.c:gen_key
```
**Symbols:**

```
ffffffff8145b580-ffffffff8145b6ff: add_token_bytestring.part.9 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/sed-opal.c (ffffffff81488300)
Location: block/sed-opal.c:579
Inline: True
Inline callers:
  - block/sed-opal.c:get_msid_cpin_pin
  - block/sed-opal.c:get_msid_cpin_pin
  - block/sed-opal.c:get_lsp_lifecycle
  - block/sed-opal.c:get_lsp_lifecycle
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:erase_locking_range
  - block/sed-opal.c:erase_locking_range
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:revert_tper
  - block/sed-opal.c:revert_tper
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_generic_opal_session
  - block/sed-opal.c:start_generic_opal_session
  - block/sed-opal.c:start_generic_opal_session
  - block/sed-opal.c:start_generic_opal_session
  - block/sed-opal.c:start_generic_opal_session
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:get_active_key
  - block/sed-opal.c:get_active_key
  - block/sed-opal.c:gen_key
  - block/sed-opal.c:gen_key
Direct callers:
  - block/sed-opal.c:get_msid_cpin_pin
  - block/sed-opal.c:get_msid_cpin_pin
  - block/sed-opal.c:get_lsp_lifecycle
  - block/sed-opal.c:get_lsp_lifecycle
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:erase_locking_range
  - block/sed-opal.c:erase_locking_range
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:revert_tper
  - block/sed-opal.c:revert_tper
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_generic_opal_session
  - block/sed-opal.c:start_generic_opal_session
  - block/sed-opal.c:start_generic_opal_session
  - block/sed-opal.c:start_generic_opal_session
  - block/sed-opal.c:start_generic_opal_session
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:get_active_key
  - block/sed-opal.c:get_active_key
  - block/sed-opal.c:gen_key
  - block/sed-opal.c:gen_key
```
**Symbols:**

```
ffffffff81487360-ffffffff814874df: add_token_bytestring.part.9 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/sed-opal.c (ffffffff814bd1cc)
Location: block/sed-opal.c:576
Inline: True
Inline callers:
  - block/sed-opal.c:get_msid_cpin_pin
  - block/sed-opal.c:get_msid_cpin_pin
  - block/sed-opal.c:get_lsp_lifecycle
  - block/sed-opal.c:get_lsp_lifecycle
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:erase_locking_range
  - block/sed-opal.c:erase_locking_range
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:revert_tper
  - block/sed-opal.c:revert_tper
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_generic_opal_session
  - block/sed-opal.c:start_generic_opal_session
  - block/sed-opal.c:start_generic_opal_session
  - block/sed-opal.c:start_generic_opal_session
  - block/sed-opal.c:start_generic_opal_session
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:get_active_key
  - block/sed-opal.c:get_active_key
  - block/sed-opal.c:gen_key
  - block/sed-opal.c:gen_key
Direct callers:
  - block/sed-opal.c:get_msid_cpin_pin
  - block/sed-opal.c:get_msid_cpin_pin
  - block/sed-opal.c:get_lsp_lifecycle
  - block/sed-opal.c:get_lsp_lifecycle
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:erase_locking_range
  - block/sed-opal.c:erase_locking_range
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:revert_tper
  - block/sed-opal.c:revert_tper
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_generic_opal_session
  - block/sed-opal.c:start_generic_opal_session
  - block/sed-opal.c:start_generic_opal_session
  - block/sed-opal.c:start_generic_opal_session
  - block/sed-opal.c:start_generic_opal_session
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:get_active_key
  - block/sed-opal.c:get_active_key
  - block/sed-opal.c:gen_key
  - block/sed-opal.c:gen_key
```
**Symbols:**

```
ffffffff814bc2c0-ffffffff814bc435: add_token_bytestring.part.10 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/sed-opal.c (ffffffff814d173c)
Location: block/sed-opal.c:576
Inline: True
Inline callers:
  - block/sed-opal.c:get_msid_cpin_pin
  - block/sed-opal.c:get_msid_cpin_pin
  - block/sed-opal.c:get_lsp_lifecycle
  - block/sed-opal.c:get_lsp_lifecycle
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:erase_locking_range
  - block/sed-opal.c:erase_locking_range
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:revert_tper
  - block/sed-opal.c:revert_tper
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_generic_opal_session
  - block/sed-opal.c:start_generic_opal_session
  - block/sed-opal.c:start_generic_opal_session
  - block/sed-opal.c:start_generic_opal_session
  - block/sed-opal.c:start_generic_opal_session
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:get_active_key
  - block/sed-opal.c:get_active_key
  - block/sed-opal.c:gen_key
  - block/sed-opal.c:gen_key
Direct callers:
  - block/sed-opal.c:get_msid_cpin_pin
  - block/sed-opal.c:get_msid_cpin_pin
  - block/sed-opal.c:get_lsp_lifecycle
  - block/sed-opal.c:get_lsp_lifecycle
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:erase_locking_range
  - block/sed-opal.c:erase_locking_range
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:revert_tper
  - block/sed-opal.c:revert_tper
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_generic_opal_session
  - block/sed-opal.c:start_generic_opal_session
  - block/sed-opal.c:start_generic_opal_session
  - block/sed-opal.c:start_generic_opal_session
  - block/sed-opal.c:start_generic_opal_session
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:get_active_key
  - block/sed-opal.c:get_active_key
  - block/sed-opal.c:gen_key
  - block/sed-opal.c:gen_key
```
**Symbols:**

```
ffffffff814d0830-ffffffff814d09a5: add_token_bytestring.part.11 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void add_token_bytestring(int *err, struct opal_dev *cmd, const u8 *bytestring, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff814fef90)
Location: block/sed-opal.c:629
Inline: False
Direct callers:
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:cmd_start
  - block/sed-opal.c:cmd_start
```
**Symbols:**

```
ffffffff814fef90-ffffffff814fefcd: add_token_bytestring (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void add_token_bytestring(int *err, struct opal_dev *cmd, const u8 *bytestring, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff8151cee0)
Location: block/sed-opal.c:630
Inline: False
Direct callers:
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:cmd_start
  - block/sed-opal.c:cmd_start
```
**Symbols:**

```
ffffffff8151cee0-ffffffff8151cf1d: add_token_bytestring (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void add_token_bytestring(int *err, struct opal_dev *cmd, const u8 *bytestring, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff8157d490)
Location: block/sed-opal.c:632
Inline: False
Direct callers:
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:cmd_start
  - block/sed-opal.c:cmd_start
```
**Symbols:**

```
ffffffff8157d490-ffffffff8157d529: add_token_bytestring (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void add_token_bytestring(int *err, struct opal_dev *cmd, const u8 *bytestring, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff8159a4d0)
Location: block/sed-opal.c:632
Inline: False
Direct callers:
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:cmd_start
  - block/sed-opal.c:cmd_start
```
**Symbols:**

```
ffffffff8159a4d0-ffffffff8159a569: add_token_bytestring (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void add_token_bytestring(int *err, struct opal_dev *cmd, const u8 *bytestring, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff815a0fc0)
Location: block/sed-opal.c:632
Inline: False
Direct callers:
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:cmd_start
  - block/sed-opal.c:cmd_start
```
**Symbols:**

```
ffffffff815a0fc0-ffffffff815a1059: add_token_bytestring (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void add_token_bytestring(int *err, struct opal_dev *cmd, const u8 *bytestring, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff81609a20)
Location: block/sed-opal.c:632
Inline: False
Direct callers:
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:cmd_start
  - block/sed-opal.c:cmd_start
```
**Symbols:**

```
ffffffff81609a20-ffffffff81609ab9: add_token_bytestring (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void add_token_bytestring(int *err, struct opal_dev *cmd, const u8 *bytestring, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff816bdbc0)
Location: block/sed-opal.c:632
Inline: False
Direct callers:
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_generic_opal_session
  - block/sed-opal.c:start_generic_opal_session
  - block/sed-opal.c:start_generic_opal_session
  - block/sed-opal.c:cmd_start
  - block/sed-opal.c:cmd_start
```
**Symbols:**

```
ffffffff816bdbc0-ffffffff816bdc67: add_token_bytestring (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void add_token_bytestring(int *err, struct opal_dev *cmd, const u8 *bytestring, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff8177e8f0)
Location: block/sed-opal.c:672
Inline: False
Direct callers:
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_generic_opal_session
  - block/sed-opal.c:start_generic_opal_session
  - block/sed-opal.c:start_generic_opal_session
  - block/sed-opal.c:cmd_start
  - block/sed-opal.c:cmd_start
```
**Symbols:**

```
ffffffff8177e8f0-ffffffff8177e997: add_token_bytestring (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void add_token_bytestring(int *err, struct opal_dev *cmd, const u8 *bytestring, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff817be0d0)
Location: block/sed-opal.c:680
Inline: False
Direct callers:
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:set_lr_boolean_ace
  - block/sed-opal.c:set_lr_boolean_ace
  - block/sed-opal.c:set_lr_boolean_ace
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_generic_opal_session
  - block/sed-opal.c:start_generic_opal_session
  - block/sed-opal.c:start_generic_opal_session
  - block/sed-opal.c:cmd_start
  - block/sed-opal.c:cmd_start
```
**Symbols:**

```
ffffffff817be0d0-ffffffff817be177: add_token_bytestring (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void add_token_bytestring(int *err, struct opal_dev *cmd, const u8 *bytestring, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff81802d90)
Location: block/sed-opal.c:793
Inline: False
Direct callers:
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:set_lr_boolean_ace
  - block/sed-opal.c:set_lr_boolean_ace
  - block/sed-opal.c:set_lr_boolean_ace
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_generic_opal_session
  - block/sed-opal.c:start_generic_opal_session
  - block/sed-opal.c:start_generic_opal_session
  - block/sed-opal.c:cmd_start
  - block/sed-opal.c:cmd_start
```
**Symbols:**

```
ffffffff81802d90-ffffffff81802e37: add_token_bytestring (STB_LOCAL)
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
void add_token_bytestring(int *err, struct opal_dev *cmd, const u8 *bytestring, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffff800010625ad0)
Location: block/sed-opal.c:630
Inline: False
Direct callers:
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:cmd_start
  - block/sed-opal.c:cmd_start
```
**Symbols:**

```
ffff800010625ad0-ffff800010625b34: add_token_bytestring (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void add_token_bytestring(int *err, struct opal_dev *cmd, const u8 *bytestring, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (c07cd56c)
Location: block/sed-opal.c:630
Inline: False
Direct callers:
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:cmd_start
  - block/sed-opal.c:cmd_start
```
**Symbols:**

```
c07cd56c-c07cd5b8: add_token_bytestring (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void add_token_bytestring(int *err, struct opal_dev *cmd, const u8 *bytestring, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (c0000000007c69f0)
Location: block/sed-opal.c:630
Inline: False
Direct callers:
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_generic_opal_session
  - block/sed-opal.c:start_generic_opal_session
  - block/sed-opal.c:start_generic_opal_session
  - block/sed-opal.c:start_generic_opal_session
  - block/sed-opal.c:cmd_start
  - block/sed-opal.c:cmd_start
```
**Symbols:**

```
c0000000007c69f0-c0000000007c6a6c: add_token_bytestring (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void add_token_bytestring(int *err, struct opal_dev *cmd, const u8 *bytestring, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffe000456ce8)
Location: block/sed-opal.c:630
Inline: False
Direct callers:
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_generic_opal_session
  - block/sed-opal.c:start_generic_opal_session
  - block/sed-opal.c:start_generic_opal_session
  - block/sed-opal.c:start_generic_opal_session
  - block/sed-opal.c:cmd_start
  - block/sed-opal.c:cmd_start
```
**Symbols:**

```
ffffffe000456ce8-ffffffe000456d3e: add_token_bytestring (STB_LOCAL)
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
void add_token_bytestring(int *err, struct opal_dev *cmd, const u8 *bytestring, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff815154c0)
Location: block/sed-opal.c:630
Inline: False
Direct callers:
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:cmd_start
  - block/sed-opal.c:cmd_start
```
**Symbols:**

```
ffffffff815154c0-ffffffff815154fd: add_token_bytestring (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void add_token_bytestring(int *err, struct opal_dev *cmd, const u8 *bytestring, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff815057d0)
Location: block/sed-opal.c:630
Inline: False
Direct callers:
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:cmd_start
  - block/sed-opal.c:cmd_start
```
**Symbols:**

```
ffffffff815057d0-ffffffff8150580d: add_token_bytestring (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void add_token_bytestring(int *err, struct opal_dev *cmd, const u8 *bytestring, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff81511550)
Location: block/sed-opal.c:630
Inline: False
Direct callers:
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:cmd_start
  - block/sed-opal.c:cmd_start
```
**Symbols:**

```
ffffffff81511550-ffffffff8151158d: add_token_bytestring (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void add_token_bytestring(int *err, struct opal_dev *cmd, const u8 *bytestring, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff8152ad10)
Location: block/sed-opal.c:630
Inline: False
Direct callers:
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:cmd_start
  - block/sed-opal.c:cmd_start
```
**Symbols:**

```
ffffffff8152ad10-ffffffff8152ad4d: add_token_bytestring (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
