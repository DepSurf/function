# Function: <code>ns_capable_common</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
bool ns_capable_common(struct user_namespace *ns, int cap, bool audit);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff8108d220)
Location: kernel/capability.c:364
Inline: True
Direct callers:
  - kernel/capability.c:capable_wrt_inode_uidgid
  - kernel/capability.c:capable
  - kernel/capability.c:ns_capable_noaudit
```
**Symbols:**

```
ffffffff8108d220-ffffffff8108d298: ns_capable_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
bool ns_capable_common(struct user_namespace *ns, int cap, bool audit);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff810921d0)
Location: kernel/capability.c:365
Inline: True
Direct callers:
  - kernel/capability.c:capable_wrt_inode_uidgid
  - kernel/capability.c:capable
  - kernel/capability.c:ns_capable_noaudit
```
**Symbols:**

```
ffffffff810921d0-ffffffff81092248: ns_capable_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
bool ns_capable_common(struct user_namespace *ns, int cap, bool audit);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff8108f380)
Location: kernel/capability.c:365
Inline: True
Direct callers:
  - kernel/capability.c:capable_wrt_inode_uidgid
  - kernel/capability.c:capable
  - kernel/capability.c:ns_capable_noaudit
```
**Symbols:**

```
ffffffff8108f380-ffffffff8108f3f8: ns_capable_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
bool ns_capable_common(struct user_namespace *ns, int cap, bool audit);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff81096240)
Location: kernel/capability.c:366
Inline: True
Direct callers:
  - kernel/capability.c:capable_wrt_inode_uidgid
  - kernel/capability.c:capable
  - kernel/capability.c:ns_capable_noaudit
```
**Symbols:**

```
ffffffff81096240-ffffffff810962b8: ns_capable_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool ns_capable_common(struct user_namespace *ns, int cap, bool audit);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/capability.c (0)
Location: kernel/capability.c:366
Inline: True
Direct callers:
  - kernel/capability.c:capable_wrt_inode_uidgid
  - kernel/capability.c:capable
  - kernel/capability.c:ns_capable_noaudit
```
**Symbols:**

```
ffffffff81099740-ffffffff810997ae: ns_capable_common (STB_LOCAL)
ffffffff81099ccc-ffffffff81099cda: ns_capable_common.cold.1 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool ns_capable_common(struct user_namespace *ns, int cap, unsigned int opts);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/capability.c (ffffffff810a2051)
Location: kernel/capability.c:366
Inline: True
Direct callers:
  - kernel/capability.c:capable_wrt_inode_uidgid
  - kernel/capability.c:capable
  - kernel/capability.c:ns_capable_noaudit
```
**Symbols:**

```
ffffffff810a1ad0-ffffffff810a1b16: ns_capable_common (STB_LOCAL)
ffffffff810a2051-ffffffff810a205f: ns_capable_common.cold.1 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool ns_capable_common(struct user_namespace *ns, int cap, unsigned int opts);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/capability.c (ffffffff810a6a81)
Location: kernel/capability.c:364
Inline: True
Direct callers:
  - kernel/capability.c:capable_wrt_inode_uidgid
  - kernel/capability.c:capable
  - kernel/capability.c:ns_capable_setid
  - kernel/capability.c:ns_capable_noaudit
```
**Symbols:**

```
ffffffff810a6500-ffffffff810a654b: ns_capable_common (STB_LOCAL)
ffffffff810a6a81-ffffffff810a6a8f: ns_capable_common.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool ns_capable_common(struct user_namespace *ns, int cap, unsigned int opts);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/capability.c (ffffffff810ad061)
Location: kernel/capability.c:364
Inline: True
Direct callers:
  - kernel/capability.c:capable_wrt_inode_uidgid
  - kernel/capability.c:capable
  - kernel/capability.c:ns_capable_setid
  - kernel/capability.c:ns_capable_noaudit
```
**Symbols:**

```
ffffffff810acae0-ffffffff810acb2b: ns_capable_common (STB_LOCAL)
ffffffff810ad061-ffffffff810ad06f: ns_capable_common.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool ns_capable_common(struct user_namespace *ns, int cap, unsigned int opts);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/capability.c (ffffffff810b49d5)
Location: kernel/capability.c:364
Inline: True
Inline callers:
  - kernel/capability.c:capable
  - kernel/capability.c:capable
  - kernel/capability.c:ns_capable_setid
  - kernel/capability.c:ns_capable_setid
  - kernel/capability.c:ns_capable_noaudit
  - kernel/capability.c:ns_capable_noaudit
Direct callers:
  - kernel/capability.c:capable_wrt_inode_uidgid
```
**Symbols:**

```
ffffffff810b47d0-ffffffff810b481e: ns_capable_common (STB_LOCAL)
ffffffff810b4b11-ffffffff810b4b1f: ns_capable_common.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool ns_capable_common(struct user_namespace *ns, int cap, unsigned int opts);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/capability.c (ffffffff810afb75)
Location: kernel/capability.c:364
Inline: True
Inline callers:
  - kernel/capability.c:capable
  - kernel/capability.c:capable
  - kernel/capability.c:ns_capable_setid
  - kernel/capability.c:ns_capable_setid
  - kernel/capability.c:ns_capable_noaudit
  - kernel/capability.c:ns_capable_noaudit
Direct callers:
  - kernel/capability.c:capable_wrt_inode_uidgid
```
**Symbols:**

```
ffffffff810af9c0-ffffffff810afa0e: ns_capable_common (STB_LOCAL)
ffffffff81bdb9f4-ffffffff81bdba02: ns_capable_common.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff810b124a)
Location: kernel/capability.c:364
Inline: True
Inline callers:
  - kernel/capability.c:capable_wrt_inode_uidgid
  - kernel/capability.c:capable_wrt_inode_uidgid
  - kernel/capability.c:capable
  - kernel/capability.c:capable
  - kernel/capability.c:ns_capable_setid
  - kernel/capability.c:ns_capable_setid
  - kernel/capability.c:ns_capable_noaudit
  - kernel/capability.c:ns_capable_noaudit
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff810c330a)
Location: kernel/capability.c:364
Inline: True
Inline callers:
  - kernel/capability.c:capable_wrt_inode_uidgid
  - kernel/capability.c:capable_wrt_inode_uidgid
  - kernel/capability.c:capable
  - kernel/capability.c:capable
  - kernel/capability.c:ns_capable_setid
  - kernel/capability.c:ns_capable_setid
  - kernel/capability.c:ns_capable_noaudit
  - kernel/capability.c:ns_capable_noaudit
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff810da84a)
Location: kernel/capability.c:365
Inline: True
Inline callers:
  - kernel/capability.c:capable_wrt_inode_uidgid
  - kernel/capability.c:capable_wrt_inode_uidgid
  - kernel/capability.c:capable
  - kernel/capability.c:capable
  - kernel/capability.c:ns_capable_setid
  - kernel/capability.c:ns_capable_setid
  - kernel/capability.c:ns_capable_noaudit
  - kernel/capability.c:ns_capable_noaudit
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff810fa91a)
Location: kernel/capability.c:365
Inline: True
Inline callers:
  - kernel/capability.c:capable_wrt_inode_uidgid
  - kernel/capability.c:capable_wrt_inode_uidgid
  - kernel/capability.c:capable
  - kernel/capability.c:capable
  - kernel/capability.c:ns_capable_setid
  - kernel/capability.c:ns_capable_setid
  - kernel/capability.c:ns_capable_noaudit
  - kernel/capability.c:ns_capable_noaudit
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff8110695a)
Location: kernel/capability.c:351
Inline: True
Inline callers:
  - kernel/capability.c:capable_wrt_inode_uidgid
  - kernel/capability.c:capable_wrt_inode_uidgid
  - kernel/capability.c:capable
  - kernel/capability.c:capable
  - kernel/capability.c:ns_capable_setid
  - kernel/capability.c:ns_capable_setid
  - kernel/capability.c:ns_capable_noaudit
  - kernel/capability.c:ns_capable_noaudit
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff811102aa)
Location: kernel/capability.c:351
Inline: True
Inline callers:
  - kernel/capability.c:capable_wrt_inode_uidgid
  - kernel/capability.c:capable_wrt_inode_uidgid
  - kernel/capability.c:capable
  - kernel/capability.c:capable
  - kernel/capability.c:ns_capable_setid
  - kernel/capability.c:ns_capable_setid
  - kernel/capability.c:ns_capable_noaudit
  - kernel/capability.c:ns_capable_noaudit
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
bool ns_capable_common(struct user_namespace *ns, int cap, unsigned int opts);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffff800010105a30)
Location: kernel/capability.c:364
Inline: True
Direct callers:
  - kernel/capability.c:capable_wrt_inode_uidgid
  - kernel/capability.c:capable
  - kernel/capability.c:ns_capable_setid
  - kernel/capability.c:ns_capable_noaudit
```
**Symbols:**

```
ffff800010105a30-ffff800010105ab4: ns_capable_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
bool ns_capable_common(struct user_namespace *ns, int cap, unsigned int opts);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/capability.c (c0360e74)
Location: kernel/capability.c:364
Inline: True
Direct callers:
  - kernel/capability.c:capable_wrt_inode_uidgid
  - kernel/capability.c:capable
  - kernel/capability.c:ns_capable_setid
  - kernel/capability.c:ns_capable_noaudit
```
**Symbols:**

```
c0360e74-c0360ef0: ns_capable_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
bool ns_capable_common(struct user_namespace *ns, int cap, unsigned int opts);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/capability.c (c00000000014d1a0)
Location: kernel/capability.c:364
Inline: True
Direct callers:
  - kernel/capability.c:capable_wrt_inode_uidgid
  - kernel/capability.c:capable
  - kernel/capability.c:ns_capable_setid
  - kernel/capability.c:ns_capable_noaudit
```
**Symbols:**

```
c00000000014d1a0-c00000000014d230: ns_capable_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
bool ns_capable_common(struct user_namespace *ns, int cap, unsigned int opts);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffe0000cb02a)
Location: kernel/capability.c:364
Inline: True
Direct callers:
  - kernel/capability.c:capable_wrt_inode_uidgid
  - kernel/capability.c:capable
  - kernel/capability.c:ns_capable_setid
  - kernel/capability.c:ns_capable_noaudit
```
**Symbols:**

```
ffffffe0000cb02a-ffffffe0000cb098: ns_capable_common (STB_LOCAL)
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
bool ns_capable_common(struct user_namespace *ns, int cap, unsigned int opts);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/capability.c (ffffffff810a73d1)
Location: kernel/capability.c:364
Inline: True
Direct callers:
  - kernel/capability.c:capable_wrt_inode_uidgid
  - kernel/capability.c:capable
  - kernel/capability.c:ns_capable_setid
  - kernel/capability.c:ns_capable_noaudit
```
**Symbols:**

```
ffffffff810a6e50-ffffffff810a6e9b: ns_capable_common (STB_LOCAL)
ffffffff810a73d1-ffffffff810a73df: ns_capable_common.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool ns_capable_common(struct user_namespace *ns, int cap, unsigned int opts);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/capability.c (ffffffff81095db1)
Location: kernel/capability.c:364
Inline: True
Direct callers:
  - kernel/capability.c:capable_wrt_inode_uidgid
  - kernel/capability.c:capable
  - kernel/capability.c:ns_capable_setid
  - kernel/capability.c:ns_capable_noaudit
```
**Symbols:**

```
ffffffff81095830-ffffffff8109587b: ns_capable_common (STB_LOCAL)
ffffffff81095db1-ffffffff81095dbf: ns_capable_common.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool ns_capable_common(struct user_namespace *ns, int cap, unsigned int opts);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/capability.c (ffffffff810a6931)
Location: kernel/capability.c:364
Inline: True
Direct callers:
  - kernel/capability.c:capable_wrt_inode_uidgid
  - kernel/capability.c:capable
  - kernel/capability.c:ns_capable_setid
  - kernel/capability.c:ns_capable_noaudit
```
**Symbols:**

```
ffffffff810a63b0-ffffffff810a63fb: ns_capable_common (STB_LOCAL)
ffffffff810a6931-ffffffff810a693f: ns_capable_common.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool ns_capable_common(struct user_namespace *ns, int cap, unsigned int opts);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/capability.c (ffffffff810aea82)
Location: kernel/capability.c:364
Inline: True
Direct callers:
  - kernel/capability.c:capable_wrt_inode_uidgid
  - kernel/capability.c:capable
  - kernel/capability.c:ns_capable_setid
  - kernel/capability.c:ns_capable_noaudit
```
**Symbols:**

```
ffffffff810ae460-ffffffff810ae4ab: ns_capable_common (STB_LOCAL)
ffffffff810aea82-ffffffff810aea90: ns_capable_common.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int opts</code>
</li>
<li>
<b>Param removed. </b>
<code>bool audit</code>
</li>
</ul>
</details>
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
