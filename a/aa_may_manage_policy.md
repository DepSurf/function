# Function: <code>aa_may_manage_policy</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int aa_may_manage_policy(struct aa_label *label, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff81380bc0)
Location: security/apparmor/policy.c:661
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:policy_update
  - security/apparmor/apparmorfs.c:profile_remove
```
**Symbols:**

```
ffffffff81380bc0-ffffffff81380c55: aa_may_manage_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int aa_may_manage_policy(struct aa_label *label, struct aa_ns *ns, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff813ba490)
Location: security/apparmor/policy.c:691
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:ns_rmdir_op
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:policy_update
```
**Symbols:**

```
ffffffff813ba490-ffffffff813ba50c: aa_may_manage_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int aa_may_manage_policy(struct aa_label *label, struct aa_ns *ns, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff813d1850)
Location: security/apparmor/policy.c:692
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:ns_rmdir_op
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:policy_update
```
**Symbols:**

```
ffffffff813d1850-ffffffff813d18cc: aa_may_manage_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int aa_may_manage_policy(struct aa_label *label, struct aa_ns *ns, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff813e46f0)
Location: security/apparmor/policy.c:677
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:policy_update
```
**Symbols:**

```
ffffffff813e46f0-ffffffff813e476c: aa_may_manage_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int aa_may_manage_policy(struct aa_label *label, struct aa_ns *ns, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff8140b6a0)
Location: security/apparmor/policy.c:678
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:policy_update
```
**Symbols:**

```
ffffffff8140b6a0-ffffffff8140b71c: aa_may_manage_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int aa_may_manage_policy(struct aa_label *label, struct aa_ns *ns, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff8143cff0)
Location: security/apparmor/policy.c:683
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:policy_update
```
**Symbols:**

```
ffffffff8143cff0-ffffffff8143d06c: aa_may_manage_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int aa_may_manage_policy(struct aa_label *label, struct aa_ns *ns, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff81459e50)
Location: security/apparmor/policy.c:683
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:policy_update
```
**Symbols:**

```
ffffffff81459e50-ffffffff81459ecc: aa_may_manage_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int aa_may_manage_policy(struct aa_label *label, struct aa_ns *ns, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff814874b0)
Location: security/apparmor/policy.c:678
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:policy_update
```
**Symbols:**

```
ffffffff814874b0-ffffffff81487531: aa_may_manage_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int aa_may_manage_policy(struct aa_label *label, struct aa_ns *ns, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff814a1360)
Location: security/apparmor/policy.c:678
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:policy_update
```
**Symbols:**

```
ffffffff814a1360-ffffffff814a13e1: aa_may_manage_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int aa_may_manage_policy(struct aa_label *label, struct aa_ns *ns, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff814fb500)
Location: security/apparmor/policy.c:682
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:policy_update
```
**Symbols:**

```
ffffffff814fb500-ffffffff814fb581: aa_may_manage_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int aa_may_manage_policy(struct aa_label *label, struct aa_ns *ns, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff81518550)
Location: security/apparmor/policy.c:682
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:policy_update
```
**Symbols:**

```
ffffffff81518550-ffffffff815185d1: aa_may_manage_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int aa_may_manage_policy(struct aa_label *label, struct aa_ns *ns, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff8151edb0)
Location: security/apparmor/policy.c:682
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:policy_update
```
**Symbols:**

```
ffffffff8151edb0-ffffffff8151ee31: aa_may_manage_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int aa_may_manage_policy(struct aa_label *label, struct aa_ns *ns, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/apparmor/policy.c (0)
Location: security/apparmor/policy.c:682
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:policy_update
```
**Symbols:**

```
ffffffff81cd654a-ffffffff81cd655e: aa_may_manage_policy.cold (STB_LOCAL)
ffffffff8157cf40-ffffffff8157cfd9: aa_may_manage_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int aa_may_manage_policy(struct aa_label *label, struct aa_ns *ns, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/apparmor/policy.c (0)
Location: security/apparmor/policy.c:768
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:policy_update
```
**Symbols:**

```
ffffffff81e8935d-ffffffff81e89372: aa_may_manage_policy.cold (STB_LOCAL)
ffffffff8161b580-ffffffff8161b641: aa_may_manage_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int aa_may_manage_policy(const struct cred *subj_cred, struct aa_label *label, struct aa_ns *ns, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/apparmor/policy.c (0)
Location: security/apparmor/policy.c:849
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:policy_update
```
**Symbols:**

```
ffffffff82074b60-ffffffff82074b7d: aa_may_manage_policy.cold (STB_LOCAL)
ffffffff816ce640-ffffffff816ce70d: aa_may_manage_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int aa_may_manage_policy(const struct cred *subj_cred, struct aa_label *label, struct aa_ns *ns, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/apparmor/policy.c (0)
Location: security/apparmor/policy.c:884
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:policy_update
```
**Symbols:**

```
ffffffff820f4765-ffffffff820f4782: aa_may_manage_policy.cold (STB_LOCAL)
ffffffff81707260-ffffffff8170732d: aa_may_manage_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int aa_may_manage_policy(const struct cred *subj_cred, struct aa_label *label, struct aa_ns *ns, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/apparmor/policy.c (0)
Location: security/apparmor/policy.c:916
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:policy_update
```
**Symbols:**

```
ffffffff821d1b9f-ffffffff821d1bbc: aa_may_manage_policy.cold (STB_LOCAL)
ffffffff81744cf0-ffffffff81744dbd: aa_may_manage_policy (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int aa_may_manage_policy(struct aa_label *label, struct aa_ns *ns, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffff8000105970a0)
Location: security/apparmor/policy.c:678
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:policy_update
```
**Symbols:**

```
ffff8000105970a0-ffff800010597188: aa_may_manage_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int aa_may_manage_policy(struct aa_label *label, struct aa_ns *ns, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (c0748180)
Location: security/apparmor/policy.c:678
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:policy_update
```
**Symbols:**

```
c0748180-c0748248: aa_may_manage_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int aa_may_manage_policy(struct aa_label *label, struct aa_ns *ns, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (c00000000070d240)
Location: security/apparmor/policy.c:678
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:policy_update
```
**Symbols:**

```
c00000000070d240-c00000000070d354: aa_may_manage_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int aa_may_manage_policy(struct aa_label *label, struct aa_ns *ns, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffe0003e3d42)
Location: security/apparmor/policy.c:678
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:policy_update
```
**Symbols:**

```
ffffffe0003e3d42-ffffffe0003e3dee: aa_may_manage_policy (STB_GLOBAL)
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
int aa_may_manage_policy(struct aa_label *label, struct aa_ns *ns, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff81499940)
Location: security/apparmor/policy.c:678
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:policy_update
```
**Symbols:**

```
ffffffff81499940-ffffffff814999c1: aa_may_manage_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int aa_may_manage_policy(struct aa_label *label, struct aa_ns *ns, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff8148a360)
Location: security/apparmor/policy.c:678
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:policy_update
```
**Symbols:**

```
ffffffff8148a360-ffffffff8148a3e1: aa_may_manage_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int aa_may_manage_policy(struct aa_label *label, struct aa_ns *ns, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff814959e0)
Location: security/apparmor/policy.c:678
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:policy_update
```
**Symbols:**

```
ffffffff814959e0-ffffffff81495a61: aa_may_manage_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int aa_may_manage_policy(struct aa_label *label, struct aa_ns *ns, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff814ada70)
Location: security/apparmor/policy.c:678
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:policy_update
```
**Symbols:**

```
ffffffff814ada70-ffffffff814adaf1: aa_may_manage_policy (STB_GLOBAL)
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
<li>
<b>Param reordered. </b>
<code>label, mask</code> ➡️ <code>label, ns, mask</code>
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
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
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
<code>label, ns, mask</code> ➡️ <code>subj_cred, label, ns, mask</code>
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
