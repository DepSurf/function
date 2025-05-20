# Function: <code>aa_policy_admin_capable</code>

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
bool aa_policy_admin_capable(struct aa_label *label, struct aa_ns *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/apparmor/policy.c (0)
Location: security/apparmor/policy.c:725
Inline: False
Direct callers:
  - security/apparmor/policy.c:aa_may_manage_policy
  - security/apparmor/policy.c:aa_current_policy_admin_capable
  - security/apparmor/policy.c:aa_current_policy_admin_capable
```
**Symbols:**

```
ffffffff81e892f6-ffffffff81e8935d: aa_policy_admin_capable.cold (STB_LOCAL)
ffffffff8161b170-ffffffff8161b2d9: aa_policy_admin_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
bool aa_policy_admin_capable(const struct cred *subj_cred, struct aa_label *label, struct aa_ns *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/apparmor/policy.c (0)
Location: security/apparmor/policy.c:803
Inline: False
Direct callers:
  - security/apparmor/policy.c:aa_may_manage_policy
  - security/apparmor/policy.c:aa_current_policy_admin_capable
  - security/apparmor/policy.c:aa_current_policy_admin_capable
```
**Symbols:**

```
ffffffff82074b2a-ffffffff82074b60: aa_policy_admin_capable.cold (STB_LOCAL)
ffffffff816ce210-ffffffff816ce364: aa_policy_admin_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool aa_policy_admin_capable(const struct cred *subj_cred, struct aa_label *label, struct aa_ns *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/apparmor/policy.c (0)
Location: security/apparmor/policy.c:838
Inline: False
Direct callers:
  - security/apparmor/policy.c:aa_may_manage_policy
  - security/apparmor/policy.c:aa_current_policy_admin_capable
  - security/apparmor/policy.c:aa_current_policy_admin_capable
```
**Symbols:**

```
ffffffff820f472f-ffffffff820f4765: aa_policy_admin_capable.cold (STB_LOCAL)
ffffffff81706e80-ffffffff81706f90: aa_policy_admin_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool aa_policy_admin_capable(const struct cred *subj_cred, struct aa_label *label, struct aa_ns *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/apparmor/policy.c (0)
Location: security/apparmor/policy.c:869
Inline: False
Direct callers:
  - security/apparmor/policy.c:aa_may_manage_policy
  - security/apparmor/policy.c:aa_current_policy_admin_capable
  - security/apparmor/policy.c:aa_current_policy_admin_capable
```
**Symbols:**

```
ffffffff821d1b69-ffffffff821d1b9f: aa_policy_admin_capable.cold (STB_LOCAL)
ffffffff81744920-ffffffff81744a20: aa_policy_admin_capable (STB_GLOBAL)
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
<code>const struct cred *subj_cred</code>
</li>
<li>
<b>Param reordered. </b>
<code>label, ns</code> ➡️ <code>subj_cred, label, ns</code>
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
