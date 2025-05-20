# Function: <code>get_current_tty</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct tty_struct *get_current_tty();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff814e0a90)
Location: drivers/tty/tty_io.c:557
Inline: False
Direct callers:
  - security/apparmor/file.c:aa_inherit_files
  - drivers/tty/tty_io.c:tty_vhangup_self
  - drivers/tty/tty_io.c:tty_open
```
**Symbols:**

```
ffffffff814e0a90-ffffffff814e0b33: get_current_tty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct tty_struct *get_current_tty();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81532480)
Location: drivers/tty/tty_io.c:564
Inline: False
Direct callers:
  - security/apparmor/file.c:aa_inherit_files
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_vhangup_self
```
**Symbols:**

```
ffffffff81532480-ffffffff81532523: get_current_tty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct tty_struct *get_current_tty();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff8155ebb0)
Location: drivers/tty/tty_io.c:564
Inline: False
Direct callers:
  - security/apparmor/file.c:aa_inherit_files
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_vhangup_self
```
**Symbols:**

```
ffffffff8155ebb0-ffffffff8155ec53: get_current_tty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct tty_struct *get_current_tty();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_jobctrl.c (ffffffff8157cc80)
Location: drivers/tty/tty_jobctrl.c:155
Inline: False
Direct callers:
  - security/apparmor/file.c:aa_inherit_files
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_vhangup_self
```
**Symbols:**

```
ffffffff8157cc80-ffffffff8157cce2: get_current_tty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct tty_struct *get_current_tty();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_jobctrl.c (ffffffff815e1930)
Location: drivers/tty/tty_jobctrl.c:156
Inline: False
Direct callers:
  - security/apparmor/file.c:aa_inherit_files
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_vhangup_self
```
**Symbols:**

```
ffffffff815e1930-ffffffff815e1998: get_current_tty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct tty_struct *get_current_tty();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_jobctrl.c (ffffffff8161abf0)
Location: drivers/tty/tty_jobctrl.c:156
Inline: False
Direct callers:
  - security/apparmor/file.c:aa_inherit_files
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_vhangup_self
```
**Symbols:**

```
ffffffff8161abf0-ffffffff8161ac58: get_current_tty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct tty_struct *get_current_tty();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_jobctrl.c (ffffffff81637e60)
Location: drivers/tty/tty_jobctrl.c:156
Inline: False
Direct callers:
  - security/apparmor/file.c:aa_inherit_files
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_vhangup_self
```
**Symbols:**

```
ffffffff81637e60-ffffffff81637ec8: get_current_tty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct tty_struct *get_current_tty();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_jobctrl.c (ffffffff8166c100)
Location: drivers/tty/tty_jobctrl.c:156
Inline: False
Direct callers:
  - security/apparmor/file.c:aa_inherit_files
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_vhangup_self
```
**Symbols:**

```
ffffffff8166c100-ffffffff8166c160: get_current_tty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct tty_struct *get_current_tty();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_jobctrl.c (ffffffff8168e770)
Location: drivers/tty/tty_jobctrl.c:156
Inline: False
Direct callers:
  - security/apparmor/file.c:aa_inherit_files
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_vhangup_self
```
**Symbols:**

```
ffffffff8168e770-ffffffff8168e7d0: get_current_tty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct tty_struct *get_current_tty();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_jobctrl.c (ffffffff81740aa0)
Location: drivers/tty/tty_jobctrl.c:156
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_bprm_committing_creds
  - security/apparmor/file.c:aa_inherit_files
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_vhangup_self
```
**Symbols:**

```
ffffffff81740aa0-ffffffff81740b2f: get_current_tty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct tty_struct *get_current_tty();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_jobctrl.c (ffffffff8175c9d0)
Location: drivers/tty/tty_jobctrl.c:158
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_bprm_committing_creds
  - security/apparmor/file.c:aa_inherit_files
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_vhangup_self
```
**Symbols:**

```
ffffffff8175c9d0-ffffffff8175ca5f: get_current_tty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct tty_struct *get_current_tty();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_jobctrl.c (ffffffff81740860)
Location: drivers/tty/tty_jobctrl.c:160
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_bprm_committing_creds
  - security/apparmor/file.c:aa_inherit_files
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_vhangup_self
```
**Symbols:**

```
ffffffff81740860-ffffffff817408ef: get_current_tty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct tty_struct *get_current_tty();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_jobctrl.c (ffffffff817c12c0)
Location: drivers/tty/tty_jobctrl.c:160
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_bprm_committing_creds
  - security/apparmor/file.c:aa_inherit_files
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_vhangup_self
```
**Symbols:**

```
ffffffff817c12c0-ffffffff817c134f: get_current_tty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct tty_struct *get_current_tty();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_jobctrl.c (ffffffff818fdc80)
Location: drivers/tty/tty_jobctrl.c:160
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_bprm_committing_creds
  - security/apparmor/file.c:aa_inherit_files
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_vhangup_self
```
**Symbols:**

```
ffffffff818fdc80-ffffffff818fdd12: get_current_tty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct tty_struct *get_current_tty();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_jobctrl.c (ffffffff81a57420)
Location: drivers/tty/tty_jobctrl.c:160
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_bprm_committing_creds
  - security/apparmor/file.c:aa_inherit_files
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_vhangup_self
```
**Symbols:**

```
ffffffff81a57420-ffffffff81a574b3: get_current_tty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct tty_struct *get_current_tty();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_jobctrl.c (ffffffff81aa1a20)
Location: drivers/tty/tty_jobctrl.c:160
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_bprm_committing_creds
  - security/apparmor/file.c:aa_inherit_files
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_vhangup_self
```
**Symbols:**

```
ffffffff81aa1a20-ffffffff81aa1ab3: get_current_tty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct tty_struct *get_current_tty();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_jobctrl.c (ffffffff81af4480)
Location: drivers/tty/tty_jobctrl.c:160
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_bprm_committing_creds
  - security/apparmor/file.c:aa_inherit_files
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_vhangup_self
```
**Symbols:**

```
ffffffff81af4480-ffffffff81af4513: get_current_tty (STB_GLOBAL)
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
struct tty_struct *get_current_tty();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_jobctrl.c (ffff80001085fc98)
Location: drivers/tty/tty_jobctrl.c:156
Inline: False
Direct callers:
  - security/apparmor/file.c:aa_inherit_files
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_vhangup_self
```
**Symbols:**

```
ffff80001085fc98-ffff80001085fd50: get_current_tty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct tty_struct *get_current_tty();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_jobctrl.c (c0967048)
Location: drivers/tty/tty_jobctrl.c:156
Inline: False
Direct callers:
  - security/apparmor/file.c:aa_inherit_files
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_vhangup_self
```
**Symbols:**

```
c0967048-c09670c0: get_current_tty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct tty_struct *get_current_tty();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_jobctrl.c (c0000000008ff090)
Location: drivers/tty/tty_jobctrl.c:156
Inline: False
Direct callers:
  - security/apparmor/file.c:aa_inherit_files
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_vhangup_self
```
**Symbols:**

```
c0000000008ff090-c0000000008ff110: get_current_tty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct tty_struct *get_current_tty();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_jobctrl.c (ffffffe000537e06)
Location: drivers/tty/tty_jobctrl.c:156
Inline: False
Direct callers:
  - security/apparmor/file.c:aa_inherit_files
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_vhangup_self
```
**Symbols:**

```
ffffffe000537e06-ffffffe000537e54: get_current_tty (STB_GLOBAL)
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
struct tty_struct *get_current_tty();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_jobctrl.c (ffffffff816541f0)
Location: drivers/tty/tty_jobctrl.c:156
Inline: False
Direct callers:
  - security/apparmor/file.c:aa_inherit_files
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_vhangup_self
```
**Symbols:**

```
ffffffff816541f0-ffffffff81654250: get_current_tty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct tty_struct *get_current_tty();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_jobctrl.c (ffffffff816345d0)
Location: drivers/tty/tty_jobctrl.c:156
Inline: False
Direct callers:
  - security/apparmor/file.c:aa_inherit_files
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_vhangup_self
```
**Symbols:**

```
ffffffff816345d0-ffffffff81634630: get_current_tty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct tty_struct *get_current_tty();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_jobctrl.c (ffffffff816825b0)
Location: drivers/tty/tty_jobctrl.c:156
Inline: False
Direct callers:
  - security/apparmor/file.c:aa_inherit_files
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_vhangup_self
```
**Symbols:**

```
ffffffff816825b0-ffffffff81682610: get_current_tty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct tty_struct *get_current_tty();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_jobctrl.c (ffffffff8169cc10)
Location: drivers/tty/tty_jobctrl.c:156
Inline: False
Direct callers:
  - security/apparmor/file.c:aa_inherit_files
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_vhangup_self
```
**Symbols:**

```
ffffffff8169cc10-ffffffff8169cc70: get_current_tty (STB_GLOBAL)
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
