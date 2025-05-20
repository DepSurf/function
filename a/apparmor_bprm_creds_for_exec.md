# Function: <code>apparmor_bprm_creds_for_exec</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int apparmor_bprm_creds_for_exec(struct linux_binprm *bprm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffffffff814f7880)
Location: security/apparmor/domain.c:852
Inline: False
```
**Symbols:**

```
ffffffff814f7880-ffffffff814f832c: apparmor_bprm_creds_for_exec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int apparmor_bprm_creds_for_exec(struct linux_binprm *bprm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffffffff815149d0)
Location: security/apparmor/domain.c:852
Inline: False
```
**Symbols:**

```
ffffffff815149d0-ffffffff8151547e: apparmor_bprm_creds_for_exec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int apparmor_bprm_creds_for_exec(struct linux_binprm *bprm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffffffff8151b280)
Location: security/apparmor/domain.c:854
Inline: False
```
**Symbols:**

```
ffffffff8151b280-ffffffff8151bdf2: apparmor_bprm_creds_for_exec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int apparmor_bprm_creds_for_exec(struct linux_binprm *bprm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/apparmor/domain.c (0)
Location: security/apparmor/domain.c:854
Inline: False
```
**Symbols:**

```
ffffffff81cd63ea-ffffffff81cd6467: apparmor_bprm_creds_for_exec.cold (STB_LOCAL)
ffffffff81579300-ffffffff81579eb9: apparmor_bprm_creds_for_exec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int apparmor_bprm_creds_for_exec(struct linux_binprm *bprm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/apparmor/domain.c (0)
Location: security/apparmor/domain.c:857
Inline: False
```
**Symbols:**

```
ffffffff81e89218-ffffffff81e8926c: apparmor_bprm_creds_for_exec.cold (STB_LOCAL)
ffffffff816173f0-ffffffff81617f94: apparmor_bprm_creds_for_exec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int apparmor_bprm_creds_for_exec(struct linux_binprm *bprm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/apparmor/domain.c (0)
Location: security/apparmor/domain.c:870
Inline: False
```
**Symbols:**

```
ffffffff82074b07-ffffffff82074b2a: apparmor_bprm_creds_for_exec.cold (STB_LOCAL)
ffffffff816ca260-ffffffff816caea3: apparmor_bprm_creds_for_exec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int apparmor_bprm_creds_for_exec(struct linux_binprm *bprm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/apparmor/domain.c (0)
Location: security/apparmor/domain.c:870
Inline: False
```
**Symbols:**

```
ffffffff820f471a-ffffffff820f472f: apparmor_bprm_creds_for_exec.cold (STB_LOCAL)
ffffffff81702f10-ffffffff817039ea: apparmor_bprm_creds_for_exec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int apparmor_bprm_creds_for_exec(struct linux_binprm *bprm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/apparmor/domain.c (0)
Location: security/apparmor/domain.c:877
Inline: False
```
**Symbols:**

```
ffffffff821d1b54-ffffffff821d1b69: apparmor_bprm_creds_for_exec.cold (STB_LOCAL)
ffffffff81740700-ffffffff817411ec: apparmor_bprm_creds_for_exec (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
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
