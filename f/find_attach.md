# Function: <code>find_attach</code>

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
In security/apparmor/domain.c (ffffffff81379c10)
Location: security/apparmor/domain.c:356
Inline: True
Direct callers:
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
```
**Symbols:**

```
ffffffff81379c10-ffffffff81379d07: find_attach.isra.8 (STB_LOCAL)
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
In security/apparmor/domain.c (ffffffff813b3440)
Location: security/apparmor/domain.c:356
Inline: True
Direct callers:
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
```
**Symbols:**

```
ffffffff813b3440-ffffffff813b3544: find_attach.isra.8 (STB_LOCAL)
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
In security/apparmor/domain.c (ffffffff813ca650)
Location: security/apparmor/domain.c:356
Inline: True
Direct callers:
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
```
**Symbols:**

```
ffffffff813ca650-ffffffff813ca754: find_attach.isra.8 (STB_LOCAL)
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
In security/apparmor/domain.c (ffffffff813df220)
Location: security/apparmor/domain.c:352
Inline: True
Direct callers:
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
```
**Symbols:**

```
ffffffff813df220-ffffffff813df2df: find_attach.isra.7 (STB_LOCAL)
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
In security/apparmor/domain.c (ffffffff81406640)
Location: security/apparmor/domain.c:373
Inline: True
Direct callers:
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
```
**Symbols:**

```
ffffffff81406640-ffffffff8140675d: find_attach.isra.7 (STB_LOCAL)
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
In security/apparmor/domain.c (ffffffff81437df0)
Location: security/apparmor/domain.c:478
Inline: True
Direct callers:
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
```
**Symbols:**

```
ffffffff81437df0-ffffffff81437f42: find_attach.isra.9 (STB_LOCAL)
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
In security/apparmor/domain.c (ffffffff814549b0)
Location: security/apparmor/domain.c:478
Inline: True
Direct callers:
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
```
**Symbols:**

```
ffffffff814549b0-ffffffff81454b0d: find_attach.isra.10 (STB_LOCAL)
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
In security/apparmor/domain.c (ffffffff81482350)
Location: security/apparmor/domain.c:474
Inline: True
Direct callers:
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
```
**Symbols:**

```
ffffffff81482350-ffffffff814824b6: find_attach.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct aa_label *find_attach(const struct linux_binprm *bprm, struct aa_ns *ns, struct list_head *head, const char *name, const char **info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffffffff8149c120)
Location: security/apparmor/domain.c:381
Inline: False
Direct callers:
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
```
**Symbols:**

```
ffffffff8149c120-ffffffff8149c46a: find_attach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct aa_label *find_attach(const struct linux_binprm *bprm, struct aa_ns *ns, struct list_head *head, const char *name, const char **info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffffffff814f4ae0)
Location: security/apparmor/domain.c:386
Inline: False
Direct callers:
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
```
**Symbols:**

```
ffffffff814f4ae0-ffffffff814f4ffd: find_attach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct aa_label *find_attach(const struct linux_binprm *bprm, struct aa_ns *ns, struct list_head *head, const char *name, const char **info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffffffff81511ee0)
Location: security/apparmor/domain.c:386
Inline: False
Direct callers:
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
```
**Symbols:**

```
ffffffff81511ee0-ffffffff81512411: find_attach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct aa_label *find_attach(const struct linux_binprm *bprm, struct aa_ns *ns, struct list_head *head, const char *name, const char **info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffffffff81518820)
Location: security/apparmor/domain.c:388
Inline: False
Direct callers:
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
```
**Symbols:**

```
ffffffff81518820-ffffffff81518d3e: find_attach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct aa_label *find_attach(const struct linux_binprm *bprm, struct aa_ns *ns, struct list_head *head, const char *name, const char **info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffffffff81576830)
Location: security/apparmor/domain.c:388
Inline: False
Direct callers:
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
```
**Symbols:**

```
ffffffff81576830-ffffffff81576d4e: find_attach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct aa_label *find_attach(const struct linux_binprm *bprm, struct aa_ns *ns, struct list_head *head, const char *name, const char **info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffffffff816146a0)
Location: security/apparmor/domain.c:378
Inline: False
Direct callers:
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
```
**Symbols:**

```
ffffffff816146a0-ffffffff81614c6d: find_attach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct aa_label *find_attach(const struct linux_binprm *bprm, struct aa_ns *ns, struct list_head *head, const char *name, const char **info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffffffff816c73c0)
Location: security/apparmor/domain.c:384
Inline: False
Direct callers:
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
```
**Symbols:**

```
ffffffff816c73c0-ffffffff816c7994: find_attach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct aa_label *find_attach(const struct linux_binprm *bprm, struct aa_ns *ns, struct list_head *head, const char *name, const char **info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffffffff816ff9a0)
Location: security/apparmor/domain.c:384
Inline: False
Direct callers:
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
```
**Symbols:**

```
ffffffff816ff9a0-ffffffff816fff67: find_attach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct aa_label *find_attach(const struct linux_binprm *bprm, struct aa_ns *ns, struct list_head *head, const char *name, const char **info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffffffff8173cf60)
Location: security/apparmor/domain.c:387
Inline: False
Direct callers:
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
```
**Symbols:**

```
ffffffff8173cf60-ffffffff8173d558: find_attach (STB_LOCAL)
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
struct aa_label *find_attach(const struct linux_binprm *bprm, struct aa_ns *ns, struct list_head *head, const char *name, const char **info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffff800010591c50)
Location: security/apparmor/domain.c:381
Inline: False
Direct callers:
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
```
**Symbols:**

```
ffff800010591c50-ffff800010591ef4: find_attach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct aa_label *find_attach(const struct linux_binprm *bprm, struct aa_ns *ns, struct list_head *head, const char *name, const char **info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (c0742858)
Location: security/apparmor/domain.c:381
Inline: False
Direct callers:
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
```
**Symbols:**

```
c0742858-c0742b18: find_attach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct aa_label *find_attach(const struct linux_binprm *bprm, struct aa_ns *ns, struct list_head *head, const char *name, const char **info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (c000000000706800)
Location: security/apparmor/domain.c:381
Inline: False
Direct callers:
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
```
**Symbols:**

```
c000000000706800-c000000000706d9c: find_attach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct aa_label *find_attach(const struct linux_binprm *bprm, struct aa_ns *ns, struct list_head *head, const char *name, const char **info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffffffe0003dfde2)
Location: security/apparmor/domain.c:381
Inline: False
Direct callers:
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
```
**Symbols:**

```
ffffffe0003dfde2-ffffffe0003e0038: find_attach (STB_LOCAL)
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
struct aa_label *find_attach(const struct linux_binprm *bprm, struct aa_ns *ns, struct list_head *head, const char *name, const char **info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffffffff81494700)
Location: security/apparmor/domain.c:381
Inline: False
Direct callers:
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
```
**Symbols:**

```
ffffffff81494700-ffffffff81494a4a: find_attach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct aa_label *find_attach(const struct linux_binprm *bprm, struct aa_ns *ns, struct list_head *head, const char *name, const char **info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffffffff81485120)
Location: security/apparmor/domain.c:381
Inline: False
Direct callers:
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
```
**Symbols:**

```
ffffffff81485120-ffffffff8148546a: find_attach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct aa_label *find_attach(const struct linux_binprm *bprm, struct aa_ns *ns, struct list_head *head, const char *name, const char **info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffffffff814907a0)
Location: security/apparmor/domain.c:381
Inline: False
Direct callers:
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
```
**Symbols:**

```
ffffffff814907a0-ffffffff81490aea: find_attach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct aa_label *find_attach(const struct linux_binprm *bprm, struct aa_ns *ns, struct list_head *head, const char *name, const char **info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffffffff814a86c0)
Location: security/apparmor/domain.c:381
Inline: False
Direct callers:
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
```
**Symbols:**

```
ffffffff814a86c0-ffffffff814a8a12: find_attach (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
