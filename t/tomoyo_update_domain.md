# Function: <code>tomoyo_update_domain</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int tomoyo_update_domain(struct tomoyo_acl_info *new_entry, const int size, struct tomoyo_acl_param *param, bool (*check_duplicate)(const struct tomoyo_acl_info *, const struct tomoyo_acl_info *), bool (*merge_duplicate)(struct tomoyo_acl_info *, struct tomoyo_acl_info *, const bool));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/domain.c (ffffffff8136d580)
Location: security/tomoyo/domain.c:88
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_task
  - security/tomoyo/environ.c:tomoyo_write_misc
  - security/tomoyo/file.c:tomoyo_update_mkdev_acl
  - security/tomoyo/file.c:tomoyo_update_mount_acl
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/network.c:tomoyo_write_inet_network
  - security/tomoyo/network.c:tomoyo_write_unix_network
```
**Symbols:**

```
ffffffff8136d580-ffffffff8136d6d9: tomoyo_update_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int tomoyo_update_domain(struct tomoyo_acl_info *new_entry, const int size, struct tomoyo_acl_param *param, bool (*check_duplicate)(const struct tomoyo_acl_info *, const struct tomoyo_acl_info *), bool (*merge_duplicate)(struct tomoyo_acl_info *, struct tomoyo_acl_info *, const bool));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/domain.c (ffffffff813a37d0)
Location: security/tomoyo/domain.c:88
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_task
  - security/tomoyo/environ.c:tomoyo_write_misc
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_update_mount_acl
  - security/tomoyo/file.c:tomoyo_update_mkdev_acl
  - security/tomoyo/network.c:tomoyo_write_unix_network
  - security/tomoyo/network.c:tomoyo_write_inet_network
```
**Symbols:**

```
ffffffff813a37d0-ffffffff813a391a: tomoyo_update_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int tomoyo_update_domain(struct tomoyo_acl_info *new_entry, const int size, struct tomoyo_acl_param *param, bool (*check_duplicate)(const struct tomoyo_acl_info *, const struct tomoyo_acl_info *), bool (*merge_duplicate)(struct tomoyo_acl_info *, struct tomoyo_acl_info *, const bool));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/domain.c (ffffffff813ba350)
Location: security/tomoyo/domain.c:88
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_task
  - security/tomoyo/environ.c:tomoyo_write_misc
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_update_mount_acl
  - security/tomoyo/file.c:tomoyo_update_mkdev_acl
  - security/tomoyo/network.c:tomoyo_write_unix_network
  - security/tomoyo/network.c:tomoyo_write_inet_network
```
**Symbols:**

```
ffffffff813ba350-ffffffff813ba49a: tomoyo_update_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int tomoyo_update_domain(struct tomoyo_acl_info *new_entry, const int size, struct tomoyo_acl_param *param, bool (*check_duplicate)(const struct tomoyo_acl_info *, const struct tomoyo_acl_info *), bool (*merge_duplicate)(struct tomoyo_acl_info *, struct tomoyo_acl_info *, const bool));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/domain.c (ffffffff813d0bc0)
Location: security/tomoyo/domain.c:90
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_task
  - security/tomoyo/environ.c:tomoyo_write_misc
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_update_mount_acl
  - security/tomoyo/file.c:tomoyo_update_mkdev_acl
  - security/tomoyo/network.c:tomoyo_write_unix_network
  - security/tomoyo/network.c:tomoyo_write_inet_network
```
**Symbols:**

```
ffffffff813d0bc0-ffffffff813d0d28: tomoyo_update_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int tomoyo_update_domain(struct tomoyo_acl_info *new_entry, const int size, struct tomoyo_acl_param *param, bool (*check_duplicate)(const struct tomoyo_acl_info *, const struct tomoyo_acl_info *), bool (*merge_duplicate)(struct tomoyo_acl_info *, struct tomoyo_acl_info *, const bool));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/domain.c (ffffffff813f7060)
Location: security/tomoyo/domain.c:91
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_task
  - security/tomoyo/environ.c:tomoyo_write_misc
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_update_mount_acl
  - security/tomoyo/file.c:tomoyo_update_mkdev_acl
  - security/tomoyo/network.c:tomoyo_write_unix_network
  - security/tomoyo/network.c:tomoyo_write_inet_network
```
**Symbols:**

```
ffffffff813f7060-ffffffff813f71d2: tomoyo_update_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int tomoyo_update_domain(struct tomoyo_acl_info *new_entry, const int size, struct tomoyo_acl_param *param, bool (*check_duplicate)(const struct tomoyo_acl_info *, const struct tomoyo_acl_info *), bool (*merge_duplicate)(struct tomoyo_acl_info *, struct tomoyo_acl_info *, const bool));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/domain.c (ffffffff81428020)
Location: security/tomoyo/domain.c:91
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_task
  - security/tomoyo/environ.c:tomoyo_write_misc
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_update_mount_acl
  - security/tomoyo/file.c:tomoyo_update_mkdev_acl
  - security/tomoyo/network.c:tomoyo_write_unix_network
  - security/tomoyo/network.c:tomoyo_write_inet_network
```
**Symbols:**

```
ffffffff81428020-ffffffff814281a3: tomoyo_update_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int tomoyo_update_domain(struct tomoyo_acl_info *new_entry, const int size, struct tomoyo_acl_param *param, bool (*check_duplicate)(const struct tomoyo_acl_info *, const struct tomoyo_acl_info *), bool (*merge_duplicate)(struct tomoyo_acl_info *, struct tomoyo_acl_info *, const bool));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/domain.c (ffffffff814448d0)
Location: security/tomoyo/domain.c:91
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_task
  - security/tomoyo/environ.c:tomoyo_write_misc
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_update_mount_acl
  - security/tomoyo/file.c:tomoyo_update_mkdev_acl
  - security/tomoyo/network.c:tomoyo_write_unix_network
  - security/tomoyo/network.c:tomoyo_write_inet_network
```
**Symbols:**

```
ffffffff814448d0-ffffffff81444a53: tomoyo_update_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int tomoyo_update_domain(struct tomoyo_acl_info *new_entry, const int size, struct tomoyo_acl_param *param, bool (*check_duplicate)(const struct tomoyo_acl_info *, const struct tomoyo_acl_info *), bool (*merge_duplicate)(struct tomoyo_acl_info *, struct tomoyo_acl_info *, const bool));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/domain.c (ffffffff814725c0)
Location: security/tomoyo/domain.c:91
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_task
  - security/tomoyo/environ.c:tomoyo_write_misc
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_update_mount_acl
  - security/tomoyo/file.c:tomoyo_update_mkdev_acl
  - security/tomoyo/network.c:tomoyo_write_unix_network
  - security/tomoyo/network.c:tomoyo_write_inet_network
```
**Symbols:**

```
ffffffff814725c0-ffffffff81472740: tomoyo_update_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int tomoyo_update_domain(struct tomoyo_acl_info *new_entry, const int size, struct tomoyo_acl_param *param, bool (*check_duplicate)(const struct tomoyo_acl_info *, const struct tomoyo_acl_info *), bool (*merge_duplicate)(struct tomoyo_acl_info *, struct tomoyo_acl_info *, const bool));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/domain.c (ffffffff8148c360)
Location: security/tomoyo/domain.c:92
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_task
  - security/tomoyo/environ.c:tomoyo_write_misc
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_update_mount_acl
  - security/tomoyo/file.c:tomoyo_update_mkdev_acl
  - security/tomoyo/network.c:tomoyo_write_unix_network
  - security/tomoyo/network.c:tomoyo_write_inet_network
```
**Symbols:**

```
ffffffff8148c360-ffffffff8148c4e0: tomoyo_update_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int tomoyo_update_domain(struct tomoyo_acl_info *new_entry, const int size, struct tomoyo_acl_param *param, bool (*check_duplicate)(const struct tomoyo_acl_info *, const struct tomoyo_acl_info *), bool (*merge_duplicate)(struct tomoyo_acl_info *, struct tomoyo_acl_info *, const bool));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/domain.c (ffffffff814e3600)
Location: security/tomoyo/domain.c:92
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_task
  - security/tomoyo/environ.c:tomoyo_write_env
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_update_mount_acl
  - security/tomoyo/file.c:tomoyo_update_mkdev_acl
  - security/tomoyo/network.c:tomoyo_write_unix_network
  - security/tomoyo/network.c:tomoyo_write_inet_network
```
**Symbols:**

```
ffffffff814e3600-ffffffff814e3780: tomoyo_update_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int tomoyo_update_domain(struct tomoyo_acl_info *new_entry, const int size, struct tomoyo_acl_param *param, bool (*check_duplicate)(const struct tomoyo_acl_info *, const struct tomoyo_acl_info *), bool (*merge_duplicate)(struct tomoyo_acl_info *, struct tomoyo_acl_info *, const bool));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/domain.c (ffffffff81500a30)
Location: security/tomoyo/domain.c:92
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_task
  - security/tomoyo/environ.c:tomoyo_write_env
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_update_mount_acl
  - security/tomoyo/file.c:tomoyo_update_mkdev_acl
  - security/tomoyo/network.c:tomoyo_write_unix_network
  - security/tomoyo/network.c:tomoyo_write_inet_network
```
**Symbols:**

```
ffffffff81500a30-ffffffff81500bb0: tomoyo_update_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int tomoyo_update_domain(struct tomoyo_acl_info *new_entry, const int size, struct tomoyo_acl_param *param, bool (*check_duplicate)(const struct tomoyo_acl_info *, const struct tomoyo_acl_info *), bool (*merge_duplicate)(struct tomoyo_acl_info *, struct tomoyo_acl_info *, const bool));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/domain.c (ffffffff815074c0)
Location: security/tomoyo/domain.c:92
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_task
  - security/tomoyo/environ.c:tomoyo_write_misc
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_update_mount_acl
  - security/tomoyo/file.c:tomoyo_update_mkdev_acl
  - security/tomoyo/network.c:tomoyo_write_unix_network
  - security/tomoyo/network.c:tomoyo_write_inet_network
```
**Symbols:**

```
ffffffff815074c0-ffffffff81507640: tomoyo_update_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int tomoyo_update_domain(struct tomoyo_acl_info *new_entry, const int size, struct tomoyo_acl_param *param, bool (*check_duplicate)(const struct tomoyo_acl_info *, const struct tomoyo_acl_info *), bool (*merge_duplicate)(struct tomoyo_acl_info *, struct tomoyo_acl_info *, const bool));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/tomoyo/domain.c (0)
Location: security/tomoyo/domain.c:92
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_task
  - security/tomoyo/environ.c:tomoyo_write_misc
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_update_mount_acl
  - security/tomoyo/file.c:tomoyo_update_mkdev_acl
  - security/tomoyo/network.c:tomoyo_write_unix_network
  - security/tomoyo/network.c:tomoyo_write_inet_network
```
**Symbols:**

```
ffffffff81cd5dfb-ffffffff81cd5e18: tomoyo_update_domain.cold (STB_LOCAL)
ffffffff81564630-ffffffff815647c6: tomoyo_update_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int tomoyo_update_domain(struct tomoyo_acl_info *new_entry, const int size, struct tomoyo_acl_param *param, bool (*check_duplicate)(const struct tomoyo_acl_info *, const struct tomoyo_acl_info *), bool (*merge_duplicate)(struct tomoyo_acl_info *, struct tomoyo_acl_info *, const bool));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/tomoyo/domain.c (0)
Location: security/tomoyo/domain.c:92
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_task
  - security/tomoyo/environ.c:tomoyo_write_misc
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_update_mount_acl
  - security/tomoyo/file.c:tomoyo_update_mkdev_acl
  - security/tomoyo/network.c:tomoyo_write_unix_network
  - security/tomoyo/network.c:tomoyo_write_inet_network
```
**Symbols:**

```
ffffffff81e88bd8-ffffffff81e88bf5: tomoyo_update_domain.cold (STB_LOCAL)
ffffffff815ffe00-ffffffff815fff78: tomoyo_update_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int tomoyo_update_domain(struct tomoyo_acl_info *new_entry, const int size, struct tomoyo_acl_param *param, bool (*check_duplicate)(const struct tomoyo_acl_info *, const struct tomoyo_acl_info *), bool (*merge_duplicate)(struct tomoyo_acl_info *, struct tomoyo_acl_info *, const bool));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/tomoyo/domain.c (0)
Location: security/tomoyo/domain.c:92
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_task
  - security/tomoyo/environ.c:tomoyo_write_misc
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_update_mount_acl
  - security/tomoyo/file.c:tomoyo_update_mkdev_acl
  - security/tomoyo/network.c:tomoyo_write_unix_network
  - security/tomoyo/network.c:tomoyo_write_inet_network
```
**Symbols:**

```
ffffffff82074700-ffffffff8207471d: tomoyo_update_domain.cold (STB_LOCAL)
ffffffff816b0cf0-ffffffff816b0e68: tomoyo_update_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int tomoyo_update_domain(struct tomoyo_acl_info *new_entry, const int size, struct tomoyo_acl_param *param, bool (*check_duplicate)(const struct tomoyo_acl_info *, const struct tomoyo_acl_info *), bool (*merge_duplicate)(struct tomoyo_acl_info *, struct tomoyo_acl_info *, const bool));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/tomoyo/domain.c (0)
Location: security/tomoyo/domain.c:92
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_task
  - security/tomoyo/environ.c:tomoyo_write_misc
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_update_mount_acl
  - security/tomoyo/file.c:tomoyo_update_mkdev_acl
  - security/tomoyo/network.c:tomoyo_write_unix_network
  - security/tomoyo/network.c:tomoyo_write_inet_network
```
**Symbols:**

```
ffffffff820f425a-ffffffff820f4277: tomoyo_update_domain.cold (STB_LOCAL)
ffffffff816e9700-ffffffff816e9878: tomoyo_update_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int tomoyo_update_domain(struct tomoyo_acl_info *new_entry, const int size, struct tomoyo_acl_param *param, bool (*check_duplicate)(const struct tomoyo_acl_info *, const struct tomoyo_acl_info *), bool (*merge_duplicate)(struct tomoyo_acl_info *, struct tomoyo_acl_info *, const bool));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/tomoyo/domain.c (0)
Location: security/tomoyo/domain.c:92
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_task
  - security/tomoyo/environ.c:tomoyo_write_misc
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_update_mount_acl
  - security/tomoyo/file.c:tomoyo_update_mkdev_acl
  - security/tomoyo/network.c:tomoyo_write_unix_network
  - security/tomoyo/network.c:tomoyo_write_inet_network
```
**Symbols:**

```
ffffffff821d169f-ffffffff821d16bc: tomoyo_update_domain.cold (STB_LOCAL)
ffffffff81726410-ffffffff81726588: tomoyo_update_domain (STB_GLOBAL)
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
int tomoyo_update_domain(struct tomoyo_acl_info *new_entry, const int size, struct tomoyo_acl_param *param, bool (*check_duplicate)(const struct tomoyo_acl_info *, const struct tomoyo_acl_info *), bool (*merge_duplicate)(struct tomoyo_acl_info *, struct tomoyo_acl_info *, const bool));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/domain.c (ffff80001057f6d8)
Location: security/tomoyo/domain.c:92
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_task
  - security/tomoyo/environ.c:tomoyo_write_misc
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_update_mount_acl
  - security/tomoyo/file.c:tomoyo_update_mkdev_acl
  - security/tomoyo/network.c:tomoyo_write_unix_network
  - security/tomoyo/network.c:tomoyo_write_inet_network
```
**Symbols:**

```
ffff80001057f6d8-ffff80001057f8cc: tomoyo_update_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int tomoyo_update_domain(struct tomoyo_acl_info *new_entry, const int size, struct tomoyo_acl_param *param, bool (*check_duplicate)(const struct tomoyo_acl_info *, const struct tomoyo_acl_info *), bool (*merge_duplicate)(struct tomoyo_acl_info *, struct tomoyo_acl_info *, const bool));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/domain.c (c0731c28)
Location: security/tomoyo/domain.c:92
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_task
  - security/tomoyo/environ.c:tomoyo_write_misc
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/network.c:tomoyo_write_unix_network
  - security/tomoyo/network.c:tomoyo_write_inet_network
```
**Symbols:**

```
c0731c28-c0731df0: tomoyo_update_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int tomoyo_update_domain(struct tomoyo_acl_info *new_entry, const int size, struct tomoyo_acl_param *param, bool (*check_duplicate)(const struct tomoyo_acl_info *, const struct tomoyo_acl_info *), bool (*merge_duplicate)(struct tomoyo_acl_info *, struct tomoyo_acl_info *, const bool));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/domain.c (c0000000006ec940)
Location: security/tomoyo/domain.c:92
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_task
  - security/tomoyo/environ.c:tomoyo_write_misc
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_update_mount_acl
  - security/tomoyo/file.c:tomoyo_update_mkdev_acl
  - security/tomoyo/network.c:tomoyo_write_unix_network
  - security/tomoyo/network.c:tomoyo_write_inet_network
```
**Symbols:**

```
c0000000006ec940-c0000000006ecbc4: tomoyo_update_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int tomoyo_update_domain(struct tomoyo_acl_info *new_entry, const int size, struct tomoyo_acl_param *param, bool (*check_duplicate)(const struct tomoyo_acl_info *, const struct tomoyo_acl_info *), bool (*merge_duplicate)(struct tomoyo_acl_info *, struct tomoyo_acl_info *, const bool));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/domain.c (ffffffe0003d04fe)
Location: security/tomoyo/domain.c:92
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_task
  - security/tomoyo/environ.c:tomoyo_write_misc
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_update_mount_acl
  - security/tomoyo/file.c:tomoyo_update_mkdev_acl
  - security/tomoyo/network.c:tomoyo_write_unix_network
  - security/tomoyo/network.c:tomoyo_write_inet_network
```
**Symbols:**

```
ffffffe0003d04fe-ffffffe0003d0734: tomoyo_update_domain (STB_GLOBAL)
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
int tomoyo_update_domain(struct tomoyo_acl_info *new_entry, const int size, struct tomoyo_acl_param *param, bool (*check_duplicate)(const struct tomoyo_acl_info *, const struct tomoyo_acl_info *), bool (*merge_duplicate)(struct tomoyo_acl_info *, struct tomoyo_acl_info *, const bool));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/domain.c (ffffffff81484940)
Location: security/tomoyo/domain.c:92
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_task
  - security/tomoyo/environ.c:tomoyo_write_misc
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_update_mount_acl
  - security/tomoyo/file.c:tomoyo_update_mkdev_acl
  - security/tomoyo/network.c:tomoyo_write_unix_network
  - security/tomoyo/network.c:tomoyo_write_inet_network
```
**Symbols:**

```
ffffffff81484940-ffffffff81484ac0: tomoyo_update_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int tomoyo_update_domain(struct tomoyo_acl_info *new_entry, const int size, struct tomoyo_acl_param *param, bool (*check_duplicate)(const struct tomoyo_acl_info *, const struct tomoyo_acl_info *), bool (*merge_duplicate)(struct tomoyo_acl_info *, struct tomoyo_acl_info *, const bool));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/domain.c (ffffffff81475360)
Location: security/tomoyo/domain.c:92
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_task
  - security/tomoyo/environ.c:tomoyo_write_misc
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_update_mount_acl
  - security/tomoyo/file.c:tomoyo_update_mkdev_acl
  - security/tomoyo/network.c:tomoyo_write_unix_network
  - security/tomoyo/network.c:tomoyo_write_inet_network
```
**Symbols:**

```
ffffffff81475360-ffffffff814754e0: tomoyo_update_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int tomoyo_update_domain(struct tomoyo_acl_info *new_entry, const int size, struct tomoyo_acl_param *param, bool (*check_duplicate)(const struct tomoyo_acl_info *, const struct tomoyo_acl_info *), bool (*merge_duplicate)(struct tomoyo_acl_info *, struct tomoyo_acl_info *, const bool));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/domain.c (ffffffff814809e0)
Location: security/tomoyo/domain.c:92
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_task
  - security/tomoyo/environ.c:tomoyo_write_misc
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_update_mount_acl
  - security/tomoyo/file.c:tomoyo_update_mkdev_acl
  - security/tomoyo/network.c:tomoyo_write_unix_network
  - security/tomoyo/network.c:tomoyo_write_inet_network
```
**Symbols:**

```
ffffffff814809e0-ffffffff81480b60: tomoyo_update_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int tomoyo_update_domain(struct tomoyo_acl_info *new_entry, const int size, struct tomoyo_acl_param *param, bool (*check_duplicate)(const struct tomoyo_acl_info *, const struct tomoyo_acl_info *), bool (*merge_duplicate)(struct tomoyo_acl_info *, struct tomoyo_acl_info *, const bool));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/domain.c (ffffffff81498550)
Location: security/tomoyo/domain.c:92
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_task
  - security/tomoyo/environ.c:tomoyo_write_misc
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_update_mount_acl
  - security/tomoyo/file.c:tomoyo_update_mkdev_acl
  - security/tomoyo/network.c:tomoyo_write_unix_network
  - security/tomoyo/network.c:tomoyo_write_inet_network
```
**Symbols:**

```
ffffffff81498550-ffffffff814986d0: tomoyo_update_domain (STB_GLOBAL)
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
