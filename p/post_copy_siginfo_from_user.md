# Function: <code>post_copy_siginfo_from_user</code>

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
In <code>4.18</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/signal.c (ffffffff810aa7e1)
Location: kernel/signal.c:3064
Inline: True
Inline callers:
  - kernel/signal.c:copy_siginfo_from_user
  - kernel/signal.c:__copy_siginfo_from_user
Direct callers:
  - kernel/signal.c:copy_siginfo_from_user
  - kernel/signal.c:__copy_siginfo_from_user
```
**Symbols:**

```
ffffffff810a4930-ffffffff810a49b2: post_copy_siginfo_from_user.isra.34.part.35 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/signal.c (ffffffff810af871)
Location: kernel/signal.c:3193
Inline: True
Inline callers:
  - kernel/signal.c:copy_siginfo_from_user
  - kernel/signal.c:__copy_siginfo_from_user
Direct callers:
  - kernel/signal.c:copy_siginfo_from_user
  - kernel/signal.c:__copy_siginfo_from_user
```
**Symbols:**

```
ffffffff810a95b0-ffffffff810a9622: post_copy_siginfo_from_user.isra.0.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/signal.c (ffffffff810b5e91)
Location: kernel/signal.c:3198
Inline: True
Inline callers:
  - kernel/signal.c:copy_siginfo_from_user
  - kernel/signal.c:__copy_siginfo_from_user
Direct callers:
  - kernel/signal.c:copy_siginfo_from_user
  - kernel/signal.c:__copy_siginfo_from_user
```
**Symbols:**

```
ffffffff810afba0-ffffffff810afc12: post_copy_siginfo_from_user.isra.0.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810be3b4)
Location: kernel/signal.c:3216
Inline: True
Inline callers:
  - kernel/signal.c:copy_siginfo_from_user
  - kernel/signal.c:copy_siginfo_from_user
  - kernel/signal.c:__copy_siginfo_from_user
  - kernel/signal.c:__copy_siginfo_from_user
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b96b4)
Location: kernel/signal.c:3236
Inline: True
Inline callers:
  - kernel/signal.c:copy_siginfo_from_user
  - kernel/signal.c:copy_siginfo_from_user
  - kernel/signal.c:__copy_siginfo_from_user
  - kernel/signal.c:__copy_siginfo_from_user
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810bae84)
Location: kernel/signal.c:3264
Inline: True
Inline callers:
  - kernel/signal.c:copy_siginfo_from_user
  - kernel/signal.c:copy_siginfo_from_user
  - kernel/signal.c:__copy_siginfo_from_user
  - kernel/signal.c:__copy_siginfo_from_user
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810cd774)
Location: kernel/signal.c:3352
Inline: True
Inline callers:
  - kernel/signal.c:copy_siginfo_from_user
  - kernel/signal.c:copy_siginfo_from_user
  - kernel/signal.c:__copy_siginfo_from_user
  - kernel/signal.c:__copy_siginfo_from_user
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/signal.c (ffffffff810dde30)
Location: kernel/signal.c:3332
Inline: True
Direct callers:
  - kernel/signal.c:__ia32_sys_rt_tgsigqueueinfo
  - kernel/signal.c:__x64_sys_rt_tgsigqueueinfo
  - kernel/signal.c:__ia32_sys_rt_sigqueueinfo
  - kernel/signal.c:__x64_sys_rt_sigqueueinfo
  - kernel/signal.c:__do_sys_pidfd_send_signal
```
**Symbols:**

```
ffffffff810dde30-ffffffff810ddf5d: post_copy_siginfo_from_user.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/signal.c (ffffffff810fe300)
Location: kernel/signal.c:3334
Inline: True
Direct callers:
  - kernel/signal.c:__ia32_sys_rt_tgsigqueueinfo
  - kernel/signal.c:__x64_sys_rt_tgsigqueueinfo
  - kernel/signal.c:__ia32_sys_rt_sigqueueinfo
  - kernel/signal.c:__x64_sys_rt_sigqueueinfo
  - kernel/signal.c:__do_sys_pidfd_send_signal
```
**Symbols:**

```
ffffffff810fe300-ffffffff810fe42d: post_copy_siginfo_from_user.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/signal.c (ffffffff8110a370)
Location: kernel/signal.c:3358
Inline: True
Direct callers:
  - kernel/signal.c:__ia32_sys_rt_tgsigqueueinfo
  - kernel/signal.c:__x64_sys_rt_tgsigqueueinfo
  - kernel/signal.c:__ia32_sys_rt_sigqueueinfo
  - kernel/signal.c:__x64_sys_rt_sigqueueinfo
  - kernel/signal.c:__do_sys_pidfd_send_signal
```
**Symbols:**

```
ffffffff8110a370-ffffffff8110a49d: post_copy_siginfo_from_user.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/signal.c (ffffffff81113d10)
Location: kernel/signal.c:3369
Inline: True
Direct callers:
  - kernel/signal.c:__ia32_sys_rt_tgsigqueueinfo
  - kernel/signal.c:__x64_sys_rt_tgsigqueueinfo
  - kernel/signal.c:__ia32_sys_rt_sigqueueinfo
  - kernel/signal.c:__x64_sys_rt_sigqueueinfo
  - kernel/signal.c:__do_sys_pidfd_send_signal
```
**Symbols:**

```
ffffffff81113d10-ffffffff81113e3d: post_copy_siginfo_from_user.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/signal.c (ffff8000101121d0)
Location: kernel/signal.c:3198
Inline: True
Inline callers:
  - kernel/signal.c:copy_siginfo_from_user
  - kernel/signal.c:__copy_siginfo_from_user
Direct callers:
  - kernel/signal.c:copy_siginfo_from_user
  - kernel/signal.c:__copy_siginfo_from_user
```
**Symbols:**

```
ffff80001010c450-ffff80001010c638: post_copy_siginfo_from_user.isra.0.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/signal.c (c03692d0)
Location: kernel/signal.c:3198
Inline: True
Inline callers:
  - kernel/signal.c:copy_siginfo_from_user
  - kernel/signal.c:__copy_siginfo_from_user
Direct callers:
  - kernel/signal.c:copy_siginfo_from_user
  - kernel/signal.c:__copy_siginfo_from_user
```
**Symbols:**

```
c03645b8-c036468c: post_copy_siginfo_from_user.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/signal.c (c000000000159c80)
Location: kernel/signal.c:3198
Inline: True
Inline callers:
  - kernel/signal.c:copy_siginfo_from_user
  - kernel/signal.c:__copy_siginfo_from_user
Direct callers:
  - kernel/signal.c:copy_siginfo_from_user
  - kernel/signal.c:__copy_siginfo_from_user
```
**Symbols:**

```
c000000000152160-c000000000152210: post_copy_siginfo_from_user.isra.0.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/signal.c (ffffffe0000d1312)
Location: kernel/signal.c:3198
Inline: True
Inline callers:
  - kernel/signal.c:copy_siginfo_from_user
  - kernel/signal.c:__copy_siginfo_from_user
Direct callers:
  - kernel/signal.c:copy_siginfo_from_user
  - kernel/signal.c:__copy_siginfo_from_user
```
**Symbols:**

```
ffffffe0000cd586-ffffffe0000cd5ec: post_copy_siginfo_from_user.isra.0.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/signal.c (ffffffff810b0201)
Location: kernel/signal.c:3198
Inline: True
Inline callers:
  - kernel/signal.c:copy_siginfo_from_user
  - kernel/signal.c:__copy_siginfo_from_user
Direct callers:
  - kernel/signal.c:copy_siginfo_from_user
  - kernel/signal.c:__copy_siginfo_from_user
```
**Symbols:**

```
ffffffff810a9f10-ffffffff810a9f82: post_copy_siginfo_from_user.isra.0.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/signal.c (ffffffff8109eb21)
Location: kernel/signal.c:3198
Inline: True
Inline callers:
  - kernel/signal.c:copy_siginfo_from_user
  - kernel/signal.c:__copy_siginfo_from_user
Direct callers:
  - kernel/signal.c:copy_siginfo_from_user
  - kernel/signal.c:__copy_siginfo_from_user
```
**Symbols:**

```
ffffffff810988c0-ffffffff81098932: post_copy_siginfo_from_user.isra.0.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/signal.c (ffffffff810af761)
Location: kernel/signal.c:3198
Inline: True
Inline callers:
  - kernel/signal.c:copy_siginfo_from_user
  - kernel/signal.c:__copy_siginfo_from_user
Direct callers:
  - kernel/signal.c:copy_siginfo_from_user
  - kernel/signal.c:__copy_siginfo_from_user
```
**Symbols:**

```
ffffffff810a9470-ffffffff810a94e2: post_copy_siginfo_from_user.isra.0.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/signal.c (ffffffff810b7a31)
Location: kernel/signal.c:3198
Inline: True
Inline callers:
  - kernel/signal.c:copy_siginfo_from_user
  - kernel/signal.c:__copy_siginfo_from_user
Direct callers:
  - kernel/signal.c:copy_siginfo_from_user
  - kernel/signal.c:__copy_siginfo_from_user
```
**Symbols:**

```
ffffffff810b1790-ffffffff810b1802: post_copy_siginfo_from_user.isra.0.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
