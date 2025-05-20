# Function: <code>tomoyo_pathcmp</code>

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
In security/tomoyo/common.c (ffffffff81368016)
Location: security/tomoyo/common.h:1150
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/common.c:tomoyo_write_control
```
```
In security/tomoyo/domain.c (ffffffff8136e6ba)
Location: security/tomoyo/common.h:1150
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_find_next_domain
```
```
In security/tomoyo/securityfs_if.c (ffffffff81372d1d)
Location: security/tomoyo/common.h:1150
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_check_task_acl
```
```
In security/tomoyo/util.c (ffffffff8137464e)
Location: security/tomoyo/common.h:1150
Inline: True
Inline callers:
  - security/tomoyo/util.c:tomoyo_find_domain
  - security/tomoyo/util.c:tomoyo_path_matches_pattern
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
In security/tomoyo/common.c (ffffffff813a185e)
Location: security/tomoyo/common.h:1150
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_write_domain
```
```
In security/tomoyo/domain.c (ffffffff813a4997)
Location: security/tomoyo/common.h:1150
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_find_next_domain
```
```
In security/tomoyo/securityfs_if.c (ffffffff813a913d)
Location: security/tomoyo/common.h:1150
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_check_task_acl
```
```
In security/tomoyo/util.c (ffffffff813aaab0)
Location: security/tomoyo/common.h:1150
Inline: True
Inline callers:
  - security/tomoyo/util.c:tomoyo_path_matches_pattern
  - security/tomoyo/util.c:tomoyo_find_domain
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
In security/tomoyo/common.c (ffffffff813b83de)
Location: security/tomoyo/common.h:1150
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_write_domain
```
```
In security/tomoyo/domain.c (ffffffff813bb517)
Location: security/tomoyo/common.h:1150
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_find_next_domain
```
```
In security/tomoyo/securityfs_if.c (ffffffff813bfcad)
Location: security/tomoyo/common.h:1150
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_check_task_acl
```
```
In security/tomoyo/util.c (ffffffff813c1630)
Location: security/tomoyo/common.h:1150
Inline: True
Inline callers:
  - security/tomoyo/util.c:tomoyo_path_matches_pattern
  - security/tomoyo/util.c:tomoyo_find_domain
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
In security/tomoyo/common.c (ffffffff813cec86)
Location: security/tomoyo/common.h:1152
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_write_domain
```
```
In security/tomoyo/domain.c (ffffffff813d1d76)
Location: security/tomoyo/common.h:1152
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_find_next_domain
```
```
In security/tomoyo/securityfs_if.c (ffffffff813d656d)
Location: security/tomoyo/common.h:1152
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_check_task_acl
```
```
In security/tomoyo/util.c (ffffffff813d7fb0)
Location: security/tomoyo/common.h:1152
Inline: True
Inline callers:
  - security/tomoyo/util.c:tomoyo_path_matches_pattern
  - security/tomoyo/util.c:tomoyo_find_domain
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
In security/tomoyo/common.c (ffffffff813f5130)
Location: security/tomoyo/common.h:1154
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_write_domain
```
```
In security/tomoyo/domain.c (ffffffff813f8286)
Location: security/tomoyo/common.h:1154
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_find_next_domain
```
```
In security/tomoyo/securityfs_if.c (ffffffff813fca9d)
Location: security/tomoyo/common.h:1154
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_check_task_acl
```
```
In security/tomoyo/util.c (ffffffff813fe400)
Location: security/tomoyo/common.h:1154
Inline: True
Inline callers:
  - security/tomoyo/util.c:tomoyo_path_matches_pattern
  - security/tomoyo/util.c:tomoyo_find_domain
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
In security/tomoyo/common.c (ffffffff81425ff4)
Location: security/tomoyo/common.h:1151
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_write_domain
```
```
In security/tomoyo/domain.c (ffffffff8142919c)
Location: security/tomoyo/common.h:1151
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_find_next_domain
```
```
In security/tomoyo/securityfs_if.c (ffffffff8142d9cd)
Location: security/tomoyo/common.h:1151
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_check_task_acl
```
```
In security/tomoyo/util.c (ffffffff8142f344)
Location: security/tomoyo/common.h:1151
Inline: True
Inline callers:
  - security/tomoyo/util.c:tomoyo_path_matches_pattern
  - security/tomoyo/util.c:tomoyo_find_domain
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
In security/tomoyo/common.c (ffffffff814426ef)
Location: security/tomoyo/common.h:1154
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_write_domain
```
```
In security/tomoyo/domain.c (ffffffff81445a60)
Location: security/tomoyo/common.h:1154
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_find_next_domain
```
```
In security/tomoyo/securityfs_if.c (ffffffff8144a31d)
Location: security/tomoyo/common.h:1154
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_check_task_acl
```
```
In security/tomoyo/util.c (ffffffff8144bd66)
Location: security/tomoyo/common.h:1154
Inline: True
Inline callers:
  - security/tomoyo/util.c:tomoyo_path_matches_pattern
  - security/tomoyo/util.c:tomoyo_find_domain
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
In security/tomoyo/common.c (ffffffff81470298)
Location: security/tomoyo/common.h:1165
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_write_domain
```
```
In security/tomoyo/domain.c (ffffffff814736d7)
Location: security/tomoyo/common.h:1165
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_find_next_domain
```
```
In security/tomoyo/securityfs_if.c (ffffffff81477fad)
Location: security/tomoyo/common.h:1165
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_check_task_acl
```
```
In security/tomoyo/util.c (ffffffff81479acb)
Location: security/tomoyo/common.h:1165
Inline: True
Inline callers:
  - security/tomoyo/util.c:tomoyo_path_matches_pattern
  - security/tomoyo/util.c:tomoyo_find_domain
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
In security/tomoyo/common.c (ffffffff8148a068)
Location: security/tomoyo/common.h:1165
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_write_domain
```
```
In security/tomoyo/domain.c (ffffffff8148d477)
Location: security/tomoyo/common.h:1165
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_find_next_domain
```
```
In security/tomoyo/securityfs_if.c (ffffffff81491cbd)
Location: security/tomoyo/common.h:1165
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_check_task_acl
```
```
In security/tomoyo/util.c (ffffffff814937cb)
Location: security/tomoyo/common.h:1165
Inline: True
Inline callers:
  - security/tomoyo/util.c:tomoyo_path_matches_pattern
  - security/tomoyo/util.c:tomoyo_find_domain
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
In security/tomoyo/common.c (ffffffff814dd430)
Location: security/tomoyo/common.h:1165
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/common.c:tomoyo_manager
```
```
In security/tomoyo/domain.c (ffffffff814e34bf)
Location: security/tomoyo/common.h:1165
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_transition_type
```
```
In security/tomoyo/securityfs_if.c (ffffffff814e93cd)
Location: security/tomoyo/common.h:1165
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_check_task_acl
```
```
In security/tomoyo/util.c (ffffffff814eab9b)
Location: security/tomoyo/common.h:1165
Inline: True
Inline callers:
  - security/tomoyo/util.c:tomoyo_path_matches_pattern
  - security/tomoyo/util.c:tomoyo_find_domain
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
In security/tomoyo/common.c (ffffffff814fa850)
Location: security/tomoyo/common.h:1165
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/common.c:tomoyo_manager
```
```
In security/tomoyo/domain.c (ffffffff815008ef)
Location: security/tomoyo/common.h:1165
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_transition_type
```
```
In security/tomoyo/securityfs_if.c (ffffffff815066ed)
Location: security/tomoyo/common.h:1165
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_check_task_acl
```
```
In security/tomoyo/util.c (ffffffff81507f9b)
Location: security/tomoyo/common.h:1165
Inline: True
Inline callers:
  - security/tomoyo/util.c:tomoyo_path_matches_pattern
  - security/tomoyo/util.c:tomoyo_find_domain
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
In security/tomoyo/common.c (ffffffff81505531)
Location: security/tomoyo/common.h:1165
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_write_domain
```
```
In security/tomoyo/domain.c (ffffffff815086da)
Location: security/tomoyo/common.h:1165
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_find_next_domain
```
```
In security/tomoyo/securityfs_if.c (ffffffff8150d22d)
Location: security/tomoyo/common.h:1165
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_check_task_acl
```
```
In security/tomoyo/util.c (ffffffff8150eb1b)
Location: security/tomoyo/common.h:1165
Inline: True
Inline callers:
  - security/tomoyo/util.c:tomoyo_path_matches_pattern
  - security/tomoyo/util.c:tomoyo_find_domain
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
In security/tomoyo/common.c (ffffffff8155ca73)
Location: security/tomoyo/common.h:1165
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/common.c:tomoyo_manager
```
```
In security/tomoyo/domain.c (ffffffff81565968)
Location: security/tomoyo/common.h:1165
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_find_next_domain
```
```
In security/tomoyo/securityfs_if.c (ffffffff8156ad6d)
Location: security/tomoyo/common.h:1165
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_check_task_acl
```
```
In security/tomoyo/util.c (ffffffff8156c6af)
Location: security/tomoyo/common.h:1165
Inline: True
Inline callers:
  - security/tomoyo/util.c:tomoyo_path_matches_pattern
  - security/tomoyo/util.c:tomoyo_find_domain
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
In security/tomoyo/common.c (ffffffff815f7b7a)
Location: security/tomoyo/common.h:1164
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/common.c:tomoyo_manager
```
```
In security/tomoyo/domain.c (ffffffff816011c7)
Location: security/tomoyo/common.h:1164
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_find_next_domain
```
```
In security/tomoyo/securityfs_if.c (ffffffff81606ddd)
Location: security/tomoyo/common.h:1164
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_check_task_acl
```
```
In security/tomoyo/util.c (ffffffff81608a55)
Location: security/tomoyo/common.h:1164
Inline: True
Inline callers:
  - security/tomoyo/util.c:tomoyo_path_matches_pattern
  - security/tomoyo/util.c:tomoyo_find_domain
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
In security/tomoyo/common.c (ffffffff816a878a)
Location: security/tomoyo/common.h:1164
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/common.c:tomoyo_manager
```
```
In security/tomoyo/domain.c (ffffffff816b215f)
Location: security/tomoyo/common.h:1164
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_find_next_domain
```
```
In security/tomoyo/securityfs_if.c (ffffffff816b832d)
Location: security/tomoyo/common.h:1164
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_check_task_acl
```
```
In security/tomoyo/util.c (ffffffff816ba315)
Location: security/tomoyo/common.h:1164
Inline: True
Inline callers:
  - security/tomoyo/util.c:tomoyo_path_matches_pattern
  - security/tomoyo/util.c:tomoyo_find_domain
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
In security/tomoyo/common.c (ffffffff816e11d6)
Location: security/tomoyo/common.h:1164
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/common.c:tomoyo_manager
```
```
In security/tomoyo/domain.c (ffffffff816eab3d)
Location: security/tomoyo/common.h:1164
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_find_next_domain
```
```
In security/tomoyo/securityfs_if.c (ffffffff816f0cfd)
Location: security/tomoyo/common.h:1164
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_check_task_acl
```
```
In security/tomoyo/util.c (ffffffff816f2cb5)
Location: security/tomoyo/common.h:1164
Inline: True
Inline callers:
  - security/tomoyo/util.c:tomoyo_path_matches_pattern
  - security/tomoyo/util.c:tomoyo_find_domain
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
In security/tomoyo/common.c (ffffffff8171de56)
Location: security/tomoyo/common.h:1162
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/common.c:tomoyo_manager
```
```
In security/tomoyo/domain.c (ffffffff8172790b)
Location: security/tomoyo/common.h:1162
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_find_next_domain
```
```
In security/tomoyo/securityfs_if.c (ffffffff8172dacd)
Location: security/tomoyo/common.h:1162
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_check_task_acl
```
```
In security/tomoyo/util.c (ffffffff8172fa75)
Location: security/tomoyo/common.h:1162
Inline: True
Inline callers:
  - security/tomoyo/util.c:tomoyo_path_matches_pattern
  - security/tomoyo/util.c:tomoyo_find_domain
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
In security/tomoyo/common.c (ffff80001057d400)
Location: security/tomoyo/common.h:1165
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_write_domain
```
```
In security/tomoyo/domain.c (ffff800010580718)
Location: security/tomoyo/common.h:1165
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_find_next_domain
```
```
In security/tomoyo/securityfs_if.c (ffff80001058645c)
Location: security/tomoyo/common.h:1165
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_check_task_acl
```
```
In security/tomoyo/util.c (ffff800010588b90)
Location: security/tomoyo/common.h:1165
Inline: True
Inline callers:
  - security/tomoyo/util.c:tomoyo_path_matches_pattern
  - security/tomoyo/util.c:tomoyo_find_domain
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
In security/tomoyo/common.c (c072f9bc)
Location: security/tomoyo/common.h:1165
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_write_domain
```
```
In security/tomoyo/domain.c (c0732ce4)
Location: security/tomoyo/common.h:1165
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_find_next_domain
```
```
In security/tomoyo/securityfs_if.c (c0737d48)
Location: security/tomoyo/common.h:1165
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_check_task_acl
```
```
In security/tomoyo/util.c (c0739f9c)
Location: security/tomoyo/common.h:1165
Inline: True
Inline callers:
  - security/tomoyo/util.c:tomoyo_path_matches_pattern
  - security/tomoyo/util.c:tomoyo_find_domain
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
In security/tomoyo/common.c (c0000000006e8cf0)
Location: security/tomoyo/common.h:1165
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_write_domain
```
```
In security/tomoyo/domain.c (c0000000006ee614)
Location: security/tomoyo/common.h:1165
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_find_next_domain
```
```
In security/tomoyo/securityfs_if.c (c0000000006f6228)
Location: security/tomoyo/common.h:1165
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_check_task_acl
```
```
In security/tomoyo/util.c (c0000000006f94c0)
Location: security/tomoyo/common.h:1165
Inline: True
Inline callers:
  - security/tomoyo/util.c:tomoyo_path_matches_pattern
  - security/tomoyo/util.c:tomoyo_find_domain
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
In security/tomoyo/common.c (ffffffe0003ce8fc)
Location: security/tomoyo/common.h:1165
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_write_domain
```
```
In security/tomoyo/domain.c (ffffffe0003d11e2)
Location: security/tomoyo/common.h:1165
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_find_next_domain
```
```
In security/tomoyo/securityfs_if.c (ffffffe0003d5dbe)
Location: security/tomoyo/common.h:1165
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_check_task_acl
```
```
In security/tomoyo/util.c (ffffffe0003d7af4)
Location: security/tomoyo/common.h:1165
Inline: True
Inline callers:
  - security/tomoyo/util.c:tomoyo_path_matches_pattern
  - security/tomoyo/util.c:tomoyo_find_domain
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
In security/tomoyo/common.c (ffffffff81482648)
Location: security/tomoyo/common.h:1165
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_write_domain
```
```
In security/tomoyo/domain.c (ffffffff81485a57)
Location: security/tomoyo/common.h:1165
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_find_next_domain
```
```
In security/tomoyo/securityfs_if.c (ffffffff8148a29d)
Location: security/tomoyo/common.h:1165
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_check_task_acl
```
```
In security/tomoyo/util.c (ffffffff8148bdab)
Location: security/tomoyo/common.h:1165
Inline: True
Inline callers:
  - security/tomoyo/util.c:tomoyo_path_matches_pattern
  - security/tomoyo/util.c:tomoyo_find_domain
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
In security/tomoyo/common.c (ffffffff81473068)
Location: security/tomoyo/common.h:1165
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_write_domain
```
```
In security/tomoyo/domain.c (ffffffff81476477)
Location: security/tomoyo/common.h:1165
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_find_next_domain
```
```
In security/tomoyo/securityfs_if.c (ffffffff8147acbd)
Location: security/tomoyo/common.h:1165
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_check_task_acl
```
```
In security/tomoyo/util.c (ffffffff8147c7cb)
Location: security/tomoyo/common.h:1165
Inline: True
Inline callers:
  - security/tomoyo/util.c:tomoyo_path_matches_pattern
  - security/tomoyo/util.c:tomoyo_find_domain
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
In security/tomoyo/common.c (ffffffff8147e6e8)
Location: security/tomoyo/common.h:1165
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_write_domain
```
```
In security/tomoyo/domain.c (ffffffff81481af7)
Location: security/tomoyo/common.h:1165
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_find_next_domain
```
```
In security/tomoyo/securityfs_if.c (ffffffff8148633d)
Location: security/tomoyo/common.h:1165
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_check_task_acl
```
```
In security/tomoyo/util.c (ffffffff81487e4b)
Location: security/tomoyo/common.h:1165
Inline: True
Inline callers:
  - security/tomoyo/util.c:tomoyo_path_matches_pattern
  - security/tomoyo/util.c:tomoyo_find_domain
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
In security/tomoyo/common.c (ffffffff814961f8)
Location: security/tomoyo/common.h:1165
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_write_domain
```
```
In security/tomoyo/domain.c (ffffffff81499687)
Location: security/tomoyo/common.h:1165
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_find_next_domain
```
```
In security/tomoyo/securityfs_if.c (ffffffff8149de7d)
Location: security/tomoyo/common.h:1165
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_check_task_acl
```
```
In security/tomoyo/util.c (ffffffff8149f98b)
Location: security/tomoyo/common.h:1165
Inline: True
Inline callers:
  - security/tomoyo/util.c:tomoyo_path_matches_pattern
  - security/tomoyo/util.c:tomoyo_find_domain
```
</details>
</li>
</ul>

## Differences
