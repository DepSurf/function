# Function: <code>aa_profile_ns_perm</code>

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
int aa_profile_ns_perm(struct aa_profile *profile, struct common_audit_data *sa, u32 request);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/apparmor/task.c (0)
Location: security/apparmor/task.c:309
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_userns_create
```
**Symbols:**

```
ffffffff81e8908e-ffffffff81e890a3: aa_profile_ns_perm.cold (STB_LOCAL)
ffffffff816107f0-ffffffff816109e5: aa_profile_ns_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int aa_profile_ns_perm(struct aa_profile *profile, struct apparmor_audit_data *ad, u32 request);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/task.c (ffffffff816c3260)
Location: security/apparmor/task.c:318
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_userns_create
```
**Symbols:**

```
ffffffff816c3260-ffffffff816c343e: aa_profile_ns_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int aa_profile_ns_perm(struct aa_profile *profile, struct apparmor_audit_data *ad, u32 request);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/task.c (ffffffff816fbe10)
Location: security/apparmor/task.c:318
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_userns_create
```
**Symbols:**

```
ffffffff816fbe10-ffffffff816fc017: aa_profile_ns_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct aa_label *aa_profile_ns_perm(struct aa_profile *profile, struct apparmor_audit_data *ad, u32 request);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/task.c (ffffffff81738db0)
Location: security/apparmor/task.c:398
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_userns_create
  - security/apparmor/lsm.c:apparmor_userns_create
```
**Symbols:**

```
ffffffff81738db0-ffffffff81739577: aa_profile_ns_perm (STB_GLOBAL)
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>struct aa_label *</code>
</li>
</ul>
</details>
</li>
</ul>
