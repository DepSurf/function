# Function: <code>add_token_u8</code>

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
In block/sed-opal.c (ffffffff8145c132)
Location: block/sed-opal.c:501
Inline: True
Inline callers:
  - block/sed-opal.c:get_msid_cpin_pin
  - block/sed-opal.c:get_msid_cpin_pin
  - block/sed-opal.c:get_msid_cpin_pin
  - block/sed-opal.c:get_msid_cpin_pin
  - block/sed-opal.c:get_msid_cpin_pin
  - block/sed-opal.c:get_msid_cpin_pin
  - block/sed-opal.c:get_msid_cpin_pin
  - block/sed-opal.c:get_msid_cpin_pin
  - block/sed-opal.c:get_msid_cpin_pin
  - block/sed-opal.c:get_msid_cpin_pin
  - block/sed-opal.c:get_msid_cpin_pin
  - block/sed-opal.c:get_msid_cpin_pin
  - block/sed-opal.c:get_msid_cpin_pin
  - block/sed-opal.c:get_lsp_lifecycle
  - block/sed-opal.c:get_lsp_lifecycle
  - block/sed-opal.c:get_lsp_lifecycle
  - block/sed-opal.c:get_lsp_lifecycle
  - block/sed-opal.c:get_lsp_lifecycle
  - block/sed-opal.c:get_lsp_lifecycle
  - block/sed-opal.c:get_lsp_lifecycle
  - block/sed-opal.c:get_lsp_lifecycle
  - block/sed-opal.c:get_lsp_lifecycle
  - block/sed-opal.c:get_lsp_lifecycle
  - block/sed-opal.c:get_lsp_lifecycle
  - block/sed-opal.c:get_lsp_lifecycle
  - block/sed-opal.c:get_lsp_lifecycle
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
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
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:erase_locking_range
  - block/sed-opal.c:erase_locking_range
  - block/sed-opal.c:erase_locking_range
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:revert_tper
  - block/sed-opal.c:revert_tper
  - block/sed-opal.c:revert_tper
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
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
  - block/sed-opal.c:start_generic_opal_session
  - block/sed-opal.c:start_generic_opal_session
  - block/sed-opal.c:start_generic_opal_session
  - block/sed-opal.c:start_generic_opal_session
  - block/sed-opal.c:start_generic_opal_session
  - block/sed-opal.c:start_generic_opal_session
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:get_active_key
  - block/sed-opal.c:get_active_key
  - block/sed-opal.c:get_active_key
  - block/sed-opal.c:get_active_key
  - block/sed-opal.c:get_active_key
  - block/sed-opal.c:get_active_key
  - block/sed-opal.c:get_active_key
  - block/sed-opal.c:get_active_key
  - block/sed-opal.c:get_active_key
  - block/sed-opal.c:get_active_key
  - block/sed-opal.c:get_active_key
  - block/sed-opal.c:get_active_key
  - block/sed-opal.c:get_active_key
  - block/sed-opal.c:gen_key
  - block/sed-opal.c:gen_key
  - block/sed-opal.c:gen_key
  - block/sed-opal.c:finalize_and_send
  - block/sed-opal.c:finalize_and_send
  - block/sed-opal.c:finalize_and_send
  - block/sed-opal.c:finalize_and_send
  - block/sed-opal.c:finalize_and_send
  - block/sed-opal.c:finalize_and_send
Direct callers:
  - block/sed-opal.c:get_msid_cpin_pin
  - block/sed-opal.c:get_msid_cpin_pin
  - block/sed-opal.c:get_msid_cpin_pin
  - block/sed-opal.c:get_msid_cpin_pin
  - block/sed-opal.c:get_msid_cpin_pin
  - block/sed-opal.c:get_msid_cpin_pin
  - block/sed-opal.c:get_msid_cpin_pin
  - block/sed-opal.c:get_msid_cpin_pin
  - block/sed-opal.c:get_msid_cpin_pin
  - block/sed-opal.c:get_msid_cpin_pin
  - block/sed-opal.c:get_msid_cpin_pin
  - block/sed-opal.c:get_msid_cpin_pin
  - block/sed-opal.c:get_msid_cpin_pin
  - block/sed-opal.c:get_lsp_lifecycle
  - block/sed-opal.c:get_lsp_lifecycle
  - block/sed-opal.c:get_lsp_lifecycle
  - block/sed-opal.c:get_lsp_lifecycle
  - block/sed-opal.c:get_lsp_lifecycle
  - block/sed-opal.c:get_lsp_lifecycle
  - block/sed-opal.c:get_lsp_lifecycle
  - block/sed-opal.c:get_lsp_lifecycle
  - block/sed-opal.c:get_lsp_lifecycle
  - block/sed-opal.c:get_lsp_lifecycle
  - block/sed-opal.c:get_lsp_lifecycle
  - block/sed-opal.c:get_lsp_lifecycle
  - block/sed-opal.c:get_lsp_lifecycle
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
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
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:erase_locking_range
  - block/sed-opal.c:erase_locking_range
  - block/sed-opal.c:erase_locking_range
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:revert_tper
  - block/sed-opal.c:revert_tper
  - block/sed-opal.c:revert_tper
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
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
  - block/sed-opal.c:start_generic_opal_session
  - block/sed-opal.c:start_generic_opal_session
  - block/sed-opal.c:start_generic_opal_session
  - block/sed-opal.c:start_generic_opal_session
  - block/sed-opal.c:start_generic_opal_session
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:get_active_key
  - block/sed-opal.c:get_active_key
  - block/sed-opal.c:get_active_key
  - block/sed-opal.c:get_active_key
  - block/sed-opal.c:get_active_key
  - block/sed-opal.c:get_active_key
  - block/sed-opal.c:get_active_key
  - block/sed-opal.c:get_active_key
  - block/sed-opal.c:get_active_key
  - block/sed-opal.c:get_active_key
  - block/sed-opal.c:get_active_key
  - block/sed-opal.c:get_active_key
  - block/sed-opal.c:get_active_key
  - block/sed-opal.c:gen_key
  - block/sed-opal.c:gen_key
  - block/sed-opal.c:gen_key
  - block/sed-opal.c:finalize_and_send
  - block/sed-opal.c:finalize_and_send
  - block/sed-opal.c:finalize_and_send
  - block/sed-opal.c:finalize_and_send
  - block/sed-opal.c:finalize_and_send
  - block/sed-opal.c:finalize_and_send
```
**Symbols:**

```
ffffffff8145b180-ffffffff8145b1b7: add_token_u8.part.7 (STB_LOCAL)
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
In block/sed-opal.c (ffffffff814882c2)
Location: block/sed-opal.c:513
Inline: True
Inline callers:
  - block/sed-opal.c:get_msid_cpin_pin
  - block/sed-opal.c:get_msid_cpin_pin
  - block/sed-opal.c:get_msid_cpin_pin
  - block/sed-opal.c:get_msid_cpin_pin
  - block/sed-opal.c:get_msid_cpin_pin
  - block/sed-opal.c:get_msid_cpin_pin
  - block/sed-opal.c:get_msid_cpin_pin
  - block/sed-opal.c:get_msid_cpin_pin
  - block/sed-opal.c:get_msid_cpin_pin
  - block/sed-opal.c:get_msid_cpin_pin
  - block/sed-opal.c:get_msid_cpin_pin
  - block/sed-opal.c:get_msid_cpin_pin
  - block/sed-opal.c:get_msid_cpin_pin
  - block/sed-opal.c:get_lsp_lifecycle
  - block/sed-opal.c:get_lsp_lifecycle
  - block/sed-opal.c:get_lsp_lifecycle
  - block/sed-opal.c:get_lsp_lifecycle
  - block/sed-opal.c:get_lsp_lifecycle
  - block/sed-opal.c:get_lsp_lifecycle
  - block/sed-opal.c:get_lsp_lifecycle
  - block/sed-opal.c:get_lsp_lifecycle
  - block/sed-opal.c:get_lsp_lifecycle
  - block/sed-opal.c:get_lsp_lifecycle
  - block/sed-opal.c:get_lsp_lifecycle
  - block/sed-opal.c:get_lsp_lifecycle
  - block/sed-opal.c:get_lsp_lifecycle
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
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
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:erase_locking_range
  - block/sed-opal.c:erase_locking_range
  - block/sed-opal.c:erase_locking_range
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:revert_tper
  - block/sed-opal.c:revert_tper
  - block/sed-opal.c:revert_tper
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
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
  - block/sed-opal.c:start_generic_opal_session
  - block/sed-opal.c:start_generic_opal_session
  - block/sed-opal.c:start_generic_opal_session
  - block/sed-opal.c:start_generic_opal_session
  - block/sed-opal.c:start_generic_opal_session
  - block/sed-opal.c:start_generic_opal_session
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:get_active_key
  - block/sed-opal.c:get_active_key
  - block/sed-opal.c:get_active_key
  - block/sed-opal.c:get_active_key
  - block/sed-opal.c:get_active_key
  - block/sed-opal.c:get_active_key
  - block/sed-opal.c:get_active_key
  - block/sed-opal.c:get_active_key
  - block/sed-opal.c:get_active_key
  - block/sed-opal.c:get_active_key
  - block/sed-opal.c:get_active_key
  - block/sed-opal.c:get_active_key
  - block/sed-opal.c:get_active_key
  - block/sed-opal.c:gen_key
  - block/sed-opal.c:gen_key
  - block/sed-opal.c:gen_key
  - block/sed-opal.c:finalize_and_send
  - block/sed-opal.c:finalize_and_send
  - block/sed-opal.c:finalize_and_send
  - block/sed-opal.c:finalize_and_send
  - block/sed-opal.c:finalize_and_send
  - block/sed-opal.c:finalize_and_send
Direct callers:
  - block/sed-opal.c:get_msid_cpin_pin
  - block/sed-opal.c:get_msid_cpin_pin
  - block/sed-opal.c:get_msid_cpin_pin
  - block/sed-opal.c:get_msid_cpin_pin
  - block/sed-opal.c:get_msid_cpin_pin
  - block/sed-opal.c:get_msid_cpin_pin
  - block/sed-opal.c:get_msid_cpin_pin
  - block/sed-opal.c:get_msid_cpin_pin
  - block/sed-opal.c:get_msid_cpin_pin
  - block/sed-opal.c:get_msid_cpin_pin
  - block/sed-opal.c:get_msid_cpin_pin
  - block/sed-opal.c:get_msid_cpin_pin
  - block/sed-opal.c:get_msid_cpin_pin
  - block/sed-opal.c:get_lsp_lifecycle
  - block/sed-opal.c:get_lsp_lifecycle
  - block/sed-opal.c:get_lsp_lifecycle
  - block/sed-opal.c:get_lsp_lifecycle
  - block/sed-opal.c:get_lsp_lifecycle
  - block/sed-opal.c:get_lsp_lifecycle
  - block/sed-opal.c:get_lsp_lifecycle
  - block/sed-opal.c:get_lsp_lifecycle
  - block/sed-opal.c:get_lsp_lifecycle
  - block/sed-opal.c:get_lsp_lifecycle
  - block/sed-opal.c:get_lsp_lifecycle
  - block/sed-opal.c:get_lsp_lifecycle
  - block/sed-opal.c:get_lsp_lifecycle
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
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
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:erase_locking_range
  - block/sed-opal.c:erase_locking_range
  - block/sed-opal.c:erase_locking_range
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:revert_tper
  - block/sed-opal.c:revert_tper
  - block/sed-opal.c:revert_tper
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
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
  - block/sed-opal.c:start_generic_opal_session
  - block/sed-opal.c:start_generic_opal_session
  - block/sed-opal.c:start_generic_opal_session
  - block/sed-opal.c:start_generic_opal_session
  - block/sed-opal.c:start_generic_opal_session
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:get_active_key
  - block/sed-opal.c:get_active_key
  - block/sed-opal.c:get_active_key
  - block/sed-opal.c:get_active_key
  - block/sed-opal.c:get_active_key
  - block/sed-opal.c:get_active_key
  - block/sed-opal.c:get_active_key
  - block/sed-opal.c:get_active_key
  - block/sed-opal.c:get_active_key
  - block/sed-opal.c:get_active_key
  - block/sed-opal.c:get_active_key
  - block/sed-opal.c:get_active_key
  - block/sed-opal.c:get_active_key
  - block/sed-opal.c:gen_key
  - block/sed-opal.c:gen_key
  - block/sed-opal.c:gen_key
  - block/sed-opal.c:finalize_and_send
  - block/sed-opal.c:finalize_and_send
  - block/sed-opal.c:finalize_and_send
  - block/sed-opal.c:finalize_and_send
  - block/sed-opal.c:finalize_and_send
  - block/sed-opal.c:finalize_and_send
```
**Symbols:**

```
ffffffff81486f50-ffffffff81486f87: add_token_u8.part.7 (STB_LOCAL)
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
In block/sed-opal.c (ffffffff814bd1a3)
Location: block/sed-opal.c:513
Inline: True
Inline callers:
  - block/sed-opal.c:get_msid_cpin_pin
  - block/sed-opal.c:get_msid_cpin_pin
  - block/sed-opal.c:get_msid_cpin_pin
  - block/sed-opal.c:get_msid_cpin_pin
  - block/sed-opal.c:get_msid_cpin_pin
  - block/sed-opal.c:get_msid_cpin_pin
  - block/sed-opal.c:get_msid_cpin_pin
  - block/sed-opal.c:get_msid_cpin_pin
  - block/sed-opal.c:get_msid_cpin_pin
  - block/sed-opal.c:get_msid_cpin_pin
  - block/sed-opal.c:get_msid_cpin_pin
  - block/sed-opal.c:get_msid_cpin_pin
  - block/sed-opal.c:get_msid_cpin_pin
  - block/sed-opal.c:get_lsp_lifecycle
  - block/sed-opal.c:get_lsp_lifecycle
  - block/sed-opal.c:get_lsp_lifecycle
  - block/sed-opal.c:get_lsp_lifecycle
  - block/sed-opal.c:get_lsp_lifecycle
  - block/sed-opal.c:get_lsp_lifecycle
  - block/sed-opal.c:get_lsp_lifecycle
  - block/sed-opal.c:get_lsp_lifecycle
  - block/sed-opal.c:get_lsp_lifecycle
  - block/sed-opal.c:get_lsp_lifecycle
  - block/sed-opal.c:get_lsp_lifecycle
  - block/sed-opal.c:get_lsp_lifecycle
  - block/sed-opal.c:get_lsp_lifecycle
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
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
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:erase_locking_range
  - block/sed-opal.c:erase_locking_range
  - block/sed-opal.c:erase_locking_range
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:revert_tper
  - block/sed-opal.c:revert_tper
  - block/sed-opal.c:revert_tper
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
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
  - block/sed-opal.c:start_generic_opal_session
  - block/sed-opal.c:start_generic_opal_session
  - block/sed-opal.c:start_generic_opal_session
  - block/sed-opal.c:start_generic_opal_session
  - block/sed-opal.c:start_generic_opal_session
  - block/sed-opal.c:start_generic_opal_session
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:get_active_key
  - block/sed-opal.c:get_active_key
  - block/sed-opal.c:get_active_key
  - block/sed-opal.c:get_active_key
  - block/sed-opal.c:get_active_key
  - block/sed-opal.c:get_active_key
  - block/sed-opal.c:get_active_key
  - block/sed-opal.c:get_active_key
  - block/sed-opal.c:get_active_key
  - block/sed-opal.c:get_active_key
  - block/sed-opal.c:get_active_key
  - block/sed-opal.c:get_active_key
  - block/sed-opal.c:get_active_key
  - block/sed-opal.c:gen_key
  - block/sed-opal.c:gen_key
  - block/sed-opal.c:gen_key
  - block/sed-opal.c:finalize_and_send
  - block/sed-opal.c:finalize_and_send
  - block/sed-opal.c:finalize_and_send
  - block/sed-opal.c:finalize_and_send
  - block/sed-opal.c:finalize_and_send
  - block/sed-opal.c:finalize_and_send
Direct callers:
  - block/sed-opal.c:get_msid_cpin_pin
  - block/sed-opal.c:get_msid_cpin_pin
  - block/sed-opal.c:get_msid_cpin_pin
  - block/sed-opal.c:get_msid_cpin_pin
  - block/sed-opal.c:get_msid_cpin_pin
  - block/sed-opal.c:get_msid_cpin_pin
  - block/sed-opal.c:get_msid_cpin_pin
  - block/sed-opal.c:get_msid_cpin_pin
  - block/sed-opal.c:get_msid_cpin_pin
  - block/sed-opal.c:get_msid_cpin_pin
  - block/sed-opal.c:get_msid_cpin_pin
  - block/sed-opal.c:get_msid_cpin_pin
  - block/sed-opal.c:get_msid_cpin_pin
  - block/sed-opal.c:get_lsp_lifecycle
  - block/sed-opal.c:get_lsp_lifecycle
  - block/sed-opal.c:get_lsp_lifecycle
  - block/sed-opal.c:get_lsp_lifecycle
  - block/sed-opal.c:get_lsp_lifecycle
  - block/sed-opal.c:get_lsp_lifecycle
  - block/sed-opal.c:get_lsp_lifecycle
  - block/sed-opal.c:get_lsp_lifecycle
  - block/sed-opal.c:get_lsp_lifecycle
  - block/sed-opal.c:get_lsp_lifecycle
  - block/sed-opal.c:get_lsp_lifecycle
  - block/sed-opal.c:get_lsp_lifecycle
  - block/sed-opal.c:get_lsp_lifecycle
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
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
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:erase_locking_range
  - block/sed-opal.c:erase_locking_range
  - block/sed-opal.c:erase_locking_range
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:revert_tper
  - block/sed-opal.c:revert_tper
  - block/sed-opal.c:revert_tper
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
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
  - block/sed-opal.c:start_generic_opal_session
  - block/sed-opal.c:start_generic_opal_session
  - block/sed-opal.c:start_generic_opal_session
  - block/sed-opal.c:start_generic_opal_session
  - block/sed-opal.c:start_generic_opal_session
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:get_active_key
  - block/sed-opal.c:get_active_key
  - block/sed-opal.c:get_active_key
  - block/sed-opal.c:get_active_key
  - block/sed-opal.c:get_active_key
  - block/sed-opal.c:get_active_key
  - block/sed-opal.c:get_active_key
  - block/sed-opal.c:get_active_key
  - block/sed-opal.c:get_active_key
  - block/sed-opal.c:get_active_key
  - block/sed-opal.c:get_active_key
  - block/sed-opal.c:get_active_key
  - block/sed-opal.c:get_active_key
  - block/sed-opal.c:gen_key
  - block/sed-opal.c:gen_key
  - block/sed-opal.c:gen_key
  - block/sed-opal.c:finalize_and_send
  - block/sed-opal.c:finalize_and_send
  - block/sed-opal.c:finalize_and_send
  - block/sed-opal.c:finalize_and_send
  - block/sed-opal.c:finalize_and_send
  - block/sed-opal.c:finalize_and_send
```
**Symbols:**

```
ffffffff814bbea0-ffffffff814bbed7: add_token_u8.part.8 (STB_LOCAL)
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
In block/sed-opal.c (ffffffff814d1713)
Location: block/sed-opal.c:513
Inline: True
Inline callers:
  - block/sed-opal.c:get_msid_cpin_pin
  - block/sed-opal.c:get_msid_cpin_pin
  - block/sed-opal.c:get_msid_cpin_pin
  - block/sed-opal.c:get_msid_cpin_pin
  - block/sed-opal.c:get_msid_cpin_pin
  - block/sed-opal.c:get_msid_cpin_pin
  - block/sed-opal.c:get_msid_cpin_pin
  - block/sed-opal.c:get_msid_cpin_pin
  - block/sed-opal.c:get_msid_cpin_pin
  - block/sed-opal.c:get_msid_cpin_pin
  - block/sed-opal.c:get_msid_cpin_pin
  - block/sed-opal.c:get_msid_cpin_pin
  - block/sed-opal.c:get_msid_cpin_pin
  - block/sed-opal.c:get_lsp_lifecycle
  - block/sed-opal.c:get_lsp_lifecycle
  - block/sed-opal.c:get_lsp_lifecycle
  - block/sed-opal.c:get_lsp_lifecycle
  - block/sed-opal.c:get_lsp_lifecycle
  - block/sed-opal.c:get_lsp_lifecycle
  - block/sed-opal.c:get_lsp_lifecycle
  - block/sed-opal.c:get_lsp_lifecycle
  - block/sed-opal.c:get_lsp_lifecycle
  - block/sed-opal.c:get_lsp_lifecycle
  - block/sed-opal.c:get_lsp_lifecycle
  - block/sed-opal.c:get_lsp_lifecycle
  - block/sed-opal.c:get_lsp_lifecycle
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
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
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:erase_locking_range
  - block/sed-opal.c:erase_locking_range
  - block/sed-opal.c:erase_locking_range
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:revert_tper
  - block/sed-opal.c:revert_tper
  - block/sed-opal.c:revert_tper
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
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
  - block/sed-opal.c:start_generic_opal_session
  - block/sed-opal.c:start_generic_opal_session
  - block/sed-opal.c:start_generic_opal_session
  - block/sed-opal.c:start_generic_opal_session
  - block/sed-opal.c:start_generic_opal_session
  - block/sed-opal.c:start_generic_opal_session
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:get_active_key
  - block/sed-opal.c:get_active_key
  - block/sed-opal.c:get_active_key
  - block/sed-opal.c:get_active_key
  - block/sed-opal.c:get_active_key
  - block/sed-opal.c:get_active_key
  - block/sed-opal.c:get_active_key
  - block/sed-opal.c:get_active_key
  - block/sed-opal.c:get_active_key
  - block/sed-opal.c:get_active_key
  - block/sed-opal.c:get_active_key
  - block/sed-opal.c:get_active_key
  - block/sed-opal.c:get_active_key
  - block/sed-opal.c:gen_key
  - block/sed-opal.c:gen_key
  - block/sed-opal.c:gen_key
  - block/sed-opal.c:finalize_and_send
  - block/sed-opal.c:finalize_and_send
  - block/sed-opal.c:finalize_and_send
  - block/sed-opal.c:finalize_and_send
  - block/sed-opal.c:finalize_and_send
  - block/sed-opal.c:finalize_and_send
Direct callers:
  - block/sed-opal.c:get_msid_cpin_pin
  - block/sed-opal.c:get_msid_cpin_pin
  - block/sed-opal.c:get_msid_cpin_pin
  - block/sed-opal.c:get_msid_cpin_pin
  - block/sed-opal.c:get_msid_cpin_pin
  - block/sed-opal.c:get_msid_cpin_pin
  - block/sed-opal.c:get_msid_cpin_pin
  - block/sed-opal.c:get_msid_cpin_pin
  - block/sed-opal.c:get_msid_cpin_pin
  - block/sed-opal.c:get_msid_cpin_pin
  - block/sed-opal.c:get_msid_cpin_pin
  - block/sed-opal.c:get_msid_cpin_pin
  - block/sed-opal.c:get_msid_cpin_pin
  - block/sed-opal.c:get_lsp_lifecycle
  - block/sed-opal.c:get_lsp_lifecycle
  - block/sed-opal.c:get_lsp_lifecycle
  - block/sed-opal.c:get_lsp_lifecycle
  - block/sed-opal.c:get_lsp_lifecycle
  - block/sed-opal.c:get_lsp_lifecycle
  - block/sed-opal.c:get_lsp_lifecycle
  - block/sed-opal.c:get_lsp_lifecycle
  - block/sed-opal.c:get_lsp_lifecycle
  - block/sed-opal.c:get_lsp_lifecycle
  - block/sed-opal.c:get_lsp_lifecycle
  - block/sed-opal.c:get_lsp_lifecycle
  - block/sed-opal.c:get_lsp_lifecycle
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
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
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:erase_locking_range
  - block/sed-opal.c:erase_locking_range
  - block/sed-opal.c:erase_locking_range
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:revert_tper
  - block/sed-opal.c:revert_tper
  - block/sed-opal.c:revert_tper
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
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
  - block/sed-opal.c:start_generic_opal_session
  - block/sed-opal.c:start_generic_opal_session
  - block/sed-opal.c:start_generic_opal_session
  - block/sed-opal.c:start_generic_opal_session
  - block/sed-opal.c:start_generic_opal_session
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:get_active_key
  - block/sed-opal.c:get_active_key
  - block/sed-opal.c:get_active_key
  - block/sed-opal.c:get_active_key
  - block/sed-opal.c:get_active_key
  - block/sed-opal.c:get_active_key
  - block/sed-opal.c:get_active_key
  - block/sed-opal.c:get_active_key
  - block/sed-opal.c:get_active_key
  - block/sed-opal.c:get_active_key
  - block/sed-opal.c:get_active_key
  - block/sed-opal.c:get_active_key
  - block/sed-opal.c:get_active_key
  - block/sed-opal.c:gen_key
  - block/sed-opal.c:gen_key
  - block/sed-opal.c:gen_key
  - block/sed-opal.c:finalize_and_send
  - block/sed-opal.c:finalize_and_send
  - block/sed-opal.c:finalize_and_send
  - block/sed-opal.c:finalize_and_send
  - block/sed-opal.c:finalize_and_send
  - block/sed-opal.c:finalize_and_send
```
**Symbols:**

```
ffffffff814d0260-ffffffff814d0297: add_token_u8.part.8 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void add_token_u8(int *err, struct opal_dev *cmd, u8 tok);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff814fea70)
Location: block/sed-opal.c:550
Inline: False
Direct callers:
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
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
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:write_shadow_mbr
  - block/sed-opal.c:write_shadow_mbr
  - block/sed-opal.c:write_shadow_mbr
  - block/sed-opal.c:write_shadow_mbr
  - block/sed-opal.c:write_shadow_mbr
  - block/sed-opal.c:write_shadow_mbr
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_get_column
  - block/sed-opal.c:generic_get_column
  - block/sed-opal.c:generic_get_column
  - block/sed-opal.c:generic_get_column
  - block/sed-opal.c:generic_get_column
  - block/sed-opal.c:generic_get_column
  - block/sed-opal.c:generic_get_column
  - block/sed-opal.c:generic_get_column
  - block/sed-opal.c:finalize_and_send
  - block/sed-opal.c:finalize_and_send
  - block/sed-opal.c:finalize_and_send
  - block/sed-opal.c:finalize_and_send
  - block/sed-opal.c:finalize_and_send
  - block/sed-opal.c:finalize_and_send
  - block/sed-opal.c:finalize_and_send
  - block/sed-opal.c:cmd_start
  - block/sed-opal.c:cmd_start
  - block/sed-opal.c:add_token_u64
  - block/sed-opal.c:add_token_u64
  - block/sed-opal.c:add_token_u64
```
**Symbols:**

```
ffffffff814fea70-ffffffff814feabb: add_token_u8 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void add_token_u8(int *err, struct opal_dev *cmd, u8 tok);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff8151c9c0)
Location: block/sed-opal.c:549
Inline: False
Direct callers:
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
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
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:write_shadow_mbr
  - block/sed-opal.c:write_shadow_mbr
  - block/sed-opal.c:write_shadow_mbr
  - block/sed-opal.c:write_shadow_mbr
  - block/sed-opal.c:write_shadow_mbr
  - block/sed-opal.c:write_shadow_mbr
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_get_column
  - block/sed-opal.c:generic_get_column
  - block/sed-opal.c:generic_get_column
  - block/sed-opal.c:generic_get_column
  - block/sed-opal.c:generic_get_column
  - block/sed-opal.c:generic_get_column
  - block/sed-opal.c:generic_get_column
  - block/sed-opal.c:generic_get_column
  - block/sed-opal.c:finalize_and_send
  - block/sed-opal.c:finalize_and_send
  - block/sed-opal.c:finalize_and_send
  - block/sed-opal.c:finalize_and_send
  - block/sed-opal.c:finalize_and_send
  - block/sed-opal.c:finalize_and_send
  - block/sed-opal.c:finalize_and_send
  - block/sed-opal.c:cmd_start
  - block/sed-opal.c:cmd_start
  - block/sed-opal.c:add_token_u64
  - block/sed-opal.c:add_token_u64
  - block/sed-opal.c:add_token_u64
```
**Symbols:**

```
ffffffff8151c9c0-ffffffff8151ca0b: add_token_u8 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void add_token_u8(int *err, struct opal_dev *cmd, u8 tok);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff8157d320)
Location: block/sed-opal.c:551
Inline: True
Direct callers:
  - block/sed-opal.c:read_table_data
  - block/sed-opal.c:read_table_data
  - block/sed-opal.c:read_table_data
  - block/sed-opal.c:read_table_data
  - block/sed-opal.c:read_table_data
  - block/sed-opal.c:read_table_data
  - block/sed-opal.c:read_table_data
  - block/sed-opal.c:read_table_data
  - block/sed-opal.c:read_table_data
  - block/sed-opal.c:read_table_data
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
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
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_table_write_data
  - block/sed-opal.c:generic_table_write_data
  - block/sed-opal.c:generic_table_write_data
  - block/sed-opal.c:generic_table_write_data
  - block/sed-opal.c:generic_table_write_data
  - block/sed-opal.c:generic_table_write_data
  - block/sed-opal.c:generic_table_write_data
  - block/sed-opal.c:generic_get_column
  - block/sed-opal.c:generic_get_column
  - block/sed-opal.c:generic_get_column
  - block/sed-opal.c:generic_get_column
  - block/sed-opal.c:generic_get_column
  - block/sed-opal.c:generic_get_column
  - block/sed-opal.c:generic_get_column
  - block/sed-opal.c:generic_get_column
  - block/sed-opal.c:generic_get_column
  - block/sed-opal.c:generic_get_column
  - block/sed-opal.c:cmd_start
  - block/sed-opal.c:cmd_start
  - block/sed-opal.c:cmd_finalize
  - block/sed-opal.c:cmd_finalize
  - block/sed-opal.c:cmd_finalize
  - block/sed-opal.c:cmd_finalize
  - block/sed-opal.c:cmd_finalize
  - block/sed-opal.c:cmd_finalize
  - block/sed-opal.c:cmd_finalize
  - block/sed-opal.c:add_bytestring_header
```
**Symbols:**

```
ffffffff8157d320-ffffffff8157d382: add_token_u8 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void add_token_u8(int *err, struct opal_dev *cmd, u8 tok);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff8159a360)
Location: block/sed-opal.c:551
Inline: True
Direct callers:
  - block/sed-opal.c:read_table_data
  - block/sed-opal.c:read_table_data
  - block/sed-opal.c:read_table_data
  - block/sed-opal.c:read_table_data
  - block/sed-opal.c:read_table_data
  - block/sed-opal.c:read_table_data
  - block/sed-opal.c:read_table_data
  - block/sed-opal.c:read_table_data
  - block/sed-opal.c:read_table_data
  - block/sed-opal.c:read_table_data
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
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
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_table_write_data
  - block/sed-opal.c:generic_table_write_data
  - block/sed-opal.c:generic_table_write_data
  - block/sed-opal.c:generic_table_write_data
  - block/sed-opal.c:generic_table_write_data
  - block/sed-opal.c:generic_table_write_data
  - block/sed-opal.c:generic_table_write_data
  - block/sed-opal.c:generic_get_column
  - block/sed-opal.c:generic_get_column
  - block/sed-opal.c:generic_get_column
  - block/sed-opal.c:generic_get_column
  - block/sed-opal.c:generic_get_column
  - block/sed-opal.c:generic_get_column
  - block/sed-opal.c:generic_get_column
  - block/sed-opal.c:generic_get_column
  - block/sed-opal.c:generic_get_column
  - block/sed-opal.c:generic_get_column
  - block/sed-opal.c:cmd_start
  - block/sed-opal.c:cmd_start
  - block/sed-opal.c:cmd_finalize
  - block/sed-opal.c:cmd_finalize
  - block/sed-opal.c:cmd_finalize
  - block/sed-opal.c:cmd_finalize
  - block/sed-opal.c:cmd_finalize
  - block/sed-opal.c:cmd_finalize
  - block/sed-opal.c:cmd_finalize
  - block/sed-opal.c:add_bytestring_header
```
**Symbols:**

```
ffffffff8159a360-ffffffff8159a3c2: add_token_u8 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void add_token_u8(int *err, struct opal_dev *cmd, u8 tok);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff815a0e50)
Location: block/sed-opal.c:551
Inline: True
Direct callers:
  - block/sed-opal.c:read_table_data
  - block/sed-opal.c:read_table_data
  - block/sed-opal.c:read_table_data
  - block/sed-opal.c:read_table_data
  - block/sed-opal.c:read_table_data
  - block/sed-opal.c:read_table_data
  - block/sed-opal.c:read_table_data
  - block/sed-opal.c:read_table_data
  - block/sed-opal.c:read_table_data
  - block/sed-opal.c:read_table_data
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
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
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_table_write_data
  - block/sed-opal.c:generic_table_write_data
  - block/sed-opal.c:generic_table_write_data
  - block/sed-opal.c:generic_table_write_data
  - block/sed-opal.c:generic_table_write_data
  - block/sed-opal.c:generic_table_write_data
  - block/sed-opal.c:generic_table_write_data
  - block/sed-opal.c:generic_get_column
  - block/sed-opal.c:generic_get_column
  - block/sed-opal.c:generic_get_column
  - block/sed-opal.c:generic_get_column
  - block/sed-opal.c:generic_get_column
  - block/sed-opal.c:generic_get_column
  - block/sed-opal.c:generic_get_column
  - block/sed-opal.c:generic_get_column
  - block/sed-opal.c:generic_get_column
  - block/sed-opal.c:generic_get_column
  - block/sed-opal.c:cmd_start
  - block/sed-opal.c:cmd_start
  - block/sed-opal.c:cmd_finalize
  - block/sed-opal.c:cmd_finalize
  - block/sed-opal.c:cmd_finalize
  - block/sed-opal.c:cmd_finalize
  - block/sed-opal.c:cmd_finalize
  - block/sed-opal.c:cmd_finalize
  - block/sed-opal.c:cmd_finalize
  - block/sed-opal.c:add_bytestring_header
```
**Symbols:**

```
ffffffff815a0e50-ffffffff815a0eb2: add_token_u8 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void add_token_u8(int *err, struct opal_dev *cmd, u8 tok);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff81609690)
Location: block/sed-opal.c:551
Inline: True
Direct callers:
  - block/sed-opal.c:read_table_data
  - block/sed-opal.c:read_table_data
  - block/sed-opal.c:read_table_data
  - block/sed-opal.c:read_table_data
  - block/sed-opal.c:read_table_data
  - block/sed-opal.c:read_table_data
  - block/sed-opal.c:read_table_data
  - block/sed-opal.c:read_table_data
  - block/sed-opal.c:read_table_data
  - block/sed-opal.c:read_table_data
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
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
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_table_write_data
  - block/sed-opal.c:generic_table_write_data
  - block/sed-opal.c:generic_table_write_data
  - block/sed-opal.c:generic_table_write_data
  - block/sed-opal.c:generic_table_write_data
  - block/sed-opal.c:generic_table_write_data
  - block/sed-opal.c:generic_table_write_data
  - block/sed-opal.c:generic_get_column
  - block/sed-opal.c:generic_get_column
  - block/sed-opal.c:generic_get_column
  - block/sed-opal.c:generic_get_column
  - block/sed-opal.c:generic_get_column
  - block/sed-opal.c:generic_get_column
  - block/sed-opal.c:generic_get_column
  - block/sed-opal.c:generic_get_column
  - block/sed-opal.c:generic_get_column
  - block/sed-opal.c:generic_get_column
  - block/sed-opal.c:cmd_start
  - block/sed-opal.c:cmd_start
  - block/sed-opal.c:cmd_finalize
  - block/sed-opal.c:cmd_finalize
  - block/sed-opal.c:cmd_finalize
  - block/sed-opal.c:cmd_finalize
  - block/sed-opal.c:cmd_finalize
  - block/sed-opal.c:cmd_finalize
  - block/sed-opal.c:cmd_finalize
  - block/sed-opal.c:add_bytestring_header
```
**Symbols:**

```
ffffffff81609690-ffffffff81609723: add_token_u8 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void add_token_u8(int *err, struct opal_dev *cmd, u8 tok);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff816bd670)
Location: block/sed-opal.c:551
Inline: True
Direct callers:
  - block/sed-opal.c:read_table_data
  - block/sed-opal.c:read_table_data
  - block/sed-opal.c:read_table_data
  - block/sed-opal.c:read_table_data
  - block/sed-opal.c:read_table_data
  - block/sed-opal.c:read_table_data
  - block/sed-opal.c:read_table_data
  - block/sed-opal.c:read_table_data
  - block/sed-opal.c:read_table_data
  - block/sed-opal.c:read_table_data
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
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
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
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
  - block/sed-opal.c:start_generic_opal_session
  - block/sed-opal.c:start_generic_opal_session
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_table_write_data
  - block/sed-opal.c:generic_table_write_data
  - block/sed-opal.c:generic_table_write_data
  - block/sed-opal.c:generic_table_write_data
  - block/sed-opal.c:generic_table_write_data
  - block/sed-opal.c:generic_table_write_data
  - block/sed-opal.c:generic_table_write_data
  - block/sed-opal.c:generic_get_column
  - block/sed-opal.c:generic_get_column
  - block/sed-opal.c:generic_get_column
  - block/sed-opal.c:generic_get_column
  - block/sed-opal.c:generic_get_column
  - block/sed-opal.c:generic_get_column
  - block/sed-opal.c:generic_get_column
  - block/sed-opal.c:generic_get_column
  - block/sed-opal.c:generic_get_column
  - block/sed-opal.c:generic_get_column
  - block/sed-opal.c:cmd_start
  - block/sed-opal.c:cmd_start
  - block/sed-opal.c:cmd_finalize
  - block/sed-opal.c:cmd_finalize
  - block/sed-opal.c:cmd_finalize
  - block/sed-opal.c:cmd_finalize
  - block/sed-opal.c:cmd_finalize
  - block/sed-opal.c:cmd_finalize
  - block/sed-opal.c:cmd_finalize
  - block/sed-opal.c:add_bytestring_header
```
**Symbols:**

```
ffffffff816bd670-ffffffff816bd727: add_token_u8 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void add_token_u8(int *err, struct opal_dev *cmd, u8 tok);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff8177e350)
Location: block/sed-opal.c:591
Inline: True
Direct callers:
  - block/sed-opal.c:read_table_data
  - block/sed-opal.c:read_table_data
  - block/sed-opal.c:read_table_data
  - block/sed-opal.c:read_table_data
  - block/sed-opal.c:read_table_data
  - block/sed-opal.c:read_table_data
  - block/sed-opal.c:read_table_data
  - block/sed-opal.c:read_table_data
  - block/sed-opal.c:read_table_data
  - block/sed-opal.c:read_table_data
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
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
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
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
  - block/sed-opal.c:start_generic_opal_session
  - block/sed-opal.c:start_generic_opal_session
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_table_write_data
  - block/sed-opal.c:generic_table_write_data
  - block/sed-opal.c:generic_table_write_data
  - block/sed-opal.c:generic_table_write_data
  - block/sed-opal.c:generic_table_write_data
  - block/sed-opal.c:generic_table_write_data
  - block/sed-opal.c:generic_table_write_data
  - block/sed-opal.c:generic_get_column
  - block/sed-opal.c:generic_get_column
  - block/sed-opal.c:generic_get_column
  - block/sed-opal.c:generic_get_column
  - block/sed-opal.c:generic_get_column
  - block/sed-opal.c:generic_get_column
  - block/sed-opal.c:generic_get_column
  - block/sed-opal.c:generic_get_column
  - block/sed-opal.c:generic_get_column
  - block/sed-opal.c:generic_get_column
  - block/sed-opal.c:cmd_start
  - block/sed-opal.c:cmd_start
  - block/sed-opal.c:cmd_finalize
  - block/sed-opal.c:cmd_finalize
  - block/sed-opal.c:cmd_finalize
  - block/sed-opal.c:cmd_finalize
  - block/sed-opal.c:cmd_finalize
  - block/sed-opal.c:cmd_finalize
  - block/sed-opal.c:cmd_finalize
  - block/sed-opal.c:add_bytestring_header
```
**Symbols:**

```
ffffffff8177e350-ffffffff8177e3ea: add_token_u8 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void add_token_u8(int *err, struct opal_dev *cmd, u8 tok);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff817bdef0)
Location: block/sed-opal.c:599
Inline: True
Direct callers:
  - block/sed-opal.c:read_table_data
  - block/sed-opal.c:read_table_data
  - block/sed-opal.c:read_table_data
  - block/sed-opal.c:read_table_data
  - block/sed-opal.c:read_table_data
  - block/sed-opal.c:read_table_data
  - block/sed-opal.c:read_table_data
  - block/sed-opal.c:read_table_data
  - block/sed-opal.c:read_table_data
  - block/sed-opal.c:read_table_data
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:set_lr_boolean_ace
  - block/sed-opal.c:set_lr_boolean_ace
  - block/sed-opal.c:set_lr_boolean_ace
  - block/sed-opal.c:set_lr_boolean_ace
  - block/sed-opal.c:set_lr_boolean_ace
  - block/sed-opal.c:set_lr_boolean_ace
  - block/sed-opal.c:set_lr_boolean_ace
  - block/sed-opal.c:set_lr_boolean_ace
  - block/sed-opal.c:set_lr_boolean_ace
  - block/sed-opal.c:set_lr_boolean_ace
  - block/sed-opal.c:set_lr_boolean_ace
  - block/sed-opal.c:set_lr_boolean_ace
  - block/sed-opal.c:set_lr_boolean_ace
  - block/sed-opal.c:set_lr_boolean_ace
  - block/sed-opal.c:set_lr_boolean_ace
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
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
  - block/sed-opal.c:start_generic_opal_session
  - block/sed-opal.c:start_generic_opal_session
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_table_write_data
  - block/sed-opal.c:generic_table_write_data
  - block/sed-opal.c:generic_table_write_data
  - block/sed-opal.c:generic_table_write_data
  - block/sed-opal.c:generic_table_write_data
  - block/sed-opal.c:generic_table_write_data
  - block/sed-opal.c:generic_table_write_data
  - block/sed-opal.c:generic_get_columns
  - block/sed-opal.c:generic_get_columns
  - block/sed-opal.c:generic_get_columns
  - block/sed-opal.c:generic_get_columns
  - block/sed-opal.c:generic_get_columns
  - block/sed-opal.c:generic_get_columns
  - block/sed-opal.c:generic_get_columns
  - block/sed-opal.c:generic_get_columns
  - block/sed-opal.c:generic_get_columns
  - block/sed-opal.c:generic_get_columns
  - block/sed-opal.c:cmd_start
  - block/sed-opal.c:cmd_start
  - block/sed-opal.c:cmd_finalize
  - block/sed-opal.c:cmd_finalize
  - block/sed-opal.c:cmd_finalize
  - block/sed-opal.c:cmd_finalize
  - block/sed-opal.c:cmd_finalize
  - block/sed-opal.c:cmd_finalize
  - block/sed-opal.c:cmd_finalize
  - block/sed-opal.c:add_bytestring_header
```
**Symbols:**

```
ffffffff817bdef0-ffffffff817bdf8a: add_token_u8 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void add_token_u8(int *err, struct opal_dev *cmd, u8 tok);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff81802800)
Location: block/sed-opal.c:712
Inline: True
Direct callers:
  - block/sed-opal.c:read_table_data
  - block/sed-opal.c:read_table_data
  - block/sed-opal.c:read_table_data
  - block/sed-opal.c:read_table_data
  - block/sed-opal.c:read_table_data
  - block/sed-opal.c:read_table_data
  - block/sed-opal.c:read_table_data
  - block/sed-opal.c:read_table_data
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:set_lr_boolean_ace
  - block/sed-opal.c:set_lr_boolean_ace
  - block/sed-opal.c:set_lr_boolean_ace
  - block/sed-opal.c:set_lr_boolean_ace
  - block/sed-opal.c:set_lr_boolean_ace
  - block/sed-opal.c:set_lr_boolean_ace
  - block/sed-opal.c:set_lr_boolean_ace
  - block/sed-opal.c:set_lr_boolean_ace
  - block/sed-opal.c:set_lr_boolean_ace
  - block/sed-opal.c:set_lr_boolean_ace
  - block/sed-opal.c:set_lr_boolean_ace
  - block/sed-opal.c:set_lr_boolean_ace
  - block/sed-opal.c:set_lr_boolean_ace
  - block/sed-opal.c:set_lr_boolean_ace
  - block/sed-opal.c:set_lr_boolean_ace
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:revert_lsp
  - block/sed-opal.c:revert_lsp
  - block/sed-opal.c:revert_lsp
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
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
  - block/sed-opal.c:start_generic_opal_session
  - block/sed-opal.c:start_generic_opal_session
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_table_write_data
  - block/sed-opal.c:generic_table_write_data
  - block/sed-opal.c:generic_table_write_data
  - block/sed-opal.c:generic_table_write_data
  - block/sed-opal.c:generic_table_write_data
  - block/sed-opal.c:generic_table_write_data
  - block/sed-opal.c:generic_get_columns
  - block/sed-opal.c:generic_get_columns
  - block/sed-opal.c:generic_get_columns
  - block/sed-opal.c:generic_get_columns
  - block/sed-opal.c:generic_get_columns
  - block/sed-opal.c:generic_get_columns
  - block/sed-opal.c:generic_get_columns
  - block/sed-opal.c:generic_get_columns
  - block/sed-opal.c:cmd_start
  - block/sed-opal.c:cmd_start
  - block/sed-opal.c:cmd_finalize
  - block/sed-opal.c:cmd_finalize
  - block/sed-opal.c:cmd_finalize
  - block/sed-opal.c:cmd_finalize
  - block/sed-opal.c:cmd_finalize
  - block/sed-opal.c:cmd_finalize
  - block/sed-opal.c:cmd_finalize
  - block/sed-opal.c:add_bytestring_header
```
**Symbols:**

```
ffffffff81802800-ffffffff8180289a: add_token_u8 (STB_LOCAL)
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
void add_token_u8(int *err, struct opal_dev *cmd, u8 tok);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffff800010625558)
Location: block/sed-opal.c:549
Inline: False
Direct callers:
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
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
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:write_shadow_mbr
  - block/sed-opal.c:write_shadow_mbr
  - block/sed-opal.c:write_shadow_mbr
  - block/sed-opal.c:write_shadow_mbr
  - block/sed-opal.c:write_shadow_mbr
  - block/sed-opal.c:write_shadow_mbr
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_get_column
  - block/sed-opal.c:generic_get_column
  - block/sed-opal.c:generic_get_column
  - block/sed-opal.c:generic_get_column
  - block/sed-opal.c:generic_get_column
  - block/sed-opal.c:generic_get_column
  - block/sed-opal.c:generic_get_column
  - block/sed-opal.c:generic_get_column
  - block/sed-opal.c:finalize_and_send
  - block/sed-opal.c:finalize_and_send
  - block/sed-opal.c:finalize_and_send
  - block/sed-opal.c:finalize_and_send
  - block/sed-opal.c:finalize_and_send
  - block/sed-opal.c:finalize_and_send
  - block/sed-opal.c:finalize_and_send
  - block/sed-opal.c:cmd_start
  - block/sed-opal.c:cmd_start
  - block/sed-opal.c:add_token_u64
  - block/sed-opal.c:add_token_u64
  - block/sed-opal.c:add_token_u64
```
**Symbols:**

```
ffff800010625558-ffff8000106255cc: add_token_u8 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void add_token_u8(int *err, struct opal_dev *cmd, u8 tok);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (c07ccf84)
Location: block/sed-opal.c:549
Inline: False
Direct callers:
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
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
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:write_shadow_mbr
  - block/sed-opal.c:write_shadow_mbr
  - block/sed-opal.c:write_shadow_mbr
  - block/sed-opal.c:write_shadow_mbr
  - block/sed-opal.c:write_shadow_mbr
  - block/sed-opal.c:write_shadow_mbr
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_get_column
  - block/sed-opal.c:generic_get_column
  - block/sed-opal.c:generic_get_column
  - block/sed-opal.c:generic_get_column
  - block/sed-opal.c:generic_get_column
  - block/sed-opal.c:generic_get_column
  - block/sed-opal.c:generic_get_column
  - block/sed-opal.c:generic_get_column
  - block/sed-opal.c:finalize_and_send
  - block/sed-opal.c:finalize_and_send
  - block/sed-opal.c:finalize_and_send
  - block/sed-opal.c:finalize_and_send
  - block/sed-opal.c:finalize_and_send
  - block/sed-opal.c:finalize_and_send
  - block/sed-opal.c:finalize_and_send
  - block/sed-opal.c:cmd_start
  - block/sed-opal.c:cmd_start
  - block/sed-opal.c:add_token_u64
  - block/sed-opal.c:add_token_u64
  - block/sed-opal.c:add_token_u64
```
**Symbols:**

```
c07ccf84-c07ccfe4: add_token_u8 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void add_token_u8(int *err, struct opal_dev *cmd, u8 tok);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (c0000000007c62b0)
Location: block/sed-opal.c:549
Inline: False
Direct callers:
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
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
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:write_shadow_mbr
  - block/sed-opal.c:write_shadow_mbr
  - block/sed-opal.c:write_shadow_mbr
  - block/sed-opal.c:write_shadow_mbr
  - block/sed-opal.c:write_shadow_mbr
  - block/sed-opal.c:write_shadow_mbr
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
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
  - block/sed-opal.c:start_generic_opal_session
  - block/sed-opal.c:start_generic_opal_session
  - block/sed-opal.c:start_generic_opal_session
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_get_column
  - block/sed-opal.c:generic_get_column
  - block/sed-opal.c:generic_get_column
  - block/sed-opal.c:generic_get_column
  - block/sed-opal.c:generic_get_column
  - block/sed-opal.c:generic_get_column
  - block/sed-opal.c:generic_get_column
  - block/sed-opal.c:generic_get_column
  - block/sed-opal.c:finalize_and_send
  - block/sed-opal.c:finalize_and_send
  - block/sed-opal.c:finalize_and_send
  - block/sed-opal.c:finalize_and_send
  - block/sed-opal.c:finalize_and_send
  - block/sed-opal.c:finalize_and_send
  - block/sed-opal.c:finalize_and_send
  - block/sed-opal.c:cmd_start
  - block/sed-opal.c:cmd_start
  - block/sed-opal.c:add_token_u64
  - block/sed-opal.c:add_token_u64
  - block/sed-opal.c:add_token_u64
```
**Symbols:**

```
c0000000007c62b0-c0000000007c633c: add_token_u8 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void add_token_u8(int *err, struct opal_dev *cmd, u8 tok);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffe000456766)
Location: block/sed-opal.c:549
Inline: False
Direct callers:
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
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
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:write_shadow_mbr
  - block/sed-opal.c:write_shadow_mbr
  - block/sed-opal.c:write_shadow_mbr
  - block/sed-opal.c:write_shadow_mbr
  - block/sed-opal.c:write_shadow_mbr
  - block/sed-opal.c:write_shadow_mbr
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
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
  - block/sed-opal.c:start_generic_opal_session
  - block/sed-opal.c:start_generic_opal_session
  - block/sed-opal.c:start_generic_opal_session
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_get_column
  - block/sed-opal.c:generic_get_column
  - block/sed-opal.c:generic_get_column
  - block/sed-opal.c:generic_get_column
  - block/sed-opal.c:generic_get_column
  - block/sed-opal.c:generic_get_column
  - block/sed-opal.c:generic_get_column
  - block/sed-opal.c:generic_get_column
  - block/sed-opal.c:finalize_and_send
  - block/sed-opal.c:finalize_and_send
  - block/sed-opal.c:finalize_and_send
  - block/sed-opal.c:finalize_and_send
  - block/sed-opal.c:finalize_and_send
  - block/sed-opal.c:finalize_and_send
  - block/sed-opal.c:finalize_and_send
  - block/sed-opal.c:cmd_start
  - block/sed-opal.c:cmd_start
  - block/sed-opal.c:add_token_u64
  - block/sed-opal.c:add_token_u64
  - block/sed-opal.c:add_token_u64
```
**Symbols:**

```
ffffffe000456766-ffffffe0004567be: add_token_u8 (STB_LOCAL)
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
void add_token_u8(int *err, struct opal_dev *cmd, u8 tok);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff81514fa0)
Location: block/sed-opal.c:549
Inline: False
Direct callers:
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
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
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:write_shadow_mbr
  - block/sed-opal.c:write_shadow_mbr
  - block/sed-opal.c:write_shadow_mbr
  - block/sed-opal.c:write_shadow_mbr
  - block/sed-opal.c:write_shadow_mbr
  - block/sed-opal.c:write_shadow_mbr
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_get_column
  - block/sed-opal.c:generic_get_column
  - block/sed-opal.c:generic_get_column
  - block/sed-opal.c:generic_get_column
  - block/sed-opal.c:generic_get_column
  - block/sed-opal.c:generic_get_column
  - block/sed-opal.c:generic_get_column
  - block/sed-opal.c:generic_get_column
  - block/sed-opal.c:finalize_and_send
  - block/sed-opal.c:finalize_and_send
  - block/sed-opal.c:finalize_and_send
  - block/sed-opal.c:finalize_and_send
  - block/sed-opal.c:finalize_and_send
  - block/sed-opal.c:finalize_and_send
  - block/sed-opal.c:finalize_and_send
  - block/sed-opal.c:cmd_start
  - block/sed-opal.c:cmd_start
  - block/sed-opal.c:add_token_u64
  - block/sed-opal.c:add_token_u64
  - block/sed-opal.c:add_token_u64
```
**Symbols:**

```
ffffffff81514fa0-ffffffff81514feb: add_token_u8 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void add_token_u8(int *err, struct opal_dev *cmd, u8 tok);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff815052b0)
Location: block/sed-opal.c:549
Inline: False
Direct callers:
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
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
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:write_shadow_mbr
  - block/sed-opal.c:write_shadow_mbr
  - block/sed-opal.c:write_shadow_mbr
  - block/sed-opal.c:write_shadow_mbr
  - block/sed-opal.c:write_shadow_mbr
  - block/sed-opal.c:write_shadow_mbr
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_get_column
  - block/sed-opal.c:generic_get_column
  - block/sed-opal.c:generic_get_column
  - block/sed-opal.c:generic_get_column
  - block/sed-opal.c:generic_get_column
  - block/sed-opal.c:generic_get_column
  - block/sed-opal.c:generic_get_column
  - block/sed-opal.c:generic_get_column
  - block/sed-opal.c:finalize_and_send
  - block/sed-opal.c:finalize_and_send
  - block/sed-opal.c:finalize_and_send
  - block/sed-opal.c:finalize_and_send
  - block/sed-opal.c:finalize_and_send
  - block/sed-opal.c:finalize_and_send
  - block/sed-opal.c:finalize_and_send
  - block/sed-opal.c:cmd_start
  - block/sed-opal.c:cmd_start
  - block/sed-opal.c:add_token_u64
  - block/sed-opal.c:add_token_u64
  - block/sed-opal.c:add_token_u64
```
**Symbols:**

```
ffffffff815052b0-ffffffff815052fb: add_token_u8 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void add_token_u8(int *err, struct opal_dev *cmd, u8 tok);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff81511030)
Location: block/sed-opal.c:549
Inline: False
Direct callers:
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
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
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:write_shadow_mbr
  - block/sed-opal.c:write_shadow_mbr
  - block/sed-opal.c:write_shadow_mbr
  - block/sed-opal.c:write_shadow_mbr
  - block/sed-opal.c:write_shadow_mbr
  - block/sed-opal.c:write_shadow_mbr
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_get_column
  - block/sed-opal.c:generic_get_column
  - block/sed-opal.c:generic_get_column
  - block/sed-opal.c:generic_get_column
  - block/sed-opal.c:generic_get_column
  - block/sed-opal.c:generic_get_column
  - block/sed-opal.c:generic_get_column
  - block/sed-opal.c:generic_get_column
  - block/sed-opal.c:finalize_and_send
  - block/sed-opal.c:finalize_and_send
  - block/sed-opal.c:finalize_and_send
  - block/sed-opal.c:finalize_and_send
  - block/sed-opal.c:finalize_and_send
  - block/sed-opal.c:finalize_and_send
  - block/sed-opal.c:finalize_and_send
  - block/sed-opal.c:cmd_start
  - block/sed-opal.c:cmd_start
  - block/sed-opal.c:add_token_u64
  - block/sed-opal.c:add_token_u64
  - block/sed-opal.c:add_token_u64
```
**Symbols:**

```
ffffffff81511030-ffffffff8151107b: add_token_u8 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void add_token_u8(int *err, struct opal_dev *cmd, u8 tok);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff8152a7f0)
Location: block/sed-opal.c:549
Inline: False
Direct callers:
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:add_user_to_lr
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
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:write_shadow_mbr
  - block/sed-opal.c:write_shadow_mbr
  - block/sed-opal.c:write_shadow_mbr
  - block/sed-opal.c:write_shadow_mbr
  - block/sed-opal.c:write_shadow_mbr
  - block/sed-opal.c:write_shadow_mbr
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_get_column
  - block/sed-opal.c:generic_get_column
  - block/sed-opal.c:generic_get_column
  - block/sed-opal.c:generic_get_column
  - block/sed-opal.c:generic_get_column
  - block/sed-opal.c:generic_get_column
  - block/sed-opal.c:generic_get_column
  - block/sed-opal.c:generic_get_column
  - block/sed-opal.c:finalize_and_send
  - block/sed-opal.c:finalize_and_send
  - block/sed-opal.c:finalize_and_send
  - block/sed-opal.c:finalize_and_send
  - block/sed-opal.c:finalize_and_send
  - block/sed-opal.c:finalize_and_send
  - block/sed-opal.c:finalize_and_send
  - block/sed-opal.c:cmd_start
  - block/sed-opal.c:cmd_start
  - block/sed-opal.c:add_token_u64
  - block/sed-opal.c:add_token_u64
  - block/sed-opal.c:add_token_u64
```
**Symbols:**

```
ffffffff8152a7f0-ffffffff8152a83b: add_token_u8 (STB_LOCAL)
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
