# Function: <code>aa_strneq</code>

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
In security/apparmor/policy.c (ffffffff8137f042)
Location: security/apparmor/include/lib.h:92
Inline: True
Inline callers:
  - security/apparmor/policy.c:__lookupn_profile
  - security/apparmor/policy.c:__lookupn_profile
  - security/apparmor/policy.c:aa_replace_profiles
```
```
In security/apparmor/policy_ns.c (ffffffff813948e0)
Location: security/apparmor/include/lib.h:92
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:aa_findn_ns
  - security/apparmor/policy_ns.c:aa_prepare_ns
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
In security/apparmor/apparmorfs.c (ffffffff813ada2b)
Location: security/apparmor/include/lib.h:92
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:ns_rmdir_op
```
```
In security/apparmor/policy.c (ffffffff813ba76a)
Location: security/apparmor/include/lib.h:92
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:__lookupn_profile
  - security/apparmor/policy.c:__lookupn_profile
```
```
In security/apparmor/policy_ns.c (ffffffff813d0532)
Location: security/apparmor/include/lib.h:92
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:aa_prepare_ns
  - security/apparmor/policy_ns.c:aa_create_ns
  - security/apparmor/policy_ns.c:aa_findn_ns
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
In security/apparmor/apparmorfs.c (ffffffff813c483b)
Location: security/apparmor/include/lib.h:93
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:ns_rmdir_op
```
```
In security/apparmor/policy.c (ffffffff813d1b2a)
Location: security/apparmor/include/lib.h:93
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:__lookupn_profile
  - security/apparmor/policy.c:__lookupn_profile
```
```
In security/apparmor/policy_ns.c (ffffffff813e7c32)
Location: security/apparmor/include/lib.h:93
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:aa_prepare_ns
  - security/apparmor/policy_ns.c:aa_create_ns
  - security/apparmor/policy_ns.c:aa_findn_ns
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
In security/apparmor/apparmorfs.c (ffffffff813da2e9)
Location: security/apparmor/include/lib.h:77
Inline: True
```
```
In security/apparmor/policy.c (ffffffff813e4aa2)
Location: security/apparmor/include/lib.h:77
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:__lookupn_profile
  - security/apparmor/policy.c:__lookupn_profile
  - security/apparmor/policy.c:__find_child
```
```
In security/apparmor/policy_ns.c (ffffffff813ec57f)
Location: security/apparmor/include/lib.h:77
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:aa_prepare_ns
  - security/apparmor/policy_ns.c:__aa_find_or_create_ns
  - security/apparmor/policy_ns.c:__aa_lookupn_ns
  - security/apparmor/policy_ns.c:__aa_lookupn_ns
  - security/apparmor/policy_ns.c:aa_findn_ns
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
In security/apparmor/apparmorfs.c (ffffffff8140062e)
Location: security/apparmor/include/lib.h:66
Inline: True
```
```
In security/apparmor/policy.c (ffffffff8140bce7)
Location: security/apparmor/include/lib.h:66
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:__lookupn_profile
  - security/apparmor/policy.c:__lookupn_profile
  - security/apparmor/policy.c:__find_child
```
```
In security/apparmor/policy_ns.c (ffffffff81413f0f)
Location: security/apparmor/include/lib.h:66
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:aa_prepare_ns
  - security/apparmor/policy_ns.c:__aa_find_or_create_ns
  - security/apparmor/policy_ns.c:__aa_lookupn_ns
  - security/apparmor/policy_ns.c:__aa_lookupn_ns
  - security/apparmor/policy_ns.c:aa_findn_ns
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
In security/apparmor/apparmorfs.c (ffffffff8143235e)
Location: security/apparmor/include/lib.h:66
Inline: True
```
```
In security/apparmor/policy.c (ffffffff8143d5a7)
Location: security/apparmor/include/lib.h:66
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:__lookupn_profile
  - security/apparmor/policy.c:__lookupn_profile
  - security/apparmor/policy.c:__find_child
```
```
In security/apparmor/policy_ns.c (ffffffff81446269)
Location: security/apparmor/include/lib.h:66
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:aa_prepare_ns
  - security/apparmor/policy_ns.c:__aa_find_or_create_ns
  - security/apparmor/policy_ns.c:__aa_lookupn_ns
  - security/apparmor/policy_ns.c:__aa_lookupn_ns
  - security/apparmor/policy_ns.c:aa_findn_ns
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
In security/apparmor/apparmorfs.c (ffffffff8144e519)
Location: security/apparmor/include/lib.h:70
Inline: True
```
```
In security/apparmor/policy.c (ffffffff8145a573)
Location: security/apparmor/include/lib.h:70
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:__lookupn_profile
  - security/apparmor/policy.c:__lookupn_profile
  - security/apparmor/policy.c:__find_child
```
```
In security/apparmor/policy_ns.c (ffffffff81463189)
Location: security/apparmor/include/lib.h:70
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:aa_prepare_ns
  - security/apparmor/policy_ns.c:__aa_find_or_create_ns
  - security/apparmor/policy_ns.c:__aa_lookupn_ns
  - security/apparmor/policy_ns.c:__aa_lookupn_ns
  - security/apparmor/policy_ns.c:aa_findn_ns
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
In security/apparmor/apparmorfs.c (ffffffff8147bf57)
Location: security/apparmor/include/lib.h:66
Inline: True
```
```
In security/apparmor/policy.c (ffffffff81487987)
Location: security/apparmor/include/lib.h:66
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:__lookupn_profile
  - security/apparmor/policy.c:__lookupn_profile
  - security/apparmor/policy.c:__find_child
```
```
In security/apparmor/policy_ns.c (ffffffff8149044d)
Location: security/apparmor/include/lib.h:66
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:aa_prepare_ns
  - security/apparmor/policy_ns.c:__aa_find_or_create_ns
  - security/apparmor/policy_ns.c:__aa_lookupn_ns
  - security/apparmor/policy_ns.c:__aa_lookupn_ns
  - security/apparmor/policy_ns.c:aa_findn_ns
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
In security/apparmor/apparmorfs.c (ffffffff81495c27)
Location: security/apparmor/include/lib.h:66
Inline: True
```
```
In security/apparmor/policy.c (ffffffff814a1837)
Location: security/apparmor/include/lib.h:66
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:__lookupn_profile
  - security/apparmor/policy.c:__lookupn_profile
  - security/apparmor/policy.c:__find_child
```
```
In security/apparmor/policy_ns.c (ffffffff814aa30d)
Location: security/apparmor/include/lib.h:66
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:aa_prepare_ns
  - security/apparmor/policy_ns.c:__aa_find_or_create_ns
  - security/apparmor/policy_ns.c:__aa_lookupn_ns
  - security/apparmor/policy_ns.c:__aa_lookupn_ns
  - security/apparmor/policy_ns.c:aa_findn_ns
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
In security/apparmor/apparmorfs.c (ffffffff814ecee1)
Location: security/apparmor/include/lib.h:66
Inline: True
```
```
In security/apparmor/policy.c (ffffffff814fbab1)
Location: security/apparmor/include/lib.h:66
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:__lookupn_profile
  - security/apparmor/policy.c:__lookupn_profile
  - security/apparmor/policy.c:__find_child
```
```
In security/apparmor/policy_ns.c (ffffffff81507fa0)
Location: security/apparmor/include/lib.h:66
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:aa_prepare_ns
  - security/apparmor/policy_ns.c:__aa_find_or_create_ns
  - security/apparmor/policy_ns.c:__aa_lookupn_ns
  - security/apparmor/policy_ns.c:__aa_lookupn_ns
  - security/apparmor/policy_ns.c:aa_find_ns
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
In security/apparmor/apparmorfs.c (ffffffff8150a981)
Location: security/apparmor/include/lib.h:66
Inline: True
```
```
In security/apparmor/policy.c (ffffffff81518afb)
Location: security/apparmor/include/lib.h:66
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:__lookupn_profile
  - security/apparmor/policy.c:__lookupn_profile
  - security/apparmor/policy.c:__find_child
```
```
In security/apparmor/policy_ns.c (ffffffff81524fa0)
Location: security/apparmor/include/lib.h:66
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:aa_prepare_ns
  - security/apparmor/policy_ns.c:__aa_find_or_create_ns
  - security/apparmor/policy_ns.c:__aa_lookupn_ns
  - security/apparmor/policy_ns.c:__aa_lookupn_ns
  - security/apparmor/policy_ns.c:aa_findn_ns
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
In security/apparmor/apparmorfs.c (ffffffff81511ece)
Location: security/apparmor/include/lib.h:66
Inline: True
```
```
In security/apparmor/policy.c (ffffffff8151f33e)
Location: security/apparmor/include/lib.h:66
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:__lookupn_profile
  - security/apparmor/policy.c:__lookupn_profile
  - security/apparmor/policy.c:__find_child
```
```
In security/apparmor/policy_ns.c (ffffffff8152b150)
Location: security/apparmor/include/lib.h:66
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:aa_prepare_ns
  - security/apparmor/policy_ns.c:__aa_find_or_create_ns
  - security/apparmor/policy_ns.c:__aa_lookupn_ns
  - security/apparmor/policy_ns.c:__aa_lookupn_ns
  - security/apparmor/policy_ns.c:aa_findn_ns
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
In security/apparmor/apparmorfs.c (ffffffff8156face)
Location: security/apparmor/include/lib.h:66
Inline: True
```
```
In security/apparmor/policy.c (ffffffff8157d4de)
Location: security/apparmor/include/lib.h:66
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:__lookupn_profile
  - security/apparmor/policy.c:__lookupn_profile
  - security/apparmor/policy.c:__find_child
```
```
In security/apparmor/policy_ns.c (ffffffff815894f0)
Location: security/apparmor/include/lib.h:66
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:aa_prepare_ns
  - security/apparmor/policy_ns.c:__aa_find_or_create_ns
  - security/apparmor/policy_ns.c:__aa_lookupn_ns
  - security/apparmor/policy_ns.c:__aa_lookupn_ns
  - security/apparmor/policy_ns.c:aa_findn_ns
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
In security/apparmor/apparmorfs.c (ffffffff8160dcd9)
Location: security/apparmor/include/lib.h:76
Inline: True
```
```
In security/apparmor/policy.c (ffffffff8161bb62)
Location: security/apparmor/include/lib.h:76
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:__lookupn_profile
  - security/apparmor/policy.c:__lookupn_profile
  - security/apparmor/policy.c:__find_child
```
```
In security/apparmor/policy_ns.c (ffffffff81629d43)
Location: security/apparmor/include/lib.h:76
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:aa_prepare_ns
  - security/apparmor/policy_ns.c:__aa_find_or_create_ns
  - security/apparmor/policy_ns.c:__aa_lookupn_ns
  - security/apparmor/policy_ns.c:__aa_lookupn_ns
  - security/apparmor/policy_ns.c:aa_findn_ns
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
In security/apparmor/apparmorfs.c (ffffffff816bfb30)
Location: security/apparmor/include/lib.h:98
Inline: True
```
```
In security/apparmor/policy.c (ffffffff816cec2c)
Location: security/apparmor/include/lib.h:98
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:__lookupn_profile
  - security/apparmor/policy.c:__lookupn_profile
  - security/apparmor/policy.c:__find_child
```
```
In security/apparmor/policy_ns.c (ffffffff816de563)
Location: security/apparmor/include/lib.h:98
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:aa_prepare_ns
  - security/apparmor/policy_ns.c:__aa_find_or_create_ns
  - security/apparmor/policy_ns.c:__aa_lookupn_ns
  - security/apparmor/policy_ns.c:__aa_lookupn_ns
  - security/apparmor/policy_ns.c:aa_find_ns
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
In security/apparmor/apparmorfs.c (ffffffff816f8630)
Location: security/apparmor/include/lib.h:101
Inline: True
```
```
In security/apparmor/policy.c (ffffffff81707838)
Location: security/apparmor/include/lib.h:101
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:__lookupn_profile
  - security/apparmor/policy.c:__lookupn_profile
  - security/apparmor/policy.c:__find_child
```
```
In security/apparmor/policy_ns.c (ffffffff81717b63)
Location: security/apparmor/include/lib.h:101
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:aa_prepare_ns
  - security/apparmor/policy_ns.c:__aa_find_or_create_ns
  - security/apparmor/policy_ns.c:__aa_lookupn_ns
  - security/apparmor/policy_ns.c:__aa_lookupn_ns
  - security/apparmor/policy_ns.c:aa_find_ns
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
In security/apparmor/apparmorfs.c (ffffffff817353e3)
Location: security/apparmor/include/lib.h:100
Inline: True
```
```
In security/apparmor/policy.c (ffffffff817452c8)
Location: security/apparmor/include/lib.h:100
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:__lookupn_profile
  - security/apparmor/policy.c:__lookupn_profile
  - security/apparmor/policy.c:__find_child
```
```
In security/apparmor/policy_ns.c (ffffffff81756533)
Location: security/apparmor/include/lib.h:100
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:aa_prepare_ns
  - security/apparmor/policy_ns.c:__aa_find_or_create_ns
  - security/apparmor/policy_ns.c:__aa_lookupn_ns
  - security/apparmor/policy_ns.c:__aa_lookupn_ns
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
In security/apparmor/apparmorfs.c (ffff80001058bc64)
Location: security/apparmor/include/lib.h:66
Inline: True
```
```
In security/apparmor/policy.c (ffff800010597524)
Location: security/apparmor/include/lib.h:66
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:__lookupn_profile
  - security/apparmor/policy.c:__lookupn_profile
  - security/apparmor/policy.c:__find_child
```
```
In security/apparmor/policy_ns.c (ffff8000105a0f24)
Location: security/apparmor/include/lib.h:66
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:aa_prepare_ns
  - security/apparmor/policy_ns.c:__aa_find_or_create_ns
  - security/apparmor/policy_ns.c:__aa_lookupn_ns
  - security/apparmor/policy_ns.c:__aa_lookupn_ns
  - security/apparmor/policy_ns.c:aa_findn_ns
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
In security/apparmor/apparmorfs.c (c073c7d4)
Location: security/apparmor/include/lib.h:66
Inline: True
```
```
In security/apparmor/policy.c (c07485ac)
Location: security/apparmor/include/lib.h:66
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:__lookupn_profile
  - security/apparmor/policy.c:__lookupn_profile
  - security/apparmor/policy.c:__find_child
```
```
In security/apparmor/policy_ns.c (c07519ac)
Location: security/apparmor/include/lib.h:66
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:aa_prepare_ns
  - security/apparmor/policy_ns.c:__aa_find_or_create_ns
  - security/apparmor/policy_ns.c:__aa_lookupn_ns
  - security/apparmor/policy_ns.c:__aa_lookupn_ns
  - security/apparmor/policy_ns.c:aa_findn_ns
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
In security/apparmor/apparmorfs.c (c0000000006fceb4)
Location: security/apparmor/include/lib.h:66
Inline: True
```
```
In security/apparmor/policy.c (c00000000070dbd4)
Location: security/apparmor/include/lib.h:66
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:__lookupn_profile
  - security/apparmor/policy.c:__lookupn_profile
  - security/apparmor/policy.c:__find_child
```
```
In security/apparmor/policy_ns.c (c00000000071b614)
Location: security/apparmor/include/lib.h:66
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:aa_prepare_ns
  - security/apparmor/policy_ns.c:__aa_find_or_create_ns
  - security/apparmor/policy_ns.c:__aa_lookupn_ns
  - security/apparmor/policy_ns.c:__aa_lookupn_ns
  - security/apparmor/policy_ns.c:aa_findn_ns
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
In security/apparmor/apparmorfs.c (ffffffe0003d9f9e)
Location: security/apparmor/include/lib.h:66
Inline: True
```
```
In security/apparmor/policy.c (ffffffe0003e419a)
Location: security/apparmor/include/lib.h:66
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:__lookupn_profile
  - security/apparmor/policy.c:__lookupn_profile
  - security/apparmor/policy.c:aa_find_child
```
```
In security/apparmor/policy_ns.c (ffffffe0003ebcb0)
Location: security/apparmor/include/lib.h:66
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:aa_prepare_ns
  - security/apparmor/policy_ns.c:__aa_find_or_create_ns
  - security/apparmor/policy_ns.c:__aa_lookupn_ns
  - security/apparmor/policy_ns.c:__aa_lookupn_ns
  - security/apparmor/policy_ns.c:aa_findn_ns
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
In security/apparmor/apparmorfs.c (ffffffff8148e207)
Location: security/apparmor/include/lib.h:66
Inline: True
```
```
In security/apparmor/policy.c (ffffffff81499e17)
Location: security/apparmor/include/lib.h:66
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:__lookupn_profile
  - security/apparmor/policy.c:__lookupn_profile
  - security/apparmor/policy.c:__find_child
```
```
In security/apparmor/policy_ns.c (ffffffff814a28ed)
Location: security/apparmor/include/lib.h:66
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:aa_prepare_ns
  - security/apparmor/policy_ns.c:__aa_find_or_create_ns
  - security/apparmor/policy_ns.c:__aa_lookupn_ns
  - security/apparmor/policy_ns.c:__aa_lookupn_ns
  - security/apparmor/policy_ns.c:aa_findn_ns
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
In security/apparmor/apparmorfs.c (ffffffff8147ec27)
Location: security/apparmor/include/lib.h:66
Inline: True
```
```
In security/apparmor/policy.c (ffffffff8148a837)
Location: security/apparmor/include/lib.h:66
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:__lookupn_profile
  - security/apparmor/policy.c:__lookupn_profile
  - security/apparmor/policy.c:__find_child
```
```
In security/apparmor/policy_ns.c (ffffffff8149330d)
Location: security/apparmor/include/lib.h:66
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:aa_prepare_ns
  - security/apparmor/policy_ns.c:__aa_find_or_create_ns
  - security/apparmor/policy_ns.c:__aa_lookupn_ns
  - security/apparmor/policy_ns.c:__aa_lookupn_ns
  - security/apparmor/policy_ns.c:aa_findn_ns
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
In security/apparmor/apparmorfs.c (ffffffff8148a2a7)
Location: security/apparmor/include/lib.h:66
Inline: True
```
```
In security/apparmor/policy.c (ffffffff81495eb7)
Location: security/apparmor/include/lib.h:66
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:__lookupn_profile
  - security/apparmor/policy.c:__lookupn_profile
  - security/apparmor/policy.c:__find_child
```
```
In security/apparmor/policy_ns.c (ffffffff8149e98d)
Location: security/apparmor/include/lib.h:66
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:aa_prepare_ns
  - security/apparmor/policy_ns.c:__aa_find_or_create_ns
  - security/apparmor/policy_ns.c:__aa_lookupn_ns
  - security/apparmor/policy_ns.c:__aa_lookupn_ns
  - security/apparmor/policy_ns.c:aa_findn_ns
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
In security/apparmor/apparmorfs.c (ffffffff814a1f72)
Location: security/apparmor/include/lib.h:66
Inline: True
```
```
In security/apparmor/policy.c (ffffffff814adf47)
Location: security/apparmor/include/lib.h:66
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:__lookupn_profile
  - security/apparmor/policy.c:__lookupn_profile
  - security/apparmor/policy.c:__find_child
```
```
In security/apparmor/policy_ns.c (ffffffff814b6fbd)
Location: security/apparmor/include/lib.h:66
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:aa_prepare_ns
  - security/apparmor/policy_ns.c:__aa_find_or_create_ns
  - security/apparmor/policy_ns.c:__aa_lookupn_ns
  - security/apparmor/policy_ns.c:__aa_lookupn_ns
  - security/apparmor/policy_ns.c:aa_findn_ns
```
</details>
</li>
</ul>

## Differences
