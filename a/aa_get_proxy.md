# Function: <code>aa_get_proxy</code>

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
In security/apparmor/apparmorfs.c (ffffffff81375568)
Location: security/apparmor/include/label.h:486
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:create_profile_file
```
```
In security/apparmor/policy.c (ffffffff8137faa0)
Location: security/apparmor/include/label.h:486
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_alloc_profile
```
```
In security/apparmor/label.c (ffffffff81389c1e)
Location: security/apparmor/include/label.h:486
Inline: True
Inline callers:
  - security/apparmor/label.c:__proxy_share
  - security/apparmor/label.c:aa_label_alloc
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
In security/apparmor/apparmorfs.c (ffffffff813aeb3d)
Location: security/apparmor/include/label.h:486
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:__aa_fs_profile_mkdir
  - security/apparmor/apparmorfs.c:create_profile_file
  - security/apparmor/apparmorfs.c:rawdata_open
```
```
In security/apparmor/policy.c (ffffffff813b945c)
Location: security/apparmor/include/label.h:486
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_alloc_profile
```
```
In security/apparmor/label.c (ffffffff813c4fb2)
Location: security/apparmor/include/label.h:486
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_alloc
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
In security/apparmor/apparmorfs.c (ffffffff813c5c11)
Location: security/apparmor/include/label.h:486
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:__aa_fs_profile_mkdir
  - security/apparmor/apparmorfs.c:create_profile_file
```
```
In security/apparmor/policy.c (ffffffff813d081c)
Location: security/apparmor/include/label.h:486
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_alloc_profile
```
```
In security/apparmor/label.c (ffffffff813dc602)
Location: security/apparmor/include/label.h:486
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_alloc
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
In security/apparmor/apparmorfs.c (ffffffff813d8c5e)
Location: security/apparmor/include/label.h:426
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:create_profile_file
```
```
In security/apparmor/policy.c (ffffffff813e3df0)
Location: security/apparmor/include/label.h:426
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_alloc_profile
```
```
In security/apparmor/label.c (ffffffff813ed18f)
Location: security/apparmor/include/label.h:426
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_alloc
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
In security/apparmor/apparmorfs.c (ffffffff81402764)
Location: security/apparmor/include/label.h:426
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:create_profile_file
```
```
In security/apparmor/policy.c (ffffffff8140abd4)
Location: security/apparmor/include/label.h:426
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_alloc_profile
```
```
In security/apparmor/label.c (ffffffff81414b9b)
Location: security/apparmor/include/label.h:426
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_alloc
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
In security/apparmor/apparmorfs.c (ffffffff81433786)
Location: security/apparmor/include/label.h:454
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:create_profile_file
```
```
In security/apparmor/policy.c (ffffffff8143c49b)
Location: security/apparmor/include/label.h:454
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_alloc_profile
```
```
In security/apparmor/label.c (ffffffff81446f9e)
Location: security/apparmor/include/label.h:454
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_alloc
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
In security/apparmor/apparmorfs.c (ffffffff81450486)
Location: security/apparmor/include/label.h:454
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:create_profile_file
```
```
In security/apparmor/policy.c (ffffffff81459316)
Location: security/apparmor/include/label.h:454
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_alloc_profile
```
```
In security/apparmor/label.c (ffffffff81463ecb)
Location: security/apparmor/include/label.h:454
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_alloc
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
In security/apparmor/apparmorfs.c (ffffffff8147dec2)
Location: security/apparmor/include/label.h:450
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:create_profile_file
```
```
In security/apparmor/policy.c (ffffffff81486abb)
Location: security/apparmor/include/label.h:450
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_alloc_profile
```
```
In security/apparmor/label.c (ffffffff81491184)
Location: security/apparmor/include/label.h:450
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_alloc
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
In security/apparmor/apparmorfs.c (ffffffff81497baa)
Location: security/apparmor/include/label.h:451
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:create_profile_file
```
```
In security/apparmor/policy.c (ffffffff814a096b)
Location: security/apparmor/include/label.h:451
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_alloc_profile
```
```
In security/apparmor/label.c (ffffffff814ab034)
Location: security/apparmor/include/label.h:451
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_alloc
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
In security/apparmor/apparmorfs.c (ffffffff814efc6d)
Location: security/apparmor/include/label.h:452
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:create_profile_file
  - security/apparmor/apparmorfs.c:seq_profile_hash_open
  - security/apparmor/apparmorfs.c:seq_profile_attach_open
  - security/apparmor/apparmorfs.c:seq_profile_mode_open
  - security/apparmor/apparmorfs.c:seq_profile_name_open
```
```
In security/apparmor/policy.c (ffffffff814faa22)
Location: security/apparmor/include/label.h:452
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_alloc_profile
```
```
In security/apparmor/label.c (ffffffff81509469)
Location: security/apparmor/include/label.h:452
Inline: True
Inline callers:
  - security/apparmor/label.c:__label_insert
  - security/apparmor/label.c:aa_label_alloc
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
In security/apparmor/apparmorfs.c (ffffffff8150d0ed)
Location: security/apparmor/include/label.h:452
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
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
```
```
In security/apparmor/policy.c (ffffffff815177a2)
Location: security/apparmor/include/label.h:452
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_alloc_profile
```
```
In security/apparmor/label.c (ffffffff815268a6)
Location: security/apparmor/include/label.h:452
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_alloc
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
In security/apparmor/apparmorfs.c (ffffffff81513b0d)
Location: security/apparmor/include/label.h:452
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
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
```
```
In security/apparmor/policy.c (ffffffff8151e052)
Location: security/apparmor/include/label.h:452
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_alloc_profile
```
```
In security/apparmor/label.c (ffffffff8152c236)
Location: security/apparmor/include/label.h:452
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_alloc
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
In security/apparmor/apparmorfs.c (ffffffff815718fd)
Location: security/apparmor/include/label.h:452
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
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
```
```
In security/apparmor/policy.c (ffffffff8157c166)
Location: security/apparmor/include/label.h:452
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_alloc_profile
```
```
In security/apparmor/label.c (ffffffff8158a624)
Location: security/apparmor/include/label.h:452
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_alloc
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
In security/apparmor/apparmorfs.c (ffffffff8160e6ff)
Location: security/apparmor/include/label.h:455
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
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
```
```
In security/apparmor/policy.c (ffffffff8161a889)
Location: security/apparmor/include/label.h:455
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_alloc_profile
```
```
In security/apparmor/label.c (ffffffff8162ba8b)
Location: security/apparmor/include/label.h:455
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_alloc
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
In security/apparmor/apparmorfs.c (ffffffff816c09ac)
Location: security/apparmor/include/label.h:456
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:create_profile_file
  - security/apparmor/apparmorfs.c:create_profile_file
```
```
In security/apparmor/policy.c (ffffffff816cd857)
Location: security/apparmor/include/label.h:456
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_alloc_profile
```
```
In security/apparmor/label.c (ffffffff816e036a)
Location: security/apparmor/include/label.h:456
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_alloc
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
In security/apparmor/apparmorfs.c (ffffffff816f94ac)
Location: security/apparmor/include/label.h:456
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:create_profile_file
  - security/apparmor/apparmorfs.c:create_profile_file
```
```
In security/apparmor/policy.c (ffffffff81706487)
Location: security/apparmor/include/label.h:456
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_alloc_profile
```
```
In security/apparmor/label.c (ffffffff8171999b)
Location: security/apparmor/include/label.h:456
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_alloc
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
In security/apparmor/apparmorfs.c (ffffffff8173624c)
Location: security/apparmor/include/label.h:451
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:create_profile_file
  - security/apparmor/apparmorfs.c:create_profile_file
```
```
In security/apparmor/policy.c (ffffffff81743e02)
Location: security/apparmor/include/label.h:451
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_alloc_profile
```
```
In security/apparmor/label.c (ffffffff8175843b)
Location: security/apparmor/include/label.h:451
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_alloc
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
In security/apparmor/apparmorfs.c (ffff80001058d738)
Location: security/apparmor/include/label.h:451
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:create_profile_file
```
```
In security/apparmor/policy.c (ffff8000105966e8)
Location: security/apparmor/include/label.h:451
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_alloc_profile
```
```
In security/apparmor/label.c (ffff8000105a1fd8)
Location: security/apparmor/include/label.h:451
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_alloc
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
In security/apparmor/apparmorfs.c (c073e5a4)
Location: security/apparmor/include/label.h:451
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:create_profile_file
  - security/apparmor/apparmorfs.c:seq_profile_open
```
```
In security/apparmor/policy.c (c07477e8)
Location: security/apparmor/include/label.h:451
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_alloc_profile
```
```
In security/apparmor/label.c (c0752684)
Location: security/apparmor/include/label.h:451
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_alloc
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
In security/apparmor/apparmorfs.c (c0000000006ffeb8)
Location: security/apparmor/include/label.h:451
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:create_profile_file
  - security/apparmor/apparmorfs.c:seq_profile_open
```
```
In security/apparmor/policy.c (c00000000070c3fc)
Location: security/apparmor/include/label.h:451
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_alloc_profile
```
```
In security/apparmor/label.c (c00000000071cf7c)
Location: security/apparmor/include/label.h:451
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_alloc
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
In security/apparmor/apparmorfs.c (ffffffe0003db8b6)
Location: security/apparmor/include/label.h:451
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:create_profile_file
  - security/apparmor/apparmorfs.c:seq_profile_open
```
```
In security/apparmor/policy.c (ffffffe0003e3470)
Location: security/apparmor/include/label.h:451
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_alloc_profile
```
```
In security/apparmor/label.c (ffffffe0003eca38)
Location: security/apparmor/include/label.h:451
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_alloc
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
In security/apparmor/apparmorfs.c (ffffffff8149018a)
Location: security/apparmor/include/label.h:451
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:create_profile_file
```
```
In security/apparmor/policy.c (ffffffff81498f4b)
Location: security/apparmor/include/label.h:451
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_alloc_profile
```
```
In security/apparmor/label.c (ffffffff814a3614)
Location: security/apparmor/include/label.h:451
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_alloc
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
In security/apparmor/apparmorfs.c (ffffffff81480baa)
Location: security/apparmor/include/label.h:451
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:create_profile_file
```
```
In security/apparmor/policy.c (ffffffff8148996b)
Location: security/apparmor/include/label.h:451
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_alloc_profile
```
```
In security/apparmor/label.c (ffffffff81494034)
Location: security/apparmor/include/label.h:451
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_alloc
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
In security/apparmor/apparmorfs.c (ffffffff8148c22a)
Location: security/apparmor/include/label.h:451
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:create_profile_file
```
```
In security/apparmor/policy.c (ffffffff81494feb)
Location: security/apparmor/include/label.h:451
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_alloc_profile
```
```
In security/apparmor/label.c (ffffffff8149f6b4)
Location: security/apparmor/include/label.h:451
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_alloc
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
In security/apparmor/apparmorfs.c (ffffffff814a406a)
Location: security/apparmor/include/label.h:451
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:create_profile_file
```
```
In security/apparmor/policy.c (ffffffff814ad00b)
Location: security/apparmor/include/label.h:451
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_alloc_profile
```
```
In security/apparmor/label.c (ffffffff814b7ce4)
Location: security/apparmor/include/label.h:451
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_alloc
  - security/apparmor/label.c:__proxy_share
```
</details>
</li>
</ul>

## Differences
