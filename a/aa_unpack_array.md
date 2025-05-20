# Function: <code>aa_unpack_array</code>

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
bool aa_unpack_array(struct aa_ext *e, const char *name, u16 *size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/policy_unpack.c (ffffffff816d1af9)
Location: security/apparmor/policy_unpack.c:330
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_pdb
  - security/apparmor/policy_unpack.c:unpack_rlimits
  - security/apparmor/policy_unpack.c:unpack_secmark
  - security/apparmor/policy_unpack.c:unpack_xattrs
  - security/apparmor/policy_unpack.c:unpack_trans_table
Direct callers:
  - security/apparmor/policy_unpack.c:unpack_profile
```
**Symbols:**

```
ffffffff816d0210-ffffffff816d028a: aa_unpack_array (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
bool aa_unpack_array(struct aa_ext *e, const char *name, u16 *size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/policy_unpack.c (ffffffff8170a9e7)
Location: security/apparmor/policy_unpack.c:341
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_pdb
  - security/apparmor/policy_unpack.c:unpack_rlimits
  - security/apparmor/policy_unpack.c:unpack_secmark
  - security/apparmor/policy_unpack.c:unpack_xattrs
  - security/apparmor/policy_unpack.c:unpack_trans_table
Direct callers:
  - security/apparmor/policy_unpack.c:unpack_profile
```
**Symbols:**

```
ffffffff81708e60-ffffffff81708eda: aa_unpack_array (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
bool aa_unpack_array(struct aa_ext *e, const char *name, u16 *size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/policy_unpack.c (ffffffff817484ca)
Location: security/apparmor/policy_unpack.c:345
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_pdb
  - security/apparmor/policy_unpack.c:unpack_rlimits
  - security/apparmor/policy_unpack.c:unpack_secmark
  - security/apparmor/policy_unpack.c:unpack_xattrs
  - security/apparmor/policy_unpack.c:unpack_trans_table
Direct callers:
  - security/apparmor/policy_unpack.c:unpack_profile
```
**Symbols:**

```
ffffffff817468f0-ffffffff8174696a: aa_unpack_array (STB_LOCAL)
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
