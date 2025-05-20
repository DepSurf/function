# Function: <code>aa_label_is_subset</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
bool aa_label_is_subset(struct aa_label *set, struct aa_label *sub);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff8138a630)
Location: security/apparmor/label.c:525
Inline: False
Direct callers:
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/file.c:aa_file_perm
  - security/apparmor/file.c:aa_file_perm
  - security/apparmor/file.c:aa_file_perm
```
**Symbols:**

```
ffffffff8138a630-ffffffff8138a6e8: aa_label_is_subset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool aa_label_is_subset(struct aa_label *set, struct aa_label *sub);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff813c5320)
Location: security/apparmor/label.c:525
Inline: False
Direct callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/file.c:aa_file_perm
  - security/apparmor/file.c:aa_file_perm
  - security/apparmor/file.c:aa_file_perm
```
**Symbols:**

```
ffffffff813c5320-ffffffff813c53da: aa_label_is_subset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool aa_label_is_subset(struct aa_label *set, struct aa_label *sub);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff813dc970)
Location: security/apparmor/label.c:541
Inline: False
Direct callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:profile_onexec
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/file.c:aa_file_perm
  - security/apparmor/file.c:aa_file_perm
  - security/apparmor/file.c:aa_file_perm
```
**Symbols:**

```
ffffffff813dc970-ffffffff813dca2a: aa_label_is_subset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool aa_label_is_subset(struct aa_label *set, struct aa_label *sub);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff813ed320)
Location: security/apparmor/label.c:545
Inline: False
Direct callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:profile_onexec
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/file.c:aa_file_perm
  - security/apparmor/file.c:aa_file_perm
  - security/apparmor/file.c:aa_file_perm
```
**Symbols:**

```
ffffffff813ed320-ffffffff813ed379: aa_label_is_subset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool aa_label_is_subset(struct aa_label *set, struct aa_label *sub);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff81414d30)
Location: security/apparmor/label.c:545
Inline: False
Direct callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:profile_onexec
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/file.c:aa_file_perm
  - security/apparmor/file.c:aa_file_perm
  - security/apparmor/file.c:aa_file_perm
```
**Symbols:**

```
ffffffff81414d30-ffffffff81414d89: aa_label_is_subset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool aa_label_is_subset(struct aa_label *set, struct aa_label *sub);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff81447130)
Location: security/apparmor/label.c:544
Inline: False
Direct callers:
  - security/apparmor/audit.c:aa_audit_rule_match
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/file.c:aa_file_perm
  - security/apparmor/file.c:aa_file_perm
  - security/apparmor/file.c:aa_file_perm
```
**Symbols:**

```
ffffffff81447130-ffffffff81447189: aa_label_is_subset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool aa_label_is_subset(struct aa_label *set, struct aa_label *sub);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff81464060)
Location: security/apparmor/label.c:545
Inline: False
Direct callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/file.c:aa_file_perm
  - security/apparmor/file.c:aa_file_perm
  - security/apparmor/file.c:aa_file_perm
```
**Symbols:**

```
ffffffff81464060-ffffffff814640b9: aa_label_is_subset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool aa_label_is_subset(struct aa_label *set, struct aa_label *sub);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff814912f0)
Location: security/apparmor/label.c:541
Inline: False
Direct callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/file.c:aa_file_perm
  - security/apparmor/file.c:aa_file_perm
  - security/apparmor/file.c:aa_file_perm
```
**Symbols:**

```
ffffffff814912f0-ffffffff81491349: aa_label_is_subset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool aa_label_is_subset(struct aa_label *set, struct aa_label *sub);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff814ab1a0)
Location: security/apparmor/label.c:535
Inline: False
Direct callers:
  - security/apparmor/file.c:aa_file_perm
  - security/apparmor/file.c:aa_file_perm
  - security/apparmor/file.c:aa_file_perm
```
**Symbols:**

```
ffffffff814ab1a0-ffffffff814ab1f9: aa_label_is_subset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool aa_label_is_subset(struct aa_label *set, struct aa_label *sub);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff81509c00)
Location: security/apparmor/label.c:535
Inline: False
Direct callers:
  - security/apparmor/audit.c:aa_audit_rule_match
  - security/apparmor/file.c:aa_file_perm
  - security/apparmor/file.c:aa_file_perm
  - security/apparmor/file.c:__file_path_perm
```
**Symbols:**

```
ffffffff81509c00-ffffffff81509c59: aa_label_is_subset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool aa_label_is_subset(struct aa_label *set, struct aa_label *sub);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff81526a70)
Location: security/apparmor/label.c:535
Inline: False
Direct callers:
  - security/apparmor/audit.c:aa_audit_rule_match
  - security/apparmor/file.c:aa_file_perm
  - security/apparmor/file.c:aa_file_perm
  - security/apparmor/file.c:__file_path_perm
```
**Symbols:**

```
ffffffff81526a70-ffffffff81526ac9: aa_label_is_subset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool aa_label_is_subset(struct aa_label *set, struct aa_label *sub);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff8152c400)
Location: security/apparmor/label.c:535
Inline: False
Direct callers:
  - security/apparmor/audit.c:aa_audit_rule_match
  - security/apparmor/file.c:aa_file_perm
  - security/apparmor/file.c:aa_file_perm
  - security/apparmor/file.c:__file_path_perm
```
**Symbols:**

```
ffffffff8152c400-ffffffff8152c459: aa_label_is_subset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool aa_label_is_subset(struct aa_label *set, struct aa_label *sub);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff8158a7f0)
Location: security/apparmor/label.c:535
Inline: False
Direct callers:
  - security/apparmor/audit.c:aa_audit_rule_match
  - security/apparmor/file.c:aa_file_perm
  - security/apparmor/file.c:aa_file_perm
  - security/apparmor/file.c:__file_path_perm
```
**Symbols:**

```
ffffffff8158a7f0-ffffffff8158a849: aa_label_is_subset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool aa_label_is_subset(struct aa_label *set, struct aa_label *sub);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff8162bca0)
Location: security/apparmor/label.c:537
Inline: False
Direct callers:
  - security/apparmor/audit.c:aa_audit_rule_match
  - security/apparmor/file.c:aa_file_perm
  - security/apparmor/file.c:aa_file_perm
  - security/apparmor/file.c:__file_mqueue_perm
  - security/apparmor/file.c:__file_path_perm
```
**Symbols:**

```
ffffffff8162bca0-ffffffff8162bd03: aa_label_is_subset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool aa_label_is_subset(struct aa_label *set, struct aa_label *sub);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff816e06c0)
Location: security/apparmor/label.c:537
Inline: False
Direct callers:
  - security/apparmor/audit.c:aa_audit_rule_match
  - security/apparmor/file.c:aa_file_perm
  - security/apparmor/file.c:aa_file_perm
  - security/apparmor/file.c:__file_mqueue_perm
  - security/apparmor/file.c:__file_path_perm
```
**Symbols:**

```
ffffffff816e06c0-ffffffff816e0723: aa_label_is_subset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool aa_label_is_subset(struct aa_label *set, struct aa_label *sub);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff81719ce0)
Location: security/apparmor/label.c:537
Inline: False
Direct callers:
  - security/apparmor/audit.c:aa_audit_rule_match
  - security/apparmor/file.c:aa_file_perm
  - security/apparmor/file.c:aa_file_perm
  - security/apparmor/file.c:__file_mqueue_perm
  - security/apparmor/file.c:__file_path_perm
```
**Symbols:**

```
ffffffff81719ce0-ffffffff81719d43: aa_label_is_subset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool aa_label_is_subset(struct aa_label *set, struct aa_label *sub);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff81758780)
Location: security/apparmor/label.c:543
Inline: False
Direct callers:
  - security/apparmor/file.c:aa_file_perm
  - security/apparmor/file.c:aa_file_perm
  - security/apparmor/file.c:__file_mqueue_perm
  - security/apparmor/file.c:__file_path_perm
```
**Symbols:**

```
ffffffff81758780-ffffffff817587e3: aa_label_is_subset (STB_GLOBAL)
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
bool aa_label_is_subset(struct aa_label *set, struct aa_label *sub);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffff8000105a21f0)
Location: security/apparmor/label.c:535
Inline: False
Direct callers:
  - security/apparmor/file.c:aa_file_perm
  - security/apparmor/file.c:aa_file_perm
  - security/apparmor/file.c:aa_file_perm
```
**Symbols:**

```
ffff8000105a21f0-ffff8000105a2270: aa_label_is_subset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool aa_label_is_subset(struct aa_label *set, struct aa_label *sub);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (c0752810)
Location: security/apparmor/label.c:535
Inline: False
Direct callers:
  - security/apparmor/file.c:aa_file_perm
  - security/apparmor/file.c:aa_file_perm
  - security/apparmor/file.c:aa_file_perm
```
**Symbols:**

```
c0752810-c0752890: aa_label_is_subset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool aa_label_is_subset(struct aa_label *set, struct aa_label *sub);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (c00000000071d220)
Location: security/apparmor/label.c:535
Inline: False
Direct callers:
  - security/apparmor/file.c:aa_file_perm
  - security/apparmor/file.c:aa_file_perm
  - security/apparmor/file.c:aa_file_perm
```
**Symbols:**

```
c00000000071d220-c00000000071d2ac: aa_label_is_subset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool aa_label_is_subset(struct aa_label *set, struct aa_label *sub);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffe0003ecbbe)
Location: security/apparmor/label.c:535
Inline: False
Direct callers:
  - security/apparmor/file.c:aa_file_perm
  - security/apparmor/file.c:aa_file_perm
  - security/apparmor/file.c:aa_file_perm
```
**Symbols:**

```
ffffffe0003ecbbe-ffffffe0003ecc02: aa_label_is_subset (STB_GLOBAL)
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
bool aa_label_is_subset(struct aa_label *set, struct aa_label *sub);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff814a3780)
Location: security/apparmor/label.c:535
Inline: False
Direct callers:
  - security/apparmor/file.c:aa_file_perm
  - security/apparmor/file.c:aa_file_perm
  - security/apparmor/file.c:aa_file_perm
```
**Symbols:**

```
ffffffff814a3780-ffffffff814a37d9: aa_label_is_subset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool aa_label_is_subset(struct aa_label *set, struct aa_label *sub);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff814941a0)
Location: security/apparmor/label.c:535
Inline: False
Direct callers:
  - security/apparmor/file.c:aa_file_perm
  - security/apparmor/file.c:aa_file_perm
  - security/apparmor/file.c:aa_file_perm
```
**Symbols:**

```
ffffffff814941a0-ffffffff814941f9: aa_label_is_subset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool aa_label_is_subset(struct aa_label *set, struct aa_label *sub);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff8149f820)
Location: security/apparmor/label.c:535
Inline: False
Direct callers:
  - security/apparmor/file.c:aa_file_perm
  - security/apparmor/file.c:aa_file_perm
  - security/apparmor/file.c:aa_file_perm
```
**Symbols:**

```
ffffffff8149f820-ffffffff8149f879: aa_label_is_subset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool aa_label_is_subset(struct aa_label *set, struct aa_label *sub);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff814b7e50)
Location: security/apparmor/label.c:535
Inline: False
Direct callers:
  - security/apparmor/file.c:aa_file_perm
  - security/apparmor/file.c:aa_file_perm
  - security/apparmor/file.c:aa_file_perm
```
**Symbols:**

```
ffffffff814b7e50-ffffffff814b7ea9: aa_label_is_subset (STB_GLOBAL)
```
</details>
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
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
