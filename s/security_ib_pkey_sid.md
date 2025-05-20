# Function: <code>security_ib_pkey_sid</code>

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
int security_ib_pkey_sid(u64 subnet_prefix, u16 pkey_num, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff813bbb80)
Location: security/selinux/ss/services.c:2246
Inline: False
Direct callers:
  - security/selinux/ibpkey.c:sel_ib_pkey_sid
```
**Symbols:**

```
ffffffff813bbb80-ffffffff813bbc28: security_ib_pkey_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int security_ib_pkey_sid(u64 subnet_prefix, u16 pkey_num, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff813e1cf0)
Location: security/selinux/ss/services.c:2256
Inline: False
Direct callers:
  - security/selinux/ibpkey.c:sel_ib_pkey_sid
```
**Symbols:**

```
ffffffff813e1cf0-ffffffff813e1d98: security_ib_pkey_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int security_ib_pkey_sid(struct selinux_state *state, u64 subnet_prefix, u16 pkey_num, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff81412a30)
Location: security/selinux/ss/services.c:2319
Inline: False
Direct callers:
  - security/selinux/ibpkey.c:sel_ib_pkey_sid
```
**Symbols:**

```
ffffffff81412a30-ffffffff81412adf: security_ib_pkey_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int security_ib_pkey_sid(struct selinux_state *state, u64 subnet_prefix, u16 pkey_num, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8142ef60)
Location: security/selinux/ss/services.c:2285
Inline: False
Direct callers:
  - security/selinux/ibpkey.c:sel_ib_pkey_sid
```
**Symbols:**

```
ffffffff8142ef60-ffffffff8142f012: security_ib_pkey_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int security_ib_pkey_sid(struct selinux_state *state, u64 subnet_prefix, u16 pkey_num, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8145c910)
Location: security/selinux/ss/services.c:2298
Inline: False
Direct callers:
  - security/selinux/ibpkey.c:sel_ib_pkey_sid
```
**Symbols:**

```
ffffffff8145c910-ffffffff8145c9c2: security_ib_pkey_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int security_ib_pkey_sid(struct selinux_state *state, u64 subnet_prefix, u16 pkey_num, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff814766c0)
Location: security/selinux/ss/services.c:2305
Inline: False
Direct callers:
  - security/selinux/ibpkey.c:sel_ib_pkey_sid
```
**Symbols:**

```
ffffffff814766c0-ffffffff81476772: security_ib_pkey_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int security_ib_pkey_sid(struct selinux_state *state, u64 subnet_prefix, u16 pkey_num, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff814cbd10)
Location: security/selinux/ss/services.c:2351
Inline: False
Direct callers:
  - security/selinux/ibpkey.c:sel_ib_pkey_sid_slow
```
**Symbols:**

```
ffffffff814cbd10-ffffffff814cbdca: security_ib_pkey_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int security_ib_pkey_sid(struct selinux_state *state, u64 subnet_prefix, u16 pkey_num, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff814e9140)
Location: security/selinux/ss/services.c:2402
Inline: False
Direct callers:
  - security/selinux/ibpkey.c:sel_ib_pkey_sid_slow
```
**Symbols:**

```
ffffffff814e9140-ffffffff814e91ef: security_ib_pkey_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int security_ib_pkey_sid(struct selinux_state *state, u64 subnet_prefix, u16 pkey_num, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff814efbe0)
Location: security/selinux/ss/services.c:2435
Inline: False
Direct callers:
  - security/selinux/ibpkey.c:sel_ib_pkey_sid
```
**Symbols:**

```
ffffffff814efbe0-ffffffff814efcb1: security_ib_pkey_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int security_ib_pkey_sid(struct selinux_state *state, u64 subnet_prefix, u16 pkey_num, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:2477
Inline: False
Direct callers:
  - security/selinux/ibpkey.c:sel_ib_pkey_sid
```
**Symbols:**

```
ffffffff81cd5051-ffffffff81cd5065: security_ib_pkey_sid.cold (STB_LOCAL)
ffffffff8154a0a0-ffffffff8154a19a: security_ib_pkey_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int security_ib_pkey_sid(struct selinux_state *state, u64 subnet_prefix, u16 pkey_num, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:2479
Inline: False
Direct callers:
  - security/selinux/ibpkey.c:sel_ib_pkey_sid
```
**Symbols:**

```
ffffffff81e87e95-ffffffff81e87eb1: security_ib_pkey_sid.cold (STB_LOCAL)
ffffffff815e2d40-ffffffff815e2e6b: security_ib_pkey_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int security_ib_pkey_sid(struct selinux_state *state, u64 subnet_prefix, u16 pkey_num, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:2472
Inline: False
Direct callers:
  - security/selinux/ibpkey.c:sel_ib_pkey_sid
```
**Symbols:**

```
ffffffff82073d7e-ffffffff82073d9a: security_ib_pkey_sid.cold (STB_LOCAL)
ffffffff81691f70-ffffffff8169209b: security_ib_pkey_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int security_ib_pkey_sid(u64 subnet_prefix, u16 pkey_num, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:2432
Inline: False
Direct callers:
  - security/selinux/ibpkey.c:sel_ib_pkey_sid
```
**Symbols:**

```
ffffffff820f3939-ffffffff820f394d: security_ib_pkey_sid.cold (STB_LOCAL)
ffffffff816ca4e0-ffffffff816ca5f2: security_ib_pkey_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int security_ib_pkey_sid(u64 subnet_prefix, u16 pkey_num, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:2442
Inline: False
Direct callers:
  - security/selinux/ibpkey.c:sel_ib_pkey_sid
```
**Symbols:**

```
ffffffff821d0aff-ffffffff821d0b13: security_ib_pkey_sid.cold (STB_LOCAL)
ffffffff817070f0-ffffffff81707202: security_ib_pkey_sid (STB_GLOBAL)
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
int security_ib_pkey_sid(struct selinux_state *state, u64 subnet_prefix, u16 pkey_num, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffff800010566178)
Location: security/selinux/ss/services.c:2305
Inline: False
Direct callers:
  - security/selinux/ibpkey.c:sel_ib_pkey_sid
```
**Symbols:**

```
ffff800010566178-ffff8000105662ac: security_ib_pkey_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int security_ib_pkey_sid(struct selinux_state *state, u64 subnet_prefix, u16 pkey_num, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (c071a868)
Location: security/selinux/ss/services.c:2305
Inline: False
Direct callers:
  - security/selinux/ibpkey.c:sel_ib_pkey_sid
```
**Symbols:**

```
c071a868-c071a960: security_ib_pkey_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int security_ib_pkey_sid(struct selinux_state *state, u64 subnet_prefix, u16 pkey_num, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (c0000000006c8a20)
Location: security/selinux/ss/services.c:2305
Inline: False
Direct callers:
  - security/selinux/ibpkey.c:sel_ib_pkey_sid
```
**Symbols:**

```
c0000000006c8a20-c0000000006c8b44: security_ib_pkey_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int security_ib_pkey_sid(struct selinux_state *state, u64 subnet_prefix, u16 pkey_num, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffe0003bc394)
Location: security/selinux/ss/services.c:2305
Inline: False
Direct callers:
  - security/selinux/ibpkey.c:sel_ib_pkey_sid
```
**Symbols:**

```
ffffffe0003bc394-ffffffe0003bc444: security_ib_pkey_sid (STB_GLOBAL)
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
int security_ib_pkey_sid(struct selinux_state *state, u64 subnet_prefix, u16 pkey_num, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8146eca0)
Location: security/selinux/ss/services.c:2305
Inline: False
Direct callers:
  - security/selinux/ibpkey.c:sel_ib_pkey_sid
```
**Symbols:**

```
ffffffff8146eca0-ffffffff8146ed52: security_ib_pkey_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int security_ib_pkey_sid(struct selinux_state *state, u64 subnet_prefix, u16 pkey_num, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8145f6c0)
Location: security/selinux/ss/services.c:2305
Inline: False
Direct callers:
  - security/selinux/ibpkey.c:sel_ib_pkey_sid
```
**Symbols:**

```
ffffffff8145f6c0-ffffffff8145f772: security_ib_pkey_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int security_ib_pkey_sid(struct selinux_state *state, u64 subnet_prefix, u16 pkey_num, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8146ad40)
Location: security/selinux/ss/services.c:2305
Inline: False
Direct callers:
  - security/selinux/ibpkey.c:sel_ib_pkey_sid
```
**Symbols:**

```
ffffffff8146ad40-ffffffff8146adf2: security_ib_pkey_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int security_ib_pkey_sid(struct selinux_state *state, u64 subnet_prefix, u16 pkey_num, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff814824d0)
Location: security/selinux/ss/services.c:2305
Inline: False
Direct callers:
  - security/selinux/ibpkey.c:sel_ib_pkey_sid
```
**Symbols:**

```
ffffffff814824d0-ffffffff81482589: security_ib_pkey_sid (STB_GLOBAL)
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
<code>subnet_prefix, pkey_num, out_sid</code> ➡️ <code>state, subnet_prefix, pkey_num, out_sid</code>
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
<code>state, subnet_prefix, pkey_num, out_sid</code> ➡️ <code>subnet_prefix, pkey_num, out_sid</code>
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
