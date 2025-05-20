# Function: <code>tomoyo_get_name</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
const struct tomoyo_path_info *tomoyo_get_name(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/memory.c (ffffffff81370fe0)
Location: security/tomoyo/memory.c:147
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_manager
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/condition.c:tomoyo_get_dqword
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/domain.c:tomoyo_write_transition_control
  - security/tomoyo/domain.c:tomoyo_write_transition_control
  - security/tomoyo/domain.c:tomoyo_write_aggregator
  - security/tomoyo/domain.c:tomoyo_write_aggregator
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/environ.c:tomoyo_write_misc
  - security/tomoyo/group.c:tomoyo_write_group
  - security/tomoyo/memory.c:tomoyo_mm_init
  - security/tomoyo/memory.c:tomoyo_get_group
  - security/tomoyo/util.c:tomoyo_parse_name_union
  - security/tomoyo/util.c:tomoyo_get_domainname
```
**Symbols:**

```
ffffffff81370fe0-ffffffff8137113b: tomoyo_get_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
const struct tomoyo_path_info *tomoyo_get_name(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/memory.c (ffffffff813a73c0)
Location: security/tomoyo/memory.c:147
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_manager
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_get_dqword
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_write_aggregator
  - security/tomoyo/domain.c:tomoyo_write_aggregator
  - security/tomoyo/domain.c:tomoyo_write_transition_control
  - security/tomoyo/domain.c:tomoyo_write_transition_control
  - security/tomoyo/environ.c:tomoyo_write_misc
  - security/tomoyo/group.c:tomoyo_write_group
  - security/tomoyo/memory.c:tomoyo_get_group
  - security/tomoyo/memory.c:tomoyo_mm_init
  - security/tomoyo/util.c:tomoyo_parse_name_union
  - security/tomoyo/util.c:tomoyo_get_domainname
```
**Symbols:**

```
ffffffff813a73c0-ffffffff813a753b: tomoyo_get_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
const struct tomoyo_path_info *tomoyo_get_name(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/memory.c (ffffffff813bdf40)
Location: security/tomoyo/memory.c:147
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_manager
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_get_dqword
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_write_aggregator
  - security/tomoyo/domain.c:tomoyo_write_aggregator
  - security/tomoyo/domain.c:tomoyo_write_transition_control
  - security/tomoyo/domain.c:tomoyo_write_transition_control
  - security/tomoyo/environ.c:tomoyo_write_misc
  - security/tomoyo/group.c:tomoyo_write_group
  - security/tomoyo/memory.c:tomoyo_get_group
  - security/tomoyo/memory.c:tomoyo_mm_init
  - security/tomoyo/util.c:tomoyo_parse_name_union
  - security/tomoyo/util.c:tomoyo_get_domainname
```
**Symbols:**

```
ffffffff813bdf40-ffffffff813be0bb: tomoyo_get_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
const struct tomoyo_path_info *tomoyo_get_name(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/memory.c (ffffffff813d4810)
Location: security/tomoyo/memory.c:147
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_manager
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_get_dqword
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_write_aggregator
  - security/tomoyo/domain.c:tomoyo_write_aggregator
  - security/tomoyo/domain.c:tomoyo_write_transition_control
  - security/tomoyo/domain.c:tomoyo_write_transition_control
  - security/tomoyo/environ.c:tomoyo_write_misc
  - security/tomoyo/group.c:tomoyo_write_group
  - security/tomoyo/memory.c:tomoyo_get_group
  - security/tomoyo/memory.c:tomoyo_mm_init
  - security/tomoyo/util.c:tomoyo_parse_name_union
  - security/tomoyo/util.c:tomoyo_get_domainname
```
**Symbols:**

```
ffffffff813d4810-ffffffff813d497c: tomoyo_get_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
const struct tomoyo_path_info *tomoyo_get_name(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/memory.c (ffffffff813fad20)
Location: security/tomoyo/memory.c:148
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_manager
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_get_dqword
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_write_aggregator
  - security/tomoyo/domain.c:tomoyo_write_aggregator
  - security/tomoyo/domain.c:tomoyo_write_transition_control
  - security/tomoyo/domain.c:tomoyo_write_transition_control
  - security/tomoyo/environ.c:tomoyo_write_misc
  - security/tomoyo/group.c:tomoyo_write_group
  - security/tomoyo/memory.c:tomoyo_get_group
  - security/tomoyo/memory.c:tomoyo_mm_init
  - security/tomoyo/util.c:tomoyo_parse_name_union
  - security/tomoyo/util.c:tomoyo_get_domainname
```
**Symbols:**

```
ffffffff813fad20-ffffffff813fae8c: tomoyo_get_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
const struct tomoyo_path_info *tomoyo_get_name(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/memory.c (ffffffff8142bcc0)
Location: security/tomoyo/memory.c:148
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_manager
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_get_dqword
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_write_aggregator
  - security/tomoyo/domain.c:tomoyo_write_aggregator
  - security/tomoyo/domain.c:tomoyo_write_transition_control
  - security/tomoyo/domain.c:tomoyo_write_transition_control
  - security/tomoyo/environ.c:tomoyo_write_misc
  - security/tomoyo/group.c:tomoyo_write_group
  - security/tomoyo/memory.c:tomoyo_get_group
  - security/tomoyo/memory.c:tomoyo_mm_init
  - security/tomoyo/util.c:tomoyo_parse_name_union
  - security/tomoyo/util.c:tomoyo_get_domainname
```
**Symbols:**

```
ffffffff8142bcc0-ffffffff8142be3a: tomoyo_get_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
const struct tomoyo_path_info *tomoyo_get_name(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/memory.c (ffffffff814485e0)
Location: security/tomoyo/memory.c:148
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_manager
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_get_dqword
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_write_aggregator
  - security/tomoyo/domain.c:tomoyo_write_aggregator
  - security/tomoyo/domain.c:tomoyo_write_transition_control
  - security/tomoyo/domain.c:tomoyo_write_transition_control
  - security/tomoyo/environ.c:tomoyo_write_misc
  - security/tomoyo/group.c:tomoyo_write_group
  - security/tomoyo/memory.c:tomoyo_get_group
  - security/tomoyo/memory.c:tomoyo_mm_init
  - security/tomoyo/util.c:tomoyo_parse_name_union
  - security/tomoyo/util.c:tomoyo_get_domainname
```
**Symbols:**

```
ffffffff814485e0-ffffffff8144875a: tomoyo_get_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
const struct tomoyo_path_info *tomoyo_get_name(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/memory.c (ffffffff81476230)
Location: security/tomoyo/memory.c:152
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_manager
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_get_dqword
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_write_aggregator
  - security/tomoyo/domain.c:tomoyo_write_aggregator
  - security/tomoyo/domain.c:tomoyo_write_transition_control
  - security/tomoyo/domain.c:tomoyo_write_transition_control
  - security/tomoyo/environ.c:tomoyo_write_misc
  - security/tomoyo/group.c:tomoyo_write_group
  - security/tomoyo/memory.c:tomoyo_get_group
  - security/tomoyo/memory.c:tomoyo_mm_init
  - security/tomoyo/util.c:tomoyo_parse_name_union
  - security/tomoyo/util.c:tomoyo_get_domainname
```
**Symbols:**

```
ffffffff81476230-ffffffff814763a8: tomoyo_get_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
const struct tomoyo_path_info *tomoyo_get_name(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/memory.c (ffffffff8148ffd0)
Location: security/tomoyo/memory.c:152
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_manager
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_get_dqword
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_write_aggregator
  - security/tomoyo/domain.c:tomoyo_write_aggregator
  - security/tomoyo/domain.c:tomoyo_write_transition_control
  - security/tomoyo/domain.c:tomoyo_write_transition_control
  - security/tomoyo/environ.c:tomoyo_write_misc
  - security/tomoyo/group.c:tomoyo_write_group
  - security/tomoyo/memory.c:tomoyo_get_group
  - security/tomoyo/memory.c:tomoyo_mm_init
  - security/tomoyo/util.c:tomoyo_parse_name_union
  - security/tomoyo/util.c:tomoyo_get_domainname
```
**Symbols:**

```
ffffffff8148ffd0-ffffffff81490148: tomoyo_get_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
const struct tomoyo_path_info *tomoyo_get_name(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/memory.c (ffffffff814e7330)
Location: security/tomoyo/memory.c:152
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_update_manager_entry
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/condition.c:tomoyo_get_transit_preference
  - security/tomoyo/condition.c:tomoyo_parse_envp
  - security/tomoyo/condition.c:tomoyo_get_dqword
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_write_aggregator
  - security/tomoyo/domain.c:tomoyo_write_aggregator
  - security/tomoyo/domain.c:tomoyo_write_transition_control
  - security/tomoyo/domain.c:tomoyo_write_transition_control
  - security/tomoyo/environ.c:tomoyo_write_env
  - security/tomoyo/group.c:tomoyo_write_group
  - security/tomoyo/memory.c:tomoyo_get_group
  - security/tomoyo/memory.c:tomoyo_mm_init
  - security/tomoyo/util.c:tomoyo_parse_name_union
  - security/tomoyo/util.c:tomoyo_get_domainname
```
**Symbols:**

```
ffffffff814e7330-ffffffff814e74ad: tomoyo_get_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
const struct tomoyo_path_info *tomoyo_get_name(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/memory.c (ffffffff81504700)
Location: security/tomoyo/memory.c:152
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_update_manager_entry
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/condition.c:tomoyo_get_transit_preference
  - security/tomoyo/condition.c:tomoyo_parse_envp
  - security/tomoyo/condition.c:tomoyo_get_dqword
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_write_aggregator
  - security/tomoyo/domain.c:tomoyo_write_aggregator
  - security/tomoyo/domain.c:tomoyo_write_transition_control
  - security/tomoyo/domain.c:tomoyo_write_transition_control
  - security/tomoyo/environ.c:tomoyo_write_env
  - security/tomoyo/group.c:tomoyo_write_group
  - security/tomoyo/memory.c:tomoyo_get_group
  - security/tomoyo/memory.c:tomoyo_mm_init
  - security/tomoyo/util.c:tomoyo_parse_name_union
  - security/tomoyo/util.c:tomoyo_get_domainname
```
**Symbols:**

```
ffffffff81504700-ffffffff8150487d: tomoyo_get_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
const struct tomoyo_path_info *tomoyo_get_name(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/memory.c (ffffffff8150b280)
Location: security/tomoyo/memory.c:152
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_manager
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_get_dqword
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_write_aggregator
  - security/tomoyo/domain.c:tomoyo_write_aggregator
  - security/tomoyo/domain.c:tomoyo_write_transition_control
  - security/tomoyo/domain.c:tomoyo_write_transition_control
  - security/tomoyo/environ.c:tomoyo_write_misc
  - security/tomoyo/group.c:tomoyo_write_group
  - security/tomoyo/memory.c:tomoyo_get_group
  - security/tomoyo/memory.c:tomoyo_mm_init
  - security/tomoyo/util.c:tomoyo_parse_name_union
  - security/tomoyo/util.c:tomoyo_get_domainname
```
**Symbols:**

```
ffffffff8150b280-ffffffff8150b3fd: tomoyo_get_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
const struct tomoyo_path_info *tomoyo_get_name(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/memory.c (ffffffff81568a90)
Location: security/tomoyo/memory.c:152
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_get_dqword
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_write_aggregator
  - security/tomoyo/domain.c:tomoyo_write_aggregator
  - security/tomoyo/domain.c:tomoyo_write_transition_control
  - security/tomoyo/domain.c:tomoyo_write_transition_control
  - security/tomoyo/environ.c:tomoyo_write_misc
  - security/tomoyo/group.c:tomoyo_write_group
  - security/tomoyo/memory.c:tomoyo_get_group
  - security/tomoyo/memory.c:tomoyo_mm_init
  - security/tomoyo/util.c:tomoyo_parse_name_union
  - security/tomoyo/util.c:tomoyo_get_domainname
```
**Symbols:**

```
ffffffff81568a90-ffffffff81568c4f: tomoyo_get_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
const struct tomoyo_path_info *tomoyo_get_name(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/memory.c (ffffffff816047b0)
Location: security/tomoyo/memory.c:152
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_get_dqword
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_write_aggregator
  - security/tomoyo/domain.c:tomoyo_write_aggregator
  - security/tomoyo/domain.c:tomoyo_write_transition_control
  - security/tomoyo/domain.c:tomoyo_write_transition_control
  - security/tomoyo/environ.c:tomoyo_write_misc
  - security/tomoyo/group.c:tomoyo_write_group
  - security/tomoyo/memory.c:tomoyo_get_group
  - security/tomoyo/memory.c:tomoyo_mm_init
  - security/tomoyo/util.c:tomoyo_parse_name_union
  - security/tomoyo/util.c:tomoyo_get_domainname
```
**Symbols:**

```
ffffffff816047b0-ffffffff8160498a: tomoyo_get_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
const struct tomoyo_path_info *tomoyo_get_name(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/memory.c (ffffffff816b5aa0)
Location: security/tomoyo/memory.c:152
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_get_dqword
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_write_aggregator
  - security/tomoyo/domain.c:tomoyo_write_aggregator
  - security/tomoyo/domain.c:tomoyo_write_transition_control
  - security/tomoyo/domain.c:tomoyo_write_transition_control
  - security/tomoyo/environ.c:tomoyo_write_misc
  - security/tomoyo/group.c:tomoyo_write_group
  - security/tomoyo/memory.c:tomoyo_get_group
  - security/tomoyo/memory.c:tomoyo_mm_init
  - security/tomoyo/util.c:tomoyo_parse_name_union
  - security/tomoyo/util.c:tomoyo_get_domainname
```
**Symbols:**

```
ffffffff816b5aa0-ffffffff816b5c7a: tomoyo_get_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
const struct tomoyo_path_info *tomoyo_get_name(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/memory.c (ffffffff816ee480)
Location: security/tomoyo/memory.c:152
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_get_dqword
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_write_aggregator
  - security/tomoyo/domain.c:tomoyo_write_aggregator
  - security/tomoyo/domain.c:tomoyo_write_transition_control
  - security/tomoyo/domain.c:tomoyo_write_transition_control
  - security/tomoyo/environ.c:tomoyo_write_misc
  - security/tomoyo/group.c:tomoyo_write_group
  - security/tomoyo/memory.c:tomoyo_get_group
  - security/tomoyo/memory.c:tomoyo_mm_init
  - security/tomoyo/util.c:tomoyo_parse_name_union
  - security/tomoyo/util.c:tomoyo_get_domainname
```
**Symbols:**

```
ffffffff816ee480-ffffffff816ee685: tomoyo_get_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
const struct tomoyo_path_info *tomoyo_get_name(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/memory.c (ffffffff8172b250)
Location: security/tomoyo/memory.c:152
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_get_dqword
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_write_aggregator
  - security/tomoyo/domain.c:tomoyo_write_aggregator
  - security/tomoyo/domain.c:tomoyo_write_transition_control
  - security/tomoyo/domain.c:tomoyo_write_transition_control
  - security/tomoyo/environ.c:tomoyo_write_misc
  - security/tomoyo/group.c:tomoyo_write_group
  - security/tomoyo/memory.c:tomoyo_get_group
  - security/tomoyo/memory.c:tomoyo_mm_init
  - security/tomoyo/util.c:tomoyo_parse_name_union
  - security/tomoyo/util.c:tomoyo_get_domainname
```
**Symbols:**

```
ffffffff8172b250-ffffffff8172b455: tomoyo_get_name (STB_GLOBAL)
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
const struct tomoyo_path_info *tomoyo_get_name(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/memory.c (ffff800010584178)
Location: security/tomoyo/memory.c:152
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_manager
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_get_dqword
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_write_aggregator
  - security/tomoyo/domain.c:tomoyo_write_aggregator
  - security/tomoyo/domain.c:tomoyo_write_transition_control
  - security/tomoyo/domain.c:tomoyo_write_transition_control
  - security/tomoyo/environ.c:tomoyo_write_misc
  - security/tomoyo/group.c:tomoyo_write_group
  - security/tomoyo/memory.c:tomoyo_get_group
  - security/tomoyo/memory.c:tomoyo_mm_init
  - security/tomoyo/util.c:tomoyo_parse_name_union
  - security/tomoyo/util.c:tomoyo_get_domainname
```
**Symbols:**

```
ffff800010584178-ffff800010584328: tomoyo_get_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
const struct tomoyo_path_info *tomoyo_get_name(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/memory.c (c0735c38)
Location: security/tomoyo/memory.c:152
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_manager
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_get_dqword
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_write_aggregator
  - security/tomoyo/domain.c:tomoyo_write_aggregator
  - security/tomoyo/domain.c:tomoyo_write_transition_control
  - security/tomoyo/domain.c:tomoyo_write_transition_control
  - security/tomoyo/environ.c:tomoyo_write_misc
  - security/tomoyo/group.c:tomoyo_write_group
  - security/tomoyo/memory.c:tomoyo_get_group
  - security/tomoyo/memory.c:tomoyo_mm_init
  - security/tomoyo/util.c:tomoyo_parse_name_union
  - security/tomoyo/util.c:tomoyo_get_domainname
```
**Symbols:**

```
c0735c38-c0735da8: tomoyo_get_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
const struct tomoyo_path_info *tomoyo_get_name(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/memory.c (c0000000006f3110)
Location: security/tomoyo/memory.c:152
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_manager
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_get_dqword
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_write_aggregator
  - security/tomoyo/domain.c:tomoyo_write_aggregator
  - security/tomoyo/domain.c:tomoyo_write_transition_control
  - security/tomoyo/domain.c:tomoyo_write_transition_control
  - security/tomoyo/environ.c:tomoyo_write_misc
  - security/tomoyo/group.c:tomoyo_write_group
  - security/tomoyo/memory.c:tomoyo_get_group
  - security/tomoyo/memory.c:tomoyo_mm_init
  - security/tomoyo/util.c:tomoyo_parse_name_union
  - security/tomoyo/util.c:tomoyo_get_domainname
```
**Symbols:**

```
c0000000006f3110-c0000000006f3540: tomoyo_get_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
const struct tomoyo_path_info *tomoyo_get_name(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/memory.c (ffffffe0003d422e)
Location: security/tomoyo/memory.c:152
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_manager
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_get_dqword
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_write_aggregator
  - security/tomoyo/domain.c:tomoyo_write_aggregator
  - security/tomoyo/domain.c:tomoyo_write_transition_control
  - security/tomoyo/domain.c:tomoyo_write_transition_control
  - security/tomoyo/environ.c:tomoyo_write_misc
  - security/tomoyo/group.c:tomoyo_write_group
  - security/tomoyo/memory.c:tomoyo_get_group
  - security/tomoyo/memory.c:tomoyo_mm_init
  - security/tomoyo/util.c:tomoyo_parse_name_union
  - security/tomoyo/util.c:tomoyo_get_domainname
```
**Symbols:**

```
ffffffe0003d422e-ffffffe0003d438e: tomoyo_get_name (STB_GLOBAL)
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
const struct tomoyo_path_info *tomoyo_get_name(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/memory.c (ffffffff814885b0)
Location: security/tomoyo/memory.c:152
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_manager
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_get_dqword
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_write_aggregator
  - security/tomoyo/domain.c:tomoyo_write_aggregator
  - security/tomoyo/domain.c:tomoyo_write_transition_control
  - security/tomoyo/domain.c:tomoyo_write_transition_control
  - security/tomoyo/environ.c:tomoyo_write_misc
  - security/tomoyo/group.c:tomoyo_write_group
  - security/tomoyo/memory.c:tomoyo_get_group
  - security/tomoyo/memory.c:tomoyo_mm_init
  - security/tomoyo/util.c:tomoyo_parse_name_union
  - security/tomoyo/util.c:tomoyo_get_domainname
```
**Symbols:**

```
ffffffff814885b0-ffffffff81488728: tomoyo_get_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
const struct tomoyo_path_info *tomoyo_get_name(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/memory.c (ffffffff81478fd0)
Location: security/tomoyo/memory.c:152
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_manager
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_get_dqword
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_write_aggregator
  - security/tomoyo/domain.c:tomoyo_write_aggregator
  - security/tomoyo/domain.c:tomoyo_write_transition_control
  - security/tomoyo/domain.c:tomoyo_write_transition_control
  - security/tomoyo/environ.c:tomoyo_write_misc
  - security/tomoyo/group.c:tomoyo_write_group
  - security/tomoyo/memory.c:tomoyo_get_group
  - security/tomoyo/memory.c:tomoyo_mm_init
  - security/tomoyo/util.c:tomoyo_parse_name_union
  - security/tomoyo/util.c:tomoyo_get_domainname
```
**Symbols:**

```
ffffffff81478fd0-ffffffff81479148: tomoyo_get_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
const struct tomoyo_path_info *tomoyo_get_name(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/memory.c (ffffffff81484650)
Location: security/tomoyo/memory.c:152
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_manager
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_get_dqword
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_write_aggregator
  - security/tomoyo/domain.c:tomoyo_write_aggregator
  - security/tomoyo/domain.c:tomoyo_write_transition_control
  - security/tomoyo/domain.c:tomoyo_write_transition_control
  - security/tomoyo/environ.c:tomoyo_write_misc
  - security/tomoyo/group.c:tomoyo_write_group
  - security/tomoyo/memory.c:tomoyo_get_group
  - security/tomoyo/memory.c:tomoyo_mm_init
  - security/tomoyo/util.c:tomoyo_parse_name_union
  - security/tomoyo/util.c:tomoyo_get_domainname
```
**Symbols:**

```
ffffffff81484650-ffffffff814847c8: tomoyo_get_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
const struct tomoyo_path_info *tomoyo_get_name(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/memory.c (ffffffff8149c190)
Location: security/tomoyo/memory.c:152
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_manager
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_get_condition
  - security/tomoyo/condition.c:tomoyo_get_dqword
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_write_aggregator
  - security/tomoyo/domain.c:tomoyo_write_aggregator
  - security/tomoyo/domain.c:tomoyo_write_transition_control
  - security/tomoyo/domain.c:tomoyo_write_transition_control
  - security/tomoyo/environ.c:tomoyo_write_misc
  - security/tomoyo/group.c:tomoyo_write_group
  - security/tomoyo/memory.c:tomoyo_get_group
  - security/tomoyo/memory.c:tomoyo_mm_init
  - security/tomoyo/util.c:tomoyo_parse_name_union
  - security/tomoyo/util.c:tomoyo_get_domainname
```
**Symbols:**

```
ffffffff8149c190-ffffffff8149c308: tomoyo_get_name (STB_GLOBAL)
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
