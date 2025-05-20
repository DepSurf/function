# Function: <code>do_compat_sigaltstack</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int do_compat_sigaltstack(const compat_stack_t *uss_ptr, compat_stack_t *uoss_ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8109cb70)
Location: kernel/signal.c:3498
Inline: False
Direct callers:
  - kernel/signal.c:compat_restore_altstack
  - kernel/signal.c:__x32_compat_sys_sigaltstack
  - kernel/signal.c:__ia32_compat_sys_sigaltstack
```
**Symbols:**

```
ffffffff8109cb70-ffffffff8109cc6b: do_compat_sigaltstack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int do_compat_sigaltstack(const compat_stack_t *uss_ptr, compat_stack_t *uoss_ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810a4e30)
Location: kernel/signal.c:3825
Inline: False
Direct callers:
  - kernel/signal.c:compat_restore_altstack
  - kernel/signal.c:__x32_compat_sys_sigaltstack
  - kernel/signal.c:__ia32_compat_sys_sigaltstack
```
**Symbols:**

```
ffffffff810a4e30-ffffffff810a4f29: do_compat_sigaltstack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int do_compat_sigaltstack(const compat_stack_t *uss_ptr, compat_stack_t *uoss_ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810a9af0)
Location: kernel/signal.c:4073
Inline: False
Direct callers:
  - kernel/signal.c:compat_restore_altstack
  - kernel/signal.c:__x32_compat_sys_sigaltstack
  - kernel/signal.c:__ia32_compat_sys_sigaltstack
```
**Symbols:**

```
ffffffff810a9af0-ffffffff810a9bef: do_compat_sigaltstack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int do_compat_sigaltstack(const compat_stack_t *uss_ptr, compat_stack_t *uoss_ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b00d0)
Location: kernel/signal.c:4081
Inline: False
Direct callers:
  - kernel/signal.c:compat_restore_altstack
  - kernel/signal.c:__x32_compat_sys_sigaltstack
  - kernel/signal.c:__ia32_compat_sys_sigaltstack
```
**Symbols:**

```
ffffffff810b00d0-ffffffff810b01cf: do_compat_sigaltstack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int do_compat_sigaltstack(const compat_stack_t *uss_ptr, compat_stack_t *uoss_ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b7c90)
Location: kernel/signal.c:4099
Inline: False
Direct callers:
  - kernel/signal.c:compat_restore_altstack
  - kernel/signal.c:__x32_compat_sys_sigaltstack
  - kernel/signal.c:__ia32_compat_sys_sigaltstack
```
**Symbols:**

```
ffffffff810b7c90-ffffffff810b7d8f: do_compat_sigaltstack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int do_compat_sigaltstack(const compat_stack_t *uss_ptr, compat_stack_t *uoss_ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b2f40)
Location: kernel/signal.c:4136
Inline: False
Direct callers:
  - kernel/signal.c:compat_restore_altstack
  - kernel/signal.c:__x32_compat_sys_sigaltstack
  - kernel/signal.c:__ia32_compat_sys_sigaltstack
```
**Symbols:**

```
ffffffff810b2f40-ffffffff810b303f: do_compat_sigaltstack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int do_compat_sigaltstack(const compat_stack_t *uss_ptr, compat_stack_t *uoss_ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b4570)
Location: kernel/signal.c:4158
Inline: False
Direct callers:
  - kernel/signal.c:compat_restore_altstack
  - kernel/signal.c:__x32_compat_sys_sigaltstack
  - kernel/signal.c:__ia32_compat_sys_sigaltstack
```
**Symbols:**

```
ffffffff810b4570-ffffffff810b466f: do_compat_sigaltstack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int do_compat_sigaltstack(const compat_stack_t *uss_ptr, compat_stack_t *uoss_ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810c6740)
Location: kernel/signal.c:4246
Inline: False
Direct callers:
  - kernel/signal.c:compat_restore_altstack
  - kernel/signal.c:__x64_compat_sys_sigaltstack
  - kernel/signal.c:__ia32_compat_sys_sigaltstack
```
**Symbols:**

```
ffffffff810c6740-ffffffff810c683f: do_compat_sigaltstack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int do_compat_sigaltstack(const compat_stack_t *uss_ptr, compat_stack_t *uoss_ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810de240)
Location: kernel/signal.c:4261
Inline: False
Direct callers:
  - kernel/signal.c:compat_restore_altstack
  - kernel/signal.c:__ia32_compat_sys_sigaltstack
```
**Symbols:**

```
ffffffff810de240-ffffffff810de37c: do_compat_sigaltstack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int do_compat_sigaltstack(const compat_stack_t *uss_ptr, compat_stack_t *uoss_ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810fe6d0)
Location: kernel/signal.c:4263
Inline: False
Direct callers:
  - kernel/signal.c:compat_restore_altstack
  - kernel/signal.c:__ia32_compat_sys_sigaltstack
```
**Symbols:**

```
ffffffff810fe6d0-ffffffff810fe80c: do_compat_sigaltstack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int do_compat_sigaltstack(const compat_stack_t *uss_ptr, compat_stack_t *uoss_ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8110a740)
Location: kernel/signal.c:4287
Inline: False
Direct callers:
  - kernel/signal.c:compat_restore_altstack
  - kernel/signal.c:__ia32_compat_sys_sigaltstack
```
**Symbols:**

```
ffffffff8110a740-ffffffff8110a87c: do_compat_sigaltstack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int do_compat_sigaltstack(const compat_stack_t *uss_ptr, compat_stack_t *uoss_ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff811140e0)
Location: kernel/signal.c:4298
Inline: False
Direct callers:
  - kernel/signal.c:compat_restore_altstack
  - kernel/signal.c:__ia32_compat_sys_sigaltstack
```
**Symbols:**

```
ffffffff811140e0-ffffffff8111421c: do_compat_sigaltstack (STB_LOCAL)
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
int do_compat_sigaltstack(const compat_stack_t *uss_ptr, compat_stack_t *uoss_ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffff80001010c0f0)
Location: kernel/signal.c:4081
Inline: False
Direct callers:
  - kernel/signal.c:compat_restore_altstack
  - kernel/signal.c:__arm64_compat_sys_sigaltstack
```
**Symbols:**

```
ffff80001010c0f0-ffff80001010c264: do_compat_sigaltstack (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int do_compat_sigaltstack(const compat_stack_t *uss_ptr, compat_stack_t *uoss_ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (c000000000152900)
Location: kernel/signal.c:4081
Inline: False
Direct callers:
  - kernel/signal.c:compat_restore_altstack
  - kernel/signal.c:__se_compat_sys_sigaltstack
```
**Symbols:**

```
c000000000152900-c000000000152a20: do_compat_sigaltstack (STB_LOCAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int do_compat_sigaltstack(const compat_stack_t *uss_ptr, compat_stack_t *uoss_ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810aa440)
Location: kernel/signal.c:4081
Inline: False
Direct callers:
  - kernel/signal.c:compat_restore_altstack
  - kernel/signal.c:__x32_compat_sys_sigaltstack
  - kernel/signal.c:__ia32_compat_sys_sigaltstack
```
**Symbols:**

```
ffffffff810aa440-ffffffff810aa53f: do_compat_sigaltstack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int do_compat_sigaltstack(const compat_stack_t *uss_ptr, compat_stack_t *uoss_ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81098df0)
Location: kernel/signal.c:4081
Inline: False
Direct callers:
  - kernel/signal.c:compat_restore_altstack
  - kernel/signal.c:__x32_compat_sys_sigaltstack
  - kernel/signal.c:__ia32_compat_sys_sigaltstack
```
**Symbols:**

```
ffffffff81098df0-ffffffff81098eef: do_compat_sigaltstack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int do_compat_sigaltstack(const compat_stack_t *uss_ptr, compat_stack_t *uoss_ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810a99a0)
Location: kernel/signal.c:4081
Inline: False
Direct callers:
  - kernel/signal.c:compat_restore_altstack
  - kernel/signal.c:__x32_compat_sys_sigaltstack
  - kernel/signal.c:__ia32_compat_sys_sigaltstack
```
**Symbols:**

```
ffffffff810a99a0-ffffffff810a9a9f: do_compat_sigaltstack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int do_compat_sigaltstack(const compat_stack_t *uss_ptr, compat_stack_t *uoss_ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b1df0)
Location: kernel/signal.c:4081
Inline: False
Direct callers:
  - kernel/signal.c:compat_restore_altstack
  - kernel/signal.c:__x32_compat_sys_sigaltstack
  - kernel/signal.c:__ia32_compat_sys_sigaltstack
```
**Symbols:**

```
ffffffff810b1df0-ffffffff810b1eef: do_compat_sigaltstack (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
