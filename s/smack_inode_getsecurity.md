# Function: <code>smack_inode_getsecurity</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int smack_inode_getsecurity(const struct inode *inode, const char *name, void **buffer, bool alloc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff81360bf0)
Location: security/smack/smack_lsm.c:1489
Inline: True
Direct callers:
  - security/smack/smack_lsm.c:smack_inode_getsecctx
```
**Symbols:**

```
ffffffff81360bf0-ffffffff81360c9c: smack_inode_getsecurity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int smack_inode_getsecurity(struct inode *inode, const char *name, void **buffer, bool alloc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff81396dd0)
Location: security/smack/smack_lsm.c:1493
Inline: True
Direct callers:
  - security/smack/smack_lsm.c:smack_inode_getsecctx
```
**Symbols:**

```
ffffffff81396dd0-ffffffff81396e7c: smack_inode_getsecurity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int smack_inode_getsecurity(struct inode *inode, const char *name, void **buffer, bool alloc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff813ad560)
Location: security/smack/smack_lsm.c:1487
Inline: True
Direct callers:
  - security/smack/smack_lsm.c:smack_inode_getsecctx
```
**Symbols:**

```
ffffffff813ad560-ffffffff813ad60c: smack_inode_getsecurity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int smack_inode_getsecurity(struct inode *inode, const char *name, void **buffer, bool alloc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff813c2a70)
Location: security/smack/smack_lsm.c:1432
Inline: True
Direct callers:
  - security/smack/smack_lsm.c:smack_inode_getsecctx
```
**Symbols:**

```
ffffffff813c2a70-ffffffff813c2b2d: smack_inode_getsecurity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int smack_inode_getsecurity(struct inode *inode, const char *name, void **buffer, bool alloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff813e7e70)
Location: security/smack/smack_lsm.c:1406
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_inode_getsecctx
```
**Symbols:**

```
ffffffff813e7e70-ffffffff813e7f52: smack_inode_getsecurity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int smack_inode_getsecurity(struct inode *inode, const char *name, void **buffer, bool alloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff81418ca0)
Location: security/smack/smack_lsm.c:1480
Inline: False
```
**Symbols:**

```
ffffffff81418ca0-ffffffff81418d88: smack_inode_getsecurity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int smack_inode_getsecurity(struct inode *inode, const char *name, void **buffer, bool alloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff81435220)
Location: security/smack/smack_lsm.c:1348
Inline: False
```
**Symbols:**

```
ffffffff81435220-ffffffff81435325: smack_inode_getsecurity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int smack_inode_getsecurity(struct inode *inode, const char *name, void **buffer, bool alloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff81462d20)
Location: security/smack/smack_lsm.c:1435
Inline: False
```
**Symbols:**

```
ffffffff81462d20-ffffffff81462e19: smack_inode_getsecurity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int smack_inode_getsecurity(struct inode *inode, const char *name, void **buffer, bool alloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff8147cad0)
Location: security/smack/smack_lsm.c:1435
Inline: False
```
**Symbols:**

```
ffffffff8147cad0-ffffffff8147cbc9: smack_inode_getsecurity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int smack_inode_getsecurity(struct inode *inode, const char *name, void **buffer, bool alloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff814d2510)
Location: security/smack/smack_lsm.c:1423
Inline: False
```
**Symbols:**

```
ffffffff814d2510-ffffffff814d2609: smack_inode_getsecurity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int smack_inode_getsecurity(struct inode *inode, const char *name, void **buffer, bool alloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff814efa00)
Location: security/smack/smack_lsm.c:1423
Inline: False
```
**Symbols:**

```
ffffffff814efa00-ffffffff814efaf0: smack_inode_getsecurity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int smack_inode_getsecurity(struct user_namespace *mnt_userns, struct inode *inode, const char *name, void **buffer, bool alloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff814f6a70)
Location: security/smack/smack_lsm.c:1408
Inline: False
```
**Symbols:**

```
ffffffff814f6a70-ffffffff814f6b5d: smack_inode_getsecurity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int smack_inode_getsecurity(struct user_namespace *mnt_userns, struct inode *inode, const char *name, void **buffer, bool alloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff81551600)
Location: security/smack/smack_lsm.c:1408
Inline: False
```
**Symbols:**

```
ffffffff81551600-ffffffff815516ed: smack_inode_getsecurity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int smack_inode_getsecurity(struct user_namespace *mnt_userns, struct inode *inode, const char *name, void **buffer, bool alloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff815ead70)
Location: security/smack/smack_lsm.c:1414
Inline: False
```
**Symbols:**

```
ffffffff815ead70-ffffffff815eae6f: smack_inode_getsecurity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int smack_inode_getsecurity(struct user_namespace *mnt_userns, struct inode *inode, const char *name, void **buffer, bool alloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff8169a9d0)
Location: security/smack/smack_lsm.c:1474
Inline: False
```
**Symbols:**

```
ffffffff8169a9d0-ffffffff8169aacf: smack_inode_getsecurity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int smack_inode_getsecurity(struct mnt_idmap *idmap, struct inode *inode, const char *name, void **buffer, bool alloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff816d31a0)
Location: security/smack/smack_lsm.c:1523
Inline: False
```
**Symbols:**

```
ffffffff816d31a0-ffffffff816d32fe: smack_inode_getsecurity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int smack_inode_getsecurity(struct mnt_idmap *idmap, struct inode *inode, const char *name, void **buffer, bool alloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff8170f540)
Location: security/smack/smack_lsm.c:1566
Inline: False
```
**Symbols:**

```
ffffffff8170f540-ffffffff8170f69e: smack_inode_getsecurity (STB_LOCAL)
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
int smack_inode_getsecurity(struct inode *inode, const char *name, void **buffer, bool alloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffff80001056d9f0)
Location: security/smack/smack_lsm.c:1435
Inline: False
```
**Symbols:**

```
ffff80001056d9f0-ffff80001056db0c: smack_inode_getsecurity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int smack_inode_getsecurity(struct inode *inode, const char *name, void **buffer, bool alloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (c0721048)
Location: security/smack/smack_lsm.c:1435
Inline: False
```
**Symbols:**

```
c0721048-c0721160: smack_inode_getsecurity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int smack_inode_getsecurity(struct inode *inode, const char *name, void **buffer, bool alloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (c0000000006d2ae0)
Location: security/smack/smack_lsm.c:1435
Inline: False
```
**Symbols:**

```
c0000000006d2ae0-c0000000006d2ff0: smack_inode_getsecurity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int smack_inode_getsecurity(struct inode *inode, const char *name, void **buffer, bool alloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffe0003c217c)
Location: security/smack/smack_lsm.c:1435
Inline: False
```
**Symbols:**

```
ffffffe0003c217c-ffffffe0003c2260: smack_inode_getsecurity (STB_LOCAL)
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
int smack_inode_getsecurity(struct inode *inode, const char *name, void **buffer, bool alloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff814750b0)
Location: security/smack/smack_lsm.c:1435
Inline: False
```
**Symbols:**

```
ffffffff814750b0-ffffffff814751a9: smack_inode_getsecurity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int smack_inode_getsecurity(struct inode *inode, const char *name, void **buffer, bool alloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff81465ad0)
Location: security/smack/smack_lsm.c:1435
Inline: False
```
**Symbols:**

```
ffffffff81465ad0-ffffffff81465bc9: smack_inode_getsecurity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int smack_inode_getsecurity(struct inode *inode, const char *name, void **buffer, bool alloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff81471150)
Location: security/smack/smack_lsm.c:1435
Inline: False
```
**Symbols:**

```
ffffffff81471150-ffffffff81471249: smack_inode_getsecurity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int smack_inode_getsecurity(struct inode *inode, const char *name, void **buffer, bool alloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff81488a20)
Location: security/smack/smack_lsm.c:1435
Inline: False
```
**Symbols:**

```
ffffffff81488a20-ffffffff81488b19: smack_inode_getsecurity (STB_LOCAL)
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
<b>Param type changed. </b>
<code>const struct inode *inode</code> ➡️ <code>struct inode *inode</code>
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
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct user_namespace *mnt_userns</code>
</li>
<li>
<b>Param reordered. </b>
<code>inode, name, buffer, alloc</code> ➡️ <code>mnt_userns, inode, name, buffer, alloc</code>
</li>
</ul>
</details>
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
<b>Param added. </b>
<code>struct mnt_idmap *idmap</code>
</li>
<li>
<b>Param removed. </b>
<code>struct user_namespace *mnt_userns</code>
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
