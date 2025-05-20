# Function: <code>SyS_kexec_load</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
long int SyS_kexec_load(long int entry, long int nr_segments, long int segments, long int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kexec.c (ffffffff8110def0)
Location: kernel/kexec.c:128
Inline: True
Inline callers:
  - kernel/kexec.c:compat_SyS_kexec_load
```
**Symbols:**

```
ffffffff8110def0-ffffffff8110e100: SyS_kexec_load (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
long int SyS_kexec_load(long int entry, long int nr_segments, long int segments, long int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kexec.c (ffffffff81115b0b)
Location: kernel/kexec.c:188
Inline: True
Inline callers:
  - kernel/kexec.c:compat_SyS_kexec_load
```
**Symbols:**

```
ffffffff81115940-ffffffff81115a15: SyS_kexec_load (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
long int SyS_kexec_load(long int entry, long int nr_segments, long int segments, long int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kexec.c (ffffffff8111d22b)
Location: kernel/kexec.c:188
Inline: True
Inline callers:
  - kernel/kexec.c:compat_SyS_kexec_load
```
**Symbols:**

```
ffffffff8111d060-ffffffff8111d135: SyS_kexec_load (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
long int SyS_kexec_load(long int entry, long int nr_segments, long int segments, long int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kexec.c (ffffffff8111ee4a)
Location: kernel/kexec.c:195
Inline: True
Inline callers:
  - kernel/kexec.c:compat_SyS_kexec_load
```
**Symbols:**

```
ffffffff8111eca0-ffffffff8111ed5c: SyS_kexec_load (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
long int SyS_kexec_load(long int entry, long int nr_segments, long int segments, long int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kexec.c (ffffffff8112a5ca)
Location: kernel/kexec.c:195
Inline: True
Inline callers:
  - kernel/kexec.c:compat_SyS_kexec_load
```
**Symbols:**

```
ffffffff8112a400-ffffffff8112a4e0: SyS_kexec_load (STB_GLOBAL)
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
