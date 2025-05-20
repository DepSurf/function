# Function: <code>compat_SyS_sigaltstack</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
long int compat_SyS_sigaltstack(long int uss_ptr, long int uoss_ptr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810919f0)
Location: kernel/signal.c:3176
Inline: True
Inline callers:
  - kernel/signal.c:compat_restore_altstack
```
**Symbols:**

```
ffffffff810919f0-ffffffff81091b69: compat_SyS_sigaltstack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
long int compat_SyS_sigaltstack(long int uss_ptr, long int uoss_ptr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81094cdf)
Location: kernel/signal.c:3179
Inline: True
Inline callers:
  - kernel/signal.c:compat_restore_altstack
```
**Symbols:**

```
ffffffff81094b60-ffffffff81094cbc: compat_SyS_sigaltstack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
long int compat_SyS_sigaltstack(long int uss_ptr, long int uoss_ptr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81099cef)
Location: kernel/signal.c:3199
Inline: True
Inline callers:
  - kernel/signal.c:compat_restore_altstack
```
**Symbols:**

```
ffffffff81099b70-ffffffff81099ccc: compat_SyS_sigaltstack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
long int compat_SyS_sigaltstack(long int uss_ptr, long int uoss_ptr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81096ddd)
Location: kernel/signal.c:3244
Inline: True
Inline callers:
  - kernel/signal.c:compat_restore_altstack
```
**Symbols:**

```
ffffffff81096cc0-ffffffff81096dbe: compat_SyS_sigaltstack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
long int compat_SyS_sigaltstack(long int uss_ptr, long int uoss_ptr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8109db7d)
Location: kernel/signal.c:3265
Inline: True
Inline callers:
  - kernel/signal.c:compat_restore_altstack
```
**Symbols:**

```
ffffffff8109da60-ffffffff8109db5e: compat_SyS_sigaltstack (STB_GLOBAL)
```
</details>
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
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
</ul>
