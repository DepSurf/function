# Function: <code>aa_label_is_unconfined_subset</code>

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
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool aa_label_is_unconfined_subset(struct aa_label *set, struct aa_label *sub);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff814ab200)
Location: security/apparmor/label.c:562
Inline: False
Direct callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:apparmor_bprm_set_creds
```
**Symbols:**

```
ffffffff814ab200-ffffffff814ab273: aa_label_is_unconfined_subset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool aa_label_is_unconfined_subset(struct aa_label *set, struct aa_label *sub);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff81509c60)
Location: security/apparmor/label.c:562
Inline: False
Direct callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
```
**Symbols:**

```
ffffffff81509c60-ffffffff81509cd3: aa_label_is_unconfined_subset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool aa_label_is_unconfined_subset(struct aa_label *set, struct aa_label *sub);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff81526ad0)
Location: security/apparmor/label.c:562
Inline: False
Direct callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
```
**Symbols:**

```
ffffffff81526ad0-ffffffff81526b43: aa_label_is_unconfined_subset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool aa_label_is_unconfined_subset(struct aa_label *set, struct aa_label *sub);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff8152c460)
Location: security/apparmor/label.c:562
Inline: False
Direct callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
```
**Symbols:**

```
ffffffff8152c460-ffffffff8152c4d3: aa_label_is_unconfined_subset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool aa_label_is_unconfined_subset(struct aa_label *set, struct aa_label *sub);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff8158a850)
Location: security/apparmor/label.c:562
Inline: False
Direct callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
```
**Symbols:**

```
ffffffff8158a850-ffffffff8158a8c3: aa_label_is_unconfined_subset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool aa_label_is_unconfined_subset(struct aa_label *set, struct aa_label *sub);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff8162bd10)
Location: security/apparmor/label.c:564
Inline: False
Direct callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
```
**Symbols:**

```
ffffffff8162bd10-ffffffff8162bd8d: aa_label_is_unconfined_subset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool aa_label_is_unconfined_subset(struct aa_label *set, struct aa_label *sub);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff816e0740)
Location: security/apparmor/label.c:564
Inline: False
Direct callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
```
**Symbols:**

```
ffffffff816e0740-ffffffff816e07bd: aa_label_is_unconfined_subset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool aa_label_is_unconfined_subset(struct aa_label *set, struct aa_label *sub);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff81719d60)
Location: security/apparmor/label.c:564
Inline: False
Direct callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
```
**Symbols:**

```
ffffffff81719d60-ffffffff81719ddd: aa_label_is_unconfined_subset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool aa_label_is_unconfined_subset(struct aa_label *set, struct aa_label *sub);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff81758800)
Location: security/apparmor/label.c:570
Inline: False
Direct callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
```
**Symbols:**

```
ffffffff81758800-ffffffff8175887d: aa_label_is_unconfined_subset (STB_GLOBAL)
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
bool aa_label_is_unconfined_subset(struct aa_label *set, struct aa_label *sub);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffff8000105a2270)
Location: security/apparmor/label.c:562
Inline: False
Direct callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:apparmor_bprm_set_creds
```
**Symbols:**

```
ffff8000105a2270-ffff8000105a2304: aa_label_is_unconfined_subset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool aa_label_is_unconfined_subset(struct aa_label *set, struct aa_label *sub);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (c0752890)
Location: security/apparmor/label.c:562
Inline: False
Direct callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:apparmor_bprm_set_creds
```
**Symbols:**

```
c0752890-c075292c: aa_label_is_unconfined_subset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool aa_label_is_unconfined_subset(struct aa_label *set, struct aa_label *sub);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (c00000000071d2b0)
Location: security/apparmor/label.c:562
Inline: False
Direct callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:apparmor_bprm_set_creds
```
**Symbols:**

```
c00000000071d2b0-c00000000071d390: aa_label_is_unconfined_subset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool aa_label_is_unconfined_subset(struct aa_label *set, struct aa_label *sub);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffe0003ecc02)
Location: security/apparmor/label.c:562
Inline: False
Direct callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:apparmor_bprm_set_creds
```
**Symbols:**

```
ffffffe0003ecc02-ffffffe0003ecc60: aa_label_is_unconfined_subset (STB_GLOBAL)
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
bool aa_label_is_unconfined_subset(struct aa_label *set, struct aa_label *sub);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff814a37e0)
Location: security/apparmor/label.c:562
Inline: False
Direct callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:apparmor_bprm_set_creds
```
**Symbols:**

```
ffffffff814a37e0-ffffffff814a3853: aa_label_is_unconfined_subset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool aa_label_is_unconfined_subset(struct aa_label *set, struct aa_label *sub);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff81494200)
Location: security/apparmor/label.c:562
Inline: False
Direct callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:apparmor_bprm_set_creds
```
**Symbols:**

```
ffffffff81494200-ffffffff81494273: aa_label_is_unconfined_subset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool aa_label_is_unconfined_subset(struct aa_label *set, struct aa_label *sub);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff8149f880)
Location: security/apparmor/label.c:562
Inline: False
Direct callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:apparmor_bprm_set_creds
```
**Symbols:**

```
ffffffff8149f880-ffffffff8149f8f3: aa_label_is_unconfined_subset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool aa_label_is_unconfined_subset(struct aa_label *set, struct aa_label *sub);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff814b7eb0)
Location: security/apparmor/label.c:562
Inline: False
Direct callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:apparmor_bprm_set_creds
```
**Symbols:**

```
ffffffff814b7eb0-ffffffff814b7f23: aa_label_is_unconfined_subset (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
