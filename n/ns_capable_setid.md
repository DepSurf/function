# Function: <code>ns_capable_setid</code>

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
<summary>In <code>5.3</code>: ✅</summary>

```c
bool ns_capable_setid(struct user_namespace *ns, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff810a65b0)
Location: kernel/capability.c:431
Inline: False
Direct callers:
  - kernel/sys.c:__sys_setfsuid
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setuid
  - kernel/sys.c:__sys_setreuid
  - kernel/sys.c:__sys_setreuid
```
**Symbols:**

```
ffffffff810a65b0-ffffffff810a65c5: ns_capable_setid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool ns_capable_setid(struct user_namespace *ns, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff810acb90)
Location: kernel/capability.c:431
Inline: False
Direct callers:
  - kernel/sys.c:__sys_setfsuid
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setuid
  - kernel/sys.c:__sys_setreuid
  - kernel/sys.c:__sys_setreuid
```
**Symbols:**

```
ffffffff810acb90-ffffffff810acba5: ns_capable_setid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
bool ns_capable_setid(struct user_namespace *ns, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/capability.c (0)
Location: kernel/capability.c:431
Inline: False
Direct callers:
  - kernel/sys.c:__sys_setfsuid
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setuid
  - kernel/sys.c:__sys_setreuid
  - kernel/sys.c:__sys_setreuid
```
**Symbols:**

```
ffffffff810b4b1f-ffffffff810b4b2d: ns_capable_setid.cold (STB_LOCAL)
ffffffff810b48c0-ffffffff810b4911: ns_capable_setid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
bool ns_capable_setid(struct user_namespace *ns, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/capability.c (0)
Location: kernel/capability.c:431
Inline: False
Direct callers:
  - kernel/sys.c:__sys_setfsgid
  - kernel/sys.c:__sys_setfsuid
  - kernel/sys.c:__sys_setresgid
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setuid
  - kernel/sys.c:__sys_setreuid
  - kernel/sys.c:__sys_setreuid
  - kernel/sys.c:__sys_setgid
  - kernel/sys.c:__sys_setregid
  - kernel/sys.c:__sys_setregid
  - kernel/groups.c:__do_sys_setgroups
```
**Symbols:**

```
ffffffff81bdba02-ffffffff81bdba10: ns_capable_setid.cold (STB_LOCAL)
ffffffff810afac0-ffffffff810afb11: ns_capable_setid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
bool ns_capable_setid(struct user_namespace *ns, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/capability.c (0)
Location: kernel/capability.c:431
Inline: False
Direct callers:
  - kernel/sys.c:__sys_setfsgid
  - kernel/sys.c:__sys_setfsuid
  - kernel/sys.c:__sys_setresgid
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setuid
  - kernel/sys.c:__sys_setreuid
  - kernel/sys.c:__sys_setreuid
  - kernel/sys.c:__sys_setgid
  - kernel/sys.c:__sys_setregid
  - kernel/sys.c:__sys_setregid
  - kernel/groups.c:__do_sys_setgroups
```
**Symbols:**

```
ffffffff81bcdab2-ffffffff81bcdac0: ns_capable_setid.cold (STB_LOCAL)
ffffffff810b1010-ffffffff810b1061: ns_capable_setid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
bool ns_capable_setid(struct user_namespace *ns, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/capability.c (0)
Location: kernel/capability.c:431
Inline: False
Direct callers:
  - kernel/sys.c:__sys_setfsgid
  - kernel/sys.c:__sys_setfsuid
  - kernel/sys.c:__sys_setresgid
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setuid
  - kernel/sys.c:__sys_setreuid
  - kernel/sys.c:__sys_setreuid
  - kernel/sys.c:__sys_setgid
  - kernel/sys.c:__sys_setregid
  - kernel/sys.c:__sys_setregid
  - kernel/groups.c:__do_sys_setgroups
```
**Symbols:**

```
ffffffff81ca4597-ffffffff81ca45a5: ns_capable_setid.cold (STB_LOCAL)
ffffffff810c30e0-ffffffff810c3131: ns_capable_setid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool ns_capable_setid(struct user_namespace *ns, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/capability.c (0)
Location: kernel/capability.c:432
Inline: False
Direct callers:
  - kernel/sys.c:__sys_setfsgid
  - kernel/sys.c:__sys_setfsuid
  - kernel/sys.c:__sys_setresgid
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setuid
  - kernel/sys.c:__sys_setreuid
  - kernel/sys.c:__sys_setreuid
  - kernel/sys.c:__sys_setgid
  - kernel/sys.c:__sys_setregid
  - kernel/sys.c:__sys_setregid
  - kernel/groups.c:__do_sys_setgroups
```
**Symbols:**

```
ffffffff81e53e38-ffffffff81e53e46: ns_capable_setid.cold (STB_LOCAL)
ffffffff810da630-ffffffff810da688: ns_capable_setid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool ns_capable_setid(struct user_namespace *ns, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff810fa6b0)
Location: kernel/capability.c:432
Inline: False
Direct callers:
  - kernel/sys.c:__sys_setfsgid
  - kernel/sys.c:__sys_setfsuid
  - kernel/sys.c:__sys_setresgid
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setuid
  - kernel/sys.c:__sys_setreuid
  - kernel/sys.c:__sys_setreuid
  - kernel/sys.c:__sys_setgid
  - kernel/sys.c:__sys_setregid
  - kernel/sys.c:__sys_setregid
  - kernel/groups.c:__do_sys_setgroups
```
**Symbols:**

```
ffffffff810fa6b0-ffffffff810fa712: ns_capable_setid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool ns_capable_setid(struct user_namespace *ns, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff81106660)
Location: kernel/capability.c:418
Inline: False
Direct callers:
  - kernel/sys.c:__sys_setfsgid
  - kernel/sys.c:__sys_setfsuid
  - kernel/sys.c:__sys_setresgid
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setuid
  - kernel/sys.c:__sys_setreuid
  - kernel/sys.c:__sys_setreuid
  - kernel/sys.c:__sys_setgid
  - kernel/sys.c:__sys_setregid
  - kernel/sys.c:__sys_setregid
  - kernel/groups.c:__do_sys_setgroups
```
**Symbols:**

```
ffffffff81106660-ffffffff811066c2: ns_capable_setid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool ns_capable_setid(struct user_namespace *ns, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff8110ffb0)
Location: kernel/capability.c:418
Inline: False
Direct callers:
  - kernel/sys.c:__sys_setfsgid
  - kernel/sys.c:__sys_setfsuid
  - kernel/sys.c:__sys_setresgid
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setuid
  - kernel/sys.c:__sys_setreuid
  - kernel/sys.c:__sys_setreuid
  - kernel/sys.c:__sys_setgid
  - kernel/sys.c:__sys_setregid
  - kernel/sys.c:__sys_setregid
  - kernel/groups.c:__do_sys_setgroups
```
**Symbols:**

```
ffffffff8110ffb0-ffffffff81110012: ns_capable_setid (STB_GLOBAL)
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
bool ns_capable_setid(struct user_namespace *ns, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffff800010105b60)
Location: kernel/capability.c:431
Inline: False
Direct callers:
  - kernel/sys.c:__sys_setfsuid
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setuid
  - kernel/sys.c:__sys_setreuid
  - kernel/sys.c:__sys_setreuid
```
**Symbols:**

```
ffff800010105b60-ffff800010105b98: ns_capable_setid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool ns_capable_setid(struct user_namespace *ns, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/capability.c (c0360f5c)
Location: kernel/capability.c:431
Inline: False
Direct callers:
  - kernel/sys.c:__sys_setfsuid
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setuid
  - kernel/sys.c:__sys_setreuid
  - kernel/sys.c:__sys_setreuid
```
**Symbols:**

```
c0360f5c-c0360f7c: ns_capable_setid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool ns_capable_setid(struct user_namespace *ns, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/capability.c (c00000000014d2a0)
Location: kernel/capability.c:431
Inline: False
Direct callers:
  - kernel/sys.c:__sys_setfsuid
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setuid
  - kernel/sys.c:__sys_setreuid
  - kernel/sys.c:__sys_setreuid
```
**Symbols:**

```
c00000000014d2a0-c00000000014d2b8: ns_capable_setid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool ns_capable_setid(struct user_namespace *ns, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffe0000cb134)
Location: kernel/capability.c:431
Inline: False
Direct callers:
  - kernel/sys.c:__sys_setfsuid
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setuid
  - kernel/sys.c:__sys_setreuid
  - kernel/sys.c:__sys_setreuid
```
**Symbols:**

```
ffffffe0000cb134-ffffffe0000cb168: ns_capable_setid (STB_GLOBAL)
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
bool ns_capable_setid(struct user_namespace *ns, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff810a6f00)
Location: kernel/capability.c:431
Inline: False
Direct callers:
  - kernel/sys.c:__sys_setfsuid
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setuid
  - kernel/sys.c:__sys_setreuid
  - kernel/sys.c:__sys_setreuid
```
**Symbols:**

```
ffffffff810a6f00-ffffffff810a6f15: ns_capable_setid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool ns_capable_setid(struct user_namespace *ns, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff810958e0)
Location: kernel/capability.c:431
Inline: False
Direct callers:
  - kernel/sys.c:__sys_setfsuid
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setuid
  - kernel/sys.c:__sys_setreuid
  - kernel/sys.c:__sys_setreuid
```
**Symbols:**

```
ffffffff810958e0-ffffffff810958f5: ns_capable_setid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool ns_capable_setid(struct user_namespace *ns, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff810a6460)
Location: kernel/capability.c:431
Inline: False
Direct callers:
  - kernel/sys.c:__sys_setfsuid
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setuid
  - kernel/sys.c:__sys_setreuid
  - kernel/sys.c:__sys_setreuid
```
**Symbols:**

```
ffffffff810a6460-ffffffff810a6475: ns_capable_setid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool ns_capable_setid(struct user_namespace *ns, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff810ae510)
Location: kernel/capability.c:431
Inline: False
Direct callers:
  - kernel/sys.c:__sys_setfsuid
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setuid
  - kernel/sys.c:__sys_setreuid
  - kernel/sys.c:__sys_setreuid
```
**Symbols:**

```
ffffffff810ae510-ffffffff810ae525: ns_capable_setid (STB_GLOBAL)
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
