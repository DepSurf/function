# Function: <code>landlock_append_fs_rule</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int landlock_append_fs_rule(const struct landlock_ruleset * ruleset, const const struct path * path, u32 access_rights);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/landlock/fs.c (ffffffff81539070)
Location: security/landlock/fs.c:157
Inline: False
Direct callers:
  - security/landlock/syscalls.c:__ia32_sys_landlock_add_rule
  - security/landlock/syscalls.c:__x64_sys_landlock_add_rule
```
**Symbols:**

```
ffffffff81539070-ffffffff81539214: landlock_append_fs_rule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int landlock_append_fs_rule(const struct landlock_ruleset * ruleset, const const struct path * path, u32 access_rights);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/landlock/fs.c (ffffffff815978b0)
Location: security/landlock/fs.c:157
Inline: False
Direct callers:
  - security/landlock/syscalls.c:__ia32_sys_landlock_add_rule
  - security/landlock/syscalls.c:__x64_sys_landlock_add_rule
```
**Symbols:**

```
ffffffff815978b0-ffffffff81597a54: landlock_append_fs_rule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int landlock_append_fs_rule(const struct landlock_ruleset * ruleset, const const struct path * path, access_mask_t access_rights);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/landlock/fs.c (ffffffff8163c020)
Location: security/landlock/fs.c:155
Inline: False
Direct callers:
  - security/landlock/syscalls.c:__ia32_sys_landlock_add_rule
  - security/landlock/syscalls.c:__x64_sys_landlock_add_rule
```
**Symbols:**

```
ffffffff8163c020-ffffffff8163c1d5: landlock_append_fs_rule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int landlock_append_fs_rule(const struct landlock_ruleset * ruleset, const const struct path * path, access_mask_t access_rights);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/landlock/fs.c (ffffffff816f3800)
Location: security/landlock/fs.c:166
Inline: False
Direct callers:
  - security/landlock/syscalls.c:__ia32_sys_landlock_add_rule
  - security/landlock/syscalls.c:__x64_sys_landlock_add_rule
```
**Symbols:**

```
ffffffff816f3800-ffffffff816f39b7: landlock_append_fs_rule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int landlock_append_fs_rule(const struct landlock_ruleset * ruleset, const const struct path * path, access_mask_t access_rights);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/landlock/fs.c (ffffffff8172d930)
Location: security/landlock/fs.c:166
Inline: False
Direct callers:
  - security/landlock/syscalls.c:__ia32_sys_landlock_add_rule
  - security/landlock/syscalls.c:__x64_sys_landlock_add_rule
```
**Symbols:**

```
ffffffff8172d930-ffffffff8172dadf: landlock_append_fs_rule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int landlock_append_fs_rule(const struct landlock_ruleset * ruleset, const const struct path * path, access_mask_t access_rights);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/landlock/fs.c (ffffffff8176dff0)
Location: security/landlock/fs.c:156
Inline: False
Direct callers:
  - security/landlock/syscalls.c:add_rule_path_beneath
```
**Symbols:**

```
ffffffff8176dff0-ffffffff8176e1aa: landlock_append_fs_rule (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>u32 access_rights</code> ➡️ <code>access_mask_t access_rights</code>
</li>
</ul>
</details>
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
