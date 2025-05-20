# Function: <code>C_SYSC_sigaction</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long int C_SYSC_sigaction(int sig, const struct compat_old_sigaction *act, struct compat_old_sigaction *oact);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81091790)
Location: kernel/signal.c:3410
Inline: False
Direct callers:
  - kernel/signal.c:compat_SyS_sigaction
```
**Symbols:**

```
ffffffff81091790-ffffffff810918fb: C_SYSC_sigaction (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long int C_SYSC_sigaction(int sig, const struct compat_old_sigaction *act, struct compat_old_sigaction *oact);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81094900)
Location: kernel/signal.c:3413
Inline: False
Direct callers:
  - kernel/signal.c:compat_SyS_sigaction
```
**Symbols:**

```
ffffffff81094900-ffffffff81094a6d: C_SYSC_sigaction (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long int C_SYSC_sigaction(int sig, const struct compat_old_sigaction *act, struct compat_old_sigaction *oact);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81099910)
Location: kernel/signal.c:3440
Inline: False
Direct callers:
  - kernel/signal.c:compat_SyS_sigaction
```
**Symbols:**

```
ffffffff81099910-ffffffff81099a7d: C_SYSC_sigaction (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long int C_SYSC_sigaction(int sig, const struct compat_old_sigaction *act, struct compat_old_sigaction *oact);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81096960)
Location: kernel/signal.c:3495
Inline: False
Direct callers:
  - kernel/signal.c:compat_SyS_sigaction
```
**Symbols:**

```
ffffffff81096960-ffffffff81096ac6: C_SYSC_sigaction (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long int C_SYSC_sigaction(int sig, const struct compat_old_sigaction *act, struct compat_old_sigaction *oact);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8109d6f0)
Location: kernel/signal.c:3510
Inline: False
Direct callers:
  - kernel/signal.c:compat_SyS_sigaction
```
**Symbols:**

```
ffffffff8109d6f0-ffffffff8109d862: C_SYSC_sigaction (STB_LOCAL)
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
