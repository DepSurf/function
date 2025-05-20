# Function: <code>security_get_user_sids</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int security_get_user_sids(u32 fromsid, char *username, u32 **sids, u32 *nel);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff81358880)
Location: security/selinux/ss/services.c:2355
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_user
```
**Symbols:**

```
ffffffff81358880-ffffffff81358dc8: security_get_user_sids (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int security_get_user_sids(u32 fromsid, char *username, u32 **sids, u32 *nel);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8138e7e0)
Location: security/selinux/ss/services.c:2349
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_user
```
**Symbols:**

```
ffffffff8138e7e0-ffffffff8138ed2a: security_get_user_sids (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int security_get_user_sids(u32 fromsid, char *username, u32 **sids, u32 *nel);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff813a5400)
Location: security/selinux/ss/services.c:2349
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_user
```
**Symbols:**

```
ffffffff813a5400-ffffffff813a594a: security_get_user_sids (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int security_get_user_sids(u32 fromsid, char *username, u32 **sids, u32 *nel);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff813bbec0)
Location: security/selinux/ss/services.c:2465
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_user
```
**Symbols:**

```
ffffffff813bbec0-ffffffff813bc3b3: security_get_user_sids (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int security_get_user_sids(u32 fromsid, char *username, u32 **sids, u32 *nel);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff813e2030)
Location: security/selinux/ss/services.c:2475
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_user
```
**Symbols:**

```
ffffffff813e2030-ffffffff813e2523: security_get_user_sids (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int security_get_user_sids(struct selinux_state *state, u32 fromsid, char *username, u32 **sids, u32 *nel);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff81412dd0)
Location: security/selinux/ss/services.c:2562
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_user
```
**Symbols:**

```
ffffffff81412dd0-ffffffff81413345: security_get_user_sids (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int security_get_user_sids(struct selinux_state *state, u32 fromsid, char *username, u32 **sids, u32 *nel);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8142f310)
Location: security/selinux/ss/services.c:2528
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_user
```
**Symbols:**

```
ffffffff8142f310-ffffffff8142f88c: security_get_user_sids (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int security_get_user_sids(struct selinux_state *state, u32 fromsid, char *username, u32 **sids, u32 *nel);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8145ccb0)
Location: security/selinux/ss/services.c:2541
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_user
```
**Symbols:**

```
ffffffff8145ccb0-ffffffff8145d238: security_get_user_sids (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int security_get_user_sids(struct selinux_state *state, u32 fromsid, char *username, u32 **sids, u32 *nel);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff81476a60)
Location: security/selinux/ss/services.c:2548
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_user
```
**Symbols:**

```
ffffffff81476a60-ffffffff81476fe8: security_get_user_sids (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int security_get_user_sids(struct selinux_state *state, u32 fromsid, char *username, u32 **sids, u32 *nel);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff814cc0c0)
Location: security/selinux/ss/services.c:2591
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_user
```
**Symbols:**

```
ffffffff814cc0c0-ffffffff814cc647: security_get_user_sids (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int security_get_user_sids(struct selinux_state *state, u32 fromsid, char *username, u32 **sids, u32 *nel);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff814e94d0)
Location: security/selinux/ss/services.c:2666
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_user
```
**Symbols:**

```
ffffffff814e94d0-ffffffff814e9a43: security_get_user_sids (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int security_get_user_sids(struct selinux_state *state, u32 fromsid, char *username, u32 **sids, u32 *nel);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff814f0020)
Location: security/selinux/ss/services.c:2726
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_user
```
**Symbols:**

```
ffffffff814f0020-ffffffff814f05b3: security_get_user_sids (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int security_get_user_sids(struct selinux_state *state, u32 fromsid, char *username, u32 **sids, u32 *nel);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:2746
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_user
```
**Symbols:**

```
ffffffff81cd50a1-ffffffff81cd50b5: security_get_user_sids.cold (STB_LOCAL)
ffffffff8154a580-ffffffff8154ab1d: security_get_user_sids (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int security_get_user_sids(struct selinux_state *state, u32 fromsid, char *username, u32 **sids, u32 *nel);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:2748
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_user
```
**Symbols:**

```
ffffffff81e87eee-ffffffff81e87f02: security_get_user_sids.cold (STB_LOCAL)
ffffffff815e3280-ffffffff815e381d: security_get_user_sids (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int security_get_user_sids(struct selinux_state *state, u32 fromsid, char *username, u32 **sids, u32 *nel);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:2741
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_user
```
**Symbols:**

```
ffffffff82073dd7-ffffffff82073deb: security_get_user_sids.cold (STB_LOCAL)
ffffffff816924f0-ffffffff81692a84: security_get_user_sids (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int security_get_user_sids(u32 fromsid, char *username, u32 **sids, u32 *nel);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:2693
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_user
```
**Symbols:**

```
ffffffff820f3989-ffffffff820f399d: security_get_user_sids.cold (STB_LOCAL)
ffffffff816caa60-ffffffff816cafe8: security_get_user_sids (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int security_get_user_sids(u32 fromsid, char *username, u32 **sids, u32 *nel);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:2703
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_user
```
**Symbols:**

```
ffffffff821d0b4f-ffffffff821d0b63: security_get_user_sids.cold (STB_LOCAL)
ffffffff81707670-ffffffff81707c27: security_get_user_sids (STB_GLOBAL)
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
int security_get_user_sids(struct selinux_state *state, u32 fromsid, char *username, u32 **sids, u32 *nel);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffff8000105666e0)
Location: security/selinux/ss/services.c:2548
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_user
```
**Symbols:**

```
ffff8000105666e0-ffff800010566b60: security_get_user_sids (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int security_get_user_sids(struct selinux_state *state, u32 fromsid, char *username, u32 **sids, u32 *nel);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (c071acc0)
Location: security/selinux/ss/services.c:2548
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_user
```
**Symbols:**

```
c071acc0-c071b1c4: security_get_user_sids (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int security_get_user_sids(struct selinux_state *state, u32 fromsid, char *username, u32 **sids, u32 *nel);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (c0000000006c9320)
Location: security/selinux/ss/services.c:2548
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_user
```
**Symbols:**

```
c0000000006c9320-c0000000006c99d0: security_get_user_sids (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int security_get_user_sids(struct selinux_state *state, u32 fromsid, char *username, u32 **sids, u32 *nel);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffe0003bc6c4)
Location: security/selinux/ss/services.c:2548
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_user
```
**Symbols:**

```
ffffffe0003bc6c4-ffffffe0003bcb0e: security_get_user_sids (STB_GLOBAL)
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
int security_get_user_sids(struct selinux_state *state, u32 fromsid, char *username, u32 **sids, u32 *nel);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8146f040)
Location: security/selinux/ss/services.c:2548
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_user
```
**Symbols:**

```
ffffffff8146f040-ffffffff8146f5c8: security_get_user_sids (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int security_get_user_sids(struct selinux_state *state, u32 fromsid, char *username, u32 **sids, u32 *nel);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8145fa60)
Location: security/selinux/ss/services.c:2548
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_user
```
**Symbols:**

```
ffffffff8145fa60-ffffffff8145ffe8: security_get_user_sids (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int security_get_user_sids(struct selinux_state *state, u32 fromsid, char *username, u32 **sids, u32 *nel);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8146b0e0)
Location: security/selinux/ss/services.c:2548
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_user
```
**Symbols:**

```
ffffffff8146b0e0-ffffffff8146b668: security_get_user_sids (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int security_get_user_sids(struct selinux_state *state, u32 fromsid, char *username, u32 **sids, u32 *nel);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff81482890)
Location: security/selinux/ss/services.c:2548
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_user
```
**Symbols:**

```
ffffffff81482890-ffffffff81482e16: security_get_user_sids (STB_GLOBAL)
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
<code>fromsid, username, sids, nel</code> ➡️ <code>state, fromsid, username, sids, nel</code>
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
<code>state, fromsid, username, sids, nel</code> ➡️ <code>fromsid, username, sids, nel</code>
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
