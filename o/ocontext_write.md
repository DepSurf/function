# Function: <code>ocontext_write</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff81354a65)
Location: security/selinux/ss/policydb.c:3059
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_write
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff8138aa24)
Location: security/selinux/ss/policydb.c:3059
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_write
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff813a1634)
Location: security/selinux/ss/policydb.c:3063
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_write
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff813b7e22)
Location: security/selinux/ss/policydb.c:3102
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_write
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff813ddf92)
Location: security/selinux/ss/policydb.c:3102
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_write
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (0)
Location: security/selinux/ss/policydb.c:3102
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_write
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
In security/selinux/ss/policydb.c (ffffffff81427410)
Location: security/selinux/ss/policydb.c:3127
Inline: True
Direct callers:
  - security/selinux/ss/policydb.c:policydb_write
```
**Symbols:**

```
ffffffff81427410-ffffffff8142770f: ocontext_write.isra.27 (STB_LOCAL)
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
In security/selinux/ss/policydb.c (ffffffff81454c70)
Location: security/selinux/ss/policydb.c:3073
Inline: True
Direct callers:
  - security/selinux/ss/policydb.c:policydb_write
```
**Symbols:**

```
ffffffff81454c70-ffffffff81454fa9: ocontext_write.isra.0 (STB_LOCAL)
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
In security/selinux/ss/policydb.c (ffffffff8146ea10)
Location: security/selinux/ss/policydb.c:3075
Inline: True
Direct callers:
  - security/selinux/ss/policydb.c:policydb_write
```
**Symbols:**

```
ffffffff8146ea10-ffffffff8146ed49: ocontext_write.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ocontext_write(struct policydb *p, struct policydb_compat_info *info, void *fp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff814c4180)
Location: security/selinux/ss/policydb.c:3220
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_write
```
**Symbols:**

```
ffffffff814c4180-ffffffff814c44b5: ocontext_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ocontext_write(struct policydb *p, struct policydb_compat_info *info, void *fp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff814e1ca0)
Location: security/selinux/ss/policydb.c:3262
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_write
```
**Symbols:**

```
ffffffff814e1ca0-ffffffff814e1fd5: ocontext_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ocontext_write(struct policydb *p, struct policydb_compat_info *info, void *fp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff814e8cd0)
Location: security/selinux/ss/policydb.c:3260
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_write
```
**Symbols:**

```
ffffffff814e8cd0-ffffffff814e9005: ocontext_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ocontext_write(struct policydb *p, struct policydb_compat_info *info, void *fp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff81542610)
Location: security/selinux/ss/policydb.c:3259
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_write
```
**Symbols:**

```
ffffffff81542610-ffffffff81542971: ocontext_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ocontext_write(struct policydb *p, const struct policydb_compat_info *info, void *fp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff815dad10)
Location: security/selinux/ss/policydb.c:3251
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_write
```
**Symbols:**

```
ffffffff815dad10-ffffffff815db24a: ocontext_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ocontext_write(struct policydb *p, const struct policydb_compat_info *info, void *fp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff81689820)
Location: security/selinux/ss/policydb.c:3251
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_write
```
**Symbols:**

```
ffffffff81689820-ffffffff81689f39: ocontext_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ocontext_write(struct policydb *p, const struct policydb_compat_info *info, void *fp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff816c16e0)
Location: security/selinux/ss/policydb.c:3255
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_write
```
**Symbols:**

```
ffffffff816c16e0-ffffffff816c1d58: ocontext_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ocontext_write(struct policydb *p, const struct policydb_compat_info *info, void *fp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff816fe150)
Location: security/selinux/ss/policydb.c:3280
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_write
```
**Symbols:**

```
ffffffff816fe150-ffffffff816fe7c8: ocontext_write (STB_LOCAL)
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
In security/selinux/ss/policydb.c (ffff80001055ecd8)
Location: security/selinux/ss/policydb.c:3075
Inline: True
Direct callers:
  - security/selinux/ss/policydb.c:policydb_write
```
**Symbols:**

```
ffff80001055ecd8-ffff80001055f094: ocontext_write.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ocontext_write(struct policydb *p, struct policydb_compat_info *info, void *fp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (c071272c)
Location: security/selinux/ss/policydb.c:3075
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_write
```
**Symbols:**

```
c071272c-c0712b50: ocontext_write (STB_LOCAL)
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
In security/selinux/ss/policydb.c (c0000000006be1a0)
Location: security/selinux/ss/policydb.c:3075
Inline: True
Direct callers:
  - security/selinux/ss/policydb.c:policydb_write
```
**Symbols:**

```
c0000000006be1a0-c0000000006be640: ocontext_write.isra.0 (STB_LOCAL)
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
In security/selinux/ss/policydb.c (ffffffe0003b6002)
Location: security/selinux/ss/policydb.c:3075
Inline: True
Direct callers:
  - security/selinux/ss/policydb.c:policydb_write
```
**Symbols:**

```
ffffffe0003b6002-ffffffe0003b64c6: ocontext_write.isra.0 (STB_LOCAL)
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
In security/selinux/ss/policydb.c (ffffffff81466ff0)
Location: security/selinux/ss/policydb.c:3075
Inline: True
Direct callers:
  - security/selinux/ss/policydb.c:policydb_write
```
**Symbols:**

```
ffffffff81466ff0-ffffffff81467329: ocontext_write.isra.0 (STB_LOCAL)
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
In security/selinux/ss/policydb.c (ffffffff81457a20)
Location: security/selinux/ss/policydb.c:3075
Inline: True
Direct callers:
  - security/selinux/ss/policydb.c:policydb_write
```
**Symbols:**

```
ffffffff81457a20-ffffffff81457d59: ocontext_write.isra.0 (STB_LOCAL)
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
In security/selinux/ss/policydb.c (ffffffff81463090)
Location: security/selinux/ss/policydb.c:3075
Inline: True
Direct callers:
  - security/selinux/ss/policydb.c:policydb_write
```
**Symbols:**

```
ffffffff81463090-ffffffff814633c9: ocontext_write.isra.0 (STB_LOCAL)
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
In security/selinux/ss/policydb.c (ffffffff8147a890)
Location: security/selinux/ss/policydb.c:3075
Inline: True
Direct callers:
  - security/selinux/ss/policydb.c:policydb_write
```
**Symbols:**

```
ffffffff8147a890-ffffffff8147abc9: ocontext_write.isra.0 (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct policydb_compat_info *info</code> ➡️ <code>const struct policydb_compat_info *info</code>
</li>
</ul>
</details>
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
</ul>
