# Function: <code>delay_halt_mwaitx</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void delay_halt_mwaitx(u64 unused, u64 cycles);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/delay.c (ffffffff815fd3e0)
Location: arch/x86/lib/delay.c:125
Inline: False
```
**Symbols:**

```
ffffffff815fd3e0-ffffffff815fd420: delay_halt_mwaitx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void delay_halt_mwaitx(u64 unused, u64 cycles);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/delay.c (ffffffff81622110)
Location: arch/x86/lib/delay.c:125
Inline: False
```
**Symbols:**

```
ffffffff81622110-ffffffff81622150: delay_halt_mwaitx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void delay_halt_mwaitx(u64 unused, u64 cycles);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/delay.c (ffffffff816059e0)
Location: arch/x86/lib/delay.c:125
Inline: False
```
**Symbols:**

```
ffffffff816059e0-ffffffff81605a23: delay_halt_mwaitx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void delay_halt_mwaitx(u64 unused, u64 cycles);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/delay.c (ffffffff816742d0)
Location: arch/x86/lib/delay.c:125
Inline: False
```
**Symbols:**

```
ffffffff816742d0-ffffffff81674313: delay_halt_mwaitx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void delay_halt_mwaitx(u64 unused, u64 cycles);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/delay.c (ffffffff8178e9b0)
Location: arch/x86/lib/delay.c:125
Inline: False
```
**Symbols:**

```
ffffffff8178e9b0-ffffffff8178e9ff: delay_halt_mwaitx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void delay_halt_mwaitx(u64 unused, u64 cycles);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/delay.c (ffffffff8204c310)
Location: arch/x86/lib/delay.c:125
Inline: False
```
**Symbols:**

```
ffffffff8204c310-ffffffff8204c35f: delay_halt_mwaitx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void delay_halt_mwaitx(u64 unused, u64 cycles);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/delay.c (ffffffff820cac20)
Location: arch/x86/lib/delay.c:125
Inline: False
```
**Symbols:**

```
ffffffff820cac20-ffffffff820cac6f: delay_halt_mwaitx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void delay_halt_mwaitx(u64 unused, u64 cycles);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/delay.c (ffffffff821a5460)
Location: arch/x86/lib/delay.c:125
Inline: False
```
**Symbols:**

```
ffffffff821a5460-ffffffff821a54af: delay_halt_mwaitx (STB_LOCAL)
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
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
