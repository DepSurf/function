# Function: <code>cmd_start</code>

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
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int cmd_start(struct opal_dev *dev, const u8 *uid, const u8 *method);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff814fefd0)
Location: block/sed-opal.c:1025
Inline: False
Direct callers:
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:write_shadow_mbr
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:gen_key
  - block/sed-opal.c:generic_get_column
```
**Symbols:**

```
ffffffff814fefd0-ffffffff814ff08c: cmd_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int cmd_start(struct opal_dev *dev, const u8 *uid, const u8 *method);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff8151cf20)
Location: block/sed-opal.c:1024
Inline: False
Direct callers:
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:write_shadow_mbr
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:gen_key
  - block/sed-opal.c:generic_get_column
```
**Symbols:**

```
ffffffff8151cf20-ffffffff8151cfdc: cmd_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int cmd_start(struct opal_dev *dev, const u8 *uid, const u8 *method);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff8157d980)
Location: block/sed-opal.c:1026
Inline: False
Direct callers:
  - block/sed-opal.c:read_table_data
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:erase_locking_range
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_table_write_data
  - block/sed-opal.c:gen_key
  - block/sed-opal.c:generic_get_column
```
**Symbols:**

```
ffffffff8157d980-ffffffff8157da6d: cmd_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int cmd_start(struct opal_dev *dev, const u8 *uid, const u8 *method);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff8159a9c0)
Location: block/sed-opal.c:1026
Inline: False
Direct callers:
  - block/sed-opal.c:read_table_data
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:erase_locking_range
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_table_write_data
  - block/sed-opal.c:gen_key
  - block/sed-opal.c:generic_get_column
```
**Symbols:**

```
ffffffff8159a9c0-ffffffff8159aaad: cmd_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int cmd_start(struct opal_dev *dev, const u8 *uid, const u8 *method);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff815a14b0)
Location: block/sed-opal.c:1026
Inline: False
Direct callers:
  - block/sed-opal.c:read_table_data
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:erase_locking_range
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_table_write_data
  - block/sed-opal.c:gen_key
  - block/sed-opal.c:generic_get_column
```
**Symbols:**

```
ffffffff815a14b0-ffffffff815a159d: cmd_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int cmd_start(struct opal_dev *dev, const u8 *uid, const u8 *method);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff81609d90)
Location: block/sed-opal.c:1026
Inline: False
Direct callers:
  - block/sed-opal.c:read_table_data
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:erase_locking_range
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:revert_tper
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_table_write_data
  - block/sed-opal.c:gen_key
  - block/sed-opal.c:generic_get_column
```
**Symbols:**

```
ffffffff81609d90-ffffffff81609e7d: cmd_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int cmd_start(struct opal_dev *dev, const u8 *uid, const u8 *method);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff816bdc70)
Location: block/sed-opal.c:1026
Inline: False
Direct callers:
  - block/sed-opal.c:read_table_data
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:erase_locking_range
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:revert_tper
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_generic_opal_session
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_table_write_data
  - block/sed-opal.c:gen_key
  - block/sed-opal.c:generic_get_column
```
**Symbols:**

```
ffffffff816bdc70-ffffffff816bdd35: cmd_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int cmd_start(struct opal_dev *dev, const u8 *uid, const u8 *method);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff8177e9b0)
Location: block/sed-opal.c:1066
Inline: False
Direct callers:
  - block/sed-opal.c:read_table_data
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:erase_locking_range
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_generic_opal_session
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_table_write_data
  - block/sed-opal.c:gen_key
  - block/sed-opal.c:generic_get_column
```
**Symbols:**

```
ffffffff8177e9b0-ffffffff8177ea79: cmd_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int cmd_start(struct opal_dev *dev, const u8 *uid, const u8 *method);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff817be540)
Location: block/sed-opal.c:1074
Inline: False
Direct callers:
  - block/sed-opal.c:read_table_data
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:set_lr_boolean_ace
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:erase_locking_range
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_generic_opal_session
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_table_write_data
  - block/sed-opal.c:gen_key
  - block/sed-opal.c:generic_get_columns
```
**Symbols:**

```
ffffffff817be540-ffffffff817be604: cmd_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int cmd_start(struct opal_dev *dev, const u8 *uid, const u8 *method);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff81802e50)
Location: block/sed-opal.c:1191
Inline: False
Direct callers:
  - block/sed-opal.c:read_table_data
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:set_lr_boolean_ace
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:erase_locking_range
  - block/sed-opal.c:revert_lsp
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_generic_opal_session
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_table_write_data
  - block/sed-opal.c:gen_key
  - block/sed-opal.c:generic_get_columns
```
**Symbols:**

```
ffffffff81802e50-ffffffff81802f14: cmd_start (STB_LOCAL)
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
int cmd_start(struct opal_dev *dev, const u8 *uid, const u8 *method);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffff800010625b38)
Location: block/sed-opal.c:1024
Inline: False
Direct callers:
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:write_shadow_mbr
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:gen_key
  - block/sed-opal.c:generic_get_column
```
**Symbols:**

```
ffff800010625b38-ffff800010625bf8: cmd_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int cmd_start(struct opal_dev *dev, const u8 *uid, const u8 *method);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (c07cd5b8)
Location: block/sed-opal.c:1024
Inline: False
Direct callers:
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:write_shadow_mbr
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_get_column
```
**Symbols:**

```
c07cd5b8-c07cd67c: cmd_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int cmd_start(struct opal_dev *dev, const u8 *uid, const u8 *method);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (c0000000007c6a70)
Location: block/sed-opal.c:1024
Inline: False
Direct callers:
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:write_shadow_mbr
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_generic_opal_session
  - block/sed-opal.c:start_generic_opal_session
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:gen_key
  - block/sed-opal.c:generic_get_column
```
**Symbols:**

```
c0000000007c6a70-c0000000007c6b58: cmd_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int cmd_start(struct opal_dev *dev, const u8 *uid, const u8 *method);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffe000456d3e)
Location: block/sed-opal.c:1024
Inline: False
Direct callers:
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:write_shadow_mbr
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_generic_opal_session
  - block/sed-opal.c:start_generic_opal_session
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:generic_get_column
```
**Symbols:**

```
ffffffe000456d3e-ffffffe000456dee: cmd_start (STB_LOCAL)
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
int cmd_start(struct opal_dev *dev, const u8 *uid, const u8 *method);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff81515500)
Location: block/sed-opal.c:1024
Inline: False
Direct callers:
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:write_shadow_mbr
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:gen_key
  - block/sed-opal.c:generic_get_column
```
**Symbols:**

```
ffffffff81515500-ffffffff815155bc: cmd_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int cmd_start(struct opal_dev *dev, const u8 *uid, const u8 *method);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff81505810)
Location: block/sed-opal.c:1024
Inline: False
Direct callers:
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:write_shadow_mbr
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:gen_key
  - block/sed-opal.c:generic_get_column
```
**Symbols:**

```
ffffffff81505810-ffffffff815058cc: cmd_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int cmd_start(struct opal_dev *dev, const u8 *uid, const u8 *method);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff81511590)
Location: block/sed-opal.c:1024
Inline: False
Direct callers:
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:write_shadow_mbr
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:gen_key
  - block/sed-opal.c:generic_get_column
```
**Symbols:**

```
ffffffff81511590-ffffffff8151164c: cmd_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int cmd_start(struct opal_dev *dev, const u8 *uid, const u8 *method);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff8152ad50)
Location: block/sed-opal.c:1024
Inline: False
Direct callers:
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:generic_pw_cmd
  - block/sed-opal.c:write_shadow_mbr
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:generic_lr_enable_disable
  - block/sed-opal.c:gen_key
  - block/sed-opal.c:generic_get_column
```
**Symbols:**

```
ffffffff8152ad50-ffffffff8152ae0c: cmd_start (STB_LOCAL)
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
