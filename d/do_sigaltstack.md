# Function: <code>do_sigaltstack</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int do_sigaltstack(const stack_t *uss, stack_t *uoss, long unsigned int sp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8108d1b0)
Location: kernel/signal.c:3091
Inline: False
Direct callers:
  - kernel/signal.c:SyS_sigaltstack
  - kernel/signal.c:restore_altstack
  - kernel/signal.c:compat_restore_altstack
```
**Symbols:**

```
ffffffff8108d1b0-ffffffff8108d33b: do_sigaltstack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int do_sigaltstack(const stack_t *uss, stack_t *uoss, long unsigned int sp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81090650)
Location: kernel/signal.c:3091
Inline: False
Direct callers:
  - kernel/signal.c:compat_restore_altstack
  - kernel/signal.c:restore_altstack
  - kernel/signal.c:SyS_sigaltstack
```
**Symbols:**

```
ffffffff81090650-ffffffff810907fc: do_sigaltstack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int do_sigaltstack(const stack_t *uss, stack_t *uoss, long unsigned int sp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810955d0)
Location: kernel/signal.c:3111
Inline: False
Direct callers:
  - kernel/signal.c:compat_restore_altstack
  - kernel/signal.c:restore_altstack
  - kernel/signal.c:SyS_sigaltstack
```
**Symbols:**

```
ffffffff810955d0-ffffffff8109577c: do_sigaltstack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int do_sigaltstack(const stack_t *ss, stack_t *oss, long unsigned int sp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81092320)
Location: kernel/signal.c:3166
Inline: False
Direct callers:
  - kernel/signal.c:compat_restore_altstack
  - kernel/signal.c:restore_altstack
  - kernel/signal.c:SyS_sigaltstack
  - kernel/signal.c:SyS_sigaltstack
  - kernel/signal.c:SyS_sigaltstack
  - kernel/signal.c:SyS_sigaltstack
```
**Symbols:**

```
ffffffff81092320-ffffffff81092454: do_sigaltstack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int do_sigaltstack(const stack_t *ss, stack_t *oss, long unsigned int sp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810991b0)
Location: kernel/signal.c:3187
Inline: False
Direct callers:
  - kernel/signal.c:compat_restore_altstack
  - kernel/signal.c:restore_altstack
  - kernel/signal.c:SyS_sigaltstack
  - kernel/signal.c:SyS_sigaltstack
  - kernel/signal.c:SyS_sigaltstack
  - kernel/signal.c:SyS_sigaltstack
```
**Symbols:**

```
ffffffff810991b0-ffffffff810992e4: do_sigaltstack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int do_sigaltstack(const stack_t *ss, stack_t *oss, long unsigned int sp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8109c930)
Location: kernel/signal.c:3420
Inline: False
Direct callers:
  - kernel/signal.c:do_compat_sigaltstack
  - kernel/signal.c:restore_altstack
  - kernel/signal.c:__ia32_sys_sigaltstack
  - kernel/signal.c:__ia32_sys_sigaltstack
  - kernel/signal.c:__ia32_sys_sigaltstack
  - kernel/signal.c:__ia32_sys_sigaltstack
  - kernel/signal.c:__x64_sys_sigaltstack
  - kernel/signal.c:__x64_sys_sigaltstack
  - kernel/signal.c:__x64_sys_sigaltstack
  - kernel/signal.c:__x64_sys_sigaltstack
```
**Symbols:**

```
ffffffff8109c930-ffffffff8109ca67: do_sigaltstack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/signal.c (ffffffff810a4cf0)
Location: kernel/signal.c:3744
Inline: True
Direct callers:
  - kernel/signal.c:do_compat_sigaltstack
  - kernel/signal.c:restore_altstack
  - kernel/signal.c:__ia32_sys_sigaltstack
  - kernel/signal.c:__ia32_sys_sigaltstack
  - kernel/signal.c:__ia32_sys_sigaltstack
  - kernel/signal.c:__ia32_sys_sigaltstack
  - kernel/signal.c:__x64_sys_sigaltstack
  - kernel/signal.c:__x64_sys_sigaltstack
  - kernel/signal.c:__x64_sys_sigaltstack
  - kernel/signal.c:__x64_sys_sigaltstack
```
**Symbols:**

```
ffffffff810a4cf0-ffffffff810a4e27: do_sigaltstack.constprop.53 (STB_LOCAL)
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
In kernel/signal.c (ffffffff810a99a0)
Location: kernel/signal.c:3992
Inline: True
Direct callers:
  - kernel/signal.c:do_compat_sigaltstack
  - kernel/signal.c:restore_altstack
  - kernel/signal.c:__ia32_sys_sigaltstack
  - kernel/signal.c:__ia32_sys_sigaltstack
  - kernel/signal.c:__ia32_sys_sigaltstack
  - kernel/signal.c:__ia32_sys_sigaltstack
  - kernel/signal.c:__x64_sys_sigaltstack
  - kernel/signal.c:__x64_sys_sigaltstack
  - kernel/signal.c:__x64_sys_sigaltstack
  - kernel/signal.c:__x64_sys_sigaltstack
```
**Symbols:**

```
ffffffff810a99a0-ffffffff810a9ae3: do_sigaltstack.constprop.0 (STB_LOCAL)
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
In kernel/signal.c (ffffffff810aff90)
Location: kernel/signal.c:4000
Inline: True
Direct callers:
  - kernel/signal.c:do_compat_sigaltstack
  - kernel/signal.c:restore_altstack
  - kernel/signal.c:__ia32_sys_sigaltstack
  - kernel/signal.c:__ia32_sys_sigaltstack
  - kernel/signal.c:__ia32_sys_sigaltstack
  - kernel/signal.c:__ia32_sys_sigaltstack
  - kernel/signal.c:__x64_sys_sigaltstack
  - kernel/signal.c:__x64_sys_sigaltstack
  - kernel/signal.c:__x64_sys_sigaltstack
  - kernel/signal.c:__x64_sys_sigaltstack
```
**Symbols:**

```
ffffffff810aff90-ffffffff810b00c9: do_sigaltstack.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/signal.c (ffffffff810bf325)
Location: kernel/signal.c:4018
Inline: True
Inline callers:
  - kernel/signal.c:restore_altstack
Direct callers:
  - kernel/signal.c:do_compat_sigaltstack
  - kernel/signal.c:__ia32_sys_sigaltstack
  - kernel/signal.c:__ia32_sys_sigaltstack
  - kernel/signal.c:__ia32_sys_sigaltstack
  - kernel/signal.c:__ia32_sys_sigaltstack
  - kernel/signal.c:__x64_sys_sigaltstack
  - kernel/signal.c:__x64_sys_sigaltstack
  - kernel/signal.c:__x64_sys_sigaltstack
  - kernel/signal.c:__x64_sys_sigaltstack
```
**Symbols:**

```
ffffffff810b7b50-ffffffff810b7c87: do_sigaltstack.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/signal.c (ffffffff810ba545)
Location: kernel/signal.c:4055
Inline: True
Inline callers:
  - kernel/signal.c:restore_altstack
Direct callers:
  - kernel/signal.c:do_compat_sigaltstack
  - kernel/signal.c:__ia32_sys_sigaltstack
  - kernel/signal.c:__ia32_sys_sigaltstack
  - kernel/signal.c:__ia32_sys_sigaltstack
  - kernel/signal.c:__ia32_sys_sigaltstack
  - kernel/signal.c:__x64_sys_sigaltstack
  - kernel/signal.c:__x64_sys_sigaltstack
  - kernel/signal.c:__x64_sys_sigaltstack
  - kernel/signal.c:__x64_sys_sigaltstack
```
**Symbols:**

```
ffffffff810b2e00-ffffffff810b2f37: do_sigaltstack.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/signal.c (ffffffff810bbe83)
Location: kernel/signal.c:4077
Inline: True
Inline callers:
  - kernel/signal.c:restore_altstack
Direct callers:
  - kernel/signal.c:do_compat_sigaltstack
  - kernel/signal.c:__ia32_sys_sigaltstack
  - kernel/signal.c:__ia32_sys_sigaltstack
  - kernel/signal.c:__ia32_sys_sigaltstack
  - kernel/signal.c:__ia32_sys_sigaltstack
  - kernel/signal.c:__x64_sys_sigaltstack
  - kernel/signal.c:__x64_sys_sigaltstack
  - kernel/signal.c:__x64_sys_sigaltstack
  - kernel/signal.c:__x64_sys_sigaltstack
```
**Symbols:**

```
ffffffff810b4430-ffffffff810b456a: do_sigaltstack.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/signal.c (ffffffff810ce8e3)
Location: kernel/signal.c:4169
Inline: True
Inline callers:
  - kernel/signal.c:restore_altstack
Direct callers:
  - kernel/signal.c:do_compat_sigaltstack
  - kernel/signal.c:__ia32_sys_sigaltstack
  - kernel/signal.c:__ia32_sys_sigaltstack
  - kernel/signal.c:__ia32_sys_sigaltstack
  - kernel/signal.c:__ia32_sys_sigaltstack
  - kernel/signal.c:__x64_sys_sigaltstack
  - kernel/signal.c:__x64_sys_sigaltstack
  - kernel/signal.c:__x64_sys_sigaltstack
  - kernel/signal.c:__x64_sys_sigaltstack
```
**Symbols:**

```
ffffffff810c6600-ffffffff810c673a: do_sigaltstack.constprop.0 (STB_LOCAL)
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
In kernel/signal.c (ffffffff810de050)
Location: kernel/signal.c:4169
Inline: True
Direct callers:
  - kernel/signal.c:do_compat_sigaltstack
  - kernel/signal.c:restore_altstack
  - kernel/signal.c:__ia32_sys_sigaltstack
  - kernel/signal.c:__ia32_sys_sigaltstack
  - kernel/signal.c:__x64_sys_sigaltstack
  - kernel/signal.c:__x64_sys_sigaltstack
```
**Symbols:**

```
ffffffff810de050-ffffffff810de236: do_sigaltstack.constprop.0 (STB_LOCAL)
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
In kernel/signal.c (ffffffff810fe4d0)
Location: kernel/signal.c:4171
Inline: True
Direct callers:
  - kernel/signal.c:do_compat_sigaltstack
  - kernel/signal.c:restore_altstack
  - kernel/signal.c:__ia32_sys_sigaltstack
  - kernel/signal.c:__ia32_sys_sigaltstack
  - kernel/signal.c:__x64_sys_sigaltstack
  - kernel/signal.c:__x64_sys_sigaltstack
```
**Symbols:**

```
ffffffff810fe4d0-ffffffff810fe6b6: do_sigaltstack.constprop.0 (STB_LOCAL)
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
In kernel/signal.c (ffffffff8110a540)
Location: kernel/signal.c:4195
Inline: True
Direct callers:
  - kernel/signal.c:do_compat_sigaltstack
  - kernel/signal.c:restore_altstack
  - kernel/signal.c:__ia32_sys_sigaltstack
  - kernel/signal.c:__ia32_sys_sigaltstack
  - kernel/signal.c:__x64_sys_sigaltstack
  - kernel/signal.c:__x64_sys_sigaltstack
```
**Symbols:**

```
ffffffff8110a540-ffffffff8110a726: do_sigaltstack.constprop.0 (STB_LOCAL)
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
In kernel/signal.c (ffffffff81113ee0)
Location: kernel/signal.c:4206
Inline: True
Direct callers:
  - kernel/signal.c:do_compat_sigaltstack
  - kernel/signal.c:restore_altstack
  - kernel/signal.c:__ia32_sys_sigaltstack
  - kernel/signal.c:__ia32_sys_sigaltstack
  - kernel/signal.c:__x64_sys_sigaltstack
  - kernel/signal.c:__x64_sys_sigaltstack
```
**Symbols:**

```
ffffffff81113ee0-ffffffff811140c6: do_sigaltstack.constprop.0 (STB_LOCAL)
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
int do_sigaltstack(const stack_t *ss, stack_t *oss, long unsigned int sp, size_t min_ss_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffff80001010abd8)
Location: kernel/signal.c:4000
Inline: False
Direct callers:
  - kernel/signal.c:do_compat_sigaltstack
  - kernel/signal.c:restore_altstack
  - kernel/signal.c:__arm64_sys_sigaltstack
```
**Symbols:**

```
ffff80001010abd8-ffff80001010ad08: do_sigaltstack (STB_LOCAL)
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
In kernel/signal.c (c0364374)
Location: kernel/signal.c:4000
Inline: True
Direct callers:
  - kernel/signal.c:restore_altstack
  - kernel/signal.c:__se_sys_sigaltstack
  - kernel/signal.c:__se_sys_sigaltstack
```
**Symbols:**

```
c0364374-c03644b0: do_sigaltstack.constprop.0 (STB_LOCAL)
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
In kernel/signal.c (c0000000001527a0)
Location: kernel/signal.c:4000
Inline: True
Direct callers:
  - kernel/signal.c:do_compat_sigaltstack
  - kernel/signal.c:restore_altstack
  - kernel/signal.c:__se_sys_sigaltstack
  - kernel/signal.c:__se_sys_sigaltstack
```
**Symbols:**

```
c0000000001527a0-c0000000001528f8: do_sigaltstack.constprop.0 (STB_LOCAL)
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
In kernel/signal.c (ffffffe0000cd9f4)
Location: kernel/signal.c:4000
Inline: True
Direct callers:
  - kernel/signal.c:restore_altstack
  - kernel/signal.c:__se_sys_sigaltstack
  - kernel/signal.c:__se_sys_sigaltstack
```
**Symbols:**

```
ffffffe0000cd9f4-ffffffe0000cdaea: do_sigaltstack.constprop.0 (STB_LOCAL)
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
In kernel/signal.c (ffffffff810aa300)
Location: kernel/signal.c:4000
Inline: True
Direct callers:
  - kernel/signal.c:do_compat_sigaltstack
  - kernel/signal.c:restore_altstack
  - kernel/signal.c:__ia32_sys_sigaltstack
  - kernel/signal.c:__ia32_sys_sigaltstack
  - kernel/signal.c:__ia32_sys_sigaltstack
  - kernel/signal.c:__ia32_sys_sigaltstack
  - kernel/signal.c:__x64_sys_sigaltstack
  - kernel/signal.c:__x64_sys_sigaltstack
  - kernel/signal.c:__x64_sys_sigaltstack
  - kernel/signal.c:__x64_sys_sigaltstack
```
**Symbols:**

```
ffffffff810aa300-ffffffff810aa439: do_sigaltstack.constprop.0 (STB_LOCAL)
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
In kernel/signal.c (ffffffff81098cb0)
Location: kernel/signal.c:4000
Inline: True
Direct callers:
  - kernel/signal.c:do_compat_sigaltstack
  - kernel/signal.c:restore_altstack
  - kernel/signal.c:__ia32_sys_sigaltstack
  - kernel/signal.c:__ia32_sys_sigaltstack
  - kernel/signal.c:__ia32_sys_sigaltstack
  - kernel/signal.c:__ia32_sys_sigaltstack
  - kernel/signal.c:__x64_sys_sigaltstack
  - kernel/signal.c:__x64_sys_sigaltstack
  - kernel/signal.c:__x64_sys_sigaltstack
  - kernel/signal.c:__x64_sys_sigaltstack
```
**Symbols:**

```
ffffffff81098cb0-ffffffff81098de9: do_sigaltstack.constprop.0 (STB_LOCAL)
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
In kernel/signal.c (ffffffff810a9860)
Location: kernel/signal.c:4000
Inline: True
Direct callers:
  - kernel/signal.c:do_compat_sigaltstack
  - kernel/signal.c:restore_altstack
  - kernel/signal.c:__ia32_sys_sigaltstack
  - kernel/signal.c:__ia32_sys_sigaltstack
  - kernel/signal.c:__ia32_sys_sigaltstack
  - kernel/signal.c:__ia32_sys_sigaltstack
  - kernel/signal.c:__x64_sys_sigaltstack
  - kernel/signal.c:__x64_sys_sigaltstack
  - kernel/signal.c:__x64_sys_sigaltstack
  - kernel/signal.c:__x64_sys_sigaltstack
```
**Symbols:**

```
ffffffff810a9860-ffffffff810a9999: do_sigaltstack.constprop.0 (STB_LOCAL)
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
In kernel/signal.c (ffffffff810b1cb0)
Location: kernel/signal.c:4000
Inline: True
Direct callers:
  - kernel/signal.c:do_compat_sigaltstack
  - kernel/signal.c:restore_altstack
  - kernel/signal.c:__ia32_sys_sigaltstack
  - kernel/signal.c:__ia32_sys_sigaltstack
  - kernel/signal.c:__ia32_sys_sigaltstack
  - kernel/signal.c:__ia32_sys_sigaltstack
  - kernel/signal.c:__x64_sys_sigaltstack
  - kernel/signal.c:__x64_sys_sigaltstack
  - kernel/signal.c:__x64_sys_sigaltstack
  - kernel/signal.c:__x64_sys_sigaltstack
```
**Symbols:**

```
ffffffff810b1cb0-ffffffff810b1de9: do_sigaltstack.constprop.0 (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const stack_t *ss</code>
</li>
<li>
<b>Param added. </b>
<code>stack_t *oss</code>
</li>
<li>
<b>Param removed. </b>
<code>const stack_t *uss</code>
</li>
<li>
<b>Param removed. </b>
<code>stack_t *uoss</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
</ul>
