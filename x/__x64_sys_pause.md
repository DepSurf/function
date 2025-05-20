# Function: <code>__x64_sys_pause</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long int __x64_sys_pause();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8109c680)
Location: kernel/signal.c:3843
Inline: False
```
**Symbols:**

```
ffffffff8109c680-ffffffff8109c6c1: __x64_sys_pause (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long int __x64_sys_pause();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810a48e0)
Location: kernel/signal.c:4170
Inline: False
```
**Symbols:**

```
ffffffff810a48e0-ffffffff810a4921: __x64_sys_pause (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long int __x64_sys_pause();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810a9570)
Location: kernel/signal.c:4418
Inline: False
```
**Symbols:**

```
ffffffff810a9570-ffffffff810a95a8: __x64_sys_pause (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int __x64_sys_pause(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810afb60)
Location: kernel/signal.c:4426
Inline: False
```
**Symbols:**

```
ffffffff810afb60-ffffffff810afb98: __x64_sys_pause (STB_GLOBAL)
```
</details>
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

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
```
**Symbols:**

```
ffffffff810b43d0-ffffffff810b4428: __x64_sys_pause (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
```
**Symbols:**

```
ffffffff810c65a0-ffffffff810c65f7: __x64_sys_pause (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
```
**Symbols:**

```
ffffffff810ddfe0-ffffffff810de043: __x64_sys_pause (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
```
**Symbols:**

```
ffffffff810fe970-ffffffff810fe9d3: __x64_sys_pause (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
```
**Symbols:**

```
ffffffff8110a9e0-ffffffff8110aa43: __x64_sys_pause (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - arch/x86/entry/syscall_64.c:x64_sys_call
```
**Symbols:**

```
ffffffff81114430-ffffffff81114493: __x64_sys_pause (STB_GLOBAL)
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
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
long int __x64_sys_pause(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810a9ed0)
Location: kernel/signal.c:4426
Inline: False
```
**Symbols:**

```
ffffffff810a9ed0-ffffffff810a9f08: __x64_sys_pause (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int __x64_sys_pause(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81098880)
Location: kernel/signal.c:4426
Inline: False
```
**Symbols:**

```
ffffffff81098880-ffffffff810988b8: __x64_sys_pause (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int __x64_sys_pause(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810a9430)
Location: kernel/signal.c:4426
Inline: False
```
**Symbols:**

```
ffffffff810a9430-ffffffff810a9468: __x64_sys_pause (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int __x64_sys_pause(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b1650)
Location: kernel/signal.c:4426
Inline: False
```
**Symbols:**

```
ffffffff810b1650-ffffffff810b1688: __x64_sys_pause (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.3</code> and <code>5.4</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct pt_regs *__unused</code>
</li>
</ul>
</details>
</li>
</ul>
<b>Arch</b>
<ul>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
