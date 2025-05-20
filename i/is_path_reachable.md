# Function: <code>is_path_reachable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
bool is_path_reachable(struct mount *mnt, struct dentry *dentry, const struct path *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8122fda0)
Location: fs/namespace.c:2937
Inline: False
Direct callers:
  - fs/namespace.c:path_is_under
  - fs/namespace.c:SyS_pivot_root
  - fs/namespace.c:SyS_pivot_root
  - fs/pnode.c:get_dominating_id
```
**Symbols:**

```
ffffffff8122fda0-ffffffff8122fdf6: is_path_reachable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool is_path_reachable(struct mount *mnt, struct dentry *dentry, const struct path *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81258440)
Location: fs/namespace.c:2924
Inline: False
Direct callers:
  - fs/namespace.c:SyS_pivot_root
  - fs/namespace.c:SyS_pivot_root
  - fs/namespace.c:path_is_under
  - fs/pnode.c:get_dominating_id
```
**Symbols:**

```
ffffffff81258440-ffffffff81258490: is_path_reachable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool is_path_reachable(struct mount *mnt, struct dentry *dentry, const struct path *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8126b8d0)
Location: fs/namespace.c:3068
Inline: False
Direct callers:
  - fs/namespace.c:SyS_pivot_root
  - fs/namespace.c:SyS_pivot_root
  - fs/namespace.c:path_is_under
  - fs/pnode.c:get_dominating_id
```
**Symbols:**

```
ffffffff8126b8d0-ffffffff8126b920: is_path_reachable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool is_path_reachable(struct mount *mnt, struct dentry *dentry, const struct path *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812790a0)
Location: fs/namespace.c:3010
Inline: False
Direct callers:
  - fs/namespace.c:SyS_pivot_root
  - fs/namespace.c:SyS_pivot_root
  - fs/namespace.c:path_is_under
  - fs/pnode.c:get_dominating_id
```
**Symbols:**

```
ffffffff812790a0-ffffffff812790f0: is_path_reachable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool is_path_reachable(struct mount *mnt, struct dentry *dentry, const struct path *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8129bae0)
Location: fs/namespace.c:3083
Inline: False
Direct callers:
  - fs/namespace.c:SyS_pivot_root
  - fs/namespace.c:SyS_pivot_root
  - fs/namespace.c:path_is_under
  - fs/pnode.c:get_dominating_id
```
**Symbols:**

```
ffffffff8129bae0-ffffffff8129bb30: is_path_reachable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool is_path_reachable(struct mount *mnt, struct dentry *dentry, const struct path *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812c1c20)
Location: fs/namespace.c:3120
Inline: False
Direct callers:
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:path_is_under
  - fs/pnode.c:get_dominating_id
```
**Symbols:**

```
ffffffff812c1c20-ffffffff812c1c70: is_path_reachable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool is_path_reachable(struct mount *mnt, struct dentry *dentry, const struct path *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812d6ec0)
Location: fs/namespace.c:3092
Inline: False
Direct callers:
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:path_is_under
  - fs/pnode.c:get_dominating_id
```
**Symbols:**

```
ffffffff812d6ec0-ffffffff812d6f10: is_path_reachable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool is_path_reachable(struct mount *mnt, struct dentry *dentry, const struct path *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812f5320)
Location: fs/namespace.c:3549
Inline: False
Direct callers:
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:path_is_under
  - fs/pnode.c:get_dominating_id
```
**Symbols:**

```
ffffffff812f5320-ffffffff812f5364: is_path_reachable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool is_path_reachable(struct mount *mnt, struct dentry *dentry, const struct path *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81306ea0)
Location: fs/namespace.c:3580
Inline: False
Direct callers:
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:path_is_under
  - fs/pnode.c:get_dominating_id
```
**Symbols:**

```
ffffffff81306ea0-ffffffff81306ee4: is_path_reachable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool is_path_reachable(struct mount *mnt, struct dentry *dentry, const struct path *root);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8133b101)
Location: fs/namespace.c:3633
Inline: True
Inline callers:
  - fs/namespace.c:path_is_under
Direct callers:
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:__do_sys_pivot_root
  - fs/pnode.c:get_dominating_id
```
**Symbols:**

```
ffffffff813406d0-ffffffff81340717: is_path_reachable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool is_path_reachable(struct mount *mnt, struct dentry *dentry, const struct path *root);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81346eb1)
Location: fs/namespace.c:3655
Inline: True
Inline callers:
  - fs/namespace.c:path_is_under
Direct callers:
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:__do_sys_pivot_root
  - fs/pnode.c:get_dominating_id
```
**Symbols:**

```
ffffffff8134c760-ffffffff8134c7a7: is_path_reachable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool is_path_reachable(struct mount *mnt, struct dentry *dentry, const struct path *root);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8134d6d1)
Location: fs/namespace.c:3701
Inline: True
Inline callers:
  - fs/namespace.c:path_is_under
Direct callers:
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:__do_sys_pivot_root
  - fs/pnode.c:get_dominating_id
```
**Symbols:**

```
ffffffff81353330-ffffffff81353374: is_path_reachable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool is_path_reachable(struct mount *mnt, struct dentry *dentry, const struct path *root);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8139b631)
Location: fs/namespace.c:3780
Inline: True
Inline callers:
  - fs/namespace.c:path_is_under
Direct callers:
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:__do_sys_pivot_root
  - fs/pnode.c:get_dominating_id
```
**Symbols:**

```
ffffffff813a1780-ffffffff813a17c4: is_path_reachable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
bool is_path_reachable(struct mount *mnt, struct dentry *dentry, const struct path *root);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8141e5d9)
Location: fs/namespace.c:3823
Inline: True
Inline callers:
  - fs/namespace.c:path_is_under
Direct callers:
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:__do_sys_pivot_root
  - fs/pnode.c:get_dominating_id
```
**Symbols:**

```
ffffffff81425120-ffffffff81425187: is_path_reachable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
bool is_path_reachable(struct mount *mnt, struct dentry *dentry, const struct path *root);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff814aad79)
Location: fs/namespace.c:3929
Inline: True
Inline callers:
  - fs/namespace.c:path_is_under
Direct callers:
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:__do_sys_pivot_root
  - fs/pnode.c:get_dominating_id
```
**Symbols:**

```
ffffffff814b1890-ffffffff814b18f7: is_path_reachable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
bool is_path_reachable(struct mount *mnt, struct dentry *dentry, const struct path *root);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff814dfb79)
Location: fs/namespace.c:4121
Inline: True
Inline callers:
  - fs/namespace.c:path_is_under
Direct callers:
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:__do_sys_pivot_root
  - fs/pnode.c:get_dominating_id
```
**Symbols:**

```
ffffffff814e68e0-ffffffff814e6947: is_path_reachable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
bool is_path_reachable(struct mount *mnt, struct dentry *dentry, const struct path *root);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81514750)
Location: fs/namespace.c:4134
Inline: True
Inline callers:
  - fs/namespace.c:__ia32_sys_listmount
  - fs/namespace.c:__ia32_sys_listmount
  - fs/namespace.c:__x64_sys_listmount
  - fs/namespace.c:__x64_sys_listmount
  - fs/namespace.c:do_statmount
  - fs/namespace.c:path_is_under
Direct callers:
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:__do_sys_pivot_root
  - fs/pnode.c:get_dominating_id
```
**Symbols:**

```
ffffffff8151a720-ffffffff8151a787: is_path_reachable (STB_GLOBAL)
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
bool is_path_reachable(struct mount *mnt, struct dentry *dentry, const struct path *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffff8000103ba5d0)
Location: fs/namespace.c:3580
Inline: False
Direct callers:
  - fs/namespace.c:__arm64_sys_pivot_root
  - fs/namespace.c:__arm64_sys_pivot_root
  - fs/namespace.c:path_is_under
  - fs/pnode.c:get_dominating_id
```
**Symbols:**

```
ffff8000103ba5d0-ffff8000103ba65c: is_path_reachable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool is_path_reachable(struct mount *mnt, struct dentry *dentry, const struct path *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (c0598404)
Location: fs/namespace.c:3580
Inline: False
Direct callers:
  - fs/namespace.c:__se_sys_pivot_root
  - fs/namespace.c:__se_sys_pivot_root
  - fs/namespace.c:path_is_under
  - fs/pnode.c:get_dominating_id
```
**Symbols:**

```
c0598404-c0598468: is_path_reachable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool is_path_reachable(struct mount *mnt, struct dentry *dentry, const struct path *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (c0000000004b7dd0)
Location: fs/namespace.c:3580
Inline: False
Direct callers:
  - fs/namespace.c:__se_sys_pivot_root
  - fs/namespace.c:__se_sys_pivot_root
  - fs/namespace.c:path_is_under
  - fs/pnode.c:get_dominating_id
```
**Symbols:**

```
c0000000004b7dd0-c0000000004b7e5c: is_path_reachable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool is_path_reachable(struct mount *mnt, struct dentry *dentry, const struct path *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffe00027cafc)
Location: fs/namespace.c:3580
Inline: False
Direct callers:
  - fs/namespace.c:__se_sys_pivot_root
  - fs/namespace.c:__se_sys_pivot_root
  - fs/namespace.c:path_is_under
  - fs/pnode.c:get_dominating_id
```
**Symbols:**

```
ffffffe00027cafc-ffffffe00027cb68: is_path_reachable (STB_GLOBAL)
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
bool is_path_reachable(struct mount *mnt, struct dentry *dentry, const struct path *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812ff480)
Location: fs/namespace.c:3580
Inline: False
Direct callers:
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:path_is_under
  - fs/pnode.c:get_dominating_id
```
**Symbols:**

```
ffffffff812ff480-ffffffff812ff4c4: is_path_reachable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool is_path_reachable(struct mount *mnt, struct dentry *dentry, const struct path *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812f00a0)
Location: fs/namespace.c:3580
Inline: False
Direct callers:
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:path_is_under
  - fs/pnode.c:get_dominating_id
```
**Symbols:**

```
ffffffff812f00a0-ffffffff812f00e4: is_path_reachable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool is_path_reachable(struct mount *mnt, struct dentry *dentry, const struct path *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812fd270)
Location: fs/namespace.c:3580
Inline: False
Direct callers:
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:path_is_under
  - fs/pnode.c:get_dominating_id
```
**Symbols:**

```
ffffffff812fd270-ffffffff812fd2b4: is_path_reachable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool is_path_reachable(struct mount *mnt, struct dentry *dentry, const struct path *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8130e5d0)
Location: fs/namespace.c:3580
Inline: False
Direct callers:
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:path_is_under
  - fs/pnode.c:get_dominating_id
```
**Symbols:**

```
ffffffff8130e5d0-ffffffff8130e614: is_path_reachable (STB_GLOBAL)
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
