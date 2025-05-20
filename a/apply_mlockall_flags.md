# Function: <code>apply_mlockall_flags</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int apply_mlockall_flags(int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff811c3980)
Location: mm/mlock.c:685
Inline: False
Direct callers:
  - mm/mlock.c:SyS_mlockall
  - mm/mlock.c:SyS_mlockall
  - mm/mlock.c:sys_munlockall
```
**Symbols:**

```
ffffffff811c3980-ffffffff811c3ab2: apply_mlockall_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int apply_mlockall_flags(int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff811df770)
Location: mm/mlock.c:700
Inline: False
Direct callers:
  - mm/mlock.c:sys_munlockall
  - mm/mlock.c:SyS_mlockall
  - mm/mlock.c:SyS_mlockall
```
**Symbols:**

```
ffffffff811df770-ffffffff811df8c1: apply_mlockall_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int apply_mlockall_flags(int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff811ef6d0)
Location: mm/mlock.c:754
Inline: False
Direct callers:
  - mm/mlock.c:sys_munlockall
  - mm/mlock.c:SyS_mlockall
  - mm/mlock.c:SyS_mlockall
```
**Symbols:**

```
ffffffff811ef6d0-ffffffff811ef821: apply_mlockall_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int apply_mlockall_flags(int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff811fa5d0)
Location: mm/mlock.c:755
Inline: False
Direct callers:
  - mm/mlock.c:sys_munlockall
  - mm/mlock.c:SyS_mlockall
  - mm/mlock.c:SyS_mlockall
```
**Symbols:**

```
ffffffff811fa5d0-ffffffff811fa721: apply_mlockall_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int apply_mlockall_flags(int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff81212b00)
Location: mm/mlock.c:752
Inline: False
Direct callers:
  - mm/mlock.c:sys_munlockall
  - mm/mlock.c:SyS_mlockall
  - mm/mlock.c:SyS_mlockall
```
**Symbols:**

```
ffffffff81212b00-ffffffff81212c51: apply_mlockall_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int apply_mlockall_flags(int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff81233a20)
Location: mm/mlock.c:759
Inline: False
Direct callers:
  - mm/mlock.c:__x64_sys_munlockall
  - mm/mlock.c:__ia32_sys_mlockall
  - mm/mlock.c:__ia32_sys_mlockall
  - mm/mlock.c:__x64_sys_mlockall
  - mm/mlock.c:__x64_sys_mlockall
```
**Symbols:**

```
ffffffff81233a20-ffffffff81233b38: apply_mlockall_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int apply_mlockall_flags(int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff812471f0)
Location: mm/mlock.c:759
Inline: False
Direct callers:
  - mm/mlock.c:__x64_sys_munlockall
  - mm/mlock.c:__ia32_sys_mlockall
  - mm/mlock.c:__ia32_sys_mlockall
  - mm/mlock.c:__x64_sys_mlockall
  - mm/mlock.c:__x64_sys_mlockall
```
**Symbols:**

```
ffffffff812471f0-ffffffff81247308: apply_mlockall_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int apply_mlockall_flags(int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff81259400)
Location: mm/mlock.c:759
Inline: False
Direct callers:
  - mm/mlock.c:__x64_sys_munlockall
  - mm/mlock.c:__ia32_sys_mlockall
  - mm/mlock.c:__ia32_sys_mlockall
  - mm/mlock.c:__x64_sys_mlockall
  - mm/mlock.c:__x64_sys_mlockall
```
**Symbols:**

```
ffffffff81259400-ffffffff81259518: apply_mlockall_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int apply_mlockall_flags(int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff812678d0)
Location: mm/mlock.c:763
Inline: False
Direct callers:
  - mm/mlock.c:__x64_sys_munlockall
  - mm/mlock.c:__ia32_sys_mlockall
  - mm/mlock.c:__ia32_sys_mlockall
  - mm/mlock.c:__x64_sys_mlockall
  - mm/mlock.c:__x64_sys_mlockall
```
**Symbols:**

```
ffffffff812678d0-ffffffff812679e8: apply_mlockall_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int apply_mlockall_flags(int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff81297a00)
Location: mm/mlock.c:763
Inline: False
Direct callers:
  - mm/mlock.c:__do_sys_munlockall
  - mm/mlock.c:__do_sys_mlockall
  - mm/mlock.c:__do_sys_mlockall
```
**Symbols:**

```
ffffffff81297a00-ffffffff81297b17: apply_mlockall_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int apply_mlockall_flags(int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff812a2ac0)
Location: mm/mlock.c:739
Inline: False
Direct callers:
  - mm/mlock.c:__do_sys_munlockall
  - mm/mlock.c:__do_sys_mlockall
```
**Symbols:**

```
ffffffff812a2ac0-ffffffff812a2bd7: apply_mlockall_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int apply_mlockall_flags(int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff812a8340)
Location: mm/mlock.c:738
Inline: False
Direct callers:
  - mm/mlock.c:__do_sys_munlockall
  - mm/mlock.c:__do_sys_mlockall
```
**Symbols:**

```
ffffffff812a8340-ffffffff812a8457: apply_mlockall_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int apply_mlockall_flags(int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff812e9980)
Location: mm/mlock.c:739
Inline: False
Direct callers:
  - mm/mlock.c:__do_sys_munlockall
  - mm/mlock.c:__do_sys_mlockall
```
**Symbols:**

```
ffffffff812e9980-ffffffff812e9a97: apply_mlockall_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int apply_mlockall_flags(int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff81349b00)
Location: mm/mlock.c:660
Inline: False
Direct callers:
  - mm/mlock.c:__do_sys_munlockall
  - mm/mlock.c:__do_sys_mlockall
```
**Symbols:**

```
ffffffff81349b00-ffffffff81349c18: apply_mlockall_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int apply_mlockall_flags(int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff813c1e60)
Location: mm/mlock.c:659
Inline: False
Direct callers:
  - mm/mlock.c:__do_sys_munlockall
  - mm/mlock.c:__do_sys_mlockall
```
**Symbols:**

```
ffffffff813c1e60-ffffffff813c1f90: apply_mlockall_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int apply_mlockall_flags(int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff813f7510)
Location: mm/mlock.c:666
Inline: False
Direct callers:
  - mm/mlock.c:__do_sys_munlockall
  - mm/mlock.c:__do_sys_mlockall
```
**Symbols:**

```
ffffffff813f7510-ffffffff813f7639: apply_mlockall_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int apply_mlockall_flags(int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff81422990)
Location: mm/mlock.c:716
Inline: False
Direct callers:
  - mm/mlock.c:__do_sys_munlockall
  - mm/mlock.c:__do_sys_mlockall
```
**Symbols:**

```
ffffffff81422990-ffffffff81422ab8: apply_mlockall_flags (STB_LOCAL)
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
int apply_mlockall_flags(int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffff8000102fea30)
Location: mm/mlock.c:763
Inline: False
Direct callers:
  - mm/mlock.c:__arm64_sys_munlockall
  - mm/mlock.c:__arm64_sys_mlockall
  - mm/mlock.c:__arm64_sys_mlockall
```
**Symbols:**

```
ffff8000102fea30-ffff8000102feb4c: apply_mlockall_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int apply_mlockall_flags(int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (c051d940)
Location: mm/mlock.c:763
Inline: False
Direct callers:
  - mm/mlock.c:sys_munlockall
  - mm/mlock.c:__se_sys_mlockall
  - mm/mlock.c:__se_sys_mlockall
```
**Symbols:**

```
c051d940-c051da74: apply_mlockall_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int apply_mlockall_flags(int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (c0000000003ca5b0)
Location: mm/mlock.c:763
Inline: False
Direct callers:
  - mm/mlock.c:sys_munlockall
  - mm/mlock.c:__se_sys_mlockall
  - mm/mlock.c:__se_sys_mlockall
```
**Symbols:**

```
c0000000003ca5b0-c0000000003ca724: apply_mlockall_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int apply_mlockall_flags(int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffe00020cc72)
Location: mm/mlock.c:763
Inline: False
Direct callers:
  - mm/mlock.c:sys_munlockall
  - mm/mlock.c:__se_sys_mlockall
  - mm/mlock.c:__se_sys_mlockall
```
**Symbols:**

```
ffffffe00020cc72-ffffffe00020cd26: apply_mlockall_flags (STB_LOCAL)
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
int apply_mlockall_flags(int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff8125ff20)
Location: mm/mlock.c:763
Inline: False
Direct callers:
  - mm/mlock.c:__x64_sys_munlockall
  - mm/mlock.c:__ia32_sys_mlockall
  - mm/mlock.c:__ia32_sys_mlockall
  - mm/mlock.c:__x64_sys_mlockall
  - mm/mlock.c:__x64_sys_mlockall
```
**Symbols:**

```
ffffffff8125ff20-ffffffff81260038: apply_mlockall_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int apply_mlockall_flags(int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff81252340)
Location: mm/mlock.c:763
Inline: False
Direct callers:
  - mm/mlock.c:__x64_sys_munlockall
  - mm/mlock.c:__ia32_sys_mlockall
  - mm/mlock.c:__ia32_sys_mlockall
  - mm/mlock.c:__x64_sys_mlockall
  - mm/mlock.c:__x64_sys_mlockall
```
**Symbols:**

```
ffffffff81252340-ffffffff81252458: apply_mlockall_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int apply_mlockall_flags(int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff8125dcc0)
Location: mm/mlock.c:763
Inline: False
Direct callers:
  - mm/mlock.c:__x64_sys_munlockall
  - mm/mlock.c:__ia32_sys_mlockall
  - mm/mlock.c:__ia32_sys_mlockall
  - mm/mlock.c:__x64_sys_mlockall
  - mm/mlock.c:__x64_sys_mlockall
```
**Symbols:**

```
ffffffff8125dcc0-ffffffff8125ddd8: apply_mlockall_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int apply_mlockall_flags(int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff8126d6a0)
Location: mm/mlock.c:763
Inline: False
Direct callers:
  - mm/mlock.c:__x64_sys_munlockall
  - mm/mlock.c:__ia32_sys_mlockall
  - mm/mlock.c:__ia32_sys_mlockall
  - mm/mlock.c:__x64_sys_mlockall
  - mm/mlock.c:__x64_sys_mlockall
```
**Symbols:**

```
ffffffff8126d6a0-ffffffff8126d7b3: apply_mlockall_flags (STB_LOCAL)
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
