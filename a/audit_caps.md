# Function: <code>audit_caps</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/capability.c (ffffffff81376ea8)
Location: security/apparmor/capability.c:66
Inline: True
Inline callers:
  - security/apparmor/capability.c:aa_capable
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/capability.c (ffffffff813af999)
Location: security/apparmor/capability.c:66
Inline: True
Inline callers:
  - security/apparmor/capability.c:aa_capable
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/capability.c (ffffffff813c6b19)
Location: security/apparmor/capability.c:66
Inline: True
Inline callers:
  - security/apparmor/capability.c:aa_capable
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/capability.c (ffffffff813dc8f7)
Location: security/apparmor/capability.c:68
Inline: True
Inline callers:
  - security/apparmor/capability.c:aa_capable
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/capability.c (ffffffff81403362)
Location: security/apparmor/capability.c:68
Inline: True
Inline callers:
  - security/apparmor/capability.c:aa_capable
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/capability.c (ffffffff81434507)
Location: security/apparmor/capability.c:68
Inline: True
Inline callers:
  - security/apparmor/capability.c:aa_capable
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/capability.c (ffffffff8145105b)
Location: security/apparmor/capability.c:68
Inline: True
Inline callers:
  - security/apparmor/capability.c:aa_capable
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/capability.c (ffffffff8147eb18)
Location: security/apparmor/capability.c:64
Inline: True
Inline callers:
  - security/apparmor/capability.c:aa_capable
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/capability.c (ffffffff81498818)
Location: security/apparmor/capability.c:64
Inline: True
Inline callers:
  - security/apparmor/capability.c:aa_capable
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int audit_caps(struct common_audit_data *sa, struct aa_profile *profile, int cap, int error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/capability.c (ffffffff814f0ad0)
Location: security/apparmor/capability.c:64
Inline: False
Direct callers:
  - security/apparmor/capability.c:aa_capable
```
**Symbols:**

```
ffffffff814f0ad0-ffffffff814f0cde: audit_caps (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int audit_caps(struct common_audit_data *sa, struct aa_profile *profile, int cap, int error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/capability.c (ffffffff8150dd50)
Location: security/apparmor/capability.c:64
Inline: False
Direct callers:
  - security/apparmor/capability.c:aa_capable
```
**Symbols:**

```
ffffffff8150dd50-ffffffff8150df5e: audit_caps (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int audit_caps(struct common_audit_data *sa, struct aa_profile *profile, int cap, int error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/capability.c (ffffffff81514760)
Location: security/apparmor/capability.c:64
Inline: False
Direct callers:
  - security/apparmor/capability.c:aa_capable
```
**Symbols:**

```
ffffffff81514760-ffffffff8151497c: audit_caps (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int audit_caps(struct common_audit_data *sa, struct aa_profile *profile, int cap, int error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/capability.c (ffffffff81572630)
Location: security/apparmor/capability.c:64
Inline: False
Direct callers:
  - security/apparmor/capability.c:aa_capable
```
**Symbols:**

```
ffffffff81572630-ffffffff815728aa: audit_caps (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int audit_caps(struct common_audit_data *sa, struct aa_profile *profile, int cap, int error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/capability.c (ffffffff8160f600)
Location: security/apparmor/capability.c:64
Inline: False
Direct callers:
  - security/apparmor/capability.c:aa_capable
```
**Symbols:**

```
ffffffff8160f600-ffffffff8160f8d6: audit_caps (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int audit_caps(struct apparmor_audit_data *ad, struct aa_profile *profile, int cap, int error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/capability.c (ffffffff816c2000)
Location: security/apparmor/capability.c:64
Inline: False
Direct callers:
  - security/apparmor/capability.c:aa_capable
```
**Symbols:**

```
ffffffff816c2000-ffffffff816c22e5: audit_caps (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int audit_caps(struct apparmor_audit_data *ad, struct aa_profile *profile, int cap, int error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/apparmor/capability.c (0)
Location: security/apparmor/capability.c:64
Inline: False
Direct callers:
  - security/apparmor/capability.c:aa_capable
```
**Symbols:**

```
ffffffff816fac30-ffffffff816faf2f: audit_caps (STB_LOCAL)
ffffffff820f4659-ffffffff820f46f3: audit_caps.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int audit_caps(struct apparmor_audit_data *ad, struct aa_profile *profile, int cap, int error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/apparmor/capability.c (0)
Location: security/apparmor/capability.c:65
Inline: False
Direct callers:
  - security/apparmor/capability.c:profile_capable
```
**Symbols:**

```
ffffffff81737840-ffffffff81737b3f: audit_caps (STB_LOCAL)
ffffffff821d1a9e-ffffffff821d1b38: audit_caps.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/capability.c (ffff80001058e418)
Location: security/apparmor/capability.c:64
Inline: True
Inline callers:
  - security/apparmor/capability.c:aa_capable
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/capability.c (c073f338)
Location: security/apparmor/capability.c:64
Inline: True
Inline callers:
  - security/apparmor/capability.c:aa_capable
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/capability.c (c000000000700f94)
Location: security/apparmor/capability.c:64
Inline: True
Inline callers:
  - security/apparmor/capability.c:aa_capable
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/capability.c (ffffffe0003dc402)
Location: security/apparmor/capability.c:64
Inline: True
Inline callers:
  - security/apparmor/capability.c:aa_capable
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/capability.c (ffffffff81490df8)
Location: security/apparmor/capability.c:64
Inline: True
Inline callers:
  - security/apparmor/capability.c:aa_capable
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/capability.c (ffffffff81481818)
Location: security/apparmor/capability.c:64
Inline: True
Inline callers:
  - security/apparmor/capability.c:aa_capable
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/capability.c (ffffffff8148ce98)
Location: security/apparmor/capability.c:64
Inline: True
Inline callers:
  - security/apparmor/capability.c:aa_capable
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/capability.c (ffffffff814a4cd8)
Location: security/apparmor/capability.c:64
Inline: True
Inline callers:
  - security/apparmor/capability.c:aa_capable
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
