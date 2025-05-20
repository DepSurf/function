# Function: <code>security_sid_to_context_core</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int security_sid_to_context_core(u32 sid, char **scontext, u32 *scontext_len, int force);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff81355460)
Location: security/selinux/ss/services.c:1242
Inline: True
Direct callers:
  - security/selinux/ss/services.c:security_sid_to_context
  - security/selinux/ss/services.c:security_sid_to_context_force
```
**Symbols:**

```
ffffffff81355460-ffffffff81355591: security_sid_to_context_core (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int security_sid_to_context_core(u32 sid, char **scontext, u32 *scontext_len, int force);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8138b3e0)
Location: security/selinux/ss/services.c:1236
Inline: True
Direct callers:
  - security/selinux/ss/services.c:security_sid_to_context_force
  - security/selinux/ss/services.c:security_sid_to_context
```
**Symbols:**

```
ffffffff8138b3e0-ffffffff8138b50e: security_sid_to_context_core (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int security_sid_to_context_core(u32 sid, char **scontext, u32 *scontext_len, int force);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff813a1ff0)
Location: security/selinux/ss/services.c:1236
Inline: True
Direct callers:
  - security/selinux/ss/services.c:security_sid_to_context_force
  - security/selinux/ss/services.c:security_sid_to_context
```
**Symbols:**

```
ffffffff813a1ff0-ffffffff813a211e: security_sid_to_context_core (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int security_sid_to_context_core(u32 sid, char **scontext, u32 *scontext_len, int force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff813b8990)
Location: security/selinux/ss/services.c:1248
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_sid_to_context_force
  - security/selinux/ss/services.c:security_sid_to_context
```
**Symbols:**

```
ffffffff813b8990-ffffffff813b8abe: security_sid_to_context_core (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int security_sid_to_context_core(u32 sid, char **scontext, u32 *scontext_len, int force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff813deb00)
Location: security/selinux/ss/services.c:1253
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_sid_to_context_force
  - security/selinux/ss/services.c:security_sid_to_context
```
**Symbols:**

```
ffffffff813deb00-ffffffff813dec2e: security_sid_to_context_core (STB_LOCAL)
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
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:1284
Inline: True
Direct callers:
  - security/selinux/ss/services.c:security_sid_to_context_force
  - security/selinux/ss/services.c:security_sid_to_context
```
**Symbols:**

```
ffffffff8140f030-ffffffff8140f147: security_sid_to_context_core.isra.15 (STB_LOCAL)
ffffffff814149be-ffffffff814149fe: security_sid_to_context_core.isra.15.cold.26 (STB_LOCAL)
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
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:1281
Inline: True
Direct callers:
  - security/selinux/ss/services.c:security_sid_to_context_force
  - security/selinux/ss/services.c:security_sid_to_context
```
**Symbols:**

```
ffffffff8142b540-ffffffff8142b65a: security_sid_to_context_core.isra.15 (STB_LOCAL)
ffffffff81430f9e-ffffffff81430fde: security_sid_to_context_core.isra.15.cold.26 (STB_LOCAL)
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
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:1267
Inline: True
Direct callers:
  - security/selinux/ss/services.c:security_sid_to_context_inval
  - security/selinux/ss/services.c:security_sid_to_context_force
  - security/selinux/ss/services.c:security_sid_to_context
```
**Symbols:**

```
ffffffff81459ad0-ffffffff81459c02: security_sid_to_context_core.isra.0 (STB_LOCAL)
ffffffff8145ea42-ffffffff8145ea82: security_sid_to_context_core.isra.0.cold (STB_LOCAL)
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
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:1267
Inline: True
Direct callers:
  - security/selinux/ss/services.c:security_sid_to_context_inval
  - security/selinux/ss/services.c:security_sid_to_context_force
  - security/selinux/ss/services.c:security_sid_to_context
```
**Symbols:**

```
ffffffff81473870-ffffffff814739a2: security_sid_to_context_core.isra.0 (STB_LOCAL)
ffffffff814787f2-ffffffff81478832: security_sid_to_context_core.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int security_sid_to_context_core(struct selinux_state *state, u32 sid, char **scontext, u32 *scontext_len, int force, int only_invalid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:1308
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_sid_to_context_inval
  - security/selinux/ss/services.c:security_sid_to_context_force
  - security/selinux/ss/services.c:security_sid_to_context
```
**Symbols:**

```
ffffffff814c9c60-ffffffff814c9dd0: security_sid_to_context_core (STB_LOCAL)
ffffffff814cdda5-ffffffff814cdde5: security_sid_to_context_core.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int security_sid_to_context_core(struct selinux_state *state, u32 sid, char **scontext, u32 *scontext_len, int force, int only_invalid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:1323
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_sid_to_context_inval
  - security/selinux/ss/services.c:security_sid_to_context_force
  - security/selinux/ss/services.c:security_sid_to_context
```
**Symbols:**

```
ffffffff814e5df0-ffffffff814e5f10: security_sid_to_context_core (STB_LOCAL)
ffffffff81bf0d19-ffffffff81bf0d5b: security_sid_to_context_core.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int security_sid_to_context_core(struct selinux_state *state, u32 sid, char **scontext, u32 *scontext_len, int force, int only_invalid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:1325
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_sid_to_context_inval
  - security/selinux/ss/services.c:security_sid_to_context_force
  - security/selinux/ss/services.c:security_sid_to_context
```
**Symbols:**

```
ffffffff814ec580-ffffffff814ec6a3: security_sid_to_context_core (STB_LOCAL)
ffffffff81be2e5a-ffffffff81be2e9c: security_sid_to_context_core.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int security_sid_to_context_core(struct selinux_state *state, u32 sid, char **scontext, u32 *scontext_len, int force, int only_invalid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:1327
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_sid_to_context_inval
  - security/selinux/ss/services.c:security_sid_to_context_force
  - security/selinux/ss/services.c:security_sid_to_context
```
**Symbols:**

```
ffffffff81547f20-ffffffff8154806a: security_sid_to_context_core (STB_LOCAL)
ffffffff81cd4b95-ffffffff81cd4bfc: security_sid_to_context_core.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int security_sid_to_context_core(struct selinux_state *state, u32 sid, char **scontext, u32 *scontext_len, int force, int only_invalid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:1325
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_sid_to_context_inval
  - security/selinux/ss/services.c:security_sid_to_context_force
  - security/selinux/ss/services.c:security_sid_to_context
```
**Symbols:**

```
ffffffff815df220-ffffffff815df383: security_sid_to_context_core (STB_LOCAL)
ffffffff81e879bd-ffffffff81e87a24: security_sid_to_context_core.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int security_sid_to_context_core(struct selinux_state *state, u32 sid, char **scontext, u32 *scontext_len, int force, int only_invalid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:1319
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_sid_to_context_inval
  - security/selinux/ss/services.c:security_sid_to_context_force
  - security/selinux/ss/services.c:security_sid_to_context
```
**Symbols:**

```
ffffffff8168df20-ffffffff8168e0b2: security_sid_to_context_core (STB_LOCAL)
ffffffff82073bbc-ffffffff82073bdf: security_sid_to_context_core.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int security_sid_to_context_core(u32 sid, char **scontext, u32 *scontext_len, int force, int only_invalid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:1308
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_sid_to_context_inval
  - security/selinux/ss/services.c:security_sid_to_context_force
  - security/selinux/ss/services.c:security_sid_to_context
```
**Symbols:**

```
ffffffff816c6310-ffffffff816c64ab: security_sid_to_context_core (STB_LOCAL)
ffffffff820f37a0-ffffffff820f37bb: security_sid_to_context_core.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int security_sid_to_context_core(u32 sid, char **scontext, u32 *scontext_len, int force, int only_invalid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:1308
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_sid_to_context_inval
  - security/selinux/ss/services.c:security_sid_to_context_force
  - security/selinux/ss/services.c:security_sid_to_context
```
**Symbols:**

```
ffffffff81703ac0-ffffffff81703c65: security_sid_to_context_core (STB_LOCAL)
ffffffff821d097b-ffffffff821d0996: security_sid_to_context_core.cold (STB_LOCAL)
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
In security/selinux/ss/services.c (ffff800010563bf8)
Location: security/selinux/ss/services.c:1267
Inline: True
Direct callers:
  - security/selinux/ss/services.c:security_sid_to_context_inval
  - security/selinux/ss/services.c:security_sid_to_context_force
  - security/selinux/ss/services.c:security_sid_to_context
```
**Symbols:**

```
ffff800010563bf8-ffff800010563de0: security_sid_to_context_core.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int security_sid_to_context_core(struct selinux_state *state, u32 sid, char **scontext, u32 *scontext_len, int force, int only_invalid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (c07175fc)
Location: security/selinux/ss/services.c:1267
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_sid_to_context_inval
  - security/selinux/ss/services.c:security_sid_to_context_force
  - security/selinux/ss/services.c:security_sid_to_context
```
**Symbols:**

```
c07175fc-c0717778: security_sid_to_context_core (STB_LOCAL)
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
In security/selinux/ss/services.c (c0000000006c49d0)
Location: security/selinux/ss/services.c:1267
Inline: True
Direct callers:
  - security/selinux/ss/services.c:security_sid_to_context_inval
  - security/selinux/ss/services.c:security_sid_to_context_force
  - security/selinux/ss/services.c:security_sid_to_context
```
**Symbols:**

```
c0000000006c49d0-c0000000006c4c14: security_sid_to_context_core.isra.0 (STB_LOCAL)
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
In security/selinux/ss/services.c (ffffffe0003b8f1a)
Location: security/selinux/ss/services.c:1267
Inline: True
Direct callers:
  - security/selinux/ss/services.c:security_sid_to_context_inval
  - security/selinux/ss/services.c:security_sid_to_context_force
  - security/selinux/ss/services.c:security_sid_to_context
```
**Symbols:**

```
ffffffe0003b8f1a-ffffffe0003b9064: security_sid_to_context_core.isra.0 (STB_LOCAL)
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
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:1267
Inline: True
Direct callers:
  - security/selinux/ss/services.c:security_sid_to_context_inval
  - security/selinux/ss/services.c:security_sid_to_context_force
  - security/selinux/ss/services.c:security_sid_to_context
```
**Symbols:**

```
ffffffff8146be50-ffffffff8146bf82: security_sid_to_context_core.isra.0 (STB_LOCAL)
ffffffff81470dd2-ffffffff81470e12: security_sid_to_context_core.isra.0.cold (STB_LOCAL)
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
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:1267
Inline: True
Direct callers:
  - security/selinux/ss/services.c:security_sid_to_context_inval
  - security/selinux/ss/services.c:security_sid_to_context_force
  - security/selinux/ss/services.c:security_sid_to_context
```
**Symbols:**

```
ffffffff8145c880-ffffffff8145c9b2: security_sid_to_context_core.isra.0 (STB_LOCAL)
ffffffff814617f2-ffffffff81461832: security_sid_to_context_core.isra.0.cold (STB_LOCAL)
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
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:1267
Inline: True
Direct callers:
  - security/selinux/ss/services.c:security_sid_to_context_inval
  - security/selinux/ss/services.c:security_sid_to_context_force
  - security/selinux/ss/services.c:security_sid_to_context
```
**Symbols:**

```
ffffffff81467ef0-ffffffff81468022: security_sid_to_context_core.isra.0 (STB_LOCAL)
ffffffff8146ce72-ffffffff8146ceb2: security_sid_to_context_core.isra.0.cold (STB_LOCAL)
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
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:1267
Inline: True
Direct callers:
  - security/selinux/ss/services.c:security_sid_to_context_inval
  - security/selinux/ss/services.c:security_sid_to_context_force
  - security/selinux/ss/services.c:security_sid_to_context
```
**Symbols:**

```
ffffffff8147f6c0-ffffffff8147f7e4: security_sid_to_context_core.isra.0 (STB_LOCAL)
ffffffff814846dc-ffffffff8148471e: security_sid_to_context_core.isra.0.cold (STB_LOCAL)
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
<code>state, sid, scontext, scontext_len, force, only_invalid</code> ➡️ <code>sid, scontext, scontext_len, force, only_invalid</code>
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
