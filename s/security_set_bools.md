# Function: <code>security_set_bools</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int security_set_bools(int len, int *values);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff81359840)
Location: security/selinux/ss/services.c:2630
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_commit_bools_write
```
**Symbols:**

```
ffffffff81359840-ffffffff81359a30: security_set_bools (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int security_set_bools(int len, int *values);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8138f7e0)
Location: security/selinux/ss/services.c:2624
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_commit_bools_write
```
**Symbols:**

```
ffffffff8138f7e0-ffffffff8138f9d3: security_set_bools (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int security_set_bools(int len, int *values);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff813a6400)
Location: security/selinux/ss/services.c:2624
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_commit_bools_write
```
**Symbols:**

```
ffffffff813a6400-ffffffff813a65f3: security_set_bools (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int security_set_bools(int len, int *values);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff813bce50)
Location: security/selinux/ss/services.c:2740
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_commit_bools_write
```
**Symbols:**

```
ffffffff813bce50-ffffffff813bd044: security_set_bools (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int security_set_bools(int len, int *values);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff813e2fc0)
Location: security/selinux/ss/services.c:2750
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_commit_bools_write
```
**Symbols:**

```
ffffffff813e2fc0-ffffffff813e31b3: security_set_bools (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int security_set_bools(struct selinux_state *state, int len, int *values);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff81413710)
Location: security/selinux/ss/services.c:2867
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_commit_bools_write
```
**Symbols:**

```
ffffffff81413710-ffffffff8141394d: security_set_bools (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int security_set_bools(struct selinux_state *state, int len, int *values);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8142fc40)
Location: security/selinux/ss/services.c:2833
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_commit_bools_write
```
**Symbols:**

```
ffffffff8142fc40-ffffffff8142fe7a: security_set_bools (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int security_set_bools(struct selinux_state *state, int len, int *values);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8145d5f0)
Location: security/selinux/ss/services.c:2846
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_commit_bools_write
```
**Symbols:**

```
ffffffff8145d5f0-ffffffff8145d810: security_set_bools (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int security_set_bools(struct selinux_state *state, int len, int *values);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff814773a0)
Location: security/selinux/ss/services.c:2853
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_commit_bools_write
```
**Symbols:**

```
ffffffff814773a0-ffffffff814775c0: security_set_bools (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int security_set_bools(struct selinux_state *state, u32 len, int *values);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff814cc810)
Location: security/selinux/ss/services.c:2901
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_commit_bools_write
```
**Symbols:**

```
ffffffff814cc810-ffffffff814cc9fa: security_set_bools (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int security_set_bools(struct selinux_state *state, u32 len, int *values);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff814ea030)
Location: security/selinux/ss/services.c:2990
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_commit_bools_write
```
**Symbols:**

```
ffffffff814ea030-ffffffff814ea1f5: security_set_bools (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int security_set_bools(struct selinux_state *state, u32 len, int *values);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff814f0c30)
Location: security/selinux/ss/services.c:3068
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_commit_bools_write
```
**Symbols:**

```
ffffffff814f0c30-ffffffff814f0df5: security_set_bools (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int security_set_bools(struct selinux_state *state, u32 len, int *values);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:3075
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_commit_bools_write
```
**Symbols:**

```
ffffffff81cd5157-ffffffff81cd5171: security_set_bools.cold (STB_LOCAL)
ffffffff8154b1f0-ffffffff8154b3c5: security_set_bools (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int security_set_bools(struct selinux_state *state, u32 len, int *values);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:3077
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_commit_bools_write
```
**Symbols:**

```
ffffffff81e87fa4-ffffffff81e87fbe: security_set_bools.cold (STB_LOCAL)
ffffffff815e3f90-ffffffff815e416d: security_set_bools (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int security_set_bools(struct selinux_state *state, u32 len, int *values);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:3070
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_commit_bools_write
```
**Symbols:**

```
ffffffff82073e2f-ffffffff82073e49: security_set_bools.cold (STB_LOCAL)
ffffffff81693290-ffffffff81693469: security_set_bools (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int security_set_bools(u32 len, int *values);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:3017
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_commit_bools_write
```
**Symbols:**

```
ffffffff820f39e0-ffffffff820f39fa: security_set_bools.cold (STB_LOCAL)
ffffffff816cb7b0-ffffffff816cb988: security_set_bools (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int security_set_bools(u32 len, int *values);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:3026
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_commit_bools_write
```
**Symbols:**

```
ffffffff821d0ba6-ffffffff821d0bc0: security_set_bools.cold (STB_LOCAL)
ffffffff81708470-ffffffff81708648: security_set_bools (STB_GLOBAL)
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
int security_set_bools(struct selinux_state *state, int len, int *values);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffff800010566fd0)
Location: security/selinux/ss/services.c:2853
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_commit_bools_write
```
**Symbols:**

```
ffff800010566fd0-ffff800010567288: security_set_bools (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int security_set_bools(struct selinux_state *state, int len, int *values);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (c071b56c)
Location: security/selinux/ss/services.c:2853
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_commit_bools_write
```
**Symbols:**

```
c071b56c-c071b7f0: security_set_bools (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int security_set_bools(struct selinux_state *state, int len, int *values);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (c0000000006ca2e0)
Location: security/selinux/ss/services.c:2853
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_commit_bools_write
```
**Symbols:**

```
c0000000006ca2e0-c0000000006ca658: security_set_bools (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int security_set_bools(struct selinux_state *state, int len, int *values);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffe0003bce1a)
Location: security/selinux/ss/services.c:2853
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_commit_bools_write
```
**Symbols:**

```
ffffffe0003bce1a-ffffffe0003bd01c: security_set_bools (STB_GLOBAL)
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
int security_set_bools(struct selinux_state *state, int len, int *values);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8146f980)
Location: security/selinux/ss/services.c:2853
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_commit_bools_write
```
**Symbols:**

```
ffffffff8146f980-ffffffff8146fba0: security_set_bools (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int security_set_bools(struct selinux_state *state, int len, int *values);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff814603a0)
Location: security/selinux/ss/services.c:2853
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_commit_bools_write
```
**Symbols:**

```
ffffffff814603a0-ffffffff814605bb: security_set_bools (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int security_set_bools(struct selinux_state *state, int len, int *values);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8146ba20)
Location: security/selinux/ss/services.c:2853
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_commit_bools_write
```
**Symbols:**

```
ffffffff8146ba20-ffffffff8146bc40: security_set_bools (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int security_set_bools(struct selinux_state *state, int len, int *values);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff814831c0)
Location: security/selinux/ss/services.c:2853
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_commit_bools_write
```
**Symbols:**

```
ffffffff814831c0-ffffffff814833f0: security_set_bools (STB_GLOBAL)
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
<code>len, values</code> ➡️ <code>state, len, values</code>
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
<code>int len</code> ➡️ <code>u32 len</code>
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
<code>state, len, values</code> ➡️ <code>len, values</code>
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
