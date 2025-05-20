# Function: <code>aa_proxy_kref</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void aa_proxy_kref(struct kref *kref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff813898e0)
Location: security/apparmor/label.c:57
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:aa_fs_seq_profile_release
  - security/apparmor/apparmorfs.c:create_profile_file
  - security/apparmor/apparmorfs.c:__aa_fs_profile_rmdir
  - security/apparmor/label.c:label_destroy
  - security/apparmor/label.c:__proxy_share
```
**Symbols:**

```
ffffffff813898e0-ffffffff81389923: aa_proxy_kref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void aa_proxy_kref(struct kref *kref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff813c44d0)
Location: security/apparmor/label.c:57
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:create_profile_file
  - security/apparmor/apparmorfs.c:__aa_fs_profile_rmdir
  - security/apparmor/apparmorfs.c:rawdata_release
  - security/apparmor/apparmorfs.c:aa_fs_seq_profile_release
  - security/apparmor/label.c:label_destroy
  - security/apparmor/label.c:__proxy_share
```
**Symbols:**

```
ffffffff813c44d0-ffffffff813c4513: aa_proxy_kref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void aa_proxy_kref(struct kref *kref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff813dbae0)
Location: security/apparmor/label.c:57
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:create_profile_file
  - security/apparmor/apparmorfs.c:__aa_fs_profile_rmdir
  - security/apparmor/apparmorfs.c:aa_fs_seq_profile_release
  - security/apparmor/label.c:label_destroy
  - security/apparmor/label.c:__proxy_share
```
**Symbols:**

```
ffffffff813dbae0-ffffffff813dbb23: aa_proxy_kref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void aa_proxy_kref(struct kref *kref);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff813ece28)
Location: security/apparmor/label.c:57
Inline: True
Inline callers:
  - security/apparmor/label.c:label_destroy
  - security/apparmor/label.c:__proxy_share
Direct callers:
  - security/apparmor/apparmorfs.c:create_profile_file
  - security/apparmor/apparmorfs.c:seq_profile_release
```
**Symbols:**

```
ffffffff813ecdc0-ffffffff813ecdd0: aa_proxy_kref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void aa_proxy_kref(struct kref *kref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff81414570)
Location: security/apparmor/label.c:57
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:create_profile_file
  - security/apparmor/apparmorfs.c:seq_profile_release
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/label.c:label_destroy
  - security/apparmor/label.c:__proxy_share
```
**Symbols:**

```
ffffffff81414570-ffffffff814145b7: aa_proxy_kref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void aa_proxy_kref(struct kref *kref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff81446910)
Location: security/apparmor/label.c:57
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:create_profile_file
  - security/apparmor/apparmorfs.c:seq_profile_release
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/label.c:label_destroy
  - security/apparmor/label.c:__proxy_share
```
**Symbols:**

```
ffffffff81446910-ffffffff81446958: aa_proxy_kref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void aa_proxy_kref(struct kref *kref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff81463780)
Location: security/apparmor/label.c:57
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:create_profile_file
  - security/apparmor/apparmorfs.c:seq_profile_release
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/label.c:label_destroy
  - security/apparmor/label.c:__proxy_share
```
**Symbols:**

```
ffffffff81463780-ffffffff814637c8: aa_proxy_kref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void aa_proxy_kref(struct kref *kref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff81490a30)
Location: security/apparmor/label.c:53
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:create_profile_file
  - security/apparmor/apparmorfs.c:seq_profile_release
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/label.c:label_destroy
  - security/apparmor/label.c:__proxy_share
```
**Symbols:**

```
ffffffff81490a30-ffffffff81490a7c: aa_proxy_kref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void aa_proxy_kref(struct kref *kref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff814aa8f0)
Location: security/apparmor/label.c:53
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:create_profile_file
  - security/apparmor/apparmorfs.c:seq_profile_release
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/label.c:label_destroy
  - security/apparmor/label.c:__proxy_share
```
**Symbols:**

```
ffffffff814aa8f0-ffffffff814aa93c: aa_proxy_kref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void aa_proxy_kref(struct kref *kref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff81509140)
Location: security/apparmor/label.c:53
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:create_profile_file
  - security/apparmor/apparmorfs.c:seq_profile_hash_open
  - security/apparmor/apparmorfs.c:seq_profile_attach_open
  - security/apparmor/apparmorfs.c:seq_profile_mode_open
  - security/apparmor/apparmorfs.c:seq_profile_name_open
  - security/apparmor/apparmorfs.c:seq_profile_release
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/label.c:__label_insert
  - security/apparmor/label.c:aa_label_destroy
```
**Symbols:**

```
ffffffff81509140-ffffffff815091c7: aa_proxy_kref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void aa_proxy_kref(struct kref *kref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff81526100)
Location: security/apparmor/label.c:53
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:create_profile_file
  - security/apparmor/apparmorfs.c:seq_profile_hash_open
  - security/apparmor/apparmorfs.c:seq_profile_attach_open
  - security/apparmor/apparmorfs.c:seq_profile_mode_open
  - security/apparmor/apparmorfs.c:seq_profile_name_open
  - security/apparmor/apparmorfs.c:seq_profile_release
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/label.c:aa_label_destroy
  - security/apparmor/label.c:__proxy_share
```
**Symbols:**

```
ffffffff81526100-ffffffff81526187: aa_proxy_kref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void aa_proxy_kref(struct kref *kref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff8152ba90)
Location: security/apparmor/label.c:53
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:create_profile_file
  - security/apparmor/apparmorfs.c:seq_profile_hash_open
  - security/apparmor/apparmorfs.c:seq_profile_attach_open
  - security/apparmor/apparmorfs.c:seq_profile_mode_open
  - security/apparmor/apparmorfs.c:seq_profile_name_open
  - security/apparmor/apparmorfs.c:seq_profile_release
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/label.c:aa_label_destroy
  - security/apparmor/label.c:__proxy_share
```
**Symbols:**

```
ffffffff8152ba90-ffffffff8152bb17: aa_proxy_kref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void aa_proxy_kref(struct kref *kref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff81589e70)
Location: security/apparmor/label.c:53
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:create_profile_file
  - security/apparmor/apparmorfs.c:seq_profile_hash_open
  - security/apparmor/apparmorfs.c:seq_profile_attach_open
  - security/apparmor/apparmorfs.c:seq_profile_mode_open
  - security/apparmor/apparmorfs.c:seq_profile_name_open
  - security/apparmor/apparmorfs.c:seq_profile_release
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/label.c:aa_label_destroy
  - security/apparmor/label.c:__proxy_share
```
**Symbols:**

```
ffffffff81589e70-ffffffff81589ef7: aa_proxy_kref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void aa_proxy_kref(struct kref *kref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff8162b030)
Location: security/apparmor/label.c:53
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:create_profile_file
  - security/apparmor/apparmorfs.c:seq_profile_hash_open
  - security/apparmor/apparmorfs.c:seq_profile_attach_open
  - security/apparmor/apparmorfs.c:seq_profile_mode_open
  - security/apparmor/apparmorfs.c:seq_profile_name_open
  - security/apparmor/apparmorfs.c:seq_profile_release
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/label.c:aa_label_destroy
  - security/apparmor/label.c:__proxy_share
```
**Symbols:**

```
ffffffff8162b030-ffffffff8162b0c8: aa_proxy_kref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void aa_proxy_kref(struct kref *kref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff816df8b0)
Location: security/apparmor/label.c:53
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:create_profile_file
  - security/apparmor/apparmorfs.c:seq_profile_release
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/label.c:aa_label_destroy
  - security/apparmor/label.c:__proxy_share
```
**Symbols:**

```
ffffffff816df8b0-ffffffff816df948: aa_proxy_kref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void aa_proxy_kref(struct kref *kref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff81718f00)
Location: security/apparmor/label.c:53
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:create_profile_file
  - security/apparmor/apparmorfs.c:seq_profile_release
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/label.c:aa_label_destroy
  - security/apparmor/label.c:__proxy_share
```
**Symbols:**

```
ffffffff81718f00-ffffffff81718f98: aa_proxy_kref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void aa_proxy_kref(struct kref *kref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff81757990)
Location: security/apparmor/label.c:53
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:create_profile_file
  - security/apparmor/apparmorfs.c:seq_profile_release
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/label.c:aa_label_destroy
  - security/apparmor/label.c:__proxy_share
```
**Symbols:**

```
ffffffff81757990-ffffffff81757a28: aa_proxy_kref (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void aa_proxy_kref(struct kref *kref);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffff8000105a1bbc)
Location: security/apparmor/label.c:53
Inline: True
Inline callers:
  - security/apparmor/label.c:label_destroy
  - security/apparmor/label.c:__proxy_share
Direct callers:
  - security/apparmor/apparmorfs.c:create_profile_file
  - security/apparmor/apparmorfs.c:seq_profile_release
  - security/apparmor/policy.c:aa_replace_profiles
```
**Symbols:**

```
ffff8000105a1ab0-ffff8000105a1adc: aa_proxy_kref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void aa_proxy_kref(struct kref *kref);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (c07522f8)
Location: security/apparmor/label.c:53
Inline: True
Inline callers:
  - security/apparmor/label.c:label_destroy
  - security/apparmor/label.c:__proxy_share
Direct callers:
  - security/apparmor/apparmorfs.c:create_profile_file
  - security/apparmor/apparmorfs.c:seq_profile_release
  - security/apparmor/apparmorfs.c:seq_profile_open
  - security/apparmor/policy.c:aa_replace_profiles
```
**Symbols:**

```
c0752210-c075222c: aa_proxy_kref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void aa_proxy_kref(struct kref *kref);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (c00000000071c850)
Location: security/apparmor/label.c:53
Inline: True
Inline callers:
  - security/apparmor/label.c:label_destroy
  - security/apparmor/label.c:__proxy_share
Direct callers:
  - security/apparmor/apparmorfs.c:create_profile_file
  - security/apparmor/apparmorfs.c:seq_profile_release
  - security/apparmor/apparmorfs.c:seq_profile_open
  - security/apparmor/policy.c:aa_replace_profiles
```
**Symbols:**

```
c00000000071c790-c00000000071c7a4: aa_proxy_kref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void aa_proxy_kref(struct kref *kref);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffe0003ec406)
Location: security/apparmor/label.c:53
Inline: True
Inline callers:
  - security/apparmor/label.c:label_destroy
  - security/apparmor/label.c:__proxy_share
Direct callers:
  - security/apparmor/apparmorfs.c:create_profile_file
  - security/apparmor/apparmorfs.c:seq_profile_release
  - security/apparmor/apparmorfs.c:seq_profile_open
  - security/apparmor/policy.c:aa_replace_profiles
```
**Symbols:**

```
ffffffe0003ec31a-ffffffe0003ec344: aa_proxy_kref (STB_GLOBAL)
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
void aa_proxy_kref(struct kref *kref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff814a2ed0)
Location: security/apparmor/label.c:53
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:create_profile_file
  - security/apparmor/apparmorfs.c:seq_profile_release
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/label.c:label_destroy
  - security/apparmor/label.c:__proxy_share
```
**Symbols:**

```
ffffffff814a2ed0-ffffffff814a2f1c: aa_proxy_kref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void aa_proxy_kref(struct kref *kref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff814938f0)
Location: security/apparmor/label.c:53
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:create_profile_file
  - security/apparmor/apparmorfs.c:seq_profile_release
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/label.c:label_destroy
  - security/apparmor/label.c:__proxy_share
```
**Symbols:**

```
ffffffff814938f0-ffffffff8149393c: aa_proxy_kref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void aa_proxy_kref(struct kref *kref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff8149ef70)
Location: security/apparmor/label.c:53
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:create_profile_file
  - security/apparmor/apparmorfs.c:seq_profile_release
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/label.c:label_destroy
  - security/apparmor/label.c:__proxy_share
```
**Symbols:**

```
ffffffff8149ef70-ffffffff8149efbc: aa_proxy_kref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void aa_proxy_kref(struct kref *kref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff814b75a0)
Location: security/apparmor/label.c:53
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:create_profile_file
  - security/apparmor/apparmorfs.c:seq_profile_release
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/label.c:label_destroy
  - security/apparmor/label.c:__proxy_share
```
**Symbols:**

```
ffffffff814b75a0-ffffffff814b75ec: aa_proxy_kref (STB_GLOBAL)
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
