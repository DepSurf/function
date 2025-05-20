# Function: <code>aa_vec_find_or_create_label</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct aa_label *aa_vec_find_or_create_label(struct aa_profile **vec, int len, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff8138a970)
Location: security/apparmor/label.c:850
Inline: False
Direct callers:
  - security/apparmor/domain.c:change_hat
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/label.c:aa_label_parse
```
**Symbols:**

```
ffffffff8138a970-ffffffff8138ab42: aa_vec_find_or_create_label (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct aa_label *aa_vec_find_or_create_label(struct aa_profile **vec, int len, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff813c5660)
Location: security/apparmor/label.c:850
Inline: False
Direct callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/label.c:aa_label_parse
  - security/apparmor/mount.c:aa_pivotroot
```
**Symbols:**

```
ffffffff813c5660-ffffffff813c5821: aa_vec_find_or_create_label (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct aa_label *aa_vec_find_or_create_label(struct aa_profile **vec, int len, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff813dccb0)
Location: security/apparmor/label.c:866
Inline: False
Direct callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/label.c:aa_label_parse
  - security/apparmor/mount.c:aa_pivotroot
```
**Symbols:**

```
ffffffff813dccb0-ffffffff813dce68: aa_vec_find_or_create_label (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct aa_label *aa_vec_find_or_create_label(struct aa_profile **vec, int len, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff813ed600)
Location: security/apparmor/label.c:864
Inline: False
Direct callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/label.c:aa_label_parse
  - security/apparmor/mount.c:aa_pivotroot
```
**Symbols:**

```
ffffffff813ed600-ffffffff813ed6f3: aa_vec_find_or_create_label (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct aa_label *aa_vec_find_or_create_label(struct aa_profile **vec, int len, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff81415010)
Location: security/apparmor/label.c:864
Inline: False
Direct callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/label.c:aa_label_parse
  - security/apparmor/mount.c:aa_pivotroot
```
**Symbols:**

```
ffffffff81415010-ffffffff8141510f: aa_vec_find_or_create_label (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct aa_label *aa_vec_find_or_create_label(struct aa_profile **vec, int len, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff81447420)
Location: security/apparmor/label.c:863
Inline: False
Direct callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/mount.c:aa_pivotroot
```
**Symbols:**

```
ffffffff81447420-ffffffff81447530: aa_vec_find_or_create_label (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct aa_label *aa_vec_find_or_create_label(struct aa_profile **vec, int len, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff81464350)
Location: security/apparmor/label.c:864
Inline: False
Direct callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/mount.c:aa_pivotroot
```
**Symbols:**

```
ffffffff81464350-ffffffff81464460: aa_vec_find_or_create_label (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct aa_label *aa_vec_find_or_create_label(struct aa_profile **vec, int len, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff814915f0)
Location: security/apparmor/label.c:860
Inline: False
Direct callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/mount.c:aa_pivotroot
```
**Symbols:**

```
ffffffff814915f0-ffffffff814916fa: aa_vec_find_or_create_label (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct aa_label *aa_vec_find_or_create_label(struct aa_profile **vec, int len, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff814ab520)
Location: security/apparmor/label.c:887
Inline: False
Direct callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/mount.c:aa_pivotroot
```
**Symbols:**

```
ffffffff814ab520-ffffffff814ab62a: aa_vec_find_or_create_label (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct aa_label *aa_vec_find_or_create_label(struct aa_profile **vec, int len, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff8150a000)
Location: security/apparmor/label.c:887
Inline: False
Direct callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/mount.c:aa_pivotroot
```
**Symbols:**

```
ffffffff8150a000-ffffffff8150a231: aa_vec_find_or_create_label (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct aa_label *aa_vec_find_or_create_label(struct aa_profile **vec, int len, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff81526e70)
Location: security/apparmor/label.c:887
Inline: False
Direct callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/mount.c:aa_pivotroot
```
**Symbols:**

```
ffffffff81526e70-ffffffff815270a1: aa_vec_find_or_create_label (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct aa_label *aa_vec_find_or_create_label(struct aa_profile **vec, int len, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff8152c800)
Location: security/apparmor/label.c:887
Inline: False
Direct callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:change_hat
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/mount.c:aa_pivotroot
```
**Symbols:**

```
ffffffff8152c800-ffffffff8152ca27: aa_vec_find_or_create_label (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct aa_label *aa_vec_find_or_create_label(struct aa_profile **vec, int len, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff8158abf0)
Location: security/apparmor/label.c:887
Inline: False
Direct callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:change_hat
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/mount.c:aa_pivotroot
```
**Symbols:**

```
ffffffff8158abf0-ffffffff8158ae17: aa_vec_find_or_create_label (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct aa_label *aa_vec_find_or_create_label(struct aa_profile **vec, int len, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff8162c0d0)
Location: security/apparmor/label.c:889
Inline: False
Direct callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/mount.c:aa_pivotroot
```
**Symbols:**

```
ffffffff8162c0d0-ffffffff8162c313: aa_vec_find_or_create_label (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct aa_label *aa_vec_find_or_create_label(struct aa_profile **vec, int len, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff816e0b40)
Location: security/apparmor/label.c:889
Inline: False
Direct callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/mount.c:aa_pivotroot
```
**Symbols:**

```
ffffffff816e0b40-ffffffff816e0d83: aa_vec_find_or_create_label (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct aa_label *aa_vec_find_or_create_label(struct aa_profile **vec, int len, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff8171a140)
Location: security/apparmor/label.c:889
Inline: False
Direct callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/mount.c:aa_pivotroot
```
**Symbols:**

```
ffffffff8171a140-ffffffff8171a383: aa_vec_find_or_create_label (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct aa_label *aa_vec_find_or_create_label(struct aa_profile **vec, int len, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff81758bf0)
Location: security/apparmor/label.c:896
Inline: False
Direct callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/lsm.c:apparmor_userns_create
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/mount.c:aa_pivotroot
```
**Symbols:**

```
ffffffff81758bf0-ffffffff81758e33: aa_vec_find_or_create_label (STB_GLOBAL)
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
struct aa_label *aa_vec_find_or_create_label(struct aa_profile **vec, int len, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffff8000105a2748)
Location: security/apparmor/label.c:887
Inline: False
Direct callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/mount.c:aa_pivotroot
```
**Symbols:**

```
ffff8000105a2748-ffff8000105a28ec: aa_vec_find_or_create_label (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct aa_label *aa_vec_find_or_create_label(struct aa_profile **vec, int len, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (c0752bbc)
Location: security/apparmor/label.c:887
Inline: False
Direct callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/mount.c:aa_pivotroot
```
**Symbols:**

```
c0752bbc-c0752cbc: aa_vec_find_or_create_label (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct aa_label *aa_vec_find_or_create_label(struct aa_profile **vec, int len, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (c00000000071d770)
Location: security/apparmor/label.c:887
Inline: False
Direct callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/mount.c:aa_pivotroot
```
**Symbols:**

```
c00000000071d770-c00000000071d918: aa_vec_find_or_create_label (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct aa_label *aa_vec_find_or_create_label(struct aa_profile **vec, int len, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffe0003ecedc)
Location: security/apparmor/label.c:887
Inline: False
Direct callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/mount.c:aa_pivotroot
```
**Symbols:**

```
ffffffe0003ecedc-ffffffe0003ecfd2: aa_vec_find_or_create_label (STB_GLOBAL)
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
struct aa_label *aa_vec_find_or_create_label(struct aa_profile **vec, int len, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff814a3b00)
Location: security/apparmor/label.c:887
Inline: False
Direct callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/mount.c:aa_pivotroot
```
**Symbols:**

```
ffffffff814a3b00-ffffffff814a3c0a: aa_vec_find_or_create_label (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct aa_label *aa_vec_find_or_create_label(struct aa_profile **vec, int len, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff81494520)
Location: security/apparmor/label.c:887
Inline: False
Direct callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/mount.c:aa_pivotroot
```
**Symbols:**

```
ffffffff81494520-ffffffff8149462a: aa_vec_find_or_create_label (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct aa_label *aa_vec_find_or_create_label(struct aa_profile **vec, int len, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff8149fba0)
Location: security/apparmor/label.c:887
Inline: False
Direct callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/mount.c:aa_pivotroot
```
**Symbols:**

```
ffffffff8149fba0-ffffffff8149fcaa: aa_vec_find_or_create_label (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct aa_label *aa_vec_find_or_create_label(struct aa_profile **vec, int len, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff814b81d0)
Location: security/apparmor/label.c:887
Inline: False
Direct callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/mount.c:aa_pivotroot
```
**Symbols:**

```
ffffffff814b81d0-ffffffff814b82da: aa_vec_find_or_create_label (STB_GLOBAL)
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
