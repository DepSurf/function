# Function: <code>security_get_permissions</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int security_get_permissions(char *class, char ***perms, int *nperms);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff81359ef0)
Location: security/selinux/ss/services.c:2931
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_load
```
**Symbols:**

```
ffffffff81359ef0-ffffffff8135a038: security_get_permissions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int security_get_permissions(char *class, char ***perms, int *nperms);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8138fea0)
Location: security/selinux/ss/services.c:2925
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_load
```
**Symbols:**

```
ffffffff8138fea0-ffffffff8138fff4: security_get_permissions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int security_get_permissions(char *class, char ***perms, int *nperms);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff813a6ac0)
Location: security/selinux/ss/services.c:2925
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_load
```
**Symbols:**

```
ffffffff813a6ac0-ffffffff813a6c14: security_get_permissions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int security_get_permissions(char *class, char ***perms, int *nperms);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff813bd4f0)
Location: security/selinux/ss/services.c:3041
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_load
```
**Symbols:**

```
ffffffff813bd4f0-ffffffff813bd63f: security_get_permissions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int security_get_permissions(char *class, char ***perms, int *nperms);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff813e3660)
Location: security/selinux/ss/services.c:3051
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_load
```
**Symbols:**

```
ffffffff813e3660-ffffffff813e37af: security_get_permissions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int security_get_permissions(struct selinux_state *state, char *class, char ***perms, int *nperms);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:3193
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
```
**Symbols:**

```
ffffffff81414e12-ffffffff81414e33: security_get_permissions.cold.40 (STB_LOCAL)
ffffffff81413e10-ffffffff81413f4a: security_get_permissions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int security_get_permissions(struct selinux_state *state, char *class, char ***perms, int *nperms);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:3159
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
```
**Symbols:**

```
ffffffff814313cd-ffffffff814313ee: security_get_permissions.cold.40 (STB_LOCAL)
ffffffff81430360-ffffffff8143049a: security_get_permissions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int security_get_permissions(struct selinux_state *state, char *class, char ***perms, int *nperms);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:3178
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
```
**Symbols:**

```
ffffffff8145ee98-ffffffff8145eeb9: security_get_permissions.cold (STB_LOCAL)
ffffffff8145dd00-ffffffff8145de3a: security_get_permissions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int security_get_permissions(struct selinux_state *state, char *class, char ***perms, int *nperms);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:3185
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
```
**Symbols:**

```
ffffffff81478c4a-ffffffff81478c6b: security_get_permissions.cold (STB_LOCAL)
ffffffff81477ab0-ffffffff81477bea: security_get_permissions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int security_get_permissions(struct selinux_state *state, char *class, char ***perms, int *nperms);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:3223
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_make_perm_files
```
**Symbols:**

```
ffffffff814ce0e7-ffffffff814ce108: security_get_permissions.cold (STB_LOCAL)
ffffffff814ccf30-ffffffff814cd06a: security_get_permissions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int security_get_permissions(struct selinux_policy *policy, char *class, char ***perms, int *nperms);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:3353
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_make_perm_files
```
**Symbols:**

```
ffffffff81bf1143-ffffffff81bf1164: security_get_permissions.cold (STB_LOCAL)
ffffffff814ea680-ffffffff814ea775: security_get_permissions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int security_get_permissions(struct selinux_policy *policy, char *class, char ***perms, int *nperms);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:3436
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_make_classes
```
**Symbols:**

```
ffffffff81be3286-ffffffff81be32a7: security_get_permissions.cold (STB_LOCAL)
ffffffff814f12e0-ffffffff814f13d5: security_get_permissions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int security_get_permissions(struct selinux_policy *policy, char *class, char ***perms, int *nperms);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:3444
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_make_classes
```
**Symbols:**

```
ffffffff81cd5275-ffffffff81cd5296: security_get_permissions.cold (STB_LOCAL)
ffffffff8154b920-ffffffff8154ba15: security_get_permissions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int security_get_permissions(struct selinux_policy *policy, char *class, char ***perms, int *nperms);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:3447
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_make_classes
```
**Symbols:**

```
ffffffff81e880b2-ffffffff81e880d3: security_get_permissions.cold (STB_LOCAL)
ffffffff815e4740-ffffffff815e4847: security_get_permissions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int security_get_permissions(struct selinux_policy *policy, char *class, char ***perms, int *nperms);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff81693af0)
Location: security/selinux/ss/services.c:3440
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_make_classes
```
**Symbols:**

```
ffffffff81693af0-ffffffff81693c18: security_get_permissions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int security_get_permissions(struct selinux_policy *policy, char *class, char ***perms, int *nperms);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff816cbff0)
Location: security/selinux/ss/services.c:3384
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_make_classes
```
**Symbols:**

```
ffffffff816cbff0-ffffffff816cc121: security_get_permissions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int security_get_permissions(struct selinux_policy *policy, const char *class, char ***perms, u32 *nperms);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff81708ca0)
Location: security/selinux/ss/services.c:3394
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_make_classes
```
**Symbols:**

```
ffffffff81708ca0-ffffffff81708dae: security_get_permissions (STB_GLOBAL)
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
int security_get_permissions(struct selinux_state *state, char *class, char ***perms, int *nperms);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffff800010567940)
Location: security/selinux/ss/services.c:3185
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
```
**Symbols:**

```
ffff800010567940-ffff800010567b2c: security_get_permissions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int security_get_permissions(struct selinux_state *state, char *class, char ***perms, int *nperms);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (c071bd9c)
Location: security/selinux/ss/services.c:3185
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
```
**Symbols:**

```
c071bd9c-c071bf34: security_get_permissions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int security_get_permissions(struct selinux_state *state, char *class, char ***perms, int *nperms);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (c0000000006cae10)
Location: security/selinux/ss/services.c:3185
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
```
**Symbols:**

```
c0000000006cae10-c0000000006cb00c: security_get_permissions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int security_get_permissions(struct selinux_state *state, char *class, char ***perms, int *nperms);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffe0003bd4d2)
Location: security/selinux/ss/services.c:3185
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
```
**Symbols:**

```
ffffffe0003bd4d2-ffffffe0003bd608: security_get_permissions (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int security_get_permissions(struct selinux_state *state, char *class, char ***perms, int *nperms);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:3185
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
```
**Symbols:**

```
ffffffff8147122a-ffffffff8147124b: security_get_permissions.cold (STB_LOCAL)
ffffffff81470090-ffffffff814701ca: security_get_permissions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int security_get_permissions(struct selinux_state *state, char *class, char ***perms, int *nperms);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:3185
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
```
**Symbols:**

```
ffffffff81461c4a-ffffffff81461c6b: security_get_permissions.cold (STB_LOCAL)
ffffffff81460ab0-ffffffff81460bea: security_get_permissions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int security_get_permissions(struct selinux_state *state, char *class, char ***perms, int *nperms);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:3185
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
```
**Symbols:**

```
ffffffff8146d2ca-ffffffff8146d2eb: security_get_permissions.cold (STB_LOCAL)
ffffffff8146c130-ffffffff8146c26a: security_get_permissions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int security_get_permissions(struct selinux_state *state, char *class, char ***perms, int *nperms);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:3185
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
```
**Symbols:**

```
ffffffff81484b36-ffffffff81484b57: security_get_permissions.cold (STB_LOCAL)
ffffffff814838f0-ffffffff81483a25: security_get_permissions (STB_GLOBAL)
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
<code>struct selinux_state *state</code>
</li>
<li>
<b>Param reordered. </b>
<code>class, perms, nperms</code> ➡️ <code>state, class, perms, nperms</code>
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct selinux_policy *policy</code>
</li>
<li>
<b>Param removed. </b>
<code>struct selinux_state *state</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>char *class</code> ➡️ <code>const char *class</code>
</li>
<li>
<b>Param type changed. </b>
<code>int *nperms</code> ➡️ <code>u32 *nperms</code>
</li>
</ul>
</details>
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
