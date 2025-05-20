# Function: <code>do_mlock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int do_mlock(long unsigned int start, size_t len, vm_flags_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff811c3820)
Location: mm/mlock.c:607
Inline: False
Direct callers:
  - mm/mlock.c:SyS_mlock
  - mm/mlock.c:SyS_mlock2
```
**Symbols:**

```
ffffffff811c3820-ffffffff811c3976: do_mlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int do_mlock(long unsigned int start, size_t len, vm_flags_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff811df600)
Location: mm/mlock.c:620
Inline: False
Direct callers:
  - mm/mlock.c:SyS_mlock2
  - mm/mlock.c:SyS_mlock
```
**Symbols:**

```
ffffffff811df600-ffffffff811df76a: do_mlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int do_mlock(long unsigned int start, size_t len, vm_flags_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff811ef4a0)
Location: mm/mlock.c:664
Inline: False
Direct callers:
  - mm/mlock.c:SyS_mlock2
  - mm/mlock.c:SyS_mlock
```
**Symbols:**

```
ffffffff811ef4a0-ffffffff811ef6c1: do_mlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int do_mlock(long unsigned int start, size_t len, vm_flags_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff811fa3a0)
Location: mm/mlock.c:665
Inline: False
Direct callers:
  - mm/mlock.c:SyS_mlock2
  - mm/mlock.c:SyS_mlock
```
**Symbols:**

```
ffffffff811fa3a0-ffffffff811fa5c7: do_mlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int do_mlock(long unsigned int start, size_t len, vm_flags_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff812128d0)
Location: mm/mlock.c:664
Inline: False
Direct callers:
  - mm/mlock.c:SyS_mlock2
  - mm/mlock.c:SyS_mlock
```
**Symbols:**

```
ffffffff812128d0-ffffffff81212af2: do_mlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int do_mlock(long unsigned int start, size_t len, vm_flags_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff81233600)
Location: mm/mlock.c:671
Inline: False
Direct callers:
  - mm/mlock.c:__ia32_sys_mlock2
  - mm/mlock.c:__x64_sys_mlock2
  - mm/mlock.c:__ia32_sys_mlock
  - mm/mlock.c:__x64_sys_mlock
```
**Symbols:**

```
ffffffff81233600-ffffffff8123381f: do_mlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int do_mlock(long unsigned int start, size_t len, vm_flags_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff81246dd0)
Location: mm/mlock.c:671
Inline: False
Direct callers:
  - mm/mlock.c:__ia32_sys_mlock2
  - mm/mlock.c:__x64_sys_mlock2
  - mm/mlock.c:__ia32_sys_mlock
  - mm/mlock.c:__x64_sys_mlock
```
**Symbols:**

```
ffffffff81246dd0-ffffffff81246fef: do_mlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int do_mlock(long unsigned int start, size_t len, vm_flags_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff81258fe0)
Location: mm/mlock.c:671
Inline: False
Direct callers:
  - mm/mlock.c:__ia32_sys_mlock2
  - mm/mlock.c:__x64_sys_mlock2
  - mm/mlock.c:__ia32_sys_mlock
  - mm/mlock.c:__x64_sys_mlock
```
**Symbols:**

```
ffffffff81258fe0-ffffffff812591f5: do_mlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int do_mlock(long unsigned int start, size_t len, vm_flags_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff812674b0)
Location: mm/mlock.c:671
Inline: False
Direct callers:
  - mm/mlock.c:__ia32_sys_mlock2
  - mm/mlock.c:__x64_sys_mlock2
  - mm/mlock.c:__ia32_sys_mlock
  - mm/mlock.c:__x64_sys_mlock
```
**Symbols:**

```
ffffffff812674b0-ffffffff812676c5: do_mlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int do_mlock(long unsigned int start, size_t len, vm_flags_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff812975e0)
Location: mm/mlock.c:671
Inline: False
Direct callers:
  - mm/mlock.c:__ia32_sys_mlock2
  - mm/mlock.c:__x64_sys_mlock2
  - mm/mlock.c:__ia32_sys_mlock
  - mm/mlock.c:__x64_sys_mlock
```
**Symbols:**

```
ffffffff812975e0-ffffffff812977f9: do_mlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int do_mlock(long unsigned int start, size_t len, vm_flags_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff812a25a0)
Location: mm/mlock.c:647
Inline: False
Direct callers:
  - mm/mlock.c:__ia32_sys_mlock2
  - mm/mlock.c:__x64_sys_mlock2
  - mm/mlock.c:__ia32_sys_mlock
  - mm/mlock.c:__x64_sys_mlock
```
**Symbols:**

```
ffffffff812a25a0-ffffffff812a281c: do_mlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int do_mlock(long unsigned int start, size_t len, vm_flags_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff812a7e40)
Location: mm/mlock.c:646
Inline: False
Direct callers:
  - mm/mlock.c:__ia32_sys_mlock2
  - mm/mlock.c:__x64_sys_mlock2
  - mm/mlock.c:__ia32_sys_mlock
  - mm/mlock.c:__x64_sys_mlock
```
**Symbols:**

```
ffffffff812a7e40-ffffffff812a8099: do_mlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int do_mlock(long unsigned int start, size_t len, vm_flags_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff812e9490)
Location: mm/mlock.c:647
Inline: False
Direct callers:
  - mm/mlock.c:__ia32_sys_mlock2
  - mm/mlock.c:__x64_sys_mlock2
  - mm/mlock.c:__ia32_sys_mlock
  - mm/mlock.c:__x64_sys_mlock
```
**Symbols:**

```
ffffffff812e9490-ffffffff812e96e9: do_mlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int do_mlock(long unsigned int start, size_t len, vm_flags_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff8134a0e0)
Location: mm/mlock.c:568
Inline: False
Direct callers:
  - mm/mlock.c:__ia32_sys_mlock2
  - mm/mlock.c:__x64_sys_mlock2
  - mm/mlock.c:__ia32_sys_mlock
  - mm/mlock.c:__x64_sys_mlock
```
**Symbols:**

```
ffffffff8134a0e0-ffffffff8134a33b: do_mlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int do_mlock(long unsigned int start, size_t len, vm_flags_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff813c2c20)
Location: mm/mlock.c:567
Inline: False
Direct callers:
  - mm/mlock.c:__ia32_sys_mlock2
  - mm/mlock.c:__x64_sys_mlock2
  - mm/mlock.c:__ia32_sys_mlock
  - mm/mlock.c:__x64_sys_mlock
```
**Symbols:**

```
ffffffff813c2c20-ffffffff813c2efa: do_mlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int do_mlock(long unsigned int start, size_t len, vm_flags_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff813f7e70)
Location: mm/mlock.c:574
Inline: False
Direct callers:
  - mm/mlock.c:__ia32_sys_mlock2
  - mm/mlock.c:__x64_sys_mlock2
  - mm/mlock.c:__ia32_sys_mlock
  - mm/mlock.c:__x64_sys_mlock
```
**Symbols:**

```
ffffffff813f7e70-ffffffff813f8168: do_mlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int do_mlock(long unsigned int start, size_t len, vm_flags_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff81423a40)
Location: mm/mlock.c:624
Inline: False
Direct callers:
  - mm/mlock.c:__ia32_sys_mlock2
  - mm/mlock.c:__x64_sys_mlock2
  - mm/mlock.c:__ia32_sys_mlock
  - mm/mlock.c:__x64_sys_mlock
```
**Symbols:**

```
ffffffff81423a40-ffffffff81423d37: do_mlock (STB_LOCAL)
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
int do_mlock(long unsigned int start, size_t len, vm_flags_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffff8000102fe6f8)
Location: mm/mlock.c:671
Inline: False
Direct callers:
  - mm/mlock.c:__arm64_sys_mlock2
  - mm/mlock.c:__arm64_sys_mlock
```
**Symbols:**

```
ffff8000102fe6f8-ffff8000102fe910: do_mlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int do_mlock(long unsigned int start, size_t len, vm_flags_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (c051d700)
Location: mm/mlock.c:671
Inline: False
Direct callers:
  - mm/mlock.c:__se_sys_mlock2
  - mm/mlock.c:__se_sys_mlock
```
**Symbols:**

```
c051d700-c051d940: do_mlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int do_mlock(long unsigned int start, size_t len, vm_flags_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (c0000000003ca160)
Location: mm/mlock.c:671
Inline: False
Direct callers:
  - mm/mlock.c:__se_sys_mlock2
  - mm/mlock.c:__se_sys_mlock
```
**Symbols:**

```
c0000000003ca160-c0000000003ca444: do_mlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int do_mlock(long unsigned int start, size_t len, vm_flags_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffe00020cafa)
Location: mm/mlock.c:671
Inline: False
Direct callers:
  - mm/mlock.c:__se_sys_mlock2
  - mm/mlock.c:__se_sys_mlock
```
**Symbols:**

```
ffffffe00020cafa-ffffffe00020cc72: do_mlock (STB_LOCAL)
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
int do_mlock(long unsigned int start, size_t len, vm_flags_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff8125fb00)
Location: mm/mlock.c:671
Inline: False
Direct callers:
  - mm/mlock.c:__ia32_sys_mlock2
  - mm/mlock.c:__x64_sys_mlock2
  - mm/mlock.c:__ia32_sys_mlock
  - mm/mlock.c:__x64_sys_mlock
```
**Symbols:**

```
ffffffff8125fb00-ffffffff8125fd15: do_mlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int do_mlock(long unsigned int start, size_t len, vm_flags_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff81251f20)
Location: mm/mlock.c:671
Inline: False
Direct callers:
  - mm/mlock.c:__ia32_sys_mlock2
  - mm/mlock.c:__x64_sys_mlock2
  - mm/mlock.c:__ia32_sys_mlock
  - mm/mlock.c:__x64_sys_mlock
```
**Symbols:**

```
ffffffff81251f20-ffffffff81252135: do_mlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int do_mlock(long unsigned int start, size_t len, vm_flags_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff8125d8a0)
Location: mm/mlock.c:671
Inline: False
Direct callers:
  - mm/mlock.c:__ia32_sys_mlock2
  - mm/mlock.c:__x64_sys_mlock2
  - mm/mlock.c:__ia32_sys_mlock
  - mm/mlock.c:__x64_sys_mlock
```
**Symbols:**

```
ffffffff8125d8a0-ffffffff8125dab5: do_mlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int do_mlock(long unsigned int start, size_t len, vm_flags_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff8126d280)
Location: mm/mlock.c:671
Inline: False
Direct callers:
  - mm/mlock.c:__ia32_sys_mlock2
  - mm/mlock.c:__x64_sys_mlock2
  - mm/mlock.c:__ia32_sys_mlock
  - mm/mlock.c:__x64_sys_mlock
```
**Symbols:**

```
ffffffff8126d280-ffffffff8126d495: do_mlock (STB_LOCAL)
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
