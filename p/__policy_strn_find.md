# Function: <code>__policy_strn_find</code>

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
Location: security/apparmor/include/lib.h:215
Inline: True
Inline callers:
  - security/apparmor/policy.c:__lookupn_profile
  - security/apparmor/policy.c:__lookupn_profile
  - security/apparmor/policy.c:aa_replace_profiles
```
```
In security/apparmor/policy_ns.c (ffffffff813948ca)
Location: security/apparmor/include/lib.h:215
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
In security/apparmor/apparmorfs.c (ffffffff813ada0a)
Location: security/apparmor/include/lib.h:215
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:ns_rmdir_op
```
```
In security/apparmor/policy.c (ffffffff813ba76a)
Location: security/apparmor/include/lib.h:215
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:__lookupn_profile
  - security/apparmor/policy.c:__lookupn_profile
```
```
In security/apparmor/policy_ns.c (ffffffff813d051f)
Location: security/apparmor/include/lib.h:215
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
In security/apparmor/apparmorfs.c (ffffffff813c481a)
Location: security/apparmor/include/lib.h:216
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:ns_rmdir_op
```
```
In security/apparmor/policy.c (ffffffff813d1b2a)
Location: security/apparmor/include/lib.h:216
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:__lookupn_profile
  - security/apparmor/policy.c:__lookupn_profile
```
```
In security/apparmor/policy_ns.c (ffffffff813e7c1f)
Location: security/apparmor/include/lib.h:216
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
In security/apparmor/apparmorfs.c (ffffffff813da2c0)
Location: security/apparmor/include/lib.h:197
Inline: True
```
```
In security/apparmor/policy.c (ffffffff813e4aa2)
Location: security/apparmor/include/lib.h:197
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:__lookupn_profile
  - security/apparmor/policy.c:__lookupn_profile
  - security/apparmor/policy.c:__find_child
```
```
In security/apparmor/policy_ns.c (ffffffff813ec56c)
Location: security/apparmor/include/lib.h:197
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
In security/apparmor/apparmorfs.c (ffffffff81400606)
Location: security/apparmor/include/lib.h:186
Inline: True
```
```
In security/apparmor/policy.c (ffffffff8140bce7)
Location: security/apparmor/include/lib.h:186
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:__lookupn_profile
  - security/apparmor/policy.c:__lookupn_profile
  - security/apparmor/policy.c:__find_child
```
```
In security/apparmor/policy_ns.c (ffffffff81413efc)
Location: security/apparmor/include/lib.h:186
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
In security/apparmor/apparmorfs.c (ffffffff81432342)
Location: security/apparmor/include/lib.h:186
Inline: True
```
```
In security/apparmor/policy.c (ffffffff8143d592)
Location: security/apparmor/include/lib.h:186
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:__lookupn_profile
  - security/apparmor/policy.c:__lookupn_profile
  - security/apparmor/policy.c:__find_child
```
```
In security/apparmor/policy_ns.c (ffffffff81446255)
Location: security/apparmor/include/lib.h:186
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
In security/apparmor/apparmorfs.c (ffffffff8144e4fd)
Location: security/apparmor/include/lib.h:190
Inline: True
```
```
In security/apparmor/policy.c (ffffffff8145a55e)
Location: security/apparmor/include/lib.h:190
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:__lookupn_profile
  - security/apparmor/policy.c:__lookupn_profile
  - security/apparmor/policy.c:__find_child
```
```
In security/apparmor/policy_ns.c (ffffffff81463175)
Location: security/apparmor/include/lib.h:190
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
In security/apparmor/apparmorfs.c (ffffffff8147bf43)
Location: security/apparmor/include/lib.h:186
Inline: True
```
```
In security/apparmor/policy.c (ffffffff8148796d)
Location: security/apparmor/include/lib.h:186
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:__lookupn_profile
  - security/apparmor/policy.c:__lookupn_profile
  - security/apparmor/policy.c:__find_child
```
```
In security/apparmor/policy_ns.c (ffffffff81490439)
Location: security/apparmor/include/lib.h:186
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
In security/apparmor/apparmorfs.c (ffffffff81495c13)
Location: security/apparmor/include/lib.h:186
Inline: True
```
```
In security/apparmor/policy.c (ffffffff814a181d)
Location: security/apparmor/include/lib.h:186
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:__lookupn_profile
  - security/apparmor/policy.c:__lookupn_profile
  - security/apparmor/policy.c:__find_child
```
```
In security/apparmor/policy_ns.c (ffffffff814aa2f9)
Location: security/apparmor/include/lib.h:186
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
In security/apparmor/apparmorfs.c (ffffffff814ececa)
Location: security/apparmor/include/lib.h:186
Inline: True
```
```
In security/apparmor/policy.c (ffffffff814fba9f)
Location: security/apparmor/include/lib.h:186
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:__lookupn_profile
  - security/apparmor/policy.c:__lookupn_profile
  - security/apparmor/policy.c:__find_child
```
```
In security/apparmor/policy_ns.c (ffffffff81507f8c)
Location: security/apparmor/include/lib.h:186
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
In security/apparmor/apparmorfs.c (ffffffff8150a96a)
Location: security/apparmor/include/lib.h:186
Inline: True
```
```
In security/apparmor/policy.c (ffffffff81518aec)
Location: security/apparmor/include/lib.h:186
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:__lookupn_profile
  - security/apparmor/policy.c:__lookupn_profile
  - security/apparmor/policy.c:__find_child
```
```
In security/apparmor/policy_ns.c (ffffffff81524f8c)
Location: security/apparmor/include/lib.h:186
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
In security/apparmor/apparmorfs.c (ffffffff81511eb7)
Location: security/apparmor/include/lib.h:186
Inline: True
```
```
In security/apparmor/policy.c (ffffffff8151f32f)
Location: security/apparmor/include/lib.h:186
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:__lookupn_profile
  - security/apparmor/policy.c:__lookupn_profile
  - security/apparmor/policy.c:__find_child
```
```
In security/apparmor/policy_ns.c (ffffffff8152b13c)
Location: security/apparmor/include/lib.h:186
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
In security/apparmor/apparmorfs.c (ffffffff8156fab7)
Location: security/apparmor/include/lib.h:186
Inline: True
```
```
In security/apparmor/policy.c (ffffffff8157d4cf)
Location: security/apparmor/include/lib.h:186
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:__lookupn_profile
  - security/apparmor/policy.c:__lookupn_profile
  - security/apparmor/policy.c:__find_child
```
```
In security/apparmor/policy_ns.c (ffffffff815894dc)
Location: security/apparmor/include/lib.h:186
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
In security/apparmor/apparmorfs.c (ffffffff8160dcc1)
Location: security/apparmor/include/lib.h:202
Inline: True
```
```
In security/apparmor/policy.c (ffffffff8161bb4f)
Location: security/apparmor/include/lib.h:202
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:__lookupn_profile
  - security/apparmor/policy.c:__lookupn_profile
  - security/apparmor/policy.c:__find_child
```
```
In security/apparmor/policy_ns.c (ffffffff81629d2c)
Location: security/apparmor/include/lib.h:202
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
In security/apparmor/apparmorfs.c (ffffffff816bfb18)
Location: security/apparmor/include/lib.h:224
Inline: True
```
```
In security/apparmor/policy.c (ffffffff816cec18)
Location: security/apparmor/include/lib.h:224
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:__lookupn_profile
  - security/apparmor/policy.c:__lookupn_profile
  - security/apparmor/policy.c:__find_child
```
```
In security/apparmor/policy_ns.c (ffffffff816de54c)
Location: security/apparmor/include/lib.h:224
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
In security/apparmor/apparmorfs.c (ffffffff816f8618)
Location: security/apparmor/include/lib.h:235
Inline: True
```
```
In security/apparmor/policy.c (ffffffff81707824)
Location: security/apparmor/include/lib.h:235
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:__lookupn_profile
  - security/apparmor/policy.c:__lookupn_profile
  - security/apparmor/policy.c:__find_child
```
```
In security/apparmor/policy_ns.c (ffffffff81717b4c)
Location: security/apparmor/include/lib.h:235
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
In security/apparmor/apparmorfs.c (ffffffff817353cb)
Location: security/apparmor/include/lib.h:234
Inline: True
```
```
In security/apparmor/policy.c (ffffffff817452b4)
Location: security/apparmor/include/lib.h:234
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:__lookupn_profile
  - security/apparmor/policy.c:__lookupn_profile
  - security/apparmor/policy.c:__find_child
```
```
In security/apparmor/policy_ns.c (ffffffff8175651c)
Location: security/apparmor/include/lib.h:234
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
In security/apparmor/apparmorfs.c (ffff80001058bc54)
Location: security/apparmor/include/lib.h:186
Inline: True
```
```
In security/apparmor/policy.c (ffff80001059750c)
Location: security/apparmor/include/lib.h:186
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:__lookupn_profile
  - security/apparmor/policy.c:__lookupn_profile
  - security/apparmor/policy.c:__find_child
```
```
In security/apparmor/policy_ns.c (ffff8000105a0f08)
Location: security/apparmor/include/lib.h:186
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
In security/apparmor/apparmorfs.c (c073c7c4)
Location: security/apparmor/include/lib.h:186
Inline: True
```
```
In security/apparmor/policy.c (c074859c)
Location: security/apparmor/include/lib.h:186
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:__lookupn_profile
  - security/apparmor/policy.c:__lookupn_profile
  - security/apparmor/policy.c:__find_child
```
```
In security/apparmor/policy_ns.c (c07519a4)
Location: security/apparmor/include/lib.h:186
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
In security/apparmor/apparmorfs.c (c0000000006fce94)
Location: security/apparmor/include/lib.h:186
Inline: True
```
```
In security/apparmor/policy.c (c00000000070dbb8)
Location: security/apparmor/include/lib.h:186
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:__lookupn_profile
  - security/apparmor/policy.c:__lookupn_profile
  - security/apparmor/policy.c:__find_child
```
```
In security/apparmor/policy_ns.c (c00000000071b5ec)
Location: security/apparmor/include/lib.h:186
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
In security/apparmor/apparmorfs.c (ffffffe0003d9f86)
Location: security/apparmor/include/lib.h:186
Inline: True
```
```
In security/apparmor/policy.c (ffffffe0003e419a)
Location: security/apparmor/include/lib.h:186
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
In security/apparmor/policy_ns.c (ffffffe0003ebc98)
Location: security/apparmor/include/lib.h:186
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
In security/apparmor/apparmorfs.c (ffffffff8148e1f3)
Location: security/apparmor/include/lib.h:186
Inline: True
```
```
In security/apparmor/policy.c (ffffffff81499dfd)
Location: security/apparmor/include/lib.h:186
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:__lookupn_profile
  - security/apparmor/policy.c:__lookupn_profile
  - security/apparmor/policy.c:__find_child
```
```
In security/apparmor/policy_ns.c (ffffffff814a28d9)
Location: security/apparmor/include/lib.h:186
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
In security/apparmor/apparmorfs.c (ffffffff8147ec13)
Location: security/apparmor/include/lib.h:186
Inline: True
```
```
In security/apparmor/policy.c (ffffffff8148a81d)
Location: security/apparmor/include/lib.h:186
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:__lookupn_profile
  - security/apparmor/policy.c:__lookupn_profile
  - security/apparmor/policy.c:__find_child
```
```
In security/apparmor/policy_ns.c (ffffffff814932f9)
Location: security/apparmor/include/lib.h:186
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
In security/apparmor/apparmorfs.c (ffffffff8148a293)
Location: security/apparmor/include/lib.h:186
Inline: True
```
```
In security/apparmor/policy.c (ffffffff81495e9d)
Location: security/apparmor/include/lib.h:186
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:__lookupn_profile
  - security/apparmor/policy.c:__lookupn_profile
  - security/apparmor/policy.c:__find_child
```
```
In security/apparmor/policy_ns.c (ffffffff8149e979)
Location: security/apparmor/include/lib.h:186
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
In security/apparmor/apparmorfs.c (ffffffff814a1f5e)
Location: security/apparmor/include/lib.h:186
Inline: True
```
```
In security/apparmor/policy.c (ffffffff814adf2d)
Location: security/apparmor/include/lib.h:186
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:__lookupn_profile
  - security/apparmor/policy.c:__lookupn_profile
  - security/apparmor/policy.c:__find_child
```
```
In security/apparmor/policy_ns.c (ffffffff814b6fa9)
Location: security/apparmor/include/lib.h:186
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
