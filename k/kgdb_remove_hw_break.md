# Function: <code>kgdb_remove_hw_break</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int kgdb_remove_hw_break(long unsigned int addr, int len, enum kgdb_bptype bptype);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kgdb.c (ffffffff81061330)
Location: arch/x86/kernel/kgdb.c:292
Inline: False
```
**Symbols:**

```
ffffffff81061330-ffffffff810613a7: kgdb_remove_hw_break (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int kgdb_remove_hw_break(long unsigned int addr, int len, enum kgdb_bptype bptype);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kgdb.c (ffffffff81061160)
Location: arch/x86/kernel/kgdb.c:293
Inline: False
```
**Symbols:**

```
ffffffff81061160-ffffffff810611df: kgdb_remove_hw_break (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int kgdb_remove_hw_break(long unsigned int addr, int len, enum kgdb_bptype bptype);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kgdb.c (ffffffff81064210)
Location: arch/x86/kernel/kgdb.c:293
Inline: False
```
**Symbols:**

```
ffffffff81064210-ffffffff8106428f: kgdb_remove_hw_break (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int kgdb_remove_hw_break(long unsigned int addr, int len, enum kgdb_bptype bptype);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kgdb.c (ffffffff81063140)
Location: arch/x86/kernel/kgdb.c:293
Inline: False
```
**Symbols:**

```
ffffffff81063140-ffffffff810631bf: kgdb_remove_hw_break (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int kgdb_remove_hw_break(long unsigned int addr, int len, enum kgdb_bptype bptype);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kgdb.c (ffffffff810672c0)
Location: arch/x86/kernel/kgdb.c:293
Inline: False
```
**Symbols:**

```
ffffffff810672c0-ffffffff8106733f: kgdb_remove_hw_break (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int kgdb_remove_hw_break(long unsigned int addr, int len, enum kgdb_bptype bptype);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/kgdb.c (0)
Location: arch/x86/kernel/kgdb.c:293
Inline: False
```
**Symbols:**

```
ffffffff81069ec0-ffffffff81069f32: kgdb_remove_hw_break (STB_LOCAL)
ffffffff8106a681-ffffffff8106a698: kgdb_remove_hw_break.cold.9 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int kgdb_remove_hw_break(long unsigned int addr, int len, enum kgdb_bptype bptype);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/kgdb.c (0)
Location: arch/x86/kernel/kgdb.c:293
Inline: False
```
**Symbols:**

```
ffffffff8106fc50-ffffffff8106fcc2: kgdb_remove_hw_break (STB_LOCAL)
ffffffff81070411-ffffffff81070428: kgdb_remove_hw_break.cold.9 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int kgdb_remove_hw_break(long unsigned int addr, int len, enum kgdb_bptype bptype);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/kgdb.c (0)
Location: arch/x86/kernel/kgdb.c:276
Inline: False
```
**Symbols:**

```
ffffffff81073ce0-ffffffff81073d4a: kgdb_remove_hw_break (STB_LOCAL)
ffffffff8107445e-ffffffff81074475: kgdb_remove_hw_break.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int kgdb_remove_hw_break(long unsigned int addr, int len, enum kgdb_bptype bptype);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/kgdb.c (0)
Location: arch/x86/kernel/kgdb.c:276
Inline: False
```
**Symbols:**

```
ffffffff81074ca0-ffffffff81074d0a: kgdb_remove_hw_break (STB_LOCAL)
ffffffff8107542e-ffffffff81075445: kgdb_remove_hw_break.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int kgdb_remove_hw_break(long unsigned int addr, int len, enum kgdb_bptype bptype);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/kgdb.c (0)
Location: arch/x86/kernel/kgdb.c:276
Inline: False
```
**Symbols:**

```
ffffffff8107bcf0-ffffffff8107bd5a: kgdb_remove_hw_break (STB_LOCAL)
ffffffff8107c63a-ffffffff8107c651: kgdb_remove_hw_break.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int kgdb_remove_hw_break(long unsigned int addr, int len, enum kgdb_bptype bptype);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/kgdb.c (0)
Location: arch/x86/kernel/kgdb.c:276
Inline: False
```
**Symbols:**

```
ffffffff8107bbe0-ffffffff8107bc4a: kgdb_remove_hw_break (STB_LOCAL)
ffffffff81bd7c23-ffffffff81bd7c3a: kgdb_remove_hw_break.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int kgdb_remove_hw_break(long unsigned int addr, int len, enum kgdb_bptype bptype);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/kgdb.c (0)
Location: arch/x86/kernel/kgdb.c:276
Inline: False
```
**Symbols:**

```
ffffffff8107cd90-ffffffff8107cdfa: kgdb_remove_hw_break (STB_LOCAL)
ffffffff81bc9bd6-ffffffff81bc9bed: kgdb_remove_hw_break.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int kgdb_remove_hw_break(long unsigned int addr, int len, enum kgdb_bptype bptype);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/kgdb.c (0)
Location: arch/x86/kernel/kgdb.c:276
Inline: False
```
**Symbols:**

```
ffffffff8108b0a0-ffffffff8108b168: kgdb_remove_hw_break (STB_LOCAL)
ffffffff81c9ea8a-ffffffff81c9eaa1: kgdb_remove_hw_break.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int kgdb_remove_hw_break(long unsigned int addr, int len, enum kgdb_bptype bptype);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/kgdb.c (0)
Location: arch/x86/kernel/kgdb.c:276
Inline: False
```
**Symbols:**

```
ffffffff8109b890-ffffffff8109b951: kgdb_remove_hw_break (STB_LOCAL)
ffffffff81e4dec3-ffffffff81e4ded7: kgdb_remove_hw_break.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int kgdb_remove_hw_break(long unsigned int addr, int len, enum kgdb_bptype bptype);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kgdb.c (ffffffff810b2580)
Location: arch/x86/kernel/kgdb.c:276
Inline: False
```
**Symbols:**

```
ffffffff810b2580-ffffffff810b2650: kgdb_remove_hw_break (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int kgdb_remove_hw_break(long unsigned int addr, int len, enum kgdb_bptype bptype);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kgdb.c (ffffffff810b5690)
Location: arch/x86/kernel/kgdb.c:276
Inline: False
```
**Symbols:**

```
ffffffff810b5690-ffffffff810b5760: kgdb_remove_hw_break (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int kgdb_remove_hw_break(long unsigned int addr, int len, enum kgdb_bptype bptype);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kgdb.c (ffffffff810bcad0)
Location: arch/x86/kernel/kgdb.c:276
Inline: False
```
**Symbols:**

```
ffffffff810bcad0-ffffffff810bcba0: kgdb_remove_hw_break (STB_LOCAL)
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int kgdb_remove_hw_break(long unsigned int addr, int len, enum kgdb_bptype bptype);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/kgdb.c (0)
Location: arch/x86/kernel/kgdb.c:276
Inline: False
```
**Symbols:**

```
ffffffff81073ca0-ffffffff81073d0a: kgdb_remove_hw_break (STB_LOCAL)
ffffffff8107442e-ffffffff81074445: kgdb_remove_hw_break.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int kgdb_remove_hw_break(long unsigned int addr, int len, enum kgdb_bptype bptype);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/kgdb.c (0)
Location: arch/x86/kernel/kgdb.c:276
Inline: False
```
**Symbols:**

```
ffffffff81063cf0-ffffffff81063d5a: kgdb_remove_hw_break (STB_LOCAL)
ffffffff8106445e-ffffffff81064475: kgdb_remove_hw_break.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int kgdb_remove_hw_break(long unsigned int addr, int len, enum kgdb_bptype bptype);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/kgdb.c (0)
Location: arch/x86/kernel/kgdb.c:276
Inline: False
```
**Symbols:**

```
ffffffff81073c50-ffffffff81073cba: kgdb_remove_hw_break (STB_LOCAL)
ffffffff810743de-ffffffff810743f5: kgdb_remove_hw_break.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int kgdb_remove_hw_break(long unsigned int addr, int len, enum kgdb_bptype bptype);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/kgdb.c (0)
Location: arch/x86/kernel/kgdb.c:276
Inline: False
```
**Symbols:**

```
ffffffff81075cb0-ffffffff81075d1a: kgdb_remove_hw_break (STB_LOCAL)
ffffffff8107643e-ffffffff81076455: kgdb_remove_hw_break.cold (STB_LOCAL)
```
</details>
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
