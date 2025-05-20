# Function: <code>security_get_bools</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int security_get_bools(int *len, char ***names, int **values);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff813590e0)
Location: security/selinux/ss/services.c:2585
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/ss/services.c:security_load_policy
```
**Symbols:**

```
ffffffff813590e0-ffffffff81359276: security_get_bools (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int security_get_bools(int *len, char ***names, int **values);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8138f060)
Location: security/selinux/ss/services.c:2579
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/ss/services.c:security_load_policy
```
**Symbols:**

```
ffffffff8138f060-ffffffff8138f1f5: security_get_bools (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int security_get_bools(int *len, char ***names, int **values);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff813a5c80)
Location: security/selinux/ss/services.c:2579
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/ss/services.c:security_load_policy
```
**Symbols:**

```
ffffffff813a5c80-ffffffff813a5e15: security_get_bools (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int security_get_bools(int *len, char ***names, int **values);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff813bc700)
Location: security/selinux/ss/services.c:2695
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/ss/services.c:security_load_policy
```
**Symbols:**

```
ffffffff813bc700-ffffffff813bc88d: security_get_bools (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int security_get_bools(int *len, char ***names, int **values);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff813e2870)
Location: security/selinux/ss/services.c:2705
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/ss/services.c:security_load_policy
```
**Symbols:**

```
ffffffff813e2870-ffffffff813e29fd: security_get_bools (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
int security_get_bools(struct selinux_state *state, int *len, char ***names, int **values);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (ffffffff81412521)
Location: security/selinux/ss/services.c:2809
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_load_policy
Direct callers:
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/ss/services.c:security_load_policy
```
**Symbols:**

```
ffffffff81410ae0-ffffffff81410ca0: security_get_bools.part.22 (STB_LOCAL)
ffffffff814136e0-ffffffff8141370d: security_get_bools (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
int security_get_bools(struct selinux_state *state, int *len, char ***names, int **values);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8142e96f)
Location: security/selinux/ss/services.c:2775
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_load_policy
Direct callers:
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/ss/services.c:security_load_policy
```
**Symbols:**

```
ffffffff8142d170-ffffffff8142d32d: security_get_bools.part.21 (STB_LOCAL)
ffffffff8142fc10-ffffffff8142fc3d: security_get_bools (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int security_get_bools(struct selinux_state *state, int *len, char ***names, int **values);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8145c3eb)
Location: security/selinux/ss/services.c:2788
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_load_policy
Direct callers:
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/ss/services.c:security_load_policy
```
**Symbols:**

```
ffffffff8145aa20-ffffffff8145abd2: security_get_bools.part.0 (STB_LOCAL)
ffffffff8145d5c0-ffffffff8145d5ed: security_get_bools (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int security_get_bools(struct selinux_state *state, int *len, char ***names, int **values);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8147619b)
Location: security/selinux/ss/services.c:2795
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_load_policy
Direct callers:
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/ss/services.c:security_load_policy
```
**Symbols:**

```
ffffffff814747d0-ffffffff81474982: security_get_bools.part.0 (STB_LOCAL)
ffffffff81477370-ffffffff8147739d: security_get_bools (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int security_get_bools(struct selinux_state *state, u32 *len, char ***names, int **values);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (ffffffff814ca13d)
Location: security/selinux/ss/services.c:2838
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_preserve_bools
Direct callers:
  - security/selinux/selinuxfs.c:sel_make_bools
  - security/selinux/ss/services.c:security_preserve_bools
```
**Symbols:**

```
ffffffff814c9f80-ffffffff814ca0ff: security_get_bools.part.0 (STB_LOCAL)
ffffffff814cc7e0-ffffffff814cc80f: security_get_bools (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int security_get_bools(struct selinux_policy *policy, u32 *len, char ***names, int **values);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff814e9be0)
Location: security/selinux/ss/services.c:2937
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_make_bools
  - security/selinux/ss/services.c:security_preserve_bools
```
**Symbols:**

```
ffffffff814e9be0-ffffffff814e9d33: security_get_bools (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int security_get_bools(struct selinux_policy *policy, u32 *len, char ***names, int **values);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff814f07a0)
Location: security/selinux/ss/services.c:3015
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_make_bools
  - security/selinux/ss/services.c:security_load_policy
```
**Symbols:**

```
ffffffff814f07a0-ffffffff814f08f3: security_get_bools (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int security_get_bools(struct selinux_policy *policy, u32 *len, char ***names, int **values);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8154ad50)
Location: security/selinux/ss/services.c:3022
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_make_bools
  - security/selinux/ss/services.c:security_load_policy
```
**Symbols:**

```
ffffffff8154ad50-ffffffff8154aea3: security_get_bools (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int security_get_bools(struct selinux_policy *policy, u32 *len, char ***names, int **values);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff815e3a80)
Location: security/selinux/ss/services.c:3024
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_make_bools
  - security/selinux/ss/services.c:security_load_policy
```
**Symbols:**

```
ffffffff815e3a80-ffffffff815e3bea: security_get_bools (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int security_get_bools(struct selinux_policy *policy, u32 *len, char ***names, int **values);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff81692d30)
Location: security/selinux/ss/services.c:3017
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_make_bools
  - security/selinux/ss/services.c:security_load_policy
```
**Symbols:**

```
ffffffff81692d30-ffffffff81692e9a: security_get_bools (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int security_get_bools(struct selinux_policy *policy, u32 *len, char ***names, int **values);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff816cb270)
Location: security/selinux/ss/services.c:2964
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_make_bools
  - security/selinux/ss/services.c:security_load_policy
```
**Symbols:**

```
ffffffff816cb270-ffffffff816cb3cd: security_get_bools (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int security_get_bools(struct selinux_policy *policy, u32 *len, char ***names, int **values);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff81707eb0)
Location: security/selinux/ss/services.c:2973
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_load_policy
```
**Symbols:**

```
ffffffff81707eb0-ffffffff8170800d: security_get_bools (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
int security_get_bools(struct selinux_state *state, int *len, char ***names, int **values);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (ffff800010565c64)
Location: security/selinux/ss/services.c:2795
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_load_policy
Direct callers:
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/ss/services.c:security_load_policy
```
**Symbols:**

```
ffff8000105631e8-ffff8000105633f0: security_get_bools.part.0 (STB_LOCAL)
ffff800010566f60-ffff800010566fd0: security_get_bools (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
int security_get_bools(struct selinux_state *state, int *len, char ***names, int **values);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (c071a40c)
Location: security/selinux/ss/services.c:2795
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_load_policy
Direct callers:
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/ss/services.c:security_load_policy
```
**Symbols:**

```
c07187a8-c0718938: security_get_bools.part.0 (STB_LOCAL)
c071b524-c071b56c: security_get_bools (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
int security_get_bools(struct selinux_state *state, int *len, char ***names, int **values);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (c0000000006c8440)
Location: security/selinux/ss/services.c:2795
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_load_policy
Direct callers:
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/ss/services.c:security_load_policy
```
**Symbols:**

```
c0000000006c6070-c0000000006c629c: security_get_bools.part.0 (STB_LOCAL)
c0000000006ca290-c0000000006ca2d4: security_get_bools (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
int security_get_bools(struct selinux_state *state, int *len, char ***names, int **values);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (ffffffe0003bbfd4)
Location: security/selinux/ss/services.c:2795
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_load_policy
Direct callers:
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/ss/services.c:security_load_policy
```
**Symbols:**

```
ffffffe0003ba67a-ffffffe0003ba7ec: security_get_bools.part.0 (STB_LOCAL)
ffffffe0003bcdb4-ffffffe0003bce1a: security_get_bools (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
int security_get_bools(struct selinux_state *state, int *len, char ***names, int **values);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8146e77b)
Location: security/selinux/ss/services.c:2795
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_load_policy
Direct callers:
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/ss/services.c:security_load_policy
```
**Symbols:**

```
ffffffff8146cdb0-ffffffff8146cf62: security_get_bools.part.0 (STB_LOCAL)
ffffffff8146f950-ffffffff8146f97d: security_get_bools (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
int security_get_bools(struct selinux_state *state, int *len, char ***names, int **values);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8145f1ab)
Location: security/selinux/ss/services.c:2795
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_load_policy
Direct callers:
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/ss/services.c:security_load_policy
```
**Symbols:**

```
ffffffff8145d7e0-ffffffff8145d992: security_get_bools.part.0 (STB_LOCAL)
ffffffff81460370-ffffffff8146039d: security_get_bools (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
int security_get_bools(struct selinux_state *state, int *len, char ***names, int **values);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8146a81b)
Location: security/selinux/ss/services.c:2795
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_load_policy
Direct callers:
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/ss/services.c:security_load_policy
```
**Symbols:**

```
ffffffff81468e50-ffffffff81469002: security_get_bools.part.0 (STB_LOCAL)
ffffffff8146b9f0-ffffffff8146ba1d: security_get_bools (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
int security_get_bools(struct selinux_state *state, int *len, char ***names, int **values);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (ffffffff81481fbb)
Location: security/selinux/ss/services.c:2795
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_load_policy
Direct callers:
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/ss/services.c:security_load_policy
```
**Symbols:**

```
ffffffff81480610-ffffffff814807c1: security_get_bools.part.0 (STB_LOCAL)
ffffffff81483190-ffffffff814831bd: security_get_bools (STB_GLOBAL)
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
<code>len, names, values</code> ➡️ <code>state, len, names, values</code>
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
<code>int *len</code> ➡️ <code>u32 *len</code>
</li>
</ul>
</details>
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
