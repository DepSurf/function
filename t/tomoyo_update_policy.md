# Function: <code>tomoyo_update_policy</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int tomoyo_update_policy(struct tomoyo_acl_head *new_entry, const int size, struct tomoyo_acl_param *param, bool (*check_duplicate)(const struct tomoyo_acl_head *, const struct tomoyo_acl_head *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/domain.c (ffffffff8136d4b0)
Location: security/tomoyo/domain.c:28
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_manager
  - security/tomoyo/domain.c:tomoyo_write_transition_control
  - security/tomoyo/domain.c:tomoyo_write_aggregator
  - security/tomoyo/group.c:tomoyo_write_group
  - security/tomoyo/group.c:tomoyo_write_group
  - security/tomoyo/group.c:tomoyo_write_group
```
**Symbols:**

```
ffffffff8136d4b0-ffffffff8136d579: tomoyo_update_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int tomoyo_update_policy(struct tomoyo_acl_head *new_entry, const int size, struct tomoyo_acl_param *param, bool (*check_duplicate)(const struct tomoyo_acl_head *, const struct tomoyo_acl_head *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/domain.c (ffffffff813a36f0)
Location: security/tomoyo/domain.c:28
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_manager
  - security/tomoyo/domain.c:tomoyo_write_aggregator
  - security/tomoyo/domain.c:tomoyo_write_transition_control
  - security/tomoyo/group.c:tomoyo_write_group
  - security/tomoyo/group.c:tomoyo_write_group
  - security/tomoyo/group.c:tomoyo_write_group
```
**Symbols:**

```
ffffffff813a36f0-ffffffff813a37c9: tomoyo_update_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int tomoyo_update_policy(struct tomoyo_acl_head *new_entry, const int size, struct tomoyo_acl_param *param, bool (*check_duplicate)(const struct tomoyo_acl_head *, const struct tomoyo_acl_head *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/domain.c (ffffffff813ba270)
Location: security/tomoyo/domain.c:28
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_manager
  - security/tomoyo/domain.c:tomoyo_write_aggregator
  - security/tomoyo/domain.c:tomoyo_write_transition_control
  - security/tomoyo/group.c:tomoyo_write_group
  - security/tomoyo/group.c:tomoyo_write_group
  - security/tomoyo/group.c:tomoyo_write_group
```
**Symbols:**

```
ffffffff813ba270-ffffffff813ba349: tomoyo_update_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int tomoyo_update_policy(struct tomoyo_acl_head *new_entry, const int size, struct tomoyo_acl_param *param, bool (*check_duplicate)(const struct tomoyo_acl_head *, const struct tomoyo_acl_head *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/domain.c (ffffffff813d0ae0)
Location: security/tomoyo/domain.c:30
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_manager
  - security/tomoyo/domain.c:tomoyo_write_aggregator
  - security/tomoyo/domain.c:tomoyo_write_transition_control
  - security/tomoyo/group.c:tomoyo_write_group
  - security/tomoyo/group.c:tomoyo_write_group
  - security/tomoyo/group.c:tomoyo_write_group
```
**Symbols:**

```
ffffffff813d0ae0-ffffffff813d0bb6: tomoyo_update_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int tomoyo_update_policy(struct tomoyo_acl_head *new_entry, const int size, struct tomoyo_acl_param *param, bool (*check_duplicate)(const struct tomoyo_acl_head *, const struct tomoyo_acl_head *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/domain.c (ffffffff813f6f80)
Location: security/tomoyo/domain.c:31
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_manager
  - security/tomoyo/domain.c:tomoyo_write_aggregator
  - security/tomoyo/domain.c:tomoyo_write_transition_control
  - security/tomoyo/group.c:tomoyo_write_group
  - security/tomoyo/group.c:tomoyo_write_group
  - security/tomoyo/group.c:tomoyo_write_group
```
**Symbols:**

```
ffffffff813f6f80-ffffffff813f7059: tomoyo_update_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int tomoyo_update_policy(struct tomoyo_acl_head *new_entry, const int size, struct tomoyo_acl_param *param, bool (*check_duplicate)(const struct tomoyo_acl_head *, const struct tomoyo_acl_head *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/domain.c (ffffffff81427f40)
Location: security/tomoyo/domain.c:31
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_manager
  - security/tomoyo/domain.c:tomoyo_write_aggregator
  - security/tomoyo/domain.c:tomoyo_write_transition_control
  - security/tomoyo/group.c:tomoyo_write_group
  - security/tomoyo/group.c:tomoyo_write_group
  - security/tomoyo/group.c:tomoyo_write_group
```
**Symbols:**

```
ffffffff81427f40-ffffffff81428019: tomoyo_update_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int tomoyo_update_policy(struct tomoyo_acl_head *new_entry, const int size, struct tomoyo_acl_param *param, bool (*check_duplicate)(const struct tomoyo_acl_head *, const struct tomoyo_acl_head *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/domain.c (ffffffff814447f0)
Location: security/tomoyo/domain.c:31
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_manager
  - security/tomoyo/domain.c:tomoyo_write_aggregator
  - security/tomoyo/domain.c:tomoyo_write_transition_control
  - security/tomoyo/group.c:tomoyo_write_group
  - security/tomoyo/group.c:tomoyo_write_group
  - security/tomoyo/group.c:tomoyo_write_group
```
**Symbols:**

```
ffffffff814447f0-ffffffff814448c9: tomoyo_update_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int tomoyo_update_policy(struct tomoyo_acl_head *new_entry, const int size, struct tomoyo_acl_param *param, bool (*check_duplicate)(const struct tomoyo_acl_head *, const struct tomoyo_acl_head *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/domain.c (ffffffff814724e0)
Location: security/tomoyo/domain.c:31
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_manager
  - security/tomoyo/domain.c:tomoyo_write_aggregator
  - security/tomoyo/domain.c:tomoyo_write_transition_control
  - security/tomoyo/group.c:tomoyo_write_group
  - security/tomoyo/group.c:tomoyo_write_group
  - security/tomoyo/group.c:tomoyo_write_group
```
**Symbols:**

```
ffffffff814724e0-ffffffff814725b9: tomoyo_update_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int tomoyo_update_policy(struct tomoyo_acl_head *new_entry, const int size, struct tomoyo_acl_param *param, bool (*check_duplicate)(const struct tomoyo_acl_head *, const struct tomoyo_acl_head *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/domain.c (ffffffff8148c280)
Location: security/tomoyo/domain.c:31
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_manager
  - security/tomoyo/domain.c:tomoyo_write_aggregator
  - security/tomoyo/domain.c:tomoyo_write_transition_control
  - security/tomoyo/group.c:tomoyo_write_group
  - security/tomoyo/group.c:tomoyo_write_group
  - security/tomoyo/group.c:tomoyo_write_group
```
**Symbols:**

```
ffffffff8148c280-ffffffff8148c359: tomoyo_update_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int tomoyo_update_policy(struct tomoyo_acl_head *new_entry, const int size, struct tomoyo_acl_param *param, bool (*check_duplicate)(const struct tomoyo_acl_head *, const struct tomoyo_acl_head *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/domain.c (ffffffff814e3520)
Location: security/tomoyo/domain.c:31
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_update_manager_entry
  - security/tomoyo/domain.c:tomoyo_write_aggregator
  - security/tomoyo/domain.c:tomoyo_write_transition_control
  - security/tomoyo/group.c:tomoyo_write_group
  - security/tomoyo/group.c:tomoyo_write_group
  - security/tomoyo/group.c:tomoyo_write_group
```
**Symbols:**

```
ffffffff814e3520-ffffffff814e35f9: tomoyo_update_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int tomoyo_update_policy(struct tomoyo_acl_head *new_entry, const int size, struct tomoyo_acl_param *param, bool (*check_duplicate)(const struct tomoyo_acl_head *, const struct tomoyo_acl_head *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/domain.c (ffffffff81500950)
Location: security/tomoyo/domain.c:31
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_update_manager_entry
  - security/tomoyo/domain.c:tomoyo_write_aggregator
  - security/tomoyo/domain.c:tomoyo_write_transition_control
  - security/tomoyo/group.c:tomoyo_write_group
  - security/tomoyo/group.c:tomoyo_write_group
  - security/tomoyo/group.c:tomoyo_write_group
```
**Symbols:**

```
ffffffff81500950-ffffffff81500a29: tomoyo_update_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int tomoyo_update_policy(struct tomoyo_acl_head *new_entry, const int size, struct tomoyo_acl_param *param, bool (*check_duplicate)(const struct tomoyo_acl_head *, const struct tomoyo_acl_head *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/domain.c (ffffffff815073e0)
Location: security/tomoyo/domain.c:31
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_manager
  - security/tomoyo/domain.c:tomoyo_write_aggregator
  - security/tomoyo/domain.c:tomoyo_write_transition_control
  - security/tomoyo/group.c:tomoyo_write_group
  - security/tomoyo/group.c:tomoyo_write_group
  - security/tomoyo/group.c:tomoyo_write_group
```
**Symbols:**

```
ffffffff815073e0-ffffffff815074b9: tomoyo_update_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int tomoyo_update_policy(struct tomoyo_acl_head *new_entry, const int size, struct tomoyo_acl_param *param, bool (*check_duplicate)(const struct tomoyo_acl_head *, const struct tomoyo_acl_head *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/tomoyo/domain.c (0)
Location: security/tomoyo/domain.c:31
Inline: False
Direct callers:
  - security/tomoyo/domain.c:tomoyo_write_aggregator
  - security/tomoyo/domain.c:tomoyo_write_transition_control
  - security/tomoyo/group.c:tomoyo_write_group
  - security/tomoyo/group.c:tomoyo_write_group
  - security/tomoyo/group.c:tomoyo_write_group
```
**Symbols:**

```
ffffffff81cd5db6-ffffffff81cd5dfb: tomoyo_update_policy.cold (STB_LOCAL)
ffffffff81564520-ffffffff81564625: tomoyo_update_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int tomoyo_update_policy(struct tomoyo_acl_head *new_entry, const int size, struct tomoyo_acl_param *param, bool (*check_duplicate)(const struct tomoyo_acl_head *, const struct tomoyo_acl_head *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/tomoyo/domain.c (0)
Location: security/tomoyo/domain.c:31
Inline: False
Direct callers:
  - security/tomoyo/domain.c:tomoyo_write_aggregator
  - security/tomoyo/domain.c:tomoyo_write_transition_control
  - security/tomoyo/group.c:tomoyo_write_group
  - security/tomoyo/group.c:tomoyo_write_group
  - security/tomoyo/group.c:tomoyo_write_group
```
**Symbols:**

```
ffffffff81e88b9b-ffffffff81e88bd8: tomoyo_update_policy.cold (STB_LOCAL)
ffffffff815ffcf0-ffffffff815ffdfe: tomoyo_update_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int tomoyo_update_policy(struct tomoyo_acl_head *new_entry, const int size, struct tomoyo_acl_param *param, bool (*check_duplicate)(const struct tomoyo_acl_head *, const struct tomoyo_acl_head *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/tomoyo/domain.c (0)
Location: security/tomoyo/domain.c:31
Inline: False
Direct callers:
  - security/tomoyo/domain.c:tomoyo_write_aggregator
  - security/tomoyo/domain.c:tomoyo_write_transition_control
  - security/tomoyo/group.c:tomoyo_write_group
  - security/tomoyo/group.c:tomoyo_write_group
  - security/tomoyo/group.c:tomoyo_write_group
```
**Symbols:**

```
ffffffff820746c3-ffffffff82074700: tomoyo_update_policy.cold (STB_LOCAL)
ffffffff816b0bd0-ffffffff816b0cde: tomoyo_update_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int tomoyo_update_policy(struct tomoyo_acl_head *new_entry, const int size, struct tomoyo_acl_param *param, bool (*check_duplicate)(const struct tomoyo_acl_head *, const struct tomoyo_acl_head *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/tomoyo/domain.c (0)
Location: security/tomoyo/domain.c:31
Inline: False
Direct callers:
  - security/tomoyo/domain.c:tomoyo_write_aggregator
  - security/tomoyo/domain.c:tomoyo_write_transition_control
  - security/tomoyo/group.c:tomoyo_write_group
  - security/tomoyo/group.c:tomoyo_write_group
  - security/tomoyo/group.c:tomoyo_write_group
```
**Symbols:**

```
ffffffff820f421d-ffffffff820f425a: tomoyo_update_policy.cold (STB_LOCAL)
ffffffff816e95e0-ffffffff816e96ee: tomoyo_update_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int tomoyo_update_policy(struct tomoyo_acl_head *new_entry, const int size, struct tomoyo_acl_param *param, bool (*check_duplicate)(const struct tomoyo_acl_head *, const struct tomoyo_acl_head *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/tomoyo/domain.c (0)
Location: security/tomoyo/domain.c:31
Inline: False
Direct callers:
  - security/tomoyo/domain.c:tomoyo_write_aggregator
  - security/tomoyo/domain.c:tomoyo_write_transition_control
  - security/tomoyo/group.c:tomoyo_write_group
  - security/tomoyo/group.c:tomoyo_write_group
  - security/tomoyo/group.c:tomoyo_write_group
```
**Symbols:**

```
ffffffff821d1662-ffffffff821d169f: tomoyo_update_policy.cold (STB_LOCAL)
ffffffff817262f0-ffffffff817263fe: tomoyo_update_policy (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int tomoyo_update_policy(struct tomoyo_acl_head *new_entry, const int size, struct tomoyo_acl_param *param, bool (*check_duplicate)(const struct tomoyo_acl_head *, const struct tomoyo_acl_head *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/domain.c (ffff80001057f5d0)
Location: security/tomoyo/domain.c:31
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_manager
  - security/tomoyo/domain.c:tomoyo_write_aggregator
  - security/tomoyo/domain.c:tomoyo_write_transition_control
  - security/tomoyo/group.c:tomoyo_write_group
  - security/tomoyo/group.c:tomoyo_write_group
  - security/tomoyo/group.c:tomoyo_write_group
```
**Symbols:**

```
ffff80001057f5d0-ffff80001057f6d8: tomoyo_update_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int tomoyo_update_policy(struct tomoyo_acl_head *new_entry, const int size, struct tomoyo_acl_param *param, bool (*check_duplicate)(const struct tomoyo_acl_head *, const struct tomoyo_acl_head *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/domain.c (c0731b34)
Location: security/tomoyo/domain.c:31
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_manager
  - security/tomoyo/domain.c:tomoyo_write_aggregator
  - security/tomoyo/domain.c:tomoyo_write_transition_control
  - security/tomoyo/group.c:tomoyo_write_group
  - security/tomoyo/group.c:tomoyo_write_group
  - security/tomoyo/group.c:tomoyo_write_group
```
**Symbols:**

```
c0731b34-c0731c28: tomoyo_update_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int tomoyo_update_policy(struct tomoyo_acl_head *new_entry, const int size, struct tomoyo_acl_param *param, bool (*check_duplicate)(const struct tomoyo_acl_head *, const struct tomoyo_acl_head *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/domain.c (c0000000006ec7d0)
Location: security/tomoyo/domain.c:31
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_manager
  - security/tomoyo/domain.c:tomoyo_write_aggregator
  - security/tomoyo/domain.c:tomoyo_write_transition_control
  - security/tomoyo/group.c:tomoyo_write_group
  - security/tomoyo/group.c:tomoyo_write_group
  - security/tomoyo/group.c:tomoyo_write_group
```
**Symbols:**

```
c0000000006ec7d0-c0000000006ec93c: tomoyo_update_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int tomoyo_update_policy(struct tomoyo_acl_head *new_entry, const int size, struct tomoyo_acl_param *param, bool (*check_duplicate)(const struct tomoyo_acl_head *, const struct tomoyo_acl_head *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/domain.c (ffffffe0003d0428)
Location: security/tomoyo/domain.c:31
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_manager
  - security/tomoyo/domain.c:tomoyo_write_aggregator
  - security/tomoyo/domain.c:tomoyo_write_transition_control
  - security/tomoyo/group.c:tomoyo_write_group
  - security/tomoyo/group.c:tomoyo_write_group
  - security/tomoyo/group.c:tomoyo_write_group
```
**Symbols:**

```
ffffffe0003d0428-ffffffe0003d04fe: tomoyo_update_policy (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int tomoyo_update_policy(struct tomoyo_acl_head *new_entry, const int size, struct tomoyo_acl_param *param, bool (*check_duplicate)(const struct tomoyo_acl_head *, const struct tomoyo_acl_head *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/domain.c (ffffffff81484860)
Location: security/tomoyo/domain.c:31
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_manager
  - security/tomoyo/domain.c:tomoyo_write_aggregator
  - security/tomoyo/domain.c:tomoyo_write_transition_control
  - security/tomoyo/group.c:tomoyo_write_group
  - security/tomoyo/group.c:tomoyo_write_group
  - security/tomoyo/group.c:tomoyo_write_group
```
**Symbols:**

```
ffffffff81484860-ffffffff81484939: tomoyo_update_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int tomoyo_update_policy(struct tomoyo_acl_head *new_entry, const int size, struct tomoyo_acl_param *param, bool (*check_duplicate)(const struct tomoyo_acl_head *, const struct tomoyo_acl_head *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/domain.c (ffffffff81475280)
Location: security/tomoyo/domain.c:31
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_manager
  - security/tomoyo/domain.c:tomoyo_write_aggregator
  - security/tomoyo/domain.c:tomoyo_write_transition_control
  - security/tomoyo/group.c:tomoyo_write_group
  - security/tomoyo/group.c:tomoyo_write_group
  - security/tomoyo/group.c:tomoyo_write_group
```
**Symbols:**

```
ffffffff81475280-ffffffff81475359: tomoyo_update_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int tomoyo_update_policy(struct tomoyo_acl_head *new_entry, const int size, struct tomoyo_acl_param *param, bool (*check_duplicate)(const struct tomoyo_acl_head *, const struct tomoyo_acl_head *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/domain.c (ffffffff81480900)
Location: security/tomoyo/domain.c:31
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_manager
  - security/tomoyo/domain.c:tomoyo_write_aggregator
  - security/tomoyo/domain.c:tomoyo_write_transition_control
  - security/tomoyo/group.c:tomoyo_write_group
  - security/tomoyo/group.c:tomoyo_write_group
  - security/tomoyo/group.c:tomoyo_write_group
```
**Symbols:**

```
ffffffff81480900-ffffffff814809d9: tomoyo_update_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int tomoyo_update_policy(struct tomoyo_acl_head *new_entry, const int size, struct tomoyo_acl_param *param, bool (*check_duplicate)(const struct tomoyo_acl_head *, const struct tomoyo_acl_head *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/domain.c (ffffffff81498470)
Location: security/tomoyo/domain.c:31
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_manager
  - security/tomoyo/domain.c:tomoyo_write_aggregator
  - security/tomoyo/domain.c:tomoyo_write_transition_control
  - security/tomoyo/group.c:tomoyo_write_group
  - security/tomoyo/group.c:tomoyo_write_group
  - security/tomoyo/group.c:tomoyo_write_group
```
**Symbols:**

```
ffffffff81498470-ffffffff81498549: tomoyo_update_policy (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
