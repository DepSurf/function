# Function: <code>security_capget</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int security_capget(struct task_struct *target, kernel_cap_t *effective, kernel_cap_t *inheritable, kernel_cap_t *permitted);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8133cc90)
Location: security/security.c:166
Inline: False
Direct callers:
  - kernel/capability.c:SyS_capget
  - kernel/capability.c:SyS_capget
```
**Symbols:**

```
ffffffff8133cc90-ffffffff8133ccf7: security_capget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int security_capget(struct task_struct *target, kernel_cap_t *effective, kernel_cap_t *inheritable, kernel_cap_t *permitted);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813722c0)
Location: security/security.c:167
Inline: False
Direct callers:
  - kernel/capability.c:SyS_capget
  - kernel/capability.c:SyS_capget
```
**Symbols:**

```
ffffffff813722c0-ffffffff81372327: security_capget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int security_capget(struct task_struct *target, kernel_cap_t *effective, kernel_cap_t *inheritable, kernel_cap_t *permitted);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81388bf0)
Location: security/security.c:167
Inline: False
Direct callers:
  - kernel/capability.c:SyS_capget
  - kernel/capability.c:SyS_capget
```
**Symbols:**

```
ffffffff81388bf0-ffffffff81388c57: security_capget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int security_capget(struct task_struct *target, kernel_cap_t *effective, kernel_cap_t *inheritable, kernel_cap_t *permitted);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8139df60)
Location: security/security.c:738
Inline: False
Direct callers:
  - kernel/capability.c:SyS_capget
  - kernel/capability.c:SyS_capget
```
**Symbols:**

```
ffffffff8139df60-ffffffff8139dfc7: security_capget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int security_capget(struct task_struct *target, kernel_cap_t *effective, kernel_cap_t *inheritable, kernel_cap_t *permitted);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813c38e0)
Location: security/security.c:688
Inline: False
Direct callers:
  - kernel/capability.c:SyS_capget
  - kernel/capability.c:SyS_capget
```
**Symbols:**

```
ffffffff813c38e0-ffffffff813c394d: security_capget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int security_capget(struct task_struct *target, kernel_cap_t *effective, kernel_cap_t *inheritable, kernel_cap_t *permitted);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813f3fe0)
Location: security/security.c:265
Inline: False
Direct callers:
  - kernel/capability.c:__ia32_sys_capget
  - kernel/capability.c:__ia32_sys_capget
  - kernel/capability.c:__x64_sys_capget
  - kernel/capability.c:__x64_sys_capget
```
**Symbols:**

```
ffffffff813f3fe0-ffffffff813f4038: security_capget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int security_capget(struct task_struct *target, kernel_cap_t *effective, kernel_cap_t *inheritable, kernel_cap_t *permitted);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8140f410)
Location: security/security.c:751
Inline: False
Direct callers:
  - kernel/capability.c:__ia32_sys_capget
  - kernel/capability.c:__ia32_sys_capget
  - kernel/capability.c:__x64_sys_capget
  - kernel/capability.c:__x64_sys_capget
```
**Symbols:**

```
ffffffff8140f410-ffffffff8140f468: security_capget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int security_capget(struct task_struct *target, kernel_cap_t *effective, kernel_cap_t *inheritable, kernel_cap_t *permitted);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8143c870)
Location: security/security.c:750
Inline: False
Direct callers:
  - kernel/capability.c:__ia32_sys_capget
  - kernel/capability.c:__ia32_sys_capget
  - kernel/capability.c:__x64_sys_capget
  - kernel/capability.c:__x64_sys_capget
```
**Symbols:**

```
ffffffff8143c870-ffffffff8143c8d5: security_capget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int security_capget(struct task_struct *target, kernel_cap_t *effective, kernel_cap_t *inheritable, kernel_cap_t *permitted);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814563d0)
Location: security/security.c:784
Inline: False
Direct callers:
  - kernel/capability.c:__ia32_sys_capget
  - kernel/capability.c:__ia32_sys_capget
  - kernel/capability.c:__x64_sys_capget
  - kernel/capability.c:__x64_sys_capget
```
**Symbols:**

```
ffffffff814563d0-ffffffff81456428: security_capget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int security_capget(struct task_struct *target, kernel_cap_t *effective, kernel_cap_t *inheritable, kernel_cap_t *permitted);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814a9190)
Location: security/security.c:927
Inline: False
Direct callers:
  - kernel/capability.c:__do_sys_capget
  - kernel/capability.c:__do_sys_capget
```
**Symbols:**

```
ffffffff814a9190-ffffffff814a91e8: security_capget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int security_capget(struct task_struct *target, kernel_cap_t *effective, kernel_cap_t *inheritable, kernel_cap_t *permitted);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814c6790)
Location: security/security.c:929
Inline: False
Direct callers:
  - kernel/capability.c:__do_sys_capget
  - kernel/capability.c:__do_sys_capget
```
**Symbols:**

```
ffffffff814c6790-ffffffff814c67e8: security_capget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int security_capget(struct task_struct *target, kernel_cap_t *effective, kernel_cap_t *inheritable, kernel_cap_t *permitted);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814cc880)
Location: security/security.c:953
Inline: False
Direct callers:
  - kernel/capability.c:__do_sys_capget
  - kernel/capability.c:__do_sys_capget
```
**Symbols:**

```
ffffffff814cc880-ffffffff814cc8d8: security_capget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int security_capget(struct task_struct *target, kernel_cap_t *effective, kernel_cap_t *inheritable, kernel_cap_t *permitted);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81525a00)
Location: security/security.c:953
Inline: False
Direct callers:
  - kernel/capability.c:__do_sys_capget
  - kernel/capability.c:__do_sys_capget
```
**Symbols:**

```
ffffffff81525a00-ffffffff81525a58: security_capget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int security_capget(struct task_struct *target, kernel_cap_t *effective, kernel_cap_t *inheritable, kernel_cap_t *permitted);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff815b9c20)
Location: security/security.c:952
Inline: False
Direct callers:
  - kernel/capability.c:__do_sys_capget
  - kernel/capability.c:__do_sys_capget
```
**Symbols:**

```
ffffffff815b9c20-ffffffff815b9c9d: security_capget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int security_capget(struct task_struct *target, kernel_cap_t *effective, kernel_cap_t *inheritable, kernel_cap_t *permitted);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81665440)
Location: security/security.c:950
Inline: False
Direct callers:
  - kernel/capability.c:__do_sys_capget
  - kernel/capability.c:__do_sys_capget
```
**Symbols:**

```
ffffffff81665440-ffffffff816654bd: security_capget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int security_capget(struct task_struct *target, kernel_cap_t *effective, kernel_cap_t *inheritable, kernel_cap_t *permitted);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8169d9c0)
Location: security/security.c:1032
Inline: False
Direct callers:
  - kernel/capability.c:__do_sys_capget
  - kernel/capability.c:__do_sys_capget
```
**Symbols:**

```
ffffffff8169d9c0-ffffffff8169da3d: security_capget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int security_capget(const struct task_struct *target, kernel_cap_t *effective, kernel_cap_t *inheritable, kernel_cap_t *permitted);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816da2f0)
Location: security/security.c:1075
Inline: False
Direct callers:
  - kernel/capability.c:__do_sys_capget
  - kernel/capability.c:__do_sys_capget
```
**Symbols:**

```
ffffffff816da2f0-ffffffff816da36d: security_capget (STB_GLOBAL)
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
int security_capget(struct task_struct *target, kernel_cap_t *effective, kernel_cap_t *inheritable, kernel_cap_t *permitted);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffff800010541bf8)
Location: security/security.c:784
Inline: False
Direct callers:
  - kernel/capability.c:__arm64_sys_capget
  - kernel/capability.c:__arm64_sys_capget
```
**Symbols:**

```
ffff800010541bf8-ffff800010541c6c: security_capget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int security_capget(struct task_struct *target, kernel_cap_t *effective, kernel_cap_t *inheritable, kernel_cap_t *permitted);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c06f7be4)
Location: security/security.c:784
Inline: False
Direct callers:
  - kernel/capability.c:__se_sys_capget
  - kernel/capability.c:__se_sys_capget
```
**Symbols:**

```
c06f7be4-c06f7c50: security_capget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int security_capget(struct task_struct *target, kernel_cap_t *effective, kernel_cap_t *inheritable, kernel_cap_t *permitted);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c0000000006946b0)
Location: security/security.c:784
Inline: False
Direct callers:
  - kernel/capability.c:__se_sys_capget
  - kernel/capability.c:__se_sys_capget
```
**Symbols:**

```
c0000000006946b0-c000000000694794: security_capget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int security_capget(struct task_struct *target, kernel_cap_t *effective, kernel_cap_t *inheritable, kernel_cap_t *permitted);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffe00039e7a4)
Location: security/security.c:784
Inline: False
Direct callers:
  - kernel/capability.c:__se_sys_capget
  - kernel/capability.c:__se_sys_capget
```
**Symbols:**

```
ffffffe00039e7a4-ffffffe00039e7f8: security_capget (STB_GLOBAL)
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
int security_capget(struct task_struct *target, kernel_cap_t *effective, kernel_cap_t *inheritable, kernel_cap_t *permitted);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8144e9b0)
Location: security/security.c:784
Inline: False
Direct callers:
  - kernel/capability.c:__ia32_sys_capget
  - kernel/capability.c:__ia32_sys_capget
  - kernel/capability.c:__x64_sys_capget
  - kernel/capability.c:__x64_sys_capget
```
**Symbols:**

```
ffffffff8144e9b0-ffffffff8144ea08: security_capget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int security_capget(struct task_struct *target, kernel_cap_t *effective, kernel_cap_t *inheritable, kernel_cap_t *permitted);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8143f400)
Location: security/security.c:784
Inline: False
Direct callers:
  - kernel/capability.c:__ia32_sys_capget
  - kernel/capability.c:__ia32_sys_capget
  - kernel/capability.c:__x64_sys_capget
  - kernel/capability.c:__x64_sys_capget
```
**Symbols:**

```
ffffffff8143f400-ffffffff8143f458: security_capget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int security_capget(struct task_struct *target, kernel_cap_t *effective, kernel_cap_t *inheritable, kernel_cap_t *permitted);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8144aa50)
Location: security/security.c:784
Inline: False
Direct callers:
  - kernel/capability.c:__ia32_sys_capget
  - kernel/capability.c:__ia32_sys_capget
  - kernel/capability.c:__x64_sys_capget
  - kernel/capability.c:__x64_sys_capget
```
**Symbols:**

```
ffffffff8144aa50-ffffffff8144aaa8: security_capget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int security_capget(struct task_struct *target, kernel_cap_t *effective, kernel_cap_t *inheritable, kernel_cap_t *permitted);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81461e20)
Location: security/security.c:784
Inline: False
Direct callers:
  - kernel/capability.c:__ia32_sys_capget
  - kernel/capability.c:__ia32_sys_capget
  - kernel/capability.c:__x64_sys_capget
  - kernel/capability.c:__x64_sys_capget
```
**Symbols:**

```
ffffffff81461e20-ffffffff81461e78: security_capget (STB_GLOBAL)
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct task_struct *target</code> ➡️ <code>const struct task_struct *target</code>
</li>
</ul>
</details>
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
