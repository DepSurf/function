# Function: <code>add_token_u64</code>

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
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void add_token_u64(int *err, struct opal_dev *cmd, u64 number);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff8145dde0)
Location: block/sed-opal.c:540
Inline: True
Direct callers:
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_generic_opal_session
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
```
**Symbols:**

```
ffffffff8145dde0-ffffffff8145df4b: add_token_u64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void add_token_u64(int *err, struct opal_dev *cmd, u64 number);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff81489bc0)
Location: block/sed-opal.c:552
Inline: True
Direct callers:
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_generic_opal_session
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
```
**Symbols:**

```
ffffffff81489bc0-ffffffff81489d2b: add_token_u64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void add_token_u64(int *err, struct opal_dev *cmd, u64 number);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff814be8e0)
Location: block/sed-opal.c:552
Inline: True
Direct callers:
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_generic_opal_session
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
```
**Symbols:**

```
ffffffff814be8e0-ffffffff814bea35: add_token_u64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void add_token_u64(int *err, struct opal_dev *cmd, u64 number);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff814d2e50)
Location: block/sed-opal.c:552
Inline: True
Direct callers:
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_generic_opal_session
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
```
**Symbols:**

```
ffffffff814d2e50-ffffffff814d2fa5: add_token_u64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void add_token_u64(int *err, struct opal_dev *cmd, u64 number);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff814fed90)
Location: block/sed-opal.c:584
Inline: False
Direct callers:
  - block/sed-opal.c:write_shadow_mbr
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:generic_get_column
  - block/sed-opal.c:generic_get_column
```
**Symbols:**

```
ffffffff814fed90-ffffffff814fee97: add_token_u64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void add_token_u64(int *err, struct opal_dev *cmd, u64 number);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff8151cce0)
Location: block/sed-opal.c:585
Inline: False
Direct callers:
  - block/sed-opal.c:write_shadow_mbr
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:generic_get_column
  - block/sed-opal.c:generic_get_column
```
**Symbols:**

```
ffffffff8151cce0-ffffffff8151cde7: add_token_u64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/sed-opal.c (ffffffff815804b6)
Location: block/sed-opal.c:587
Inline: True
Inline callers:
  - block/sed-opal.c:read_table_data
  - block/sed-opal.c:read_table_data
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:generic_table_write_data
  - block/sed-opal.c:generic_get_column
  - block/sed-opal.c:generic_get_column
Direct callers:
  - block/sed-opal.c:read_table_data
  - block/sed-opal.c:read_table_data
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:generic_table_write_data
```
**Symbols:**

```
ffffffff8157f8a0-ffffffff8157f9ed: add_token_u64.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/sed-opal.c (ffffffff8159d4f4)
Location: block/sed-opal.c:587
Inline: True
Inline callers:
  - block/sed-opal.c:read_table_data
  - block/sed-opal.c:read_table_data
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:generic_table_write_data
  - block/sed-opal.c:generic_get_column
  - block/sed-opal.c:generic_get_column
Direct callers:
  - block/sed-opal.c:read_table_data
  - block/sed-opal.c:read_table_data
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:generic_table_write_data
```
**Symbols:**

```
ffffffff8159c8e0-ffffffff8159ca2d: add_token_u64.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/sed-opal.c (ffffffff815a4147)
Location: block/sed-opal.c:587
Inline: True
Inline callers:
  - block/sed-opal.c:read_table_data
  - block/sed-opal.c:read_table_data
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:generic_table_write_data
  - block/sed-opal.c:generic_get_column
  - block/sed-opal.c:generic_get_column
Direct callers:
  - block/sed-opal.c:read_table_data
  - block/sed-opal.c:read_table_data
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:generic_table_write_data
```
**Symbols:**

```
ffffffff815a3400-ffffffff815a3548: add_token_u64.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/sed-opal.c (ffffffff8160cb54)
Location: block/sed-opal.c:587
Inline: True
Inline callers:
  - block/sed-opal.c:read_table_data
  - block/sed-opal.c:read_table_data
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:generic_table_write_data
  - block/sed-opal.c:generic_get_column
  - block/sed-opal.c:generic_get_column
Direct callers:
  - block/sed-opal.c:read_table_data
  - block/sed-opal.c:read_table_data
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:generic_table_write_data
```
**Symbols:**

```
ffffffff8160bd60-ffffffff8160beeb: add_token_u64.part.0 (STB_LOCAL)
ffffffff81cda5c9-ffffffff81cda5e8: add_token_u64.part.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/sed-opal.c (ffffffff816c0c0e)
Location: block/sed-opal.c:587
Inline: True
Inline callers:
  - block/sed-opal.c:read_table_data
  - block/sed-opal.c:read_table_data
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_generic_opal_session
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:generic_table_write_data
  - block/sed-opal.c:generic_get_column
  - block/sed-opal.c:generic_get_column
Direct callers:
  - block/sed-opal.c:read_table_data
  - block/sed-opal.c:read_table_data
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_generic_opal_session
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:generic_table_write_data
```
**Symbols:**

```
ffffffff816bfd30-ffffffff816bfea1: add_token_u64.part.0 (STB_LOCAL)
ffffffff81e8e177-ffffffff81e8e196: add_token_u64.part.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/sed-opal.c (ffffffff81781d3b)
Location: block/sed-opal.c:627
Inline: True
Inline callers:
  - block/sed-opal.c:read_table_data
  - block/sed-opal.c:read_table_data
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_generic_opal_session
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:generic_table_write_data
  - block/sed-opal.c:generic_get_column
  - block/sed-opal.c:generic_get_column
Direct callers:
  - block/sed-opal.c:read_table_data
  - block/sed-opal.c:read_table_data
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_generic_opal_session
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:generic_table_write_data
```
**Symbols:**

```
ffffffff81780df0-ffffffff81780f2a: add_token_u64.part.0 (STB_LOCAL)
ffffffff820773b2-ffffffff820773c9: add_token_u64.part.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/sed-opal.c (ffffffff817c1e6b)
Location: block/sed-opal.c:635
Inline: True
Inline callers:
  - block/sed-opal.c:read_table_data
  - block/sed-opal.c:read_table_data
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_generic_opal_session
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:generic_table_write_data
  - block/sed-opal.c:generic_get_columns
  - block/sed-opal.c:generic_get_columns
Direct callers:
  - block/sed-opal.c:read_table_data
  - block/sed-opal.c:read_table_data
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_generic_opal_session
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:generic_table_write_data
```
**Symbols:**

```
ffffffff817c0cb0-ffffffff817c0e2b: add_token_u64.part.0 (STB_LOCAL)
ffffffff820f73f7-ffffffff820f740e: add_token_u64.part.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void add_token_u64(int *err, struct opal_dev *cmd, u64 number);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/sed-opal.c (ffffffff8180620d)
Location: block/sed-opal.c:748
Inline: True
Inline callers:
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
Direct callers:
  - block/sed-opal.c:read_table_data
  - block/sed-opal.c:read_table_data
  - block/sed-opal.c:activate_lsp
  - block/sed-opal.c:revert_lsp
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_generic_opal_session
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:generic_table_write_data
  - block/sed-opal.c:generic_get_columns
  - block/sed-opal.c:generic_get_columns
```
**Symbols:**

```
ffffffff81804a50-ffffffff81804bd4: add_token_u64 (STB_LOCAL)
ffffffff821d4e1f-ffffffff821d4e36: add_token_u64.cold (STB_LOCAL)
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
void add_token_u64(int *err, struct opal_dev *cmd, u64 number);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffff800010625878)
Location: block/sed-opal.c:585
Inline: False
Direct callers:
  - block/sed-opal.c:write_shadow_mbr
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:generic_get_column
  - block/sed-opal.c:generic_get_column
```
**Symbols:**

```
ffff800010625878-ffff80001062599c: add_token_u64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void add_token_u64(int *err, struct opal_dev *cmd, u64 number);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (c07cd2cc)
Location: block/sed-opal.c:585
Inline: False
Direct callers:
  - block/sed-opal.c:write_shadow_mbr
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:generic_get_column
  - block/sed-opal.c:generic_get_column
```
**Symbols:**

```
c07cd2cc-c07cd444: add_token_u64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void add_token_u64(int *err, struct opal_dev *cmd, u64 number);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (c0000000007c66c0)
Location: block/sed-opal.c:585
Inline: False
Direct callers:
  - block/sed-opal.c:write_shadow_mbr
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_generic_opal_session
  - block/sed-opal.c:start_generic_opal_session
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:generic_get_column
  - block/sed-opal.c:generic_get_column
```
**Symbols:**

```
c0000000007c66c0-c0000000007c6870: add_token_u64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void add_token_u64(int *err, struct opal_dev *cmd, u64 number);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffe000456adc)
Location: block/sed-opal.c:585
Inline: False
Direct callers:
  - block/sed-opal.c:write_shadow_mbr
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:start_generic_opal_session
  - block/sed-opal.c:start_generic_opal_session
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:generic_get_column
  - block/sed-opal.c:generic_get_column
```
**Symbols:**

```
ffffffe000456adc-ffffffe000456bfc: add_token_u64 (STB_LOCAL)
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
void add_token_u64(int *err, struct opal_dev *cmd, u64 number);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff815152c0)
Location: block/sed-opal.c:585
Inline: False
Direct callers:
  - block/sed-opal.c:write_shadow_mbr
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:generic_get_column
  - block/sed-opal.c:generic_get_column
```
**Symbols:**

```
ffffffff815152c0-ffffffff815153c7: add_token_u64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void add_token_u64(int *err, struct opal_dev *cmd, u64 number);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff815055d0)
Location: block/sed-opal.c:585
Inline: False
Direct callers:
  - block/sed-opal.c:write_shadow_mbr
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:generic_get_column
  - block/sed-opal.c:generic_get_column
```
**Symbols:**

```
ffffffff815055d0-ffffffff815056d7: add_token_u64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void add_token_u64(int *err, struct opal_dev *cmd, u64 number);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff81511350)
Location: block/sed-opal.c:585
Inline: False
Direct callers:
  - block/sed-opal.c:write_shadow_mbr
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:generic_get_column
  - block/sed-opal.c:generic_get_column
```
**Symbols:**

```
ffffffff81511350-ffffffff81511457: add_token_u64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void add_token_u64(int *err, struct opal_dev *cmd, u64 number);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff8152ab10)
Location: block/sed-opal.c:585
Inline: False
Direct callers:
  - block/sed-opal.c:write_shadow_mbr
  - block/sed-opal.c:start_auth_opal_session
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:setup_locking_range
  - block/sed-opal.c:generic_get_column
  - block/sed-opal.c:generic_get_column
```
**Symbols:**

```
ffffffff8152ab10-ffffffff8152ac17: add_token_u64 (STB_LOCAL)
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
