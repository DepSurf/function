# Function: <code>netlink_table_grab</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void netlink_table_grab();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff8174d1c0)
Location: net/netlink/af_netlink.c:969
Inline: True
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
ffffffff8174d1c0-ffffffff8174d2bb: netlink_table_grab (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void netlink_table_grab();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff817b9580)
Location: net/netlink/af_netlink.c:355
Inline: True
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
ffffffff817b9580-ffffffff817b96a3: netlink_table_grab (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void netlink_table_grab();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff817e8f20)
Location: net/netlink/af_netlink.c:362
Inline: True
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
ffffffff817e8f20-ffffffff817e9046: netlink_table_grab (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void netlink_table_grab();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81808c10)
Location: net/netlink/af_netlink.c:393
Inline: True
Direct callers:
  - net/netlink/af_netlink.c:netlink_change_ngroups
  - net/netlink/af_netlink.c:__netlink_kernel_create
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_realloc_groups
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/genetlink.c:genl_unregister_family
```
**Symbols:**

```
ffffffff81808c10-ffffffff81808d36: netlink_table_grab (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void netlink_table_grab();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81887ad0)
Location: net/netlink/af_netlink.c:395
Inline: True
Direct callers:
  - net/netlink/af_netlink.c:netlink_change_ngroups
  - net/netlink/af_netlink.c:__netlink_kernel_create
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_realloc_groups
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/genetlink.c:genl_unregister_family
```
**Symbols:**

```
ffffffff81887ad0-ffffffff81887c02: netlink_table_grab (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void netlink_table_grab();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff818db4c0)
Location: net/netlink/af_netlink.c:429
Inline: True
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
ffffffff818db4c0-ffffffff818db5f2: netlink_table_grab (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void netlink_table_grab();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81907dc0)
Location: net/netlink/af_netlink.c:429
Inline: True
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
ffffffff81907dc0-ffffffff81907ef2: netlink_table_grab (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void netlink_table_grab();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff819690e0)
Location: net/netlink/af_netlink.c:420
Inline: True
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
ffffffff819690e0-ffffffff819691dd: netlink_table_grab (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void netlink_table_grab();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff8199fb80)
Location: net/netlink/af_netlink.c:420
Inline: True
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
ffffffff8199fb80-ffffffff8199fc7d: netlink_table_grab (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void netlink_table_grab();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81a7b4f5)
Location: net/netlink/af_netlink.c:420
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_change_ngroups
  - net/netlink/af_netlink.c:__netlink_kernel_create
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_realloc_groups
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_remove
Direct callers:
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/netlink/af_netlink.c:netlink_change_ngroups
  - net/netlink/af_netlink.c:__netlink_kernel_create
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_realloc_groups
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/genetlink.c:genl_unregister_mc_groups
  - net/netlink/genetlink.c:genl_validate_assign_mc_groups
```
**Symbols:**

```
ffffffff81a77310-ffffffff81a773fb: netlink_table_grab.part.0 (STB_LOCAL)
ffffffff81a793d0-ffffffff81a793fd: netlink_table_grab (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void netlink_table_grab();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81a84375)
Location: net/netlink/af_netlink.c:421
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_change_ngroups
  - net/netlink/af_netlink.c:__netlink_kernel_create
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_realloc_groups
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_remove
Direct callers:
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/netlink/af_netlink.c:netlink_change_ngroups
  - net/netlink/af_netlink.c:__netlink_kernel_create
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_realloc_groups
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/genetlink.c:genl_unregister_mc_groups
  - net/netlink/genetlink.c:genl_validate_assign_mc_groups
```
**Symbols:**

```
ffffffff81a80070-ffffffff81a8015b: netlink_table_grab.part.0 (STB_LOCAL)
ffffffff81a821e0-ffffffff81a8220d: netlink_table_grab (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void netlink_table_grab();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81a6d465)
Location: net/netlink/af_netlink.c:429
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_change_ngroups
  - net/netlink/af_netlink.c:__netlink_kernel_create
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_realloc_groups
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_remove
Direct callers:
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/netlink/af_netlink.c:netlink_change_ngroups
  - net/netlink/af_netlink.c:__netlink_kernel_create
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_realloc_groups
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/genetlink.c:genl_unregister_family
  - net/netlink/genetlink.c:genl_validate_assign_mc_groups
```
**Symbols:**

```
ffffffff81a69080-ffffffff81a69158: netlink_table_grab.part.0 (STB_LOCAL)
ffffffff81a6b2c0-ffffffff81a6b2ed: netlink_table_grab (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void netlink_table_grab();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81b26ae5)
Location: net/netlink/af_netlink.c:429
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
  - net/netlink/af_netlink.c:netlink_change_ngroups
  - net/netlink/af_netlink.c:__netlink_kernel_create
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_realloc_groups
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/genetlink.c:genl_unregister_family
  - net/netlink/genetlink.c:genl_validate_assign_mc_groups
```
**Symbols:**

```
ffffffff81b22640-ffffffff81b22707: netlink_table_grab.part.0 (STB_LOCAL)
ffffffff81b248f0-ffffffff81b2491d: netlink_table_grab (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void netlink_table_grab();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81caf7f5)
Location: net/netlink/af_netlink.c:433
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
  - net/netlink/af_netlink.c:netlink_change_ngroups
  - net/netlink/af_netlink.c:__netlink_kernel_create
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_realloc_groups
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/genetlink.c:genl_unregister_family
  - net/netlink/genetlink.c:genl_validate_assign_mc_groups
```
**Symbols:**

```
ffffffff81caa8d0-ffffffff81caa99f: netlink_table_grab.part.0 (STB_LOCAL)
ffffffff81cae420-ffffffff81cae45d: netlink_table_grab (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void netlink_table_grab();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff83f0dd37)
Location: net/netlink/af_netlink.c:433
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
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/netlink/af_netlink.c:netlink_change_ngroups
  - net/netlink/af_netlink.c:__netlink_kernel_create
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_realloc_groups
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/genetlink.c:genl_unregister_family
  - net/netlink/genetlink.c:genl_validate_assign_mc_groups
```
**Symbols:**

```
ffffffff81e679b0-ffffffff81e67a7f: netlink_table_grab.part.0 (STB_LOCAL)
ffffffff81e6ba20-ffffffff81e6ba5d: netlink_table_grab (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void netlink_table_grab();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff83734347)
Location: net/netlink/af_netlink.c:433
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
```
**Symbols:**

```
ffffffff81ec3790-ffffffff81ec385f: netlink_table_grab.part.0 (STB_LOCAL)
ffffffff81ec7a70-ffffffff81ec7aad: netlink_table_grab (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void netlink_table_grab();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff839688e5)
Location: net/netlink/af_netlink.c:431
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
```
**Symbols:**

```
ffffffff81f86bb0-ffffffff81f86c7f: netlink_table_grab.part.0 (STB_LOCAL)
ffffffff81f8ade0-ffffffff81f8ae1d: netlink_table_grab (STB_GLOBAL)
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
void netlink_table_grab();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffff800010c4df80)
Location: net/netlink/af_netlink.c:420
Inline: True
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
ffff800010c4df80-ffff800010c4e12c: netlink_table_grab (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void netlink_table_grab();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (c0d5e248)
Location: net/netlink/af_netlink.c:420
Inline: True
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
c0d5e248-c0d5e398: netlink_table_grab (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void netlink_table_grab();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (c000000000d4c340)
Location: net/netlink/af_netlink.c:420
Inline: True
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
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/genetlink.c:genl_unregister_family
  - net/netlink/genetlink.c:genl_validate_assign_mc_groups
```
**Symbols:**

```
c000000000d4c340-c000000000d4c4b4: netlink_table_grab (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void netlink_table_grab();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffe0007ba1ba)
Location: net/netlink/af_netlink.c:420
Inline: True
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
ffffffe0007ba1ba-ffffffe0007ba2aa: netlink_table_grab (STB_GLOBAL)
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
void netlink_table_grab();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff8193f9f0)
Location: net/netlink/af_netlink.c:420
Inline: True
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
ffffffff8193f9f0-ffffffff8193faed: netlink_table_grab (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void netlink_table_grab();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff818f94f0)
Location: net/netlink/af_netlink.c:420
Inline: True
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
ffffffff818f94f0-ffffffff818f95e7: netlink_table_grab (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void netlink_table_grab();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81990b80)
Location: net/netlink/af_netlink.c:420
Inline: True
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
ffffffff81990b80-ffffffff81990c7d: netlink_table_grab (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void netlink_table_grab();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff819b3610)
Location: net/netlink/af_netlink.c:420
Inline: True
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
ffffffff819b3610-ffffffff819b3706: netlink_table_grab (STB_GLOBAL)
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
