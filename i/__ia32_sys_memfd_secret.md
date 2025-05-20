# Function: <code>__ia32_sys_memfd_secret</code>

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
In <code>5.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
long int __ia32_sys_memfd_secret(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sys_ni.c (0)
Location: kernel/sys_ni.c:358
Inline: False
```
**Symbols:**

```
ffffffff81cc3558-ffffffff81cc356c: __ia32_sys_memfd_secret.cold (STB_LOCAL)
ffffffff81366540-ffffffff813665f3: __ia32_sys_memfd_secret (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
long int __ia32_sys_memfd_secret(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sys_ni.c (0)
Location: kernel/sys_ni.c:361
Inline: False
```
**Symbols:**

```
ffffffff81e75b9a-ffffffff81e75baf: __ia32_sys_memfd_secret.cold (STB_LOCAL)
ffffffff813e3600-ffffffff813e36b9: __ia32_sys_memfd_secret (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
long int __ia32_sys_memfd_secret(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sys_ni.c (0)
Location: kernel/sys_ni.c:361
Inline: False
```
**Symbols:**

```
ffffffff82068535-ffffffff8206854a: __ia32_sys_memfd_secret.cold (STB_LOCAL)
ffffffff8146afc0-ffffffff8146b079: __ia32_sys_memfd_secret (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
long int __ia32_sys_memfd_secret(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sys_ni.c (0)
Location: kernel/sys_ni.c:254
Inline: False
```
**Symbols:**

```
ffffffff820e7e72-ffffffff820e7e87: __ia32_sys_memfd_secret.cold (STB_LOCAL)
ffffffff814a00a0-ffffffff814a0156: __ia32_sys_memfd_secret (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
long int __ia32_sys_memfd_secret(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sys_ni.c (0)
Location: kernel/sys_ni.c:272
Inline: False
Direct callers:
  - arch/x86/entry/syscall_32.c:ia32_sys_call
```
**Symbols:**

```
ffffffff821c4b46-ffffffff821c4b5b: __ia32_sys_memfd_secret.cold (STB_LOCAL)
ffffffff814cf5d0-ffffffff814cf686: __ia32_sys_memfd_secret (STB_GLOBAL)
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
