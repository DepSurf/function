# Function: <code>aa_profile_mqueue_perm</code>

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
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int aa_profile_mqueue_perm(struct aa_profile *profile, const struct path *path, u32 request, char *buffer, struct common_audit_data *sa);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/apparmor/ipc.c (0)
Location: security/apparmor/ipc.c:137
Inline: False
Direct callers:
  - security/apparmor/ipc.c:aa_mqueue_perm
  - security/apparmor/file.c:__file_mqueue_perm
  - security/apparmor/file.c:__file_mqueue_perm
  - security/apparmor/file.c:__file_mqueue_perm
```
**Symbols:**

```
ffffffff81e890a3-ffffffff81e890bc: aa_profile_mqueue_perm.cold (STB_LOCAL)
ffffffff81610f40-ffffffff816110d9: aa_profile_mqueue_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int aa_profile_mqueue_perm(struct aa_profile *profile, const struct path *path, u32 request, char *buffer, struct apparmor_audit_data *ad);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/ipc.c (ffffffff816c39a0)
Location: security/apparmor/ipc.c:145
Inline: False
Direct callers:
  - security/apparmor/ipc.c:aa_mqueue_perm
  - security/apparmor/file.c:__file_mqueue_perm
  - security/apparmor/file.c:__file_mqueue_perm
  - security/apparmor/file.c:__file_mqueue_perm
```
**Symbols:**

```
ffffffff816c39a0-ffffffff816c3b36: aa_profile_mqueue_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int aa_profile_mqueue_perm(struct aa_profile *profile, const struct path *path, u32 request, char *buffer, struct apparmor_audit_data *ad);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/ipc.c (ffffffff816fc590)
Location: security/apparmor/ipc.c:145
Inline: False
Direct callers:
  - security/apparmor/ipc.c:aa_mqueue_perm
  - security/apparmor/file.c:__file_mqueue_perm
  - security/apparmor/file.c:__file_mqueue_perm
  - security/apparmor/file.c:__file_mqueue_perm
```
**Symbols:**

```
ffffffff816fc590-ffffffff816fc72a: aa_profile_mqueue_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int aa_profile_mqueue_perm(struct aa_profile *profile, const struct path *path, u32 request, char *buffer, struct apparmor_audit_data *ad);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/ipc.c (ffffffff81739ae0)
Location: security/apparmor/ipc.c:144
Inline: False
Direct callers:
  - security/apparmor/ipc.c:aa_mqueue_perm
  - security/apparmor/file.c:__file_mqueue_perm
  - security/apparmor/file.c:__file_mqueue_perm
  - security/apparmor/file.c:__file_mqueue_perm
```
**Symbols:**

```
ffffffff81739ae0-ffffffff81739c85: aa_profile_mqueue_perm (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct apparmor_audit_data *ad</code>
</li>
<li>
<b>Param removed. </b>
<code>struct common_audit_data *sa</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
