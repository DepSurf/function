# Function: <code>unpack_perm</code>

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
<summary>In <code>5.19</code>: ✅</summary>

```c
bool unpack_perm(struct aa_ext *e, u32 version, struct aa_perms *perm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy_unpack.c (ffffffff8161e150)
Location: security/apparmor/policy_unpack.c:678
Inline: False
Direct callers:
  - security/apparmor/policy_unpack.c:unpack_pdb
```
**Symbols:**

```
ffffffff8161e150-ffffffff8161e41f: unpack_perm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool unpack_perm(struct aa_ext *e, u32 version, struct aa_perms *perm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy_unpack.c (ffffffff816d1560)
Location: security/apparmor/policy_unpack.c:646
Inline: False
Direct callers:
  - security/apparmor/policy_unpack.c:unpack_pdb
```
**Symbols:**

```
ffffffff816d1560-ffffffff816d182f: unpack_perm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool unpack_perm(struct aa_ext *e, u32 version, struct aa_perms *perm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy_unpack.c (ffffffff8170a460)
Location: security/apparmor/policy_unpack.c:657
Inline: False
Direct callers:
  - security/apparmor/policy_unpack.c:unpack_pdb
```
**Symbols:**

```
ffffffff8170a460-ffffffff8170a72f: unpack_perm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool unpack_perm(struct aa_ext *e, u32 version, struct aa_perms *perm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy_unpack.c (ffffffff81747f60)
Location: security/apparmor/policy_unpack.c:660
Inline: False
Direct callers:
  - security/apparmor/policy_unpack.c:unpack_pdb
```
**Symbols:**

```
ffffffff81747f60-ffffffff8174822f: unpack_perm (STB_LOCAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
