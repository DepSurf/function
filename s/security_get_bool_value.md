# Function: <code>security_get_bool_value</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int security_get_bool_value(int bool);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff81359a30)
Location: security/selinux/ss/services.c:2679
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_read_bool
```
**Symbols:**

```
ffffffff81359a30-ffffffff81359a76: security_get_bool_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int security_get_bool_value(int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8138f9e0)
Location: security/selinux/ss/services.c:2673
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_read_bool
```
**Symbols:**

```
ffffffff8138f9e0-ffffffff8138fa26: security_get_bool_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int security_get_bool_value(int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff813a6600)
Location: security/selinux/ss/services.c:2673
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_read_bool
```
**Symbols:**

```
ffffffff813a6600-ffffffff813a6646: security_get_bool_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int security_get_bool_value(int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff813bd050)
Location: security/selinux/ss/services.c:2789
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_read_bool
```
**Symbols:**

```
ffffffff813bd050-ffffffff813bd096: security_get_bool_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int security_get_bool_value(int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff813e31c0)
Location: security/selinux/ss/services.c:2799
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_read_bool
```
**Symbols:**

```
ffffffff813e31c0-ffffffff813e3206: security_get_bool_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int security_get_bool_value(struct selinux_state *state, int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff81413950)
Location: security/selinux/ss/services.c:2919
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_read_bool
```
**Symbols:**

```
ffffffff81413950-ffffffff814139a6: security_get_bool_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int security_get_bool_value(struct selinux_state *state, int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8142fe80)
Location: security/selinux/ss/services.c:2885
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_read_bool
```
**Symbols:**

```
ffffffff8142fe80-ffffffff8142fed3: security_get_bool_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int security_get_bool_value(struct selinux_state *state, int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8145d810)
Location: security/selinux/ss/services.c:2898
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_read_bool
```
**Symbols:**

```
ffffffff8145d810-ffffffff8145d868: security_get_bool_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int security_get_bool_value(struct selinux_state *state, int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff814775c0)
Location: security/selinux/ss/services.c:2905
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_read_bool
```
**Symbols:**

```
ffffffff814775c0-ffffffff81477618: security_get_bool_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int security_get_bool_value(struct selinux_state *state, u32 index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff814cca00)
Location: security/selinux/ss/services.c:2948
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_read_bool
```
**Symbols:**

```
ffffffff814cca00-ffffffff814cca5a: security_get_bool_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int security_get_bool_value(struct selinux_state *state, u32 index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff814ea200)
Location: security/selinux/ss/services.c:3061
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_read_bool
```
**Symbols:**

```
ffffffff814ea200-ffffffff814ea247: security_get_bool_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int security_get_bool_value(struct selinux_state *state, u32 index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff814f0e00)
Location: security/selinux/ss/services.c:3139
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_read_bool
```
**Symbols:**

```
ffffffff814f0e00-ffffffff814f0e47: security_get_bool_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int security_get_bool_value(struct selinux_state *state, u32 index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:3146
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_read_bool
```
**Symbols:**

```
ffffffff81cd5171-ffffffff81cd5186: security_get_bool_value.cold (STB_LOCAL)
ffffffff8154b3d0-ffffffff8154b430: security_get_bool_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int security_get_bool_value(struct selinux_state *state, u32 index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:3148
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_read_bool
```
**Symbols:**

```
ffffffff81e87fbe-ffffffff81e87fd3: security_get_bool_value.cold (STB_LOCAL)
ffffffff815e4170-ffffffff815e41f5: security_get_bool_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int security_get_bool_value(struct selinux_state *state, u32 index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:3141
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_read_bool
```
**Symbols:**

```
ffffffff82073e49-ffffffff82073e5e: security_get_bool_value.cold (STB_LOCAL)
ffffffff81693480-ffffffff81693505: security_get_bool_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int security_get_bool_value(u32 index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:3089
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_read_bool
```
**Symbols:**

```
ffffffff820f39fa-ffffffff820f3a0f: security_get_bool_value.cold (STB_LOCAL)
ffffffff816cb9a0-ffffffff816cba1f: security_get_bool_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int security_get_bool_value(u32 index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:3098
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_read_bool
```
**Symbols:**

```
ffffffff821d0bc0-ffffffff821d0bd5: security_get_bool_value.cold (STB_LOCAL)
ffffffff81708660-ffffffff817086df: security_get_bool_value (STB_GLOBAL)
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
int security_get_bool_value(struct selinux_state *state, int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffff800010567288)
Location: security/selinux/ss/services.c:2905
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_read_bool
```
**Symbols:**

```
ffff800010567288-ffff800010567344: security_get_bool_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int security_get_bool_value(struct selinux_state *state, int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (c071b7f0)
Location: security/selinux/ss/services.c:2905
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_read_bool
```
**Symbols:**

```
c071b7f0-c071b868: security_get_bool_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int security_get_bool_value(struct selinux_state *state, int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (c0000000006ca660)
Location: security/selinux/ss/services.c:2905
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_read_bool
```
**Symbols:**

```
c0000000006ca660-c0000000006ca6f8: security_get_bool_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int security_get_bool_value(struct selinux_state *state, int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffe0003bd01c)
Location: security/selinux/ss/services.c:2905
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_read_bool
```
**Symbols:**

```
ffffffe0003bd01c-ffffffe0003bd07a: security_get_bool_value (STB_GLOBAL)
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
int security_get_bool_value(struct selinux_state *state, int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8146fba0)
Location: security/selinux/ss/services.c:2905
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_read_bool
```
**Symbols:**

```
ffffffff8146fba0-ffffffff8146fbf8: security_get_bool_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int security_get_bool_value(struct selinux_state *state, int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff814605c0)
Location: security/selinux/ss/services.c:2905
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_read_bool
```
**Symbols:**

```
ffffffff814605c0-ffffffff81460618: security_get_bool_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int security_get_bool_value(struct selinux_state *state, int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8146bc40)
Location: security/selinux/ss/services.c:2905
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_read_bool
```
**Symbols:**

```
ffffffff8146bc40-ffffffff8146bc98: security_get_bool_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int security_get_bool_value(struct selinux_state *state, int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff814833f0)
Location: security/selinux/ss/services.c:2905
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_read_bool
```
**Symbols:**

```
ffffffff814833f0-ffffffff81483447: security_get_bool_value (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int index</code>
</li>
<li>
<b>Param removed. </b>
<code>int bool</code>
</li>
</ul>
</details>
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
<code>index</code> ➡️ <code>state, index</code>
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int index</code> ➡️ <code>u32 index</code>
</li>
</ul>
</details>
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
<code>state, index</code> ➡️ <code>index</code>
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
