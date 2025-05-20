# Function: <code>__aa_findn_ns</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/policy_ns.c (ffffffff813948ca)
Location: security/apparmor/policy_ns.c:159
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
Location: security/apparmor/include/policy_ns.h:138
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:ns_rmdir_op
```
```
In security/apparmor/policy_ns.c (ffffffff813d051f)
Location: security/apparmor/include/policy_ns.h:138
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
Location: security/apparmor/include/policy_ns.h:141
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:ns_rmdir_op
```
```
In security/apparmor/policy_ns.c (ffffffff813e7c1f)
Location: security/apparmor/include/policy_ns.h:141
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
Location: security/apparmor/include/policy_ns.h:145
Inline: True
```
```
In security/apparmor/policy_ns.c (ffffffff813ec56c)
Location: security/apparmor/include/policy_ns.h:145
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
Location: security/apparmor/include/policy_ns.h:145
Inline: True
```
```
In security/apparmor/policy_ns.c (ffffffff81413efc)
Location: security/apparmor/include/policy_ns.h:145
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
In security/apparmor/apparmorfs.c (ffffffff81432336)
Location: security/apparmor/include/policy_ns.h:145
Inline: True
```
```
In security/apparmor/policy_ns.c (ffffffff81446255)
Location: security/apparmor/include/policy_ns.h:145
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
In security/apparmor/apparmorfs.c (ffffffff8144e4f1)
Location: security/apparmor/include/policy_ns.h:145
Inline: True
```
```
In security/apparmor/policy_ns.c (ffffffff81463175)
Location: security/apparmor/include/policy_ns.h:145
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
In security/apparmor/apparmorfs.c (ffffffff8147bf3b)
Location: security/apparmor/include/policy_ns.h:141
Inline: True
```
```
In security/apparmor/policy_ns.c (ffffffff81490439)
Location: security/apparmor/include/policy_ns.h:141
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
In security/apparmor/apparmorfs.c (ffffffff81495c0b)
Location: security/apparmor/include/policy_ns.h:141
Inline: True
```
```
In security/apparmor/policy_ns.c (ffffffff814aa2f9)
Location: security/apparmor/include/policy_ns.h:141
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
In security/apparmor/apparmorfs.c (ffffffff814ecec7)
Location: security/apparmor/include/policy_ns.h:141
Inline: True
```
```
In security/apparmor/policy_ns.c (ffffffff81507f8c)
Location: security/apparmor/include/policy_ns.h:141
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
In security/apparmor/apparmorfs.c (ffffffff8150a967)
Location: security/apparmor/include/policy_ns.h:141
Inline: True
```
```
In security/apparmor/policy_ns.c (ffffffff81524f8c)
Location: security/apparmor/include/policy_ns.h:141
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
In security/apparmor/apparmorfs.c (ffffffff81511eb4)
Location: security/apparmor/include/policy_ns.h:141
Inline: True
```
```
In security/apparmor/policy_ns.c (ffffffff8152b13c)
Location: security/apparmor/include/policy_ns.h:141
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
In security/apparmor/apparmorfs.c (ffffffff8156fab4)
Location: security/apparmor/include/policy_ns.h:141
Inline: True
```
```
In security/apparmor/policy_ns.c (ffffffff815894dc)
Location: security/apparmor/include/policy_ns.h:141
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
In security/apparmor/apparmorfs.c (ffffffff8160dcb9)
Location: security/apparmor/include/policy_ns.h:142
Inline: True
```
```
In security/apparmor/policy_ns.c (ffffffff81629d2c)
Location: security/apparmor/include/policy_ns.h:142
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
In security/apparmor/apparmorfs.c (ffffffff816bfb10)
Location: security/apparmor/include/policy_ns.h:153
Inline: True
```
```
In security/apparmor/policy_ns.c (ffffffff816de54c)
Location: security/apparmor/include/policy_ns.h:153
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
In security/apparmor/apparmorfs.c (ffffffff816f8610)
Location: security/apparmor/include/policy_ns.h:153
Inline: True
```
```
In security/apparmor/policy_ns.c (ffffffff81717b4c)
Location: security/apparmor/include/policy_ns.h:153
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
In security/apparmor/apparmorfs.c (ffffffff817353c3)
Location: security/apparmor/include/policy_ns.h:150
Inline: True
```
```
In security/apparmor/policy_ns.c (ffffffff8175651c)
Location: security/apparmor/include/policy_ns.h:150
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
Location: security/apparmor/include/policy_ns.h:141
Inline: True
```
```
In security/apparmor/policy_ns.c (ffff8000105a0f08)
Location: security/apparmor/include/policy_ns.h:141
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
Location: security/apparmor/include/policy_ns.h:141
Inline: True
```
```
In security/apparmor/policy_ns.c (c07519a4)
Location: security/apparmor/include/policy_ns.h:141
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
Location: security/apparmor/include/policy_ns.h:141
Inline: True
```
```
In security/apparmor/policy_ns.c (c00000000071b5e8)
Location: security/apparmor/include/policy_ns.h:141
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
Location: security/apparmor/include/policy_ns.h:141
Inline: True
```
```
In security/apparmor/policy_ns.c (ffffffe0003ebc98)
Location: security/apparmor/include/policy_ns.h:141
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
In security/apparmor/apparmorfs.c (ffffffff8148e1eb)
Location: security/apparmor/include/policy_ns.h:141
Inline: True
```
```
In security/apparmor/policy_ns.c (ffffffff814a28d9)
Location: security/apparmor/include/policy_ns.h:141
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
In security/apparmor/apparmorfs.c (ffffffff8147ec0b)
Location: security/apparmor/include/policy_ns.h:141
Inline: True
```
```
In security/apparmor/policy_ns.c (ffffffff814932f9)
Location: security/apparmor/include/policy_ns.h:141
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
In security/apparmor/apparmorfs.c (ffffffff8148a28b)
Location: security/apparmor/include/policy_ns.h:141
Inline: True
```
```
In security/apparmor/policy_ns.c (ffffffff8149e979)
Location: security/apparmor/include/policy_ns.h:141
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
In security/apparmor/apparmorfs.c (ffffffff814a1f56)
Location: security/apparmor/include/policy_ns.h:141
Inline: True
```
```
In security/apparmor/policy_ns.c (ffffffff814b6fa9)
Location: security/apparmor/include/policy_ns.h:141
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
