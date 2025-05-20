# Function: <code>aa_get_dfa</code>

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
In security/apparmor/policy.c (ffffffff8137fe5a)
Location: security/apparmor/include/match.h:141
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_null_profile
  - security/apparmor/policy.c:aa_null_profile
```
```
In security/apparmor/policy_unpack.c (ffffffff8138221d)
Location: security/apparmor/include/match.h:141
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
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
In security/apparmor/policy.c (ffffffff813b9843)
Location: security/apparmor/include/match.h:142
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_null_profile
  - security/apparmor/policy.c:aa_null_profile
```
```
In security/apparmor/policy_unpack.c (ffffffff813bbe5e)
Location: security/apparmor/include/match.h:142
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
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
In security/apparmor/policy.c (ffffffff813d0c0a)
Location: security/apparmor/include/match.h:142
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_null_profile
  - security/apparmor/policy.c:aa_null_profile
```
```
In security/apparmor/policy_unpack.c (ffffffff813d336e)
Location: security/apparmor/include/match.h:142
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
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
In security/apparmor/policy.c (ffffffff813e43b7)
Location: security/apparmor/include/match.h:142
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_new_null_profile
```
```
In security/apparmor/policy_unpack.c (ffffffff813e5f7f)
Location: security/apparmor/include/match.h:142
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
```
```
In security/apparmor/policy_ns.c (ffffffff813ebf4f)
Location: security/apparmor/include/match.h:142
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:alloc_ns
  - security/apparmor/policy_ns.c:alloc_ns
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
In security/apparmor/policy.c (ffffffff8140b303)
Location: security/apparmor/include/match.h:142
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_new_null_profile
```
```
In security/apparmor/policy_unpack.c (ffffffff8140d16f)
Location: security/apparmor/include/match.h:142
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
```
```
In security/apparmor/policy_ns.c (ffffffff8141393f)
Location: security/apparmor/include/match.h:142
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:alloc_ns
  - security/apparmor/policy_ns.c:alloc_ns
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
In security/apparmor/policy.c (ffffffff8143cc2f)
Location: security/apparmor/include/match.h:167
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_new_null_profile
```
```
In security/apparmor/policy_unpack.c (ffffffff8143ed9a)
Location: security/apparmor/include/match.h:167
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
```
```
In security/apparmor/policy_ns.c (ffffffff81445c3b)
Location: security/apparmor/include/match.h:167
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:alloc_ns
  - security/apparmor/policy_ns.c:alloc_ns
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
In security/apparmor/policy.c (ffffffff81459a8f)
Location: security/apparmor/include/match.h:167
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_new_null_profile
```
```
In security/apparmor/policy_unpack.c (ffffffff8145bcaf)
Location: security/apparmor/include/match.h:167
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
```
```
In security/apparmor/policy_ns.c (ffffffff81462b57)
Location: security/apparmor/include/match.h:167
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:alloc_ns
  - security/apparmor/policy_ns.c:alloc_ns
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
In security/apparmor/policy.c (ffffffff81487120)
Location: security/apparmor/include/match.h:163
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_new_null_profile
```
```
In security/apparmor/policy_unpack.c (ffffffff814893fb)
Location: security/apparmor/include/match.h:163
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
```
```
In security/apparmor/policy_ns.c (ffffffff8148fe8f)
Location: security/apparmor/include/match.h:163
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:alloc_ns
  - security/apparmor/policy_ns.c:alloc_ns
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
In security/apparmor/policy.c (ffffffff814a0fd0)
Location: security/apparmor/include/match.h:162
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_new_null_profile
```
```
In security/apparmor/policy_unpack.c (ffffffff814a32a5)
Location: security/apparmor/include/match.h:162
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
```
```
In security/apparmor/policy_ns.c (ffffffff814a9d4f)
Location: security/apparmor/include/match.h:162
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:alloc_ns
  - security/apparmor/policy_ns.c:alloc_ns
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
In security/apparmor/policy.c (ffffffff814faf45)
Location: security/apparmor/include/match.h:169
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_new_null_profile
```
```
In security/apparmor/policy_unpack.c (ffffffff814fe500)
Location: security/apparmor/include/match.h:169
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
```
```
In security/apparmor/policy_ns.c (ffffffff81507730)
Location: security/apparmor/include/match.h:169
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:alloc_ns
  - security/apparmor/policy_ns.c:alloc_ns
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/apparmor/policy.c (ffffffff81517ffe)
Location: security/apparmor/include/match.h:169
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_new_null_profile
```
```
In security/apparmor/policy_unpack.c (ffffffff8151b760)
Location: security/apparmor/include/match.h:169
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
Direct callers:
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
```
```
In security/apparmor/policy_ns.c (ffffffff815247d0)
Location: security/apparmor/include/match.h:169
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:alloc_ns
  - security/apparmor/policy_ns.c:alloc_ns
  - security/apparmor/policy_ns.c:alloc_ns
  - security/apparmor/policy_ns.c:alloc_ns
```
**Symbols:**

```
ffffffff8151a3f0-ffffffff8151a422: aa_get_dfa.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/apparmor/policy.c (ffffffff8151e86c)
Location: security/apparmor/include/match.h:169
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_new_null_profile
```
```
In security/apparmor/policy_unpack.c (ffffffff81521e5f)
Location: security/apparmor/include/match.h:169
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
Direct callers:
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
```
```
In security/apparmor/policy_ns.c (ffffffff8152a910)
Location: security/apparmor/include/match.h:169
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:alloc_ns
  - security/apparmor/policy_ns.c:alloc_ns
  - security/apparmor/policy_ns.c:alloc_ns
  - security/apparmor/policy_ns.c:alloc_ns
```
**Symbols:**

```
ffffffff81520cf0-ffffffff81520d22: aa_get_dfa.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/apparmor/policy.c (ffffffff8157c9bc)
Location: security/apparmor/include/match.h:169
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_new_null_profile
```
```
In security/apparmor/policy_unpack.c (ffffffff8158002e)
Location: security/apparmor/include/match.h:169
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
Direct callers:
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
```
```
In security/apparmor/policy_ns.c (ffffffff81588cbc)
Location: security/apparmor/include/match.h:169
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:alloc_ns
  - security/apparmor/policy_ns.c:alloc_ns
  - security/apparmor/policy_ns.c:alloc_ns
  - security/apparmor/policy_ns.c:alloc_ns
```
**Symbols:**

```
ffffffff8157ee90-ffffffff8157eec2: aa_get_dfa.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/apparmor/policy.c (ffffffff8161aed9)
Location: security/apparmor/include/match.h:169
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_new_null_profile
```
```
In security/apparmor/policy_unpack.c (ffffffff8161f081)
Location: security/apparmor/include/match.h:169
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
Direct callers:
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
```
```
In security/apparmor/policy_ns.c (ffffffff81629434)
Location: security/apparmor/include/match.h:169
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:alloc_unconfined
  - security/apparmor/policy_ns.c:alloc_unconfined
  - security/apparmor/policy_ns.c:alloc_unconfined
  - security/apparmor/policy_ns.c:alloc_unconfined
```
**Symbols:**

```
ffffffff8161d8e0-ffffffff8161d936: aa_get_dfa.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/apparmor/policy.c (ffffffff816cdd71)
Location: security/apparmor/include/match.h:169
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_alloc_null
  - security/apparmor/policy.c:aa_alloc_null
  - security/apparmor/policy.c:aa_alloc_null
  - security/apparmor/policy.c:aa_alloc_null
```
```
In security/apparmor/policy_unpack.c (ffffffff816d2562)
Location: security/apparmor/include/match.h:169
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
Direct callers:
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
```
**Symbols:**

```
ffffffff816d0a30-ffffffff816d0a86: aa_get_dfa.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff836f8a66)
Location: security/apparmor/include/match.h:163
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_init
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff8392bc5b)
Location: security/apparmor/include/match.h:163
Inline: True
Inline callers:
  - security/apparmor/lsm.c:aa_setup_dfa_engine
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
In security/apparmor/policy.c (ffff800010596ccc)
Location: security/apparmor/include/match.h:162
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_new_null_profile
```
```
In security/apparmor/policy_unpack.c (ffff800010599004)
Location: security/apparmor/include/match.h:162
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
```
```
In security/apparmor/policy_ns.c (ffff8000105a0724)
Location: security/apparmor/include/match.h:162
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:alloc_ns
  - security/apparmor/policy_ns.c:alloc_ns
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
In security/apparmor/policy.c (c0747d9c)
Location: security/apparmor/include/match.h:162
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_new_null_profile
```
```
In security/apparmor/policy_unpack.c (c074a2bc)
Location: security/apparmor/include/match.h:162
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
```
```
In security/apparmor/policy_ns.c (c075132c)
Location: security/apparmor/include/match.h:162
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:alloc_ns
  - security/apparmor/policy_ns.c:alloc_ns
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
In security/apparmor/policy.c (c00000000070cd4c)
Location: security/apparmor/include/match.h:162
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_new_null_profile
```
```
In security/apparmor/policy_unpack.c (c0000000007100f4)
Location: security/apparmor/include/match.h:162
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
```
```
In security/apparmor/policy_ns.c (c00000000071ab20)
Location: security/apparmor/include/match.h:162
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:alloc_ns
  - security/apparmor/policy_ns.c:alloc_ns
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
In security/apparmor/policy.c (ffffffe0003e39fc)
Location: security/apparmor/include/match.h:162
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_new_null_profile
```
```
In security/apparmor/policy_unpack.c (ffffffe0003e5850)
Location: security/apparmor/include/match.h:162
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
```
```
In security/apparmor/policy_ns.c (ffffffe0003eb68c)
Location: security/apparmor/include/match.h:162
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:alloc_ns
  - security/apparmor/policy_ns.c:alloc_ns
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
In security/apparmor/policy.c (ffffffff814995b0)
Location: security/apparmor/include/match.h:162
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_new_null_profile
```
```
In security/apparmor/policy_unpack.c (ffffffff8149b885)
Location: security/apparmor/include/match.h:162
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
```
```
In security/apparmor/policy_ns.c (ffffffff814a232f)
Location: security/apparmor/include/match.h:162
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:alloc_ns
  - security/apparmor/policy_ns.c:alloc_ns
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
In security/apparmor/policy.c (ffffffff81489fd0)
Location: security/apparmor/include/match.h:162
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_new_null_profile
```
```
In security/apparmor/policy_unpack.c (ffffffff8148c2a5)
Location: security/apparmor/include/match.h:162
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
```
```
In security/apparmor/policy_ns.c (ffffffff81492d4f)
Location: security/apparmor/include/match.h:162
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:alloc_ns
  - security/apparmor/policy_ns.c:alloc_ns
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
In security/apparmor/policy.c (ffffffff81495650)
Location: security/apparmor/include/match.h:162
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_new_null_profile
```
```
In security/apparmor/policy_unpack.c (ffffffff81497925)
Location: security/apparmor/include/match.h:162
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
```
```
In security/apparmor/policy_ns.c (ffffffff8149e3cf)
Location: security/apparmor/include/match.h:162
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:alloc_ns
  - security/apparmor/policy_ns.c:alloc_ns
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
In security/apparmor/policy.c (ffffffff814ad6b0)
Location: security/apparmor/include/match.h:162
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_new_null_profile
```
```
In security/apparmor/policy_unpack.c (ffffffff814afa75)
Location: security/apparmor/include/match.h:162
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
```
```
In security/apparmor/policy_ns.c (ffffffff814b69bf)
Location: security/apparmor/include/match.h:162
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:alloc_ns
  - security/apparmor/policy_ns.c:alloc_ns
```
</details>
</li>
</ul>

## Differences
