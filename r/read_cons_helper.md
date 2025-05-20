# Function: <code>read_cons_helper</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff813527a0)
Location: security/selinux/ss/policydb.c:1216
Inline: True
Direct callers:
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:class_read
```
**Symbols:**

```
ffffffff813527a0-ffffffff81352a61: read_cons_helper.isra.6 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff813887c0)
Location: security/selinux/ss/policydb.c:1216
Inline: True
Direct callers:
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:class_read
```
**Symbols:**

```
ffffffff813887c0-ffffffff81388a7d: read_cons_helper.isra.6 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff8139f270)
Location: security/selinux/ss/policydb.c:1219
Inline: True
Direct callers:
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:class_read
```
**Symbols:**

```
ffffffff8139f270-ffffffff8139f52d: read_cons_helper.isra.6 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff813b5780)
Location: security/selinux/ss/policydb.c:1219
Inline: True
Direct callers:
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:class_read
```
**Symbols:**

```
ffffffff813b5780-ffffffff813b5a2d: read_cons_helper.isra.8 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff813db8d0)
Location: security/selinux/ss/policydb.c:1219
Inline: True
Direct callers:
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:class_read
```
**Symbols:**

```
ffffffff813db8d0-ffffffff813dbb83: read_cons_helper.isra.8 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff8140be60)
Location: security/selinux/ss/policydb.c:1219
Inline: True
Direct callers:
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:class_read
```
**Symbols:**

```
ffffffff8140be60-ffffffff8140c110: read_cons_helper.isra.10 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff81428420)
Location: security/selinux/ss/policydb.c:1230
Inline: True
Direct callers:
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:class_read
```
**Symbols:**

```
ffffffff81428420-ffffffff814286f0: read_cons_helper.isra.10 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff814553e0)
Location: security/selinux/ss/policydb.c:1182
Inline: True
Direct callers:
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:class_read
```
**Symbols:**

```
ffffffff814553e0-ffffffff814556be: read_cons_helper.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff8146f180)
Location: security/selinux/ss/policydb.c:1184
Inline: True
Direct callers:
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:class_read
```
**Symbols:**

```
ffffffff8146f180-ffffffff8146f45e: read_cons_helper.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int read_cons_helper(struct policydb *p, struct constraint_node **nodep, int ncons, int allowxtarget, void *fp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff814c4ce0)
Location: security/selinux/ss/policydb.c:1170
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:class_read
```
**Symbols:**

```
ffffffff814c4ce0-ffffffff814c4fc7: read_cons_helper (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int read_cons_helper(struct policydb *p, struct constraint_node **nodep, int ncons, int allowxtarget, void *fp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff814e2640)
Location: security/selinux/ss/policydb.c:1202
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:class_read
```
**Symbols:**

```
ffffffff814e2640-ffffffff814e2927: read_cons_helper (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int read_cons_helper(struct policydb *p, struct constraint_node **nodep, int ncons, int allowxtarget, void *fp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff814e8020)
Location: security/selinux/ss/policydb.c:1200
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:class_read
```
**Symbols:**

```
ffffffff814e8020-ffffffff814e8304: read_cons_helper (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int read_cons_helper(struct policydb *p, struct constraint_node **nodep, int ncons, int allowxtarget, void *fp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff81541960)
Location: security/selinux/ss/policydb.c:1200
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:class_read
```
**Symbols:**

```
ffffffff81541960-ffffffff81541c44: read_cons_helper (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int read_cons_helper(struct policydb *p, struct constraint_node **nodep, int ncons, int allowxtarget, void *fp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff815da0f0)
Location: security/selinux/ss/policydb.c:1194
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:class_read
```
**Symbols:**

```
ffffffff815da0f0-ffffffff815da3f8: read_cons_helper (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int read_cons_helper(struct policydb *p, struct constraint_node **nodep, int ncons, int allowxtarget, void *fp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff816890c0)
Location: security/selinux/ss/policydb.c:1194
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:class_read
```
**Symbols:**

```
ffffffff816890c0-ffffffff816893c8: read_cons_helper (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int read_cons_helper(struct policydb *p, struct constraint_node **nodep, int ncons, int allowxtarget, void *fp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff816c2170)
Location: security/selinux/ss/policydb.c:1194
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:class_read
```
**Symbols:**

```
ffffffff816c2170-ffffffff816c2462: read_cons_helper (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int read_cons_helper(struct policydb *p, struct constraint_node **nodep, u32 ncons, int allowxtarget, void *fp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff816febf0)
Location: security/selinux/ss/policydb.c:1215
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:class_read
```
**Symbols:**

```
ffffffff816febf0-ffffffff816fef8e: read_cons_helper (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/ss/policydb.c (ffff80001055f400)
Location: security/selinux/ss/policydb.c:1184
Inline: True
Direct callers:
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:class_read
```
**Symbols:**

```
ffff80001055f400-ffff80001055f6b8: read_cons_helper.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int read_cons_helper(struct policydb *p, struct constraint_node **nodep, int ncons, int allowxtarget, void *fp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (c0712ef4)
Location: security/selinux/ss/policydb.c:1184
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:class_read
```
**Symbols:**

```
c0712ef4-c07131d0: read_cons_helper (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/ss/policydb.c (c0000000006beae0)
Location: security/selinux/ss/policydb.c:1184
Inline: True
Direct callers:
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:class_read
```
**Symbols:**

```
c0000000006beae0-c0000000006beecc: read_cons_helper.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffe0003b5042)
Location: security/selinux/ss/policydb.c:1184
Inline: True
Direct callers:
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:class_read
```
**Symbols:**

```
ffffffe0003b5042-ffffffe0003b5338: read_cons_helper.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff81467760)
Location: security/selinux/ss/policydb.c:1184
Inline: True
Direct callers:
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:class_read
```
**Symbols:**

```
ffffffff81467760-ffffffff81467a3e: read_cons_helper.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff81458190)
Location: security/selinux/ss/policydb.c:1184
Inline: True
Direct callers:
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:class_read
```
**Symbols:**

```
ffffffff81458190-ffffffff8145846e: read_cons_helper.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff81463800)
Location: security/selinux/ss/policydb.c:1184
Inline: True
Direct callers:
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:class_read
```
**Symbols:**

```
ffffffff81463800-ffffffff81463ade: read_cons_helper.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff8147b000)
Location: security/selinux/ss/policydb.c:1184
Inline: True
Direct callers:
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:class_read
```
**Symbols:**

```
ffffffff8147b000-ffffffff8147b2de: read_cons_helper.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int ncons</code> ➡️ <code>u32 ncons</code>
</li>
</ul>
</details>
</li>
</ul>
<b>Arch</b>
<ul>
</ul>
