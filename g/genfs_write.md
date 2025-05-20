# Function: <code>genfs_write</code>

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
In security/selinux/ss/policydb.c (ffffffff81354bb5)
Location: security/selinux/ss/policydb.c:3156
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
In security/selinux/ss/policydb.c (ffffffff8138ab82)
Location: security/selinux/ss/policydb.c:3156
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
In security/selinux/ss/policydb.c (ffffffff813a1792)
Location: security/selinux/ss/policydb.c:3160
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
In security/selinux/ss/policydb.c (ffffffff813b819a)
Location: security/selinux/ss/policydb.c:3226
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
In security/selinux/ss/policydb.c (ffffffff813de310)
Location: security/selinux/ss/policydb.c:3226
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
In security/selinux/ss/policydb.c (ffffffff8140d9bb)
Location: security/selinux/ss/policydb.c:3226
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_write
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff8142ac6d)
Location: security/selinux/ss/policydb.c:3257
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_write
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
In security/selinux/ss/policydb.c (ffffffff814551e0)
Location: security/selinux/ss/policydb.c:3203
Inline: True
Direct callers:
  - security/selinux/ss/policydb.c:policydb_write
```
**Symbols:**

```
ffffffff814551e0-ffffffff81455320: genfs_write.isra.0 (STB_LOCAL)
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
In security/selinux/ss/policydb.c (ffffffff8146ef80)
Location: security/selinux/ss/policydb.c:3205
Inline: True
Direct callers:
  - security/selinux/ss/policydb.c:policydb_write
```
**Symbols:**

```
ffffffff8146ef80-ffffffff8146f0c0: genfs_write.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int genfs_write(struct policydb *p, void *fp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff814c4550)
Location: security/selinux/ss/policydb.c:3350
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_write
```
**Symbols:**

```
ffffffff814c4550-ffffffff814c4698: genfs_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int genfs_write(struct policydb *p, void *fp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff814e2070)
Location: security/selinux/ss/policydb.c:3392
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_write
```
**Symbols:**

```
ffffffff814e2070-ffffffff814e21b8: genfs_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int genfs_write(struct policydb *p, void *fp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff814e90a0)
Location: security/selinux/ss/policydb.c:3390
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_write
```
**Symbols:**

```
ffffffff814e90a0-ffffffff814e91e8: genfs_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int genfs_write(struct policydb *p, void *fp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff81542a10)
Location: security/selinux/ss/policydb.c:3389
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_write
```
**Symbols:**

```
ffffffff81542a10-ffffffff81542b58: genfs_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int genfs_write(struct policydb *p, void *fp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff815db450)
Location: security/selinux/ss/policydb.c:3381
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_write
```
**Symbols:**

```
ffffffff815db450-ffffffff815db683: genfs_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int genfs_write(struct policydb *p, void *fp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff81689480)
Location: security/selinux/ss/policydb.c:3381
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_write
```
**Symbols:**

```
ffffffff81689480-ffffffff8168968c: genfs_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int genfs_write(struct policydb *p, void *fp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff816c0550)
Location: security/selinux/ss/policydb.c:3385
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_write
```
**Symbols:**

```
ffffffff816c0550-ffffffff816c0758: genfs_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int genfs_write(struct policydb *p, void *fp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff816fce50)
Location: security/selinux/ss/policydb.c:3411
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_write
```
**Symbols:**

```
ffffffff816fce50-ffffffff816fd058: genfs_write (STB_LOCAL)
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
In security/selinux/ss/policydb.c (ffff80001055f1a8)
Location: security/selinux/ss/policydb.c:3205
Inline: True
Direct callers:
  - security/selinux/ss/policydb.c:policydb_write
```
**Symbols:**

```
ffff80001055f1a8-ffff80001055f324: genfs_write.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int genfs_write(struct policydb *p, void *fp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (c0712c58)
Location: security/selinux/ss/policydb.c:3205
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_write
```
**Symbols:**

```
c0712c58-c0712e04: genfs_write (STB_LOCAL)
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
In security/selinux/ss/policydb.c (c0000000006be7d0)
Location: security/selinux/ss/policydb.c:3205
Inline: True
Direct callers:
  - security/selinux/ss/policydb.c:policydb_write
```
**Symbols:**

```
c0000000006be7d0-c0000000006be9e8: genfs_write.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffe0003b8822)
Location: security/selinux/ss/policydb.c:3205
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_write
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
In security/selinux/ss/policydb.c (ffffffff81467560)
Location: security/selinux/ss/policydb.c:3205
Inline: True
Direct callers:
  - security/selinux/ss/policydb.c:policydb_write
```
**Symbols:**

```
ffffffff81467560-ffffffff814676a0: genfs_write.isra.0 (STB_LOCAL)
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
In security/selinux/ss/policydb.c (ffffffff81457f90)
Location: security/selinux/ss/policydb.c:3205
Inline: True
Direct callers:
  - security/selinux/ss/policydb.c:policydb_write
```
**Symbols:**

```
ffffffff81457f90-ffffffff814580d0: genfs_write.isra.0 (STB_LOCAL)
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
In security/selinux/ss/policydb.c (ffffffff81463600)
Location: security/selinux/ss/policydb.c:3205
Inline: True
Direct callers:
  - security/selinux/ss/policydb.c:policydb_write
```
**Symbols:**

```
ffffffff81463600-ffffffff81463740: genfs_write.isra.0 (STB_LOCAL)
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
In security/selinux/ss/policydb.c (ffffffff8147ae00)
Location: security/selinux/ss/policydb.c:3205
Inline: True
Direct callers:
  - security/selinux/ss/policydb.c:policydb_write
```
**Symbols:**

```
ffffffff8147ae00-ffffffff8147af40: genfs_write.isra.0 (STB_LOCAL)
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
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
</ul>
