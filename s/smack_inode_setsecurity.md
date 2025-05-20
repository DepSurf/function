# Function: <code>smack_inode_setsecurity</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int smack_inode_setsecurity(struct inode *inode, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff8135e530)
Location: security/smack/smack_lsm.c:2712
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_inode_notifysecctx
```
**Symbols:**

```
ffffffff8135e530-ffffffff8135e678: smack_inode_setsecurity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int smack_inode_setsecurity(struct inode *inode, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff81394680)
Location: security/smack/smack_lsm.c:2731
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_inode_notifysecctx
```
**Symbols:**

```
ffffffff81394680-ffffffff813947c8: smack_inode_setsecurity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int smack_inode_setsecurity(struct inode *inode, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff813ab1c0)
Location: security/smack/smack_lsm.c:2730
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_inode_notifysecctx
```
**Symbols:**

```
ffffffff813ab1c0-ffffffff813ab308: smack_inode_setsecurity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int smack_inode_setsecurity(struct inode *inode, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff813c1ad0)
Location: security/smack/smack_lsm.c:2660
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_inode_notifysecctx
```
**Symbols:**

```
ffffffff813c1ad0-ffffffff813c1c3d: smack_inode_setsecurity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int smack_inode_setsecurity(struct inode *inode, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff813e8170)
Location: security/smack/smack_lsm.c:2629
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_inode_notifysecctx
```
**Symbols:**

```
ffffffff813e8170-ffffffff813e82dd: smack_inode_setsecurity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int smack_inode_setsecurity(struct inode *inode, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/smack/smack_lsm.c (0)
Location: security/smack/smack_lsm.c:2754
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_inode_notifysecctx
```
**Symbols:**

```
ffffffff81418fb0-ffffffff814190d3: smack_inode_setsecurity (STB_LOCAL)
ffffffff8141cfd5-ffffffff8141cff1: smack_inode_setsecurity.cold.31 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int smack_inode_setsecurity(struct inode *inode, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/smack/smack_lsm.c (0)
Location: security/smack/smack_lsm.c:2592
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_inode_notifysecctx
```
**Symbols:**

```
ffffffff81435690-ffffffff814357ce: smack_inode_setsecurity (STB_LOCAL)
ffffffff814395d6-ffffffff814395f2: smack_inode_setsecurity.cold.32 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int smack_inode_setsecurity(struct inode *inode, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/smack/smack_lsm.c (0)
Location: security/smack/smack_lsm.c:2679
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_inode_notifysecctx
```
**Symbols:**

```
ffffffff81463100-ffffffff81463266: smack_inode_setsecurity (STB_LOCAL)
ffffffff81467208-ffffffff81467224: smack_inode_setsecurity.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int smack_inode_setsecurity(struct inode *inode, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/smack/smack_lsm.c (0)
Location: security/smack/smack_lsm.c:2677
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_inode_notifysecctx
```
**Symbols:**

```
ffffffff8147ced0-ffffffff8147d036: smack_inode_setsecurity (STB_LOCAL)
ffffffff81480fe8-ffffffff81481004: smack_inode_setsecurity.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int smack_inode_setsecurity(struct inode *inode, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/smack/smack_lsm.c (0)
Location: security/smack/smack_lsm.c:2661
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_inode_notifysecctx
```
**Symbols:**

```
ffffffff814d2970-ffffffff814d2ad6: smack_inode_setsecurity (STB_LOCAL)
ffffffff814d6f35-ffffffff814d6f51: smack_inode_setsecurity.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int smack_inode_setsecurity(struct inode *inode, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/smack/smack_lsm.c (0)
Location: security/smack/smack_lsm.c:2676
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_inode_notifysecctx
```
**Symbols:**

```
ffffffff814f1110-ffffffff814f1271: smack_inode_setsecurity (STB_LOCAL)
ffffffff81bf120f-ffffffff81bf122b: smack_inode_setsecurity.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int smack_inode_setsecurity(struct inode *inode, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/smack/smack_lsm.c (0)
Location: security/smack/smack_lsm.c:2675
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_inode_notifysecctx
```
**Symbols:**

```
ffffffff814f8a80-ffffffff814f8bb4: smack_inode_setsecurity (STB_LOCAL)
ffffffff81be3390-ffffffff81be33b4: smack_inode_setsecurity.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int smack_inode_setsecurity(struct inode *inode, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/smack/smack_lsm.c (0)
Location: security/smack/smack_lsm.c:2675
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_inode_notifysecctx
```
**Symbols:**

```
ffffffff81553670-ffffffff815537a4: smack_inode_setsecurity (STB_LOCAL)
ffffffff81cd54c6-ffffffff81cd54ea: smack_inode_setsecurity.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int smack_inode_setsecurity(struct inode *inode, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/smack/smack_lsm.c (0)
Location: security/smack/smack_lsm.c:2681
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_inode_notifysecctx
```
**Symbols:**

```
ffffffff815eb1e0-ffffffff815eb30e: smack_inode_setsecurity (STB_LOCAL)
ffffffff81e882b5-ffffffff81e882d1: smack_inode_setsecurity.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int smack_inode_setsecurity(struct inode *inode, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff8169aff0)
Location: security/smack/smack_lsm.c:2756
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_inode_notifysecctx
```
**Symbols:**

```
ffffffff8169aff0-ffffffff8169b131: smack_inode_setsecurity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int smack_inode_setsecurity(struct inode *inode, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff816d3800)
Location: security/smack/smack_lsm.c:2819
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_inode_notifysecctx
```
**Symbols:**

```
ffffffff816d3800-ffffffff816d3941: smack_inode_setsecurity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int smack_inode_setsecurity(struct inode *inode, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff81711800)
Location: security/smack/smack_lsm.c:2878
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_inode_notifysecctx
```
**Symbols:**

```
ffffffff81711800-ffffffff81711941: smack_inode_setsecurity (STB_LOCAL)
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
int smack_inode_setsecurity(struct inode *inode, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffff80001056f5a0)
Location: security/smack/smack_lsm.c:2677
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_inode_notifysecctx
```
**Symbols:**

```
ffff80001056f5a0-ffff80001056f744: smack_inode_setsecurity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int smack_inode_setsecurity(struct inode *inode, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (c0721518)
Location: security/smack/smack_lsm.c:2677
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_inode_notifysecctx
```
**Symbols:**

```
c0721518-c0721674: smack_inode_setsecurity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int smack_inode_setsecurity(struct inode *inode, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (c0000000006d3500)
Location: security/smack/smack_lsm.c:2677
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_inode_notifysecctx
```
**Symbols:**

```
c0000000006d3500-c0000000006d3aa0: smack_inode_setsecurity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int smack_inode_setsecurity(struct inode *inode, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffe0003c2670)
Location: security/smack/smack_lsm.c:2677
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_inode_notifysecctx
```
**Symbols:**

```
ffffffe0003c2670-ffffffe0003c27b4: smack_inode_setsecurity (STB_LOCAL)
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
int smack_inode_setsecurity(struct inode *inode, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/smack/smack_lsm.c (0)
Location: security/smack/smack_lsm.c:2677
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_inode_notifysecctx
```
**Symbols:**

```
ffffffff814754b0-ffffffff81475616: smack_inode_setsecurity (STB_LOCAL)
ffffffff814795c8-ffffffff814795e4: smack_inode_setsecurity.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int smack_inode_setsecurity(struct inode *inode, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/smack/smack_lsm.c (0)
Location: security/smack/smack_lsm.c:2677
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_inode_notifysecctx
```
**Symbols:**

```
ffffffff81465ed0-ffffffff81466036: smack_inode_setsecurity (STB_LOCAL)
ffffffff81469fe8-ffffffff8146a004: smack_inode_setsecurity.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int smack_inode_setsecurity(struct inode *inode, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/smack/smack_lsm.c (0)
Location: security/smack/smack_lsm.c:2677
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_inode_notifysecctx
```
**Symbols:**

```
ffffffff81471550-ffffffff814716b6: smack_inode_setsecurity (STB_LOCAL)
ffffffff81475668-ffffffff81475684: smack_inode_setsecurity.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int smack_inode_setsecurity(struct inode *inode, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/smack/smack_lsm.c (0)
Location: security/smack/smack_lsm.c:2677
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_inode_notifysecctx
```
**Symbols:**

```
ffffffff81488e40-ffffffff81488fa6: smack_inode_setsecurity (STB_LOCAL)
ffffffff8148d066-ffffffff8148d082: smack_inode_setsecurity.cold (STB_LOCAL)
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
No changes between <code>4.15</code> and <code>4.18</code> ✅
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
