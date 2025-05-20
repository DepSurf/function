# Function: <code>compat_SyS_select</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
long int compat_SyS_select(long int n, long int inp, long int outp, long int exp, long int tvp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/compat.c (ffffffff812653a0)
Location: fs/compat.c:1305
Inline: True
Inline callers:
  - fs/compat.c:compat_SyS_old_select
```
**Symbols:**

```
ffffffff812653a0-ffffffff812654a1: compat_SyS_select (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
long int compat_SyS_select(long int n, long int inp, long int outp, long int exp, long int tvp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/compat.c (ffffffff8129181c)
Location: fs/compat.c:1308
Inline: True
Inline callers:
  - fs/compat.c:compat_SyS_old_select
```
**Symbols:**

```
ffffffff812916c0-ffffffff812917c1: compat_SyS_select (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
long int compat_SyS_select(long int n, long int inp, long int outp, long int exp, long int tvp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/compat.c (ffffffff812a65ac)
Location: fs/compat.c:1219
Inline: True
Inline callers:
  - fs/compat.c:compat_SyS_old_select
```
**Symbols:**

```
ffffffff812a6450-ffffffff812a6551: compat_SyS_select (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
long int compat_SyS_select(long int n, long int inp, long int outp, long int exp, long int tvp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff8126a7a6)
Location: fs/select.c:1266
Inline: True
Inline callers:
  - fs/select.c:compat_SyS_old_select
```
**Symbols:**

```
ffffffff8126a650-ffffffff8126a753: compat_SyS_select (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
long int compat_SyS_select(long int n, long int inp, long int outp, long int exp, long int tvp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff8128d046)
Location: fs/select.c:1257
Inline: True
Inline callers:
  - fs/select.c:compat_SyS_old_select
```
**Symbols:**

```
ffffffff8128cef0-ffffffff8128cff3: compat_SyS_select (STB_GLOBAL)
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
