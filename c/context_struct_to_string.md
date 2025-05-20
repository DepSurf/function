# Function: <code>context_struct_to_string</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int context_struct_to_string(struct context *context, char **scontext, u32 *scontext_len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff81355180)
Location: security/selinux/ss/services.c:1185
Inline: True
Direct callers:
  - security/selinux/ss/services.c:compute_sid_handle_invalid_context
  - security/selinux/ss/services.c:compute_sid_handle_invalid_context
  - security/selinux/ss/services.c:compute_sid_handle_invalid_context
  - security/selinux/ss/services.c:security_validate_transition
  - security/selinux/ss/services.c:security_validate_transition
  - security/selinux/ss/services.c:security_validate_transition
  - security/selinux/ss/services.c:security_bounded_transition
  - security/selinux/ss/services.c:security_bounded_transition
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_sid_mls_copy
```
**Symbols:**

```
ffffffff81355180-ffffffff8135533c: context_struct_to_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int context_struct_to_string(struct context *context, char **scontext, u32 *scontext_len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8138b100)
Location: security/selinux/ss/services.c:1179
Inline: True
Direct callers:
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:compute_sid_handle_invalid_context
  - security/selinux/ss/services.c:compute_sid_handle_invalid_context
  - security/selinux/ss/services.c:compute_sid_handle_invalid_context
  - security/selinux/ss/services.c:security_bounded_transition
  - security/selinux/ss/services.c:security_bounded_transition
```
**Symbols:**

```
ffffffff8138b100-ffffffff8138b2bc: context_struct_to_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int context_struct_to_string(struct context *context, char **scontext, u32 *scontext_len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff813a1d10)
Location: security/selinux/ss/services.c:1179
Inline: True
Direct callers:
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:compute_sid_handle_invalid_context
  - security/selinux/ss/services.c:compute_sid_handle_invalid_context
  - security/selinux/ss/services.c:compute_sid_handle_invalid_context
  - security/selinux/ss/services.c:security_bounded_transition
  - security/selinux/ss/services.c:security_bounded_transition
```
**Symbols:**

```
ffffffff813a1d10-ffffffff813a1ecc: context_struct_to_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int context_struct_to_string(struct context *context, char **scontext, u32 *scontext_len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff813b86a0)
Location: security/selinux/ss/services.c:1191
Inline: True
Direct callers:
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:compute_sid_handle_invalid_context
  - security/selinux/ss/services.c:compute_sid_handle_invalid_context
  - security/selinux/ss/services.c:compute_sid_handle_invalid_context
  - security/selinux/ss/services.c:security_sid_to_context_core
  - security/selinux/ss/services.c:security_bounded_transition
  - security/selinux/ss/services.c:security_bounded_transition
```
**Symbols:**

```
ffffffff813b86a0-ffffffff813b8862: context_struct_to_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int context_struct_to_string(struct context *context, char **scontext, u32 *scontext_len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff813de810)
Location: security/selinux/ss/services.c:1196
Inline: True
Direct callers:
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:compute_sid_handle_invalid_context
  - security/selinux/ss/services.c:compute_sid_handle_invalid_context
  - security/selinux/ss/services.c:compute_sid_handle_invalid_context
  - security/selinux/ss/services.c:security_sid_to_context_core
  - security/selinux/ss/services.c:security_bounded_transition
  - security/selinux/ss/services.c:security_bounded_transition
```
**Symbols:**

```
ffffffff813de810-ffffffff813de9d2: context_struct_to_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int context_struct_to_string(struct policydb *p, struct context *context, char **scontext, u32 *scontext_len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8140ed20)
Location: security/selinux/ss/services.c:1225
Inline: True
Direct callers:
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:compute_sid_handle_invalid_context
  - security/selinux/ss/services.c:compute_sid_handle_invalid_context
  - security/selinux/ss/services.c:compute_sid_handle_invalid_context
  - security/selinux/ss/services.c:security_bounded_transition
  - security/selinux/ss/services.c:security_bounded_transition
```
**Symbols:**

```
ffffffff8140ed20-ffffffff8140eee9: context_struct_to_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int context_struct_to_string(struct policydb *p, struct context *context, char **scontext, u32 *scontext_len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8142b230)
Location: security/selinux/ss/services.c:1222
Inline: True
Direct callers:
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/services.c:compute_sid_handle_invalid_context
  - security/selinux/ss/services.c:compute_sid_handle_invalid_context
  - security/selinux/ss/services.c:compute_sid_handle_invalid_context
  - security/selinux/ss/services.c:security_bounded_transition
  - security/selinux/ss/services.c:security_bounded_transition
```
**Symbols:**

```
ffffffff8142b230-ffffffff8142b3f9: context_struct_to_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int context_struct_to_string(struct policydb *p, struct context *context, char **scontext, u32 *scontext_len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff81459670)
Location: security/selinux/ss/services.c:1208
Inline: True
Direct callers:
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/services.c:compute_sid_handle_invalid_context
  - security/selinux/ss/services.c:compute_sid_handle_invalid_context
  - security/selinux/ss/services.c:compute_sid_handle_invalid_context
  - security/selinux/ss/services.c:security_bounded_transition
  - security/selinux/ss/services.c:security_bounded_transition
```
**Symbols:**

```
ffffffff81459670-ffffffff81459818: context_struct_to_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int context_struct_to_string(struct policydb *p, struct context *context, char **scontext, u32 *scontext_len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff81473410)
Location: security/selinux/ss/services.c:1208
Inline: True
Direct callers:
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/services.c:compute_sid_handle_invalid_context
  - security/selinux/ss/services.c:compute_sid_handle_invalid_context
  - security/selinux/ss/services.c:compute_sid_handle_invalid_context
  - security/selinux/ss/services.c:security_bounded_transition
  - security/selinux/ss/services.c:security_bounded_transition
```
**Symbols:**

```
ffffffff81473410-ffffffff814735b8: context_struct_to_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int context_struct_to_string(struct policydb *p, struct context *context, char **scontext, u32 *scontext_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff814c7b70)
Location: security/selinux/ss/services.c:1215
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/services.c:compute_sid_handle_invalid_context
```
**Symbols:**

```
ffffffff814c7b70-ffffffff814c7d12: context_struct_to_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int context_struct_to_string(struct policydb *p, struct context *context, char **scontext, u32 *scontext_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff814e57c0)
Location: security/selinux/ss/services.c:1228
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/services.c:compute_sid_handle_invalid_context
```
**Symbols:**

```
ffffffff814e57c0-ffffffff814e5962: context_struct_to_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int context_struct_to_string(struct policydb *p, struct context *context, char **scontext, u32 *scontext_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff814ec110)
Location: security/selinux/ss/services.c:1230
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/services.c:convert_context
```
**Symbols:**

```
ffffffff814ec110-ffffffff814ec2b2: context_struct_to_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int context_struct_to_string(struct policydb *p, struct context *context, char **scontext, u32 *scontext_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff81545eb0)
Location: security/selinux/ss/services.c:1232
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/services.c:compute_sid_handle_invalid_context
```
**Symbols:**

```
ffffffff81545eb0-ffffffff81546052: context_struct_to_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int context_struct_to_string(struct policydb *p, struct context *context, char **scontext, u32 *scontext_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff815de7e0)
Location: security/selinux/ss/services.c:1230
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/services.c:compute_sid_handle_invalid_context
```
**Symbols:**

```
ffffffff815de7e0-ffffffff815de99a: context_struct_to_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int context_struct_to_string(struct policydb *p, struct context *context, char **scontext, u32 *scontext_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8168d4f0)
Location: security/selinux/ss/services.c:1224
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:services_convert_context
  - security/selinux/ss/services.c:services_convert_context
  - security/selinux/ss/services.c:compute_sid_handle_invalid_context
```
**Symbols:**

```
ffffffff8168d4f0-ffffffff8168d6aa: context_struct_to_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int context_struct_to_string(struct policydb *p, struct context *context, char **scontext, u32 *scontext_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff816c57d0)
Location: security/selinux/ss/services.c:1213
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:services_convert_context
  - security/selinux/ss/services.c:services_convert_context
  - security/selinux/ss/services.c:compute_sid_handle_invalid_context
```
**Symbols:**

```
ffffffff816c57d0-ffffffff816c598a: context_struct_to_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int context_struct_to_string(struct policydb *p, struct context *context, char **scontext, u32 *scontext_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff81702420)
Location: security/selinux/ss/services.c:1213
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:services_convert_context
  - security/selinux/ss/services.c:services_convert_context
  - security/selinux/ss/services.c:compute_sid_handle_invalid_context
```
**Symbols:**

```
ffffffff81702420-ffffffff817025da: context_struct_to_string (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int context_struct_to_string(struct policydb *p, struct context *context, char **scontext, u32 *scontext_len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffff800010561c58)
Location: security/selinux/ss/services.c:1208
Inline: True
Direct callers:
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/services.c:compute_sid_handle_invalid_context
  - security/selinux/ss/services.c:compute_sid_handle_invalid_context
  - security/selinux/ss/services.c:compute_sid_handle_invalid_context
  - security/selinux/ss/services.c:security_bounded_transition
  - security/selinux/ss/services.c:security_bounded_transition
```
**Symbols:**

```
ffff800010561c58-ffff800010561e20: context_struct_to_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int context_struct_to_string(struct policydb *p, struct context *context, char **scontext, u32 *scontext_len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (c0717178)
Location: security/selinux/ss/services.c:1208
Inline: True
Direct callers:
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/services.c:security_sid_to_context_core
  - security/selinux/ss/services.c:security_bounded_transition
  - security/selinux/ss/services.c:security_bounded_transition
```
**Symbols:**

```
c0717178-c0717344: context_struct_to_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int context_struct_to_string(struct policydb *p, struct context *context, char **scontext, u32 *scontext_len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (c0000000006c43f0)
Location: security/selinux/ss/services.c:1208
Inline: True
Direct callers:
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/services.c:compute_sid_handle_invalid_context
  - security/selinux/ss/services.c:compute_sid_handle_invalid_context
  - security/selinux/ss/services.c:compute_sid_handle_invalid_context
  - security/selinux/ss/services.c:security_bounded_transition
  - security/selinux/ss/services.c:security_bounded_transition
```
**Symbols:**

```
c0000000006c43f0-c0000000006c468c: context_struct_to_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int context_struct_to_string(struct policydb *p, struct context *context, char **scontext, u32 *scontext_len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffe0003b8c58)
Location: security/selinux/ss/services.c:1208
Inline: True
Direct callers:
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/services.c:compute_sid_handle_invalid_context
  - security/selinux/ss/services.c:compute_sid_handle_invalid_context
  - security/selinux/ss/services.c:compute_sid_handle_invalid_context
  - security/selinux/ss/services.c:security_bounded_transition
  - security/selinux/ss/services.c:security_bounded_transition
```
**Symbols:**

```
ffffffe0003b8c58-ffffffe0003b8dde: context_struct_to_string (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int context_struct_to_string(struct policydb *p, struct context *context, char **scontext, u32 *scontext_len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8146b9f0)
Location: security/selinux/ss/services.c:1208
Inline: True
Direct callers:
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/services.c:compute_sid_handle_invalid_context
  - security/selinux/ss/services.c:compute_sid_handle_invalid_context
  - security/selinux/ss/services.c:compute_sid_handle_invalid_context
  - security/selinux/ss/services.c:security_bounded_transition
  - security/selinux/ss/services.c:security_bounded_transition
```
**Symbols:**

```
ffffffff8146b9f0-ffffffff8146bb98: context_struct_to_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int context_struct_to_string(struct policydb *p, struct context *context, char **scontext, u32 *scontext_len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8145c420)
Location: security/selinux/ss/services.c:1208
Inline: True
Direct callers:
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/services.c:compute_sid_handle_invalid_context
  - security/selinux/ss/services.c:compute_sid_handle_invalid_context
  - security/selinux/ss/services.c:compute_sid_handle_invalid_context
  - security/selinux/ss/services.c:security_bounded_transition
  - security/selinux/ss/services.c:security_bounded_transition
```
**Symbols:**

```
ffffffff8145c420-ffffffff8145c5c8: context_struct_to_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int context_struct_to_string(struct policydb *p, struct context *context, char **scontext, u32 *scontext_len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff81467a90)
Location: security/selinux/ss/services.c:1208
Inline: True
Direct callers:
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/services.c:compute_sid_handle_invalid_context
  - security/selinux/ss/services.c:compute_sid_handle_invalid_context
  - security/selinux/ss/services.c:compute_sid_handle_invalid_context
  - security/selinux/ss/services.c:security_bounded_transition
  - security/selinux/ss/services.c:security_bounded_transition
```
**Symbols:**

```
ffffffff81467a90-ffffffff81467c38: context_struct_to_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int context_struct_to_string(struct policydb *p, struct context *context, char **scontext, u32 *scontext_len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8147f270)
Location: security/selinux/ss/services.c:1208
Inline: True
Direct callers:
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/services.c:convert_context
  - security/selinux/ss/services.c:compute_sid_handle_invalid_context
  - security/selinux/ss/services.c:compute_sid_handle_invalid_context
  - security/selinux/ss/services.c:compute_sid_handle_invalid_context
  - security/selinux/ss/services.c:security_bounded_transition
  - security/selinux/ss/services.c:security_bounded_transition
```
**Symbols:**

```
ffffffff8147f270-ffffffff8147f418: context_struct_to_string (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct policydb *p</code>
</li>
<li>
<b>Param reordered. </b>
<code>context, scontext, scontext_len</code> ➡️ <code>p, context, scontext, scontext_len</code>
</li>
</ul>
</details>
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
