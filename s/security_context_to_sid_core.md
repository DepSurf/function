# Function: <code>security_context_to_sid_core</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int security_context_to_sid_core(const char *scontext, u32 scontext_len, u32 *sid, u32 def_sid, gfp_t gfp_flags, int force);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff813562a0)
Location: security/selinux/ss/services.c:1397
Inline: True
Direct callers:
  - security/selinux/ss/services.c:security_context_str_to_sid
  - security/selinux/ss/services.c:security_context_to_sid_default
  - security/selinux/ss/services.c:security_context_to_sid_force
```
**Symbols:**

```
ffffffff813562a0-ffffffff8135650b: security_context_to_sid_core (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int security_context_to_sid_core(const char *scontext, u32 scontext_len, u32 *sid, u32 def_sid, gfp_t gfp_flags, int force);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8138bfc0)
Location: security/selinux/ss/services.c:1391
Inline: True
Direct callers:
  - security/selinux/ss/services.c:security_context_to_sid_force
  - security/selinux/ss/services.c:security_context_to_sid_default
  - security/selinux/ss/services.c:security_context_str_to_sid
```
**Symbols:**

```
ffffffff8138bfc0-ffffffff8138c231: security_context_to_sid_core (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int security_context_to_sid_core(const char *scontext, u32 scontext_len, u32 *sid, u32 def_sid, gfp_t gfp_flags, int force);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff813a2bd0)
Location: security/selinux/ss/services.c:1391
Inline: True
Direct callers:
  - security/selinux/ss/services.c:security_context_to_sid_force
  - security/selinux/ss/services.c:security_context_to_sid_default
  - security/selinux/ss/services.c:security_context_str_to_sid
```
**Symbols:**

```
ffffffff813a2bd0-ffffffff813a2e41: security_context_to_sid_core (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int security_context_to_sid_core(const char *scontext, u32 scontext_len, u32 *sid, u32 def_sid, gfp_t gfp_flags, int force);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff813b9e40)
Location: security/selinux/ss/services.c:1403
Inline: True
Direct callers:
  - security/selinux/ss/services.c:security_context_to_sid_force
  - security/selinux/ss/services.c:security_context_to_sid_default
  - security/selinux/ss/services.c:security_context_str_to_sid
```
**Symbols:**

```
ffffffff813b9e40-ffffffff813ba0a2: security_context_to_sid_core (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int security_context_to_sid_core(const char *scontext, u32 scontext_len, u32 *sid, u32 def_sid, gfp_t gfp_flags, int force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff813dfa00)
Location: security/selinux/ss/services.c:1408
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_context_to_sid_force
  - security/selinux/ss/services.c:security_context_to_sid_default
  - security/selinux/ss/services.c:security_context_str_to_sid
```
**Symbols:**

```
ffffffff813dfa00-ffffffff813dfc2e: security_context_to_sid_core (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (ffffffff81410350)
Location: security/selinux/ss/services.c:1449
Inline: True
Direct callers:
  - security/selinux/ss/services.c:security_context_to_sid_force
  - security/selinux/ss/services.c:security_context_to_sid_default
  - security/selinux/ss/services.c:security_context_str_to_sid
```
**Symbols:**

```
ffffffff81410350-ffffffff814105c7: security_context_to_sid_core.isra.16 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8142c390)
Location: security/selinux/ss/services.c:1442
Inline: True
Direct callers:
  - security/selinux/ss/services.c:security_context_to_sid_force
  - security/selinux/ss/services.c:security_context_to_sid_default
  - security/selinux/ss/services.c:security_context_str_to_sid
```
**Symbols:**

```
ffffffff8142c390-ffffffff8142c5d8: security_context_to_sid_core.isra.16 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (ffffffff81459410)
Location: security/selinux/ss/services.c:1452
Inline: True
Direct callers:
  - security/selinux/ss/services.c:security_context_to_sid_force
  - security/selinux/ss/services.c:security_context_to_sid_default
  - security/selinux/ss/services.c:security_context_str_to_sid
```
**Symbols:**

```
ffffffff81459410-ffffffff81459665: security_context_to_sid_core.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (ffffffff814731b0)
Location: security/selinux/ss/services.c:1452
Inline: True
Direct callers:
  - security/selinux/ss/services.c:security_context_to_sid_force
  - security/selinux/ss/services.c:security_context_to_sid_default
  - security/selinux/ss/services.c:security_context_str_to_sid
```
**Symbols:**

```
ffffffff814731b0-ffffffff81473405: security_context_to_sid_core.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int security_context_to_sid_core(struct selinux_state *state, const char *scontext, u32 scontext_len, u32 *sid, u32 def_sid, gfp_t gfp_flags, int force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff814c9340)
Location: security/selinux/ss/services.c:1493
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_context_to_sid_force
  - security/selinux/ss/services.c:security_context_to_sid_default
  - security/selinux/ss/services.c:security_context_str_to_sid
```
**Symbols:**

```
ffffffff814c9340-ffffffff814c95ab: security_context_to_sid_core (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int security_context_to_sid_core(struct selinux_state *state, const char *scontext, u32 scontext_len, u32 *sid, u32 def_sid, gfp_t gfp_flags, int force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff814e6720)
Location: security/selinux/ss/services.c:1510
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_context_to_sid_force
  - security/selinux/ss/services.c:security_context_to_sid_default
  - security/selinux/ss/services.c:security_context_str_to_sid
```
**Symbols:**

```
ffffffff814e6720-ffffffff814e6921: security_context_to_sid_core (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int security_context_to_sid_core(struct selinux_state *state, const char *scontext, u32 scontext_len, u32 *sid, u32 def_sid, gfp_t gfp_flags, int force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff814edbf0)
Location: security/selinux/ss/services.c:1512
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_context_to_sid_force
  - security/selinux/ss/services.c:security_context_to_sid_default
  - security/selinux/ss/services.c:security_context_str_to_sid
```
**Symbols:**

```
ffffffff814edbf0-ffffffff814ede81: security_context_to_sid_core (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int security_context_to_sid_core(struct selinux_state *state, const char *scontext, u32 scontext_len, u32 *sid, u32 def_sid, gfp_t gfp_flags, int force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:1516
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_context_to_sid_force
  - security/selinux/ss/services.c:security_context_to_sid_default
  - security/selinux/ss/services.c:security_context_str_to_sid
```
**Symbols:**

```
ffffffff81548070-ffffffff81548327: security_context_to_sid_core (STB_LOCAL)
ffffffff81cd4bfc-ffffffff81cd4c11: security_context_to_sid_core.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int security_context_to_sid_core(struct selinux_state *state, const char *scontext, u32 scontext_len, u32 *sid, u32 def_sid, gfp_t gfp_flags, int force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:1514
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_context_to_sid_force
  - security/selinux/ss/services.c:security_context_to_sid_default
  - security/selinux/ss/services.c:security_context_str_to_sid
```
**Symbols:**

```
ffffffff815df5a0-ffffffff815df880: security_context_to_sid_core (STB_LOCAL)
ffffffff81e87a24-ffffffff81e87a39: security_context_to_sid_core.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int security_context_to_sid_core(struct selinux_state *state, const char *scontext, u32 scontext_len, u32 *sid, u32 def_sid, gfp_t gfp_flags, int force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:1508
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_context_to_sid_force
  - security/selinux/ss/services.c:security_context_to_sid_default
  - security/selinux/ss/services.c:security_context_str_to_sid
```
**Symbols:**

```
ffffffff8168fa90-ffffffff8168fd70: security_context_to_sid_core (STB_LOCAL)
ffffffff82073c4e-ffffffff82073c63: security_context_to_sid_core.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int security_context_to_sid_core(const char *scontext, u32 scontext_len, u32 *sid, u32 def_sid, gfp_t gfp_flags, int force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:1493
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_context_to_sid_force
  - security/selinux/ss/services.c:security_context_to_sid_default
  - security/selinux/ss/services.c:security_context_str_to_sid
```
**Symbols:**

```
ffffffff816c7f10-ffffffff816c81e3: security_context_to_sid_core (STB_LOCAL)
ffffffff820f3828-ffffffff820f383d: security_context_to_sid_core.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int security_context_to_sid_core(const char *scontext, u32 scontext_len, u32 *sid, u32 def_sid, gfp_t gfp_flags, int force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:1504
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_context_to_sid_force
  - security/selinux/ss/services.c:security_context_to_sid_default
  - security/selinux/ss/services.c:security_context_str_to_sid
```
**Symbols:**

```
ffffffff81704b20-ffffffff81704df5: security_context_to_sid_core (STB_LOCAL)
ffffffff821d09ee-ffffffff821d0a03: security_context_to_sid_core.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (ffff8000105639a0)
Location: security/selinux/ss/services.c:1452
Inline: True
Direct callers:
  - security/selinux/ss/services.c:security_context_to_sid_force
  - security/selinux/ss/services.c:security_context_to_sid_default
  - security/selinux/ss/services.c:security_context_str_to_sid
```
**Symbols:**

```
ffff8000105639a0-ffff800010563bf8: security_context_to_sid_core.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int security_context_to_sid_core(struct selinux_state *state, const char *scontext, u32 scontext_len, u32 *sid, u32 def_sid, gfp_t gfp_flags, int force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (c0716f24)
Location: security/selinux/ss/services.c:1452
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_context_to_sid_force
  - security/selinux/ss/services.c:security_context_to_sid_default
  - security/selinux/ss/services.c:security_context_str_to_sid
```
**Symbols:**

```
c0716f24-c0717178: security_context_to_sid_core (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (c0000000006c3f50)
Location: security/selinux/ss/services.c:1452
Inline: True
Direct callers:
  - security/selinux/ss/services.c:security_context_to_sid_force
  - security/selinux/ss/services.c:security_context_to_sid_default
  - security/selinux/ss/services.c:security_context_str_to_sid
```
**Symbols:**

```
c0000000006c3f50-c0000000006c43e8: security_context_to_sid_core.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (ffffffe0003b9bfe)
Location: security/selinux/ss/services.c:1452
Inline: True
Direct callers:
  - security/selinux/ss/services.c:security_context_to_sid_force
  - security/selinux/ss/services.c:security_context_to_sid_default
  - security/selinux/ss/services.c:security_context_str_to_sid
```
**Symbols:**

```
ffffffe0003b9bfe-ffffffe0003b9de2: security_context_to_sid_core.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8146b790)
Location: security/selinux/ss/services.c:1452
Inline: True
Direct callers:
  - security/selinux/ss/services.c:security_context_to_sid_force
  - security/selinux/ss/services.c:security_context_to_sid_default
  - security/selinux/ss/services.c:security_context_str_to_sid
```
**Symbols:**

```
ffffffff8146b790-ffffffff8146b9e5: security_context_to_sid_core.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8145c1c0)
Location: security/selinux/ss/services.c:1452
Inline: True
Direct callers:
  - security/selinux/ss/services.c:security_context_to_sid_force
  - security/selinux/ss/services.c:security_context_to_sid_default
  - security/selinux/ss/services.c:security_context_str_to_sid
```
**Symbols:**

```
ffffffff8145c1c0-ffffffff8145c415: security_context_to_sid_core.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (ffffffff81467830)
Location: security/selinux/ss/services.c:1452
Inline: True
Direct callers:
  - security/selinux/ss/services.c:security_context_to_sid_force
  - security/selinux/ss/services.c:security_context_to_sid_default
  - security/selinux/ss/services.c:security_context_str_to_sid
```
**Symbols:**

```
ffffffff81467830-ffffffff81467a85: security_context_to_sid_core.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8147f010)
Location: security/selinux/ss/services.c:1452
Inline: True
Direct callers:
  - security/selinux/ss/services.c:security_context_to_sid_force
  - security/selinux/ss/services.c:security_context_to_sid_default
  - security/selinux/ss/services.c:security_context_str_to_sid
```
**Symbols:**

```
ffffffff8147f010-ffffffff8147f264: security_context_to_sid_core.isra.0 (STB_LOCAL)
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct selinux_state *state</code>
</li>
<li>
<b>Param reordered. </b>
<code>state, scontext, scontext_len, sid, def_sid, gfp_flags, force</code> ➡️ <code>scontext, scontext_len, sid, def_sid, gfp_flags, force</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
</ul>
