# Function: <code>sys_rt_sigreturn</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long int sys_rt_sigreturn();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/signal.c (ffffffff8102ecb0)
Location: arch/x86/kernel/signal.c:568
Inline: False
```
**Symbols:**

```
ffffffff8102ecb0-ffffffff8102ed88: sys_rt_sigreturn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long int sys_rt_sigreturn();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/signal.c (ffffffff8102dce0)
Location: arch/x86/kernel/signal.c:633
Inline: False
```
**Symbols:**

```
ffffffff8102dce0-ffffffff8102ddc4: sys_rt_sigreturn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long int sys_rt_sigreturn();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/signal.c (ffffffff8102db40)
Location: arch/x86/kernel/signal.c:634
Inline: False
```
**Symbols:**

```
ffffffff8102db40-ffffffff8102dc24: sys_rt_sigreturn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long int sys_rt_sigreturn();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/signal.c (ffffffff8102bdc0)
Location: arch/x86/kernel/signal.c:635
Inline: False
```
**Symbols:**

```
ffffffff8102bdc0-ffffffff8102bea4: sys_rt_sigreturn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long int sys_rt_sigreturn();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/signal.c (ffffffff8102cae0)
Location: arch/x86/kernel/signal.c:636
Inline: False
```
**Symbols:**

```
ffffffff8102cae0-ffffffff8102cbc5: sys_rt_sigreturn (STB_GLOBAL)
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
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int sys_rt_sigreturn(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm/kernel/signal.c (c030e61c)
Location: arch/arm/kernel/signal.c:254
Inline: False
```
**Symbols:**

```
c030e61c-c030e6ac: sys_rt_sigreturn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int sys_rt_sigreturn();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/powerpc/kernel/signal_64.c (c000000000033f00)
Location: arch/powerpc/kernel/signal_64.c:704
Inline: False
```
**Symbols:**

```
c000000000033f00-c0000000000342d8: sys_rt_sigreturn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long int sys_rt_sigreturn();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/riscv/kernel/signal.c (ffffffe0000b6854)
Location: arch/riscv/kernel/signal.c:93
Inline: False
```
**Symbols:**

```
ffffffe0000b6854-ffffffe0000b69e8: sys_rt_sigreturn (STB_GLOBAL)
```
</details>
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
<b>Arch</b>
<ul>
</ul>
