# Function: <code>aa_get_profile_not0</code>

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
In security/apparmor/policy.c (ffffffff8137fc5a)
Location: security/apparmor/include/policy.h:237
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_find_child
  - security/apparmor/policy.c:aa_lookupn_profile
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff813b961a)
Location: security/apparmor/include/policy.h:254
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_find_child
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff813d09da)
Location: security/apparmor/include/policy.h:254
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_find_child
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff813e3e86)
Location: security/apparmor/include/policy.h:258
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_find_child
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff8140ac76)
Location: security/apparmor/include/policy.h:258
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_find_child
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff8143cb40)
Location: security/apparmor/include/policy.h:266
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_new_null_profile
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff814599a0)
Location: security/apparmor/include/policy.h:266
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_new_null_profile
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff81486b56)
Location: security/apparmor/include/policy.h:261
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_find_child
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
In security/apparmor/domain.c (ffffffff8149c1f7)
Location: security/apparmor/include/policy.h:261
Inline: True
Inline callers:
  - security/apparmor/domain.c:find_attach
```
```
In security/apparmor/policy.c (ffffffff814a0a06)
Location: security/apparmor/include/policy.h:261
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_find_child
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
In security/apparmor/domain.c (ffffffff814f4bfd)
Location: security/apparmor/include/policy.h:264
Inline: True
Inline callers:
  - security/apparmor/domain.c:find_attach
```
```
In security/apparmor/policy.c (ffffffff814faae8)
Location: security/apparmor/include/policy.h:264
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_find_child
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
In security/apparmor/domain.c (ffffffff81511ffd)
Location: security/apparmor/include/policy.h:264
Inline: True
Inline callers:
  - security/apparmor/domain.c:find_attach
```
```
In security/apparmor/policy.c (ffffffff81517868)
Location: security/apparmor/include/policy.h:264
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_find_child
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
In security/apparmor/domain.c (ffffffff8151893d)
Location: security/apparmor/include/policy.h:264
Inline: True
Inline callers:
  - security/apparmor/domain.c:find_attach
```
```
In security/apparmor/policy.c (ffffffff8151e118)
Location: security/apparmor/include/policy.h:264
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_find_child
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
In security/apparmor/domain.c (ffffffff8157694d)
Location: security/apparmor/include/policy.h:264
Inline: True
Inline callers:
  - security/apparmor/domain.c:find_attach
```
```
In security/apparmor/policy.c (ffffffff8157c268)
Location: security/apparmor/include/policy.h:264
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_find_child
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
In security/apparmor/domain.c (ffffffff816147f6)
Location: security/apparmor/include/policy.h:331
Inline: True
Inline callers:
  - security/apparmor/domain.c:find_attach
```
```
In security/apparmor/policy.c (ffffffff8161a9b0)
Location: security/apparmor/include/policy.h:331
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_find_child
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
In security/apparmor/domain.c (ffffffff816c7513)
Location: security/apparmor/include/policy.h:337
Inline: True
Inline callers:
  - security/apparmor/domain.c:find_attach
```
```
In security/apparmor/policy.c (ffffffff816cd9b0)
Location: security/apparmor/include/policy.h:337
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_find_child
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
In security/apparmor/domain.c (ffffffff816ffaf1)
Location: security/apparmor/include/policy.h:368
Inline: True
Inline callers:
  - security/apparmor/domain.c:find_attach
```
```
In security/apparmor/policy.c (ffffffff81706610)
Location: security/apparmor/include/policy.h:368
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_find_child
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
In security/apparmor/domain.c (ffffffff8173d0cd)
Location: security/apparmor/include/policy.h:378
Inline: True
Inline callers:
  - security/apparmor/domain.c:find_attach
```
```
In security/apparmor/policy.c (ffffffff81744090)
Location: security/apparmor/include/policy.h:378
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_find_child
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
In security/apparmor/domain.c (ffff800010591d24)
Location: security/apparmor/include/policy.h:261
Inline: True
Inline callers:
  - security/apparmor/domain.c:find_attach
```
```
In security/apparmor/policy.c (ffff800010596788)
Location: security/apparmor/include/policy.h:261
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_find_child
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
In security/apparmor/domain.c (c0742944)
Location: security/apparmor/include/policy.h:261
Inline: True
Inline callers:
  - security/apparmor/domain.c:find_attach
```
```
In security/apparmor/policy.c (c0747864)
Location: security/apparmor/include/policy.h:261
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_find_child
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
In security/apparmor/domain.c (c000000000706968)
Location: security/apparmor/include/policy.h:261
Inline: True
Inline callers:
  - security/apparmor/domain.c:find_attach
```
```
In security/apparmor/policy.c (c00000000070c4e8)
Location: security/apparmor/include/policy.h:261
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_find_child
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
In security/apparmor/domain.c (ffffffe0003dfe1e)
Location: security/apparmor/include/policy.h:261
Inline: True
Inline callers:
  - security/apparmor/domain.c:find_attach
```
```
In security/apparmor/policy.c (ffffffe0003e34e6)
Location: security/apparmor/include/policy.h:261
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_find_child
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
In security/apparmor/domain.c (ffffffff814947d7)
Location: security/apparmor/include/policy.h:261
Inline: True
Inline callers:
  - security/apparmor/domain.c:find_attach
```
```
In security/apparmor/policy.c (ffffffff81498fe6)
Location: security/apparmor/include/policy.h:261
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_find_child
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
In security/apparmor/domain.c (ffffffff814851f7)
Location: security/apparmor/include/policy.h:261
Inline: True
Inline callers:
  - security/apparmor/domain.c:find_attach
```
```
In security/apparmor/policy.c (ffffffff81489a06)
Location: security/apparmor/include/policy.h:261
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_find_child
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
In security/apparmor/domain.c (ffffffff81490877)
Location: security/apparmor/include/policy.h:261
Inline: True
Inline callers:
  - security/apparmor/domain.c:find_attach
```
```
In security/apparmor/policy.c (ffffffff81495086)
Location: security/apparmor/include/policy.h:261
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_find_child
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
In security/apparmor/domain.c (ffffffff814a879c)
Location: security/apparmor/include/policy.h:261
Inline: True
Inline callers:
  - security/apparmor/domain.c:find_attach
```
```
In security/apparmor/policy.c (ffffffff814ad0b0)
Location: security/apparmor/include/policy.h:261
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_find_child
```
</details>
</li>
</ul>

## Differences
