# Function: <code>selinux_bprm_creds_for_exec</code>

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
int selinux_bprm_creds_for_exec(struct linux_binprm *bprm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff814b7900)
Location: security/selinux/hooks.c:2289
Inline: False
```
**Symbols:**

```
ffffffff814b7900-ffffffff814b7baf: selinux_bprm_creds_for_exec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int selinux_bprm_creds_for_exec(struct linux_binprm *bprm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff814d55f0)
Location: security/selinux/hooks.c:2298
Inline: False
```
**Symbols:**

```
ffffffff814d55f0-ffffffff814d58bc: selinux_bprm_creds_for_exec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int selinux_bprm_creds_for_exec(struct linux_binprm *bprm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff814dc420)
Location: security/selinux/hooks.c:2351
Inline: False
```
**Symbols:**

```
ffffffff814dc420-ffffffff814dc6ec: selinux_bprm_creds_for_exec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int selinux_bprm_creds_for_exec(struct linux_binprm *bprm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff815358d0)
Location: security/selinux/hooks.c:2344
Inline: False
```
**Symbols:**

```
ffffffff815358d0-ffffffff81535b9c: selinux_bprm_creds_for_exec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int selinux_bprm_creds_for_exec(struct linux_binprm *bprm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff815cbcf0)
Location: security/selinux/hooks.c:2282
Inline: False
```
**Symbols:**

```
ffffffff815cbcf0-ffffffff815cbff2: selinux_bprm_creds_for_exec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int selinux_bprm_creds_for_exec(struct linux_binprm *bprm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81678ed0)
Location: security/selinux/hooks.c:2281
Inline: False
```
**Symbols:**

```
ffffffff81678ed0-ffffffff816791d2: selinux_bprm_creds_for_exec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int selinux_bprm_creds_for_exec(struct linux_binprm *bprm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff816b10f0)
Location: security/selinux/hooks.c:2268
Inline: False
```
**Symbols:**

```
ffffffff816b10f0-ffffffff816b13b2: selinux_bprm_creds_for_exec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int selinux_bprm_creds_for_exec(struct linux_binprm *bprm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:2308
Inline: False
```
**Symbols:**

```
ffffffff816ee0b0-ffffffff816ee3ab: selinux_bprm_creds_for_exec (STB_LOCAL)
ffffffff821d04db-ffffffff821d04f0: selinux_bprm_creds_for_exec.cold (STB_LOCAL)
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
