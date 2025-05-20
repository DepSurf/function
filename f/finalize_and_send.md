# Function: <code>finalize_and_send</code>

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
<summary>In <code>4.13</code>: ✅</summary>

```c
int finalize_and_send(struct opal_dev *dev, cont_fn *cont);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff8145b1c0)
Location: block/sed-opal.c:1009
Inline: False
Direct callers:
  - block/sed-opal.c:get_msid_cpin_pin
  - block/sed-opal.c:get_lsp_lifecycle
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:lock_unlock_locking_range_sum
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:erase_locking_range
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:revert_tper
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_generic_opal_session
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:get_active_key
  - block/sed-opal.c:gen_key
```
**Symbols:**

```
ffffffff8145b1c0-ffffffff8145b578: finalize_and_send (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int finalize_and_send(struct opal_dev *dev, cont_fn *cont);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff81486f90)
Location: block/sed-opal.c:1021
Inline: False
Direct callers:
  - block/sed-opal.c:get_msid_cpin_pin
  - block/sed-opal.c:get_lsp_lifecycle
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:lock_unlock_locking_range_sum
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:erase_locking_range
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:revert_tper
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_generic_opal_session
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:get_active_key
  - block/sed-opal.c:gen_key
```
**Symbols:**

```
ffffffff81486f90-ffffffff8148735c: finalize_and_send (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int finalize_and_send(struct opal_dev *dev, cont_fn *cont);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff814bbee0)
Location: block/sed-opal.c:1038
Inline: False
Direct callers:
  - block/sed-opal.c:get_msid_cpin_pin
  - block/sed-opal.c:get_lsp_lifecycle
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:lock_unlock_locking_range_sum
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:erase_locking_range
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:revert_tper
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_generic_opal_session
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:get_active_key
  - block/sed-opal.c:gen_key
```
**Symbols:**

```
ffffffff814bbee0-ffffffff814bc2b1: finalize_and_send (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int finalize_and_send(struct opal_dev *dev, cont_fn *cont);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff814d02a0)
Location: block/sed-opal.c:1038
Inline: False
Direct callers:
  - block/sed-opal.c:get_msid_cpin_pin
  - block/sed-opal.c:get_lsp_lifecycle
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:lock_unlock_locking_range_sum
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:erase_locking_range
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:revert_tper
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_generic_opal_session
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:get_active_key
  - block/sed-opal.c:gen_key
```
**Symbols:**

```
ffffffff814d02a0-ffffffff814d066c: finalize_and_send (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int finalize_and_send(struct opal_dev *dev, cont_fn *cont);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff814feac0)
Location: block/sed-opal.c:1090
Inline: False
Direct callers:
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:lock_unlock_locking_range_sum
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:write_shadow_mbr
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:gen_key
  - block/sed-opal.c:generic_get_column
```
**Symbols:**

```
ffffffff814feac0-ffffffff814fed82: finalize_and_send (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int finalize_and_send(struct opal_dev *dev, cont_fn *cont);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff8151ca10)
Location: block/sed-opal.c:1091
Inline: False
Direct callers:
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:lock_unlock_locking_range_sum
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:write_shadow_mbr
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:gen_key
  - block/sed-opal.c:generic_get_column
```
**Symbols:**

```
ffffffff8151ca10-ffffffff8151ccd2: finalize_and_send (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int finalize_and_send(struct opal_dev *dev, cont_fn *cont);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff8157d740)
Location: block/sed-opal.c:1093
Inline: False
Direct callers:
  - block/sed-opal.c:read_table_data
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:lock_unlock_locking_range_sum
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:set_new_pw
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:erase_locking_range
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:generic_table_write_data
  - block/sed-opal.c:gen_key
  - block/sed-opal.c:generic_get_column
```
**Symbols:**

```
ffffffff8157d740-ffffffff8157d8b9: finalize_and_send (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int finalize_and_send(struct opal_dev *dev, cont_fn *cont);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff8159a780)
Location: block/sed-opal.c:1093
Inline: False
Direct callers:
  - block/sed-opal.c:read_table_data
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:lock_unlock_locking_range_sum
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:set_new_pw
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:erase_locking_range
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:generic_table_write_data
  - block/sed-opal.c:gen_key
  - block/sed-opal.c:generic_get_column
```
**Symbols:**

```
ffffffff8159a780-ffffffff8159a8f9: finalize_and_send (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int finalize_and_send(struct opal_dev *dev, cont_fn *cont);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff815a1270)
Location: block/sed-opal.c:1093
Inline: False
Direct callers:
  - block/sed-opal.c:read_table_data
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:lock_unlock_locking_range_sum
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:set_new_pw
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:erase_locking_range
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:generic_table_write_data
  - block/sed-opal.c:gen_key
  - block/sed-opal.c:generic_get_column
```
**Symbols:**

```
ffffffff815a1270-ffffffff815a13e9: finalize_and_send (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int finalize_and_send(struct opal_dev *dev, cont_fn *cont);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff81609b50)
Location: block/sed-opal.c:1093
Inline: False
Direct callers:
  - block/sed-opal.c:read_table_data
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:lock_unlock_locking_range_sum
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:set_new_pw
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:erase_locking_range
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:revert_tper
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:generic_table_write_data
  - block/sed-opal.c:gen_key
  - block/sed-opal.c:generic_get_column
```
**Symbols:**

```
ffffffff81609b50-ffffffff81609cc3: finalize_and_send (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int finalize_and_send(struct opal_dev *dev, cont_fn *cont);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff816bd8a0)
Location: block/sed-opal.c:1093
Inline: False
Direct callers:
  - block/sed-opal.c:read_table_data
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:lock_unlock_locking_range_sum
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:set_new_pw
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:erase_locking_range
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:revert_tper
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_generic_opal_session
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:generic_table_write_data
  - block/sed-opal.c:gen_key
  - block/sed-opal.c:generic_get_column
```
**Symbols:**

```
ffffffff816bd8a0-ffffffff816bda26: finalize_and_send (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int finalize_and_send(struct opal_dev *dev, cont_fn *cont);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff8177e580)
Location: block/sed-opal.c:1133
Inline: False
Direct callers:
  - block/sed-opal.c:read_table_data
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:lock_unlock_locking_range_sum
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:set_new_pw
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:erase_locking_range
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_generic_opal_session
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:generic_table_write_data
  - block/sed-opal.c:gen_key
  - block/sed-opal.c:generic_get_column
```
**Symbols:**

```
ffffffff8177e580-ffffffff8177e6fd: finalize_and_send (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int finalize_and_send(struct opal_dev *dev, cont_fn *cont);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff817be310)
Location: block/sed-opal.c:1141
Inline: False
Direct callers:
  - block/sed-opal.c:read_table_data
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:lock_unlock_locking_range_sum
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:add_user_to_lr_ace
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:set_new_pw
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:erase_locking_range
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_generic_opal_session
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:generic_table_write_data
  - block/sed-opal.c:gen_key
  - block/sed-opal.c:generic_get_columns
```
**Symbols:**

```
ffffffff817be310-ffffffff817be48d: finalize_and_send (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int finalize_and_send(struct opal_dev *dev, cont_fn *cont);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff81802a30)
Location: block/sed-opal.c:1258
Inline: False
Direct callers:
  - block/sed-opal.c:read_table_data
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:lock_unlock_locking_range_sum
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:add_user_to_lr_ace
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:set_new_pw
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:erase_locking_range
  - block/sed-opal.c:revert_lsp
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_generic_opal_session
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:generic_table_write_data
  - block/sed-opal.c:gen_key
  - block/sed-opal.c:generic_get_columns
```
**Symbols:**

```
ffffffff81802a30-ffffffff81802bad: finalize_and_send (STB_LOCAL)
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
int finalize_and_send(struct opal_dev *dev, cont_fn *cont);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffff8000106255d0)
Location: block/sed-opal.c:1091
Inline: False
Direct callers:
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:lock_unlock_locking_range_sum
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:write_shadow_mbr
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:gen_key
  - block/sed-opal.c:generic_get_column
```
**Symbols:**

```
ffff8000106255d0-ffff800010625874: finalize_and_send (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int finalize_and_send(struct opal_dev *dev, cont_fn *cont);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (c07ccfe4)
Location: block/sed-opal.c:1091
Inline: False
Direct callers:
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:lock_unlock_locking_range_sum
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:write_shadow_mbr
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:generic_get_column
```
**Symbols:**

```
c07ccfe4-c07cd2cc: finalize_and_send (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int finalize_and_send(struct opal_dev *dev, cont_fn *cont);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (c0000000007c6340)
Location: block/sed-opal.c:1091
Inline: False
Direct callers:
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:lock_unlock_locking_range_sum
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:write_shadow_mbr
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_generic_opal_session
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:gen_key
  - block/sed-opal.c:generic_get_column
```
**Symbols:**

```
c0000000007c6340-c0000000007c66b4: finalize_and_send (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int finalize_and_send(struct opal_dev *dev, cont_fn *cont);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffe0004567be)
Location: block/sed-opal.c:1091
Inline: False
Direct callers:
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:lock_unlock_locking_range_sum
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:write_shadow_mbr
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_generic_opal_session
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:generic_get_column
```
**Symbols:**

```
ffffffe0004567be-ffffffe000456adc: finalize_and_send (STB_LOCAL)
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
int finalize_and_send(struct opal_dev *dev, cont_fn *cont);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff81514ff0)
Location: block/sed-opal.c:1091
Inline: False
Direct callers:
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:lock_unlock_locking_range_sum
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:write_shadow_mbr
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:gen_key
  - block/sed-opal.c:generic_get_column
```
**Symbols:**

```
ffffffff81514ff0-ffffffff815152b2: finalize_and_send (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int finalize_and_send(struct opal_dev *dev, cont_fn *cont);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff81505300)
Location: block/sed-opal.c:1091
Inline: False
Direct callers:
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:lock_unlock_locking_range_sum
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:write_shadow_mbr
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:gen_key
  - block/sed-opal.c:generic_get_column
```
**Symbols:**

```
ffffffff81505300-ffffffff815055c2: finalize_and_send (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int finalize_and_send(struct opal_dev *dev, cont_fn *cont);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff81511080)
Location: block/sed-opal.c:1091
Inline: False
Direct callers:
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:lock_unlock_locking_range_sum
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:write_shadow_mbr
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:gen_key
  - block/sed-opal.c:generic_get_column
```
**Symbols:**

```
ffffffff81511080-ffffffff81511342: finalize_and_send (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int finalize_and_send(struct opal_dev *dev, cont_fn *cont);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff8152a840)
Location: block/sed-opal.c:1091
Inline: False
Direct callers:
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:lock_unlock_locking_range_sum
  - block/sed-opal.c:lock_unlock_locking_range
  - block/sed-opal.c:add_user_to_lr
  - block/sed-opal.c:write_shadow_mbr
  - block/sed-opal.c:set_mbr_enable_disable
  - block/sed-opal.c:set_mbr_done
  - block/sed-opal.c:internal_activate_user
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:gen_key
  - block/sed-opal.c:generic_get_column
```
**Symbols:**

```
ffffffff8152a840-ffffffff8152ab02: finalize_and_send (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
