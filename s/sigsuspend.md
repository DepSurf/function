# Function: <code>sigsuspend</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int sigsuspend(sigset_t *set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81090b20)
Location: kernel/signal.c:3506
Inline: False
Direct callers:
  - kernel/signal.c:compat_SyS_rt_sigsuspend
  - kernel/signal.c:SyS_sigsuspend
```
**Symbols:**

```
ffffffff81090b20-ffffffff81090b95: sigsuspend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int sigsuspend(sigset_t *set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81093bb0)
Location: kernel/signal.c:3509
Inline: False
Direct callers:
  - kernel/signal.c:SyS_sigsuspend
  - kernel/signal.c:compat_SyS_rt_sigsuspend
```
**Symbols:**

```
ffffffff81093bb0-ffffffff81093c46: sigsuspend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int sigsuspend(sigset_t *set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81098bb0)
Location: kernel/signal.c:3536
Inline: False
Direct callers:
  - kernel/signal.c:SyS_sigsuspend
  - kernel/signal.c:compat_SyS_rt_sigsuspend
```
**Symbols:**

```
ffffffff81098bb0-ffffffff81098c30: sigsuspend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int sigsuspend(sigset_t *set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81095e40)
Location: kernel/signal.c:3591
Inline: False
Direct callers:
  - kernel/signal.c:SyS_sigsuspend
  - kernel/signal.c:compat_SyS_rt_sigsuspend
```
**Symbols:**

```
ffffffff81095e40-ffffffff81095eb1: sigsuspend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int sigsuspend(sigset_t *set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8109cc90)
Location: kernel/signal.c:3606
Inline: False
Direct callers:
  - kernel/signal.c:SyS_sigsuspend
  - kernel/signal.c:compat_SyS_rt_sigsuspend
  - kernel/signal.c:SyS_rt_sigsuspend
```
**Symbols:**

```
ffffffff8109cc90-ffffffff8109cd0a: sigsuspend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int sigsuspend(sigset_t *set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810a1250)
Location: kernel/signal.c:3854
Inline: False
Direct callers:
  - kernel/signal.c:__ia32_sys_sigsuspend
  - kernel/signal.c:__x64_sys_sigsuspend
  - kernel/signal.c:__x32_compat_sys_rt_sigsuspend
  - kernel/signal.c:__ia32_compat_sys_rt_sigsuspend
  - kernel/signal.c:__ia32_sys_rt_sigsuspend
  - kernel/signal.c:__x64_sys_rt_sigsuspend
```
**Symbols:**

```
ffffffff810a1250-ffffffff810a12ca: sigsuspend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int sigsuspend(sigset_t *set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810a97d0)
Location: kernel/signal.c:4181
Inline: False
Direct callers:
  - kernel/signal.c:__ia32_sys_sigsuspend
  - kernel/signal.c:__x64_sys_sigsuspend
  - kernel/signal.c:__x32_compat_sys_rt_sigsuspend
  - kernel/signal.c:__ia32_compat_sys_rt_sigsuspend
  - kernel/signal.c:__ia32_sys_rt_sigsuspend
  - kernel/signal.c:__x64_sys_rt_sigsuspend
```
**Symbols:**

```
ffffffff810a97d0-ffffffff810a984a: sigsuspend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int sigsuspend(sigset_t *set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810ac060)
Location: kernel/signal.c:4429
Inline: False
Direct callers:
  - kernel/signal.c:__ia32_sys_sigsuspend
  - kernel/signal.c:__x64_sys_sigsuspend
  - kernel/signal.c:__x32_compat_sys_rt_sigsuspend
  - kernel/signal.c:__ia32_compat_sys_rt_sigsuspend
  - kernel/signal.c:__ia32_sys_rt_sigsuspend
  - kernel/signal.c:__x64_sys_rt_sigsuspend
```
**Symbols:**

```
ffffffff810ac060-ffffffff810ac0c0: sigsuspend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int sigsuspend(sigset_t *set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b2670)
Location: kernel/signal.c:4437
Inline: False
Direct callers:
  - kernel/signal.c:__ia32_sys_sigsuspend
  - kernel/signal.c:__x64_sys_sigsuspend
  - kernel/signal.c:__x32_compat_sys_rt_sigsuspend
  - kernel/signal.c:__ia32_compat_sys_rt_sigsuspend
  - kernel/signal.c:__ia32_sys_rt_sigsuspend
  - kernel/signal.c:__x64_sys_rt_sigsuspend
```
**Symbols:**

```
ffffffff810b2670-ffffffff810b26d0: sigsuspend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int sigsuspend(sigset_t *set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810bb0f0)
Location: kernel/signal.c:4455
Inline: False
Direct callers:
  - kernel/signal.c:__ia32_sys_sigsuspend
  - kernel/signal.c:__x64_sys_sigsuspend
  - kernel/signal.c:__x32_compat_sys_rt_sigsuspend
  - kernel/signal.c:__ia32_compat_sys_rt_sigsuspend
  - kernel/signal.c:__ia32_sys_rt_sigsuspend
  - kernel/signal.c:__x64_sys_rt_sigsuspend
```
**Symbols:**

```
ffffffff810bb0f0-ffffffff810bb153: sigsuspend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int sigsuspend(sigset_t *set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b63a0)
Location: kernel/signal.c:4492
Inline: False
Direct callers:
  - kernel/signal.c:__ia32_sys_sigsuspend
  - kernel/signal.c:__x64_sys_sigsuspend
  - kernel/signal.c:__x32_compat_sys_rt_sigsuspend
  - kernel/signal.c:__ia32_compat_sys_rt_sigsuspend
  - kernel/signal.c:__ia32_sys_rt_sigsuspend
  - kernel/signal.c:__x64_sys_rt_sigsuspend
```
**Symbols:**

```
ffffffff810b63a0-ffffffff810b6418: sigsuspend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int sigsuspend(sigset_t *set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b5640)
Location: kernel/signal.c:4514
Inline: False
Direct callers:
  - kernel/signal.c:__ia32_sys_sigsuspend
  - kernel/signal.c:__x64_sys_sigsuspend
  - kernel/signal.c:__x32_compat_sys_rt_sigsuspend
  - kernel/signal.c:__ia32_compat_sys_rt_sigsuspend
  - kernel/signal.c:__ia32_sys_rt_sigsuspend
  - kernel/signal.c:__x64_sys_rt_sigsuspend
```
**Symbols:**

```
ffffffff810b5640-ffffffff810b56fa: sigsuspend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int sigsuspend(sigset_t *set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810c7c40)
Location: kernel/signal.c:4598
Inline: False
Direct callers:
  - kernel/signal.c:__ia32_sys_sigsuspend
  - kernel/signal.c:__x64_sys_sigsuspend
  - kernel/signal.c:__x64_compat_sys_rt_sigsuspend
  - kernel/signal.c:__ia32_compat_sys_rt_sigsuspend
  - kernel/signal.c:__ia32_sys_rt_sigsuspend
  - kernel/signal.c:__x64_sys_rt_sigsuspend
```
**Symbols:**

```
ffffffff810c7c40-ffffffff810c7cf9: sigsuspend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int sigsuspend(sigset_t *set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810def20)
Location: kernel/signal.c:4613
Inline: False
Direct callers:
  - kernel/signal.c:__ia32_sys_sigsuspend
  - kernel/signal.c:__x64_sys_sigsuspend
  - kernel/signal.c:__ia32_compat_sys_rt_sigsuspend
  - kernel/signal.c:__ia32_sys_rt_sigsuspend
  - kernel/signal.c:__x64_sys_rt_sigsuspend
```
**Symbols:**

```
ffffffff810def20-ffffffff810defda: sigsuspend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int sigsuspend(sigset_t *set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810ffcc0)
Location: kernel/signal.c:4615
Inline: False
Direct callers:
  - kernel/signal.c:__ia32_sys_sigsuspend
  - kernel/signal.c:__x64_sys_sigsuspend
  - kernel/signal.c:__ia32_compat_sys_rt_sigsuspend
  - kernel/signal.c:__ia32_sys_rt_sigsuspend
  - kernel/signal.c:__x64_sys_rt_sigsuspend
```
**Symbols:**

```
ffffffff810ffcc0-ffffffff810ffd7a: sigsuspend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int sigsuspend(sigset_t *set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8110bd50)
Location: kernel/signal.c:4639
Inline: False
Direct callers:
  - kernel/signal.c:__ia32_sys_sigsuspend
  - kernel/signal.c:__x64_sys_sigsuspend
  - kernel/signal.c:__ia32_compat_sys_rt_sigsuspend
  - kernel/signal.c:__ia32_sys_rt_sigsuspend
  - kernel/signal.c:__x64_sys_rt_sigsuspend
```
**Symbols:**

```
ffffffff8110bd50-ffffffff8110be0a: sigsuspend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int sigsuspend(sigset_t *set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81115700)
Location: kernel/signal.c:4650
Inline: False
Direct callers:
  - kernel/signal.c:__ia32_sys_sigsuspend
  - kernel/signal.c:__x64_sys_sigsuspend
  - kernel/signal.c:__ia32_compat_sys_rt_sigsuspend
  - kernel/signal.c:__ia32_sys_rt_sigsuspend
  - kernel/signal.c:__x64_sys_rt_sigsuspend
```
**Symbols:**

```
ffffffff81115700-ffffffff811157ba: sigsuspend (STB_LOCAL)
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
int sigsuspend(sigset_t *set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffff80001010e498)
Location: kernel/signal.c:4437
Inline: False
Direct callers:
  - kernel/signal.c:__arm64_sys_sigsuspend
  - kernel/signal.c:__arm64_compat_sys_rt_sigsuspend
  - kernel/signal.c:__arm64_sys_rt_sigsuspend
```
**Symbols:**

```
ffff80001010e498-ffff80001010e530: sigsuspend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int sigsuspend(sigset_t *set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (c036656c)
Location: kernel/signal.c:4437
Inline: False
Direct callers:
  - kernel/signal.c:__se_sys_sigsuspend
  - kernel/signal.c:__se_sys_rt_sigsuspend
```
**Symbols:**

```
c036656c-c036661c: sigsuspend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int sigsuspend(sigset_t *set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (c0000000001558d0)
Location: kernel/signal.c:4437
Inline: False
Direct callers:
  - kernel/signal.c:__se_sys_sigsuspend
  - kernel/signal.c:__se_compat_sys_rt_sigsuspend
  - kernel/signal.c:__se_sys_rt_sigsuspend
```
**Symbols:**

```
c0000000001558d0-c000000000155978: sigsuspend (STB_LOCAL)
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
In kernel/signal.c (ffffffe0000d1eda)
Location: kernel/signal.c:4437
Inline: True
Inline callers:
  - kernel/signal.c:__se_sys_rt_sigsuspend
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
int sigsuspend(sigset_t *set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810ac9e0)
Location: kernel/signal.c:4437
Inline: False
Direct callers:
  - kernel/signal.c:__ia32_sys_sigsuspend
  - kernel/signal.c:__x64_sys_sigsuspend
  - kernel/signal.c:__x32_compat_sys_rt_sigsuspend
  - kernel/signal.c:__ia32_compat_sys_rt_sigsuspend
  - kernel/signal.c:__ia32_sys_rt_sigsuspend
  - kernel/signal.c:__x64_sys_rt_sigsuspend
```
**Symbols:**

```
ffffffff810ac9e0-ffffffff810aca40: sigsuspend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int sigsuspend(sigset_t *set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8109b360)
Location: kernel/signal.c:4437
Inline: False
Direct callers:
  - kernel/signal.c:__ia32_sys_sigsuspend
  - kernel/signal.c:__x64_sys_sigsuspend
  - kernel/signal.c:__x32_compat_sys_rt_sigsuspend
  - kernel/signal.c:__ia32_compat_sys_rt_sigsuspend
  - kernel/signal.c:__ia32_sys_rt_sigsuspend
  - kernel/signal.c:__x64_sys_rt_sigsuspend
```
**Symbols:**

```
ffffffff8109b360-ffffffff8109b3c0: sigsuspend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int sigsuspend(sigset_t *set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810abf40)
Location: kernel/signal.c:4437
Inline: False
Direct callers:
  - kernel/signal.c:__ia32_sys_sigsuspend
  - kernel/signal.c:__x64_sys_sigsuspend
  - kernel/signal.c:__x32_compat_sys_rt_sigsuspend
  - kernel/signal.c:__ia32_compat_sys_rt_sigsuspend
  - kernel/signal.c:__ia32_sys_rt_sigsuspend
  - kernel/signal.c:__x64_sys_rt_sigsuspend
```
**Symbols:**

```
ffffffff810abf40-ffffffff810abfa0: sigsuspend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int sigsuspend(sigset_t *set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b40b0)
Location: kernel/signal.c:4437
Inline: False
Direct callers:
  - kernel/signal.c:__ia32_sys_sigsuspend
  - kernel/signal.c:__x64_sys_sigsuspend
  - kernel/signal.c:__x32_compat_sys_rt_sigsuspend
  - kernel/signal.c:__ia32_compat_sys_rt_sigsuspend
  - kernel/signal.c:__ia32_sys_rt_sigsuspend
  - kernel/signal.c:__x64_sys_rt_sigsuspend
```
**Symbols:**

```
ffffffff810b40b0-ffffffff810b4110: sigsuspend (STB_LOCAL)
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
