# Function: <code>aa_put_loaddata</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff813ad74a)
Location: security/apparmor/include/policy_unpack.h:59
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:policy_update
```
```
In security/apparmor/policy.c (ffffffff813b92b3)
Location: security/apparmor/include/policy_unpack.h:59
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_free_profile
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
In security/apparmor/apparmorfs.c (ffffffff813c2431)
Location: security/apparmor/include/policy_unpack.h:59
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:rawdata_release
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:policy_update
```
```
In security/apparmor/policy.c (ffffffff813d0673)
Location: security/apparmor/include/policy_unpack.h:59
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_free_profile
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
In security/apparmor/apparmorfs.c (ffffffff813d934c)
Location: security/apparmor/include/policy_unpack.h:119
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:rawdata_release
  - security/apparmor/apparmorfs.c:seq_rawdata_release
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:policy_update
```
```
In security/apparmor/policy.c (ffffffff813e4944)
Location: security/apparmor/include/policy_unpack.h:119
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
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
In security/apparmor/apparmorfs.c (ffffffff813ff55c)
Location: security/apparmor/include/policy_unpack.h:119
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:rawdata_release
  - security/apparmor/apparmorfs.c:seq_rawdata_release
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:policy_update
```
```
In security/apparmor/policy.c (ffffffff8140bf55)
Location: security/apparmor/include/policy_unpack.h:119
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
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
In security/apparmor/apparmorfs.c (ffffffff814304ec)
Location: security/apparmor/include/policy_unpack.h:119
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:rawdata_release
  - security/apparmor/apparmorfs.c:seq_rawdata_release
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:policy_update
```
```
In security/apparmor/policy.c (ffffffff8143d4a6)
Location: security/apparmor/include/policy_unpack.h:119
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
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
In security/apparmor/apparmorfs.c (ffffffff8144d03c)
Location: security/apparmor/include/policy_unpack.h:119
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:rawdata_release
  - security/apparmor/apparmorfs.c:seq_rawdata_release
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:policy_update
```
```
In security/apparmor/policy.c (ffffffff8145a472)
Location: security/apparmor/include/policy_unpack.h:119
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
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
In security/apparmor/apparmorfs.c (ffffffff8147addc)
Location: security/apparmor/include/policy_unpack.h:115
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:rawdata_release
  - security/apparmor/apparmorfs.c:seq_rawdata_release
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:policy_update
```
```
In security/apparmor/policy.c (ffffffff814876e7)
Location: security/apparmor/include/policy_unpack.h:115
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
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
In security/apparmor/apparmorfs.c (ffffffff81494aac)
Location: security/apparmor/include/policy_unpack.h:115
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:rawdata_release
  - security/apparmor/apparmorfs.c:seq_rawdata_release
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:policy_update
```
```
In security/apparmor/policy.c (ffffffff814a1597)
Location: security/apparmor/include/policy_unpack.h:115
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
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
In security/apparmor/apparmorfs.c (ffffffff814ef55d)
Location: security/apparmor/include/policy_unpack.h:121
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:rawdata_open
  - security/apparmor/apparmorfs.c:rawdata_open
  - security/apparmor/apparmorfs.c:rawdata_release
  - security/apparmor/apparmorfs.c:seq_rawdata_release
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:policy_update
```
```
In security/apparmor/policy.c (ffffffff814fb752)
Location: security/apparmor/include/policy_unpack.h:121
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_free_profile
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
In security/apparmor/apparmorfs.c (ffffffff8150c9dd)
Location: security/apparmor/include/policy_unpack.h:121
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:rawdata_open
  - security/apparmor/apparmorfs.c:rawdata_open
  - security/apparmor/apparmorfs.c:rawdata_release
  - security/apparmor/apparmorfs.c:seq_rawdata_release
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:policy_update
```
```
In security/apparmor/policy.c (ffffffff8151879f)
Location: security/apparmor/include/policy_unpack.h:121
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_free_profile
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
In security/apparmor/apparmorfs.c (ffffffff81513039)
Location: security/apparmor/include/policy_unpack.h:121
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:rawdata_open
  - security/apparmor/apparmorfs.c:rawdata_open
  - security/apparmor/apparmorfs.c:rawdata_release
  - security/apparmor/apparmorfs.c:seq_rawdata_release
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:policy_update
```
```
In security/apparmor/policy.c (ffffffff8151efef)
Location: security/apparmor/include/policy_unpack.h:121
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_free_profile
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
In security/apparmor/apparmorfs.c (ffffffff81570c39)
Location: security/apparmor/include/policy_unpack.h:121
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:rawdata_open
  - security/apparmor/apparmorfs.c:rawdata_open
  - security/apparmor/apparmorfs.c:rawdata_release
  - security/apparmor/apparmorfs.c:seq_rawdata_release
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:policy_update
```
```
In security/apparmor/policy.c (ffffffff8157d18f)
Location: security/apparmor/include/policy_unpack.h:121
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_free_profile
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
In security/apparmor/apparmorfs.c (ffffffff8160b4ff)
Location: security/apparmor/include/policy_unpack.h:125
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:rawdata_open
  - security/apparmor/apparmorfs.c:rawdata_open
  - security/apparmor/apparmorfs.c:rawdata_open
  - security/apparmor/apparmorfs.c:rawdata_open
  - security/apparmor/apparmorfs.c:rawdata_release
  - security/apparmor/apparmorfs.c:rawdata_release
  - security/apparmor/apparmorfs.c:seq_rawdata_release
  - security/apparmor/apparmorfs.c:seq_rawdata_release
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:policy_update
  - security/apparmor/apparmorfs.c:policy_update
```
```
In security/apparmor/policy.c (ffffffff8161b815)
Location: security/apparmor/include/policy_unpack.h:125
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_free_profile
  - security/apparmor/policy.c:aa_free_profile
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
In security/apparmor/apparmorfs.c (ffffffff816bdaf7)
Location: security/apparmor/include/policy_unpack.h:162
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:rawdata_open
  - security/apparmor/apparmorfs.c:rawdata_open
  - security/apparmor/apparmorfs.c:rawdata_open
  - security/apparmor/apparmorfs.c:rawdata_open
  - security/apparmor/apparmorfs.c:rawdata_release
  - security/apparmor/apparmorfs.c:rawdata_release
  - security/apparmor/apparmorfs.c:seq_rawdata_release
  - security/apparmor/apparmorfs.c:seq_rawdata_release
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:policy_update
  - security/apparmor/apparmorfs.c:policy_update
```
```
In security/apparmor/policy.c (ffffffff816ce8e8)
Location: security/apparmor/include/policy_unpack.h:162
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
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
In security/apparmor/apparmorfs.c (ffffffff816f65af)
Location: security/apparmor/include/policy_unpack.h:163
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:rawdata_open
  - security/apparmor/apparmorfs.c:rawdata_open
  - security/apparmor/apparmorfs.c:rawdata_open
  - security/apparmor/apparmorfs.c:rawdata_open
  - security/apparmor/apparmorfs.c:rawdata_release
  - security/apparmor/apparmorfs.c:rawdata_release
  - security/apparmor/apparmorfs.c:seq_rawdata_release
  - security/apparmor/apparmorfs.c:seq_rawdata_release
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:policy_update
  - security/apparmor/apparmorfs.c:policy_update
```
```
In security/apparmor/policy.c (ffffffff817074fb)
Location: security/apparmor/include/policy_unpack.h:163
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
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
In security/apparmor/apparmorfs.c (ffffffff8173330f)
Location: security/apparmor/include/policy_unpack.h:163
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:rawdata_open
  - security/apparmor/apparmorfs.c:rawdata_open
  - security/apparmor/apparmorfs.c:rawdata_open
  - security/apparmor/apparmorfs.c:rawdata_open
  - security/apparmor/apparmorfs.c:rawdata_release
  - security/apparmor/apparmorfs.c:rawdata_release
  - security/apparmor/apparmorfs.c:seq_rawdata_release
  - security/apparmor/apparmorfs.c:seq_rawdata_release
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:policy_update
  - security/apparmor/apparmorfs.c:policy_update
```
```
In security/apparmor/policy.c (ffffffff81744f8b)
Location: security/apparmor/include/policy_unpack.h:163
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
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
In security/apparmor/apparmorfs.c (ffff80001058a3bc)
Location: security/apparmor/include/policy_unpack.h:115
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:rawdata_release
  - security/apparmor/apparmorfs.c:rawdata_release
  - security/apparmor/apparmorfs.c:seq_rawdata_release
  - security/apparmor/apparmorfs.c:seq_rawdata_release
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:policy_update
  - security/apparmor/apparmorfs.c:policy_update
```
```
In security/apparmor/policy.c (ffff800010597460)
Location: security/apparmor/include/policy_unpack.h:115
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
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
In security/apparmor/apparmorfs.c (c073b530)
Location: security/apparmor/include/policy_unpack.h:115
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:rawdata_release
  - security/apparmor/apparmorfs.c:rawdata_release
  - security/apparmor/apparmorfs.c:seq_rawdata_release
  - security/apparmor/apparmorfs.c:seq_rawdata_release
  - security/apparmor/apparmorfs.c:seq_rawdata_open
  - security/apparmor/apparmorfs.c:seq_rawdata_open
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:policy_update
  - security/apparmor/apparmorfs.c:policy_update
```
```
In security/apparmor/policy.c (c07484f4)
Location: security/apparmor/include/policy_unpack.h:115
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
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
In security/apparmor/apparmorfs.c (c0000000006fb864)
Location: security/apparmor/include/policy_unpack.h:115
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:rawdata_release
  - security/apparmor/apparmorfs.c:seq_rawdata_release
  - security/apparmor/apparmorfs.c:seq_rawdata_open
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:policy_update
```
```
In security/apparmor/policy.c (c00000000070d67c)
Location: security/apparmor/include/policy_unpack.h:115
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
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
In security/apparmor/apparmorfs.c (ffffffe0003d8758)
Location: security/apparmor/include/policy_unpack.h:115
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:rawdata_release
  - security/apparmor/apparmorfs.c:seq_rawdata_release
  - security/apparmor/apparmorfs.c:seq_rawdata_open
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:policy_update
```
```
In security/apparmor/policy.c (ffffffe0003e3f36)
Location: security/apparmor/include/policy_unpack.h:115
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
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
In security/apparmor/apparmorfs.c (ffffffff8148d08c)
Location: security/apparmor/include/policy_unpack.h:115
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:rawdata_release
  - security/apparmor/apparmorfs.c:seq_rawdata_release
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:policy_update
```
```
In security/apparmor/policy.c (ffffffff81499b77)
Location: security/apparmor/include/policy_unpack.h:115
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
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
In security/apparmor/apparmorfs.c (ffffffff8147daac)
Location: security/apparmor/include/policy_unpack.h:115
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:rawdata_release
  - security/apparmor/apparmorfs.c:seq_rawdata_release
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:policy_update
```
```
In security/apparmor/policy.c (ffffffff8148a597)
Location: security/apparmor/include/policy_unpack.h:115
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
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
In security/apparmor/apparmorfs.c (ffffffff8148912c)
Location: security/apparmor/include/policy_unpack.h:115
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:rawdata_release
  - security/apparmor/apparmorfs.c:seq_rawdata_release
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:policy_update
```
```
In security/apparmor/policy.c (ffffffff81495c17)
Location: security/apparmor/include/policy_unpack.h:115
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
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
In security/apparmor/apparmorfs.c (ffffffff814a0cec)
Location: security/apparmor/include/policy_unpack.h:115
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:rawdata_release
  - security/apparmor/apparmorfs.c:seq_rawdata_release
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:policy_update
```
```
In security/apparmor/policy.c (ffffffff814adca7)
Location: security/apparmor/include/policy_unpack.h:115
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
```
</details>
</li>
</ul>

## Differences
