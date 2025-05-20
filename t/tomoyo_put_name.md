# Function: <code>tomoyo_put_name</code>

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
In security/tomoyo/common.c (ffffffff81367df3)
Location: security/tomoyo/common.h:1163
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_manager
  - security/tomoyo/common.c:tomoyo_write_task
  - security/tomoyo/common.c:tomoyo_write_profile
```
```
In security/tomoyo/condition.c (ffffffff8136c3ae)
Location: security/tomoyo/common.h:1163
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_get_condition
```
```
In security/tomoyo/domain.c (ffffffff8136d88c)
Location: security/tomoyo/common.h:1163
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_write_transition_control
  - security/tomoyo/domain.c:tomoyo_write_transition_control
  - security/tomoyo/domain.c:tomoyo_write_aggregator
  - security/tomoyo/domain.c:tomoyo_write_aggregator
  - security/tomoyo/domain.c:tomoyo_assign_domain
```
```
In security/tomoyo/environ.c (ffffffff8136ea22)
Location: security/tomoyo/common.h:1163
Inline: True
Inline callers:
  - security/tomoyo/environ.c:tomoyo_write_misc
```
```
In security/tomoyo/file.c (ffffffff8136ee09)
Location: security/tomoyo/common.h:1163
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_put_name_union
```
```
In security/tomoyo/gc.c (ffffffff8136ff76)
Location: security/tomoyo/common.h:1163
Inline: True
Inline callers:
  - security/tomoyo/gc.c:tomoyo_del_acl
  - security/tomoyo/gc.c:tomoyo_del_condition
  - security/tomoyo/gc.c:tomoyo_del_condition
  - security/tomoyo/gc.c:tomoyo_del_condition
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/gc.c:tomoyo_try_to_gc
```
```
In security/tomoyo/group.c (ffffffff81370bc8)
Location: security/tomoyo/common.h:1163
Inline: True
Inline callers:
  - security/tomoyo/group.c:tomoyo_write_group
```
```
In security/tomoyo/memory.c (ffffffff813711cb)
Location: security/tomoyo/common.h:1163
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_group
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
In security/tomoyo/common.c (ffffffff8139e217)
Location: security/tomoyo/common.h:1163
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_task
  - security/tomoyo/common.c:tomoyo_write_manager
  - security/tomoyo/common.c:tomoyo_write_profile
```
```
In security/tomoyo/condition.c (ffffffff813a25cc)
Location: security/tomoyo/common.h:1163
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_get_condition
```
```
In security/tomoyo/domain.c (ffffffff813a4016)
Location: security/tomoyo/common.h:1163
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_write_aggregator
  - security/tomoyo/domain.c:tomoyo_write_aggregator
  - security/tomoyo/domain.c:tomoyo_write_transition_control
  - security/tomoyo/domain.c:tomoyo_write_transition_control
```
```
In security/tomoyo/environ.c (ffffffff813a4d06)
Location: security/tomoyo/common.h:1163
Inline: True
Inline callers:
  - security/tomoyo/environ.c:tomoyo_write_misc
```
```
In security/tomoyo/file.c (ffffffff813a50f9)
Location: security/tomoyo/common.h:1163
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_put_name_union
```
```
In security/tomoyo/gc.c (ffffffff813a663f)
Location: security/tomoyo/common.h:1163
Inline: True
Inline callers:
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/gc.c:tomoyo_del_condition
  - security/tomoyo/gc.c:tomoyo_del_condition
  - security/tomoyo/gc.c:tomoyo_del_condition
  - security/tomoyo/gc.c:tomoyo_del_acl
```
```
In security/tomoyo/group.c (ffffffff813a6fb8)
Location: security/tomoyo/common.h:1163
Inline: True
Inline callers:
  - security/tomoyo/group.c:tomoyo_write_group
```
```
In security/tomoyo/memory.c (ffffffff813a75c9)
Location: security/tomoyo/common.h:1163
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_group
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
In security/tomoyo/common.c (ffffffff813b4df7)
Location: security/tomoyo/common.h:1163
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_task
  - security/tomoyo/common.c:tomoyo_write_manager
  - security/tomoyo/common.c:tomoyo_write_profile
```
```
In security/tomoyo/condition.c (ffffffff813b914c)
Location: security/tomoyo/common.h:1163
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_get_condition
```
```
In security/tomoyo/domain.c (ffffffff813bab96)
Location: security/tomoyo/common.h:1163
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_write_aggregator
  - security/tomoyo/domain.c:tomoyo_write_aggregator
  - security/tomoyo/domain.c:tomoyo_write_transition_control
  - security/tomoyo/domain.c:tomoyo_write_transition_control
```
```
In security/tomoyo/environ.c (ffffffff813bb886)
Location: security/tomoyo/common.h:1163
Inline: True
Inline callers:
  - security/tomoyo/environ.c:tomoyo_write_misc
```
```
In security/tomoyo/file.c (ffffffff813bbc79)
Location: security/tomoyo/common.h:1163
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_put_name_union
```
```
In security/tomoyo/gc.c (ffffffff813bd1bf)
Location: security/tomoyo/common.h:1163
Inline: True
Inline callers:
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/gc.c:tomoyo_del_condition
  - security/tomoyo/gc.c:tomoyo_del_condition
  - security/tomoyo/gc.c:tomoyo_del_condition
  - security/tomoyo/gc.c:tomoyo_del_acl
```
```
In security/tomoyo/group.c (ffffffff813bdb38)
Location: security/tomoyo/common.h:1163
Inline: True
Inline callers:
  - security/tomoyo/group.c:tomoyo_write_group
```
```
In security/tomoyo/memory.c (ffffffff813be14c)
Location: security/tomoyo/common.h:1163
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_group
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
In security/tomoyo/common.c (ffffffff813cb7e8)
Location: security/tomoyo/common.h:1165
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_task
  - security/tomoyo/common.c:tomoyo_write_manager
  - security/tomoyo/common.c:tomoyo_write_profile
```
```
In security/tomoyo/condition.c (ffffffff813cfa2d)
Location: security/tomoyo/common.h:1165
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_get_condition
```
```
In security/tomoyo/domain.c (ffffffff813d1424)
Location: security/tomoyo/common.h:1165
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_write_aggregator
  - security/tomoyo/domain.c:tomoyo_write_aggregator
  - security/tomoyo/domain.c:tomoyo_write_transition_control
  - security/tomoyo/domain.c:tomoyo_write_transition_control
```
```
In security/tomoyo/environ.c (ffffffff813d2183)
Location: security/tomoyo/common.h:1165
Inline: True
Inline callers:
  - security/tomoyo/environ.c:tomoyo_write_misc
```
```
In security/tomoyo/file.c (ffffffff813d2579)
Location: security/tomoyo/common.h:1165
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_put_name_union
```
```
In security/tomoyo/gc.c (ffffffff813d3b53)
Location: security/tomoyo/common.h:1165
Inline: True
Inline callers:
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/gc.c:tomoyo_del_condition
  - security/tomoyo/gc.c:tomoyo_del_condition
  - security/tomoyo/gc.c:tomoyo_del_condition
  - security/tomoyo/gc.c:tomoyo_del_acl
```
```
In security/tomoyo/group.c (ffffffff813d445f)
Location: security/tomoyo/common.h:1165
Inline: True
Inline callers:
  - security/tomoyo/group.c:tomoyo_write_group
```
```
In security/tomoyo/memory.c (ffffffff813d4a10)
Location: security/tomoyo/common.h:1165
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_group
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
In security/tomoyo/common.c (ffffffff813f1c78)
Location: security/tomoyo/common.h:1167
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_task
  - security/tomoyo/common.c:tomoyo_write_manager
  - security/tomoyo/common.c:tomoyo_write_profile
```
```
In security/tomoyo/condition.c (ffffffff813f5edd)
Location: security/tomoyo/common.h:1167
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_get_condition
```
```
In security/tomoyo/domain.c (ffffffff813f78e4)
Location: security/tomoyo/common.h:1167
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_write_aggregator
  - security/tomoyo/domain.c:tomoyo_write_aggregator
  - security/tomoyo/domain.c:tomoyo_write_transition_control
  - security/tomoyo/domain.c:tomoyo_write_transition_control
```
```
In security/tomoyo/environ.c (ffffffff813f8693)
Location: security/tomoyo/common.h:1167
Inline: True
Inline callers:
  - security/tomoyo/environ.c:tomoyo_write_misc
```
```
In security/tomoyo/file.c (ffffffff813f8a89)
Location: security/tomoyo/common.h:1167
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_put_name_union
```
```
In security/tomoyo/gc.c (ffffffff813fa068)
Location: security/tomoyo/common.h:1167
Inline: True
Inline callers:
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/gc.c:tomoyo_del_condition
  - security/tomoyo/gc.c:tomoyo_del_condition
  - security/tomoyo/gc.c:tomoyo_del_condition
  - security/tomoyo/gc.c:tomoyo_del_acl
```
```
In security/tomoyo/group.c (ffffffff813fa96f)
Location: security/tomoyo/common.h:1167
Inline: True
Inline callers:
  - security/tomoyo/group.c:tomoyo_write_group
```
```
In security/tomoyo/memory.c (ffffffff813faf20)
Location: security/tomoyo/common.h:1167
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_group
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
In security/tomoyo/common.c (ffffffff81422a98)
Location: security/tomoyo/common.h:1164
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_task
  - security/tomoyo/common.c:tomoyo_write_manager
  - security/tomoyo/common.c:tomoyo_write_profile
```
```
In security/tomoyo/condition.c (ffffffff81426ec2)
Location: security/tomoyo/common.h:1164
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_get_condition
```
```
In security/tomoyo/domain.c (ffffffff814288cf)
Location: security/tomoyo/common.h:1164
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_write_aggregator
  - security/tomoyo/domain.c:tomoyo_write_aggregator
  - security/tomoyo/domain.c:tomoyo_write_transition_control
  - security/tomoyo/domain.c:tomoyo_write_transition_control
```
```
In security/tomoyo/environ.c (ffffffff81429686)
Location: security/tomoyo/common.h:1164
Inline: True
Inline callers:
  - security/tomoyo/environ.c:tomoyo_write_misc
```
```
In security/tomoyo/file.c (ffffffff81429a79)
Location: security/tomoyo/common.h:1164
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_put_name_union
```
```
In security/tomoyo/gc.c (ffffffff8142afcb)
Location: security/tomoyo/common.h:1164
Inline: True
Inline callers:
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/gc.c:tomoyo_del_condition
  - security/tomoyo/gc.c:tomoyo_del_condition
  - security/tomoyo/gc.c:tomoyo_del_condition
  - security/tomoyo/gc.c:tomoyo_del_acl
```
```
In security/tomoyo/group.c (ffffffff8142b90f)
Location: security/tomoyo/common.h:1164
Inline: True
Inline callers:
  - security/tomoyo/group.c:tomoyo_write_group
```
```
In security/tomoyo/memory.c (ffffffff8142bf4a)
Location: security/tomoyo/common.h:1164
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_group
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
In security/tomoyo/common.c (ffffffff8143f0f8)
Location: security/tomoyo/common.h:1167
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_task
  - security/tomoyo/common.c:tomoyo_write_manager
  - security/tomoyo/common.c:tomoyo_write_profile
```
```
In security/tomoyo/condition.c (ffffffff814435ca)
Location: security/tomoyo/common.h:1167
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_get_condition
```
```
In security/tomoyo/domain.c (ffffffff8144518a)
Location: security/tomoyo/common.h:1167
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_write_aggregator
  - security/tomoyo/domain.c:tomoyo_write_aggregator
  - security/tomoyo/domain.c:tomoyo_write_transition_control
  - security/tomoyo/domain.c:tomoyo_write_transition_control
```
```
In security/tomoyo/environ.c (ffffffff81445f46)
Location: security/tomoyo/common.h:1167
Inline: True
Inline callers:
  - security/tomoyo/environ.c:tomoyo_write_misc
```
```
In security/tomoyo/file.c (ffffffff81446339)
Location: security/tomoyo/common.h:1167
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_put_name_union
```
```
In security/tomoyo/gc.c (ffffffff81447937)
Location: security/tomoyo/common.h:1167
Inline: True
Inline callers:
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/gc.c:tomoyo_del_condition
  - security/tomoyo/gc.c:tomoyo_del_condition
  - security/tomoyo/gc.c:tomoyo_del_condition
  - security/tomoyo/gc.c:tomoyo_del_acl
```
```
In security/tomoyo/group.c (ffffffff8144822f)
Location: security/tomoyo/common.h:1167
Inline: True
Inline callers:
  - security/tomoyo/group.c:tomoyo_write_group
```
```
In security/tomoyo/memory.c (ffffffff81448888)
Location: security/tomoyo/common.h:1167
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_group
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
In security/tomoyo/common.c (ffffffff8146cd7a)
Location: security/tomoyo/common.h:1178
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_task
  - security/tomoyo/common.c:tomoyo_write_manager
  - security/tomoyo/common.c:tomoyo_write_profile
```
```
In security/tomoyo/condition.c (ffffffff814711ed)
Location: security/tomoyo/common.h:1178
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_get_condition
```
```
In security/tomoyo/domain.c (ffffffff81472ddc)
Location: security/tomoyo/common.h:1178
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_write_aggregator
  - security/tomoyo/domain.c:tomoyo_write_aggregator
  - security/tomoyo/domain.c:tomoyo_write_transition_control
  - security/tomoyo/domain.c:tomoyo_write_transition_control
```
```
In security/tomoyo/environ.c (ffffffff81473b5c)
Location: security/tomoyo/common.h:1178
Inline: True
Inline callers:
  - security/tomoyo/environ.c:tomoyo_write_misc
```
```
In security/tomoyo/file.c (ffffffff81473f39)
Location: security/tomoyo/common.h:1178
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_put_name_union
```
```
In security/tomoyo/gc.c (ffffffff8147553d)
Location: security/tomoyo/common.h:1178
Inline: True
Inline callers:
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/gc.c:tomoyo_del_condition
  - security/tomoyo/gc.c:tomoyo_del_condition
  - security/tomoyo/gc.c:tomoyo_del_condition
  - security/tomoyo/gc.c:tomoyo_del_acl
```
```
In security/tomoyo/group.c (ffffffff81475e6f)
Location: security/tomoyo/common.h:1178
Inline: True
Inline callers:
  - security/tomoyo/group.c:tomoyo_write_group
```
```
In security/tomoyo/memory.c (ffffffff814764d5)
Location: security/tomoyo/common.h:1178
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_group
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
In security/tomoyo/common.c (ffffffff81486b5a)
Location: security/tomoyo/common.h:1178
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_task
  - security/tomoyo/common.c:tomoyo_write_manager
  - security/tomoyo/common.c:tomoyo_write_profile
```
```
In security/tomoyo/condition.c (ffffffff8148af8d)
Location: security/tomoyo/common.h:1178
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_get_condition
```
```
In security/tomoyo/domain.c (ffffffff8148cb7c)
Location: security/tomoyo/common.h:1178
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_write_aggregator
  - security/tomoyo/domain.c:tomoyo_write_aggregator
  - security/tomoyo/domain.c:tomoyo_write_transition_control
  - security/tomoyo/domain.c:tomoyo_write_transition_control
```
```
In security/tomoyo/environ.c (ffffffff8148d8fc)
Location: security/tomoyo/common.h:1178
Inline: True
Inline callers:
  - security/tomoyo/environ.c:tomoyo_write_misc
```
```
In security/tomoyo/file.c (ffffffff8148dcd9)
Location: security/tomoyo/common.h:1178
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_put_name_union
```
```
In security/tomoyo/gc.c (ffffffff8148f2dd)
Location: security/tomoyo/common.h:1178
Inline: True
Inline callers:
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/gc.c:tomoyo_del_condition
  - security/tomoyo/gc.c:tomoyo_del_condition
  - security/tomoyo/gc.c:tomoyo_del_condition
  - security/tomoyo/gc.c:tomoyo_del_acl
```
```
In security/tomoyo/group.c (ffffffff8148fc0f)
Location: security/tomoyo/common.h:1178
Inline: True
Inline callers:
  - security/tomoyo/group.c:tomoyo_write_group
```
```
In security/tomoyo/memory.c (ffffffff81490275)
Location: security/tomoyo/common.h:1178
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_group
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
In security/tomoyo/common.c (ffffffff814dd53a)
Location: security/tomoyo/common.h:1178
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_task
  - security/tomoyo/common.c:tomoyo_update_manager_entry
  - security/tomoyo/common.c:tomoyo_write_profile
```
```
In security/tomoyo/condition.c (ffffffff814e226f)
Location: security/tomoyo/common.h:1178
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_parse_envp
```
```
In security/tomoyo/domain.c (ffffffff814e3e5a)
Location: security/tomoyo/common.h:1178
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_write_aggregator
  - security/tomoyo/domain.c:tomoyo_write_aggregator
  - security/tomoyo/domain.c:tomoyo_write_transition_control
  - security/tomoyo/domain.c:tomoyo_write_transition_control
```
```
In security/tomoyo/environ.c (ffffffff814e49e5)
Location: security/tomoyo/common.h:1178
Inline: True
Inline callers:
  - security/tomoyo/environ.c:tomoyo_write_env
```
```
In security/tomoyo/file.c (ffffffff814e50e9)
Location: security/tomoyo/common.h:1178
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_put_name_union
```
```
In security/tomoyo/gc.c (ffffffff814e66a4)
Location: security/tomoyo/common.h:1178
Inline: True
Inline callers:
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/gc.c:tomoyo_del_condition
  - security/tomoyo/gc.c:tomoyo_del_condition
  - security/tomoyo/gc.c:tomoyo_del_condition
  - security/tomoyo/gc.c:tomoyo_del_acl
```
```
In security/tomoyo/group.c (ffffffff814e6f2f)
Location: security/tomoyo/common.h:1178
Inline: True
Inline callers:
  - security/tomoyo/group.c:tomoyo_write_group
```
```
In security/tomoyo/memory.c (ffffffff814e75d2)
Location: security/tomoyo/common.h:1178
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_group
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
In security/tomoyo/common.c (ffffffff814fa95a)
Location: security/tomoyo/common.h:1178
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_task
  - security/tomoyo/common.c:tomoyo_update_manager_entry
  - security/tomoyo/common.c:tomoyo_write_profile
```
```
In security/tomoyo/condition.c (ffffffff814ff5ef)
Location: security/tomoyo/common.h:1178
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_parse_envp
```
```
In security/tomoyo/domain.c (ffffffff8150128a)
Location: security/tomoyo/common.h:1178
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_write_aggregator
  - security/tomoyo/domain.c:tomoyo_write_aggregator
  - security/tomoyo/domain.c:tomoyo_write_transition_control
  - security/tomoyo/domain.c:tomoyo_write_transition_control
```
```
In security/tomoyo/environ.c (ffffffff81501de5)
Location: security/tomoyo/common.h:1178
Inline: True
Inline callers:
  - security/tomoyo/environ.c:tomoyo_write_env
```
```
In security/tomoyo/file.c (ffffffff815024e9)
Location: security/tomoyo/common.h:1178
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_put_name_union
```
```
In security/tomoyo/gc.c (ffffffff81503aa4)
Location: security/tomoyo/common.h:1178
Inline: True
Inline callers:
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/gc.c:tomoyo_del_condition
  - security/tomoyo/gc.c:tomoyo_del_condition
  - security/tomoyo/gc.c:tomoyo_del_condition
  - security/tomoyo/gc.c:tomoyo_del_acl
```
```
In security/tomoyo/group.c (ffffffff8150433f)
Location: security/tomoyo/common.h:1178
Inline: True
Inline callers:
  - security/tomoyo/group.c:tomoyo_write_group
```
```
In security/tomoyo/memory.c (ffffffff815049a2)
Location: security/tomoyo/common.h:1178
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_group
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
In security/tomoyo/common.c (ffffffff8150155a)
Location: security/tomoyo/common.h:1178
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_task
  - security/tomoyo/common.c:tomoyo_write_manager
  - security/tomoyo/common.c:tomoyo_write_profile
```
```
In security/tomoyo/condition.c (ffffffff8150671f)
Location: security/tomoyo/common.h:1178
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_get_condition
```
```
In security/tomoyo/domain.c (ffffffff81507d1c)
Location: security/tomoyo/common.h:1178
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_write_aggregator
  - security/tomoyo/domain.c:tomoyo_write_aggregator
  - security/tomoyo/domain.c:tomoyo_write_transition_control
  - security/tomoyo/domain.c:tomoyo_write_transition_control
```
```
In security/tomoyo/environ.c (ffffffff81508a8c)
Location: security/tomoyo/common.h:1178
Inline: True
Inline callers:
  - security/tomoyo/environ.c:tomoyo_write_misc
```
```
In security/tomoyo/file.c (ffffffff815090b9)
Location: security/tomoyo/common.h:1178
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_put_name_union
```
```
In security/tomoyo/gc.c (ffffffff8150a549)
Location: security/tomoyo/common.h:1178
Inline: True
Inline callers:
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/gc.c:tomoyo_del_condition
  - security/tomoyo/gc.c:tomoyo_del_condition
  - security/tomoyo/gc.c:tomoyo_del_condition
  - security/tomoyo/gc.c:tomoyo_del_acl
```
```
In security/tomoyo/group.c (ffffffff8150aebf)
Location: security/tomoyo/common.h:1178
Inline: True
Inline callers:
  - security/tomoyo/group.c:tomoyo_write_group
```
```
In security/tomoyo/memory.c (ffffffff8150b528)
Location: security/tomoyo/common.h:1178
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_group
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
In security/tomoyo/common.c (ffffffff8155cb7a)
Location: security/tomoyo/common.h:1178
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_task
  - security/tomoyo/common.c:tomoyo_write_profile
```
```
In security/tomoyo/condition.c (ffffffff8156361f)
Location: security/tomoyo/common.h:1178
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_get_condition
```
```
In security/tomoyo/domain.c (ffffffff81564f29)
Location: security/tomoyo/common.h:1178
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_write_aggregator
  - security/tomoyo/domain.c:tomoyo_write_aggregator
  - security/tomoyo/domain.c:tomoyo_write_transition_control
  - security/tomoyo/domain.c:tomoyo_write_transition_control
```
```
In security/tomoyo/environ.c (ffffffff81565d0c)
Location: security/tomoyo/common.h:1178
Inline: True
Inline callers:
  - security/tomoyo/environ.c:tomoyo_write_misc
```
```
In security/tomoyo/file.c (ffffffff815663f9)
Location: security/tomoyo/common.h:1178
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_put_name_union
```
```
In security/tomoyo/gc.c (ffffffff81567bd9)
Location: security/tomoyo/common.h:1178
Inline: True
Inline callers:
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/gc.c:tomoyo_del_condition
  - security/tomoyo/gc.c:tomoyo_del_condition
  - security/tomoyo/gc.c:tomoyo_del_condition
  - security/tomoyo/gc.c:tomoyo_del_acl
```
```
In security/tomoyo/group.c (ffffffff8156865f)
Location: security/tomoyo/common.h:1178
Inline: True
Inline callers:
  - security/tomoyo/group.c:tomoyo_write_group
```
```
In security/tomoyo/memory.c (ffffffff81568d84)
Location: security/tomoyo/common.h:1178
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_group
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
In security/tomoyo/common.c (ffffffff815f7c87)
Location: security/tomoyo/common.h:1177
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_task
  - security/tomoyo/common.c:tomoyo_write_profile
```
```
In security/tomoyo/condition.c (ffffffff815fe757)
Location: security/tomoyo/common.h:1177
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_get_condition
```
```
In security/tomoyo/domain.c (ffffffff816006e5)
Location: security/tomoyo/common.h:1177
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_write_aggregator
  - security/tomoyo/domain.c:tomoyo_write_aggregator
  - security/tomoyo/domain.c:tomoyo_write_transition_control
  - security/tomoyo/domain.c:tomoyo_write_transition_control
```
```
In security/tomoyo/environ.c (ffffffff816015ab)
Location: security/tomoyo/common.h:1177
Inline: True
Inline callers:
  - security/tomoyo/environ.c:tomoyo_write_misc
```
```
In security/tomoyo/file.c (ffffffff81601dd9)
Location: security/tomoyo/common.h:1177
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_put_name_union
```
```
In security/tomoyo/gc.c (ffffffff816037f5)
Location: security/tomoyo/common.h:1177
Inline: True
Inline callers:
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/gc.c:tomoyo_del_condition
  - security/tomoyo/gc.c:tomoyo_del_condition
  - security/tomoyo/gc.c:tomoyo_del_condition
  - security/tomoyo/gc.c:tomoyo_del_acl
```
```
In security/tomoyo/group.c (ffffffff816042db)
Location: security/tomoyo/common.h:1177
Inline: True
Inline callers:
  - security/tomoyo/group.c:tomoyo_write_group
```
```
In security/tomoyo/memory.c (ffffffff81604ac5)
Location: security/tomoyo/common.h:1177
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_group
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
In security/tomoyo/common.c (ffffffff816a88a7)
Location: security/tomoyo/common.h:1177
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_task
  - security/tomoyo/common.c:tomoyo_write_profile
```
```
In security/tomoyo/condition.c (ffffffff816af5d7)
Location: security/tomoyo/common.h:1177
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_get_condition
```
```
In security/tomoyo/domain.c (ffffffff816b1625)
Location: security/tomoyo/common.h:1177
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_write_aggregator
  - security/tomoyo/domain.c:tomoyo_write_aggregator
  - security/tomoyo/domain.c:tomoyo_write_transition_control
  - security/tomoyo/domain.c:tomoyo_write_transition_control
```
```
In security/tomoyo/environ.c (ffffffff816b255b)
Location: security/tomoyo/common.h:1177
Inline: True
Inline callers:
  - security/tomoyo/environ.c:tomoyo_write_misc
```
```
In security/tomoyo/file.c (ffffffff816b2e99)
Location: security/tomoyo/common.h:1177
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_put_name_union
```
```
In security/tomoyo/gc.c (ffffffff816b49b5)
Location: security/tomoyo/common.h:1177
Inline: True
Inline callers:
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/gc.c:tomoyo_del_condition
  - security/tomoyo/gc.c:tomoyo_del_condition
  - security/tomoyo/gc.c:tomoyo_del_condition
  - security/tomoyo/gc.c:tomoyo_del_acl
```
```
In security/tomoyo/group.c (ffffffff816b550b)
Location: security/tomoyo/common.h:1177
Inline: True
Inline callers:
  - security/tomoyo/group.c:tomoyo_write_group
```
```
In security/tomoyo/memory.c (ffffffff816b5dc5)
Location: security/tomoyo/common.h:1177
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_group
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
In security/tomoyo/common.c (ffffffff816e12e7)
Location: security/tomoyo/common.h:1177
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_task
  - security/tomoyo/common.c:tomoyo_write_profile
```
```
In security/tomoyo/condition.c (ffffffff816e7ff8)
Location: security/tomoyo/common.h:1177
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_get_condition
```
```
In security/tomoyo/domain.c (ffffffff816ea035)
Location: security/tomoyo/common.h:1177
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_write_aggregator
  - security/tomoyo/domain.c:tomoyo_write_aggregator
  - security/tomoyo/domain.c:tomoyo_write_transition_control
  - security/tomoyo/domain.c:tomoyo_write_transition_control
```
```
In security/tomoyo/environ.c (ffffffff816eaf4b)
Location: security/tomoyo/common.h:1177
Inline: True
Inline callers:
  - security/tomoyo/environ.c:tomoyo_write_misc
```
```
In security/tomoyo/file.c (ffffffff816eb869)
Location: security/tomoyo/common.h:1177
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_put_name_union
```
```
In security/tomoyo/gc.c (ffffffff816ed47d)
Location: security/tomoyo/common.h:1177
Inline: True
Inline callers:
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/gc.c:tomoyo_del_condition
  - security/tomoyo/gc.c:tomoyo_del_condition
  - security/tomoyo/gc.c:tomoyo_del_condition
  - security/tomoyo/gc.c:tomoyo_del_acl
```
```
In security/tomoyo/group.c (ffffffff816edeeb)
Location: security/tomoyo/common.h:1177
Inline: True
Inline callers:
  - security/tomoyo/group.c:tomoyo_write_group
```
```
In security/tomoyo/memory.c (ffffffff816ee7d5)
Location: security/tomoyo/common.h:1177
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_group
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
In security/tomoyo/common.c (ffffffff8171df67)
Location: security/tomoyo/common.h:1175
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_task
  - security/tomoyo/common.c:tomoyo_write_profile
```
```
In security/tomoyo/condition.c (ffffffff81724d08)
Location: security/tomoyo/common.h:1175
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_get_condition
```
```
In security/tomoyo/domain.c (ffffffff81726d45)
Location: security/tomoyo/common.h:1175
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_write_aggregator
  - security/tomoyo/domain.c:tomoyo_write_aggregator
  - security/tomoyo/domain.c:tomoyo_write_transition_control
  - security/tomoyo/domain.c:tomoyo_write_transition_control
```
```
In security/tomoyo/environ.c (ffffffff81727d1b)
Location: security/tomoyo/common.h:1175
Inline: True
Inline callers:
  - security/tomoyo/environ.c:tomoyo_write_misc
```
```
In security/tomoyo/file.c (ffffffff81728639)
Location: security/tomoyo/common.h:1175
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_put_name_union
```
```
In security/tomoyo/gc.c (ffffffff8172a24d)
Location: security/tomoyo/common.h:1175
Inline: True
Inline callers:
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/gc.c:tomoyo_del_condition
  - security/tomoyo/gc.c:tomoyo_del_condition
  - security/tomoyo/gc.c:tomoyo_del_condition
  - security/tomoyo/gc.c:tomoyo_del_acl
```
```
In security/tomoyo/group.c (ffffffff8172acbb)
Location: security/tomoyo/common.h:1175
Inline: True
Inline callers:
  - security/tomoyo/group.c:tomoyo_write_group
```
```
In security/tomoyo/memory.c (ffffffff8172b5a5)
Location: security/tomoyo/common.h:1175
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_group
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
In security/tomoyo/common.c (ffff80001057b5ac)
Location: security/tomoyo/common.h:1178
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_task
  - security/tomoyo/common.c:tomoyo_write_manager
  - security/tomoyo/common.c:tomoyo_write_profile
```
```
In security/tomoyo/condition.c (ffff80001057e64c)
Location: security/tomoyo/common.h:1178
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_get_condition
```
```
In security/tomoyo/domain.c (ffff800010580060)
Location: security/tomoyo/common.h:1178
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_write_aggregator
  - security/tomoyo/domain.c:tomoyo_write_aggregator
  - security/tomoyo/domain.c:tomoyo_write_transition_control
  - security/tomoyo/domain.c:tomoyo_write_transition_control
```
```
In security/tomoyo/environ.c (ffff800010580db0)
Location: security/tomoyo/common.h:1178
Inline: True
Inline callers:
  - security/tomoyo/environ.c:tomoyo_write_misc
```
```
In security/tomoyo/file.c (ffff800010581484)
Location: security/tomoyo/common.h:1178
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_put_name_union
```
```
In security/tomoyo/gc.c (ffff800010582e8c)
Location: security/tomoyo/common.h:1178
Inline: True
Inline callers:
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/gc.c:tomoyo_del_condition
  - security/tomoyo/gc.c:tomoyo_del_condition
  - security/tomoyo/gc.c:tomoyo_del_condition
  - security/tomoyo/gc.c:tomoyo_del_acl
```
```
In security/tomoyo/group.c (ffff800010583c28)
Location: security/tomoyo/common.h:1178
Inline: True
Inline callers:
  - security/tomoyo/group.c:tomoyo_write_group
```
```
In security/tomoyo/memory.c (ffff800010584438)
Location: security/tomoyo/common.h:1178
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_group
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
In security/tomoyo/common.c (c072c104)
Location: security/tomoyo/common.h:1178
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_task
  - security/tomoyo/common.c:tomoyo_write_manager
  - security/tomoyo/common.c:tomoyo_write_profile
```
```
In security/tomoyo/condition.c (c0730a68)
Location: security/tomoyo/common.h:1178
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_get_condition
```
```
In security/tomoyo/domain.c (c073253c)
Location: security/tomoyo/common.h:1178
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_write_aggregator
  - security/tomoyo/domain.c:tomoyo_write_aggregator
  - security/tomoyo/domain.c:tomoyo_write_transition_control
  - security/tomoyo/domain.c:tomoyo_write_transition_control
```
```
In security/tomoyo/environ.c (c07331dc)
Location: security/tomoyo/common.h:1178
Inline: True
Inline callers:
  - security/tomoyo/environ.c:tomoyo_write_misc
```
```
In security/tomoyo/file.c (c0733744)
Location: security/tomoyo/common.h:1178
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_put_name_union
```
```
In security/tomoyo/gc.c (c0734dd0)
Location: security/tomoyo/common.h:1178
Inline: True
Inline callers:
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/gc.c:tomoyo_del_condition
  - security/tomoyo/gc.c:tomoyo_del_condition
  - security/tomoyo/gc.c:tomoyo_del_condition
  - security/tomoyo/gc.c:tomoyo_del_acl
```
```
In security/tomoyo/group.c (c0735808)
Location: security/tomoyo/common.h:1178
Inline: True
Inline callers:
  - security/tomoyo/group.c:tomoyo_write_group
```
```
In security/tomoyo/memory.c (c0735ec8)
Location: security/tomoyo/common.h:1178
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_group
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
In security/tomoyo/common.c (c0000000006e338c)
Location: security/tomoyo/common.h:1178
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_task
  - security/tomoyo/common.c:tomoyo_write_manager
  - security/tomoyo/common.c:tomoyo_write_profile
```
```
In security/tomoyo/condition.c (c0000000006eb3f0)
Location: security/tomoyo/common.h:1178
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_get_condition
```
```
In security/tomoyo/domain.c (c0000000006ed7ec)
Location: security/tomoyo/common.h:1178
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_write_aggregator
  - security/tomoyo/domain.c:tomoyo_write_aggregator
  - security/tomoyo/domain.c:tomoyo_write_transition_control
  - security/tomoyo/domain.c:tomoyo_write_transition_control
```
```
In security/tomoyo/environ.c (c0000000006ef2b0)
Location: security/tomoyo/common.h:1178
Inline: True
Inline callers:
  - security/tomoyo/environ.c:tomoyo_write_misc
```
```
In security/tomoyo/file.c (c0000000006f1140)
Location: security/tomoyo/common.h:1178
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_update_mount_acl
  - security/tomoyo/file.c:tomoyo_update_mount_acl
  - security/tomoyo/file.c:tomoyo_update_mount_acl
  - security/tomoyo/file.c:tomoyo_update_mkdev_acl
```
```
In security/tomoyo/gc.c (c0000000006f1a74)
Location: security/tomoyo/common.h:1178
Inline: True
Inline callers:
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/gc.c:tomoyo_del_condition
  - security/tomoyo/gc.c:tomoyo_del_condition
  - security/tomoyo/gc.c:tomoyo_del_condition
  - security/tomoyo/gc.c:tomoyo_del_acl
```
```
In security/tomoyo/group.c (c0000000006f2910)
Location: security/tomoyo/common.h:1178
Inline: True
Inline callers:
  - security/tomoyo/group.c:tomoyo_write_group
```
```
In security/tomoyo/memory.c (c0000000006f3680)
Location: security/tomoyo/common.h:1178
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_group
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
In security/tomoyo/common.c (ffffffe0003cb394)
Location: security/tomoyo/common.h:1178
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_task
  - security/tomoyo/common.c:tomoyo_write_manager
  - security/tomoyo/common.c:tomoyo_write_profile
```
```
In security/tomoyo/condition.c (ffffffe0003cf738)
Location: security/tomoyo/common.h:1178
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_get_condition
```
```
In security/tomoyo/domain.c (ffffffe0003d0ca2)
Location: security/tomoyo/common.h:1178
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_write_aggregator
  - security/tomoyo/domain.c:tomoyo_write_aggregator
  - security/tomoyo/domain.c:tomoyo_write_transition_control
  - security/tomoyo/domain.c:tomoyo_write_transition_control
```
```
In security/tomoyo/environ.c (ffffffe0003d17be)
Location: security/tomoyo/common.h:1178
Inline: True
Inline callers:
  - security/tomoyo/environ.c:tomoyo_write_misc
```
```
In security/tomoyo/file.c (ffffffe0003d2c16)
Location: security/tomoyo/common.h:1178
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_write_file
  - security/tomoyo/file.c:tomoyo_update_mount_acl
  - security/tomoyo/file.c:tomoyo_update_mount_acl
  - security/tomoyo/file.c:tomoyo_update_mount_acl
  - security/tomoyo/file.c:tomoyo_update_mkdev_acl
```
```
In security/tomoyo/gc.c (ffffffe0003d31fe)
Location: security/tomoyo/common.h:1178
Inline: True
Inline callers:
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/gc.c:tomoyo_del_condition
  - security/tomoyo/gc.c:tomoyo_del_condition
  - security/tomoyo/gc.c:tomoyo_del_condition
  - security/tomoyo/gc.c:tomoyo_del_acl
```
```
In security/tomoyo/group.c (ffffffe0003d3dfc)
Location: security/tomoyo/common.h:1178
Inline: True
Inline callers:
  - security/tomoyo/group.c:tomoyo_write_group
```
```
In security/tomoyo/memory.c (ffffffe0003d447c)
Location: security/tomoyo/common.h:1178
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_group
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
In security/tomoyo/common.c (ffffffff8147f13a)
Location: security/tomoyo/common.h:1178
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_task
  - security/tomoyo/common.c:tomoyo_write_manager
  - security/tomoyo/common.c:tomoyo_write_profile
```
```
In security/tomoyo/condition.c (ffffffff8148356d)
Location: security/tomoyo/common.h:1178
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_get_condition
```
```
In security/tomoyo/domain.c (ffffffff8148515c)
Location: security/tomoyo/common.h:1178
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_write_aggregator
  - security/tomoyo/domain.c:tomoyo_write_aggregator
  - security/tomoyo/domain.c:tomoyo_write_transition_control
  - security/tomoyo/domain.c:tomoyo_write_transition_control
```
```
In security/tomoyo/environ.c (ffffffff81485edc)
Location: security/tomoyo/common.h:1178
Inline: True
Inline callers:
  - security/tomoyo/environ.c:tomoyo_write_misc
```
```
In security/tomoyo/file.c (ffffffff814862b9)
Location: security/tomoyo/common.h:1178
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_put_name_union
```
```
In security/tomoyo/gc.c (ffffffff814878bd)
Location: security/tomoyo/common.h:1178
Inline: True
Inline callers:
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/gc.c:tomoyo_del_condition
  - security/tomoyo/gc.c:tomoyo_del_condition
  - security/tomoyo/gc.c:tomoyo_del_condition
  - security/tomoyo/gc.c:tomoyo_del_acl
```
```
In security/tomoyo/group.c (ffffffff814881ef)
Location: security/tomoyo/common.h:1178
Inline: True
Inline callers:
  - security/tomoyo/group.c:tomoyo_write_group
```
```
In security/tomoyo/memory.c (ffffffff81488855)
Location: security/tomoyo/common.h:1178
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_group
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
In security/tomoyo/common.c (ffffffff8146fb5a)
Location: security/tomoyo/common.h:1178
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_task
  - security/tomoyo/common.c:tomoyo_write_manager
  - security/tomoyo/common.c:tomoyo_write_profile
```
```
In security/tomoyo/condition.c (ffffffff81473f8d)
Location: security/tomoyo/common.h:1178
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_get_condition
```
```
In security/tomoyo/domain.c (ffffffff81475b7c)
Location: security/tomoyo/common.h:1178
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_write_aggregator
  - security/tomoyo/domain.c:tomoyo_write_aggregator
  - security/tomoyo/domain.c:tomoyo_write_transition_control
  - security/tomoyo/domain.c:tomoyo_write_transition_control
```
```
In security/tomoyo/environ.c (ffffffff814768fc)
Location: security/tomoyo/common.h:1178
Inline: True
Inline callers:
  - security/tomoyo/environ.c:tomoyo_write_misc
```
```
In security/tomoyo/file.c (ffffffff81476cd9)
Location: security/tomoyo/common.h:1178
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_put_name_union
```
```
In security/tomoyo/gc.c (ffffffff814782dd)
Location: security/tomoyo/common.h:1178
Inline: True
Inline callers:
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/gc.c:tomoyo_del_condition
  - security/tomoyo/gc.c:tomoyo_del_condition
  - security/tomoyo/gc.c:tomoyo_del_condition
  - security/tomoyo/gc.c:tomoyo_del_acl
```
```
In security/tomoyo/group.c (ffffffff81478c0f)
Location: security/tomoyo/common.h:1178
Inline: True
Inline callers:
  - security/tomoyo/group.c:tomoyo_write_group
```
```
In security/tomoyo/memory.c (ffffffff81479275)
Location: security/tomoyo/common.h:1178
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_group
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
In security/tomoyo/common.c (ffffffff8147b1da)
Location: security/tomoyo/common.h:1178
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_task
  - security/tomoyo/common.c:tomoyo_write_manager
  - security/tomoyo/common.c:tomoyo_write_profile
```
```
In security/tomoyo/condition.c (ffffffff8147f60d)
Location: security/tomoyo/common.h:1178
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_get_condition
```
```
In security/tomoyo/domain.c (ffffffff814811fc)
Location: security/tomoyo/common.h:1178
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_write_aggregator
  - security/tomoyo/domain.c:tomoyo_write_aggregator
  - security/tomoyo/domain.c:tomoyo_write_transition_control
  - security/tomoyo/domain.c:tomoyo_write_transition_control
```
```
In security/tomoyo/environ.c (ffffffff81481f7c)
Location: security/tomoyo/common.h:1178
Inline: True
Inline callers:
  - security/tomoyo/environ.c:tomoyo_write_misc
```
```
In security/tomoyo/file.c (ffffffff81482359)
Location: security/tomoyo/common.h:1178
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_put_name_union
```
```
In security/tomoyo/gc.c (ffffffff8148395d)
Location: security/tomoyo/common.h:1178
Inline: True
Inline callers:
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/gc.c:tomoyo_del_condition
  - security/tomoyo/gc.c:tomoyo_del_condition
  - security/tomoyo/gc.c:tomoyo_del_condition
  - security/tomoyo/gc.c:tomoyo_del_acl
```
```
In security/tomoyo/group.c (ffffffff8148428f)
Location: security/tomoyo/common.h:1178
Inline: True
Inline callers:
  - security/tomoyo/group.c:tomoyo_write_group
```
```
In security/tomoyo/memory.c (ffffffff814848f5)
Location: security/tomoyo/common.h:1178
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_group
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
In security/tomoyo/common.c (ffffffff81492dca)
Location: security/tomoyo/common.h:1178
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_task
  - security/tomoyo/common.c:tomoyo_write_manager
  - security/tomoyo/common.c:tomoyo_write_profile
```
```
In security/tomoyo/condition.c (ffffffff8149713d)
Location: security/tomoyo/common.h:1178
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_get_condition
```
```
In security/tomoyo/domain.c (ffffffff81498d6c)
Location: security/tomoyo/common.h:1178
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_write_aggregator
  - security/tomoyo/domain.c:tomoyo_write_aggregator
  - security/tomoyo/domain.c:tomoyo_write_transition_control
  - security/tomoyo/domain.c:tomoyo_write_transition_control
```
```
In security/tomoyo/environ.c (ffffffff81499b0c)
Location: security/tomoyo/common.h:1178
Inline: True
Inline callers:
  - security/tomoyo/environ.c:tomoyo_write_misc
```
```
In security/tomoyo/file.c (ffffffff81499ee9)
Location: security/tomoyo/common.h:1178
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_put_name_union
```
```
In security/tomoyo/gc.c (ffffffff8149b506)
Location: security/tomoyo/common.h:1178
Inline: True
Inline callers:
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/gc.c:tomoyo_del_condition
  - security/tomoyo/gc.c:tomoyo_del_condition
  - security/tomoyo/gc.c:tomoyo_del_condition
  - security/tomoyo/gc.c:tomoyo_del_acl
```
```
In security/tomoyo/group.c (ffffffff8149bdcf)
Location: security/tomoyo/common.h:1178
Inline: True
Inline callers:
  - security/tomoyo/group.c:tomoyo_write_group
```
```
In security/tomoyo/memory.c (ffffffff8149c435)
Location: security/tomoyo/common.h:1178
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_group
```
</details>
</li>
</ul>

## Differences
