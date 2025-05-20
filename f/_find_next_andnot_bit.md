# Function: <code>_find_next_andnot_bit</code>

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
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long unsigned int _find_next_andnot_bit(const long unsigned int *addr1, const long unsigned int *addr2, long unsigned int nbits, long unsigned int start);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/find_bit.c (ffffffff817d6ff0)
Location: lib/find_bit.c:168
Inline: False
Direct callers:
  - kernel/sched/core.c:__sched_core_flip
```
**Symbols:**

```
ffffffff817d6ff0-ffffffff817d7077: _find_next_andnot_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long unsigned int _find_next_andnot_bit(const long unsigned int *addr1, const long unsigned int *addr2, long unsigned int nbits, long unsigned int start);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/find_bit.c (ffffffff81816020)
Location: lib/find_bit.c:177
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:smp_kick_mwait_play_dead
  - kernel/sched/core.c:__sched_core_flip
```
**Symbols:**

```
ffffffff81816020-ffffffff818160a4: _find_next_andnot_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long unsigned int _find_next_andnot_bit(const long unsigned int *addr1, const long unsigned int *addr2, long unsigned int nbits, long unsigned int start);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/find_bit.c (ffffffff8185b160)
Location: lib/find_bit.c:177
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:smp_kick_mwait_play_dead
  - kernel/sched/core.c:__sched_core_flip
```
**Symbols:**

```
ffffffff8185b160-ffffffff8185b1e4: _find_next_andnot_bit (STB_GLOBAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
