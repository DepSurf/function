# Function: <code>tomoyo_parse_name_union</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
bool tomoyo_parse_name_union(struct tomoyo_acl_param *param, struct tomoyo_name_union *ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/util.c (ffffffff81374370)
Location: security/tomoyo/util.c:257
Inline: False
Direct callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/file.c:tomoyo_update_mkdev_acl
  - security/tomoyo/file.c:tomoyo_update_mount_acl
  - security/tomoyo/file.c:tomoyo_update_mount_acl
  - security/tomoyo/file.c:tomoyo_update_mount_acl
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/network.c:tomoyo_write_unix_network
```
**Symbols:**

```
ffffffff81374370-ffffffff813743d3: tomoyo_parse_name_union (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool tomoyo_parse_name_union(struct tomoyo_acl_param *param, struct tomoyo_name_union *ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/util.c (ffffffff813aa770)
Location: security/tomoyo/util.c:257
Inline: False
Direct callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_update_mount_acl
  - security/tomoyo/file.c:tomoyo_update_mount_acl
  - security/tomoyo/file.c:tomoyo_update_mount_acl
  - security/tomoyo/file.c:tomoyo_update_mkdev_acl
  - security/tomoyo/network.c:tomoyo_write_unix_network
```
**Symbols:**

```
ffffffff813aa770-ffffffff813aa7db: tomoyo_parse_name_union (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool tomoyo_parse_name_union(struct tomoyo_acl_param *param, struct tomoyo_name_union *ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/util.c (ffffffff813c12f0)
Location: security/tomoyo/util.c:257
Inline: False
Direct callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_update_mount_acl
  - security/tomoyo/file.c:tomoyo_update_mount_acl
  - security/tomoyo/file.c:tomoyo_update_mount_acl
  - security/tomoyo/file.c:tomoyo_update_mkdev_acl
  - security/tomoyo/network.c:tomoyo_write_unix_network
```
**Symbols:**

```
ffffffff813c12f0-ffffffff813c135b: tomoyo_parse_name_union (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool tomoyo_parse_name_union(struct tomoyo_acl_param *param, struct tomoyo_name_union *ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/util.c (ffffffff813d7c70)
Location: security/tomoyo/util.c:259
Inline: False
Direct callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_update_mount_acl
  - security/tomoyo/file.c:tomoyo_update_mount_acl
  - security/tomoyo/file.c:tomoyo_update_mount_acl
  - security/tomoyo/file.c:tomoyo_update_mkdev_acl
  - security/tomoyo/network.c:tomoyo_write_unix_network
```
**Symbols:**

```
ffffffff813d7c70-ffffffff813d7cdb: tomoyo_parse_name_union (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool tomoyo_parse_name_union(struct tomoyo_acl_param *param, struct tomoyo_name_union *ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/util.c (ffffffff813fe0c0)
Location: security/tomoyo/util.c:239
Inline: False
Direct callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_update_mount_acl
  - security/tomoyo/file.c:tomoyo_update_mount_acl
  - security/tomoyo/file.c:tomoyo_update_mount_acl
  - security/tomoyo/file.c:tomoyo_update_mkdev_acl
  - security/tomoyo/network.c:tomoyo_write_unix_network
```
**Symbols:**

```
ffffffff813fe0c0-ffffffff813fe12b: tomoyo_parse_name_union (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool tomoyo_parse_name_union(struct tomoyo_acl_param *param, struct tomoyo_name_union *ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/util.c (ffffffff8142efc0)
Location: security/tomoyo/util.c:239
Inline: False
Direct callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_update_mount_acl
  - security/tomoyo/file.c:tomoyo_update_mount_acl
  - security/tomoyo/file.c:tomoyo_update_mount_acl
  - security/tomoyo/file.c:tomoyo_update_mkdev_acl
  - security/tomoyo/network.c:tomoyo_write_unix_network
```
**Symbols:**

```
ffffffff8142efc0-ffffffff8142f02b: tomoyo_parse_name_union (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool tomoyo_parse_name_union(struct tomoyo_acl_param *param, struct tomoyo_name_union *ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/util.c (ffffffff8144b9e0)
Location: security/tomoyo/util.c:239
Inline: False
Direct callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_update_mount_acl
  - security/tomoyo/file.c:tomoyo_update_mount_acl
  - security/tomoyo/file.c:tomoyo_update_mount_acl
  - security/tomoyo/file.c:tomoyo_update_mkdev_acl
  - security/tomoyo/network.c:tomoyo_write_unix_network
```
**Symbols:**

```
ffffffff8144b9e0-ffffffff8144ba43: tomoyo_parse_name_union (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool tomoyo_parse_name_union(struct tomoyo_acl_param *param, struct tomoyo_name_union *ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/util.c (ffffffff81479730)
Location: security/tomoyo/util.c:245
Inline: False
Direct callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_update_mount_acl
  - security/tomoyo/file.c:tomoyo_update_mount_acl
  - security/tomoyo/file.c:tomoyo_update_mount_acl
  - security/tomoyo/file.c:tomoyo_update_mkdev_acl
  - security/tomoyo/network.c:tomoyo_write_unix_network
```
**Symbols:**

```
ffffffff81479730-ffffffff81479793: tomoyo_parse_name_union (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool tomoyo_parse_name_union(struct tomoyo_acl_param *param, struct tomoyo_name_union *ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/util.c (ffffffff81493430)
Location: security/tomoyo/util.c:245
Inline: False
Direct callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_update_mount_acl
  - security/tomoyo/file.c:tomoyo_update_mount_acl
  - security/tomoyo/file.c:tomoyo_update_mount_acl
  - security/tomoyo/file.c:tomoyo_update_mkdev_acl
  - security/tomoyo/network.c:tomoyo_write_unix_network
```
**Symbols:**

```
ffffffff81493430-ffffffff81493493: tomoyo_parse_name_union (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool tomoyo_parse_name_union(struct tomoyo_acl_param *param, struct tomoyo_name_union *ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/util.c (ffffffff814ea7f0)
Location: security/tomoyo/util.c:245
Inline: False
Direct callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_update_mount_acl
  - security/tomoyo/file.c:tomoyo_update_mount_acl
  - security/tomoyo/file.c:tomoyo_update_mount_acl
  - security/tomoyo/file.c:tomoyo_update_mkdev_acl
  - security/tomoyo/network.c:tomoyo_write_unix_network
```
**Symbols:**

```
ffffffff814ea7f0-ffffffff814ea853: tomoyo_parse_name_union (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool tomoyo_parse_name_union(struct tomoyo_acl_param *param, struct tomoyo_name_union *ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/util.c (ffffffff81507bd0)
Location: security/tomoyo/util.c:247
Inline: False
Direct callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_update_mount_acl
  - security/tomoyo/file.c:tomoyo_update_mount_acl
  - security/tomoyo/file.c:tomoyo_update_mount_acl
  - security/tomoyo/file.c:tomoyo_update_mkdev_acl
  - security/tomoyo/network.c:tomoyo_write_unix_network
```
**Symbols:**

```
ffffffff81507bd0-ffffffff81507c33: tomoyo_parse_name_union (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool tomoyo_parse_name_union(struct tomoyo_acl_param *param, struct tomoyo_name_union *ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/util.c (ffffffff8150e750)
Location: security/tomoyo/util.c:247
Inline: False
Direct callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_update_mount_acl
  - security/tomoyo/file.c:tomoyo_update_mount_acl
  - security/tomoyo/file.c:tomoyo_update_mount_acl
  - security/tomoyo/file.c:tomoyo_update_mkdev_acl
  - security/tomoyo/network.c:tomoyo_write_unix_network
```
**Symbols:**

```
ffffffff8150e750-ffffffff8150e7b3: tomoyo_parse_name_union (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool tomoyo_parse_name_union(struct tomoyo_acl_param *param, struct tomoyo_name_union *ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/util.c (ffffffff8156c2a0)
Location: security/tomoyo/util.c:247
Inline: False
Direct callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_update_mount_acl
  - security/tomoyo/file.c:tomoyo_update_mount_acl
  - security/tomoyo/file.c:tomoyo_update_mount_acl
  - security/tomoyo/file.c:tomoyo_update_mkdev_acl
  - security/tomoyo/network.c:tomoyo_write_unix_network
```
**Symbols:**

```
ffffffff8156c2a0-ffffffff8156c303: tomoyo_parse_name_union (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool tomoyo_parse_name_union(struct tomoyo_acl_param *param, struct tomoyo_name_union *ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/util.c (ffffffff816085a0)
Location: security/tomoyo/util.c:247
Inline: False
Direct callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_update_mount_acl
  - security/tomoyo/file.c:tomoyo_update_mount_acl
  - security/tomoyo/file.c:tomoyo_update_mount_acl
  - security/tomoyo/file.c:tomoyo_update_mkdev_acl
  - security/tomoyo/network.c:tomoyo_write_unix_network
```
**Symbols:**

```
ffffffff816085a0-ffffffff8160861b: tomoyo_parse_name_union (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool tomoyo_parse_name_union(struct tomoyo_acl_param *param, struct tomoyo_name_union *ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/util.c (ffffffff816b9df0)
Location: security/tomoyo/util.c:247
Inline: False
Direct callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_update_mount_acl
  - security/tomoyo/file.c:tomoyo_update_mount_acl
  - security/tomoyo/file.c:tomoyo_update_mount_acl
  - security/tomoyo/file.c:tomoyo_update_mkdev_acl
  - security/tomoyo/network.c:tomoyo_write_unix_network
```
**Symbols:**

```
ffffffff816b9df0-ffffffff816b9e6b: tomoyo_parse_name_union (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool tomoyo_parse_name_union(struct tomoyo_acl_param *param, struct tomoyo_name_union *ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/util.c (ffffffff816f2790)
Location: security/tomoyo/util.c:247
Inline: False
Direct callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_update_mount_acl
  - security/tomoyo/file.c:tomoyo_update_mount_acl
  - security/tomoyo/file.c:tomoyo_update_mount_acl
  - security/tomoyo/file.c:tomoyo_update_mkdev_acl
  - security/tomoyo/network.c:tomoyo_write_unix_network
```
**Symbols:**

```
ffffffff816f2790-ffffffff816f280b: tomoyo_parse_name_union (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool tomoyo_parse_name_union(struct tomoyo_acl_param *param, struct tomoyo_name_union *ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/util.c (ffffffff8172f550)
Location: security/tomoyo/util.c:247
Inline: False
Direct callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_update_mount_acl
  - security/tomoyo/file.c:tomoyo_update_mount_acl
  - security/tomoyo/file.c:tomoyo_update_mount_acl
  - security/tomoyo/file.c:tomoyo_update_mkdev_acl
  - security/tomoyo/network.c:tomoyo_write_unix_network
```
**Symbols:**

```
ffffffff8172f550-ffffffff8172f5cb: tomoyo_parse_name_union (STB_GLOBAL)
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
bool tomoyo_parse_name_union(struct tomoyo_acl_param *param, struct tomoyo_name_union *ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/util.c (ffff800010588660)
Location: security/tomoyo/util.c:245
Inline: False
Direct callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_update_mount_acl
  - security/tomoyo/file.c:tomoyo_update_mount_acl
  - security/tomoyo/file.c:tomoyo_update_mount_acl
  - security/tomoyo/file.c:tomoyo_update_mkdev_acl
  - security/tomoyo/network.c:tomoyo_write_unix_network
```
**Symbols:**

```
ffff800010588660-ffff8000105886fc: tomoyo_parse_name_union (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool tomoyo_parse_name_union(struct tomoyo_acl_param *param, struct tomoyo_name_union *ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/util.c (c0739b28)
Location: security/tomoyo/util.c:245
Inline: False
Direct callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/network.c:tomoyo_write_unix_network
```
**Symbols:**

```
c0739b28-c0739ba0: tomoyo_parse_name_union (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool tomoyo_parse_name_union(struct tomoyo_acl_param *param, struct tomoyo_name_union *ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/util.c (c0000000006f8cb0)
Location: security/tomoyo/util.c:245
Inline: False
Direct callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_update_mount_acl
  - security/tomoyo/file.c:tomoyo_update_mount_acl
  - security/tomoyo/file.c:tomoyo_update_mount_acl
  - security/tomoyo/file.c:tomoyo_update_mkdev_acl
  - security/tomoyo/network.c:tomoyo_write_unix_network
```
**Symbols:**

```
c0000000006f8cb0-c0000000006f8d84: tomoyo_parse_name_union (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool tomoyo_parse_name_union(struct tomoyo_acl_param *param, struct tomoyo_name_union *ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/util.c (ffffffe0003d76da)
Location: security/tomoyo/util.c:245
Inline: False
Direct callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_update_mount_acl
  - security/tomoyo/file.c:tomoyo_update_mount_acl
  - security/tomoyo/file.c:tomoyo_update_mount_acl
  - security/tomoyo/file.c:tomoyo_update_mkdev_acl
  - security/tomoyo/network.c:tomoyo_write_unix_network
```
**Symbols:**

```
ffffffe0003d76da-ffffffe0003d7766: tomoyo_parse_name_union (STB_GLOBAL)
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
bool tomoyo_parse_name_union(struct tomoyo_acl_param *param, struct tomoyo_name_union *ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/util.c (ffffffff8148ba10)
Location: security/tomoyo/util.c:245
Inline: False
Direct callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_update_mount_acl
  - security/tomoyo/file.c:tomoyo_update_mount_acl
  - security/tomoyo/file.c:tomoyo_update_mount_acl
  - security/tomoyo/file.c:tomoyo_update_mkdev_acl
  - security/tomoyo/network.c:tomoyo_write_unix_network
```
**Symbols:**

```
ffffffff8148ba10-ffffffff8148ba73: tomoyo_parse_name_union (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool tomoyo_parse_name_union(struct tomoyo_acl_param *param, struct tomoyo_name_union *ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/util.c (ffffffff8147c430)
Location: security/tomoyo/util.c:245
Inline: False
Direct callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_update_mount_acl
  - security/tomoyo/file.c:tomoyo_update_mount_acl
  - security/tomoyo/file.c:tomoyo_update_mount_acl
  - security/tomoyo/file.c:tomoyo_update_mkdev_acl
  - security/tomoyo/network.c:tomoyo_write_unix_network
```
**Symbols:**

```
ffffffff8147c430-ffffffff8147c493: tomoyo_parse_name_union (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool tomoyo_parse_name_union(struct tomoyo_acl_param *param, struct tomoyo_name_union *ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/util.c (ffffffff81487ab0)
Location: security/tomoyo/util.c:245
Inline: False
Direct callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_update_mount_acl
  - security/tomoyo/file.c:tomoyo_update_mount_acl
  - security/tomoyo/file.c:tomoyo_update_mount_acl
  - security/tomoyo/file.c:tomoyo_update_mkdev_acl
  - security/tomoyo/network.c:tomoyo_write_unix_network
```
**Symbols:**

```
ffffffff81487ab0-ffffffff81487b13: tomoyo_parse_name_union (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool tomoyo_parse_name_union(struct tomoyo_acl_param *param, struct tomoyo_name_union *ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/util.c (ffffffff8149f5f0)
Location: security/tomoyo/util.c:245
Inline: False
Direct callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_update_mount_acl
  - security/tomoyo/file.c:tomoyo_update_mount_acl
  - security/tomoyo/file.c:tomoyo_update_mount_acl
  - security/tomoyo/file.c:tomoyo_update_mkdev_acl
  - security/tomoyo/network.c:tomoyo_write_unix_network
```
**Symbols:**

```
ffffffff8149f5f0-ffffffff8149f653: tomoyo_parse_name_union (STB_GLOBAL)
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
