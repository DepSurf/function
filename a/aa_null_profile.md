# Function: <code>aa_null_profile</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct aa_profile *aa_null_profile(struct aa_profile *parent, bool hat, const char *base, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff8137fcb0)
Location: security/apparmor/policy.c:290
Inline: False
Direct callers:
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:aa_change_profile
```
**Symbols:**

```
ffffffff8137fcb0-ffffffff8137ffea: aa_null_profile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct aa_profile *aa_null_profile(struct aa_profile *parent, bool hat, const char *base, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff813b9680)
Location: security/apparmor/policy.c:315
Inline: False
Direct callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:profile_transition
```
**Symbols:**

```
ffffffff813b9680-ffffffff813b99a9: aa_null_profile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct aa_profile *aa_null_profile(struct aa_profile *parent, bool hat, const char *base, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff813d0a40)
Location: security/apparmor/policy.c:315
Inline: False
Direct callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:profile_transition
```
**Symbols:**

```
ffffffff813d0a40-ffffffff813d0d70: aa_null_profile (STB_GLOBAL)
```
</details>
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
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
</ul>
