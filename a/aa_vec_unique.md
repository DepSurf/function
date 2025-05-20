# Function: <code>aa_vec_unique</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int aa_vec_unique(struct aa_profile **vec, int n, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff81389f60)
Location: security/apparmor/label.c:261
Inline: False
Direct callers:
  - security/apparmor/domain.c:change_hat
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_parse
  - security/apparmor/label.c:__aa_labelset_update_subtree
```
**Symbols:**

```
ffffffff81389f60-ffffffff8138a19c: aa_vec_unique (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int aa_vec_unique(struct aa_profile **vec, int n, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff813c4ba0)
Location: security/apparmor/label.c:261
Inline: False
Direct callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:aa_label_parse
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/mount.c:aa_pivotroot
```
**Symbols:**

```
ffffffff813c4ba0-ffffffff813c4e78: aa_vec_unique (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int aa_vec_unique(struct aa_profile **vec, int n, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff813dc1f0)
Location: security/apparmor/label.c:261
Inline: False
Direct callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:aa_label_parse
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/mount.c:aa_pivotroot
```
**Symbols:**

```
ffffffff813dc1f0-ffffffff813dc4c8: aa_vec_unique (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int aa_vec_unique(struct aa_profile **vec, int n, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff813ecaf0)
Location: security/apparmor/label.c:266
Inline: False
Direct callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:aa_label_parse
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/mount.c:aa_pivotroot
```
**Symbols:**

```
ffffffff813ecaf0-ffffffff813eccc1: aa_vec_unique (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int aa_vec_unique(struct aa_profile **vec, int n, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff814148f0)
Location: security/apparmor/label.c:266
Inline: False
Direct callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:aa_label_parse
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/mount.c:aa_pivotroot
```
**Symbols:**

```
ffffffff814148f0-ffffffff81414ac5: aa_vec_unique (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int aa_vec_unique(struct aa_profile **vec, int n, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff81446cb0)
Location: security/apparmor/label.c:266
Inline: False
Direct callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/mount.c:aa_pivotroot
```
**Symbols:**

```
ffffffff81446cb0-ffffffff81446ec3: aa_vec_unique (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int aa_vec_unique(struct aa_profile **vec, int n, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff81463be0)
Location: security/apparmor/label.c:266
Inline: False
Direct callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/mount.c:aa_pivotroot
```
**Symbols:**

```
ffffffff81463be0-ffffffff81463df3: aa_vec_unique (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int aa_vec_unique(struct aa_profile **vec, int n, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff81490e80)
Location: security/apparmor/label.c:262
Inline: False
Direct callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/mount.c:aa_pivotroot
```
**Symbols:**

```
ffffffff81490e80-ffffffff814910a3: aa_vec_unique (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int aa_vec_unique(struct aa_profile **vec, int n, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff814aad30)
Location: security/apparmor/label.c:262
Inline: False
Direct callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/mount.c:aa_pivotroot
```
**Symbols:**

```
ffffffff814aad30-ffffffff814aaf53: aa_vec_unique (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int aa_vec_unique(struct aa_profile **vec, int n, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff815095d0)
Location: security/apparmor/label.c:262
Inline: False
Direct callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:label_merge_insert
  - security/apparmor/mount.c:aa_pivotroot
```
**Symbols:**

```
ffffffff815095d0-ffffffff815098e3: aa_vec_unique (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int aa_vec_unique(struct aa_profile **vec, int n, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff81526440)
Location: security/apparmor/label.c:262
Inline: False
Direct callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:label_merge_insert
  - security/apparmor/mount.c:aa_pivotroot
```
**Symbols:**

```
ffffffff81526440-ffffffff81526753: aa_vec_unique (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int aa_vec_unique(struct aa_profile **vec, int n, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff8152bdd0)
Location: security/apparmor/label.c:262
Inline: False
Direct callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:change_hat
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:label_merge_insert
  - security/apparmor/mount.c:aa_pivotroot
```
**Symbols:**

```
ffffffff8152bdd0-ffffffff8152c0e2: aa_vec_unique (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int aa_vec_unique(struct aa_profile **vec, int n, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff8158a1b0)
Location: security/apparmor/label.c:262
Inline: False
Direct callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:change_hat
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:label_merge_insert
  - security/apparmor/mount.c:aa_pivotroot
```
**Symbols:**

```
ffffffff8158a1b0-ffffffff8158a4c2: aa_vec_unique (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int aa_vec_unique(struct aa_profile **vec, int n, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff8162b5b0)
Location: security/apparmor/label.c:265
Inline: False
Direct callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:label_merge_insert
  - security/apparmor/mount.c:aa_pivotroot
```
**Symbols:**

```
ffffffff8162b5b0-ffffffff8162b8fb: aa_vec_unique (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int aa_vec_unique(struct aa_profile **vec, int n, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff816dfe60)
Location: security/apparmor/label.c:265
Inline: False
Direct callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:label_merge_insert
  - security/apparmor/mount.c:aa_pivotroot
```
**Symbols:**

```
ffffffff816dfe60-ffffffff816e01ab: aa_vec_unique (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int aa_vec_unique(struct aa_profile **vec, int n, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff81719480)
Location: security/apparmor/label.c:265
Inline: False
Direct callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:label_merge_insert
  - security/apparmor/mount.c:aa_pivotroot
```
**Symbols:**

```
ffffffff81719480-ffffffff817197dd: aa_vec_unique (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int aa_vec_unique(struct aa_profile **vec, int n, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff81757f20)
Location: security/apparmor/label.c:271
Inline: False
Direct callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/lsm.c:apparmor_userns_create
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:label_merge_insert
  - security/apparmor/mount.c:aa_pivotroot
```
**Symbols:**

```
ffffffff81757f20-ffffffff8175827d: aa_vec_unique (STB_GLOBAL)
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
int aa_vec_unique(struct aa_profile **vec, int n, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffff8000105a1720)
Location: security/apparmor/label.c:262
Inline: False
Direct callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/mount.c:aa_pivotroot
```
**Symbols:**

```
ffff8000105a1720-ffff8000105a192c: aa_vec_unique (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int aa_vec_unique(struct aa_profile **vec, int n, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (c0751f10)
Location: security/apparmor/label.c:262
Inline: False
Direct callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/mount.c:aa_pivotroot
```
**Symbols:**

```
c0751f10-c07520d8: aa_vec_unique (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int aa_vec_unique(struct aa_profile **vec, int n, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (c00000000071c2b0)
Location: security/apparmor/label.c:262
Inline: False
Direct callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/mount.c:aa_pivotroot
```
**Symbols:**

```
c00000000071c2b0-c00000000071c594: aa_vec_unique (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int aa_vec_unique(struct aa_profile **vec, int n, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffe0003ec738)
Location: security/apparmor/label.c:262
Inline: False
Direct callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/mount.c:aa_pivotroot
```
**Symbols:**

```
ffffffe0003ec738-ffffffe0003ec8f8: aa_vec_unique (STB_GLOBAL)
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
int aa_vec_unique(struct aa_profile **vec, int n, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff814a3310)
Location: security/apparmor/label.c:262
Inline: False
Direct callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/mount.c:aa_pivotroot
```
**Symbols:**

```
ffffffff814a3310-ffffffff814a3533: aa_vec_unique (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int aa_vec_unique(struct aa_profile **vec, int n, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff81493d30)
Location: security/apparmor/label.c:262
Inline: False
Direct callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/mount.c:aa_pivotroot
```
**Symbols:**

```
ffffffff81493d30-ffffffff81493f53: aa_vec_unique (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int aa_vec_unique(struct aa_profile **vec, int n, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff8149f3b0)
Location: security/apparmor/label.c:262
Inline: False
Direct callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/mount.c:aa_pivotroot
```
**Symbols:**

```
ffffffff8149f3b0-ffffffff8149f5d3: aa_vec_unique (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int aa_vec_unique(struct aa_profile **vec, int n, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff814b79e0)
Location: security/apparmor/label.c:262
Inline: False
Direct callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/mount.c:aa_pivotroot
```
**Symbols:**

```
ffffffff814b79e0-ffffffff814b7c03: aa_vec_unique (STB_GLOBAL)
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
