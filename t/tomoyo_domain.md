# Function: <code>tomoyo_domain</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/tomoyo/common.c (ffffffff8136b5ca)
Location: security/tomoyo/common.h:1203
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_control
```
```
In security/tomoyo/domain.c (ffffffff8136dca5)
Location: security/tomoyo/common.h:1203
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_find_next_domain
```
```
In security/tomoyo/securityfs_if.c (ffffffff81372d46)
Location: security/tomoyo/common.h:1203
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_read_self
```
```
In security/tomoyo/tomoyo.c (ffffffff8137352b)
Location: security/tomoyo/common.h:1203
Inline: True
Inline callers:
  - security/tomoyo/tomoyo.c:tomoyo_file_open
```
```
In security/tomoyo/util.c (ffffffff8137480f)
Location: security/tomoyo/common.h:1203
Inline: True
Inline callers:
  - security/tomoyo/util.c:tomoyo_init_request_info
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/tomoyo/common.c (ffffffff813a17ba)
Location: security/tomoyo/common.h:1203
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_control
```
```
In security/tomoyo/domain.c (ffffffff813a4381)
Location: security/tomoyo/common.h:1203
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
```
```
In security/tomoyo/securityfs_if.c (ffffffff813a92f6)
Location: security/tomoyo/common.h:1203
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_read_self
```
```
In security/tomoyo/tomoyo.c (ffffffff813a994b)
Location: security/tomoyo/common.h:1203
Inline: True
Inline callers:
  - security/tomoyo/tomoyo.c:tomoyo_file_open
```
```
In security/tomoyo/util.c (ffffffff813aac0f)
Location: security/tomoyo/common.h:1203
Inline: True
Inline callers:
  - security/tomoyo/util.c:tomoyo_init_request_info
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/tomoyo/common.c (ffffffff813b833a)
Location: security/tomoyo/common.h:1203
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_control
```
```
In security/tomoyo/domain.c (ffffffff813baf01)
Location: security/tomoyo/common.h:1203
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
```
```
In security/tomoyo/securityfs_if.c (ffffffff813bfe66)
Location: security/tomoyo/common.h:1203
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_read_self
```
```
In security/tomoyo/tomoyo.c (ffffffff813c04bb)
Location: security/tomoyo/common.h:1203
Inline: True
Inline callers:
  - security/tomoyo/tomoyo.c:tomoyo_file_open
```
```
In security/tomoyo/util.c (ffffffff813c178f)
Location: security/tomoyo/common.h:1203
Inline: True
Inline callers:
  - security/tomoyo/util.c:tomoyo_init_request_info
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/tomoyo/common.c (ffffffff813cebc2)
Location: security/tomoyo/common.h:1220
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_control
```
```
In security/tomoyo/domain.c (ffffffff813d174d)
Location: security/tomoyo/common.h:1220
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
```
```
In security/tomoyo/securityfs_if.c (ffffffff813d6756)
Location: security/tomoyo/common.h:1220
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_read_self
```
```
In security/tomoyo/tomoyo.c (ffffffff813d6df8)
Location: security/tomoyo/common.h:1220
Inline: True
Inline callers:
  - security/tomoyo/tomoyo.c:tomoyo_file_open
```
```
In security/tomoyo/util.c (ffffffff813d811f)
Location: security/tomoyo/common.h:1220
Inline: True
Inline callers:
  - security/tomoyo/util.c:tomoyo_init_request_info
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/tomoyo/common.c (ffffffff813f5074)
Location: security/tomoyo/common.h:1222
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_control
```
```
In security/tomoyo/domain.c (ffffffff813f7c5d)
Location: security/tomoyo/common.h:1222
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
```
```
In security/tomoyo/securityfs_if.c (ffffffff813fcc86)
Location: security/tomoyo/common.h:1222
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_read_self
```
```
In security/tomoyo/tomoyo.c (ffffffff813fd32d)
Location: security/tomoyo/common.h:1222
Inline: True
Inline callers:
  - security/tomoyo/tomoyo.c:tomoyo_file_open
```
```
In security/tomoyo/util.c (ffffffff813fe56f)
Location: security/tomoyo/common.h:1222
Inline: True
Inline callers:
  - security/tomoyo/util.c:tomoyo_init_request_info
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/tomoyo/common.c (ffffffff81425f50)
Location: security/tomoyo/common.h:1204
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_control
```
```
In security/tomoyo/domain.c (ffffffff81428c41)
Location: security/tomoyo/common.h:1204
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
```
```
In security/tomoyo/securityfs_if.c (ffffffff8142dbb5)
Location: security/tomoyo/common.h:1204
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_read_self
```
```
In security/tomoyo/tomoyo.c (ffffffff8142e22f)
Location: security/tomoyo/common.h:1204
Inline: True
Inline callers:
  - security/tomoyo/tomoyo.c:tomoyo_file_open
```
```
In security/tomoyo/util.c (ffffffff8142f475)
Location: security/tomoyo/common.h:1204
Inline: True
Inline callers:
  - security/tomoyo/util.c:tomoyo_init_request_info
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/tomoyo/common.c (ffffffff81442640)
Location: security/tomoyo/common.h:1218
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_control
```
```
In security/tomoyo/domain.c (ffffffff8144550c)
Location: security/tomoyo/common.h:1218
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
```
```
In security/tomoyo/securityfs_if.c (ffffffff828ce8b4)
Location: security/tomoyo/common.h:1218
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/tomoyo/securityfs_if.c:tomoyo_read_self
```
```
In security/tomoyo/tomoyo.c (ffffffff8144ab9f)
Location: security/tomoyo/common.h:1218
Inline: True
Inline callers:
  - security/tomoyo/tomoyo.c:tomoyo_file_open
```
```
In security/tomoyo/util.c (ffffffff8144be95)
Location: security/tomoyo/common.h:1218
Inline: True
Inline callers:
  - security/tomoyo/util.c:tomoyo_init_request_info
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct tomoyo_domain_info *tomoyo_domain();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/tomoyo.c (ffffffff81478950)
Location: security/tomoyo/tomoyo.c:16
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/tomoyo/securityfs_if.c:tomoyo_read_self
  - security/tomoyo/util.c:tomoyo_init_request_info
```
**Symbols:**

```
ffffffff81478950-ffffffff81478993: tomoyo_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct tomoyo_domain_info *tomoyo_domain();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/tomoyo.c (ffffffff81492670)
Location: security/tomoyo/tomoyo.c:16
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/tomoyo/securityfs_if.c:tomoyo_read_self
  - security/tomoyo/util.c:tomoyo_init_request_info
```
**Symbols:**

```
ffffffff81492670-ffffffff814926b3: tomoyo_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct tomoyo_domain_info *tomoyo_domain();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/tomoyo.c (ffffffff814e9a60)
Location: security/tomoyo/tomoyo.c:16
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_manager
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_namespace_jump
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/tomoyo/securityfs_if.c:tomoyo_read_self
  - security/tomoyo/util.c:tomoyo_init_request_info
```
**Symbols:**

```
ffffffff814e9a60-ffffffff814e9aa3: tomoyo_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct tomoyo_domain_info *tomoyo_domain();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/tomoyo.c (ffffffff81506d80)
Location: security/tomoyo/tomoyo.c:16
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_manager
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_namespace_jump
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/tomoyo/securityfs_if.c:tomoyo_read_self
  - security/tomoyo/util.c:tomoyo_init_request_info
```
**Symbols:**

```
ffffffff81506d80-ffffffff81506dc3: tomoyo_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct tomoyo_domain_info *tomoyo_domain();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/tomoyo.c (ffffffff8150d8c0)
Location: security/tomoyo/tomoyo.c:16
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/tomoyo/securityfs_if.c:tomoyo_read_self
  - security/tomoyo/util.c:tomoyo_init_request_info
```
**Symbols:**

```
ffffffff8150d8c0-ffffffff8150d903: tomoyo_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct tomoyo_domain_info *tomoyo_domain();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/tomoyo.c (ffffffff8156b410)
Location: security/tomoyo/tomoyo.c:16
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_manager
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/tomoyo/securityfs_if.c:tomoyo_read_self
  - security/tomoyo/util.c:tomoyo_init_request_info
```
**Symbols:**

```
ffffffff8156b410-ffffffff8156b453: tomoyo_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct tomoyo_domain_info *tomoyo_domain();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/tomoyo.c (ffffffff81607610)
Location: security/tomoyo/tomoyo.c:16
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_manager
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/tomoyo/securityfs_if.c:tomoyo_read_self
  - security/tomoyo/util.c:tomoyo_init_request_info
```
**Symbols:**

```
ffffffff81607610-ffffffff8160765b: tomoyo_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct tomoyo_domain_info *tomoyo_domain();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/tomoyo.c (ffffffff816b8d50)
Location: security/tomoyo/tomoyo.c:17
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_manager
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/tomoyo/securityfs_if.c:tomoyo_read_self
  - security/tomoyo/util.c:tomoyo_init_request_info
```
**Symbols:**

```
ffffffff816b8d50-ffffffff816b8d9b: tomoyo_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct tomoyo_domain_info *tomoyo_domain();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/tomoyo.c (ffffffff816f1730)
Location: security/tomoyo/tomoyo.c:17
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_manager
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/tomoyo/securityfs_if.c:tomoyo_read_self
  - security/tomoyo/util.c:tomoyo_init_request_info
```
**Symbols:**

```
ffffffff816f1730-ffffffff816f177b: tomoyo_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct tomoyo_domain_info *tomoyo_domain();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/tomoyo.c (ffffffff8172e500)
Location: security/tomoyo/tomoyo.c:17
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_manager
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/tomoyo/securityfs_if.c:tomoyo_read_self
  - security/tomoyo/tomoyo.c:tomoyo_file_open
  - security/tomoyo/util.c:tomoyo_init_request_info
```
**Symbols:**

```
ffffffff8172e500-ffffffff8172e54b: tomoyo_domain (STB_GLOBAL)
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
struct tomoyo_domain_info *tomoyo_domain();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/tomoyo.c (ffff800010587478)
Location: security/tomoyo/tomoyo.c:16
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/tomoyo/securityfs_if.c:tomoyo_read_self
  - security/tomoyo/util.c:tomoyo_init_request_info
```
**Symbols:**

```
ffff800010587478-ffff8000105874f4: tomoyo_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct tomoyo_domain_info *tomoyo_domain();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/tomoyo.c (c0738a64)
Location: security/tomoyo/tomoyo.c:16
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/tomoyo/securityfs_if.c:tomoyo_read_self
  - security/tomoyo/util.c:tomoyo_init_request_info
```
**Symbols:**

```
c0738a64-c0738adc: tomoyo_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct tomoyo_domain_info *tomoyo_domain();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/tomoyo.c (c0000000006f7480)
Location: security/tomoyo/tomoyo.c:16
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/tomoyo/securityfs_if.c:tomoyo_read_self
  - security/tomoyo/util.c:tomoyo_init_request_info
```
**Symbols:**

```
c0000000006f7480-c0000000006f74e0: tomoyo_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct tomoyo_domain_info *tomoyo_domain();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/tomoyo/tomoyo.c (ffffffe0003d6858)
Location: security/tomoyo/tomoyo.c:16
Inline: True
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/tomoyo/securityfs_if.c:tomoyo_read_self
  - security/tomoyo/util.c:tomoyo_init_request_info
```
**Symbols:**

```
ffffffe0003d69b4-ffffffe0003d69fc: tomoyo_domain (STB_GLOBAL)
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
struct tomoyo_domain_info *tomoyo_domain();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/tomoyo.c (ffffffff8148ac50)
Location: security/tomoyo/tomoyo.c:16
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/tomoyo/securityfs_if.c:tomoyo_read_self
  - security/tomoyo/util.c:tomoyo_init_request_info
```
**Symbols:**

```
ffffffff8148ac50-ffffffff8148ac93: tomoyo_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct tomoyo_domain_info *tomoyo_domain();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/tomoyo.c (ffffffff8147b670)
Location: security/tomoyo/tomoyo.c:16
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/tomoyo/securityfs_if.c:tomoyo_read_self
  - security/tomoyo/util.c:tomoyo_init_request_info
```
**Symbols:**

```
ffffffff8147b670-ffffffff8147b6b3: tomoyo_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct tomoyo_domain_info *tomoyo_domain();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/tomoyo.c (ffffffff81486cf0)
Location: security/tomoyo/tomoyo.c:16
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/tomoyo/securityfs_if.c:tomoyo_read_self
  - security/tomoyo/util.c:tomoyo_init_request_info
```
**Symbols:**

```
ffffffff81486cf0-ffffffff81486d33: tomoyo_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct tomoyo_domain_info *tomoyo_domain();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/tomoyo.c (ffffffff8149e830)
Location: security/tomoyo/tomoyo.c:16
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/securityfs_if.c:tomoyo_initerface_init
  - security/tomoyo/securityfs_if.c:tomoyo_read_self
  - security/tomoyo/util.c:tomoyo_init_request_info
```
**Symbols:**

```
ffffffff8149e830-ffffffff8149e873: tomoyo_domain (STB_GLOBAL)
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
