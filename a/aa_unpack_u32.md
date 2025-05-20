# Function: <code>aa_unpack_u32</code>

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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
bool aa_unpack_u32(struct aa_ext *e, u32 *data, const char *name);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/policy_unpack.c (ffffffff816d2f2c)
Location: security/apparmor/policy_unpack.c:292
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:aa_unpack
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_pdb
  - security/apparmor/policy_unpack.c:unpack_pdb
  - security/apparmor/policy_unpack.c:unpack_pdb
  - security/apparmor/policy_unpack.c:unpack_perm
  - security/apparmor/policy_unpack.c:unpack_perm
  - security/apparmor/policy_unpack.c:unpack_perm
  - security/apparmor/policy_unpack.c:unpack_perm
  - security/apparmor/policy_unpack.c:unpack_perm
  - security/apparmor/policy_unpack.c:unpack_perm
  - security/apparmor/policy_unpack.c:unpack_rlimits
Direct callers:
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_perm
  - security/apparmor/policy_unpack.c:unpack_perm
  - security/apparmor/policy_unpack.c:unpack_perm
  - security/apparmor/policy_unpack.c:unpack_perm
  - security/apparmor/policy_unpack.c:unpack_perm
  - security/apparmor/policy_unpack.c:unpack_perm
  - security/apparmor/policy_unpack.c:unpack_perm
  - security/apparmor/policy_unpack.c:unpack_perm
```
**Symbols:**

```
ffffffff816d0180-ffffffff816d01fa: aa_unpack_u32 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
bool aa_unpack_u32(struct aa_ext *e, u32 *data, const char *name);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/policy_unpack.c (ffffffff8170bf2b)
Location: security/apparmor/policy_unpack.c:283
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:aa_unpack
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_pdb
  - security/apparmor/policy_unpack.c:unpack_pdb
  - security/apparmor/policy_unpack.c:unpack_pdb
  - security/apparmor/policy_unpack.c:unpack_perm
  - security/apparmor/policy_unpack.c:unpack_perm
  - security/apparmor/policy_unpack.c:unpack_perm
  - security/apparmor/policy_unpack.c:unpack_perm
  - security/apparmor/policy_unpack.c:unpack_perm
  - security/apparmor/policy_unpack.c:unpack_perm
  - security/apparmor/policy_unpack.c:unpack_rlimits
Direct callers:
  - security/apparmor/policy_unpack.c:unpack_perm
  - security/apparmor/policy_unpack.c:unpack_perm
  - security/apparmor/policy_unpack.c:unpack_perm
  - security/apparmor/policy_unpack.c:unpack_perm
  - security/apparmor/policy_unpack.c:unpack_perm
  - security/apparmor/policy_unpack.c:unpack_perm
  - security/apparmor/policy_unpack.c:unpack_perm
  - security/apparmor/policy_unpack.c:unpack_perm
```
**Symbols:**

```
ffffffff81708dd0-ffffffff81708e4a: aa_unpack_u32 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
bool aa_unpack_u32(struct aa_ext *e, u32 *data, const char *name);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/policy_unpack.c (ffffffff81749c3b)
Location: security/apparmor/policy_unpack.c:287
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:aa_unpack
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_pdb
  - security/apparmor/policy_unpack.c:unpack_pdb
  - security/apparmor/policy_unpack.c:unpack_pdb
  - security/apparmor/policy_unpack.c:unpack_pdb
  - security/apparmor/policy_unpack.c:unpack_perm
  - security/apparmor/policy_unpack.c:unpack_perm
  - security/apparmor/policy_unpack.c:unpack_perm
  - security/apparmor/policy_unpack.c:unpack_perm
  - security/apparmor/policy_unpack.c:unpack_perm
  - security/apparmor/policy_unpack.c:unpack_perm
  - security/apparmor/policy_unpack.c:unpack_rlimits
Direct callers:
  - security/apparmor/policy_unpack.c:unpack_perm
  - security/apparmor/policy_unpack.c:unpack_perm
  - security/apparmor/policy_unpack.c:unpack_perm
  - security/apparmor/policy_unpack.c:unpack_perm
  - security/apparmor/policy_unpack.c:unpack_perm
  - security/apparmor/policy_unpack.c:unpack_perm
  - security/apparmor/policy_unpack.c:unpack_perm
  - security/apparmor/policy_unpack.c:unpack_perm
```
**Symbols:**

```
ffffffff81746860-ffffffff817468da: aa_unpack_u32 (STB_LOCAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
