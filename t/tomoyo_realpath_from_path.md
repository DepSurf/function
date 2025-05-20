# Function: <code>tomoyo_realpath_from_path</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
char *tomoyo_realpath_from_path(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/realpath.c (ffffffff81372a70)
Location: security/tomoyo/realpath.c:250
Inline: False
Direct callers:
  - security/tomoyo/audit.c:tomoyo_init_log
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/file.c:tomoyo_path_number_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/realpath.c:tomoyo_realpath_nofollow
  - security/tomoyo/util.c:tomoyo_get_exe
```
**Symbols:**

```
ffffffff81372a70-ffffffff81372c95: tomoyo_realpath_from_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
char *tomoyo_realpath_from_path(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/realpath.c (ffffffff813a8e90)
Location: security/tomoyo/realpath.c:250
Inline: False
Direct callers:
  - security/tomoyo/audit.c:tomoyo_init_log
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/realpath.c:tomoyo_realpath_nofollow
  - security/tomoyo/util.c:tomoyo_get_exe
```
**Symbols:**

```
ffffffff813a8e90-ffffffff813a90b3: tomoyo_realpath_from_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
char *tomoyo_realpath_from_path(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/realpath.c (ffffffff813bfa10)
Location: security/tomoyo/realpath.c:250
Inline: False
Direct callers:
  - security/tomoyo/audit.c:tomoyo_init_log
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/realpath.c:tomoyo_realpath_nofollow
  - security/tomoyo/util.c:tomoyo_get_exe
```
**Symbols:**

```
ffffffff813bfa10-ffffffff813bfc22: tomoyo_realpath_from_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
char *tomoyo_realpath_from_path(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/realpath.c (ffffffff813d62f0)
Location: security/tomoyo/realpath.c:250
Inline: False
Direct callers:
  - security/tomoyo/audit.c:tomoyo_init_log
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/realpath.c:tomoyo_realpath_nofollow
  - security/tomoyo/util.c:tomoyo_get_exe
```
**Symbols:**

```
ffffffff813d62f0-ffffffff813d64f0: tomoyo_realpath_from_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
char *tomoyo_realpath_from_path(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/realpath.c (ffffffff813fc810)
Location: security/tomoyo/realpath.c:251
Inline: False
Direct callers:
  - security/tomoyo/audit.c:tomoyo_init_log
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/realpath.c:tomoyo_realpath_nofollow
  - security/tomoyo/util.c:tomoyo_get_exe
```
**Symbols:**

```
ffffffff813fc810-ffffffff813fca13: tomoyo_realpath_from_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
char *tomoyo_realpath_from_path(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/realpath.c (ffffffff8142d740)
Location: security/tomoyo/realpath.c:251
Inline: False
Direct callers:
  - security/tomoyo/audit.c:tomoyo_init_log
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/realpath.c:tomoyo_realpath_nofollow
  - security/tomoyo/util.c:tomoyo_get_exe
```
**Symbols:**

```
ffffffff8142d740-ffffffff8142d93e: tomoyo_realpath_from_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
char *tomoyo_realpath_from_path(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/realpath.c (ffffffff8144a090)
Location: security/tomoyo/realpath.c:251
Inline: False
Direct callers:
  - security/tomoyo/audit.c:tomoyo_init_log
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/realpath.c:tomoyo_realpath_nofollow
  - security/tomoyo/util.c:tomoyo_get_exe
```
**Symbols:**

```
ffffffff8144a090-ffffffff8144a284: tomoyo_realpath_from_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
char *tomoyo_realpath_from_path(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/realpath.c (ffffffff81477d00)
Location: security/tomoyo/realpath.c:260
Inline: False
Direct callers:
  - security/tomoyo/audit.c:tomoyo_init_log
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/realpath.c:tomoyo_realpath_nofollow
  - security/tomoyo/util.c:tomoyo_get_exe
```
**Symbols:**

```
ffffffff81477d00-ffffffff81477f15: tomoyo_realpath_from_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
char *tomoyo_realpath_from_path(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/realpath.c (ffffffff81491aa0)
Location: security/tomoyo/realpath.c:235
Inline: False
Direct callers:
  - security/tomoyo/audit.c:tomoyo_init_log
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/realpath.c:tomoyo_realpath_nofollow
  - security/tomoyo/util.c:tomoyo_get_exe
```
**Symbols:**

```
ffffffff81491aa0-ffffffff81491c25: tomoyo_realpath_from_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
char *tomoyo_realpath_from_path(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/realpath.c (ffffffff814e8e90)
Location: security/tomoyo/realpath.c:237
Inline: False
Direct callers:
  - security/tomoyo/audit.c:tomoyo_init_log
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/realpath.c:tomoyo_realpath_nofollow
  - security/tomoyo/util.c:tomoyo_get_exe
```
**Symbols:**

```
ffffffff814e8e90-ffffffff814e9028: tomoyo_realpath_from_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
char *tomoyo_realpath_from_path(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/realpath.c (ffffffff815061d0)
Location: security/tomoyo/realpath.c:237
Inline: False
Direct callers:
  - security/tomoyo/audit.c:tomoyo_init_log
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/realpath.c:tomoyo_realpath_nofollow
  - security/tomoyo/util.c:tomoyo_get_exe
```
**Symbols:**

```
ffffffff815061d0-ffffffff81506368: tomoyo_realpath_from_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
char *tomoyo_realpath_from_path(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/realpath.c (ffffffff8150cd10)
Location: security/tomoyo/realpath.c:237
Inline: False
Direct callers:
  - security/tomoyo/audit.c:tomoyo_init_log
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/realpath.c:tomoyo_realpath_nofollow
  - security/tomoyo/util.c:tomoyo_get_exe
```
**Symbols:**

```
ffffffff8150cd10-ffffffff8150cea8: tomoyo_realpath_from_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
char *tomoyo_realpath_from_path(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/realpath.c (ffffffff8156a840)
Location: security/tomoyo/realpath.c:237
Inline: False
Direct callers:
  - security/tomoyo/audit.c:tomoyo_init_log
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/realpath.c:tomoyo_realpath_nofollow
  - security/tomoyo/util.c:tomoyo_get_exe
```
**Symbols:**

```
ffffffff8156a840-ffffffff8156a9d8: tomoyo_realpath_from_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
char *tomoyo_realpath_from_path(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/realpath.c (ffffffff81606800)
Location: security/tomoyo/realpath.c:237
Inline: False
Direct callers:
  - security/tomoyo/audit.c:tomoyo_init_log
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/realpath.c:tomoyo_realpath_nofollow
  - security/tomoyo/util.c:tomoyo_get_exe
```
**Symbols:**

```
ffffffff81606800-ffffffff816069aa: tomoyo_realpath_from_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
char *tomoyo_realpath_from_path(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/realpath.c (ffffffff816b7cc0)
Location: security/tomoyo/realpath.c:237
Inline: False
Direct callers:
  - security/tomoyo/audit.c:tomoyo_init_log
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/realpath.c:tomoyo_realpath_nofollow
  - security/tomoyo/util.c:tomoyo_get_exe
```
**Symbols:**

```
ffffffff816b7cc0-ffffffff816b7e66: tomoyo_realpath_from_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
char *tomoyo_realpath_from_path(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/realpath.c (ffffffff816f0690)
Location: security/tomoyo/realpath.c:237
Inline: False
Direct callers:
  - security/tomoyo/audit.c:tomoyo_init_log
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/realpath.c:tomoyo_realpath_nofollow
  - security/tomoyo/util.c:tomoyo_get_exe
```
**Symbols:**

```
ffffffff816f0690-ffffffff816f0831: tomoyo_realpath_from_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
char *tomoyo_realpath_from_path(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/realpath.c (ffffffff8172d460)
Location: security/tomoyo/realpath.c:237
Inline: False
Direct callers:
  - security/tomoyo/audit.c:tomoyo_init_log
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/realpath.c:tomoyo_realpath_nofollow
  - security/tomoyo/util.c:tomoyo_get_exe
```
**Symbols:**

```
ffffffff8172d460-ffffffff8172d601: tomoyo_realpath_from_path (STB_GLOBAL)
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
char *tomoyo_realpath_from_path(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/realpath.c (ffff800010586208)
Location: security/tomoyo/realpath.c:235
Inline: False
Direct callers:
  - security/tomoyo/audit.c:tomoyo_init_log
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/realpath.c:tomoyo_realpath_nofollow
  - security/tomoyo/util.c:tomoyo_get_exe
```
**Symbols:**

```
ffff800010586208-ffff8000105863ac: tomoyo_realpath_from_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
char *tomoyo_realpath_from_path(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/realpath.c (c0737af8)
Location: security/tomoyo/realpath.c:235
Inline: False
Direct callers:
  - security/tomoyo/audit.c:tomoyo_init_log
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/realpath.c:tomoyo_realpath_nofollow
  - security/tomoyo/util.c:tomoyo_get_exe
```
**Symbols:**

```
c0737af8-c0737ca0: tomoyo_realpath_from_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
char *tomoyo_realpath_from_path(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/realpath.c (c0000000006f5ef0)
Location: security/tomoyo/realpath.c:235
Inline: False
Direct callers:
  - security/tomoyo/audit.c:tomoyo_init_log
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/realpath.c:tomoyo_realpath_nofollow
  - security/tomoyo/util.c:tomoyo_get_exe
```
**Symbols:**

```
c0000000006f5ef0-c0000000006f614c: tomoyo_realpath_from_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
char *tomoyo_realpath_from_path(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/realpath.c (ffffffe0003d5bb4)
Location: security/tomoyo/realpath.c:235
Inline: False
Direct callers:
  - security/tomoyo/audit.c:tomoyo_init_log
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/realpath.c:tomoyo_realpath_nofollow
  - security/tomoyo/util.c:tomoyo_get_exe
```
**Symbols:**

```
ffffffe0003d5bb4-ffffffe0003d5d40: tomoyo_realpath_from_path (STB_GLOBAL)
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
char *tomoyo_realpath_from_path(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/realpath.c (ffffffff8148a080)
Location: security/tomoyo/realpath.c:235
Inline: False
Direct callers:
  - security/tomoyo/audit.c:tomoyo_init_log
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/realpath.c:tomoyo_realpath_nofollow
  - security/tomoyo/util.c:tomoyo_get_exe
```
**Symbols:**

```
ffffffff8148a080-ffffffff8148a205: tomoyo_realpath_from_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
char *tomoyo_realpath_from_path(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/realpath.c (ffffffff8147aaa0)
Location: security/tomoyo/realpath.c:235
Inline: False
Direct callers:
  - security/tomoyo/audit.c:tomoyo_init_log
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/realpath.c:tomoyo_realpath_nofollow
  - security/tomoyo/util.c:tomoyo_get_exe
```
**Symbols:**

```
ffffffff8147aaa0-ffffffff8147ac25: tomoyo_realpath_from_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
char *tomoyo_realpath_from_path(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/realpath.c (ffffffff81486120)
Location: security/tomoyo/realpath.c:235
Inline: False
Direct callers:
  - security/tomoyo/audit.c:tomoyo_init_log
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/realpath.c:tomoyo_realpath_nofollow
  - security/tomoyo/util.c:tomoyo_get_exe
```
**Symbols:**

```
ffffffff81486120-ffffffff814862a5: tomoyo_realpath_from_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
char *tomoyo_realpath_from_path(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/realpath.c (ffffffff8149dc60)
Location: security/tomoyo/realpath.c:235
Inline: False
Direct callers:
  - security/tomoyo/audit.c:tomoyo_init_log
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/realpath.c:tomoyo_realpath_nofollow
  - security/tomoyo/util.c:tomoyo_get_exe
```
**Symbols:**

```
ffffffff8149dc60-ffffffff8149dde5: tomoyo_realpath_from_path (STB_GLOBAL)
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
