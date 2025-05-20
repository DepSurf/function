# Function: <code>policy_admin_capable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
bool policy_admin_capable();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff81380710)
Location: security/apparmor/policy.c:620
Inline: False
Direct callers:
  - security/apparmor/policy.c:aa_may_manage_policy
  - security/apparmor/lsm.c:param_get_mode
  - security/apparmor/lsm.c:param_get_audit
  - security/apparmor/lsm.c:param_set_mode
  - security/apparmor/lsm.c:param_set_audit
  - security/apparmor/lsm.c:param_get_aabool
  - security/apparmor/lsm.c:param_set_aabool
  - security/apparmor/lsm.c:param_set_aalockpolicy
  - security/apparmor/lsm.c:param_get_aauint
  - security/apparmor/lsm.c:param_set_aauint
  - security/apparmor/lsm.c:apparmor_dointvec
```
**Symbols:**

```
ffffffff81380710-ffffffff8138094a: policy_admin_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool policy_admin_capable(struct aa_ns *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff813ba3e0)
Location: security/apparmor/policy.c:673
Inline: False
Direct callers:
  - security/apparmor/policy.c:aa_may_manage_policy
  - security/apparmor/lsm.c:apparmor_dointvec
  - security/apparmor/lsm.c:param_set_mode
  - security/apparmor/lsm.c:param_set_audit
  - security/apparmor/lsm.c:param_set_aauint
  - security/apparmor/lsm.c:param_set_aabool
  - security/apparmor/lsm.c:param_set_aalockpolicy
```
**Symbols:**

```
ffffffff813ba3e0-ffffffff813ba490: policy_admin_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool policy_admin_capable(struct aa_ns *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff813d17a0)
Location: security/apparmor/policy.c:674
Inline: False
Direct callers:
  - security/apparmor/policy.c:aa_may_manage_policy
  - security/apparmor/lsm.c:apparmor_dointvec
  - security/apparmor/lsm.c:param_set_aauint
  - security/apparmor/lsm.c:param_set_aabool
```
**Symbols:**

```
ffffffff813d17a0-ffffffff813d1850: policy_admin_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool policy_admin_capable(struct aa_ns *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff813e4600)
Location: security/apparmor/policy.c:659
Inline: False
Direct callers:
  - security/apparmor/policy.c:aa_may_manage_policy
  - security/apparmor/lsm.c:apparmor_dointvec
  - security/apparmor/lsm.c:param_set_aabool
```
**Symbols:**

```
ffffffff813e4600-ffffffff813e46e7: policy_admin_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool policy_admin_capable(struct aa_ns *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff8140b5b0)
Location: security/apparmor/policy.c:660
Inline: False
Direct callers:
  - security/apparmor/policy.c:aa_may_manage_policy
  - security/apparmor/lsm.c:apparmor_dointvec
  - security/apparmor/lsm.c:param_set_aabool
```
**Symbols:**

```
ffffffff8140b5b0-ffffffff8140b697: policy_admin_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool policy_admin_capable(struct aa_ns *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff8143cf00)
Location: security/apparmor/policy.c:665
Inline: False
Direct callers:
  - security/apparmor/policy.c:aa_may_manage_policy
  - security/apparmor/lsm.c:apparmor_dointvec
  - security/apparmor/lsm.c:param_set_mode
  - security/apparmor/lsm.c:param_set_audit
  - security/apparmor/lsm.c:param_set_aabool
```
**Symbols:**

```
ffffffff8143cf00-ffffffff8143cfe7: policy_admin_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool policy_admin_capable(struct aa_ns *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff81459d70)
Location: security/apparmor/policy.c:665
Inline: False
Direct callers:
  - security/apparmor/policy.c:aa_may_manage_policy
  - security/apparmor/lsm.c:apparmor_dointvec
  - security/apparmor/lsm.c:param_set_mode
  - security/apparmor/lsm.c:param_set_audit
  - security/apparmor/lsm.c:param_set_aabool
```
**Symbols:**

```
ffffffff81459d70-ffffffff81459e4a: policy_admin_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool policy_admin_capable(struct aa_ns *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff814873d0)
Location: security/apparmor/policy.c:660
Inline: False
Direct callers:
  - security/apparmor/policy.c:aa_may_manage_policy
  - security/apparmor/lsm.c:apparmor_dointvec
  - security/apparmor/lsm.c:param_set_mode
  - security/apparmor/lsm.c:param_set_audit
  - security/apparmor/lsm.c:param_set_aabool
  - security/apparmor/lsm.c:param_set_aalockpolicy
```
**Symbols:**

```
ffffffff814873d0-ffffffff814874a2: policy_admin_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool policy_admin_capable(struct aa_ns *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff814a1280)
Location: security/apparmor/policy.c:660
Inline: False
Direct callers:
  - security/apparmor/policy.c:aa_may_manage_policy
  - security/apparmor/lsm.c:apparmor_dointvec
  - security/apparmor/lsm.c:param_set_mode
  - security/apparmor/lsm.c:param_set_audit
  - security/apparmor/lsm.c:param_set_aabool
  - security/apparmor/lsm.c:param_set_aalockpolicy
```
**Symbols:**

```
ffffffff814a1280-ffffffff814a1352: policy_admin_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool policy_admin_capable(struct aa_ns *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff814fb420)
Location: security/apparmor/policy.c:664
Inline: False
Direct callers:
  - security/apparmor/policy.c:aa_may_manage_policy
  - security/apparmor/lsm.c:apparmor_dointvec
  - security/apparmor/lsm.c:param_set_mode
  - security/apparmor/lsm.c:param_set_audit
```
**Symbols:**

```
ffffffff814fb420-ffffffff814fb4f2: policy_admin_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool policy_admin_capable(struct aa_ns *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff81518470)
Location: security/apparmor/policy.c:664
Inline: False
Direct callers:
  - security/apparmor/policy.c:aa_may_manage_policy
  - security/apparmor/lsm.c:apparmor_dointvec
  - security/apparmor/lsm.c:param_set_mode
  - security/apparmor/lsm.c:param_set_audit
```
**Symbols:**

```
ffffffff81518470-ffffffff81518542: policy_admin_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool policy_admin_capable(struct aa_ns *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff8151ecd0)
Location: security/apparmor/policy.c:664
Inline: False
Direct callers:
  - security/apparmor/policy.c:aa_may_manage_policy
  - security/apparmor/lsm.c:apparmor_dointvec
  - security/apparmor/lsm.c:param_set_mode
  - security/apparmor/lsm.c:param_set_audit
```
**Symbols:**

```
ffffffff8151ecd0-ffffffff8151eda2: policy_admin_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
bool policy_admin_capable(struct aa_ns *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/apparmor/policy.c (0)
Location: security/apparmor/policy.c:664
Inline: False
Direct callers:
  - security/apparmor/policy.c:aa_may_manage_policy
  - security/apparmor/lsm.c:apparmor_dointvec
  - security/apparmor/lsm.c:param_set_mode
  - security/apparmor/lsm.c:param_set_audit
```
**Symbols:**

```
ffffffff81cd64e1-ffffffff81cd654a: policy_admin_capable.cold (STB_LOCAL)
ffffffff8157ce20-ffffffff8157cf36: policy_admin_capable (STB_GLOBAL)
```
</details>
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
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
bool policy_admin_capable(struct aa_ns *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffff800010596f88)
Location: security/apparmor/policy.c:660
Inline: False
Direct callers:
  - security/apparmor/policy.c:aa_may_manage_policy
  - security/apparmor/lsm.c:apparmor_dointvec
  - security/apparmor/lsm.c:param_set_mode
  - security/apparmor/lsm.c:param_set_audit
  - security/apparmor/lsm.c:param_set_aabool
```
**Symbols:**

```
ffff800010596f88-ffff80001059709c: policy_admin_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool policy_admin_capable(struct aa_ns *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (c074806c)
Location: security/apparmor/policy.c:660
Inline: False
Direct callers:
  - security/apparmor/policy.c:aa_may_manage_policy
  - security/apparmor/lsm.c:apparmor_dointvec
  - security/apparmor/lsm.c:param_set_mode
  - security/apparmor/lsm.c:param_set_audit
  - security/apparmor/lsm.c:param_set_aabool
```
**Symbols:**

```
c074806c-c0748180: policy_admin_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool policy_admin_capable(struct aa_ns *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (c00000000070d0f0)
Location: security/apparmor/policy.c:660
Inline: False
Direct callers:
  - security/apparmor/policy.c:aa_may_manage_policy
  - security/apparmor/lsm.c:apparmor_dointvec
  - security/apparmor/lsm.c:param_set_mode
  - security/apparmor/lsm.c:param_set_audit
  - security/apparmor/lsm.c:param_set_aabool
  - security/apparmor/lsm.c:param_set_aalockpolicy
```
**Symbols:**

```
c00000000070d0f0-c00000000070d240: policy_admin_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool policy_admin_capable(struct aa_ns *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffe0003e3c3a)
Location: security/apparmor/policy.c:660
Inline: False
Direct callers:
  - security/apparmor/policy.c:aa_may_manage_policy
  - security/apparmor/lsm.c:apparmor_dointvec
  - security/apparmor/lsm.c:param_set_mode
  - security/apparmor/lsm.c:param_set_audit
  - security/apparmor/lsm.c:param_set_aabool
```
**Symbols:**

```
ffffffe0003e3c3a-ffffffe0003e3d42: policy_admin_capable (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
bool policy_admin_capable(struct aa_ns *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff81499860)
Location: security/apparmor/policy.c:660
Inline: False
Direct callers:
  - security/apparmor/policy.c:aa_may_manage_policy
  - security/apparmor/lsm.c:apparmor_dointvec
  - security/apparmor/lsm.c:param_set_mode
  - security/apparmor/lsm.c:param_set_audit
  - security/apparmor/lsm.c:param_set_aabool
  - security/apparmor/lsm.c:param_set_aalockpolicy
```
**Symbols:**

```
ffffffff81499860-ffffffff81499932: policy_admin_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool policy_admin_capable(struct aa_ns *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff8148a280)
Location: security/apparmor/policy.c:660
Inline: False
Direct callers:
  - security/apparmor/policy.c:aa_may_manage_policy
  - security/apparmor/lsm.c:apparmor_dointvec
  - security/apparmor/lsm.c:param_set_mode
  - security/apparmor/lsm.c:param_set_audit
  - security/apparmor/lsm.c:param_set_aabool
  - security/apparmor/lsm.c:param_set_aalockpolicy
```
**Symbols:**

```
ffffffff8148a280-ffffffff8148a352: policy_admin_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool policy_admin_capable(struct aa_ns *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff81495900)
Location: security/apparmor/policy.c:660
Inline: False
Direct callers:
  - security/apparmor/policy.c:aa_may_manage_policy
  - security/apparmor/lsm.c:apparmor_dointvec
  - security/apparmor/lsm.c:param_set_mode
  - security/apparmor/lsm.c:param_set_audit
  - security/apparmor/lsm.c:param_set_aabool
  - security/apparmor/lsm.c:param_set_aalockpolicy
```
**Symbols:**

```
ffffffff81495900-ffffffff814959d2: policy_admin_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool policy_admin_capable(struct aa_ns *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff814ad990)
Location: security/apparmor/policy.c:660
Inline: False
Direct callers:
  - security/apparmor/policy.c:aa_may_manage_policy
  - security/apparmor/lsm.c:apparmor_dointvec
  - security/apparmor/lsm.c:param_set_mode
  - security/apparmor/lsm.c:param_set_audit
  - security/apparmor/lsm.c:param_set_aabool
  - security/apparmor/lsm.c:param_set_aalockpolicy
```
**Symbols:**

```
ffffffff814ad990-ffffffff814ada62: policy_admin_capable (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct aa_ns *ns</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
