# Function: <code>__ia32_sys_landlock_restrict_self</code>

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
long int __ia32_sys_landlock_restrict_self(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff815376b0)
Location: kernel/sys_ni.c:273
Inline: False
```
**Symbols:**

```
ffffffff815376b0-ffffffff815377ce: __ia32_sys_landlock_restrict_self (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
long int __ia32_sys_landlock_restrict_self(const struct pt_regs *__unused);
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
ffffffff81cd6b4f-ffffffff81cd6b63: __ia32_sys_landlock_restrict_self.cold (STB_LOCAL)
ffffffff81595e80-ffffffff81595fab: __ia32_sys_landlock_restrict_self (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
long int __ia32_sys_landlock_restrict_self(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sys_ni.c (0)
Location: kernel/sys_ni.c:274
Inline: False
```
**Symbols:**

```
ffffffff81e89a91-ffffffff81e89aa5: __ia32_sys_landlock_restrict_self.cold (STB_LOCAL)
ffffffff816381d0-ffffffff81638318: __ia32_sys_landlock_restrict_self (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
long int __ia32_sys_landlock_restrict_self(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sys_ni.c (0)
Location: kernel/sys_ni.c:274
Inline: False
```
**Symbols:**

```
ffffffff82074eac-ffffffff82074ec0: __ia32_sys_landlock_restrict_self.cold (STB_LOCAL)
ffffffff816ef330-ffffffff816ef478: __ia32_sys_landlock_restrict_self (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
long int __ia32_sys_landlock_restrict_self(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sys_ni.c (0)
Location: kernel/sys_ni.c:170
Inline: False
```
**Symbols:**

```
ffffffff820f4a57-ffffffff820f4a6b: __ia32_sys_landlock_restrict_self.cold (STB_LOCAL)
ffffffff817297e0-ffffffff81729922: __ia32_sys_landlock_restrict_self (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
long int __ia32_sys_landlock_restrict_self(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sys_ni.c (0)
Location: kernel/sys_ni.c:171
Inline: False
Direct callers:
  - arch/x86/entry/syscall_32.c:ia32_sys_call
```
**Symbols:**

```
ffffffff821d1ef1-ffffffff821d1f05: __ia32_sys_landlock_restrict_self.cold (STB_LOCAL)
ffffffff8176ad80-ffffffff8176aec5: __ia32_sys_landlock_restrict_self (STB_GLOBAL)
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
