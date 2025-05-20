# Function: <code>sidtab_context_to_sid</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int sidtab_context_to_sid(struct sidtab *s, struct context *context, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/sidtab.c (ffffffff8134eb40)
Location: security/selinux/ss/sidtab.c:197
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_port_sid
  - security/selinux/ss/services.c:security_netif_sid
  - security/selinux/ss/services.c:security_netif_sid
  - security/selinux/ss/services.c:security_node_sid
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_genfs_sid
  - security/selinux/ss/services.c:security_fs_use
  - security/selinux/ss/services.c:security_fs_use
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
```
**Symbols:**

```
ffffffff8134eb40-ffffffff8134ef00: sidtab_context_to_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int sidtab_context_to_sid(struct sidtab *s, struct context *context, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/sidtab.c (ffffffff81384b40)
Location: security/selinux/ss/sidtab.c:197
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_fs_use
  - security/selinux/ss/services.c:security_fs_use
  - security/selinux/ss/services.c:security_genfs_sid
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_node_sid
  - security/selinux/ss/services.c:security_netif_sid
  - security/selinux/ss/services.c:security_netif_sid
  - security/selinux/ss/services.c:security_port_sid
```
**Symbols:**

```
ffffffff81384b40-ffffffff81384f1b: sidtab_context_to_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int sidtab_context_to_sid(struct sidtab *s, struct context *context, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/sidtab.c (ffffffff8139b5d0)
Location: security/selinux/ss/sidtab.c:197
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_fs_use
  - security/selinux/ss/services.c:security_fs_use
  - security/selinux/ss/services.c:security_genfs_sid
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_node_sid
  - security/selinux/ss/services.c:security_netif_sid
  - security/selinux/ss/services.c:security_netif_sid
  - security/selinux/ss/services.c:security_port_sid
```
**Symbols:**

```
ffffffff8139b5d0-ffffffff8139b9ab: sidtab_context_to_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int sidtab_context_to_sid(struct sidtab *s, struct context *context, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/sidtab.c (ffffffff813b1cf0)
Location: security/selinux/ss/sidtab.c:190
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_fs_use
  - security/selinux/ss/services.c:security_fs_use
  - security/selinux/ss/services.c:security_genfs_sid
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_node_sid
  - security/selinux/ss/services.c:security_netif_sid
  - security/selinux/ss/services.c:security_netif_sid
  - security/selinux/ss/services.c:security_ib_endport_sid
  - security/selinux/ss/services.c:security_ib_pkey_sid
  - security/selinux/ss/services.c:security_port_sid
```
**Symbols:**

```
ffffffff813b1cf0-ffffffff813b20f2: sidtab_context_to_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int sidtab_context_to_sid(struct sidtab *s, struct context *context, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/sidtab.c (ffffffff813d7e30)
Location: security/selinux/ss/sidtab.c:191
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_fs_use
  - security/selinux/ss/services.c:security_fs_use
  - security/selinux/ss/services.c:security_genfs_sid
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_node_sid
  - security/selinux/ss/services.c:security_netif_sid
  - security/selinux/ss/services.c:security_netif_sid
  - security/selinux/ss/services.c:security_ib_endport_sid
  - security/selinux/ss/services.c:security_ib_pkey_sid
  - security/selinux/ss/services.c:security_port_sid
  - security/selinux/ss/services.c:security_context_to_sid_core
```
**Symbols:**

```
ffffffff813d7e30-ffffffff813d8232: sidtab_context_to_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int sidtab_context_to_sid(struct sidtab *s, struct context *context, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/sidtab.c (0)
Location: security/selinux/ss/sidtab.c:191
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_fs_use
  - security/selinux/ss/services.c:security_fs_use
  - security/selinux/ss/services.c:security_genfs_sid
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_node_sid
  - security/selinux/ss/services.c:security_netif_sid
  - security/selinux/ss/services.c:security_netif_sid
  - security/selinux/ss/services.c:security_ib_endport_sid
  - security/selinux/ss/services.c:security_ib_pkey_sid
  - security/selinux/ss/services.c:security_port_sid
```
**Symbols:**

```
ffffffff81408a31-ffffffff81408a4e: sidtab_context_to_sid.cold.3 (STB_LOCAL)
ffffffff81408460-ffffffff8140882e: sidtab_context_to_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int sidtab_context_to_sid(struct sidtab *s, struct context *context, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/sidtab.c (0)
Location: security/selinux/ss/sidtab.c:339
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_fs_use
  - security/selinux/ss/services.c:security_fs_use
  - security/selinux/ss/services.c:security_genfs_sid
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_node_sid
  - security/selinux/ss/services.c:security_netif_sid
  - security/selinux/ss/services.c:security_netif_sid
  - security/selinux/ss/services.c:security_ib_endport_sid
  - security/selinux/ss/services.c:security_ib_pkey_sid
  - security/selinux/ss/services.c:security_port_sid
```
**Symbols:**

```
ffffffff81424d0d-ffffffff81424d22: sidtab_context_to_sid.cold.7 (STB_LOCAL)
ffffffff814244b0-ffffffff81424af0: sidtab_context_to_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int sidtab_context_to_sid(struct sidtab *s, struct context *context, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/sidtab.c (0)
Location: security/selinux/ss/sidtab.c:344
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_fs_use
  - security/selinux/ss/services.c:security_fs_use
  - security/selinux/ss/services.c:security_genfs_sid
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_node_sid
  - security/selinux/ss/services.c:security_netif_sid
  - security/selinux/ss/services.c:security_netif_sid
  - security/selinux/ss/services.c:security_ib_endport_sid
  - security/selinux/ss/services.c:security_ib_pkey_sid
  - security/selinux/ss/services.c:security_port_sid
```
**Symbols:**

```
ffffffff814528f8-ffffffff8145290d: sidtab_context_to_sid.cold (STB_LOCAL)
ffffffff81452020-ffffffff814526c1: sidtab_context_to_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int sidtab_context_to_sid(struct sidtab *s, struct context *context, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/sidtab.c (0)
Location: security/selinux/ss/sidtab.c:338
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_fs_use
  - security/selinux/ss/services.c:security_fs_use
  - security/selinux/ss/services.c:security_genfs_sid
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_node_sid
  - security/selinux/ss/services.c:security_netif_sid
  - security/selinux/ss/services.c:security_netif_sid
  - security/selinux/ss/services.c:security_ib_endport_sid
  - security/selinux/ss/services.c:security_ib_pkey_sid
  - security/selinux/ss/services.c:security_port_sid
```
**Symbols:**

```
ffffffff8146c698-ffffffff8146c6ad: sidtab_context_to_sid.cold (STB_LOCAL)
ffffffff8146bdf0-ffffffff8146c465: sidtab_context_to_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int sidtab_context_to_sid(struct sidtab *s, struct context *context, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/sidtab.c (0)
Location: security/selinux/ss/sidtab.c:263
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_fs_use
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_node_sid
  - security/selinux/ss/services.c:security_netif_sid
  - security/selinux/ss/services.c:security_netif_sid
  - security/selinux/ss/services.c:security_ib_endport_sid
  - security/selinux/ss/services.c:security_ib_pkey_sid
  - security/selinux/ss/services.c:security_port_sid
  - security/selinux/ss/services.c:security_context_to_sid_core
```
**Symbols:**

```
ffffffff814c0e2f-ffffffff814c0e54: sidtab_context_to_sid.cold (STB_LOCAL)
ffffffff814c0660-ffffffff814c0a5c: sidtab_context_to_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int sidtab_context_to_sid(struct sidtab *s, struct context *context, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/sidtab.c (0)
Location: security/selinux/ss/sidtab.c:263
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_fs_use
  - security/selinux/ss/services.c:__security_genfs_sid
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_node_sid
  - security/selinux/ss/services.c:security_netif_sid
  - security/selinux/ss/services.c:security_netif_sid
  - security/selinux/ss/services.c:security_ib_endport_sid
  - security/selinux/ss/services.c:security_ib_pkey_sid
  - security/selinux/ss/services.c:security_port_sid
  - security/selinux/ss/services.c:security_context_to_sid_core
```
**Symbols:**

```
ffffffff81bf070f-ffffffff81bf0734: sidtab_context_to_sid.cold (STB_LOCAL)
ffffffff814de0e0-ffffffff814de4dc: sidtab_context_to_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int sidtab_context_to_sid(struct sidtab *s, struct context *context, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/sidtab.c (0)
Location: security/selinux/ss/sidtab.c:264
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_fs_use
  - security/selinux/ss/services.c:__security_genfs_sid
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_node_sid
  - security/selinux/ss/services.c:security_netif_sid
  - security/selinux/ss/services.c:security_netif_sid
  - security/selinux/ss/services.c:security_ib_endport_sid
  - security/selinux/ss/services.c:security_ib_pkey_sid
  - security/selinux/ss/services.c:security_port_sid
  - security/selinux/ss/services.c:security_context_to_sid_core
```
**Symbols:**

```
ffffffff81be285c-ffffffff81be2881: sidtab_context_to_sid.cold (STB_LOCAL)
ffffffff814e4a40-ffffffff814e4e59: sidtab_context_to_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int sidtab_context_to_sid(struct sidtab *s, struct context *context, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/sidtab.c (0)
Location: security/selinux/ss/sidtab.c:264
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_fs_use
  - security/selinux/ss/services.c:__security_genfs_sid
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_node_sid
  - security/selinux/ss/services.c:security_netif_sid
  - security/selinux/ss/services.c:security_ib_endport_sid
  - security/selinux/ss/services.c:security_ib_pkey_sid
  - security/selinux/ss/services.c:security_port_sid
  - security/selinux/ss/services.c:security_context_to_sid_core
```
**Symbols:**

```
ffffffff81cd435a-ffffffff81cd43a0: sidtab_context_to_sid.cold (STB_LOCAL)
ffffffff8153e080-ffffffff8153e4a5: sidtab_context_to_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int sidtab_context_to_sid(struct sidtab *s, struct context *context, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/sidtab.c (0)
Location: security/selinux/ss/sidtab.c:264
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_fs_use
  - security/selinux/ss/services.c:__security_genfs_sid
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_node_sid
  - security/selinux/ss/services.c:security_netif_sid
  - security/selinux/ss/services.c:security_ib_endport_sid
  - security/selinux/ss/services.c:security_ib_pkey_sid
  - security/selinux/ss/services.c:security_port_sid
  - security/selinux/ss/services.c:security_compute_sid
  - security/selinux/ss/services.c:security_context_to_sid_core
```
**Symbols:**

```
ffffffff81e872e4-ffffffff81e87322: sidtab_context_to_sid.cold (STB_LOCAL)
ffffffff815d5a80-ffffffff815d5e81: sidtab_context_to_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int sidtab_context_to_sid(struct sidtab *s, struct context *context, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/sidtab.c (0)
Location: security/selinux/ss/sidtab.c:265
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_fs_use
  - security/selinux/ss/services.c:__security_genfs_sid
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_node_sid
  - security/selinux/ss/services.c:security_netif_sid
  - security/selinux/ss/services.c:security_ib_endport_sid
  - security/selinux/ss/services.c:security_ib_pkey_sid
  - security/selinux/ss/services.c:security_port_sid
  - security/selinux/ss/services.c:security_compute_sid
  - security/selinux/ss/services.c:security_context_to_sid_core
```
**Symbols:**

```
ffffffff82073a40-ffffffff82073a61: sidtab_context_to_sid.cold (STB_LOCAL)
ffffffff81683ce0-ffffffff81684103: sidtab_context_to_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int sidtab_context_to_sid(struct sidtab *s, struct context *context, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/sidtab.c (0)
Location: security/selinux/ss/sidtab.c:265
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_fs_use
  - security/selinux/ss/services.c:__security_genfs_sid
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_node_sid
  - security/selinux/ss/services.c:security_netif_sid
  - security/selinux/ss/services.c:security_ib_endport_sid
  - security/selinux/ss/services.c:security_ib_pkey_sid
  - security/selinux/ss/services.c:security_port_sid
  - security/selinux/ss/services.c:security_compute_sid
  - security/selinux/ss/services.c:security_context_to_sid_core
```
**Symbols:**

```
ffffffff820f3615-ffffffff820f3636: sidtab_context_to_sid.cold (STB_LOCAL)
ffffffff816bc040-ffffffff816bc47d: sidtab_context_to_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int sidtab_context_to_sid(struct sidtab *s, struct context *context, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/sidtab.c (0)
Location: security/selinux/ss/sidtab.c:265
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_fs_use
  - security/selinux/ss/services.c:__security_genfs_sid
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_node_sid
  - security/selinux/ss/services.c:security_netif_sid
  - security/selinux/ss/services.c:security_ib_endport_sid
  - security/selinux/ss/services.c:security_ib_pkey_sid
  - security/selinux/ss/services.c:security_port_sid
  - security/selinux/ss/services.c:security_compute_sid
  - security/selinux/ss/services.c:security_context_to_sid_core
```
**Symbols:**

```
ffffffff821d07ef-ffffffff821d0810: sidtab_context_to_sid.cold (STB_LOCAL)
ffffffff816f8b70-ffffffff816f8fad: sidtab_context_to_sid (STB_GLOBAL)
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
int sidtab_context_to_sid(struct sidtab *s, struct context *context, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/sidtab.c (ffff80001055ac78)
Location: security/selinux/ss/sidtab.c:338
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_fs_use
  - security/selinux/ss/services.c:security_fs_use
  - security/selinux/ss/services.c:security_genfs_sid
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_node_sid
  - security/selinux/ss/services.c:security_netif_sid
  - security/selinux/ss/services.c:security_netif_sid
  - security/selinux/ss/services.c:security_ib_endport_sid
  - security/selinux/ss/services.c:security_ib_pkey_sid
  - security/selinux/ss/services.c:security_port_sid
```
**Symbols:**

```
ffff80001055ac78-ffff80001055b27c: sidtab_context_to_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int sidtab_context_to_sid(struct sidtab *s, struct context *context, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/sidtab.c (c070f444)
Location: security/selinux/ss/sidtab.c:338
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_fs_use
  - security/selinux/ss/services.c:security_fs_use
  - security/selinux/ss/services.c:security_genfs_sid
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_node_sid
  - security/selinux/ss/services.c:security_netif_sid
  - security/selinux/ss/services.c:security_netif_sid
  - security/selinux/ss/services.c:security_ib_endport_sid
  - security/selinux/ss/services.c:security_ib_pkey_sid
  - security/selinux/ss/services.c:security_port_sid
  - security/selinux/ss/services.c:security_context_to_sid_core
```
**Symbols:**

```
c070f444-c070fb4c: sidtab_context_to_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int sidtab_context_to_sid(struct sidtab *s, struct context *context, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/sidtab.c (c0000000006b9a00)
Location: security/selinux/ss/sidtab.c:338
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_fs_use
  - security/selinux/ss/services.c:security_fs_use
  - security/selinux/ss/services.c:security_genfs_sid
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_node_sid
  - security/selinux/ss/services.c:security_netif_sid
  - security/selinux/ss/services.c:security_netif_sid
  - security/selinux/ss/services.c:security_ib_endport_sid
  - security/selinux/ss/services.c:security_ib_pkey_sid
  - security/selinux/ss/services.c:security_port_sid
```
**Symbols:**

```
c0000000006b9a00-c0000000006ba55c: sidtab_context_to_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int sidtab_context_to_sid(struct sidtab *s, struct context *context, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/sidtab.c (ffffffe0003b1b98)
Location: security/selinux/ss/sidtab.c:338
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_fs_use
  - security/selinux/ss/services.c:security_fs_use
  - security/selinux/ss/services.c:security_genfs_sid
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_node_sid
  - security/selinux/ss/services.c:security_netif_sid
  - security/selinux/ss/services.c:security_netif_sid
  - security/selinux/ss/services.c:security_ib_endport_sid
  - security/selinux/ss/services.c:security_ib_pkey_sid
  - security/selinux/ss/services.c:security_port_sid
```
**Symbols:**

```
ffffffe0003b1b98-ffffffe0003b20b8: sidtab_context_to_sid (STB_GLOBAL)
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
int sidtab_context_to_sid(struct sidtab *s, struct context *context, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/sidtab.c (0)
Location: security/selinux/ss/sidtab.c:338
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_fs_use
  - security/selinux/ss/services.c:security_fs_use
  - security/selinux/ss/services.c:security_genfs_sid
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_node_sid
  - security/selinux/ss/services.c:security_netif_sid
  - security/selinux/ss/services.c:security_netif_sid
  - security/selinux/ss/services.c:security_ib_endport_sid
  - security/selinux/ss/services.c:security_ib_pkey_sid
  - security/selinux/ss/services.c:security_port_sid
```
**Symbols:**

```
ffffffff81464c78-ffffffff81464c8d: sidtab_context_to_sid.cold (STB_LOCAL)
ffffffff814643d0-ffffffff81464a45: sidtab_context_to_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int sidtab_context_to_sid(struct sidtab *s, struct context *context, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/sidtab.c (0)
Location: security/selinux/ss/sidtab.c:338
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_fs_use
  - security/selinux/ss/services.c:security_fs_use
  - security/selinux/ss/services.c:security_genfs_sid
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_node_sid
  - security/selinux/ss/services.c:security_netif_sid
  - security/selinux/ss/services.c:security_netif_sid
  - security/selinux/ss/services.c:security_ib_endport_sid
  - security/selinux/ss/services.c:security_ib_pkey_sid
  - security/selinux/ss/services.c:security_port_sid
```
**Symbols:**

```
ffffffff814556a8-ffffffff814556bd: sidtab_context_to_sid.cold (STB_LOCAL)
ffffffff81454e00-ffffffff81455475: sidtab_context_to_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int sidtab_context_to_sid(struct sidtab *s, struct context *context, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/sidtab.c (0)
Location: security/selinux/ss/sidtab.c:338
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_fs_use
  - security/selinux/ss/services.c:security_fs_use
  - security/selinux/ss/services.c:security_genfs_sid
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_node_sid
  - security/selinux/ss/services.c:security_netif_sid
  - security/selinux/ss/services.c:security_netif_sid
  - security/selinux/ss/services.c:security_ib_endport_sid
  - security/selinux/ss/services.c:security_ib_pkey_sid
  - security/selinux/ss/services.c:security_port_sid
```
**Symbols:**

```
ffffffff81460d18-ffffffff81460d2d: sidtab_context_to_sid.cold (STB_LOCAL)
ffffffff81460470-ffffffff81460ae5: sidtab_context_to_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int sidtab_context_to_sid(struct sidtab *s, struct context *context, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/sidtab.c (0)
Location: security/selinux/ss/sidtab.c:338
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_fs_use
  - security/selinux/ss/services.c:security_fs_use
  - security/selinux/ss/services.c:security_genfs_sid
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_node_sid
  - security/selinux/ss/services.c:security_netif_sid
  - security/selinux/ss/services.c:security_netif_sid
  - security/selinux/ss/services.c:security_ib_endport_sid
  - security/selinux/ss/services.c:security_ib_pkey_sid
  - security/selinux/ss/services.c:security_port_sid
```
**Symbols:**

```
ffffffff81478518-ffffffff8147852d: sidtab_context_to_sid.cold (STB_LOCAL)
ffffffff81477c70-ffffffff814782e5: sidtab_context_to_sid (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>u32 *sid</code>
</li>
<li>
<b>Param removed. </b>
<code>u32 *out_sid</code>
</li>
</ul>
</details>
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
