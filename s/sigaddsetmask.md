# Function: <code>sigaddsetmask</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81091e48)
Location: include/linux/signal.h:173
Inline: True
Inline callers:
  - kernel/signal.c:SyS_sigprocmask
```
```
In kernel/compat.c (ffffffff81110a36)
Location: include/linux/signal.h:173
Inline: True
Inline callers:
  - kernel/compat.c:compat_SyS_sigprocmask
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81094f98)
Location: include/linux/signal.h:188
Inline: True
Inline callers:
  - kernel/signal.c:SyS_sigprocmask
```
```
In kernel/compat.c (ffffffff81118176)
Location: include/linux/signal.h:188
Inline: True
Inline callers:
  - kernel/compat.c:compat_SyS_sigprocmask
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81099f98)
Location: include/linux/signal.h:205
Inline: True
Inline callers:
  - kernel/signal.c:SyS_sigprocmask
```
```
In kernel/compat.c (ffffffff8111f896)
Location: include/linux/signal.h:205
Inline: True
Inline callers:
  - kernel/compat.c:compat_SyS_sigprocmask
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810970fa)
Location: include/linux/signal.h:183
Inline: True
Inline callers:
  - kernel/signal.c:SyS_sigprocmask
```
```
In kernel/compat.c (ffffffff81120c54)
Location: include/linux/signal.h:183
Inline: True
Inline callers:
  - kernel/compat.c:compat_SyS_sigprocmask
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8109ddea)
Location: include/linux/signal.h:198
Inline: True
Inline callers:
  - kernel/signal.c:SyS_sigprocmask
```
```
In kernel/compat.c (ffffffff8112c334)
Location: include/linux/signal.h:198
Inline: True
Inline callers:
  - kernel/compat.c:compat_SyS_sigprocmask
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810a1108)
Location: include/linux/signal.h:200
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_sigprocmask
  - kernel/signal.c:__x64_sys_sigprocmask
```
```
In kernel/compat.c (ffffffff8113a7a3)
Location: include/linux/signal.h:200
Inline: True
Inline callers:
  - kernel/compat.c:__x32_compat_sys_sigprocmask
  - kernel/compat.c:__ia32_compat_sys_sigprocmask
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810a9688)
Location: include/linux/signal.h:210
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_sigprocmask
  - kernel/signal.c:__x64_sys_sigprocmask
```
```
In kernel/compat.c (ffffffff81146013)
Location: include/linux/signal.h:210
Inline: True
Inline callers:
  - kernel/compat.c:__x32_compat_sys_sigprocmask
  - kernel/compat.c:__ia32_compat_sys_sigprocmask
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810abf18)
Location: include/linux/signal.h:210
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_sigprocmask
  - kernel/signal.c:__x64_sys_sigprocmask
```
```
In kernel/compat.c (ffffffff811513e3)
Location: include/linux/signal.h:210
Inline: True
Inline callers:
  - kernel/compat.c:__x32_compat_sys_sigprocmask
  - kernel/compat.c:__ia32_compat_sys_sigprocmask
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b2528)
Location: include/linux/signal.h:210
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_sigprocmask
  - kernel/signal.c:__x64_sys_sigprocmask
```
```
In kernel/compat.c (ffffffff8115d033)
Location: include/linux/signal.h:210
Inline: True
Inline callers:
  - kernel/compat.c:__x32_compat_sys_sigprocmask
  - kernel/compat.c:__ia32_compat_sys_sigprocmask
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810bb088)
Location: include/linux/signal.h:218
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_sigprocmask
  - kernel/signal.c:__x64_sys_sigprocmask
```
```
In kernel/compat.c (ffffffff8116db66)
Location: include/linux/signal.h:218
Inline: True
Inline callers:
  - kernel/compat.c:__x32_compat_sys_sigprocmask
  - kernel/compat.c:__ia32_compat_sys_sigprocmask
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b6338)
Location: include/linux/signal.h:218
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_sigprocmask
  - kernel/signal.c:__x64_sys_sigprocmask
```
```
In kernel/compat.c (ffffffff8116a143)
Location: include/linux/signal.h:218
Inline: True
Inline callers:
  - kernel/compat.c:__x32_compat_sys_sigprocmask
  - kernel/compat.c:__ia32_compat_sys_sigprocmask
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b7f38)
Location: include/linux/signal.h:220
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_sigprocmask
  - kernel/signal.c:__x64_sys_sigprocmask
```
```
In kernel/compat.c (ffffffff8116ae13)
Location: include/linux/signal.h:220
Inline: True
Inline callers:
  - kernel/compat.c:__x32_compat_sys_sigprocmask
  - kernel/compat.c:__ia32_compat_sys_sigprocmask
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810ca3c8)
Location: include/linux/signal.h:220
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_sigprocmask
  - kernel/signal.c:__x64_sys_sigprocmask
```
```
In kernel/compat.c (ffffffff81190a13)
Location: include/linux/signal.h:220
Inline: True
Inline callers:
  - kernel/compat.c:__x64_compat_sys_sigprocmask
  - kernel/compat.c:__ia32_compat_sys_sigprocmask
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810dff52)
Location: include/linux/signal.h:219
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_sigprocmask
  - kernel/signal.c:__x64_sys_sigprocmask
```
```
In kernel/compat.c (ffffffff811c0214)
Location: include/linux/signal.h:219
Inline: True
Inline callers:
  - kernel/compat.c:__ia32_compat_sys_sigprocmask
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff811005e2)
Location: include/linux/signal.h:219
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_sigprocmask
  - kernel/signal.c:__x64_sys_sigprocmask
```
```
In kernel/compat.c (ffffffff812025d4)
Location: include/linux/signal.h:219
Inline: True
Inline callers:
  - kernel/compat.c:__ia32_compat_sys_sigprocmask
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8110c6bb)
Location: include/linux/signal.h:219
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_sigprocmask
  - kernel/signal.c:__x64_sys_sigprocmask
```
```
In kernel/compat.c (ffffffff81217992)
Location: include/linux/signal.h:219
Inline: True
Inline callers:
  - kernel/compat.c:__ia32_compat_sys_sigprocmask
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8111609b)
Location: include/linux/signal.h:220
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_sigprocmask
  - kernel/signal.c:__x64_sys_sigprocmask
```
```
In kernel/compat.c (ffffffff8122f552)
Location: include/linux/signal.h:220
Inline: True
Inline callers:
  - kernel/compat.c:__ia32_compat_sys_sigprocmask
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffff80001010e314)
Location: include/linux/signal.h:210
Inline: True
Inline callers:
  - kernel/signal.c:__arm64_sys_sigprocmask
```
```
In kernel/compat.c (ffff8000101cc6c4)
Location: include/linux/signal.h:210
Inline: True
Inline callers:
  - kernel/compat.c:__arm64_compat_sys_sigprocmask
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (c036a568)
Location: include/linux/signal.h:210
Inline: True
Inline callers:
  - kernel/signal.c:__se_sys_sigprocmask
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (c000000000155760)
Location: include/linux/signal.h:210
Inline: True
Inline callers:
  - kernel/signal.c:__se_sys_sigprocmask
```
```
In kernel/compat.c (c000000000236c80)
Location: include/linux/signal.h:210
Inline: True
Inline callers:
  - kernel/compat.c:__se_compat_sys_sigprocmask
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
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810ac898)
Location: include/linux/signal.h:210
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_sigprocmask
  - kernel/signal.c:__x64_sys_sigprocmask
```
```
In kernel/compat.c (ffffffff81155653)
Location: include/linux/signal.h:210
Inline: True
Inline callers:
  - kernel/compat.c:__x32_compat_sys_sigprocmask
  - kernel/compat.c:__ia32_compat_sys_sigprocmask
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8109b218)
Location: include/linux/signal.h:210
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_sigprocmask
  - kernel/signal.c:__x64_sys_sigprocmask
```
```
In kernel/compat.c (ffffffff81148973)
Location: include/linux/signal.h:210
Inline: True
Inline callers:
  - kernel/compat.c:__x32_compat_sys_sigprocmask
  - kernel/compat.c:__ia32_compat_sys_sigprocmask
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810abdf8)
Location: include/linux/signal.h:210
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_sigprocmask
  - kernel/signal.c:__x64_sys_sigprocmask
```
```
In kernel/compat.c (ffffffff81153423)
Location: include/linux/signal.h:210
Inline: True
Inline callers:
  - kernel/compat.c:__x32_compat_sys_sigprocmask
  - kernel/compat.c:__ia32_compat_sys_sigprocmask
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b3f68)
Location: include/linux/signal.h:210
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_sigprocmask
  - kernel/signal.c:__x64_sys_sigprocmask
```
```
In kernel/compat.c (ffffffff81160323)
Location: include/linux/signal.h:210
Inline: True
Inline callers:
  - kernel/compat.c:__x32_compat_sys_sigprocmask
  - kernel/compat.c:__ia32_compat_sys_sigprocmask
```
</details>
</li>
</ul>

## Differences
