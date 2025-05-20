# Function: <code>security_ib_endport_sid</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int security_ib_endport_sid(const char *dev_name, u8 port_num, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff813bbc30)
Location: security/selinux/ss/services.c:2286
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ib_endport_manage_subnet
```
**Symbols:**

```
ffffffff813bbc30-ffffffff813bbcea: security_ib_endport_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int security_ib_endport_sid(const char *dev_name, u8 port_num, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff813e1da0)
Location: security/selinux/ss/services.c:2296
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ib_endport_manage_subnet
```
**Symbols:**

```
ffffffff813e1da0-ffffffff813e1e5a: security_ib_endport_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int security_ib_endport_sid(struct selinux_state *state, const char *dev_name, u8 port_num, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff81412ae0)
Location: security/selinux/ss/services.c:2365
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ib_endport_manage_subnet
```
**Symbols:**

```
ffffffff81412ae0-ffffffff81412bbd: security_ib_endport_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int security_ib_endport_sid(struct selinux_state *state, const char *dev_name, u8 port_num, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8142f020)
Location: security/selinux/ss/services.c:2331
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ib_endport_manage_subnet
```
**Symbols:**

```
ffffffff8142f020-ffffffff8142f0fd: security_ib_endport_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int security_ib_endport_sid(struct selinux_state *state, const char *dev_name, u8 port_num, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8145c9d0)
Location: security/selinux/ss/services.c:2344
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ib_endport_manage_subnet
```
**Symbols:**

```
ffffffff8145c9d0-ffffffff8145caad: security_ib_endport_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int security_ib_endport_sid(struct selinux_state *state, const char *dev_name, u8 port_num, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff81476780)
Location: security/selinux/ss/services.c:2351
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ib_endport_manage_subnet
```
**Symbols:**

```
ffffffff81476780-ffffffff8147685d: security_ib_endport_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int security_ib_endport_sid(struct selinux_state *state, const char *dev_name, u8 port_num, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff814cbdd0)
Location: security/selinux/ss/services.c:2397
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ib_endport_manage_subnet
```
**Symbols:**

```
ffffffff814cbdd0-ffffffff814cbead: security_ib_endport_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int security_ib_endport_sid(struct selinux_state *state, const char *dev_name, u8 port_num, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff814e91f0)
Location: security/selinux/ss/services.c:2454
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ib_endport_manage_subnet
```
**Symbols:**

```
ffffffff814e91f0-ffffffff814e92b9: security_ib_endport_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int security_ib_endport_sid(struct selinux_state *state, const char *dev_name, u8 port_num, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff814efcc0)
Location: security/selinux/ss/services.c:2493
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ib_endport_manage_subnet
```
**Symbols:**

```
ffffffff814efcc0-ffffffff814efda8: security_ib_endport_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int security_ib_endport_sid(struct selinux_state *state, const char *dev_name, u8 port_num, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:2531
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ib_endport_manage_subnet
```
**Symbols:**

```
ffffffff81cd5065-ffffffff81cd5079: security_ib_endport_sid.cold (STB_LOCAL)
ffffffff8154a1a0-ffffffff8154a2d2: security_ib_endport_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int security_ib_endport_sid(struct selinux_state *state, const char *dev_name, u8 port_num, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:2533
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ib_endport_manage_subnet
```
**Symbols:**

```
ffffffff81e87eb1-ffffffff81e87ec5: security_ib_endport_sid.cold (STB_LOCAL)
ffffffff815e2e70-ffffffff815e2fa2: security_ib_endport_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int security_ib_endport_sid(struct selinux_state *state, const char *dev_name, u8 port_num, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:2526
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ib_endport_manage_subnet
```
**Symbols:**

```
ffffffff82073d9a-ffffffff82073dae: security_ib_endport_sid.cold (STB_LOCAL)
ffffffff816920b0-ffffffff816921e2: security_ib_endport_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int security_ib_endport_sid(const char *dev_name, u8 port_num, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:2484
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ib_endport_manage_subnet
```
**Symbols:**

```
ffffffff820f394d-ffffffff820f3961: security_ib_endport_sid.cold (STB_LOCAL)
ffffffff816ca610-ffffffff816ca73b: security_ib_endport_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int security_ib_endport_sid(const char *dev_name, u8 port_num, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:2494
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ib_endport_manage_subnet
```
**Symbols:**

```
ffffffff821d0b13-ffffffff821d0b27: security_ib_endport_sid.cold (STB_LOCAL)
ffffffff81707220-ffffffff8170734b: security_ib_endport_sid (STB_GLOBAL)
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
int security_ib_endport_sid(struct selinux_state *state, const char *dev_name, u8 port_num, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffff8000105662b0)
Location: security/selinux/ss/services.c:2351
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ib_endport_manage_subnet
```
**Symbols:**

```
ffff8000105662b0-ffff8000105663f8: security_ib_endport_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int security_ib_endport_sid(struct selinux_state *state, const char *dev_name, u8 port_num, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (c071a960)
Location: security/selinux/ss/services.c:2351
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ib_endport_manage_subnet
```
**Symbols:**

```
c071a960-c071aa50: security_ib_endport_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int security_ib_endport_sid(struct selinux_state *state, const char *dev_name, u8 port_num, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (c0000000006c8b50)
Location: security/selinux/ss/services.c:2351
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ib_endport_manage_subnet
```
**Symbols:**

```
c0000000006c8b50-c0000000006c8e1c: security_ib_endport_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int security_ib_endport_sid(struct selinux_state *state, const char *dev_name, u8 port_num, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffe0003bc444)
Location: security/selinux/ss/services.c:2351
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ib_endport_manage_subnet
```
**Symbols:**

```
ffffffe0003bc444-ffffffe0003bc506: security_ib_endport_sid (STB_GLOBAL)
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
int security_ib_endport_sid(struct selinux_state *state, const char *dev_name, u8 port_num, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8146ed60)
Location: security/selinux/ss/services.c:2351
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ib_endport_manage_subnet
```
**Symbols:**

```
ffffffff8146ed60-ffffffff8146ee3d: security_ib_endport_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int security_ib_endport_sid(struct selinux_state *state, const char *dev_name, u8 port_num, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8145f780)
Location: security/selinux/ss/services.c:2351
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ib_endport_manage_subnet
```
**Symbols:**

```
ffffffff8145f780-ffffffff8145f85d: security_ib_endport_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int security_ib_endport_sid(struct selinux_state *state, const char *dev_name, u8 port_num, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8146ae00)
Location: security/selinux/ss/services.c:2351
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ib_endport_manage_subnet
```
**Symbols:**

```
ffffffff8146ae00-ffffffff8146aedd: security_ib_endport_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int security_ib_endport_sid(struct selinux_state *state, const char *dev_name, u8 port_num, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff81482590)
Location: security/selinux/ss/services.c:2351
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ib_endport_manage_subnet
```
**Symbols:**

```
ffffffff81482590-ffffffff8148266b: security_ib_endport_sid (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<code>dev_name, port_num, out_sid</code> ➡️ <code>state, dev_name, port_num, out_sid</code>
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct selinux_state *state</code>
</li>
<li>
<b>Param reordered. </b>
<code>state, dev_name, port_num, out_sid</code> ➡️ <code>dev_name, port_num, out_sid</code>
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
