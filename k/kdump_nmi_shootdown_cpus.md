# Function: <code>kdump_nmi_shootdown_cpus</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/crash.c (ffffffff8105d7af)
Location: arch/x86/kernel/crash.c:131
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/crash.c (ffffffff8105d709)
Location: arch/x86/kernel/crash.c:136
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void kdump_nmi_shootdown_cpus();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/crash.c (ffffffff81060720)
Location: arch/x86/kernel/crash.c:136
Inline: False
```
**Symbols:**

```
ffffffff81060720-ffffffff8106073c: kdump_nmi_shootdown_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void kdump_nmi_shootdown_cpus();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/crash.c (ffffffff8105f7a0)
Location: arch/x86/kernel/crash.c:137
Inline: False
```
**Symbols:**

```
ffffffff8105f7a0-ffffffff8105f7bc: kdump_nmi_shootdown_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void kdump_nmi_shootdown_cpus();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/crash.c (ffffffff810637d0)
Location: arch/x86/kernel/crash.c:137
Inline: False
```
**Symbols:**

```
ffffffff810637d0-ffffffff810637ec: kdump_nmi_shootdown_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void kdump_nmi_shootdown_cpus();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/crash.c (ffffffff81066480)
Location: arch/x86/kernel/crash.c:106
Inline: False
```
**Symbols:**

```
ffffffff81066480-ffffffff8106649c: kdump_nmi_shootdown_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void kdump_nmi_shootdown_cpus();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/crash.c (ffffffff8106c490)
Location: arch/x86/kernel/crash.c:107
Inline: False
```
**Symbols:**

```
ffffffff8106c490-ffffffff8106c4ac: kdump_nmi_shootdown_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void kdump_nmi_shootdown_cpus();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/crash.c (ffffffff81070490)
Location: arch/x86/kernel/crash.c:99
Inline: False
```
**Symbols:**

```
ffffffff81070490-ffffffff810704ac: kdump_nmi_shootdown_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void kdump_nmi_shootdown_cpus();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/crash.c (ffffffff81071490)
Location: arch/x86/kernel/crash.c:99
Inline: False
```
**Symbols:**

```
ffffffff81071490-ffffffff810714ac: kdump_nmi_shootdown_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void kdump_nmi_shootdown_cpus();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/crash.c (ffffffff81078550)
Location: arch/x86/kernel/crash.c:114
Inline: False
```
**Symbols:**

```
ffffffff81078550-ffffffff8107856c: kdump_nmi_shootdown_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void kdump_nmi_shootdown_cpus();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/crash.c (ffffffff81078550)
Location: arch/x86/kernel/crash.c:114
Inline: False
```
**Symbols:**

```
ffffffff81078550-ffffffff8107856c: kdump_nmi_shootdown_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void kdump_nmi_shootdown_cpus();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/crash.c (ffffffff81079410)
Location: arch/x86/kernel/crash.c:114
Inline: False
```
**Symbols:**

```
ffffffff81079410-ffffffff8107942c: kdump_nmi_shootdown_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void kdump_nmi_shootdown_cpus();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/crash.c (ffffffff81087470)
Location: arch/x86/kernel/crash.c:101
Inline: False
```
**Symbols:**

```
ffffffff81087470-ffffffff8108748c: kdump_nmi_shootdown_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void kdump_nmi_shootdown_cpus();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/crash.c (ffffffff81097580)
Location: arch/x86/kernel/crash.c:101
Inline: False
```
**Symbols:**

```
ffffffff81097580-ffffffff810975a2: kdump_nmi_shootdown_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void kdump_nmi_shootdown_cpus();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/crash.c (ffffffff810ada40)
Location: arch/x86/kernel/crash.c:91
Inline: False
```
**Symbols:**

```
ffffffff810ada40-ffffffff810ada62: kdump_nmi_shootdown_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void kdump_nmi_shootdown_cpus();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/crash.c (ffffffff810b0a40)
Location: arch/x86/kernel/crash.c:91
Inline: False
```
**Symbols:**

```
ffffffff810b0a40-ffffffff810b0a62: kdump_nmi_shootdown_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void kdump_nmi_shootdown_cpus();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/crash.c (ffffffff810b7ba0)
Location: arch/x86/kernel/crash.c:65
Inline: False
```
**Symbols:**

```
ffffffff810b7ba0-ffffffff810b7bc2: kdump_nmi_shootdown_cpus (STB_GLOBAL)
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
void kdump_nmi_shootdown_cpus();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/crash.c (ffffffff81070490)
Location: arch/x86/kernel/crash.c:99
Inline: False
```
**Symbols:**

```
ffffffff81070490-ffffffff810704ac: kdump_nmi_shootdown_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void kdump_nmi_shootdown_cpus();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/crash.c (ffffffff810604a0)
Location: arch/x86/kernel/crash.c:99
Inline: False
```
**Symbols:**

```
ffffffff810604a0-ffffffff810604bc: kdump_nmi_shootdown_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void kdump_nmi_shootdown_cpus();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/crash.c (ffffffff81070490)
Location: arch/x86/kernel/crash.c:99
Inline: False
```
**Symbols:**

```
ffffffff81070490-ffffffff810704ac: kdump_nmi_shootdown_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void kdump_nmi_shootdown_cpus();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/crash.c (ffffffff810724a0)
Location: arch/x86/kernel/crash.c:99
Inline: False
```
**Symbols:**

```
ffffffff810724a0-ffffffff810724bc: kdump_nmi_shootdown_cpus (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
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
