# Function: <code>netlink_table_ungrab</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void netlink_table_ungrab();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff8174d2c0)
Location: net/netlink/af_netlink.c:994
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:__netlink_kernel_create
  - net/netlink/af_netlink.c:netlink_realloc_groups
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_change_ngroups
  - net/netlink/genetlink.c:genl_unregister_family
```
**Symbols:**

```
ffffffff8174d2c0-ffffffff8174d2f1: netlink_table_ungrab (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void netlink_table_ungrab();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff817b96b0)
Location: net/netlink/af_netlink.c:380
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_change_ngroups
  - net/netlink/af_netlink.c:__netlink_kernel_create
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_realloc_groups
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/genetlink.c:genl_unregister_family
```
**Symbols:**

```
ffffffff817b96b0-ffffffff817b96e1: netlink_table_ungrab (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void netlink_table_ungrab();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff817e9050)
Location: net/netlink/af_netlink.c:387
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_change_ngroups
  - net/netlink/af_netlink.c:__netlink_kernel_create
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_realloc_groups
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/genetlink.c:genl_unregister_family
```
**Symbols:**

```
ffffffff817e9050-ffffffff817e9081: netlink_table_ungrab (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void netlink_table_ungrab();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81808d40)
Location: net/netlink/af_netlink.c:418
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_change_ngroups
  - net/netlink/af_netlink.c:__netlink_kernel_create
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_realloc_groups
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/genetlink.c:genl_unregister_family
```
**Symbols:**

```
ffffffff81808d40-ffffffff81808d71: netlink_table_ungrab (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void netlink_table_ungrab();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81887c10)
Location: net/netlink/af_netlink.c:420
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_change_ngroups
  - net/netlink/af_netlink.c:__netlink_kernel_create
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_realloc_groups
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/genetlink.c:genl_unregister_family
```
**Symbols:**

```
ffffffff81887c10-ffffffff81887c41: netlink_table_ungrab (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void netlink_table_ungrab();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff818db600)
Location: net/netlink/af_netlink.c:454
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/netlink/af_netlink.c:netlink_change_ngroups
  - net/netlink/af_netlink.c:__netlink_kernel_create
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_realloc_groups
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/genetlink.c:genl_unregister_family
```
**Symbols:**

```
ffffffff818db600-ffffffff818db631: netlink_table_ungrab (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void netlink_table_ungrab();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81907f00)
Location: net/netlink/af_netlink.c:454
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/netlink/af_netlink.c:netlink_change_ngroups
  - net/netlink/af_netlink.c:__netlink_kernel_create
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_realloc_groups
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/genetlink.c:genl_unregister_family
```
**Symbols:**

```
ffffffff81907f00-ffffffff81907f31: netlink_table_ungrab (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void netlink_table_ungrab();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff819691e0)
Location: net/netlink/af_netlink.c:445
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/netlink/af_netlink.c:netlink_change_ngroups
  - net/netlink/af_netlink.c:__netlink_kernel_create
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_realloc_groups
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/genetlink.c:genl_unregister_family
```
**Symbols:**

```
ffffffff819691e0-ffffffff81969211: netlink_table_ungrab (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void netlink_table_ungrab();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff8199fc80)
Location: net/netlink/af_netlink.c:445
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/netlink/af_netlink.c:netlink_change_ngroups
  - net/netlink/af_netlink.c:__netlink_kernel_create
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_realloc_groups
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/genetlink.c:genl_unregister_family
```
**Symbols:**

```
ffffffff8199fc80-ffffffff8199fcb1: netlink_table_ungrab (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void netlink_table_ungrab();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81a79400)
Location: net/netlink/af_netlink.c:445
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/netlink/af_netlink.c:netlink_change_ngroups
  - net/netlink/af_netlink.c:__netlink_kernel_create
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_realloc_groups
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/genetlink.c:genl_unregister_mc_groups
  - net/netlink/genetlink.c:genl_validate_assign_mc_groups
  - net/netlink/genetlink.c:genl_validate_assign_mc_groups
```
**Symbols:**

```
ffffffff81a79400-ffffffff81a79431: netlink_table_ungrab (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void netlink_table_ungrab();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81a82210)
Location: net/netlink/af_netlink.c:446
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/netlink/af_netlink.c:netlink_change_ngroups
  - net/netlink/af_netlink.c:__netlink_kernel_create
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_realloc_groups
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/genetlink.c:genl_unregister_mc_groups
  - net/netlink/genetlink.c:genl_validate_assign_mc_groups
  - net/netlink/genetlink.c:genl_validate_assign_mc_groups
```
**Symbols:**

```
ffffffff81a82210-ffffffff81a82241: netlink_table_ungrab (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void netlink_table_ungrab();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81a6b2f0)
Location: net/netlink/af_netlink.c:454
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/netlink/af_netlink.c:netlink_change_ngroups
  - net/netlink/af_netlink.c:__netlink_kernel_create
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_realloc_groups
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/genetlink.c:genl_unregister_family
  - net/netlink/genetlink.c:genl_validate_assign_mc_groups
  - net/netlink/genetlink.c:genl_validate_assign_mc_groups
```
**Symbols:**

```
ffffffff81a6b2f0-ffffffff81a6b321: netlink_table_ungrab (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void netlink_table_ungrab();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81b24920)
Location: net/netlink/af_netlink.c:454
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/netlink/af_netlink.c:netlink_change_ngroups
  - net/netlink/af_netlink.c:__netlink_kernel_create
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_realloc_groups
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/genetlink.c:genl_unregister_family
  - net/netlink/genetlink.c:genl_validate_assign_mc_groups
  - net/netlink/genetlink.c:genl_validate_assign_mc_groups
```
**Symbols:**

```
ffffffff81b24920-ffffffff81b24951: netlink_table_ungrab (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void netlink_table_ungrab();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81caf831)
Location: net/netlink/af_netlink.c:458
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_change_ngroups
  - net/netlink/af_netlink.c:__netlink_kernel_create
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_realloc_groups
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_release
Direct callers:
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/netlink/genetlink.c:genl_unregister_family
  - net/netlink/genetlink.c:genl_validate_assign_mc_groups
  - net/netlink/genetlink.c:genl_validate_assign_mc_groups
```
**Symbols:**

```
ffffffff81cae460-ffffffff81cae49b: netlink_table_ungrab (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void netlink_table_ungrab();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff83f0dd9b)
Location: net/netlink/af_netlink.c:458
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/netlink/af_netlink.c:netlink_change_ngroups
  - net/netlink/af_netlink.c:__netlink_kernel_create
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_realloc_groups
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_release
Direct callers:
  - net/netlink/genetlink.c:genl_unregister_family
  - net/netlink/genetlink.c:genl_validate_assign_mc_groups
  - net/netlink/genetlink.c:genl_validate_assign_mc_groups
```
**Symbols:**

```
ffffffff81e6ba70-ffffffff81e6baad: netlink_table_ungrab (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void netlink_table_ungrab();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff837343ab)
Location: net/netlink/af_netlink.c:458
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/netlink/af_netlink.c:netlink_change_ngroups
  - net/netlink/af_netlink.c:__netlink_kernel_create
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_realloc_groups
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_release
Direct callers:
  - net/netlink/genetlink.c:genl_unregister_family
  - net/netlink/genetlink.c:genl_validate_assign_mc_groups
  - net/netlink/genetlink.c:genl_validate_assign_mc_groups
```
**Symbols:**

```
ffffffff81ec7ac0-ffffffff81ec7afd: netlink_table_ungrab (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void netlink_table_ungrab();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff83968949)
Location: net/netlink/af_netlink.c:456
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/netlink/af_netlink.c:netlink_change_ngroups
  - net/netlink/af_netlink.c:__netlink_kernel_create
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_realloc_groups
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_release
Direct callers:
  - net/netlink/genetlink.c:genl_unregister_family
  - net/netlink/genetlink.c:genl_validate_assign_mc_groups
  - net/netlink/genetlink.c:genl_validate_assign_mc_groups
```
**Symbols:**

```
ffffffff81f8ae30-ffffffff81f8ae6d: netlink_table_ungrab (STB_GLOBAL)
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
void netlink_table_ungrab();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffff800010c4e130)
Location: net/netlink/af_netlink.c:445
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/netlink/af_netlink.c:netlink_change_ngroups
  - net/netlink/af_netlink.c:__netlink_kernel_create
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_realloc_groups
  - net/netlink/af_netlink.c:netlink_realloc_groups
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/genetlink.c:genl_unregister_family
```
**Symbols:**

```
ffff800010c4e130-ffff800010c4e184: netlink_table_ungrab (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void netlink_table_ungrab();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (c0d5e398)
Location: net/netlink/af_netlink.c:445
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/netlink/af_netlink.c:netlink_change_ngroups
  - net/netlink/af_netlink.c:__netlink_kernel_create
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_realloc_groups
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/genetlink.c:genl_unregister_family
```
**Symbols:**

```
c0d5e398-c0d5e3e4: netlink_table_ungrab (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void netlink_table_ungrab();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (c000000000d4c4c0)
Location: net/netlink/af_netlink.c:445
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/netlink/af_netlink.c:netlink_change_ngroups
  - net/netlink/af_netlink.c:__netlink_kernel_create
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_realloc_groups
  - net/netlink/af_netlink.c:netlink_realloc_groups
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/genetlink.c:genl_unregister_family
  - net/netlink/genetlink.c:genl_validate_assign_mc_groups
  - net/netlink/genetlink.c:genl_validate_assign_mc_groups
```
**Symbols:**

```
c000000000d4c4c0-c000000000d4c524: netlink_table_ungrab (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void netlink_table_ungrab();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffe0007ba2aa)
Location: net/netlink/af_netlink.c:445
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/netlink/af_netlink.c:netlink_change_ngroups
  - net/netlink/af_netlink.c:__netlink_kernel_create
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_realloc_groups
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/genetlink.c:genl_unregister_family
```
**Symbols:**

```
ffffffe0007ba2aa-ffffffe0007ba2ea: netlink_table_ungrab (STB_GLOBAL)
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
void netlink_table_ungrab();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff8193faf0)
Location: net/netlink/af_netlink.c:445
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/netlink/af_netlink.c:netlink_change_ngroups
  - net/netlink/af_netlink.c:__netlink_kernel_create
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_realloc_groups
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/genetlink.c:genl_unregister_family
```
**Symbols:**

```
ffffffff8193faf0-ffffffff8193fb21: netlink_table_ungrab (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void netlink_table_ungrab();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff818f95f0)
Location: net/netlink/af_netlink.c:445
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/netlink/af_netlink.c:netlink_change_ngroups
  - net/netlink/af_netlink.c:__netlink_kernel_create
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_realloc_groups
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/genetlink.c:genl_unregister_family
```
**Symbols:**

```
ffffffff818f95f0-ffffffff818f961b: netlink_table_ungrab (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void netlink_table_ungrab();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81990c80)
Location: net/netlink/af_netlink.c:445
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/netlink/af_netlink.c:netlink_change_ngroups
  - net/netlink/af_netlink.c:__netlink_kernel_create
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_realloc_groups
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/genetlink.c:genl_unregister_family
```
**Symbols:**

```
ffffffff81990c80-ffffffff81990cb1: netlink_table_ungrab (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void netlink_table_ungrab();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff819b3710)
Location: net/netlink/af_netlink.c:445
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/netlink/af_netlink.c:netlink_change_ngroups
  - net/netlink/af_netlink.c:__netlink_kernel_create
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_realloc_groups
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/genetlink.c:genl_unregister_family
```
**Symbols:**

```
ffffffff819b3710-ffffffff819b373f: netlink_table_ungrab (STB_GLOBAL)
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
