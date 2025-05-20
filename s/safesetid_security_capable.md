# Function: <code>safesetid_security_capable</code>

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
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int safesetid_security_capable(const struct cred *cred, struct user_namespace *ns, int cap, unsigned int opts);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/safesetid/lsm.c (ffffffff81499385)
Location: security/safesetid/lsm.c:63
Inline: True
```
**Symbols:**

```
ffffffff81499260-ffffffff81499294: safesetid_security_capable (STB_LOCAL)
ffffffff81499385-ffffffff8149939c: safesetid_security_capable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int safesetid_security_capable(const struct cred *cred, struct user_namespace *ns, int cap, unsigned int opts);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/safesetid/lsm.c (ffffffff814b32a5)
Location: security/safesetid/lsm.c:63
Inline: True
```
**Symbols:**

```
ffffffff814b3180-ffffffff814b31b4: safesetid_security_capable (STB_LOCAL)
ffffffff814b32a5-ffffffff814b32bc: safesetid_security_capable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int safesetid_security_capable(const struct cred *cred, struct user_namespace *ns, int cap, unsigned int opts);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/safesetid/lsm.c (ffffffff8151274a)
Location: security/safesetid/lsm.c:63
Inline: True
```
**Symbols:**

```
ffffffff81512670-ffffffff815126d6: safesetid_security_capable (STB_LOCAL)
ffffffff8151274a-ffffffff81512761: safesetid_security_capable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int safesetid_security_capable(const struct cred *cred, struct user_namespace *ns, int cap, unsigned int opts);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/safesetid/lsm.c (ffffffff8152f3c3)
Location: security/safesetid/lsm.c:90
Inline: True
```
**Symbols:**

```
ffffffff8152f3a0-ffffffff8152f4af: safesetid_security_capable (STB_LOCAL)
ffffffff81bf1837-ffffffff81bf1865: safesetid_security_capable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int safesetid_security_capable(const struct cred *cred, struct user_namespace *ns, int cap, unsigned int opts);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/safesetid/lsm.c (ffffffff81535653)
Location: security/safesetid/lsm.c:90
Inline: True
```
**Symbols:**

```
ffffffff81535630-ffffffff8153573f: safesetid_security_capable (STB_LOCAL)
ffffffff81be3849-ffffffff81be3877: safesetid_security_capable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int safesetid_security_capable(const struct cred *cred, struct user_namespace *ns, int cap, unsigned int opts);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/safesetid/lsm.c (ffffffff81593c23)
Location: security/safesetid/lsm.c:90
Inline: True
```
**Symbols:**

```
ffffffff81593c00-ffffffff81593d18: safesetid_security_capable (STB_LOCAL)
ffffffff81cd6980-ffffffff81cd69ae: safesetid_security_capable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int safesetid_security_capable(const struct cred *cred, struct user_namespace *ns, int cap, unsigned int opts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/safesetid/lsm.c (0)
Location: security/safesetid/lsm.c:90
Inline: False
```
**Symbols:**

```
ffffffff81635bb0-ffffffff81635cc5: safesetid_security_capable (STB_LOCAL)
ffffffff81e898d9-ffffffff81e8990f: safesetid_security_capable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int safesetid_security_capable(const struct cred *cred, struct user_namespace *ns, int cap, unsigned int opts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/safesetid/lsm.c (ffffffff816ec8d0)
Location: security/safesetid/lsm.c:91
Inline: False
```
**Symbols:**

```
ffffffff816ec8d0-ffffffff816eca12: safesetid_security_capable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int safesetid_security_capable(const struct cred *cred, struct user_namespace *ns, int cap, unsigned int opts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/safesetid/lsm.c (ffffffff81726d00)
Location: security/safesetid/lsm.c:91
Inline: False
```
**Symbols:**

```
ffffffff81726d00-ffffffff81726e42: safesetid_security_capable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int safesetid_security_capable(const struct cred *cred, struct user_namespace *ns, int cap, unsigned int opts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/safesetid/lsm.c (ffffffff81767f50)
Location: security/safesetid/lsm.c:91
Inline: False
```
**Symbols:**

```
ffffffff81767f50-ffffffff81768092: safesetid_security_capable (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int safesetid_security_capable(const struct cred *cred, struct user_namespace *ns, int cap, unsigned int opts);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/safesetid/lsm.c (ffff8000105aadf0)
Location: security/safesetid/lsm.c:63
Inline: True
```
**Symbols:**

```
ffff8000105aadf0-ffff8000105aae5c: safesetid_security_capable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int safesetid_security_capable(const struct cred *cred, struct user_namespace *ns, int cap, unsigned int opts);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/safesetid/lsm.c (c075a9e4)
Location: security/safesetid/lsm.c:63
Inline: True
```
**Symbols:**

```
c075a9e4-c075aa40: safesetid_security_capable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int safesetid_security_capable(const struct cred *cred, struct user_namespace *ns, int cap, unsigned int opts);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/safesetid/lsm.c (c0000000007289b0)
Location: security/safesetid/lsm.c:63
Inline: True
```
**Symbols:**

```
c0000000007289b0-c000000000728a3c: safesetid_security_capable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int safesetid_security_capable(const struct cred *cred, struct user_namespace *ns, int cap, unsigned int opts);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/safesetid/lsm.c (ffffffe0003f3a66)
Location: security/safesetid/lsm.c:63
Inline: True
```
**Symbols:**

```
ffffffe0003f3a66-ffffffe0003f3aca: safesetid_security_capable (STB_LOCAL)
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
int safesetid_security_capable(const struct cred *cred, struct user_namespace *ns, int cap, unsigned int opts);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/safesetid/lsm.c (ffffffff814ab885)
Location: security/safesetid/lsm.c:63
Inline: True
```
**Symbols:**

```
ffffffff814ab760-ffffffff814ab794: safesetid_security_capable (STB_LOCAL)
ffffffff814ab885-ffffffff814ab89c: safesetid_security_capable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
int safesetid_security_capable(const struct cred *cred, struct user_namespace *ns, int cap, unsigned int opts);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/safesetid/lsm.c (ffffffff8149c2a5)
Location: security/safesetid/lsm.c:63
Inline: True
```
**Symbols:**

```
ffffffff8149c180-ffffffff8149c1b4: safesetid_security_capable (STB_LOCAL)
ffffffff8149c2a5-ffffffff8149c2bc: safesetid_security_capable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
int safesetid_security_capable(const struct cred *cred, struct user_namespace *ns, int cap, unsigned int opts);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/safesetid/lsm.c (ffffffff814a7925)
Location: security/safesetid/lsm.c:63
Inline: True
```
**Symbols:**

```
ffffffff814a7800-ffffffff814a7834: safesetid_security_capable (STB_LOCAL)
ffffffff814a7925-ffffffff814a793c: safesetid_security_capable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
int safesetid_security_capable(const struct cred *cred, struct user_namespace *ns, int cap, unsigned int opts);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/safesetid/lsm.c (ffffffff814c02b5)
Location: security/safesetid/lsm.c:63
Inline: True
```
**Symbols:**

```
ffffffff814c0190-ffffffff814c01c4: safesetid_security_capable (STB_LOCAL)
ffffffff814c02b5-ffffffff814c02cc: safesetid_security_capable.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
