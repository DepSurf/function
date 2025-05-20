# Function: <code>selinux_policy_genfs_sid</code>

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
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int selinux_policy_genfs_sid(struct selinux_policy *policy, const char *fstype, char *path, u16 orig_sclass, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff814e9aa0)
Location: security/selinux/ss/services.c:2870
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_make_bools
```
**Symbols:**

```
ffffffff814e9aa0-ffffffff814e9ab3: selinux_policy_genfs_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int selinux_policy_genfs_sid(struct selinux_policy *policy, const char *fstype, char *path, u16 orig_sclass, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff814f0640)
Location: security/selinux/ss/services.c:2938
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_make_bools
```
**Symbols:**

```
ffffffff814f0640-ffffffff814f0653: selinux_policy_genfs_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int selinux_policy_genfs_sid(struct selinux_policy *policy, const char *fstype, char *path, u16 orig_sclass, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8154aba0)
Location: security/selinux/ss/services.c:2948
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_make_bools
```
**Symbols:**

```
ffffffff8154aba0-ffffffff8154abb3: selinux_policy_genfs_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int selinux_policy_genfs_sid(struct selinux_policy *policy, const char *fstype, const char *path, u16 orig_sclass, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff815e38b0)
Location: security/selinux/ss/services.c:2951
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_make_bools
```
**Symbols:**

```
ffffffff815e38b0-ffffffff815e38d2: selinux_policy_genfs_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int selinux_policy_genfs_sid(struct selinux_policy *policy, const char *fstype, const char *path, u16 orig_sclass, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff81692b40)
Location: security/selinux/ss/services.c:2944
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_make_bools
```
**Symbols:**

```
ffffffff81692b40-ffffffff81692b62: selinux_policy_genfs_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int selinux_policy_genfs_sid(struct selinux_policy *policy, const char *fstype, const char *path, u16 orig_sclass, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff816cb0a0)
Location: security/selinux/ss/services.c:2892
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_make_bools
```
**Symbols:**

```
ffffffff816cb0a0-ffffffff816cb0c2: selinux_policy_genfs_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int selinux_policy_genfs_sid(struct selinux_policy *policy, const char *fstype, const char *path, u16 orig_sclass, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff81707ce0)
Location: security/selinux/ss/services.c:2901
Inline: False
```
**Symbols:**

```
ffffffff81707ce0-ffffffff81707d02: selinux_policy_genfs_sid (STB_GLOBAL)
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
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>char *path</code> ➡️ <code>const char *path</code>
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
