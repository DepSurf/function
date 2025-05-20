# Function: <code>__audit_log_capset</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __audit_log_capset(const struct cred *new, const struct cred *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff811297c0)
Location: kernel/auditsc.c:2341
Inline: False
Direct callers:
  - kernel/capability.c:SyS_capset
```
**Symbols:**

```
ffffffff811297c0-ffffffff81129812: __audit_log_capset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __audit_log_capset(const struct cred *new, const struct cred *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81131970)
Location: kernel/auditsc.c:2345
Inline: False
Direct callers:
  - kernel/capability.c:SyS_capset
```
**Symbols:**

```
ffffffff81131970-ffffffff811319c2: __audit_log_capset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __audit_log_capset(const struct cred *new, const struct cred *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff8113b6f0)
Location: kernel/auditsc.c:2353
Inline: False
Direct callers:
  - kernel/capability.c:SyS_capset
```
**Symbols:**

```
ffffffff8113b6f0-ffffffff8113b742: __audit_log_capset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __audit_log_capset(const struct cred *new, const struct cred *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff8113cd50)
Location: kernel/auditsc.c:2365
Inline: False
Direct callers:
  - kernel/capability.c:SyS_capset
```
**Symbols:**

```
ffffffff8113cd50-ffffffff8113cdad: __audit_log_capset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __audit_log_capset(const struct cred *new, const struct cred *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81149ad0)
Location: kernel/auditsc.c:2388
Inline: False
Direct callers:
  - kernel/capability.c:SyS_capset
```
**Symbols:**

```
ffffffff81149ad0-ffffffff81149b2d: __audit_log_capset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __audit_log_capset(const struct cred *new, const struct cred *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff811583d0)
Location: kernel/auditsc.c:2395
Inline: False
Direct callers:
  - kernel/capability.c:__ia32_sys_capset
  - kernel/capability.c:__x64_sys_capset
```
**Symbols:**

```
ffffffff811583d0-ffffffff8115842d: __audit_log_capset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __audit_log_capset(const struct cred *new, const struct cred *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff811653d0)
Location: kernel/auditsc.c:2380
Inline: False
Direct callers:
  - kernel/capability.c:__ia32_sys_capset
  - kernel/capability.c:__x64_sys_capset
```
**Symbols:**

```
ffffffff811653d0-ffffffff8116542d: __audit_log_capset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __audit_log_capset(const struct cred *new, const struct cred *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81171e70)
Location: kernel/auditsc.c:2484
Inline: False
Direct callers:
  - kernel/capability.c:__ia32_sys_capset
  - kernel/capability.c:__x64_sys_capset
```
**Symbols:**

```
ffffffff81171e70-ffffffff81171ecd: __audit_log_capset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __audit_log_capset(const struct cred *new, const struct cred *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff8117dd20)
Location: kernel/auditsc.c:2484
Inline: False
Direct callers:
  - kernel/capability.c:__ia32_sys_capset
  - kernel/capability.c:__x64_sys_capset
```
**Symbols:**

```
ffffffff8117dd20-ffffffff8117dd7d: __audit_log_capset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __audit_log_capset(const struct cred *new, const struct cred *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81190fd0)
Location: kernel/auditsc.c:2536
Inline: False
Direct callers:
  - kernel/capability.c:__do_sys_capset
```
**Symbols:**

```
ffffffff81190fd0-ffffffff8119102d: __audit_log_capset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __audit_log_capset(const struct cred *new, const struct cred *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff8118e1f0)
Location: kernel/auditsc.c:2553
Inline: False
Direct callers:
  - kernel/capability.c:__do_sys_capset
```
**Symbols:**

```
ffffffff8118e1f0-ffffffff8118e24d: __audit_log_capset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __audit_log_capset(const struct cred *new, const struct cred *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff8118f170)
Location: kernel/auditsc.c:2551
Inline: False
Direct callers:
  - kernel/capability.c:__do_sys_capset
```
**Symbols:**

```
ffffffff8118f170-ffffffff8118f1cd: __audit_log_capset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __audit_log_capset(const struct cred *new, const struct cred *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff811b8050)
Location: kernel/auditsc.c:2567
Inline: False
Direct callers:
  - kernel/capability.c:__do_sys_capset
```
**Symbols:**

```
ffffffff811b8050-ffffffff811b80ad: __audit_log_capset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __audit_log_capset(const struct cred *new, const struct cred *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff811eaf60)
Location: kernel/auditsc.c:2839
Inline: False
Direct callers:
  - kernel/capability.c:__do_sys_capset
```
**Symbols:**

```
ffffffff811eaf60-ffffffff811eafc7: __audit_log_capset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __audit_log_capset(const struct cred *new, const struct cred *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81231280)
Location: kernel/auditsc.c:2817
Inline: False
Direct callers:
  - kernel/capability.c:__do_sys_capset
```
**Symbols:**

```
ffffffff81231280-ffffffff812312e7: __audit_log_capset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __audit_log_capset(const struct cred *new, const struct cred *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81247e20)
Location: kernel/auditsc.c:2816
Inline: False
Direct callers:
  - kernel/capability.c:__do_sys_capset
```
**Symbols:**

```
ffffffff81247e20-ffffffff81247e87: __audit_log_capset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __audit_log_capset(const struct cred *new, const struct cred *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81261c80)
Location: kernel/auditsc.c:2806
Inline: False
Direct callers:
  - kernel/capability.c:__do_sys_capset
```
**Symbols:**

```
ffffffff81261c80-ffffffff81261ce7: __audit_log_capset (STB_GLOBAL)
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
void __audit_log_capset(const struct cred *new, const struct cred *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffff8000101f2b60)
Location: kernel/auditsc.c:2484
Inline: False
Direct callers:
  - kernel/capability.c:__arm64_sys_capset
```
**Symbols:**

```
ffff8000101f2b60-ffff8000101f2bc0: __audit_log_capset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __audit_log_capset(const struct cred *new, const struct cred *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (c04330cc)
Location: kernel/auditsc.c:2484
Inline: False
Direct callers:
  - kernel/capability.c:__se_sys_capset
```
**Symbols:**

```
c04330cc-c0433140: __audit_log_capset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __audit_log_capset(const struct cred *new, const struct cred *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (c000000000267490)
Location: kernel/auditsc.c:2484
Inline: False
Direct callers:
  - kernel/capability.c:__se_sys_capset
```
**Symbols:**

```
c000000000267490-c0000000002674d4: __audit_log_capset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __audit_log_capset(const struct cred *new, const struct cred *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffe00016617e)
Location: kernel/auditsc.c:2484
Inline: False
Direct callers:
  - kernel/capability.c:__se_sys_capset
```
**Symbols:**

```
ffffffe00016617e-ffffffe0001661e2: __audit_log_capset (STB_GLOBAL)
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
void __audit_log_capset(const struct cred *new, const struct cred *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81176340)
Location: kernel/auditsc.c:2484
Inline: False
Direct callers:
  - kernel/capability.c:__ia32_sys_capset
  - kernel/capability.c:__x64_sys_capset
```
**Symbols:**

```
ffffffff81176340-ffffffff8117639d: __audit_log_capset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __audit_log_capset(const struct cred *new, const struct cred *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff811694e0)
Location: kernel/auditsc.c:2484
Inline: False
Direct callers:
  - kernel/capability.c:__ia32_sys_capset
  - kernel/capability.c:__x64_sys_capset
```
**Symbols:**

```
ffffffff811694e0-ffffffff8116953d: __audit_log_capset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __audit_log_capset(const struct cred *new, const struct cred *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81174110)
Location: kernel/auditsc.c:2484
Inline: False
Direct callers:
  - kernel/capability.c:__ia32_sys_capset
  - kernel/capability.c:__x64_sys_capset
```
**Symbols:**

```
ffffffff81174110-ffffffff8117416d: __audit_log_capset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __audit_log_capset(const struct cred *new, const struct cred *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff811819f0)
Location: kernel/auditsc.c:2484
Inline: False
Direct callers:
  - kernel/capability.c:__ia32_sys_capset
  - kernel/capability.c:__x64_sys_capset
```
**Symbols:**

```
ffffffff811819f0-ffffffff81181a4d: __audit_log_capset (STB_GLOBAL)
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
