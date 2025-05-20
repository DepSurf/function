# Function: <code>current_is_single_threaded</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
bool current_is_single_threaded();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/is_single_threaded.c (ffffffff813eb420)
Location: lib/is_single_threaded.c:18
Inline: False
Direct callers:
  - kernel/fork.c:SyS_unshare
  - security/selinux/hooks.c:selinux_setprocattr
```
**Symbols:**

```
ffffffff813eb420-ffffffff813eb4d2: current_is_single_threaded (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool current_is_single_threaded();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/is_single_threaded.c (ffffffff81431770)
Location: lib/is_single_threaded.c:18
Inline: False
Direct callers:
  - kernel/fork.c:SyS_unshare
  - security/selinux/hooks.c:selinux_setprocattr
```
**Symbols:**

```
ffffffff81431770-ffffffff81431822: current_is_single_threaded (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool current_is_single_threaded();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/is_single_threaded.c (ffffffff8144d9e0)
Location: lib/is_single_threaded.c:18
Inline: False
Direct callers:
  - kernel/fork.c:SyS_unshare
  - security/selinux/hooks.c:selinux_setprocattr
```
**Symbols:**

```
ffffffff8144d9e0-ffffffff8144da92: current_is_single_threaded (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool current_is_single_threaded();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/is_single_threaded.c (ffffffff818ed690)
Location: lib/is_single_threaded.c:19
Inline: False
Direct callers:
  - kernel/fork.c:SyS_unshare
  - security/selinux/hooks.c:selinux_setprocattr
```
**Symbols:**

```
ffffffff818ed690-ffffffff818ed742: current_is_single_threaded (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool current_is_single_threaded();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/is_single_threaded.c (ffffffff81973810)
Location: lib/is_single_threaded.c:19
Inline: False
Direct callers:
  - kernel/fork.c:SyS_unshare
  - security/selinux/hooks.c:selinux_setprocattr
```
**Symbols:**

```
ffffffff81973810-ffffffff819738c2: current_is_single_threaded (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool current_is_single_threaded();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/is_single_threaded.c (ffffffff819cfcd0)
Location: lib/is_single_threaded.c:19
Inline: False
Direct callers:
  - kernel/fork.c:ksys_unshare
  - security/selinux/hooks.c:selinux_setprocattr
```
**Symbols:**

```
ffffffff819cfcd0-ffffffff819cfd94: current_is_single_threaded (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool current_is_single_threaded();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/is_single_threaded.c (ffffffff81a09230)
Location: lib/is_single_threaded.c:19
Inline: False
Direct callers:
  - kernel/fork.c:ksys_unshare
  - security/selinux/hooks.c:selinux_setprocattr
```
**Symbols:**

```
ffffffff81a09230-ffffffff81a092f4: current_is_single_threaded (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool current_is_single_threaded();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/is_single_threaded.c (ffffffff81a78bd0)
Location: lib/is_single_threaded.c:15
Inline: False
Direct callers:
  - kernel/fork.c:ksys_unshare
  - security/selinux/hooks.c:selinux_setprocattr
```
**Symbols:**

```
ffffffff81a78bd0-ffffffff81a78c99: current_is_single_threaded (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool current_is_single_threaded();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/is_single_threaded.c (ffffffff81aaff80)
Location: lib/is_single_threaded.c:15
Inline: False
Direct callers:
  - kernel/fork.c:ksys_unshare
  - security/selinux/hooks.c:selinux_setprocattr
```
**Symbols:**

```
ffffffff81aaff80-ffffffff81ab0049: current_is_single_threaded (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool current_is_single_threaded();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/is_single_threaded.c (ffffffff815e9f60)
Location: lib/is_single_threaded.c:15
Inline: False
Direct callers:
  - kernel/fork.c:ksys_unshare
  - kernel/time/namespace.c:timens_install
  - security/selinux/hooks.c:selinux_setprocattr
```
**Symbols:**

```
ffffffff815e9f60-ffffffff815ea029: current_is_single_threaded (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool current_is_single_threaded();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/is_single_threaded.c (ffffffff8160e880)
Location: lib/is_single_threaded.c:15
Inline: False
Direct callers:
  - kernel/fork.c:ksys_unshare
  - kernel/time/namespace.c:timens_install
  - security/selinux/hooks.c:selinux_setprocattr
```
**Symbols:**

```
ffffffff8160e880-ffffffff8160e963: current_is_single_threaded (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool current_is_single_threaded();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/is_single_threaded.c (ffffffff815f2010)
Location: lib/is_single_threaded.c:15
Inline: False
Direct callers:
  - kernel/fork.c:ksys_unshare
  - kernel/time/namespace.c:timens_install
  - security/selinux/hooks.c:selinux_setprocattr
```
**Symbols:**

```
ffffffff815f2010-ffffffff815f20f3: current_is_single_threaded (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool current_is_single_threaded();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/is_single_threaded.c (ffffffff8165f1c0)
Location: lib/is_single_threaded.c:15
Inline: False
Direct callers:
  - kernel/fork.c:ksys_unshare
  - kernel/time/namespace.c:timens_install
  - security/selinux/hooks.c:selinux_setprocattr
```
**Symbols:**

```
ffffffff8165f1c0-ffffffff8165f2a3: current_is_single_threaded (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool current_is_single_threaded();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/is_single_threaded.c (ffffffff81778a90)
Location: lib/is_single_threaded.c:15
Inline: False
Direct callers:
  - kernel/fork.c:ksys_unshare
  - kernel/time/namespace.c:timens_install
  - security/selinux/hooks.c:selinux_setprocattr
```
**Symbols:**

```
ffffffff81778a90-ffffffff81778b8c: current_is_single_threaded (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool current_is_single_threaded();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/is_single_threaded.c (ffffffff82021840)
Location: lib/is_single_threaded.c:15
Inline: False
Direct callers:
  - kernel/fork.c:ksys_unshare
  - kernel/time/namespace.c:timens_install
  - security/selinux/hooks.c:selinux_setprocattr
```
**Symbols:**

```
ffffffff82021840-ffffffff8202193c: current_is_single_threaded (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool current_is_single_threaded();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/is_single_threaded.c (ffffffff820a1880)
Location: lib/is_single_threaded.c:15
Inline: False
Direct callers:
  - kernel/fork.c:ksys_unshare
  - kernel/time/namespace.c:timens_install
  - security/selinux/hooks.c:selinux_setprocattr
```
**Symbols:**

```
ffffffff820a1880-ffffffff820a197f: current_is_single_threaded (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool current_is_single_threaded();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/is_single_threaded.c (ffffffff82179900)
Location: lib/is_single_threaded.c:15
Inline: False
Direct callers:
  - kernel/fork.c:ksys_unshare
  - kernel/time/namespace.c:timens_install
  - security/selinux/hooks.c:selinux_lsm_setattr
```
**Symbols:**

```
ffffffff82179900-ffffffff821799ff: current_is_single_threaded (STB_GLOBAL)
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
bool current_is_single_threaded();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/is_single_threaded.c (ffff800010d89930)
Location: lib/is_single_threaded.c:15
Inline: False
Direct callers:
  - kernel/fork.c:ksys_unshare
  - security/selinux/hooks.c:selinux_setprocattr
```
**Symbols:**

```
ffff800010d89930-ffff800010d899f0: current_is_single_threaded (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool current_is_single_threaded();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/is_single_threaded.c (c0e84440)
Location: lib/is_single_threaded.c:15
Inline: False
Direct callers:
  - kernel/fork.c:ksys_unshare
  - security/selinux/hooks.c:selinux_setprocattr
```
**Symbols:**

```
c0e84440-c0e84528: current_is_single_threaded (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool current_is_single_threaded();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/is_single_threaded.c (c000000000eca710)
Location: lib/is_single_threaded.c:15
Inline: False
Direct callers:
  - kernel/fork.c:ksys_unshare
  - security/selinux/hooks.c:selinux_setprocattr
```
**Symbols:**

```
c000000000eca710-c000000000eca7e8: current_is_single_threaded (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool current_is_single_threaded();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/is_single_threaded.c (ffffffe0008b3290)
Location: lib/is_single_threaded.c:15
Inline: False
Direct callers:
  - kernel/fork.c:ksys_unshare
  - security/selinux/hooks.c:selinux_setprocattr
```
**Symbols:**

```
ffffffe0008b3290-ffffffe0008b3330: current_is_single_threaded (STB_GLOBAL)
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
bool current_is_single_threaded();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/is_single_threaded.c (ffffffff81a4edd0)
Location: lib/is_single_threaded.c:15
Inline: False
Direct callers:
  - kernel/fork.c:ksys_unshare
  - security/selinux/hooks.c:selinux_setprocattr
```
**Symbols:**

```
ffffffff81a4edd0-ffffffff81a4ee99: current_is_single_threaded (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool current_is_single_threaded();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/is_single_threaded.c (ffffffff81a0bed0)
Location: lib/is_single_threaded.c:15
Inline: False
Direct callers:
  - kernel/fork.c:ksys_unshare
  - security/selinux/hooks.c:selinux_setprocattr
```
**Symbols:**

```
ffffffff81a0bed0-ffffffff81a0bf99: current_is_single_threaded (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool current_is_single_threaded();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/is_single_threaded.c (ffffffff81abb1c0)
Location: lib/is_single_threaded.c:15
Inline: False
Direct callers:
  - kernel/fork.c:ksys_unshare
  - security/selinux/hooks.c:selinux_setprocattr
```
**Symbols:**

```
ffffffff81abb1c0-ffffffff81abb289: current_is_single_threaded (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool current_is_single_threaded();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/is_single_threaded.c (ffffffff81ac7600)
Location: lib/is_single_threaded.c:15
Inline: False
Direct callers:
  - kernel/fork.c:ksys_unshare
  - security/selinux/hooks.c:selinux_setprocattr
```
**Symbols:**

```
ffffffff81ac7600-ffffffff81ac76f0: current_is_single_threaded (STB_GLOBAL)
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
