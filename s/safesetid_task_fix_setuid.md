# Function: <code>safesetid_task_fix_setuid</code>

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
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int safesetid_task_fix_setuid(struct cred *new, const struct cred *old, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/safesetid/lsm.c (ffffffff814992a0)
Location: security/safesetid/lsm.c:128
Inline: True
```
**Symbols:**

```
ffffffff814992a0-ffffffff81499317: safesetid_task_fix_setuid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int safesetid_task_fix_setuid(struct cred *new, const struct cred *old, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/safesetid/lsm.c (ffffffff814b31c0)
Location: security/safesetid/lsm.c:128
Inline: True
```
**Symbols:**

```
ffffffff814b31c0-ffffffff814b3237: safesetid_task_fix_setuid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int safesetid_task_fix_setuid(struct cred *new, const struct cred *old, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/safesetid/lsm.c (ffffffff815125b0)
Location: security/safesetid/lsm.c:128
Inline: True
```
**Symbols:**

```
ffffffff815125b0-ffffffff81512668: safesetid_task_fix_setuid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int safesetid_task_fix_setuid(struct cred *new, const struct cred *old, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/safesetid/lsm.c (ffffffff8152f710)
Location: security/safesetid/lsm.c:199
Inline: True
```
**Symbols:**

```
ffffffff8152f710-ffffffff8152f781: safesetid_task_fix_setuid.part.0 (STB_LOCAL)
ffffffff8152f790-ffffffff8152f81d: safesetid_task_fix_setuid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int safesetid_task_fix_setuid(struct cred *new, const struct cred *old, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/safesetid/lsm.c (ffffffff81535980)
Location: security/safesetid/lsm.c:196
Inline: True
```
**Symbols:**

```
ffffffff81535980-ffffffff81535a61: safesetid_task_fix_setuid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int safesetid_task_fix_setuid(struct cred *new, const struct cred *old, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/safesetid/lsm.c (ffffffff81593f70)
Location: security/safesetid/lsm.c:196
Inline: True
```
**Symbols:**

```
ffffffff81593f70-ffffffff81594051: safesetid_task_fix_setuid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int safesetid_task_fix_setuid(struct cred *new, const struct cred *old, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/safesetid/lsm.c (ffffffff81635f90)
Location: security/safesetid/lsm.c:196
Inline: False
```
**Symbols:**

```
ffffffff81635f90-ffffffff8163608b: safesetid_task_fix_setuid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int safesetid_task_fix_setuid(struct cred *new, const struct cred *old, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/safesetid/lsm.c (ffffffff816ecf60)
Location: security/safesetid/lsm.c:191
Inline: False
```
**Symbols:**

```
ffffffff816ecf60-ffffffff816ed05b: safesetid_task_fix_setuid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int safesetid_task_fix_setuid(struct cred *new, const struct cred *old, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/safesetid/lsm.c (ffffffff81727380)
Location: security/safesetid/lsm.c:191
Inline: False
```
**Symbols:**

```
ffffffff81727380-ffffffff8172747b: safesetid_task_fix_setuid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int safesetid_task_fix_setuid(struct cred *new, const struct cred *old, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/safesetid/lsm.c (ffffffff81768620)
Location: security/safesetid/lsm.c:191
Inline: False
```
**Symbols:**

```
ffffffff81768620-ffffffff8176871b: safesetid_task_fix_setuid (STB_LOCAL)
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
int safesetid_task_fix_setuid(struct cred *new, const struct cred *old, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/safesetid/lsm.c (ffff8000105aae60)
Location: security/safesetid/lsm.c:128
Inline: True
```
**Symbols:**

```
ffff8000105aae60-ffff8000105aaefc: safesetid_task_fix_setuid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int safesetid_task_fix_setuid(struct cred *new, const struct cred *old, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/safesetid/lsm.c (c075aa40)
Location: security/safesetid/lsm.c:128
Inline: True
```
**Symbols:**

```
c075aa40-c075aad8: safesetid_task_fix_setuid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int safesetid_task_fix_setuid(struct cred *new, const struct cred *old, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/safesetid/lsm.c (c000000000728a40)
Location: security/safesetid/lsm.c:128
Inline: True
```
**Symbols:**

```
c000000000728a40-c000000000728b04: safesetid_task_fix_setuid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int safesetid_task_fix_setuid(struct cred *new, const struct cred *old, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/safesetid/lsm.c (ffffffe0003f3aca)
Location: security/safesetid/lsm.c:128
Inline: True
```
**Symbols:**

```
ffffffe0003f3aca-ffffffe0003f3b50: safesetid_task_fix_setuid (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int safesetid_task_fix_setuid(struct cred *new, const struct cred *old, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/safesetid/lsm.c (ffffffff814ab7a0)
Location: security/safesetid/lsm.c:128
Inline: True
```
**Symbols:**

```
ffffffff814ab7a0-ffffffff814ab817: safesetid_task_fix_setuid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int safesetid_task_fix_setuid(struct cred *new, const struct cred *old, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/safesetid/lsm.c (ffffffff8149c1c0)
Location: security/safesetid/lsm.c:128
Inline: True
```
**Symbols:**

```
ffffffff8149c1c0-ffffffff8149c237: safesetid_task_fix_setuid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int safesetid_task_fix_setuid(struct cred *new, const struct cred *old, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/safesetid/lsm.c (ffffffff814a7840)
Location: security/safesetid/lsm.c:128
Inline: True
```
**Symbols:**

```
ffffffff814a7840-ffffffff814a78b7: safesetid_task_fix_setuid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int safesetid_task_fix_setuid(struct cred *new, const struct cred *old, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/safesetid/lsm.c (ffffffff814c01d0)
Location: security/safesetid/lsm.c:128
Inline: True
```
**Symbols:**

```
ffffffff814c01d0-ffffffff814c0247: safesetid_task_fix_setuid (STB_LOCAL)
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
