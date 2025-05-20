# Function: <code>aa_put_proxy</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff81375154)
Location: security/apparmor/include/label.h:494
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_fs_seq_profile_release
  - security/apparmor/apparmorfs.c:create_profile_file
  - security/apparmor/apparmorfs.c:__aa_fs_profile_rmdir
```
```
In security/apparmor/label.c (ffffffff8138972b)
Location: security/apparmor/include/label.h:494
Inline: True
Inline callers:
  - security/apparmor/label.c:label_destroy
  - security/apparmor/label.c:__proxy_share
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff813ac15b)
Location: security/apparmor/include/label.h:494
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:create_profile_file
  - security/apparmor/apparmorfs.c:__aa_fs_profile_rmdir
  - security/apparmor/apparmorfs.c:rawdata_release
  - security/apparmor/apparmorfs.c:aa_fs_seq_profile_release
```
```
In security/apparmor/label.c (ffffffff813c4312)
Location: security/apparmor/include/label.h:494
Inline: True
Inline callers:
  - security/apparmor/label.c:label_destroy
  - security/apparmor/label.c:__proxy_share
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff813c2f6b)
Location: security/apparmor/include/label.h:494
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:create_profile_file
  - security/apparmor/apparmorfs.c:__aa_fs_profile_rmdir
  - security/apparmor/apparmorfs.c:aa_fs_seq_profile_release
```
```
In security/apparmor/label.c (ffffffff813db908)
Location: security/apparmor/include/label.h:494
Inline: True
Inline callers:
  - security/apparmor/label.c:label_destroy
  - security/apparmor/label.c:__proxy_share
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff813d8ca5)
Location: security/apparmor/include/label.h:434
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:create_profile_file
  - security/apparmor/apparmorfs.c:seq_profile_release
```
```
In security/apparmor/label.c (ffffffff813ece11)
Location: security/apparmor/include/label.h:434
Inline: True
Inline callers:
  - security/apparmor/label.c:label_destroy
  - security/apparmor/label.c:__proxy_share
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff81401447)
Location: security/apparmor/include/label.h:434
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:create_profile_file
  - security/apparmor/apparmorfs.c:seq_profile_release
```
```
In security/apparmor/policy.c (ffffffff8140c1b0)
Location: security/apparmor/include/label.h:434
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
```
```
In security/apparmor/label.c (ffffffff814147d2)
Location: security/apparmor/include/label.h:434
Inline: True
Inline callers:
  - security/apparmor/label.c:label_destroy
  - security/apparmor/label.c:__proxy_share
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff81430531)
Location: security/apparmor/include/label.h:462
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:create_profile_file
  - security/apparmor/apparmorfs.c:seq_profile_release
```
```
In security/apparmor/policy.c (ffffffff8143dc74)
Location: security/apparmor/include/label.h:462
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
```
```
In security/apparmor/label.c (ffffffff81446b75)
Location: security/apparmor/include/label.h:462
Inline: True
Inline callers:
  - security/apparmor/label.c:label_destroy
  - security/apparmor/label.c:__proxy_share
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff8144d361)
Location: security/apparmor/include/label.h:462
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:create_profile_file
  - security/apparmor/apparmorfs.c:seq_profile_release
```
```
In security/apparmor/policy.c (ffffffff8145aac2)
Location: security/apparmor/include/label.h:462
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
```
```
In security/apparmor/label.c (ffffffff81463865)
Location: security/apparmor/include/label.h:462
Inline: True
Inline callers:
  - security/apparmor/label.c:label_destroy
  - security/apparmor/label.c:__proxy_share
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff8147b0f2)
Location: security/apparmor/include/label.h:458
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:create_profile_file
  - security/apparmor/apparmorfs.c:seq_profile_release
```
```
In security/apparmor/policy.c (ffffffff814880db)
Location: security/apparmor/include/label.h:458
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
```
```
In security/apparmor/label.c (ffffffff81490b15)
Location: security/apparmor/include/label.h:458
Inline: True
Inline callers:
  - security/apparmor/label.c:label_destroy
  - security/apparmor/label.c:__proxy_share
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff81494dc2)
Location: security/apparmor/include/label.h:459
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:create_profile_file
  - security/apparmor/apparmorfs.c:seq_profile_release
```
```
In security/apparmor/policy.c (ffffffff814a1f8b)
Location: security/apparmor/include/label.h:459
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
```
```
In security/apparmor/label.c (ffffffff814aa9cf)
Location: security/apparmor/include/label.h:459
Inline: True
Inline callers:
  - security/apparmor/label.c:label_destroy
  - security/apparmor/label.c:__proxy_share
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff814ecc16)
Location: security/apparmor/include/label.h:460
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:create_profile_file
  - security/apparmor/apparmorfs.c:seq_profile_hash_open
  - security/apparmor/apparmorfs.c:seq_profile_attach_open
  - security/apparmor/apparmorfs.c:seq_profile_mode_open
  - security/apparmor/apparmorfs.c:seq_profile_name_open
  - security/apparmor/apparmorfs.c:seq_profile_release
```
```
In security/apparmor/policy.c (ffffffff814fc144)
Location: security/apparmor/include/label.h:460
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
```
```
In security/apparmor/label.c (ffffffff8150949f)
Location: security/apparmor/include/label.h:460
Inline: True
Inline callers:
  - security/apparmor/label.c:__label_insert
  - security/apparmor/label.c:aa_label_destroy
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff8150a176)
Location: security/apparmor/include/label.h:460
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:create_profile_file
  - security/apparmor/apparmorfs.c:seq_profile_hash_open
  - security/apparmor/apparmorfs.c:seq_profile_attach_open
  - security/apparmor/apparmorfs.c:seq_profile_mode_open
  - security/apparmor/apparmorfs.c:seq_profile_name_open
  - security/apparmor/apparmorfs.c:seq_profile_release
```
```
In security/apparmor/policy.c (ffffffff81519265)
Location: security/apparmor/include/label.h:460
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
```
```
In security/apparmor/label.c (ffffffff81525eeb)
Location: security/apparmor/include/label.h:460
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_destroy
  - security/apparmor/label.c:__proxy_share
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff81510d66)
Location: security/apparmor/include/label.h:460
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:create_profile_file
  - security/apparmor/apparmorfs.c:seq_profile_hash_open
  - security/apparmor/apparmorfs.c:seq_profile_attach_open
  - security/apparmor/apparmorfs.c:seq_profile_mode_open
  - security/apparmor/apparmorfs.c:seq_profile_name_open
  - security/apparmor/apparmorfs.c:seq_profile_release
```
```
In security/apparmor/policy.c (ffffffff8151fb17)
Location: security/apparmor/include/label.h:460
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
```
```
In security/apparmor/label.c (ffffffff8152b87b)
Location: security/apparmor/include/label.h:460
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_destroy
  - security/apparmor/label.c:__proxy_share
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff8156ea56)
Location: security/apparmor/include/label.h:460
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:create_profile_file
  - security/apparmor/apparmorfs.c:seq_profile_hash_open
  - security/apparmor/apparmorfs.c:seq_profile_attach_open
  - security/apparmor/apparmorfs.c:seq_profile_mode_open
  - security/apparmor/apparmorfs.c:seq_profile_name_open
  - security/apparmor/apparmorfs.c:seq_profile_release
```
```
In security/apparmor/policy.c (ffffffff8157dcb7)
Location: security/apparmor/include/label.h:460
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
```
```
In security/apparmor/label.c (ffffffff81589c5b)
Location: security/apparmor/include/label.h:460
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_destroy
  - security/apparmor/label.c:__proxy_share
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff8160b3b5)
Location: security/apparmor/include/label.h:463
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:create_profile_file
  - security/apparmor/apparmorfs.c:create_profile_file
  - security/apparmor/apparmorfs.c:seq_profile_hash_open
  - security/apparmor/apparmorfs.c:seq_profile_hash_open
  - security/apparmor/apparmorfs.c:seq_profile_attach_open
  - security/apparmor/apparmorfs.c:seq_profile_attach_open
  - security/apparmor/apparmorfs.c:seq_profile_mode_open
  - security/apparmor/apparmorfs.c:seq_profile_mode_open
  - security/apparmor/apparmorfs.c:seq_profile_name_open
  - security/apparmor/apparmorfs.c:seq_profile_name_open
  - security/apparmor/apparmorfs.c:seq_profile_release
  - security/apparmor/apparmorfs.c:seq_profile_release
```
```
In security/apparmor/policy.c (ffffffff8161c422)
Location: security/apparmor/include/label.h:463
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
```
```
In security/apparmor/label.c (ffffffff8162add7)
Location: security/apparmor/include/label.h:463
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_destroy
  - security/apparmor/label.c:aa_label_destroy
  - security/apparmor/label.c:__proxy_share
  - security/apparmor/label.c:__proxy_share
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff816bd535)
Location: security/apparmor/include/label.h:464
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:create_profile_file
  - security/apparmor/apparmorfs.c:create_profile_file
  - security/apparmor/apparmorfs.c:seq_profile_release
  - security/apparmor/apparmorfs.c:seq_profile_release
```
```
In security/apparmor/policy.c (ffffffff816cf72d)
Location: security/apparmor/include/label.h:464
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
```
```
In security/apparmor/label.c (ffffffff816df617)
Location: security/apparmor/include/label.h:464
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_destroy
  - security/apparmor/label.c:aa_label_destroy
  - security/apparmor/label.c:__proxy_share
  - security/apparmor/label.c:__proxy_share
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff816f5ff5)
Location: security/apparmor/include/label.h:464
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:create_profile_file
  - security/apparmor/apparmorfs.c:create_profile_file
  - security/apparmor/apparmorfs.c:seq_profile_release
  - security/apparmor/apparmorfs.c:seq_profile_release
```
```
In security/apparmor/policy.c (ffffffff81708379)
Location: security/apparmor/include/label.h:464
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
```
```
In security/apparmor/label.c (ffffffff81718c67)
Location: security/apparmor/include/label.h:464
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_destroy
  - security/apparmor/label.c:aa_label_destroy
  - security/apparmor/label.c:__proxy_share
  - security/apparmor/label.c:__proxy_share
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff81732d55)
Location: security/apparmor/include/label.h:459
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:create_profile_file
  - security/apparmor/apparmorfs.c:create_profile_file
  - security/apparmor/apparmorfs.c:seq_profile_release
  - security/apparmor/apparmorfs.c:seq_profile_release
```
```
In security/apparmor/policy.c (ffffffff81745e09)
Location: security/apparmor/include/label.h:459
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
```
```
In security/apparmor/label.c (ffffffff817576f7)
Location: security/apparmor/include/label.h:459
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_destroy
  - security/apparmor/label.c:aa_label_destroy
  - security/apparmor/label.c:__proxy_share
  - security/apparmor/label.c:__proxy_share
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffff80001058a304)
Location: security/apparmor/include/label.h:459
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:create_profile_file
  - security/apparmor/apparmorfs.c:create_profile_file
  - security/apparmor/apparmorfs.c:seq_profile_release
  - security/apparmor/apparmorfs.c:seq_profile_release
```
```
In security/apparmor/policy.c (ffff800010597b30)
Location: security/apparmor/include/label.h:459
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
```
```
In security/apparmor/label.c (ffff8000105a1b8c)
Location: security/apparmor/include/label.h:459
Inline: True
Inline callers:
  - security/apparmor/label.c:label_destroy
  - security/apparmor/label.c:label_destroy
  - security/apparmor/label.c:__proxy_share
  - security/apparmor/label.c:__proxy_share
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (c073b49c)
Location: security/apparmor/include/label.h:459
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:create_profile_file
  - security/apparmor/apparmorfs.c:create_profile_file
  - security/apparmor/apparmorfs.c:seq_profile_release
  - security/apparmor/apparmorfs.c:seq_profile_release
  - security/apparmor/apparmorfs.c:seq_profile_open
  - security/apparmor/apparmorfs.c:seq_profile_open
```
```
In security/apparmor/policy.c (c0748cf4)
Location: security/apparmor/include/label.h:459
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
```
```
In security/apparmor/label.c (c07522d4)
Location: security/apparmor/include/label.h:459
Inline: True
Inline callers:
  - security/apparmor/label.c:label_destroy
  - security/apparmor/label.c:label_destroy
  - security/apparmor/label.c:__proxy_share
  - security/apparmor/label.c:__proxy_share
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (c0000000006fb904)
Location: security/apparmor/include/label.h:459
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:create_profile_file
  - security/apparmor/apparmorfs.c:seq_profile_release
  - security/apparmor/apparmorfs.c:seq_profile_open
```
```
In security/apparmor/policy.c (c00000000070e10c)
Location: security/apparmor/include/label.h:459
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
```
```
In security/apparmor/label.c (c00000000071c800)
Location: security/apparmor/include/label.h:459
Inline: True
Inline callers:
  - security/apparmor/label.c:label_destroy
  - security/apparmor/label.c:__proxy_share
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffe0003d9726)
Location: security/apparmor/include/label.h:459
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:create_profile_file
  - security/apparmor/apparmorfs.c:seq_profile_release
  - security/apparmor/apparmorfs.c:seq_profile_open
```
```
In security/apparmor/policy.c (ffffffe0003e45ae)
Location: security/apparmor/include/label.h:459
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
```
```
In security/apparmor/label.c (ffffffe0003ec3d8)
Location: security/apparmor/include/label.h:459
Inline: True
Inline callers:
  - security/apparmor/label.c:label_destroy
  - security/apparmor/label.c:__proxy_share
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff8148d3a2)
Location: security/apparmor/include/label.h:459
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:create_profile_file
  - security/apparmor/apparmorfs.c:seq_profile_release
```
```
In security/apparmor/policy.c (ffffffff8149a56b)
Location: security/apparmor/include/label.h:459
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
```
```
In security/apparmor/label.c (ffffffff814a2faf)
Location: security/apparmor/include/label.h:459
Inline: True
Inline callers:
  - security/apparmor/label.c:label_destroy
  - security/apparmor/label.c:__proxy_share
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff8147ddc2)
Location: security/apparmor/include/label.h:459
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:create_profile_file
  - security/apparmor/apparmorfs.c:seq_profile_release
```
```
In security/apparmor/policy.c (ffffffff8148af8b)
Location: security/apparmor/include/label.h:459
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
```
```
In security/apparmor/label.c (ffffffff814939cf)
Location: security/apparmor/include/label.h:459
Inline: True
Inline callers:
  - security/apparmor/label.c:label_destroy
  - security/apparmor/label.c:__proxy_share
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff81489442)
Location: security/apparmor/include/label.h:459
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:create_profile_file
  - security/apparmor/apparmorfs.c:seq_profile_release
```
```
In security/apparmor/policy.c (ffffffff8149660b)
Location: security/apparmor/include/label.h:459
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
```
```
In security/apparmor/label.c (ffffffff8149f04f)
Location: security/apparmor/include/label.h:459
Inline: True
Inline callers:
  - security/apparmor/label.c:label_destroy
  - security/apparmor/label.c:__proxy_share
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff814a1272)
Location: security/apparmor/include/label.h:459
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:create_profile_file
  - security/apparmor/apparmorfs.c:seq_profile_release
```
```
In security/apparmor/policy.c (ffffffff814ae688)
Location: security/apparmor/include/label.h:459
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
```
```
In security/apparmor/label.c (ffffffff814b767f)
Location: security/apparmor/include/label.h:459
Inline: True
Inline callers:
  - security/apparmor/label.c:label_destroy
  - security/apparmor/label.c:__proxy_share
```
</details>
</li>
</ul>

## Differences
