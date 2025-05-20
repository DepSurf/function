# Function: <code>aa_inbounds</code>

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
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/policy_unpack.c (ffffffff816d2f39)
Location: security/apparmor/policy_unpack.c:159
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
  - security/apparmor/policy_unpack.c:unpack_pdb
  - security/apparmor/policy_unpack.c:unpack_perm
  - security/apparmor/policy_unpack.c:unpack_perm
  - security/apparmor/policy_unpack.c:unpack_perm
  - security/apparmor/policy_unpack.c:unpack_perm
  - security/apparmor/policy_unpack.c:unpack_perm
  - security/apparmor/policy_unpack.c:unpack_perm
  - security/apparmor/policy_unpack.c:unpack_perm
  - security/apparmor/policy_unpack.c:unpack_perm
  - security/apparmor/policy_unpack.c:unpack_perm
  - security/apparmor/policy_unpack.c:unpack_perm
  - security/apparmor/policy_unpack.c:unpack_rlimits
  - security/apparmor/policy_unpack.c:unpack_rlimits
  - security/apparmor/policy_unpack.c:unpack_rlimits
  - security/apparmor/policy_unpack.c:unpack_secmark
  - security/apparmor/policy_unpack.c:unpack_secmark
  - security/apparmor/policy_unpack.c:unpack_secmark
  - security/apparmor/policy_unpack.c:unpack_xattrs
  - security/apparmor/policy_unpack.c:unpack_trans_table
  - security/apparmor/policy_unpack.c:aa_unpack_str
  - security/apparmor/policy_unpack.c:aa_unpack_str
  - security/apparmor/policy_unpack.c:aa_unpack_blob
  - security/apparmor/policy_unpack.c:aa_unpack_blob
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/policy_unpack.c (ffffffff8170bf38)
Location: security/apparmor/policy_unpack.c:159
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
  - security/apparmor/policy_unpack.c:unpack_pdb
  - security/apparmor/policy_unpack.c:unpack_perm
  - security/apparmor/policy_unpack.c:unpack_perm
  - security/apparmor/policy_unpack.c:unpack_perm
  - security/apparmor/policy_unpack.c:unpack_perm
  - security/apparmor/policy_unpack.c:unpack_perm
  - security/apparmor/policy_unpack.c:unpack_perm
  - security/apparmor/policy_unpack.c:unpack_perm
  - security/apparmor/policy_unpack.c:unpack_perm
  - security/apparmor/policy_unpack.c:unpack_perm
  - security/apparmor/policy_unpack.c:unpack_perm
  - security/apparmor/policy_unpack.c:unpack_rlimits
  - security/apparmor/policy_unpack.c:unpack_rlimits
  - security/apparmor/policy_unpack.c:unpack_rlimits
  - security/apparmor/policy_unpack.c:unpack_secmark
  - security/apparmor/policy_unpack.c:unpack_secmark
  - security/apparmor/policy_unpack.c:unpack_secmark
  - security/apparmor/policy_unpack.c:unpack_xattrs
  - security/apparmor/policy_unpack.c:unpack_trans_table
  - security/apparmor/policy_unpack.c:aa_unpack_str
  - security/apparmor/policy_unpack.c:aa_unpack_str
  - security/apparmor/policy_unpack.c:aa_unpack_blob
  - security/apparmor/policy_unpack.c:aa_unpack_blob
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/policy_unpack.c (ffffffff81749c48)
Location: security/apparmor/policy_unpack.c:163
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
  - security/apparmor/policy_unpack.c:unpack_pdb
  - security/apparmor/policy_unpack.c:unpack_perm
  - security/apparmor/policy_unpack.c:unpack_perm
  - security/apparmor/policy_unpack.c:unpack_perm
  - security/apparmor/policy_unpack.c:unpack_perm
  - security/apparmor/policy_unpack.c:unpack_perm
  - security/apparmor/policy_unpack.c:unpack_perm
  - security/apparmor/policy_unpack.c:unpack_perm
  - security/apparmor/policy_unpack.c:unpack_perm
  - security/apparmor/policy_unpack.c:unpack_perm
  - security/apparmor/policy_unpack.c:unpack_perm
  - security/apparmor/policy_unpack.c:unpack_rlimits
  - security/apparmor/policy_unpack.c:unpack_rlimits
  - security/apparmor/policy_unpack.c:unpack_rlimits
  - security/apparmor/policy_unpack.c:unpack_secmark
  - security/apparmor/policy_unpack.c:unpack_secmark
  - security/apparmor/policy_unpack.c:unpack_secmark
  - security/apparmor/policy_unpack.c:unpack_xattrs
  - security/apparmor/policy_unpack.c:unpack_trans_table
  - security/apparmor/policy_unpack.c:aa_unpack_str
  - security/apparmor/policy_unpack.c:aa_unpack_str
  - security/apparmor/policy_unpack.c:aa_unpack_blob
  - security/apparmor/policy_unpack.c:aa_unpack_blob
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
