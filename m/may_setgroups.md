# Function: <code>may_setgroups</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
bool may_setgroups();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffff810a46f0)
Location: kernel/groups.c:214
Inline: False
Direct callers:
  - kernel/groups.c:SyS_setgroups
  - kernel/uid16.c:SyS_setgroups16
```
**Symbols:**

```
ffffffff810a46f0-ffffffff810a472d: may_setgroups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool may_setgroups();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffff810a7df0)
Location: kernel/groups.c:214
Inline: False
Direct callers:
  - kernel/groups.c:SyS_setgroups
  - kernel/uid16.c:SyS_setgroups16
```
**Symbols:**

```
ffffffff810a7df0-ffffffff810a7e33: may_setgroups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool may_setgroups();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffff810addf0)
Location: kernel/groups.c:189
Inline: False
Direct callers:
  - kernel/groups.c:SyS_setgroups
  - kernel/uid16.c:SyS_setgroups16
```
**Symbols:**

```
ffffffff810addf0-ffffffff810ade33: may_setgroups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool may_setgroups();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffff810aa920)
Location: kernel/groups.c:176
Inline: False
Direct callers:
  - kernel/groups.c:SyS_setgroups
  - kernel/uid16.c:SyS_setgroups16
```
**Symbols:**

```
ffffffff810aa920-ffffffff810aa963: may_setgroups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool may_setgroups();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffff810b1600)
Location: kernel/groups.c:177
Inline: False
Direct callers:
  - kernel/groups.c:SyS_setgroups
  - kernel/uid16.c:SyS_setgroups16
```
**Symbols:**

```
ffffffff810b1600-ffffffff810b1643: may_setgroups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool may_setgroups();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffff810b8560)
Location: kernel/groups.c:177
Inline: False
Direct callers:
  - kernel/groups.c:__ia32_sys_setgroups
  - kernel/groups.c:__x64_sys_setgroups
  - kernel/uid16.c:__ia32_sys_setgroups16
  - kernel/uid16.c:__x64_sys_setgroups16
```
**Symbols:**

```
ffffffff810b8560-ffffffff810b85a8: may_setgroups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool may_setgroups();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffff810c1590)
Location: kernel/groups.c:177
Inline: False
Direct callers:
  - kernel/groups.c:__ia32_sys_setgroups
  - kernel/groups.c:__x64_sys_setgroups
  - kernel/uid16.c:__ia32_sys_setgroups16
  - kernel/uid16.c:__x64_sys_setgroups16
```
**Symbols:**

```
ffffffff810c1590-ffffffff810c15d0: may_setgroups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool may_setgroups();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffff810c7670)
Location: kernel/groups.c:177
Inline: False
Direct callers:
  - kernel/groups.c:__ia32_sys_setgroups
  - kernel/groups.c:__x64_sys_setgroups
  - kernel/uid16.c:__ia32_sys_setgroups16
  - kernel/uid16.c:__x64_sys_setgroups16
```
**Symbols:**

```
ffffffff810c7670-ffffffff810c76b3: may_setgroups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool may_setgroups();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffff810d0740)
Location: kernel/groups.c:177
Inline: False
Direct callers:
  - kernel/groups.c:__ia32_sys_setgroups
  - kernel/groups.c:__x64_sys_setgroups
  - kernel/uid16.c:__ia32_sys_setgroups16
  - kernel/uid16.c:__x64_sys_setgroups16
```
**Symbols:**

```
ffffffff810d0740-ffffffff810d0783: may_setgroups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool may_setgroups();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffff810da660)
Location: kernel/groups.c:177
Inline: True
Inline callers:
  - kernel/groups.c:__do_sys_setgroups
Direct callers:
  - kernel/uid16.c:__ia32_sys_setgroups16
  - kernel/uid16.c:__x64_sys_setgroups16
```
**Symbols:**

```
ffffffff810da860-ffffffff810da8a7: may_setgroups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool may_setgroups();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffff810d5dc0)
Location: kernel/groups.c:177
Inline: True
Inline callers:
  - kernel/groups.c:__do_sys_setgroups
Direct callers:
  - kernel/uid16.c:__ia32_sys_setgroups16
  - kernel/uid16.c:__x64_sys_setgroups16
```
**Symbols:**

```
ffffffff810d5fc0-ffffffff810d6007: may_setgroups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool may_setgroups();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffff810d7a8b)
Location: kernel/groups.c:172
Inline: True
Inline callers:
  - kernel/groups.c:__do_sys_setgroups
Direct callers:
  - kernel/uid16.c:__ia32_sys_setgroups16
  - kernel/uid16.c:__x64_sys_setgroups16
```
**Symbols:**

```
ffffffff810d7cb0-ffffffff810d7cf7: may_setgroups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool may_setgroups();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffff810eb33b)
Location: kernel/groups.c:172
Inline: True
Inline callers:
  - kernel/groups.c:__do_sys_setgroups
Direct callers:
  - kernel/uid16.c:__ia32_sys_setgroups16
  - kernel/uid16.c:__x64_sys_setgroups16
```
**Symbols:**

```
ffffffff810eb560-ffffffff810eb5a7: may_setgroups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
bool may_setgroups();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffff8110625b)
Location: kernel/groups.c:172
Inline: True
Inline callers:
  - kernel/groups.c:__do_sys_setgroups
Direct callers:
  - kernel/uid16.c:__ia32_sys_setgroups16
  - kernel/uid16.c:__x64_sys_setgroups16
```
**Symbols:**

```
ffffffff811064b0-ffffffff81106506: may_setgroups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
bool may_setgroups();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffff8112beab)
Location: kernel/groups.c:185
Inline: True
Inline callers:
  - kernel/groups.c:__do_sys_setgroups
Direct callers:
  - kernel/uid16.c:__ia32_sys_setgroups16
  - kernel/uid16.c:__x64_sys_setgroups16
```
**Symbols:**

```
ffffffff8112c160-ffffffff8112c1b6: may_setgroups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
bool may_setgroups();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffff81138d0b)
Location: kernel/groups.c:185
Inline: True
Inline callers:
  - kernel/groups.c:__do_sys_setgroups
Direct callers:
  - kernel/uid16.c:__ia32_sys_setgroups16
  - kernel/uid16.c:__x64_sys_setgroups16
```
**Symbols:**

```
ffffffff81138fc0-ffffffff81139016: may_setgroups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
bool may_setgroups();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffff81143a4b)
Location: kernel/groups.c:185
Inline: True
Inline callers:
  - kernel/groups.c:__do_sys_setgroups
Direct callers:
  - kernel/uid16.c:__do_sys_setgroups16
```
**Symbols:**

```
ffffffff81143d50-ffffffff81143da6: may_setgroups (STB_GLOBAL)
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
bool may_setgroups();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffff800010131268)
Location: kernel/groups.c:177
Inline: False
Direct callers:
  - kernel/groups.c:__arm64_sys_setgroups
  - kernel/uid16.c:__arm64_sys_setgroups16
```
**Symbols:**

```
ffff800010131268-ffff8000101312c0: may_setgroups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool may_setgroups();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/groups.c (c0380658)
Location: kernel/groups.c:177
Inline: False
Direct callers:
  - kernel/groups.c:__se_sys_setgroups
  - kernel/uid16.c:__se_sys_setgroups16
```
**Symbols:**

```
c0380658-c03806a4: may_setgroups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool may_setgroups();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/groups.c (c00000000017a710)
Location: kernel/groups.c:177
Inline: False
Direct callers:
  - kernel/groups.c:__se_sys_setgroups
```
**Symbols:**

```
c00000000017a710-c00000000017a790: may_setgroups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool may_setgroups();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffe0000e41e4)
Location: kernel/groups.c:177
Inline: False
Direct callers:
  - kernel/groups.c:__se_sys_setgroups
```
**Symbols:**

```
ffffffe0000e41e4-ffffffe0000e422a: may_setgroups (STB_GLOBAL)
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
bool may_setgroups();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffff810caac0)
Location: kernel/groups.c:177
Inline: False
Direct callers:
  - kernel/groups.c:__ia32_sys_setgroups
  - kernel/groups.c:__x64_sys_setgroups
  - kernel/uid16.c:__ia32_sys_setgroups16
  - kernel/uid16.c:__x64_sys_setgroups16
```
**Symbols:**

```
ffffffff810caac0-ffffffff810cab03: may_setgroups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool may_setgroups();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffff810b92d0)
Location: kernel/groups.c:177
Inline: False
Direct callers:
  - kernel/groups.c:__ia32_sys_setgroups
  - kernel/groups.c:__x64_sys_setgroups
  - kernel/uid16.c:__ia32_sys_setgroups16
  - kernel/uid16.c:__x64_sys_setgroups16
```
**Symbols:**

```
ffffffff810b92d0-ffffffff810b9313: may_setgroups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool may_setgroups();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffff810c9ff0)
Location: kernel/groups.c:177
Inline: False
Direct callers:
  - kernel/groups.c:__ia32_sys_setgroups
  - kernel/groups.c:__x64_sys_setgroups
  - kernel/uid16.c:__ia32_sys_setgroups16
  - kernel/uid16.c:__x64_sys_setgroups16
```
**Symbols:**

```
ffffffff810c9ff0-ffffffff810ca033: may_setgroups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool may_setgroups();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffff810d2540)
Location: kernel/groups.c:177
Inline: False
Direct callers:
  - kernel/groups.c:__ia32_sys_setgroups
  - kernel/groups.c:__x64_sys_setgroups
  - kernel/uid16.c:__ia32_sys_setgroups16
  - kernel/uid16.c:__x64_sys_setgroups16
```
**Symbols:**

```
ffffffff810d2540-ffffffff810d2583: may_setgroups (STB_GLOBAL)
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
