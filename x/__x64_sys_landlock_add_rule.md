# Function: <code>__x64_sys_landlock_add_rule</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int __x64_sys_landlock_add_rule(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff81537590)
Location: kernel/sys_ni.c:272
Inline: False
```
**Symbols:**

```
ffffffff81537590-ffffffff815376a8: __x64_sys_landlock_add_rule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
long int __x64_sys_landlock_add_rule(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sys_ni.c (0)
Location: kernel/sys_ni.c:272
Inline: False
```
**Symbols:**

```
ffffffff81cd6b3a-ffffffff81cd6b4f: __x64_sys_landlock_add_rule.cold (STB_LOCAL)
ffffffff81595d40-ffffffff81595e75: __x64_sys_landlock_add_rule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
long int __x64_sys_landlock_add_rule(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sys_ni.c (0)
Location: kernel/sys_ni.c:273
Inline: False
```
**Symbols:**

```
ffffffff81e89a7d-ffffffff81e89a91: __x64_sys_landlock_add_rule.cold (STB_LOCAL)
ffffffff81638060-ffffffff816381cb: __x64_sys_landlock_add_rule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
long int __x64_sys_landlock_add_rule(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sys_ni.c (0)
Location: kernel/sys_ni.c:273
Inline: False
```
**Symbols:**

```
ffffffff82074ec0-ffffffff82074ed4: __x64_sys_landlock_add_rule.cold (STB_LOCAL)
ffffffff816ef490-ffffffff816ef5fb: __x64_sys_landlock_add_rule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
long int __x64_sys_landlock_add_rule(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sys_ni.c (0)
Location: kernel/sys_ni.c:169
Inline: False
```
**Symbols:**

```
ffffffff820f4a6b-ffffffff820f4a7f: __x64_sys_landlock_add_rule.cold (STB_LOCAL)
ffffffff81729940-ffffffff81729aab: __x64_sys_landlock_add_rule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
long int __x64_sys_landlock_add_rule(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sys_ni.c (0)
Location: kernel/sys_ni.c:170
Inline: False
Direct callers:
  - arch/x86/entry/syscall_64.c:x64_sys_call
```
**Symbols:**

```
ffffffff821d1f05-ffffffff821d1f19: __x64_sys_landlock_add_rule.cold (STB_LOCAL)
ffffffff8176aee0-ffffffff8176af9c: __x64_sys_landlock_add_rule (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
