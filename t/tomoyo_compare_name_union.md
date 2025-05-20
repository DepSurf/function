# Function: <code>tomoyo_compare_name_union</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
const struct tomoyo_path_info *tomoyo_compare_name_union(const struct tomoyo_path_info *name, const struct tomoyo_name_union *ptr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/tomoyo/file.c (ffffffff8136f050)
Location: security/tomoyo/file.c:81
Inline: True
Direct callers:
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/file.c:tomoyo_check_path2_acl
  - security/tomoyo/file.c:tomoyo_check_path2_acl
  - security/tomoyo/file.c:tomoyo_check_path_number_acl
  - security/tomoyo/file.c:tomoyo_check_mkdev_acl
  - security/tomoyo/mount.c:tomoyo_check_mount_acl
  - security/tomoyo/mount.c:tomoyo_check_mount_acl
  - security/tomoyo/mount.c:tomoyo_check_mount_acl
  - security/tomoyo/network.c:tomoyo_check_unix_acl
```
**Symbols:**

```
ffffffff8136f050-ffffffff8136f084: tomoyo_compare_name_union (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
const struct tomoyo_path_info *tomoyo_compare_name_union(const struct tomoyo_path_info *name, const struct tomoyo_name_union *ptr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/tomoyo/file.c (ffffffff813a5340)
Location: security/tomoyo/file.c:81
Inline: True
Direct callers:
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/file.c:tomoyo_check_mkdev_acl
  - security/tomoyo/file.c:tomoyo_check_path2_acl
  - security/tomoyo/file.c:tomoyo_check_path2_acl
  - security/tomoyo/file.c:tomoyo_check_path_number_acl
  - security/tomoyo/mount.c:tomoyo_check_mount_acl
  - security/tomoyo/mount.c:tomoyo_check_mount_acl
  - security/tomoyo/mount.c:tomoyo_check_mount_acl
  - security/tomoyo/network.c:tomoyo_check_unix_acl
```
**Symbols:**

```
ffffffff813a5340-ffffffff813a5374: tomoyo_compare_name_union (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
const struct tomoyo_path_info *tomoyo_compare_name_union(const struct tomoyo_path_info *name, const struct tomoyo_name_union *ptr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/tomoyo/file.c (ffffffff813bbec0)
Location: security/tomoyo/file.c:81
Inline: True
Direct callers:
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/file.c:tomoyo_check_mkdev_acl
  - security/tomoyo/file.c:tomoyo_check_path2_acl
  - security/tomoyo/file.c:tomoyo_check_path2_acl
  - security/tomoyo/file.c:tomoyo_check_path_number_acl
  - security/tomoyo/mount.c:tomoyo_check_mount_acl
  - security/tomoyo/mount.c:tomoyo_check_mount_acl
  - security/tomoyo/mount.c:tomoyo_check_mount_acl
  - security/tomoyo/network.c:tomoyo_check_unix_acl
```
**Symbols:**

```
ffffffff813bbec0-ffffffff813bbef4: tomoyo_compare_name_union (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
const struct tomoyo_path_info *tomoyo_compare_name_union(const struct tomoyo_path_info *name, const struct tomoyo_name_union *ptr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/tomoyo/file.c (ffffffff813d27c0)
Location: security/tomoyo/file.c:81
Inline: True
Direct callers:
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/file.c:tomoyo_check_mkdev_acl
  - security/tomoyo/file.c:tomoyo_check_path2_acl
  - security/tomoyo/file.c:tomoyo_check_path2_acl
  - security/tomoyo/file.c:tomoyo_check_path_number_acl
  - security/tomoyo/mount.c:tomoyo_check_mount_acl
  - security/tomoyo/mount.c:tomoyo_check_mount_acl
  - security/tomoyo/mount.c:tomoyo_check_mount_acl
  - security/tomoyo/network.c:tomoyo_check_unix_acl
```
**Symbols:**

```
ffffffff813d27c0-ffffffff813d27f4: tomoyo_compare_name_union (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
const struct tomoyo_path_info *tomoyo_compare_name_union(const struct tomoyo_path_info *name, const struct tomoyo_name_union *ptr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/tomoyo/file.c (ffffffff813f8cd0)
Location: security/tomoyo/file.c:82
Inline: True
Direct callers:
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/file.c:tomoyo_check_mkdev_acl
  - security/tomoyo/file.c:tomoyo_check_path2_acl
  - security/tomoyo/file.c:tomoyo_check_path2_acl
  - security/tomoyo/file.c:tomoyo_check_path_number_acl
  - security/tomoyo/mount.c:tomoyo_check_mount_acl
  - security/tomoyo/mount.c:tomoyo_check_mount_acl
  - security/tomoyo/mount.c:tomoyo_check_mount_acl
  - security/tomoyo/network.c:tomoyo_check_unix_acl
```
**Symbols:**

```
ffffffff813f8cd0-ffffffff813f8d04: tomoyo_compare_name_union (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
const struct tomoyo_path_info *tomoyo_compare_name_union(const struct tomoyo_path_info *name, const struct tomoyo_name_union *ptr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/tomoyo/file.c (ffffffff81429cc0)
Location: security/tomoyo/file.c:82
Inline: True
Direct callers:
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/file.c:tomoyo_check_mkdev_acl
  - security/tomoyo/file.c:tomoyo_check_path2_acl
  - security/tomoyo/file.c:tomoyo_check_path2_acl
  - security/tomoyo/file.c:tomoyo_check_path_number_acl
  - security/tomoyo/mount.c:tomoyo_check_mount_acl
  - security/tomoyo/mount.c:tomoyo_check_mount_acl
  - security/tomoyo/mount.c:tomoyo_check_mount_acl
  - security/tomoyo/network.c:tomoyo_check_unix_acl
```
**Symbols:**

```
ffffffff81429cc0-ffffffff81429cf4: tomoyo_compare_name_union (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
const struct tomoyo_path_info *tomoyo_compare_name_union(const struct tomoyo_path_info *name, const struct tomoyo_name_union *ptr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/tomoyo/file.c (ffffffff81446580)
Location: security/tomoyo/file.c:82
Inline: True
Direct callers:
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/file.c:tomoyo_check_mkdev_acl
  - security/tomoyo/file.c:tomoyo_check_path2_acl
  - security/tomoyo/file.c:tomoyo_check_path2_acl
  - security/tomoyo/file.c:tomoyo_check_path_number_acl
  - security/tomoyo/mount.c:tomoyo_check_mount_acl
  - security/tomoyo/mount.c:tomoyo_check_mount_acl
  - security/tomoyo/mount.c:tomoyo_check_mount_acl
  - security/tomoyo/network.c:tomoyo_check_unix_acl
```
**Symbols:**

```
ffffffff81446580-ffffffff814465c3: tomoyo_compare_name_union (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
const struct tomoyo_path_info *tomoyo_compare_name_union(const struct tomoyo_path_info *name, const struct tomoyo_name_union *ptr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/tomoyo/file.c (ffffffff81474160)
Location: security/tomoyo/file.c:82
Inline: True
Direct callers:
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/file.c:tomoyo_check_mkdev_acl
  - security/tomoyo/file.c:tomoyo_check_path2_acl
  - security/tomoyo/file.c:tomoyo_check_path2_acl
  - security/tomoyo/file.c:tomoyo_check_path_number_acl
  - security/tomoyo/mount.c:tomoyo_check_mount_acl
  - security/tomoyo/mount.c:tomoyo_check_mount_acl
  - security/tomoyo/mount.c:tomoyo_check_mount_acl
  - security/tomoyo/network.c:tomoyo_check_unix_acl
```
**Symbols:**

```
ffffffff81474160-ffffffff814741a2: tomoyo_compare_name_union (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
const struct tomoyo_path_info *tomoyo_compare_name_union(const struct tomoyo_path_info *name, const struct tomoyo_name_union *ptr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/tomoyo/file.c (ffffffff8148df00)
Location: security/tomoyo/file.c:82
Inline: True
Direct callers:
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/file.c:tomoyo_check_mkdev_acl
  - security/tomoyo/file.c:tomoyo_check_path2_acl
  - security/tomoyo/file.c:tomoyo_check_path2_acl
  - security/tomoyo/file.c:tomoyo_check_path_number_acl
  - security/tomoyo/mount.c:tomoyo_check_mount_acl
  - security/tomoyo/mount.c:tomoyo_check_mount_acl
  - security/tomoyo/mount.c:tomoyo_check_mount_acl
  - security/tomoyo/network.c:tomoyo_check_unix_acl
```
**Symbols:**

```
ffffffff8148df00-ffffffff8148df42: tomoyo_compare_name_union (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
const struct tomoyo_path_info *tomoyo_compare_name_union(const struct tomoyo_path_info *name, const struct tomoyo_name_union *ptr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/tomoyo/file.c (ffffffff814e507a)
Location: security/tomoyo/file.c:82
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_check_mkdev_acl
  - security/tomoyo/file.c:tomoyo_check_mkdev_acl
  - security/tomoyo/file.c:tomoyo_check_path2_acl
  - security/tomoyo/file.c:tomoyo_check_path2_acl
  - security/tomoyo/file.c:tomoyo_check_path2_acl
  - security/tomoyo/file.c:tomoyo_check_path2_acl
  - security/tomoyo/file.c:tomoyo_check_path_number_acl
  - security/tomoyo/file.c:tomoyo_check_path_number_acl
Direct callers:
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/mount.c:tomoyo_check_mount_acl
  - security/tomoyo/mount.c:tomoyo_check_mount_acl
  - security/tomoyo/mount.c:tomoyo_check_mount_acl
  - security/tomoyo/network.c:tomoyo_check_unix_acl
```
**Symbols:**

```
ffffffff814e5310-ffffffff814e5352: tomoyo_compare_name_union (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
const struct tomoyo_path_info *tomoyo_compare_name_union(const struct tomoyo_path_info *name, const struct tomoyo_name_union *ptr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/tomoyo/file.c (ffffffff8150247a)
Location: security/tomoyo/file.c:82
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_check_mkdev_acl
  - security/tomoyo/file.c:tomoyo_check_mkdev_acl
  - security/tomoyo/file.c:tomoyo_check_path2_acl
  - security/tomoyo/file.c:tomoyo_check_path2_acl
  - security/tomoyo/file.c:tomoyo_check_path2_acl
  - security/tomoyo/file.c:tomoyo_check_path2_acl
  - security/tomoyo/file.c:tomoyo_check_path_number_acl
  - security/tomoyo/file.c:tomoyo_check_path_number_acl
Direct callers:
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/mount.c:tomoyo_check_mount_acl
  - security/tomoyo/mount.c:tomoyo_check_mount_acl
  - security/tomoyo/mount.c:tomoyo_check_mount_acl
  - security/tomoyo/network.c:tomoyo_check_unix_acl
```
**Symbols:**

```
ffffffff81502710-ffffffff81502752: tomoyo_compare_name_union (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
const struct tomoyo_path_info *tomoyo_compare_name_union(const struct tomoyo_path_info *name, const struct tomoyo_name_union *ptr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/tomoyo/file.c (ffffffff8150904a)
Location: security/tomoyo/file.c:82
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_check_mkdev_acl
  - security/tomoyo/file.c:tomoyo_check_mkdev_acl
  - security/tomoyo/file.c:tomoyo_check_path2_acl
  - security/tomoyo/file.c:tomoyo_check_path2_acl
  - security/tomoyo/file.c:tomoyo_check_path2_acl
  - security/tomoyo/file.c:tomoyo_check_path2_acl
  - security/tomoyo/file.c:tomoyo_check_path_number_acl
  - security/tomoyo/file.c:tomoyo_check_path_number_acl
Direct callers:
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/mount.c:tomoyo_check_mount_acl
  - security/tomoyo/mount.c:tomoyo_check_mount_acl
  - security/tomoyo/mount.c:tomoyo_check_mount_acl
  - security/tomoyo/network.c:tomoyo_check_unix_acl
```
**Symbols:**

```
ffffffff815092e0-ffffffff81509322: tomoyo_compare_name_union (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
const struct tomoyo_path_info *tomoyo_compare_name_union(const struct tomoyo_path_info *name, const struct tomoyo_name_union *ptr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/tomoyo/file.c (ffffffff8156637c)
Location: security/tomoyo/file.c:82
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_check_mkdev_acl
  - security/tomoyo/file.c:tomoyo_check_mkdev_acl
  - security/tomoyo/file.c:tomoyo_check_path2_acl
  - security/tomoyo/file.c:tomoyo_check_path2_acl
  - security/tomoyo/file.c:tomoyo_check_path2_acl
  - security/tomoyo/file.c:tomoyo_check_path2_acl
  - security/tomoyo/file.c:tomoyo_check_path_number_acl
  - security/tomoyo/file.c:tomoyo_check_path_number_acl
Direct callers:
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/mount.c:tomoyo_check_mount_acl
  - security/tomoyo/mount.c:tomoyo_check_mount_acl
  - security/tomoyo/mount.c:tomoyo_check_mount_acl
  - security/tomoyo/network.c:tomoyo_check_unix_acl
```
**Symbols:**

```
ffffffff81566620-ffffffff81566662: tomoyo_compare_name_union (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
const struct tomoyo_path_info *tomoyo_compare_name_union(const struct tomoyo_path_info *name, const struct tomoyo_name_union *ptr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/tomoyo/file.c (ffffffff81601d56)
Location: security/tomoyo/file.c:82
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_check_mkdev_acl
  - security/tomoyo/file.c:tomoyo_check_mkdev_acl
  - security/tomoyo/file.c:tomoyo_check_path2_acl
  - security/tomoyo/file.c:tomoyo_check_path2_acl
  - security/tomoyo/file.c:tomoyo_check_path2_acl
  - security/tomoyo/file.c:tomoyo_check_path2_acl
  - security/tomoyo/file.c:tomoyo_check_path_number_acl
  - security/tomoyo/file.c:tomoyo_check_path_number_acl
Direct callers:
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/mount.c:tomoyo_check_mount_acl
  - security/tomoyo/mount.c:tomoyo_check_mount_acl
  - security/tomoyo/mount.c:tomoyo_check_mount_acl
  - security/tomoyo/network.c:tomoyo_check_unix_acl
```
**Symbols:**

```
ffffffff81602020-ffffffff81602073: tomoyo_compare_name_union (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
const struct tomoyo_path_info *tomoyo_compare_name_union(const struct tomoyo_path_info *name, const struct tomoyo_name_union *ptr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/tomoyo/file.c (ffffffff816b2e06)
Location: security/tomoyo/file.c:82
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_check_mkdev_acl
  - security/tomoyo/file.c:tomoyo_check_mkdev_acl
  - security/tomoyo/file.c:tomoyo_check_path2_acl
  - security/tomoyo/file.c:tomoyo_check_path2_acl
  - security/tomoyo/file.c:tomoyo_check_path2_acl
  - security/tomoyo/file.c:tomoyo_check_path2_acl
  - security/tomoyo/file.c:tomoyo_check_path_number_acl
  - security/tomoyo/file.c:tomoyo_check_path_number_acl
Direct callers:
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/mount.c:tomoyo_check_mount_acl
  - security/tomoyo/mount.c:tomoyo_check_mount_acl
  - security/tomoyo/mount.c:tomoyo_check_mount_acl
  - security/tomoyo/network.c:tomoyo_check_unix_acl
```
**Symbols:**

```
ffffffff816b3110-ffffffff816b3163: tomoyo_compare_name_union (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
const struct tomoyo_path_info *tomoyo_compare_name_union(const struct tomoyo_path_info *name, const struct tomoyo_name_union *ptr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/tomoyo/file.c (ffffffff816eb7e0)
Location: security/tomoyo/file.c:82
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_check_mkdev_acl
  - security/tomoyo/file.c:tomoyo_check_mkdev_acl
  - security/tomoyo/file.c:tomoyo_check_path2_acl
  - security/tomoyo/file.c:tomoyo_check_path2_acl
  - security/tomoyo/file.c:tomoyo_check_path2_acl
  - security/tomoyo/file.c:tomoyo_check_path2_acl
  - security/tomoyo/file.c:tomoyo_check_path_number_acl
  - security/tomoyo/file.c:tomoyo_check_path_number_acl
Direct callers:
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/mount.c:tomoyo_check_mount_acl
  - security/tomoyo/mount.c:tomoyo_check_mount_acl
  - security/tomoyo/mount.c:tomoyo_check_mount_acl
  - security/tomoyo/network.c:tomoyo_check_unix_acl
```
**Symbols:**

```
ffffffff816ebae0-ffffffff816ebb33: tomoyo_compare_name_union (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
const struct tomoyo_path_info *tomoyo_compare_name_union(const struct tomoyo_path_info *name, const struct tomoyo_name_union *ptr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/tomoyo/file.c (ffffffff817285b0)
Location: security/tomoyo/file.c:82
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_check_mkdev_acl
  - security/tomoyo/file.c:tomoyo_check_mkdev_acl
  - security/tomoyo/file.c:tomoyo_check_path2_acl
  - security/tomoyo/file.c:tomoyo_check_path2_acl
  - security/tomoyo/file.c:tomoyo_check_path2_acl
  - security/tomoyo/file.c:tomoyo_check_path2_acl
  - security/tomoyo/file.c:tomoyo_check_path_number_acl
  - security/tomoyo/file.c:tomoyo_check_path_number_acl
Direct callers:
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/mount.c:tomoyo_check_mount_acl
  - security/tomoyo/mount.c:tomoyo_check_mount_acl
  - security/tomoyo/mount.c:tomoyo_check_mount_acl
  - security/tomoyo/network.c:tomoyo_check_unix_acl
```
**Symbols:**

```
ffffffff817288b0-ffffffff81728903: tomoyo_compare_name_union (STB_GLOBAL)
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
const struct tomoyo_path_info *tomoyo_compare_name_union(const struct tomoyo_path_info *name, const struct tomoyo_name_union *ptr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/tomoyo/file.c (ffff8000105817b0)
Location: security/tomoyo/file.c:82
Inline: True
Direct callers:
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/file.c:tomoyo_check_mkdev_acl
  - security/tomoyo/file.c:tomoyo_check_path2_acl
  - security/tomoyo/file.c:tomoyo_check_path2_acl
  - security/tomoyo/file.c:tomoyo_check_path_number_acl
  - security/tomoyo/mount.c:tomoyo_check_mount_acl
  - security/tomoyo/mount.c:tomoyo_check_mount_acl
  - security/tomoyo/mount.c:tomoyo_check_mount_acl
  - security/tomoyo/network.c:tomoyo_check_unix_acl
```
**Symbols:**

```
ffff8000105817b0-ffff800010581828: tomoyo_compare_name_union (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
const struct tomoyo_path_info *tomoyo_compare_name_union(const struct tomoyo_path_info *name, const struct tomoyo_name_union *ptr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/tomoyo/file.c (c073376c)
Location: security/tomoyo/file.c:82
Inline: True
Direct callers:
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/file.c:tomoyo_check_mkdev_acl
  - security/tomoyo/file.c:tomoyo_check_path2_acl
  - security/tomoyo/file.c:tomoyo_check_path2_acl
  - security/tomoyo/file.c:tomoyo_check_path_number_acl
  - security/tomoyo/mount.c:tomoyo_check_mount_acl
  - security/tomoyo/mount.c:tomoyo_check_mount_acl
  - security/tomoyo/mount.c:tomoyo_check_mount_acl
  - security/tomoyo/network.c:tomoyo_check_unix_acl
```
**Symbols:**

```
c073376c-c07337bc: tomoyo_compare_name_union (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
const struct tomoyo_path_info *tomoyo_compare_name_union(const struct tomoyo_path_info *name, const struct tomoyo_name_union *ptr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/tomoyo/file.c (c0000000006efd40)
Location: security/tomoyo/file.c:82
Inline: True
Direct callers:
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/file.c:tomoyo_check_mkdev_acl
  - security/tomoyo/file.c:tomoyo_check_path2_acl
  - security/tomoyo/file.c:tomoyo_check_path2_acl
  - security/tomoyo/file.c:tomoyo_check_path_number_acl
  - security/tomoyo/mount.c:tomoyo_check_mount_acl
  - security/tomoyo/mount.c:tomoyo_check_mount_acl
  - security/tomoyo/mount.c:tomoyo_check_mount_acl
  - security/tomoyo/network.c:tomoyo_check_unix_acl
```
**Symbols:**

```
c0000000006efd40-c0000000006efdfc: tomoyo_compare_name_union (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
const struct tomoyo_path_info *tomoyo_compare_name_union(const struct tomoyo_path_info *name, const struct tomoyo_name_union *ptr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/tomoyo/file.c (ffffffe0003d1ed6)
Location: security/tomoyo/file.c:82
Inline: True
Direct callers:
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/file.c:tomoyo_check_mkdev_acl
  - security/tomoyo/file.c:tomoyo_check_path2_acl
  - security/tomoyo/file.c:tomoyo_check_path2_acl
  - security/tomoyo/file.c:tomoyo_check_path_number_acl
  - security/tomoyo/mount.c:tomoyo_check_mount_acl
  - security/tomoyo/mount.c:tomoyo_check_mount_acl
  - security/tomoyo/mount.c:tomoyo_check_mount_acl
  - security/tomoyo/network.c:tomoyo_check_unix_acl
```
**Symbols:**

```
ffffffe0003d1ed6-ffffffe0003d1f3a: tomoyo_compare_name_union (STB_GLOBAL)
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
const struct tomoyo_path_info *tomoyo_compare_name_union(const struct tomoyo_path_info *name, const struct tomoyo_name_union *ptr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/tomoyo/file.c (ffffffff814864e0)
Location: security/tomoyo/file.c:82
Inline: True
Direct callers:
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/file.c:tomoyo_check_mkdev_acl
  - security/tomoyo/file.c:tomoyo_check_path2_acl
  - security/tomoyo/file.c:tomoyo_check_path2_acl
  - security/tomoyo/file.c:tomoyo_check_path_number_acl
  - security/tomoyo/mount.c:tomoyo_check_mount_acl
  - security/tomoyo/mount.c:tomoyo_check_mount_acl
  - security/tomoyo/mount.c:tomoyo_check_mount_acl
  - security/tomoyo/network.c:tomoyo_check_unix_acl
```
**Symbols:**

```
ffffffff814864e0-ffffffff81486522: tomoyo_compare_name_union (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
const struct tomoyo_path_info *tomoyo_compare_name_union(const struct tomoyo_path_info *name, const struct tomoyo_name_union *ptr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/tomoyo/file.c (ffffffff81476f00)
Location: security/tomoyo/file.c:82
Inline: True
Direct callers:
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/file.c:tomoyo_check_mkdev_acl
  - security/tomoyo/file.c:tomoyo_check_path2_acl
  - security/tomoyo/file.c:tomoyo_check_path2_acl
  - security/tomoyo/file.c:tomoyo_check_path_number_acl
  - security/tomoyo/mount.c:tomoyo_check_mount_acl
  - security/tomoyo/mount.c:tomoyo_check_mount_acl
  - security/tomoyo/mount.c:tomoyo_check_mount_acl
  - security/tomoyo/network.c:tomoyo_check_unix_acl
```
**Symbols:**

```
ffffffff81476f00-ffffffff81476f42: tomoyo_compare_name_union (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
const struct tomoyo_path_info *tomoyo_compare_name_union(const struct tomoyo_path_info *name, const struct tomoyo_name_union *ptr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/tomoyo/file.c (ffffffff81482580)
Location: security/tomoyo/file.c:82
Inline: True
Direct callers:
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/file.c:tomoyo_check_mkdev_acl
  - security/tomoyo/file.c:tomoyo_check_path2_acl
  - security/tomoyo/file.c:tomoyo_check_path2_acl
  - security/tomoyo/file.c:tomoyo_check_path_number_acl
  - security/tomoyo/mount.c:tomoyo_check_mount_acl
  - security/tomoyo/mount.c:tomoyo_check_mount_acl
  - security/tomoyo/mount.c:tomoyo_check_mount_acl
  - security/tomoyo/network.c:tomoyo_check_unix_acl
```
**Symbols:**

```
ffffffff81482580-ffffffff814825c2: tomoyo_compare_name_union (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
const struct tomoyo_path_info *tomoyo_compare_name_union(const struct tomoyo_path_info *name, const struct tomoyo_name_union *ptr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/tomoyo/file.c (ffffffff8149a110)
Location: security/tomoyo/file.c:82
Inline: True
Direct callers:
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/file.c:tomoyo_check_mkdev_acl
  - security/tomoyo/file.c:tomoyo_check_path2_acl
  - security/tomoyo/file.c:tomoyo_check_path2_acl
  - security/tomoyo/file.c:tomoyo_check_path_number_acl
  - security/tomoyo/mount.c:tomoyo_check_mount_acl
  - security/tomoyo/mount.c:tomoyo_check_mount_acl
  - security/tomoyo/mount.c:tomoyo_check_mount_acl
  - security/tomoyo/network.c:tomoyo_check_unix_acl
```
**Symbols:**

```
ffffffff8149a110-ffffffff8149a152: tomoyo_compare_name_union (STB_GLOBAL)
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
