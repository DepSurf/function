# Function: <code>str_read</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int str_read(char **strp, gfp_t flags, void *fp, u32 len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff81350690)
Location: security/selinux/ss/policydb.c:1092
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:cat_read
  - security/selinux/ss/policydb.c:sens_read
  - security/selinux/ss/policydb.c:type_read
  - security/selinux/ss/policydb.c:common_read
  - security/selinux/ss/policydb.c:role_read
  - security/selinux/ss/policydb.c:user_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
```
**Symbols:**

```
ffffffff81350690-ffffffff813506f2: str_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int str_read(char **strp, gfp_t flags, void *fp, u32 len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff813866d0)
Location: security/selinux/ss/policydb.c:1092
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:cat_read
  - security/selinux/ss/policydb.c:sens_read
  - security/selinux/ss/policydb.c:user_read
  - security/selinux/ss/policydb.c:type_read
  - security/selinux/ss/policydb.c:role_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:common_read
```
**Symbols:**

```
ffffffff813866d0-ffffffff81386742: str_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int str_read(char **strp, gfp_t flags, void *fp, u32 len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff8139d180)
Location: security/selinux/ss/policydb.c:1092
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:cat_read
  - security/selinux/ss/policydb.c:sens_read
  - security/selinux/ss/policydb.c:user_read
  - security/selinux/ss/policydb.c:type_read
  - security/selinux/ss/policydb.c:role_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:common_read
```
**Symbols:**

```
ffffffff8139d180-ffffffff8139d200: str_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int str_read(char **strp, gfp_t flags, void *fp, u32 len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff813b4930)
Location: security/selinux/ss/policydb.c:1094
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:cat_read
  - security/selinux/ss/policydb.c:sens_read
  - security/selinux/ss/policydb.c:user_read
  - security/selinux/ss/policydb.c:type_read
  - security/selinux/ss/policydb.c:role_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:common_read
```
**Symbols:**

```
ffffffff813b4930-ffffffff813b49af: str_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int str_read(char **strp, gfp_t flags, void *fp, u32 len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff813da9b0)
Location: security/selinux/ss/policydb.c:1094
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:cat_read
  - security/selinux/ss/policydb.c:sens_read
  - security/selinux/ss/policydb.c:user_read
  - security/selinux/ss/policydb.c:type_read
  - security/selinux/ss/policydb.c:role_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:common_read
```
**Symbols:**

```
ffffffff813da9b0-ffffffff813daa2f: str_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int str_read(char **strp, gfp_t flags, void *fp, u32 len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff8140b240)
Location: security/selinux/ss/policydb.c:1094
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:cat_read
  - security/selinux/ss/policydb.c:sens_read
  - security/selinux/ss/policydb.c:user_read
  - security/selinux/ss/policydb.c:type_read
  - security/selinux/ss/policydb.c:role_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:common_read
```
**Symbols:**

```
ffffffff8140b240-ffffffff8140b2bf: str_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int str_read(char **strp, gfp_t flags, void *fp, u32 len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff81427940)
Location: security/selinux/ss/policydb.c:1105
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:cat_read
  - security/selinux/ss/policydb.c:sens_read
  - security/selinux/ss/policydb.c:user_read
  - security/selinux/ss/policydb.c:type_read
  - security/selinux/ss/policydb.c:role_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:common_read
```
**Symbols:**

```
ffffffff81427940-ffffffff814279c5: str_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int str_read(char **strp, gfp_t flags, void *fp, u32 len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff814558c0)
Location: security/selinux/ss/policydb.c:1057
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:genfs_read
  - security/selinux/ss/policydb.c:genfs_read
  - security/selinux/ss/policydb.c:cat_read
  - security/selinux/ss/policydb.c:sens_read
  - security/selinux/ss/policydb.c:user_read
  - security/selinux/ss/policydb.c:type_read
  - security/selinux/ss/policydb.c:role_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:common_read
```
**Symbols:**

```
ffffffff814558c0-ffffffff8145593f: str_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int str_read(char **strp, gfp_t flags, void *fp, u32 len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff8146f660)
Location: security/selinux/ss/policydb.c:1059
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:genfs_read
  - security/selinux/ss/policydb.c:genfs_read
  - security/selinux/ss/policydb.c:cat_read
  - security/selinux/ss/policydb.c:sens_read
  - security/selinux/ss/policydb.c:user_read
  - security/selinux/ss/policydb.c:type_read
  - security/selinux/ss/policydb.c:role_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:common_read
```
**Symbols:**

```
ffffffff8146f660-ffffffff8146f6df: str_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int str_read(char **strp, gfp_t flags, void *fp, u32 len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff814c2f00)
Location: security/selinux/ss/policydb.c:1045
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:ocontext_read
  - security/selinux/ss/policydb.c:ocontext_read
  - security/selinux/ss/policydb.c:ocontext_read
  - security/selinux/ss/policydb.c:genfs_read
  - security/selinux/ss/policydb.c:genfs_read
  - security/selinux/ss/policydb.c:filename_trans_read_helper
  - security/selinux/ss/policydb.c:filename_trans_read_helper_compat
  - security/selinux/ss/policydb.c:cat_read
  - security/selinux/ss/policydb.c:sens_read
  - security/selinux/ss/policydb.c:user_read
  - security/selinux/ss/policydb.c:type_read
  - security/selinux/ss/policydb.c:role_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:common_read
```
**Symbols:**

```
ffffffff814c2f00-ffffffff814c2f96: str_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int str_read(char **strp, gfp_t flags, void *fp, u32 len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff814e0a30)
Location: security/selinux/ss/policydb.c:1077
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:ocontext_read
  - security/selinux/ss/policydb.c:ocontext_read
  - security/selinux/ss/policydb.c:ocontext_read
  - security/selinux/ss/policydb.c:genfs_read
  - security/selinux/ss/policydb.c:genfs_read
  - security/selinux/ss/policydb.c:filename_trans_read_helper
  - security/selinux/ss/policydb.c:filename_trans_read_helper_compat
  - security/selinux/ss/policydb.c:cat_read
  - security/selinux/ss/policydb.c:sens_read
  - security/selinux/ss/policydb.c:user_read
  - security/selinux/ss/policydb.c:type_read
  - security/selinux/ss/policydb.c:role_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:common_read
```
**Symbols:**

```
ffffffff814e0a30-ffffffff814e0ac6: str_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int str_read(char **strp, gfp_t flags, void *fp, u32 len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff814e6ea0)
Location: security/selinux/ss/policydb.c:1075
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:ocontext_read
  - security/selinux/ss/policydb.c:ocontext_read
  - security/selinux/ss/policydb.c:ocontext_read
  - security/selinux/ss/policydb.c:genfs_read
  - security/selinux/ss/policydb.c:genfs_read
  - security/selinux/ss/policydb.c:filename_trans_read_helper
  - security/selinux/ss/policydb.c:filename_trans_read_helper_compat
  - security/selinux/ss/policydb.c:cat_read
  - security/selinux/ss/policydb.c:sens_read
  - security/selinux/ss/policydb.c:user_read
  - security/selinux/ss/policydb.c:type_read
  - security/selinux/ss/policydb.c:role_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:common_read
```
**Symbols:**

```
ffffffff814e6ea0-ffffffff814e6f36: str_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int str_read(char **strp, gfp_t flags, void *fp, u32 len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff81540730)
Location: security/selinux/ss/policydb.c:1075
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:ocontext_read
  - security/selinux/ss/policydb.c:ocontext_read
  - security/selinux/ss/policydb.c:ocontext_read
  - security/selinux/ss/policydb.c:genfs_read
  - security/selinux/ss/policydb.c:genfs_read
  - security/selinux/ss/policydb.c:filename_trans_read_helper
  - security/selinux/ss/policydb.c:filename_trans_read_helper_compat
  - security/selinux/ss/policydb.c:cat_read
  - security/selinux/ss/policydb.c:sens_read
  - security/selinux/ss/policydb.c:user_read
  - security/selinux/ss/policydb.c:type_read
  - security/selinux/ss/policydb.c:role_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:common_read
```
**Symbols:**

```
ffffffff81540730-ffffffff815407c6: str_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int str_read(char **strp, gfp_t flags, void *fp, u32 len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff815d8a60)
Location: security/selinux/ss/policydb.c:1069
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:ocontext_read
  - security/selinux/ss/policydb.c:ocontext_read
  - security/selinux/ss/policydb.c:ocontext_read
  - security/selinux/ss/policydb.c:genfs_read
  - security/selinux/ss/policydb.c:genfs_read
  - security/selinux/ss/policydb.c:filename_trans_read_helper
  - security/selinux/ss/policydb.c:filename_trans_read_helper_compat
  - security/selinux/ss/policydb.c:cat_read
  - security/selinux/ss/policydb.c:sens_read
  - security/selinux/ss/policydb.c:user_read
  - security/selinux/ss/policydb.c:type_read
  - security/selinux/ss/policydb.c:role_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:common_read
```
**Symbols:**

```
ffffffff815d8a60-ffffffff815d8af2: str_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int str_read(char **strp, gfp_t flags, void *fp, u32 len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff81687790)
Location: security/selinux/ss/policydb.c:1069
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:ocontext_read
  - security/selinux/ss/policydb.c:ocontext_read
  - security/selinux/ss/policydb.c:ocontext_read
  - security/selinux/ss/policydb.c:genfs_read
  - security/selinux/ss/policydb.c:genfs_read
  - security/selinux/ss/policydb.c:filename_trans_read_helper
  - security/selinux/ss/policydb.c:filename_trans_read_helper_compat
  - security/selinux/ss/policydb.c:cat_read
  - security/selinux/ss/policydb.c:sens_read
  - security/selinux/ss/policydb.c:user_read
  - security/selinux/ss/policydb.c:type_read
  - security/selinux/ss/policydb.c:role_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:common_read
```
**Symbols:**

```
ffffffff81687790-ffffffff81687822: str_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int str_read(char **strp, gfp_t flags, void *fp, u32 len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff816c0830)
Location: security/selinux/ss/policydb.c:1069
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:ocontext_read
  - security/selinux/ss/policydb.c:ocontext_read
  - security/selinux/ss/policydb.c:ocontext_read
  - security/selinux/ss/policydb.c:genfs_read
  - security/selinux/ss/policydb.c:genfs_read
  - security/selinux/ss/policydb.c:filename_trans_read_helper
  - security/selinux/ss/policydb.c:filename_trans_read_helper_compat
  - security/selinux/ss/policydb.c:cat_read
  - security/selinux/ss/policydb.c:sens_read
  - security/selinux/ss/policydb.c:user_read
  - security/selinux/ss/policydb.c:type_read
  - security/selinux/ss/policydb.c:role_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:common_read
```
**Symbols:**

```
ffffffff816c0830-ffffffff816c08d7: str_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff816fd130)
Location: security/selinux/ss/policydb.c:1090
Inline: True
Direct callers:
  - security/selinux/ss/policydb.c:ocontext_read
  - security/selinux/ss/policydb.c:ocontext_read
  - security/selinux/ss/policydb.c:ocontext_read
  - security/selinux/ss/policydb.c:genfs_read
  - security/selinux/ss/policydb.c:genfs_read
  - security/selinux/ss/policydb.c:filename_trans_read_helper
  - security/selinux/ss/policydb.c:filename_trans_read_helper_compat
  - security/selinux/ss/policydb.c:cat_read
  - security/selinux/ss/policydb.c:sens_read
  - security/selinux/ss/policydb.c:user_read
  - security/selinux/ss/policydb.c:type_read
  - security/selinux/ss/policydb.c:role_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:common_read
```
**Symbols:**

```
ffffffff816fd130-ffffffff816fd1d4: str_read.constprop.0 (STB_LOCAL)
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
int str_read(char **strp, gfp_t flags, void *fp, u32 len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffff80001055dba0)
Location: security/selinux/ss/policydb.c:1059
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:genfs_read
  - security/selinux/ss/policydb.c:genfs_read
  - security/selinux/ss/policydb.c:cat_read
  - security/selinux/ss/policydb.c:sens_read
  - security/selinux/ss/policydb.c:user_read
  - security/selinux/ss/policydb.c:type_read
  - security/selinux/ss/policydb.c:type_read
  - security/selinux/ss/policydb.c:role_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:common_read
```
**Symbols:**

```
ffff80001055dba0-ffff80001055dc4c: str_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int str_read(char **strp, gfp_t flags, void *fp, u32 len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (c07131d0)
Location: security/selinux/ss/policydb.c:1059
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:ocontext_read
  - security/selinux/ss/policydb.c:ocontext_read
  - security/selinux/ss/policydb.c:ocontext_read
  - security/selinux/ss/policydb.c:genfs_read
  - security/selinux/ss/policydb.c:genfs_read
  - security/selinux/ss/policydb.c:cat_read
  - security/selinux/ss/policydb.c:sens_read
  - security/selinux/ss/policydb.c:user_read
  - security/selinux/ss/policydb.c:type_read
  - security/selinux/ss/policydb.c:role_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:common_read
```
**Symbols:**

```
c07131d0-c0713260: str_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int str_read(char **strp, gfp_t flags, void *fp, u32 len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (c0000000006bf1c0)
Location: security/selinux/ss/policydb.c:1059
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:genfs_read
  - security/selinux/ss/policydb.c:genfs_read
  - security/selinux/ss/policydb.c:cat_read
  - security/selinux/ss/policydb.c:sens_read
  - security/selinux/ss/policydb.c:user_read
  - security/selinux/ss/policydb.c:type_read
  - security/selinux/ss/policydb.c:type_read
  - security/selinux/ss/policydb.c:role_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:common_read
```
**Symbols:**

```
c0000000006bf1c0-c0000000006bf2a8: str_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int str_read(char **strp, gfp_t flags, void *fp, u32 len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffe0003b4756)
Location: security/selinux/ss/policydb.c:1059
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:cat_read
  - security/selinux/ss/policydb.c:sens_read
  - security/selinux/ss/policydb.c:user_read
  - security/selinux/ss/policydb.c:user_read
  - security/selinux/ss/policydb.c:type_read
  - security/selinux/ss/policydb.c:type_read
  - security/selinux/ss/policydb.c:role_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:common_read
```
**Symbols:**

```
ffffffe0003b4756-ffffffe0003b47ee: str_read (STB_LOCAL)
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
int str_read(char **strp, gfp_t flags, void *fp, u32 len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff81467c40)
Location: security/selinux/ss/policydb.c:1059
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:genfs_read
  - security/selinux/ss/policydb.c:genfs_read
  - security/selinux/ss/policydb.c:cat_read
  - security/selinux/ss/policydb.c:sens_read
  - security/selinux/ss/policydb.c:user_read
  - security/selinux/ss/policydb.c:type_read
  - security/selinux/ss/policydb.c:role_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:common_read
```
**Symbols:**

```
ffffffff81467c40-ffffffff81467cbf: str_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int str_read(char **strp, gfp_t flags, void *fp, u32 len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff81458670)
Location: security/selinux/ss/policydb.c:1059
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:genfs_read
  - security/selinux/ss/policydb.c:genfs_read
  - security/selinux/ss/policydb.c:cat_read
  - security/selinux/ss/policydb.c:sens_read
  - security/selinux/ss/policydb.c:user_read
  - security/selinux/ss/policydb.c:type_read
  - security/selinux/ss/policydb.c:role_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:common_read
```
**Symbols:**

```
ffffffff81458670-ffffffff814586ef: str_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int str_read(char **strp, gfp_t flags, void *fp, u32 len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff81463ce0)
Location: security/selinux/ss/policydb.c:1059
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:genfs_read
  - security/selinux/ss/policydb.c:genfs_read
  - security/selinux/ss/policydb.c:cat_read
  - security/selinux/ss/policydb.c:sens_read
  - security/selinux/ss/policydb.c:user_read
  - security/selinux/ss/policydb.c:type_read
  - security/selinux/ss/policydb.c:role_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:common_read
```
**Symbols:**

```
ffffffff81463ce0-ffffffff81463d5f: str_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int str_read(char **strp, gfp_t flags, void *fp, u32 len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff8147b4e0)
Location: security/selinux/ss/policydb.c:1059
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:genfs_read
  - security/selinux/ss/policydb.c:genfs_read
  - security/selinux/ss/policydb.c:cat_read
  - security/selinux/ss/policydb.c:sens_read
  - security/selinux/ss/policydb.c:user_read
  - security/selinux/ss/policydb.c:type_read
  - security/selinux/ss/policydb.c:role_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:common_read
```
**Symbols:**

```
ffffffff8147b4e0-ffffffff8147b55f: str_read (STB_LOCAL)
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
