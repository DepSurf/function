# Function: <code>C_SYSC_getrusage</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long int C_SYSC_getrusage(int who, struct compat_rusage *ru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810929d0)
Location: kernel/sys.c:1648
Inline: False
Direct callers:
  - kernel/sys.c:compat_SyS_getrusage
```
**Symbols:**

```
ffffffff810929d0-ffffffff81092a4a: C_SYSC_getrusage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long int C_SYSC_getrusage(int who, struct compat_rusage *ru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff81095b60)
Location: kernel/sys.c:1648
Inline: False
Direct callers:
  - kernel/sys.c:compat_SyS_getrusage
```
**Symbols:**

```
ffffffff81095b60-ffffffff81095bda: C_SYSC_getrusage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long int C_SYSC_getrusage(int who, struct compat_rusage *ru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff8109ab50)
Location: kernel/sys.c:1649
Inline: False
Direct callers:
  - kernel/sys.c:compat_SyS_getrusage
```
**Symbols:**

```
ffffffff8109ab50-ffffffff8109abca: C_SYSC_getrusage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long int C_SYSC_getrusage(int who, struct compat_rusage *ru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff8109b3b0)
Location: kernel/sys.c:1755
Inline: False
Direct callers:
  - kernel/sys.c:compat_SyS_getrusage
```
**Symbols:**

```
ffffffff8109b3b0-ffffffff8109b43f: C_SYSC_getrusage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long int C_SYSC_getrusage(int who, struct compat_rusage *ru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810a2090)
Location: kernel/sys.c:1762
Inline: False
Direct callers:
  - kernel/sys.c:compat_SyS_getrusage
```
**Symbols:**

```
ffffffff810a2090-ffffffff810a211f: C_SYSC_getrusage (STB_LOCAL)
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
