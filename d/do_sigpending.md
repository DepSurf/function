# Function: <code>do_sigpending</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81090de1)
Location: kernel/signal.c:2604
Inline: True
Inline callers:
  - kernel/signal.c:compat_SyS_rt_sigpending
  - kernel/signal.c:SyS_sigpending
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81094e6c)
Location: kernel/signal.c:2604
Inline: True
Inline callers:
  - kernel/signal.c:SyS_sigpending
  - kernel/signal.c:compat_SyS_rt_sigpending
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81099e6c)
Location: kernel/signal.c:2617
Inline: True
Inline callers:
  - kernel/signal.c:SyS_sigpending
  - kernel/signal.c:compat_SyS_rt_sigpending
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81096fcc)
Location: kernel/signal.c:2638
Inline: True
Inline callers:
  - kernel/signal.c:compat_SyS_sigpending
  - kernel/signal.c:SyS_sigpending
  - kernel/signal.c:compat_SyS_rt_sigpending
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int do_sigpending(sigset_t *set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81099710)
Location: kernel/signal.c:2625
Inline: False
Direct callers:
  - kernel/signal.c:compat_SyS_sigpending
  - kernel/signal.c:SyS_sigpending
  - kernel/signal.c:compat_SyS_rt_sigpending
```
**Symbols:**

```
ffffffff81099710-ffffffff8109977f: do_sigpending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int do_sigpending(sigset_t *set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8109cf50)
Location: kernel/signal.c:2758
Inline: False
Direct callers:
  - kernel/signal.c:__x32_compat_sys_sigpending
  - kernel/signal.c:__ia32_compat_sys_sigpending
  - kernel/signal.c:__ia32_sys_sigpending
  - kernel/signal.c:__x64_sys_sigpending
  - kernel/signal.c:__x32_compat_sys_rt_sigpending
  - kernel/signal.c:__ia32_compat_sys_rt_sigpending
  - kernel/signal.c:__ia32_sys_rt_sigpending
  - kernel/signal.c:__x64_sys_rt_sigpending
```
**Symbols:**

```
ffffffff8109cf50-ffffffff8109cfbf: do_sigpending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void do_sigpending(sigset_t *set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810a5260)
Location: kernel/signal.c:2936
Inline: False
Direct callers:
  - kernel/signal.c:__x32_compat_sys_sigpending
  - kernel/signal.c:__ia32_compat_sys_sigpending
  - kernel/signal.c:__ia32_sys_sigpending
  - kernel/signal.c:__x64_sys_sigpending
  - kernel/signal.c:__x32_compat_sys_rt_sigpending
  - kernel/signal.c:__ia32_compat_sys_rt_sigpending
  - kernel/signal.c:__ia32_sys_rt_sigpending
  - kernel/signal.c:__x64_sys_rt_sigpending
```
**Symbols:**

```
ffffffff810a5260-ffffffff810a52cd: do_sigpending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void do_sigpending(sigset_t *set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810a9f30)
Location: kernel/signal.c:3065
Inline: False
Direct callers:
  - kernel/signal.c:__x32_compat_sys_sigpending
  - kernel/signal.c:__ia32_compat_sys_sigpending
  - kernel/signal.c:__ia32_sys_sigpending
  - kernel/signal.c:__x64_sys_sigpending
  - kernel/signal.c:__x32_compat_sys_rt_sigpending
  - kernel/signal.c:__ia32_compat_sys_rt_sigpending
  - kernel/signal.c:__ia32_sys_rt_sigpending
  - kernel/signal.c:__x64_sys_rt_sigpending
```
**Symbols:**

```
ffffffff810a9f30-ffffffff810a9f92: do_sigpending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void do_sigpending(sigset_t *set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b0510)
Location: kernel/signal.c:3070
Inline: False
Direct callers:
  - kernel/signal.c:__x32_compat_sys_sigpending
  - kernel/signal.c:__ia32_compat_sys_sigpending
  - kernel/signal.c:__ia32_sys_sigpending
  - kernel/signal.c:__x64_sys_sigpending
  - kernel/signal.c:__x32_compat_sys_rt_sigpending
  - kernel/signal.c:__ia32_compat_sys_rt_sigpending
  - kernel/signal.c:__ia32_sys_rt_sigpending
  - kernel/signal.c:__x64_sys_rt_sigpending
```
**Symbols:**

```
ffffffff810b0510-ffffffff810b0572: do_sigpending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void do_sigpending(sigset_t *set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b8760)
Location: kernel/signal.c:3088
Inline: False
Direct callers:
  - kernel/signal.c:__x32_compat_sys_sigpending
  - kernel/signal.c:__ia32_compat_sys_sigpending
  - kernel/signal.c:__ia32_sys_sigpending
  - kernel/signal.c:__x64_sys_sigpending
  - kernel/signal.c:__x32_compat_sys_rt_sigpending
  - kernel/signal.c:__ia32_compat_sys_rt_sigpending
  - kernel/signal.c:__ia32_sys_rt_sigpending
  - kernel/signal.c:__x64_sys_rt_sigpending
```
**Symbols:**

```
ffffffff810b8760-ffffffff810b87c2: do_sigpending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void do_sigpending(sigset_t *set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b3a10)
Location: kernel/signal.c:3108
Inline: False
Direct callers:
  - kernel/signal.c:__x32_compat_sys_sigpending
  - kernel/signal.c:__ia32_compat_sys_sigpending
  - kernel/signal.c:__ia32_sys_sigpending
  - kernel/signal.c:__x64_sys_sigpending
  - kernel/signal.c:__x32_compat_sys_rt_sigpending
  - kernel/signal.c:__ia32_compat_sys_rt_sigpending
  - kernel/signal.c:__ia32_sys_rt_sigpending
  - kernel/signal.c:__x64_sys_rt_sigpending
```
**Symbols:**

```
ffffffff810b3a10-ffffffff810b3a72: do_sigpending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void do_sigpending(sigset_t *set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b4fc0)
Location: kernel/signal.c:3130
Inline: False
Direct callers:
  - kernel/signal.c:__x32_compat_sys_sigpending
  - kernel/signal.c:__ia32_compat_sys_sigpending
  - kernel/signal.c:__ia32_sys_sigpending
  - kernel/signal.c:__x64_sys_sigpending
  - kernel/signal.c:__x32_compat_sys_rt_sigpending
  - kernel/signal.c:__ia32_compat_sys_rt_sigpending
  - kernel/signal.c:__ia32_sys_rt_sigpending
  - kernel/signal.c:__x64_sys_rt_sigpending
```
**Symbols:**

```
ffffffff810b4fc0-ffffffff810b5022: do_sigpending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void do_sigpending(sigset_t *set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810c75a0)
Location: kernel/signal.c:3215
Inline: False
Direct callers:
  - kernel/signal.c:__x64_compat_sys_sigpending
  - kernel/signal.c:__ia32_compat_sys_sigpending
  - kernel/signal.c:__ia32_sys_sigpending
  - kernel/signal.c:__x64_sys_sigpending
  - kernel/signal.c:__x64_compat_sys_rt_sigpending
  - kernel/signal.c:__ia32_compat_sys_rt_sigpending
  - kernel/signal.c:__ia32_sys_rt_sigpending
  - kernel/signal.c:__x64_sys_rt_sigpending
```
**Symbols:**

```
ffffffff810c75a0-ffffffff810c7602: do_sigpending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void do_sigpending(sigset_t *set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810dd2e0)
Location: kernel/signal.c:3195
Inline: False
Direct callers:
  - kernel/signal.c:__ia32_compat_sys_sigpending
  - kernel/signal.c:__ia32_sys_sigpending
  - kernel/signal.c:__x64_sys_sigpending
  - kernel/signal.c:__ia32_compat_sys_rt_sigpending
  - kernel/signal.c:__ia32_sys_rt_sigpending
  - kernel/signal.c:__x64_sys_rt_sigpending
```
**Symbols:**

```
ffffffff810dd2e0-ffffffff810dd341: do_sigpending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void do_sigpending(sigset_t *set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810fd640)
Location: kernel/signal.c:3197
Inline: False
Direct callers:
  - kernel/signal.c:__ia32_compat_sys_sigpending
  - kernel/signal.c:__ia32_sys_sigpending
  - kernel/signal.c:__x64_sys_sigpending
  - kernel/signal.c:__ia32_compat_sys_rt_sigpending
  - kernel/signal.c:__ia32_sys_rt_sigpending
  - kernel/signal.c:__x64_sys_rt_sigpending
```
**Symbols:**

```
ffffffff810fd640-ffffffff810fd6a1: do_sigpending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void do_sigpending(sigset_t *set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff811096b0)
Location: kernel/signal.c:3221
Inline: False
Direct callers:
  - kernel/signal.c:__ia32_compat_sys_sigpending
  - kernel/signal.c:__ia32_sys_sigpending
  - kernel/signal.c:__x64_sys_sigpending
  - kernel/signal.c:__ia32_compat_sys_rt_sigpending
  - kernel/signal.c:__ia32_sys_rt_sigpending
  - kernel/signal.c:__x64_sys_rt_sigpending
```
**Symbols:**

```
ffffffff811096b0-ffffffff81109711: do_sigpending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void do_sigpending(sigset_t *set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81113050)
Location: kernel/signal.c:3232
Inline: False
Direct callers:
  - kernel/signal.c:__ia32_compat_sys_sigpending
  - kernel/signal.c:__ia32_sys_sigpending
  - kernel/signal.c:__x64_sys_sigpending
  - kernel/signal.c:__ia32_compat_sys_rt_sigpending
  - kernel/signal.c:__ia32_sys_rt_sigpending
  - kernel/signal.c:__x64_sys_rt_sigpending
```
**Symbols:**

```
ffffffff81113050-ffffffff811130b1: do_sigpending (STB_LOCAL)
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
void do_sigpending(sigset_t *set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffff80001010b580)
Location: kernel/signal.c:3070
Inline: False
Direct callers:
  - kernel/signal.c:__arm64_compat_sys_sigpending
  - kernel/signal.c:__arm64_sys_sigpending
  - kernel/signal.c:__arm64_compat_sys_rt_sigpending
  - kernel/signal.c:__arm64_sys_rt_sigpending
```
**Symbols:**

```
ffff80001010b580-ffff80001010b638: do_sigpending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void do_sigpending(sigset_t *set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (c0363600)
Location: kernel/signal.c:3070
Inline: False
Direct callers:
  - kernel/signal.c:__se_sys_sigpending
  - kernel/signal.c:__se_sys_rt_sigpending
```
**Symbols:**

```
c0363600-c03636b8: do_sigpending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void do_sigpending(sigset_t *set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (c000000000152cd0)
Location: kernel/signal.c:3070
Inline: False
Direct callers:
  - kernel/signal.c:__se_compat_sys_sigpending
  - kernel/signal.c:__se_sys_sigpending
  - kernel/signal.c:__se_compat_sys_rt_sigpending
  - kernel/signal.c:__se_sys_rt_sigpending
```
**Symbols:**

```
c000000000152cd0-c000000000152d90: do_sigpending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffe0000cf362)
Location: kernel/signal.c:3070
Inline: True
Inline callers:
  - kernel/signal.c:__se_sys_rt_sigpending
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
void do_sigpending(sigset_t *set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810aa880)
Location: kernel/signal.c:3070
Inline: False
Direct callers:
  - kernel/signal.c:__x32_compat_sys_sigpending
  - kernel/signal.c:__ia32_compat_sys_sigpending
  - kernel/signal.c:__ia32_sys_sigpending
  - kernel/signal.c:__x64_sys_sigpending
  - kernel/signal.c:__x32_compat_sys_rt_sigpending
  - kernel/signal.c:__ia32_compat_sys_rt_sigpending
  - kernel/signal.c:__ia32_sys_rt_sigpending
  - kernel/signal.c:__x64_sys_rt_sigpending
```
**Symbols:**

```
ffffffff810aa880-ffffffff810aa8e2: do_sigpending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void do_sigpending(sigset_t *set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81099230)
Location: kernel/signal.c:3070
Inline: False
Direct callers:
  - kernel/signal.c:__x32_compat_sys_sigpending
  - kernel/signal.c:__ia32_compat_sys_sigpending
  - kernel/signal.c:__ia32_sys_sigpending
  - kernel/signal.c:__x64_sys_sigpending
  - kernel/signal.c:__x32_compat_sys_rt_sigpending
  - kernel/signal.c:__ia32_compat_sys_rt_sigpending
  - kernel/signal.c:__ia32_sys_rt_sigpending
  - kernel/signal.c:__x64_sys_rt_sigpending
```
**Symbols:**

```
ffffffff81099230-ffffffff8109928c: do_sigpending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void do_sigpending(sigset_t *set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810a9de0)
Location: kernel/signal.c:3070
Inline: False
Direct callers:
  - kernel/signal.c:__x32_compat_sys_sigpending
  - kernel/signal.c:__ia32_compat_sys_sigpending
  - kernel/signal.c:__ia32_sys_sigpending
  - kernel/signal.c:__x64_sys_sigpending
  - kernel/signal.c:__x32_compat_sys_rt_sigpending
  - kernel/signal.c:__ia32_compat_sys_rt_sigpending
  - kernel/signal.c:__ia32_sys_rt_sigpending
  - kernel/signal.c:__x64_sys_rt_sigpending
```
**Symbols:**

```
ffffffff810a9de0-ffffffff810a9e42: do_sigpending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void do_sigpending(sigset_t *set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b0ed0)
Location: kernel/signal.c:3070
Inline: False
Direct callers:
  - kernel/signal.c:__x32_compat_sys_sigpending
  - kernel/signal.c:__ia32_compat_sys_sigpending
  - kernel/signal.c:__ia32_sys_sigpending
  - kernel/signal.c:__x64_sys_sigpending
  - kernel/signal.c:__x32_compat_sys_rt_sigpending
  - kernel/signal.c:__ia32_compat_sys_rt_sigpending
  - kernel/signal.c:__ia32_sys_rt_sigpending
  - kernel/signal.c:__x64_sys_rt_sigpending
```
**Symbols:**

```
ffffffff810b0ed0-ffffffff810b0f29: do_sigpending (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>void</code>
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
