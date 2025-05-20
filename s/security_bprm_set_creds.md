# Function: <code>security_bprm_set_creds</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int security_bprm_set_creds(struct linux_binprm *bprm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8133d000)
Location: security/security.c:239
Inline: False
```
**Symbols:**

```
ffffffff8133d000-ffffffff8133d043: security_bprm_set_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int security_bprm_set_creds(struct linux_binprm *bprm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81372630)
Location: security/security.c:240
Inline: False
```
**Symbols:**

```
ffffffff81372630-ffffffff81372673: security_bprm_set_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int security_bprm_set_creds(struct linux_binprm *bprm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81388f60)
Location: security/security.c:240
Inline: False
```
**Symbols:**

```
ffffffff81388f60-ffffffff81388fa3: security_bprm_set_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int security_bprm_set_creds(struct linux_binprm *bprm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8139e2d0)
Location: security/security.c:811
Inline: False
```
**Symbols:**

```
ffffffff8139e2d0-ffffffff8139e313: security_bprm_set_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int security_bprm_set_creds(struct linux_binprm *bprm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813c3c90)
Location: security/security.c:761
Inline: False
Direct callers:
  - fs/exec.c:prepare_binprm
```
**Symbols:**

```
ffffffff813c3c90-ffffffff813c3cd9: security_bprm_set_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int security_bprm_set_creds(struct linux_binprm *bprm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813f42f0)
Location: security/security.c:338
Inline: False
Direct callers:
  - fs/exec.c:prepare_binprm
```
**Symbols:**

```
ffffffff813f42f0-ffffffff813f432a: security_bprm_set_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int security_bprm_set_creds(struct linux_binprm *bprm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8140f6d0)
Location: security/security.c:820
Inline: False
Direct callers:
  - fs/exec.c:prepare_binprm
```
**Symbols:**

```
ffffffff8140f6d0-ffffffff8140f70a: security_bprm_set_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int security_bprm_set_creds(struct linux_binprm *bprm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8143cb90)
Location: security/security.c:819
Inline: False
Direct callers:
  - fs/exec.c:prepare_binprm
```
**Symbols:**

```
ffffffff8143cb90-ffffffff8143cbd1: security_bprm_set_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int security_bprm_set_creds(struct linux_binprm *bprm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81456690)
Location: security/security.c:853
Inline: False
Direct callers:
  - fs/exec.c:prepare_binprm
```
**Symbols:**

```
ffffffff81456690-ffffffff814566ca: security_bprm_set_creds (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int security_bprm_set_creds(struct linux_binprm *bprm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffff800010541f70)
Location: security/security.c:853
Inline: False
Direct callers:
  - fs/exec.c:prepare_binprm
```
**Symbols:**

```
ffff800010541f70-ffff800010541fc0: security_bprm_set_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int security_bprm_set_creds(struct linux_binprm *bprm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c06f7f1c)
Location: security/security.c:853
Inline: False
Direct callers:
  - fs/exec.c:prepare_binprm
```
**Symbols:**

```
c06f7f1c-c06f7f70: security_bprm_set_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int security_bprm_set_creds(struct linux_binprm *bprm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c000000000694d80)
Location: security/security.c:853
Inline: False
Direct callers:
  - fs/exec.c:prepare_binprm
```
**Symbols:**

```
c000000000694d80-c000000000694e28: security_bprm_set_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int security_bprm_set_creds(struct linux_binprm *bprm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffe00039ea10)
Location: security/security.c:853
Inline: False
Direct callers:
  - fs/exec.c:prepare_binprm
```
**Symbols:**

```
ffffffe00039ea10-ffffffe00039ea4c: security_bprm_set_creds (STB_GLOBAL)
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
int security_bprm_set_creds(struct linux_binprm *bprm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8144ec70)
Location: security/security.c:853
Inline: False
Direct callers:
  - fs/exec.c:prepare_binprm
```
**Symbols:**

```
ffffffff8144ec70-ffffffff8144ecaa: security_bprm_set_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int security_bprm_set_creds(struct linux_binprm *bprm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8143f6c0)
Location: security/security.c:853
Inline: False
Direct callers:
  - fs/exec.c:prepare_binprm
```
**Symbols:**

```
ffffffff8143f6c0-ffffffff8143f6fa: security_bprm_set_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int security_bprm_set_creds(struct linux_binprm *bprm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8144ad10)
Location: security/security.c:853
Inline: False
Direct callers:
  - fs/exec.c:prepare_binprm
```
**Symbols:**

```
ffffffff8144ad10-ffffffff8144ad4a: security_bprm_set_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int security_bprm_set_creds(struct linux_binprm *bprm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814620e0)
Location: security/security.c:853
Inline: False
Direct callers:
  - fs/exec.c:prepare_binprm
```
**Symbols:**

```
ffffffff814620e0-ffffffff8146211a: security_bprm_set_creds (STB_GLOBAL)
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
