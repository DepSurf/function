# Function: <code>security_load_policy</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int security_load_policy(void *data, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff81359280)
Location: security/selinux/ss/services.c:2013
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_load
```
**Symbols:**

```
ffffffff81359280-ffffffff8135983a: security_load_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int security_load_policy(void *data, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8138f200)
Location: security/selinux/ss/services.c:2007
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_load
```
**Symbols:**

```
ffffffff8138f200-ffffffff8138f7d2: security_load_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int security_load_policy(void *data, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff813a5e20)
Location: security/selinux/ss/services.c:2007
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_load
```
**Symbols:**

```
ffffffff813a5e20-ffffffff813a63f2: security_load_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int security_load_policy(void *data, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff813bc890)
Location: security/selinux/ss/services.c:2038
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_load
```
**Symbols:**

```
ffffffff813bc890-ffffffff813bce4c: security_load_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int security_load_policy(void *data, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff813e2a00)
Location: security/selinux/ss/services.c:2044
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_load
```
**Symbols:**

```
ffffffff813e2a00-ffffffff813e2fbe: security_load_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int security_load_policy(struct selinux_state *state, void *data, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:2108
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_load
```
**Symbols:**

```
ffffffff81414d00-ffffffff81414d77: security_load_policy.cold.37 (STB_LOCAL)
ffffffff81412300-ffffffff81412928: security_load_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int security_load_policy(struct selinux_state *state, void *data, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:2064
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_load
```
**Symbols:**

```
ffffffff814312b6-ffffffff81431332: security_load_policy.cold.37 (STB_LOCAL)
ffffffff8142e820-ffffffff8142ee52: security_load_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int security_load_policy(struct selinux_state *state, void *data, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:2077
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_load
```
**Symbols:**

```
ffffffff8145ed4f-ffffffff8145eddf: security_load_policy.cold (STB_LOCAL)
ffffffff8145c1a0-ffffffff8145c7f5: security_load_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int security_load_policy(struct selinux_state *state, void *data, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:2084
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_load
```
**Symbols:**

```
ffffffff81478b01-ffffffff81478b91: security_load_policy.cold (STB_LOCAL)
ffffffff81475f50-ffffffff814765a5: security_load_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int security_load_policy(struct selinux_state *state, void *data, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:2133
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_load
```
**Symbols:**

```
ffffffff814cdfd5-ffffffff814ce03a: security_load_policy.cold (STB_LOCAL)
ffffffff814cb700-ffffffff814cbbf5: security_load_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int security_load_policy(struct selinux_state *state, void *data, size_t len, struct selinux_load_state *load_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:2248
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_load
```
**Symbols:**

```
ffffffff81bf1059-ffffffff81bf1094: security_load_policy.cold (STB_LOCAL)
ffffffff814e9e40-ffffffff814ea029: security_load_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int security_load_policy(struct selinux_state *state, void *data, size_t len, struct selinux_load_state *load_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:2275
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_load
```
**Symbols:**

```
ffffffff81be3184-ffffffff81be31e2: security_load_policy.cold (STB_LOCAL)
ffffffff814f0900-ffffffff814f0c2e: security_load_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int security_load_policy(struct selinux_state *state, void *data, size_t len, struct selinux_load_state *load_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:2282
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_load
```
**Symbols:**

```
ffffffff81cd50e5-ffffffff81cd5157: security_load_policy.cold (STB_LOCAL)
ffffffff8154aeb0-ffffffff8154b1e8: security_load_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int security_load_policy(struct selinux_state *state, void *data, size_t len, struct selinux_load_state *load_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:2284
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_load
```
**Symbols:**

```
ffffffff81e87f31-ffffffff81e87fa4: security_load_policy.cold (STB_LOCAL)
ffffffff815e3bf0-ffffffff815e3f84: security_load_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int security_load_policy(struct selinux_state *state, void *data, size_t len, struct selinux_load_state *load_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:2277
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_load
```
**Symbols:**

```
ffffffff82073e1a-ffffffff82073e2f: security_load_policy.cold (STB_LOCAL)
ffffffff81692eb0-ffffffff81693277: security_load_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int security_load_policy(void *data, size_t len, struct selinux_load_state *load_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:2240
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_load
```
**Symbols:**

```
ffffffff820f39cb-ffffffff820f39e0: security_load_policy.cold (STB_LOCAL)
ffffffff816cb3e0-ffffffff816cb792: security_load_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int security_load_policy(void *data, size_t len, struct selinux_load_state *load_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:2250
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_load
```
**Symbols:**

```
ffffffff821d0b91-ffffffff821d0ba6: security_load_policy.cold (STB_LOCAL)
ffffffff81708020-ffffffff8170845f: security_load_policy (STB_GLOBAL)
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
int security_load_policy(struct selinux_state *state, void *data, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffff800010565988)
Location: security/selinux/ss/services.c:2084
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_load
```
**Symbols:**

```
ffff800010565988-ffff800010565fa0: security_load_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int security_load_policy(struct selinux_state *state, void *data, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (c071a134)
Location: security/selinux/ss/services.c:2084
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_load
```
**Symbols:**

```
c071a134-c071a718: security_load_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int security_load_policy(struct selinux_state *state, void *data, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (c0000000006c80d0)
Location: security/selinux/ss/services.c:2084
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_load
```
**Symbols:**

```
c0000000006c80d0-c0000000006c886c: security_load_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int security_load_policy(struct selinux_state *state, void *data, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffe0003bbd54)
Location: security/selinux/ss/services.c:2084
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_load
```
**Symbols:**

```
ffffffe0003bbd54-ffffffe0003bc298: security_load_policy (STB_GLOBAL)
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
int security_load_policy(struct selinux_state *state, void *data, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:2084
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_load
```
**Symbols:**

```
ffffffff814710e1-ffffffff81471171: security_load_policy.cold (STB_LOCAL)
ffffffff8146e530-ffffffff8146eb85: security_load_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int security_load_policy(struct selinux_state *state, void *data, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:2084
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_load
```
**Symbols:**

```
ffffffff81461b01-ffffffff81461b91: security_load_policy.cold (STB_LOCAL)
ffffffff8145ef60-ffffffff8145f5af: security_load_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int security_load_policy(struct selinux_state *state, void *data, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:2084
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_load
```
**Symbols:**

```
ffffffff8146d181-ffffffff8146d211: security_load_policy.cold (STB_LOCAL)
ffffffff8146a5d0-ffffffff8146ac25: security_load_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int security_load_policy(struct selinux_state *state, void *data, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:2084
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_load
```
**Symbols:**

```
ffffffff814849ed-ffffffff81484a7d: security_load_policy.cold (STB_LOCAL)
ffffffff81481d70-ffffffff814823c3: security_load_policy (STB_GLOBAL)
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
<code>data, len</code> ➡️ <code>state, data, len</code>
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
<code>struct selinux_load_state *load_state</code>
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct selinux_state *state</code>
</li>
<li>
<b>Param reordered. </b>
<code>state, data, len, load_state</code> ➡️ <code>data, len, load_state</code>
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
